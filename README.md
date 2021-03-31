# good-enough-javascript
An opinionated curated list for a simple modern frontend

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


---

|Name                     |Repository                                         |NPM name               |License                                                           |minified + gzip                                               |tree-shaking                                                        |dependency count                                                        |Notes                                                                                                                                    |Browser fallback|
|-------------------------|---------------------------------------------------|-----------------------|------------------------------------------------------------------|--------------------------------------------------------------|--------------------------------------------------------------------|------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|----------------|
|DOM + UI                 |https://github.com/alpinejs/alpine                 |alpinejs               |![Badge](https://badgen.net/github/license/alpinejs/alpine)       |![Badge](https://badgen.net/bundlephobia/minzip/alpinejs)     |![Badge](https://badgen.net/bundlephobia/tree-shaking/alpinejs)     |![Badge](https://badgen.net/bundlephobia/dependency-count/alpinejs)     |                                                                                                                                         |                |
|Auto Complete            |https://github.com/alphagov/accessible-autocomplete|accessible-autocomplete|![Badge](https://badgen.net/github/license/alphagov/accessible-autocomplete)|![Badge](https://badgen.net/bundlephobia/minzip/accessible-autocomplete)|![Badge](https://badgen.net/bundlephobia/tree-shaking/accessible-autocomplete)|![Badge](https://badgen.net/bundlephobia/dependency-count/accessible-autocomplete)|                                                                                                                                         |                |
|Carousel                 |https://github.com/rcbyr/keen-slider               |keen-slider            |![Badge](https://badgen.net/github/license/rcbyr/keen-slider)     |![Badge](https://badgen.net/bundlephobia/minzip/keen-slider)  |![Badge](https://badgen.net/bundlephobia/tree-shaking/keen-slider)  |![Badge](https://badgen.net/bundlephobia/dependency-count/keen-slider)  |                                                                                                                                         |                |
|Charts                   |https://github.com/chartjs/Chart.js                |chart.js               |![Badge](https://badgen.net/github/license/chartjs/Chart.js)      |![Badge](https://badgen.net/bundlephobia/minzip/chart.js)     |![Badge](https://badgen.net/bundlephobia/tree-shaking/chart.js)     |![Badge](https://badgen.net/bundlephobia/dependency-count/chart.js)     |Version 3 is still in beta                                                                                                               |                |
|Conditionally class names|https://github.com/JedWatson/classnames            |classnames             |![Badge](https://badgen.net/github/license/JedWatson/classnames)  |![Badge](https://badgen.net/bundlephobia/minzip/classnames)   |![Badge](https://badgen.net/bundlephobia/tree-shaking/classnames)   |![Badge](https://badgen.net/bundlephobia/dependency-count/classnames)   |                                                                                                                                         |                |
|Dates                    |https://github.com/date-fns/date-fns               |date-fns               |![Badge](https://badgen.net/github/license/date-fns/date-fns)     |![Badge](https://badgen.net/bundlephobia/minzip/date-fns)     |![Badge](https://badgen.net/bundlephobia/tree-shaking/date-fns)     |![Badge](https://badgen.net/bundlephobia/dependency-count/date-fns)     |                                                                                                                                         |                |
|Dynamic font size        |https://github.com/rikschennink/fitty              |fitty                  |![Badge](https://badgen.net/github/license/rikschennink/fitty)    |![Badge](https://badgen.net/bundlephobia/minzip/fitty)        |![Badge](https://badgen.net/bundlephobia/tree-shaking/fitty)        |![Badge](https://badgen.net/bundlephobia/dependency-count/fitty)        |                                                                                                                                         |                |
|Lazy load elements       |https://github.com/verlok/vanilla-lazyload         |vanilla-lazyload       |![Badge](https://badgen.net/github/license/verlok/vanilla-lazyload)|![Badge](https://badgen.net/bundlephobia/minzip/vanilla-lazyload)|![Badge](https://badgen.net/bundlephobia/tree-shaking/vanilla-lazyload)|![Badge](https://badgen.net/bundlephobia/dependency-count/vanilla-lazyload)|Safari doesn't have support for native lazy loading, and Firefox only support lazy load for image elements. Also has more functionality. |Yes             |
|Modal                    |https://github.com/Ghosh/micromodal                |micromodal             |![Badge](https://badgen.net/github/license/Ghosh/micromodal)      |![Badge](https://badgen.net/bundlephobia/minzip/micromodal)   |![Badge](https://badgen.net/bundlephobia/tree-shaking/micromodal)   |![Badge](https://badgen.net/bundlephobia/dependency-count/micromodal)   |                                                                                                                                         |                |
|Smooth scroll            |https://github.com/zengabor/zenscroll              |zenscroll              |![Badge](https://badgen.net/github/license/zengabor/zenscroll)    |![Badge](https://badgen.net/bundlephobia/minzip/zenscroll)    |![Badge](https://badgen.net/bundlephobia/tree-shaking/zenscroll)    |![Badge](https://badgen.net/bundlephobia/dependency-count/zenscroll)    |Has a bunch of other features that are not available with the native implementation. Safari doesn’t support CSSOM Scroll-behavior.       |Yes             |
|Table of contents        |https://github.com/tscanlin/tocbot                 |tocbot                 |![Badge](https://badgen.net/github/license/tscanlin/tocbot)       |![Badge](https://badgen.net/bundlephobia/minzip/tocbot)       |![Badge](https://badgen.net/bundlephobia/tree-shaking/tocbot)       |![Badge](https://badgen.net/bundlephobia/dependency-count/tocbot)       |                                                                                                                                         |                |
|Tabs                     |https://github.com/cferdinandi/tabby               |tabbyjs                |![Badge](https://badgen.net/github/license/cferdinandi/tabby)     |![Badge](https://badgen.net/bundlephobia/minzip/tabbyjs)      |![Badge](https://badgen.net/bundlephobia/tree-shaking/tabbyjs)      |![Badge](https://badgen.net/bundlephobia/dependency-count/tabbyjs)      |                                                                                                                                         |                |
|Utility library          |https://github.com/lodash/lodash                   |lodash                 |![Badge](https://badgen.net/github/license/lodash/lodash)         |![Badge](https://badgen.net/bundlephobia/minzip/lodash)       |![Badge](https://badgen.net/bundlephobia/tree-shaking/lodash)       |![Badge](https://badgen.net/bundlephobia/dependency-count/lodash)       |                                                                                                                                         |                |
|Accordion                |https://github.com/rstacruz/details-polyfill       |details-polyfill       |![Badge](https://badgen.net/github/license/rstacruz/details-polyfill)|![Badge](https://badgen.net/bundlephobia/minzip/details-polyfill)|![Badge](https://badgen.net/bundlephobia/tree-shaking/details-polyfill)|![Badge](https://badgen.net/bundlephobia/dependency-count/details-polyfill)|https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details                                                                        |Yes             |
