# @turf/isobands

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## isobands

Takes a square or rectangular grid [FeatureCollection][1] of [Point][2] features with z-values and an array of
value breaks and generates filled contour isobands.

### Parameters

*   `pointGrid` **[FeatureCollection][1]<[Point][2]>** input points - must be square or rectangular
*   `breaks` **[Array][3]<[number][4]>** where to draw contours
*   `options` **[Object][5]** options on output (optional, default `{}`)

    *   `options.zProperty` **[string][6]** the property name in `points` from which z-values will be pulled (optional, default `'elevation'`)
    *   `options.commonProperties` **[Object][5]** GeoJSON properties passed to ALL isobands (optional, default `{}`)
    *   `options.breaksProperties` **[Array][3]<[Object][5]>** GeoJSON properties passed, in order, to the correspondent isoband (order defined by breaks) (optional, default `[]`)

Returns **[FeatureCollection][1]<[MultiPolygon][7]>** a FeatureCollection of [MultiPolygon][7] features representing isobands

[1]: https://tools.ietf.org/html/rfc7946#section-3.3

[2]: https://tools.ietf.org/html/rfc7946#section-3.1.2

[3]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array

[4]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

[5]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[6]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[7]: https://tools.ietf.org/html/rfc7946#section-3.1.7

<!-- This file is automatically generated. Please don't edit it directly. If you find an error, edit the source file of the module in question (likely index.js or index.ts), and re-run "yarn docs" from the root of the turf project. -->

---

This module is part of the [Turfjs project](https://turfjs.org/), an open source module collection dedicated to geographic algorithms. It is maintained in the [Turfjs/turf](https://github.com/Turfjs/turf) repository, where you can create PRs and issues.

### Installation

Install this single module individually:

```sh
$ npm install @turf/isobands
```

Or install the all-encompassing @turf/turf module that includes all modules as functions:

```sh
$ npm install @turf/turf
```
