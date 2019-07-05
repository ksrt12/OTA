
====================
     07-05-2019
====================


   * device/xiaomi/gemini/
d8033cd3 Android 9.0.0 Release 45 (PQ3B.190705.003)

   * external/freetype/
883523e7 freetype: update to version 2.10.1

   * frameworks/native/
98e204332 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into pie

   * hardware/qcom/audio-caf/msm8996/
996a0a40 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/display-caf/msm8996/
55184b8e Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0

   * hardware/qcom/media-caf/msm8996/
64be1662 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into 9.0

   * kernel/xiaomi/msm8996/
5d3ae62631f3 Update defconfigs
3aa18820db4a Let Google Camera work in the background
034e25227a10 proc: Don't let Google Camera and Settings run in the background
a5fd062f1fbd selinux: Avoid dynamic memory allocation for small context buffers
ef32d8aac4c9 soc: qcom: smp2p: Fix compile errors when testing is disabled

   * packages/apps/Dialer/
82cb23f1a Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
a5189f8 toggle torch proximity check [2/2]
f2a114e Rework hw button illumination
fc4545c Revert "Pocket judge"
1abe30c Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Settings/
a043ea001f Support to notify connected/disconnected stations
4bf1e5dbb6 Havoc Build Date [2/2]
8e856dd52c DeviceInfoSettings: Bring back CAF/AOSP tags
3b5a5f449a my colors
8461705999 Revert "Revert "Settings: Add toggle for proximity wake""

   * system/bt/
d28240d3e Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
5319930d0 RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
8b15509b2 sdclang: true
ca386b0e4 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
f8304af56 Allow adb root even in no debuggable builds

   * vendor/codeaurora/telephony/
f192d11 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie

   * vendor/havoc/
fa356e62 update Lawnchair to alpha-2268

   * vendor/qcom/opensource/audio/
5df76d7 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
d1c44d0 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
2e03a84 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

   * vendor/support/
72c97ac add variables for buttom backlight

====================
     07-04-2019
====================


====================
     07-03-2019
====================


   * build/make/
31f4a43d4 Merge tag 'android-9.0.0_r45' of https://android.googlesource.com/platform/build into pie

   * frameworks/base/
dcc548fc5f7 Merge tag 'android-9.0.0_r45' of https://android.googlesource.com/platform/frameworks/base into pie
2a484a6d2d8 base: Q seekbar: make the seekbar transparent for non-seekable notifs
44b9be092cf Frameworks: Slightly refactor Parcel code
5f1c7c38e79 Stable seek bar positioning
1472d68d043 GamingMode: Clean up and refine [1/3]
f2821480540 SmartCharging: add reset battery stats option [1/2]
30365a6ab3f SmartCharging: allow user set resume level [1/2]
8815af4b6e6 Revert "ActivityRecord: add fw boost after r33 merge"
e0255c1f837 SystemUI: Use proper lock icon scale on dismissing notification panel view
0382f7c7a68 SystemUI: Handle orientation and screenSize changes for TunerActivity
93a6310d301 SystemUI: Adjust battery and location icon size
5a752034702 Revert "Keyguard: Forward port lockscreen quick unlock (1/2)"

   * frameworks/native/
85f026a5d Merge tag 'android-9.0.0_r45' of https://android.googlesource.com/platform/frameworks/native into HEAD

   * frameworks/opt/net/wifi/
81ee77957 Prevent scan searching overhead

   * kernel/xiaomi/msm8996/
e37eec1d192b crypto: msm: Don't bail out when debugfs creation fails

   * vendor/havoc/
79662562 Havoc 2.7
078398aa extract_utils: Add functions to extract vendor blobs from vendor.img
2d9f1644 build: Separate platform macros from QCOM platform definition
d6966062 build: Reorganize inclusion of QCOM macros
e7a520ad build: Use ifeq/else ifeq/else construction in board config
3d60c80a build: Set mode for makefiles
eb15bf27 update Lawnchair to alpha-2238

