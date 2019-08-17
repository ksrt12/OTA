
====================
     08-17-2019
====================


   * device/xiaomi/gemini/
35f2d948 fix kcal settings titles
9bcfee65 msm8996-common: sepolicy: Allow readfem to use msm_sock_ipc_ioctls
541a1722 rebase configpanel
b0f694d1 Merge tag 'android-9.0.0_r47' into 9.0
3160134d msm8996-common: add QC3 permissions

   * kernel/xiaomi/msm8996/
0438803ab798 defconfig: update after 4bffbdf36702e5b74fcfba1800b17b3e9de9292f
f772242616db random: Switch random fully over to Chacha20
89b32ef2fd6d random: replace non-blocking pool with a Chacha20-based CRNG
4bffbdf36702 crypto: chacha20 - Add a generic ChaCha20 stream cipher implementation
329b157e06bf builder: add timer function
70380b38a9c3 ANDROID: binder: correct the cmd print for BINDER_WORK_RETURN_ERROR
d3105b9f1e47 msm: sps: Fix uninitialized result usage when an invalid IRQ is found
84e30eb0519c arm64: enable 128bit ints
1b6e9f25c93b arm64: support bitrev
5c818f2791a9 Makefile: add optimization flags
c5920f561145 defconfig: disable spectre/meltdown protection
8a34581f4f76 init: Kconfig: Don't force DEBUG_KERNEL when EXPERT is enabled

   * vendor/havoc/
5a363dda update Device Health Services to 1.11.0.259314730.release

====================
     08-16-2019
====================


   * frameworks/native/
a595fda8a SurfaceFlinger: Exclude CAF extensions from non-QC devices

   * packages/apps/Dialer/
a2290c98a Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
51ec453 add haptic feedback intensity control
5110c4c toggle torch proximity check [2/2]
c506d08 Rework hw button illumination
dc9295b Revert "Pocket judge"
447ae9e Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Settings/
1cf6d9a97b Support to notify connected/disconnected stations
d6a7ed76e4 Havoc Build Date [2/2]
c062662ebb DeviceInfoSettings: Bring back CAF/AOSP tags
fdbd2b9544 my colors
a3c1632119 Revert "Revert "Settings: Add toggle for proximity wake""

   * system/bt/
1112e8420 Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
3cdb90e2d RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
ad8cd2d90 sdclang: true
a12cd74c1 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
8aef1e16b Allow adb root even in no debuggable builds

   * vendor/havoc/
52a9514f vendor: Add qcom platform type to soongs vars
abcdeb7d LatinIME: Add Polish dictionary

   * vendor/support/
74010b4 add variables for buttom backlight

====================
     08-15-2019
====================


====================
     08-14-2019
====================


   * kernel/xiaomi/msm8996/
ac1ca3dbae5e mm: decrease vm_swappiness to 50
d0062f1c8f62 Add new universal build script (WIP)
4b2befee7e8c Add customized AnyKernel3
c142eb016a72 defconfig: tweak entropy controls
f3c8c6f3edea char: Kconfig: create default read/write entropy configs
b6e9dbc190f0 drivers: fixup inconsistent mutex
a295d92dffc6 drivers: major code fixups
f69b49f7ce79 mm: Implement minimum bound for performing readahead
2c07141f48ea mm: Do readahead if requested size is over 64 KiB
915719a4fc3a block: Do not collect I/O statistics
bce2c897c30c defconfig: Disable bounce buffers
7bd20d73ad78 sched: Enable NEXT_BUDDY for better cache locality
96dd3e04d88c staging: sync: Don't copy fence names by default
182b975bbd49 gpu: msm: Do not compile Adreno 3xx / 4xx drivers
712984df71d3 irq: spurious: Disable IRQ debugging by default
af7cd4965fe6 Makefile: remove -ffast-math because -Ofast is here too
2630764b92b2 defconfig: disable some small logs and stats
7f1014a148d5 defconfig: enable NTFS driver and disable sdFAT stats
28848b88e383 mmc: disable software CRC checks and make them toggleable
128a34777a82 defconfig: enable CONFIG_PGTABLE_MAPPING
77339a34f111 defconfig: disable most of the congestion algorithms
100d05d087a8 Fix code errors detected by GCC
afecdfb78bb0 power: use power efficient wq
2bafa0d37b59 msm-core: disable userspace access to poll_ms

   * system/core/
8821bf7bd Add cpu set for audio app

====================
     08-13-2019
====================


   * packages/apps/HavocSettings/
641830b Settings: Fix typos

====================
     08-12-2019
====================


   * packages/apps/HavocSettings/
8a4031c Add Xiaomi Mi Mix

====================
     08-11-2019
====================


====================
     08-10-2019
====================


   * hardware/interfaces/
5d84ebc2f Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

   * hardware/qcom/audio-caf/msm8996/
af97a487 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/display-caf/msm8996/
9f0f3688 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0

   * hardware/qcom/media-caf/msm8996/
39af73be Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into 9.0

   * vendor/qcom/opensource/audio/
c88c6c9 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
4a1c410 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
3909e2b Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     08-09-2019
====================


   * packages/services/Telecomm/
d90e5107 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/packages/services/Telecomm into pie

