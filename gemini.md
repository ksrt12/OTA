
====================
     08-29-2019
====================


   * device/xiaomi/gemini/
f688b74f update vendorsetup.sh

   * device/xiaomi/translations/
1274136 Bangla translation
12c6ba3 update ru

   * packages/apps/HavocSettings/
9d49e15 Bangla translation

   * vendor/qcom/opensource/dataservices/
39b0587 convert mk to bp

====================
     08-27-2019
====================


   * device/havoc/sepolicy/
026aa69 rebase recovery sepolicy
51fb5c7 sepolicy: allow recovery to setenforce
49c4912 sepolicy: Add hal_lineage_fod domain
56c6e21 sepolicy: Add hal_lineage_camera_motor domain
1f3d89e Remove minivold rules
6e4e66b rebase lineage hals
7613b59 sepolicy: qcom: Label /d/rpmh
8d70dde sepolicy: Dontaudit sysinit
5c6b061 sepolicy: Add rules for Long screenshot service
1c43941 sepolicy: Guard neverallowed policy for system_file with userdebug/eng

   * frameworks/base/
91f7ce030be SystemUI: Q clock: update polish translation

   * hardware/qcom/bt-caf/
76e8842 libbt-vendor: use generated kernel headers

   * hardware/qcom/display-caf/msm8996/
65a4789b Revert "Revert "display: Define soong namespace""

====================
     08-26-2019
====================

   * art/
34b265e528 Stop verifying barrier count for thread dumping
2df00fa1ba ART: Cache type index validity

   * frameworks/base/
8042ad6e9ed fix aapt2 warnings
0bdc4050e0a LiveDisplayTile: Remove tile if unavailable
206c6f12708 LiveDisplayTile: Refresh state after livedisplay initialization
75e58677691 LiveDisplayTile: Enable for outdoor mode and skip night display on HWC2
51ea98a01eb LiveDisplayService: Notify SystemUI after initialization finished
5598f83653e LiveDisplayManager: Perform null check in getConfig()
61cae206856 OutdoorModeController: Unconditionally enable auto mode on HWC2
874d18fb3e2 OutdoorModeController: Advertise MODE_AUTO
3d244390979 LiveDisplayService: Properly disable ColorTemperature
6e15221dc96 LiveDisplay: Cleanup
650e8596148 FOD: Differentiate dreaming and pulse
d3fb65589f4 Initial support for in-display fingerprint sensors
642f8024457 Revert "Initial support for OnePlus in-display fingerprint sensor"
721bf436e5a BatteryEstimates: Toggle without SystemUI restart
2c5fb021aa4 SystemUI: Tiny expanding improvement
761e1e0c0e5 NotificationColorUtil: Kill logspam
d3bdecb0e78 fwb: Port extended screenshot function from OOS
a8126895cbb fwb: Add support for internal audio recording
f87b7aa33dd Remove uses of libcore.io DropBox and EventLogger
589c568157b SystemUI: Use matching data usage size formatting between QS and Settings
1108aebc76b Update Xbox BT controller mapping to support upcoming controller firmware update
dfdf7e48778 Add keylayout for Xbox One USB controller
4864977450e Keylayout for xbox controllers
04f86a78547 Added mapping files for DualShock3 and DualShock4
e1806919412 Fallback BUTTON_MODE to HOME
00083e425fc Remap PS key to BUTTON_MODE
277ff7bd558 Set default VR_MODE based on VR feature support
f83536e16ba fw/b: Add capability to allow tethering to use VPN upstreams
762a3e11923 power: Respect global vibration setting for charging sounds
447967c8757 Fix wrong locale causing reboot in recovery
de4538b0d54 Correction in logic of roundend size calculation of SD card
ca8316ed2bf SystemUI: Q clock translation: remove unneeded extra quotes
69f38582d34 Fix type header clock strings for Q Clock
c127a92f970 ViewRootImpl: set max fling ticks per sec to 24
77f02765291 SystemUI: fix constant FC on certain devices after b20262a40fcf2f73a1faf0e57dd3971534be8951
237d952e484 base: Improve haptic feedback for some UI elements
c396740865c don't import unused protos

   * packages/apps/HavocSettings/
