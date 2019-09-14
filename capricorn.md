
====================
     09-14-2019
====================


   * device/xiaomi/gemini/
bf63260b Revert "BoardConfig: permissive kernel"

   * external/skia/
e575f19d34 Merge tag 'android-9.0.0_r48' into HEAD
53a4cdce32 Merge remote-tracking branch 'havoc/pie' into HEAD

   * frameworks/opt/telephony/
06beb358e5 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

   * kernel/xiaomi/msm-4.4/
e195c888fdfa dts: capricorn: configure thermal_simple zones
a428ff28e4ae dts: update usb init-seq from latest xiaomi kernel drop
b43bb78e55f4 update capricorn_defconfig from gemini_defconfig

   * kernel/xiaomi/msm8996/
18dc616aef3b drop anykernel3
72d47b0a35be update kconfig from 4.4
c09e8a52ea2a capricorn: clean up dtsi
568ff0f66c88 update capricorn_defconfig

   * packages/apps/Contacts/
98ad2ebd1 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Contacts into HEAD

   * packages/apps/Dialer/
6d0afb563 Revert "Fix in-call buttons layout"

   * packages/apps/Nfc/
476b89a5 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD

   * packages/apps/PackageInstaller/
acb50f0e Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/PackageInstaller into HEAD

   * packages/apps/Settings/
ab3000b7bb add SearchIndexProvider into HavocSettings [2/2]
7f5ae1605e Support to notify connected/disconnected stations
613ebb2355 Havoc Build Date [2/2]
ee2a8f7b96 DeviceInfoSettings: Bring back CAF/AOSP tags
b725e50259 my colors
5cd27e42ea Revert "Revert "Settings: Add toggle for proximity wake""

   * packages/providers/DownloadProvider/
47b3f81 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/providers/DownloadProvider into HEAD

   * packages/services/Telecomm/
7449c5c1 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/services/Telecomm into pie
7ca655e7 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into pie

   * system/bt/
7338cd552 Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
a7a98e847 RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
0f6c8366e sdclang: true
c1b40a295 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
00455239b Allow adb root even in no debuggable builds

   * system/libhwbinder/
7c61b90 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/libhwbinder into HEAD

   * system/netd/
d8f5f11 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/netd into HEAD

   * system/sepolicy/
69ca73ffd Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/sepolicy into pie

   * system/tools/hidl/
bf3f43b Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/tools/hidl into HEAD

   * system/update_engine/
a13e2e5 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/update_engine into HEAD

   * system/vold/
67e0254 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/vold into HEAD

====================
     09-13-2019
====================


   * device/xiaomi/gemini/
307af7fc build stock health service
274bc5e9 update some LOG_TAGs
0dcd1042 update vendorsetup.sh
7c1a8177 add new path for /sys/class/power_supply/bms/charge_full

   * frameworks/base/
2b6a876c26c Fix StatusBarWifiView applying the wrong wifi icon
99f0c371324 Update systemui wifi icons to GM2.
c5928fc6d24 Use frameworks wifi icons instead of sysui
0fb34399374 Invalidate SignalDrawable on level change.
982c6d76afe Update SignalDrawable to show X for empty state
c8451758fd4 Update SignalDrawable.
57d29075358 Update systemui animations to GM2.
e4b34a1aa23 Remove unused badged wifi API/drawables.
93a98f034f1 SettingsLib: Update Utils APIs usage

   * kernel/xiaomi/msm-4.4/
2c2e04368326 defconfig: set schedutil as default governor
1b94ba4265b1 defconfig: enable pwrutilx governor
a09563b666c3 Update pwrutilx governer * to last ZeroInfinityXDA changes
703a9c610fba cpufreq_pwrutilx: Cap big cluster during screen off
a8184a37106b cpufreq_pwrutilx: Add support for thermal throttling
ebca66cf74f9 cpufreq_pwrutilx: Add new governor
f7c01585252b defconfig: enable CONFIG_THERMAL_QPNP
9821ed14f308 Merge branch 'pie' of https://github.com/xNombre/msm-4.4 into pie
bdbae18b6be9 Revert "msm: kgsl: Correct the iommu protection ranges"
8f285ebec432 defconfig: enable scm errata

====================
     09-12-2019
====================


   * frameworks/base/
eae8c644bcc KeyguardSliceView: Improve Alignment

   * kernel/xiaomi/msm-4.4/
e4287d45ebfb Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie
fed4e1b20885 Merge branch 'upstream-linux-4.4.y' of https://android.googlesource.com/kernel/common into pie

   * packages/apps/Settings/
7ba50f2dd9 SettingsLib: Update Utils APIs usage

