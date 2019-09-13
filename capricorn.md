
====================
     09-13-2019
====================


   * device/xiaomi/gemini/
69762e9a Revert "BoardConfig: permissive kernel"
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

   * packages/apps/Settings/
520ef75315 add SearchIndexProvider into HavocSettings [2/2]
05cedbf8d7 Support to notify connected/disconnected stations
b253824d58 Havoc Build Date [2/2]
9dce25a628 DeviceInfoSettings: Bring back CAF/AOSP tags
5fc0bfc4c7 my colors
2417d6c957 Revert "Revert "Settings: Add toggle for proximity wake""

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

====================
     09-11-2019
====================


   * kernel/xiaomi/msm-4.4/
473504d5ddf4 Merge 4.4.192 into kernel.lnx.4.4.r37-rel
882f8791e141 Linux 4.4.192
89e0660bc531 net: stmmac: dwmac-rk: Don't fail if phy regulator is absent
e6198d2b4ff0 net: fix skb use after free in netpoll
94eb5357f6d6 Revert "x86/apic: Include the LDR when clearing out APIC registers"
e187a57fc653 spi: bcm2835aux: fix corruptions for longer spi transfers
b2f16660fc86 spi: bcm2835aux: remove dangerous uncontrolled read of fifo
5473cd1dbf97 spi: bcm2835aux: unifying code between polling and interrupt driven code
c99ad4f20c5b spi: bcm2835aux: ensure interrupts are enabled for shared handler
c3083eff1b1b libceph: allow ceph_buffer_put() to receive a NULL ceph_buffer
bce83d9ccca5 KVM: arm/arm64: Only skip MMIO insn once
1d86cb8d3204 ceph: fix buffer free while holding i_ceph_lock in __ceph_setxattr()
bc68ba54a2d3 IB/mlx4: Fix memory leaks
6442370b5642 Tools: hv: kvp: eliminate 'may be used uninitialized' warning
bf3583e15956 ravb: Fix use-after-free ravb_tstamp_skb
62b1e22efe3e wimax/i2400m: fix a memory leak bug
1b25f01d604e net: kalmia: fix memory leaks
2d28afe7a79e cx82310_eth: fix a memory leak bug
f6f3170c57da net: myri10ge: fix memory leaks
fa6d2679e5ca cxgb4: fix a memory leak bug
f46a46a9de0f gpio: Fix build error of function redefinition
da5cc03c7562 ibmveth: Convert multicast list size for little-endian system
5694f0d1cb10 Bluetooth: btqca: Add a short delay before downloading the NVM
ffb54f3eae72 net: tc35815: Explicitly check NET_IP_ALIGN is not zero in tc35815_rx
e040f074d49f net: tundra: tsi108: use spin_lock_irqsave instead of spin_lock_irq in IRQ context

====================
     09-10-2019
====================


   * frameworks/base/
d48f2a23e0e SystemUI: Allow SystemUI WRITE_APN_SETTINGS
63e1c188d98 base: seekbar: Increase bottom padding
d5d62f2af61 base: media_seekbar: make it sexy
dd3f9cb28c0 SystemUI: Whitelist our recorder on CastController
7346f4f89ed VolumeDialogControllerImpl: Check for internal audio recording support
562e7094c49 QSTileHost: Recreate tiles when LiveDisplay gets initialized
e9dc6c7f2a0 Revert "LiveDisplayTile: Remove tile if unavailable"
d41fcc067f8 Better QS detail clip animation
b0cdd3be0de fw/b: Use common network restrict apps method
31ec3c3185a SystemUI: Allow for notch view to be ignored
5d8fb38a43e base: Add toggle for OP gestures haptic feedback [1/2]
9e6a384003d Allow override of DUN settings
396656ae826 SystemUI: CellularTile: Improve layout
9fd08954ab1 SystemUI: Add default data sub switcher in CellularTile
189821a286c base: Add Circle battery style from PA [1/2]
c37ddff12fe base: Add 2 more date styles [1/2]
88450ed0a74 base: Add more date styles [1/2]
e98768bcea9 Introduce lockscreen date styles [1/2]
9587d5403f4 base: Cleanup Screenrecord
42fabfa873f Fix Google Markup FC

   * kernel/xiaomi/msm-4.4/
7fab8f77e8d3 tcp: Disable TCP timestamp accounting

   * packages/apps/HavocSettings/
ee616b1 Settings: Add toggle for OP gestures haptic feedback [2/2]
c96da3d Settings: Add Circle battery style from PA [2/2]
d5e139d Settings: Add 2 more date styles [2/2]
8c5d8a9 Settings: Add more date styles [2/2]
5041eb5 Lockscreen date styles [2/2]
7021100 Settings: Cleanup Screenrecord
1c38957 Merge pull request #6 from Sobuj53/pie

   * vendor/havoc/
f3ac8f8d update Recorder permissions
82bc4129 Havoc 2.9
a3135a86 prebuilts: Remove outdated TCP init script
83dbc654 LatinIME: Add en_GB, en_US, lt, lv, ro, sl, sr, tr dictionaries

====================
     09-09-2019
====================


   * kernel/xiaomi/msm-4.4/
c6ac0af96ba3 config: disable KALLSYMS
d6c12922b197 defconfig: disable MEMCG for enable Simple LMK
276eebc4ddd4 msm: sps: Fix uninitialized result usage when an invalid IRQ is found
84009fa8795a arm64: enable 128bit ints
2cea537ac640 defconfig: Disable bounce buffers
bd4b27456859 Makefile: add optimization flags
7cb4dffa5bf9 mm: Implement minimum bound for performing readahead
4b77a17695d1 mm: Do readahead if requested size is over 64 KiB
0dfeaae0a7f0 defconfig: Disable bounce buffers
e5ab2474d136 sched: Enable NEXT_BUDDY for better cache locality
b9deeae1468c gpu: msm: Do not compile Adreno 3xx / 4xx drivers
fad7f026ce60 irq: spurious: Disable IRQ debugging by default
7dae9143a3bd msm: kgsl: Avoid dynamically allocating small command buffers
367487436a06 mbcache2: Speed up cache entry creation
a7acbb40d53c ext4 crypto: Use a larger on-stack file name buffer
c71e101fc71a selinux: Avoid dynamic memory allocation for small context buffers
2f851631a4c3 crypto: msm: Don't bail out when debugfs creation fails
abececddfb6d dtc: drop HMP flags from bootargs
1a7d693a2288 Merge branch 'upstream-linux-4.4.y' of https://android.googlesource.com/kernel/common into pie

   * packages/apps/HavocSettings/
2a47642 Updated some more text translations
32dc08e Merge pull request #1 from HavocGemini/pie
2114e6f Original file
f1c0ac9 Bangla translation
4795a92 Translation updated

====================
     09-08-2019
====================

   * art/
5ab5014a30 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/art into pie

   * build/make/
4a4a6d7ae Bump Security String to 2019-09-05
e8c0b4528 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/build into pie

   * device/qcom/sepolicy/
d0cebf3d Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into HEAD

   * device/xiaomi/gemini/
74b87c7c Android tag: 9.0.0_r48, CAF: LA.UM.7.6.r1-05900-89xx.0
0dc0d601 build 4.4 by default
d990efc2 msm8996-common: manifest: Disable IDisplayModes for livedisplay
357a8351 BoardConfig: switch to gcc 9.2.0 for inline kernel building

   * external/f2fs-tools/
cf62e1f Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/external/f2fs-tools into HEAD

   * external/skia/
39b01cd8b5 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/external/skia into pie

   * frameworks/av/
9b2e66ee1c Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/frameworks/av into HEAD

   * frameworks/base/
871ef9888c4 Updated Bangla translation
bbcd5829151 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/frameworks/base into HEAD

   * frameworks/native/
6929ebac2 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/frameworks/native into HEAD

   * frameworks/opt/net/ims/
e6a6853 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

   * frameworks/opt/telephony/
7a74527f13 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

   * kernel/xiaomi/msm-4.4/
7136452cb550 Merge branch '4.4-eas' of https://github.com/SyberiaProject-Devices/platform_kernel_xiaomi_msm8996 into pie

   * packages/apps/Contacts/
93f6d9bb9 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Contacts into HEAD

   * packages/apps/Dialer/
f23ad765d Revert "Fix in-call buttons layout"

   * packages/apps/Nfc/
f20bb61b Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD

   * packages/apps/PackageInstaller/
605b8059 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/PackageInstaller into HEAD

   * packages/providers/DownloadProvider/
87339a7 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/providers/DownloadProvider into HEAD

   * packages/services/Telecomm/
06fe66d6 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/services/Telecomm into pie

   * system/bt/
8f2e7bb56 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/bt into HEAD
d8084795f Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
66b2c46ea RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
5ac75714c sdclang: true
46ff89f84 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
e8ca28c2f Fix a memory leak in gatekeeper.
4a3c089b0 Allow adb root even in no debuggable builds

   * system/libhwbinder/
8ad884e Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/libhwbinder into HEAD

   * system/netd/
09675f1 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/netd into HEAD

   * system/sepolicy/
fcb959919 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/sepolicy into pie
e0e9346f1 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie

   * system/tools/hidl/
5d83b4c Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/tools/hidl into HEAD

   * system/update_engine/
75935ee Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/update_engine into HEAD

   * system/vold/
92ced5a Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/vold into HEAD

   * vendor/havoc/
f61704e1 BoardConfigKernel: separate KERNEL_OBJ paths
d9f4202c update Lawnchair to alpha-2399

====================
     09-07-2019
====================


   * device/xiaomi/gemini/
7f78d069 rootdir: drop 'eng' tag
4c067a59 rootdir: kang configfs from nile-common
2bb7d888 BoardConfig: permissive kernel
138aa319 msm8996: add missing libs

   * kernel/xiaomi/msm-4.4/
1b41801e11ab defconfig: Change LOCALVERSION for EAS kernel
4c1ebaade573 Merge 4.4.191 into kernel.lnx.4.4.r37-rel

====================
     09-06-2019
====================


   * frameworks/base/
ffeecb46478 Fix typo

   * kernel/xiaomi/msm-4.4/
efbc4a364bd5 Linux 4.4.191
61263fbe574b x86/ptrace: fix up botched merge of spectrev1 fix
8c0932cd8197 mac80211: fix possible sta leak
3161dea144dd Revert "cfg80211: fix processing world regdomain when non modular"
16ab568881f8 VMCI: Release resource if the work is already queued
c25b7d78f0e8 stm class: Fix a double free of stm_source_device
e2f1509fca47 mmc: core: Fix init of SD cards reporting an invalid VDD range
12a897daa78b mmc: sdhci-of-at91: add quirk for broken HS200
4d1a41682781 uprobes/x86: Fix detection of 32-bit user mode
d6029fe64cef ptrace,x86: Make user_64bit_mode() available to 32-bit builds
476147408876 USB: storage: ums-realtek: Whitelist auto-delink support
00087c6e434e USB: storage: ums-realtek: Update module parameter description for auto_delink_en
eb1ff5020b3e usb: host: ohci: fix a race condition between shutdown and irq
0d743d816ace USB: cdc-wdm: fix race between write and disconnect due to flag abuse
6f575b509cce usb-storage: Add new JMS567 revision to unusual_devs
5bd0d83e2d5a x86/apic: Include the LDR when clearing out APIC registers
26285030611e x86/apic: Do not initialize LDR and DFR for bigsmp
0fff074fc4ae KVM: x86: Don't update RIP or do single-step on faulting emulation
e3abf92c855c ALSA: seq: Fix potential concurrent access to the deleted pool
ec1933594cbb tcp: make sure EPOLLOUT wont be missed
a485888b5189 ALSA: usb-audio: Fix an OOB bug in parse_audio_mixer_unit
735a16d1afc0 ALSA: usb-audio: Fix a stack buffer overflow bug in check_input_term
1a48b39d1885 tcp: fix tcp_rtx_queue_tail in case of empty retransmit queue
59326db35268 watchdog: bcm2835_wdt: Fix module autoload
348e556cd7e6 tools: hv: fix KVP and VSS daemons exit code
6cf3f1cd77ba usb: host: fotg2: restart hcd after port reset
c66c6ac3ff15 usb: gadget: composite: Clear "suspended" on reset/disconnect
d4d31cf624a0 dmaengine: ste_dma40: fix unneeded variable warning
ffb7396e3c99 scsi: ufs: Fix NULL pointer dereference in ufshcd_config_vreg_hpm()
721a2f80a4cb x86/CPU/AMD: Clear RDRAND CPUID bit on AMD family 15h/16h
f0395f6e1100 x86/pm: Introduce quirk framework to save/restore extra MSR registers around suspend/resume
f5a3392464a9 Revert "perf test 6: Fix missing kvm module load for s390"
b7a27ca75b43 netfilter: conntrack: Use consistent ct id hash calculation
36bbd861a402 netfilter: ctnetlink: don't use conntrack/expect object addresses as id
66f8c5ff8ed3 inet: switch IP ID generator to siphash
71b951c85b3b siphash: implement HalfSipHash1-3 for hash tables
994fcca7f1c9 siphash: add cryptographically secure PRF
6ca24361c2a4 vhost: scsi: add weight support
bb85b4cbd8f6 vhost_net: fix possible infinite loop
9e0b34063264 vhost: introduce vhost_exceeds_weight()
94291043ad32 vhost_net: introduce vhost_exceeds_weight()
7f3cfe5d32d8 vhost_net: use packet weight for rx handler, too
e44915de7559 vhost-net: set packet weight of tx polling to 2 * vq size
b31c9932f84c net: arc_emac: fix koops caused by sk_buff free
d61e517e3914 GFS2: don't set rgrp gl_object until it's inserted into rgrp tree
d60df1c0892f cgroup: Disable IRQs while holding css_set_lock
1f1d46fe5cc0 dm table: fix invalid memory accesses with too high sector number
77529c247cc2 dm space map metadata: fix missing store of apply_bops() return value
063c4d18688b dm btree: fix order of block initialization in btree_split_beneath
24a5ed6757d8 x86/boot: Fix boot regression caused by bootparam sanitizing
41664b97f46e x86/boot: Save fields explicitly, zero out everything else
a0a0e3bf98fc x86/apic: Handle missing global clockevent gracefully
35b67f4f1659 x86/retpoline: Don't clobber RFLAGS during CALL_NOSPEC on i386
858cfbe83a44 userfaultfd_release: always remove uffd flags and clear vm_userfaultfd_ctx
74c6926bf988 Revert "dm bufio: fix deadlock with loop device"
a19535e838d5 HID: wacom: correct misreported EKR ring values
a43b6e062d69 selftests: kvm: Adding config fragments
d2b2a7dd72c6 libata: add SG safety checks in SFF pio transfers
114bf652fbb6 net: hisilicon: Fix dma_map_single failed on arm64
e3ae5d356fb6 net: hisilicon: fix hip04-xmit never return TX_BUSY
47cadfd97156 net: hisilicon: make hip04_tx_reclaim non-reentrant
acd6061a2a02 net: cxgb3_main: Fix a resource leak in a error path in 'init_one()'
d72eb7187dcb NFSv4: Fix a potential sleep while atomic in nfs4_do_reclaim()
1f46dbe266aa can: peak_usb: force the string buffer NULL-terminated
583354067975 can: sja1000: force the string buffer NULL-terminated
2931cc0aa912 perf bench numa: Fix cpu0 binding
d1f1bad0ac51 isdn: hfcsusb: Fix mISDN driver crash caused by transfer buffer on the stack
95305808fcb2 isdn: mISDN: hfcsusb: Fix possible null-pointer dereferences in start_isoc_chain()
cbfc4562e69f net: usb: qmi_wwan: Add the BroadMobi BM818 card
25772b11f85e ASoC: ti: davinci-mcasp: Correct slot_width posed constraint
7cdc11216827 st_nci_hci_connectivity_event_received: null check the allocation
c697bfc26a46 st21nfca_connectivity_event_received: null check the allocation
dc8438815624 can: dev: call netif_carrier_off() in register_candev()
5927e91f5024 bonding: Force slave speed check after link state recovery for 802.3ad
2fd7fdc057e6 netfilter: ebtables: fix a memory leak bug in compat
afbd69c7c6ce MIPS: kernel: only use i8253 clocksource with periodic clockevent
4322f947c6f5 HID: Add 044f:b320 ThrustMaster, Inc. 2 in 1 DT
27addce7a479 defconfig: Use Simple LMK
043992db2fc5 simple_lmk: Mark reclaim kthread as performance critical
44f8b7e9a441 simple_lmk: Introduce Simple Low Memory Killer for Android
db7671447ab7 defconfig: Enable kcal
b3dffe433e9f msm: mdss: kcal: Add KCAL support for post processing control [v2]
c27fa1dfdb1f Merge branch 'pie' of https://github.com/xNombre/msm-4.4 into pie

   * prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-9.1/
