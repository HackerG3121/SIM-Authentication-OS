**Day 01**

# What is Android?

* Mobile OS - Developed by Google - designed for touchscreen - built-in Linux Kernel - Open source - anyone can customize everything.

# What is AOSP?

* AOSP - Android Open Source Project
* Open source - control the innovation of another - AOSP to create custom variants of Android OS

# Android Architecture

Android is 5 layers of works

```bash
         Android Layers

          Application
               |
      Application Framework
               |
         System Services
               |
    HAL-(Hardware Abstraction Layer)
               |
         Linux Kernel
               |
            Hardware
```

# Linux Kernel

* Linux kernel is low level OS core - manage hardware, memory, processes, drivers.

# What is Android Framework?

* Providing High-level APIs & System Service that application use to access Android features without directly interacting with hardware.

# What is System Service?

* Its providing Telephony Manager
* Telephony service for Apps.

# HAL (Hardware Abstraction Layer)

* Providing Std. Interface - Android Framework & device specific hardware drivers.
* HAL is the "Translator".

# What is the Telephony Framework?

* Part of Android - provides ISP (VI/JIO/AIRTEL/BSNL) for voice calls/SMS/MMS/Data connection.
* Its the software stack that turns raw cellular hardware into usable phone features for apps and users.

```bash
        Telephony Manager
                ↓
     Phone Interface Manager
                ↓
               RIL
                ↓
          Baseband Modem
```

# My Understanding

Day 01 (17/07/2026)

Today I am learn basics of Android.

**New words Today**

* AOSP - Android Open Source Project
* Telephony
* TelephonyManager
* HAL - Hardware Abstraction Layer
* TelephonyFramework

**Test by ChatGPT (as a mentor)**

Why doesn't Android simply block SIM removal today?

ANSWER:
Google isn't simply blocked.

Key reasons
-> Physical security - anyone can power-off.
-> Visibility & Carrier diversity
   --> Legitimately swap SIMs.
-> Security model
   --> Android focuses on device level protection.
   --> Whole device to specific SIM.
