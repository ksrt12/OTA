
====================
     06-25-2019
====================


   * build/make/
295d584d9 dex2oat: disable multithreading for WSL
f915cf5b4 Add detection for WSL
3f14e9d03 Add the missing dependency on BOARD_PREBUILT_DTBOIMAGE.

   * device/xiaomi/translations/
0c7f6b8 update RU gaming mode translations

   * vendor/havoc/
2153e846 update Lawnchair to alpha-2181

   * vendor/xiaomi/
acd83cdc gemini: Add 60fps Video Recording
2f93b815 add libsecureui.so
044f84a6 add camera blobs from 8.11.22

====================
     06-24-2019
====================


   * build/make/
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

   * packages/apps/Dialer/
4db02d01e Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
8c026ad toggle torch proximity check [2/2]
8d752ce Rework hw button illumination
a338504 Revert "Pocket judge"
5bf80ae Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Settings/
fc14d4993b Support to notify connected/disconnected stations
72cd52a6e5 Havoc Build Date [2/2]
064fa7faf9 DeviceInfoSettings: Bring back CAF/AOSP tags
31463692f1 my colors
6dbdde8038 Revert "Revert "Settings: Add toggle for proximity wake""
160bc0d3d6 Add Dual Channel into Bluetooth Audio Channel Mode developer options menu
db13cdfad6 Revert "Add Dual Channel into Bluetooth Audio Channel Mode developer options menu"
be473b8991 Use a proper bool check for notification light color option
dbc6a0387a fuelgauge: Fix NPE
04fc272c39 Revert "Port "Battery Usage Alerts" feature from factory images"

   * system/bt/
96f2f0f17 Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
3531a560d RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
c0a109cb8 sdclang: true
f5084a4ec Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.
080c11834 Allow using alternative (higher) SBC HD bitrates with a property
450c9b9f1 Explicit SBC Dual Channel (SBC HD) support
d11fba320 Increase maximum Bluetooth SBC codec bitrate for SBC HD
1a3cab19b Revert "Increase maximum Bluetooth SBC codec bitpool and bitrate values"
eeef36e66 Revert "Explicit SBC Dual Channel (SBC HD) support"
64d931724 Revert "Allow using alternative (higher) SBC HD bitrates with a property"

   * system/core/
0d827ce6f Allow adb root even in no debuggable builds

   * vendor/support/
e9d91ab add variables for buttom backlight

====================
     06-23-2019
====================


   * packages/apps/HavocSettings/
f70dccb Add OnePlus 7 Pro to devices
a5e5935 Add Xiaomi Redmi 6 Pro (Sakura)

   * system/sepolicy/
ba555aadf sepolicy: Add missing entry for font service

====================
     06-22-2019
====================


   * external/expat/
4f115d6 expat: update to version 2.2.7

   * packages/apps/HavocSettings/
0482ed3 Cutout force fullscreen: Disable fast scroller
0267919 GamingMode: cleanup a bit
029c013 GamingMode: add master switch [2/2]
fe3e122 GamingMode: Rewrite implementation [2/2]

   * system/sepolicy/
