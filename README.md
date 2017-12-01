# Dockerfile for Android Projects

This is a Dockerfile to make minimum images for Android projects.
No `ant`, `maven`, nor `android-ndk` are included. Not even Gradle. Please use Gradle wrapper with this image.

This fork aims to provide tags for the Docker images that represent the build tools version installed in the image, so your project can reference whichever version it needs. The matching Android platform is installed as well.

Example: for `27.0.1` tag the `build-tools;27.0.1` and `platforms;android-27` package is installed.

## Included

* OpenJDK 8
* Android SDK

Based on: https://github.com/wizbii/docker-android-sdk which is based on: https://github.com/gfx/docker-android-project
