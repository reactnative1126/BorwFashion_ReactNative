![React Native Apps](http://i.imgur.com/MmGT6cn.png "React Native Apps")

This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Borw Fashion Mobile Application

![platforms](https://img.shields.io/badge/platforms-Android%20%7C%20iOS-brightgreen.svg?style=flat-square&colorB=191A17)
![star this repo](https://img.shields.io/github/stars/react-native-webview/react-native-webview?style=flat-square)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![NPM Version](https://img.shields.io/npm/v/react-native-webview.svg?style=flat-square)](https://www.npmjs.com/package/react-native-webview)
![Npm Downloads](https://img.shields.io/npm/dm/react-native-webview.svg)

<img src="https://github.com/reactnative1126/BorwFashion_ReactNative/blob/master/src/assets/images/icon.png" width="80">

## Download

[![App Store Button](http://imgur.com/y8PTxr9.png "App Store Button")](https://apps.apple.com/ca/app/borw/id1504578577)
[![Play Store Button](http://imgur.com/utWa1co.png "Play Store Button")](https://play.google.com/store/apps/details?id=com.borw&hl=en_US&gl=US)

<!-- <a href="https://play.google.com/store/search?q=house%20sigma&c=apps&hl=en_US&gl=US">
  <img alt="Download on Google Play" src="https://play.google.com/intl/en_us/badges/images/badge_new.png" height=43>
</a>
<a href="https://apps.apple.com/us/app/housesigma-canada-real-estate/id1255490256">
  <img alt="Download on App Store" src="https://user-images.githubusercontent.com/7317008/43209852-4ca39622-904b-11e8-8ce1-cdc3aee76ae9.png" height=43>
</a> -->

## Preview

Welcome to my project! Below are my favorite videos and screenshots related to this project:

<a href="https://vimeo.com/958085312">
   <img src="https://github.com/reactnative1126/Brokier_ReactNative/blob/master/src/assets/screens/3.png" width="500" alt="Screen 3" hspace="5">
</a>

<img src="https://github.com/reactnative1126/Brokier_ReactNative/blob/master/src/assets/screens/1.png" width="250" alt="Screen 1" hspace="5"> <img src="https://github.com/reactnative1126/Brokier_ReactNative/blob/master/src/assets/screens/5.png" width="250" alt="Screen 5" hspace="5"> <img src="https://github.com/reactnative1126/Brokier_ReactNative/blob/master/src/assets/screens/4.png" width="250" alt="Screen 4" hspace="5">

## Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till the "Creating a new application" step, before proceeding.

### Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

### Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

#### For the first time

- Step 1: Install rvm https://rvm.io/rvm/install
```\curl -sSL https://get.rvm.io | bash```

- Step 2: Sync terminal: https://stackoverflow.com/questions/11677771/rvm-command-not-found-mac-ox
```$ source ~/.rvm/scripts/rvm```

- Step 3:
```$ cd ./fastlane```
run to install bundler
```gem install bundler```

#### If already installed bundler

- Step 4: run bundle to install fastlane and some dependent libraries
```bundle```

#### For iOS & Android

``` ./build.sh```

#### For Android

```sh
  cd ./fastlane
  fastlane Android beta
```

#### For iOS

```sh
  cd ./fastlane
  fastlane ios beta
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

### Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!

### Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

#### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

## Contributors

<table>
  <tr>
    <td align="center"><a href="https://twitter.com/@satya164"><img src="https://avatars2.githubusercontent.com/u/1174278?v=4" width="100px;" alt="Satyajit Sahoo"/><br /><sub><b>Satyajit Sahoo</b></sub></a><br /><a href="#ideas-satya164" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/callstack/react-native-paper/commits?author=satya164" title="Code">💻</a> <a href="https://github.com/callstack/react-native-paper/commits?author=satya164" title="Documentation">📖</a></td>
    <td align="center"><a href="https://ferrannp.com/"><img src="https://avatars2.githubusercontent.com/u/774577?v=4" width="100px;" alt="Ferran Negre"/><br /><sub><b>Ferran Negre</b></sub></a><br /><a href="#ideas-ferrannp" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/callstack/react-native-paper/commits?author=ferrannp" title="Code">💻</a></td>
    <td align="center"><a href="http://dawidurbaniak.pl"><img src="https://avatars3.githubusercontent.com/u/18584155?v=4" width="100px;" alt="Dawid"/><br /><sub><b>Dawid</b></sub></a><br /><a href="#ideas-Trancever" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/callstack/react-native-paper/commits?author=Trancever" title="Code">💻</a> <a href="https://github.com/callstack/react-native-paper/commits?author=Trancever" title="Documentation">📖</a></td>
    <td align="center"><a href="https://twitter.com/esemesek"><img src="https://avatars2.githubusercontent.com/u/9092510?v=4" width="100px;" alt="Kacper Wiszczuk"/><br /><sub><b>Kacper Wiszczuk</b></sub></a><br /><a href="#ideas-Esemesek" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/callstack/react-native-paper/commits?author=Esemesek" title="Code">💻</a></td>
    <td align="center"><a href="https://medium.com/@_happiryu"><img src="https://avatars1.githubusercontent.com/u/22746080?v=4" width="100px;" alt="Luke Walczak"/><br /><sub><b>Luke Walczak</b></sub></a><br /><a href="https://github.com/callstack/react-native-paper/commits?author=lukewalczak" title="Code">💻</a> <a href="https://github.com/callstack/react-native-paper/commits?author=lukewalczak" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/ahmedlhanafy"><img src="https://avatars2.githubusercontent.com/u/7052827?v=4" width="100px;" alt="Ahmed Elhanafy"/><br /><sub><b>Ahmed Elhanafy</b></sub></a><br /><a href="#ideas-ahmedlhanafy" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/callstack/react-native-paper/commits?author=ahmedlhanafy" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/kpsroka"><img src="https://avatars0.githubusercontent.com/u/24893014?v=4" width="100px;" alt="K. P. Sroka"/><br /><sub><b>K. P. Sroka</b></sub></a><br /><a href="https://github.com/callstack/react-native-paper/commits?author=kpsroka" title="Code">💻</a> <a href="https://github.com/callstack/react-native-paper/commits?author=kpsroka" title="Documentation">📖</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://twitter.com/_panpawel"><img src="https://avatars3.githubusercontent.com/u/3886886?v=4" width="100px;" alt="Paweł Szymański"/><br /><sub><b>Paweł Szymański</b></sub></a><br /><a href="https://github.com/callstack/react-native-paper/commits?author=pan-pawel" title="Code">💻</a> <a href="https://github.com/callstack/react-native-paper/commits?author=pan-pawel" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/jayu"><img src="https://avatars1.githubusercontent.com/u/11561585?v=4" width="100px;" alt="Kuba"/><br /><sub><b>Kuba</b></sub></a><br /><a href="https://github.com/callstack/react-native-paper/commits?author=jayu" title="Code">💻</a> <a href="#ideas-jayu" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/jbinda"><img src="https://avatars2.githubusercontent.com/u/21242757?v=4" width="100px;" alt="jbinda"/><br /><sub><b>jbinda</b></sub></a><br /><a href="https://github.com/callstack/react-native-paper/commits?author=jbinda" title="Code">💻</a> <a href="#ideas-jbinda" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

## Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

## Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.

## License

Borw React Native mobile application is licensed under [The MIT License](LICENSE) © Silas Jones 2017-
