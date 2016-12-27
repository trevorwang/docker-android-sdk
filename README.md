# Dockerfile for Android Projects

This is a Dockerfile to make minimum images for Android projects.
No `ant`, `maven`, nor `android-ndk` are included.

This fork aims to provide tags for the Docker images that represent the build tools version installed in the image, so your project can reference whichever version it needs. The matching Android platform is installed as well.

Example: for `25.0.2` tag the `build-tools-25.0.2` and `android-25` package is installed.

## Included

* OpenJDK 8
* Android SDK
* Android Support Libraries
* Google Play Services
* ConstraintLayout

Based on: https://github.com/wizbii/docker-android-sdk which is based on: https://github.com/gfx/docker-android-project
