# reactNativeGuide

INSTALL REACT NATIVE

https://facebook.github.io/react-native/docs/getting-started.html

Install Dependencies
1.  	brew install node
	brew install watchman

Install React Native globally
2.	npm install -g react-native-cli

Download and Install Xcode
3.	https://itunes.apple.com/us/app/xcode/id497799835?mt=12
	(version 8.3.2 from Mac Store; only works on macOS Sierra or newer)
	https://stackoverflow.com/questions/10335747/how-to-download-xcode-dmg-or-xip-file
	(legacy versions for older Macs; 8.2.1 is last build that supports El Capitan)
	WARNING: File is 4.2Gb!  Install takes up 12Gb of storage

Install Xcode command line tools
4.	Xcode>Preferences>Locations
	Select your current Xcode build in the Command Line Tools dropdown

Build a Project
5.	react-native init AwesomeProject
	cd AwesomeProject
	react-native run-ios

Wait for build to generate
6.	Xcode Simulator will open and display a basic hello world
	Edit index.ios.js to see changes.  Cmd R will refresh the page.
