fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios deploy_all

```sh
[bundle exec] fastlane ios deploy_all
```

Deploy all steps for the iOS app

### ios check_app_existence

```sh
[bundle exec] fastlane ios check_app_existence
```

Check if the app exists in App Store Connect

### ios handle_code_signing

```sh
[bundle exec] fastlane ios handle_code_signing
```

Handle code signing for the iOS app

### ios ios_app

```sh
[bundle exec] fastlane ios ios_app
```

Build the iOS app

### ios upload_to_app_store_connect

```sh
[bundle exec] fastlane ios upload_to_app_store_connect
```

Upload the build to App Store Connect

### ios set_keychain_partition_list

```sh
[bundle exec] fastlane ios set_keychain_partition_list
```

Set keychain partition list to avoid permission prompts during code signing

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
