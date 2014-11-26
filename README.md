# Titanium Docs
The Appcelerator [Titanium & Alloy Documentation](http://docs.appcelerator.com/titanium/latest/) packaged as a MacOS/Windows/Linux desktop app for fast, offline access. Build using [TideSDK](http://www.tidesdk.org) and the [Continuous Builds](http://builds.appcelerator.com/#docs) of the static online documentation.

![](screenshot.png)

## How to install

**NOTE:** I've only done MacOS builds so far, since that's my platform. Feel free to send PRs with updated `tiapp.xml` and the build attached (see *How to update*).

1. Download the latest DMG from [Releases](https://github.com/FokkeZB/Titanium-Docs/releases).
2. Mount the image.
3. Drag the *Titanium Docs* app to the *Applications* folder.
4. Open *Titanium Docs* and find a nice spot for it in your dock ;)

## How to update

1. Go to [http://builds.appcelerator.com/#docs](http://builds.appcelerator.com/#docs).
2. Download the latest *Titanium Documentation*.
3. Extract the ZIP and move the contents of the extracted directory to `Resources/docs`.
4. In [tiapp.xml](tiapp.xml) update `<version>` with the 
5. Build the app (see *How to build*).
6. Send a PR and attach the compiled app found in `packages/[platform]`.

## How to build

1. Follow the [TideSDK Getting Started](http://tidesdk.multipart.net/docs/user-dev/generated/#!/guide/getting_started) to setup TideSDK on a machine running the same platform you want to build the app for.
2. Clone or [Download](https://github.com/FokkeZB/Titanium-Docs/archive/master.zip) this repository.
3. Import the downloaded repository as a project in *TideSDK Developer*.
4. Go to *Test & Package*.
5. Run *Package with Runtime*.

## Documentation copyright
© 2008—2014 Appcelerator Inc. All rights reserved. Appcelerator is a registered trademark