fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android slack_debug

```sh
[bundle exec] fastlane android slack_debug
```

Debug the Slack integration

### android test

```sh
[bundle exec] fastlane android test
```

Runs all the tests

### android increment_version

```sh
[bundle exec] fastlane android increment_version
```

Increments version in the pubspec.yaml

### android firebase_distribute

```sh
[bundle exec] fastlane android firebase_distribute
```

Uses Firebase App Distribution to distribute the APK to testers

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
