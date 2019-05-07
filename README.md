# ![LOGO](logo.png) Bandsintown **flow**ground Connector

## Description

A generated **flow**ground connector for the Bandsintown API (version 3.0.0).

Generated from: https://api.apis.guru/v2/specs/bandsintown.com/3.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:39:29+03:00

## API Description

# What is the Bandsintown API?
The Bandsintown API is designed for enterprise partners and artists with websites, media players, and/or mobile applications that would like to list an artist's events and provide their users with the ability to buy tickets and RSVP to these events.

It offers read-only access to artist info and artist events:
- artist info: returns the link to the Bandsintown artist page, the link to the artist photo, the current number of trackers and more
- artist events: returns the list of events including their date and time, venue name and location, ticket links, lineup, description and the link to the Bandsintown event page

Note you can specify if you only want to return upcoming events, past events, all events, or events within a given date range.

# Getting Started
- In order to use the Bandsintown API, you must have written consent from Bandsintown Inc. Any other use of the Bandsintown API is prohibited. [Contact Bandsintown](http://help.bandsintown.com/) to tell us what you plan to do and request your personal application ID.
- Find out about the API methods available and the format of the API responses below. Select the method you wish to use and try it out online with the app ID provided to you.
- Call our Bandsintown API with the app ID provided straight from your website or back-end platform and choose which element of the API response you wish to display. Scroll to the bottom of this page to find out about the Models used.


## Authorization

This API does not require authorization.

## Actions

### Get artist information

> Get artist information

*Tags:* `artist information`

#### Input Parameters
* `artistname` - _required_ - The name of the artist. If it contains one of the special characters below, please be sure to replace it by the corresponding code: for / use %252F, for ? use %253F, for * use %252A, and for " use %27C
* `app_id` - _required_ - The application ID assigned to you by Bandsintown

### Get upcoming, past, or all artist events, or events within a date range

> artist events

*Tags:* `artist events`

#### Input Parameters
* `artistname` - _required_ - The name of the artist. If it contains one of the special characters below, please be sure to replace it by the corresponding code: for / use %252F, for ? use %253F, for * use %252A, and for " use %27C
* `app_id` - _required_ - The application ID assigned to you by Bandsintown
* `date` - _optional_ - Can be one of the following values: "upcoming", "past", "all", or a date range e.g. "2015-05-05,2017-05-05". If not specified, only upcoming shows are returned

## License

**flow**ground :- Telekom iPaaS / bandsintown-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