====================
     07-02-2019
====================


   * bootable/recovery/
f8ec73cb recovery: wipe bootloader message from index 0 when using custom offsets
bd5023de recovery: Blank screen on init

   * frameworks/av/
02261bd80c Merge tag 'android-9.0.0_r44' into pie

   * packages/apps/PackageInstaller/
89494f01 Merge tag 'android-9.0.0_r44' into pie

   * system/bt/
ab457be83 Merge tag 'android-9.0.0_r44' into pie

   * system/core/
c893af2f4 DO NOT MERGE Start update_verifier early in late-fs.

   * system/libhwbinder/
3fcb895 Merge tag 'android-9.0.0_r44' into pie

   * system/netd/
1bceea1 Merge tag 'android-9.0.0_r44' into pie

   * system/tools/hidl/
ae51c8c Merge tag 'android-9.0.0_r44' into pie

====================
     07-01-2019
====================


   * kernel/xiaomi/msm8996/
82c47d336abf config: disable KALLSYMS & MODULES
7acd70da8e11 update .gitignore

====================
     06-30-2019
====================


   * device/xiaomi/gemini/
fb580e18 msm8996-common: wifi: Enable DFS channel scanning in P2P search

   * packages/apps/HavocSettings/
186bcf8 GamingMode: Clean up and refine [3/3]

   * packages/apps/Settings/
cdcda73a8c GamingMode: Clean up and refine [2/3]

====================
     06-29-2019
====================


====================
     06-28-2019
====================


   * packages/apps/Settings/
0267a81fae SmartCharging: add reset battery stats option [2/2]
f19fe3d111 SmartCharging: allow user set resume level [2/2]

   * vendor/support/
3db3055 Add missing methods in CustomSeekBarPreference

====================
     06-27-2019
====================


   * hardware/qcom/audio-caf/msm8996/
0b1121ea Merge b0701bdc1d9161042f70db4ea335023f162f6b19 on remote branch

   * hardware/qcom/display-caf/msm8996/
a47563f4 Merge e2add2e51bfce096053110c55199da7dc8f4e5a3 on remote branch

   * hardware/qcom/media-caf/msm8996/
f1451b06 Merge 429b73b3990f743f16b292cbd6a78ccfb80b1222 on remote branch

   * vendor/qcom/opensource/audio/
3892e0e Merge 97376a9080990e1bd2929eb865f691b8e9b7f37e on remote branch

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
24f74a0 Merge 98278cbab83c8bc876c7c6f041576de599233fb3 on remote branch

   * vendor/qcom/opensource/interfaces/
6b6345e Merge b8d91476053d0e8b17f6338839a452d58413b8ef on remote branch

====================
     06-26-2019
====================


   * frameworks/base/
d0e02f20f9e Update JPN language

   * packages/apps/HavocSettings/
7933398 Add Bacon to devices

   * system/vold/
0558ab5 Use wrapped key for metadata encryption

====================
     06-25-2019
====================


   * device/xiaomi/translations/
0c7f6b8 update RU gaming mode translations

   * packages/apps/HavocSettings/
109796c Add OnePlus 7 Pro to devices
6e953ca Add Xiaomi Redmi 6 Pro (Sakura)
70a246e Cutout force fullscreen: Disable fast scroller
8d5d358 GamingMode: cleanup a bit
8be52e4 GamingMode: add master switch [2/2]

   * packages/apps/Settings/
045b871c1a Revert "Keyguard: Forward port lockscreen quick unlock (2/2)"
1b8e98cef8 Settings: appops: Drop GET_UNINSTALLED_PACKAGES from getApplicationInfo()

   * prebuilts/build-tools/
61dbccf build-tools: Update for new sources and clang

   * prebuilts/clang/host/linux-x86/
7fadab54 Update prebuilt Clang to r353983d.

   * vendor/xiaomi/
