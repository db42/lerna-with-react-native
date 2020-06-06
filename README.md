# Lerna-with-react-native

This is a React Native project configured with lerna.

## How to build and run this project

Run these commands from the root directory

```
npm install
npx lerna bootstrap
```


Run these commands from `packages/MobileApp` directory

```
cd packages/MobileApp/ios
pod install //You might need to install cocoapods first

cd .. //Navigate back to packages/MobileApp
npx react-native start //Run metro bundler
npm run ios //Run project on iOS simulator

```



