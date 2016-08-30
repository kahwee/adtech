# ad-resources

These are resources to libraries that are relating to the advertising technology (adtech) industry.

Feel free to do a pull request to add a library that you know of.

# Contents

* [IAB Standards](#iab-standards)
  * [HTML5 recommendations](#html5-recommendations)
  * [VAST](#vast)
    * [VAST 4.0](#vast-40)
  * [VPAID](#vpaid)
* [Players](#players)
  * [Flowplayer](#flowplayer)
  * [Video.js](#videojs)

# IAB standards

## General

* [iab HTML5 guidelines](http://www.iab.com/guidelines/html5-for-digital-advertising-1-0-guidance-for-ad-designers-creative-technologists/) [Google Doc](https://docs.google.com/document/d/1pesMB5eec_kVEczQ5DOY12ZPdpEn4Fhe8fh_Ray96BY/edit)
* [Digital Video Glossary](http://www.iab.com/news/iab-launches-digital-video-glossary/)

## VAST

### VAST 4.0

VAST 4.0 is in draft. What's new:

* A new element to separate the video file for linear ads from files that use an API framework for interaction along with guidance on how to serve linear media files with VAST
* A new viewable impression tracking element to support publishers’ ability to track viewability and better manage campaign delivery

Currently in [draft published in IAB's website](http://www.iab.com/guidelines/digital-video-ad-serving-template-vast-4-0/).

* [What's a VAST?](http://www.iab.com/news/whats-vast-understanding-iab-digital-video-suite/)
* [Daily Motion vast-client](https://github.com/dailymotion/vast-client-js)

## VPAID

VPAID is the standard to play interactive advertisements. There are more JavaScript implementation today.

* [VPAID ad inspector](https://github.com/kahwee/vpaid-ad-inspector)
* [Ryan Thompson's examples](https://github.com/ryanthompson591/vpaidExamples/)
* [Adobe Animate CC bridge](https://github.com/kahwee/animate-vpaid-bridge)
  * Use this [VAST tag](https://s3.amazonaws.com/animate-vpaid-bridge/sample-1.xml) to test on JW Player or something.
* [VPAID ad base](https://github.com/kahwee/vpaid-ad)

# Players

## Varrando

Smallest HTML5 video player, single file no dependencies: <50kb.

Complete, performant, error-free VAST 3.0/VPAID 2.0/VMAP JS implementations. Google IMA support as well.

Ad fill and revenue maximization algorithms included. Given us a list of video ad sources. It calls every ad network in parallel and optimizes revenue based on CPM.

New ad scheduling algorithm: schedule ad breaks across a user session (eg. every X minutes or every X videos).

* [Player Demo](https://varrando.com/demo/)
* [Video Demo of the platform](https://www.youtube.com/watch?v=8jhRMaClUjI)


## Brightcove player

Brightcove does not have a demo page.

## JW Player

JW Player allows customization of player's look and feel. It also supports VAST and VPAID in JavaScript.

* [Demo](https://developer.jwplayer.com/tools/ad-tester/)

## Flowplayer

* [Pricing](https://flowplayer.org/pricing/player.html)
* [VPAID support](https://github.com/mantisadnetwork/flowplayer-vpaid)

## Video.js

### Ad plugins

* [videojs-contrib-ads](https://github.com/videojs/videojs-contrib-ads): Supports Video.js v5 but requires you to add in VAST and VPAID support on top of this.
* [MailOnline's VAST and VPAID plugin](https://github.com/MailOnline/videojs-vast-vpaid/): Support in Video.js v5 is coming. This is a full package and comes with VAST and VPAID support in a plugin.
