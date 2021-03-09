# Pyronix Demo App

This is a **demonstration** app which I wrote, using the **Ionic** framework, for an interview with **Pyronix**.

## Getting Started

The below is intended for developing an **Android** app using a **Linux** machine.

### Building Your App

1. Ensure Node.js and NPM are already present on your system.
1. Install Ionic with `sudo npm install -g @ionic/cli`.
1. Create your app with `ionic start [APP_NAME] [TEMPLATE]`.
    * The template argument can be `blank`, `tabs`, etc.
1. Navigate to the directory created by the previous step.
1. Build your app using `ionic build`.
1. Preview your app in a browser using `ionic serve`.

### Building an Android Emulator

1. Install the drivers necessary for a 64-bit Linux system using `sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386`.
1. Download [the Android Studio archive](https://developer.android.com/studio/install).
1. Unzip the required folder from the archive, and then run `sudo cp -R ~/path/to/android-studio /usr/local/`.
1. Run Android Studio using `sh /usr/local/android-studio/bin/studio.sh` and then set up follow the wizard.
1. Within Android Studio, create an Android Virtual Device using the AVD Manager.
