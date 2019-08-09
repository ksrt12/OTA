
====================
     08-09-2019
====================


   * device/xiaomi/gemini/
8a20e40d msm8996-common: add QC3 permissions
d8c7ab8e Merge tag 'android-9.0.0_r47' into 9.0

   * packages/apps/HavocSettings/
844f68f add haptic feedback intensity control

====================
     08-08-2019
====================


   * frameworks/base/
7f86c416023 OP Gestures: Enable gestures on the keyguard as well

   * vendor/havoc/
a867cdd9 update GoogleWallpapers
3df445e4 Havoc 2.8

====================
     08-07-2019
====================


   * frameworks/av/
e8b2ab4fe4 Merge tag 'android-9.0.0_r47' into pie

   * frameworks/base/
f2a125a90cc GamingMode: Clean up for dynamic mode
8f3b2103212 SystemUI: Fix SystemUI failed to go to doze issue
9aefcce16d1 Fix sim pin on DSDS
3847ce99a41 Dismiss SIM lock page after correct SIM
17a8bb77949 When data switches during voice call, make sure signal bar updates it.
f96fa074ed6 Stop USB Debugging authorization window dismissing on tap outside.
54484b41919 Update navigation bar upon change of display density
fc13ab0b19b Unable to input PIN with hardware keyboard
2cc42c075a9 NetworkManagement : Add ability to restrict app vpn usage
b266b764860 Switch widgets away from android.text.format.Time
b5671be46b1 Migrate telephony code away from Time
618a060de18 Remove unused class
4b695a2299c Remove unnecessary usage of deprecated Time class
c42ce8e2569 Add a basic benchmark for android.text.format.Time
15ddf7211cd Avoid use of DateUtilsBridge.icuTimeZone()
031b5ef5627 base: Introduce DisplayModeManager [1/2]

   * packages/apps/CustomDoze/
077344c CustomDoze: Add support for custom Tilt and Proximity sensors

   * packages/apps/Dialer/
337685180 Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
2a29a62 toggle torch proximity check [2/2]
c0de71b Rework hw button illumination
d3f1cfa Revert "Pocket judge"
ae37308 Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Nfc/
253db558 Merge tag 'android-9.0.0_r47' into pie

   * packages/apps/Settings/
909c1de28e Support to notify connected/disconnected stations
ad9c181dc6 Havoc Build Date [2/2]
e0a6541b31 DeviceInfoSettings: Bring back CAF/AOSP tags
048d24bb77 my colors
3f9cff67b1 Revert "Revert "Settings: Add toggle for proximity wake""
1cee15176d Merge tag 'android-9.0.0_r47' into pie
1a9f1de789 Settings: per-app VPN data restriction
2a4fc04b6d SimSettings: Fix preferred calls sim not being disabled

   * system/bt/
2fa72092e Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
d0c5a557b RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
1d924ddbd sdclang: true
8d850f8c9 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.
8b22bc44e Merge tag 'android-9.0.0_r47' into pie

   * system/core/
513bafa34 Allow adb root even in no debuggable builds

   * system/libhwbinder/
9ef1b59 Merge tag 'android-9.0.0_r47' into pie

   * vendor/qcom/opensource/audio/
2db65b4 policy_hal: Adapt to AudioMix API changes in f/av audiopolicy

   * vendor/support/
a35d03e add variables for buttom backlight

====================
     08-06-2019
====================

   * art/
3fca776287 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/art into pie

   * build/make/
168ecc715 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/build into pie

   * frameworks/base/
e13a0d65f9c Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/frameworks/base into pie

   * frameworks/native/
37409432e Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/frameworks/native into HEAD

   * vendor/havoc/
51e46aa3 update Lawnchair to alpha-2357

====================
     08-05-2019
====================


   * device/xiaomi/translations/
b1fd66a update 05082019

   * frameworks/av/
12cc0d00b5 libcameraservice: write all pkgNames

   * hardware/qcom/fm/
2cf84a8 Automatic translation import

   * packages/apps/FMRadio/
b3c56e7 Automatic translation import

====================
     08-04-2019
====================


   * frameworks/av/
75bf9b61d1 Camera: Consider the currently acquired input buffers

====================
     08-03-2019
====================


   * bootable/recovery/
45b03ada Make adb sideload work properly
62ece71c recovery: hide option to mount emulated storage after wiping data
14d1b2f4 recovery: Extend mountable check to all volumes and fix volume selection

   * hardware/broadcom/libbt/
4545703 libbt: configure audio codec right after firmware

   * system/netd/
08a4e54 NetD : Allow passing in interface names for vpn app restriction

====================
     08-02-2019
====================


====================
     08-01-2019
====================


   * external/chromium-webview/
8901da9 Update Chromium Webview to 76.0.3809.89

   * vendor/havoc/
9fb9bf70 update prebuilt calculator & deskclock
68c95147 update Lawnchair to alpha-2338

====================
     07-31-2019
====================


   * frameworks/base/
08e1a73c8fa Fix to register the receiver for all users
99e389ae119 Audio assets: add NFC sounds
62514f2c44f Import translations for Typographic Clock

====================
     07-30-2019
====================


====================
     07-29-2019
====================


====================
     07-28-2019
====================


====================
     07-27-2019
====================


   * frameworks/base/
f5daef6c3f2 TypographicClock: Tint top row with wallpaper primary color
5d6f8e78c48 Revert "Q Style Clock: Animate change in time"
94c385e513f MediaCodecInfo: Add support for level 6.2
9a33be1e474 base: Materialize gesture anywhere layout
a2a03156dc9 base : Fix GA crash and saving the gesture cache
d106a41109e base: Increase gesture anywhere width to 40px [1/2]
3d45ca143d7 base: Gesture Anywhere [1/3]
6cc10ef7207 SettingsLib: Hide QS tile overlays from app list
db3dd3d632c SystemUI: Ensure battery estimates update on callback

   * frameworks/opt/net/wifi/
51a8e96da Filter unsupported networks from Open network notifier
7d60ef996 wifi: Skip rmmod during the device shutdown/reboot
c973e0614 wifi-aware: (Re)-Set default discovery window after screen on.

====================
     07-26-2019
====================


====================
     07-25-2019
====================


   * external/gptfdisk/
c1ea282 gptfdisk: include gptcl.h after sgdisk.h

   * external/sqlite/
bb1fcc3 sqlite: upgrade to SQLite 3.29.0

   * packages/apps/Settings/
a08533291c Settings: rearrange Sounds page a little

====================
     07-24-2019
====================


====================
     07-23-2019
====================


   * frameworks/av/
f4ebc1b899 media: Add support for up to level 6.2 for AVC

====================
     07-22-2019
====================


====================
     07-21-2019
====================


   * packages/apps/HavocSettings/
26645d4 Settings: Increase gesture anywhere width to 40px [1/2]
85b2e9b Settings: Gesture Anywhere [2/3]

