# Kodeco SwiftUI Project Template
This is an extract of the SwiftUI project from official [Kodeco MyRWTutorial repository](https://github.com/kodecocodes/MyRWTutorial).

It contains a barebone Xcode 14 SwiftUI application that sets up some of the basics according to standards for kodeco.com tutorial sample projects. Such things include:
- Sets the tab width to 2 spaces throughout the project
- Has the `LaunchScreen.xib` and app icons already set up
- Has the correct company name, bundle identifier, and code signing definitions (none)
- Defaults new files to use the correct copyright information

## How To Use This
After downloading and unzipping the skeleton project, several pieces should be changed to unique values such that they are relevant to the tutorial under development, including:
- Select the project in project navigator and rename the project
- Xcode will prompt to rename targets and other metafiles as well - select all of them
- Change the bundle identifier
- Change the scheme name
- Rename the top-level directory (the one that contains the `.xcodeproj` file)
- Select your target, open the Build Settings tab and set the path of the Development Assets to `YourProjectName/Preview\ Content`.
- Also, under the Build Settings of your target, go to Packaging and set the path of the `Info.plist` file to `YourProjectName/Info.plist`.
