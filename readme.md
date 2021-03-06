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

### Install meetsy ###

```node
npm install -g meetsy
```

## Setup instructions ##

### Google calendar ###
https://developers.google.com/google-apps/calendar/quickstart/nodejs

* follow the instructions from the link above on step 1 to get your `client_secret.json`
* save this JSON file anywhere  for later use as --secret (remember the path to the file!)
* * in the meetsy example it's in the project root and named as googleApi_clientSecret.json

---------------


## Usage instructions ##

```node
meetsy --calID 'yourGoogleCalenderID' --meetupApiKey 'yourMeetupApiKey' --secret './googleApi_clientSecret.json'
```

*Note:* On first use you have to authorize the calender tool by a URL shown
in your terminal.


### How to get your Google calendar ID/address ###
https://support.google.com/calendar/answer/37083#link


### How to get your meetup api key ###
https://secure.meetup.com/de-DE/meetup_api/key/



---------------


## Next features ##
[See Issues](https://github.com/kotzendekrabbe/meetsy/issues?q=is%3Aissue+is%3Aopen+label%3Afeature)



## Contribute ##
Feel free to dive in! Open an
[issue](https://github.com/kotzendekrabbe/meetsy/issues/new) or
submit a [Pull Request](https://github.com/kotzendekrabbe/meetsy/compare). ❤️

meetsy follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).

---------------

Copyright 2017 by SinnerSchrader Deutschland GmbH and contributors.
Released under the MIT license.
