# INSTALL REACT NATIVE

https://facebook.github.io/react-native/docs/getting-started.html

## Install Dependencies
  	1.	brew install node
		brew install watchman

## Install React Native globally
	2.	npm install -g react-native-cli

## Download and Install Xcode
	3.	https://itunes.apple.com/us/app/xcode/id497799835?mt=12
		(version 8.3.2 from Mac Store; only works on macOS Sierra or newer)
		https://stackoverflow.com/questions/10335747/how-to-download-xcode-dmg-or-xip-file
		(legacy versions for older Macs; 8.2.1 is last build that supports El Capitan)
		WARNING: File is 4.2Gb!  Install takes up 12Gb of storage

## Install Xcode command line tools
	4.	Xcode>Preferences>Locations
		Select your current Xcode build in the Command Line Tools dropdown

## Build a Project
	5.	react-native init AwesomeProject
		cd AwesomeProject
		react-native run-ios

## Wait for build to generate
	6.	Xcode Simulator will open and display a basic hello world
		Edit index.ios.js to see changes.  Cmd R will refresh the page.





# DEPLOY REACT NATIVE to iPhone

https://facebook.github.io/react-native/docs/running-on-device.html

# Create Apple Developer account (free version)
	1.	https://developer.apple.com/

		Connect iPhone to computer

# Open Xcode Project
	2.	Navigate to YourProject>ios>.xcodeproj
	3.	Open the Xcode project file in Xcode

# Sign in to your developer account
	4.	Xcode>Preferences>Accounts>Sign in

# Select your Team for the Project
	5.	Go to General>Signing dropdown
	6.	Select your account (your name) under the Team dropdown

# Choose build destination
	7.	Select your phone from the options list at the top of the Xcode project (below navigate)

# Run build
	8.	Click the ‘play’ button to build the project as an app on your phone
		Note: You will need the most updated Xcode build to use a newer iPhone (6s, 7)
			If incompatible, you will get this error: 
				Could not locate device support files.
				This iPhone 6s is running iOS 10.3.1 (14E304), which may not be supported by this 					version of Xcode.

