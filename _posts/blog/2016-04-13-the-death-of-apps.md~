---
layout: article
title:  "The Death of Native Mobile Apps"
categories: articles
modified: 2016-04-12
image:
  teaser: "dead_apps.jpg"
share: true
ads: false
---

[Progressive Web Applications](https://developers.google.com/web/progressive-web-apps?hl=en) will replace almost all native mobile apps in the near future.

New web technologies such as [push notifications](https://developers.google.com/web/updates/2015/03/push-notifications-on-the-open-web?hl=en), [offline web pages](https://github.com/slightlyoff/ServiceWorker/blob/master/explainer.md) and [installable web pages](https://developers.google.com/web/updates/2014/11/Support-for-installable-web-apps-with-webapp-manifest-in-chrome-38-for-Android?hl=en) mean that almost all functionality provided by a native application can come from a web page instead.

The advantages of using Progressive Web Applications (PWAs) over native apps are numerous:

 * quicker to develop and deploy
 * platform independent
 * lower barrier to adoption

There are, however, a few areas where native wins... for now:

 * in-app payments
 * access to sensors

In-app payments are well supported by the major app stores and can provide a significant revenue stream with low barrier-to-entry. PWAs will need to use web-based payment platforms such as PayPal which may increase friction to payment.
Access to some sensors, such as location and camera, came with HTML5. Unfortunately we are still lacking good support for many sensors, even those that are included in the HTML5 specification such as the Battery Status API and the Network Information API. Further sensors such as proximity, light, gyroscope etc may have limited support which means that native applications are required where these are necessary.

Perhaps most importantly for the world of Bluetooth beacons is the Web Bluetooth API. This will allow web pages to interact directly with Bluetooth devices - for example to control a Bluetooth light or get data from a Bluetooth heart rate monitor. Unfortunately at the time of writing there is [0% browser support](http://caniuse.com/#feat=web-bluetooth) for this API.

![CanIUse.com Web Bluetooth](/images/webbluetooth.png)

If you have a mobile project coming up it is worth seriously considering if a PWA will do everything you need, at a lower cost to native.	
