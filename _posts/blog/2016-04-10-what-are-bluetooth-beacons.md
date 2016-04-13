---
layout: article
title:  "What are Bluetooth Beacons?"
categories: blog
modified: 2016-04-10
image:
    teaser: "beacon_sm2.jpg"
share: true
ads: false
---

So what's it all about? Bluetooth beacons are small, battery powered devices which have low-energy Bluetooth radios.

Bluetooth beacons have been in use for some time, mainly in the form of [iBeacon](https://en.wikipedia.org/wiki/IBeacon) - a proprietary protocol supported by Apple (and some other) devices. These beacons have unique identifiers which are linked to native applications, thus the user has to have the application installed to use the beacon.

A great example of iBeacons in use is the [Starbucks loyalty app](http://www.mobilecommercedaily.com/starbucks-cooks-up-ibeacon-strategy-to-support-premium-coffee-emphasis) (warning - slow website!).

The limitation of iBeacon is the dependency on a native mobile application.

In 2015, a team of engineers at Google developed the [Eddystone specification](https://en.wikipedia.org/wiki/Eddystone_(Google)). Unlike iBeacon this specification is open-source and platform independent, with the ability to broadcast not just a unique identifier but also a URL.

Broadcasting a URL over Bluetooth means that any device with Bluetooth capability can consume the information, no app required.

