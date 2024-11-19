# @turf/point-to-polygon-distance

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## pointToPolygonDistance

Calculates the distance from a point to the edges of a polygon or multi-polygon.
Returns negative values for points inside the polygon.
Handles polygons with holes and multi-polygons.
A hole is treated as the exterior of the polygon.

### Parameters

*   `point` **([Feature][1]<[Point][2]> | [Point][2] | [Position][3])** Input point
*   `polygonOrMultiPolygon` **([Feature][1]<([Polygon][4] | [MultiPolygon][5])> | [Polygon][4] | [MultiPolygon][5])** Input polygon or multipolygon
*   `options` **[Object][6]** Optional parameters (optional, default `{}`)

    *   `options.units` **Units** Units of the result e.g. "kilometers", "miles", "meters"
    *   `options.method` **(`"geodesic"` | `"planar"`)** Method of the result

<!---->

*   Throws **[Error][7]** If input geometries are invalid

Returns **[number][8]** Distance in meters (negative values for points inside the polygon)

[1]: https://tools.ietf.org/html/rfc7946#section-3.2

[2]: https://tools.ietf.org/html/rfc7946#section-3.1.2

[3]: https://developer.mozilla.org/docs/Web/API/Position

[4]: https://tools.ietf.org/html/rfc7946#section-3.1.6

[5]: https://tools.ietf.org/html/rfc7946#section-3.1.7

[6]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[7]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Error

[8]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Number

<!-- This file is automatically generated. Please don't edit it directly. If you find an error, edit the source file of the module in question (likely index.js or index.ts), and re-run "yarn docs" from the root of the turf project. -->

---

This module is part of the [Turfjs project](https://turfjs.org/), an open source module collection dedicated to geographic algorithms. It is maintained in the [Turfjs/turf](https://github.com/Turfjs/turf) repository, where you can create PRs and issues.

### Installation

Install this single module individually:

```sh
$ npm install @turf/point-to-polygon-distance
```

Or install the all-encompassing @turf/turf module that includes all modules as functions:

```sh
$ npm install @turf/turf
```