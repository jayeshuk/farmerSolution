# Smart Warehouse Management System
## Project of SIH 2020 Internal Hackathon

An android app based platform to connect the farmers and warehouse owners, which will facilitate the service of accessing nearby warehouses and cold storages along with easy booking of the same.

Built with React, React Native, JavaScript, and CSS.

## App Snapshots

### Login & Register Screen
| <img src="https://user-images.githubusercontent.com/46965764/111064399-da4a3c80-84d9-11eb-8b0b-645ba9287cab.jpg"  width="294" height="580"> | <img src="https://user-images.githubusercontent.com/46965764/111064402-ddddc380-84d9-11eb-8b13-9a1b47e94746.jpg"  width="294" height="580"> | <img src="https://user-images.githubusercontent.com/46965764/111065828-be4a9900-84e1-11eb-8651-9a1d73915c8d.jpg"  width="294" height="580"> | 
| :----------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: |
| LOGIN | REGISTER | ROLE |



### Farmer Screens

| <img src="https://user-images.githubusercontent.com/46965764/111064457-21383200-84da-11eb-8c59-2ca3e2250095.jpg"  width="294" height="580"> | <img src="https://user-images.githubusercontent.com/46965764/111065032-948f7300-84dd-11eb-9375-c20162422e1a.jpg"  width="294" height="580"> | <img src="https://user-images.githubusercontent.com/46965764/111064496-504ea380-84da-11eb-8b74-ce7a44161a7e.jpg"  width="294" height="580"> |
| :----------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: |
| DASHBOARD | WAREHOUSE DETAILS | GOODS |


### Warehouse Owner Screens

| <img src="https://user-images.githubusercontent.com/46965764/111064511-678d9100-84da-11eb-9e5c-9e344d7eb2d7.jpg"  width="294" height="580"> | <img src="https://user-images.githubusercontent.com/46965764/111064512-69efeb00-84da-11eb-8d9b-4697aa38740c.png"  width="294" height="580"> | <img src="https://user-images.githubusercontent.com/46965764/111064515-6e1c0880-84da-11eb-8c76-07e1e69b5c90.jpg"  width="294" height="580"> |
| :----------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: |
| DASHBOARD | WAREHOUSE STATUS | POST NEW SPACE |


### Buyer Screens

| <img src="https://user-images.githubusercontent.com/46965764/111064573-cfdc7280-84da-11eb-80ba-fb1335c0f5f7.jpg"  width="294" height="638"> | <img src="https://user-images.githubusercontent.com/46965764/111064576-d1a63600-84da-11eb-91ae-260b957c9e97.jpg"  width="294" height="638"> |
| :----------------------------------------------: | :--------------------------------------------: |
| PRODUCTS | ORDER HISTORY |

### Select Language, Select Role and Profile Screen

| <img src="https://user-images.githubusercontent.com/46965764/111065784-83e0fc00-84e1-11eb-8787-c680c2f8d771.jpg"  width="294" height="638"> | <img src="https://user-images.githubusercontent.com/46965764/111065795-8d6a6400-84e1-11eb-96f9-f3ee6bac1da5.jpg"  width="294" height="638"> |
| :--------------------------------------------: | :--------------------------------------------: |
| LANGUAGE | PROFILE |




## Technology
<h2 align="center">
  <a href="https://reactnative.dev/">
    React Native
  </a>
</h2>

<h3 align="center">
  <a href="https://reactnative.dev/docs/getting-started">Getting Started</a>
  <span> · </span>
  <a href="https://reactnative.dev/docs/tutorial">Learn the Basics</a>
  <span> · </span>
  <a href="https://reactnative.dev/showcase.html">Showcase</a>
  <span> · </span>
  <a href="https://reactnative.dev/docs/contributing">Contribute</a>
  <span> · </span>
  <a href="https://reactnative.dev/en/help">Community</a>
  <span> · </span>
  <a href="https://github.com/facebook/react-native/blob/master/.github/SUPPORT.md">Support</a>
</h3>

React Native brings [**React**'s][r] declarative UI framework to iOS and Android. With React Native, you use native UI controls and have full access to the native platform.

- **Declarative.** React makes it painless to create interactive UIs. Declarative views make your code more predictable and easier to debug.
- **Component-Based.** Build encapsulated components that manage their state, then compose them to make complex UIs.
- **Developer Velocity.** See local changes in seconds. Changes to JavaScript code can be live reloaded without rebuilding the native app.
- **Portability.** Reuse code across iOS, Android, and [other platforms][p].

React Native is developed and supported by many companies and individual core contributors. Find out more in our [ecosystem overview][e].

[r]: https://reactjs.org/
[p]: https://reactnative.dev/docs/out-of-tree-platforms
[e]: https://github.com/facebook/react-native/blob/master/ECOSYSTEM.md

<h2 align="center">
  <a href="https://nativebase.io/">
    NativeBase
  </a>
</h2>

<h3 align="center">
  <a href="https://docs.nativebase.io/docs/GetStarted.html">Getting Started</a>
  <span> · </span>
  <a href="https://docs.nativebase.io/">Learn the Basics</a>
  <span> · </span>
  <a href="https://docs.nativebase.io/docs/CheatSheet.html">CheatSheet</a>
  <span> · </span>
  <a href="https://docs.nativebase.io/docs/FeaturedApps.html">Featured Apps</a>
  <span> · </span>
  <a href="https://docs.nativebase.io/docs/Contribute.html">Contribute</a>
  <span> · </span>
  <a href="https://docs.nativebase.io/docs/faq/FAQs.html">FAQs</a>
  <span> · </span>
  
  
</h3>

NativeBase is a free and open source UI component library for React Native to build native mobile apps for iOS and Android platforms. NativeBase also supports web from version 2.4.1.
One of our main goal with NativeBase 2.0 is to make it easy to theme the components with very little changes to components themselves.

General Syntax of NativeBase Component:


```
import React, { Component } from 'react';
import { Container, Button, Text } from 'native-base';
export default class GeneralExample extends Component {
  render() {
    return (
      <Container>
        <Button>
          <Text>
            Button
          </Text>
        </Button>
      </Container>
    );
  }
}
```


## Updating to New Releases

You should only need to update the global installation of `create-react-native-app` very rarely, ideally never.

Updating the `react-native-scripts` dependency of your app should be as simple as bumping the version number in `package.json` and reinstalling your project's dependencies.

Upgrading to a new version of React Native requires updating the `react-native`, `react`, and `navigation` package versions, and setting the correct `sdkVersion` in `app.json`. See the [versioning guide](https://github.com/react-community/create-react-native-app/blob/master/VERSIONS.md) for up-to-date information about package version compatibility.

## Installation and Setup Instructions

Clone down this repository. You will need `node` and `npm` installed globally on your machine.  

1. Installation:

    `npm install`    

2. Prerequisites to Run:
    
     - Connect Physical Android/iOS device in USB debugging mode  OR  Launch Emulator using AVD Manager [Android Studio].
     - Sometimes you may need to reset or clear the React Native packager's cache. To do so, you can pass the `--reset-cache` flag to the start script:

          ```
          npm start -- --reset-cache
          # or
          yarn start -- --reset-cache
          ```

3. To Start Android Application:

    * For Android users:
      `npx react-native run-android`

    * For iOS users:
      `npx react-native run-ios`

4. To Visit App: 
    
    App Launched in your Android/iOS Device
    
5. Login Details (Demo): 
    
    Role : Any
    
    Email Id : vedant
    
    Password : 123456
    
## Run tests
Unittests: `npm run mocha`

Unittests with coverage: `npm run coverage`

Linter: `npm run lint`
