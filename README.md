# Koodall Arcloud IOS Swift
[![](https://www.koodall.ai/media/images/logo/logo-color.svg)](https://www.koodall.ai/)

Quick start examples for integrating [Koodall SDK on iOS](https://docs.koodall.ai/face-ar-sdk-v1/ios/ios_getting_started) into Swift apps.  
  
# Getting Started

1. GGet the Koodall SDK client token. Please contact us via [sales@koodall.ai](mailto:sales@koodall.ai).
2. Install [CocoaPods](https://guides.cocoapods.org/using/getting-started.html) if you don't have it.
3. Install required project dependencies by running `pod install`.
4. Copy and Paste your client token into appropriate section of `arcloud-ios-swift/arcloud-ios-swift/BanubaClientToken.swift`
5. Open generated workspace (not a project!) in Xcode and run the example.

# AR Cloud

 1. Get the latest KoodallARCloud SDK archive for iOS and the AR cloud URL. Please contact us via [sales@koodall.ai](mailto:sales@koodall.ai).
 2. Copy `KoodallARCloudSDK.xcframework` into `arcloud-ios-swift/Frameworks/`
 3. Copy `KoodallUtilities.xcframework` into `arcloud-ios-swift/Frameworks/`
 4. Copy and Paste your AR cloud URL into [koodallArCloudURL](/arcloud-ios-swift/KoodallClientToken.swift#L4) property or use predefined Demo bucket

# Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# Testing

The project contains XCUITest in `arcloud-ios-swiftUITests`. For correct tests work `UItest` album should be created on device and should contain at least one photo and one video inside.

