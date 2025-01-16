This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# React Native Vector Icons Test
# Getting Started

>**Note**: At present, the only font character displayed is a single rocketship in the usual React Native kickstart header. That is intentional. The purpose of this test is to document how to bootstrap react-native-vector-icons in your app. After you finish the process, the app should build and compile on both iOS and Android, should display a rocketship icon, and the <Icon> component should appear in your Visual Studio Code editor without a squiggly red line; that is, the syntax should be understood as a proper JSX component.

## Step 1: install the packages

```yarn add react-native-vector-icons
yarn add -D @types/react-native-vector-icons
cd ios
pod install
```

## Step 2: Set up tsconfig.json

include this in your compiler options to prevent false 'errors' from presenting when you use <Icon>

```"compilerOptions": {
    "paths": {
      "react": ["./node_modules/@types/react"]
    }
  }
```

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
