![Add to Calendar Button React Wrapper](https://github.com/add2cal/add-to-calendar-button-react/blob/main/assets/readme-header.png?raw=true)

![Version](https://img.shields.io/npm/v/add-to-calendar-button-react?style=for-the-badge&label=Version)
[![Parent Script Version](https://img.shields.io/badge/Parent%20Script%20Version-v2.2.2-blue?style=for-the-badge)](https://github.com/add2cal/add-to-calendar-button)
[![npm bundle size](https://img.shields.io/bundlephobia/minzip/add-to-calendar-button-react?style=for-the-badge)](https://www.npmjs.com/package/add-to-calendar-button-react)
[![npm Installations](https://img.shields.io/npm/dt/add-to-calendar-button-react?label=npm%20Installations&style=for-the-badge)](https://www.npmjs.com/package/add-to-calendar-button-react)

<br />

# The Add to Calendar Button - optimized for React

This is a wrapper repository for the popular [Add to Calendar Button](https://github.com/add2cal/add-to-calendar-button), making it even more convenient, to create beautiful buttons in React, where people can add events to their calendars.

<br /><br />

This is for everybody, who wants to include a button in their React application, which enables users to easily add a specific event to their calendars.
The main goal of this repository is to keep this process as easy as possible at maximum compatibility. Simply define your button configuration and everything else is automatically generated by the script.
Supporting calendars at Apple, Google, Microsoft (365, Outlook, Teams), Yahoo, and generic iCal.

![Supported Calendars: Apple (via iCal), Google, Microsoft (365, Outlook, Teams), Yahoo, generic iCal](https://github.com/add2cal/add-to-calendar-button-react/blob/main/assets/badge-supported-calendars.svg)

In terms of system support, **all modern browsers** (Chrome, Edge, Firefox, Safari) on **Windows, Mac, Android, and iOS** as well as rather restricted webview environments like the **Instagram** in-app browser are supported.

<br /><br />

---

<br />

## ▶️ Demo

See [add-to-calendar-button.com](https://add-to-calendar-button.com/) for a live demo and more documentation.

And remember to [⭐ **star** this repository](#) in order to stay up-to-date and save it for later! 🤗

<br />

---

<br />

## ✨ Features

Simple and convenient integration of 1 or many buttons, optimized to be used as a React component.

### Supported Calendars

- **Google** Calendar.
- **Yahoo** Calender.
- **Microsoft 365, Outlook, and Teams**.
- Automatically generated **iCal/ics** files (for all other calendars, like **Apple**).

### Event Types

- Timed and all-day events.
- One-time, multi-date, recurring.
- Calendar Subscription.
- Most robust time zone and daylight saving management (via our own [TimeZones iCal Library](https://github.com/add2cal/timezones-ical-library)).
- Dynamic dates (like "today + 3").

### Look

- Beautiful and adjustable UI.
- Light and dark mode.
- Multiple themes.

### Accessibility

- Optimized and adjustable UX (for desktop and mobile).
- Dynamic dropdown positioning.
- Taking care of all those edge cases, where some scenarios do not support specific setups (like WebView blocking downloads); utilizing beautiful user guidance workarounds.
- Auto-generated Schema.org rich (structured) data for better SEO.
- Full support for mouse, touch, or keyboard input (W3C WAI compliant).
- Supporting 20+ languages, incl. RTL text for Arabic; but also custom labels and text blocks.

### And much more

- Well documented code, to easily understand the processes and build on top of it.
- No external module or backend dependencies.
- Fully GDPR, CCPA, and LGPD compliant by design - without the need of signing some data processing agreement.
- FREE and easy.

<br />

---

<br />

## 📦 Installation

Import the package using the following npm command:

```sh
npm install add-to-calendar-button-react
```

It requires React and React-Dom, both >=18.0.0. The installer will warn you automatically if your setup does not fit.

<br /><br />

## 🎛️ Setup & Configuration

Import the component wherever you want to use it:

```javascript
import { AddToCalendarButton } from 'add-to-calendar-button-react';
```

Use the componet inside your code and declare any options as props. You will get warned about any type misconfiguration.

```javascript
<AddToCalendarButton
  name="Test-Event"
  startDate="2023-05-22"
  options={['Apple','Google','Yahoo','iCal']}
></AddToCalendarButton>
```

<br /><br />

### All options and hidden features

Find all information about the available props and how to configure specific features on the demo page at [add-to-calendar-button.com/configuration](https://add-to-calendar-button.com/configuration).

Mind the difference to the web component! At this wrapper, you would use the `<AddToCalendarButton>` component instead of the `<add-to-calendar-button>` custom element.

**Also mind that, different to the main package, with the React wrapper, you can actually declare arrays (like with the options prop) as arrays and objects (like with multi-date setups) as objects!**

<br />

---

<br />

## ⚡ Changelog

- v2.2 : update to parent script v2.2; type fixes; "attendee" option; better lazy load of external css
- v2.1 : update to parent script v2.1; type fixes
- v2.0 : supporting latest major version of the parent script
- v1.0 : initial release

(Only referring to this wrapper repository and not including any patches!)

Find all changes regarding the parent package at its [CHANGELOG.md](https://github.com/add2cal/add-to-calendar-button/blob/main/CHANGELOG.md).

<br />

## 🙌 Contributing

Anyone is welcome to contribute, but mind the [guidelines](.github/CONTRIBUTING.md):

- [Bug reports](.github/CONTRIBUTING.md#bugs)
- [Feature requests](.github/CONTRIBUTING.md#features)
- [Pull requests](.github/CONTRIBUTING.md#pull-requests)

**IMPORTANT NOTE:** Run `npm install` and `npm run format` before you create any pull request!

<br />

## 📃 Copyright and License

Copyright (c) [Jens Kuerschner](https://jenskuerschner.de).

Licensed under [Elastic License 2.0 (ELv2)](LICENSE.txt).

**About open-source**:
We consider ourselves open-source.
However, we are also aware of the controversy coming with licenses like the one selected.
Therefore, and contrary to many other companies and products, we no longer use the term in any marketing statements unless it is about other pieces which really are under an official OSI license.

Speaking **about the license**:
We love it, because it is so simple. Have a look!
You are basically free to do anything unless you are not offering the tool itself as a product or service; or want to remove copyright and license stuff.
In doubt, simply ask and we find a way. :)

<br />

---

<br />

## 💜 Kudos go to

...all contributors and people involved! Thanks a lot!

Find more details at [the respective parent repo section here...](https://github.com/add2cal/add-to-calendar-button#-kudos-go-to)

<br />
