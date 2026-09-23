# LifeOS Android — Samsung A10

This is an Android Studio project containing your current LifeOS website as a real Android app.

## Build/install on your Samsung A10

1. Install Android Studio on your Windows computer.
2. Extract `LifeOS_Android.zip`.
3. Open Android Studio.
4. Choose **Open** and select the extracted `LifeOS_Android` folder.
5. Let Android Studio finish Gradle/SDK setup and sync.

### Install directly to your A10

On the Samsung A10:
1. Settings → About phone → Software information.
2. Tap **Build number** 7 times.
3. Go back → Developer options.
4. Turn on **USB debugging**.
5. Connect the A10 to the computer with USB.
6. Accept the USB debugging permission on the phone.
7. In Android Studio select the Samsung device.
8. Press the green **Run ▶** button.

LifeOS will appear in your Android app list with its own icon.

## Create an APK file

In Android Studio:
**Build → Build App Bundle(s) / APK(s) → Build APK(s)**

For a debug build, the APK is normally created under:
`app/build/outputs/apk/debug/app-debug.apk`

You can copy that APK to the Samsung A10 and install it.

## Important

- The app works offline because `index.html` is stored inside the Android app.
- Your LifeOS tasks, notes, areas, etc. are stored locally in the Android WebView.
- The current JavaScript reminder feature is not yet a true Android background alarm.
- A true alarm that rings while LifeOS is closed requires adding Android AlarmManager/notifications.
- The AI that rewrites the site's source code cannot rewrite an already-installed APK. For that, LifeOS should later load a remotely editable UI/configuration or receive app updates.

## App pinning

After LifeOS is installed, use Samsung's **Pin windows / App pinning** setting to keep the phone in LifeOS.
