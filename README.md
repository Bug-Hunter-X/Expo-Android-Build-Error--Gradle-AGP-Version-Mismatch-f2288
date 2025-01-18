# Expo Android Build Error: Gradle/AGP Version Mismatch

This repository demonstrates a common error encountered when building Android apps using the Expo CLI. The error arises from a mismatch between the required Android Gradle Plugin (AGP) version and the Gradle version specified in your project.  Expo requires specific versions for compatibility, and using incorrect versions will lead to build failures.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory in your terminal.
3. Attempt to build the Android app using `expo build:android`.

## Solution

The solution involves updating the Gradle and AGP versions to those compatible with your Expo SDK version.  Consult the Expo documentation for the correct versions to use with your SDK.