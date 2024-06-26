# Changelog

## 5.4.0

* Add Typescript types

## 5.3.0

* Apply https://github.com/aackerman/circular-dependency-plugin/pull/49

## 5.2.2

* Fixed an issue where typescript modules were identified as having a circular dependency on themselves in Webpack 5

## 5.2.1

* Fixed an issue where modules that do not include themselves were marked as having circular dependencies

## 5.2.0

* Webpack 5 compatibility

## 5.1.0

* Added `include` option to allow checking only certain directories

## 5.0.1

* Set webpack peer dependency to greater than `4.0.1`

## 5.0.0

* Support for webpack 4
* Exclude logic will now be checked regardless of presence of `onDetected` method

## 4.4.0

* Added `onStart` and `onEnd` callbacks

## 4.3.0

* Added `cwd` parameter to allow setting the current working directory for displaying module paths

## 4.2.0

* The webpack module record is now passed into the `onDetected` callback

## 4.1.0

* Added support for the `ModuleConcatenationPlugin` from webpack

## 4.0.0

* Dropped support for Node 4.x

## 3.0.0

* Started using Error objects instead of plain strings for webpack compilation warnings/errors
