This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# React Native Vector Icons Test
# Getting Started

>**Note**: At present, the only font character displayed is a single rocketship in the usual React Native kickstart header. That is intentional. The purpose of this test is to document how to bootstrap react-native-vector-icons in your app. After you finish the process, the app should build and compile on both iOS and Android, should display a rocketship icon, and the Icon component should appear in your Visual Studio Code editor without a squiggly red line; that is, the syntax should be understood as a proper JSX component.

>**Note**: react-native-vector-icons has been rearchitected and in latest version there is no 'fonts' folder. Pull an earlier tagged version to get 'classic' version. I'll make an updated version of this shortly. 

## Step 1: install the packages

```
yarn add react-native-vector-icons
yarn add -D @types/react-native-vector-icons (test, maybe not needed)
cd ios
pod install
```

## Step 2: Set up tsconfig.json

include this in your compiler options to prevent false 'errors' from presenting when you use the Icon component.

```
"compilerOptions": {
    "paths": {
      "react": ["./node_modules/@types/react"]
    }
  }
```

## Step 3:

Download the project from github. Copy the contents of the Fonts folder to:

**into the app/src/assets/fonts for Android

**into the Fonts folder in the project folder in iOS

here's the github for the package:
https://github.com/oblador/react-native-vector-icons

## Step 4: 

here's the NPM page:
https://www.npmjs.com/package/react-native-vector-icons

follow the simple directions for iOS install on the NPM page

follow the manual directions for the Android install, but don't do the final step, installing the VectorIconsPackage.

This video will guide you through that:
https://www.youtube.com/watch?v=ZI9cCrKaZJg


### Now what?

- I plan to expand the tutorial and show adding custom fonts etc. Stay tuned.

