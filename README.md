# All About Kali Nethunter 
About kali Nethunter GitHub Repository 

<div align="center">
  <h2>Important Notice</h2>
</div>

<p align="justify">
  <strong>Disclaimer:</strong> Please be aware that any actions you take are entirely your own responsibility. The authors of these posts and the Forum Administration cannot be held liable for any consequences arising from your device modifications. It is important to note that the content shared is purely for educational purposes.
</p>

<p align="justify">
  We strongly advise against engaging in any illegal activities. The intention behind sharing information is to foster learning and understanding. It is essential to exercise caution and to always follow ethical and legal guidelines when working with technology.
</p>

<div align="center">
  <em>Thank you for your understanding and responsible approach.</em>
</div>

---------
<div align="center">
  <h2>Exploring NetHunter: Empowering Mobile Penetration Testing</h2>
</div>

<p align="justify">
  NetHunter is an exceptional Android-ROM overlay that transforms your device into an agile and dynamic mobile penetration testing platform. Imagine having a comprehensive toolkit at your fingertips, neatly integrated into a secure environment, for investigating the security landscape of Android devices.
</p>

<p align="justify">
  At its core, NetHunter comprises a custom kernel, an ingenious Kali Linux chroot, and a suite of Android companion apps that facilitate seamless interaction with an array of cutting-edge security tools and attack techniques. This confluence of features enables you to not just explore but actively engage with the intricate world of cybersecurity.
</p>

<p align="justify">
  Beyond its comprehensive arsenal of Kali Linux penetration testing tools, NetHunter propels you into the realm of advanced security exploration. The platform boasts an array of specialized features, including the ability to execute HID Keyboard Attacks, orchestrate potent BadUSB exploits, orchestrate Evil AP MANA attacks, and so much more. It's not just about probing vulnerabilities; it's about understanding the depths of modern security challenges.
</p>

<p align="justify">
  NetHunter's power lies in its ability to empower enthusiasts, professionals, and anyone curious about the security landscape. By providing a controlled and potent environment, NetHunter invites you to unravel the layers of Android security with confidence and curiosity.
</p>

<div align="center">
  <em>Join the journey of becoming a security explorer with NetHunter!</em>
</div>
____

<details>
<summary>Installation Requirements:</summary>

- A device with a minimum of 8GB of available storage space.
- Custom recovery installed on your device.
- A kernel with support for * feature (specific to your use case).
- Familiarity with flashing devices.
- Proficiency in working with Linux from the terminal.

</details>
<details>
<summary>Support in the Kernel*:</summary>

- Network adapters support (rtl, broadcom - outdated, bluetooth)
- HID, rndis support (possibly in conjunction with qcrndis)
- Mass Storage: FunctionFS support
- OTG (USB Power) support
- HackRF support (if possible)
- System V IPC support
- Preferably without panic on oops

</details>

## [Official Kali NetHunter Kernels](https://stats.nethunter.com/kernels.html)

<details>
<summary>Xiaomi:</summary>

- Poco Model
- Pocophone
- NetHunter-Enabled Kernel for Poco X3 Pro
- NetHunter-Enabled Kernel for Poco X3 Pro
- Poco X3 NFC / Poco X3
- Poco X3
- Poco x3 OSS
- Poco F1 (beryllium) -1
- Poco F3 (alioth/alioth-in)
- Nethunter-enabled kernel for Poco x3 pro (vayu)

</details>
<details>
<summary>Mi Model:</summary>

- Xiaomi Mi 10i 5G (Gauguinpro)
- Xiaomi Mi Max (hydrogen)
- Xiaomi Mi 8 (dipper)
- Mi A1
- Xiaomi Mi 8 Pro (equuleus)
- Xiaomi Mi 9T
- Mi max 3(nitrogen)

</details>
<details>
<summary>Redmi Model:</summary>

- Xiaomi Redmi 8a / Redmi 8
- Xiaomi Redmi 5 (rosy)
- Xiaomi Redmi 5 Plus (vince)
- Xiaomi Redmi 5 Plus / Note 5 India (vince)
- Xiaomi Redmi 5 Plus / Note 5 (vince) India
- Xiaomi Redmi 5 Plus (vince)
- Xiaomi Redmi 4A (rolex)
- Xiaomi Redmi 4A (rolex)
- Xiaomi Redmi 4X (santoni)
- Xiaomi Redmi 3S, 3X (land) +1
- Xiaomi Redmi 3/3 Pro (ido)
- Redmi 10 (selene)

