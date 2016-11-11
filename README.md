<p align="center">
  <img src="https://s3.amazonaws.com/alaunus-web-2.0-us-east-data/wp-content/uploads/2015/06/logo_1500x571.png" alt="Alaunus: API Documentation" width="226">
</p>

<p align="center">Slate helps you create beautiful, intelligent, responsive API documentation.</p>

<p align="center"><img src="https://dl.dropboxusercontent.com/u/95847291/github%20images/slate/slate_screenshot_new.png" width=700 alt="Screenshot of Example Documentation created with Slate"></p>

<p align="center"><em>The example above was created with Slate. Check it out at <a href="https://lord.github.io/slate">lord.github.io/slate</a>.</em></p>

Features
------------

* **Clean, intuaitive design** — The description of Alaunus API is on the left side of the documentation, and all the code examples are on the right side. Alaunus API is responsive, so it looks great on tablets, phones, and even in print.

* **Everything on a single page** — Gone are the days when your users had to search through a million pages to find what they wanted. The entire documentation is on a single page. We haven't sacrificed linkability, though. As you scroll, your browser's hash will update to the nearest header, so linking to a particular point in the documentation is still natural and easy.

* **Mix of Markdown and erb** — The Alaunus API is a mix of Markdown and erb, in order to create simple new pages, it is possible to do it with Markdown, the more complex and dynamic ones are written in erb.

* **Write code samples in multiple languages** — You can easily put in tabs to switch between the languages. In your document, you'll distinguish different languages by specifying the language name at the top of each code block, just like with Github Flavored Markdown.

* **Out-of-the-box syntax highlighting** for [almost 100 languages](http://rouge.jneen.net/), no configuration required.

* **Automatic, smoothly scrolling table of contents** on the far left of the page. As you scroll, it displays your current position in the document. It's fast, too.

Getting Started with Slate
------------------------------

### Prerequisites

You're going to need:

 - **Linux or OS X** — Windows may work, but is unsupported.
 - **Ruby, version 2.0 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Fork this repository on Github.
2. Clone *your forked repository* (not our original one) to your hard drive with `git clone https://github.com/YOURUSERNAME/slate.git`
3. `cd slate`
4. Initialize and start Slate. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567. Whoa! That was fast!

Now that Slate is all set up on your machine, you'll probably want to learn more about [editing Slate markdown](https://github.com/lord/slate/wiki/Markdown-Syntax), or [how to publish your docs](https://github.com/lord/slate/wiki/Deploying-Slate).

If you'd prefer to use Docker, instructions are available [in the wiki](https://github.com/lord/slate/wiki/Docker).

Companies Using Slate
---------------------------------

* [NASA](https://api.nasa.gov)
* [IBM Cloudant](https://docs.cloudant.com/api.html)
* [Travis-CI](https://docs.travis-ci.com/api/)
* [Mozilla](http://mozilla.github.io/localForage/)
* [Appium](http://appium.io/slate/en/master)
* [Dwolla](https://docs.dwolla.com/)
* [Clearbit](https://clearbit.com/docs)
* [Coinbase](https://developers.coinbase.com/api)
* [Parrot Drones](http://developer.parrot.com/docs/bebop/)
* [Fidor Bank](http://docs.fidor.de/)

You can view more in [the list on the wiki](https://github.com/lord/slate/wiki/Slate-in-the-Wild).

Need Help? Found a bug?
--------------------

[Submit an issue](https://github.com/lord/slate/issues) to the Slate Github if you need any help. And, of course, feel free to submit pull requests with bug fixes or changes.

Contributors
--------------------

Slate was built by [Robert Lord](https://lord.io) while interning at [TripIt](https://www.tripit.com/).

Thanks to the following people who have submitted major pull requests:

- [@chrissrogers](https://github.com/chrissrogers)
- [@bootstraponline](https://github.com/bootstraponline)
- [@realityking](https://github.com/realityking)
- [@cvkef](https://github.com/cvkef)

Also, thanks to [Sauce Labs](http://saucelabs.com) for helping sponsor the project.

Special Thanks
--------------------
- [Middleman](https://github.com/middleman/middleman)
- [jquery.tocify.js](https://github.com/gfranko/jquery.tocify.js)
- [middleman-syntax](https://github.com/middleman/middleman-syntax)
- [middleman-gh-pages](https://github.com/edgecase/middleman-gh-pages)
- [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
