
====================
     05-11-2019
====================


   * frameworks/base/
2a5dcb14869c Support CALLBACK_TYPE_SENSOR_ROUTING
4c6586400645 Revert "SystemUI: Add Cellular tile icon from OOS"
c751452ff6c4 Keyguard: Don't listen for fingerprint when prox.sensor is covered
e61b272d4ba1 show bt battery for all devices
2b7d429bf20d change battery save color
3bdc88028bdb fix answer from home key
1e1253cfa6a1 toggle torch proximity check [1/2]
5be094561703 proximity check for all wake keys
8b46dc383f8e Havoc Build Date [1/2]
2cf7c4ce06a4 fix button backlight
2221c8157c24 fix priv-apps permissions
ff1d2b1c66d9 for gemini: Revert "Revert "Proximity check on wake""
dc1988c8ce23 Revert "hwui: Enable quicksilver"
3f439014233c SystemUI: Fix notification lag
0cc9ce5a0597 Fix translation derps

   * packages/apps/HavocSettings/
9305707 toggle torch proximity check [2/2]
593e943 Rework hw button illumination
1663aa6 Revert "Pocket judge"

   * packages/apps/Settings/
c373eec250 Havoc Build Date [2/2]
8f88b766a3 DeviceInfoSettings: Bring back CAF/AOSP tags
af45c7d1fa Revert "Revert "Settings: Add toggle for proximity wake""
1ceb84b685 my colors
8772b85d44 Settings: Smart Charging (2/4)
4af6b3c5af Update Turkish translations

====================
     05-10-2019
====================


   * frameworks/base/
910f16a6dc03 pocket: Allow to listen for fingerprint
b67436c217d7 base: Smart Charging (1/4)
fe2631fc0daa Android Q text clock Turkish translation
a73cdc203b91 Fix Russian translation

   * packages/apps/HavocSettings/
d5825cd Update Turkish translations

   * packages/apps/SmartNavSettings/
e8827d0 Fix typo in Turkish translation

====================
     05-09-2019
====================


   * external/wpa_supplicant_8/
98d2504a Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/external/wpa_supplicant_8 into HEAD

   * frameworks/base/
9a5735e92370 Fix derp on "Fix screen pinning unlock with hwkeys"
af02dafd1d6c carrierlabel & left clock: Properly handle View Visibility
97245b88ba94 Merge tag 'android-9.0.0_r37' into pie
659aa372e4a7 LiveDisplay: Disable 'Reduce power consumption'
a7c822b8166b SystemUI: Set proper color for battery text view
7dd64e2b3202 Improvements for swipe to screenshot
974e13d556ce Cutout force full screen: Remove fullscreen checks
ca7289f032ab Android Q text clock Vietnamese translation
a615e92e7cb0 Android Q text clock Russian translation
99c92ab648a2 Android Q text clock Spanish translation
a869526b2baa Android Q text clock Persian translation
61e41cfe3e8c Pocket lock improvements
e7a5e359d992 pocket: Don't show immersive mode confirmation when UI showing
aacd27da7381 pocket: Fix pocket lock view for display cutouts
75571eaabd4d pocket: Adjust sleep timeout for pocket lock view to 10 secs
235de4c4a3eb pocket: introduce pocket bridge
368fb959bb1a PocketService: Adjust light sensor rate to 400ms
b6ac06ba1511 pocket: Add hardware acceleration and properly maintain SYSTEM_UI flags
bbc95934c038 policy: introduce pocket lock
af68b0448769 pocket: introduce pocket judge
6e89a6738b49 Revert "Proximity check on wake"
b00b82e02d7e LiveDisplay: Disable by default
ae247ab7dde9 LiveDisplay: don't start services if phone is encrypted
c60248eff9e0 SystemUI: Add reading mode tile
bdd50d730a1f SystemUI: Add LiveDisplay tile
43549d33fea0 Introduce LiveDisplay from Lineage
a463a989c1a5 fwb: [1/2] Implement cutout force full screen
97845224c929 SystemUI: Change NFC icon
09c6c33db250 Logo: fix warnings
c1d415635537 SystemUI: Battery icon padding fixes
81c1634e97ad SystemUI: Fix percentage issues with Q style battery icon
0cc246b1115b QS: Add advanced location tile options
cffcc04eb011 Revert "QS: LocationTile: make it cycle modes"
e80875e07330 SystemUI: Enable/fix QS detail view & adapt to Pie
bfd7a824c7ee Fix inaccurate power algorithm of mobile radio
238e249ba6c1 Update Korean translation
aadf30448246 base: Add Q style to battery icon chooser [1/2]
7d4e27ac0ccc fod: dont show FP icons if FOD is in use
fc5402667092 fod: prevent reapplying modes if theres no changes
15d6f1500e25 fod: differentiate dreaming and pulse
aea796be776d Initial support for OnePlus in-display fingerprint sensor
a055923aa84c Lockscreen Visualizer: Automatic color based on wallpaper if no album art found
63483fb38d97 Add lockscreen visualizer customization for solid lines [1/2]

   * packages/apps/Bluetooth/
