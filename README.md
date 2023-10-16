# Reproduce Steps

step1. build CustomEnvApp

```shell
$ cd CustomEnvApp && yarn install
$ cd ios && pod install && cd ..
$ npx react-native run-ios
...

Build Succeeded
success Successfully built the app
...
success Successfully launched the app on the simulator
```

step2. build EnvApp

```shell
$ cd ../EnvApp && yarn install
$ cd ios && pod install && cd ..
$ npx react-native run-ios
...

error Failed to build iOS project. We ran "xcodebuild" command but it exited with error code 65. To debug build logs further, consider building your app with Xcode.app, by opening EnvApp.xcworkspace.
```