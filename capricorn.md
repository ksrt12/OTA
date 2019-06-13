
====================
     06-13-2019
====================


   * bionic/
53f03e4ec Revert "Revert "Remove __overloadable/__RENAME_CLANG""
6076c1891 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/bionic into HEAD

   * device/qcom/sepolicy/
0d1764ba Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0

   * device/xiaomi/gemini/
edaf4586 capricorn: revert back to stock sensors
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

   * packages/apps/Dialer/
d9e30ab5a Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
41d1718 toggle torch proximity check [2/2]
b1f0a15 Rework hw button illumination
c705cf9 Revert "Pocket judge"
1b83811 Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Settings/
6c7843b7a5 Support to notify connected/disconnected stations
fef7660af7 Havoc Build Date [2/2]
f8610440f7 DeviceInfoSettings: Bring back CAF/AOSP tags
8efc4ad38a my colors
4672fd75b3 Revert "Revert "Settings: Add toggle for proximity wake""

   * packages/services/Telecomm/
694866f4 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into HEAD

   * packages/services/Telephony/
35862ae79 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into HEAD

   * system/bt/
7edd09359 Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
54cdcd18e RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
db7d9b756 sdclang: true
45c6a1712 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
fa2dfabaf Allow adb root even in no debuggable builds

   * system/sepolicy/
e0904cb19 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie

   * vendor/support/
afb614c add variables for buttom backlight

   * vendor/xiaomi/
e9c6c1bd Revert back to stock sensors

====================
     06-12-2019
====================


   * external/freetype/
88fa80fa freetype: update to version 2.10.0

   * external/vim/
fc4e70ca5 vimrc.android: Set nomodeline

   * frameworks/base/
f82b87ed95c8 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/frameworks/base into HEAD

   * system/qcom/
54c6bea fix build warnings

   * vendor/havoc/
1ffdc5f3 update Lawnchair to alpha-2112

====================
     06-11-2019
====================


   * device/xiaomi/gemini/
55e5e082 add vendor.lineage.livedisplay to vendor_framework_compatibility_matrix.xml

   * frameworks/base/
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

   * vendor/qcom/opensource/audio/
fc759a6 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into HEAD

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
2b41bd3 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into HEAD

   * vendor/qcom/opensource/interfaces/
0256dfa Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into HEAD

====================
     06-10-2019
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

====================
     06-09-2019
====================


   * bionic/
41932b7de bionic: Enable -O3
e9cad93c8 bionic: update for glibc 2.17
968772988 bionic: update for using jemalloc 5+

   * external/nano/
ae26fda9 nano: Regenerate config.h
9f2c790e nano: fix another implicit declaration of time()

   * external/vim/
00fa77daa vim: Add spacehi plugin
96dfaad56 vim: Update xml plugin
1a97a0904 vim/syntax: Add android logcat syntax
c1e3494c6 vim: Add autogenerated configs
1f66998d1 vim: Don't ingore generated configs
dad7e0af5 vim: Import Android makefiles
ac2450a9a patch 8.1.1511: matches in a popup window are not displayed properly
80dad48c5 patch 8.1.1510: a plugin cannot easily expand a command like done internally
954bb0636 patch 8.1.1509: cmdline_row can become negative, causing a crash
541faf7a7 patch 8.1.1508: sound keeps failing on Travis
a90998d93 patch 8.1.1507: sound test still fails on Travis
b29cfb8c2 patch 8.1.1506: syntax error in Travis config
8ed75cb0b patch 8.1.1505: running "make clean" twice gives errors
ef23c527b patch 8.1.1504: sound test still fails on Travis
ffa60dda0 patch 8.1.1503: sound test fails on Travis
427f5b66c patch 8.1.1502: cannot play any sound

   * packages/apps/HavocSettings/
71633d2 Add Xiaomi Redmi Note 7 (lavender)

====================
     06-08-2019
====================


   * device/xiaomi/gemini/
359a0368 update com.android.vending privapp-permissions

   * external/vim/
260addf79 patch 8.1.1501: new behavior of b:changedtick not tested
21f8d93c7 patch 8.1.1500: wrong shell command when building with VIMDLL and "!" in 'go'
24a5ac5d4 patch 8.1.1499: ruler not updated after popup window was removed
c024b4667 patch 8.1.1498: ":write" increments b:changedtick even though nothing changed
aef5c62a6 patch 8.1.1497: accessing memory beyond allocated space
acc682bd7 patch 8.1.1496: popup window height is not recomputed
1748c7f77 patch 8.1.1495: memory access error
6c009a397 patch 8.1.1494: build failure
33796b39b patch 8.1.1493: redrawing with popups is slow and causes flicker
7c348bb5a patch 8.1.1492: MS-Windows: when "!" is in 'guioptions' ":!start" fails
606407384 patch 8.1.1491: when skipping over code a function call may cause trouble
4e0bf8462 patch 8.1.1490: when a single test fails the exit code is not set

   * frameworks/base/
043ab77f0d89 Revert "hwui: Enable quicksilver"
8dc5c5e6d2d1 Q Style Clock: Animate change in time
b554e35f8ded Q Style Clock: Align owner info as per the clock style
f3fa721e83a7 SystemUI: Fix analog clocks not refreshing in AOD
cd913a82b857 Utils: Introduce method to determine countries that use Fahrenheit
f28cca15b3e3 Utils: Add method to determine battery temp
8744d702c6dc base: Add toggle to disable charging animation [1/2]

   * frameworks/opt/net/ims/
1f10d68 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

   * frameworks/opt/net/wifi/
c42164527 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/frameworks/opt/net/wifi into HEAD

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
     06-07-2019
====================


   * external/vim/
64416127f patch 8.1.1489: sign order wrong when priority was changed
150f0550f patch 8.1.1488: summary of tests has incorrect failed count
62a88f498 patch 8.1.1487: older msgfmt cannot generate proper .desktop file
125370459 patch 8.1.1486: a listener change is merged even when it adds a line

