# Animations with Sky Segmentation

[ ![Codeship Status for fritzlabs/fritz-sdk-android](https://app.codeship.com/projects/c74152e0-65d1-0136-2d69-32e87736c6c6/status?branch=master)](https://app.codeship.com/projects/297281)
[![Twitter](https://img.shields.io/badge/twitter-@fritzlabs-blue.svg?style=flat)](http://twitter.com/fritzlabs)

In this app, we create a simple photo app to replace the sky with an animation.

![](images/skyani.gif)

This example app uses the on-device Image Segmentation API with the Sky Segmentation Model for Android.

- [Overview](https://www.fritz.ai/features/image-segmentation.html?utm_source=github&utm_campaign=fritz-examples)
- [Documentation](https://docs.fritz.ai/develop/vision/image-segmentation/android.html?utm_source=github&utm_campaign=fritz-examples)

## Fritz AI

Fritz AI is the machine learning platform for iOS and Android developers. Teach your mobile apps to see, hear, sense, and think. Start with our ready-to-use feature APIs or connect and deploy your own custom models.

## Requirements

- Android Studio 3.2 or above
- Android device in developer model (USB debugging enabled)

## Getting Started

**Step 1: Create a Fritz AI Account**

[Sign up](https://app.fritz.ai/register?utm_source=github&utm_campaign=fritz-examples) for a free account on Fritz AI in order to get started.

Register the Android app in your Fritz account with the package id "ai.fritz.animatedSky". During registration, you'll receive an API key for the app. Save this for later. To find it in the webapp, you can go to Project Settings > Apps > Your App > Show API Key.

**Step 2: Clone / Fork the fritz-examples repository and open the AnimatedSkyApp app in Android Studio**

```
git clone https://github.com/fritzlabs/fritz-examples.git
```

In Android Studio, choose "Open an existing Android Studio project" and select `AnimatedSkyApp`.

**Step 3: Edit the fritz.xml file with your API Key**

In app/src/main/res/values/fritz.xml, change the fritz_api_key attribute with the one you received in step 1.

**Step 4: Build the Android Studio Project**

Select "Build > Make Project" from the top nav. Download any missing libraries if applicable. This should sync the gradle dependencies so give the build a second to complete.

**Step 5: Install the app onto your device**

With your Android device connected, select `Run > Run App` from the top nav. When running the app for the first time, you'll have to give permissions to access the camera. After the app is installed and running, take a picture outside and watch as we replace the sky with an animated image.

## Official Documentation

[SDK Documentation](https://docs.fritz.ai/?utm_source=github&utm_campaign=fritz-examples)

[Android API Docs](https://docs.fritz.ai/android/latest/index.html?utm_source=github&utm_campaign=fritz-examples)

## Join the community

[Heartbeat](https://heartbeat.fritz.ai/?utm_source=github&utm_campaign=fritz-examples) is a community of developers interested in the intersection of mobile and machine learning. [Chat with us in Slack](https://www.fritz.ai/slack?utm_source=github&utm_campaign=fritz-examples) and stay up to date on the latest mobile ML news with our [Newsletter](https://mobileml.us16.list-manage.com/subscribe?u=de53bead690affb8e9a21de8f&id=68acb5c0fd).

## Help

For any questions or issues, you can:

- Submit an issue on this repo
- Go to [Support](https://support.fritz.ai/?utm_source=github&utm_campaign=fritz-examples)
- Message us directly in [Slack](https://www.fritz.ai/slack?utm_source=github&utm_campaign=fritz-examples)
