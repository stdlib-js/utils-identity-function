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

# Identity Function

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Identity function.



<section class="usage">

## Usage

```javascript
import identity from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-identity-function@deno/mod.js';
```

#### identity( x )

Returns `x`.

```javascript
var v = identity( 3.14 );
// returns 3.14

var input = [];
var output = identity( input );
var bool = ( input === output );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
import identity from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-identity-function@deno/mod.js';

var v = identity( 3.14 );
// returns 3.14

v = identity( true );
// returns true

v = identity( null );
// returns null

v = identity( void 0 );
// returns undefined

v = identity();
// returns undefined
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/utils-constant-function`][@stdlib/utils/constant-function]</span><span class="delimiter">: </span><span class="description">constant function.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/utils-identity-function.svg
[npm-url]: https://npmjs.org/package/@stdlib/utils-identity-function

[test-image]: https://github.com/stdlib-js/utils-identity-function/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/utils-identity-function/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/utils-identity-function/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/utils-identity-function?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/utils-identity-function.svg
[dependencies-url]: https://david-dm.org/stdlib-js/utils-identity-function/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/utils-identity-function/tree/deno
[umd-url]: https://github.com/stdlib-js/utils-identity-function/tree/umd
[esm-url]: https://github.com/stdlib-js/utils-identity-function/tree/esm
[branches-url]: https://github.com/stdlib-js/utils-identity-function/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/utils-identity-function/main/LICENSE

<!-- <related-links> -->

[@stdlib/utils/constant-function]: https://github.com/stdlib-js/utils-constant-function/tree/deno

<!-- </related-links> -->

</section>

<!-- /.links -->
