#Instructions

## Quick Start

1. Ensure current JDK is installed (nothing else is required -- other dependencies will automatically download )
2. Clone the project using `git clone https://github.com/Nkperiwal/demo-testng-selenium-gradle-project`
3. Provide execute permission to gradlew sript using `chmod +x gradlew`
4. To run tests with Chrome run: `./gradlew :test --tests "SeleniumExampleTest.browserInitTest" -i`

## Notes

When running from Gradle -- the build script will automatically try to download required OS specific drivers for Chrome, and update requirement environment variables -- webdriver.chrome.driver

Example for running individual tests from commandline: ./gradlew :test --tests "SeleniumExampleTest.browserInitTest" -i