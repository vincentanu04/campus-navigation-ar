**Steps to run the app**

SETTING UP THE SOFTWARE REQUIREMENT.
_Note: We will be developing the app in Android only first for simplicity._
1. Have NodeJS installed. If you don't have it installed, head to https://nodejs.org/en/download/package-manager.
2. If you have an Android device, I think you can run and test the app on your device by downloading Expo Go app on your android.
   Else if no Android device, you need to have Android Studio installed and set up the Emulator. When you run the Emulator Virtual Device, download the Expo Go app from the playstore.

RUNNING THE APP.
1. Clone the repo and open it.
2. Run ``npm install`` to download required packages.
3. Run ``npm run android`` to create a running instance of the application. _Note: it is very likely this will cause bugs on your side as you need to do some more setting up such as setting up Android SDK. It will be different according to each OS. I am using Linux on Windows so I'm not sure how to debug on your side, however if using Linux can ask me. You will need to use Stack Overflow for this, just copy and paste the error. I know firsthand this is very annoying btw but pls bare with me._
4. Once npm run android works, there should be a link or a qr code. If you have an Android device, you can open the Expo Go app, and you should be able to open the app by scanning the QR (I think?). If using emulator, you can insert the link given to the Expo Go app.
5. You can now develop and play around the app. BTW, changing the code and then saving the file will cause instant update on the Expo Go app.
    
