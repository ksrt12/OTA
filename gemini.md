====================
     03-15-2019
====================


   * frameworks/base/
a3f0a127f7d5 Revert "hwui: Enable quicksilver"
1321215e4602 Re-add WPS implementation (2/3)
d2ceb722e112 base: Fix less frequent notification sounds value
357ab2a80459 base: Add vibrate util methods
de6005fee923 base: Turn on display if Doze On Charge is Enabled
c2ce0cd906e9 Volume panel: Add notification volume row if unlinked
1c43a913abd0 Code improvements for expanded volume panel

   * frameworks/opt/net/wifi/
1d20bcb7d Re-add WPS implementation (3/3)

   * packages/apps/Settings/
7fc597f456 Re-add WPS implementation (1/3)

====================
     03-14-2019
====================


   * frameworks/base/
a64871a54dae Volume panel: Visual improvements
9e04b0d26950 base: Redo expanded volume panel for 9.x
f55f113a75b4 Volume panel: Do the same with less
6491c1a654e9 Volume panel: Fixes for unlinked notifications

====================
     03-13-2019
====================


   * frameworks/base/
d0e8013be14d Revert "Extended audio panel [1/2]"

====================
     03-12-2019
====================


   * frameworks/base/
69cdb751566b base: Code improvements QS footer visibilities
4ccfc811e872 BatteryMeterView: Fix logcat spam

====================
     03-10-2019
====================


   * frameworks/base/
c4d1cdb8bd6a WeatherClient: Check boot completed prop
ca8b6dca106b OP gestures: fix APP switch triggering

   * kernel/xiaomi/msm8996pro/
e9638f6b06cc sjit
3595e34d3c69 chpick and build lol

   * vendor/themes/
11a8a23 themes: Update GBoard MD2 themes

====================
     03-09-2019
====================


   * frameworks/base/
9824ee03058d Show mobile icons with left-to-right in order of slot index
8e39919ff56b Revert "SystemUI: Sort subscriptions in reversed order"
a3d60dd7a956 Revert "base: SystemUI: tuner: fix reorder of mobile slots"
4e7c92f11142 Keyguard: Remove carrier text for disabled SIMs
2e5f0162db8d Code improvements for "SystemUI: Refresh themes on dirty flash"

====================
     03-08-2019
====================


   * frameworks/base/
721ee3d68c5e Automagically set night mode when dark or black theme is turned on
0143a72a9947 Revert "base: Add Gboard overlay [1/2]"

   * packages/apps/HavocSettings/
918e35b Settings: Fixes
dd44649 Settings: Add back About section

   * packages/apps/Settings/
40dafa984a Changelog: Fix title on actionbar
046443c5f6 Changelog: Add left padding
091dc40239 Settings: update changelog activity * improve code
48aec6ce33 Changelog: Fix text selection with dot
40c4c9ccce Changelog: clean and make themeable before: https://imgur.com/a/ylSQG after: https://imgur.com/a/GdnPN
8dbd4b8fe8 Changelog: prettify
c651d5971b Settings: Changelog

   * packages/apps/SmartNavSettings/
23f249b Settings: Fixes

   * vendor/themes/
52c3f50 Revert "themes: Add Gboard overlay [2/2]"

====================
     03-08-2019
====================


   * frameworks/base/
7b812043499a Keyguard: Don't listen for fingerprint when prox.sensor is covered
a56d2508b2d3 show bt battery for all devices
02983b2019b5 change battery save color
e5c11428ef26 fix answer from home key
dd49bfdc0625 toggle torch proximity check [1/2]
e857e26e14fe proximity check for all wake keys
c7a53ff8f40d Havoc Build Date [1/2]
753106c3da9c fix button backlight
f2a5cfa356eb fix priv-apps permissions
f11a55d79a23 Revert "hwui: Enable quicksilver"
721ee3d68c5e Automagically set night mode when dark or black theme is turned on
0143a72a9947 Revert "base: Add Gboard overlay [1/2]"

   * packages/apps/HavocSettings/
afa4225 toggle torch proximity check [2/2]
f401726 Rework hw button illumination
918e35b Settings: Fixes
dd44649 Settings: Add back About section

   * packages/apps/Settings/
56b5263a62 Havoc Build Date [2/2]
23d5cc4ee9 DeviceInfoSettings: Bring back CAF/AOSP tags
3076d7e0e2 my colors
40dafa984a Changelog: Fix title on actionbar
046443c5f6 Changelog: Add left padding
091dc40239 Settings: update changelog activity * improve code
48aec6ce33 Changelog: Fix text selection with dot
40c4c9ccce Changelog: clean and make themeable before: https://imgur.com/a/ylSQG after: https://imgur.com/a/GdnPN
8dbd4b8fe8 Changelog: prettify
c651d5971b Settings: Changelog

   * packages/apps/SmartNavSettings/
23f249b Settings: Fixes

   * vendor/themes/
