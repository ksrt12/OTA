
====================
     05-19-2019
====================


   * device/xiaomi/gemini/
3a6abb67 msm8996-common: sepolicy: Address qfp-daemon denials properly
a962aec8 cparicorn: update overlays

   * kernel/xiaomi/msm8996/
1b8436269a37 sound: soc: codecs: import tfa98xx driver v6.5.5

====================
     05-18-2019
====================

   * device/xiaomi/gemini
eee5e3ba capricorn: build kernel with clang 9.0.3
8390ca04 gemini: convert to Android.bp
9c7c6a0e move some variables to device.mk

====================
     05-17-2019
====================


   * frameworks/base/
581b79763eb3 Revert "hwui: Enable quicksilver"
f4ce5749cad6 Battery Estimates: Disable by default [1/2]
e9434d09fe54 Battery Estimates: Move battery icon to QS header when disabled
61116db2f680 Aggressive Battery: fix auto enable on battery saver
0bb14d1fcb2e base: SystemUI: make qs edit repect header image
7e61cca7ce03 Revert "Network traffic: Retain our notch check"
f4312b75048e LiveDisplay tile: allow override outdoor capablity

   * hardware/havoc/interfaces/
a8b523d havoc/interfaces: Remove lineage trust hal
3dde4e9 havoc/interfaces: Remove lineage power hal
f99f0f8 Init Havoc...

   * packages/apps/Settings/
d492b42374 Battery Estimates: Disable by default [2/2]
3aa40abc7e Settings: Restart SystemUI when toggling battery estimates
8fcef4284a Settings: Add User icon to the searchbar

====================
     05-16-2019
====================

   * kernel/xiaomi/msm8996/
