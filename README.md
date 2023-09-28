# Digit Classification Android Demo

### Overview

This is an end-to-end example of a digit classifier model built with TensorFlow
2.0 (Keras API), and trained on MNIST dataset. The example app allows users to
draw a number and predict which number it will be. These instructions walk you
through building and running the demo on an Android device.

The model file is downloaded via Gradle scripts when you build and run the
app. You don't need to do any steps to download TFLite models into the project
explicitly.


![Language Detector Demo](Digit Classification.png?raw=true "Digit Classification Demo")

## Build the demo using Android Studio

### Prerequisites

* The **[Android Studio](https://developer.android.com/studio/index.html)** IDE.
  This sample has been tested on Android Studio Chipmunk.

* A physical or emulated Android device with a minimum OS version of SDK 21
  (Android 5.0) with developer mode enabled. The process of enabling
  developer mode may vary by device.


### Models used

Downloading, extraction, and placing the models into the assets folder is
managed automatically by the download_model.gradle file.