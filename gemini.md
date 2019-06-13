
====================
     06-13-2019
====================


   * bionic/
b60dbb09b Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie

   * device/qcom/sepolicy/
0d1764ba Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0

   * device/xiaomi/gemini/
d027de56 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/common into 9.0

   * frameworks/opt/net/ims/
85a0433 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

   * frameworks/opt/net/wifi/
5da0d6922 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into pie

   * frameworks/opt/telephony/
0e8baa5444 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

   * hardware/interfaces/
e6b2eddfe Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into HEAD

   * hardware/qcom/audio-caf/msm8996/
ce982b62 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into HEAD

   * hardware/qcom/bt-caf/
aa6520b Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into HEAD

   * hardware/qcom/display-caf/msm8996/
1b1da616 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into HEAD

   * hardware/qcom/media-caf/msm8996/
09dac8a2 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD

   * hardware/qcom/wlan-caf/
9f99f21 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/wlan into HEAD

   * hardware/ril/
9a16b612 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/ril into HEAD

   * packages/services/Telecomm/
694866f4 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into HEAD

   * packages/services/Telephony/
35862ae79 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into HEAD

   * system/sepolicy/
e0904cb19 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie

   * vendor/havoc/
1ffdc5f3 update Lawnchair to alpha-2112

====================
     06-12-2019
====================


   * device/xiaomi/gemini/
55e5e082 add vendor.lineage.livedisplay to vendor_framework_compatibility_matrix.xml

   * frameworks/base/
f82b87ed95c8 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/frameworks/base into HEAD
576f83aa0ed8 fix
37524965f02d wifi: Add wifi latency level API to WifiManager
eca56ed280ae wifi: Support to add vendor based Intent namespace
31703d98e8f4 Wifi: Define DATA_STALL intent to broadcast message
727a3e95ffad wifi: Notify Connected/Disconnected Mac address on hotspot
4bab90088e69 Wifi: Send DHCP DISCOVER with rapid commit
b20155920eb4 Wifi: Add support for repeater mode
506895b3317a base: add support for SAP+SAP.
ad924e7196ad Wifi: Allow saving sim_num for EAP-SIM/AKA/AKA_PRIME configurations
3e326462f811 framework: Add Wifi Simple Configuration support
d916ea9e9d64 framework: Add WiFi Display R2 device info
4d9d03f65647 wifi: Add APIs and keymgmt to support WPA3(DPP,SAE,OWE,SuiteB).
ed97eb18df1a Wifi: Add FILS support in WifiConfiguration

   * frameworks/opt/net/wifi/
9a289059c Revert "Disable hostapd during wifi initialization."
b787217d4 Revert "DO NOT MERGE Add data integrity checking for wifi passwords"
6fcda2bfa Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into HEAD

   * vendor/codeaurora/telephony/
61b747c Merge tag 'LA.UM.7.4.r1-05300-8x98.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into HEAD

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
2b41bd3 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into HEAD

====================
     06-11-2019
====================


   * frameworks/base/
6b08c83e1165 Support CALLBACK_TYPE_SENSOR_ROUTING
cd66dc3609e5 Revert "SystemUI: Add Cellular tile icon from OOS"
6c970393d96d Keyguard: Don't listen for fingerprint when prox.sensor is covered
6ef20e8b7cd7 show bt battery for all devices
604055af24a2 change battery save color
8b6942971341 fix answer from home key
2db5080674a6 toggle torch proximity check [1/2]
1a27b3018ed8 proximity check for all wake keys
c0797a755ec8 Havoc Build Date [1/2]
e63801109b42 fix button backlight
5ba57310b8ae fix priv-apps permissions
fab5130d96cc for gemini: Revert "Revert "Proximity check on wake""
28d1664c669d Revert "HW: Fix Home button during call"

   * packages/apps/Bluetooth/
b381d3bf Merge branch '9.0' of https://github.com/syberia-   */platform_packages_apps_Bluetooth into HEAD

   * packages/apps/Dialer/