4f96ce7 cc1, lto1: Fix library rpath
0335d0d Update toolchain to GCC 9.2.0 + binutils 2.32
21ee8f1 lib: Bundle flex library for Ubuntu 14.04 compatibility
e8ca67d lib: Bundle unconventional shared libraries used by GCC

====================
     09-05-2019
====================


   * kernel/xiaomi/msm-4.4/
81faf1872506 Merge branch 'pie' of https://github.com/xNombre/msm-4.4 into HEAD
e6da35184e23 gemini_defconfig: enable kcal
42d6c64b1198 msm: mdss: kcal: Add KCAL support for post processing control [v2]
a08956478cc7 defconfig: change kernel name to xNombre
6b1f33b53ecb remove prebuilt compiler
5177054a9c81 README: fix derp
1dcca8b4a8c9 i2c-msm-v2: Ensure system is always active for i2c transfers
68fea8070df6 Update README
23e8706d926b Clean tree
e553737568cd Merge branch 'pie' of https://github.com/xNombre/msm-4.4 into HEAD

   * packages/apps/Recorder/
a3cd3c7 Recorder: UI changes and improvements

====================
     09-04-2019
====================


   * device/xiaomi/gemini/
aae7bf47 msm8996: Add libmm-omxcore.so required by libOmxVpp.so

   * kernel/xiaomi/msm-4.4/
f94413e6d08a Merge branch 'pie' of https://github.com/xNombre/msm-4.4 into pie
de9dcc22d870 update gemini_defconfig
d8cf3e7e22f8 defconfig: enable exFAT and NTFS for OTG
c1a13268f09b Import exFAT driver
35cf8b23cfa2 defcofnig: enable skip sync
e42140958bb7 defconfig: massive debloat

   * packages/apps/Longshot/
ff71ea5 Add edit action on notification
7135a5e Declare priv-app permission

   * packages/apps/Recorder/
25243f4 Automatic translation import

====================
     09-03-2019
====================


   * hardware/interfaces/
5e1979a96 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

   * hardware/qcom/audio-caf/msm8996/
eb9999c2 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/bt-caf/
3b4dc64 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into 9.0

   * hardware/qcom/media-caf/msm8996/
8016b702 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into 9.0

   * kernel/xiaomi/msm-4.4/
