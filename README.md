A fast way to get started with the [Google Maps Android API v2](http://developers.google.com/maps/documentation/android).
![Analytics](https://maps-ga-beacon.appspot.com/UA-12846745-20/hellomap-android/readme?pixel)

#### Current version of library dependencies:

  * Google Play Services Maps 8.4.0

# TOC

  * [Requirements](#requirements)
  * [Android Studio](#android-studio)
    * [Download Android Studio](#download-android-studio)
    * [Open the project](#open-the-project)
    * [Add your API key](#add-your-api-key-1)
    * [Run the app](#run-the-app-1)
    * [Troubleshooting](#troubleshooting-1)

# Requirements

Java Development Kit (JDK) [Download](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Android SDK [Download](http://developer.android.com/sdk/index.html)

# Android Studio

## Download Android Studio
Download Android Studio (http://developer.android.com/sdk/index.html)

## Open the project
  1. On the welcome screen, select "Open an existing Android Studio project" or if you have a project open, choose "File->Open...""
  2. Choose Android > Existing Android Code Into Workspace
  3. Navigate to the checked out project
  4. Press "Ok"

## Add your API key
  1. Navigate to the AndroidManifest.xml file
  2. Click the "AndroidManifest.xml" tab, next to "Instrumentation", to see the XML view.
  3. Replace "your_api_key" with an API key generated using [these instructions](https://developers.google.com/maps/documentation/android/start#the_google_maps_api_key)

## Run the app
  1. Ensure your phone is in plugged in, developer mode enabled and screen unlocked
  2. Press the green arrow, or choose Run>Run

## Troubleshooting
### I see a grey map
Follow the instructions under "Add your API key" and try again.

### "Please specify Android SDK"
  1. Click "New..."
  2. Choose "Android SDK"
  3. Navigate to the Android SDK's "sdk" directory, press "Choose"

###  "No Java SDK of appropriate version found"
  1. Click "New..."
  2. Choose "JDK"
  3. Navigate to the JDK's home directory. For OS X, this is at `/Library/Java/JavaVirtualMachines/jdk.../Contents/Home`
  4. Press "Choose"
  5. If you are prompted with "Set up created SDK on project?", press No.
  6. Follow the instructions above
  7. If you are prompted with "Set up created SDK on project?", press Yes.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/googlemaps/hellomap-android/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