947a79839 Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
d9d15da toggle torch proximity check [2/2]
6566ee5 Rework hw button illumination
de27b37 Revert "Pocket judge"
327c8c6 Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Settings/
958142059d Support to notify connected/disconnected stations
0c92297d0d Havoc Build Date [2/2]
79c500dcfb DeviceInfoSettings: Bring back CAF/AOSP tags
970e3110c3 my colors
1949de1d50 Revert "Revert "Settings: Add toggle for proximity wake""

   * system/bt/
c52f4336b Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
52078308d RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
f8c0c3d84 sdclang: true
cef561ebb Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
2e104f28c Allow adb root even in no debuggable builds

   * vendor/qcom/opensource/audio/
fc759a6 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into HEAD

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
2b41bd3 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into HEAD

   * vendor/qcom/opensource/interfaces/
0256dfa Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into HEAD

   * vendor/support/
e056e4e add variables for buttom backlight

====================
     06-10-2019
====================


   * external/nano/
ae26fda9 nano: Regenerate config.h
9f2c790e nano: fix another implicit declaration of time()

   * packages/apps/HavocSettings/
71633d2 Add Xiaomi Redmi Note 7 (lavender)

====================
     06-09-2019
====================


   * bionic/
e5adca11d Revert "bionic: strip libc and linker"

   * frameworks/base/
043ab77f0d89 Revert "hwui: Enable quicksilver"
8dc5c5e6d2d1 Q Style Clock: Animate change in time
b554e35f8ded Q Style Clock: Align owner info as per the clock style
f3fa721e83a7 SystemUI: Fix analog clocks not refreshing in AOD
cd913a82b857 Utils: Introduce method to determine countries that use Fahrenheit
f28cca15b3e3 Utils: Add method to determine battery temp
8744d702c6dc base: Add toggle to disable charging animation [1/2]

   * hardware/qcom/fm/
2140e05 Automatic translation import

   * packages/apps/FMRadio/
b74e30b Automatic translation import

   * packages/apps/HavocSettings/
682d3cb Add new maintainer for GSIs
adb83b0 Settings: Add toggle to disable charging animation [2/2]

   * packages/apps/Settings/
82db524638 Settings: Add drawable for Private DNS
9d93f715b4 Battery temp: Use MCC to determine the scale type
40563cc6c3 Battery temp: Ensure preference is updated
8e8d5d4b1d Battery stats: Display battery temperature

   * packages/apps/Terminal/
4a764c0 Automatic translation import

====================
     06-08-2019
====================


   * device/xiaomi/gemini/
359a0368 update com.android.vending privapp-permissions

   * frameworks/opt/net/ims/
1f10d68 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

   * frameworks/opt/net/wifi/
c42164527 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/frameworks/opt/net/wifi into HEAD

====================
     06-07-2019
====================


   * external/nano/
561b50da nano: don't spam warnings as errors
ad2eedc1 nano: fix implicit declaration of time function
161086fe nano: Make revision.h a stub
5daed7f4 nano: Update makefile for new nanorc path
3ca7bc57 nano: Add nanorc
7b10e544 nano: Add android makefile
161f0291 nano: Add config.h and revision.h
e810d7e3 nano: Don't ignore config.h & revision.h

   * frameworks/base/
94d657a63694 LiveDisplayTile: Report unavailable on HWC2

====================
     06-06-2019
====================


   * device/xiaomi/gemini/
500e2db6 update README
a2e1d561 Android 9.0.0 release 42 (PQ3B.190605.006)

   * external/skia/
357d211bf5 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/external/skia into pie

   * frameworks/base/
091b7a318ed7 Merge "Snap for 5524043 from e31b34fa0cd1e70d1105e2f472d400f6619b2913 to pi-platform-release am: 799a8ca54f" into pie-gsi
0175732ba9d7 Snap for 5524043 from e31b34fa0cd1e70d1105e2f472d400f6619b2913 to pi-platform-release am: 799a8ca54f
799a8ca54fed Snap for 5524043 from e31b34fa0cd1e70d1105e2f472d400f6619b2913 to pi-platform-release

   * frameworks/opt/telephony/