57821a89a sepolicy: Add Google App build props
102c06e4d system_server: allow writes to /proc/pid/*
c474486d4 sepolicy: Add Label to f2fs sysfs files

====================
     06-21-2019
====================


====================
     06-20-2019
====================


   * frameworks/native/
818341590 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into HEAD

   * frameworks/opt/net/wifi/
4114b3280 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into pie

   * hardware/qcom/audio-caf/msm8996/
e1b7160b Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/media-caf/msm8996/
da64591b Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into 9.0

   * kernel/xiaomi/msm8996/
d05907cfa913 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' into drivers/staging/qcacld-2.0

   * packages/apps/HavocSettings/
e61b992 GamingMode: add more ringer modes [2/2]
8b79848 Settings: Gaming Mode revamped [2/4]

   * prebuilts/r8/
213db48 r8: Update D8 and R8 to 1.6.7-dev

   * vendor/codeaurora/telephony/
c3b8339 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
2438644 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
642f3e3 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     06-19-2019
====================


   * build/make/
79f160f78 Enable armv8-2a supporting on 2nd arch. variant

   * build/soong/
c1dd398a Support Qualcomm Kryo 385 CPU variant
52b65925 Add to support armv8-2a on 2nd arch. variant
fce1572d Move arch variants registering code to arch.go
5119a1a5 Configure the default arch variant features per-OS

   * hardware/interfaces/
d53190555 Merge tag 'LA.UM.7.6.2.r1-09100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

   * hardware/qcom/bt-caf/
dd952b3 Merge tag 'LA.UM.7.6.2.r1-09100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into 9.0

   * system/core/
e33f6900b fs_mgr: Add MF_WRAPPEDKEY flag

   * system/netd/
ddc03c7 Copy queries synchronously in DnsTlsSocket

   * system/vold/
19b3a91 vold: change to upgrade key if export fails
aa677ab vold: add support for clear key
3410a89 vold: Use separate flag for wrappedkey

   * vendor/havoc/
efc39b3a apn: Update German carriers
257a4033 repopick: cmp() is not available in Python 3, define it manually
d4d3bda1 apns: Update Singapore's APNs
5dd7d4ad charger: add 400dpi symlink
5a6442e4 update Lawnchair to alpha-2152

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
cbf62bc Merge tag 'LA.UM.7.6.2.r1-09100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

====================
     06-18-2019
====================


   * build/soong/
fad7bd77 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/build/soong into HEAD

   * device/xiaomi/gemini/
bb471fd7 rebase rootdir
2913e215 update sepolicy
06f678e7 msm8996-common: readmac: Convert symbolic permissions to octal

   * frameworks/av/
8fa5a24668 CameraService: Default to HAL1 for OPCam if not specified

====================
     06-17-2019
====================

   * art/
7503577a73 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/art into pie

   * bionic/
109dc8aa5 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/bionic into pie
dc015cebe Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie

   * build/make/
f3400eb64 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/build into HEAD

   * frameworks/native/
c91cc94ee [SF] Fix unittest crash

   * system/sepolicy/
f5203d137 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/system/sepolicy into pie

   * vendor/xiaomi/
bcf90aa2 capricorn: revert back to stock sensors

====================
     06-16-2019
====================


   * device/xiaomi/gemini/
39d26384 capricorn: revert back to stock sensors
25f27c28 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/device/qcom/common into 9.0

====================
     06-15-2019
====================


   * hardware/qcom/audio-caf/msm8996/
da6cf741 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/display-caf/msm8996/
ce561239 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0

   * hardware/qcom/media-caf/msm8996/
e2c18e87 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into 9.0

   * hardware/qcom/wlan-caf/
6f7406d Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/wlan into 9.0

   * kernel/xiaomi/msm8996/
7166310c581f Merge tag 'LA.UM.7.5.r1-05300-8x96.0' into drivers/staging/qcacld-2.0
4dd3c77e97c2 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into HEAD

   * packages/services/Telecomm/
f42d9e02 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into HEAD

   * packages/services/Telephony/
1b3b39af8 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into HEAD
5e8a96ec4 Telephony: Remove duplicate definition

   * system/sepolicy/
5ac083a7a Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie

   * vendor/qcom/opensource/audio/
7278b4c Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
bbf5baa Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
606ba09 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     06-14-2019
====================


   * bionic/
b60dbb09b Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie

   * device/qcom/sepolicy/
0d1764ba Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0

   * device/xiaomi/translations/
e776f7d update RU 20190613

   * frameworks/native/
b1d2e195a Merge c8288466da5169f6bfc50cc72cd9df5cb32a069f on remote branch

   * frameworks/opt/net/ims/
85a0433 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

   * frameworks/opt/net/wifi/
340f25a36 Merge 0eaec84e98bf76cc9aa6272658f3fa738ce46899 on remote branch
5da0d6922 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into pie

   * frameworks/opt/telephony/
0e8baa5444 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

   * hardware/interfaces/
8555daa7b Merge 2f57e8e3ad3588e10bbbcd56c22c03c7c78e5e0e on remote branch
e6b2eddfe Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into HEAD

   * hardware/qcom/audio-caf/msm8996/
a1bb2f59 Merge 3d42a81fd26cf94ab1e00ca37e96f7b3ff56f898 on remote branch
ce982b62 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into HEAD

   * hardware/qcom/bt-caf/
989ebd0 Merge b7bdccd743d37f592cf4e407c5ae9c9e1f130043 on remote branch
aa6520b Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into HEAD

   * hardware/qcom/display-caf/msm8996/
1b1da616 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into HEAD

   * hardware/qcom/media-caf/msm8996/
6512165b Merge 5029253b815df1b49da827dbd5514a6f3c87e3c1 on remote branch
09dac8a2 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD

   * hardware/qcom/wlan-caf/
9f99f21 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/wlan into HEAD

   * hardware/ril/
9a16b612 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/ril into HEAD

   * kernel/xiaomi/msm8996/
7fa073eeb83a Merge 78aa41ba569c485b91955fc5c0eb3e075fc3ee30 on remote branch

   * packages/services/Telecomm/
694866f4 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into HEAD

   * packages/services/Telephony/
35862ae79 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into HEAD

   * system/sepolicy/
e0904cb19 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie

   * vendor/codeaurora/telephony/
132f6f2 Merge 3b08f080ab3df40fa80a17d6d01ae3c61fc429ff on remote branch

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
62e6d45 Merge 298c2caf64ef3efe78430542a5c2852738f50287 on remote branch
1f4b771 Merge 298c2caf64ef3efe78430542a5c2852738f50287 on remote branch

   * vendor/qcom/opensource/interfaces/
147d103 Merge 93071bf7476a2fe0bfb1f42074d19af7975425e2 on remote branch

