# Basics

The goal here is to demostrate the ease-of-use of Ionic framework on mobile development. By using Ionic, a single source code can generate an App for each kind of mobile architecture, i.e: iOS, Android and Windows Phone.

This is a simple app that implements the concept of instant messaging. 


## Installation Steps

	1. Install Node e NPM
		*	https://nodejs.org/en/download
	2. Install Bower
		*	http://bower.io/#install-bower
	3. Install Cordova and Ionic CLI
		*	Execute `npm i cordova ionic@beta -g` on the terminal and, once finished, verify the 
		instalation status with the command `cordova -v && ionic -v`
	4. Install Android and/or iOS environment
		*	iOS
    		XCode
		*	Android
    		Android SDK's (http://ionicframework.com/docs/v2/resources/what-is/#android-sdk)
	5. Install Ionic View on your phone 

## Running
	1.	On Desktop
		* run `ionic serve`
	2. Simulating iOS on Desktop
		* `ionic run ios` (may require `npm install -g ios-sim`)
		* if issues are seeing here, try running same run command again
	3. On Phone
		* `ionic upload` (needs ionic account to be created)
		Once App is pushed to your Ionic account, go to your Cellphone, open Ionic View app
		and open your brand new app.