acd83cdc gemini: Add 60fps Video Recording
2f93b815 add libsecureui.so
044f84a6 add camera blobs from 8.11.22

====================
     06-24-2019
====================


   * build/make/
295d584d9 dex2oat: disable multithreading for WSL
f915cf5b4 Add detection for WSL
3f14e9d03 Add the missing dependency on BOARD_PREBUILT_DTBOIMAGE.
99ed86d61 build: Respect fs_config when generating recovery ramdisk

   * frameworks/base/
d54003dbae4 SystemUI: Expose ambient music ticker bottom margin
b05590dc5e0 SystemUI: Statusbar layout improvements
bffada2d905 Allow SBC as HD audio codec in Bluetooth device configuration
f3ba1ed2f8e Add Dual Channel into Bluetooth Audio Channel Mode developer options menu
9bea6223bbc Add CHANNEL_MODE_DUAL_CHANNEL constant
a7a2e5f8dfc Revert "Add Dual Channel into Bluetooth Audio Channel Mode developer options menu"
01602607b6b base: Import Android Q activity animations
69183cd2bea PhoneWindowManager: Set delay for screenshot shortcut to 0
50cceca22fa AudioService: Remove Analog Dock from fixed-volume devices
ac6c605044f Reduce the padding between media controls & seekbar
4b3e0f87919 fwb: Improve AOSP twilight code
03d40904670 LiveDisplayService: Disable ColorTemperature when NightDisplay is available
5a70e8db431 GamingMode: add master switch [1/2]
e6457044945 GamingMode: cleanup and fix a bit
95d660b365e GamingMode: Rewrite implementation [1/2]
c87940305d2 GamingMode: add more ringer modes [1/2]
47c37cd2835 Gaming Mode: minor improvements
e6984da5e3e base: FireHound Gaming [1/4]
085dc0b026d Revert "Gaming Mode"
3682dffcbb5 Add optional OP cam support
d98f919be24 Revert "FB: Add oneplus camera support"
2f1495c5606 base: notch-city: Don't work if the device doesn't have a cutout
9ea3eba9d66 base: Add 5 more styles for qs
76dcaf4ffe5 BatteryStatsImpl: Reset battery stats at 95 percent
f4ac81a6750 Reload Pixel Home Animation without reboot
ae09953a2c4 Pixel Navbar animation toggle [1/2]
93861b232ed SystemUI: Add navigation touch animation support
79a99f68ae5 SystemUI: Remove older Pixel Animation
1d7c71a8f69 SystemUI: Fix several layout bugs

   * hardware/qcom/media-caf/msm8996/
429b73b3 Merge "venc: Disable RGBA direct input to Venus"

   * packages/apps/Settings/
160bc0d3d6 Add Dual Channel into Bluetooth Audio Channel Mode developer options menu
db13cdfad6 Revert "Add Dual Channel into Bluetooth Audio Channel Mode developer options menu"
be473b8991 Use a proper bool check for notification light color option
dbc6a0387a fuelgauge: Fix NPE
04fc272c39 Revert "Port "Battery Usage Alerts" feature from factory images"

====================
     06-23-2019
====================


   * system/bt/
080c11834 Allow using alternative (higher) SBC HD bitrates with a property
450c9b9f1 Explicit SBC Dual Channel (SBC HD) support
d11fba320 Increase maximum Bluetooth SBC codec bitrate for SBC HD
1a3cab19b Revert "Increase maximum Bluetooth SBC codec bitpool and bitrate values"
eeef36e66 Revert "Explicit SBC Dual Channel (SBC HD) support"
64d931724 Revert "Allow using alternative (higher) SBC HD bitrates with a property"

====================
     06-22-2019
====================


   * external/expat/
4f115d6 expat: update to version 2.2.7

   * system/sepolicy/
ba555aadf sepolicy: Add missing entry for font service

