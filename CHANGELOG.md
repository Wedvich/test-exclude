# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="4.0.0"></a>
# [4.0.0](https://github.com/istanbuljs/test-exclude/compare/v3.3.0...v4.0.0) (2017-01-19)


### Features

* add coverage to default excludes ([#23](https://github.com/istanbuljs/test-exclude/issues/23)) ([59e8bbf](https://github.com/istanbuljs/test-exclude/commit/59e8bbf))


### BREAKING CHANGES

* additional coverage folder is now excluded



<a name="3.3.0"></a>
# [3.3.0](https://github.com/istanbuljs/test-exclude/compare/v3.2.2...v3.3.0) (2016-11-22)


### Features

* allow include/exclude rules to be a string rather than array ([#22](https://github.com/istanbuljs/test-exclude/issues/22)) ([f8f99c6](https://github.com/istanbuljs/test-exclude/commit/f8f99c6))



<a name="3.2.2"></a>
## [3.2.2](https://github.com/istanbuljs/test-exclude/compare/v3.2.1...v3.2.2) (2016-11-14)


### Bug Fixes

* we no longer need to add node_modules/** rule ([d0cfbc3](https://github.com/istanbuljs/test-exclude/commit/d0cfbc3))



<a name="3.2.1"></a>
## [3.2.1](https://github.com/istanbuljs/test-exclude/compare/v3.2.0...v3.2.1) (2016-11-14)


### Bug Fixes

* fix bug matching files in root, introduced by dotfiles setting ([27b249c](https://github.com/istanbuljs/test-exclude/commit/27b249c))



<a name="3.2.0"></a>
# [3.2.0](https://github.com/istanbuljs/test-exclude/compare/v3.1.0...v3.2.0) (2016-11-14)


### Features

* adds *.test.*.js exclude rule ([#20](https://github.com/istanbuljs/test-exclude/issues/20)) ([34f5cba](https://github.com/istanbuljs/test-exclude/commit/34f5cba))



<a name="3.1.0"></a>
# [3.1.0](https://github.com/istanbuljs/test-exclude/compare/v3.0.0...v3.1.0) (2016-11-14)


### Features

* we now support dot folders ([f2c1598](https://github.com/istanbuljs/test-exclude/commit/f2c1598))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/istanbuljs/test-exclude/compare/v2.1.3...v3.0.0) (2016-11-13)


### Features

* always exclude node_modules ([#18](https://github.com/istanbuljs/test-exclude/issues/18)) ([b86d144](https://github.com/istanbuljs/test-exclude/commit/b86d144))


### BREAKING CHANGES

* `**/node_modules/**` is again added by default, but can be counteracted with `!**/node_modules/**`.



<a name="2.1.3"></a>
## [2.1.3](https://github.com/istanbuljs/test-exclude/compare/v2.1.2...v2.1.3) (2016-09-30)


### Bug Fixes

* switch lodash.assign to object-assign ([#16](https://github.com/istanbuljs/test-exclude/issues/16)) ([45a5488](https://github.com/istanbuljs/test-exclude/commit/45a5488))



<a name="2.1.2"></a>
## [2.1.2](https://github.com/istanbuljs/test-exclude/compare/v2.1.1...v2.1.2) (2016-08-31)


### Bug Fixes

* **exclude-config:** Use the defaultExcludes for anything passed in that is not an array ([#15](https://github.com/istanbuljs/test-exclude/issues/15)) ([227042f](https://github.com/istanbuljs/test-exclude/commit/227042f))



<a name="2.1.1"></a>
# [2.1.1](https://github.com/istanbuljs/test-exclude/compare/v2.1.0...v2.1.1) (2016-08-12)


### Bug Fixes

* it should be possible to cover the node_modules folder ([#13](https://github.com/istanbuljs/test-exclude/issues/13)) ([09f2788](https://github.com/istanbuljs/test-exclude/commit/09f2788))


<a name="2.1.0"></a>
# [2.1.0](https://github.com/istanbuljs/test-exclude/compare/v2.0.0...v2.1.0) (2016-08-12)


### Features

* export defaultExclude, so that it can be used in yargs' default settings ([#12](https://github.com/istanbuljs/test-exclude/issues/12)) ([5b3743b](https://github.com/istanbuljs/test-exclude/commit/5b3743b))



<a name="2.0.0"></a>
# [2.0.0](https://github.com/istanbuljs/test-exclude/compare/v1.1.0...v2.0.0) (2016-08-12)


### Bug Fixes

* use Array#reduce and remove unneeded branch in prepGlobPatterns ([#5](https://github.com/istanbuljs/test-exclude/issues/5)) ([c0f0f59](https://github.com/istanbuljs/test-exclude/commit/c0f0f59))


### Features

* don't exclude anything when empty array passed ([#11](https://github.com/istanbuljs/test-exclude/issues/11)) ([200ec07](https://github.com/istanbuljs/test-exclude/commit/200ec07))


### BREAKING CHANGES

* we now allow an empty array to be passed in, making it possible to disable the default exclude rules -- we will need to be mindful when pulling this logic into nyc.



<a name="1.1.0"></a>
# [1.1.0](https://github.com/bcoe/test-exclude/compare/v1.0.0...v1.1.0) (2016-06-08)


### Features

* set configFound if we find a configuration key in package.json ([#2](https://github.com/bcoe/test-exclude/issues/2)) ([64da7b9](https://github.com/bcoe/test-exclude/commit/64da7b9))



<a name="1.0.0"></a>
# 1.0.0 (2016-06-06)


### Features

* initial commit, pulled over some of the functionality from nyc ([3f1fce3](https://github.com/bcoe/test-exclude/commit/3f1fce3))
* you can now load include/exclude logic from a package.json stanza ([#1](https://github.com/bcoe/test-exclude/issues/1)) ([29b543d](https://github.com/bcoe/test-exclude/commit/29b543d))
