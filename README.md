GrandEntrance-ios
=================

A simple application using iBeacons from Estimote to give you a Grand Entrance.

## Installation
Make sure to install submodules (Alamofire) by running

`git submodule init`

Install CocoaPods dependencies by running 

`pod install`

## Usage
The server will start playing a given Spotify URI doing a GET request to the Grand Entrance Server. The URL could look something like this: `http://localhost:3000/track/play/spotify:track:2rjOaGr1mcTYePllS8crRf`.

## License

GrandEntrance-ios is available under the MIT license. See the LICENSE file for more info.

The notification sounds where borrowed from Panic Inc's [PunchClock](https://github.com/panicinc/PunchClock).

PUNCHCLOCK
Copyright (C) 2014 Panic, Inc.
All rights reserved.
