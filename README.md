# VisualConstraints

[![CI Status](http://img.shields.io/travis/Catalina Turlea/VisualConstraints.svg?style=flat)](https://travis-ci.org/Catalina Turlea/VisualConstraints)
[![Version](https://img.shields.io/cocoapods/v/VisualConstraints.svg?style=flat)](http://cocoadocs.org/docsets/VisualConstraints)
[![License](https://img.shields.io/cocoapods/l/VisualConstraints.svg?style=flat)](http://cocoadocs.org/docsets/VisualConstraints)
[![Platform](https://img.shields.io/cocoapods/p/VisualConstraints.svg?style=flat)](http://cocoadocs.org/docsets/VisualConstraints)

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

VisualConstraints is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "VisualConstraints"
```

## Usage

To use the Categories in your project make sure to use 

```ruby
#import <VisualConstraints/VisualConstraints.h>
```

The methods to add constraints to UI elements are pretty straight forward and easy to use:

```
let contentView = UIView()
self.view.addSubview(contentView)

// Add the constraints
contentView.addConstraintsForWidth(300)
contentView.addConstraints(forWidth: 200)
contentView.addConstraintsToCenter() 
```

## Author

Catalina Turlea, catalina.turlea@gmail.com

## License

VisualConstraints is available under the MIT license. See the LICENSE file for more info.

