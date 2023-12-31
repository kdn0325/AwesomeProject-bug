### Description

[!] Error installing boost
Verification checksum was incorrect, expected f0397ba6e982c4450f27bf32a2a83292aba035b827a5623a14636ea583318c41, got 5e89103d9b70bba5c91a794126b169cb67654be2051f90cf7c22ba6893ede0ff

Error occurred during React Native pod install. Please help

### Steps to reproduce

`npx react-native@latest init AwesomeProject `

`cd ios & pod install`

### React Native Version

0.73.1

### Affected Platforms

Runtime - iOS

### Output of `npx react-native info`

```text
System:
  OS: macOS 14.1.1
  CPU: (10) arm64 Apple M2 Pro
  Memory: 355.98 MB / 16.00 GB
  Shell:
    version: "5.9"
    path: /bin/zsh
Binaries:
  Node:
    version: 20.10.0
    path: ~/.nvm/versions/node/v20.10.0/bin/node
  Yarn:
    version: 1.22.19
    path: /opt/homebrew/bin/yarn
  npm:
    version: 10.2.3
    path: ~/.nvm/versions/node/v20.10.0/bin/npm
  Watchman:
    version: 2023.11.27.00
    path: /opt/homebrew/bin/watchman
Managers:
  CocoaPods:
    version: 1.14.3
    path: /Users/abel/.gem/bin/pod
SDKs:
  iOS SDK:
    Platforms:
      - DriverKit 23.2
      - iOS 17.2
      - macOS 14.2
      - tvOS 17.2
      - watchOS 10.2
  Android SDK: Not Found
IDEs:
  Android Studio: 2022.1 AI-221.6008.13.2211.9619390
  Xcode:
    version: 15.1/15C65
    path: /usr/bin/xcodebuild
Languages:
  Java:
    version: 11.0.11
    path: /usr/bin/javac
  Ruby:
    version: 2.7.6
    path: /Users/abel/.rbenv/shims/ruby
npmPackages:
  "@react-native-community/cli": Not Found
  react:
    installed: 18.2.0
    wanted: 18.2.0
  react-native:
    installed: 0.73.1
    wanted: 0.73.1
  react-native-macos: Not Found
npmGlobalPackages:
  "*react-native*": Not Found
Android:
  hermesEnabled: true
  newArchEnabled: false
iOS:
  hermesEnabled: Not found
  newArchEnabled: false

 abel@Abelui-MacBookPro  ~/Desktop/AwesomeProject   main  >....
    Platforms:
      - DriverKit 23.2
      - iOS 17.2
      - macOS 14.2
      - tvOS 17.2
      - watchOS 10.2
  Android SDK: Not Found
IDEs:
  Android Studio: 2022.1 AI-221.6008.13.2211.9619390
  Xcode:
    version: 15.1/15C65
    path: /usr/bin/xcodebuild
Languages:
  Java:
    version: 11.0.11
    path: /usr/bin/javac
  Ruby:
    version: 2.7.6
    path: /Users/abel/.rbenv/shims/ruby
npmPackages:
  "@react-native-community/cli": Not Found
  react:
    installed: 18.2.0
    wanted: 18.2.0
  react-native:
    installed: 0.73.1
    wanted: 0.73.1
  react-native-macos: Not Found
npmGlobalPackages:
  "*react-native*": Not Found
Android:
  hermesEnabled: true
  newArchEnabled: false
iOS:
  hermesEnabled: Not found
  newArchEnabled: false
```


### Stacktrace or Logs

```text
[!] Error installing boost
Verification checksum was incorrect, expected 6478edfe2f3305127cffe8caf73ea0176c53769f4bf1585be237eb30798c3b8e, got 5e89103d9b70bba5c91a794126b169cb67654be2051f90cf7c22ba6893ede0ff
```


### Reproducer

https://github.com/kdn0325/AwesomeProject-bug


### Solved

https://github.com/facebook/react-native/issues/42110#issuecomment-1872913081

### Screenshots and Videos

<img width="773" alt="스크린샷 2023-12-31 오후 6 04 02" src="https://github.com/facebook/react-native/assets/91298955/a4d3eb34-d090-4bb2-896d-9b49e2f2b981">
