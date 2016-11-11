{
    "name": "accounts",
    "documentationhide": false,
    "attrs": {
        "_id": {
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default ID"
                }
            },
            "manditory": {
                "fields": true,
                "conditions": {
                    "type": "Function",
                    "function": "account",
                    "documentation": {
                        "description": "Conditons to be mandatory"
                    }
                },
                "documentation": {
                    "description": "If it is manditory or not"
                }
            },
            "documentation": {
                "description": "This contains the account id number",
                "color": "red",
                "notice": "This is a notice example",
                "warning": "This is a warning example",
                "success": "This is a success example",
                "hide": false
            }
        },
        "_account": {
            "manditory": false,
            "documentation": {
                "description": "",
                "color": "red",
                "hide": true
            }
        },
        "_created_date": {
            "permissions": {
                "fields": true,
                "documentation": {
                    "description": "Permissions for the _created_date",
                    "color": "red",
                    "hide": false
                }
            },
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default _created_date",
                    "color": "red",
                    "hide": false
                }
            },
            "documentation": {
                "description": "This contains the created date",
                "color": "red",
                "hide": false
            }
        },
        "_demo": {
            "type": "boolean",
            "permissions": {
                "fields": true,
                "conditions": true
            },
            "default": {
                "fields": true
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "ext_id": {
            "type": "string",
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                },
                "documentation": {
                    "description": "External ID permissions"
                }
            },
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default external ID"
                }
            },
            "documentation": {
                "description": "Contains the external id",
                "color": "red",
                "hide": false
            }
        },
        "email": {
            "type": "string",
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                },
                "documentation": {
                    "description": "Email permissions"
                }
            },
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default email"
                }
            },
            "documentation": {
                "description": "Retrieves the email data",
                "color": "red",
                "hide": false
            }
        },
        "website": {
            "type": "string",
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                }
            },
            "default": {
                "fields": true
            },
            "documentation": {
                "description": "Contains the company's website",
                "color": "red",
                "hide": false
            }
        },
        "hst_number": {
            "type": "string",
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                },
                "documentation": {
                    "description": "HST number permissions"
                }
            },
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default HST number"
                }
            },
            "documentation": {
                "description": "Contains the HST number",
                "color": "red",
                "hide": false
            }
        },
        "active": {
            "type": "integer",
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                },
                "documentation": {
                    "description": "Permissions on the active"
                }
            },
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default option"
                }
            },
            "events": {
                "insert": {
                    "default": 1
                },
                "documentation": {
                    "description": "The events for the activation"
                }
            },
            "documentation": {
                "description": "If the account is active or not",
                "color": "red",
                "hide": false
            }
        },
        "photo": {
            "type": "file",
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                }
            },
            "default": {
                "fields": true
            },
            "documentation": {
                "description": "Photo",
                "color": "red",
                "hide": true
            }
        },
        "departments": {
            "type": "subdocuments",
            "permissions": {
                "documents": {
                    "delete": true
                }
            },
            "subdocument": {
                "code": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "color": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                }
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "events_types": {
            "type": "subdocuments",
            "permissions": {
                "documents": {
                    "delete": true
                }
            },
            "subdocument": {
                "code": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "color": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                }
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "name": {
            "type": "subdocument",
            "subdocument": {
                "title": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Title permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default title"
                        }
                    },
                    "documentation": {
                        "description": "Name's title"
                    }
                },
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions on the label"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default label"
                        }
                    },
                    "documentation": {
                        "description": "Name's label"
                    }
                },
                "documentation": {
                    "description": "Subdocument with title and label"
                }
            },
            "documentation": {
                "description": "Name of the company",
                "color": "red",
                "hide": false
            }
        },
        "logo": {
            "type": "file",
            "reference": {
                "type": "referenceOne",
                "collection": "files"
            },
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                },
                "documentation": {
                    "description": "Permissions on the logo"
                }
            },
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default logo"
                }
            },
            "documentation": {
                "description": "Company logo",
                "color": "red",
                "hide": false
            }
        },
        "telephony": {
            "type": "subdocument",
            "subdocument": {
                "account_sid": {
                    "type": "string"
                },
                "auth_token": {
                    "type": "string"
                },
                "number": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Telephony number"
                    }
                },
                "errors": {
                    "type": "subdocument",
                    "subdocument": {
                        "redirect": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    },
                    "documentation": {
                        "description": "Telephony errors"
                    }
                },
                "documentation": {
                    "description": "Subdocument with account_sid, auth_token, number and errors"
                }
            },
            "documentation": {
                "description": "Contains the telephony information, like the authentication token, errors and others",
                "color": "red",
                "hide": false
            }
        },
        "chron": {
            "type": "subdocument",
            "subdocument": {
                "invoices": {
                    "type": "subdocument",
                    "subdocument": {
                        "biweekly_start_date": {
                            "type": "datetime",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        },
                        "last_run_date": {
                            "type": "datetime",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    }
                },
                "events": {
                    "type": "subdocument",
                    "subdocument": {
                        "last_run_date": {
                            "type": "datetime",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    }
                },
                "payrolls": {
                    "type": "subdocument",
                    "subdocument": {
                        "biweekly_start_date": {
                            "type": "datetime",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        },
                        "last_run_date": {
                            "type": "datetime",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    }
                },
                "users": {
                    "type": "subdocument",
                    "subdocument": {
                        "last_run_date": {
                            "type": "datetime",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    }
                },
                "queue": {
                    "type": "subdocument",
                    "subdocument": {
                        "last_run_date": {
                            "type": "datetime",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    }
                }
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "policy": {
            "type": "file",
            "reference": {
                "type": "referenceOne",
                "collection": "files"
            },
            "permissions": {
                "fields": true,
                "conditions": true,
                "sort": true,
                "documents": {
                    "insert": true,
                    "update": true,
                    "delete": true
                },
                "documentation": {
                    "description": "Permissions of the policy"
                }
            },
            "default": {
                "fields": true,
                "documentation": {
                    "description": "Default policy"
                }
            },
            "documentation": {
                "description": "The company's policy",
                "color": "red",
                "hide": false
            }
        },
        "settings": {
            "type": "subdocument",
            "subdocument": {
                "timezone": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "timezone",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Timezone options on the settings"
                    }
                },
                "time_format": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "time_format",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Time format options on the settings"
                    }
                },
                "new_user_showtime": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Showtime of the new user on the settings"
                    }
                },
                "currency": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "currency",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Currency settings"
                    }
                },
                "country": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "country",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Country settings"
                    }
                },
                "state": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "state",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "State settings"
                    }
                },
                "datetime_format": {
                    "type": "id",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Datetime format settings"
                    }
                },
                "language": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "language",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Language settings"
                    }
                },
                "office_hours": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "monday": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "start": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "end": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                }
                            }
                        },
                        "tuesday": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "start": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "end": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                }
                            }
                        },
                        "wednesday": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "start": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "end": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                }
                            }
                        },
                        "thursday": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "start": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "end": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                }
                            }
                        },
                        "friday": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "start": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "end": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                }
                            }
                        },
                        "saturday": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "start": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "end": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                }
                            }
                        },
                        "sunday": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "start": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "end": {
                                    "type": "integer",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                }
                            }
                        },
                        "after_hours_alert": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with the days of the week and the after hours alert"
                        }
                    },
                    "documentation": {
                        "description": "Office hours on different days settings"
                    }
                },
                "phone_dialer": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "phone_dialer",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Phone dialer settings"
                    }
                },
                "stat_holiday_multiplier": {
                    "type": "float",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "The multiplier for statutory holidays settings"
                    }
                },
                "geolocation_radius": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Geolocation radius settings"
                    }
                },
                "documentation": {
                    "description": "Subdocument with timezone, time_format, new_user_showtime, currency, country, state, datetime_format, language, office_hours, phone_dialer, stat_holiday_multiplier and geolocation_radius"
                }
            },
            "documentation": {
                "description": "Contains settings like the timezone, currency used, country, language and others",
                "color": "red",
                "hide": false
            }
        },
        "role_settings": {
            "type": "subdocument",
            "subdocument": {
                "executive_role": {
                    "type": "id",
                    "reference": {
                        "type": "referenceOne",
                        "collection": "accounts.roles"
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Executive role permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default executive role"
                        }
                    },
                    "documentation": {
                        "description": "Executive role settings"
                    }
                },
                "executive_user": {
                    "type": "id",
                    "reference": {
                        "type": "referenceOne",
                        "collection": "users"
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Executive user permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default exective user"
                        }
                    },
                    "documentation": {
                        "description": "Executive user settings"
                    }
                },
                "documentation": {
                    "description": "Subdocument with executiver user and role"
                }
            },
            "documentation": {
                "description": "This contains the settings for each role inside the company",
                "color": "red",
                "hide": false
            }
        },
        "invoice_settings": {
            "type": "subdocument",
            "subdocument": {
                "referral": {
                    "type": "id",
                    "reference": {
                        "type": "referenceOne",
                        "collection": "contacts",
                        "documentation": {
                            "description": "Referral reference"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Referral permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default referral"
                        }
                    },
                    "documentation": {
                        "description": "Reference contact"
                    }
                },
                "sales_rep": {
                    "type": "id",
                    "reference": {
                        "type": "referenceOne",
                        "collection": "accounts.sales_reps",
                        "documentation": {
                            "description": "Sales rep reference"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Sales rep permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default sales rep"
                        }
                    },
                    "documentation": {
                        "description": "Sales representative"
                    }
                },
                "documentation": {
                    "description": "Subdocument with referral and sales_rep"
                }
            },
            "documentation": {
                "description": "Contains all the invoice settings, like the sales rep for example.",
                "color": "red",
                "hide": false
            }
        },
        "billing_settings": {
            "type": "subdocument",
            "subdocument": {
                "term": {
                    "type": "id",
                    "reference": {
                        "type": "referenceOne",
                        "collection": "accounts.terms"
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions on the term"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default term"
                        }
                    },
                    "documentation": {
                        "description": "Term of the billing"
                    }
                },
                "header_message": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions on header message"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default header message"
                        }
                    },
                    "documentation": {
                        "description": "Message on header of the billing"
                    }
                },
                "footer_message": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions on footer message"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default footer message"
                        }
                    },
                    "documentation": {
                        "description": "Message on footer of the billing"
                    }
                },
                "type": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "invoice_type",
                            "options": [],
                            "documentation": {
                                "description": "Reference filter"
                            }
                        },
                        "documentation": {
                            "description": "Reference type of the billing settings"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions for the type"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default type"
                        }
                    },
                    "documentation": {
                        "description": "Type of billing"
                    }
                },
                "from_email": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions on from whom is the email"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default from_email"
                        }
                    },
                    "documentation": {
                        "description": "From what email"
                    }
                },
                "invoice_number_generation": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "invoice_number_generation_type",
                            "options": []
                        },
                        "documentation": {
                            "description": "Invoice number generation's reference"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Invoice number generation's permission"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default invoice number generation"
                        }
                    },
                    "documentation": {
                        "description": "The invoice number generation type"
                    }
                },
                "start_number": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Start number's permission"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default start number"
                        }
                    },
                    "documentation": {
                        "description": "Start number of the billing"
                    }
                },
                "method": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "invoice_method",
                            "options": []
                        },
                        "documentation": {
                            "description": "Reference method of the billing settings"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the method"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default method"
                        }
                    },
                    "documentation": {
                        "description": "The method of billing"
                    }
                },
                "accounting_ids": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions for the accounting ID"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default accounting ID"
                        }
                    },
                    "documentation": {
                        "description": "Accounting IDs"
                    }
                },
                "client_location_accounting_ids": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the client location accounting ID"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default client location accounting ID"
                        }
                    },
                    "documentation": {
                        "description": "Client location accounting IDs"
                    }
                },
                "patient_billing_accounting_ids": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "The permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default patient billing accounting ID"
                        }
                    },
                    "documentation": {
                        "description": "The accounting IDs for the patient billing"
                    }
                },
                "patient_default_accounting_ids": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Patient default accounting ID permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default patient default accounting ID"
                        }
                    },
                    "documentation": {
                        "description": "Default patient accounting IDs"
                    }
                },
                "billing_period": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the billing period"
                        }
                    },
                    "subdocument": {
                        "period": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "billing_period",
                                    "options": []
                                },
                                "documentation": {
                                    "description": "Period's reference"
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Permissions of period"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default period"
                                }
                            },
                            "documentation": {
                                "description": "Period of the billing period"
                            }
                        },
                        "day": {
                            "type": "integer",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Permissions for the billing period's day"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default day"
                                }
                            },
                            "documentation": {
                                "description": "Day of the billing period"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with period and day"
                        }

                    },
                    "documentation": {
                        "description": "Billing period (days and etc)"
                    }
                },
                "outstanding": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Outstanding permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default outstanding"
                        }
                    },
                    "documentation": {
                        "description": "Outstanding value"
                    }
                },
                "rounding_type": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "bill_rounding_types",
                            "options": []
                        },
                        "documentation": {
                            "description": "Rounding type reference"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Rounding type permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default rounding type"
                        }
                    },
                    "documentation": {
                        "description": "What is the rounding type for the bill"
                    }
                },
                "clock_estimate": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the clock estimate"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default clock estimate"
                        }
                    },
                    "documentation": {
                        "description": "Estimate on the clock"
                    }
                },
                "early_checkin": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Early checkin permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default early checkin"
                        }
                    },
                    "documentation": {
                        "description": "Billing for early check in"
                    }
                },
                "late_checkin": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Late checking permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default late checkin"
                        }
                    },
                    "documentation": {
                        "description": "Billing for late check in"
                    }
                },
                "late_checkout": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Late checkout permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default late checkout"
                        }
                    },
                    "documentation": {
                        "description": "Billing for late check out"
                    }
                },
                "documentation": {
                    "description": "Subdocument with billing period, late checkout and etc"
                }
            },
            "documentation": {
                "description": "Contains all the billing settings, like how is the billing going to happen, what happens with late checkouts and others",
                "color": "red",
                "hide": false
            }
        },
        "visit_settings": {
            "type": "subdocument",
            "subdocument": {
                "punchcards_enabled": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "If the punchcards are enabled or not"
                    }
                },
                "overrides_enabled": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "If the override is enabled or not"
                    }
                },
                "telephony_enabled": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "If the telephony is enabled or not"
                    }
                },
                "gps_enabled": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "If the gps is enabled or not"
                    }
                },
                "documentation": {
                    "description": "Subdocument with information on what is enabled (punchcards, gps and telephony)"
                }
            },
            "documentation": {
                "description": "Contains all the visit settings, like punchcards, gps, overrides and telephony",
                "color": "red",
                "hide": false
            }
        },
        "payroll_settings": {
            "type": "subdocument",
            "subdocument": {
                "pay_period": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the pay period"
                        }
                    },
                    "subdocument": {
                        "period": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "billing_period",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Billing period"
                            }
                        },
                        "day": {
                            "type": "integer",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Billing day"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument witch the billing period and day"
                        }
                    },
                    "documentation": {
                        "description": "Period of the payroll"
                    }
                },
                "payroll_runs": {
                    "type": "subdocument",
                    "subdocument": {
                        "current": {
                            "type": "id",
                            "reference": {
                                "type": "referenceOne",
                                "collection": "payrolls"
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Permissions of the current payroll run"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default current payroll runs"
                                }
                            },
                            "documentation": {
                                "description": "Current payroll run"
                            }
                        },
                        "previous": {
                            "type": "id",
                            "reference": {
                                "type": "referenceOne",
                                "collection": "payrolls"
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Permissions on the previous payroll runs"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default previous payroll run"
                                }
                            },
                            "documentation": {
                                "description": "Previous payroll run"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with current and previous payroll runs"
                        }
                    },
                    "documentation": {
                        "description": "Payroll runs"
                    }
                },
                "export_type": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "payrolls_export_type",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the export type of the payroll settings"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default export type"
                        }
                    },
                    "documentation": {
                        "description": "Export type"
                    }
                },
                "payroll_type": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "payroll_types",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the payroll type"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default payroll type"
                        }
                    },
                    "documentation": {
                        "description": "Payroll type"
                    }
                },
                "documentation": {
                    "description": "Subdocument with period, runs, type of export and type of payroll"
                }
            },
            "documentation": {
                "description": "Contains all the payroll settings, like the type of payroll, the period and others",
                "color": "red",
                "hide": false
            }
        },
        "scheduler_settings": {
            "type": "subdocument",
            "subdocument": {
                "start_of_week": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "weekday",
                            "options": []
                        },
                        "documentation": {
                            "description": "Start of the week's reference"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the start of the week of the scheduler settings"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default start of the week"
                        }
                    },
                    "documentation": {
                        "description": "Start of the week on event"
                    }
                },
                "duration": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permission of the scheduler settings duration"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default duration"
                        }
                    },
                    "documentation": {
                        "description": "Duration of event"
                    }
                },
                "documentation": {
                    "description": "Subdocument with start of week and duration"
                }
            },
            "documentation": {
                "description": "Contains all the scheduler settings, like duration and permissions for example",
                "color": "red",
                "hide": false
            }
        },
        "candidate_settings": {
            "type": "subdocument",
            "subdocument": {
                "request_id": {
                    "type": "id",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documentation": {
                            "description": "Request ID permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default request ID"
                        }
                    },
                    "documentation": {
                        "description": "Request ID"
                    }
                },
                "submit_id": {
                    "type": "id",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documentation": {
                            "description": "Submit ID permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default submit ID"
                        }
                    },
                    "documentation": {
                        "description": "Submit ID"
                    }
                },
                "is_hiring": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions on the is hiring"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default is_hearing"
                        }
                    },
                    "documentation": {
                        "description": "If it is hiring"
                    }
                },
                "candidate_description": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Candidate description permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default candidate description"
                        }
                    },
                    "documentation": {
                        "description": "Candidate description"
                    }
                },
                "completed_submission_message": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Completed submission message permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default completed submission message"
                        }
                    },
                    "documentation": {
                        "description": "Entire submission message"
                    }
                },
                "candidate_stages": {
                    "type": "subdocuments",
                    "permissions": {
                        "documents": {
                            "delete": true
                        },
                        "documentation": {
                            "description": "Candidate stages permissions"
                        }
                    },
                    "subdocument": {
                        "code": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Code permissions"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default code"
                                }
                            },
                            "documentation": {
                                "description": "Code of the stage"
                            }
                        },
                        "label": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Label permissions"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default label"
                                }
                            },
                            "documentation": {
                                "description": "Label of the stage"
                            }
                        },
                        "color": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Color permissions"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default color"
                                }
                            },
                            "documentation": {
                                "description": "Color of the stage"
                            }
                        },
                        "order": {
                            "type": "integer",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "documentation": {
                                    "description": "Order permissions"
                                }
                            },
                            "default": {
                                "fields": true,
                                "documentation": {
                                    "description": "Default order"
                                }
                            },
                            "documentation": {
                                "description": "Order of the stages"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with code, label, color and order"
                        }
                    },
                    "documentation": {
                        "description": "Stages for the candidates"
                    }
                },
                "candidate_agreement": {
                    "type": "file",
                    "reference": {
                        "type": "referenceOne",
                        "collection": "files",
                        "documentation": {
                            "description": "Candidate agreement reference"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Candidate agreement permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default candidate agreement"
                        }
                    }
                    ,
                    "documentation": {
                        "description": "Candidate agreement"
                    }
                },
                "hr_email": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Human resources email permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default human resources email"
                        }
                    },
                    "documentation": {
                        "description": "Human resources email"
                    }
                },
                "documentation": {
                    "description": "Subdocument with request_id, submit_id, is_hiring, candidate_description, completed_submission_message, candidate_stages, candidate_agreement and hr_email"
                }
            },
            "documentation": {
                "description": "Contains all information on employee candidates, like stage, description, hr information and more",
                "color": "red",
                "hide": false
            }
        },
        "security_questions": {
            "type": "subdocuments",
            "subdocument": {
                "question": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                }
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "positions": {
            "type": "subdocuments",
            "permissions": {
                "documents": {
                    "delete": true
                }
            },
            "subdocument": {
                "code": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "color": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                }
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "locations": {
            "type": "subdocuments",
            "events": {
                "insert": [
                    {
                        "function": "geolocate"
                    }
                ],
                "update": [
                    {
                        "function": "geolocate"
                    }
                ],
                "documentation": {
                    "description": "Locations, geolocate"
                }
            },
            "permissions": {
                "documents": {
                    "delete": true
                },
                "documentation": {
                    "description": "Locations permissions"
                }
            },
            "subdocument": {
                "primary": {
                    "type": "boolean",
                    "primary": true,
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Primary permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default primary"
                        }
                    },
                    "documentation": {
                        "description": "If the location is the primay location or not"
                    }
                },
                "address": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions on the address"
                        }
                    },
                    "subdocument": {
                        "city": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "City name"
                            }
                        },
                        "country": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "country",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Country name"
                            }
                        },
                        "lat": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Latitude"
                            }
                        },
                        "lng": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Longitude"
                            }
                        },
                        "state": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "state",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "State"
                            }
                        },
                        "street": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Street name"
                            }
                        },
                        "street_extra": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Extra info on the street"
                            }
                        },
                        "zip": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Zip code"
                            }
                        },
                        "map_img": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "documentation": {
                                "description": "Map image"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with city, country, lat, lng, state, street, street_extra, zip and map_img"
                        }
                    },
                    "documentation": {
                        "description": "Adress, with street name, city, country, latitude, longitude and others"
                    }
                },
                "title": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Title of the location"
                    }
                },
                "phone": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "country": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "country",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Country of the phone number"
                            }
                        },
                        "number": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Phone number"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with country and number"
                        }
                    },
                    "documentation": {
                        "description": "Phone"
                    }
                },
                "fax": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "country": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "country",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Fax country"
                            }
                        },
                        "number": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Fax number"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with country and number"
                        }
                    },
                    "documentation": {
                        "description": "Fax"
                    }
                },
                "documentation": {
                    "description": "Subdocument with primary, address, title, phone and fax"
                }
            },
            "documentation": {
                "description": "Location info, like address and geolocation",
                "color": "red",
                "hide": false
            }
        },
        "roles": {
            "type": "subdocuments",
            "permissions": {
                "documents": {
                    "delete": true
                }
            },
            "subdocument": {
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "query": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Role's label"
                    }
                },
                "description": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "query": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Role's description"
                    }
                },
                "color": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "query": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Role's colors"
                    }
                },
                "default_view": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "query": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Default view"
                    }
                },
                "role_type": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "role_type",
                            "options": []
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "query": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Type of role"
                    }
                },
                "permissions": {
                    "type": "subdocument",
                    "subdocument": {
                        "patients": {
                            "type": "subdocument",
                            "subdocument": {
                                "all": {
                                    "type": "boolean",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "query": {
                                        "fields": true
                                    }
                                },
                                "events_permissions": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "visit_restricted": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "days_before": {
                                            "type": "integer",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "days_after": {
                                            "type": "integer",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        }
                                    }
                                }
                            }
                        },
                        "modules": {
                            "type": "subdocument",
                            "subdocument": {
                                "calendar": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        }
                                    }
                                },
                                "contacts": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "contacts_add": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "contacts_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "contacts_delete": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "contacts_email": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "contacts_phone": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "progress_notes": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "patients": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "patients_add": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patient_info_export": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_delete": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_setstatus": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_import": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_export": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_certify": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_email": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_phone": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "patients_checklist": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "info": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "caregiverblacklist": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "profile_ccac": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "contacts": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "contacts_phone": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "accounting_id": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "legal_rep": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "referral": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "progress_notes": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                },
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "notes_add": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "notes_edit": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "notes_delete": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "notes_approve": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "notes_export": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "private_visible": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "users_visible": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "service_visible": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "timecards": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "calendar": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "problems": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "services": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "billing": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "files": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "invoices": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "clients": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "clients_add": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "clients_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "clients_delete": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "clients_import": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "clients_export": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "employees": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "timecards": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "progress_notes": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "invoices": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "users_management": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "users_add": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "users_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "users_delete": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "users_suspend": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "users_resetpassword": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "users_import": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "users_export": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "positions_payroll": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "notes": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                },
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "notes_add": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "notes_edit": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "notes_delete": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "progress_notes": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "calendar": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "availability": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                },
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "availability_edit": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "timecards": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "visit_summary": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "employment_history": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "education_training": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "equipment": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "files": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "candidates": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "candidates_add": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "candidates_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "candidates_export": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "candidates_hire": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "candidates_delete": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "resume": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "employment_history": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "notes": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "education_training": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "availability": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                },
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "availability_edit": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "company": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "accounts_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "positions": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "locations": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "calendar": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "notifications": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "salesreps": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "settings": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "roles": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                },
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "roles_add": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "roles_edit": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        },
                                                                        "roles_delete": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "accounting": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "client_statements": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "payroll": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                },
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "payrolls_close": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "invoices": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                },
                                                                "permissions": {
                                                                    "type": "subdocument",
                                                                    "subdocument": {
                                                                        "invoices_close": {
                                                                            "type": "boolean",
                                                                            "permissions": {
                                                                                "fields": true,
                                                                                "conditions": true,
                                                                                "sort": true,
                                                                                "documents": {
                                                                                    "insert": true,
                                                                                    "update": true,
                                                                                    "delete": true
                                                                                }
                                                                            },
                                                                            "query": {
                                                                                "fields": true
                                                                            }
                                                                        }
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "archived": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "views": {
                                                    "type": "subdocument",
                                                    "subdocument": {
                                                        "patients": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "candidates": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "users": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "clients": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "contacts": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        },
                                                        "events": {
                                                            "type": "subdocument",
                                                            "permissions": {
                                                                "documents": {
                                                                    "delete": true
                                                                }
                                                            },
                                                            "subdocument": {
                                                                "permission": {
                                                                    "type": "boolean",
                                                                    "permissions": {
                                                                        "fields": true,
                                                                        "conditions": true,
                                                                        "sort": true,
                                                                        "documents": {
                                                                            "insert": true,
                                                                            "update": true,
                                                                            "delete": true
                                                                        }
                                                                    },
                                                                    "query": {
                                                                        "fields": true
                                                                    }
                                                                }
                                                            }
                                                        }
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "profile": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "profile_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "messages": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "managers_visible": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "users_visible": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "map": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "_id": {
                                            "type": "id",
                                            "primary": true,
                                            "length": 24,
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "users_filter": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "export_nearby": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                }
                                            }
                                        }
                                    }
                                },
                                "scheduler": {
                                    "type": "subdocument",
                                    "permissions": {
                                        "documents": {
                                            "delete": true
                                        }
                                    },
                                    "subdocument": {
                                        "permission": {
                                            "type": "boolean",
                                            "permissions": {
                                                "fields": true,
                                                "conditions": true,
                                                "sort": true,
                                                "documents": {
                                                    "insert": true,
                                                    "update": true,
                                                    "delete": true
                                                }
                                            },
                                            "query": {
                                                "fields": true
                                            }
                                        },
                                        "permissions": {
                                            "type": "subdocument",
                                            "subdocument": {
                                                "visit_add": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "visit_edit": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "visit_delete": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                },
                                                "dateofloss_warning": {
                                                    "type": "boolean",
                                                    "permissions": {
                                                        "fields": true,
                                                        "conditions": true,
                                                        "sort": true,
                                                        "documents": {
                                                            "insert": true,
                                                            "update": true,
                                                            "delete": true
                                                        }
                                                    },
                                                    "query": {
                                                        "fields": true
                                                    }
                                                }
                                            }
                                        }
                                    }
                                }
                            }
                        }
                    }
                },
                "documentation": {
                    "description": "Subdocument with label, description, color, default_view and role_type"
                }
            },
            "documentation": {
                "description": "Contains information about the roles, like for example the type, color and all the permissions",
                "color": "red",
                "hide": false
            }
        },
        "terms": {
            "type": "subdocuments",
            "subdocument": {
                "term": {
                    "type": "integer",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Term's term"
                    }
                },
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Term's label"
                    }
                },
                "documentation": {
                    "description": "Subdocument with term and label"
                }
            },
            "documentation": {
                "description": "Contains the company's terms",
                "color": "red",
                "hide": false
            }
        },
        "taxes": {
            "type": "subdocuments",
            "subdocument": {
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Taxe's label"
                    }
                },
                "amount": {
                    "type": "float",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Amount of taxes"
                    }
                },
                "documentation": {
                    "description": "Subdocument with label and amount"
                }
            },
            "documentation": {
                "description": "Contains the taxes info, like the amount and its label",
                "color": "red",
                "hide": false
            }
        },
        "services": {
            "type": "subdocuments",
            "permissions": {
                "documents": {
                    "delete": true
                }
            },
            "subdocument": {
                "code": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Permissions of the code of the service"
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "color": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Color of the service"
                    }
                },
                "label": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Label of the service"
                    }
                },
                "description": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Description of the service"
                    }
                },
                "bill_rate": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "rate": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Rate of the service"
                            }
                        },
                        "unit": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "pay_unit",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Unit of the service's bill_rate"
                            }
                        },
                        "taxes": {
                            "type": "subdocuments",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "tax": {
                                    "type": "id",
                                    "reference": {
                                        "type": "referenceOne",
                                        "collection": "accounts.taxes"
                                    },
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Tax"
                                    }
                                }
                            },
                            "documentation": {
                                "description": "Taxes on the bill rate"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with rate, unit and taxes"
                        }
                    },
                    "documentation": {
                        "description": "Bill rate"
                    }
                },
                "min_billable_hours": {
                    "type": "float",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Minimum billable hours"
                    }
                },
                "billable_after_some_hours": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "after": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "How much it was after for the billable hours"
                            }
                        },
                        "rate": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Rate for the billable after some hours"
                            }
                        },
                        "unit": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "pay_unit",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Pay unit for the billable after some hours"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with after, rate and unit"
                        }
                    },
                    "documentation": {
                        "description": "Services billable after some hours"
                    }
                },
                "max_billables": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "visit": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "hours": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "dollars": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    }
                                },
                                "documentation": {
                                    "description": "Subdocument with hours and dollars"
                                }
                            },
                            "documentation": {
                                "description": "Services max billables visit"
                            }
                        },
                        "day": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "hours": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Hours of the day for the max billable of the service"
                                    }
                                },
                                "dollars": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Dollars of the day for the max billable of the service"
                                    }
                                },
                                "documentation": {
                                    "description": "Subdocument with hours and dollars"
                                }
                            },
                            "documentation": {
                                "description": "Services day"
                            }
                        },
                        "week": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "hours": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Hours of the week for the max billable of the service"
                                    }
                                },
                                "dollars": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Dollars of the week for the max billable of the service"
                                    }
                                },
                                "documentation": {
                                    "description": "Subdocument with hours and dollars"
                                }
                            },
                            "documentation": {
                                "description": "Services week"
                            }
                        },
                        "biweek": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "hours": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Hours of the biweek for the max billable of the service"
                                    }
                                },
                                "dollars": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Dollars of the biweek for the max billable of the service"
                                    }
                                },
                                "documentation": {
                                    "description": "Subdocument with hours and dollars"
                                }
                            },
                            "documentation": {
                                "description": "Services biweek"
                            }
                        },
                        "semimonth": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "hours": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Hours of the semimonth for the max billable of the service"
                                    }
                                },
                                "dollars": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Dollars of the semimonth for the max billable of the service"
                                    }
                                },
                                "documentation": {
                                    "description": "Subdocument with hours and dollars"
                                }
                            },
                            "documentation": {
                                "description": "Services semimonth"
                            }
                        },
                        "month": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "hours": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Hours of the month for the max billable of the service"
                                    }
                                },
                                "dollars": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Dollars of the month for the max billable of the service"
                                    }
                                },
                                "documentation": {
                                    "description": "Subdocument with hours and dollars"
                                }
                            },
                            "documentation": {
                                "description": "Services month"
                            }
                        },
                        "contract": {
                            "type": "subdocument",
                            "permissions": {
                                "documents": {
                                    "delete": true
                                }
                            },
                            "subdocument": {
                                "hours": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Hours of the contract for the max billable of the service"
                                    }
                                },
                                "dollars": {
                                    "type": "float",
                                    "permissions": {
                                        "fields": true,
                                        "conditions": true,
                                        "sort": true,
                                        "documents": {
                                            "insert": true,
                                            "update": true,
                                            "delete": true
                                        }
                                    },
                                    "default": {
                                        "fields": true
                                    },
                                    "documentation": {
                                        "description": "Dolalrs of the contract for the max billable of the service"
                                    }
                                },
                                "documentation": {
                                    "description": "Subdocument with hours and dollars"
                                }
                            },
                            "documentation": {
                                "description": "Services contract"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with visit, day, week, biweek, semimonth, month and contract"
                        }
                    },
                    "documentation": {
                        "description": "Services max billables"
                    }
                },
                "pay_rate": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "rate": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Pay rate"
                            }
                        },
                        "unit": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "pay_unit",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Pay rate unit"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with rate and unit"
                        }
                    },
                    "documentation": {
                        "description": "Services pay rate"
                    }
                },
                "payable_after_some_hours": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "after": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Time after the payable hours"
                            }
                        },
                        "rate": {
                            "type": "float",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Rate for after the payable hours"
                            }
                        },
                        "unit": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "pay_unit",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Unit for after the payable hours"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with after, rate and unit"
                        }
                    },
                    "documentation": {
                        "description": "Services payable after some hours"
                    }
                },
                "duties": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Services duties"
                    }
                },
                "catastrophic": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Catastrophic services"
                    }
                },
                "documentation": {
                    "description": "Subdocument with code, color, label, description, bill_rate, min_billable_hours, billable_after_some_hours, max_billables, pay_rate, payable_after_some_hours, duties and catastrophic"
                }
            },
            "documentation": {
                "description": "Contains the services and its informations, like its code, description, pay rate and others",
                "color": "red",
                "hide": false
            }
        },
        "emergency_phones": {
            "type": "subdocuments",
            "permissions": {
                "documents": {
                    "delete": true
                },
                "documentation": {
                    "description": "Emergency phones permissions"
                }
            },
            "subdocument": {
                "primary": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Primary permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default primary"
                        }
                    },
                    "documentation": {
                        "description": "If it is the primary emergency phone number or not"
                    }
                },
                "title": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Title permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default title"
                        }
                    },
                    "documentation": {
                        "description": "Title of the emergency phone"
                    }
                },
                "number": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Number permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default number"
                        }
                    },
                    "documentation": {
                        "description": "The emergency phone number"
                    }
                },
                "country": {
                    "type": "id",
                    "reference": {
                        "type": "picklist",
                        "filter": {
                            "function": "country",
                            "options": []
                        },
                        "documentation": {
                            "description": "Country's reference"
                        }
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Country's permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default country"
                        }
                    },
                    "documentation": {
                        "description": "Country of the emergency phone number"
                    }
                },
                "documentation": {
                    "description": "Subdocument with primary, title, number and country"
                }
            },
            "documentation": {
                "description": "Contains the emergency phones and its informations",
                "color": "red",
                "hide": false
            }
        },
        "notifications": {
            "type": "subdocuments",
            "subdocument": {
                "active": {
                    "type": "boolean",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "code": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "group": {
                    "type": "id",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "name": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "description": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    }
                },
                "triggers": {
                    "type": "subdocuments",
                    "subdocument": {
                        "active": {
                            "type": "boolean",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        },
                        "type": {
                            "type": "id",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        },
                        "title": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    }
                },
                "alerts": {
                    "type": "subdocuments",
                    "subdocument": {
                        "type": {
                            "type": "id",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        },
                        "user": {
                            "type": "id",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            }
                        }
                    }
                }
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "templates": {
            "type": "subdocument",
            "subdocument": {
                "invoices": {
                    "type": "id",
                    "permissions": {
                        "fields": true
                    },
                    "default": {
                        "fields": true
                    }
                },
                "client_statements": {
                    "type": "id",
                    "permissions": {
                        "fields": true
                    },
                    "default": {
                        "fields": true
                    }
                }
            },
            "documentation": {
                "description": "aaaaaaaaaaaaaaaaa",
                "color": "red",
                "hide": true
            }
        },
        "sales_reps": {
            "type": "subdocuments",
            "permissions": {
                "documents": {
                    "delete": true
                }
            },
            "subdocument": {
                "ext_id": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "External ID permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default external ID"
                        }
                    },
                    "documentation": {
                        "description": "Sales rep external ID"
                    }
                },
                "accounting_id": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        },
                        "documentation": {
                            "description": "Accounting ID permissions"
                        }
                    },
                    "default": {
                        "fields": true,
                        "documentation": {
                            "description": "Default accounting id"
                        }
                    },
                    "documentation": {
                        "description": "Sales rep accounting ID"
                    }
                },
                "territory": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Sales rep territory"
                    }
                },
                "name": {
                    "type": "subdocument",
                    "filter": {
                        "function": "name",
                        "options": {
                            "type": "full"
                        }
                    },
                    "subdocument": {
                        "first": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "sort": true
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "First name"
                            }
                        },
                        "last": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                },
                                "sort": true
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Last name"
                            }
                        },
                        "middle": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Middle name"
                            }
                        },
                        "nickname": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Sales rep nickname"
                            }
                        },
                        "title": {
                            "type": "id",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Name's title"
                            }
                        },
                        "documentation": {
                            "description": "Subdocument with first, last, middle, nickname and title"
                        }
                    },
                    "documentation": {
                        "description": "Sales representatives name"
                    }
                },
                "office": {
                    "type": "id",
                    "reference": {
                        "type": "referenceOne",
                        "collection": "accounts.locations"
                    },
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Sales representatives offices"
                    }
                },
                "phone": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "country": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "country",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Phone country"
                            }
                        },
                        "number": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Phone number"
                            }
                        }
                    },
                    "documentation": {
                        "description": "Sales representatives phones"
                    }
                },
                "fax": {
                    "type": "subdocument",
                    "permissions": {
                        "documents": {
                            "delete": true
                        }
                    },
                    "subdocument": {
                        "country": {
                            "type": "id",
                            "reference": {
                                "type": "picklist",
                                "filter": {
                                    "function": "country",
                                    "options": []
                                }
                            },
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Fax country"
                            }
                        },
                        "number": {
                            "type": "string",
                            "permissions": {
                                "fields": true,
                                "conditions": true,
                                "sort": true,
                                "documents": {
                                    "insert": true,
                                    "update": true,
                                    "delete": true
                                }
                            },
                            "default": {
                                "fields": true
                            },
                            "documentation": {
                                "description": "Fax number"
                            }
                        }
                    },
                    "documentation": {
                        "description": "Sales representative's fax"
                    }
                },
                "email": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Sales representative email"
                    }
                },
                "notes": {
                    "type": "string",
                    "permissions": {
                        "fields": true,
                        "conditions": true,
                        "sort": true,
                        "documents": {
                            "insert": true,
                            "update": true,
                            "delete": true
                        }
                    },
                    "default": {
                        "fields": true
                    },
                    "documentation": {
                        "description": "Sales representative's notes"
                    }
                },
                "documentation": {
                    "description": "Subdocument with notes, email, fax, phone, office, name, territory, accounting_id and ext_id"
                }
            },
            "documentation": {
                "description": "Contains information on the sales reps, like his or hers name, office, nickname and others",
                "color": "red",
                "hide": false
            }
        }
    },
    "codes": {
        "ruby": {
            "line1": "require 'test'",
            "line2": "api = Test::APIClient.authorize!('key')",
            "line3": "api.tests.get"
        },
        "javascript": {
            "line1": "dsja javascript",
            "line2": "dsja javascript",
            "line3": "print 'Hello, world!'",
            "line4": "sads shell"
        },
        "python": {
            "line1": "import test",
            "line2": " ",
            "line3": "api = test.authorize('key')",
            "line4": "api.test.get()"
        },
        "shell": {
            "line1": "curl 'http://example.com/api/test'",
            "line2": "  -H 'Authorization: key'"
        }
    },
    "examples": {
        "example1": {
            "auth": {
                "access_token": "JDJhJDEwJDZucU9qVDEvVXo3dFlvNXk3b2NOR0...",
                "access_secret": "VTJGc2RHVmtYMS91TDRQWTZxeE5LTWJPZ0xka...",
                "access_key": "VTJGc2RHVmtYMSs4cjJqUlAxckxxRDV2NUN4Uk14..."
            },
            "user": {
                "_id": "57360e77f90e15c27c8b4567",
                "ext_id": "6O0482C",
                "last_login_date": "2016-11-08T15:37:29-05:00",
                "pin_lastchanged_date": "2016-05-13T13:36:44-04:00",
                "date_of_birth": "1983-05-17",
                "locations": [{
                    "_created_user": {
                        "_id": "5679cdb609da69d90c8b4577",
                        "ext_id": "BNUWU93",
                        "email": "iegor.benzyk2@alaunus.com",
                        "name": {
                            "first": "Isaac",
                            "last": "Romanov",
                            "title": "2e5c84ad927c053c8b7a7657"
                        }
                    },
                    "address": {
                        "street": "151 Charles St W",
                        "city": "Kitchener",
                        "lat": 43.4509381,
                        "lng": -80.4982637,
                        "country": "29f678bca33e6a07d9d61066",
                        "state": "baa39fa80fb2f0bbf4d8cfdf"
                    },
                    "primary": true,
                    "type": "3f5aa337cc7338b01f435787",
                    "_id": "5736124ef90e15c37c8b456c",
                    "_key": 0
                }],
                "is_recover": true
            },
            "stage": "dev",
            "version": "1.4.5"
        }
    },
    "actions":{
        "create": "crud/create.erb",
        "delete": "crud/delete.erb",
        "edit": "crud/edit.erb",
        "get": "crud/get.erb",
        "list": "crud/list.erb",
        "custom1": "account/custom1.erb"
    }
}