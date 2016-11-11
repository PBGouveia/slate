---
title: API Alaunus

language_tabs:
  - shell: Curl

toc_footers:
  - <a href='https://alaunus.com/contact/' target="_blank">Sign Up for a Developer Key</a>
  - <a href='https://alaunus.com' target="_blank">Access Alaunus Website</a>

includes:
  - filej1
  - filej2

search: true
---

# Introduction

## Overview

This writeup is a guide on how to write urls to make backend calls to the Alaunus API. 
In most cases we will be using the development base url.

* Development base url: <a href='https://api-dev.alaunus.com' target="_blank">https://api-dev.alaunus.com</a>
* Test base url: <a href='https://api-test.alaunus.com' target="_blank">https://api-test.alaunus.com</a>
* Production base url: <a href='https://api.alaunus.com' target="_blank">https://api.alaunus.com</a>

## Collections

A "collection" is a reference to a specific set of documents in the database. 
A valid collection is exactly one of the following values:
accounts, clients, contacts, conversations, devices, events, 
invoices, payments, payrolls, payrolls-users, patients, patients-progressnotes, 
punchcards, tickets, users, users-activities, users-notes

## Documents

A "document" is one (of possibly many) results of a backend call. 
For example, a call to the patients collection may return one or 
many patient documents. Documents are defined using the JSON (javascript 
object notation) format. For more information on JSON, check out 
this wikipedia article: <a href='https://en.wikipedia.org/wiki/JSON' target="_blank">https://en.wikipedia.org/wiki/JSON</a>

> Example of a JSON object:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "isAlive": true,
  "age": 25,
  "height_cm": 167.6,
  "address": {
    "streetAddress": {
       "street": "21 2nd Street",
       "extra": "Apartment 302"
    },
    "city": "New York",
    "state": "NY",
    "postalCode": "10021-3100"
  },
  "phoneNumbers": [
    {
      "type": "home",
      "number": "212 555-1234"
    },
    {
      "type": "office",
      "number": "646 555-4567"
    }
  ],
  "children": [],
  "spouse": null
}
```

### Fields

A "field" is an element/member of a document. A field must be set to some value. A list of acceptable value types is listed below.
 
Using the example on the right, the following are all fields of the JSON object:

* firstName, 
* lastName, 
* age, 
* address, 
* phoneNumbers, 
* ...

The fields of the address object are:

* streetAddress, 
* city, 
* state, 
* postalCode

For the purposes of the Alaunus API, the fields of the phoneNumbers array are (even though they are wrapped in objects):

* type, 
* number

If we want to specify a field within an object or array, we can do so by using dot notation. 
Dot notation separates the different levels that a field might exist at.

<aside class="success">Example 1:<br>If we want to specify the street field within the streetAddress object, we can do so like this:<br>address.streetAddress.street</aside>
<aside class="success">Example 2:<br>If we want to specify the number field within the phoneNumbers array, we can do so like this:<br>phoneNumbers.number</aside>

This is not standard dot notation. 
Array fields aren't normally accessed this way in javascript, 
but for the purposes of the Alaunus API, we reference them this way.

## Values

A "value" is what a field is set to. 
A values can be exactly one of the following types in the table below.

<aside class="warning">Warning: There are certain special characters that can exist in a string type such as the plus sign (+) that can't be entered in the url in the normal way. Special characters must be encoded in order to use them in the url. For example, the plus sign gets encoded to %2B. This website is useful for encoding and decoding urls: <a href='http://www.freeformatter.com/url-encoder.html' target="_blank">http://www.freeformatter.com/url-encoder.html</a></aside>

Type | Examples | Notes
---- | -------- | -----
id | "542d8675e59911df228b45a4" | a 24-character (hexadecimal) reference to a document in the database wrapped in quotes
string | "hello there", "21 Jump Street" | any number of character wrapped in quotes
boolean | true, false |
integer | 493, 0, -81
float | 3.14159, -0.1234
datetime | "2014-07-01-01T13:01:00.201Z" | year-month-day hour:minute:second wrapped in quotes
date | "2014-07-01" | year-month-day wrapped in quotes
subdocument | {"field":value} | a subdocument is a javascript object denoted and wrapped by squiggly brackets
subdocuments | [{"field":value}] | a subdocuments is an array of javascript objects denoted and wrapped by square brackets
file | "542d8675e59911df228b45a4" | essentially the same as an id, except it references file storage instead of the database
timestamp | | unused
array | | unused
hash | | unused
MongoCode | | unused

# Authentication

> To authorize, use this code:

```ruby
require 'Kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
```

> Make sure to replace `meowmeowmeow` with your API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

# Error

<aside class="notice">The Alaunus API uses the following error codes:</aside>


Error | Short | Description
----- | ----- | -----------
200 | OK | Response to a successful GET, PUT, PATCH or DELETE
201 | Created | Response to a POST that results in a creation
204 | No Content | Response to a successful, but no results returned
400 | Bad Request | The request is malformed, such as if the body does not parse
401 | Unauthorized | When no or invalid authentication details are provided
403 | Forbidden | Credentials still do not grant the client permission to access the resource
404 | Not Found | A non-existent resource was requested
405 | Method Not Allowed | HTTP method is being requested that isn't allowed
409 | Request Error | This operation is invalid for this item. See response body for details.
422 | Unprocessable Entity | Used for validation errors
500 | Internal Server Error | See response body for details
