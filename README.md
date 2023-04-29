![Logo](admin/lightcontrol.png)

# ioBroker.lightcontrol

[![NPM version](https://img.shields.io/npm/v/iobroker.lightcontrol.svg)](https://www.npmjs.com/package/iobroker.lightcontrol)
[![Downloads](https://img.shields.io/npm/dm/iobroker.lightcontrol.svg)](https://www.npmjs.com/package/iobroker.lightcontrol)
![Snyk Vulnerabilities for npm package](https://img.shields.io/snyk/vulnerabilities/npm/iobroker.lightcontrol?label=npm%20vulnerabilities&style=flat-square)
![node-lts](https://img.shields.io/node/v-lts/iobroker.lightcontrol?style=flat-square)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/iobroker.lightcontrol?label=npm%20dependencies&style=flat-square)
[![Translation status](https://weblate.iobroker.net/widgets/adapters/-/lightcontrol/svg-badge.svg)](https://weblate.iobroker.net/engage/adapters/?utm_source=widget)

![GitHub](https://img.shields.io/github/license/schmakus/iobroker.lightcontrol?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/schmakus/iobroker.lightcontrol?logo=github&style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/schmakus/iobroker.lightcontrol?logo=github&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/schmakus/iobroker.lightcontrol?logo=github&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/schmakus/iobroker.lightcontrol?logo=github&style=flat-square)

![Test and Release](https://github.com/Schmakus/ioBroker.lightcontrol/workflows/Test%20and%20Release/badge.svg)

[![NPM](https://nodei.co/npm/iobroker.lightcontrol.png?downloads=true)](https://nodei.co/npm/iobroker.lightcontrol/)

## Versions

![Beta](https://img.shields.io/npm/v/iobroker.lightcontrol.svg?color=red&label=beta)
![Stable](http://iobroker.live/badges/lightcontrol-stable.svg)
![Installed](http://iobroker.live/badges/lightcontrol-installed.svg)

**This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers.** For more details and for information how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

## If you like my work:

[![Paypal Donation](https://img.shields.io/badge/paypal-donate%20%7C%20spenden-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=PK89K4V2RBU78&source=url)

## Installation

Please use the "adapter list" & Beta Repository in ioBroker to install a beta version of this adapter. You can also use the CLI to install this adapter:

```
iobroker add lightcontrol
```

## Documentation

[🇺🇸 Documentation](./en/lightcontrol.md)

[🇩🇪 Dokumentation](./docs/de/lightcontrol.md)

## ToDo

-   Select more than one LightGroup for one Object-ID (Bug with jsonCustom Select multible)
-   Availability for notice with lower brighness and defined seconds before AutoOff

## Changelog

<!--
	Placeholder for the next version (at the beginning of the line):
	### **WORK IN PROGRESS**
-->

### **WORK IN PROGRESS**

-   (Schmakus) Important Update! Dev-mode was activated in v0.2.8

### 0.2.8 (2023-04-28)

-   (Schmakus) Fix switch on/off
-   (Schmakus) Some code improvements

### 0.2.7 (2023-04-20)

-   (Schmakus) Fix switching on/off

### 0.2.6 (2023-04-19)

-   (Schmakus) Creating LightGroups is only possible if the group name does not contain any special characters other than \_ and -.

### 0.2.5 (2023-04-19)

-   (Schmakus) Fix: set brightness although no brightness state is available (blink)

### 0.2.4 (2023-04-17)

-   (Schmakus) renew release. no changes. please use this release.

## License

MIT License

Copyright (c) 2023 Schmakus <schmakus@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
