# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

## Navigation

- Two types of navigation (Tab and Stack)
- Navigation between screens using Link component
- add screen names in \_layout.tsx in the Stack component
- Navigations using Tab
- create (tabs) subdirectory and layout, define tab.screen under tabs component

## Build a Screen Summary

- before coding the UI, break down it into components from the given ui i.e: design or Image
- React Native includes a few different components for handling touch events, but <Pressable> is recommended for its flexibility. It can detect single taps, long presses, trigger separate events when the button is pushed in and released, and more.
- how to make components reusable with respect to styling e.g: Button
- how to override default styles by using inline styles

## Use an image picker

- Relied upon third party package for image picking
- image picker options to give user option to edit pic before uploadings
