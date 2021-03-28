# good-enough-javascript
Simplify modern javascript.

Drop support for older browser. Ship less code, and run more things nativly. 

Browser support:
* Edge 16 and newer
* Chromium browsers, Firefox, and Safari: Two versions back and newer

Don't use jQuery or libraries that depends on jQuery. Keep it vanilla.

## Check dependencies with these tools
* https://bundlephobia.com/
* https://npm.anvaka.com

We don't want to use libraries that take up a lot of space, or has a lot of dependencies. That way all environemnts stays fast and secure. 

## DOM + UI
https://github.com/alpinejs/alpine

## Lazy load elements
Safari doesn't have support for native lazy loading, and Firefox only support lazy load for images.

https://github.com/verlok/vanilla-lazyload

## Dynamic font size
https://github.com/rikschennink/fitty

## Conditionally class name joiner
https://github.com/JedWatson/classnames

## Carousel
https://github.com/rcbyr/keen-slider

## Charts
https://github.com/chartjs/Chart.js

## Dates
https://github.com/date-fns/date-fns

## Smooth scroll
Has a bunch of other features that are not available with the native implementation.

https://github.com/zengabor/zenscroll

## Utility library
Don't import or install all of lodash. Install one method at a time, like this `npm i lodash.debounce`.

https://github.com/lodash/lodash

## Map
https://github.com/mapbox/mapbox-gl-js

## Scrollspy
https://github.com/cferdinandi/gumshoe

## Table of contents
https://github.com/tscanlin/tocbot

## Tabs
https://github.com/cferdinandi/tabby

## Modal
https://github.com/Ghosh/micromodal

## Accordion
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details

## Select
https://github.com/alphagov/accessible-autocomplete

## Dev dependencies

Use NPM over Yarn. Not everyone has Yarn installed. 

* Unit testing: [Jest](https://github.com/facebook/jest)
* Integration tests: [Cypress](https://github.com/cypress-io/cypress)
* Code formatter: [Prettier](https://github.com/prettier/prettier)
* Git hooks: [Husky](https://github.com/typicode/husky)
* CSS class name reduction: [Purge](https://github.com/FullHuman/purgecss)
