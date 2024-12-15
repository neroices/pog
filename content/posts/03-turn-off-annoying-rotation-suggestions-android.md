+++
title = 'Turn Off Annoying Rotation Suggestions on Android'
date = 2024-05-11
draft = false
tags = ['android']
+++

# Turn Off Annoying Rotation Suggestions on Android
![ss](/img/03/screenshot.jpg)

This guide will help you ditch those rotation suggestion pop-ups on your Android device. There are two ways to do it, depending on whether you're a tech whiz with a rooted phone or a regular user.

**Non-rooted user:**

1. Head over to the Play Store and download [SetEdit](https://play.google.com/store/apps/details?id=by4a.setedit22).
2. Open ADB Shell, and run this command:
```bash
pm grant by4a.setedit22 android.permission.WRITE_SECURE_SETTINGS
```
3. - Open Setedit and find `Secure Table`.
   - Tap to add a new setting called `show_rotation_suggestions`.
   - Set the value to `0`.
   - Hit `Done` to save.

**Rooted user:**

1. Type `su` in the terminal and press Enter.
2. Type this code and press Enter:
```bash
settings put secure show_rotation_suggestions 0
```
That's it!

Now you can freely flip your phone without any judgmental pop-ups telling you how to hold it.
