## Yarn workspace setup for multiple NativeScript apps

This sample workspace demonstrates using NativeScript 8.1+ cli capabilities to manage multiple NativeScript apps within a [yarn workspace](https://classic.yarnpkg.com/en/docs/workspaces/).

### Prerequisites

* node 15+/npm 7+ is recommended
* [environment setup for NativeScript](https://docs.nativescript.org/environment-setup.html)
* ensure latest NativeScript cli (8.1+) is installed:

```
npm i -g nativescript
```

### Run the apps by using the provided npm scripts:

```
// install dependencies for workspace
yarn

// run app a
yarn mobile-app-a:android
yarn mobile-app-a:ios

// run app b
yarn mobile-app-b:android
yarn mobile-app-b:ios
```

### Clean workspace anytime

```
yarn clean
```
