# [3.0.0](https://github.com/smnbbrv/ngx-plyr/compare/v2.0.0...v3.0.0) (2019-07-24)


### Features

* turn playsinline and crossorigin attributes to be configurable as ngx-plyr parameters ([395ac3c](https://github.com/smnbbrv/ngx-plyr/commit/395ac3c))


### BREAKING CHANGES

* crossorigin and playsinline are no more set initially, please set the up manually as [plyrCrossOrigin]="true" and [plyrPlaysInline]="true"

# [2.0.0](https://github.com/smnbbrv/ngx-plyr/compare/v1.2.2...v2.0.0) (2019-07-22)


### Features

* upgrade to angular 8 ([f4a831e](https://github.com/smnbbrv/ngx-plyr/commit/f4a831e))


### BREAKING CHANGES

* angular 8 breaks the original behavior of ViewChild (and the library depends on it)

## [1.2.2](https://github.com/smnbbrv/ngx-plyr/compare/v1.2.1...v1.2.2) (2019-05-06)


### Bug Fixes

* plyr is recreated properly after options change, fix [#12](https://github.com/smnbbrv/ngx-plyr/issues/12) ([4f81dfc](https://github.com/smnbbrv/ngx-plyr/commit/4f81dfc))

## [1.2.1](https://github.com/smnbbrv/ngx-plyr/compare/v1.2.0...v1.2.1) (2019-04-08)


### Bug Fixes

* add keywords & badge for NPM ([a882108](https://github.com/smnbbrv/ngx-plyr/commit/a882108))

# [1.2.0](https://github.com/smnbbrv/ngx-plyr/compare/v1.1.1...v1.2.0) (2018-12-21)


### Features

* add hls.js and dash.js example integrations ([53f8a51](https://github.com/smnbbrv/ngx-plyr/commit/53f8a51))
* add plyr-driver ([8f6053f](https://github.com/smnbbrv/ngx-plyr/commit/8f6053f))

## [1.1.1](https://github.com/smnbbrv/ngx-plyr/compare/v1.1.0...v1.1.1) (2018-12-18)


### Bug Fixes

* add component export to public api, close [#1](https://github.com/smnbbrv/ngx-plyr/issues/1) ([5af440f](https://github.com/smnbbrv/ngx-plyr/commit/5af440f))

# [1.1.0](https://github.com/smnbbrv/ngx-plyr/compare/v1.0.0...v1.1.0) (2018-12-18)


### Features

* add attribute selector ([f14b3c9](https://github.com/smnbbrv/ngx-plyr/commit/f14b3c9))
* add plyrPlayerInit event ([f730424](https://github.com/smnbbrv/ngx-plyr/commit/f730424))
* add support for plyr initial options ([bdf5c6e](https://github.com/smnbbrv/ngx-plyr/commit/bdf5c6e))

# 1.0.0 (2018-12-18)


### Features

* init ([c36527f](https://github.com/smnbbrv/ngx-plyr/commit/c36527f))