</details>

<details>
<summary>Note Model:</summary>

- Xiaomi Redmi Note 10 Pro
- Xiaomi Redmi Note 7 (lavender)
- Xiaomi Redmi Note 7 stormhunter
- Xiaomi Redmi Note 9 Pro
- Xiaomi Redmi Note 7 Pro (violet)
- Xiaomi Redmi Note 6 Pro (tulip)
- Xiaomi Redmi Note 5 (whyred)
- Xiaomi Redmi Note 5 (Android 10 + HID)
- Xiaomi Redmi Note 5 Pro (Xiaomi Redmi Note 5 Global / China) (whyred)
- Xiaomi Redmi Note 4 (nikel) Snapdragon
- Xiaomi Redmi Note 4X (mido) Snapdragon
- Redmi 8 Note
- Redmi Note 8T
- Redmi Note 8 Pro
- Redmi Note 8 Pro Helium
- Xiaomi Redmi Note 4X (mido) Snapdragon
- Redmi Note 10 Pro (sweet)
- Xiaomi Redmi Note 4 [Snapdragon] (mido)
- Xiaomi Redmi Note 6 Pro

</details>

<details>
<summary>One Plus Model:</summary>

- One Plus 7
- OnePlus 7T Pro
- OnePlus 8/8pro/8T/9R (opkona)

</details>

<details>
<summary>Samsung:</summary>

- Samsung Galaxy Note 4 (SM-N910C)

</details>

<details>
<summary>Lenovo Model:</summary>

- Lenovo ZUK Z2 Plus (z2_plus)
- Lenovo Vibe S1

</details>

<details>
<summary>ZTE:</summary>

- ZTE Axon Mini

</details>

<details>
<summary>LeEco:</summary>

- LeEco Cool 1 (C106/C103/R116)
- LeEco Le 2 / LeEco Le S3 (X520 / X526 / X527 / X522)
- Leeco Le 2 (s2) Android 11(R)

</details>

<details>
<summary>Sony:</summary>

- Sony Xperia Z
- Sony Xperia XA1 Plus (Teak)

</details>

<details>
<summary>Asus:</summary>

- Asus Zenfone Max Pro M1

</details>

<details>
<summary>HUAWEI/HONOR:</summary>

- Huawei Honor Y7 2018/7C/7A Pro

</details>

___
<details>
<summary>Installing NetHunter:</summary>

- Installation requires installed Busybox (preferably in /system/xbin), also root rights.
- Device selection for NetHunter.
- <details>
<summary>A small lyrical digression:</summary>

I think that most of you know that mobile devices have 2 main manufacturers of processors: Qualcomm and MediaTek (MTK). Some have injections (you need a qucacld-2 driver) and HID, unlike devices with chips from MTK.

Also, if you have not bought a device yet, then either choose the device where the core for NH is already ready, or order from the craftsmen for + -30 $ (2.2k₽), or after buying the device, assemble the core yourself.

If you are a professional pentester, then I advise you to pay attention to the devices whose main OS is Linux. For example:
- PinePhone (PDA or smartphone with Linux)
- Librem 5 (PDA or smartphone with Linux)
- Raspberry Pi (ARM based mini PC)
- Orange Pi (ARM based mini PC)

</details>

### Recommended firmware.
### Universal method for all devices.
<details>
<summary>What doesn't work without a kernel?</summary>

1. Wifi/Bluetooth/RF adapters
2. Bluetooth
3. HID/RNDIS

</details>

- If you encounter errors, we recommend that you see [Troubleshooting and FAQ](troubleshooting-faq-link).

</details>

<details> <summary>General install process with magics</summary>  

If you want to use Kali NetHunter, you must install Busybox  on your phone, Busybox  is not provided in the kernel file, if provided then check and no need to install separately. If you want you can install Busybox  from playstore or flash Busybox  zip through magisk. I would suggest flashing the zip! 

