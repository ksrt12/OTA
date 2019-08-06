
====================
     08-06-2019
====================

   * art/
3fca776287 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/art into pie

   * build/make/
168ecc715 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/build into pie

   * device/xiaomi/gemini/
3a5bbde4 Merge tag 'android-9.0.0_r47' into 9.0

   * frameworks/av/
fff6217f13 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/frameworks/av into HEAD

   * frameworks/base/
e13a0d65f9c Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/frameworks/base into pie

   * frameworks/native/
37409432e Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/frameworks/native into HEAD

   * packages/apps/Dialer/
639206d23 Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
d2f9ee5 toggle torch proximity check [2/2]
c6d890b Rework hw button illumination
6788fea Revert "Pocket judge"
d840e68 Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Settings/
f1af0c5a56 Support to notify connected/disconnected stations
a1437ea6b3 Havoc Build Date [2/2]
f040e13368 DeviceInfoSettings: Bring back CAF/AOSP tags
91d6778d30 my colors
9cf8081f1b Revert "Revert "Settings: Add toggle for proximity wake""

   * system/bt/
e3dc6b4cf Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/system/bt into HEAD
f20c234bb Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
6ea055ead RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
e7698d0a2 sdclang: true
81bd1ef49 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
3c3d379c2 Allow adb root even in no debuggable builds

   * system/libhwbinder/
c576e0d Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/system/libhwbinder into HEAD

   * vendor/havoc/
51e46aa3 update Lawnchair to alpha-2357

   * vendor/support/
13c41f5 add variables for buttom backlight

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


