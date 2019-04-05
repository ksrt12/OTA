====================
     04-05-2019
====================


   * frameworks/base/
46ecd376751b Revert "SystemUI: Add Cellular tile icon from OOS"
f02c213982e6 Keyguard: Don't listen for fingerprint when prox.sensor is covered
a70cfa97340a show bt battery for all devices
656d1af4d7c0 change battery save color
586895a20a60 fix answer from home key
2334e1db8a25 toggle torch proximity check [1/2]
6e7e4fab1d90 proximity check for all wake keys
0d2dd8a7e6fc Havoc Build Date [1/2]
26b5183a6892 fix button backlight
c7bc4341904a fix priv-apps permissions

   * packages/apps/Dialer/
512f2874d Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
4219bf7 toggle torch proximity check [2/2]
a60a85c Rework hw button illumination

   * packages/apps/Settings/
6719222405 Havoc Build Date [2/2]
f2508a3e14 DeviceInfoSettings: Bring back CAF/AOSP tags
c0f1f31309 my colors

   * system/core/
0a0f28cb4 Fix path for treble default prop
4aac16a79 Allow adb root even in no debuggable builds

   * vendor/huawei/kiwi/
187cf0b kiwi: Remove btnvtool

   * vendor/support/
7a4a501 add variables for buttom backlight

====================
     04-04-2019
====================


   * packages/apps/HavocSettings/
8be2d6f Settings: Fix typos

   * prebuilts/clang/host/linux-x86/
61537703 Update prebuilt Clang to r353983b.

====================
     04-03-2019
====================


   * external/vixl/
33132247 libvixl: Disable use of dex2oat pgo profile [1/2]

   * frameworks/base/
9c97433df831 Revert "hwui: Enable quicksilver"
bac951595126 Merge tag 'android-9.0.0_r35' into pie
4a127c6ce48f GamingModeTile: stop adjusting volume

   * packages/apps/Bluetooth/
9cee3b33 Merge tag 'android-9.0.0_r35' into pie

   * system/bt/
1128e8c70 Merge tag 'android-9.0.0_r35' into pie

   * system/netd/
a5767e1 Merge tag 'android-9.0.0_r35' into pie

====================
     04-02-2019
====================


   * external/google/
39d0cdb SmartNav: Fix NPE when navbar is not set to stock mode
5d47a24 elmyra: Adapt to smartnav changes
f3917f0 Init Havoc...

   * frameworks/base/
5e994a3c4a8c LTE tile: Remove oreo style slashes
24005c2812a8 base: Add Lockscreen cover art filter [1/2]
77368697353c ImageHelper: add getBlurredImage
4bfb71245d11 Dreamliner: Disable DockObserver conditionally
dc5a685b6eb9 Dreamliner: Reorganise the external repo [2/2]
077ba49cf291 ActionUtils: Reverse actions for QS and notification panel
5354d7ae854d Active Edge: allow to choose a specific app activity [4/4]
05ad0b3835d7 Introduce long squeeze action [3/3]

   * frameworks/opt/slimrecent/
e282441 Slimrecents: catch IllegalArgumentException too

   * packages/apps/Browser/
6cf19b0 Browser: Update assets to use outline style
ac48339 Browser: Increase content padding for search bar
09e187b Browser: Use round search bar
ad897aa Browser: Use Pixel blue accent
c271bf4 Browser: QuickTiles for Favorites, Incognito, and New Tabs
6807d03 Browser: QuickTiles for Favorites, Incognito, and New Tabs
309478e Browser: Add save form data setting
4de469a Browser: Add Adblocker capabilities
788eecd Browser: Let the system know we're changing bar colors
c9fe68d Browser: Add a setting to set incognito defaults
cceb503 Browser: Don't save form data in incognito mode
9e981e7 Browser: Begin rebase onto newer Jelly

   * packages/apps/HavocSettings/
e79ac79 Settings: Add Lockscreen cover art filter [2/2]
1264f64 Fallback to "no action" when an application gets removed [2/2]
3c939ca Active Edge: allow to choose a specific app activity [3/4]
74a291a Introduce long squeeze action [2/3]

   * system/core/
db08c342f Filter out QTI performance spam
0f5db3580 Shut up camera and wcnss debug output
e0aa9113a Filter GalleryDatab*

   * system/vold/
f7bdc95 increase timeout for waiting on block device

   * vendor/support/
66b4a13 Fix displaying units for CustomSeekBarPreference
a1166d1 App Picker: Add back press override
261216d Active Edge: allow to choose a specific app activity [2/4]

====================
     04-01-2019
====================


====================
     03-31-2019
====================


   * kernel/huawei/kiwi/
c3917bf4ac0 kiwi: defconfig: Set CONFIG_USB_MSM_OTG flag

   * vendor/huawei/kiwi/
46602fc kiwi: Remove 32bit bt blobs

====================
     03-30-2019
====================


====================
     03-29-2019
====================


====================
     03-28-2019
====================


   * packages/apps/HavocSettings/
18f9e1a Add natrium in devices

   * system/bt/
8e407eed7 Bluetooth: Fix BT calls

====================
     03-27-2019
====================


   * frameworks/base/
ffb83eb07ce3 Ambient music ticker: fix text scrolling on AoD

   * packages/apps/Dialer/
b56cb3d41 Make proxi sensor smart-case friendly
4df34762b Fix incorrect proximity sensor behaviour

   * packages/apps/HavocSettings/
50b8b8a Give Tushar a promotion
8bb45d8 Drop tulip
7bf0703 Settings: Adaptive icon system-wide setting [2/3]
cdfedc5 Interface: Get rid of Controllers

   * system/core/
b3b777a81 healthd: make periodic battery status a debug message

