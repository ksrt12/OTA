
====================
     09-27-2019
====================


   * device/xiaomi/gemini/
2a781bb6c Restore ANT+
12ec511a8 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' into gps

   * external/ant-wireless/ant_service/
f760ac5 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/external/ant-wireless/ant_service into HEAD

   * vendor/xiaomi/
4e85d19a msm8996-common: Restore ANT+
10feabd2 convert some modules to Android.bp

====================
     09-25-2019
====================


   * device/xiaomi/gemini/
c1267fabe overlays: move some values to fwb

   * frameworks/base/
bc18bee45f6 overlays: move some values from device path

   * hardware/interfaces/
ad3e3bc69 replace <cutils/log.h> with <log/log.h>

====================
     09-23-2019
====================


   * device/xiaomi/gemini/
344d9285f move PRODUCT_BRAND var back to $(PRODUCT_NAME).mk

   * vendor/nxp/opensource/commonsys/external/libnfc-nci/
145f3dd fix warnings

====================
     09-22-2019
====================


   * kernel/xiaomi/msm-4.4/
c624abc05b4c Merge branch 'upstream-linux-4.4.y' of https://android.googlesource.com/kernel/common into pie
5f090d837b1f Linux 4.4.194
00ff438addf8 net_sched: let qdisc_put() accept NULL pointer
6b011ece4cdf ARC: export "abort" for modules
db38be77199f media: technisat-usb2: break out of loop at end of buffer
f5282fe27305 floppy: fix usercopy direction
c08c6b9eb55e keys: Fix missing null pointer check in request_key_auth_describe()
c9670a4e6d7b dmaengine: ti: omap-dma: Add cleanup in omap_dma_probe()
8636e178385b net: seeq: Fix the function used to release some memory in an error handling path
a96b6b408c7e tools/power turbostat: fix buffer overrun
015c9eff13ac sky2: Disable MSI on yet another ASUS boards (P6Xxxx)
a17102c93c25 cifs: Use kzfree() to zero out the password
1456d3cea311 cifs: set domainName when a domain-key is used in multiuser
c8030f7553bc NFSv2: Fix write regression
ccc4f53a7d45 NFSv2: Fix eof handling
1ad4aaa984dc netfilter: nf_conntrack_ftp: Fix debug output
0fe97b245999 x86/apic: Fix arch_dynirq_lower_bound() bug for DT enabled machines
ac49c35cc0aa r8152: Set memory to all 0xFFs on failed reg reads
f1717aab217f ARM: 8874/1: mm: only adjust sections of valid mm structures
77019b608910 Kconfig: Fix the reference to the IDT77105 Phy driver in the description of ATM_NICSTAR_USE_IDT77105
7e536ef98334 NFS: Fix initialisation of I/O result struct in nfs_pgio_rpcsetup
79925a025c49 NFSv4: Fix return values for nfs4_file_open()
a8c60149c00b s390/bpf: use 32-bit index for tail calls
8459803d5df3 ARM: OMAP2+: Fix omap4 errata warning on other SoCs
efd9998ebfb9 s390/bpf: fix lcgr instruction encoding
851224e62b55 mwifiex: Fix three heap overflow at parsing element in cfg80211_ap_settings
441bb21e68de tty/serial: atmel: reschedule TX after RX was started
9f5c140882b2 serial: sprd: correct the wrong sequence of arguments
ae41539657ce KVM: coalesced_mmio: add bounds checking
ac591429f94c xen-netfront: do not assume sk_buff_head list is empty in error handling
7f32c5f5f8c1 x86/boot: Add missing bootparam that breaks boot on some platforms
996cfd1aea06 media: tm6000: double free if usb disconnect while streaming
20a07e1aadcd USB: usbcore: Fix slab-out-of-bounds bug during device reset
8f4e692ba061 ARC: configs: Remove CONFIG_INITRAMFS_SOURCE from defconfigs
9bf96aad172f MIPS: netlogic: xlr: Remove erroneous check in nlm_fmn_send()
b00c29041eb7 x86/build: Add -Wnoaddress-of-packed-member to REALMODE_CFLAGS, to silence GCC9 build warning
bde9af379c8d crypto: talitos - check data blocksize in ablkcipher.
64aa7ed4482f crypto: talitos - check AES key size
0ad99030b143 driver core: Fix use-after-free and double free on glue directory
b6e216cc5654 clk: rockchip: Don't yell about bad mmc phases when getting
cb02963e0197 MIPS: VDSO: Use same -m%-float cflag as the kernel proper
e3484129eb0f MIPS: VDSO: Prevent use of smp_processor_id()
2a24255bdc2a KVM: nVMX: handle page fault in vmread
ba7f1c934f2e KVM: x86: work around leak of uninitialized stack contents
cb3f9ff61574 KVM: s390: Do not leak kernel stack data in the KVM_S390_INTERRUPT ioctl
eac850cc07a9 genirq: Prevent NULL pointer dereference in resend_irqs()
d63e1c7753bc Btrfs: fix assertion failure during fsync and use of stale transaction
5848e115d797 Revert "MIPS: SiByte: Enable swiotlb for SWARM, LittleSur and BigSur"
305fb9d38b58 tun: fix use-after-free when register netdev failed
b9eeaa30e4ea tipc: add NULL pointer check before calling kfree_rcu
348c123d20b4 tcp: fix tcp_ecn_withdraw_cwr() to clear TCP_ECN_QUEUE_CWR
3c8f7497174f sctp: use transport pf_retrans in sctp_do_8_2_transport_strike
3498083352c6 sctp: Fix the link time qualifier of 'sctp_ctrlsock_exit()'
f1b5406b5f83 sch_hhf: ensure quantum and hhf_non_hh_weight are non-zero
19dc97c98426 net: Fix null de-reference of device refcount
79bf5c3c94f3 isdn/capi: check message length in capi_write()
b2786ad2c111 ipv6: Fix the link time qualifier of 'ping_v6_proc_exit_net()'
5bd616b44fce cdc_ether: fix rndis support for Mediatek based smartphones
7a55aba16c57 bridge/mdb: remove wrong use of NLM_F_MULTI

