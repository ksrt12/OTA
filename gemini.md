====================
     03-30-2019
====================


   * external/chromium-webview/
c857034 use Bromite System WebView 73.0.3683.88

====================
     03-29-2019
====================


====================
     03-28-2019
====================


   * packages/apps/Settings/
501f46d418 Revert "Change Battery drawable"

   * system/bt/
8e407eed7 Bluetooth: Fix BT calls

====================
     03-27-2019
====================


   * frameworks/base/
2bfad421e6a0 Revert "hwui: Enable quicksilver"
ffb83eb07ce3 Ambient music ticker: fix text scrolling on AoD

   * packages/apps/Dialer/
b56cb3d41 Make proxi sensor smart-case friendly
4df34762b Fix incorrect proximity sensor behaviour

   * packages/apps/HavocSettings/
7bf0703 Settings: Adaptive icon system-wide setting [2/3]
cdfedc5 Interface: Get rid of Controllers

   * system/core/
47f9f45e6 Fix path for treble default prop
cde05b220 Allow adb root even in no debuggable builds
b3b777a81 healthd: make periodic battery status a debug message

   * vendor/nxp/opensource/commonsys/packages/apps/Nfc/
0fbdd877 fix
f7168107 NFC: Fix NFC enable issue for CDP or RCM platforms

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


   * build/kati/
64200d7 Sort results of output from the "find" command
deb7807 Ignore TMPDIR when calculating the kati stamp
5e93bef Silence FindEmulator

   * frameworks/base/
f64192921679 SystemUI: Fix multiuser icon glitch in QS footer
4b53510542a7 SystemUI: Add Cellular tile icon from OOS
9f4f73efb0d6 Revert "Navbar: Do not fiddle with haptic feedback"
a0f527fffa00 base: Cleanup SystemUI tuner

   * packages/providers/DownloadProvider/
0d3a49f DownloadProvider: Stop using Arrays.checkOffsetAndCount
c4579dd Downloaded content is deleted if Download folder is renamed using MTP
c61600e DownloadProvider: allow more redirects
363c0c9 Stop download from the site with invalid certificate
3ad8e0a Add support to manually pause/resume downloads [2/2]
983e6cd Remove download notification after preview
a6c6ab6 Add download speed, remaining time, and percentage in notification

====================
     03-24-2019
====================


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
8647b01 Revert "Revert "Screen off animations [2/2]""
774d40c Revert "Add toggle for hiding QS drag handle [2/2]"

   * packages/apps/Settings/
8cdd773a26 Settings: Fix actionbar title for HAFR
e4220b2504 Revert "Settings: Move Notch settings to display"

   * packages/apps/SmartNavSettings/
7cf3e9a SmartNavSettings: Cleanup and fixes

====================
     03-23-2019
====================


====================
     03-22-2019
====================


   * frameworks/base/
e9add4667c34 Revert "services: allow to force "never" mode for display cutout [1/2]"
5098a4473974 Ambient music ticker: fix text scrolling glitches
4eb5f92764b5 Improve ambient play layout on keyguard
a06b2c4cb89f Ambient music: do not extend pulse notification when not needed
ba8c13ff863e Revert "Ambient music: Use animated icon"

   * vendor/MiuiCamera/
b002a3d Ready For Build
d9260f9 Fix Buiding Error

====================
     03-21-2019
====================


   * frameworks/av/
50b4ed6a98 Fixed audioserver crash in monkey test
afc6302dfe audioflinger: do not idle thread if active tracks exist
55272b5233 audio: ensure effect chain with specific session id is unique
b7b4d787d3 audioflinger: Throttle output if no active tracks
a209cae7bb audio: don't apply ramp if track is paused before the first mix
995cf80e1b Request to reset effect buffer in clearInputBuffer

   * packages/apps/HavocSettings/
c483fad Add mido in devices

