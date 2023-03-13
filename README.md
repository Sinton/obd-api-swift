# obd-api-swift

## Introduction

A Swift API for use with an ELM327-based OBD-II interface to reading vehicle engine data

## 🖥️ Installation

### Requirements

* iOS 13 (SwiftUI require iOS 13.0) or iPadOS 13
* Xcode 14 and Swift 5.6
* No MacOS, and WatchOS support for now

### Install

#### Swift Package Manager (Recommended)

```swift
let package = Package(
    // ...
    dependencies: [
        .package(
            url: "https://github.com/Sinton/obd-api-swift.git",
            from: "1.0.0"
        )
    ],
    targets: [
        .target(
            name: "MyTarget",
            dependencies: ["obd-api-swift"]
        ),
    ]
)
```

You can install obd-api-swift into your Xcode project via SPM. 
To learn more about SPM, click [here](https://swift.org/package-manager/)
1. In Xcode 14, open your project and navigate to **File** → **Swift Packages** → **Add Package Dependency...**

For Xcode 14, navigate to **Files** → **Add Package**

1. Paste the repository URL (`https://github.com/Sinton/obd-api-swift`) and click **Next**.
2. For **Version**, verify it's **Up to next major**.
3. Click **Next** and Apple will access your app 

### CocoaPods

To integrate obd-api-swift into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
pod 'obd-api-swift'
```

### Manual

Clone the repo and drag files from `Sources` folder into your Xcode project.

## 🛠️ Usage

```swift
var OdbCommand(OBD_RPM)
```

## License

RunIt is available under the MIT license. See LICENSE for details.