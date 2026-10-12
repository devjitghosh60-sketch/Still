# Still

Still is a native iOS app for browsing movies, series, and anime from compatible add-ons and playing streams on-device.

## Download and install

Download the **Still iOS source** archive from [Releases](https://github.com/devjitghosh60-sketch/Still/releases), extract it, and open `Still/Still.xcodeproj` in Xcode.

Requirements: macOS with Xcode 16 or later, an iPhone running iOS 18 or later, and an Apple ID configured for development signing.

In Xcode, select the Still app target, open **Signing & Capabilities**, enable automatic signing, and select your own development team. If Xcode reports a bundle identifier conflict, change it to a unique value. Connect the iPhone, select it as the run destination, and press **Run**.

This package includes iPhone device frameworks; simulator builds are not included. Framework license notices are in `ThirdParty`. TorrServerKit is GPL-3.0 and MobileVLCKit is LGPL; TorrServerKit's corresponding source is linked in its notice.

In the app, use **Settings → Add-ons** to configure compatible add-ons. Still does not include media files. Use only sources and media you are authorized to access.
