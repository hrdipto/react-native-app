# React Native for Windows Boilerplate


## Installation

```sh
git clone https://github.com/hrdipto/react-native-app
cd react-native-app
yarn install
npx react-native-windows-init --overwrite
npx react-native run-windows
```

## Nuget Restore Issue
- Open the solution file (temp.sln) from windows in visual studio.
- Install necessary dependency for visual studio
- Right click on solution explorer project and restore nuget


## Local certificate issue
While installing certificate Select "Local Machine", and then selected "Trusted Root Certification Authorities <br />
[Ref](https://stackoverflow.com/questions/23812471/installing-appx-without-trusted-certificate#comment83694631_24372483)

## Build / Deploy <br />
- From visual studio
Go to solution explorer > publish > create app packages and follow the step
- From cli 
```sh
npx react-native run-windows --release
```
## Publish
[Documentation](https://microsoft.github.io/react-native-windows/docs/app-publishing)
