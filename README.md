SIMPLE ADD AND FETCH IN ANDROID USING FIRESTORE
===============================================

[https://github.com/jpablico20/AndroidFirestore.git](https://github.com/jpablico20/AndroidFirestore.git)



1.  Open the Firebase console.

2. Click “Create a project”.

3. The “Create a project” window opens.

4. Enter the following information to create a new project.

5. Project name
Enter First Android Firebase. This is the project name of your app in the Firebase console.

6. Click the Android icon to start adding an Android app.

7. The “Add Firebase to your Android app” screen opens.

Enter the package name of the mobile app. Specify the package name specified when you created the project in Android Studio.

Click “Register app” to continue.

![captionless image](https://miro.medium.com/v2/resize:fit:544/format:webp/1*Cjtjp1wJOoHXvVoTNNQCRw.png)![captionless image](https://miro.medium.com/v2/resize:fit:892/format:webp/1*b7raRQ6Vup1C_yhgPZmw1Q.png)

![captionless image](https://miro.medium.com/v2/resize:fit:730/format:webp/1*2G0Yxb8JKHQtKWZmmS5UcA.png)![captionless image](https://miro.medium.com/v2/resize:fit:1272/format:webp/1*ukyHIFPWDdLwp4n6ZP8NsQ.png)

**Add Firebase to Your Android App**:

*   Once your project is ready, click the Android icon to add an app.
*   Enter your Android package name (from your app’s `AndroidManifest.xml`) and app nickname (optional).
*   Download the `google-services.json` file provided by Firebase.

![captionless image](https://miro.medium.com/v2/resize:fit:1318/format:webp/1*hmc-mhTmeeR5LiCCCt1EiA.png)![captionless image](https://miro.medium.com/v2/resize:fit:684/format:webp/1*QtBACr_Hr13AQTFwjhP__g.png)

![captionless image](https://miro.medium.com/v2/format:webp/1*HN0mQ7yk34YoSpd7xeAqgg.png)

**Add** `**google-services.json**` **to Your Project**:

*   Place the `google-services.json` file in the `app` directory of your Android project.

![captionless image](https://miro.medium.com/v2/resize:fit:538/format:webp/1*Xf8Z94twchgQFY8YuawUxw.png)

**Modify the** `**build.gradle**` **Files**:

In the Project-level (`build.gradle`):

![captionless image](https://miro.medium.com/v2/resize:fit:1300/format:webp/1*m7wFkoir2dTfwDl2tDtipw.png)

In the App-level (`build.gradle`):

![captionless image](https://miro.medium.com/v2/resize:fit:908/format:webp/1*2UI9Q42XKVz3HEqIVh7Gcw.png)

![captionless image](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*sSl3hq2r5TCJPafyzz5BLA.png)

**Sync Your Project**:

*   Click “Sync Now” in Android Studio to apply the changes.

**Test Firebase Integration**:

*   Build and run your app. Go to the Firebase Console under the Analytics tab to verify that Firebase is successfully connected.

![captionless image](https://miro.medium.com/v2/resize:fit:904/format:webp/1*eYZAQKGuhdCopreU4o0OHQ.png)![captionless image](https://miro.medium.com/v2/resize:fit:1098/format:webp/1*xzPW5K1R_h5V5drnm-iYsg.png)

![captionless image](https://miro.medium.com/v2/resize:fit:1460/format:webp/1*uMM101_UWSkmPNdEecVLTg.png)![captionless image](https://miro.medium.com/v2/resize:fit:542/format:webp/1*56k-hal9_PXMllP7Xp_MOQ.png)

![captionless image](https://miro.medium.com/v2/resize:fit:2000/format:webp/1*WXoB4YP3WthHDjzFqZixGA.png)
