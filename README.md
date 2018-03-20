<div>
  <br/><br />
  <p align="center">
    <a href="https://irisplatform.io" target="_blank" align="center">
        <img src="https://irisplatform.io/static/images/company/iris-by-bambuser-black-horisontal.png" width="280">
    </a>
  </p>
  <br /><br />
  <h1>Iris player SDK for Android sample code</h1>
</div>

Sample code for video playback using the Iris player SDK for Android.

The sample code in this project will load the latest video found in your Iris environment and start playing it.


## Getting started

1. Install Android Studio.
2. Clone the sample code from this repository, so you have a local directory named i.e. `Sampleplayer`.
3. Sign up for an account on https://irisplatform.io/ if you don't already have one, and make sure you have some videos.
4. Download the Android SDK zip from https://dashboard.irisplatform.io/developer and open the zip file.
5. Copy the `libbambuser-x.x.x.aar` file to the `Sampleplayer/libbambuser` folder.
6. Import the `Sampleplayer` project in Android Studio.
7. Edit `Sampleplayer/libbambuser/build.gradle` and point it to the version of the `.aar` file.
8. Generate an `applicationId` and an `API key` at https://dashboard.irisplatform.io/developer
9. Open the `PlayerActivity.java` file in Android Studio and insert the `applicationId` and an `API key` generated above.
10. Run the sample code on your device


The Iris platform by Bambuser can be found at https://irisplatform.io/,
and technical documentation can be found at https://irisplatform.io/docs/
