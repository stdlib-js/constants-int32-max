<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Max Int32

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Maximum [signed 32-bit integer][max-int32].



<section class="usage">

## Usage

To use in Observable,

```javascript
INT32_MAX = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-int32-max@umd/bundle.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/constants-int32-max@umd/bundle.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.INT32_MAX;
})();
</script>
```

#### INT32_MAX

Maximum [signed 32-bit integer][max-int32].

```javascript
var bool = ( INT32_MAX === 2147483647 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/constants-int32-max@umd/bundle.js"></script>
<script type="text/javascript">
(function () {

console.log( INT32_MAX );
// => 2147483647

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/constants/int32/min`][@stdlib/constants/int32/min]</span><span class="delimiter">: </span><span class="description">minimum signed 32-bit integer.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-int32-max.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-int32-max

[test-image]: https://github.com/stdlib-js/constants-int32-max/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/constants-int32-max/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-int32-max/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-int32-max?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-int32-max.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-int32-max/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-int32-max/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-int32-max/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-int32-max/tree/esm

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-int32-max/main/LICENSE

[max-int32]: http://en.wikipedia.org/wiki/2147483647

<!-- <related-links> -->

[@stdlib/constants/int32/min]: https://github.com/stdlib-js/constants-int32-min/tree/umd

<!-- </related-links> -->

</section>

<!-- /.links -->
