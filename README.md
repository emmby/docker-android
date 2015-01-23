# docker-android

A handy little Dockerfile for building Android apps.

Installs:

* Android SDK Platform-tools, revision 21
* Android SDK Build-tools, revision 21.1.2
* Android SDK Tools, revision 24.0.2
* SDK Platform Android 5.0.1, API 21
* Android Extras
 
You can download and use the container [on dockerhub](https://registry.hub.docker.com/u/emmby/docker-android/).

Source for the dockerfile is available [on github](https://github.com/emmby/docker-android).

Want to try building something?  You can clone and build the Android App Development for Dummies source by running:
* docker pull emmby/docker-android
* docker run -i -t emmby/docker-android /bin/bash
* git clone https://github.com/emmby/android-for-dummies-v3.git
* cd android-for-dummies-v3
* ./gradlew assemble

To request an update, please file a ticket on the [issues list](https://github.com/emmby/docker-android/issues).

