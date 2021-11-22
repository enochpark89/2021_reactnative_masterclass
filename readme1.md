# React Native Masters

- We are going to create **four applications** because we can't explain everything by creating one application

1. Movie App

- We are going to build tab, stack, native, JavaScript navigations.
- Handle API and caching. 
- Style in reactnative. 
- dark mode. 

2. Language learning application

- users are going to tell us whether they know the word or not. 
- Persistence, Animation, transition and interaction in react native. 
- You can swipe cards to the right or to the left. 

3. Journaling application that can keep track of everything that they do. 

- Run MongoDB in reactNative. 
- We can have DB within the react native. 
- Ads in application. Free application earn money via ADs.

4. Crypto Currency tracker application. 

- We are going to make data visualization of charts going up and down. 
- We are going to learn FireBase to create a backend as a DB. 

# Dev Environment Set up.

*How do build an app with reactNative?*

1. Use Expo to handle JavaScript part. 
2. Native Native way.

1. ReactNative

URL: 
reactnative.dev

1. Click "get started"
2. Environment setup > setting up the development environment.
3. Explo CLI or React Native CLI


*How do you install React Native CLI?*

1. Install Chocolatey (a popular package manager for Windows.)
https://chocolatey.org/install

2. Using chocolatey install node.js and openjdk8
choco install -y nodejs.install openjdk8

3. Install Android Studio.
https://developer.android.com/studio/index.html
make sure the boxes next to all of the following items are checked:

Android SDK
Android SDK Platform
Android Virtual Device

4. Install the latest Android SDK.
File > Settings > Appearance & Behavior > System Settings > Android SDK

Make sure below items are checked:
- Android 10 (Q)
- Android SDK Platform 29
- Intel x86 Atom_64 System Image or Google APIs Intel x86 Atom System Image

Since SDKs are heavy application, it will take some time to install.

5. Configure the ANDROID_HOME environment variable. 
Please refer to the ReactNative website. 
https://reactnative.dev/docs/environment-setup

*How do you make sure that everything is installed properly?*

- To test, we are going to use react-native init
- in an empty folder, create an awesomeproject (test)

*This is a naked project. We are going to use other method to create a completed project.*
```js
npx react-native init AwesomeProject
```

*How do we run the project?*

```shell
npx react-native run-android
# or
npm run android
```

- Once these commands run to test the android studio, you will get metro server + simulator running if everything is installed properly. 

# CLI vs Ignite vs CRNA

- If you install with the CLI, you won't have the preinstalled configuration. 

- Instead we can use ignite and CRNA to get application with preconfiguration. 

- ignite installs with defaults
URL: https://github.com/infinitered/ignite
Installed Tech Stack:
- React Native
- React Navigation 5
- MobX-State-Tree (Why not Redux?)
- MobX-React-Lite
- TypeScript
- AsyncStorage (integrated with MST for restoring state)
- apisauce (to talk to REST servers)
- Flipper-ready
- Reactotron-ready (and pre-integrated with MST)
- Supports Expo (and Expo web) out of the box
- And more!

If you are going to one of these, it is better to start with ignite. 

*How do you create using ignite-cli?*

- Read the instruction
```shell
npx ignite-cli new PizzaApp.
```

- Nico recommends use ignite for the next application because it will teach alot. 
- Most of the scripts provided are what you need to come up by yourself. 
- Just by reading ignite code, you might get a good idea how to structure your react-native app. 
- In application folder, there are structured folders. It might be a good idea to follow those rules. 
- You will become very productive when you realize pre-setting.

*How do you create a react-native app?*
```
npx react-native init AwesomeProject 
```
1. Creates an application that we have native files that we need (Android and iOS file)
2. It allows us to use the expo as well. 
3. Expo can't access the Android and iOS files.


