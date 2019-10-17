# Notify-Alert

Simple Android application that generates the notifications upon receiving the messages.

Step 1 - Edit the app level build.gradle ![file](app/build.gradle)

implementation 'com.android.support:design:28.0.0'    (For older android sdk versions)

                                        or

implementation 'com.google.android.material:material:1.0.0'       (For Newer AndroidX Version)


Step 2 - open the Strings file and add those ![strings](app/src/main/res/values/strings.xml).

Step 3 - open your app's ![Manifest](app/src/main/AndroidManifest.xml) file and add this permission:
<uses-permission android:name="android.permission.INTERNET"/>



Step 4 - Then, Copy and paste the ![layouts](app/src/main/res/layout/activity_main.xml) and ![java code](app/src/main/java/com/example/studetails/MainActivity.java) .