8230dfa1b15d cpufreq: Don't let userspace set the max freq
52bd55d3c315 Defconfig: Enable Thermal Simple
ef2b5b4afd70 dts: gemini: configure thermal_simple zones
5fbb57e57334 Defconfig: bring initial EAS defconfig
27436b1559e1 Revert "arch: arm64: crypto: Improve CPU targeting"
3a8ab440196c Treewide: Solve various compilation issues
3fbc1103df61 soc: qcom: scm: Add a noretry variant for scm_call2
5999a81b1780 qseecom: replace scm_call2 with scm_call2_noretry
9312d9c46ed2 msm: kgsl: Wake GPU upon receiving an ioctl rather than upon touch input
311db5745977 Revert "sched/debug: Fix potential deadlock when writing to sched_features"
0a8a18b0340e fs: f2fs: Adapt gc.c to use f2fs_info()
152cc53b25be ARM: dts: msm8996: Set GPU idle timeout to 64 ms
463b2c94bcb0 dts: msm8996: fix idle cost data
b67351e7c5b7 dts: msm: Patch msm8996 cluster energy model to be monotonically increasing
2c5855162b9e dts: msm: Make SD820's Big cluster energy model more identical to Little's
f62bb6864b13 dts: msm: Rework energy model for SD820 SOC
3fb58cd91698 ARM: dts: msm: Import msm8996 energy model
c6b2f74224c1 arm64: Select ARCH_HAS_FAST_MULTIPLIER
ecdfefcf4247 msm: mdss: save state of vsync handler
93d95df8a394 sched/fair: Do not migrate due to a sync wakeup on exit
d3093c5a2e73 sched: Rename sched_group_cpus()
2fa0477c96a2 [FIXUP] sched/fair, cpumask: Export for_each_cpu_wrap()
f3939d9af5a2 sched: debug: Remove stats that were used in select_idle_sibling()
c98a0985409e sched/fair: Use a recently used CPU as an idle candidate and the basis for SIS
062d00882fcf sched/fair: Fix sched domains NULL dereference in select_idle_sibling()
ec69dab9cb41 ANDROID: sched: EAS: take cstate into account when selecting idle core
a819c95587d5 sched/core: Rewrite and improve select_idle_siblings()
57871d7020b8 sched/core: Replace sd_busy/nr_busy_cpus with sched_domain_shared
5f2e14460ea5 sched/core: Introduce 'struct sched_domain_shared'
8de9c57b5f3f sched/fair: Make the use of prev_cpu consistent in the wakeup path
31f515bd7b83 Revert "sched: EAS: take cstate into account when selecting idle core"
58615f209911 Revert "BACKPORT: sched/fair: Make the use of prev_cpu consistent in the wakeup path"
b02ddfd46408 Revert "sched/fair: Simplify idle_idx handling in select_idle_sibling()"
64423d2c3ef5 msm/sde/rotator: fix probe defferal issue
e09df9bd2476 msm: sde: avoid dynamic kthread create for each rot session
d39bf93664e9 msm/sde/rotator: add pm qos for rotator after core init
b066ed836f7c drm/msm/sde: add PM QOS for rotator path
533c49687e90 Revert "locking: Implement an algorithm choice for Wound-Wait mutexes"
5d7d8750afa0 Revert "locking/mutex: Fix mutex debug call and ww_mutex documentation"
5acb5a837c34 sched/fair: Initialize throttle_count for new task-groups lazily
ee8f42ce4943 sched/fair: Fix typo in sync_throttle()
5465eebd0b43 sched/fair: Rework throttle_count sync
2a6e90df9169 sched/fair: Remove unused but set variable 'rq'
6780b0255fed sched/fair: Reorder cgroup creation code
a46b9181522c sched/fair: Update and fix the runnable propagation rule
8b8ad9d8b70b arm64/lib: copy_page: use consistent prefetch stride
69b783c6d9ce sched: Move cpu_util() to the header file
54adbffa0566 sched/rt: Make sched_rt_update_capacity_req no-op
a5e856b9d29b softirq, sched: reduce softirq conflicts with RT
2fdd43bff6f1 Revert "softirq: defer softirq processing to ksoftirqd if CPU is busy with RT"
9a2730fab71a Revert "softirq: Don't defer all softirq during RT task"
1add0f907f05 sched/rt: Fix inconsistencies in the CAF tree
b4cf46359da3 ANDROID: sched/rt: rt cpu selection integration with EAS.
8e2c2d10ad42 qcom-cpufreq: Set dvfs_possible_from_any_cpu cpufreq driver flag
01168ff88766 [FIXUP] cpufreq: schedutil: Don't set next_freq to UINT_MAX
68678a8c6050 sched/rt: Show the 'sched_rr_timeslice' SCHED_RR timeslice tuning knob in milliseconds
db52dfd783f8 locking/rwsem: for rwsem prio aware enhancement
3e4de57d2a86 qseecom: use scm_call2 for shutdown app
d8d80c4e4a81 clk: qcom: Use regmap_update_bits() to update the clock flags
c85952e0156d usb: dwc3-msm: Ensure reset if h/w is out of lpm without any events
26b91ce6504f sched/fair: Only strict skip for current task
2a2bd84b7970 sched/core: Inline part of try_to_wake_up() with Mainline
07678b06500a locking/spinlock, sched/core: Clarify requirements for smp_mb__after_spinlock()
8a87573801fa locking: Introduce smp_mb__after_spinlock()
00fc052da8de Revert "cpufreq: schedutil: Only apply single core busy logic with PELT"
9d4e00131635 sched/core: Guard WALT code
43fd330eca73 asm/sections: add helpers to check for section data
1f23a77b7102 atomics/treewide: Make atomic_fetch_add_unless() optional
aafbab5fc025 atomics/treewide: Rename __atomic_add_unless() => atomic_fetch_add_unless()
32583b37c01b init: Hardcode value for CC_HAS_ASM_GOTO
af9ebd2dd0b9 arm64/kernel: jump_label: Switch to relative references
9d53cb899214 jump_label: Batch updates if arch supports it
82270c56ed57 jump_label: Sort entries of the same key by the code
cbbf98914480 jump_label: Add a jump_label_can_update() helper
5dfa6fd910b9 jump_label: move 'asm goto' support test to Kconfig
cc05c3647171 sched/debug: Fix potential deadlock when writing to sched_features
026efe69613b sched/debug: Move the /sys/kernel/debug/sched_features file setup into debug.c
6c944f4f2806 netfilter: don't call hooks unless needed
ae4315811a60 dynamic_debug: add jump label support
77d6e6d84094 locking/static_key: Fix false positive warnings on concurrent dec/inc
3d5769c43e4e jump_label: Fix NULL dereference bug in __jump_label_mod_update()
b18e77507c82 jump_label: Annotate entries that operate on __init code earlier
c825b6f49036 jump_label: Implement generic support for relative references
313a71209fc4 jump_label: Abstract jump_entry member accessors
8a20bf0fc628 jump_label: Fix typo in warning message
2a4b3836c533 jump_label: Use static_key_linked() accessor
2527ed82c807 jump_label: Disable jump labels in __exit code
e0671d6caf0e jump_label: Fix sparc64 warning
a5946df08e85 extable: Make init_kernel_text() global
8f8b8a57a1b3 jump_label: Warn on failed jump_label patching attempt
a93d2725433c jump_label: Explicitly disable jump labels in __init code
c6d2054a5755 jump_label: Reduce the size of struct static_key
f2eb96808f8d jump_label: remove bug.h, atomic.h dependencies for HAVE_JUMP_LABEL
76da5af66e16 jump_label: disable preemption around __module_text_address().
055f1942f493 jump_label: Make it possible for arches to invoke jump_label_init() earlier
ae489d07ddc4 locking/static_keys: Fix non static symbol Sparse warning
5edca36adb6c sched/fair: Mask UTIL_AVG_UNCHANGED usages
fb62cb3bd73f sched/fair: Add checks for WALT in cpu_util*()
5ba0b6156e25 sched: Import cpu_util_freq()
ea9f5b4d3abe sched/fair: Reimport cpu_util*() functions
4e8eb1c55ceb sched: Remove cpu_util*() definitions
577a13743b93 sched: Turn on TTWU_QUEUE feature
d5878ee13e2b sched/fair: Remove setting task's se->runnable_weight during PELT update
e3fc269c7834 sched/pelt: Move PELT related code in a dedicated file
314ef12fc16d iommu: do not attempt reclaim on higher order allocs
9677d36339be sched/fair: Fix O(nr_cgroups) in the load balancing path
e866828db70f sched/fair: Move the rq_of() helper function
26adf27f4c3e sched/fair: Fix unnecessary increase of balance interval
88d654d0a92d sched/fair: Fix rounding bug for asym packing
624728f2fe27 sched/fair: Trigger asym_packing during idle load balance
038e4ffb1fe9 sched/fair: Fix infinite loop in update_blocked_averages() by reverting a9e7f6544b9c
60421bae2ae0 sched/fair: Add cfs_se_util_change() call to it's proper place
6a73aef4ca73 sched/core: Ensure load_balance() respects the active_mask
0e4ec0bb50ab sched/fair: Update calc_group_*() comments
705197f04b8d sched/fair: Calculate runnable_weight slightly differently
9bb04b154fa0 sched/fair: Implement more accurate async detach
f957d9a91df1 sched/fair: Align PELT windows between cfs_rq and its se
66e2faf81d87 Revert "ANDROID: sched/fair: initialise util_est values to 0 on fork"
2f556a5a0b6b [FIXUP]sched/fair: Implement synchonous PELT detach on load-balance migrate
172a7de568d7 sched/fair: Propagate an effective runnable_load_avg
c093ac8ed7a0 sched/fair: Fix O(nr_cgroups) in load balance path
1c362375afb2 sched/fair: Rewrite PELT migration propagation
4439cdb53f98 sched/fair: Rewrite cfs_rq->removed_*avg
222949a726be sched/fair: Use reweight_entity() for set_user_nice()
3ab86d6e669f sched/fair: More accurate reweight_entity()
958f1ec3bc01 sched/fair: Introduce {en,de}queue_load_avg()
1f327cefca91 sched/fair: Rename {en,de}queue_entity_load_avg()
a2d47845da44 sched/fair: Move enqueue migrate handling
52a5abd70f6c sched/fair: Change update_load_avg() arguments
9d7035dc07a1 sched/fair: Remove se->load.weight from se->avg.load_sum
a99eb2b6c8ee sched/fair: Remove unclean cfs_se_util_change() call
bcac864c35a0 sched/fair: Cure calc_cfs_shares() vs. reweight_entity()
d9b6a6560231 sched/fair: Add comment to calc_cfs_shares()
2b54e8bb0ab2 sched/fair: Clean up calc_cfs_shares()
adb07cff0538 sched/fair: Add ';' after label attributes
8fe4a5c1197b sched/fair: Fix vruntime_normalized() for remote non-migration wakeup
444faaa2ae41 Revert "sched/fair: vruntime should normalize when switching from fair"
497297182186 sched/fair: Search a task from the tail of the queue
ecae2145bd59 [FIXUP]locking: Implement an algorithm choice for Wound-Wait mutexes
3624f1f901d7 arm64: Use aarch64elf and aarch64elfb emulation mode variants
be2162031296 arm64: ensure the kernel is compiled for LP64
5bb1afb7a746 arm64: Set UTS_MACHINE in the Makefile
e2a6e9f79f50 Revert "PM / QoS: Fix memory leak on resume_latency.notifiers"
72b692a28681 FROMLIST: sched/fair: Update blocked load from newly idle balance
22ed86715e1c sched/fair: Fix fairness issue on migration
efa546cda73a sched/core: Kill sched_class::task_waking to clean up the migration logic
36714e2c6db7 sched/core: Fix remote wakeups
a2f0b9b7e8eb sched/fair: Prepare to fix fairness problems on migration
8e9a733ccb2e Revert "sched: ignore task_h_load for CPU_NEWLY_IDLE"
2a838f944aaf Revert "sched: set loop_max after rq lock is taken"
8a0f08906e40 Revert "sched: check pinned tasks before balance"
c1dea74f2231 Revert "sched: set number of iterations to h_nr_running"
730ebc12d335 lib: refcount: Replace smp_acquire__after_ctrl_dep() with smp_rmb()
9decba58924f locking/spinlocks/arm64: Remove smp_mb() from arch_spin_is_locked()
a73a697e2261 arm64: spinlock: Ensure forward-progress in spin_unlock_wait
cb5b99c857af arm64: spinlock: order spin_{is_locked,unlock_wait} against local locks
40f88132c588 include: list: Import list_cut_before()
70e429860773 locking/mutex: Test for initialized mutex
8b4d480afd10 locking/lockdep: Hide unused 'class' variable
51ff986ea242 locking/lockdep: Fix lock used or unused stats error
cbcb0458fdf9 locking/lockdep: Fix OOO unlock when hlocks need merging
d05ab36e947a locking/lockdep: Don't complain about incorrect name for no validate class
e958b39c12af locking/rwsem: Prevent decrement of reader count before increment
10c78fff88c9 locking/lockdep: Remove unnecessary unlikely()
4510cf06943d locking/lockdep: Avoid a Clang warning
9ae9a28b858e refcount_t: Add ACQUIRE ordering on success for dec(sub)_and_test() variants
c7fc686c0b37 locking/refcount: Always allow checked forms
e6dc111cb0e2 locking/refcounts: Include fewer headers in <linux/refcount.h>
ea73f947b9e1 locking/refcounts: Implement refcount_dec_and_lock_irqsave()
ad16e5e7e545 docs: refcount_t documentation
20c999e384ad locking/refcount: Remove the half-implemented refcount_sub() API
da6b6cc923cd locking/refcount: Create unchecked atomic_t implementation
48a174d62401 refcount: change EXPORT_SYMBOL markings
a28996e692c6 locking/refcounts: Use atomic_try_cmpxchg()
f595060a58a4 locking/refcounts: Change WARN() to WARN_ONCE()
92e036573c96 locking/refcount: Add refcount_t API kernel-doc comments
6317c6527fc1 locking/refcounts: Add missing kernel.h header to have UINT_MAX defined
3930284f4960 locking/refcounts: Out-of-line everything
8a3b627f03ac refcount_t: Introduce a special purpose refcount type
2356527df304 Revert "rcu: Suppress lockdep false-positive ->boost_mtx complaints"
1aa3d4ce9409 locking/lockdep: Add module_param to enable consistency checks
e2014deda1b4 locking/lockdep: Verify whether lock objects are small enough to be used as class keys
560b57eb71ab locking/lockdep: Check data structure consistency
b18f80464423 locking/lockdep: Reuse lock chains that have been freed
b88f55b7ed84 locking/lockdep: Fix a comment in add_chain_cache()
fe9609aba362 locking/lockdep: Introduce lockdep_next_lockchain() and lock_chain_count()
b6da3523fd3d locking/lockdep: Reuse list entries that are no longer in use
2530d5e89f3e locking/lockdep: Free lock classes that are no longer in use
0404c8655ef2 locking/lockdep: Make it easy to detect whether or not inside a selftest
30a8ca12b600 locking/lockdep: Split lockdep_free_key_range() and lockdep_reset_lock()
7e380297ae7b locking/lockdep: Initialize the locks_before and locks_after lists earlier
dc6d27761164 locking/lockdep: Make zap_class() remove all matching lock order entries
defa398c727f locking/lockdep: Avoid that add_chain_cache() adds an invalid chain to the cache
691b984444c8 locking/lockdep: Fix reported required memory size (2/2)
385a7f7eba8e locking/lockdep: Fix reported required memory size (1/2)
1079bdefdcca locking/lockdep: Fix two 32-bit compiler warnings
3890c141e3dd locking/qspinlock: Remove unnecessary BUG_ON() call
3af54a40e190 futex: Handle early deadlock return correctly
a91b6de6626c locking/qspinlock_stat: Track the no MCS node available case
e020878a3d81 locking/qspinlock: Handle > 4 slowpath nesting levels
9e78b542cb36 futex: Consolidate duplicated timer setup code
fb7df9f9ac57 locking/futex: Allow low-level atomic operations to return -EAGAIN
1faa6f602350 futex: Convert futex_pi_state.refcount to refcount_t
105adaa95b56 futex: Fix barrier comment
369679b9cf6c sched/wake_q: Reduce reference counting for special users
96369901870d futex: No need to check return value of debugfs_create functions
37f8d91d2ec8 futex: Fix (possible) missed wakeup
b48e688a6fa3 futex: Cure exit race
d83e88b8f77b futex: Replace spin_is_locked() with lockdep
3d32961d0aa5 futex: Mark expected switch fall-throughs
e4e6a21c7f2c futex: Fix OWNER_DEAD fixup
385138329179 futex: Prevent overflow by strengthen input validation
40fa35a38ddc futex: futex_wake_op, do not fail on invalid op
98fd64e57d92 futex: Fix more put_pi_state() vs. exit_pi_state_list() races
94774aa32a33 futex: Fix pi_state->owner serialization
c9ec8dd3c9a8 futex: Clarify mark_wake_futex memory barrier usage
8693f8b84998 futex: Fix small (and harmless looking) inconsistencies
54b43da41065 futex: Avoid freeing an active timer
a653483d71d5 [FIXUP]futex: Drop hb->lock before enqueueing on the rtmutex
6234ffdb16f7 futex: Futex_unlock_pi() determinism
3916cd9f8e16 locking/lockdep: Add debug_locks check in __lock_downgrade()
1a0a3b2970c8 locking/lockdep: Provide enum lock_usage_bit mask names
f9a62988cf93 locking/lockdep: Simplify mark_held_locks()
c351344b7885 locking/lockdep: Add debug_locks check in __lock_downgrade()
5456a02f9d21 locking/rwsem: Fix (possible) missed wakeup
aef8b9690b18 kernel/locking/mutex.c: remove caller signal_pending branch predictions
07bd13973dce locking/lockdep: Stop using RCU primitives to access 'all_lock_classes'
4e5cca08a9d8 locking/lockdep: Make concurrent lockdep_reset_lock() calls safe
bf84611467bd locking/lockdep: Remove a superfluous INIT_LIST_HEAD() statement
a8f406496e31 locking/lockdep: Introduce lock_class_cache_is_registered()
97f678a74bc6 locking/lockdep: Inline __lockdep_init_map()
eddf54cfc651 locking/lockdep: Declare local symbols static
688ef573eee5 locking/mutex: Replace spin_is_locked() with lockdep
bb9846d84ce7 locking/pvqspinlock: Extend node size when pvqspinlock is configured
694b5c10706f locking/qspinlock_stat: Count instances of nested lock slowpaths
96f979496a6b locking/qspinlock: Provide liveness guarantee
44b89ee1e8c2 locking/qspinlock: Rework some comments
37116c489daa locking/qspinlock: Re-order code
0900f6036c60 locking/lockdep: Remove duplicated 'lock_class_ops' percpu array
fc7db1a3bcdf locking/lockdep: Make class->ops a percpu counter and move it under CONFIG_DEBUG_LOCKDEP=y
34357ddd28de locking/lockdep: Add a faster path in __lock_release()
1660f0eb3707 locking/lockdep: Eliminate redundant IRQs check in __lock_acquire()
09bd9cd61346 locking/lockdep: Remove add_chain_cache_classes()
632e1388d77a locking/rtmutex: Fix the preprocessor logic with normal #ifdef #else #endif
ac9fa5116ff9 locking/rwsem: Make owner store task pointer of last owning reader
73aa2e00b17e locking/rwsem: Exit read lock slowpath if queue empty & no writer
26d8d7910e03 locking/mutex: Fix mutex debug call and ww_mutex documentation
c5362ec0cc9d lockdep: Use this_cpu_ptr instead of get_cpu_var stats
1227e92187a5 locking/rtmutex: Allow specifying a subclass for nested locking
bd73b3d556ea locking: Implement an algorithm choice for Wound-Wait mutexes
6f8dc23a1653 locking: WW mutex cleanup
8b9c55a28f16 locking/rwsem: Fix up_read_non_owner() warning with DEBUG_RWSEMS
507c9933a323 locking/rwsem: Simplify the is-owner-spinnable checks
7987c0f25c8b locking/percpu-rwsem: Annotate rwsem ownership transfer by setting RWSEM_OWNER_UNKNOWN
32b994f98e29 locking/rwsem: Add a new RWSEM_ANONYMOUSLY_OWNED flag
668a5ddb414c locking/lockdep: Move sanity check to inside lockdep_print_held_locks()
a695da42d3fb locking/lockdep: Use for_each_process_thread() for debug_show_all_locks()
ef8489750d75 locking/qspinlock: Remove duplicate clear_pending() function from PV code
3b8babd16468 locking/qspinlock: Add stat tracking for pending vs. slowpath
a658770c2136 locking/qspinlock: Use try_cmpxchg() instead of cmpxchg() when locking
f7aaae6aa5bd locking/qspinlock: Elide back-to-back RELEASE operations with smp_wmb()
4f6113916171 locking/qspinlock: Use smp_cond_load_relaxed() to wait for next node
ef1ccedb7fde locking/mcs: Use smp_cond_load_acquire() in MCS spin loop
7fe796282fcd locking/qspinlock: Use atomic_cond_read_acquire()
3189d7af838d locking/qspinlock: Kill cmpxchg() loop when claiming lock from head of queue
0b731f36792f locking/qspinlock: Remove unbounded cmpxchg() loop from locking slowpath
278176886798 locking/qspinlock: Bound spinning on pending->locked transition in slowpath
db644014c1db locking/qspinlock: Merge 'struct __qspinlock' into 'struct qspinlock'
8252667599c5 locking/qspinlock: Move __ARCH_SPIN_LOCK_UNLOCKED to qspinlock_types.h
9d0126ffcf58 locking/rwsem: Add DEBUG_RWSEMS to look for lock/unlock mismatches
c29fea0bdf5b lockdep: Make the lock debug output more useful
ced3cc27800b locking/rtmutex: Handle non enqueued waiters gracefully in remove_waiter()
b3be53d98ff2 locking/mutex: Improve documentation
238f29de3c31 rtmutex: Make rt_mutex_futex_unlock() safe for irq-off callsites
1c73cd91d4a2 rcu: Suppress lockdep false-positive ->boost_mtx complaints
b34cbb28464f locking/lockdep: Show unadorned pointers
9999b77f810b locking/qspinlock: Ensure node is initialised before updating prev->next
bc264bd91d87 locking/lockdep: Avoid triggering hardlockup from debug_show_all_locks()
6d9e20d77dd1 lockdep: Make lockdep checking constant
19c115a2d681 lockdep: Assign lock keys on registration
9d1e3aa34cda futex: Avoid violating the 10th rule of futex
89ef7fd27109 locking/lockdep: Remove the cross-release locking checks
b7d08840fd00 locking/core: Remove break_lock field when CONFIG_GENERIC_LOCKBREAK=y
ec6f9623801d locking/core: Fix deadlock during boot on systems with GENERIC_LOCKBREAK
d86ef5c00e3b locking/lockdep: Fix possible NULL deref
01c347d0b55f locking: Remove smp_read_barrier_depends() from queued_spin_lock_slowpath()
040f6c1faa02 locking/pvqspinlock: Implement hybrid PV queued/unfair locks
6c45f309b282 locking/rwlocks: Fix comments
24516be12515 locking: rtmutex: DEFINE_WAKE_Q -> WAKE_Q
a54036c99457 ALSA: seq: Align temporary re-locking with irqsave version
f85f5b5df9f5 ipc: Replace spin_unlock_wait() with lock/unlock pair
9e93ae4d01c9 task_work: Replace spin_unlock_wait() with lock/unlock pair
829fdd7dfbac locking/spinlock: Update spin_unlock_wait() users
a96ed6806755 completion: Replace spin_unlock_wait() with lock/unlock pair
f9dac85ce25e exit: Replace spin_unlock_wait() with lock/unlock pair
cc37e881d089 rcuwait: Annotate task_struct with __rcu
481b29cd547f sched/wait, rcuwait: Fix typo in comment
7caf575e214d sched/wait, RCU: Introduce rcuwait machinery
e40b1699a65b sched/api: Introduce task_rcu_dereference() and try_get_task_struct()
e26fcb38715f init: Kconfig: Don't use imply
99f75e4807ac locking/lockdep: Introduce CONFIG_BOOTPARAM_LOCKDEP_CROSSRELEASE_FULLSTACK=y
da0f1fb08d41 locking/lockdep: Make CONFIG_LOCKDEP_CROSSRELEASE and CONFIG_LOCKDEP_COMPLETIONS truly non-interactive
1f02567793ae locking/lockdep: Rename CONFIG_LOCKDEP_COMPLETE to CONFIG_LOCKDEP_COMPLETIONS
962f58a1d830 locking/lockdep: Make CONFIG_LOCKDEP_CROSSRELEASE part of CONFIG_PROVE_LOCKING
5c9018e9a33f locking/lockdep: Apply crossrelease to completions
dd34ead4abe1 sched/completions: Fix complete_all() semantics
a43570cc7d7f locking/lockdep: Add a boot parameter allowing unwind in cross-release and disable it by default
f5a71bc80ba7 locking/qrwlock: Prevent slowpath writers getting held up by fastpath
75794fe982c6 locking/qrwlock: Use atomic_cond_read_acquire() when spinning in qrwlock
306a307a00e3 locking/qrwlock: Use 'struct qrwlock' instead of 'struct __qrwlock'
33ea898a8c12 locking/qrwlock: Fix write unlock bug on big endian systems
160c2262bd0b locking/core: Remove {read,spin,write}_can_lock()
9e2eb5414fcd locking/rwsem: Add down_read_killable()
3ef30adffdae locking/lockdep: Fix stacktrace mess
439cd2a63743 locking/rtmutex: replace top-waiter and pi_waiters leftmost caching
99f048afff61 locking/pvqspinlock: Relax cmpxchg's to improve performance on some architectures
0de36934c553 locking/lockdep: Untangle xhlock history save/restore from task independence
4fa76eb4be2c locking/lockdep: Fix workqueue crossrelease annotation
5735d600e8aa locking/lockdep: Explicitly initialize wq_barrier::done::map
2ecdffc73102 lockdep: make MAX_LOCKDEP_SUBCLASSES unconditionally visible
61fa3f98f30d locking: Remove spin_unlock_wait() generic definitions
aee423c827fe locking/lockdep: Fix the rollback and overwrite detection logic in crossrelease
ea5650ca7c36 locking/lockdep: Add a comment about crossrelease_hist_end() in lockdep_sys_exit()
fbd1b73c1996 locking/lockdep: Make print_circular_bug() aware of crossrelease
d7c1b199e49d locking/lockdep: Handle non(or multi)-acquisition of a crosslock
c2725f53ba9b locking/lockdep: Detect and handle hist_lock ring buffer overwrite
7a3482c3419c locking/lockdep: Implement the 'crossrelease' feature
de03c1f977b0 locking/lockdep: Make check_prev_add() able to handle external stack_trace
4efb1e004fdc locking/lockdep: Change the meaning of check_prev_add()'s return value
8fde276d3562 locking/lockdep: Add a function building a chain between two classes
91db6e4d7717 locking/lockdep: Refactor lookup_chain_cache()
d14b5098bac4 locking/lockdep: Avoid creating redundant links
29b422aad1bc locking/rwsem-xadd: Add killable versions of rwsem_down_read_failed()
ad794e528061 locking/rwsem-spinlock: Add killable versions of __down_read()
1ac098ef6ccd futex: Allow for compiling out PI support
4af1eabc263a locking/rtmutex: Remove unnecessary priority adjustment
043c641f8bdd locking/qspinlock: Explicitly include asm/prefetch.h
8c1324a17ad5 locking/rwsem-spinlock: Fix EINTR branch in __down_write_common()
afb6d01224f1 locking/rtmutex: Don't initialize lockdep when not required
9719ad7e6fab lockdep: Use consistent printing primitives
f1ac5a7d544d rt_mutex: Add lockdep annotations
a053a8ae952b kernel/locking: Fix compile error with qrwlock.c
ee43070f3d10 futex,rt_mutex: Fix rt_mutex_cleanup_proxy_lock()
d1531aa7429a mutex, futex: adjust kernel-doc markups to generate ReST
c75b73ba84b6 lockdep: teach lockdep about memalloc_noio_save
9fb80128ea8f lockdep: Use "WARNING" tag on lockdep splats
a9a3a9c6eb18 sparc64: Use LOCKDEP_SMALL, not PROVE_LOCKING_SMALL
0972e9045d51 rtmutex: Plug preempt count leak in rt_mutex_futex_unlock()
d07d43148715 rtmutex: Fix more prio comparisons
f3b4eb936836 rtmutex: Fix PI chain order integrity
f1ff8a21c2cc sched/rtmutex: Refactor rt_mutex_setprio()
2f0ceafa21f0 rtmutex: Clean up
77d8701c03a0 sched/deadline/rtmutex: Dont miss the dl_runtime/dl_period update
1833d7bec8e2 sched/rtmutex/deadline: Fix a PI crash for deadline tasks
69955a6bb299 rtmutex: Deboost before waking up the top waiter
6f6f02670363 futex: Drop hb->lock before enqueueing on the rtmutex
0732b41333a2 futex: Rework futex_lock_pi() to use rt_mutex_*_proxy_lock()
a309070e9ebe futex: Pull rt_mutex_futex_unlock() out from under hb->lock
d7b24c387147 futex: Rework inconsistent rt_mutex/futex_q state
4bcee4012fe7 futex: Cleanup refcounting
a1a18e59c2c6 futex: Change locking rules
1cdc9465280e futex: Use smp_store_release() in mark_wake_futex()
6920e470638f futex: Cleanup variable names for futex_top_waiter()
ed93cb655669 futex: Rename barrier references in ordering guarantees
f5aa2de62043 futex: Allow FUTEX_CLOCK_REALTIME with FUTEX_WAIT op
2c1648ad3d6a futex: Cleanup the goto confusion in requeue_pi()
02948f46b458 futex: Remove pointless put_pi_state calls in requeue()
e3ae172d0369 futex: Document pi_state refcounting in requeue code
4516f85f3120 futex: Rename free_pi_state() to put_pi_state()
2875fcc98c5b futex,rt_mutex: Introduce rt_mutex_init_waiter()
fee37caca0dd futex,rt_mutex: Provide futex specific rt_mutex API
ca8fd9a57917 futex: Remove rt_mutex_deadlock_account_*()
1b709dd1bc9e locking/lockdep: Handle statically initialized PER_CPU locks properly
afee1aeb8d61 locking/lockdep: Add new check to lock_downgrade()
91c6a995b669 locking/lockdep: Factor out the validate_held_lock() helper function
8f0debc7705a locking/lockdep: Factor out the find_held_lock() helper function
87109422544c locking/rwsem: Fix down_write_killable() for CONFIG_RWSEM_GENERIC_SPINLOCK=y
5b99438997cd locking/spinlock/debug: Remove spinlock lockup detection code
122cfb2c39c3 lockdep: Fix incorrect condition to print bug msgs for MAX_LOCKDEP_CHAIN_HLOCKS
11e2d6866754 locking/mutex: Fix lockdep_assert_held() fail
779fd119f52f locking/rtmutex: Flip unlikely() branch to likely() in __rt_mutex_slowlock()
9b2f5cf422c5 lockdep: Make RCU suspicious-access splats use pr_err
aa46031af467 locking/rwsem: Reinit wake_q after use
504857d3a720 locking/mutex, sched/wait: Add mutex_lock_io()
aedf27f01bae locking/mutex: Initialize mutex_waiter::ww_ctx with poison when debugging
738ea73983c8 locking/ww_mutex: Optimize ww-mutexes by yielding to other waiters from optimistic spin
0b55a7fa3bdb locking/ww_mutex: Re-check ww->ctx in the inner optimistic spin loop
340e459a9fc7 locking/mutex: Improve inlining
530f672b5831 locking/ww_mutex: Optimize ww-mutexes by waking at most one waiter for backoff when acquiring the lock
ede9cdf50dc6 locking/ww_mutex: Notify waiters that have to back off while adding tasks to wait list
c51b90d7a329 locking/ww_mutex: Add waiters in stamp order
f4fc21d85a89 locking/ww_mutex: Remove the __ww_mutex_lock*() inline wrappers
588fe1af7ec5 locking/ww_mutex: Set use_ww_ctx even when locking without a context
b1a8cd0c8a4d locking/ww_mutex: Extract stamp comparison to __ww_mutex_stamp_after()
468b5c568ccb locking/mutex: Fix mutex handoff
ae0e6b749199 locking/percpu-rwsem: Replace waitqueue with rcuwait
d0338968ad92 sched/core: Remove set_task_state()
669d7c96ca75 kernel/locking: Compute 'current' directly
4a5c5b52ea58 locking/pvqspinlock: Don't wait if vCPU is preempted
20bb36532c95 locking/spinlocks: Remove the unused spin_lock_bh_nested() API
934311586c38 msm: kgsl Rework mutex::owner inside adreno_dispatcher_idle()
2f7a7da08242 locking/barriers, arch/arm64: Implement LDXR+WFE based smp_cond_load_acquire()
8bf7500f464d locking/atomic: Introduce atomic_try_cmpxchg()
a6533905c0b9 locking/atomic, arch/arm64: Implement atomic{,64}_fetch_{add,sub,and,andnot,or,xor}{,_relaxed,_acquire,_release}()
29f5fa01ebe2 locking/mutex: Optimize __mutex_trylock_fast()
588f578a0249 locking/barriers: Introduce smp_cond_load_relaxed() and atomic_cond_read_relaxed()
24e7e1b52679 locking/barriers: Move smp_cond_load_acquire() to asm-generic/barrier.h
4fa255e2efce asm-generic: implement virt_xxx memory barriers
b39aa185307a locking/atomic: Add atomic_cond_read_acquire()
6c61a913fcf1 locking/atomic: Introduce inc/dec variants for the atomic_fetch_$op() API
70a32e13710f locking/atomic: Implement atomic{,64,_long}_fetch_{add,sub,and,andnot,or,xor}{,_relaxed,_acquire,_release}()
5e1e77e88399 locking/atomic: Fix atomic64_relaxed() bits
bd8299840e85 atomics: Add test for atomic operations with _relaxed variants
c56ffc4cfee4 include/asm-generic/atomic-long.h: force inlining of some atomic_long operations
5d5dabdc1bc5 locking/percpu-rwsem: Add DEFINE_STATIC_PERCPU_RWSEMand percpu_rwsem_assert_held()
b524f165fb60 sched/core: Introduce the vcpu_is_preempted(cpu) interface
9b1f9b695915 fs/locks: Replace lg_local with a per-cpu spinlock
d00834e43f86 fs/locks: Replace lg_global with a percpu-rwsem
1eee60c0f364 lockdep: Fix report formatting
0e639469b93a locking/rtmutex: Explain locking rules for rt_mutex_proxy_unlock()/init_proxy_locked()
0ebcac5b3ba2 locking/rtmutex: Get rid of RT_MUTEX_OWNER_MASKALL
0a68dd429917 locking/lockdep: Provide a type check for lock_is_held
a7c9b764dc5d locking/mutex: Break out of expensive busy-loop on {mutex,rwsem}_spin_on_owner() when owner vCPU is preempted
6f96026aab6a locking/osq: Break out of spin-wait busy waiting loop for a preempted vCPU in osq_lock()
c45a9ef4836e lockdep: Limit static allocations if PROVE_LOCKING_SMALL is defined
15d4c92a438f locking/core: Remove cpu_relax_lowlatency() users
be0c26d22292 locking/lockdep: Remove unused parameter from the add_lock_to_list() function
c6f2ab405d1d locking/mutex: Enable optimistic spinning of woken waiter
f19863c960cc locking/mutex: Simplify some ww_mutex code in __mutex_lock_common()
139385798b25 locking/mutex: Restructure wait loop
1c8c53b05a3a locking/mutex: Add lock handoff to avoid starvation
0f250823885f locking/mutex: Rework mutex::owner
cb5e29b84678 locking/lglock: Remove lglock implementation
c6388c213748 locking/pv-qspinlock: Use cmpxchg_release() in __pv_queued_spin_unlock()
14ce46001bf8 locking/rwsem: Scan the wait_list for readers only once
249e9cf14d16 locking/rwsem: Remove a few useless comments
ef2e29e4b712 locking/rwsem: Return void in __rwsem_mark_wake()
cecbc9144eed locking/pvstat: Separate wait_again and spurious wakeup stats
ce9f9fdbe57c locking/qspinlock: Improve readability
27c8436ad191 locking/pvqspinlock: Fix a bug in qstat_read()
cbd01c4d665c locking/pvqspinlock: Fix double hash race
b987ae44360f locking/qspinlock: Use __this_cpu_dec() instead of full-blown this_cpu_dec()
6ee8a7d35675 locking/atomic, arch/rwsem: Employ atomic_long_fetch_add()
01c62e57f6bb locking/atomic, arch/qrwlock: Employ atomic_fetch_add_acquire()
6111a42652e7 locking/atomic: Remove the deprecated atomic_{set,clear}_mask() functions
58e028f08117 locking/barriers: Introduce smp_acquire__after_ctrl_dep()
f7b6d1361d6e locking/barriers: Replace smp_cond_acquire() with smp_cond_load_acquire()
1cfb9ac6002a locking/csd_lock: Use smp_cond_acquire() in csd_lock_wait()
98d464970eb6 locking/csd_lock: Explicitly inline csd_lock*() helpers
900861ac8c97 locking/rwsem: Streamline the rwsem_optimistic_spin() code
d9ead2decb29 locking/rwsem: Improve reader wakeup code
2fbf4112a818 locking/rwsem: Protect all writes to owner by WRITE_ONCE()
730245e34f04 locking/rwsem: Add reader-owned state to the owner field
4a868f379cfc locking/rwsem: Convert sem->count to 'atomic_long_t'
914b77628b03 locking/qspinlock: Add comments
8d48e344fe20 locking/qspinlock: Clarify xchg_tail() ordering
670b5913e9e8 locking/rtmutex: Only warn once on a trylock from bad context
15b9a862e6a7 locking/lockdep: Use __jhash_mix() for iterate_chain_key()
ed9621a9664f locking/mutex: Set and clear owner using WRITE_ONCE()
1ea6d29d1ea2 locking/rwsem: Optimize write lock by reducing operations in slowpath
5fdc683c240b locking/rwsem: Rework zeroing reader waiter->task
7c8e37e307b4 locking/rwsem: Enable lockless waiter wakeup(s)
ab2bd0b8cadf add down_write_killable_nested()
0ee68cb3166e locking/rwsem: Fix down_write_killable()
335f9200843d locking/pvqspinlock: Robustify init_qspinlock_stat()
f0398a71ad0a locking/pvqspinlock: Avoid double resetting of stats
5e03579a2d95 lcoking/locktorture: Simplify the torture_runnable computation
69b4d9d3f900 lockdep: Fix lock_chain::base size
3f14062a1fb8 locking/lockdep: Fix ->irq_context calculation
f223e9d193b9 locking/rwsem: Provide down_write_killable()
1886f2673c70 locking/pvqspinlock: Fix division by zero in qstat_read()
05429a6c2018 locking/rwsem: Introduce basis for down_write_killable()
92c3a7be9068 locking/rwsem: Get rid of __down_write_nested()
c5b8b04ffc35 locking/lockdep: Deinline register_lock_class(), save 2328 bytes
af81957ddc91 locking/locktorture: Fix deboosting NULL pointer dereference
d201dedca8cb locking/lockdep: Fix print_collision() unused warning
061276144e91 locking/lockdep: Print chain_key collision information
99e0011d0763 tags: Fix DEFINE_PER_CPU expansions
df0fb9d13542 locking/lockdep: Detect chain_key collisions
402a9e792335 locking/lockdep: Prevent chain_key collisions
0db92dc85634 locking/pvqspinlock: Enable slowpath locking count tracking
790477a89468 locking/qspinlock: Use smp_cond_acquire() in pending code
1d1fc1d9aef8 locking/pvqspinlock: Move lock stealing count tracking code into pv_queued_spin_steal_lock()
b142e99719db locking/lockdep: Eliminate lockdep_init()
d8d1b6ac6d9c locking/lockdep: Convert hash tables to hlists
a387253adaf4 locking/lockdep: Fix stack trace caching logic
62ed3976547e rtmutex: Make wait_lock irq safe
bb2dc6bb2806 locking/pvqspinlock: Queue node adaptive spinning
be06a4c45ec3 locking/pvqspinlock: Allow limited lock stealing
1d8935548ec6 locking/pvqspinlock: Collect slowpath lock statistics
4d6b5e8c50a6 locking/pvqspinlock, x86: Optimize the PV unlock code path
29e23bca8ff5 locking/qspinlock: Avoid redundant read of next pointer
2a7338ae7d98 locking/qspinlock: Prefetch the next node cacheline
ed43996d4762 locking/qspinlock: Use _acquire/_release() versions of cmpxchg() & xchg()
8a0057af7043 posix-timers: Use spin_lock_irq() in itimer_delete()
b5772c89c31d sched/core: Unify p->on_rq updates
23ef5d570030 sched/core: Use load_avg for selecting idlest group
9babb5e270bb sched/fair: Push rq lock pin/unpin into idle_balance()
13424d41afa6 sched/fair: update_rq_clock after nr_running check in load balance path
2641f02328ad sched: Fix assert_clock_updated warning emitted during CPU isolation
50bd9229c65c sched/fair: Add missing update_rq_clock() call while pushing task
e5fd1d4cf3a3 Revert "sched/fair: Fix PELT integrity for new groups"
f547a4886ea8 sched: rt: Fix CAF mismerge of 8623286 and ec888d4
18dd38d380b9 sched: deadline: Fix CAF mismerge of 8623286 and ec888d4
f6c0dcf2ea7b sched/deadline: Add missing update_rq_clock() in dl_task_timer()
e568285f4c24 sched/deadline: Fix the intention to re-evalute tick dependency for offline CPU
c9f1d8becbcc sched/deadline: Fix lock pinning warning during CPU hotplug
ef089218e7b2 genirq: Avoid summation loops for /proc/stat
ae86e420c70c genirq: Robustify handle_percpu_devid_irq()
2738d21947b3 sched: core: Fix yet another CAF mismerge of 8623286 and ec888d4
bb0285b80f59 hrtimer: Use irqsave/irqrestore around __run_hrtimer()
32281f8d70f1 sched/core: Add missing update_rq_clock() call in sched_move_task()
6e0c788cdd6d sched/core: Make sched_ttwu_pending() atomic in time
15f617e9c352 stop_machine: Remove stop_cpus_lock and lg_double_lock/unlock()
36dc92d0f9a3 stop_machine: Use raw spinlocks
f94a104d70ac kernel: sched: Add missing ENQUEUE_NOCLOCK flag in set_user_nice()
722116481148 sched/core: Introduce set_next_task() helper for better code readability
2b5e1612b285 sched/core: Fix rq lock pinning warning after call balance callbacks
be7497e2ffc8 sched: core: Update migration_call() to latest changes
6431456de2bd sched: fair: Add update_rq_clock before __update_cpu_load
5ab55fdbe1c3 sched/fair: Update rq clock before changing a task's CPU affinity
1b48e2d0a20f sched: core: Add missed ENQUEUE_NOCLOCK flag
2c27be9f9ace sched: fair: Remove double_(un)lock_balance fuckery from CAF
9561ddcd1556 Revert "sched: Fix racy invocation of fixup_busy_time via move_queued_task"
8e005739d20c sched/core: Fix double update_rq_clock) calls in attach_task()/detach_task()
de74a29122a6 sched/core: Add rq->lock wrappers
0693eac14182 sched/core: Fix update_rq_clock() splat on hotplug (and suspend/resume)
fb13b54f44a8 sched/fair: Restore previous rq_flags when migrating tasks in hotplug
723da4f8c995 sched/cfs: Make util/load_avg more stable
d98b5e2b842b sched/fair: Simplify wake_affine() for the single socket case
c9a0eee3f541 sched: tune: Convert locking to rq_flags
2a65272abff6 sched/deadline: Update rq_clock of later_rq when pushing a task
46b0cb75ff9b sched: deadline: Fix another CAF mismerge of 8623286 and ec888d4
883eedc741ac sched/core: Add {EN,DE}QUEUE_NOCLOCK flags
f46034e9b34c sched/core: Add WARNING for multiple update_rq_clock() calls
c59c3e141243 sched/core: Simplify helpers for rq clock update skip requests
217c967305b0 sched/rq_clock: Consolidate the ordering of the rq_clock methods
a3b847964a45 sched/core: Avoid double update_rq_clock() in move_queued_task()
790810275cdb sched/core: Simplify update_rq_clock() in __schedule()
5aa703058fc3 sched/deadline: Make update_curr_dl() more accurate
c4601a93c4f0 sched/core: Avoid obvious double update_rq_clock()
2c292c831d1e sched/core: Add debugging code to catch missing update_rq_clock() calls
c18f6e298bd7 sched/core: Add wrappers for lockdep_(un)pin_lock()
cad3929a741f locking/lockdep, sched/core: Implement a better lock pinning scheme
1befbdbf1ed5 sched/core: Introduce 'struct rq_flags'
6abdc6d95094 sched/core: Reset RQCF_ACT_SKIP before unpinning rq->lock
4ebcaf001872 sched: rt: fix CAF mismerge of 8623286277c31443d38a024de85adab973498664 and ec888d46d8993b2bf205ed375e538a3819c23659
1d096e4f3ea0 arm64: arch_timer: simplify accessors
9618ad972d73 ANDROID: binder: correct the cmd print for BINDER_WORK_RETURN_ERROR
186f32c81ec6 binder: fix incorrect cmd to binder_stat_br
3542c6820248 ANDROID: sched/fair: correct pelt load information in sched-pelt.h
6bf91078adc3 FROMLIST: sched/fair: add support to tune PELT ramp/decay timings
662d5eaa1dfc sched/fair: Move the PELT constants into a generated header
75720d8f8df2 sched/fair: Fix comments
36a198b0499d sched/fair: Fix corner case in __accumulate_sum()
73e7e6b488e1 sched/fair: Optimize ___update_sched_avg()
ee71341dee4c sched/fair: Optimize sum computation with a lookup table
6231093b0b46 sched/fair: Explicitly generate __update_load_avg() instances
a88cf772b3cb BACKPORT: sched/fair: Fix cpu_util_wake() for 'execl' type  workloads
02d3beeb1856 sched/fair: Update util_est only on util_avg updates
5c9961aecd54 sched/fair: Use util_est in LB and WU paths
05a77e31ba30 Revert "sched/fair: Optimize sum computation with a lookup table"
d76c6ff58c4d Revert "sched/fair: Explicitly generate __update_load_avg() instances"
845b0359f844 Revert "sched/fair: Optimize ___update_sched_avg()"
bb903f33f070 Revert "sched/fair: Fix corner case in __accumulate_sum()"
9c7e6d201437 Revert "sched/fair: Fix comments"
6c8b0ea28107 Revert "sched/fair: Move the PELT constants into a generated header"
d49d171d8675 Revert "FROMLIST: sched/fair: add support to tune PELT ramp/decay timings"
5a7dc62e143e Revert "ANDROID: sched/fair: correct pelt load information in sched-pelt.h"
387a1e234e30 Revert "ANDROID: sched/fair: Cleanup cpu_util{_wake}()"
4e36b2a6a2ab Revert "BACKPORT: sched/fair: Use util_est in LB and WU paths"
7385cb8da99b Revert "BACKPORT: sched/fair: Update util_est only on util_avg updates"
efec35af5c18 Revert "BACKPORT: sched/fair: Fix cpu_util_wake() for 'execl' type workloads"
6420ddc1e690 sched/fair: Don't push cfs_bandwith slack timers forward
166c64f2fd79 sched/fair: Make sync_entity_load_avg() and remove_entity_load_avg() static
d5b5069c6333 sched/fair: Don't increase sd->balance_interval on newidle balance
c03a1e82f813 sched/fair: Fix bandwidth timer clock drift condition
10b8c9ceab8f sched/fair: Advance global expiration when period timer is restarted
71ebaf56c3e2 sched/core: Fix preempt warning in ttwu
a87cb784508f sched/core: Optimize try_to_wake_up() for local wakeups
a09e7a375db2 sched/core: Add __sched tag for io_schedule()
9999a6c8aa4e sched: Factor out nr_iowait and nr_iowait_cpu
ca338f6831de sched/core: Use READ_ONCE()/WRITE_ONCE() in move_queued_task()/task_rq_lock()
35f8ff6180b4 sched: set number of iterations to h_nr_running
8980e06020de sched/rt: Make update_curr_rt() more accurate
cb9b8ea7023d cpuidle: lpm-levels: Add back clock_debug_print_enabled
115fd474f97c sched/fair, cpumask: Export for_each_cpu_wrap()
57b70c63d595 sched/topology: Fix building of overlapping sched-groups
996336c6ee65 sched/core: Get rid of 'cpu' argument in wq_worker_sleeping()
ae84ae01d204 sched/core / kcov: avoid kcov_area during task switch
e558b9a70153 sched/core: Fix incorrect utilization accounting when switching to fair class
6d1d168ce41b nmi_backtrace: generate one-line reports for idle cpus
99848f60cf2b FROMLIST: sched/fair: Change prefer_sibling type to bool
081183f9213e sched/fair: Fix CPU capacity updates in update_cpu_capacity()
12abbef816e1 sched: ignore task_h_load for CPU_NEWLY_IDLE
f471ff5f5508 sched/fair: Remove 'cpu_busy' parameter from update_next_balance()
c8ce25cedbd5 sched: set loop_max after rq lock is taken
a635d9d076ee sched: check pinned tasks before balance
bc299eea39a6 UPSTREAM: sched/fair: Fix FTQ noise bench regression
3bfde53495b4 PM / QoS: Fix memory leak on resume_latency.notifiers
af08a8069274 cpuidle: menu: Avoid overflows when computing variance
2e5adca9d69c cpuidle: menu: Remove get_loadavg() from the performance multiplier
e4494deac167 cpu: clean up register_cpu func
8d9bce09d502 cpuidle: menu: help gcc generate slightly better code
fea9134dc2ee cpuidle: menu: avoid expensive square root computation
25368ad8d726 cpuidle: menu: Avoid pointless checks in menu_select()
5e2af52444fd cpuidle: Avoid assignment in if () argument
0d04bd560d60 cpuidle: Clean up cpuidle_enable_device() error handling a bit
24f46e0a3732 cpuidle: Fix idle time tracking
bd38209c0ff1 sched/clock: Remove watchdog touching
1034d7aabc63 sched/clock: Remove unused argument to sched_clock_idle_wakeup_event()
aa4332495840 cpuidle: Fix last_residency division
d939ee0a351f cpuidle: Replace ktime_get() with local_clock()
a3d72d52a058 drivers: cpu-idle: lpm-levels: Use cpuidle disable sysfs
9a0826cdec61 msm: vidc: Avoid information leak while accessing the packet
743677008c54 msm: vidc: Add checks to avoid OOB access
b09b24731a79 BACKPORT: thermal: core: using power_efficient_wq for thermal worker
86c2a0272ea4 Treewide: Fix uninitialized warnings
7118a7aabc16 kernel: Fix massive cpufreq stats memory leaks
899611579640 cgroup: Add generic cgroup subsystem permission checks
4598425318e7 cpufreq: Remove uid_cpupower_enable check
9ff25a1065c6 cpufreq: stats: Fix uninitialized variable
5200b0e8f761 kernel: initialize and free cpufreq stats properly
3d2b81a14c0d cpufreq: stats: use seq iterator for large uid-related files
59f4b0479a11 cpufreq: stats: update uid data in acct_update_power
62492239146d ANDROID: cpufreq: change uid_cpupower to use u32
71259da4991c STOPSHIP: ANDROID: cpufreq: concurrent_*_time P/H experiment
63195b1b0731 ANDROID: cpufreq: Remove seq_printf from critical path
82df81785cf8 ANDROID: cpufreq: update conditions for recording cputime
e437bc55e9e0 ANDROID: cpufreq: uid_concurrent_policy_time
eef1ac7f37ad ANDROID: cpufreq: uid_concurrent_active_time
c17af82377fe ANDROID: cpufreq: concurrent_policy_time by pid
78fa2b1e00a7 ANDROID: cpufreq: concurrent_active_time by pid
00e5f530243c ANDROID: cpufreq: Add time_in_state to /proc/uid directories
dda567969bc8 ANDROID: cpufreq: stats: Fix dead stats clearing timing
dcae25c03472 ANDROID: cpufreq: stats: Fix sleeping while atomic in cpufreq_task_stats_init
e325c5409b55 ANDROID: cpufreq: stats: Fix NULL policy scenarios
226922e83364 ANDROID: cpufreq: stats: add per task/uid/freq/cluster stats
b2c694c97bbc cpufreq: Remove cpufreq_times from CAF
2aecabb10148 sched: tune: Inline css_st with Wahoo merge
c1906f514d9c sched: tune: Unconditionally allow attach
6d0693b87a02 sched/tune: fix tracepoint location
84dec802330b sched/tune: allow negative cpu boosts
79ce6a4e3e77 sched/debug: Fix SCHED_WARN_ON() to return a value on !CONFIG_SCHED_DEBUG as well
85cb6789ac7c sched/debug: Add SCHED_WARN_ON()
46fe971d402a sched/fair: Fix insertion in rq->leaf_cfs_rq_list
85bd466d9a98 sched/fair: Add tmp_alone_branch assertion
e45cb4ba7889 sched/fair: Plug hole between hotplug and active_load_balance()
5184ad394a50 sched/fair: Avoid newidle balance for !active CPUs
81f6aa099352 sched/topology, cpuset: Avoid spurious/wrong domain rebuilds
3112c4ced75b sched/pelt: Skip updating util_est when utilization is higher than CPU's capacity
8bfb9368e1a0 sched/fair: Optimize update_blocked_averages()
a565836d3121 sched/util_est: Fix util_est_dequeue() for throttled cfs_rq
306437a9fa40 sched/fair: Implement synchonous PELT detach on load-balance migrate
f999850d6a53 sched/fair: Fix PELT integrity for new groups
48de076e6a36 arm/topology: link arch_scale_min_freq_capacity to cpufreq
f5bddbb016b8 arm64/topology: link arch_scale_min_freq_capacity to cpufreq
edd2e545eda7 cpufreq: add scaled minimum capacity tracking for policy changes
3afa74682a0e arm64: enable max frequency capping
0e619798bf62 arm: enable max frequency capping
4d1411e1731f cpufreq: implement max frequency capping
546ad843e7a8 cpufreq: remove max frequency capping from scale_freq_capacity()
561c8f08e8a2 Revert "ANDROID: cpufreq: Max freq invariant scheduler load-tracking and cpu capacity support"
a5dee4fccd43 Revert "ANDROID: arm: Enable max freq invariant scheduler load-tracking and capacity support"
86b32bda8e1b Revert "ANDROID: arm64: Enable max freq invariant scheduler load-tracking and capacity support"
4f79cf09777e ANDROID: cpufreq: provide default frequency-invariance setter function
19d3ac2d4470 qcom-cpufreq: Notify the current frequency to the topology driver
40caad28de8c Revert "cpufreq: qcom: Remove tracing"
071110410dcc ANDROID: arm64: topology: Parse and store cpu efficiency values from dt
f1cad94ccbb0 msm: kgsl: Fix drawqueue timer race condition
3afcb65a1643 msm: kgsl: Omit referencing pointers in traces
1f4b6eea624b NFC: Fix device node probing issue
1aa43b5cee99 sysctl: promote sched_migration_cost_ns out of CONFIG_SCHED_DEBUG
b090c5d4770d sched/rt: Restore rt_runtime after disabling RT_RUNTIME_SHARE
ac776fd12065 arm64: arch_timer: Save cntkctl_el1 as a per-cpu variable
9a848ad59af3 arm_arch_timer: Expose event stream status
4f6f5436b58b NFC: Add recovery mechanism for i2_master_recv error
d1eb81ba46bc NFC: Remove PMIC clock voting from HLOS
c5f0a9c99d7e qseecom: improve app_block_wq processing
4449176cf486 qseecom: use wait_event_interruptible
631ff3127e7a Revert "cpufreq: schedutil: Ignore CPU load older than WALT window size"
a9da034b35ef Revert "cpufreq: schedutil: Avoid unnecessary kthread wakeup"
4194503f7e14 Revert "schedutil: Don't assume we are likely using PELT"
2ae52d8274b2 FROMLIST: sched: force update of blocked load of idle cpus
6990538486a5 sched/pelt: Fix false running accounting
314cfb5a71c3 ANDROID: sched/fair: correct pelt load information in sched-pelt.h
e3fd73d89e44 BACKPORT: sched/fair: Fix cpu_util_wake() for 'execl' type workloads
a429007eefaa ANDROID: sched/fair: initialise util_est values to 0 on fork
69c996b37448 ANDROID: sched/fair: schedtune: update before schedutil
9c5c74782830 Revert "ANDROID: Move schedtune en/dequeue before schedutil update triggers"
6adb50072aa9 FROMLIST: sched/fair: add support to tune PELT ramp/decay timings
8646b8fab4da BACKPORT: sched/fair: Update util_est before updating schedutil
cd5a62b29857 BACKPORT: sched/fair: Update util_est only on util_avg updates
54dcab5fc6b9 BACKPORT: sched/fair: Use util_est in LB and WU paths
adf6d34f37e2 BACKPORT: sched/fair: Add util_est on top of PELT
94688d7053d1 ANDROID: sched/fair: Cleanup cpu_util{_wake}()
0a827c82e3d7 ANDROID: sched/fair: unify spare capacity calculation
372ad23fec9c ANDROID: sched/fair: fix CPU selection for non latency sensitive tasks
5909df430ada sched/fair: Move the PELT constants into a generated header
73a78bffa463 sched/fair: Increase PELT accuracy for small tasks
884bbc59c218 sched/fair: Fix comments
e2fad7c255fe sched/Documentation: Add 'sched-pelt' tool
2b7d0ad0fff2 sched/fair: Fix corner case in __accumulate_sum()
2b6d73b0ecbd sched/fair: Optimize ___update_sched_avg()
dda149dea6f2 sched/fair: Explicitly generate __update_load_avg() instances
b46bfb40ac73 sched/fair: Optimize sum computation with a lookup table
4e451ec8e87d Revert "compiler: allow all arches to enable CONFIG_OPTIMIZE_INLINING"
bdea66534bf5 seq_file: allocate seq_file from kmem_cache
5ceeaef30ee8 ASoC: msm-cpe-lsm: Fix out of bounds write in msm_cpe_lsm_ioctl_compat
ec4154b0c917 sched: fair: Add strict skip buddy support
b31a6b235c06 cpuset: Restore tasks affinity while moving across cpusets
0a147b12f2d1 sched/fair: Improve no-hz idle balance kicking in misfit task scenario
541663a70c3d sched: Don't update idle_cpus_mask during core isolation
5cedb2e6abbf sched: fair: avoid little cpus due to sync, prev_bias
1d5bf1563a08 ANDROID: sched/fair: if sync flag ignored, try to place in same cluster
229a5a1d3e75 BACKPORT: sched/fair: remove sync logic from select_energy_cpu_brute
4bd18a147b6b sched: Use capacity_orig_of instead of capacity_of in overutilized function
fa46a4f0d95a sched/fair: vruntime should normalize when switching from fair
7dfd6bc79677 sched/fair: honor sync only if CPU is about to goto idle
ff51bb7a9081 sched/fair: Make tick path active migration more robust
16ff705561b9 ANDROID: update_group_capacity for single cpu in cluster
c83e5e2b575d ANDROID: sched/fair: add idle state filter to prefer_idle case
162cba90e77e ANDROID:sched/fair: prefer energy efficient CPUs for !prefer_idle tasks
9f3adf32a53d ANDROID: sched/fair: remove order from CPU selection
224420f4aa51 Revert "ANDROID: sched/fair: prefer energy efficient CPUs for !prefer_idle tasks"
a3198b1fe3c9 Revert "ANDROID: sched/fair: remove order from CPU selection"
f52943cd3036 Revert "ANDROID: sched/fair: add idle state filter to prefer_idle case"
3385f21f4900 Revert "ANDROID: update_group_capacity for single cpu in cluster"
f6fd264680b2 schedutil: Down up_rate_limit to default
8fb9c7946140 Treewide: Fix constant pointer declaration
85081cfeadbc Revert "f_fs: set maxburst to one before enabling endpoints"
872e7cfeb894 usb: gadget: f_fs: Fix possibe deadlock
409eb0b1564d diag: Fix diag msg mask buffer overflow issue
2fe9068d7d77 ANDROID: sched/walt: make walt_ktime_suspended __read_mostly
bc765d4c0ba3 msm: kgsl: Mark dispatcher thread as performance-critical
b1b2caa6bb80 msm: kgsl: Dispatch commands using a master kthread
4886fd46bb86 Revert "msm: kgsl: Dispatch commands using a master kthread"
b90e3fe4b59e Revert "msm: kgsl: Mark dispatcher thread as performance-critical"
a6ce3442014e cpufreq: Simplify cpufreq_can_do_remote_dvfs()
342ffd963163 cpufreq: Process remote callbacks from any CPU if the platform permits
f9a504e4ff77 sched/cpufreq: Fix kobject memleak
e5346dee08f2 cpufreq: schedutil: Lower up_rate_limit_us and disable iowait boost
ab6a9787d693 cpufreq: schedutil: Avoid missing updates for one-CPU policies
9cd28d1f00b2 cpufreq: Rename cpufreq_can_do_remote_dvfs()
3a3dadfeafdf Revert "cpufreq: schedutil: Don't restrict kthread to related_cpus unnecessarily"
f4a404e6bb64 sched/cpufreq/schedutil: Fix error path mutex unlock
deac2e7ec59f sched/cpufreq: Remove unused SUGOV_KTHREAD_PRIORITY macro
ce398530f789 cpufreq: schedutil: Use idle_calls counter of the remote CPU
6efab4dfa601 sched/cpufreq: Don't pass flags to sugov_set_iowait_boost()
8d56acf33e40 cpufreq: schedutil: Examine the correct CPU when we update util
91e0d61bb6f0 cpufreq: schedutil: Always process remote callback with slow switching
cfc9786b2605 cpufreq: schedutil: Don't assume CPU of util update calls
00ebed553b48 cpufreq: schedutil: Don't restrict kthread to related_cpus unnecessarily
a48454e8665f sched: cpufreq: Allow remote cpufreq callbacks
dedb29b7fb53 cpufreq: schedutil: Hard-code rate-limit thresholds
926b0aa61c36 cpufreq: schedutil: Only apply single core busy logic with PELT
028a3bc66478 cpufreq: schedutil: Switch from sprintf to scnprintf
64f184905c8c cpufreq: schedutil: Avoid unnecessary kthread wakeup
167c5a3dcba3 cpufreq: schedutil: Ignore CPU load older than WALT window size
1e956a5bcfa7 BACKPORT: cpufreq: Call cpufreq_disable_fast_switch() in sugov_exit()
302edca09d7b BACKPORT: cpufreq: schedutil: Avoid using invalid next_freq
730128963413 cpufreq: schedutil: Don't set next_freq to UINT_MAX
9c78496ee84c schedutil: Allow cpufreq requests to be made even when kthread kicked
a6a35861b3a8 cpufreq: schedutil: Fix iowait boost reset
db0558e22b49 BACKPORT: cpufreq: Return 0 from ->fast_switch() on errors
6492cad99ad6 cpufreq: schedutil: Fix sugov_start versus sugov_update_shared race
505be9006b5b BACKPORT: cpufreq: schedutil: Cache tunables on governor exit
e1b278870309 schedutil: Don't assume we are likely using PELT
8b89fba6de83 cpufreq: schedutil: Use >= when aggregating CPU loads in a policy
ffa7b5a3d20a FROMLIST: sched: Make iowait_boost optional in schedutil
87c2a18a3eb9 schedutil: Reset to clean state
28a99b641372 cpufreq: Drop redundant check from cpufreq_update_current_freq()
da59e1416e26 cpufreq: Avoid false-positive WARN_ON()s in cpufreq_update_policy()
5fdee033455e cpufreq: simplified goto out in cpufreq_register_driver()
5da9299eca14 cpufreq: governor: CPUFREQ_GOV_LIMITS never fails
1449d957f62f cpufreq: Rearrange __cpufreq_driver_target()
54a019ded331 cpufreq: Use clamp_val() in __cpufreq_driver_target()
0b77aa80422e cpufreq: Send START policy notification after sending CREATE
5143c53b862a cpufreq: Fix clamp_val() usage in cpufreq_driver_fast_switch()
d2fb4ea251d3 cpufreq: Abort cpufreq_update_current_freq() for cpufreq_suspended set
3d4fb67f8078 cpufreq: Support for fast frequency switching
d1da08525c70 cpufreq: Always update current frequency before startig governor
13a4e809ca94 cpufreq: Introduce cpufreq_start_governor()
475df38ac587 cpufreq: Rename __cpufreq_governor() to cpufreq_governor()
3c17ab57d04d cpufreq: Introduce cpufreq_update_current_freq()
d7e98fc0a525 cpufreq: Make cpufreq_quick_get() safe to call
4f11f5751658 Revert "cpufreq: Drop rwsem lock around CPUFREQ_GOV_POLICY_EXIT"
f3fd5fd21e93 cpufreq: Remove 'policy->governor_enabled'
ed2c2f733b4e cpufreq: Relocate handle_update() to kill its declaration
30da741d8804 cpufreq: Call __cpufreq_governor() with policy->rwsem held
0c3dc06d786f cpufreq: Merge cpufreq_offline_prepare/finish routines
2ca70e84b7e5 cpufreq: Fix kobject memleak
be8dd45aff3a Revert "cpufreq: postfix policy directory with the first CPU in related_cpus"
da8bbb9b2bb3 cpufreq: Rename cpufreq_can_do_remote_dvfs()
233dcc9b14d0 cpufreq: schedutil: Always process remote callback with slow switching
d9d64b6b62f5 sched: cpufreq: Allow remote cpufreq callbacks
073687c4fcc8 cpufreq: governor: Create cpufreq_policy_apply_limits()
0adf70fb3a08 cpufreq: governor: Remove unnecessary bits from print message
aaefd52fb14b cpufreq: governor: Fix handling of special cases in dbs_update()
a5a4750e0b76 cpufreq: governor: Change confusing struct field and variable names
4c71ea87ceb4 cpufreq: governor: Fix prev_load initialization in cpufreq_governor_start()
e6c20e6a6497 Revert "cpufreq: governor: Fix negative idle_time when configured with CONFIG_HZ_PERIODIC"
7cb1a02ec33e cpufreq: governor: New data type for management part of dbs_data
1d9758b7bc35 cpufreq: governor: Always schedule work on the CPU running update
907f85199560 cpufreq: governor: Drop unnecessary checks from show() and store()
4347f2249869 cpufreq: governor: Fix race in dbs_update_util_handler()
6b400fbeefbf cpufreq: governor: Make gov_set_update_util() static
4f090d5f16b6 cpufreq: governor: Narrow down the dbs_data_mutex coverage
c58f419ff5a2 cpufreq: governor: Make dbs_data_mutex static
b2617da8a33f cpufreq: governor: Move per-CPU data to the common code
f4f2e68bd966 cpufreq: governor: Drop unused governor callback and data fields
fcbe2594062a cpufreq: governor: Make governor private data per-policy
e42389f083d0 cpufreq: governor: Fix CPU load information updates via ->store
74a64b2285b6 cpufreq: governor: Add a ->start callback for governors
0865441b3aba cpufreq: governor: Move io_is_busy to struct dbs_data
ad0ebb4e8873 cpufreq: governor: Close dbs_data update race condition

   * packages/apps/Recorder/
