# SwiftyVIN 1.3.1

A Swift version of VIN validations using Swift 5.0

## Getting Started

Just after installation

```
import SwiftyVIN
```

Create SwiftyVIN object

```
let swiftyVin: SwiftyVIN = SwiftyVIN("")
```

Then validate

```
swiftyVin.isValid()
```

## Debug mode

To enable debug mode

```
SwiftyVINLogger.shared.debugMode = true
```


### Installing

Add the following inside your podfile

```

use_frameworks!

pod 'SwiftyVIN'

```

Then

```
pod install

```

## Running the tests

Checking valid and invalid VIN with 100% code coverage.


## Reference

* [VIN.pdf](http://assets.ibc.ca/Documents/Auto%20Insurance/brochure/Understanding-Vehicle-Identification-Numbers.pdf) - VIN document.
* inspired from [python-libvin](https://github.com/h3/python-libvin)

## Authors

* **Majd Sabah** - *Initial work* - [sbhmajd](https://github.com/sbhmajd)