d58d9db themes: Fix volume panel footer bg
52c3f50 Revert "themes: Add Gboard overlay [2/2]"

====================
     03-07-2019
====================


   * hardware/nxp/nfc/
c310d47 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/nxp/nfc into HEAD

   * hardware/nxp/secure_element/
8585787 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/nxp/secure_element into HEAD

   * packages/apps/Nfc/
0c4a6522 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/apps/Nfc into HEAD

   * system/core/
d08ffcc4a Allow adb root even in no debuggable builds

   * system/nfc/
d469ef3 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/system/nfc into HEAD

   * vendor/nxp/opensource/commonsys/packages/apps/Nfc/
f0d81de2 fix build warnings

====================
     03-06-2019
====================


   * external/skia/
7f877d0300 Merge branch '9.0' of https://github.com/syberia-project/platform_external_skia into HEAD

   * frameworks/av/
a3a06f02cf Merge tag 'android-9.0.0_r34' into pie

   * frameworks/base/
cafce7535485 Merge tag 'android-9.0.0_r34' into pie
c4ce24fec895 base: Fix camera hal1 prop

   * hardware/nxp/nfc/
1a42707 Merge tag 'android-9.0.0_r34' into pie

   * packages/apps/Bluetooth/
0461c553 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_apps_Bluetooth into HEAD

   * packages/apps/CarrierConfig/
348518b Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_apps_CarrierConfig into HEAD

   * packages/apps/CellBroadcastReceiver/
16720e7 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_apps_CellBroadcastReceiver into HEAD

   * packages/apps/Dialer/
29837d5e3 Revert "Fix in-call buttons layout"

   * packages/apps/DocumentsUI/
5b111000 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_apps_DocumentsUI into HEAD

   * packages/apps/EmergencyInfo/
cadec59 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_apps_EmergencyInfo into HEAD

   * packages/apps/Nfc/
45f22999 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_apps_Nfc into HEAD

   * packages/apps/PackageInstaller/
29e48bf4 Merge tag 'android-9.0.0_r34' into pie

   * packages/apps/Updater/
4b882eb my OTA
b4c8ff5 Updater: Assume older Android version to be incompatible

   * prebuilts/r8/
2e25531 r8: Update D8 and R8 to 1.5.9-dev

   * system/bt/
b3c794b73 Merge tag 'android-9.0.0_r34' into pie

   * system/core/
6f9956b09 Export maximum number of fds/ints in a native_handle.

   * system/libhwbinder/
3a1f28e Merge tag 'android-9.0.0_r34' into pie

   * system/tools/hidl/
30d29fd Merge tag 'android-9.0.0_r34' into pie

====================
     03-05-2019
====================

   * art/
e5b1f29adb Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/art into HEAD

   * frameworks/av/
95a03429db av: Fix Derp

   * vendor/support/
d2d1947 add variables for buttom backlight

====================
     03-04-2019
====================


   * frameworks/av/
67f618d25b effects: Initialize volume at -96

   * frameworks/base/
1981ac20dfca SystemUI: Remove unused resources
d86b25fd0ae6 SystemUI: OneHandMode QS tile
e382a6dac638 SystemUI: Update SoundTile
1a54bf6bc23d SystemUI: Update ScreenRecord tile
610d899a3d75 SystemUI: Update OnTheGo tile
9b36c4a9ecd0 base: migrate isServiceRunning check to HavocUtils
b7e78c7f6dc5 UpdateEngine: Add perf mode binder interface
49930c4e622e SystemUI: Fix Powermenu layout
23d59883f578 Network Traffic: Add more customizations and improvement [2/2]
f55a341cd962 base: Add Gboard overlay [1/2]
1c92e0339711 SystemUI: Fix margin for small QS icons
9c3cf7428f98 base: Expose system icon area weight
601cae9a1f19 ColorDisplayService: change default night light brightness (2/2)
e48751dfc82c Revert "SettingsProvider: Hide sensitive notification content"
e6eaa3ac460a Do not apply date customization to QS clock
70f75f83b332 SystemUI: Always show date in QS header
cb6399f11d22 Clock: Always show time in the quickstatusbar
ab520a10b74a Network traffic: Retain our notch check
f81c5b02f563 Notch friendly carrier label [1/2]
31b7ddc1c326 base: Link more things to a common dimen
1103cbd0ba2f SystemUI: Make recents grid view accept more than 8 tasks
85049f58bf73 Revert "Disable grid recents [1/2]"
fa7abbf51fdb base: Supress telephony crashing platform
01ac1bc1a81a am: Avoid scheduling service restart twice
675549bac3b5 base: screenrecord: update notif text for high aspect ratio devices
e4cffa346a55 Method to detect a notch'd device
0f806af7f38e VisualizerView: Don't add null end actions to animators
ebcd84dc5fc4 SystemUI: grant missing READ_PHONE_STATE permission
b7c983d2d326 base: Fix Auto-hide clock overlapping on keyguard
e5d10d6c1b39 Add option to auto hide status-bar clock [1/2]
19d7631f254d Power button flashlight: allow to skip proximity check per device
e48dac2c66a2 Power button flashlight toggle: add proximity sensor check
5ae948fb0418 Allow doubletap/longpress power to toggle torch [1/3]
456b598393c6 Revert "Power button flashlight"
0a7e24b81a14 Helper functions for SmartActions action binding [1/2]
97e79d9bc1df CustomActions: Use settings provider to store value [2/3]
4653509aff81 ActionUtils: Improve ringer modes
3f54a935f646 ActionUtils: Ringer modes

