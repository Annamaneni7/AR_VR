# Viro React wrapped in React Native 

This is a blank React Native project setup with Viro React and has React Navigation linked to it.

This starter-file has three bottom tabs, each tab loads a different AR component that you can build off from.  There's a portal AR component in one tab, 360 degree video on another and 360 image on the third.

## Installation

1. `git clone https://github.com/ViroCommunity/starter-kit.git`
2. `cd starter-kit`
3. `npm install`
4. `cd ios ` (iOS) 
4. `pod install` (iOS) 
5. Follow the steps on https://reactnative.dev/docs/running-on-device to run this app on your Android/IOS device. 

NOTE: 

1.You cannot use expo to run this app in the development phase because expo doesn't support viro react yet. 

2.You cannot use virtual emulators running on your pc to run this app either because they don't support VR/AR which needs camera access.

3.Because you cannot run this on expo, various libraries like react navigation have to be manually installed in the react native environment. This starter file does include the react navigation library along with tab navigator modules as well.