====================
     09-21-2019
====================


   * device/xiaomi/gemini/
ef3b8b2ef CAF tag: LA.UM.7.5.2.r1-03700-8x96.0
ef828fd04 Add device info HIDL service

   * hardware/interfaces/
d80e1c1a2 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

   * hardware/qcom/audio-caf/msm8996/
8d84b06c Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/media-caf/msm8996/
bbafd00c Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into 9.0

   * kernel/xiaomi/msm-4.4/
aeff9231613b qcacld-2.0: Fix buffer overflow in htt_t2h_msg_handler_fast
5561a0af0705 qcacld-2.0: Add support for report TX failed pkt to upper layer
6d3746835e17 qcacld-2.0: Fix multiple length definition issue in WLAN FW message
075becc521e0 qcacld-2.0: Add CONFIG_MULTI_IF_LOG to support multi if log
536a676adf84 qcacld-2.0: Fix compile error excluding static 11p channels
12a01941306d qcacld-2.0: Send user space about FW CRASHED indication
749b0ae6dc39 qcacld-2.0: Use correct format code in for the type of size_t
937840442bee qcacld-2.0: Validate 11p channel from static channel list
cee29eec543d qcacld-2.0: Revert "RSN IE Update in case of BSS already started"
c14dd5cdc28d qcacld-2.0: Add host tx queue statistic
33bb5486fe21 qcacld-2.0: Add rx time statistic for dump survey
22a054f8482a qcacld-2.0: Adjust loglevel in __wmi_control_rx()
b1551d297444 qcacld-2.0: Adjust CFG_SET_TSF_GPIO_PIN_MAX value to 255
d0100d858dd3 qcacld-2.0: Adjust loglevel in txrx
cc05d70cd1e9 qcacld-2.0: Fix loss of DSRC per packet tx stats
2c42558c3068 qcacld-2.0: Set ini 5g_rssi_penalize_factor as signed integer
8e744e0986a4 qcacld-2.0: Set ini 5g_rssi_boost_threshold as signed integer
fc5b8f117207 qcacld-2.0: Zero sRegulatoryChannel before create new reg entry
e250e7069174 qcacld-2.0: Adjust loglevel in print_hdd_cfg()
ed30acdacb0f qcacld-2.0: Adjust loglevel in print_hdd_cfg()
7a35295a7f7a qcacld-2.0: Fix potential double free in wma_log_supported_evt_handler
3e44d87f1a5f qcacld-2.0: Support to pass HW version to userspace

   * kernel/xiaomi/msm8996/
fc9782024b3c Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' into drivers/staging/qcacld-2.0

   * packages/apps/Contacts/
2465a44cf Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Contacts into HEAD

   * packages/apps/Dialer/
bd439d6ba Revert "Fix in-call buttons layout"

   * packages/apps/Nfc/
8751fc0b Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD

   * packages/apps/PackageInstaller/
d61c91d5 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/PackageInstaller into HEAD

   * packages/providers/DownloadProvider/
772c8c7 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/providers/DownloadProvider into HEAD

   * system/netd/
26017ab Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/netd into HEAD

   * system/tools/hidl/
201c894 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/tools/hidl into HEAD

   * system/update_engine/
3ffcfa0 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/update_engine into HEAD

   * system/vold/
d3faf27 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/vold into HEAD

   * vendor/qcom/opensource/audio/
e052706 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
4751e2f Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
35fcb03 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     09-19-2019
====================


   * device/xiaomi/gemini/
60245cde0 DRM: import missing libops.so from sm8150
76ccf376e adsp: restore stock libadsp_fd_skel.so

   * vendor/xiaomi/
