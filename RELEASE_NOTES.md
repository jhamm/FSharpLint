##### 0.1.14 - January 18 2015

* Added a new rule `CanBeReplacedWithComposition` to the `FSharpLint.FunctionReimplementation` analyser: http://fsprojects.github.io/FSharpLint/FSharpLint.FunctionReimplementation.html

##### 0.1.13 - January 11 2015

* Fixed bug: https://github.com/fsprojects/FSharpLint/issues/63
* Fixed bug: https://github.com/fsprojects/FSharpLint/issues/57
* Files can now be ignored via the .fsproj file: https://github.com/fsprojects/FSharpLint/issues/55
* FAKE task now reports on how many files were linted and how many warnings were found.
* FAKE task now includes more detailed information on failure.
* FAKE task now includes an option to fail the build if any warnings are found.

##### 0.1.12 - December 16 2014

* Fixed bug: https://github.com/fsprojects/FSharpLint/issues/57

##### 0.1.11 - November 23 2014

* FSharp.Compiler.Service now included as a strongly named assembly.
* TargetFrameworkVersion now taken from the project file: https://github.com/fsprojects/FSharpLint/issues/52

##### 0.1.10 - November 19 2014

* Dropped MSBuild tools back down from 12 to 4 to support VS2010

##### 0.1.9 - November 17 2014

* Updated `FSharp.Compiler.Service` for compatibility with VisualFSharpPowerTools: https://github.com/fsprojects/FSharpLint/issues/51

##### 0.1.8 - November 15 2014

* FSharp.Core lookup now supports F# 4, the package is now a single click install in VS 2015 preview

##### 0.1.7 - November 14 2014

* Added support for SuppressMessageAttribute for the Typography analyser
* Fixed bug: https://github.com/fsprojects/FSharpLint/issues/48
* Fixed bug: https://github.com/fsprojects/FSharpLint/issues/47
* Attempted to fix assembly resolution issues by including FParsec built against FSharp.Core 4.3.0.0
* Added FAKE task to the nuget package

##### 0.1.6 - October 25 2014

* Added `FSharpLint.Binding.TupleOfWildcards` rule
* Fixed bug: https://github.com/fsprojects/FSharpLint/issues/38

##### 0.1.5 - October 24 2014

* Added support for `SuppressMessageAttribute` for all analysers except `FSharpLint.Typography`
* Added FAKE task, thanks to [@archaeron](https://github.com/archaeron) for this contribution

##### 0.1.4 - October 21 2014

* Fixed bug: https://github.com/fsprojects/FSharpLint/issues/36

##### 0.1.3 - October 16 2014

* Implemented new analyser: `FSharpLint.RaiseWithTooManyArguments`
* Implemented new rule: `FSharpLint.Binding.WildcardNamedWithAsPattern`

##### 0.1.2 - October 14 2014

* More hints and support added for matching if statements, tuples, lists, array, and patterns with hints

##### 0.1.1 - September 28 2014

* Fixed bug: literals in pattern matches were generating lint warnings saying that they should be camel case, whereas they must be pascal case.

##### 0.1.0 - September 25 2014

* First release
