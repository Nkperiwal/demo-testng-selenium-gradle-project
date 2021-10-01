#Instructions

## Quick Start

1. Ensure current JDK is installed (nothing else is required -- other dependencies will automatically download )
2. To run tests with Chrome run: ./gradlew

## Notes

When running from Gradle -- the build script will automatically try to download required OS specific drivers for Chrome, and update requirement environment variables -- webdriver.chrome.driver

Example for running indivisual tests from commandline: ./gradlew :test --tests "SeleniumExampleTest.browserInitTest" -i

### Old
=> When running from an IDE -- you will need these environment variables setup and pointing to the correct webdriver

=> Example for running individual tests from the commandline: gradle testPhantomJs -Dtest.single=TestNgExample