003947b93c46 Merge 3.18.140 into kernel.lnx.3.18.r34-rel
6b1ae527b1fd Linux 3.18.140
36927e41c311 powerpc/booke64: set RI in default MSR
db7e50136a20 drivers/virt/fsl_hypervisor.c: prevent integer overflow in ioctl
3b187319bc7c drivers/virt/fsl_hypervisor.c: dereferencing error pointers in ioctl
66ed3c8b10c1 bonding: fix arp_validate toggling in active-backup mode
ae0f0ebd83c2 ipv4: Fix raw socket lookup for local traffic
860e91819fed vlan: disable SIOCSHWTSTAMP in container
97d36ca9da84 packet: Fix error path in packet_init
9d59fa6eeb6b net: ucc_geth - fix Oops when changing number of buffers in the ring
28107baf408d bridge: Fix error path for kobject_init_and_add()
c0759c18e95d USB: serial: fix unthrottle races
6b612ec29abd USB: serial: use variable for status
466153fc585e Don't jump to compute_result state from check_result state
913fbfc3fd78 gpu: ipu-v3: dp: fix CSC handling
fad368428284 selftests/net: correct the return value for run_netsocktests
68e8a8d9bcca s390: ctcm: fix ctcm_new_device error return code
4ce4b005e584 init: initialize jump labels before command line option parsing
f97fc640c425 tools lib traceevent: Fix missing equality check for strcmp
72ba8a7a7c8e KVM: x86: avoid misreporting level-triggered irqs as edge-triggered in tracing
eca5f4de2f5f s390/3270: fix lockdep false positive on view->lock
2f922c459f48 s390/dasd: Fix capacity calculation for large volumes
e172a3b59098 HID: input: add mapping for keyboard Brightness Up/Down/Toggle keys
b8f6da2fcb2e iio: adc: xilinx: fix potential use-after-free on remove
23a030f79c35 platform/x86: sony-laptop: Fix unintentional fall-through
d2774665f7c7 netfilter: compat: initialize all fields in xt_init
b784e7a613d1 timer/debug: Change /proc/timer_stats from 0644 to 0600
b16a6c99f88c Bluetooth: Align minimum encryption key size for LE and BR/EDR connections
9c47ad93de73 Bluetooth: hidp: fix buffer overflow
6ee71083b16f scsi: qla2xxx: Fix incorrect region-size setting in optrom SYSFS routines
43dae3a4e492 genirq: Prevent use-after-free and work list corruption
17f93dcb6222 iommu/amd: Set exclusion range correctly
47ebd4007edc scsi: csiostor: fix missing data copy in csio_scsi_err_handler()
0562cef837e2 ASoC: tlv320aic32x4: Fix Common Pins
e0124792043a ASoC: cs4270: Set auto-increment bit for register writes
0a635ced7127 ASoC:soc-pcm:fix a codec fixup issue in TDM case
ec22b57b0527 scsi: libsas: fix a race condition when smp task timeout
f52118781632 media: v4l2: i2c: ov7670: Fix PLL bypass register values
56c85b204c3b staging: iio: adt7316: fix the dac write calculation
05aafb6243c8 staging: iio: adt7316: fix the dac read calculation
4e12fe2e5520 staging: iio: adt7316: allow adt751x to use internal vref for all dacs
19a81333239e usb: usbip: fix isoc packet num validation in get_pipe
9f3a2aa76996 ARM: iop: don't use using 64-bit DMA masks
91b4d929ccb0 ARM: orion: don't use using 64-bit DMA masks
77541ef954e3 xsysace: Fix error handling in ace_setup
b3a65e122a39 hugetlbfs: fix memory leak for resv_map
202dff90b727 scsi: storvsc: Fix calculation of sub-channel count
44a476cf0bc2 jffs2: fix use-after-free on symlink traversal
c452e33d4940 bonding: show full hw address in sysfs for slave entries
b2eed39466f8 igb: Fix WARN_ONCE on runtime suspend
00a9ea1b3a7d rtc: sh: Fix invalid alarm warning for non-enabled alarm
358e9483e84a HID: debug: fix race condition with between rdesc_show() and device removal
bc1c5d1ac477 USB: core: Fix bug caused by duplicate interface PM usage counter
fe1e6f511cb1 USB: media: disable tlg2300 driver
652c6e122fda USB: core: Fix unterminated string returned by usb_string()
483dc306cb1d USB: w1 ds2490: Fix bug caused by improper use of altsetting array
15c0d2672a47 USB: yurex: Fix protection fault after device removal
f4d6bb3a95be ipv6/flowlabel: wait rcu grace period before put_pid()
6ca4b4080c10 packet: validate msg_namelen in send directly
91c38d754460 ipv6: invert flowlabel sharing check in process and user mode
1e584073efa2 ipv4: ip_do_fragment: Preserve skb_iif during fragmentation
e2e7cf41baba kconfig/[mn]conf: handle backspace (^H) key
c2e5f31ccbf2 libata: fix using DMA buffers on stack
ef269561a9de scsi: zfcp: reduce flood of fcrscn1 trace records on multi-element RSCN
d98c0b86e7a1 ceph: fix use-after-free on symlink traversal
a826eff401e6 usb: u132-hcd: fix resource leak
61d586191960 scsi: qla4xxx: fix a potential NULL pointer dereference
0f1cf480956c net: ibm: fix possible object reference leak
90a9d6d23c0e net: ks8851: Set initial carrier state to down
cd30c290a14d net: ks8851: Delay requesting IRQ until opened
76fc3b4b21c0 net: ks8851: Reassert reset pin if chip ID check fails
47d93a167555 net: ks8851: Dequeue RX packets explicitly
906dbadf304e usb: gadget: net2272: Fix net2272_dequeue()
1da2fd016314 usb: gadget: net2280: Fix overrun of OUT messages
65e6cca34beb qlcnic: Avoid potential NULL pointer dereference
a0118894ef08 net: stmmac: move stmmac_check_ether_addr() to driver probe
5466bd95f6e3 team: fix possible recursive locking when add slaves
f37fb00c1c4f ipv4: add sanity checks in ipv4_link_failure()
7f29d9b03ac7 Revert "block/loop: Use global lock for ioctl() operation."
9331b51b7b05 netfilter: ebtables: CONFIG_COMPAT: drop a bogus WARN_ON
dcbb0ca6856c NFS: Forbid setting AF_INET6 to "struct sockaddr_in"->sin_family.
7ab3ca7f1461 fs/proc/proc_sysctl.c: Fix a NULL pointer dereference
0cc8c5a22996 slip: make slhc_free() silently accept an error pointer
b0b38ec24346 sunrpc: don't mark uninitialised items as VALID.
596c78267376 ceph: ensure d_name stability in ceph_dentry_hash()
7c82b63c7258 sched/numa: Fix a possible divide-by-zero
316bc8144b44 trace: Fix preempt_enable_no_resched() abuse
d1a3145b6b48 MIPS: scall64-o32: Fix indirect syscall number load

   * frameworks/base/
