====================
     05-07-2019
====================


   * external/turbine/
bf068b5 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/external/turbine into HEAD

   * external/wpa_supplicant_8/
36dfa10a Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/external/wpa_supplicant_8 into HEAD

   * frameworks/av/
0eaf956cbc Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/frameworks/av into HEAD

   * frameworks/base/
615d50fb5989 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/frameworks/base into HEAD
8af9596e9a7f Fix error

   * packages/apps/Bluetooth/
b500beb3 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/Bluetooth into HEAD

   * packages/apps/Camera2/
bfe761cec Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/Camera2 into HEAD

   * packages/apps/CarrierConfig/
4413298 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/CarrierConfig into HEAD

   * packages/apps/CellBroadcastReceiver/
1e1c42d Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/CellBroadcastReceiver into HEAD

   * packages/apps/Contacts/
c2ee9d828 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/Contacts into HEAD

   * packages/apps/DocumentsUI/
8048ea99 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/DocumentsUI into HEAD

   * packages/apps/EmergencyInfo/
43f3ba4 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/EmergencyInfo into HEAD

   * packages/apps/HavocSettings/
e27056c toggle torch proximity check [2/2]
912dda1 Rework hw button illumination

   * packages/apps/Nfc/
3078bf9d Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD

   * packages/apps/PackageInstaller/
887b87a8 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/PackageInstaller into HEAD

   * packages/apps/Settings/
62cc0f60be Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/Settings into HEAD

   * system/bt/
e3db1774f Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/system/bt into HEAD
b8c8dc1cb Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
c7efe9d3c RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
9da82e76b Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
434f066f3 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/system/core into HEAD

   * system/libhwbinder/
b9cbdf6 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/system/libhwbinder into HEAD

   * system/netd/
8bd23ac Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/system/netd into HEAD

   * system/vold/
4ed2c4f Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/system/vold into HEAD

====================
     05-06-2019
====================


   * frameworks/base/
4c536ec098e2 Fix Russian translations
e3744e812f6c Android Q text clock Vietnamese translation
dd7d01852185 Fixing the escape character
b7fa2683b2b6 Android Q text clock Spanish translation

====================
     05-05-2019
====================


   * frameworks/base/
cb8e174c9601 Android Q text clock Persian translation
60e3d2089cb1 Revert "hwui: Enable quicksilver"
916e75196db6 Logo: fix warnings
643ada90a528 SystemUI: Battery icon padding fixes
7208f813476a SystemUI: Fix percentage issues with Q style battery icon
26b925ee7772 QS: Add advanced location tile options
9e45b8cae887 Revert "QS: LocationTile: make it cycle modes"
3567dc770c98 SystemUI: Enable/fix QS detail view & adapt to Pie
2bcb5451d1aa Fix inaccurate power algorithm of mobile radio
c1c59ad1dd38 Fix mWaitingForDrawnCallback of startImeAdjustAnimation
b25af19acd25 Update Korean translation

   * packages/apps/Settings/
1b07627044 Settings: Fix missing battery icon

====================
     05-04-2019
====================


   * frameworks/base/
dba47c8cf5e5 base: Add Q style to battery icon chooser [1/2]
0abd82d94036 fod: dont show FP icons if FOD is in use

   * packages/apps/Dialer/
54387b536 Automatic translation import
db23b54a8 Dialer: fix a few full screen photo issues
0aab3cf1d Dialer: Add full screen photo option
35052dab1 Make proxi sensor smart-case friendly
52ded1e79 Fix incorrect proximity sensor behaviour

   * packages/apps/HavocSettings/
340ee0e Update Korean translation

   * prebuilts/r8/
6935423 r8: Update D8 and R8 to 1.5.20-dev
dbbedca r8: Update D8 and R8 to 1.5.19-dev
d0f904c r8: Update D8 and R8 to 1.5.18-dev
7527f3d Update D8 and R8 to 1.5.12-dev
5392e09 r8: Update D8 and R8 to 1.5.10-dev

====================
     04-30-2019
====================


   * packages/apps/Bluetooth/
52dc89d3 Merge branch '9.0' of https://github.com/syberia-project*/platform_packages_apps_Bluetooth into HEAD

   * packages/apps/CustomDoze/
72fb66e Update Korean translation

====================
     04-28-2019
====================


   * packages/apps/HavocSettings/
5162059 Settings: Add Q style to battery icon chooser [2/2]

====================
     04-27-2019
====================


   * frameworks/base/
cec700bd060b fod: prevent reapplying modes if theres no changes
b2786dfc9032 fod: differentiate dreaming and pulse
b4f9f68b48ee Initial support for OnePlus in-display fingerprint sensor

   * prebuilts/clang/host/linux-x86/
5469971c Update prebuilt Clang to r353983c.

   * vendor/interfaces/
b1ef1bc add optional tags

====================
     04-25-2019
====================


   * packages/apps/Bluetooth/
907cc115 Fix leak of registerReceiver
eb1429ed HID: Fix the potential NPE in HidHostService jni callback

