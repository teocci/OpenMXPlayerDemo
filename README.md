## OpenMXPlayer Audio player for Android

This is a port of the "OpenMXPlayer" open source library to Android platform adapted for AndroidStudio and Android platform 25.

### Overview

The project contains two modules:
- OpenMXPlayer - the library, the "decoder"
- OpenMXPlayerDemo - a simple project that illustrates how to use the player library, the "player"

The "decoder" module contains the Java code used for wrapping
the underlying  decoding algorithms (which is currently based on MediaCodec but it could be easily changed).

The "player" module is an example how to use the "decoder" library in your
project.

#### Intalling 

##### Requirements:
- Android SDK - at least platform 16 (Android 4.1 / JellyBean)

##### Compiling:

1) open the "decoder" and the "player" projects in your Android IDE and compile it

3) install the APK on the emulator or a device:
    adb install OpenMXPlayerDemo.apk
    

The original source code can be obtained at http://code.google.com/p/openmxplayer-android/

