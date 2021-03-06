fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios store
```
fastlane ios store
```
build & release for app store
### ios beta
```
fastlane ios beta
```
build & export for adhoc
### ios refresh_dsyms
```
fastlane ios refresh_dsyms
```
download and upload dSYM files
### ios bump_version
```
fastlane ios bump_version
```
bump version

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
