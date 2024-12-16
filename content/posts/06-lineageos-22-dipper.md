+++
title = 'LineageOS 22 for Xiaomi Mi 8 (dipper)'
date = 2024-12-16
draft = false
tags = ['android']
+++

# LineageOS 22 for Xiaomi Mi 8 (dipper)

```c
#include <std_disclaimer.h>

/*
 * IMPORTANT NOTICE:
 *
 * Before proceeding, consider the following:
 *
 * 1. I am NOT responsible for any damage caused to your device, life, or
 * anything else.
 * 2. Flashing this stuffs might void your warranty, break your device, or
 * turn your phone into a very expensive paperweight.
 * 3. If you lose data, well... it was probably due to your own poor
 * decision-making.
 *
 * You have been warned. Enjoy flashing at your own risk. If anything breaks,
 * I will kindly ignore your complaints while sipping my coffee.
 *
 * Proceed with extreme caution.
 */
```
You may know LineageOS already, so let's proceed to installation guide.

## Installation Guide
1. Download the [ROM](https://sourceforge.net/projects/kiso-dev/files/ROM/xiaomi/dipper/lineage-22.0-20241211-UNOFFICIAL-dipper.zip/download) and [recovery](https://sourceforge.net/projects/kiso-dev/files/images/xiaomi/dipper/20241207/recovery.img/download).
2. Reboot to bootloader
3. Flash the recovery by using this command:
```bash
fastboot flash recovery recovery.img
```
4. Reboot to recovery
5. Flash the ROM by using `adb sideload` method
6. Format /data
7. Profit

## Screenshots
<center>
<img src="/img/06/1.png" alt="home" style="width:300px;"/><img src="/img/06/2.png" alt="qs" style="width:300px;"/>
<img src="/img/06/3.png" alt="settings" style="width:300px;"/><img src="/img/06/4.png" alt="about" style="width:300px;"/>
<img src="/img/06/5.png" alt="android" style="width:300px;"/><img src="/img/06/6.png" alt="easteregg" style="width:300px;"/>
</center>

## Changelog
You can find it [here](https://github.com/kisodev/rel/blob/main/lineage/dipper) :)

## Source Code
- [ROM](https://github.com/LineageOS)
- [Device](https://github.com/kisodev/android_device_xiaomi_dipper)
- [Kernel](https://github.com/kisodev/android_kernel_xiaomi_sdm845)
