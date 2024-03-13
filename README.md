# Flutter Native Splash Screen

This is a sample app for building native splash screen in flutter.

# Usage

First, add flutter_native_splash as a dependency in your pubspec.yaml file.

```bash
  dependencies:
  flutter_native_splash: ^2.3.13
```

In pubspec.yaml file below dependencies add the following to update the splash icon and background color of splash screen: 
```bash
  flutter_native_splash:
  android: true
  ios: true
  web: false
  color: "#FFFF00"
  image: "assets/images/splash_icon.png"
```
Run the following command in the terminal: 
```bash
flutter clean
flutter pub get
flutter pub run flutter_native_splash:create
```
## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#FFFF00](https://via.placeholder.com/10/0a192f?text=+) #FFFF00|

## Screenshots
![splash](https://github.com/Neelambansal/splash_screen_flutter/assets/20795058/8e909730-95ed-443b-a81a-1ea9f0acf127)
![home_screen](https://github.com/Neelambansal/splash_screen_flutter/assets/20795058/f447174a-bfab-4365-8ac5-edc1534da96f)

