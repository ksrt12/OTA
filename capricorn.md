====================
     04-01-2019
====================


====================
     03-31-2019
====================


====================
     03-30-2019
====================


====================
     03-29-2019
====================


====================
     03-28-2019
====================


====================
     03-27-2019
====================


   * external/skia/
c7981cb4fd Merge branch '9.0' of https://github.com/syberia-   */platform_external_skia into HEAD

   * frameworks/base/
3fcb4534198a Revert "SystemUI: Add Cellular tile icon from OOS"
0d57cb15407f Keyguard: Don't listen for fingerprint when prox.sensor is covered
50d274049f79 show bt battery for all devices
c2df2a14bd97 change battery save color
f2c2a7813806 fix answer from home key
b2f92b8788e6 toggle torch proximity check [1/2]
ab9b9e804ca8 proximity check for all wake keys
efa4c7be9e06 Havoc Build Date [1/2]
3d59f3fbefbf fix button backlight
2ef4433314c1 fix priv-apps permissions
2bfad421e6a0 Revert "hwui: Enable quicksilver"
ffb83eb07ce3 Ambient music ticker: fix text scrolling on AoD

   * packages/apps/Dialer/
43bea5d3b Revert "Fix in-call buttons layout"
b56cb3d41 Make proxi sensor smart-case friendly
4df34762b Fix incorrect proximity sensor behaviour

   * packages/apps/HavocSettings/
6680ca5 toggle torch proximity check [2/2]
c11308d Rework hw button illumination
50b8b8a Give Tushar a promotion
8bb45d8 Drop tulip
7bf0703 Settings: Adaptive icon system-wide setting [2/3]
cdfedc5 Interface: Get rid of Controllers

   * packages/apps/Settings/
b9b9ccc2b2 Havoc Build Date [2/2]
65a4c1f3d7 DeviceInfoSettings: Bring back CAF/AOSP tags
a2a0461049 my colors

   * system/bt/
8e407eed7 Bluetooth: Fix BT calls

   * system/core/
47f9f45e6 Fix path for treble default prop
cde05b220 Allow adb root even in no debuggable builds
b3b777a81 healthd: make periodic battery status a debug message

   * vendor/nxp/opensource/commonsys/packages/apps/Nfc/
0fbdd877 fix
f7168107 NFC: Fix NFC enable issue for CDP or RCM platforms

   * vendor/support/
e127905 add variables for buttom backlight

====================
     03-26-2019
====================


   * frameworks/base/
38c5771c6134 base: Adaptive icon system-wide setting [1/3]
3ec9f6862a19 base: Fix partial screenshot
8b16537b9c99 SettingsLib: Increase battery saver outline thickness

   * vendor/support/
9abcdbe Add SystemPropListPreference

====================
     03-25-2019
====================


   * frameworks/base/
f64192921679 SystemUI: Fix multiuser icon glitch in QS footer
4b53510542a7 SystemUI: Add Cellular tile icon from OOS
9f4f73efb0d6 Revert "Navbar: Do not fiddle with haptic feedback"
a0f527fffa00 base: Cleanup SystemUI tuner

====================
     03-24-2019
====================


   * build/kati/
64200d7 Sort results of output from the "find" command
deb7807 Ignore TMPDIR when calculating the kati stamp
5e93bef Silence FindEmulator

   * frameworks/base/
0375302fffc2 ColorFade: Silence logspam
b12bd87ccc98 Revert "Revert "base: screen off animation config [1/2]""
478e7efeba37 base: Make vendor mismatch message optional
3df01015f8e8 base: Let's use MD2 icons for Powermenu
63d6be741a91 Revert "ViewRoot: Ensure we release surface from setWindowStopped"
c7c72b0413c1 core: view: Add property to disable VSync for CPU rendered apps
d0872f293806 add VSYNC scheduled flag and avoid two doFrame calls in one period
68b8fe7203cf Fix potential crash when per-procstate cpu times tracking is turned on
3c5931cd60f2 Return null on failed insert due to permissions
27c88efd79d6 Fix RouterAdvertisementDaemon thread leakage problem
bd9d1e9789ac Volume panel: Fix incorrect positioning
ffcdf0ae2cbb OP Gestures: Fix navbar detection and landscape mode
1a19739c3f56 SettingsLib: Bring the dividers back to life
19e91055d24b QSPanel: Always show divider like OOS
fd2b666609f8 base: Persistent settings icon on qs panel for 9.x
c99131b338f7 Revert "base: SystemUI: add tuner to hide qs drag handle"

   * packages/apps/HavocSettings/
970692b Settings: Cleanup and fixes

   * packages/apps/Settings/
8cdd773a26 Settings: Fix actionbar title for HAFR
e4220b2504 Revert "Settings: Move Notch settings to display"

   * packages/apps/SmartNavSettings/
7cf3e9a SmartNavSettings: Cleanup and fixes

   * packages/providers/DownloadProvider/
0d3a49f DownloadProvider: Stop using Arrays.checkOffsetAndCount
c4579dd Downloaded content is deleted if Download folder is renamed using MTP
c61600e DownloadProvider: allow more redirects
363c0c9 Stop download from the site with invalid certificate
3ad8e0a Add support to manually pause/resume downloads [2/2]
983e6cd Remove download notification after preview
a6c6ab6 Add download speed, remaining time, and percentage in notification

====================
     03-23-2019
====================


   * packages/apps/HavocSettings/
8647b01 Revert "Revert "Screen off animations [2/2]""
774d40c Revert "Add toggle for hiding QS drag handle [2/2]"

