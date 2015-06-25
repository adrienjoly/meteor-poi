meteor-poi
==========

Meteor-POI is an app to curate points of interest.

It is maintained and tested to evaluate the relevance and performance of Meteor to develop mobile apps. But it also runs on desktop.

This repository was forked from one of the examples of the [mobile-packages](https://github.com/meteor/mobile-packages) repository. This was originally the app that was first used to demonstrate Meteor Cordova functionality at the Meteor Devshop in August 2014. It uses the Camera, Geolocation, and reload-on-resume packages, in addition to local packages for [Ionic Framework CSS](http://ionicframework.com/) and a simple implementation of the [Google Maps Javascript API](https://developers.google.com/maps/documentation/javascript/).

It runs on Meteor 0.9.2 and above.

<img src="screenshot.jpg" width="300" />

## Running the App

First install the [Meteor Web Framework](https://www.meteor.com/), then pick a platform and run the appropriate commands!

### Web Browser

`meteor`, then go to the indicated URL in your preferred web browser.

### Android Simulator

`meteor run android`, the simulator should open automatically. The simulator is currently quite slow, we are working on improving the installation process to configure faster simulation.

### iOS Simulator (Mac Only)

`meteor run ios`, the simulator should open automatically. You may be prompted to install Xcode to get the simulator if you don't have it.

### Android Device

1. [enable USB Debug Mode](http://developer.android.com/tools/device.html#developer-device-options) on your Android Device.
2. Make sure your Android device is connected to the same WiFi network as your computer.
3. Find out your computer's IP address - the device needs this to be able to connect to your development server.
4. `meteor run android-device -p <ip address>:3000`

### iOS Device (Mac Only, Need to be Member of iOS Developer Program)

1. Make sure your iOS device is connected to the same WiFi network as your computer.
2. Find out your computer's IP address - the device needs this to be able to connect to your development server.
3. `meteor run ios-device -p <ip address>:3000`, this command will open Xcode with the relevant project.
4. Use Xcode to run the app on your device.
