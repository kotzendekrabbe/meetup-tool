[![npm version](https://badge.fury.io/js/npm.svg)](https://badge.fury.io/js/npm)
[![npm version](https://badge.fury.io/js/node.svg)](https://badge.fury.io/js/node)
> Sync your Meetup events with Google Calendar

# meetsy #

Is a CLI tool which syncs your meetup events with your (google) calendar.
It could help you to have a better overview on upcoming events.
You can also sync it with a shared google calendar with others,
e.g.: you can create a google calendar for your company to share Meetup events with your colleagues.


## At the moment it's only a MVP: ##
* get the next 30 meetup events
* get the next 100 google events
* compare events with each other, if there are events which are not existing insert these into the calendar

## What you need ##
* google calendar for the meetup events
* [meetup account](https://meetup.com/)
* [npm and node](https://www.npmjs.com/get-np)

---------------


## Installation ##

### Get meetsy ###
You can clone or download meetsy by using the "Clone or Download" Button above.

### Install meetsy ###

```node
npm install
```

## Setup instructions ##

### Google calendar ###
https://developers.google.com/google-apps/calendar/quickstart/nodejs

* follow the instructions from the link above on step 1 to get your `client_secret.json`
* save this data at project root and rename it to `googleApi_clientSecret.json`

---------------


## Usage instructions ##

```node
node ./cli.js --calID 'yourGoogleCalenderID' --meetupApiKey 'yourMeetupApiKey'
```

*Note:* On first use you have to authorize the calender tool by a URL shown
in your terminal.


### How to get your Google calendar ID/address ###
https://support.google.com/calendar/answer/37083#link


### How to get your meetup api key ###
https://secure.meetup.com/de-DE/meetup_api/key/



---------------

## dependencies ##
* node
* npm
* google-auth-library
* googleapis
* meow
* node-fetch
"": {
    "google-auth-library": "^0.10.0",
    "googleapis": "^19.0.0",
    "meow": "^3.7.0",
    "node-fetch": "^1.7.2"
  }

---------------


## Next features ##
[See Issues](https://github.com/kotzendekrabbe/meetup-tool/issues?q=is%3Aissue+is%3Aopen+label%3Afeature)



## Contribute ##
Feel free to dive in! Open an
[issue](https://github.com/kotzendekrabbe/meetup-tool/issues/new) or
submit a [Pull Request](https://github.com/kotzendekrabbe/meetup-tool/compare). ❤️

meetsy follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).

---------------

Copyright 2017 by SinnerSchrader Deutschland GmbH and contributors.
Released under the MIT license.