22d9b2b7 adsp: restore stock libadsp_fd_skel.so
b4f5694d DRM: import missing libops.so from sm8150
28f93595 don't copy gnss libs twice
acba925a msm8996-common: Update WFD blobs from LA.UM.7.5.r1-05300-8x96.0
aa2ff50c msm8996-common: Import TUI blobs from LA.UM.7.5.r1-05300-8x96.0
4f2628e4 msm8996-common: Update Time services blobs from LA.UM.7.5.r1-05300-8x96.0
b28702fe msm8996-common: Update Thermal blobs from LA.UM.7.5.r1-05300-8x96.0
3519a00d msm8996-common: Update Sensors blobs from LA.UM.7.5.r1-05300-8x96.0
6d1fa0af msm8996-common: Update Power-off alarm blobs from LA.UM.7.5.r1-05300-8x96.0
9ad4dd7e msm8996-common: Update Postprocessing blobs from LA.UM.7.5.r1-05300-8x96.0
a10d6511 msm8996-common: Update Peripheral manager blobs from LA.UM.7.5.r1-05300-8x96.0
6f37be00 msm8996-common: Update Media blobs from LA.UM.7.5.r1-05300-8x96.0
1ad8276a msm8996-common: Update SoundTrigger blobs from LA.UM.7.5.r1-05300-8x96.0
f8207bd7 msm8996-common: Update Keystore blobs from LA.UM.7.5.r1-05300-8x96.0
6105c410 msm8996-common: Update Graphics blobs from LA.UM.7.5.r1-05300-8x96.0
2efcaca1 msm8996-common: Update Gatekeeper blobs from LA.UM.7.5.r1-05300-8x96.0
f8b58ddf msm8996-common: Update DRM Widevine blobs from Crosshatch - PQ3A.190801.002
801ac418 msm8996-common: Update DRM blobs from LA.UM.7.5.r1-05300-8x96.0

====================
     09-18-2019
====================


   * device/xiaomi/gemini/
47b5b55cf update blobs from LA.UM.7.5.r1-05300-8x96.0

   * kernel/xiaomi/msm-4.4/
4d24a1a073e7 Revert "gemini_defconfig: use HZ_250"
57df86be3826 Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie
8b2011307666 gemini_defconfig: use HZ_250
dbf991f4999f Revert "defconfig: enable CONFIG_THERMAL_QPNP"

====================
     09-17-2019
====================


   * device/xiaomi/gemini/
8fed04bd2 msm8996-common: Remove ANT+

   * kernel/xiaomi/msm-4.4/
812a631eb713 Merge 4.4.193 into kernel.lnx.4.4.r37-rel
e19c5132f78a Linux 4.4.193
35b29a78cc9b vhost: make sure log_num < in_num
8cc953562e2e af_packet: tone down the Tx-ring unsupported spew.
52b0d2ee55ca x86, boot: Remove multiple copy of static function sanitize_boot_params()
f935c9418992 clk: s2mps11: Add used attribute to s2mps11_dt_match
7ab6e38aec38 scripts/decode_stacktrace: match basepath using shell prefix operator, not regex
17b919f0e667 vhost/test: fix build for vhost test
e1b22f7a0b27 xfrm: clean up xfrm protocol checks
949f4ca254dd ALSA: hda/realtek - Fix overridden device-specific initialization
272e1835861e ALSA: hda - Fix potential endless loop at applying quirks
f6b078fe5214 update defconfigs

   * kernel/xiaomi/msm8996/
7690030177f8 defconfig: massive debloat

====================
     09-16-2019
====================


   * device/xiaomi/gemini/
6b8c0189e msm8996-common: Remove wcnss_filter
b44c5c5e3 update sepolicy
703d730ca update qc3 path

   * kernel/xiaomi/msm-4.4/
92c94ebd572c defconfig: enable Maple I/O Scheduler

   * packages/apps/HavocSettings/
912f581 add qc3 control

   * vendor/xiaomi/
c67b27ba msm8996-common: Update DPM blobs from LA.UM.7.5.r1-05300-8x96.0
65287e95 msm8996-common: Update CNE blobs from LA.UM.7.5.r1-05300-8x96.0
80b117cb msm8996-common: Update Bluetooth blobs from LA.UM.7.5.r1-05300-8x96.0
192adf7e msm8996-common: Update ADSP blobs from LA.UM.7.5.r1-05300-8x96.0
94172d93 msm8996-common: Remove ANT+
d32bdb68 msm8996-common: Remove wcnss_filter

====================
     09-15-2019
====================


   * device/xiaomi/gemini/
bf63260b8 Revert "BoardConfig: permissive kernel"

   * external/skia/
e575f19d34 Merge tag 'android-9.0.0_r48' into HEAD
53a4cdce32 Merge remote-tracking branch 'havoc/pie' into HEAD

   * frameworks/opt/telephony/
06beb358e5 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

   * kernel/xiaomi/msm-4.4/
261b23907f37 block: Add Maple I/O Scheduler
01e858995ee7 Defconfig: Disable BCL driver

   * packages/services/Telecomm/
7449c5c1 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/services/Telecomm into pie
7ca655e7 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into pie

