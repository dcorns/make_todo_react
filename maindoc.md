#Making a To-do Application with [React Native](https://facebook.github.io/react-native/)
###Exploring the [react native](https://facebook.github.io/react-native/) frame work.
 This is a tutorial designed to explore the basics of using the react native framework to create native applications for android and ios device operating systems. Since compiling the code for ios devices requires an apple device, we will be demonstrating usage of the framework for android. This will make it possible for a wider audience to benefit. I have avoided using device specific imports, so it is expected that the code will produce the same results on an ios device if placed into the required file (index.ios.js). There are also some minor differences in installation steps for ios development which will not be covered. If anyone tries this, please pass on the results and I will attempt to update the tutorial. Also, I always welcome useful feedback regarding anything I write.
 ### Prerequisites
 This tutorial is slightly advanced and as such will not cover the basics of [node](https://nodejs.org) or [npm](https://www.npmjs.com). If you do not know what these are or how to use them, familiarize yourself first, or proceed if you enjoy the additional challenge. We will be using [yarn](https://yarnpkg.com) rather than npm to install and manage modules, but those familiar with npm will have no problem translating the yarn commands.
 ###Getting Started
 I use yarn instead of npm because it has useful features which I believe make it superior, however, as stated above translating yarn commands that sometimes differ slightly from npm should be self explanatory. The main difference to be aware of is that the yarn add 'command' is equivalent to the npm 'install' command. If you would like to try out yarn use the following the installation instructions here [Linux](https://yarnpkg.com/en/docs/install#linux-tab), [macOS](https://yarnpkg.com/en/docs/install#mac-tab), [Windows](https://yarnpkg.com/en/docs/install#windows-tab). That said, let's open a terminal window and get started.
 ####Installing the React Native command line interface (CLI)
 Using the CLI makes getting started with React Native easy.

`yarn add global react-native-cli` or using npm
`npm install -g react-native-cli`

####Download and install Android Studio
Since we are writing primarily for Android, we need to install [Android Studio](https://developer.android.com/studio/install.html). It is an IDE developed for the purpose of writing native applications with Java, but we need it because it provides the Android SDK and AVD (emulator) required to run and test our React Native application. Download Android studio. You can find the download for linux [here](https://developer.android.com/studio/index.html). If you are not using linux you can find your download by starting [here](https://developer.android.com/studio/install.html).
