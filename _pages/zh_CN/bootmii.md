---
title: "BootMii 备份"
---

{% include toc title="Table of Contents" %}

If you need help for anything regarding this tutorial, please join [the RiiConnect24 Discord server](https://discord.gg/rc24) (recommended) or [e-mail us at support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![BootMii Logo](/images/bootmii.png)

你需要一张**SD卡**来使用BootMii创建一个NAND备份。 If you do not have one, you can skip this page, although it is highly recommended to make a NAND backup if you can.
{: .notice--warning}

BootMii as boot2 is recommended, but only available to install on early Wiis. Otherwise, it can be installed as an IOS. Otherwise, it can only be installed as an IOS.
{: .notice--info}

One of BootMii's most important features is the ability to backup and restore your Wii's NAND storage. We will be going over how to perform a NAND backup. You can then restore from that backup for whatever reason. It's a good idea to make a NAND backup regularly or before doing something risky to your console (and if you know what you're doing, you won't have to do anything risky). We will be going over how to perform a NAND backup. You can then restore from that backup for any reason. It's a good idea to make a NAND backup regularly or before doing something risky to your console (and if you know what you're doing, you won't have to do anything risky).

#### 需要
* 一张SD卡，至少有512MB的空间。

#### 步骤
If you have BootMii installed as boot2 you will need to launch BootMii by restarting the console. Skip steps 1 and 2 if this is the case. Skip steps 1 and 2 if this is the case.
{: .notice--info}
1. 启动Homebrew Channel。
2. 按下Home按钮，选择"Launch BootMii"。

    Navigating BootMii is not possible using a Wii Remote. You must use the POWER and RESET buttons on your console, or a GameCube controller plugged into port 1. To navigate between options, press POWER on your Wii (or right on the +Control Pad on a GameCube controller). To select an option, hit RESET on your Wii or A on your GameCube controller. You must use the POWER and RESET buttons on your console, or a GameCube controller plugged into port 1. To navigate between options, press POWER on your Wii (or right on the +Control Pad on a GameCube controller). To select an option, hit RESET on your Wii or A on your GameCube controller.
    {: .notice--info}


    If the screen stays black and the blue disc drive light is blinking, you are missing the BootMii files on your SD card. Download [this zip](https://static.hackmii.com/bootmii_sd_files.zip) and extract it to the root of your SD card, then try again. Download [this zip](https://static.hackmii.com/bootmii_sd_files.zip) and extract it to the root of your SD card, then try again.
    {: .notice--warning}

3. Select the Options button (the icon with the gears).
4. Select the BackupMii button (the icon with the green arrow, aka the first icon on your left).
- NAND备份会开始。 你可以观看屏幕上的过程。
- "损坏区域"是正常的。 Don't worry when you see some on a NAND backup.
- 在这一步后，它会验证这个备份。 即使是推荐的，但是你可以按EJECT按钮跳过。
5. 当备份完全完成后，按任何按键退出NAND备份。
6. 要退出BootMii，按下Back按钮（有箭头的那个）然后你可以按下Wii菜单按钮或者HBC按钮来退出。

To restore from a NAND backup on your SD card, you can follow these instructions using RestoreMii (the icon with the red arrow, aka the second icon on your left). This is useful in the unlikely case you brick your Wii.
{: .notice--info}

To make sure you don’t lose the files, it's recommended to `nand.bin` and `keys.bin` from the root of your SD card to your computer.
{: .notice--info}

[Continue to Priiloader Installation](priiloader) Priiloader adds a level of brick protection, and we recommend it, especially if you were only able to install BootMii IOS.
{: .notice--info}
