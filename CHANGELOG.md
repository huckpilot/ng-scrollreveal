<a name="2.0.2"></a>
## [2.0.2](https://github.com/tinesoft/ng-scrollreveal/compare/2.0.1...2.0.2) (2017-03-24)


### Bug Fixes

* **peerDependencies:** remove 'angular-cli-ghpages' from peerDependencies (accidentally added since v2.0.0) ([141e133](https://github.com/tinesoft/ng-scrollreveal/commit/141e133))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/tinesoft/ng-scrollreveal/compare/2.0.0...2.0.1) (2017-03-24)


### Bug Fixes

* **config:** export `NgsRevealConfig` service to allow global configuration ([a3c64cc](https://github.com/tinesoft/ng-scrollreveal/commit/a3c64cc)), closes [#6](https://github.com/tinesoft/ng-scrollreveal/issues/6)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/tinesoft/ng-scrollreveal/compare/1.0.1...v2.0.0) (2017-03-08)


### Code Refactoring

* **all:** move demo app to own folder and improve build tools ([504499b](https://github.com/tinesoft/ng-scrollreveal/commit/504499b))


### Features

* **all:** making [@IgorMinar](https://github.com/IgorMinar) happy all the way (it's just angular!) ([061c648](https://github.com/tinesoft/ng-scrollreveal/commit/061c648))


### BREAKING CHANGES

* all: rename UMD bundled file from `ng-scrollreveal.min.js` to `ng-scrollreveal.umd.js`
* all: rename package from `ng2-scrollreveal` to `ng-scrollreveal` to conform with new Angular Naming Guidelines.

This only affect how you install and import the library (no actual breaking changes in code).

Before:

```
npm install --save ng2-scrollreveal

...

import { NgsRevealModule } from 'ng2-scrollreveal';
```

After:

```
npm install --save ng-scrollreveal
...

import { NgsRevealModule } from 'ng-scrollreveal';
```



<a name="1.0.1"></a>
## [1.0.1](https://github.com/tinesoft/ng-scrollreveal/compare/1.0.0...1.0.1) (2016-11-27)



<a name="1.0.0"></a>
# 1.0.0 (2016-11-09)