c74af6a overlay: Use dp instead of sp on timer tick
6586a41 Keep overlay always dark
e4765ae ScreencastService: Update notification immediately after recording started
5467cfc OverlayService: Hide when starting recording, if not overlay should not be displayed
a3ba553 Fix inline build
fc9f85b Revert "Android studio import"
c28df9e Android studio import
f9d51c4 Improve error handling and some code
acc6ec7 Prevent miss-clicks on views

====================
     09-02-2019
====================


   * device/xiaomi/translations/
5702263 move ru translations to fwb [1/2]

   * frameworks/base/
28eaf291c27 make some strings untranslatable
aaa0cd2bdf0 move ru translations to fwb [2/2]
e19df829405 fix aapt2 warnings
54c8606e2fe Fix binder leakage when turning off Bluetooth
3cf47e8298b longshot: set timeout to 1,8 sec
ae6032cccef SystemUI: Q clock: update polish translation

   * kernel/xiaomi/msm-4.4/
4c71ea87ceb4 cpufreq: governor: Fix prev_load initialization in cpufreq_governor_start()
e6c20e6a6497 Revert "cpufreq: governor: Fix negative idle_time when configured with CONFIG_HZ_PERIODIC"
7cb1a02ec33e cpufreq: governor: New data type for management part of dbs_data
1d9758b7bc35 cpufreq: governor: Always schedule work on the CPU running update
907f85199560 cpufreq: governor: Drop unnecessary checks from show() and store()
4347f2249869 cpufreq: governor: Fix race in dbs_update_util_handler()
6b400fbeefbf cpufreq: governor: Make gov_set_update_util() static
4f090d5f16b6 cpufreq: governor: Narrow down the dbs_data_mutex coverage
c58f419ff5a2 cpufreq: governor: Make dbs_data_mutex static
b2617da8a33f cpufreq: governor: Move per-CPU data to the common code
f4f2e68bd966 cpufreq: governor: Drop unused governor callback and data fields
fcbe2594062a cpufreq: governor: Make governor private data per-policy
e42389f083d0 cpufreq: governor: Fix CPU load information updates via ->store
74a64b2285b6 cpufreq: governor: Add a ->start callback for governors
0865441b3aba cpufreq: governor: Move io_is_busy to struct dbs_data
ad0ebb4e8873 cpufreq: governor: Close dbs_data update race condition
aa8d3b70ff26 cpufreq: governor: Use microseconds in sample delay computations
a99dfb8b3d63 cpufreq: governor: Drop unused macros for creating governor tunable attributes
6a34ed9dc298 cpufreq: governor: Create generic macro for common tunables
2880aa644909 cpufreq: governor: Move rate_mult to struct policy_dbs
2b931a7275b0 cpufreq: governor: Reset sample delay in store_sampling_rate()
83f6dc766ec5 cpufreq: governor: Get rid of the ->gov_check_cpu callback
7761f2ac4f75 cpufreq: Remove cpufreq_governor_lock
320e861bda2e cpufreq: governor: Clean up load-related computations
c93dec0144bc cpufreq: governor: Fix nice contribution computation in dbs_check_cpu()
4adf4cb38513 cpufreq: governor: Avoid atomic operations in hot paths
c219b01907b0 cpufreq: governor: Simplify gov_cancel_work() slightly
330809f52b1d cpufreq: governor: Avoid irq_work_queue_on() crash on non-SMP ARM
59b9459035f6 cpufreq: conservative: Update sample_delay_ns immediately
c056107dc755 cpufreq: governor: No need to manage state machine now
056759237bb8 cpufreq: governor: Create and traverse list of policy_dbs to avoid deadlock
921a0122da82 cpufreq: governor: New sysfs show/store callbacks for governor tunables
50ef5a27c94e cpufreq: governor: Move common tunables to 'struct dbs_data'
3320202691f6 cpufreq: governor: Drop pointless goto from cpufreq_governor_init()
f0c254bfd04c cpufreq: governor: Rename skip_work to work_count
9935982d5268 cpufreq: governor: Symmetrize cpu_dbs_info initialization and cleanup
87d680d1a462 cpufreq: governor: Rearrange governor data structures
764bd725d201 cpufreq: governor: Simplify cpufreq_governor_limits()
587d2c672d59 cpufreq: governor: Drop cpu argument from dbs_check_cpu()
364fdb0a3777 cpufreq: governor: Rename cpu_common_dbs_info to policy_dbs_info
bbb962522a71 cpufreq: governor: Drop the gov pointer from struct dbs_data
aa403192ad7a cpufreq: governor: Rework cpufreq_governor_dbs()
e929eb8c9134 cpufreq: governor: Rename some data types and variables
8a9d3f1b639d cpufreq: governor: Put governor structure into common_dbs_data
11324d1769ff cpufreq: governor: Avoid passing dbs_data pointers around unnecessarily
6b9feaeb0876 cpufreq: governor: Use common mutex for dbs_data protection
39229a1bf005 cpufreq: governor: Replace timers with utilization update callbacks
92754f951207 cpufreq: governor: Fix negative idle_time when configured with CONFIG_HZ_PERIODIC
fd56be0a2085 cpufreq: governor: Use lockless timer function
c0c429adb00a cpufreq: governor: replace per-CPU delayed work with timers
d88ed5c82f5b cpufreq: governor: initialize/destroy timer_mutex with 'shared'
d2d28c549d32 cpufreq: governor: Pass policy as argument to ->gov_dbs_timer()
d7ab2ae8d60b Revert "msm: kgsl: Defer issue commands to worker thread"
62741e980321 msm: kgsl: Mark dispatcher thread as performance-critical
bfe50a2727f9 msm: kgsl: Dispatch commands using a master kthread
1dfde2a82825 Revert "scsi: ufs: Get TX and RX FSM states for debug purpose"
0b1958f4b26a Revert "scsi: ufs: Get TX and RX fsm state in case of abort"
af34ddab302e Revert "scsi: ufs: Adding io_stats to UFS debugfs"
dfac998b308a Revert "scsi: ufs: Add UFS slow I/O monitoring."
f7164ca697bb block: Disable IO_STAT and ADD_RANDOM
fd7446740293 Treewide: Silence GCC 4.9 warnings
f647427e920a compiler: allow all arches to enable CONFIG_OPTIMIZE_INLINING
5a4917c52dbc Compiler Attributes: add support for __copy (gcc >= 9)
b125b000a9a0 power: Compile wakeup_reason.c only with DEDUCE_WAKEUP_REASONS
585c7798bfcf BACKPORT: usb: host: plat: Enable xHCI plat runtime PM
dd3c4cef9285 msm: thermal: simple: Introduce simple MSM thermal solution
a679b2be65ee block: Fix a race between blk_cleanup_queue() and timeout handling
78908df7607d block: defer timeouts to a workqueue
492aa30fa5d7 block: prevent merging of requests with different priorities
5bf2dec623f0 sched/fair: Only kick nohz balance when runqueue has more than 1 task
3e286a198327 kernel: time: Add delay after cpu_relax() in tight loops
dad3ad53f940 msm: ipa: avoid printing UL data stall
e422f4726569 power: Silence leftover spammy logger
64e1fae72400 sched/fair: load balance if a group is overloaded
5c64a6a79c69 sched/fair: Fix asym packing to select correct CPU
bd99a953d4d1 sched/fair: Fix the min_vruntime update logic in dequeue_entity()
7db4775ccc5c sched/fair: Fix min_vruntime tracking
7a4563f5c8ac sched/fair: Fix util_avg of new tasks for asymmetric systems
baf7713844e0 FROMLIST: sched: Wrap rq->rd->overload accesses with READ/WRITE_ONCE
be3b0459aa58 sched/fair: Fix load_balance redo for !imbalance
727ed172e0a9 BACKPORT: sched/fair: Don't move tasks to lower capacity CPUs unless necessary
e4afaaabd0a6 sched/fair: Allow idle local group to pull tasks from overloaded group
baafc96ecf21 ANDROID: sched/fair: Don't balance misfits if it would overload local group
aebab5198bfc ANDROID: sched/fair: Attempt to improve throughput for asym cap systems
b6470833fd46 ANDROID: update_group_capacity for single cpu in cluster
79875cc39ca8 ANDROID: sched/fair: add idle state filter to prefer_idle case
9e8341a7d959 ANDROID: sched/fair: remove order from CPU selection
2c9bf90fde3b ANDROID: sched/fair: prefer energy efficient CPUs for !prefer_idle tasks
27b08a66418c sched: EAS: kick nohz idle CPU within the same sched domain
1f81183bc254 cpumask: make cpumask_size() return "unsigned int"
f57cde50593c sched/core: Optimize sched_feat() for !CONFIG_SCHED_DEBUG builds
80c5c412ca88 sched/debug: Ignore TASK_IDLE for SysRq-W
2a12a5b7e4d0 sched/core: Fix pick_next_task() for RT,DL
411e763682a9 sched/core: Optimize pick_next_task() for idle_sched_class
b99579090452 sched/core: Separate out io_schedule_prepare() and io_schedule_finish()
c2b58573385f delayacct: Account blkio completion on the correct task
a6d022499748 sched/core: move IO scheduling accounting from io_schedule_timeout() into scheduler
1ceb555fd093 sched/core: Fix oops in sched_show_task()
a99346a2ce61 sched/core: Move task_rq_lock() out of line
714ab0011b9b sched: Replace spin_unlock_wait() with lock/unlock pair
6ae8254751b5 sched/fair: fix for group_smaller_cpu_capacity()
48601dd49fdd sched/fair: select busiest rq with misfit task
0da2119c2a48 sched/fair: kick active load balance for misfit task
8ee87123857f sched/fair: fix to set sgs->group_misfit_task
9b21177e9bdd sched/fair: correct task_fits_max() for misfit task
45f4feb90f65 BACKPORT: FROMGIT: sched/debug: Explicitly cast sched_feat() to bool
d4f1641e2c9a Revert "sched/core: Properly fix constant logical operand Clang warning"
ccc5d96064bb sched/core: Fix &rd->cpudl memory leak
35f2f9101367 sched/core: Fix &rd->rto_mask memory leak
cb9da4ca7923 sched/rt: Minimize rq->lock contention in do_sched_rt_period_timer()
3ecd77bc05a6 sched/rt: Remove unnecessary condition in push_rt_task()
e871eece7e25 sched/rt: Make update_curr_rt() more accurate
6eb6c5ce9eb4 sched/fair: Fix the wrong throttled clock time for cfs_rq_clock_task()
3833919d0b56 sched/rt: Prevent leaking kernel address
df0ad6a75044 sched/rt, sched/dl: Don't push if task's scheduling class was changed
a0b08a776da1 sched/rt: Kick RT bandwidth timer immediately on start up
2ad099a9aaec locking, sched: Introduce smp_cond_acquire() and use it
d7d9bba022f2 sched/core: Move the sched_to_prio[] arrays out of line
c6248b8f7e01 sched/fair: Move the cache-hot 'load_avg' variable into its own cacheline
3322512289f8 sched: Make wake_up_nohz_cpu() handle CPUs going offline
de9b99da62de sched/core: Avoid _cond_resched() for PREEMPT=y
ee11092921f6 sched/core: Optimize __schedule()
7532284d9115 BACKPORT: sched/core: Fix rules for running on online && !active CPUs
3a67052ebdd2 BACKPORT: sched/core: Allow kthreads to fall back to online && !active cpus
2e30ae87da72 mm: remove unused variable in memory hotplug
0adfd5de418b mm: remove per-zone hashtable of bitlock waitqueues
03c46b224eaf sched/core: Remove pointless printout in sched_show_task()
5b595f3d1fa2 sched/cputime: Improve scalability by not accounting thread group tasks pending runtime
b4adb0ff40c9 sched/cputime: Mitigate performance regression in times()/clock_gettime()
0dd76ac71ac5 arm64: relax assembly code alignment from 16 byte to 4 byte
3c9a38b20bd7 scsi: ufs: fix wrong count of q_depth
aec9ab2894aa kernel: fake system calls on seccomp to succeed
93162f01ad21 power_supply: Fix unbalanced the power supplies
468145a16745 mfd: wcd9xxx: disable slimbus register access for debugfs
08d89cfee6ab UPSTREAM: dm crypt: use WQ_HIGHPRI for the IO and crypt workqueues
bc2a22d787af Revert "ANDROID: dm-crypt: run in a WQ_HIGHPRI workqueue"
9cedba83a9e0 scsi: ufs: call single_release to avoid memory leak
d6c582163505 mm: Enable oom_kill_allocating_task and disable oom_dump_tasks
a087f33db131 arm64: mm: allow preemption in copy_to_user_page
eedae11b160f tree wide: get rid of __GFP_REPEAT for order-0 allocations part I
446f271b35d2 arm64: get rid of superfluous __GFP_REPEAT
9430d3e5613b relay: Use irq_work instead of plain timer for deferred wakeup
0649026b51fc asoc/msm: Reduce min capture size
6c9089114afc UPSTREAM: lz4: fix wrong compress buffer size for 64-bits
35ac11ec56d3 UPSTREAM: lib: lz4: cleanup unaligned access efficiency detection
f245a5a381b8 CHROMIUM: selinux: Do not log permissive denials
9dd5ae228394 BACKPORT: mm: fix pageblock heuristic
2902ddadb607 Silences WLAN, PCIe, and CPU suspend state kernel messages
aa6426e7da7f Treewide: Fix GCC 9.1 warnings
54442a64bfa9 cpufreq: qcom: Remove tracing
ca9739ab2ac2 ion: avoid allocate high order of pages in system heap pools
60362bfc89cb Revert "ion: ion_system_heap: update supported page-orders for ion pool"
296cd415b170 Revert "ion: Consider ion pool pages as indirectly reclaimable"
0b36318fbaf6 Revert "ion: add movability support for page pools"
650ca4f35f8f Revert "ion:synchronize debugfs callback and ion_client_destroy"
1ec9c9acdbf1 binder: Disable binder_debug_mask
379d3bf7ca4e qseecom: fix a blocked listener request issue
8834cdf9e6ea qseecom: double check if app entry exists when unloading app
ed3fb37d245f qseecom: replace scm_call2 with scm_call2_noretry
f04364ecae3e qseecom: fix listener unregister issues
058c4a3fbbb0 qseecom: check register listener syscall result
8949dca138d2 qseecom: Add flag to support key wrap in KS
dc91fb29573e qseecom: add NULL check for ptr_svc->ihandle
5b55b3fa56c3 qseecom: fix listener_access_lock and unregister issues
1c1ac54002c0 qseecom: listener unregister and register optimization
9ff1eea00982 qseecom: Silence qseecom_receive_req
13f54113af89 qseecom: set rcv_req_flag to 0 when listener is just registered
c1c2bd9f1cb9 qseecom: do not wake up listener to receive request if it is not ready
c67f5f4fa448 qseecom: check if listener is not ready to receive request
c8676d434ada qseecom: set listener id before sending registration scm_call
85abdef073bd qseecom: processing invalid listener request
4a053bb234d8 qseecom: change check_blocked flag to an u32 value
5aa4fa06e7d8 qseecom: check if app is blocked when unloading app
97143e52bf49 qseecom: improve blocked listener processing for smcinvoke
16612cc32961 qseecom: abort all listener threads before listener unregistration
20df0b907927 qseecom: Increase the scattered entry buffer size
43433cdec6d8 usb: gadget: f_accessory: Avoid double-free
393e344a8fa8 ANDROID: sched/fair: fix energy compute when a cluster is only a cpu core in multi-cluster system
46bcc5400870 ion: fix a possible memory leak in ion_cma_allocate
221c6843b00a input: qpnp-power-on: correct Power-off reason of PMIC FAULT cases
109af49903c9 ASoC: Silence platform not registered message
c6c6ffee9043 binder: Fix concurrency issue in target_thread wakeup
47a6104db5c2 ion: add movability support for page pools
4008f195df76 ion: use unbounded wq for prefetch work
968128d0a1eb mm: swap: swap pages one at a time
60f479bf5839 kernel: time: reduce ntp wakeups
954d15114d65 mm: skip swap readahead when process is exiting
9965c08ef45e ion: ion_system_heap: update supported page-orders for ion pool
3b1b26390c29 msm: kgsl: Stop slab shrinker when no more pages can be reclaimed
9e0335e90174 Revert "msm: kgsl: Add disable-wake-on-touch devicetree property"
781f488ebade Revert "msm: kgsl: Add debug log in adreno_of_get_pwrlevels()"
cdadbfe08588 rcu: Import rcu_segcblist_entrain()
e69275a20bb5 srcu: Abstract multi-tail callback list handling
203fb8e57c5e rcu: Don't wake rcuc/X kthreads on NOCB CPUs
1dd415fa7821 qseecom: fix memory leak in qseecom_start_app()
21ac8935796b net: ipc_router: Fix remote port memory leak
f873bd8f3809 usb: dwc3: Fix OF memory leak in probe
0d36d03fc654 dma: Fix mem leak reported by kmemleak
4ce5d53c5945 sched/cpufreq: Fix kobject memleak
8ad7dd35edda rcu: Make cond_resched_rcu_qs() supply RCU-sched expedited QS
ed546dbf68ad rcu: Prevent rcu_barrier() from starting needless grace periods
b7cb681fdf5a rcu: Speed up calling of RCU tasks callbacks
9c8c99257f54 sched/core: Call __schedule() from do_idle() without enabling preemption
4df6fb81bae0 sched/idle: Micro-optimize the idle loop
05c53689bf6a sched/idle: Move quiet_vmstate() into the NOHZ code
9dec2e674e86 cpufreq: schedutil: Fix sugov_start versus sugov_update_shared race
0faa0a8a9f0a schedutil: Allow cpufreq requests to be made even when kthread kicked
658dd3e78f76 BACKPORT: cpufreq: schedutil: Avoid using invalid next_freq
d99d75409892 cpufreq: schedutil: Don't set next_freq to UINT_MAX
43dc56248e20 sched/cpufreq/schedutil: Fix error path mutex unlock
ea6f93b388cb cpufreq: schedutil: Only apply single core busy logic with PELT
a61be9416f9e cpufreq: schedutil: Switch from sprintf to scnprintf
ed6f4e586625 cpufreq: schedutil: Avoid unnecessary kthread wakeup
6c68eab42836 cpufreq: schedutil: Ignore CPU load older than WALT window size
262d6d516b9b BACKPORT: cpufreq: schedutil: Cache tunables on governor exit
b28fc0c965ce cpufreq: schedutil: Use >= when aggregating CPU loads in a policy
fd7985c0091c msm: msm_bus: Fix error handling in msm_bus_device_probe
2b4dc65c1968 slimbus: fix inconsistent mutex_lock
421729c17ffd qdsp6v2: fix inconsistent mutex_lock
61eafac372bf wcd9335: fix inconsistent mutex_lock
0fe9455aab26 msm_cci: fix inconsistent mutex_lock
3236a46f02b3 msm: qdsp6v2: fix inconsistent spin_lock
f8b7fb7fed16 msm: memshare: relaese mutex if req client id is not found
f706a45d71b5 qcom: qmi: release mutex upon qmi_svc_event_notifier_register error
111fe607ccd5 thermal: qpnp-adc-tm: release lock upon disable_chan_meas failure
4aef7e9804fe lib: Kconfig: Don't enable DEBUG_BUGVERBOSE by default
810908b24686 arch: arm64: crypto: Improve CPU targeting
06505ede75d3 msm: gsi: Guard IPC logging
0ddb93f9a248 HACK: arm64: add CNTPCT_EL0 trap handler
b4466c3c695d msm: bus_arb: disable debug logging
015ee895363c slim-msm-ngd: Prevent race condition between resume and SSR
a37e3bebf757 slimbus: slim-msm: Handle system suspend while active slimbus transfers
149e3f5adf1d slimbus: Fix the type usage of transaction id
6e7bf1c7e957 pinctrl: qcom: Add irq_enable callback for msm gpio
6360baa95353 drivers: pinctrl: mask non-wakeup interrupts in suspend path
2bf475145e35 block/cfq-iosched: make group_idle per io cgroup tunable
263639719b49 Revert "block/cfq-iosched: make group_idle per io cgroup tuneable"
048409641b46 kernel: Allow IRQs to become perf-critical after they're created
4dfd40e1ba99 msm: mdss: Speed up MDP interrupt processing for cmd mode panels
075fefb52bfb Revert "usb: gadget: mtp: Increase RX transfer length to 1M"
907da158dfdc Revert "usb: gadget: f_mtp: Increase default TX buffer size"
dd428ccf3ed0 Workaround for sensor ipc message causing high power consume
942dc1898e2a soc: qcom: sleepstate: Move delay to suspend path
b41a4c244bd8 soc: qcom: sleepstate: Tune suspend and resume delays
82de7b6451ee msm: kgsl: Relax adreno spin idle tight loop
6ed8aa298e49 UPSTREAM: arm64: Implement __lshrti3 library function
5d89f542c1e8 arm64: Kconfig: Don't select FRAME_POINTERS
7eaeb34e12ac mm: add Kconfig interface for vmstat interval
920c973f166f arm64: debug: disable self-hosted debug by default
0d722e217f2d staging android: Keep timestamp info of merged fences.
93ffd5e0afad Revert "GIC: Show interrupts that triggered wakeup"
3211d85c0d2e Revert "msm: show_resume_irq: print the irq name"
dd5aa670488c Revert "irqchip: gic: print correct resume irq name"
eee06edd171e Revert "BACKPORT: irqchip/irq-goldfish-pic: Add Goldfish PIC driver"
e3dd98eec299 init/main.c: add sync point between each level
be1b88691397 Revert "init/main: Put kernel end place_marker"
4fdfb3269fa5 Revert "power:hibernate: KPI marker for Hibernation Success"
9745d2edeadf FIXUP: cpuidle: Optimize pm_qos notifier callback
492a6270f6f4 msm: mdss: add idle state node
c6fa8bf2eef9 sched: Import sched_(get|set)_wake_up_idle
743dc3394ff8 arm64: only pass -mpc-relative-literal-loads if 843419 fix is enabled
6069391213d5 arm64: relocatable: fix inconsistencies in linker script and options
62482e28530c UPSTREAM: arm64: prevent regressions in compressed kernel image size when upgrading to binutils 2.27
fea408452dbc UPSTREAM: arm64: kernel: force ET_DYN ELF type for CONFIG_RELOCATABLE=y
defd5fd43de0 UPSTREAM: arm64: support __int128 on gcc 5+
6afde3a27f74 scsi: ufs: call single_release to avoid memory leak
709b1543bd10 scsi: ufs: mark device and link state if probe fails
5453af48cdf8 scsi: ufs: Dont send abort command to w-luns
487302c5f454 scsi: ufs: Avoid deadlock in suspend and eeh_work
42d44dc7027b scsi: ufs: fix the UFS command tracing events
106b31927a81 scsi: ufs: change the clock scaling polling period and up threshold
e91412c8b55c scsi: ufs: avoid deadlock by releasing rw_sem during hibernate
4e6d2b588695 scsi: ufs: Avoid writing null to Boot LUN enable attribute
35f353abb1f3 scsi: ufs: revise commit ecd2676bd513 ("disallow SECURITY_PROTOCOL_IN without _OUT")
1a466654f66d scsi: ufs: disallow SECURITY_PROTOCOL_IN without _OUT
4433f9e89127 scsi: ufs: disable clock scaling
609838fc2240 scsi: ufs: Add discard command support to ufs debugfs req. stats
37bc7430e073 scsi: ufs: Adding io_stats to UFS debugfs
c2a5ddb19952 scsi: ufs: fix req_stats debugfs entry
f81e9cb2af19 scsi: ufs: fix wrong order for slow io
56e68722ed20 scsi: ufs: Add UFS slow I/O monitoring.
e77d4c5796f6 scsi: ufs: fix wrong pointer for enabled latency_hist
54e7a533da69 scsi: ufs: nullify lrbp->cmd inside of valid tag period
b3ef996f3262 scsi/ufs: use 16 queue depth for Samsung UFS part
6c1dca7e1f34 ufs: show ufs part info in error case
78c9baed2c73 Revert "scsi: ufs: disable auto hibern8"
4b7a8724f1f7 scsi: ufs: Change power mode on line reset
79abec06ce41 Revert "scsi: ufs: Change power mode on line reset"
b9dc24c5a756 scsi: ufs: disable auto hibern8
434f0aca85f0 scsi: ufs: fix issue with scaling up gear
c69e17982760 scsi: ufs: Fix scale up issue
28219b0cc699 cfq: Suppress compiler warnings about comparisons
f2c733238278 cfq: clear queue pointers from cfqg after unpinning them in cfq_pd_offline
d1b5af0bf482 block/cfq-iosched: make group_idle per io cgroup tuneable
07848244587f block: Initialize cfqq->ioprio_class in cfq_get_queue()
4c4782fe71ea android,lowmemorykiller: Don't abuse TIF_MEMDIE.
d37492d82693 mm: Default to 128KB readahead
4a71b91d6a74 net/sched: Shut up
06eab9eb70e8 net: sched: do not emit messages while holding spinlock
c4632a316e1a kernel: Don't override do_set_cpus_allowed() for perf-critical tasks
bfa1f2e9899e cpuidle: Optimize pm_qos notifier callback
de7a9099c4a2 qos: Execute notifier callbacks atomically
a7a9885a5f8e qos: Don't disable interrupts while holding pm_qos_lock
79578385345e kernel: Remove calls to get/put_online_cpus in affine_one_perf_irq
e0169287a1d0 cpuidle: lpm-levels: Remove debug event logging
df58aab966e4 staging: sync: Don't copy fence names by default
7d8191471e02 msm: mdss: Speed up mdss_mdp_get_format_params for UBWC formats
846e520871ad qos: Don't allow userspace to impose restrictions on CPU idle levels
9f1d10274602 msm: kgsl: Relax CPU latency requirements to save power
ebc375319c69 cpuidle: lpm-levels: Allow exit latencies equal to target latencies
b45ce9bf5ded msm: kgsl: Remove sync debug name generation from hot path
33279e9a4ad9 msm: mdss: Remove sync debug name generation from hot path
2debdbb714d8 selinux: Remove audit dependency
b205fb2fb70d kernel: Boost to the max for a short amount of time when zygote forks
1225a78fa30f kernel: Boost whenever a zygote-forked process becomes a top app
3b0779314f97 msm: clock-osm: Use CLKFLAG_NO_RATE_CACHE for pwrcl and perfcl clk
c99f0ab79174 msm: mdss: Boost CPU and DDR bus when committing a new frame
c36b6e0dcfdf devfreq_boost: Mark boost kthreads as performance critical
cf73d8d74860 devfreq_boost: Introduce devfreq boost driver
709febb9ff3c cpu_input_boost: Mark boost kthread as performance critical
cbaf11571ae7 cpu_input_boost: Introduce driver for event-based CPU boosting
1d3a7767db70 msm: kgsl: Increase worker thread priority
246100adbca0 treewide: Fix -Wmaybe-uninitialized warnings
172b0a6721e0 Makefile: Don't disable -Wmaybe-uninitialized globally
3a7322739666 Revert "msm: kgsl: Disallow L2PC during wake up from SLUMBER"
e2b3e54aec4a msm: kgsl: Remove POPP
7ed0caf66a62 msm: ipa3: Fix redundant wakelock releases in error paths
f2b8427ccf0e treewide: Fix code issues detected using GCC 8
6e201b46eaa0 Makefile: Disable noisy GCC 8 warnings
4febe2348656 usb: pd_engine: Fix mismerge of 1862c1441190f64b65dfe00bd8536f647b8e6188
85c74576e0dd usb: pd_engine: Fix memory leaks in probe and destroy
558a5b09110e msm: vidc: Fix broken debugfs creation error checks and error paths
aa6edf85ff3a msm: pcie: Fix uninitialized pointer usage in msm_pcie_debug_info()
ba9fb445e781 msm: camera: isp: Fix memory leaks in vfe probe
7bfd8e604f03 msm: mdss: Don't cache the address of a stack variable in timings init
a27cb91a1e27 soc: qcom: watchdog_v2: Fix memory leaks when memory_dump_v2 isn't built
d1a72d39f416 msm: vidc: Use seq_file for debugfs interface
fcd73017f427 msm: mdss: Mark IRQ and important kthreads as performance critical
54c784da184d msm: kgsl: Mark IRQ and worker thread as performance critical
45eb24ac0852 kernel: Add API to mark IRQs and kthreads as performance critical
551b218ae540 cpumask: Add cpumasks for big and LITTLE CPU clusters
45b07307b2ca cpuidle: don't disable cpuidle when entering suspend
1169ce4fb243 cpu: Silence log spam when a CPU is brought up
a3eed670e3ef msm: msm_bus: Don't enable QoS clocks when none are present
b818acc249e4 scripts: Don't append "+" to localversion
8e1b0fa6645a mdss: fix of_find_property call
4c2542904abe fs: drop_caches: expose mm_drop_caches()
3d6678a75348 fs: default to noatime
c896b436e0cf writeback: hardcode dirty_expire_centisecs=3000 (30s)
c965f81c1f9c ANDROID: vfs/ext4,f2fs: finish umount(2) in time with filesystem work
6780da16b10c f2fs: always assume that the device is idle under gc_urgent
5fdc3b743bee f2fs: don't wait with each discards under gc_urgent
2e3bf9348cd4 f2fs: use a more reasonable discard policy for high utilization
c1f5356d45ca f2fs: reduce timeout for uncongestion on f2fs_write_cache_pages()
dfd7b9a5b6b8 f2fs: rename /sys/fs/f2fs
4aa05c31d150 f2fs: do not expose tunables that doesn't work with rapid GC
f589935708f1 f2fs: drop caches upon rapid GC exit
4d02c7434cb0 f2fs: explicitly flush device upon foreground GC
6827324a19b4 f2fs: fix rapid GC breakage from merge 4e87f7d2befb8
d2749b10e494 f2fs/rapid_gc: do not wait until all invalid blocks are discarded
30f8a539d0e0 f2fs: convert wakelock APIs to wakeup_source
7202dd411e8a f2fs: implement rapid GC for Android
75dfe3707bf1 f2fs: set ioprio of GC kthread to idle
18717b56ed18 f2fs: use 1ms for discarding under GC_URGENT
6add32826444 sched: Turn on MIN_CAPACITY_CAPPING feature
4a7f7578d272 sched/fair: Add bias schedtune boosted tasks sched feature
e64f62ac3b0a sched/fair: use min capacity when evaluating active cpus
b59de9f56294 sched/fair: use min capacity when evaluating idle backup cpus
d5cf80ecc214 sched/fair: use min capacity when evaluating placement energy costs
1087961987fa sched/fair: introduce minimum capacity capping sched feature
eed7b15e3b49 sched: add arch_scale_min_freq_capacity to track minimum capacity caps
15f09332386a sched/fair: introduce an arch scaling function for max frequency capping
7fd375a68096 FROMLIST: sched: Make iowait_boost optional in schedutil
7de72f045a48 FROMLIST: cpufreq: Make iowait boost a policy option
efd009f7cba3 sched/fair: Fix issue where frequency update not skipped
08e3f97e07cf ANDROID: Move schedtune en/dequeue before schedutil update triggers
b4ee5b660445 sched/fair: Skip frequency updates if CPU about to idle
ad460be22df7 sched: EAS: upmigrate misfit current task
5d7ba93e5d47 sched: EAS: kill incorrect nohz idle cpu kick
f0029887847a sched/fair: kick nohz idle balance for misfit task
8604ea6c7d6d sched: Extend active balance to accept 'push_task' argument
327f5326a2af sched/walt: use do_div instead of division operator
0349ab6edb79 schedutil: Don't assume we are likely using PELT
408307d449cc Reapply 43bd960 ("sched: WALT: account cumulative window demand")
e035655e99d7 sched: deadline: Add missing WALT code
472829176c3c sched: Add missing WALT code
1c02426c4cd5 treewide: Remove HMP and CORE_CTL for EAS bringup
66e928146cf2 dts: restore i2c_6
6c28c8a8bc68 defconfig: add capricorn
89045816b053 drivers: soc: qcom: Import Capacitive touch driver
ac1f9fc32928 Merge branch 'upstream-linux-4.4.y' of https://android.googlesource.com/kernel/common into HEAD
3c01433101bf fix some warnigs
c9147677451e add anykernel3
bb39fe24e9b2 platforms: add support for capricorn
1dd270dc00e5 defconfig: All credits to Andrzej Perczak

   * packages/apps/Recorder/