52c48bc81b50 SystemUI: Fix clicking battery icon in QS header
6d4c6632d551 base: Add toggle to disable battery estimates in QS [1/2]

   * packages/apps/HavocSettings/
aa36b59 Add tblte in devices
16be001 Add j7xelte in devices

   * packages/apps/Settings/
9ef94508eb Settings: Add toggle to disable battery estimates in QS [2/2]
3071dfd096 Settings: Add Q Green accent [2/3]
a508b726ab Settings: Add Sweet Q Purple accent [2/3]

   * packages/apps/SettingsIntelligence/
a5c1e6f SettingsIntelligence: Match Settings searchbar

====================
     05-15-2019
====================


   * external/sqlite/
cc954ee sqlite: upgrade to SQLite 3.28.0

   * frameworks/base/
06ad5054235e LiveDisplay tile: allow FEATURE_MANAGED_OUTDOOR_MODE
82a23130e6ae Improve checks for lockscreen visualizer
67f378a349be SystemUI: Improve Circle battery size
0d33701ab6a2 SettingsLib: Increase Signal icon size
d5abed856975 SystemUI: Improve battery estimate layout in QS
36a7ead8b76f base: Add Q Green accent [1/3]
4a26bdf6daf6 base: Add Sweet Q Purple accent [1/3]
02f48c75f146 KeyguardUpdateMonitor: Fix SystemUI crash with auto face unlock
7071a7daa42a Fix conflict between pulse auto color and lockscreen wallpaper
38a3a9f402b4 Lockscreen Visualizer: Check for media playing before displaying artwork
9f4d2a9956e8 Lockscreen Visualizer: Automatic color based on wallpaper if no album art found
efcccaed78cc Update Turkish translations
da7176dc1e4b base: Add seekbar to media notification
fe96ed992c65 Q Always-On Display: Add double tap media slice to skip song
442c2fc80b51 Q Always-On Display: Show media info in keyguard slice
8b990d24dd12 SystemUI: Fix ambient music ticker double tap detection
1a4d9b283706 base: Use headline font in notification texts
9a7df1c69300 SystemUI: Use headline font in various parts
cbefd388fc70 Fix weird artifact in battery icon
f5f4b075cc3e Improve Q battery icon and unify with portrait style
1e68302218b8 SettingsLib: Expose Q battery icon paths
800bd85bc55f SystemUI: Implement enhanced battery estimates in QS

====================
     05-14-2019
====================


   * frameworks/av/
51a046ed70 Explicitly initialise base class in copy constructor

   * frameworks/base/
b4a4ab9ae432 SystemUI: Set proper color for battery text view
5016d7ee783b base: Add Q style to battery icon chooser [1/2]
aa20c35a248b Battery icon: Don't force show percentage
060b13fad9aa Settings: inherit battery meter style in view [1/2]
3559137908e8 BatteryMeterView: Fix logcat spam
0ff74b7fde33 Battery icon style: improve text/hidden switch
f5b1e68a20bd Battery icon: force show pct in QS header and when charging/powersave
ce23aafedd5d Battery icon: show outside percentage on charging
8cf773bac3d3 Text battery style: show a bolt ⚡ when charging
2064e9228f3b SystemUI: clean up battery styles code
b0ac58eb099b Add the powersave hint to the circle battery
02a35117efe7 BatteryMeterDrawable: add dotted circle style (1/2)
36e430a01699 BatteryMeterDrawable: add hidden option (1/2)
040ad9d475fc BatteryMeterDrawable: add text style (1/2)
39e1af5b0640 BatteryMeterDrawable: add battery styles
c1cf0cf6a34a Implement battery percent styles (1/2)
21d4775ad23b base: Cleanup battery styles implementation
e9517c501117 CustomTextClock: Improvements and translations

   * packages/apps/CarrierConfig/
4c189b9 CarrierConfig: Enable VOLTE, WFC, VT on Singapore carriers

   * packages/apps/HavocSettings/
9d67adc Update Russian translations
c8ec271 Fix Russian translations

   * packages/apps/Settings/
7514d7a601 Update Turkish translations

   * vendor/themes/
938c917 themes: Add Q Green accent [3/3]
e8b5a2b themes: Add Sweet Q Purple accent [3/3]

====================
     05-13-2019
====================


   * packages/apps/HavocSettings/
bfc78b8 Add montana to devices

