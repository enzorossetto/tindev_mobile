# Tindev - Mobile version

## To run

1. You must have [NodeJS](https://nodejs.org/en/download/) and [Yarn](https://classic.yarnpkg.com/en/docs/install/) on your machine
2. Open the repository folder on your terminal and run `yarn` to install it's dependencies
3. Run a device emulator (Android or iOS) or plug a device USB debug mode on
   - If running on Android emulator also run the command `adb reverse tcp:3333 tcp:3333` on your terminal after the emulator starts
4. Run the command for your platform:
   - Android: `npx react-native run-android` 
   - iOS: `npx react-native run-ios`
5. And finally run `npx react-native start`

> Never tested on iOS because I don't have an Apple device