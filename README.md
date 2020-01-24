<div>
  <br/><br />
  <p align="center">
    <a href="https://bambuser.com" target="_blank" align="center">
        <img src="https://bambuser.com/wp-content/themes/bambuser/assets/images/logos/bambuser-logo-horizontal-black.png" width="280">
    </a>
  </p>
  <br /><br />
  <h1>Bambuser player SDK for Android sample code</h1>
</div>

Sample code for video playback using the Bambuser player SDK for Android.

The sample code in this project will load the latest video found in your Bambuser environment and start playing it.


## Getting started

1. Install Android Studio.
2. Clone the sample code from this repository, so you have a local directory named i.e. `Myplayer`.
3. Sign up for an account on https://bambuser.com/ if you don't already have one, and make sure you have some videos.
4. Download the Android SDK zip from https://dashboard.bambuser.com/developer and open the zip file.
5. Copy the `libbambuser-x.x.x.aar` file to the `Myplayer/libbambuser` folder.
6. Import the `Myplayer` project in Android Studio.
7. Edit `Myplayer/libbambuser/build.gradle` and point it to the version of the `.aar` file.
8. Generate an `applicationId` and an `API key` at https://dashboard.bambuser.com/developer
9. Open the `MainActivity.java` file in Android Studio and insert the `applicationId` and an `API key` generated above.
10. Run the sample code on your device

## More information

* [Bambuser Docs](https://bambuser.com/docs)

* [Bambuser AB](https://bambuser.com)

* Our guide for building a player app from scratch can be found at [Player guide](https://bambuser.com/docs/playback/android-player/).
