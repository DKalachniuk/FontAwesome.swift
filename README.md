# FontAwesome.swift

[![Build Status](http://img.shields.io/travis/thii/FontAwesome.swift.svg?style=flat)](https://travis-ci.org/thii/FontAwesome.swift)
[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/FontAwesome.swift.svg)](https://img.shields.io/cocoapods/v/FontAwesome.swift.svg)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![Platform](https://img.shields.io/cocoapods/p/FontAwesome.swift.svg?style=flat)](http://cocoadocs.org/docsets/FontAwesome.swift)
[![License](https://img.shields.io/cocoapods/l/FontAwesome.swift.svg)](https://raw.githubusercontent.com/thii/FontAwesome.swift/master/LICENSE)

Use FontAwesome < 5 in your Swift projects. Updated with swift 4.2 and Xcode 10
### Use branch swift4.2_fontawesome4 for that!

To see the complete set of 3,978 icons in Font Awesome 5, please check the [FontAwesome.com](http://fontawesome.com/icons/) site.


## Examples
![](./.github/examples.png)

## Installation

### Carthage

    github "thii/FontAwesome.swift"

### CocoaPods

    pod 'FontAwesome.swift', :git => 'https://github.com/DKalachniuk/FontAwesome.swift', :branch => 'swift4.2_fontawesome4'

**Note**: If you install this using CocoaPods, the framework name will be
`FontAwesome_swift` (there is an underscore).

### Manually
- Drag and drop all `.otf` and `.swift` files into your project

## Requirements

iOS 8 or later.

## Development
To update this project to include all the latest icons from the new verison of
Font Awesome (replace `x.y.z` with the new font version):

    bundle exec fastlane update_font version:x.y.z

To release a new version `x.y.z` (replace `x.y.z` with a real version number):

    bundle exec fastlane release version:x.y.z

Since it will automatically make a new commit to bump version and push to CocoaPods
trunk, make sure you have write access to this repo and be one of the podspec owners.
If you are a maintainer but don't have these privilege yet, please let me know.

## License
- All font files licensed under [SIL OFL 1.1](http://scripts.sil.org/OFL)
- FontAwesome.swift licensed under [MIT](http://thi.mit-license.org/)