fc01360 Fix lag when dragging overlay and updating timer
5b48203 Add alpha on floating window
16e3015 Cleanup config
a650176 Adjust internal audio recording params
1f56e9a Add timer into activity
5f33ba7 Revert "Open last recorded item on stop"
9778c93 Improve floating window
f04b85c Use accent from framework
54deb67 Don't hardcode font
4fc7b0f Fix black theme
54130d1 overlay: Add little spacing on the end of recording button
19386d1 Improve share notifications
263eac9 Disable qs tiles when locked
dd671a9 Open last recorded item on stop
aad89be Add listener on Settings activity
f33d5a3 Stop overlay service on record started
3a78d14 Add orientation preference
0e4e3a4 Pause recording when screen off to save resources
db7264c Check before unregistering broadcast receiver
309b558 Always use H264
5d4f105 Hide some activities from recents
73f9d42 Add more preferences
dbb5dec Use reflection to collapse statusbar
1ede6d1 Improve transparent theme
02c298e Conditionally disable internal audio recording support
38c59b2 Import custom androidx preference library for better theming
fec3196 More theming improvements
c09bc90 Refactor settings UI
adbd547 Refactor recording methods
9511b58 Separate and improve strings
446ad5a Rename strings to custom_strings.xml
6574d90 Cleanup intents
9afc974 Remove from launcher
6e48d03 Update icon
8ff4d49 Change version
7004cc5 Implement qs tiles and refactor code
2885a4d Improve recording floating overlay
33ce278 Don't use shared prefs to store recording state
fccca20 UI redesign
55254ec Add system audio recording support [1/2]
e97bc73 Rebrand
1ad0339 Bump sdk

   * vendor/qcom/opensource/audio/
