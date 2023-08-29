# mmb-demos/cordova-splashscreen

Demo project to test the Android 12 SplashScreen API included into the core of the Cordova-Android platform since [cordova-android@11 release (Jul. 12, 2022)](https://cordova.apache.org/announcements/2022/07/12/cordova-android-release-11.0.0.html).

## Getting Started

You can test any app icon for splashscreen.
The app icon must be a [vector drawable](https://developer.android.com/develop/ui/views/graphics/vector-drawable-resources).

### Prerequisites

[Cordova get started](https://cordova.apache.org/#getstarted)

```sh
% npm i -g cordova
```

### Installing

```sh
% cordova platform add android@11.0.0 --save
```

### Running locally

```sh
% cordova run android
```

If you change assets you could need to clean build to avoid compile errors:

```sh
% cordova clean android
% cordova run android
```

## Authors

* [vdias38](https://github.com/vdias38) - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
