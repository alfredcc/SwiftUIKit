<p align="center">
    <img src ="Resources/Logo.png" alt="SwiftUIKit" title="SwiftUIKit Logo" width=500 />
</p>

<p align="center">
    <img src="https://img.shields.io/github/v/release/danielsaidi/SwiftUIKit?color=%2300550&sort=semver" alt="Version" />
    <img src="https://img.shields.io/badge/platform-SwiftUI-red.svg" alt="Swift UI" />
    <img src="https://img.shields.io/badge/Swift-5.3-orange.svg" alt="Swift 5.3" />
    <img src="https://img.shields.io/github/license/danielsaidi/SwiftUIKit" alt="MIT License" />
    <a href="https://twitter.com/danielsaidi">
        <img src="https://img.shields.io/badge/contact-@danielsaidi-blue.svg?style=flat" alt="Twitter: @danielsaidi" />
    </a>
</p>


## About SwiftUIKit

`SwiftUIKit` adds extra functionality to `SwiftUI`, like extensions to existing types and completely new views, pickers, utilites, services etc. 

`SwiftUIKit` is divided into these areas:

* Bridging
* Cameras
* Colors
* Data
* Documents
* Environment
* Extensions
* Files
* Gestures
* Navigation
* Pickers
* Presentation
* Printing
* Sharing
* Styles
* Views

You can explore these sections in the [documentation][Documentation] and the demo app.

### Important about 3.0

Moving to 3.0, larger and more conceptual parts will be moved from this library to separate, smaller libraries. Some examples are functionality that consists of many types (like the list and picker utils) and views that have great value in themselves. This will make the things in this library easier to understand and document, since they will require less context and coupling.


## Installation

### Swift Package Manager

```
https://github.com/danielsaidi/SwiftUIKit.git
```

### CocoaPods

```
pod DSSwiftUIKit
```


## Supported Platforms

SwiftUIKit supports `iOS 13`, `macOS 11`, `tvOS 13` and `watchOS 6`.

Many parts of the library only supports a few or a certain platform, where they make sense. Also, while some views compile on a certain platform, they may still render incorrectly. Please help improve this library by submitting PRs that improve the rendering on e.g. macOS.  


## Documentation

The [online documentation][Documentation] contains more information, code examples etc. and makes it easy to overview the various parts of the library.

Note that the online documentation is currently built for macOS. To generate documentation for another platform, open the package in Xcode, select the correct simulator then generate documentation from the `Product` menu.

Any help in making the documentation multi-platform would be greatly appreciated.


## Demo Application

This project contains a demo app that lets you explore WebViewKit on iOS and macOS. To run it, just open and run `Demo/Demo.xcodeproj`.


## Support

You can sponsor this project on [GitHub Sponsors][Sponsors] or get in touch for paid support.


## Contact

Feel free to reach out if you have questions or if you want to contribute in any way:

* E-mail: [daniel.saidi@gmail.com][Email]
* Twitter: [@danielsaidi][Twitter]
* Web site: [danielsaidi.com][Website]


## License

SwiftUIKit is available under the MIT license. See the [LICENSE][License] file for more info.



[Email]: mailto:daniel.saidi@gmail.com
[Twitter]: http://www.twitter.com/danielsaidi
[Website]: http://www.danielsaidi.com
[Sponsors]: https://github.com/sponsors/danielsaidi

[Documentation]: https://danielsaidi.github.io/SwiftUIKit/documentation/swiftuikit/
[DocumentationZip]: https://github.com/danielsaidi/Documentation/blob/main/Docs/SwiftUIKit.doccarchive.zip?raw=true
[License]: https://github.com/danielsaidi/SwiftUIKit/blob/master/LICENSE
