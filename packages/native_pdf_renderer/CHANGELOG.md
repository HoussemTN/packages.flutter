## 1.6.2

* Target sdk version for android upped to 28

## 1.6.1

* Added more tests
* Fixed `PDFPageImage.pageNumber` always returns `null`
* If page not in document throws `PdfPageNotFoundException`

## 1.6.0 

* Added more documentation for public properties and methods
* `crop` property in `render` method marked as deprecated, usage `cropRect` instead
* Added `isClosed` property for `PDFDocument` and `PDFPage`
* Added tests

## 1.5.0

* Added crop option for rendering (#11)
* Fixed bug with render same page from issue #5

## 1.4.2

* Fixed not correctly filling background Color on IOS

## 1.4.1

* Resolve supports Flutter v1.7

## 1.4.0+1

* Hotfix

## 1.4.0

* Now `format` and `backgroundColor` options for image rendering works on IOS.

## 1.3.0+1

* Hotfix

## 1.3.0

* Added `format` and `backgroundColor` options for image rendering.
  *Attention*: it feature works only on Android platform! 
* Added dart linter
* Refactoring existing code

## 1.2.3

* Scale fix on IOS

## 1.2.2

* Upgrade to Swift 5

## 1.2.1

* Fix IOS build error

## 1.2.0

* Optimized UI freezes on android platform

## 1.1.2

* Update readme

## 1.1.1

* Fix compilation error on pure android Java projects (#1)

## 1.1.0

* Transferred sources to `src` directory
* Removed `dispose` method from `PDFDocument` class (Replaced by `close` method) 
* Added more comments in code

## 1.0.1

* Fixed support capability dart v2.0 (non 2.1) by add import `dart:core` in files with use `Future`

## 1.0.0

* Initial release
