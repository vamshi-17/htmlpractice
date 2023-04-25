#HEMO

HEMO APP

HEMO is a mobile app that connects patients, hospitals, and donors for streamlined blood donation. It sends notifications to registered hospitals when there is a need for blood, reducing the time and effort required. Patients can book appointments with doctors and view medical records. Donors can indicate their blood type and availability and accept blood donation requests through the app. Hospitals can accept or reject requests based on their availability.

Dependencies:

Creating space in Firebase Database:

Initial Database Setup - Remote database integration https://console.firebase.google.com/

Add project >- Enter Project Name

Enable Required features and create project.

Select OS for the database >- android

Enter package name to the firebase database.

Click on register app

The downloaded Google-services.json file should be placed in application folder of android studio.

Integrate SDK based on the versions.

This is how the Database is setup and integrated.

Android Studio:

Additional Installation Guide

Step 1: Head over to https://developer.android.com/studio/ to get the Android Studio executable or zip file.

Step 2: Click on the Download Android Studio Button. Click on the “I have read and agree with the above terms and conditions” checkbox followed by the download button.Click on the Save file button in the appeared prompt box and the file will start downloading.

Step 3: After the downloading has finished, open the file from downloads and run it. It will prompt the following dialog box. Click on next. In the next prompt, it’ll ask for a path for installation. Choose a path and hit next.

Step 4: It will start the installation, and once it is completed, it will be like the image shown below. Click on next.

Step 5: Once “Finish” is clicked, it will ask whether the previous settings need to be imported [if the android studio had been installed earlier, or not. It is better to choose the ‘Don’t import Settings option’. Click the OK button.

Step 6: This will start the Android Studio. Meanwhile, it will be finding the available SDK components.

Step 7: After it has found the SDK components, it will redirect to the Welcome dialog box. Click on Next. Choose Standard and click on Next. Now choose the theme, whether the Light theme or the Dark one. The light one is called the IntelliJ theme whereas the dark theme is called Darcula. Choose as required. Click on the Next button.

Step 8: Now it is time to download the SDK components. Click on Finish. Components begin to download and let it complete. The Android Studio has been successfully configured. Now it’s time to launch and build apps. Click on the Finish button to launch it.

Step 9: Click on Start a new Android Studio project to build a new app.

Executing program:

Once you open the Android Studio, Click on the open which is on the right top of the screen to open the project.

The path of the project has to be given and click ok.

The project will be loaded to the android studio.

After you have seen the project uploaded, to generate an apk, go to build on the top and select build apk.

An apk gets generated and you can locate the folder where the apk is generated. One can share the apk to mobile and use the application.

The other process is to connect the device to the laptop and change few settings in phone:

Go to about phone where the build number is located and click on it 7 times.

Now you will be able to see the developer options when you search in the settings.

There you have to enable the USB debugging and later see the pop-up saying allow RSA fingerprint. Allow it.

Now the device got connected and you will be able to see the device name on the top of the android studio screen.

Then you have to run the project. It might take a few minutes and after that the app gets installed in the device for use.
