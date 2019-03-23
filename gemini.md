====================
     03-24-2019
====================


   * frameworks/base/
0d84ba3cabba Keyguard: Don't listen for fingerprint when prox.sensor is covered
745bd8a47d54 show bt battery for all devices
465414e38b50 change battery save color
5d7d542ee44c fix answer from home key
ce14a24fe3cf toggle torch proximity check [1/2]
7edfcc265c37 proximity check for all wake keys
beb7a1a851e5 Havoc Build Date [1/2]
cd672837cd86 fix button backlight
16c37b626d4c fix priv-apps permissions
402d30850bdc Revert "hwui: Enable quicksilver"
fd984fe9ca08 Revert "Navbar: Do not fiddle with haptic feedback"
76d033826162 base: Cleanup SystemUI tuner
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
c0aeb32 toggle torch proximity check [2/2]
e55158a Rework hw button illumination
970692b Settings: Cleanup and fixes
8647b01 Revert "Revert "Screen off animations [2/2]""
774d40c Revert "Add toggle for hiding QS drag handle [2/2]"

   * packages/apps/Settings/
03ade1786d Havoc Build Date [2/2]
d0b0af6aa3 DeviceInfoSettings: Bring back CAF/AOSP tags
fcd45aa83b my colors
8cdd773a26 Settings: Fix actionbar title for HAFR
e4220b2504 Revert "Settings: Move Notch settings to display"

   * packages/apps/SmartNavSettings/
7cf3e9a SmartNavSettings: Cleanup and fixes

====================
     03-23-2019
====================


   * system/core/
53ed75cd8 Fix path for treble default prop

====================
     03-22-2019
====================

   * bootable/recovery/
37905b69 fix
a0de3d51 Android.mk: do not include file_contexts for P and up
cd202d46 applypatch: Link with bmlutils and mtdutils properly.
3a51f45f mtdutils: Convert makefile to bp.
4cd328a4 bmlutils: Convert makefile to bp.
c0a0aa35 libcrecovery: Convert makefile to bp.
f159b590 otautil: Link with libziparchive.

   * frameworks/base/
e9add4667c34 Revert "services: allow to force "never" mode for display cutout [1/2]"
5098a4473974 Ambient music ticker: fix text scrolling glitches
4eb5f92764b5 Improve ambient play layout on keyguard
a06b2c4cb89f Ambient music: do not extend pulse notification when not needed
ba8c13ff863e Revert "Ambient music: Use animated icon"

====================
     03-21-2019
====================

   * bootable/recovery/
64e0a652 Use listbox for device-specific advanced menu items
908442df Merge "Update FDE decrypt to pie from CAF" into android-9.0
98661c1a Update FDE decrypt to pie from CAF
af32bb9c MTP FFS updates:
e9a49efe Adding Edl button in reboot menu

   * frameworks/av/
50b4ed6a98 Fixed audioserver crash in monkey test
afc6302dfe audioflinger: do not idle thread if active tracks exist
55272b5233 audio: ensure effect chain with specific session id is unique
b7b4d787d3 audioflinger: Throttle output if no active tracks
a209cae7bb audio: don't apply ramp if track is paused before the first mix
995cf80e1b Request to reset effect buffer in clearInputBuffer

   * packages/apps/HavocSettings/
c483fad Add mido in devices

====================
     03-20-2019
====================

   * bootable/recovery/
08f91e84 gpt: Add -Wno-format-security
38d2d526 TWRP: fix compiling on Android 7
e03158eb Fix gr_clip

====================
     03-19-2019
====================

   * bootable/recovery/
3157f121 Full screen action: simplify by just hiding navbar
eff335d8 prebuilt: Avoid re-linking ARM64 specific library on other architectures
d32b7ebf TW_ROTATION: add flag to handle hardware-rotated display panels
19874f14 AB/Non AB Devices: updates for moving cache
3ed778ad Vibration: allow BoardConfig to disable vibration for a device.
9220dbab fix building TWRP for devices without cache

   * frameworks/base/
76e5e4eeace6 Clean up screenshot if nothing selected
6edf38977167 IMMS should preserve selected IME upon boot
a4334517999f Add bluetooth icon.
322b446a4d51 base: Cleanup FP controller

   * packages/apps/Dirac/
8329e99 Prevent failures when toggling
9037c79 Only call setEnabled on boot completed
d3856fc Refactor Dirac setup
5d23300 Dirac fixes
2b01382 Refactor dirac strings
e0d910d Add summary for dirac
6515719 Add DiracSound backend
70b11a0 Introduce Dirac preferences

   * system/core/
6363d6cf9 Allow adb root even in no debuggable builds

   * vendor/themes/
07dbfc8 themes: Fix volume panel footer background

====================
     03-18-2019
====================

   * bootable/recovery/
5f8394ca Merge "slot management: add library for slot management." into android-9.0

   * packages/apps/Nfc/
1c574eee NfcNci: make T3T/Nfc-F HCE optional

   * packages/apps/Settings/
7a9cc0d166 Update the timestamp used for time zone filtering
41351028d4 Settings: fix eject sdcard icon color

   * system/core/
614ff9d8e storaged: change log level for health HAL calls

====================
     03-17-2019
====================


====================
     03-16-2019
====================


   * external/roboto-fonts/
fd30717 Add missing glyphs from Roboto

   * frameworks/base/
8a6383d3c9f7 SystemUI: Reduce padding between wifi and signal icon
844892ef4de3 KeyguardStatusBarView: Request batteryview update only when required
aeb43aa95ada PowerManager: Don't bother devices not using wait for MPCTL
6d684a1803d8 PerformanceManager: Allow wait for MPCTL to start on boot
67e063df5c41 AudioService: Fix camera shutter sound toggle
c48b25b0fe94 Navbar: Do not fiddle with haptic feedback
c197ee75bcf7 SystemUI: Separate global actions theme from qs

   * packages/apps/DocumentsUI/
2752868d DocumentsUI: Improve dark theme

   * vendor/themes/
cc7a998 themes: Dark theme improvements

====================
     03-15-2019
====================

   * bootable/recovery/
3ae89edb Merge "Fix build error on Pie with TW_NO_LEGACY_PROPS := true" into android-9.0
6b9ee0e0 Merge "Revert "Fix ld.config.txt errors on Android 8.1 system root devices"" into android-9.0

   * frameworks/base/
1321215e4602 Re-add WPS implementation (2/3)
d2ceb722e112 base: Fix less frequent notification sounds value
357ab2a80459 base: Add vibrate util methods
de6005fee923 base: Turn on display if Doze On Charge is Enabled
c2ce0cd906e9 Volume panel: Add notification volume row if unlinked
1c43a913abd0 Code improvements for expanded volume panel

   * frameworks/opt/net/wifi/
1d20bcb7d Re-add WPS implementation (3/3)

   * packages/apps/HavocSettings/
e824dff Add cancro in devices

   * packages/apps/Settings/
7fc597f456 Re-add WPS implementation (1/3)