0744ca9 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
37d4529 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
390f275 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     09-01-2019
====================


   * device/xiaomi/gemini/
7ac48ccf msm8996-common: add prop persist.vendor.usb.config.extra
4fc61054 msm8996: use vidc from msm8998
fbdf1899 msm8996: use stock USB hal

   * kernel/xiaomi/msm-4.4/
97ad7b7ca26e Merge branch 'upstream-linux-4.4.y' of https://android.googlesource.com/kernel/common into HEAD
dcca93e9595e Makefile: set arm64 as default
2f7feaba997d [SQUASH] drivers: bluetooth: revert btfm_slim changes
954ab977d38a net: wireless: cnss: add option to disable SDIO support
e764be070493 defconfig: disable LZO
446adbaf5249 drivers: zram: don't force LZO
d1cf7953defa defconfig: enable LZ4 for ZRAM
04551b2f5ef3 defconfig: add missing security stuff
5cb5cf932263 defconfig: enable back wakelocks
3a2992578e15 defconfig: use HZ_100
f8268899700e drivers: misc: drv2604: disable remove function
30141e82d754 drivers: misc: drv2604: change printk to pr_*
3b096352ca80 drivers: misc: constify structs
5d9ce0e2ce81 drivers: drv2604: Rename vtg_level_default to vtg_default
990eed8b5124 drivers: drv2604: Create sysfs interface for vibration intensity
cc70a3c0cd41 drivers: staging: qcacld-2.0: remove useless warning
2042afe0fb53 defconfig: debloat
16076150b29e defconfig: massive disable of debug and some tweaks
54eb86be574e sound: soc: msm: fix wsa881x init skip
91bb42974f42 trace: add CONFIG_DISABLE_TRACE_PRINTK option
1d1b73ad3442 Update README
ddb61f9412fc msm: camera_v2: fix for older blobs

   * packages/apps/HavocSettings/