e653d650c8 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/frameworks/opt/telephony into caf

====================
     06-05-2019
====================


   * frameworks/av/
3092601cd6 Merge tag 'android-9.0.0_r42' into pie

   * frameworks/base/
50eefdf08461 Merge tag 'android-9.0.0_r42' into pie
473fc03cfbb1 KeyguardSliceProvider: Show dnd icon regardless of suppression mode
4e7ac60ee9e5 Q Style Clock: Set "It's" to accent color instead of gold / yellow color

   * hardware/qcom/fm/
221e94e Partially revert "fm: Fix wrong BT SOC property name"

   * packages/apps/Bluetooth/
75d8899a Merge tag 'android-9.0.0_r42' into pie
797a4c1d Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/packages/apps/Bluetooth into HEAD

   * packages/apps/CellBroadcastReceiver/
e100c47 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/Contacts/
3088d1b0e Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/DocumentsUI/
1ec25c71 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/EmergencyInfo/
c93fc34 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/HavocSettings/
659ffbb Add sirius to devices

   * packages/apps/Nfc/
2636c6df Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/PackageInstaller/
ed8e1766 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/Settings/
a4555eefd9 Merge tag 'android-9.0.0_r42' into pie
6758f9e75b Settings: Add battery saving mode for location
03d669d057 livedisplay: Don't show display mode and color tempertature on HWC2
76383f3983 Revert "Settings: Hide Night Mode suggestion if LiveDisplay feature is present"

   * packages/inputmethods/LatinIME/
40292fb36 Merge tag 'android-9.0.0_r42' into pie

   * packages/providers/MediaProvider/
b83152f Merge tag 'android-9.0.0_r42' into pie

   * system/bt/
dd6509256 Merge tag 'android-9.0.0_r42' into pie

   * system/libhwbinder/
17d29d6 Merge tag 'android-9.0.0_r42' into pie

   * system/vold/
756a932 Merge tag 'android-9.0.0_r42' into pie

   * vendor/havoc/
538911c0 Havoc 2.6

====================
     06-04-2019
====================


   * build/make/
3bba1846a Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/build into pie

   * device/xiaomi/gemini/
6449ba2f Migrate to livedisplay 2.0
0049ca85 audio: fix audio_policy_configuration copy path
604db03f update .gitignore
daf68f5e update dump sepolicy

   * frameworks/native/
86f317d99 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/frameworks/native into pie

   * hardware/interfaces/
6a0cd5dcc Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/hardware/interfaces into 9.0

   * packages/services/Telecomm/
5a383110 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/packages/services/Telecomm into caf

   * packages/services/Telephony/
c486facc6 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/packages/services/Telephony into caf

====================
     06-03-2019
====================


   * vendor/codeaurora/telephony/
8081ac3 Merge 3b08f080ab3df40fa80a17d6d01ae3c61fc429ff on remote branch

====================
     06-02-2019
====================


   * external/zlib/
593a35c minizip: More build fixes
99fc328 minizip: Clean up the code
2c043d6 minizip: Fix build under Android 6.0 and higher
39df7f0 zlib: enable unaligned memory access

   * frameworks/base/
0fbb84c08992 Revert "NightDisplayController: report unavailable if livedisplay feature is present"

   * hardware/lineage/livedisplay/
fd1713f sdm: Fix restoring default mode when using prebuilt vendor

   * packages/apps/HavocSettings/
015fa4f QS Headers: Fix summary and add missing entry

   * packages/services/Telecomm/
2e83a95f Change UI to be consistency with dialer settings light M2 theme

   * packages/services/Telephony/
b8bd27fec Add missing null check on start of SipIncomingCallReceiver received.
0a15f28ab Change action bar icon and text color from white to grey
0d02064c1 Fix the drawable resource can't be loaded from RRO package

   * prebuilts/r8/
51b762f r8: Update D8 and R8 to 1.6.3-dev

   * vendor/havoc/
b80dc04f update prebuilt apps