## For Zip busybox: [![](https://img.shields.io/badge/Busybox-A12-blue)](https://github.com/masshuvo/Nethunter_kernel_Gauguinpro/releases/download/Busybox12/Busybox-for-Android-NDK_1.34.1_.13412.zip)
https://github.com/Magisk-Modules-Repo/busybox-ndk
https://github.com/meefik/busybox

## Download and setup some Busybox  for your phone that works on your phone: 

🖇️

1.  https://play.google.com/store/apps/details?id=stericson.busybox

2. https://play.google.com/store/apps/details?id=com.jrummy.busybox.installer

3. https://play.google.com/store/apps/details?id=ru.meefik.busybox


## After flashing Busybox  or after installing Busybox  from playstore and setup, you can check if Busybox  is installed on your phone with this application: 

OnePlus's Kali Nethunter Rom includes busybox, Wifi framework, provided by developers. No need to install them separately if provided by developers. 

🖇️ https://play.google.com/store/apps/details?id=com.joeykrim.rootcheck


Once this is done, if you want to do wifi testing from your phone / use wifi adapter / bluetooth adapter / HID Device / Rucky / rubber ducky / USB HUMAN INTERFACE DEVICE / then flash the wifi framework zip using magisk 

 Flashing this framework zip is mandatory for doing all kinds of hardware related testing through your mobile.
 [![](https://img.shields.io/badge/W_F_W-v1-blue)](https://github.com/masshuvo/Nethunter_kernel_Gauguinpro/releases/download/wi-fi_framework/Wireless_Firmware_for_Nethunter.zip)
 
## Link above 🖇️🖇️
https://forum.xda-developers.com/t/module-wireless-firmware-for-nethunter.3857465/

https://github.com/rithvikvibhu/nh-magisk-wifi-firmware

## If you don't know how to flash Wi-Fi framework with magisk then you can watch this video of mine
https://youtu.be/Ssgt1viwb2U


## Download Kali Nethunter latest version 
https://kali.download/nethunter-images/

----------------------------------------------------------------------------------------
after flash kali netHunter than you need to give permissionpermission to use kali netHunter: 

<code> If there is no problem to open terminal and permission is already given in your Kali Nethunter then I don't need to follow this procedure separately!  That's why I said that there are some ROMs that are only for using Kali Nethunter, if you have downloaded and used any such ROM then you don't need to follow this procedure. </code>
**Open kali terminal**


**click Androidsu**

``` echo "FIX NETHUNTER PERMISSIONS"

echo "in Android 12"

pm grant com.offsec.nethunter android.permission.ACCESS_FINE_LOCATION 

pm grant com.offsec.nethunter android.permission.ACCESS_COARSE_LOCATION

 pm grant com.offsec.nethunter android.permission.READ_EXTERNAL_STORAGE

 pm grant com.offsec.nethunter android.permission.WRITE_EXTERNAL_STORAGE

 pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT 

pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT_SU

 pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT_NH

 pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT_NH_LOGIN

clear

sleep 3

echo "done"
```
**copy and past : Entar.**

After doing this you need to give internet permission.

**Open Kali Terminal**

**click Root**
**Copy 👇 and Past and Enter:**

```groupadd -g 3003 aid_inet && usermod -G nogroup -g aid_inet _apt

echo 'APT::Sandbox::User "root";' > /etc/apt/apt.conf.d/01-android-nosandbox 
```


Before we start testing web applications' security, we need to be sure that we have all the necessary up-to-date tools. This recipe covers the basic task of keeping Kali Nethunter and its tools at their most recent versions.

How to do it...

Once you have a working instance of Kali Nethunter up and running, perform the following steps:

Log in as a root on Kali Nethunter; the default password is "toor", without the quotes. You can also use su to switch the user or sudo to execute single commands if using a regular user is preferred instead of root.

Open a terminal.

Run the apt-get update command. This will download the updated list of packages (applications and tools) that are available to install.

```apt-get update```

Once the update is finished, run the following command to update non-system packages to their last stable version:

```apt-get upgrade```

When asked to continue, press Y and then press Enter.

Next, let's upgrade our system. Type the following command and press Enter:

```apt-get dist-upgrade```


  
</Details>