====================
     03-03-2019
====================


   * external/bash/
a40f251 bash: Silence all build warnings

   * external/openssh/
729a9063 openssh: Silence build warnings

   * external/rsync/
4a30b87d rsync: Silence build warnings

   * packages/apps/Bluetooth/
d559f31b Bluetooth: Remove unused string resources
364b045b Fix generating id in android namespace

   * packages/apps/Updater/
2fe39a6 Updater: Nuke Lineage's website on installation blocked dialog
789988b Updater: Always show preferences
4008406 Updater: Add changelog dialog
c9efcc7 Updater: Don't check version before install
fd0e37c Updater: Pixel UI redesign
c7eb31e Updater: Theme actionbar text too

====================
     03-02-2019
====================


   * external/sqlite/
c23543f sqlite: upgrade to SQLite 3.27.2

   * frameworks/base/
d9ac335ea88b VolumeDialog: avoid multiple animations on touch spam

   * hardware/qcom/display-caf/msm8916/
197a40e hwc: Remove _vendor from libbfqio

   * hardware/qcom/fm/
1b4078d Merge tag 'LA.UM.7.3.r1-06900-sdm845.0' into HEAD

   * packages/apps/HavocSettings/
84201f0 Settings: Increase rounded content padding
88e53ec Network Traffic: Add more customizations and improvement [1/2]

   * packages/providers/WeatherProvider/
46e8f56 WeatherProvider: Fix conditions

====================
     03-01-2019
====================


   * packages/apps/Updater/
1be7297 Updater: Use accent for actionbar items
e3567d8 Updater: Expose the lower background color
d33726f Init Havoc...

====================
     02-28-2019
====================


   * external/wpa_supplicant_8/
f1e24465 wpa_supplicant: Disable EAP_PROXY
6cba6c5f Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/external/wpa_supplicant_8 into 9.0

====================
     02-27-2019
====================


   * device/qcom/sepolicy-legacy/
8cd0ca1 sepolicy: Resolve cameraserver denials
18203e2 legacy: Resolve hal_camera_default denials
2310fa8 sepolicy: Label vendor.post_boot.parsed
78c6497 sepolicy: Resolve hal_nfc denials
6447cb7 legacy: Resolve rome BT denials
6185be5 sepolicy: Correctly label display.qservice per SoC
62e0e65 Revert "legacy: allow init to read /proc/device-tree"
21dd2e0 legacy: Label /data/misc/display again
9f1e187 legacy: Ignore neverallows

   * hardware/qcom/fm/
f44384a Automatic translation import

   * packages/apps/Bluetooth/
99da10d1 Automatic translation import

   * packages/apps/CellBroadcastReceiver/
6ca28b4 Automatic translation import

   * packages/apps/CertInstaller/
bb8806e Automatic translation import

   * packages/apps/DocumentsUI/
02da8bc0 Automatic translation import

   * packages/apps/EmergencyInfo/
4c0429e Automatic translation import

   * packages/apps/FMRadio/
33e0f38 Automatic translation import

   * packages/apps/HTMLViewer/
4f3d2a2 Automatic translation import

   * packages/apps/KeyChain/
b9e2ade Automatic translation import

   * packages/apps/ManagedProvisioning/
34f61939 Automatic translation import

   * packages/apps/Nfc/
1be41703 Automatic translation import

   * packages/apps/PhoneCommon/
7fa4dbf Automatic translation import

   * packages/apps/SafetyRegulatoryInfo/
67a84d6 Automatic translation import

   * packages/apps/StorageManager/
e381bd7 Automatic translation import

   * packages/apps/Tag/
21c21c0 Automatic translation import

   * packages/apps/Terminal/
a22a21d Automatic translation import

   * packages/apps/TvSettings/
263066a4 Automatic translation import

   * packages/apps/UnifiedEmail/
4eb92ca6b Automatic translation import

   * packages/apps/Updater/
2849967 Automatic translation import

   * packages/apps/WallpaperPicker/
efb671b Automatic translation import

   * packages/services/BuiltInPrintService/
17c9346 Automatic translation import

   * packages/services/Mms/
600a172 Automatic translation import

   * vendor/qcom/opensource/thermal-engine/
3e8495d Merge tag 'LA.UM.7.3.r1-06900-sdm845.0' into HEAD

