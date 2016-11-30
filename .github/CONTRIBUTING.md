Welcome to Udacity Blitz as an Android Contributor!
## Code Guidelines:

We try to follow Java-specific guidelines direct from Android!
See here: <https://source.android.com/source/code-style.html>

## Best Practices During Development
* Enable Developer Mode on all devices/emulators used for testing.
..* Enable Strict Mode on devices/emulators
..* Enable Overdraw mode on your device when testing.
..* Enable "Don’t keep Activities" as a good test of saving state, etc.

* We try our best to support the widest array of stable Android API Versions.
Android OS Distribution: <https://developer.android.com/about/dashboards/index.html> Min SDK version support should be API 15 in a majority of the cases. Target SDK version should be the latest stable release (of this writing, 24 - Android 7.0 Nougat)
* Knowledge share with your fellow developers! Anything you find interesting about the platform, concerns you have with the project, are most welcome in the Slack channel for your project. The more everyone communicates, generally the experience and end result will be better!
* As stated before, be a good Git citizen.
* Don’t try and reinvent the wheel. There are a number of good third-party solutions. Use your best discretion, and also convene with your TPM and other developers.
* We like square’s LeakCanary for finding low hanging fruit when it comes to memory leaks: https://github.com/square/leakcanary

## Android Studio:
* Use Android Lint (Code > Inspect), but be judicious with it (false positives exist)
* No hardcoded strings (as parameters to method calls)
* Use the latest stable version of Android Studio

## Writing tests/QA:

Test coverage is important to delivering quality code. It’s often too time consuming for 100% full coverage, but for critical features some tests are better than none.
https://developer.android.com/studio/test/espresso-test-recorder.html This has its limitations, but could be very useful in getting quick integrated test coverage for core functionality and user experience (without writing the tests by hand).
As you are developing and testing, please keep this checklist in mind: https://developer.android.com/distribute/essentials/quality/core.html
We use CircleCI for continuous integration. Read about it here: https://circleci.com/docs/android/ . Note: unless specifically instructed, you don’t have to configure this yourself.

