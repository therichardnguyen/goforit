fastlane documentation
================
# Installation
```
sudo gem install fastlane
```
# Available Actions
## iOS
### ios app_store
```
fastlane ios app_store
```
Build and sign the Medisas app



This will do the following: 

 • Set the appropriate bundle identifier

 • Make sure the provisioning profiles are up to date and download the latest one

 • Bump the build number for the app version

 • Build and sign the app



This will **not** get the necessary signing certificates. Acquire these from a Medisas engineer.

Submit a new build to the App Store



Arguments:

 • version_number - The version number that you'd like to use for this build
### ios demo
```
fastlane ios demo
```
Submit a new Demo build to 's TestFlight



Arguments:

 • version_number - The version number that you'd like to use for this build
### ios play
```
fastlane ios play
```
Submit a new Play build to 's TestFlight



Arguments:

 • version_number - The version number that you'd like to use for this build

----

This README.md is auto-generated and will be re-generated every time to run [fastlane](https://fastlane.tools).
More information about fastlane can be found on [https://fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [GitHub](https://github.com/fastlane/fastlane/tree/master/fastlane).