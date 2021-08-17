# BackgroundLocationRepro

This repository contains two projects both containing the exact same JavaScript code:
- A standard React Native project
- A bare workflow Expo project

To run either project:
1. `cd` into its directory.
2. Run `yarn` to install packages.
3. `cd ios` then `pod install`
4. Go back to the main project directory and run `yarn ios --device` to run on your connected iOS device.

