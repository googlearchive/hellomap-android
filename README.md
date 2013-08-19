A fast way to get started with the [Google Maps Android API v2](http://developers.google.com/maps/documentation/android).

#### Current version of library dependencies:

  * Google Play Services, revision 7
  * Android Support Library, revision 13

# TOC

  * [Requirements](#requirements)
  * [Check out the project](#check-out-the-project)
  * [Eclipse](#eclipse)
    * [Download Eclipse](#download-eclipse)
    * [Import the project to your workspace](#import-the-project-to-your-workspace)
    * [Add your API key](#add-your-api-key)
    * [Run the app](#run-the-app)
    * [Troubleshooting](#troubleshooting)
  * [IntelliJ](#intellij)
    * [Download IntelliJ](#download-intellij)
    * [Import the project](#import-the-project)
    * [Add your API key](#add-your-api-key-1)
    * [Run the app](#run-the-app-1)
    * [Troubleshooting](#troubleshooting-1)

# Requirements

Java Development Kit (JDK) [Download](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html)

Android SDK [Download](http://developer.android.com/sdk/index.html)

# Eclipse

## Download Eclipse
Eclipse is packaged with the [Android Developer Tools bundle](http://developer.android.com/sdk/index.html)

## Import the project to your workspace
  1. Choose File> Import...
  2. Choose Android > Existing Android Code Into Workspace
  3. Navigate to the checked out project
  4. You should see two projects - "hellomap" and "google-play-services_lib".
  5. Ensure both are selected
  6. Press "Finish"

## Add your API key
  1. Navigate to AndroidManifest.xml, under the "hellomap" project.
  2. Click the "AndroidManifest.xml" tab, next to "Instrumentation", to see the XML view.
  3. Replace "your_api_key" with an API key generated using [these instructions](https://developers.google.com/maps/documentation/android/start#the_google_maps_api_key)

## Run the app
  1. Ensure your phone is in plugged in, developer mode enabled and screen unlocked
  2. Press the green arrow, or choose Run>Run

## Troubleshooting
### I see a grey map

Follow the instructions under "Add your API key" and try again.

### I see the Android starter screen
  1. Choose Window>Close All Perspectives
  2. Choose Window>Open Perspective>Other...
  3. Choose Java

# IntelliJ
## Download IntelliJ
http://www.jetbrains.com/idea/download/
Choose the "Community Edition"

## Import the project
  1. In the start up screen, choose "Open project"
  2. Select the checked out project, press OK

## Add your API key
  1. Navigate to the AndroidManifest.xml file
  2. Replace "your_api_key" with an API key generated using [these instructions](https://developers.google.com/maps/documentation/android/start#the_google_maps_api_key)

## Run the app
  1. Ensure your phone is in plugged in, developer mode enabled and screen unlocked
  2. Choose Run>Edit Configurations...
  3. Press the + button
  4. Click "Android Application"
  5. Edit the name
  6. Choose "hellomap" as the Module
  7. Choose "USB Device" as your Target Device
  8. Press OK
  9. Press the green play button next to the name you specified. This will build the app, install it on the device and run it.

## Troubleshooting
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

### I see a grey map
Follow the instructions under "Add your API key" and try again.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/googlemaps/hellomap-android/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

