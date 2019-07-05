
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

