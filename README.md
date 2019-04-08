# Connect-uClockIn
This is a simple Time and Attendance mobile app in for Connect ERP. This is a local PhoneGap project with the platform setup for iOS.This application makes use of the secured APIs provided for Time and Attendance in Connect ERP. The user will need to setup Time and Attendance base data to allow the application to login. Once the application is logged in, user will now be able to select their User and enter a secure pin (setup in Connect ERP) to Check In/Out. The Admin will be able to setup preferences like location etc of the Device that is being used to do the Check In/Out.


## Building for Android
A build for Android was not done as yet. However it should just be a matter of adding the Android platform and copying over the www folder.

## Building for iOS
You should be able to open the Xcode project and setup your signing and app id information and then compile the application. 

## Running the App
Currently you will need developer access to the Connect ERP system to setup Time and Attendance users and access to the application. Once the Time and Attendance is ported to <a href = 'https://easyaccounts.online/'>Connect Online </a> (SaaS version of Connect ERP) you will be able to setup this for your account directly and run this mobile app against it.