6a4ffc2 Translation updated

====================
     08-31-2019
====================


   * build/make/
c70a05174 More base_rules.mk optimizations
d67269190 Skip much of aux_config.mk

   * device/xiaomi/translations/
f832815 remove obsolete Updater translations

   * frameworks/av/
dd944d0830 audiopolicy: Fixes for internal audio recording

   * kernel/xiaomi/msm-4.4/
116056ab5811 msm: kgsl: Correct the iommu protection ranges
200fd22e0416 q6asm: Remove payload size check
9c76f3d86eed sound: msm8996: Don't try to init wsa881x when it's not enabled
1c549da4038a defconfig: disable unused codecs on gemini
f461b958db88 sound: codecs: don't select unused codecs
1bb646bbf695 Add README
5c46424cf2c7 kernel: sched: fix ifdef
b1ad7883bbb2 defconfig: initial defconfig for gemini
70cee48fd50e dts: remove reserved memory for hdmi display
059f65d95bcb dts: disable more unused devices
15c0585deace dts: disable uart console
87a3c2501120 dts: delete unused devices
0c4f245c778c dts: correct pwm node
7e3a4dbb547f dts: remove ocimem reserved region
b89a0705094f dts: correct ramoops address
ee7732dd6e19 dts: correct reserved region
98e7791c40eb dts: nuke custom qusb settings
acc79ea98b25 drivers: media: camera_v2: Include Xiaomi camera OIS support
001cc78edfdb drivers: media: camera_v2: Import Xiaomi camera stack

   * packages/apps/Updater/
10090f3 Bangla Translation (#1)
98f5452 delete untranslatable strings
b35ac20 Bangla Translation
bce67ca fix typos

   * vendor/havoc/
1cea1cdd Revert "Remove prebuilt MarkupGoogle"
250354b2 vendor: Build Recorder app
fbbe98bc overlay: Disable config_keyguardUserSwitcher on sw600dp

