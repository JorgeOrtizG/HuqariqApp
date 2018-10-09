# HuqariqApp


<a href="https://platform.telerik.com/#appbuilder/clone/https%3A%2F%2Fgithub.com%2FIcenium%2Fsample-translator" target="_blank"><img src="http://docs.telerik.com/platform/samples/images/try-in-appbuilder.png" alt="Try in AppBuilder" title="Try in AppBuilder" /></a>  

<a id="top"></a>
* [Overview](#overview)
* [Screenshots](#screenshots)
* [Test the Sample](#test-the-sample)
* [Limitations](#limitations)

# Overview

This sample shows you how to create a simple translator app which uses the MyMemory translation service via its RESTful API. The app is created using jQuery Mobile.

> *Supported mobile platforms:* iOS, Android, Windows Phone
>
> *Developed with:* Windows Phone SDK 8.1, Apache Cordova 4.0.0, jQuery Mobile 1.4.5, jQuery 2.2.0

[Back to Top](#top)

# Screenshots

Platform | Home | Translation
---|---|---
All | ![](https://raw.githubusercontent.com/Icenium/sample-translator/master/screenshots/home.png) | ![](https://raw.githubusercontent.com/Icenium/sample-translator/master/screenshots/translation.png)

[Back to Top](#top)

# Test the Sample

Apart from exploring the sample code base in GitHub, you can also clone and build apk test.


### Clone the sample

1. Click the button at the top of this document.
1. Provide your login credentials, if prompted.


### Android Studio

(These instructions were tested with Android Studio version 2.2.2, 2.2.3, 2.3, and 2.3.2)

* Open Android Studio and select `File->Open...` or from the Android Launcher select `Import project (Eclipse ADT, Gradle, etc.)` and navigate to the root directory of your project.
* Select the directory or drill in and select the file `build.gradle` in the cloned repo.
* Click 'OK' to open the the project in Android Studio.
* A Gradle sync should start, but you can force a sync and build the 'app' module as needed.

### Gradle (command line)

* Build the APK: `./gradlew build`