5e9dd2a3 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/Bluetooth into HEAD

   * packages/apps/Camera2/
477d68dc5 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/Camera2 into HEAD

   * packages/apps/CarrierConfig/
af43f03 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/CarrierConfig into HEAD

   * packages/apps/CellBroadcastReceiver/
0856286 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/CellBroadcastReceiver into HEAD

   * packages/apps/Contacts/
bfa5ce8a8 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/Contacts into HEAD

   * packages/apps/Dialer/
0a150306a Revert "Fix in-call buttons layout"

   * packages/apps/DocumentsUI/
4a94ca0e Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/DocumentsUI into HEAD

   * packages/apps/EmergencyInfo/
f2614ab Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/EmergencyInfo into HEAD

   * packages/apps/HavocSettings/
31541f7 Add new maintainer for Redmi 4 Prime
c6163d9 Add nx531j to devices

   * packages/apps/Nfc/
688aa4b7 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD

   * packages/apps/PackageInstaller/
8abb14f7 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/apps/PackageInstaller into HEAD

   * packages/inputmethods/LatinIME/
fe1079fe5 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/inputmethods/LatinIME into HEAD

   * packages/providers/DownloadProvider/
6644967 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/providers/DownloadProvider into HEAD

   * packages/providers/MediaProvider/
4f41739 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/providers/MediaProvider into HEAD

   * system/bt/
9180f134f Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
819d5b61e RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
3fe933b4d Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
f4132553c Allow adb root even in no debuggable builds

   * vendor/support/
593a8a6 add variables for buttom backlight

====================
     05-08-2019
====================


   * external/turbine/
2eae284 Merge tag 'android-9.0.0_r37' into pie

   * external/wpa_supplicant_8/
36dfa10a Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/external/wpa_supplicant_8 into HEAD

   * frameworks/av/
871d171ec3 Merge tag 'android-9.0.0_r37' into pie

   * frameworks/opt/net/wifi/
b6fe3c4de Merge tag 'android-9.0.0_r37' into pie

   * hardware/nxp/nfc/
0aa8b67 Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/Camera2/
3d314109b Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/CarrierConfig/
0a273b2 Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/CellBroadcastReceiver/
a1c4dfe Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/Contacts/
f53751077 Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/DocumentsUI/
6087363c Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/EmergencyInfo/
aea52d0 Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/HavocSettings/
8629aea Settings: [2/2] Implement cutout force full screen
4845d7b Revert "Revert "Pocket judge""

   * packages/apps/Nfc/
77004b0d Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/PackageInstaller/
643a9971 Merge tag 'android-9.0.0_r37' into pie

   * packages/apps/Settings/
d54031894b Merge tag 'android-9.0.0_r37' into pie
ad8520a077 Revert "Settings: Add toggle for proximity wake"
f3991fa9b3 Settings: Changes for LiveDisplay

   * packages/inputmethods/LatinIME/
d29bef2c2 Merge tag 'android-9.0.0_r37' into pie

   * packages/providers/DownloadProvider/
145807f Merge tag 'android-9.0.0_r37' into pie

   * packages/providers/MediaProvider/
51de237 Merge tag 'android-9.0.0_r37' into pie

   * prebuilts/r8/
2cfede7 r8: Update D8 and R8 to 1.5.23-dev
01b10b1 r8: Update D8 and R8 to 1.5.22-dev
f988252 r8: Update D8 and R8 to 1.5.21-dev

   * system/bt/
ed00153ec Merge tag 'android-9.0.0_r37' into pie

   * system/core/
bd9b031cc lmkd: bump process priority and set to FOREGROUND group before kill
468dccd34 Run BoringSSL self test during startup

   * system/libhwbinder/
307ab5e Merge tag 'android-9.0.0_r37' into pie

   * system/netd/
2af70af Merge tag 'android-9.0.0_r37' into pie

   * system/tools/hidl/
57e363b Merge tag 'android-9.0.0_r37' into pie

   * system/vold/
5017501 Merge tag 'android-9.0.0_r37' into pie

====================
     05-07-2019
====================


   * hardware/havoc/interfaces/
520c203 interfaces: Add 2.0 livedisplay interfaces

====================
     05-06-2019
====================


   * packages/apps/Settings/
1b07627044 Settings: Fix missing battery icon

====================
     05-05-2019
====================


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