bb254a9 fix typos
1d8ded6 Settings: Remove haptic feedback duration for OP gestures
18a08fe add SearchIndexProvider into HavocSettings [1/2]
f9e2dfb add haptic feedback intensity control
d224668 toggle torch proximity check [2/2]
70772a6 Rework hw button illumination
2f75b6b Revert "Pocket judge"
3ff353b set default rounded values

   * packages/apps/Settings/
49c2aaf10b add SearchIndexProvider into HavocSettings [2/2]

   * packages/services/Telephony/
e65c02e48 fix typos

   * vendor/havoc/
ea32739d vendor: Add vendor.lineage.biometrics.fingerprint.inscreen permission
b719d232 backuptool_ab: Make copy_file preserve file/directory attrs
2f26d7ea overlay: Remove config_wifi_wakeup_available

====================
     08-25-2019
====================


   * hardware/havoc/interfaces/
3188b3b IFingerprintInscreen: Allow HALs to control position and size
633cc27 IFingerprintInscreen: Allow HALs to provide finger up/down callback
0c2a47a IFingerprintInscreen: Allow HALs to control dimming
8c64861 Introduce in-screen fingerprint scanner HAL

   * packages/apps/Settings/
f4f72f2079 LiveDisplaySettings: Hide automatic outdoor mode preference on HWC2
89b80d7f50 LiveDisplaySettings: Reenable display mode preference for outdoor mode
9201a2df21 Settings: Don't index display mode and color temperature on HWC2
eaf7a73db1 LiveDisplay: Cleanup
22939a78de Revert "Settings: Restart SystemUI when toggling battery estimates"
47953ab5f2 Settings: Add hotspot setting to allow VPN upstreams

   * system/vold/
7a92952 Add "changepw" command to vdc.

   * vendor/havoc/
39cef568 Remove prebuilt MarkupGoogle
8ea74e20 Let the user choose the screenshot editor himself
eee7e568 vendor: Build Longshot app
16653a83 config: Use tether automatic upstream selection
e9046744 update Lawnchair to alpha-2382

====================
     08-23-2019
====================


   * packages/apps/Longshot/
3886633 Import modded Longshot app

====================
     08-22-2019
====================


   * device/xiaomi/gemini/
a2e50a59 rebase configpanel new
36a1510a build syberia capricorn

====================
     08-21-2019
====================


   * external/toybox/
232850b4 Regenerate config files
d3b8f503 Fix cp -r dir/. symlink child.
10538639 Add failing test for cp -r dir/. symlink child.
beef651d Fix cp permissions when copying symlink contents, and add test.
c078b2b6 Implement --preserve default = mot behavior (fixes segfault when no argument).
50a83f51 Fix "cp -p" doesn't preserve timestamps bug
f11efa35 Add cp --parents
c113fb14 Add mkpath() for common case of mkpathat(), and #define magic constants.

   * kernel/xiaomi/msm8996/
f60ca1fe91a6 builder: add INAME var
17819b5e56a1 builder: add mkzip function

====================
     08-19-2019
====================


   * kernel/xiaomi/msm8996/
791e4ac50326 defconfig: re-enable UID_SYS_STATS

====================
     08-18-2019
====================


   * device/qcom/sepolicy/
3bdd56f4 Merge tag 'LA.UM.7.6.2.c1-03100-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into HEAD

   * device/xiaomi/gemini/
a258edd5 capricorn: set some vibration patterns
250a78fc msm8996-common: sepolicy: Allow readfem to use msm_sock_ipc_ioctls
b72bfe1b msm8996-common: add QC3 permissions
ef567699 Merge tag 'android-9.0.0_r47' into 9.0
a876a0dc update priv_app sepolicy

   * system/sepolicy/
58fee8440 sepolicy: Address some theme_data_file denials
5c4707e46 add some storaged rules

====================
     08-17-2019
====================


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

   * packages/apps/HavocSettings/
447ae9e Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * vendor/havoc/
52a9514f vendor: Add qcom platform type to soongs vars
abcdeb7d LatinIME: Add Polish dictionary

====================
     08-15-2019
====================


   * external/chromium-webview/
8b3f380 Update Chromium Webview to 76.0.3809.111

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

   * packages/apps/Longshot/
687523b Initial commit

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


   * device/qcom/sepolicy/
8f95d283 Merge "sepolicy: Add qseecom device access permissions to audio HAL"

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

