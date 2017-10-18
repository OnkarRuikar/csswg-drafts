# Spatial Navigation
This is the repository for making the Web excellently embrace the spatial navigation features so that the Web technology can be propagated into several industries such as TV, IVI, game console, and upcoming smart devices.

This repository consists of the basic description for spatial navigation, landscapes of the relevant industries, and the current status for [W3C standardization](explainer.md) and [Web engine implementation](impl.md) such as Blink, WebKit, Gecko, and EdgeHTML, while the relevant issues would be discussed in W3C working groups and Web engine open source communities.

You're welcome to contribute! If you have something to say for the spatial navigation, please kindly put it on [issues](https://github.com/lgeweb/spatial-navigation/issues) of this repository. Let's make the Web to be extensible for the several industries!

## Overview
**Spatial navigation (aka Snav)** is the ability to navigate between focusable elements based on their position within a structured document. Spatial navigation is often called the directional navigation which enables four directional navigation. Users are usually familiar with the 2-way navigation using tab key for the forward direction and shift+tab key for the backward direction, but not familiar with the 4-way navigation using arrow keys.

Regarding TV remote control, game console pad, IVI jog dial with 4-way keys, and Web accessibility, spatial navigation has been a rising important input mechanism in several industries. If the Web can embrace the spatial navigation and effectively support the functionalities in Web engines and W3C APIs, it will be more promising technology for existing products as mentioned above and various upcoming products.

## Motivation
Technical description
Use cases description
Industry description

## Mission
explainer link

## History
The history of WebKit, Blink, Gekco, and W3C

## FAQ
**Q. I’m not sure how the spatial (directional) navigation behavior work.**
  - You can see the video that shows the Snav behavior in the YouTube page ([link](https://www.youtube.com/watch?v=TzDtcX9urUg)).
  - You can see the brief description for the Snav in Wikipedia ([link](https://en.wikipedia.org/wiki/Spatial_navigation)).
  - In several references below, you can get the help to understand the Snav operations.

**Q. Isn’t it enough just using the relevant Web frameworks?**
  - Severel Web frameworks and extensions for the Snav have been provided so far due to no support from web engines. For examples, [js-spatial-navigation](https://github.com/luke-chang/js-spatial-navigation) made by Mozilla seems one of the frameworks and the quality would be good to support the features of Snav. [Spotlight library](https://github.com/enyojs/spotlight) made by LGE is an instance of the frameworks for the Snav, even though it was deprecated now. However, the support of Snav from Web frameworks has some limits. blahblah (aligning scrolling, particularily using native focus method for a11y)

**Q. The Snav seems not the general feature esp. in mobile with no physical key-based interface.**
  - Honestly, the mobile has been a first citizen of Snav about 10 years old. Before touch-based interface, the majority of interface for mobile was key-based methods. We're familiar with kind of mobile phone named a feature phone. In the future, the input methods for smart devices will be changed to something like voice command, hand gesture, and eyes direction, but the key-based interfaces will never disappear, even though it'll be used as a secondary method. It would be the most intuitive method with a strong feedback after pushing a key, while we couldn't imagine a touch-based keyboard without any physical keys.

**Q. Put the question on issues of this repository :D**
  - Everything for Snav is welcome

## Reference
- JavaScript Spatial Navigation (Mozilla)
  - https://github.com/luke-chang/js-spatial-navigation
- Spotlight library for spatial navigation (LG Electronics)
  - https://github.com/enyojs/spotlight **(deprecated)**
- Implementing TV remote control navigation (MDN)
  - https://developer.mozilla.org/en-US/docs/Mozilla/Firefox_OS_for_TV/TV_remote_control_navigation
- Focus navigation with keyboard, gamepad, and accessibility tools (MS)
  - https://docs.microsoft.com/en-us/windows/uwp/input-and-devices/managing-focus-navigation
- Designing for Xbox and TV (MS)
  - https://docs.microsoft.com/en-us/windows/uwp/input-and-devices/designing-for-tv
