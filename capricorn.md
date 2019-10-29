
====================
     29-10-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ dc8298fd9 rootdir: clean up
 ▪ 492ac6407 rootdir: restore time_daemon
 ▪ 4b0e2e0ef Revert "msm8996-common: Enable clearkey drm plugin v1.2"

 ▼ kernel/xiaomi/msm8996/
 ▪ a8d69ba83556 arm64: configs: capricorn_defconfig: re-enable CONFIG_QPNP_HAPTIC
 ▪ 819f5a572c86 msm: ipa: Move NAT invalid protocol define to uapi
 ▪ ba814dab23e3 vdso: update Makefile

 ▼ vendor/xiaomi/
 ▪ 16dabd70 drop land

====================
     27-10-2019
====================

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ bd391c8c Merge tag 'LA.UM.8.6.r1-02300-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 8ed2382d Merge tag 'LA.UM.8.6.r1-02300-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into lineage-17.0-caf-msm8996

====================
     26-10-2019
====================

 ▼ build/make/
 ▪ e45b51f8b Bump Security String to 2019-10-05

 ▼ frameworks/base/
 ▪ 5af468b200f Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/frameworks/base into pie

 ▼ system/bt/
 ▪ a3bf896be convert <cutils/log.h> to <log/log.h>

 ▼ system/libhwbinder/
 ▪ 502215c Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/system/libhwbinder into HEAD

 ▼ system/netd/
 ▪ 18509eb Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/system/netd into HEAD
 ▪ 0a7d7a5 cutils -> utlis

 ▼ system/nfc/
 ▪ 3e3c750 Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/system/nfc into HEAD

 ▼ system/sepolicy/
 ▪ 945571ac8 Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/system/sepolicy into pie

 ▼ system/update_engine/
 ▪ db14189 Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/system/update_engine into HEAD

====================
     20-10-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ ced4cd99a vendor_prop: add some tweaks
 ▪ 414a17c6b Revert "msm8996: use stock USB hal"
 ▪ c1689093b Revert "msm8996-common: add prop persist.vendor.usb.config.extra"
 ▪ e56f85014 rootdir: update usb to LA.UM.7.5.2.r1-03700-8x96
 ▪ abaef7ebf msm8996-common: Remove firmware class path for kernel firmware loading
 ▪ f1da56a34 msm8996-common: Add /vendor/firmware_mnt/image to firmware_directory path
 ▪ 1f403a6b7 msm8996-common: Change ownership of /vendor/firmware_mnt/image
 ▪ a71f29988 BoardConfig: use gcc 9.2 for TARGET_KERNEL_CROSS_COMPILE_ARM32
 ▪ efda28dbd Revert "msm8996: use vidc from msm8998"

 ▼ frameworks/native/
 ▪ d18488724 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into HEAD

 ▼ kernel/xiaomi/msm8996/
 ▪ ef0d40464b8c defconfig: enable new feature
 ▪ 220e1d5dc2f8 kbuild: clean up link rule of composite modules
 ▪ ac2763b47500 kbuild: improve linker compatibility with lib-ksyms.o build
 ▪ 009b8ad873cf kbuild: remove CONFIG_HAVE_UNDERSCORE_SYMBOL_PREFIX
 ▪ e2ac227e4d20 kbuild: cmd_export_list: tighten the sed script
 ▪ d50e77c8a1cc kbuild: reword help of LD_DEAD_CODE_DATA_ELIMINATION
 ▪ 4a5d45eca787 arm64: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selected
 ▪ ad33fbbaa26c kbuild: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selectable if enabled
 ▪ 61f28a9f8da6 kbuild: LD_DEAD_CODE_DATA_ELIMINATION no -ffunction-sections/-fdata-sections for module build
 ▪ dfbf3ebb4fae kbuild: Fix asm-generic/vmlinux.lds.h for LD_DEAD_CODE_DATA_ELIMINATION
 ▪ bd21964549b1 FROMLIST: BACKPORT: arm64: keep .altinstructions and .altinstr_replacement
 ▪ f5985aab108b arm64: fix LD_DEAD_CODE_DATA_ELIMINATION
 ▪ 7de5d49feffb FROMLIST: kbuild: fix LD_DEAD_CODE_DATA_ELIMINATION
 ▪ 3386608d72f9 kbuild: linker script do not match C names unless LD_DEAD_CODE_DATA_ELIMINATION is configured
 ▪ cf89a0378daf kbuild: keep data tables through dead code elimination
 ▪ aa482dee35cc kbuild: avoid conflict between -ffunction-sections and -pg on gcc-4.7
 ▪ befb5c109437 kbuild: -ffunction-sections fix for archs with conflicting sections
 ▪ fe8e06318321 kbuild: allow archs to select link dead code/data elimination
 ▪ f5abc1c706d8 kbuild: clean up archive rule of built-in.a
 ▪ 8de7b79f4a2e kbuild: remove partial section mismatch detection for built-in.a
 ▪ 97fc33adecba kbuild: link $(real-obj-y) instead of $(obj-y) into built-in.a
 ▪ 2704d9327db1 [kbuild] handle exports in lib-y objects reliably
 ▪ 30ff70969cc8 kbuild: rename real-objs-y/m to real-obj-y/m
 ▪ 71aba6e171b1 kbuild: drop $(extra-y) from real-objs-y
 ▪ 150eceece93c kbuild: Allow to specify composite modules with modname-m
 ▪ 1dd33e7d5f44 kbuild: create built-in.o automatically if parent directory wants it
 ▪ 2f1dd3abf0d4 kbuild: rename built-in.o to built-in.a
 ▪ f2bf961520b5 kbuild: remove incremental linking option
 ▪ 9225f8d9b72d kbuild: handle libs-y archives separately from built-in.o archives
 ▪ c75cf715bc0d kbuild: thin archives make default for all archs
 ▪ 43d00c00983d kbuild: thin archives use P option to ar
 ▪ 1711bc67dc28 kbuild: thin archives for multi-y targets
 ▪ a5dc222086eb kbuild: thin archives final link close --whole-archives option
 ▪ c1825316834d kbuild: minor improvement for thin archives build
 ▪ e88419826e62 kbuild: allow architectures to use thin archives instead of ld -r
 ▪ 5e25a2124a98 Makefile: add minimal flags
 ▪ 0d8744662235 Makefile: opt-out from 835769/843419 errata fixes
 ▪ 0357f18eea97 Makefile: O3 it up for host executables

====================
     19-10-2019
====================

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 22478dcb audio-hal: always treat v4 as NULL

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ d9ba2d86 msm8996: use generated kernel headers
 ▪ 4b2e84a6 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into lineage-17.0-caf-msm8996

====================
     15-10-2019
====================

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ e3257a17 Merge 872acb95ba1f98e59b7f7dc5888edbe6a6418475 on remote branch

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ bfb392fd Merge d417d8eee0c1264d7da6230d36db7a6fcee125ef on remote branch

====================
     14-10-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 7d11f9983 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/common into HEAD
 ▪ 1fe195bc6 Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/device/common into HEAD

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 8094d5ef correct audio features for gemini

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 489859014 Merge tag 'LA.UM.7.4.r1-05700-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD

 ▼ kernel/xiaomi/msm8996/
 ▪ 45d41f42d4f8 Bluetooth: Fix regression with minimum encryption key size alignment
 ▪ 9808efed03ea skge: fix checksum byte order
 ▪ 6080d7be9127 sch_netem: fix a divide by zero in tabledist()
 ▪ 5120f1a0aa51 openvswitch: change type of UPCALL_PID attribute to NLA_UNSPEC
 ▪ a8a805103e99 net/phy: fix DP83865 10 Mbps HDX loopback disable function
 ▪ bfc754d46523 cdc_ncm: fix divide-by-zero caused by invalid wMaxPacketSize
 ▪ e74760286bb5 ASoC: fsl: Fix of-node refcount unbalance in fsl_ssi_probe_from_dt()
 ▪ e7e48dbd81fe mtd: cfi_cmdset_0002: Use chip_good() to retry in do_write_oneword()
 ▪ eac82785e60f HID: hidraw: Fix invalid read in hidraw_ioctl
 ▪ bd091567fc8b HID: lg: make transfer buffers DMA capable
 ▪ b00700543eb8 HID: prodikeys: Fix general protection fault during probe
 ▪ 7826c0499717 media: technisat-usb2: break out of loop at end of buffer
 ▪ b804f7682fb0 mwifiex: Fix three heap overflow at parsing element in cfg80211_ap_settings
 ▪ 1e076858b0bd KVM: coalesced_mmio: add bounds checking
 ▪ c79477dac963 media: tm6000: double free if usb disconnect while streaming
 ▪ b6512600afac crypto: talitos - check data blocksize in ablkcipher.
 ▪ 3bfc73a8870c crypto: talitos - check AES key size
 ▪ 8b0ded0609e2 genirq: Prevent NULL pointer dereference in resend_irqs()
 ▪ 42e2ceead5ff tun: fix use-after-free when register netdev failed
 ▪ c76bd47f8a4a tcp: fix tcp_ecn_withdraw_cwr() to clear TCP_ECN_QUEUE_CWR
 ▪ ed260d244cd0 sctp: Fix the link time qualifier of 'sctp_ctrlsock_exit()'
 ▪ 991af43ea325 sch_hhf: ensure quantum and hhf_non_hh_weight are non-zero
 ▪ 607c1d711971 net: Fix null de-reference of device refcount
 ▪ 22d5557ce264 isdn/capi: check message length in capi_write()
 ▪ c74ed225324a ipv6: Fix the link time qualifier of 'ping_v6_proc_exit_net()'
 ▪ 0040f23bb049 net_sched: let qdisc_put() accept NULL pointer
 ▪ fada34a3a9cc vhost: make sure log_num < in_num
 ▪ 87eab9883343 xfrm: clean up xfrm protocol checks
 ▪ 057c93598fb2 ALSA: hda - Fix potential endless loop at applying quirks
 ▪ b5dedf3ba3fc ovl: filter of trusted xattr results in audit
 ▪ f2e560ab9e13 NFC: fix attrs checks in netlink interface
 ▪ 60d9016d7bdc Smack: Don't ignore other bprm->unsafe flags if LSM_UNSAFE_PTRACE is set
 ▪ 6b00756e3db3 sch_cbq: validate TCA_CBQ_WRROPT to avoid crash
 ▪ 344f22a7d70f net/rds: Fix error handling in rds_ib_add_one()
 ▪ 99b6f7c840c7 sch_dsmark: fix potential NULL deref in dsmark_init()
 ▪ 848792540504 nfc: fix memory leak in llcp_sock_bind()
 ▪ 758a02e91b32 net: qlogic: Fix memory leak in ql_alloc_large_buffers
 ▪ 7459e8dcc06f net: ipv4: avoid mixed n_redirects and rate_tokens usage
 ▪ 70af816b2aa7 ipv6: drop incoming packets having a v4mapped source address
 ▪ 8fea9ec0156b hso: fix NULL-deref on tty open

 ▼ vendor/havoc/
 ▪ 97625f53 update Lawnchair to alpha-2500

====================
     13-10-2019
====================

 ▼ hardware/interfaces/
 ▪ e48a12518 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 4997af15 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 2ccf5291f Merge tag 'LA.UM.7.2.r2-02600-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD

 ▼ kernel/xiaomi/msm8996/
 ▪ 62d21821bb96 msm: kgsl: Make the "scratch" global buffer use a random GPU address
 ▪ 0b4b79344b35 msm: kgsl: Use a bitmap allocator for global addressing
 ▪ d33d8c6f92b2 defconfig: msm: Disable EXT2 and EXT3 FS configs for MSM8937/53
 ▪ 310033e9c202 msm: kgsl: Change data type for GPU ib vote
 ▪ db6ea37dca6f icnss: Add check on msa region
 ▪ 200cef711098 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' into drivers/staging/qcacld-2.0

 ▼ vendor/qcom/opensource/audio/
 ▪ cd76f92 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 6daae03 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     10-10-2019
====================

 ▼ build/make/
 ▪ d7e8a3d4c update gcc to 9.2

 ▼ build/soong/
 ▪ 326e8dfe update gcc to 9.2

 ▼ device/xiaomi/gemini/
 ▪ 76027807d msm8996-common: configs: Remove 2 instance support for "primary input"
 ▪ 5b124957e msm8996-common: Enable clearkey drm plugin v1.2
 ▪ 4a6581204 msm8996-common: bluetooth: Push×pop PROPERTY_VALUE_MAX in buildcfg header
 ▪ a448126a9 msm8996-common: Append 'Xiaomi' to BT name
 ▪ b36bb3477 merge bdroid_buildcfg.h
 ▪ 92f2cc732 change HAVOC_BUILD_TYPE logic
 ▪ 5dc0221d3 drop wcnss_filter sepolicy rules
 ▪ 78cab3a55 Restore ANT+
 ▪ 9f4829bb6 gps: LocIpc derefs nullptr if stopping blocking listener
 ▪ f4e45070a gps: Set SV in use mask based on final fixes
 ▪ c1267fabe overlays: move some values to fwb
 ▪ 344d9285f move PRODUCT_BRAND var back to $(PRODUCT_NAME).mk
 ▪ ef3b8b2ef CAF tag: LA.UM.7.5.2.r1-03700-8x96.0
 ▪ ef828fd04 Add device info HIDL service
 ▪ 60245cde0 DRM: import missing libops.so from sm8150
 ▪ 76ccf376e adsp: restore stock libadsp_fd_skel.so
 ▪ 47b5b55cf update blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 8fed04bd2 msm8996-common: Remove ANT+
 ▪ 6b8c0189e msm8996-common: Remove wcnss_filter
 ▪ b44c5c5e3 update sepolicy
 ▪ 703d730ca update qc3 path
 ▪ bf63260b8 Revert "BoardConfig: permissive kernel"
 ▪ 307af7fc2 build stock health service
 ▪ 274bc5e9d update some LOG_TAGs
 ▪ 0dcd1042a update vendorsetup.sh
 ▪ 7c1a8177c add new path for /sys/class/power_supply/bms/charge_full

 ▼ external/ant-wireless/ant_service/
 ▪ f760ac5 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/external/ant-wireless/ant_service into HEAD

 ▼ external/chromium-webview/
 ▪ b6acc67 Update Chromium Webview to 77.0.3865.116
 ▪ 880977b Update Chromium Webview to 77.0.3865.92

 ▼ external/icu/
 ▪ e6af4b830 DO NOT MERGE: Update tzdb version from 2019b to 2019c

 ▼ external/skia/
 ▪ e575f19d34 Merge tag 'android-9.0.0_r48' into HEAD
 ▪ 53a4cdce32 Merge remote-tracking branch 'havoc/pie' into HEAD

 ▼ frameworks/av/
 ▪ 0e48c9ceeb Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/frameworks/av into HEAD

 ▼ frameworks/base/
 ▪ bc18bee45f6 overlays: move some values from device path
 ▪ 2b6a876c26c Fix StatusBarWifiView applying the wrong wifi icon
 ▪ 99f0c371324 Update systemui wifi icons to GM2.
 ▪ c5928fc6d24 Use frameworks wifi icons instead of sysui
 ▪ 0fb34399374 Invalidate SignalDrawable on level change.
 ▪ 982c6d76afe Update SignalDrawable to show X for empty state
 ▪ c8451758fd4 Update SignalDrawable.
 ▪ 57d29075358 Update systemui animations to GM2.
 ▪ e4b34a1aa23 Remove unused badged wifi API/drawables.
 ▪ 93a98f034f1 SettingsLib: Update Utils APIs usage
 ▪ eae8c644bcc KeyguardSliceView: Improve Alignment

 ▼ frameworks/opt/telephony/
 ▪ 06beb358e5 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

 ▼ hardware/interfaces/
 ▪ 410cad195 Merge 063247cc2a3cbd90f52bf1de191bad17d6a3d961 on remote branch
 ▪ f7d2262e1 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 0564c3370 Merge 063247cc2a3cbd90f52bf1de191bad17d6a3d961 on remote branch
 ▪ ad3e3bc69 replace <cutils/log.h> with <log/log.h>
 ▪ d80e1c1a2 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 063247cc2 Snap for 5883521 from 905279fe6d022910938a67c6c32f615405cdc075 to p-keystone-qcom-release
 ▪ 905279fe6 Increase initWithMmapSize to 32k for cas service

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ de34d823 Merge 6b015e0b353fedf409a5c5ecf51582308341e462 on remote branch
 ▪ 17c900ad Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ 6b015e0b Merge "A2dp: Send default channel mapping for TWS+ mono." into audio-hal.lnx.5.0
 ▪ 637433f5 Merge "hal: Unload modem wrt peripheral manager update" into audio-hal.lnx.5.0
 ▪ 052dba06 Merge d033707810af0d64b1df7c9e8684ea6209783d32 on remote branch
 ▪ 872acb95 Merge "configs:sdm429: Add mixer ctl for Headphone and WSA combo" into audio-hal.lnx.5.0.c5
 ▪ 06e2b9a2 Merge "hal: Allow hal to open Telephony RX as attached device" into audio-hal.lnx.5.0.c5
 ▪ 6e8c782c Merge "hal: fix voip usecase selection for voice_tx path" into audio-hal.lnx.5.0.c5
 ▪ 8d84b06c Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ 5781b50b hal: Allow hal to open Telephony RX as attached device
 ▪ 7c73061b hal: Allow hal to open Telephony RX as attached device
 ▪ ca521c57 configs:sdm429: Add mixer ctl for Headphone and WSA combo
 ▪ 6ec3f1cb A2dp: Send default channel mapping for TWS+ mono.
 ▪ 2025baa7 hal: Unload modem wrt peripheral manager update
 ▪ a556d3a2 configs:sdm429: Add mixer ctl for Headphone and WSA combo
 ▪ c54f03b3 Merge 8588718cb0cf7ee2fc977135b807e44fe4e171b4 on remote branch
 ▪ 25d77b76 Merge accff5940e271f72dcc2301ff9f9dc3eae2322ae on remote branch
 ▪ d0337078 Merge "hal: fix for voice call fails with usb-headphone"
 ▪ 00444a13 hal: fix voip usecase selection for voice_tx path

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 6573821c media: Don't link libgpustats
 ▪ eadb4951 media: Add extrapolated gpustats header for PQ
 ▪ 37ca2142 media: libOmxSw encoders require prop headers :(
 ▪ abdaa6ba venc: Fix VQZip issue
 ▪ 26f4dc5a media: Use project pathmap
 ▪ d417d8ee mm-video-v4l2: vdec: Correct order of reading color primaries
 ▪ b3702481 Merge b107ffda0d09d62628456a2a9c373585c5ccf843 on remote branch
 ▪ b107ffda mm-video-v4l2: venc: handle use after free on venc_dev

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ f2b45b2bc Merge 321949846222a4726f0ea90ff115fb9c5c5a0bc8 on remote branch
 ▪ 919063e04 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD
 ▪ c6656a5c0 Merge c89450b6a36d1a73bd97843d73e5656294a09858 on remote branch
 ▪ 0273e0eaf Merge c89450b6a36d1a73bd97843d73e5656294a09858 on remote branch
 ▪ 6f6a18573 fix build
 ▪ 0d6147e1d Merge tag 'LA.UM.7.2.r2-02200-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into lineage-16.0-caf-8998

 ▼ kernel/xiaomi/msm8996/
 ▪ 5154ab91138d Merge 442f13d9530d094814d5d6626149e19b8eae331e on remote branch
 ▪ a095cd303834 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into 9.0
 ▪ fc9782024b3c Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 452d3a1d855b Merge 8a0fcb0d8e45c03a63c979b911c47d5932d1e730 on remote branch
 ▪ 7690030177f8 defconfig: massive debloat
 ▪ 18dc616aef3b drop anykernel3
 ▪ 72d47b0a35be update kconfig from 4.4
 ▪ c09e8a52ea2a capricorn: clean up dtsi
 ▪ 568ff0f66c88 update capricorn_defconfig
 ▪ 442f13d9530d Merge "qcacld-2.0: Convert peer RSSI to dBm unit" into wlan-cld2.driver.lnx.1.0

 ▼ packages/apps/Contacts/
 ▪ 2465a44cf Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Contacts into HEAD

 ▼ packages/apps/Dialer/
 ▪ bd439d6ba Revert "Fix in-call buttons layout"

 ▼ packages/apps/HavocSettings/
 ▪ 912f581 add qc3 control

 ▼ packages/apps/Nfc/
 ▪ 8751fc0b Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD

 ▼ packages/apps/PackageInstaller/
 ▪ d61c91d5 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/PackageInstaller into HEAD

 ▼ packages/apps/Settings/
 ▪ 1374c956d3 add SearchIndexProvider into HavocSettings [2/2]
 ▪ 10f01e413b Support to notify connected/disconnected stations
 ▪ e0d9c55902 Havoc Build Date [2/2]
 ▪ 0029aacfca DeviceInfoSettings: Bring back CAF/AOSP tags
 ▪ 0bb8d41306 my colors
 ▪ 60c187f11f Revert "Revert "Settings: Add toggle for proximity wake""
 ▪ 7ba50f2dd9 SettingsLib: Update Utils APIs usage

 ▼ packages/providers/DownloadProvider/
 ▪ 772c8c7 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/providers/DownloadProvider into HEAD

 ▼ packages/services/Telecomm/
 ▪ 7449c5c1 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/services/Telecomm into pie
 ▪ 7ca655e7 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into pie

 ▼ system/bt/
 ▪ 635243f0f Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
 ▪ 45b4ca732 RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
 ▪ 9d6bbb79e sdclang: true
 ▪ a466f7342 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

 ▼ system/core/
 ▪ 268c4a3d8 Allow adb root even in no debuggable builds

 ▼ system/timezone/
 ▪ e2ed9ed DO NOT MERGE: Update tzdb version from 2019b to 2019c

 ▼ system/tools/hidl/
 ▪ 201c894 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/tools/hidl into HEAD

 ▼ system/vold/
 ▪ d3faf27 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/vold into HEAD

 ▼ vendor/nxp/opensource/commonsys/external/libnfc-nci/
 ▪ 145f3dd fix warnings

 ▼ vendor/qcom/opensource/audio/
 ▪ ccf33dc Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ e052706 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ c0ba834 Merge 630c0c52c08b00b26efc82402a8e1b82bd65410a on remote branch

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ e3e4246 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ 4751e2f Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 6ae63b5 Merge b8e4183b95aa72ad25ff2bdd1890cf73003f0030 on remote branch
 ▪ f45d900 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ fbd0516 Merge b8e4183b95aa72ad25ff2bdd1890cf73003f0030 on remote branch
 ▪ 35fcb03 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ b8e4183 Merge "camera: Add offline post processor service support"
 ▪ 75aca03 Merge a9ab3a736069433263319c4c30dcae2340e66efb on remote branch
 ▪ 4547654 camera: Add offline post processor service support

 ▼ vendor/xiaomi/
 ▪ 2ea7c304 Revert "msm8996-common: Update Bluetooth blobs from LA.UM.7.5.r1-05300-8x96.0"
 ▪ 4e85d19a msm8996-common: Restore ANT+
 ▪ 10feabd2 convert some modules to Android.bp
 ▪ 22d9b2b7 adsp: restore stock libadsp_fd_skel.so
 ▪ b4f5694d DRM: import missing libops.so from sm8150
 ▪ 28f93595 don't copy gnss libs twice
 ▪ acba925a msm8996-common: Update WFD blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ aa2ff50c msm8996-common: Import TUI blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 4f2628e4 msm8996-common: Update Time services blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ b28702fe msm8996-common: Update Thermal blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 3519a00d msm8996-common: Update Sensors blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 6d1fa0af msm8996-common: Update Power-off alarm blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 9ad4dd7e msm8996-common: Update Postprocessing blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ a10d6511 msm8996-common: Update Peripheral manager blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 6f37be00 msm8996-common: Update Media blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 1ad8276a msm8996-common: Update SoundTrigger blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ f8207bd7 msm8996-common: Update Keystore blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 6105c410 msm8996-common: Update Graphics blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 2efcaca1 msm8996-common: Update Gatekeeper blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ f8b58ddf msm8996-common: Update DRM Widevine blobs from Crosshatch - PQ3A.190801.002
 ▪ 801ac418 msm8996-common: Update DRM blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ c67b27ba msm8996-common: Update DPM blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 65287e95 msm8996-common: Update CNE blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 80b117cb msm8996-common: Update Bluetooth blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 192adf7e msm8996-common: Update ADSP blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 94172d93  msm8996-common: Remove ANT+
 ▪ d32bdb68 msm8996-common: Remove wcnss_filter

====================
     09-10-2019
====================
 ▼ art/
 ▪ 5ab5014a30 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/art into pie
 ▪ 34b265e528 Stop verifying barrier count for thread dumping
 ▪ 2df00fa1ba ART: Cache type index validity

 ▼ build/make/
 ▪ 4a4a6d7ae Bump Security String to 2019-09-05
 ▪ e8c0b4528 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/build into pie
 ▪ c70a05174 More base_rules.mk optimizations
 ▪ d67269190 Skip much of aux_config.mk

 ▼ development/
 ▪ dbfc71e8b development: Ship a 64-bit libc++.dylib in platform-tools

 ▼ device/havoc/sepolicy/
 ▪ 026aa69 rebase recovery sepolicy
 ▪ 51fb5c7 sepolicy: allow recovery to setenforce
 ▪ 49c4912 sepolicy: Add hal_lineage_fod domain
 ▪ 56c6e21 sepolicy: Add hal_lineage_camera_motor domain
 ▪ 1f3d89e Remove minivold rules
 ▪ 6e4e66b rebase lineage hals
 ▪ 7613b59 sepolicy: qcom: Label /d/rpmh
 ▪ 8d70dde sepolicy: Dontaudit sysinit
 ▪ 5c6b061 sepolicy: Add rules for Long screenshot service
 ▪ 1c43941 sepolicy: Guard neverallowed policy for system_file with userdebug/eng

 ▼ device/qcom/sepolicy/
 ▪ d0cebf3d Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into HEAD
 ▪ 5af3c127 Merge 8f95d283c2394faafdff47d9f3f5b94f577b0ab4 on remote branch
 ▪ 3bdd56f4 Merge tag 'LA.UM.7.6.2.c1-03100-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into HEAD

 ▼ device/xiaomi/gemini/
 ▪ 74b87c7c0 Android tag: 9.0.0_r48, CAF: LA.UM.7.6.r1-05900-89xx.0
 ▪ 0dc0d601b build 4.4 by default
 ▪ d990efc2b msm8996-common: manifest: Disable IDisplayModes for livedisplay
 ▪ 357a83516 BoardConfig: switch to gcc 9.2.0 for inline kernel building
 ▪ 7f78d0693 rootdir: drop 'eng' tag
 ▪ 4c067a59a rootdir: kang configfs from nile-common
 ▪ 2bb7d888b BoardConfig: permissive kernel
 ▪ 138aa3192 msm8996: add missing libs
 ▪ aae7bf47c msm8996: Add libmm-omxcore.so required by libOmxVpp.so
 ▪ 7ac48ccfb msm8996-common: add prop persist.vendor.usb.config.extra
 ▪ 4fc610547 msm8996: use vidc from msm8998
 ▪ fbdf18994 msm8996: use stock USB hal
 ▪ f688b74fa update vendorsetup.sh
 ▪ a2e50a59d rebase configpanel new
 ▪ 36a1510a2 build syberia capricorn
 ▪ a258edd52 capricorn: set some vibration patterns
 ▪ 250a78fc6 msm8996-common: sepolicy: Allow readfem to use msm_sock_ipc_ioctls
 ▪ b72bfe1b7 msm8996-common: add QC3 permissions
 ▪ ef5676996 Merge tag 'android-9.0.0_r47' into 9.0
 ▪ a876a0dc4 update priv_app sepolicy

 ▼ device/xiaomi/translations/
 ▪ 5702263 move ru translations to fwb [1/2]
 ▪ f832815 remove obsolete Updater translations
 ▪ 1274136 Bangla translation
 ▪ 12c6ba3 update ru

 ▼ external/ant-wireless/ant_service/
 ▪ f6bc0db Merge 200fcc9565814288bd2cfe7c81620b6dea3a75d7 on remote branch

 ▼ external/chromium-webview/
 ▪ 8b3f380 Update Chromium Webview to 76.0.3809.111

 ▼ external/libcups/
 ▪ 8a9a6ce Fix heap buffer overflow in ipp.c

 ▼ external/libhevc/
 ▪ 9108295 decoder: Fix valid SPS check in parsing SEI

 ▼ external/toybox/
 ▪ 232850b4 Regenerate config files
 ▪ d3b8f503 Fix cp -r dir/. symlink child.
 ▪ 10538639 Add failing test for cp -r dir/. symlink child.
 ▪ beef651d Fix cp permissions when copying symlink contents, and add test.
 ▪ c078b2b6 Implement --preserve default = mot behavior (fixes segfault when no argument).
 ▪ 50a83f51 Fix "cp -p" doesn't preserve timestamps bug
 ▪ f11efa35 Add cp --parents
 ▪ c113fb14 Add mkpath() for common case of mkpathat(), and #define magic constants.

 ▼ frameworks/av/
 ▪ dd944d0830 audiopolicy: Fixes for internal audio recording

 ▼ frameworks/base/
 ▪ d48f2a23e0e SystemUI: Allow SystemUI WRITE_APN_SETTINGS
 ▪ 63e1c188d98 base: seekbar: Increase bottom padding
 ▪ d5d62f2af61 base: media_seekbar: make it sexy
 ▪ dd3f9cb28c0 SystemUI: Whitelist our recorder on CastController
 ▪ 7346f4f89ed VolumeDialogControllerImpl: Check for internal audio recording support
 ▪ 562e7094c49 QSTileHost: Recreate tiles when LiveDisplay gets initialized
 ▪ e9dc6c7f2a0 Revert "LiveDisplayTile: Remove tile if unavailable"
 ▪ d41fcc067f8 Better QS detail clip animation
 ▪ b0cdd3be0de fw/b: Use common network restrict apps method
 ▪ 31ec3c3185a SystemUI: Allow for notch view to be ignored
 ▪ 5d8fb38a43e base: Add toggle for OP gestures haptic feedback [1/2]
 ▪ 9e6a384003d Allow override of DUN settings
 ▪ 396656ae826 SystemUI: CellularTile: Improve layout
 ▪ 9fd08954ab1 SystemUI: Add default data sub switcher in CellularTile
 ▪ 189821a286c base: Add Circle battery style from PA [1/2]
 ▪ c37ddff12fe base: Add 2 more date styles [1/2]
 ▪ 88450ed0a74 base: Add more date styles [1/2]
 ▪ e98768bcea9 Introduce lockscreen date styles [1/2]
 ▪ 9587d5403f4 base: Cleanup Screenrecord
 ▪ 42fabfa873f Fix Google Markup FC
 ▪ 871ef9888c4 Updated Bangla translation
 ▪ bbcd5829151 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/frameworks/base into HEAD
 ▪ ffeecb46478 Fix typo
 ▪ 28eaf291c27 make some strings untranslatable
 ▪ aaa0cd2bdf0 move ru translations to fwb [2/2]
 ▪ e19df829405 fix aapt2 warnings
 ▪ 54c8606e2fe Fix binder leakage when turning off Bluetooth
 ▪ 3cf47e8298b longshot: set timeout to 1,8 sec
 ▪ ae6032cccef SystemUI: Q clock: update polish translation
 ▪ 0bdc4050e0a LiveDisplayTile: Remove tile if unavailable
 ▪ 206c6f12708 LiveDisplayTile: Refresh state after livedisplay initialization
 ▪ 75e58677691 LiveDisplayTile: Enable for outdoor mode and skip night display on HWC2
 ▪ 51ea98a01eb LiveDisplayService: Notify SystemUI after initialization finished
 ▪ 5598f83653e LiveDisplayManager: Perform null check in getConfig()
 ▪ 61cae206856 OutdoorModeController: Unconditionally enable auto mode on HWC2
 ▪ 874d18fb3e2 OutdoorModeController: Advertise MODE_AUTO
 ▪ 3d244390979 LiveDisplayService: Properly disable ColorTemperature
 ▪ 6e15221dc96 LiveDisplay: Cleanup
 ▪ 650e8596148 FOD: Differentiate dreaming and pulse
 ▪ d3fb65589f4 Initial support for in-display fingerprint sensors
 ▪ 642f8024457 Revert "Initial support for OnePlus in-display fingerprint sensor"
 ▪ 721bf436e5a BatteryEstimates: Toggle without SystemUI restart
 ▪ 2c5fb021aa4 SystemUI: Tiny expanding improvement
 ▪ 761e1e0c0e5 NotificationColorUtil: Kill logspam
 ▪ d3bdecb0e78 fwb: Port extended screenshot function from OOS
 ▪ a8126895cbb fwb: Add support for internal audio recording
 ▪ f87b7aa33dd Remove uses of libcore.io DropBox and EventLogger
 ▪ 589c568157b SystemUI: Use matching data usage size formatting between QS and Settings
 ▪ 1108aebc76b Update Xbox BT controller mapping to support upcoming controller firmware update
 ▪ dfdf7e48778 Add keylayout for Xbox One USB controller
 ▪ 4864977450e Keylayout for xbox controllers
 ▪ 04f86a78547 Added mapping files for DualShock3 and DualShock4
 ▪ e1806919412 Fallback BUTTON_MODE to HOME
 ▪ 00083e425fc Remap PS key to BUTTON_MODE
 ▪ 277ff7bd558 Set default VR_MODE based on VR feature support
 ▪ f83536e16ba fw/b: Add capability to allow tethering to use VPN upstreams
 ▪ 762a3e11923 power: Respect global vibration setting for charging sounds
 ▪ 447967c8757 Fix wrong locale causing reboot in recovery
 ▪ de4538b0d54 Correction in logic of roundend size calculation of SD card
 ▪ ca8316ed2bf SystemUI: Q clock translation: remove unneeded extra quotes
 ▪ 69f38582d34 Fix type header clock strings for Q Clock
 ▪ c127a92f970 ViewRootImpl: set max fling ticks per sec to 24
 ▪ 77f02765291 SystemUI: fix constant FC on certain devices after b20262a40fcf2f73a1faf0e57dd3971534be8951
 ▪ 237d952e484 base: Improve haptic feedback for some UI elements
 ▪ c396740865c don't import unused protos

 ▼ frameworks/native/
 ▪ 6929ebac2 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/frameworks/native into HEAD
 ▪ b269a6eb1 Merge c045dac2f64d369c6d5563ff8c5fe224d7d8183d on remote branch
 ▪ a595fda8a SurfaceFlinger: Exclude CAF extensions from non-QC devices

 ▼ frameworks/opt/net/ims/
 ▪ e6a6853 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

 ▼ frameworks/opt/telephony/
 ▪ 07b8a114b1 Merge a6ee76d6daaa9811d6271e4ead2440932144826f on remote branch

 ▼ hardware/havoc/interfaces/
 ▪ 3188b3b IFingerprintInscreen: Allow HALs to control position and size
 ▪ 633cc27 IFingerprintInscreen: Allow HALs to provide finger up/down callback
 ▪ 0c2a47a IFingerprintInscreen: Allow HALs to control dimming
 ▪ 8c64861 Introduce in-screen fingerprint scanner HAL

 ▼ hardware/interfaces/
 ▪ 5e1979a96 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 37fe7a697 Merge c32fb753175acf76009a48ff0202739681e8f5ef on remote branch
 ▪ 64c21b6ed Merge c32fb753175acf76009a48ff0202739681e8f5ef on remote branch

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ e7e9c07b Merge "configs: Add button click suppression mixer for wcd937x and trinket"
 ▪ 8588718c Merge "hal: fix voip usecase selection for voice_tx path"
 ▪ b0ae275b Merge ff19193b8102a0801eeebf664a6a892d67830795 on remote branch
 ▪ eb9999c2 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ b5518438 config: msm8953: enable Audio HIDL HAL 5.0
 ▪ 687bb917 Merge "hal: Call into v4 version of acdb loader send audio cal"
 ▪ 3fe883a2 fm: Restore fm on Speaker
 ▪ 90ba026a Merge ff19193b8102a0801eeebf664a6a892d67830795 on remote branch
 ▪ d986042b hal: fix voip usecase selection for voice_tx path
 ▪ 524bd341 hal: fix voip usecase selection for voice_tx path
 ▪ 05aed289 audio: free and assign NULL to global static device pointer
 ▪ d50bd104 hal: Call into v4 version of acdb loader send audio cal
 ▪ 250a5009 Merge d7904b037deaedfdf4239b08486970029813c34b on remote branch
 ▪ f88c5eb6 hal: fix for voice call fails with usb-headphone
 ▪ a9fde13f Merge 1244b1f5090eb9c5c57692d82cfc7f56983fddba on remote branch
 ▪ ff19193b hal: MS12: qap test app update

 ▼ hardware/qcom/bt-caf/
 ▪ 3b4dc64 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into 9.0
 ▪ 76e8842 libbt-vendor: use generated kernel headers

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ 65a4789b Revert "Revert "display: Define soong namespace""

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ f754b5bc Merge 98b291fce23cf547b963fb87e9cbc1d42abe7b51 on remote branch
 ▪ ec714736 Merge fbffc2bb6526ed05e16e011c1281d7d8c97be26c on remote branch

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ c89450b6a Fix for 4k60fps video clip performance issue
 ▪ 8d6a4e37a Merge fbffc2bb6526ed05e16e011c1281d7d8c97be26c on remote branch
 ▪ 78613a577 Merge tag 'LA.UM.7.4.r1-05500-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into lineage-16.0-caf-8998
 ▪ 321949846 mm-video-v4l2: Enable secure C2D in encoder
 ▪ 2830667f0 Merge fbffc2bb6526ed05e16e011c1281d7d8c97be26c on remote branch
 ▪ 97ff9048e Merge 57beea57153a8d6c4ca6b0aade333f68edd0c06b on remote branch

 ▼ kernel/xiaomi/msm8996/
 ▪ b7448bab51ac qcacld-2.0: Convert peer RSSI to dBm unit
 ▪ 8a0fcb0d8e45 qcacld-2.0: Disable adf_nbuf_unmap_debug for HL platform
 ▪ b8423a65ca76 Merge "qcacld-2.0: Add interface for getting multicast group info" into wlan-cld2.driver.lnx.1.0
 ▪ 83110a695a83 qcacld-2.0: Fix compile issue on vos_utils and IFNAME_SUFFIX
 ▪ cd9414d4f520 Merge "qcacld-2.0: Enlarge timeout value for reg_notifier" into wlan-cld2.driver.lnx.1.0
 ▪ 0966b5ba69d3 qcacld-2.0: Add interface for getting multicast group info
 ▪ 5822c3a08843 Merge "qcacld-2.0: refine timer_list callback function" into wlan-cld2.driver.lnx.1.0
 ▪ 61d880b48df2 Merge "qcacld-2.0: Update driver timer APIs according to kernel 4.19" into wlan-cld2.driver.lnx.1.0
 ▪ 5a337b998366 Merge "qcacld-2.0: ndo_select_queue support for 4.19 kernel" into wlan-cld2.driver.lnx.1.0
 ▪ dd57c92ffa86 Merge "qcacld-2.0: Configure sdio cccr values in Kbuild" into wlan-cld2.driver.lnx.1.0
 ▪ 06c651e75c72 Merge "qcacld-2.0: Porting onto 4.14 kernel for QCS405" into wlan-cld2.driver.lnx.1.0
 ▪ 49f485819de8 qcacld-2.0: Configure sdio cccr values in Kbuild
 ▪ b0c2d8d8c596 qcacld-2.0: Porting onto 4.14 kernel for QCS405
 ▪ e9141c2f63c6 qcacld-2.0: Enlarge timeout value for reg_notifier
 ▪ 00d99f8b6994 qcacld-2.0: Add support for wlm latency configurations
 ▪ 318c3eafa558 Merge "qcacld-2.0: Enable dma map/unmap api only for PCIE device" into wlan-cld2.driver.lnx.1.0
 ▪ f728e1edad69 qcacld-2.0: Refine vos_lock init for host tx queue statistic
 ▪ ff78610a1934 Merge 5e4e63fd28a8daf4c3d3382828e7c486da461f96 on remote branch
 ▪ 9a8c69b42ac4 Merge 6a01c51101b6b61d2ec9843f8f182c26fac5c3aa on remote branch
 ▪ 3f78478bf5d4 Merge 3b0f8c123142cfbd5cd41a12b7a2ddf4469d3288 on remote branch
 ▪ 5b0fb7657bb0 Merge "qcacld-2.0: Fix report error band width after switch to 5/10M mode" into wlan-cld2.driver.lnx.1.0
 ▪ 5e4e63fd28a8 ASoC: msm: qdsp6v2: add support for AMR_WB_PLUS offload
 ▪ 2ec527cd8c01 qcacld-2.0: Fix report error band width after switch to 5/10M mode
 ▪ 4a4e40373739 Merge "qcacld-2.0: Add interface for audio multicast group setting" into wlan-cld2.driver.lnx.1.0
 ▪ 6b6ba82da36d qcacld-2.0: Add interface for audio multicast group setting
 ▪ cc91c1d8cc92 qcacld-2.0: refine timer_list callback function
 ▪ ce4272f2dc08 qcacld-2.0: Update driver timer APIs according to kernel 4.19
 ▪ 4cfd8a32b0c7 qcacld-2.0: ndo_select_queue support for 4.19 kernel
 ▪ 7d69ea3ea229 qcacld-2.0: limit time for scan when miracast is running
 ▪ ec135114d34b Merge "qcacld-2.0: CL 6874312 - CL 7913653 Update fw common interface files" into wlan-cld2.driver.lnx.1.0
 ▪ e20509443f6b qcacld-2.0: CL 6874312 - CL 7913653 Update fw common interface files
 ▪ 2c0e4604bbcf Merge "qcacld-2.0: Add setting to disable CCK and MCS rates" into wlan-cld2.driver.lnx.1.0
 ▪ 17819b5e56a1 builder: add mkzip function
 ▪ 6a01c51101b6 Merge "qcacld-2.0: Fix stats error in Smart Antenna" into wlan-cld2.driver.lnx.1.0
 ▪ 95f5771595bf qcacld-2.0: Add setting to disable CCK and MCS rates
 ▪ 43d69d69fd7c Merge 5c55277cdefd82fbce437b46a69052577b4e6628 on remote branch
 ▪ 888cbe744261 qcacld-2.0: Enable dma map/unmap api only for PCIE device
 ▪ 791e4ac50326 defconfig: re-enable UID_SYS_STATS
 ▪ 0438803ab798 defconfig: update after 4bffbdf36702e5b74fcfba1800b17b3e9de9292f
 ▪ f772242616db random: Switch random fully over to Chacha20
 ▪ 89b32ef2fd6d random: replace non-blocking pool with a Chacha20-based CRNG
 ▪ 4bffbdf36702 crypto: chacha20 - Add a generic ChaCha20 stream cipher implementation
 ▪ 329b157e06bf builder: add timer function
 ▪ 70380b38a9c3 ANDROID: binder: correct the cmd print for BINDER_WORK_RETURN_ERROR
 ▪ d3105b9f1e47 msm: sps: Fix uninitialized result usage when an invalid IRQ is found
 ▪ 84e30eb0519c arm64: enable 128bit ints
 ▪ 1b6e9f25c93b arm64: support bitrev
 ▪ 5c818f2791a9 Makefile: add optimization flags
 ▪ c5920f561145 defconfig: disable spectre/meltdown protection
 ▪ 8a34581f4f76 init: Kconfig: Don't force DEBUG_KERNEL when EXPERT is enabled
 ▪ 3cd9769b4de2 qcacld-2.0: add null check
 ▪ e66cfe5f86f9 qcacld-2.0: Fix integer overflow
 ▪ b50e0be04ea3 qcacld-2.0: Fix type issue
 ▪ 2c8eb9b11879 qcacld-2.0: Fix stats error in Smart Antenna
 ▪ 3b0f8c123142 net: qmi_wwan: fix divide by 0 on bad descriptors
 ▪ ac1ca3dbae5e mm: decrease vm_swappiness to 50
 ▪ d0062f1c8f62 Add new universal build script (WIP)
 ▪ 4b2befee7e8c Add customized AnyKernel3
 ▪ c142eb016a72 defconfig: tweak entropy controls
 ▪ f3c8c6f3edea char: Kconfig: create default read/write entropy configs
 ▪ b6e9dbc190f0 drivers: fixup inconsistent mutex
 ▪ a295d92dffc6 drivers: major code fixups
 ▪ f69b49f7ce79 mm: Implement minimum bound for performing readahead
 ▪ 2c07141f48ea mm: Do readahead if requested size is over 64 KiB
 ▪ 915719a4fc3a block: Do not collect I/O statistics
 ▪ bce2c897c30c defconfig: Disable bounce buffers
 ▪ 7bd20d73ad78 sched: Enable NEXT_BUDDY for better cache locality
 ▪ 96dd3e04d88c staging: sync: Don't copy fence names by default
 ▪ 182b975bbd49 gpu: msm: Do not compile Adreno 3xx / 4xx drivers
 ▪ 712984df71d3 irq: spurious: Disable IRQ debugging by default
 ▪ af7cd4965fe6 Makefile: remove -ffast-math because -Ofast is here too
 ▪ 2630764b92b2 defconfig: disable some small logs and stats
 ▪ 7f1014a148d5 defconfig: enable NTFS driver and disable sdFAT stats
 ▪ 28848b88e383 mmc: disable software CRC checks and make them toggleable
 ▪ 128a34777a82 defconfig: enable CONFIG_PGTABLE_MAPPING
 ▪ 77339a34f111 defconfig: disable most of the congestion algorithms
 ▪ 100d05d087a8 Fix code errors detected by GCC
 ▪ afecdfb78bb0 power: use power efficient wq
 ▪ 2bafa0d37b59 msm-core: disable userspace access to poll_ms
 ▪ ad73d354019c Merge "msm: vidc: Ensure size of the data available before typecasting"
 ▪ 702816d1ea9b msm: vidc: Ensure size of the data available before typecasting
 ▪ b2913c0688a5 l2tp: pass tunnel pointer to ->session_create()

 ▼ packages/apps/HavocSettings/
 ▪ ee616b1 Settings: Add toggle for OP gestures haptic feedback [2/2]
 ▪ c96da3d Settings: Add Circle battery style from PA [2/2]
 ▪ d5e139d Settings: Add 2 more date styles [2/2]
 ▪ 8c5d8a9 Settings: Add more date styles [2/2]
 ▪ 5041eb5 Lockscreen date styles [2/2]
 ▪ 7021100 Settings: Cleanup Screenrecord
 ▪ 1c38957 Merge pull request #6 from Sobuj53/pie
 ▪ 2a47642 Updated some more text translations
 ▪ 32dc08e Merge pull request #1 from HavocGemini/pie
 ▪ 2114e6f Original file
 ▪ f1c0ac9 Bangla translation
 ▪ 4795a92 Translation updated
 ▪ 6a4ffc2 Translation updated
 ▪ ac16ca0 Bangla translation
 ▪ 0491a78 Bangla translation
 ▪ bb254a9 fix typos
 ▪ 1d8ded6 Settings: Remove haptic feedback duration for OP gestures
 ▪ 18a08fe add SearchIndexProvider into HavocSettings [1/2]
 ▪ f9e2dfb add haptic feedback intensity control
 ▪ d224668 toggle torch proximity check [2/2]
 ▪ 70772a6 Rework hw button illumination
 ▪ 2f75b6b Revert "Pocket judge"
 ▪ 3ff353b set default rounded values
 ▪ 447ae9e Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"
 ▪ 641830b Settings: Fix typos
 ▪ 8a4031c Add Xiaomi Mi Mix

 ▼ packages/apps/Longshot/
 ▪ ff71ea5 Add edit action on notification
 ▪ 7135a5e Declare priv-app permission
 ▪ 3886633 Import modded Longshot app
 ▪ 687523b Initial commit

 ▼ packages/apps/Recorder/
 ▪ a3cd3c7 Recorder: UI changes and improvements
 ▪ c74af6a overlay: Use dp instead of sp on timer tick
 ▪ 6586a41 Keep overlay always dark
 ▪ e4765ae ScreencastService: Update notification immediately after recording started
 ▪ 5467cfc OverlayService: Hide when starting recording, if not overlay should not be displayed
 ▪ a3ba553 Fix inline build
 ▪ fc9f85b Revert "Android studio import"
 ▪ c28df9e Android studio import
 ▪ f9d51c4 Improve error handling and some code
 ▪ acc6ec7 Prevent miss-clicks on views
 ▪ fc01360 Fix lag when dragging overlay and updating timer
 ▪ 5b48203 Add alpha on floating window
 ▪ 16e3015 Cleanup config
 ▪ a650176 Adjust internal audio recording params
 ▪ 1f56e9a Add timer into activity
 ▪ 5f33ba7 Revert "Open last recorded item on stop"
 ▪ 9778c93 Improve floating window
 ▪ f04b85c Use accent from framework
 ▪ 54deb67 Don't hardcode font
 ▪ 4fc7b0f Fix black theme
 ▪ 54130d1 overlay: Add little spacing on the end of recording button
 ▪ 19386d1 Improve share notifications
 ▪ 263eac9 Disable qs tiles when locked
 ▪ dd671a9 Open last recorded item on stop
 ▪ aad89be Add listener on Settings activity
 ▪ f33d5a3 Stop overlay service on record started
 ▪ 3a78d14 Add orientation preference
 ▪ 0e4e3a4 Pause recording when screen off to save resources
 ▪ db7264c Check before unregistering broadcast receiver
 ▪ 309b558 Always use H264
 ▪ 5d4f105 Hide some activities from recents
 ▪ 73f9d42 Add more preferences
 ▪ dbb5dec Use reflection to collapse statusbar
 ▪ 1ede6d1 Improve transparent theme
 ▪ 02c298e Conditionally disable internal audio recording support
 ▪ 38c59b2 Import custom androidx preference library for better theming
 ▪ fec3196 More theming improvements
 ▪ c09bc90 Refactor settings UI
 ▪ adbd547 Refactor recording methods
 ▪ 9511b58 Separate and improve strings
 ▪ 446ad5a Rename strings to custom_strings.xml
 ▪ 6574d90 Cleanup intents
 ▪ 9afc974 Remove from launcher
 ▪ 6e48d03 Update icon
 ▪ 8ff4d49 Change version
 ▪ 7004cc5 Implement qs tiles and refactor code
 ▪ 2885a4d Improve recording floating overlay
 ▪ 33ce278 Don't use shared prefs to store recording state
 ▪ fccca20 UI redesign
 ▪ 55254ec Add system audio recording support [1/2]
 ▪ e97bc73 Rebrand
 ▪ 1ad0339 Bump sdk

 ▼ packages/apps/Settings/
 ▪ f4f72f2079 LiveDisplaySettings: Hide automatic outdoor mode preference on HWC2
 ▪ 89b80d7f50 LiveDisplaySettings: Reenable display mode preference for outdoor mode
 ▪ 9201a2df21 Settings: Don't index display mode and color temperature on HWC2
 ▪ eaf7a73db1 LiveDisplay: Cleanup
 ▪ 22939a78de Revert "Settings: Restart SystemUI when toggling battery estimates"
 ▪ 47953ab5f2 Settings: Add hotspot setting to allow VPN upstreams

 ▼ packages/apps/Updater/
 ▪ 10090f3 Bangla Translation (#1)
 ▪ 98f5452 delete untranslatable strings
 ▪ b35ac20 Bangla Translation
 ▪ bce67ca fix typos

 ▼ packages/services/Telecomm/
 ▪ a2cc5de0 Merge 35ac45b31c20c7f2daf787ed48667fd6e527b5f7 on remote branch

 ▼ packages/services/Telephony/
 ▪ e65c02e48 fix typos

 ▼ system/core/
 ▪ 41aac2854 Fix a memory leak in gatekeeper.
 ▪ 8821bf7bd Add cpu set for audio app

 ▼ system/netd/
 ▪ b4a8670 netd: Consolidate restrict apps methods

 ▼ system/nfc/
 ▪ 2e25e87 Prevent OOB read in rw_t4t.cc
 ▪ eb35d9a Prevent integer overflow in NDEF_MsgValidate

 ▼ system/sepolicy/
 ▪ e0e9346f1 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie
 ▪ 58fee8440 sepolicy: Address some theme_data_file denials
 ▪ 5c4707e46 add some storaged rules

 ▼ system/vold/
 ▪ 7a92952 Add "changepw" command to vdc.

 ▼ vendor/havoc/
 ▪ f3ac8f8d update Recorder permissions
 ▪ 82bc4129 Havoc 2.9
 ▪ a3135a86 prebuilts: Remove outdated TCP init script
 ▪ 83dbc654 LatinIME: Add en_GB, en_US, lt, lv, ro, sl, sr, tr dictionaries
 ▪ f61704e1 BoardConfigKernel: separate KERNEL_OBJ paths
 ▪ d9f4202c update Lawnchair to alpha-2399
 ▪ 1cea1cdd Revert "Remove prebuilt MarkupGoogle"
 ▪ 250354b2 vendor: Build Recorder app
 ▪ fbbe98bc overlay: Disable config_keyguardUserSwitcher on sw600dp
 ▪ ea32739d vendor: Add vendor.lineage.biometrics.fingerprint.inscreen permission
 ▪ b719d232 backuptool_ab: Make copy_file preserve file/directory attrs
 ▪ 2f26d7ea overlay: Remove config_wifi_wakeup_available
 ▪ 39cef568 Remove prebuilt MarkupGoogle
 ▪ 8ea74e20 Let the user choose the screenshot editor himself
 ▪ eee7e568 vendor: Build Longshot app
 ▪ 16653a83 config: Use tether automatic upstream selection
 ▪ e9046744 update Lawnchair to alpha-2382
 ▪ 5a363dda update Device Health Services to 1.11.0.259314730.release
 ▪ 52a9514f vendor: Add qcom platform type to soongs vars
 ▪ abcdeb7d LatinIME: Add Polish dictionary

 ▼ vendor/nxp/opensource/commonsys/packages/apps/Nfc/
 ▪ 0e1260ff delete tests
 ▪ 0104f525 fix reorder warnings

 ▼ vendor/qcom/opensource/audio/
 ▪ 5bb3851 Merge 630c0c52c08b00b26efc82402a8e1b82bd65410a on remote branch
 ▪ 0744ca9 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ 630c0c5 audiopolicy: align custom APM with AOSP.
 ▪ 8ed64fb Merge ab144dfecf3fefe0aa579825eca26ed9794aeb55 on remote branch
 ▪ 445b43d Merge ab144dfecf3fefe0aa579825eca26ed9794aeb55 on remote branch

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ 00e3691 Merge 1f562ee38a3ec3dd3647a8caa1af9d703c675103 on remote branch
 ▪ 37d4529 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ 381087f Merge 1f562ee38a3ec3dd3647a8caa1af9d703c675103 on remote branch
 ▪ c31cf53 Merge 7a95be085bad6c40d0784d96b0f1b37e17a81803 on remote branch
 ▪ 1f562ee ipacm: Enable Lan2Lan Bridge feature for Hana55 and Kona55 target

 ▼ vendor/qcom/opensource/dataservices/
 ▪ 39b0587 convert mk to bp

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 7aa343b Update IQtiComposer/IQtiComposerClient intf to 2.0
 ▪ c2514b9 Merge a9ab3a736069433263319c4c30dcae2340e66efb on remote branch
 ▪ 390f275 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ e83d3af Merge cb1b981b884f66fd346b6470bf0c63a976b86bb2 on remote branch
 ▪ a9ab3a7 Add Hash Version of Servicetracker@1.1 HAL
 ▪ 67118af Introduce vendor.qti.hardware.servicetracker@1.1 HAL
 ▪ 1dbebc6 Merge cb1b981b884f66fd346b6470bf0c63a976b86bb2 on remote branch

====================
     08-10-2019
====================
 ▼ art/
 ▪ 3fca776287 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/art into pie
 ▪ 37b0c5e2f1 oatdump: Only compile CompactDex conversion for host
 ▪ 755171d29e oatdump: Convert CompactDex to StandardDex before exporting

 ▼ bootable/recovery/
 ▪ e86683f9 Merge tag 'android-9.0.0_r37' into pie

 ▼ build/blueprint/
 ▪ 6c23f79 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ build/kati/
 ▪ 69cb715 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ build/make/
 ▪ 168ecc715 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/build into pie

 ▼ build/soong/
 ▪ eca3f313 Give Blueprint modules access to all namespaces

 ▼ development/
 ▪ 9b8a35f8e Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ device/qcom/sepolicy/
 ▪ 8f95d283 Merge "sepolicy: Add qseecom device access permissions to audio HAL"
 ▪ e5522ed7 sepolicy: Add qseecom device access permissions to audio HAL
 ▪ 5219ddf4 sepolicy: Allow platform app to access fingerprint HAL
 ▪ 6129dba9 Add Device Info hal vendor.qti.hardware.radio.deviceinfo@1.0
 ▪ 9028a11d sepolicy : add rule to allow dpmd self kill

 ▼ device/xiaomi/gemini/
 ▪ e559f1f95 add snapcam priv-app permissions
 ▪ 1a22e3538 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' into 9.0

 ▼ device/xiaomi/translations/
 ▪ b1fd66a update 05082019

 ▼ external/ant-wireless/ant_service/
 ▪ 200fcc9 Merge remote-tracking branch 'remotes/origin/caf/github/production/4.0.x' into ant.lnx.2.9.1
 ▪ 674e8d9 Release version 4.0.1

 ▼ external/chromium-webview/
 ▪ 8901da9 Update Chromium Webview to 76.0.3809.89

 ▼ external/f2fs-tools/
 ▪ bd0159a Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ external/fsck_msdos/
 ▪ 8eea348 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ external/gptfdisk/
 ▪ c1ea282 gptfdisk: include gptcl.h after sgdisk.h

 ▼ external/icu/
 ▪ 45845fb8d DO NOT MERGE: Update tzdb version to 2019b
 ▪ c555ad468 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ external/jemalloc/
 ▪ 3c5b1fb Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ external/nano/
 ▪ 1d23c7f7 nano: Zero entire struct sigaction struct
 ▪ 5f71cf2e nano: Bump PACKAGE_STRING to 4.3 too
 ▪ 37aec986 Properly 0 initialize sigaction
 ▪ 10fe4835 Merge tag 'v4.3' into HEAD

 ▼ external/proguard/
 ▪ 56c2bf7 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ external/skia/
 ▪ fbc77220c5 Add private save-behind and draw-behind methods to canvas.
 ▪ 780f94a577 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/external/skia into pie
 ▪ 324aadbeda Add private save-behind and draw-behind methods to canvas.
 ▪ 4e54e0ceca Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ external/sqlite/
 ▪ bb1fcc3 sqlite: upgrade to SQLite 3.29.0

 ▼ external/turbine/
 ▪ 4cba3b5 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ frameworks/av/
 ▪ c7bd64265c Fix OOB access in mpeg4/h263 decoder
 ▪ 6a841c2242 m4v_h263: add a test for invalid/negative value
 ▪ e8b2ab4fe4 Merge tag 'android-9.0.0_r47' into pie
 ▪ 12cc0d00b5 libcameraservice: write all pkgNames
 ▪ 75bf9b61d1 Camera: Consider the currently acquired input buffers
 ▪ f4ebc1b899 media: Add support for up to level 6.2 for AVC
 ▪ a768b60268 Merge remote-tracking branch 'aosp/pie-gsi' into pie
 ▪ c24c924da9 CameraService: Support hooks for motorized camera

 ▼ frameworks/base/
 ▪ 06aed1054fb [RESTRICT AUTOMERGE] Pass correct realCallingUid to startActivity() if provided by PendingIntentRecord#sendInner()
 ▪ ea894cfc5a0 OP_REQUEST_INSTALL_PACKAGES denied by default
 ▪ 7f86c416023 OP Gestures: Enable gestures on the keyguard as well
 ▪ f2a125a90cc GamingMode: Clean up for dynamic mode
 ▪ 8f3b2103212 SystemUI: Fix SystemUI failed to go to doze issue
 ▪ 9aefcce16d1 Fix sim pin on DSDS
 ▪ 3847ce99a41 Dismiss SIM lock page after correct SIM
 ▪ 17a8bb77949 When data switches during voice call, make sure signal bar updates it.
 ▪ f96fa074ed6 Stop USB Debugging authorization window dismissing on tap outside.
 ▪ 54484b41919 Update navigation bar upon change of display density
 ▪ fc13ab0b19b Unable to input PIN with hardware keyboard
 ▪ 2cc42c075a9 NetworkManagement : Add ability to restrict app vpn usage
 ▪ b266b764860 Switch widgets away from android.text.format.Time
 ▪ b5671be46b1 Migrate telephony code away from Time
 ▪ 618a060de18 Remove unused class
 ▪ 4b695a2299c Remove unnecessary usage of deprecated Time class
 ▪ c42ce8e2569 Add a basic benchmark for android.text.format.Time
 ▪ 15ddf7211cd Avoid use of DateUtilsBridge.icuTimeZone()
 ▪ 031b5ef5627 base: Introduce DisplayModeManager [1/2]
 ▪ e13a0d65f9c Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/frameworks/base into pie
 ▪ 333bf1c2ddd DO NOT MERGE Fix display freezing when screen size mismatches
 ▪ 08e1a73c8fa Fix to register the receiver for all users
 ▪ 99e389ae119 Audio assets: add NFC sounds
 ▪ 62514f2c44f Import translations for Typographic Clock
 ▪ f5daef6c3f2 TypographicClock: Tint top row with wallpaper primary color
 ▪ 5d6f8e78c48 Revert "Q Style Clock: Animate change in time"
 ▪ 94c385e513f MediaCodecInfo: Add support for level 6.2
 ▪ 9a33be1e474 base: Materialize gesture anywhere layout
 ▪ a2a03156dc9 base : Fix GA crash and saving the gesture cache
 ▪ d106a41109e base: Increase gesture anywhere width to 40px [1/2]
 ▪ 3d45ca143d7 base: Gesture Anywhere [1/3]
 ▪ 6cc10ef7207 SettingsLib: Hide QS tile overlays from app list
 ▪ db3dd3d632c SystemUI: Ensure battery estimates update on callback
 ▪ e258e0a541e Fix Layout.primaryIsTrailingPreviousAllLineOffsets
 ▪ daba8f835b9 HidProfile: sync isPreferred() with HidHostService
 ▪ dd56d82cb49 [RESTRICT AUTOMERGE] Correct argument order in permission check
 ▪ 196d6839a94 wifi: Filter unsupported networks from scan results
 ▪ c8783a6dbe4 Wifi: Connect indication on UI for STA when AP supports SAE+PSK
 ▪ 6e369bdd7f4 GamingMode: Fix unnecessary unloading of gaming mode
 ▪ ea9ea9904db MusicTile: Clean up redundant code
 ▪ 31ae1f2143e Improve performance of unclipped save layers.
 ▪ 8e257625331 base: Add Gaming Mode icons from OOS
 ▪ 480861a3f65 Aggressive Battery: Improve value substitution
 ▪ e11a7a7af1e Guard in short-circuit evaluations for stringSplit methods
 ▪ d2674eedef0 GamingMode: allow disable navigation gestures [1/2]
 ▪ 5b3f832bdde GamingModeTile: Long press to open settings [1/2]
 ▪ 36eba01ac6c base: Add Gaming mode tile
 ▪ 1e2d58c47f9 GamingMode: Exempt calls and alarms when headsup disabled
 ▪ 9b6d0b8beab core: Import more animations from Android Q
 ▪ ae42c3ae424 SystemUI: Disable wellbeing grayscale tile if reading mode available
 ▪ 4c3b20c3316 LiveDisplay: Refactor for HWC devices and cleanup
 ▪ e5789c10b81 Revert "SystemUI: Add LiveDisplay tile"
 ▪ 4ed2b1a2019 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/frameworks/base into pie

 ▼ frameworks/native/
 ▪ 37409432e Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/frameworks/native into HEAD
 ▪ c045dac2f Snap for 5737601 from e9d5346b832bd6e28fad02a662fd39cca5403df3 to p-keystone-qcom-release
 ▪ 1816557bd Fix race between SensorManager ctor and callback
 ▪ f584248b4 Free mObjects if no objects left to realloc on resize
 ▪ e9d5346b8 Merge SPL-2019-07-05

 ▼ frameworks/opt/net/ims/
 ▪ f047cdf Merge branch 'pie-gsi' of https://android.googlesource.com/platform/frameworks/opt/net/ims into pie

 ▼ frameworks/opt/net/wifi/
 ▪ 51a8e96da Filter unsupported networks from Open network notifier
 ▪ 7d60ef996 wifi: Skip rmmod during the device shutdown/reboot
 ▪ c973e0614 wifi-aware: (Re)-Set default discovery window after screen on.

 ▼ frameworks/opt/telephony/
 ▪ a6ee76d6da Snap for 5737601 from ce1b1ef52032c4efef68d1edd58a587764562941 to p-keystone-qcom-release
 ▪ ca6dad149c Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD
 ▪ ce1b1ef520 Merge SPL-2019-07-05

 ▼ frameworks/support/
 ▪ 63e2472598 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ hardware/broadcom/libbt/
 ▪ 4545703 libbt: configure audio codec right after firmware

 ▼ hardware/broadcom/wlan/
 ▪ 9610886 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ hardware/havoc/interfaces/
 ▪ 7d39191 Introduce camera motor hal

 ▼ hardware/interfaces/
 ▪ 5d84ebc2f Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ a06dd86cb Merge c32fb753175acf76009a48ff0202739681e8f5ef on remote branch
 ▪ c32fb7531 Snap for 5737601 from dbf26747b0e79fef823253d8d60fe158fa02e4ca to p-keystone-qcom-release
 ▪ 60df6dd80 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ dbf26747b Merge SPL-2019-07-05

 ▼ hardware/nxp/nfc/
 ▪ 6ea5be3 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ af97a487 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ 1244b1f5 Merge "config: msm8953: enable Audio HIDL HAL 5.0"
 ▪ accff594 config: msm8953: enable Audio HIDL HAL 5.0
 ▪ 5a8f0193 Merge "configs: Enable AAC frame control for A2DP"
 ▪ e9e0c4b6 Merge "hal: enable mono clips for incall music delivery"
 ▪ 426567e4 hal: fix voip usecase selection for voice_tx path
 ▪ c9d3273d Merge d7904b037deaedfdf4239b08486970029813c34b on remote branch
 ▪ 253fda65 Merge "fm: Restore fm on Speaker"
 ▪ 75f0c8bf Merge "hal: fix voip usecase selection for voice_tx path"
 ▪ a7f96eb4 config: msm8953: enable Audio HIDL HAL 5.0
 ▪ bbc41461 configs: Enable AAC frame control for A2DP
 ▪ b5ede682 configs: Add button click suppression mixer for wcd937x and trinket
 ▪ 38f4dfad fm: Restore fm on Speaker
 ▪ d7904b03 Merge "hal: fix voip device selection is not proper after voice call stop"
 ▪ 60d5c77c Merge "configs: msm8937: Add speaker and headphones paths"
 ▪ c6f0addd hal: enable mono clips for incall music delivery
 ▪ a4ab4623 hal: fix voip usecase selection for voice_tx path
 ▪ 979aa2e7 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ 602a39b5 audio: notify device info twice for combo output
 ▪ ab30673b Merge "hal: add apptype as a part of event_value"
 ▪ ce3b5635 Merge "hal: move gef device notification after sample rate adjustment"
 ▪ 0db11eb6 Merge "audio: introduce dedicated adev->cal_lock for gef interfaces"
 ▪ fb485071 hal: fix voip device selection is not proper after voice call stop

 ▼ hardware/qcom/bt-caf/
 ▪ fa39bcc Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into 9.0

 ▼ hardware/qcom/data/ipacfg-mgr/
 ▪ 7367dc7 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ 9f0f3688 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0
 ▪ 4f18b7c6 Merge b361ad8b63a12b11bbadd6adca4ffcb632bba8dc on remote branch
 ▪ aed97947 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0

 ▼ hardware/qcom/fm/

 ▼ hardware/qcom/gps/
 ▪ a62882c9 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ fbffc2bb mm-video-v4l2: vidc: vdec: Support interlaced clip playback for LV
 ▪ 98b291fc vdec: Allow setting default fps to driver

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ fbffc2bb6 mm-video-v4l2: vidc: vdec: Support interlaced clip playback for LV
 ▪ 2b14ed9df Merge 57beea57153a8d6c4ca6b0aade333f68edd0c06b on remote branch
 ▪ 08d9b91f0 Merge 57beea57153a8d6c4ca6b0aade333f68edd0c06b on remote branch

 ▼ kernel/xiaomi/msm8996/
 ▪ 6d72b0085577 soc: qcom: glink_smem: Initialize buffers
 ▪ 5c55277cdefd Merge "qcacld-2.0: Fix multiple length definition issue in WLAN FW message" into wlan-cld2.driver.lnx.1.0
 ▪ be829d2c880d Merge "USB: check usb_get_extra_descriptor for proper size"
 ▪ 0463006a9d9a USB: check usb_get_extra_descriptor for proper size
 ▪ 5fdc377b5c54 Merge "msm: ais: Remove dead code from Camera drivers"
 ▪ f98355b8255c Merge "defconfig: arm64: msm: Disable AIS support"
 ▪ 78071f87e2a9 msm: ais: Remove dead code from Camera drivers
 ▪ eaa5c9eec41d defconfig: arm64: msm: Disable AIS support
 ▪ 0e91f193285e Merge "msm:camera:isp: Fix array index bound checks"
 ▪ 3fe7abbee0a7 Merge "vidc: Add checks to avoid OOB access"
 ▪ f55ff08b254a qcacld-2.0: Fix buffer overflow in htt_t2h_msg_handler_fast
 ▪ 2c62467a1705 vidc: Add checks to avoid OOB access
 ▪ 381e9c172cf4 msm:camera:isp: Fix array index bound checks
 ▪ 1bd13115ff40 Merge "scsi: libsas: fix a race condition when smp task timeout"
 ▪ 8377cc3eb400 Merge "usb: otg: don't set a_alt_hnp_support feature for OTG 2.0 device"
 ▪ a444a4b8a2f9 Merge "aio: mark AIO pseudo-fs noexec"
 ▪ ede1728f42de Merge "vfs, writeback: replace FS_CGROUP_WRITEBACK with SB_I_CGROUPWB"
 ▪ b7c03c0a23de usb: otg: don't set a_alt_hnp_support feature for OTG 2.0 device
 ▪ eda744368b90 aio: mark AIO pseudo-fs noexec
 ▪ 3732cd598430 vfs: Commit to never having exectuables on proc and sysfs
 ▪ 0514246a2e36 vfs, writeback: replace FS_CGROUP_WRITEBACK with SB_I_CGROUPWB
 ▪ 89bb088c616d pwm: Mark all devices as "might sleep"
 ▪ 0ab09ba7251c mm: get rid of vmacache_flush_all() entirely
 ▪ 3d8551611bd2 [media] cx231xx-cards: fix NULL-deref on missing association descriptor
 ▪ b98194f6bb6a scsi: libsas: fix a race condition when smp task timeout
 ▪ 98fa53a2b230 scsi: megaraid_sas: return error when create DMA pool failed
 ▪ 98808cb6a7e3 scsi: target: iscsi: Use bin2hex instead of a re-implementation
 ▪ bd82e3410393 qcacld-2.0: Add support for report TX failed pkt to upper layer
 ▪ 0b6a4486a9a9 msm: vidc: Avoid information leak while accessing the packet
 ▪ a3a640df47ba Merge "qcacld-2.0: Send user space about FW CRASHED indication" into wlan-cld2.driver.lnx.1.0
 ▪ 75f8c59443e1 diag: Prevent out-of-bound access while processing dci transaction
 ▪ 843a77763998 qcacld-2.0: Fix multiple length definition issue in WLAN FW message
 ▪ 3b22a74bb78f qcacld-2.0: Add CONFIG_MULTI_IF_LOG to support multi if log
 ▪ 72bc6242e154 qcacld-2.0: Fix compile error excluding static 11p channels
 ▪ 58c4d2de424d qcacld-2.0: Send user space about FW CRASHED indication
 ▪ 4b9eca1dbcbc Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 648331e9f538 msm: camera: jpegdma: Added missing lock for dqbuf and streamon
 ▪ 5bfa42a4287c Merge "qcacld-2.0: Use correct format code in for the type of size_t" into wlan-cld2.driver.lnx.1.0
 ▪ db0e63952ac2 qcacld-2.0: Use correct format code in for the type of size_t
 ▪ 11867ee6505d qcacld-2.0: Validate 11p channel from static channel list
 ▪ b6298f11dcfa Merge "fbdev: msm: check the length of the external input buffer properly"
 ▪ 5d32c651c707 Merge "qcacld-2.0: Support to pass HW version to userspace" into wlan-cld2.driver.lnx.1.0
 ▪ 8d743c2e6e27 Merge "qcacld-2.0: Revert "RSN IE Update in case of BSS already started"" into wlan-cld2.driver.lnx.1.0
 ▪ 377bad6c74ea ext4 crypto: Avoid dynamically allocating memory for file names
 ▪ 5737f06bff98 ANDROID: sdcardfs: Allocate temporary name buffer on the stack
 ▪ d68b04fc34e0 Merge "qcacld-2.0: Adjust CFG_SET_TSF_GPIO_PIN_MAX value to 255" into wlan-cld2.driver.lnx.1.0
 ▪ 6d3fd622ac90 Merge "qcacld-2.0: Adjust loglevel in txrx" into wlan-cld2.driver.lnx.1.0
 ▪ 10dd3d51b22f Merge "qcacld-2.0: Adjust loglevel in __wmi_control_rx()" into wlan-cld2.driver.lnx.1.0
 ▪ dcfb694fe913 Merge "qcacld-2.0: Set ini 5g_rssi_penalize_factor as signed integer" into wlan-cld2.driver.lnx.1.0
 ▪ 8e199c990bd5 Merge "qcacld-2.0: Set ini 5g_rssi_boost_threshold as signed integer" into wlan-cld2.driver.lnx.1.0
 ▪ 73ca43cc9974 Merge "qcacld-2.0: Adjust loglevel in print_hdd_cfg()" into wlan-cld2.driver.lnx.1.0
 ▪ c125d54f60f8 Merge "qcacld-2.0: Adjust loglevel in print_hdd_cfg()" into wlan-cld2.driver.lnx.1.0
 ▪ a751d2f4909c qcacld-2.0: Revert "RSN IE Update in case of BSS already started"
 ▪ 1f5d51b1f324 qcacld-2.0: limit time for scan when miracast is running

 ▼ packages/apps/Camera2/
 ▪ 741cefaa1 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/CarrierConfig/
 ▪ b45beb0 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/CellBroadcastReceiver/
 ▪ 43089af Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/Contacts/
 ▪ 1c882fb88 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/CustomDoze/
 ▪ 077344c CustomDoze: Add support for custom Tilt and Proximity sensors

 ▼ packages/apps/DocumentsUI/
 ▪ 664edc29 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/EmergencyInfo/
 ▪ d666d24 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/FMRadio/

 ▼ packages/apps/HavocSettings/
 ▪ 26645d4 Settings: Increase gesture anywhere width to 40px [1/2]
 ▪ 85b2e9b Settings: Gesture Anywhere [2/3]
 ▪ 9620bcb Use SeekBar for OP gestures feedback duration
 ▪ 5af7426 Settings: Improve a few strings
 ▪ e972e46 GamingMode: Allow disable navigation gestures [2/2]
 ▪ 0b35939 GamingMode: Move game add summary at bottom
 ▪ 8802e91 GamingMode: Disable modifying settings when GamingMode is turned on

 ▼ packages/apps/Nfc/
 ▪ 253db558 Merge tag 'android-9.0.0_r47' into pie
 ▪ 5fea3075 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/PackageInstaller/
 ▪ 615aabbc Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/apps/Recorder/

 ▼ packages/apps/Settings/
 ▪ 1cee15176d Merge tag 'android-9.0.0_r47' into pie
 ▪ 1a9f1de789 Settings: per-app VPN data restriction
 ▪ 2a4fc04b6d SimSettings: Fix preferred calls sim not being disabled
 ▪ a08533291c Settings: rearrange Sounds page a little
 ▪ 69fc5a35c5 Settings: Gesture Anywhere [3/3]
 ▪ d542bfbfeb Open app when clicking on icon in App Info
 ▪ 2afaa963c3 BatteryUtils: Show anomalies of pre-O apps
 ▪ 22a1af3091 GamingMode: Long press tile to open settings [2/2]
 ▪ d50018b91b LiveDisplay: Refactor
 ▪ 448c5a55c8 LiveDisplay: Rebrand to keep consistency
 ▪ 2a73fcb4bb LiveDisplaySettings: Fix outdoor mode preference on hwc2
 ▪ 79995fcde4 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/inputmethods/LatinIME/
 ▪ 7117b96ce Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/providers/DownloadProvider/
 ▪ fed244c Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/providers/MediaProvider/
 ▪ 2a3ab8e Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ packages/services/Telecomm/
 ▪ d90e5107 Merge tag 'android-9.0.0_r47' of https://android.googlesource.com/platform/packages/services/Telecomm into pie
 ▪ 35ac45b3 Snap for 5765719 from 4ac89ae24f6cae1da22c4542ac4b07525e490611 to p-keystone-qcom-release
 ▪ 4ac89ae2 Merge "Change bluetooth routing to be more responsive" into p-keystone-qcom
 ▪ e53f67eb Snap for 5737601 from b6bdad0053ef65c5e1090f7e9cf3fe1c5503d186 to p-keystone-qcom-release
 ▪ 2b6280f1 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/packages/services/Telecomm into pie
 ▪ b6bdad00 Merge SPL-2019-07-05

 ▼ system/bt/
 ▪ 8b22bc44e Merge tag 'android-9.0.0_r47' into pie
 ▪ 613026555 Revert "DO NOT MERGE Separate SDP procedure from bonding state (1/2)"
 ▪ f5b67d1e4 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ system/core/
 ▪ 56d74c085 fs_mgr_fstab: Add Adiantum support
 ▪ ff07f4613 Revert "Support Speck encryption."
 ▪ 569b60869 tombstoned: fixed tombstones failed issue
 ▪ 416039080 health: Add CAP_WAKE_ALARM to service via init
 ▪ 7c79b7ba2 Fix two clang-tidy issues in crasher.cpp.
 ▪ 564a7f79d Add native vsock support to ADB.

 ▼ system/extras/
 ▪ 64531acb Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ system/libhwbinder/
 ▪ 9ef1b59 Merge tag 'android-9.0.0_r47' into pie
 ▪ 26a8e76 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ system/netd/
 ▪ 08a4e54 NetD : Allow passing in interface names for vpn app restriction
 ▪ b3d581f Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ system/nfc/
 ▪ 5a5cbd9 Prevent OOB read in rw_t4t.cc
 ▪ 0a7432f Prevent integer overflow in NDEF_MsgValidate

 ▼ system/timezone/
 ▪ 3da5ac1 DO NOT MERGE: Update tzdb version to 2019b
 ▪ de4a2bf Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ system/tools/hidl/
 ▪ 843066d Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ system/update_engine/
 ▪ 5be3b00 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

 ▼ system/vold/
 ▪ 61facd5 Merge remote-tracking branch 'aosp/pie-gsi' into pie

 ▼ vendor/havoc/
 ▪ a867cdd9 update GoogleWallpapers
 ▪ 3df445e4 Havoc 2.8
 ▪ 51e46aa3 update Lawnchair to alpha-2357
 ▪ 9fb9bf70 update prebuilt calculator & deskclock
 ▪ 68c95147 update Lawnchair to alpha-2338
 ▪ 69574b39 update prebuilt apps
 ▪ 751160af vendor: Dynamically add custom APNs
 ▪ dfbd9bde common: Add getcap/setcap to PRODUCT_PACKAGES
 ▪ 3e596962 update Lawnchair to alpha-2319

 ▼ vendor/qcom/opensource/audio/
 ▪ c88c6c9 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ 2db65b4 policy_hal: Adapt to AudioMix API changes in f/av audiopolicy
 ▪ 69cda8a Merge f98be796a4c6cfc665843f81066e21d093d5f1a8 on remote branch
 ▪ ab144df policy: hal: Force multi-channel pcm playback to deep buffer path
 ▪ 6c72725 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ 4a1c410 Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ 1a500c8 Merge 7a95be085bad6c40d0784d96b0f1b37e17a81803 on remote branch
 ▪ 2fa4b28 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 3909e2b Merge tag 'LA.UM.7.6.2.r1-09500-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ cb1b981 display: Add extensions version 1.1 with new getSurfaceMetadata API.
 ▪ 73abc17 Merge "IQtiMapperExtensions: Change marking from file types.hal"
 ▪ 72f2601 Merge a88187682c3e04e0f0532f7eff0a4218b33e9a4e on remote branch
 ▪ 59fb7c5 BT: Add  hidl interface for dun profile.
 ▪ d3f4503 Merge "SystemHelper : Adding system helper service for event and resource handling"
 ▪ c62bb5f SystemHelper : Adding system helper service for event and resource handling
 ▪ a881876 display: Add API to set qsync mode.
 ▪ 4d73d69 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ 6b24176 Merge "display: Add APIs to capture concurrent writeback output"
 ▪ d77762d IQtiMapperExtensions: Change marking from file types.hal

====================
     07-10-2019
====================
 ▼ art/
 ▪ 7503577a73 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/art into pie
 ▪ 2402bec9f1 Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ 82a88f49b8 Use conservative permissions when creating files in ART am: d224e964bd
 ▪ 2a3fa67c82 Use conservative permissions when creating files in ART

 ▼ bionic/
 ▪ 109dc8aa5 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/bionic into pie
 ▪ dc015cebe Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie
 ▪ b60dbb09b Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie

 ▼ build/make/
 ▪ 31f4a43d4 Merge tag 'android-9.0.0_r45' of https://android.googlesource.com/platform/build into pie
 ▪ 295d584d9 dex2oat: disable multithreading for WSL
 ▪ f915cf5b4 Add detection for WSL
 ▪ 3f14e9d03 Add the missing dependency on BOARD_PREBUILT_DTBOIMAGE.
 ▪ 99ed86d61 build: Respect fs_config when generating recovery ramdisk
 ▪ e0d8c9a1b Version bump to PQ3B.190801.002 [core/build_id.mk]
 ▪ 79f160f78 Enable armv8-2a supporting on 2nd arch. variant
 ▪ f3400eb64 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/build into HEAD
 ▪ 586d97e5a Make change and version bump to PQ3B.190801.001
 ▪ b10f7384a Update Security String from 08-05 to 2019-08-01 Bug:126590667
 ▪ 4a078bcf4 Update Security String to 2019-08-05 Bug:126590667 (cherry picked from commit a3e1c57a95d895fff372054205914bc322b025a1)

 ▼ build/soong/
 ▪ c1dd398a Support Qualcomm Kryo 385 CPU variant
 ▪ 52b65925 Add to support armv8-2a on 2nd arch. variant
 ▪ fce1572d Move arch variants registering code to arch.go
 ▪ 5119a1a5 Configure the default arch variant features per-OS
 ▪ fad7bd77 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/build/soong into HEAD

 ▼ development/
 ▪ ff5079718 Merge "Snap for 5622519 from 239859423412edda2096927910dd8164e6475865 to pi-platform-release am: 8ef31cb46b" into pie-gsi
 ▪ 6207d9d0c Snap for 5622519 from 239859423412edda2096927910dd8164e6475865 to pi-platform-release am: 8ef31cb46b
 ▪ 8ef31cb46 Snap for 5622519 from 239859423412edda2096927910dd8164e6475865 to pi-platform-release

 ▼ device/qcom/sepolicy/
 ▪ 598c082a Merge 6ad1349f1e77fe97c9b369054584c1c9d67a97b2 on remote branch
 ▪ 6ad1349f sepolicy: Allow secure_element HAL to access vendor data
 ▪ 0d1764ba Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ 1cd4a226 SEPolicy: Add SEPOlicy rules to allow drm_hal to access /data/vendor/mediadrm path

 ▼ device/xiaomi/gemini/
 ▪ d8033cd3e Android 9.0.0 Release 45 (PQ3B.190705.003)
 ▪ fb580e18d msm8996-common: wifi: Enable DFS channel scanning in P2P search
 ▪ bb471fd74 rebase rootdir
 ▪ 2913e2155 update sepolicy
 ▪ 06f678e7a msm8996-common: readmac: Convert symbolic permissions to octal
 ▪ 39d26384a capricorn: revert back to stock sensors
 ▪ 25f27c284 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/device/qcom/common into 9.0
 ▪ 55e5e0829 add vendor.lineage.livedisplay to vendor_framework_compatibility_matrix.xml

 ▼ device/xiaomi/translations/
 ▪ 0c7f6b8 update RU gaming mode translations
 ▪ e776f7d update RU 20190613
 ▪ 97d1dc5 update ru 11.06

 ▼ external/chromium-libpac/
 ▪ 927ac5e [DO NOT MERGE] Disable optimizing compiler for pac file

 ▼ external/chromium-webview/
 ▪ 7823db3 Update Chromium Webview to 75.0.3770.101

 ▼ external/expat/
 ▪ 4f115d6 expat: update to version 2.2.7

 ▼ external/freetype/
 ▪ 883523e7 freetype: update to version 2.10.1
 ▪ 88fa80fa freetype: update to version 2.10.0

 ▼ external/icu/
 ▪ bd4c5fe40 Snap for 5622519 from 81023f4194eeb6e8123445d2441869bf55bf2f87 to pi-platform-release am: 16b3c0277e
 ▪ b9cd61962 Snap for 5600800 from cf06cc7772c2bbad4d6ce91609dd17050a56cf59 to pi-platform-release am: a63df92ad9
 ▪ 16b3c0277 Snap for 5622519 from 81023f4194eeb6e8123445d2441869bf55bf2f87 to pi-platform-release
 ▪ a63df92ad Snap for 5600800 from cf06cc7772c2bbad4d6ce91609dd17050a56cf59 to pi-platform-release
 ▪ f8039486b Merge tag 'android-9.0.0_r44' into staging/lineage-16.0_merge-android-9.0.0_r44

 ▼ external/libavc/
 ▪ 18673f7 Decoder: Delete node from st if lt and st point to same

 ▼ external/libhevc/
 ▪ de250fd Merge cherrypicks of [7982564, 7982192, 7982565, 7981411, 7982522, 7982682, 7982193, 7982194, 7982523, 7982480, 7982623, 7981412, 7981413, 7982605, 7982606, 7982607, 7982608, 7981749, 7981750, 7981751, 7981752, 7981753, 7981754, 7982624, 7982394, 7982395, 7982625, 7982687, 7982566, 7982567, 7982568, 7982688, 7982689, 7982690, 7982195, 7982196, 7982611, 7982612, 7982396, 7982694, 7982695, 7982215] into pi-qpr3-release
 ▪ be21373 Add push-pop for Neon D8-D15 registers

 ▼ external/libvpx/
 ▪ b79844f Fixes a double free in ContentEncoding
 ▪ e4375c5 Check there is only one settings per ContentCompression

 ▼ external/nano/
 ▪ b8987a1e po: update translations and regenerate POT file and PO files
 ▪ 895d2b8e bump version numbers and add a news item for the 4.3 release
 ▪ 47068c37 build: fix compilation when configured with --disable-color
 ▪ 345cf5ac files: don't close a newly-created buffer when it is the only one
 ▪ c7ca60b0 tweaks: don't check the user's nanorc file for accessibility twice
 ▪ 01e4f85f tweaks: remove a check that is no longer relevant
 ▪ 6bfbb2bc tweaks: remove two more unneeded assignments
 ▪ d82c753b rcfile: at terminating points, verify that a defined syntax is not empty
 ▪ 0af9ce92 rcfile: close off a syntax when a non-syntax command is encountered
 ▪ 4e14a8a9 tweaks: remove two unneeded assignments, and improve a comment
 ▪ accd17c2 tweaks: remove four unneeded pre-processor directives
 ▪ e8eb30ca tweaks: just mark four rcfile errors for translation, like the others
 ▪ 36bd68f3 tweaks: rename a function, to better suit what it does
 ▪ 03692363 tweaks: move a syntax check to a better place, to reduce duplication
 ▪ 0e94575c rcfile: check for missing color commands only when a syntax is still open
 ▪ 27cc3117 tweaks: rename two parameters, for more contrast, and elide another
 ▪ 19f71632 tweaks: remove an unneeded "closing" of a syntax after extending it
 ▪ e3f18e7a tweaks: rename two variables, and frob some comments
 ▪ b55923f5 tweaks: reshuffle some lines, to group things more sensibly
 ▪ 7028adf2 rcfile: fully read each included file, so all its syntaxes are seen
 ▪ d7df7c69 tweaks: elide a pre-processor #else clause, by using braces instead
 ▪ ce69d5be tweaks: condense two comments, and normalize the whitespace of a label
 ▪ 3da42402 tweaks: rename a variable, to fit a little better
 ▪ 43caf7bb tweaks: avoid an unneeded, extra stat() for temporary files
 ▪ e8e30e51 tweaks: elide an unneeded, duplicate stat() for the FIFO check
 ▪ 189de5ee files: suppress feedback when writing an emergency or temporary file
 ▪ c57d040e tweaks: don't bother calling mblen() in a non-UTF-8 build
 ▪ 0adb15c7 display: properly show all characters in a non-UTF-8 build
 ▪ 1e48df38 build: avoid a warning when using --disable-utf8
 ▪ d4777758 build: avoid a warning on FreeBSD, OpenBSD, and Alpine
 ▪ ed40fd80 tweaks: reorder some code, to further optimize display_string() for ASCII
 ▪ 5c4b0b38 chars: redo the speedup for plain ASCII from three commits ago

 ▼ external/skia/
 ▪ 1193a855ff Merge "Snap for 5622519 from 7b904fb0143c85626198c8b65f9f9ea2de8cc271 to pi-platform-release am: 9d46f09202" into pie-gsi
 ▪ afe8ba9906 Snap for 5622519 from 7b904fb0143c85626198c8b65f9f9ea2de8cc271 to pi-platform-release am: 9d46f09202
 ▪ 9d46f09202 Snap for 5622519 from 7b904fb0143c85626198c8b65f9f9ea2de8cc271 to pi-platform-release
 ▪ 9409c9e433 Merge tag 'android-9.0.0_r44' into pie

 ▼ external/vim/
 ▪ fc4e70ca5 vimrc.android: Set nomodeline

 ▼ frameworks/av/
 ▪ 377dd121d8 Merge "Snap for 5622519 from f29ab2dbaaf2635f403be82238b18ad3ff673514 to pi-platform-release am: bcb87e5568" into pie-gsi
 ▪ 1997ff037c Snap for 5622519 from f29ab2dbaaf2635f403be82238b18ad3ff673514 to pi-platform-release am: bcb87e5568
 ▪ 6d33ddd453 Merge "Snap for 5600800 from 127949a9f35c23446a2ce4d8821fd7df21a3fa77 to pi-platform-release am: 8a898328aa" into pie-gsi
 ▪ 98bc67e01b Snap for 5600800 from 127949a9f35c23446a2ce4d8821fd7df21a3fa77 to pi-platform-release am: 8a898328aa
 ▪ bcb87e5568 Snap for 5622519 from f29ab2dbaaf2635f403be82238b18ad3ff673514 to pi-platform-release
 ▪ 8a898328aa Snap for 5600800 from 127949a9f35c23446a2ce4d8821fd7df21a3fa77 to pi-platform-release
 ▪ 02261bd80c Merge tag 'android-9.0.0_r44' into pie
 ▪ 8fa5a24668 CameraService: Default to HAL1 for OPCam if not specified
 ▪ fa4a379ff8 Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ 90292b7e24 AMR WB encoder: prevent OOB write in ACELP_4t64_fx
 ▪ af597ae487 httplive: detect oom if playlist is infinite
 ▪ 62da9cd2ad Fix overflow/dos in 3gg text description parsing
 ▪ 1f76f20b2f DO NOT MERGE: audiopolicy: Remove raw pointer references to AudioMix
 ▪ 9787b12fcd AMR WB encoder: prevent OOB write in ACELP_4t64_fx
 ▪ d53e0fa8b1 httplive: detect oom if playlist is infinite
 ▪ 0c4cc7472b Fix overflow/dos in 3gg text description parsing
 ▪ d4305e19f9 DO NOT MERGE: audiopolicy: Remove raw pointer references to AudioMix

 ▼ frameworks/base/
 ▪ f43265ba00a SystemUI: Protect against terrible music players
 ▪ 266e6c68dac perfLock: Enable ActivityBoost
 ▪ 2d685898458 Prevent crash in TTS engine due to improper configuration
 ▪ 4cf1c0fbbbe Merge "Snap for 5622519 from b869620327dabaebe715a7d8fb3d12cdddd5a221 to pi-platform-release am: 5c3946d093" into pie-gsi
 ▪ 01577783a25 Snap for 5622519 from b869620327dabaebe715a7d8fb3d12cdddd5a221 to pi-platform-release am: 5c3946d093
 ▪ b1cec28b95d Merge "Snap for 5600800 from b3f4ac23836263a1f7844b12455a81150c92bace to pi-platform-release am: f84f3454c7" into pie-gsi
 ▪ d8814cdc190 Snap for 5600800 from b3f4ac23836263a1f7844b12455a81150c92bace to pi-platform-release am: f84f3454c7
 ▪ 5c3946d0935 Snap for 5622519 from b869620327dabaebe715a7d8fb3d12cdddd5a221 to pi-platform-release
 ▪ f84f3454c7f Snap for 5600800 from b3f4ac23836263a1f7844b12455a81150c92bace to pi-platform-release
 ▪ dcc548fc5f7 Merge tag 'android-9.0.0_r45' of https://android.googlesource.com/platform/frameworks/base into pie
 ▪ 2a484a6d2d8 base: Q seekbar: make the seekbar transparent for non-seekable notifs
 ▪ 44b9be092cf Frameworks: Slightly refactor Parcel code
 ▪ 5f1c7c38e79 Stable seek bar positioning
 ▪ 1472d68d043 GamingMode: Clean up and refine [1/3]
 ▪ f2821480540 SmartCharging: add reset battery stats option [1/2]
 ▪ 30365a6ab3f SmartCharging: allow user set resume level [1/2]
 ▪ 8815af4b6e6 Revert "ActivityRecord: add fw boost after r33 merge"
 ▪ e0255c1f837 SystemUI: Use proper lock icon scale on dismissing notification panel view
 ▪ 0382f7c7a68 SystemUI: Handle orientation and screenSize changes for TunerActivity
 ▪ 93a6310d301 SystemUI: Adjust battery and location icon size
 ▪ 5a752034702 Revert "Keyguard: Forward port lockscreen quick unlock (1/2)"
 ▪ d0e02f20f9e Update JPN language
 ▪ d54003dbae4 SystemUI: Expose ambient music ticker bottom margin
 ▪ b05590dc5e0 SystemUI: Statusbar layout improvements
 ▪ bffada2d905 Allow SBC as HD audio codec in Bluetooth device configuration
 ▪ f3ba1ed2f8e Add Dual Channel into Bluetooth Audio Channel Mode developer options menu
 ▪ 9bea6223bbc Add CHANNEL_MODE_DUAL_CHANNEL constant
 ▪ a7a2e5f8dfc Revert "Add Dual Channel into Bluetooth Audio Channel Mode developer options menu"
 ▪ 01602607b6b base: Import Android Q activity animations
 ▪ 69183cd2bea PhoneWindowManager: Set delay for screenshot shortcut to 0
 ▪ 50cceca22fa AudioService: Remove Analog Dock from fixed-volume devices
 ▪ ac6c605044f Reduce the padding between media controls & seekbar
 ▪ 4b3e0f87919 fwb: Improve AOSP twilight code
 ▪ 03d40904670 LiveDisplayService: Disable ColorTemperature when NightDisplay is available
 ▪ 5a70e8db431 GamingMode: add master switch [1/2]
 ▪ e6457044945 GamingMode: cleanup and fix a bit
 ▪ 95d660b365e GamingMode: Rewrite implementation [1/2]
 ▪ c87940305d2 GamingMode: add more ringer modes [1/2]
 ▪ 47c37cd2835 Gaming Mode: minor improvements
 ▪ e6984da5e3e base: FireHound Gaming [1/4]
 ▪ 085dc0b026d Revert "Gaming Mode"
 ▪ 3682dffcbb5 Add optional OP cam support
 ▪ d98f919be24 Revert "FB: Add oneplus camera support"
 ▪ 2f1495c5606 base: notch-city: Don't work if the device doesn't have a cutout
 ▪ 9ea3eba9d66 base: Add 5 more styles for qs
 ▪ 76dcaf4ffe5 BatteryStatsImpl: Reset battery stats at 95 percent
 ▪ f4ac81a6750 Reload Pixel Home Animation without reboot
 ▪ ae09953a2c4 Pixel Navbar animation toggle [1/2]
 ▪ 93861b232ed SystemUI: Add navigation touch animation support
 ▪ 79a99f68ae5 SystemUI: Remove older Pixel Animation
 ▪ 1d7c71a8f69 SystemUI: Fix several layout bugs
 ▪ ae0c2eeba3f Merge cherrypicks of [8066319] into pi-qpr3-b-release
 ▪ fa00d60b123 Collect APK certificates after an OTA, rather than relying on timestamps
 ▪ d29c48e3c31 Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ a37574256cc [RESTRICT AUTOMERGE] Protect VPN dialogs against overlay.
 ▪ 1924f6d94de Clear the Parcel before writing an exception during a transaction
 ▪ 205e540a647 DO NOT MERGE SurfaceControl: Fix captureLayers JNI
 ▪ 1c2fcd62ec9 Clean up ProcessRecord when reuse a pid.
 ▪ 8a4b671f014 [RESTRICT AUTOMERGE] Fix NullPointerException when mLockPatternUtils is not set.
 ▪ 236b44274eb Update API docs for TelecomManager#endCall.
 ▪ 2917b1f0d7c [RESTRICT AUTOMERGE] Make LockTaskController default behaviour match ScreenPinningSettings.
 ▪ f82b87ed95c Merge branch 'pie-gsi' of https://android.googlesource.com/platform/frameworks/base into HEAD
 ▪ 576f83aa0ed fix
 ▪ 37524965f02 wifi: Add wifi latency level API to WifiManager
 ▪ eca56ed280a wifi: Support to add vendor based Intent namespace
 ▪ 31703d98e8f Wifi: Define DATA_STALL intent to broadcast message
 ▪ 727a3e95ffa wifi: Notify Connected/Disconnected Mac address on hotspot
 ▪ 4bab90088e6 Wifi: Send DHCP DISCOVER with rapid commit
 ▪ b20155920eb Wifi: Add support for repeater mode
 ▪ 506895b3317 base: add support for SAP+SAP.
 ▪ ad924e7196a Wifi: Allow saving sim_num for EAP-SIM/AKA/AKA_PRIME configurations
 ▪ 3e326462f81 framework: Add Wifi Simple Configuration support
 ▪ d916ea9e9d6 framework: Add WiFi Display R2 device info
 ▪ 4d9d03f6564 wifi: Add APIs and keymgmt to support WPA3(DPP,SAE,OWE,SuiteB).
 ▪ ed97eb18df1 Wifi: Add FILS support in WifiConfiguration
 ▪ 63af0d38da8 Clear the Parcel before writing an exception during a transaction
 ▪ 61caa7b1e1a [RESTRICT AUTOMERGE] Protect VPN dialogs against overlay.
 ▪ 17d2c5fbf60 DO NOT MERGE SurfaceControl: Fix captureLayers JNI
 ▪ cb6032432f5 Clean up ProcessRecord when reuse a pid.
 ▪ b30eff949ad Update API docs for TelecomManager#endCall.
 ▪ fcc855f0c1f [RESTRICT AUTOMERGE] Fix NullPointerException when mLockPatternUtils is not set.
 ▪ 2c028321d80 [RESTRICT AUTOMERGE] Make LockTaskController default behaviour match ScreenPinningSettings.
 ▪ 244676a4ad1 [RESTRICT AUTOMERGE] Careful with screenshots containing secure layers!
 ▪ 1bc7e4dca32 Revert "[RESTRICT AUTOMERGE] Careful with screenshots containing secure layers!"
 ▪ 6b08c83e116 Support CALLBACK_TYPE_SENSOR_ROUTING
 ▪ cd66dc3609e Revert "SystemUI: Add Cellular tile icon from OOS"
 ▪ 6c970393d96 Keyguard: Don't listen for fingerprint when prox.sensor is covered
 ▪ 6ef20e8b7cd show bt battery for all devices
 ▪ 604055af24a change battery save color
 ▪ 8b694297134 fix answer from home key
 ▪ 2db5080674a toggle torch proximity check [1/2]
 ▪ 1a27b3018ed proximity check for all wake keys
 ▪ c0797a755ec Havoc Build Date [1/2]
 ▪ e63801109b4 fix button backlight
 ▪ 5ba57310b8a fix priv-apps permissions
 ▪ fab5130d96c for gemini: Revert "Revert "Proximity check on wake""
 ▪ 28d1664c669 Revert "HW: Fix Home button during call"

 ▼ frameworks/native/
 ▪ 6431a9bc8 Snap for 5622519 from 2062c5a408eb44ead19b7e2e797e93b5781ae931 to pi-platform-release
 ▪ d3f04ec40 Snap for 5600800 from 42a149d853a6af9b6a04ef00ba644319a4c13ead to pi-platform-release
 ▪ 98e204332 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into pie
 ▪ 85f026a5d Merge tag 'android-9.0.0_r45' of https://android.googlesource.com/platform/frameworks/native into HEAD
 ▪ 818341590 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into HEAD
 ▪ c91cc94ee [SF] Fix unittest crash
 ▪ 5e33fba68 Revert "Graphics: Avoid vulkan libs access if vulkan is disabled"
 ▪ b1d2e195a Merge c8288466da5169f6bfc50cc72cd9df5cb32a069f on remote branch
 ▪ 10308535f Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ 0038364ef libbinder: Status: check dataPosition sets.
 ▪ db9a71219 libbinder: readCString: no ubsan sub-overflow
 ▪ 6aee63942 libbinder: Status: check dataPosition sets.
 ▪ 6dc120c3e libbinder: readCString: no ubsan sub-overflow
 ▪ 112193140 [RESTRICT AUTOMERGE] SurfaceFlinger: Indicate whether we have captured secure layers.
 ▪ d5fd88bfc Revert "[RESTRICT AUTOMERGE] SurfaceFlinger: Indicate whether we have captured secure layers."

 ▼ frameworks/opt/net/ims/
 ▪ 85a0433 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

 ▼ frameworks/opt/net/wifi/
 ▪ 81ee77957 Prevent scan searching overhead
 ▪ 4114b3280 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into pie
 ▪ 340f25a36 Merge 0eaec84e98bf76cc9aa6272658f3fa738ce46899 on remote branch
 ▪ 5da0d6922 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into pie
 ▪ 9a289059c Revert "Disable hostapd during wifi initialization."
 ▪ b787217d4 Revert "DO NOT MERGE Add data integrity checking for wifi passwords"
 ▪ 6fcda2bfa Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into HEAD

 ▼ frameworks/opt/telephony/
 ▪ 3baad630a5 Merge b2cba5ec1e7dc77ad76c136f31aab57bc927ce4e on remote branch
 ▪ 741849452e Snap for 5622519 from fe4b8179b63eb376b3b189ef9b3463ad523b26f1 to pi-platform-release
 ▪ 6299d80d1a Merge b2cba5ec1e7dc77ad76c136f31aab57bc927ce4e on remote branch
 ▪ 716d701da6 Snap for 5690386 from 783a4e45c31c958a96a005c06767d2351df59d9b to p-keystone-qcom-release
 ▪ 783a4e45c3 Add check for CSIM application presence
 ▪ 0e8baa5444 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

 ▼ hardware/interfaces/
 ▪ 64020a935 Merge 2f57e8e3ad3588e10bbbcd56c22c03c7c78e5e0e on remote branch
 ▪ 0ef08c828 Snap for 5622519 from b095226d9286245c7d05088a441c2cff43d2ae65 to pi-platform-release
 ▪ 905f372c7 Merge 2f57e8e3ad3588e10bbbcd56c22c03c7c78e5e0e on remote branch
 ▪ d53190555 Merge tag 'LA.UM.7.6.2.r1-09100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 8555daa7b Merge 2f57e8e3ad3588e10bbbcd56c22c03c7c78e5e0e on remote branch
 ▪ e6b2eddfe Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into HEAD

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ a638831c Merge 880800db1da4ae6b90e0670e65af240bbbc66f49 on remote branch
 ▪ 4451a4dd Merge "configs: Enable AAC frame control for A2DP"
 ▪ d18b52a5 Merge "hal: Add QAP extention"
 ▪ c7d1b59a hal: add apptype as a part of event_value
 ▪ 619761e5 hal: move gef device notification after sample rate adjustment
 ▪ 902f7d10 audio: introduce dedicated adev->cal_lock for gef interfaces
 ▪ 996a0a40 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ 7617ea5f Merge b0701bdc1d9161042f70db4ea335023f162f6b19 on remote branch
 ▪ 880800db Merge "hal: Add APIs for HIDL 5.0"
 ▪ d3cbec1b Merge "hal: Fix no audio during voice call with concurrent combo use case"
 ▪ 2fad508b Merge "qap: test: Enable ecref path"
 ▪ acef98f3 hal: Add APIs for HIDL 5.0
 ▪ f080ba3e configs: msm8937: Add speaker and headphones paths
 ▪ 0b1121ea Merge b0701bdc1d9161042f70db4ea335023f162f6b19 on remote branch
 ▪ eb4cdf25 configs: Enable AAC frame control for A2DP
 ▪ e2938530 audio: check for usecase type before accessing stream.out
 ▪ 4f1b8750 config: msm8937: enable Audio HIDL HAL 5.0
 ▪ e1b7160b Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ b0701bdc Merge "hal: get correspoding sample rate per device when sending cal data"
 ▪ b1f11834 Merge "Bluetooth: Add support of non offload by default"
 ▪ 24d53372 Merge "hal: fix in_call flag is not reset after voice call stop"
 ▪ 09cabbc7 Merge "hal: force device switch when BT SCO is off"
 ▪ da6cf741 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ 0eab043c hal: fix in_call flag is not reset after voice call stop
 ▪ afffd203 hal: Add QAP extention
 ▪ 004db97f qap: test: Enable ecref path
 ▪ a1bb2f59 Merge 3d42a81fd26cf94ab1e00ca37e96f7b3ff56f898 on remote branch
 ▪ ce982b62 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into HEAD
 ▪ 3d42a81f Merge "hal: remove HAL access to channel number mixer control"
 ▪ e36e6e4d Bluetooth: Add support of non offload by default

 ▼ hardware/qcom/bt-caf/
 ▪ 9cd3b55 Merge b7bdccd743d37f592cf4e407c5ae9c9e1f130043 on remote branch
 ▪ 6848bc4 Merge b7bdccd743d37f592cf4e407c5ae9c9e1f130043 on remote branch
 ▪ dd952b3 Merge tag 'LA.UM.7.6.2.r1-09100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into 9.0
 ▪ 989ebd0 Merge b7bdccd743d37f592cf4e407c5ae9c9e1f130043 on remote branch
 ▪ aa6520b Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into HEAD

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ 30c4250c Merge b361ad8b63a12b11bbadd6adca4ffcb632bba8dc on remote branch
 ▪ 55184b8e Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0
 ▪ a47563f4 Merge e2add2e51bfce096053110c55199da7dc8f4e5a3 on remote branch
 ▪ b361ad8b sdm: Fix resolution mismatch between mixer and active config.
 ▪ ce561239 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0
 ▪ 1b1da616 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into HEAD

 ▼ hardware/qcom/fm/

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 96d2d1e4 Merge 429b73b3990f743f16b292cbd6a78ccfb80b1222 on remote branch
 ▪ 57beea57 mm-video-v4l2: vidc: support interlace fall back to NV12 linear
 ▪ 7624eedc mm-video-v4l2: vidc: Fix for CTS ColorAspects tests
 ▪ 429b73b3 Merge "venc: Disable RGBA direct input to Venus"
 ▪ e01fc082 mm-core: Remove secure codecs for low RAM targets
 ▪ f6c507dd mm-core: Remove secure codecs for low RAM targets
 ▪ 41ef75ae Merge "mm-core: Add MPEG-H decoder support"
 ▪ 6512165b Merge 5029253b815df1b49da827dbd5514a6f3c87e3c1 on remote branch
 ▪ 02dc1af9 Merge "mm-core: Enable MPEG-H Encoder Format"
 ▪ f6105da6 Merge "QCMetaData: Add keys for MPEG-H 3D Audio CSD"
 ▪ 5d96d890 QCMetaData: Add keys for MPEG-H 3D Audio CSD
 ▪ 22cabb51 mm-video-v4l2: vidc: Add custom buffer size for input port
 ▪ 6d63440f mm-core: Add HOA type to PCMModeType
 ▪ 13c9c202 mm-core: Add MPEG-H decoder support
 ▪ cc6bec46 mm-core: Enable MPEG-H Encoder Format

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 57beea571 mm-video-v4l2: vidc: support interlace fall back to NV12 linear
 ▪ 7624eedca mm-video-v4l2: vidc: Fix for CTS ColorAspects tests
 ▪ b9c4d9644 Merge 429b73b3990f743f16b292cbd6a78ccfb80b1222 on remote branch
 ▪ 25810e0b1 Merge 429b73b3990f743f16b292cbd6a78ccfb80b1222 on remote branch
 ▪ f1451b065 Merge 429b73b3990f743f16b292cbd6a78ccfb80b1222 on remote branch
 ▪ 429b73b39 Merge "venc: Disable RGBA direct input to Venus"
 ▪ 22cabb51d mm-video-v4l2: vidc: Add custom buffer size for input port

 ▼ hardware/qcom/power/
 ▪ 2846b24 qcom: power: Stop log spam "QCOM PowerHAL: Failed to acquire lock"

 ▼ hardware/qcom/wlan-caf/
 ▪ 6f7406d Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/wlan into 9.0
 ▪ 9f99f21 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/wlan into HEAD

 ▼ hardware/ril/
 ▪ 9a16b612 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/ril into HEAD

 ▼ kernel/xiaomi/msm8996/
 ▪ 207166bdacc4 Merge "qcacld-2.0: Add host tx queue statistic" into wlan-cld2.driver.lnx.1.0
 ▪ b70247d7b061 Merge f66a9554da973ef80498e3f0a6547fa31a7b9872 on remote branch
 ▪ fbb242e0f806 qcacld-2.0: Add host tx queue statistic
 ▪ 61f49f983136 qcacld-2.0: Add rx time statistic for dump survey
 ▪ a4048283c56c qcacld-2.0: Adjust loglevel in __wmi_control_rx()
 ▪ cb3f8b9fa2d6 ARM: dts: msm: Correct year marking
 ▪ 75ea33d18537 qcacld-2.0: Adjust CFG_SET_TSF_GPIO_PIN_MAX value to 255
 ▪ c17193a2835f qcacld-2.0: Adjust loglevel in txrx
 ▪ cd15da232745 qcacld-2.0: Fix loss of DSRC per packet tx stats
 ▪ a97fdb54ece0 Merge "qcacld-2.0: Zero sRegulatoryChannel before create new reg entry" into wlan-cld2.driver.lnx.1.0
 ▪ b10c66ab6149 mbcache2: Speed up cache entry creation
 ▪ bf2a2cdbf3f0 Makefile: Force ARCH to be arm64
 ▪ 3f40b5396126 dmaengine: Fix memory leak in dma_async_device_register
 ▪ b1185ab52571 msm: kgsl: Avoid dynamically allocating small command buffers
 ▪ 2c2058cbf59a ext4 crypto: Use a larger on-stack file name buffer
 ▪ 5d3ae62631f3 Update defconfigs
 ▪ 3aa18820db4a Let Google Camera work in the background
 ▪ 034e25227a10 proc: Don't let Google Camera and Settings run in the background
 ▪ a5fd062f1fbd selinux: Avoid dynamic memory allocation for small context buffers
 ▪ ef32d8aac4c9 soc: qcom: smp2p: Fix compile errors when testing is disabled
 ▪ 9140a34d7956 qcacld-2.0: Set ini 5g_rssi_penalize_factor as signed integer
 ▪ 9849af673e95 qcacld-2.0: Set ini 5g_rssi_boost_threshold as signed integer
 ▪ 388e1ab7c3c4 qcacld-2.0: Zero sRegulatoryChannel before create new reg entry
 ▪ c7a521877469 qcacld-2.0: Adjust loglevel in print_hdd_cfg()
 ▪ 52c14718b7a2 qcacld-2.0: Adjust loglevel in print_hdd_cfg()
 ▪ fbcc8ccccc94 qcacld-2.0: Fix potential double free in wma_log_supported_evt_handler
 ▪ e37eec1d192b crypto: msm: Don't bail out when debugfs creation fails
 ▪ a8a2efcffd4b Merge eb7b0783fc30d5ffd963b78f8516361d104139a4 on remote branch
 ▪ 9bc680008f30 Merge df4b4c3503dd745baa36d0b325086fd0f3a87f06 on remote branch
 ▪ 54666c8ad7b8 msm: kgsl: Add missing check for snapshot IB dump
 ▪ 82c47d336abf config: disable KALLSYMS & MODULES
 ▪ 7acd70da8e11 update .gitignore
 ▪ f66a9554da97 Merge "qcacld-2.0: Add GPIO config and output setting" into wlan-cld2.driver.lnx.1.0
 ▪ df4b4c3503dd Merge "defconfig: msm: Disable EXT2 and EXT3 FS configs for MSM8996"
 ▪ 33637ee1202e Merge "qcacld-2.0: Set SAE auth type for PMKID cached connect request" into wlan-cld2.driver.lnx.1.0
 ▪ 63c5d97cad35 Merge "qcacld-2.0: Define FEATURE_LARGE_PREALLOC" into wlan-cld2.driver.lnx.1.0
 ▪ 852b602554ec Merge "qcacld-2.0: Fix potential memory leak and wrong bw value" into wlan-cld2.driver.lnx.1.0
 ▪ 627784f616e0 qcacld-2.0: Add GPIO config and output setting
 ▪ 83165da2e435 qcacld-2.0: Set SAE auth type for PMKID cached connect request
 ▪ 17ea8f0bfd51 qcacld-2.0: Fix potential memory leak and wrong bw value
 ▪ 50573bd5b655 ARM: dts: msm: Increase TZ apps region to 2MB on msm8909w
 ▪ 198d5b8aacd5 qcacld-2.0: Define FEATURE_LARGE_PREALLOC
 ▪ 318cd86a7e13 qcacld-2.0: Provide iwpriv to configure candidate channel
 ▪ e5b25a1ab446 diag: Prevent out-of-bound access while processing userspace data
 ▪ 9385e8a53ee6 defconfig: msm: Disable EXT2 and EXT3 FS configs for MSM8996
 ▪ 20c6f41cb832 msm: adsprpc: maintain local copy of rpra offloaded to DSP
 ▪ 501b4eb99590 Merge "asoc: Ratelimit error logs to avoid excessive logging"
 ▪ 6e0deb71d52a Merge "msm: sensor: actuator: fix out of bound read for bivcm region params"
 ▪ 9e1ad96a5bd3 asoc: Ratelimit error logs to avoid excessive logging
 ▪ d71d4382489e Merge "dsp: q6core: validate payload size before memory copy"
 ▪ c67dc743827b msm: sensor: actuator: fix out of bound read for bivcm region params
 ▪ 3533dd0503d0 fbdev: msm: check the length of the external input buffer properly
 ▪ d05907cfa913 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 320a23193a6c soc: qcom: smem: validate fields of shared structures
 ▪ 7166310c581f Merge tag 'LA.UM.7.5.r1-05300-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 4dd3c77e97c2 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into HEAD
 ▪ eb7b0783fc30 Merge "qcacld-2.0: Avoid buffer leakage when handle 11w rmf" into wlan-cld2.driver.lnx.1.0
 ▪ 7fa073eeb83a Merge 78aa41ba569c485b91955fc5c0eb3e075fc3ee30 on remote branch
 ▪ 5ec1870384fa qcacld-2.0: Fix build error in third party platform
 ▪ 76561bc8756f Merge "qcacld-2.0: Update API in driver to support kernel version 3.10" into wlan-cld2.driver.lnx.1.0
 ▪ 3fb22c62d595 Merge "qcacld-2.0: Add ini key disable smart antenna" into wlan-cld2.driver.lnx.1.0
 ▪ 27256c5d09fe Merge "net: sockev: avoid races between sockev and socket_close"
 ▪ f61d8205fdb6 net: sockev: avoid races between sockev and socket_close
 ▪ fa863c420283 Merge "qcom: smcinvoke: Fix stack overflow for arr_filp"
 ▪ 7eacb9ad7805 Merge "msm: vidc: add additional check to avoid out of bound access"
 ▪ ac662d0f5c2e msm: vidc: add additional check to avoid out of bound access
 ▪ 902b817701c7 Merge "msm: ipa3: Fix to validate the buffer size"
 ▪ 3c9b3e72e908 qcacld-2.0: Update API in driver to support kernel version 3.10

 ▼ packages/apps/Bluetooth/
 ▪ b381d3bf Merge branch '9.0' of https://github.com/syberia-project/platform_packages_apps_Bluetooth into HEAD

 ▼ packages/apps/CellBroadcastReceiver/
 ▪ 54e2dfb Merge "Snap for 5622519 from 9f6cd249778d11d394692e9ef79840dfe28b9dc8 to pi-platform-release am: cb84ec2751" into pie-gsi
 ▪ 6d13c9a Snap for 5622519 from 9f6cd249778d11d394692e9ef79840dfe28b9dc8 to pi-platform-release am: cb84ec2751
 ▪ cb84ec2 Snap for 5622519 from 9f6cd249778d11d394692e9ef79840dfe28b9dc8 to pi-platform-release

 ▼ packages/apps/Contacts/
 ▪ 29db2b04d Merge "Snap for 5622519 from 4f49c1c228daab1861c2e0d13dda03b2df2a9582 to pi-platform-release am: 5889de7669" into pie-gsi
 ▪ c106966d7 Snap for 5622519 from 4f49c1c228daab1861c2e0d13dda03b2df2a9582 to pi-platform-release am: 5889de7669
 ▪ 5889de766 Snap for 5622519 from 4f49c1c228daab1861c2e0d13dda03b2df2a9582 to pi-platform-release

 ▼ packages/apps/DocumentsUI/
 ▪ 0252d26f Snap for 5622519 from 9b6f2643661e4667493debdcccbba3ec518eb963 to pi-platform-release am: 003bac8220
 ▪ 003bac82 Snap for 5622519 from 9b6f2643661e4667493debdcccbba3ec518eb963 to pi-platform-release

 ▼ packages/apps/EmergencyInfo/
 ▪ 5c9a761 Snap for 5622519 from 1f34f131bd37703b5162c65ee4d276eb05248595 to pi-platform-release am: 9a5e31527f
 ▪ 9a5e315 Snap for 5622519 from 1f34f131bd37703b5162c65ee4d276eb05248595 to pi-platform-release

 ▼ packages/apps/HavocSettings/
 ▪ 24f100b GameMode: remove hwkeys toggle on non-hwkeys devices
 ▪ 186bcf8 GamingMode: Clean up and refine [3/3]
 ▪ 7933398 Add Bacon to devices
 ▪ 109796c Add OnePlus 7 Pro to devices
 ▪ 6e953ca Add Xiaomi Redmi 6 Pro (Sakura)
 ▪ 70a246e Cutout force fullscreen: Disable fast scroller
 ▪ 8d5d358 GamingMode: cleanup a bit
 ▪ 8be52e4 GamingMode: add master switch [2/2]
 ▪ fe3e122 GamingMode: Rewrite implementation [2/2]
 ▪ e61b992 GamingMode: add more ringer modes [2/2]
 ▪ 8b79848 Settings: Gaming Mode revamped [2/4]
 ▪ 55e447d Settings: Add 5 more qs styles

 ▼ packages/apps/Nfc/
 ▪ bd9db4f5 Merge "Snap for 5622519 from 18ad94ed67b2dfc3dfe59c7d6eb980e7ef1f9914 to pi-platform-release am: f6d7678d7e" into pie-gsi
 ▪ 59960655 Snap for 5622519 from 18ad94ed67b2dfc3dfe59c7d6eb980e7ef1f9914 to pi-platform-release am: f6d7678d7e
 ▪ f6d7678d Snap for 5622519 from 18ad94ed67b2dfc3dfe59c7d6eb980e7ef1f9914 to pi-platform-release
 ▪ 4c7873cc Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ ab9a7222 Prevent OOB Read in Mfc_Transceive
 ▪ 79f25156 Prevent OOB write in Mfc_Transceive
 ▪ bfa3d8c9 Prevent OOB write in phFriNfc_ExtnsTransceive
 ▪ 6543f9bf Prevent OOB Read in Mfc_Transceive
 ▪ 0ac0c818 Prevent OOB write in Mfc_Transceive
 ▪ 387d8889 Prevent OOB write in phFriNfc_ExtnsTransceive

 ▼ packages/apps/PackageInstaller/
 ▪ 80892d48 Merge "Snap for 5622519 from 73e82477c145d8178180382a5ad2b9f9fa4b8235 to pi-platform-release am: dbd2ae2b63" into pie-gsi
 ▪ fed0811f Snap for 5622519 from 73e82477c145d8178180382a5ad2b9f9fa4b8235 to pi-platform-release am: dbd2ae2b63
 ▪ f39dc13e Merge "Snap for 5600800 from d6b752934f71c3c59b6339900f07b204dce0d505 to pi-platform-release am: b5641733bf" into pie-gsi
 ▪ 1ca66ade Snap for 5600800 from d6b752934f71c3c59b6339900f07b204dce0d505 to pi-platform-release am: b5641733bf
 ▪ dbd2ae2b Snap for 5622519 from 73e82477c145d8178180382a5ad2b9f9fa4b8235 to pi-platform-release
 ▪ b5641733 Snap for 5600800 from d6b752934f71c3c59b6339900f07b204dce0d505 to pi-platform-release
 ▪ 89494f01 Merge tag 'android-9.0.0_r44' into pie

 ▼ packages/apps/Settings/
 ▪ dabc81c058 Merge "Snap for 5622519 from fd365ae91ebe924197c5f443c889928eb07bd02c to pi-platform-release am: ec58694ae8" into pie-gsi
 ▪ 783d0549dd Snap for 5622519 from fd365ae91ebe924197c5f443c889928eb07bd02c to pi-platform-release am: ec58694ae8
 ▪ ec58694ae8 Snap for 5622519 from fd365ae91ebe924197c5f443c889928eb07bd02c to pi-platform-release
 ▪ cdcda73a8c GamingMode: Clean up and refine [2/3]
 ▪ 0267a81fae SmartCharging: add reset battery stats option [2/2]
 ▪ f19fe3d111 SmartCharging: allow user set resume level [2/2]
 ▪ 045b871c1a Revert "Keyguard: Forward port lockscreen quick unlock (2/2)"
 ▪ 1b8e98cef8 Settings: appops: Drop GET_UNINSTALLED_PACKAGES from getApplicationInfo()
 ▪ 160bc0d3d6 Add Dual Channel into Bluetooth Audio Channel Mode developer options menu
 ▪ db13cdfad6 Revert "Add Dual Channel into Bluetooth Audio Channel Mode developer options menu"
 ▪ be473b8991 Use a proper bool check for notification light color option
 ▪ dbc6a0387a fuelgauge: Fix NPE
 ▪ 04fc272c39 Revert "Port "Battery Usage Alerts" feature from factory images"
 ▪ 4a949c0640 Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ 6183b9b1ac Do not allow draw on top for App notification settings
 ▪ a945243b5c [RESTRICT AUTOMERGE] Make ScreenPinningSettings behaviour consistent with LockTaskController.

 ▼ packages/apps/SmartNav/
 ▪ 68fbdaa SmartNav: opa: fix Pixel animation on SB with new SysUI opa

 ▼ packages/apps/UnifiedEmail/
 ▪ b47402d44 AOSP/UnifiedEmail - bug fix to composing messages.

 ▼ packages/inputmethods/LatinIME/
 ▪ 3f40ccc26 Merge "Snap for 5622519 from e035e3c31904c790e5c3d88a78b98d5566038af3 to pi-platform-release am: 8c6c1e2be6" into pie-gsi
 ▪ 55f5ab770 Snap for 5622519 from e035e3c31904c790e5c3d88a78b98d5566038af3 to pi-platform-release am: 8c6c1e2be6
 ▪ 8c6c1e2be Snap for 5622519 from e035e3c31904c790e5c3d88a78b98d5566038af3 to pi-platform-release

 ▼ packages/providers/MediaProvider/
 ▪ 62abcea Merge "Snap for 5622519 from 3750847861dd817fe5a3ec3d5d7ac0bb6e3d5016 to pi-platform-release am: f5e8f5b0d5" into pie-gsi
 ▪ 6525cbc Snap for 5622519 from 3750847861dd817fe5a3ec3d5d7ac0bb6e3d5016 to pi-platform-release am: f5e8f5b0d5
 ▪ f5e8f5b Snap for 5622519 from 3750847861dd817fe5a3ec3d5d7ac0bb6e3d5016 to pi-platform-release

 ▼ packages/services/Telecomm/
 ▪ e0f8071b Snap for 5622519 from b65ecc5a1264c78e2543dc6beade501c4d60b282 to pi-platform-release am: c83df82dbc
 ▪ c83df82d Snap for 5622519 from b65ecc5a1264c78e2543dc6beade501c4d60b282 to pi-platform-release
 ▪ 239044b2 Change bluetooth routing to be more responsive
 ▪ 5c516a19 Merge 51381c46f289fa7c32480890286a6cce9c717b0c on remote branch
 ▪ f42d9e02 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into HEAD
 ▪ 694866f4 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into HEAD
 ▪ 10102baf Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ 4f04632f DO NOT MERGE Add flag to default dialer change dialog
 ▪ e01da9a8 Prevent TelecomManager#endCall from ending emergency calls.
 ▪ 941cb233 DO NOT MERGE Add flag to default dialer change dialog
 ▪ 275e8826 Prevent TelecomManager#endCall from ending emergency calls.

 ▼ packages/services/Telephony/
 ▪ 1b3b39af8 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into HEAD
 ▪ 5e8a96ec4 Telephony: Remove duplicate definition
 ▪ 35862ae79 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into HEAD

 ▼ prebuilts/build-tools/
 ▪ 61dbccf build-tools: Update for new sources and clang

 ▼ prebuilts/r8/
 ▪ 1e2b56a r8: Update D8 and R8 to 1.6.13-local
 ▪ efa16a4 Fix d8 and r8-compat-proguard scripts to handle quoted options
 ▪ 63493ac Provide 2GB of heap space to the Java VM when running D8 and R8
 ▪ 213db48 r8: Update D8 and R8 to 1.6.7-dev

 ▼ system/bt/
 ▪ 4b1d4904a Snap for 5622519 from fef57bda2a3cf2dca83848db5b8e789cb32dac1d to pi-platform-release am: db4e774cab
 ▪ abff8cd5f Snap for 5600800 from 2d3cdf31bb8d8452380a3398e57e87f88318a274 to pi-platform-release am: 1e2fde1e24
 ▪ db4e774ca Snap for 5622519 from fef57bda2a3cf2dca83848db5b8e789cb32dac1d to pi-platform-release
 ▪ 1e2fde1e2 Snap for 5600800 from 2d3cdf31bb8d8452380a3398e57e87f88318a274 to pi-platform-release
 ▪ ab457be83 Merge tag 'android-9.0.0_r44' into pie
 ▪ 080c11834 Allow using alternative (higher) SBC HD bitrates with a property
 ▪ 450c9b9f1 Explicit SBC Dual Channel (SBC HD) support
 ▪ d11fba320 Increase maximum Bluetooth SBC codec bitrate for SBC HD
 ▪ 1a3cab19b Revert "Increase maximum Bluetooth SBC codec bitpool and bitrate values"
 ▪ eeef36e66 Revert "Explicit SBC Dual Channel (SBC HD) support"
 ▪ 64d931724 Revert "Allow using alternative (higher) SBC HD bitrates with a property"
 ▪ a3c00b274 Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ 6b7c12366 DO NOT MERGE Fix for Bluetooth connection being dropped after HCI Read Encryption Key Size
 ▪ bfeb15466 DO NOT MERGE Separate SDP procedure from bonding state (1/2)
 ▪ a950098d6 DO NOT MERGE Fix for Bluetooth connection being dropped after HCI Read Encryption Key Size
 ▪ 12df1a228 DO NOT MERGE Separate SDP procedure from bonding state (1/2)

 ▼ system/core/
 ▪ c893af2f4 DO NOT MERGE Start update_verifier early in late-fs.
 ▪ e33f6900b fs_mgr: Add MF_WRAPPEDKEY flag

 ▼ system/libhidl/
 ▪ 5628025 Delete vestigial Status parcel read.

 ▼ system/libhwbinder/
 ▪ 4959830 Snap for 5622519 from aa22afd88b4ff0fc467fa57d88ebc87de3021319 to pi-platform-release am: a5a8a516d4
 ▪ b0c7f46 Snap for 5600800 from 109b4ae7734e85c094c9446bb2f63932dcfa7207 to pi-platform-release am: 592f9f276b
 ▪ a5a8a51 Snap for 5622519 from aa22afd88b4ff0fc467fa57d88ebc87de3021319 to pi-platform-release
 ▪ 592f9f2 Snap for 5600800 from 109b4ae7734e85c094c9446bb2f63932dcfa7207 to pi-platform-release
 ▪ 3fcb895 Merge tag 'android-9.0.0_r44' into pie
 ▪ 571e174 Merge cherrypicks of [7995446, 7995447, 7996042, 7996138, 7995448, 7995449, 7995789, 7995790, 7995450, 7996029, 7996030, 7996139, 7996140, 7996141, 7996142, 7996143, 7996144, 7995544, 7995545, 7995546, 7995547, 7995548, 7995549, 7995550, 7996145, 7996146, 7996032, 7996147, 7996148, 7996149, 7996150, 7994747, 7994748, 7995451, 7994749, 7994750, 7995966, 7995967, 7994751, 7996151, 7996152, 7996153] into pi-qpr3-b-release
 ▪ 918b24d readCString: no ubsan sub-overflow
 ▪ 3b82196 readCString: no ubsan sub-overflow

 ▼ system/netd/
 ▪ 76448f5 Snap for 5622519 from 1ba507fb361520149b5683c363b85bf1d1e1fd00 to pi-platform-release am: 02ebe2a46c
 ▪ 6dcdfc8 Snap for 5600800 from 3c3c62e4d9ef34dbb9460fa9cde7945cd6486f5e to pi-platform-release am: f138d4c17e
 ▪ 02ebe2a Snap for 5622519 from 1ba507fb361520149b5683c363b85bf1d1e1fd00 to pi-platform-release
 ▪ f138d4c Snap for 5600800 from 3c3c62e4d9ef34dbb9460fa9cde7945cd6486f5e to pi-platform-release
 ▪ 1bceea1 Merge tag 'android-9.0.0_r44' into pie

 ▼ system/qcom/
 ▪ 54c6bea fix build warnings

 ▼ system/sepolicy/
 ▪ 3582d382a Merge c8292998afb69393672629dbed8e2b6795e8e92f on remote branch
 ▪ ba555aadf sepolicy: Add missing entry for font service
 ▪ 57821a89a sepolicy: Add Google App build props
 ▪ 102c06e4d system_server: allow writes to /proc/pid/*
 ▪ c474486d4 sepolicy: Add Label to f2fs sysfs files
 ▪ f5203d137 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/system/sepolicy into pie
 ▪ 5ac083a7a Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie
 ▪ e0904cb19 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie
 ▪ c8292998a Snap for 5653332 from a57e0922d978e884f3a2313ccc21b4b47ade8f58 to p-keystone-qcom-release
 ▪ a57e0922d Merge "A2dp sink SHO: Add bluetooth support to access mediametrics service" into p-keystone-qcom

 ▼ system/tools/hidl/
 ▪ 25a76d8 Snap for 5622519 from 71f3191f2c88f9cb4ad9e232d2bdb7b8208c40bf to pi-platform-release am: a5f1137806
 ▪ 607da63 Snap for 5600800 from 8b20a45f29ebb35324b0fba2fc5e0b856047aebb to pi-platform-release am: 1df6c91f83
 ▪ a5f1137 Snap for 5622519 from 71f3191f2c88f9cb4ad9e232d2bdb7b8208c40bf to pi-platform-release
 ▪ 1df6c91 Snap for 5600800 from 8b20a45f29ebb35324b0fba2fc5e0b856047aebb to pi-platform-release
 ▪ ae51c8c Merge tag 'android-9.0.0_r44' into pie

 ▼ system/vold/
 ▪ ca19a84 Merge "Snap for 5622519 from 59295fbb94e3a75c3341419aadbc66c560296179 to pi-platform-release am: ec0cb71ca1" into pie-gsi
 ▪ f2fb54f Snap for 5622519 from 59295fbb94e3a75c3341419aadbc66c560296179 to pi-platform-release am: ec0cb71ca1
 ▪ ec0cb71 Snap for 5622519 from 59295fbb94e3a75c3341419aadbc66c560296179 to pi-platform-release
 ▪ 0558ab5 Use wrapped key for metadata encryption
 ▪ 19b3a91 vold: change to upgrade key if export fails
 ▪ aa677ab vold: add support for clear key
 ▪ 3410a89 vold: Use separate flag for wrappedkey

 ▼ vendor/codeaurora/telephony/
 ▪ f192d11 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie
 ▪ c3b8339 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie
 ▪ 132f6f2 Merge 3b08f080ab3df40fa80a17d6d01ae3c61fc429ff on remote branch
 ▪ 61b747c Merge tag 'LA.UM.7.4.r1-05300-8x98.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into HEAD

 ▼ vendor/havoc/
 ▪ fa356e62 update Lawnchair to alpha-2268
 ▪ 79662562 Havoc 2.7
 ▪ 078398aa extract_utils: Add functions to extract vendor blobs from vendor.img
 ▪ 2d9f1644 build: Separate platform macros from QCOM platform definition
 ▪ d6966062 build: Reorganize inclusion of QCOM macros
 ▪ e7a520ad build: Use ifeq/else ifeq/else construction in board config
 ▪ 3d60c80a build: Set mode for makefiles
 ▪ eb15bf27 update Lawnchair to alpha-2238
 ▪ efc39b3a apn: Update German carriers
 ▪ 257a4033 repopick: cmp() is not available in Python 3, define it manually
 ▪ d4d3bda1 apns: Update Singapore's APNs
 ▪ 5dd7d4ad charger: add 400dpi symlink
 ▪ 5a6442e4 update Lawnchair to alpha-2152
 ▪ 1ffdc5f3 update Lawnchair to alpha-2112

 ▼ vendor/qcom/opensource/audio/
 ▪ 18ed1b6 Merge 97376a9080990e1bd2929eb865f691b8e9b7f37e on remote branch
 ▪ 5df76d7 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ f98be79 policy_hal: set channel mask from config at getOutputForAttr
 ▪ 1402596 Merge 97376a9080990e1bd2929eb865f691b8e9b7f37e on remote branch
 ▪ 3892e0e Merge 97376a9080990e1bd2929eb865f691b8e9b7f37e on remote branch
 ▪ 7278b4c Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ fc759a6 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into HEAD

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ a95d12a Merge 98278cbab83c8bc876c7c6f041576de599233fb3 on remote branch
 ▪ 7a95be0 ipacm: fix not support xlat on 2st tethered iface
 ▪ d1c44d0 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ dbae22e Merge 98278cbab83c8bc876c7c6f041576de599233fb3 on remote branch
 ▪ 24f74a0 Merge 98278cbab83c8bc876c7c6f041576de599233fb3 on remote branch
 ▪ 2438644 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ cbf62bc Merge tag 'LA.UM.7.6.2.r1-09100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ bbf5baa Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ 62e6d45 Merge 298c2caf64ef3efe78430542a5c2852738f50287 on remote branch
 ▪ 1f4b771 Merge 298c2caf64ef3efe78430542a5c2852738f50287 on remote branch
 ▪ 2b41bd3 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into HEAD

 ▼ vendor/qcom/opensource/interfaces/
 ▪ cfc0872 Merge b2d3ce3b31cdf6090b88ed7623262af69379b893 on remote branch
 ▪ 2e03a84 Merge tag 'LA.UM.7.6.2.r1-09200-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ e7f3165 Merge b8d91476053d0e8b17f6338839a452d58413b8ef on remote branch
 ▪ b2d3ce3 wifi: Enhance @1.1::IHostapdVendor HAL to support WPA3 SAP
 ▪ 6b6345e Merge b8d91476053d0e8b17f6338839a452d58413b8ef on remote branch
 ▪ cceeb64 display: Add APIs to capture concurrent writeback output
 ▪ 642f3e3 Merge tag 'LA.UM.7.5.2.r1-03200-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ 606ba09 Merge tag 'LA.UM.7.5.r1-05300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ 147d103 Merge 93071bf7476a2fe0bfb1f42074d19af7975425e2 on remote branch
 ▪ b8d9147 IComposer: Add composer 2.0 version
 ▪ 90db426 Merge "IQtiMapper: Add interface to get plane layout information"
 ▪ 0256dfa Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into HEAD

 ▼ vendor/support/
 ▪ 3db3055 Add missing methods in CustomSeekBarPreference

 ▼ vendor/themes/
 ▪ 3857134 themes: QSTiles: Add more styles

 ▼ vendor/xiaomi/
 ▪ acd83cdc gemini: Add 60fps Video Recording
 ▪ 2f93b815 add libsecureui.so
 ▪ 044f84a6 add camera blobs from 8.11.22
 ▪ bcf90aa2 capricorn: revert back to stock sensors

====================
     06-10-2019
====================
 ▼ art/
 ▪ fb1b0241a9 art: Enable -O3
 ▪ b4c95d7783 update tools/generate-boot-image-profile.sh

 ▼ bionic/
 ▪ e5adca11d Revert "bionic: strip libc and linker"
 ▪ d672a931c libc: Don't try to re-export libgcc symbols that don't exist in 6.3
 ▪ 8c1c4e5d4 libc: import ARM strlen from Apple C library
 ▪ 1fbee06f8 libm: Support -ffp-contract=fast
 ▪ 4e24b8a42 bionic: Enable -O3
 ▪ f7a3fdfd6 Merge branch 'pie' of https://github.com/Havoc-OS/android_bionic into pie
 ▪ 95c46abbe bionic: update for glibc 2.17
 ▪ 019573599 bionic: update for using jemalloc 5+
 ▪ 65d79d601 bionic: Remove ARM/MIPS fenv duplication
 ▪ bc0de26c6 arm64: Extend branch range in __memcpy_chk
 ▪ 07f5bdd9e bionic: strip libc and linker
 ▪ e333a7dff [AArch64] Optimize memcmp for medium to large sizes
 ▪ fe922b0bc libc: arm: Optimise memchr for NEON-enabled processors
 ▪ 7a0939020 libc: import ARM strcmp from newlib
 ▪ b6ff5c1cf Set __bionic_asm_align to 16 for arm64
 ▪ d5d6c7ec8 arm64: Use builtin for nearbyintf/nearbyint
 ▪ 1f8be99c6 Improve strncmp for mutually misaligned inputs
 ▪ d54b287b1 Improve strcmp performance for misaligned strings
 ▪ 1f290f133 Merge "Snap for 5450365 from dad73ef232034dd0f4f46bda90c74e8727d840cc to pi-platform-release am: 245e08f39e" into pie-gsi
 ▪ 4a082fe64 Snap for 5450365 from dad73ef232034dd0f4f46bda90c74e8727d840cc to pi-platform-release am: 245e08f39e

 ▼ build/make/
 ▪ 3120f634f Merge "Make change and version bump to PPRL.190605.003 am: dec688efc4" into pie-gsi
 ▪ 716cdc5c1 Make change and version bump to PPRL.190605.003 am: dec688efc4
 ▪ dec688efc Make change and version bump to PPRL.190605.003
 ▪ 3bba1846a Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/build into pie
 ▪ 41965d4b5 Version bump to PQ3B.190705.003 [core/build_id.mk]
 ▪ 6cbe894cc Version bump to PQ3B.190705.002 [core/build_id.mk]
 ▪ 39e12bb20 boot_jars: whitelist AliPay
 ▪ a3916b9fe Make change and version bump to PQ3B.190705.001
 ▪ 07050936a Update Security String to 2019-07-05 Bug:132634503 (cherry picked from commit 0718f458a1861cb70b1ab0aafa70d794c72c9f14)
 ▪ 90c61dbdc Make change and version bump to PQ3B.190701.001
 ▪ 753c431ce Update Security String to 2019-07-01 Bug:132634503 (cherry picked from commit 95bee0f53ed9f82c4e1ca27a5004eb1e917fa65c)
 ▪ 42ae11868 Merge "Make change and version bump to PPRL.190505.001 am: 24df732a99" into pie-gsi
 ▪ 281d143fb Make change and version bump to PPRL.190505.001 am: 24df732a99
 ▪ efcfd909b Version bump to PQ3B.190605.006 [core/build_id.mk]

 ▼ build/soong/
 ▪ cf71190f config: swap to glibc 2.17

 ▼ development/
 ▪ 5fb6172e4 Merge "Snap for 5450365 from 33a187438ef781129865711235b2ab4d6a7ec69d to pi-platform-release am: 3eec2e57b0" into pie-gsi
 ▪ 25d33ec7d Snap for 5450365 from 33a187438ef781129865711235b2ab4d6a7ec69d to pi-platform-release am: 3eec2e57b0

 ▼ device/havoc/sepolicy/
 ▪ c98f561 sepolicy: More fixes for OTA app
 ▪ 4231115 Allow OTA app to access recovery service
 ▪ 91f8a93 sepolicy: Smart Charging (3/4)
 ▪ 497f761 sepolicy: Run dos2unix
 ▪ 3c9076a sepolicy: Import LiveDisplay rules

 ▼ device/qcom/sepolicy/
 ▪ a6c4d97f Merge 3c63900d8f83f4d5df969c5903da82cafdbbe7f1 on remote branch
 ▪ dabce502 Merge 3c63900d8f83f4d5df969c5903da82cafdbbe7f1 on remote branch
 ▪ b2b60c55 sepolicy: allow bluetooth hal to access persist/bluetooth data
 ▪ 133f626e Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ 3c63900d Merge "sepolicy: add SE policy rules for hta runtime libraries"
 ▪ 669f006b Merge 9bda41bebdadccd204a088cb736b28bd92e404ab on remote branch
 ▪ 1d4d27ce Merge 9bda41bebdadccd204a088cb736b28bd92e404ab on remote branch
 ▪ 4b4edf83 sepolicy: permit graphics hwcomposer to read kgsl sysfs nodes
 ▪ 2d0278a3 sepolicy: add SE policy rules for hta runtime libraries

 ▼ device/xiaomi/gemini/
 ▪ 359a0368b update com.android.vending privapp-permissions
 ▪ 500e2db6f update README
 ▪ a2e1d5612 Android 9.0.0 release 42 (PQ3B.190605.006)
 ▪ 6449ba2fb Migrate to livedisplay 2.0
 ▪ 0049ca859 audio: fix audio_policy_configuration copy path
 ▪ 604db03f8 update .gitignore
 ▪ daf68f5ee update dump sepolicy
 ▪ 9b68641df add CROSS_COMPILE_ARM32
 ▪ 5a808516a update blobs from LA.UM.7.5.r1-04800-8x96.0
 ▪ 87aec9b07 update overlays
 ▪ 016dbf7d6 msm8996: Add AUDIO_CHANNEL_IN_STEREO to BT SCO Headset Mic
 ▪ 0ac3901a6 overlay: override sysfs nodes for smart charge
 ▪ a610e0e79 gps: Set SV in use mask based on final fixes
 ▪ 1fc8c355c gps: fix CFI issues
 ▪ 2de70d2a5 gps: Integer overflow leading to a buffer overflow
 ▪ 3d8d42e59 gps: util to get get symbol from a library
 ▪ 5a90276cd rename some modules
 ▪ 64c7b4dfe use QuickPic gallery mod
 ▪ d3e1adf44 caf tag: LA.UM.7.5.2.r1-02900-8x96.0
 ▪ 369ea695d BoardConfig: switch to gcc 9.1 for inline kernel building
 ▪ 354b46912 update sepolicy
 ▪ aeeebf5d8 gemini: build all modules with sdclang
 ▪ 0b4e62f0a Snapdragon LLVM Compiler for Android v8.0.6
 ▪ 3a6abb67c msm8996-common: sepolicy: Address qfp-daemon denials properly
 ▪ a962aec85 cparicorn: update overlays
 ▪ eee5e3ba8 capricorn: build kernel with clang 9.0.3
 ▪ 8390ca04d gemini: convert to Android.bp
 ▪ 9c7c6a0ef move some variables to device.mk
 ▪ a1a7c1599 mark /data/adb/modules as u:object_r:system_file:s0

 ▼ device/xiaomi/translations/
 ▪ e580d7b update 23.05
 ▪ 2839ba1 update 20190516

 ▼ external/chromium-webview/
 ▪ 995cadd Update Chromium Webview to 74.0.3729.157

 ▼ external/icu/
 ▪ 81023f419 Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ 903fd8649 DO NOT MERGE [CtsIcuTestCases] Old Android releases can optionally support the new Japanese era
 ▪ 61a2e8f9e DO NOT MERGE Cherry-pick: ICU-20536 Japanese era Reiwa support in ICU4J 60
 ▪ 951769012 DO NOT MERGE Cherry-pick: ICU-20536 Japanese era Reiwa support in ICU4C 60
 ▪ cf06cc777 Merge cherrypicks of [7508933, 7508817, 7509318, 7508934, 7509262, 7509263, 7509264, 7508935, 7508630, 7508631, 7508632, 7508633, 7508634, 7509319, 7508937, 7508841, 7509320, 7508842] into pi-qpr3-release
 ▪ 4223e4804 DO NOT MERGE [CtsIcuTestCases] Old Android releases can optionally support the new Japanese era
 ▪ cd92cfb36 DO NOT MERGE Cherry-pick: ICU-20536 Japanese era Reiwa support in ICU4J 60
 ▪ 4618c7d9b DO NOT MERGE Cherry-pick: ICU-20536 Japanese era Reiwa support in ICU4C 60
 ▪ edab3d161 Snap for 5450365 from 403985900949c50752009df72c38c1e59c295a3c to pi-platform-release am: 44dab7d4d2

 ▼ external/jemalloc/
 ▪ 5636650 Fix performance of multiple same size allocations
 ▪ 0eb3b7d [HAX] background_threads: explictly disable libdl usage
 ▪ 8bd657b jemalloc: update to version 5.2.0
 ▪ 8d70d0c jemalloc: Further updates to code
 ▪ 8e277a1 jemalloc: update to version 5.1.0

 ▼ external/libhevc/
 ▪ 628d67f Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ 58e26b2 Add few more checks for invalid parameters in sps
 ▪ af17238 Add bounds check for tile dimensions
 ▪ 366a348 Add missing return check for short_term_ref_pic_set()

 ▼ external/nano/
 ▪ bd331b01 tweaks: reshuffle some lines and frob some comments
 ▪ cd094822 tweaks: elide a function that is an amalgam of three others
 ▪ c5955d14 chars: speed up the determination of length and width for plain ASCII
 ▪ 7d383799 tweaks: rename two parameters, away from single letters
 ▪ 45bf18f8 tweaks: rename three variables, to get rid of a suffix or an underscore
 ▪ 787dca67 tweaks: elide an unneeded variable
 ▪ 15e36956 tweaks: avoid parsing a character twice
 ▪ 967f5818 tweaks: adjust some whitespace and rewrap a few lines
 ▪ ae26fda9 nano: Regenerate config.h
 ▪ 9f2c790e nano: fix another implicit declaration of time()
 ▪ 1075de12 tweaks: rename two functions, to get rid of the "mb" abbreviation
 ▪ 3457039c tweaks: rename a variable, to get out of the way of the next commit
 ▪ ca772549 tweaks: use a slightly faster function where appropriate
 ▪ 710a600f chars: speed up case-insensitive searching by roughly one percent
 ▪ 843eef65 tweaks: put some timing code back into the search function
 ▪ 781c7a7a chars: create a dedicated function for getting the length of a character
 ▪ aa205f58 tweaks: rename a bunch of variables, to become identical to others
 ▪ 3bf04afa tweaks: specifically refer to the manual of GNU grep for more regex info
 ▪ 71236e14 tweaks: rename two variables, away from a single letter
 ▪ 7be76af4 tweaks: speed up the counting of characters in mbstrlen()
 ▪ fb17929f tweaks: use FALSE for booleans instead of zero
 ▪ fea19015 docs: remove "--" from the default value of 'quotestr'
 ▪ 33fea90b justify: remove "--" from the quoting regex, to avoid false paragraphs
 ▪ f03c87c3 tweaks: squeeze excess spaces out of a line in situ
 ▪ 45b1a38b tweaks: factor out a fragment of code that is repeated three times
 ▪ c3bf17a8 tweaks: improve a handful of comments
 ▪ 8582e4a6 tweaks: don't bother keeping track of whether a squeezed line has shrunk
 ▪ 9b34d0a4 tweaks: rename two variables, to be unique
 ▪ 26d16ab9 tweaks: rename a variable, to better suit its counterpart
 ▪ 6ca85184 tweaks: make better use of two variables, and reshuffle two comments
 ▪ f2c61c4b docs: mention the default value for 'errorcolor'
 ▪ c4e04eb6 docs: show double quotes where they are needed
 ▪ 561b50da nano: don't spam warnings as errors
 ▪ ad2eedc1 nano: fix implicit declaration of time function
 ▪ 161086fe nano: Make revision.h a stub
 ▪ 5daed7f4 nano: Update makefile for new nanorc path
 ▪ 3ca7bc57 nano: Add nanorc
 ▪ 7b10e544 nano: Add android makefile
 ▪ 161f0291 nano: Add config.h and revision.h
 ▪ e810d7e3 nano: Don't ignore config.h & revision.h
 ▪ 0b257fe5 tweaks: sort three translator names better
 ▪ 94163761 docs: clarify that in nano regexes are extended regular expressions
 ▪ 378aa8bc docs: slightly reword the notice about the changed defaults since 4.0
 ▪ 157098ee gnulib: update to its current upstream state
 ▪ 8d4e171d tweaks: improve a couple of comments
 ▪ 6f1e5912 tweaks: stop allocating and freeing a holder struct for every cut/paste
 ▪ 28a6d9f3 tweaks: rename four elements of the holder struct, for more contrast
 ▪ f9260649 speller: when something goes wrong with 'sort', do not blame 'spell'
 ▪ 260588af speller: be more concise and to the point when something goes wrong
 ▪ cdc9482d tweaks: rename three variables, to use full words instead of abbrevs
 ▪ 7c1b649e tweaks: rename a function and its parameters, to be more fitting
 ▪ 57b3f83c rcfile: compile the color regexes just once
 ▪ edbdcb9b docs: add a light warning to the explanation of --nonewlines
 ▪ a6978b54 docs: say thanks to the Korean translator, and trim a double space
 ▪ 8bc2d18f tweaks: remove an unneeded pre-processor '#else' clause
 ▪ fb10a94f startup: prevent a crash when no applicable syntax is found
 ▪ 9b30bb15 tweaks: adjust the indentation after the previous change
 ▪ a1669e1b rcfile: disallow extending a syntax that is defined in a main nanorc
 ▪ 3d6eca3f tweaks: reshuffle some lines, to put the most likely candidate first
 ▪ c025a60c tweaks: rename a function and a variable, for contrast and variety
 ▪ 5e1f90d8 tweaks: don't bother to free the content of 'extendsyntax' commands
 ▪ 7f3ffe85 tweaks: remove a bit of redundant code
 ▪ ea1016ef feedback: make an error check work also when curses hasn't started yet
 ▪ f63fee79 tweaks: merge two functions, as the first is called just once
 ▪ 20034139 tweaks: move a function to the file where it is used
 ▪ 9369af77 tweaks: elide a function that is used just once
 ▪ 35d2bc6b build: fix compilation on another system
 ▪ b52d166a tweaks: rename a type, to make more sense
 ▪ 3952dcb6 tweaks: rename a variable, reduce its scope, and use it consistently
 ▪ 7e9dd385 tweaks: elide a parameter and a return value
 ▪ 2e810235 tweaks: rename two variables, and reshuffle their declarations
 ▪ b9f994b2 tweaks: elide a variable, drop a comment, and remove unneeded braces
 ▪ e9884720 tweaks: reshuffle some lines, to reduce duplication
 ▪ a77b2138 build: remove two #includes that don't seem to be needed
 ▪ 58ca5fb0 build: move an #include to where it is needed
 ▪ 844214b4 tweaks: rename two variables, to not be abbreviations
 ▪ f9dfca7d tweaks: rename a variable, to be shorter
 ▪ fe40e886 tweaks: rename a struct element, to be distinct
 ▪ 923a90cb tweaks: rename a type, for more contrast
 ▪ 5817e83e tweaks: be more sparing in redrawing things when exiting from help viewer
 ▪ 122cabd3 tweaks: elide another parameter, and rename the function to match
 ▪ c5d157dd tweaks: close a buffer differently and elide a parameter
 ▪ 3a65c0d1 feedback: when the last line is empty, don't include it in the count
 ▪ e1c011c9 tweaks: rename a variable, to match the style of its brothers
 ▪ 477ff49f feedback: don't try to represent keys outside of the seven-bit range
 ▪ 85eb9b9a tweaks: use a cheaper way to switch between buffers where possible
 ▪ 484523b3 tweaks: drop two checks that were made redundant by the previous commit
 ▪ 5a48edc9 tweaks: reshuffle some code to the one place that needs it
 ▪ 6dc8570d tweaks: reshuffle a few things, partly to make two chunks more alike
 ▪ 7e422402 tweaks: change a function to void, to make things more direct
 ▪ 5f03c20e tweaks: switch to the preceding buffer in a cheaper way (when in help)
 ▪ 71574e7a tweaks: reshuffle some closing and switching to a better place
 ▪ 821445d2 tweaks: drop some checks that were made redundant by the previous commit
 ▪ 3eab405e help: write the text directly into a new buffer, without using a tempfile
 ▪ 423ed031 help: don't cycle through the buffers for every resizing step
 ▪ 57390cff tweaks: exclude another bug check from the tiny version
 ▪ 4e637cd1 tweaks: delete a now-unused function
 ▪ add11596 tweaks: don't bother checking the return value of wait()
 ▪ dbdf38cc tweaks: consistently report failures to fork (and the like) as errors
 ▪ 47770bd3 feedback: treat statusline() being called outside of curses mode as a bug
 ▪ d656b0d3 feedback: show an appropriate message when reading a file was cut short
 ▪ d9deaf9f tweaks: reduce the scope of a variable, and let the compiler zero it
 ▪ b75563b8 tweaks: use a symbol instead of zero to refer to standard input
 ▪ 33e1bf14 startup: remove the now-unneeded workaround for a SIGWINCH during input
 ▪ d946f38a files: when needed, reconnect the keyboard and reenter curses mode
 ▪ b53dffae startup: resave the terminal's state only when there were no signals
 ▪ 6dcfcd11 tweaks: rename two functions, to better describe what they do
 ▪ f21b094d tweaks: condense a couple of comments, and reshuffle a line
 ▪ a521ac4a tweaks: exclude a bug check from the tiny version
 ▪ d972c170 build: exclude the ability to open a FIFO from the tiny version
 ▪ f6e182ca tweaks: check in a single place for files that should not be opened
 ▪ 6a83bb75 tweaks: delete a leftover
 ▪ 728498fd files: don't say "Error...: Success" when aborting after resizing
 ▪ 05f34bbf files: block SIGWINCH while opening a FIFO for reading or writing
 ▪ b7e2da74 files: don't save the state of the terminal a second time
 ▪ 8e2d03b9 build: fix compilation when configured with --enable-tiny
 ▪ 308a094d feedback: show a more fitting message when opening a FIFO is interrupted
 ▪ 5757aa8a tweaks: reuse the install and restore functions for a signal handler
 ▪ 8c5b6737 tweaks: factor out the installing and restoring of the ^C signal handler
 ▪ b2926eb6 tweaks: include the enabling of SIGINT into the tiny version
 ▪ ea117095 files: allow to abort the reading of slow files with Ctrl+C
 ▪ 8550c6bd files: allow to interrupt the opening of a FIFO for writing with Ctrl+C
 ▪ 65560a58 tweaks: rename a parameter and a variable, to be more distinct
 ▪ 35a791de tweaks: remove two unneeded checks for NULL
 ▪ 98ffb197 tweaks: stop checking for a NULL result from line_from_number()
 ▪ 93edd120 tweaks: rename a function, to be clearer and to stop using an old abbrev
 ▪ 9a475bf2 speller: don't crash when the spell-checked tempfile cannot be opened
 ▪ b512e253 tweaks: drop an unneeded parameter from open_file()
 ▪ 137c4467 speller: ensure that a Shift-selected region is retained
 ▪ 4cacb626 files: allow to interrupt the opening of a FIFO with Ctrl+C
 ▪ e3e81879 tweaks: condense the setup of the two signal handlers for Ctrl+C
 ▪ acd23551 help: don't check for confinement when opening a temporary help-text file
 ▪ 2f169107 usage: make the --help output independent from the terminal's tab size
 ▪ 12bf3bfc feedback: don't clear off possible error messages after a spell check
 ▪ d7555d07 tweaks: adjust a comment and drop two others, and reshuffle two lines
 ▪ 9596f7de tweaks: delete a now-unused function
 ▪ 20635b40 tweaks: merge two very similar functions into a single one
 ▪ 1128a40d tweaks: remove an unneeded setting and unsetting of a flag
 ▪ 1e2e6733 tweaks: add a pair of braces, to silence a compiler warning
 ▪ 2669d362 tweaks: set a boolean directly, instead of using a function call
 ▪ 22fc16b2 tweaks: add a missing forward declaration of make_new_buffer()
 ▪ 372e858e docs: note David as author of undoable indenting and undoable justifying
 ▪ da8c74a4 docs: note Brand as the author of the delayed syntax parsing
 ▪ cba9d8d0 rcfile: fully parse a syntax file only when needed
 ▪ 0e29c2a2 rcfile: store errors and display them when nano terminates
 ▪ 9e182722 feedback: print helpful message only when data comes from keyboard
 ▪ 4f1eb5fd tweaks: remove the two remaining handfuls of asserts
 ▪ 53352d0b files: try matching a syntax after scooping data from standard input
 ▪ 1d3a4df3 browser: don't show a mistaken message when exiting from help viewer
 ▪ afbaf8ae files: give feedback while waiting for a FIFO to open up
 ▪ 1b2018e9 files: check for writability by the access bits, not by trying to append
 ▪ 26642a39 files: allow a given file to be a special file but not a directory
 ▪ 87233754 tweaks: remove a superfluous and ineffective assignment
 ▪ 82aea04c bindings: at a Yes-No prompt, accept also ^Y for "Yes"
 ▪ 341601e1 bindings: at a Yes-No prompt, accept also ^N and ^Q for "No"
 ▪ 368f1a1c tweaks: elide a function that is called in just one place
 ▪ 527c6c1c tweaks: reshuffle a few lines, to be more straightforward
 ▪ a9e8f88e tweaks: enforce the miminum amount of scrolling in a simpler way
 ▪ 0cbf1f40 help: don't show Alt+Left and Alt+Right when running on a Linux console
 ▪ 96baa70c tweaks: reshuffle a couple of lines and adjust a few comments
 ▪ b18e2129 bindings: bind the Alt+arrow keystrokes also in non-UTF-8 locales
 ▪ e26cbdd6 help: make the column for the first keystroke a little wider
 ▪ 0ebfd54e softwrap: use smooth scrolling when softwrapping is toggled on
 ▪ 8f1cd50f syntax: python: avoid miscoloring stuff between two empty strings

 ▼ external/openssh/
 ▪ 3d8f688a openssh: Add boringssl compat functions for openssl-1.1.x API
 ▪ 045e1e94 openssh: Update Android build for v8.0p1
 ▪ fd3edff5 Merge tag 'V_8_0_P1' into lineage-16.0_v8.0p1

 ▼ external/sfntly/
 ▪ 63c0769 Fix uninitialized value in sfntly

 ▼ external/skia/
 ▪ c703381290 Merge "Snap for 5524043 from 104ff01147e723070b36f4c19ab444f221638ce6 to pi-platform-release am: a0db83ccc8" into pie-gsi
 ▪ ac53acf10f Snap for 5524043 from 104ff01147e723070b36f4c19ab444f221638ce6 to pi-platform-release am: a0db83ccc8
 ▪ 357d211bf5 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/external/skia into pie
 ▪ a0db83ccc8 Snap for 5524043 from 104ff01147e723070b36f4c19ab444f221638ce6 to pi-platform-release
 ▪ 939d9d9065 Merge tag 'android-9.0.0_r42' into pie
 ▪ 88f3168b6a Merge "Snap for 5450365 from 18676d83b37934a493980899f89acb5ce6f36527 to pi-platform-release am: 8dd03c05b0" into pie-gsi
 ▪ 51904d1d8c Snap for 5450365 from 18676d83b37934a493980899f89acb5ce6f36527 to pi-platform-release am: 8dd03c05b0

 ▼ external/sqlite/
 ▪ cc954ee sqlite: upgrade to SQLite 3.28.0

 ▼ external/vim/
 ▪ 00fa77daa vim: Add spacehi plugin
 ▪ 96dfaad56 vim: Update xml plugin
 ▪ 1a97a0904 vim/syntax: Add android logcat syntax
 ▪ c1e3494c6 vim: Add autogenerated configs
 ▪ 1f66998d1 vim: Don't ingore generated configs
 ▪ dad7e0af5 vim: Import Android makefiles
 ▪ ac2450a9a patch 8.1.1511: matches in a popup window are not displayed properly
 ▪ 80dad48c5 patch 8.1.1510: a plugin cannot easily expand a command like done internally
 ▪ 954bb0636 patch 8.1.1509: cmdline_row can become negative, causing a crash
 ▪ 541faf7a7 patch 8.1.1508: sound keeps failing on Travis
 ▪ a90998d93 patch 8.1.1507: sound test still fails on Travis
 ▪ b29cfb8c2 patch 8.1.1506: syntax error in Travis config
 ▪ 8ed75cb0b patch 8.1.1505: running "make clean" twice gives errors
 ▪ ef23c527b patch 8.1.1504: sound test still fails on Travis
 ▪ ffa60dda0 patch 8.1.1503: sound test fails on Travis
 ▪ 427f5b66c patch 8.1.1502: cannot play any sound
 ▪ 260addf79 patch 8.1.1501: new behavior of b:changedtick not tested
 ▪ 21f8d93c7 patch 8.1.1500: wrong shell command when building with VIMDLL and "!" in 'go'
 ▪ 24a5ac5d4 patch 8.1.1499: ruler not updated after popup window was removed
 ▪ c024b4667 patch 8.1.1498: ":write" increments b:changedtick even though nothing changed
 ▪ aef5c62a6 patch 8.1.1497: accessing memory beyond allocated space
 ▪ acc682bd7 patch 8.1.1496: popup window height is not recomputed
 ▪ 1748c7f77 patch 8.1.1495: memory access error
 ▪ 6c009a397 patch 8.1.1494: build failure
 ▪ 33796b39b patch 8.1.1493: redrawing with popups is slow and causes flicker
 ▪ 7c348bb5a patch 8.1.1492: MS-Windows: when "!" is in 'guioptions' ":!start" fails
 ▪ 606407384 patch 8.1.1491: when skipping over code a function call may cause trouble
 ▪ 4e0bf8462 patch 8.1.1490: when a single test fails the exit code is not set
 ▪ 64416127f patch 8.1.1489: sign order wrong when priority was changed
 ▪ 150f0550f patch 8.1.1488: summary of tests has incorrect failed count
 ▪ 62a88f498 patch 8.1.1487: older msgfmt cannot generate proper .desktop file
 ▪ 125370459 patch 8.1.1486: a listener change is merged even when it adds a line
 ▪ 773a97c25 Update runtime files - Add typescript syntax and indent.
 ▪ c07f67ad0 patch 8.1.1485: double free when garbage_collect() is used in autocommand
 ▪ 75ee544f9 patch 8.1.1484: some tests are slow
 ▪ 5d30ff196 patch 8.1.1483: skipped tests are not properly listed
 ▪ f6d50f1da patch 8.1.1482: no test for wincol() depending on the 'number' option
 ▪ 12e71eb8a patch 8.1.1481: length for two-digit rgb termresponse is off by one
 ▪ 8e228e21c patch 8.1.1480: desktop file check doesn't run on CI
 ▪ 133c73735 patch 8.1.1479: change included for debugging only
 ▪ 18250e291 patch 8.1.1478: still an error when running tests with the tiny version
 ▪ c7500f9cb patch 8.1.1477: test summary fails in the tiny version
 ▪ 9c0cec65f patch 8.1.1476: no statistics displayed after running tests
 ▪ db294adc6 patch 8.1.1475: search string not displayed when 'rightleft' is set
 ▪ 9aeb33639 patch 8.1.1474: 'ttybuiltin' is not tested
 ▪ 4a792c87b patch 8.1.1473: new resolve() implementation causes problem for plugins
 ▪ 61da1bfa6 Update runtime files.
 ▪ de6dbb452 patch 8.1.1472: add_termcap_entry() is not tested
 ▪ 32e197701 patch 8.1.1471: 'background' not correctly set for 2-digit rgb termresponse
 ▪ 6d718c4c3 patch 8.1.1470: new Unicode character U32FF missing from double-width table
 ▪ 66761db11 patch 8.1.1469: no test for checking the cursor style response
 ▪ d0380dc78 patch 8.1.1468: the generated desktop files may be invalid
 ▪ d6ec1730b patch 8.1.1467: cscope test fails
 ▪ 58a7f87c8 patch 8.1.1466: not updating priority on existing sign
 ▪ a37833dbd patch 8.1.1465: allocating wrong amount of memory
 ▪ cea254f5a patch 8.1.1464: only 4-digit rgb termresponse is recognized
 ▪ 277e79adc patch 8.1.1463: gcc warns for uninitialized variable
 ▪ c974022c3 patch 8.1.1462: MS-Windows: using special character requires quoting
 ▪ ddd330878 patch 8.1.1461: tests do not run or are not reliable on some systems
 ▪ 02e15072b patch 8.1.1460: popup window border characters may be wrong
 ▪ 3f6aeba18 patch 8.1.1459: popup window border looks bad when 'ambiwidth' is "double"
 ▪ 0b4c9eddb patch 8.1.1458: crash when using gtags
 ▪ 87abab92f patch 8.1.1457: cannot reuse a buffer when loading a screen dump
 ▪ 98fb65cb0 patch 8.1.1456: WinBar not redrawn after scrolling one line
 ▪ 1762731f2 patch 8.1.1455: popup_atcursor() not completely implemented
 ▪ 6116b6abb patch 8.1.1454: build failure without the conceal feature
 ▪ 3397f74ac patch 8.1.1453: popup window "moved" property not implemented yet
 ▪ b0ebbda06 patch 8.1.1452: line and col property of popup windows not properly checked
 ▪ ca2f7037c patch 8.1.1451: CTRL-L does not clear screen with a popup window
 ▪ 399d898ac patch 8.1.1450: popup window positioning wrong when using padding or borders
 ▪ 042fb4b44 patch 8.1.1449: popup text truncated at end of screen
 ▪ 988c43310 patch 8.1.1448: statusline is sometimes drawn on top of popup
 ▪ 7b29dd850 patch 8.1.1447: not allowed to create an empty popup
 ▪ 9eaac8965 patch 8.1.1446: popup window callback not implemented yet
 ▪ 790498b50 patch 8.1.1445: popup window border highlight not implemented yet
 ▪ 3bfd04e67 patch 8.1.1444: not using double line characters for popup border
 ▪ 2fd8e35e1 patch 8.1.1443: popup window padding and border not implemented yet
 ▪ 8caaf8256 patch 8.1.1442: popup windows not considered when the Vim window is resized
 ▪ bf0eff0b7 patch 8.1.1441: popup window filter not yet implemented
 ▪ 2d247849c patch 8.1.1440: win_execute() test fails
 ▪ c47ed44be patch 8.1.1439: json_encode() is very slow for large results
 ▪ 815b76bff patch 8.1.1438: some commands cause trouble in a popup window
 ▪ 3a97bb3f0 patch 8.1.1437: code to handle callbacks is duplicated
 ▪ 7dd64a3e5 Update runtime files.
 ▪ c28cb5b16 patch 8.1.1436: writefile test fails when run under /tmp
 ▪ 5d508dd39 patch 8.1.1435: memory usage test is a bit too flaky
 ▪ 1ab74a5af patch 8.1.1434: test 3 is old style
 ▪ eea169983 patch 8.1.1433: win_execute() may leave popup window focused
 ▪ ccd6e3471 patch 8.1.1432: can't build with eval feature
 ▪ c6896e20f patch 8.1.1431: popup window listed as "Scratch"
 ▪ 402502d0e patch 8.1.1430: popup window option "wrap" not supported
 ▪ ac1f1bc22 patch 8.1.1429: "pos" option of popup window not supported yet
 ▪ cc31ad9f9 patch 8.1.1428: popup_atcursor() not implemented yet
 ▪ 54fabd4b5 patch 8.1.1427: popup window screenshot test fails
 ▪ b42301247 patch 8.1.1426: no test for syntax highlight in popup window
 ▪ 89adc3a13 patch 8.1.1425: win_execute() does not set window pointers properly
 ▪ 5c3fb0462 patch 8.1.1424: crash when popup menu is deleted while waiting for char
 ▪ cacc6a5c9 patch 8.1.1423: popup windows use options from current window and buffer
 ▪ 8c2a600f7 patch 8.1.1422: popup_getoptions() not implemented yet
 ▪ 171469660 patch 8.1.1421: drawing "~" line in popup window
 ▪ 88c4e1f06 patch 8.1.1420: popup window size only uses first line length
 ▪ 68a4b04a8 patch 8.1.1419: listener callbacks may be called recursively
 ▪ 868b7b671 patch 8.1.1418: win_execute() is not implemented yet
 ▪ 1bbebab52 patch 8.1.1417: MS-Windows: resolve() does not resolve all components of path
 ▪ bc133543b patch 8.1.1416: popup_getposition() not implemented yet
 ▪ 59edb00e2 patch 8.1.1415: build error in MS-Windows GUI
 ▪ c799fe206 patch 8.1.1414: alloc() returning "char_u *" causes a lot of type casts
 ▪ b58a4b938 patch 8.1.1413: error when the drive of the swap file was disconnected
 ▪ 72fcf07b0 patch 8.1.1412: test 30 is old style
 ▪ 7833dab73 patch 8.1.1411: Coverity warns for divide by zero
 ▪ 60cdb3004 patch 8.1.1410: popup_move() is not implemented yet
 ▪ b43683729 patch 8.1.1409: Coverity warns for using uninitialized memory
 ▪ bf0ecb2cb patch 8.1.1408: PFL_HIDDEN conflicts with system header file
 ▪ 7a8d0278b patch 8.1.1407: popup_create() does not support text properties
 ▪ 2cd0dce89 patch 8.1.1406: popup_hide() and popup_show() not implemented yet
 ▪ 68e6560b8 Update runtime files.
 ▪ 20c023aee patch 8.1.1405: "highlight" option of popup windows not supported
 ▪ 9d591525a patch 8.1.1404: cannot change the patch level when building with NSIS
 ▪ 35d5af6c0 patch 8.1.1403: cannot build without the timer feature
 ▪ 51fe3b14f patch 8.1.1402: "timer" option of popup windows not supported
 ▪ 076073950 patch 8.1.1401: misspelled mkspellmem as makespellmem
 ▪ 9c27b1c6d patch 8.1.1400: using global pointer for tab-local popups is clumsy
 ▪ ec58384af patch 8.1.1399: popup windows not adjusted when switching tabs
 ▪ a8c99fb78 patch 8.1.1398: duplicate line in MSVC build file
 ▪ 80f95425c patch 8.1.1397: build fails in tiny version
 ▪ 193ffd1d9 patch 8.1.1396: 'wincolor' does not apply to lines below the buffer
 ▪ adfde115d patch 8.1.1395: saving for undo may access invalid memory
 ▪ a5e44600e patch 8.1.1394: not restoring t_F2 in registers test
 ▪ 51e14387f patch 8.1.1393: unnecessary type casts
 ▪ 682725c14 patch 8.1.1392: build failure in tiny version
 ▪ 4d784b21d patch 8.1.1391: no popup window support
 ▪ 8f46e4c4b patch 8.1.1390: search stats are off when using count or offset
 ▪ 7b31a181c patch 8.1.1389: changes are not flushed when end and start overlap
 ▪ f0884c5f3 patch 8.1.1388: errors when calling prop_remove() for an unloaded buffer
 ▪ d79eef2eb patch 8.1.1387: calling prop_add() in an empty buffer doesn't work
 ▪ 18a4ba29a patch 8.1.1386: unessesary type casts for lalloc()
 ▪ 71de720c2 patch 8.1.1385: signed/unsigned compiler warning
 ▪ 964b3746b patch 8.1.1384: using "int" for alloc() often results in compiler warnings
 ▪ d33a76412 patch 8.1.1383: warning for size_t/int mixup
 ▪ 3020a87cb patch 8.1.1382: error when editing test file
 ▪ d22a6f8aa patch 8.1.1381: MS-Windows: missing build dependency
 ▪ fa8f86195 patch 8.1.1380: MS-Windows building VIMDLL with MSVC: SUBSYSTEM is not set
 ▪ 8239c6206 patch 8.1.1379: filechanged test hangs
 ▪ 701ff0a3e patch 8.1.1378: delete() can not handle a file name that looks like a pattern
 ▪ fcc4d921d patch 8.1.1377: MS-Windows GUI uses wrong shell command for bash
 ▪ e2ad826f4 patch 8.1.1376: warnings for size_t/int mixups
 ▪ 984f031fb patch 8.1.1375: without "TS" in 'shortmess' get a hit-enter prompt often
 ▪ c97582b02 patch 8.1.1374: check for file changed triggers too often
 ▪ 0ab190c05 patch 8.1.1373: "[p" in Visual mode puts in wrong line
 ▪ 1c6fd1e10 patch 8.1.1372: when evaluating 'statusline' the current window is unknown
 ▪ 99499b1c0 patch 8.1.1371: cannot recover from a swap file
 ▪ 05b8b07e2 patch 8.1.1370: not using the new github feature for donations
 ▪ 294d9bf96 patch 8.1.1369: get E484 when using system() during GUI startup
 ▪ e09244ee3 patch 8.1.1368: modeline test fails with python but without pythonhome
 ▪ 7e800c604 patch 8.1.1367: can set 'modelineexpr' in modeline
 ▪ 110289e78 patch 8.1.1366: using expressions in a modeline is unsafe
 ▪ 535755214 patch 8.1.1365: source command doesn't check for the sandbox
 ▪ 5c017b2de patch 8.1.1364: design for popup window support needs more details
 ▪ e0b5949a3 patch 8.1.1363: ":vert options" does not make a vertical split
 ▪ c79745a82 patch 8.1.1362: code and data in tests can be hard to read
 ▪ 0b0ad35c3 patch 8.1.1361: Python setuptools don't work with Python 3
 ▪ 80341bcd8 patch 8.1.1360: buffer left 'nomodifiable' after :substitute
 ▪ f3333b02f patch 8.1.1359: text property wrong after :substitute with backslash
 ▪ 386b43e59 patch 8.1.1358: cannot enter character with a CSI byte
 ▪ 999dc1464 patch 8.1.1357: test 37 is old style
 ▪ 8471e5702 patch 8.1.1356: some text in heredoc assignment ends the text
 ▪ 16e9b8511 patch 8.1.1355: obvious mistakes are accepted as valid expressions
 ▪ f5842c5a5 patch 8.1.1354: getting a list of text lines is clumsy
 ▪ 2b39d806f patch 8.1.1353: undo test fails on Mac
 ▪ e9ebc9a91 patch 8.1.1352: undofile() reports wrong name
 ▪ 338dfdad3 patch 8.1.1351: text property wrong after :substitute
 ▪ dc6855af9 patch 8.1.1350: "W" for wrapping not shown when more than 99 matches
 ▪ cf0bfd9ad patch 8.1.1349: if writing runs into conversion error backup file is deleted
 ▪ f8191c5f0 patch 8.1.1348: running tests may cause the window to move
 ▪ bd2d68c2f patch 8.1.1347: fractional scroll position not restored after closing window
 ▪ 7f3a28490 patch 8.1.1346: error for Python exception does not show useful info
 ▪ 6349e9411 patch 8.1.1345: stuck in sandbox with ":s/../\=Function/gn"
 ▪ 0d3cb7301 patch 8.1.1344: Coverity complains about possibly using a NULL pointer
 ▪ 8055d1738 patch 8.1.1343: text properties not adjusted for Visual block mode delete
 ▪ 787880a86 patch 8.1.1342: using freed memory when joining line with text property
 ▪ 80e737cc6 patch 8.1.1341: text properties are lost when joining lines
 ▪ bfd451283 patch 8.1.1340: attributes from 'cursorline' overwrite textprop
 ▪ dabfde04f patch 8.1.1339: installer needs to product name et al.
 ▪ 0ebe12be8 patch 8.1.1338: hang when concealing the '>' shown for half of wide char
 ▪ 5c65e6a06 patch 8.1.1337: get empty text prop when splitting line just after text prop
 ▪ 17aca707f patch 8.1.1336: some eval functionality is not covered by tests
 ▪ dda4144d3 patch 8.1.1335: listener callback is called after inserting text
 ▪ eda652215 patch 8.1.1334: when buffer is hidden "F" in 'shortmess' is not used
 ▪ 45dd07f10 patch 8.1.1333: text properties don't always move after changes
 ▪ fe1ade0a7 patch 8.1.1332: cannot flush listeners without redrawing, mix of changes
 ▪ fb222df28 patch 8.1.1331: test 29 is old style
 ▪ 9e58787de patch 8.1.1330: using bold attribute in terminal changes the color
 ▪ 957f85d54 patch 8.1.1329: plans for popup window support are spread out
 ▪ bc4fd4316 patch 8.1.1328: no test for listener with undo operation
 ▪ a9b2535f4 patch 8.1.1327: unnecessary scroll after horizontal split
 ▪ 8aad88d8d patch 8.1.1326: no test for listener with partial
 ▪ 97b0075b0 patch 8.1.1325: cannot build with +eval but without +channel and +timers
 ▪ b73fbc76c patch 8.1.1324: stray comma in VMS makefile
 ▪ 5d0183b70 patch 8.1.1323: 'mouse' option is reset when using GPM mouse
 ▪ 6e75e0a40 patch 8.1.1322: Cygwin makefile is not nicely indented
 ▪ a33477296 patch 8.1.1321: no docs or tests for listener functions
 ▪ 6d2399bd1 patch 8.1.1320: it is not possible to track changes to a buffer
 ▪ 6ed881982 patch 8.1.1319: computing function length name in many places
 ▪ ec28d1516 patch 8.1.1318: code for text changes is in a "misc" file
 ▪ 3f86ca0fa Add missing files from patch 8.1.1318
 ▪ dc9f9e93f patch 8.1.1317: output from Travis can be improved
 ▪ d6896731e patch 8.1.1316: duplicated localtime() call
 ▪ afd78266c patch 8.1.1315: there is always a delay if a termrequest is never answered
 ▪ c049b52b9 patch 8.1.1314: MSVC makefile is not nicely indented
 ▪ 63d2555c9 patch 8.1.1313: warnings for using localtime() and ctime()

 ▼ external/zlib/
 ▪ 593a35c minizip: More build fixes
 ▪ 99fc328 minizip: Clean up the code
 ▪ 2c043d6 minizip: Fix build under Android 6.0 and higher
 ▪ 39df7f0 zlib: enable unaligned memory access

 ▼ frameworks/av/
 ▪ 265d8d9c6d Merge "Snap for 5524043 from f6b0c9c69c80374f534f11ada8a0bcfb4e86c755 to pi-platform-release am: acaea2ed4c" into pie-gsi
 ▪ 2ef2992da9 Snap for 5524043 from f6b0c9c69c80374f534f11ada8a0bcfb4e86c755 to pi-platform-release am: acaea2ed4c
 ▪ acaea2ed4c Snap for 5524043 from f6b0c9c69c80374f534f11ada8a0bcfb4e86c755 to pi-platform-release
 ▪ 3092601cd6 Merge tag 'android-9.0.0_r42' into pie
 ▪ f29ab2dbaa Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ 1927ee0489 Zero-initialize HIDL structs before passing
 ▪ 127949a9f3 Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ 7262280ba8 Zero-initialize HIDL structs before passing
 ▪ c0e2825f5c Merge "Snap for 5450365 from a24ab5c987af6e14a8e92970630f4ae19091eebd to pi-platform-release am: b855638c7d" into pie-gsi
 ▪ b16f1e0e85 Snap for 5450365 from a24ab5c987af6e14a8e92970630f4ae19091eebd to pi-platform-release am: b855638c7d
 ▪ 51a046ed70 Explicitly initialise base class in copy constructor
 ▪ d467694052 Zero-initialize HIDL structs before passing

 ▼ frameworks/base/
 ▪ 043ab77f0d8 Revert "hwui: Enable quicksilver"
 ▪ 8dc5c5e6d2d Q Style Clock: Animate change in time
 ▪ b554e35f8de Q Style Clock: Align owner info as per the clock style
 ▪ f3fa721e83a SystemUI: Fix analog clocks not refreshing in AOD
 ▪ cd913a82b85 Utils: Introduce method to determine countries that use Fahrenheit
 ▪ f28cca15b3e Utils: Add method to determine battery temp
 ▪ 8744d702c6d base: Add toggle to disable charging animation [1/2]
 ▪ 94d657a6369 LiveDisplayTile: Report unavailable on HWC2
 ▪ 091b7a318ed Merge "Snap for 5524043 from e31b34fa0cd1e70d1105e2f472d400f6619b2913 to pi-platform-release am: 799a8ca54f" into pie-gsi
 ▪ 0175732ba9d Snap for 5524043 from e31b34fa0cd1e70d1105e2f472d400f6619b2913 to pi-platform-release am: 799a8ca54f
 ▪ 799a8ca54fe Snap for 5524043 from e31b34fa0cd1e70d1105e2f472d400f6619b2913 to pi-platform-release
 ▪ 50eefdf0846 Merge tag 'android-9.0.0_r42' into pie
 ▪ 473fc03cfbb KeyguardSliceProvider: Show dnd icon regardless of suppression mode
 ▪ 4e7ac60ee9e Q Style Clock: Set "It's" to accent color instead of gold / yellow color
 ▪ 0fbb84c0899 Revert "NightDisplayController: report unavailable if livedisplay feature is present"
 ▪ 341fea02e78 BoostFramework: Trigger IOP at Displayed for duration.
 ▪ 4f7b9cf349c Boostframework: Adding reserved hint types for launch boost
 ▪ 90c200c88ec BoostFramework: Fix - Avoid Null Object Reference.
 ▪ 31e61fc71b1 BoostFramework : Modified Start Proc trigger and added Kill Hint.
 ▪ 806a56dd4a1 Revert "base: Add overlay for BoostFramework"
 ▪ 2df9bfdc877 base: Use wireless charging animation for wired charging too
 ▪ d08585770fd Add toggle for charging animation [1/2]
 ▪ aa88a4ed482 base: SystemUI: Fix qs-alpha conditions
 ▪ 8a055c7a22a base: Set QS BG alpha even with set qs from resources [1/2]
 ▪ 9b78bf565a6 Merge "Fix merge problems with cherry-picking "Add notification settings to backup&restore" change into pi-dev" into pie-gsi
 ▪ 0eefaf88121 Q Style Clock: Make it fully translatable
 ▪ 1ad102b2767 SystemUI: Cleanup keyguard_status_view layout
 ▪ 5ee5018da97 CustomTextClock: Code style cleanups
 ▪ f07c3b2cae1 KeyguardStatusView: Cleanup pointless duplication
 ▪ ac14cd09211 CustomTextClock: Cleanup
 ▪ a03d881b7b7 base: Double tap to trigger doze [1/2]
 ▪ 35982d76990 Add toggle for lockscreen weather and improve code
 ▪ d867b6c54b6 AmbientIndicationContainer: Fix crash when adding statusbar view
 ▪ 3a1da501286 HeadsUpAppearanceController: allow heads-up to draw beyond bounds
 ▪ 612deefc5da Update Spanish translations
 ▪ cb541e7b4b4 Update French translations
 ▪ d07e4539c88 Update Spanish translations
 ▪ 08f249233a0 Update Portuguese-BR translations
 ▪ e86e54b94db SystemUI: fix the behavior of QS with isDualTarget=true
 ▪ 59defa3c9ea Fix merge problems with cherry-picking "Add notification settings to backup&restore" change into pi-dev
 ▪ fc43176e9b3 Use headline font on battery percentage
 ▪ ba4ece07532 Fix NPE on navbar
 ▪ 850708cb6e8 LiveDisplay: Improve sunrise/sunset calculator
 ▪ 7f93dc9d015 Add in camera action to bindable actions (1/2)
 ▪ 16f8f894d25 HW: Fix Home button during call
 ▪ 5fb97a207db SmartActions: Turn on Tri-state ringer toggle [1/2]
 ▪ 1ed16049fd5 SmartActions: Add media controls to bindable actions [1/2]
 ▪ f6e7afa1266 Fixed auto-brightness first screen update
 ▪ 6afc419556e Smart Charging: allow using device overlays
 ▪ dca5ad08237 Smart Charging: rework for using more common sysfs node [1/2]
 ▪ 7eb07f18189 SettingsLib: Don't show system overlays on apps list
 ▪ 1321cd40478 LiveDisplay: Change night/day mode transition behavior
 ▪ 1b43e81ecb8 OpaLayout: Fix IllegalStateException
 ▪ aad0a79a303 PagedTileLayout: Fix IllegalStateException
 ▪ e2b390a39ca Fix NPE on ExpandableNotificationRow
 ▪ 6edb1eb3875 Use headline font in preference title
 ▪ 0c07c4a03b0 appops: put @hide back to opToDefaultMode
 ▪ d424bfbe1a3 ActivityThread: Remove Failed to find provider info logspam
 ▪ 57df0e2bc97 LS Artwork: Intensify blur more to make Clock styles more prominent
 ▪ 2b87e2de3eb CustomTextClock: Fix disappearing clock and SystemUI crash
 ▪ e61abc712a8 base: Optimize the size of statusbar icons
 ▪ 24c3865d787 Battery Estimates: Show only in QSB Header
 ▪ b741785c11f SystemUI: Allow Pixel 3 live wallpapers to work in Ambient Display
 ▪ 9c7aeb24d23 Lockscreen visualizer: Fix color transitions
 ▪ 26087765d62 Revert "Q Always-On Display: Show media info in keyguard slice"
 ▪ 5e26acb082c Revert "Q Always-On Display: Add double tap media slice to skip song"
 ▪ f4ce5749cad Battery Estimates: Disable by default [1/2]
 ▪ e9434d09fe5 Battery Estimates: Move battery icon to QS header when disabled
 ▪ 61116db2f68 Aggressive Battery: fix auto enable on battery saver
 ▪ 0bb14d1fcb2 base: SystemUI: make qs edit repect header image
 ▪ 7e61cca7ce0 Revert "Network traffic: Retain our notch check"
 ▪ f4312b75048 LiveDisplay tile: allow override outdoor capablity
 ▪ 52c48bc81b5 SystemUI: Fix clicking battery icon in QS header
 ▪ 6d4c6632d55 base: Add toggle to disable battery estimates in QS [1/2]
 ▪ b869620327d Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ e049f13eb41 Stop invoke initAppOps in Camera default constructor.
 ▪ b37e7650b09 [RESTRICT AUTOMERGE] Careful with screenshots containing secure layers!
 ▪ bbcbe0e05ec HwBlob: s/malloc/calloc/
 ▪ 5fc1b18b7fc [RESTRICT AUTOMERGE]: Exclude secure layers from most screenshots taken by the system server.
 ▪ 06ad5054235 LiveDisplay tile: allow FEATURE_MANAGED_OUTDOOR_MODE
 ▪ 82a23130e6a Improve checks for lockscreen visualizer
 ▪ 67f378a349b SystemUI: Improve Circle battery size
 ▪ 0d33701ab6a SettingsLib: Increase Signal icon size
 ▪ d5abed85697 SystemUI: Improve battery estimate layout in QS
 ▪ 36a7ead8b76 base: Add Q Green accent [1/3]
 ▪ 4a26bdf6daf base: Add Sweet Q Purple accent [1/3]
 ▪ 02f48c75f14 KeyguardUpdateMonitor: Fix SystemUI crash with auto face unlock
 ▪ 7071a7daa42 Fix conflict between pulse auto color and lockscreen wallpaper
 ▪ 38a3a9f402b Lockscreen Visualizer: Check for media playing before displaying artwork
 ▪ 9f4d2a9956e Lockscreen Visualizer: Automatic color based on wallpaper if no album art found
 ▪ efcccaed78c Update Turkish translations
 ▪ da7176dc1e4 base: Add seekbar to media notification
 ▪ fe96ed992c6 Q Always-On Display: Add double tap media slice to skip song
 ▪ 442c2fc80b5 Q Always-On Display: Show media info in keyguard slice
 ▪ 8b990d24dd1 SystemUI: Fix ambient music ticker double tap detection
 ▪ 1a4d9b28370 base: Use headline font in notification texts
 ▪ 9a7df1c6930 SystemUI: Use headline font in various parts
 ▪ cbefd388fc7 Fix weird artifact in battery icon
 ▪ f5f4b075cc3 Improve Q battery icon and unify with portrait style
 ▪ 1e68302218b SettingsLib: Expose Q battery icon paths
 ▪ 800bd85bc55 SystemUI: Implement enhanced battery estimates in QS
 ▪ b3f4ac23836 Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ da7203b6687 [RESTRICT AUTOMERGE] Careful with screenshots containing secure layers!
 ▪ 3256e59a874 HwBlob: s/malloc/calloc/
 ▪ 11d913944f5 [RESTRICT AUTOMERGE]: Exclude secure layers from most screenshots taken by the system server.
 ▪ 6e0a87dd56a Merge "Snap for 5450365 from 2a21bea448c56d892cf7c726771889ff2299f4d5 to pi-platform-release am: 7c2cd6a19a" into pie-gsi
 ▪ 210c37f14c0 Snap for 5450365 from 2a21bea448c56d892cf7c726771889ff2299f4d5 to pi-platform-release am: 7c2cd6a19a
 ▪ b4a4ab9ae43 SystemUI: Set proper color for battery text view
 ▪ 5016d7ee783 base: Add Q style to battery icon chooser [1/2]
 ▪ aa20c35a248 Battery icon: Don't force show percentage
 ▪ 060b13fad9a Settings: inherit battery meter style in view [1/2]
 ▪ 3559137908e BatteryMeterView: Fix logcat spam
 ▪ 0ff74b7fde3 Battery icon style: improve text/hidden switch
 ▪ f5b1e68a20b Battery icon: force show pct in QS header and when charging/powersave
 ▪ ce23aafedd5 Battery icon: show outside percentage on charging
 ▪ 8cf773bac3d Text battery style: show a bolt ⚡ when charging
 ▪ 2064e9228f3 SystemUI: clean up battery styles code
 ▪ b0ac58eb099 Add the powersave hint to the circle battery
 ▪ 02a35117efe BatteryMeterDrawable: add dotted circle style (1/2)
 ▪ 36e430a0169 BatteryMeterDrawable: add hidden option (1/2)
 ▪ 040ad9d475f BatteryMeterDrawable: add text style (1/2)
 ▪ 39e1af5b064 BatteryMeterDrawable: add battery styles
 ▪ c1cf0cf6a34 Implement battery percent styles (1/2)
 ▪ 21d4775ad23 base: Cleanup battery styles implementation
 ▪ e9517c50111 CustomTextClock: Improvements and translations
 ▪ 07523095420 base: SystemUI: fix themeing of notification shelf dot
 ▪ fb5f843c261 Remove useless warning when dismissing notification
 ▪ 51c03601467 pocket: Use MD2 lock drawable
 ▪ 8506599337a KeyguardSliceView: Align as per the Clock Style
 ▪ 715da0ca193 base: Make FP detection in pocket mode configurable [1/2]
 ▪ a99fb871186 Don't force show battery percentage while charging or powersave
 ▪ ff1bbb393b8 Android Q text clock Portuguese translation
 ▪ a958d29cf6c Update Turkish translations
 ▪ 7184d38586d Android Q text clock Greek translation
 ▪ 0877ed0c116 [RESTRICT AUTOMERGE] Careful with screenshots containing secure layers!
 ▪ 37c32377b21 [RESTRICT AUTOMERGE]: Exclude secure layers from most screenshots taken by the system server.
 ▪ a4ee0020e25 HwBlob: s/malloc/calloc/
 ▪ c92c383d8d3 SystemUI: Fix NavBar tuner crash when using Oreo QS style

 ▼ frameworks/native/
 ▪ dcd8de526 Graphics: Avoid vulkan libs access if vulkan is disabled
 ▪ 86f317d99 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/frameworks/native into pie
 ▪ f9e30d29e Snap for 5623383 from 8a83d2544730b704c69fca7414b5a125bd565b0c to p-keystone-qcom-release
 ▪ d60cec87a opengl: Allow implcit IT blocks on arm
 ▪ 8a83d2544 Merge SPL-2019-05-05
 ▪ 9639dc162 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into pie
 ▪ ccc2519e1 Merge c8288466da5169f6bfc50cc72cd9df5cb32a069f on remote branch
 ▪ 2062c5a40 Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ f3d8d3f68 [RESTRICT AUTOMERGE] SurfaceFlinger: Indicate whether we have captured secure layers.
 ▪ 1cc813bb3 [RESTRICT AUTOMERGE]: Exclude secure layers from most screenshots taken by the system server.
 ▪ 4c66d2660 Zero-initialize HIDL structs before passing
 ▪ 42a149d85 Merge cherrypicks of [7508933, 7508817, 7509318, 7508934, 7509262, 7509263, 7509264, 7508935, 7508630, 7508631, 7508632, 7508633, 7508634, 7509319, 7508937, 7508841, 7509320, 7508842] into pi-qpr3-release
 ▪ 84e46603c [RESTRICT AUTOMERGE] libvulkan: drop the advertised swapchain spec version to 68
 ▪ 94fdc48f7 Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ 0283c73cc [RESTRICT AUTOMERGE] SurfaceFlinger: Indicate whether we have captured secure layers.
 ▪ 9085ced4a [RESTRICT AUTOMERGE]: Exclude secure layers from most screenshots taken by the system server.
 ▪ 6a2127f16 Zero-initialize HIDL structs before passing
 ▪ 9b3bc2e47 [RESTRICT AUTOMERGE] SurfaceFlinger: Indicate whether we have captured secure layers.
 ▪ b0b22e049 Zero-initialize HIDL structs before passing
 ▪ 52927ed39 [RESTRICT AUTOMERGE]: Exclude secure layers from most screenshots taken by the system server.

 ▼ frameworks/opt/net/ims/
 ▪ 1f10d68 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/ims into pie

 ▼ frameworks/opt/net/wifi/
 ▪ c42164527 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/frameworks/opt/net/wifi into HEAD
 ▪ fef54a4a6 Merge ab619c380d3656176dcf99fcb00544f02e161d61 on remote branch
 ▪ 0eaec84e9 Snap for 5564766 from e944d35fac46b9819c0bc5d18633321f5c3ae0c3 to p-keystone-qcom-release
 ▪ e944d35fa Merge "wifi: Indicate AUTH_FAILURE for WEP password error" into p-keystone-qcom

 ▼ frameworks/opt/telephony/
 ▪ e653d650c8 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/frameworks/opt/telephony into caf
 ▪ d53452dd9e Merge 72c54cc474fa8329110d1cf6924f0909944c3f94 on remote branch
 ▪ b2cba5ec1e Snap for 5630776 from 7f89e9710c2cfda1117614bbbfeb8ebfeeb54546 to p-keystone-qcom-release
 ▪ 7f89e9710c Merge "IMS: Use Sia as service class for call waiting MMI operations" into p-keystone-qcom
 ▪ 3d8a4ff023 Snap for 5623383 from f8074a89449e2cbff04f7e33233b642cc709f519 to p-keystone-qcom-release
 ▪ f8074a8944 Merge SPL-2019-05-05
 ▪ a4014a5fd4 IMS: Use Sia as service class for call waiting MMI operations
 ▪ cb5863140b Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into caf
 ▪ a63c59b385 Merge 72c54cc474fa8329110d1cf6924f0909944c3f94 on remote branch
 ▪ d3521553f9 Merge 72c54cc474fa8329110d1cf6924f0909944c3f94 on remote branch

 ▼ hardware/broadcom/wlan/
 ▪ 55ffcf6 Merge "Snap for 5450365 from f632b64f225162de0c7e8dee5953d44bbfcf353f to pi-platform-release am: df369a168d" into pie-gsi
 ▪ 500ed30 Snap for 5450365 from f632b64f225162de0c7e8dee5953d44bbfcf353f to pi-platform-release am: df369a168d

 ▼ hardware/google/av/
 ▪ a0026f4 Zero hidl-generated structs (bufferpool)

 ▼ hardware/havoc/interfaces/
 ▪ a8b523d havoc/interfaces: Remove lineage trust hal
 ▪ 3dde4e9 havoc/interfaces: Remove lineage power hal
 ▪ f99f0f8 Init Havoc...

 ▼ hardware/interfaces/
 ▪ 6a0cd5dcc Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/hardware/interfaces into 9.0
 ▪ 2f57e8e3a Snap for 5623383 from e6621534b0c164e840c1b3f234737d8c5ee07b72 to p-keystone-qcom-release
 ▪ e6621534b Merge SPL-2019-05-05
 ▪ aa0f3be4c Snap for 5608051 from 73670a84dda5dd0be5b8cc5a3c990753b00aadd3 to p-keystone-qcom-release

 ▼ hardware/lineage/livedisplay/
 ▪ fd1713f sdm: Fix restoring default mode when using prebuilt vendor

 ▼ hardware/nxp/nfc/
 ▪ 4b2fbc9 Snap for 5450365 from 210180d4eb8971f74aa17d1677e97a342c29c7b1 to pi-platform-release am: 64337a610c

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 375199f8 Merge 7dbed74f8f2aa06fa105dbe81ab40a4bc6569dc1 on remote branch
 ▪ cecf9fc2 hal: get correspoding sample rate per device when sending cal data
 ▪ 170fdadd Merge 7dbed74f8f2aa06fa105dbe81ab40a4bc6569dc1 on remote branch
 ▪ 699200d0 hal: remove HAL access to channel number mixer control
 ▪ a32012a6 hal: force device switch when BT SCO is off
 ▪ e1e9ebee Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' into 9.0
 ▪ 94c4c78b Merge 8a314f777c2d599988e457512a8bffe530db3a52 on remote branch
 ▪ 7dbed74f configs: Add BT SCO to routes list

 ▼ hardware/qcom/bt-caf/
 ▪ b7bdccd A2DP: Send min of peer & MTU based AAC bit-rate to Audio

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ 4fe24671 Merge 049b98c6c3a64edc7c6a99712258c4f65b2d44b1 on remote branch
 ▪ e81ef49e Merge 049b98c6c3a64edc7c6a99712258c4f65b2d44b1 on remote branch
 ▪ e2add2e5 sdm: Fix closest resolution algorithm.   - if mixer resolution is not equal to     any support TV resolution, get closest     suported TV resolution with mixer resolution.
 ▪ b9be49c5 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' into 9.0
 ▪ a518ff5b Merge 049b98c6c3a64edc7c6a99712258c4f65b2d44b1 on remote branch
 ▪ 0ddc690f Merge 6c40a33a3988f204842d749dac83f18ca0be8f5a on remote branch

 ▼ hardware/qcom/fm/
 ▪ 221e94e Partially revert "fm: Fix wrong BT SOC property name"

 ▼ hardware/qcom/keymaster/
 ▪ c7a9365 keymaster: Build with BOARD_VNDK_VERSION

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 8fcbf8da venc: Disable RGBA direct input to Venus
 ▪ 5029253b mm-video-v4l2: vidc: vdec: Indicate full range video

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 8fcbf8daa venc: Disable RGBA direct input to Venus
 ▪ 6fdd73b85 Merge 5029253b815df1b49da827dbd5514a6f3c87e3c1 on remote branch
 ▪ 82d28addf Merge 5029253b815df1b49da827dbd5514a6f3c87e3c1 on remote branch
 ▪ 3bc347289 Merge 5029253b815df1b49da827dbd5514a6f3c87e3c1 on remote branch
 ▪ 24b4d7e91 Merge 9e0d0b25225e7a717df78462702a518fdd46f7da on remote branch
 ▪ 5029253b8 mm-video-v4l2: vidc: vdec: Indicate full range video

 ▼ hardware/qcom/wlan-caf/
 ▪ 2ba4690 Merge c0d0e6228d5b9c44b792885bfb520cd06c35c5e1 on remote branch
 ▪ c340659 Merge c0d0e6228d5b9c44b792885bfb520cd06c35c5e1 on remote branch
 ▪ a165b1b Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' into 9.0
 ▪ 7cd132e Merge c0d0e6228d5b9c44b792885bfb520cd06c35c5e1 on remote branch

 ▼ hardware/ril/
 ▪ b61c704d Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/ril into 9.0-caf
 ▪ 31d6c2f9 libril: Disable sanitize with latest clang

 ▼ kernel/xiaomi/msm8996/
 ▪ ef5df17d55a6 qcacld-2.0: Avoid buffer leakage when handle 11w rmf
 ▪ aaa1c2868be0 qcom: smcinvoke: Fix stack overflow for arr_filp
 ▪ 445ef3e07243 diag: Prevent out of bound access while getting build mask
 ▪ 0061e6d1850d Merge 2eacf3edfbe32db5632e59f3da0c3a88f4d3f429 on remote branch
 ▪ 38ad6b231a16 Merge c34e289099888208e829f68102ea26eade1c8efc on remote branch
 ▪ b5cb975999a0 qcacld-2.0: Add ini key disable smart antenna
 ▪ 04cd86af2ff9 qcacld-2.0: Trigger recovery in rx-hash no-match
 ▪ 78aa41ba569c Merge "qcacld-2.0: Remove debug log in wcnss_prealloc_get" into wlan-cld2.driver.lnx.1.0
 ▪ c34e28909988 diag: Check buffer size against command structure size
 ▪ 4b7c163d73ef diag: Check command size against the minimum before parsing
 ▪ 59d6a33f9d90 Merge "qcacld-2.0: Enable DFS CAC in 5/10M mode" into wlan-cld2.driver.lnx.1.0
 ▪ 4af56d62e01f qcacld-2.0: Remove debug log in wcnss_prealloc_get
 ▪ 0c20a626d695 qcacld-2.0: Add BSS hidden check in CSA
 ▪ f227ea7c0970 lsm: check payload size validity in lsm_event_detect_status_v3
 ▪ 3edc6bbc7330 Merge "qcacld-2.0: Add bound check for fixed_param->total_num_tx_power_levels" into wlan-cld2.driver.lnx.1.0
 ▪ 69fc967ab865 Merge "qcacld-2.0: Donot process get tx power command in disconnected state" into wlan-cld2.driver.lnx.1.0
 ▪ 9ce967b94867 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 26cba7c62b9b qcacld-2.0: Donot process get tx power command in disconnected state
 ▪ 391566971c71 qcacld-2.0: Add bound check for fixed_param->total_num_tx_power_levels
 ▪ 834b8d07f2db prepare for gcc 9.1
 ▪ 83d1859d1645 qcacld: use O2 optimization
 ▪ 43a937700fe2 Merge tag 'LA.UM.7.5.r1-04800-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 3f592caf3c14 msm: kgsl: Fix race condition while making page as dirty
 ▪ 24115ff94e16 qcacld-2.0: Enable DFS CAC in 5/10M mode
 ▪ 69e30f5eeff6 ignore changelog.*
 ▪ 1b8436269a37 sound: soc: codecs: import tfa98xx driver v6.5.5
 ▪ 2668ade0ff6b Merge branch 'kernel.lnx.3.18.r34-rel' of https://github.com/android-linux-stable/msm-3.18 into 9.0
 ▪ 2eacf3edfbe3 qcacld-2.0: Correct typo in csrRoamJoinedStateMsgProcessor
 ▪ 13a4291b9c75 Merge a85d60d5771be664e077575ee1aaa645c35f664a on remote branch
 ▪ 003947b93c46 Merge 3.18.140 into kernel.lnx.3.18.r34-rel
 ▪ 6b1ae527b1fd Linux 3.18.140
 ▪ 36927e41c311 powerpc/booke64: set RI in default MSR
 ▪ db7e50136a20 drivers/virt/fsl_hypervisor.c: prevent integer overflow in ioctl
 ▪ 3b187319bc7c drivers/virt/fsl_hypervisor.c: dereferencing error pointers in ioctl
 ▪ 66ed3c8b10c1 bonding: fix arp_validate toggling in active-backup mode
 ▪ ae0f0ebd83c2 ipv4: Fix raw socket lookup for local traffic
 ▪ 860e91819fed vlan: disable SIOCSHWTSTAMP in container
 ▪ 97d36ca9da84 packet: Fix error path in packet_init
 ▪ 9d59fa6eeb6b net: ucc_geth - fix Oops when changing number of buffers in the ring
 ▪ 28107baf408d bridge: Fix error path for kobject_init_and_add()
 ▪ c0759c18e95d USB: serial: fix unthrottle races
 ▪ 6b612ec29abd USB: serial: use variable for status
 ▪ 466153fc585e Don't jump to compute_result state from check_result state
 ▪ 913fbfc3fd78 gpu: ipu-v3: dp: fix CSC handling
 ▪ fad368428284 selftests/net: correct the return value for run_netsocktests
 ▪ 68e8a8d9bcca s390: ctcm: fix ctcm_new_device error return code
 ▪ 4ce4b005e584 init: initialize jump labels before command line option parsing
 ▪ f97fc640c425 tools lib traceevent: Fix missing equality check for strcmp
 ▪ 72ba8a7a7c8e KVM: x86: avoid misreporting level-triggered irqs as edge-triggered in tracing
 ▪ eca5f4de2f5f s390/3270: fix lockdep false positive on view->lock
 ▪ 2f922c459f48 s390/dasd: Fix capacity calculation for large volumes
 ▪ e172a3b59098 HID: input: add mapping for keyboard Brightness Up/Down/Toggle keys
 ▪ b8f6da2fcb2e iio: adc: xilinx: fix potential use-after-free on remove
 ▪ 23a030f79c35 platform/x86: sony-laptop: Fix unintentional fall-through
 ▪ d2774665f7c7 netfilter: compat: initialize all fields in xt_init
 ▪ b784e7a613d1 timer/debug: Change /proc/timer_stats from 0644 to 0600
 ▪ b16a6c99f88c Bluetooth: Align minimum encryption key size for LE and BR/EDR connections
 ▪ 9c47ad93de73 Bluetooth: hidp: fix buffer overflow
 ▪ 6ee71083b16f scsi: qla2xxx: Fix incorrect region-size setting in optrom SYSFS routines
 ▪ 43dae3a4e492 genirq: Prevent use-after-free and work list corruption
 ▪ 17f93dcb6222 iommu/amd: Set exclusion range correctly
 ▪ 47ebd4007edc scsi: csiostor: fix missing data copy in csio_scsi_err_handler()
 ▪ 0562cef837e2 ASoC: tlv320aic32x4: Fix Common Pins
 ▪ e0124792043a ASoC: cs4270: Set auto-increment bit for register writes
 ▪ 0a635ced7127 ASoC:soc-pcm:fix a codec fixup issue in TDM case
 ▪ ec22b57b0527 scsi: libsas: fix a race condition when smp task timeout
 ▪ f52118781632 media: v4l2: i2c: ov7670: Fix PLL bypass register values
 ▪ 56c85b204c3b staging: iio: adt7316: fix the dac write calculation
 ▪ 05aafb6243c8 staging: iio: adt7316: fix the dac read calculation
 ▪ 4e12fe2e5520 staging: iio: adt7316: allow adt751x to use internal vref for all dacs
 ▪ 19a81333239e usb: usbip: fix isoc packet num validation in get_pipe
 ▪ 9f3a2aa76996 ARM: iop: don't use using 64-bit DMA masks
 ▪ 91b4d929ccb0 ARM: orion: don't use using 64-bit DMA masks
 ▪ 77541ef954e3 xsysace: Fix error handling in ace_setup
 ▪ b3a65e122a39 hugetlbfs: fix memory leak for resv_map
 ▪ 202dff90b727 scsi: storvsc: Fix calculation of sub-channel count
 ▪ 44a476cf0bc2 jffs2: fix use-after-free on symlink traversal
 ▪ c452e33d4940 bonding: show full hw address in sysfs for slave entries
 ▪ b2eed39466f8 igb: Fix WARN_ONCE on runtime suspend
 ▪ 00a9ea1b3a7d rtc: sh: Fix invalid alarm warning for non-enabled alarm
 ▪ 358e9483e84a HID: debug: fix race condition with between rdesc_show() and device removal
 ▪ bc1c5d1ac477 USB: core: Fix bug caused by duplicate interface PM usage counter
 ▪ fe1e6f511cb1 USB: media: disable tlg2300 driver
 ▪ 652c6e122fda USB: core: Fix unterminated string returned by usb_string()
 ▪ 483dc306cb1d USB: w1 ds2490: Fix bug caused by improper use of altsetting array
 ▪ 15c0d2672a47 USB: yurex: Fix protection fault after device removal
 ▪ f4d6bb3a95be ipv6/flowlabel: wait rcu grace period before put_pid()
 ▪ 6ca4b4080c10 packet: validate msg_namelen in send directly
 ▪ 91c38d754460 ipv6: invert flowlabel sharing check in process and user mode
 ▪ 1e584073efa2 ipv4: ip_do_fragment: Preserve skb_iif during fragmentation
 ▪ e2e7cf41baba kconfig/[mn]conf: handle backspace (^H) key
 ▪ c2e5f31ccbf2 libata: fix using DMA buffers on stack
 ▪ ef269561a9de scsi: zfcp: reduce flood of fcrscn1 trace records on multi-element RSCN
 ▪ d98c0b86e7a1 ceph: fix use-after-free on symlink traversal
 ▪ a826eff401e6 usb: u132-hcd: fix resource leak
 ▪ 61d586191960 scsi: qla4xxx: fix a potential NULL pointer dereference
 ▪ 0f1cf480956c net: ibm: fix possible object reference leak
 ▪ 90a9d6d23c0e net: ks8851: Set initial carrier state to down
 ▪ cd30c290a14d net: ks8851: Delay requesting IRQ until opened
 ▪ 76fc3b4b21c0 net: ks8851: Reassert reset pin if chip ID check fails
 ▪ 47d93a167555 net: ks8851: Dequeue RX packets explicitly
 ▪ 906dbadf304e usb: gadget: net2272: Fix net2272_dequeue()
 ▪ 1da2fd016314 usb: gadget: net2280: Fix overrun of OUT messages
 ▪ 65e6cca34beb qlcnic: Avoid potential NULL pointer dereference
 ▪ a0118894ef08 net: stmmac: move stmmac_check_ether_addr() to driver probe
 ▪ 5466bd95f6e3 team: fix possible recursive locking when add slaves
 ▪ f37fb00c1c4f ipv4: add sanity checks in ipv4_link_failure()
 ▪ 7f29d9b03ac7 Revert "block/loop: Use global lock for ioctl() operation."
 ▪ 9331b51b7b05 netfilter: ebtables: CONFIG_COMPAT: drop a bogus WARN_ON
 ▪ dcbb0ca6856c NFS: Forbid setting AF_INET6 to "struct sockaddr_in"->sin_family.
 ▪ 7ab3ca7f1461 fs/proc/proc_sysctl.c: Fix a NULL pointer dereference
 ▪ 0cc8c5a22996 slip: make slhc_free() silently accept an error pointer
 ▪ b0b38ec24346 sunrpc: don't mark uninitialised items as VALID.
 ▪ 596c78267376 ceph: ensure d_name stability in ceph_dentry_hash()
 ▪ 7c82b63c7258 sched/numa: Fix a possible divide-by-zero
 ▪ 316bc8144b44 trace: Fix preempt_enable_no_resched() abuse
 ▪ d1a3145b6b48 MIPS: scall64-o32: Fix indirect syscall number load
 ▪ f3245458a981 msm: vidc: Ensure validity of shared Q indices
 ▪ a85d60d5771b qcacld-2.0: Fix possible OOB read in stats event handler
 ▪ dfbe58c2ca72 Merge "msm: camera : Lock Implementation for avoid race condition"
 ▪ 06f237ce1f16 msm: camera : Lock Implementation for avoid race condition
 ▪ fef6345ace23 qcacld-2.0: Remove limitation about length of probe response ie
 ▪ 1b0c6d385e38 msm: ais : Lock Implementation for avoid race condition

 ▼ packages/apps/Bluetooth/
 ▪ 75d8899a Merge tag 'android-9.0.0_r42' into pie
 ▪ 797a4c1d Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/packages/apps/Bluetooth into HEAD
 ▪ 6c1ab6b2 Bluetooth:add missing permission
 ▪ b41383de Merge cherrypicks of [7478367, 7478616] into pi-qpr3-b-release
 ▪ 89052445 Revert "DO NOT MERGE Separate SDP procedure from bonding state (2/2)"

 ▼ packages/apps/Camera2/
 ▪ 55b60e01a Merge "Snap for 5450365 from fff27838050900ba7f4a9ed3c6e4adff9c9cb6cc to pi-platform-release am: 5e09aec115" into pie-gsi
 ▪ aebc437d2 Snap for 5450365 from fff27838050900ba7f4a9ed3c6e4adff9c9cb6cc to pi-platform-release am: 5e09aec115

 ▼ packages/apps/CarrierConfig/
 ▪ a102472 Snap for 5450365 from fb861f45b48b80a222f2a2186cd56858b1ac1ab1 to pi-platform-release am: 2fec918b61
 ▪ 4c189b9 CarrierConfig: Enable VOLTE, WFC, VT on Singapore carriers

 ▼ packages/apps/CellBroadcastReceiver/
 ▪ e100c47 Merge tag 'android-9.0.0_r42' into pie
 ▪ d908b5e Merge "Snap for 5450365 from 554370746d809d956fb267cf5b93d22115308400 to pi-platform-release am: 84bd5b11cd" into pie-gsi
 ▪ 8cf7857 Snap for 5450365 from 554370746d809d956fb267cf5b93d22115308400 to pi-platform-release am: 84bd5b11cd

 ▼ packages/apps/Contacts/
 ▪ 3088d1b0e Merge tag 'android-9.0.0_r42' into pie
 ▪ 29d968cf5 Merge "Snap for 5450365 from ed1ec620984c2334c3ff84264ca80a1d5bf48c7f to pi-platform-release am: 75f9693ae8" into pie-gsi
 ▪ 8f4575890 Snap for 5450365 from ed1ec620984c2334c3ff84264ca80a1d5bf48c7f to pi-platform-release am: 75f9693ae8

 ▼ packages/apps/CustomDoze/
 ▪ c174fdf CustomDoze: Double tap to trigger doze [2/2]

 ▼ packages/apps/DocumentsUI/
 ▪ 1ec25c71 Merge tag 'android-9.0.0_r42' into pie
 ▪ c75b9278 Snap for 5450365 from 25e59678a28b01362736a55f07fd219073d65b8a to pi-platform-release am: 72783c7592

 ▼ packages/apps/EmergencyInfo/
 ▪ c93fc34 Merge tag 'android-9.0.0_r42' into pie
 ▪ 91a4183 Snap for 5450365 from 5289b203a085f1365b80e1fc163b581f9b656141 to pi-platform-release am: 40709a2cce

 ▼ packages/apps/FMRadio/

 ▼ packages/apps/HavocSettings/
 ▪ 71633d2 Add Xiaomi Redmi Note 7 (lavender)
 ▪ 682d3cb Add new maintainer for GSIs
 ▪ adb83b0 Settings: Add toggle to disable charging animation [2/2]
 ▪ 659ffbb Add sirius to devices
 ▪ 015fa4f QS Headers: Fix summary and add missing entry
 ▪ b92117f Add toggle for charging animation [2/2]
 ▪ 34cc4e5 Settings: Set QS BG alpha even with set qs from resources [2/2]
 ▪ 41d3596 Add toggle for lockscreen weather
 ▪ 97f1afe Fix Vietnamese translation
 ▪ cab175e Update Hungarian translations
 ▪ 447469b Add new maintainer for tulip
 ▪ 033c75f Add a6000 in devices
 ▪ 3223538 Add rosy in devices
 ▪ 9ff9c99 Add YUREKA2 to devices
 ▪ aa36b59 Add tblte in devices
 ▪ 16be001 Add j7xelte in devices
 ▪ 9d67adc Update Russian translations
 ▪ c8ec271 Fix Russian translations
 ▪ bfc78b8 Add montana to devices
 ▪ eda9d3d Settings: : Make FP detection in pocket mode configurable [2/2]
 ▪ 6d6235d Update Russian translations
 ▪ c2d18a4 Add Potter to devices

 ▼ packages/apps/Nfc/
 ▪ 2636c6df Merge tag 'android-9.0.0_r42' into pie
 ▪ eac2341a Merge "Snap for 5450365 from 4bcd27dc660f436491f532f58eb800418e212be9 to pi-platform-release am: 8e7094f4f2" into pie-gsi
 ▪ de073482 Snap for 5450365 from 4bcd27dc660f436491f532f58eb800418e212be9 to pi-platform-release am: 8e7094f4f2

 ▼ packages/apps/PackageInstaller/
 ▪ ed8e1766 Merge tag 'android-9.0.0_r42' into pie
 ▪ 73e82477 Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ 01b35042 [RESTRICT AUTOMERGE]: OP_REQUEST_INSTALL_PACKAGES denied by default
 ▪ d6b75293 Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ 80aa96eb [RESTRICT AUTOMERGE]: OP_REQUEST_INSTALL_PACKAGES denied by default
 ▪ c645cf2a Merge "Snap for 5450365 from b101f7ec0e6142b31946ae1a4da58ec4ef9ea690 to pi-platform-release am: 4f09f8e946" into pie-gsi
 ▪ 7351fc69 Snap for 5450365 from b101f7ec0e6142b31946ae1a4da58ec4ef9ea690 to pi-platform-release am: 4f09f8e946
 ▪ ac08ce7b [RESTRICT AUTOMERGE]: OP_REQUEST_INSTALL_PACKAGES denied by default

 ▼ packages/apps/Recorder/

 ▼ packages/apps/Settings/
 ▪ 82db524638 Settings: Add drawable for Private DNS
 ▪ 9d93f715b4 Battery temp: Use MCC to determine the scale type
 ▪ 40563cc6c3 Battery temp: Ensure preference is updated
 ▪ 8e8d5d4b1d Battery stats: Display battery temperature
 ▪ a4555eefd9 Merge tag 'android-9.0.0_r42' into pie
 ▪ 6758f9e75b Settings: Add battery saving mode for location
 ▪ 03d669d057 livedisplay: Don't show display mode and color tempertature on HWC2
 ▪ 76383f3983 Revert "Settings: Hide Night Mode suggestion if LiveDisplay feature is present"
 ▪ cd95dec45f Update French translations
 ▪ 59a23b3b9d Update Russian translations
 ▪ 60716d20dc Update Spanish translations
 ▪ 9da0a58092 Settings: Update NFC drawable
 ▪ d492b42374 Battery Estimates: Disable by default [2/2]
 ▪ 3aa40abc7e Settings: Restart SystemUI when toggling battery estimates
 ▪ 8fcef4284a Settings: Add User icon to the searchbar
 ▪ 9ef94508eb Settings: Add toggle to disable battery estimates in QS [2/2]
 ▪ 3071dfd096 Settings: Add Q Green accent [2/3]
 ▪ a508b726ab Settings: Add Sweet Q Purple accent [2/3]
 ▪ 8441024509 Merge "Snap for 5450365 from 1fb5b5100d642d0a3ab9ca34cdcf2f444ca9e852 to pi-platform-release am: c54ebfa7e3" into pie-gsi
 ▪ 59a8e15ee0 Snap for 5450365 from 1fb5b5100d642d0a3ab9ca34cdcf2f444ca9e852 to pi-platform-release am: c54ebfa7e3
 ▪ 7514d7a601 Update Turkish translations
 ▪ c274d5ae0e Update Russian translations

 ▼ packages/apps/SettingsIntelligence/
 ▪ a5c1e6f SettingsIntelligence: Match Settings searchbar

 ▼ packages/apps/SmartNav/
 ▪ 97d8dce SmartActions: Add in camera action to bindable actions (2/2)
 ▪ 920983b SmartActions: Turn on Tri-state ringer toggle [2/2]
 ▪ f02521b SmartActions: Add Play/Pause media to bindable actions [2/2]
 ▪ 888b755 SmartNav: update smartbar home drawable
 ▪ b97a6ef SmartNav: Use correct colors for popup

 ▼ packages/apps/Terminal/

 ▼ packages/inputmethods/LatinIME/
 ▪ 40292fb36 Merge tag 'android-9.0.0_r42' into pie
 ▪ 3efa61f82 Merge "Snap for 5450365 from b25378ea06605978ca8f30b75b500ba8f39014d0 to pi-platform-release am: 39f2d9a3bd" into pie-gsi
 ▪ 335b1371d Snap for 5450365 from b25378ea06605978ca8f30b75b500ba8f39014d0 to pi-platform-release am: 39f2d9a3bd

 ▼ packages/providers/DownloadProvider/
 ▪ 4f3fcc0 Merge "Snap for 5450365 from 57fb22ac21d2aa8bdc65c6984567e04a93d27256 to pi-platform-release am: a10cb23d08" into pie-gsi
 ▪ 5bf498b Snap for 5450365 from 57fb22ac21d2aa8bdc65c6984567e04a93d27256 to pi-platform-release am: a10cb23d08

 ▼ packages/providers/MediaProvider/
 ▪ b83152f Merge tag 'android-9.0.0_r42' into pie
 ▪ 8f82bed Merge "Snap for 5450365 from 33d84b73b9009df74073c718a293617db7a768fa to pi-platform-release am: 23ae57a307" into pie-gsi
 ▪ 406dbef Snap for 5450365 from 33d84b73b9009df74073c718a293617db7a768fa to pi-platform-release am: 23ae57a307

 ▼ packages/providers/TelephonyProvider/
 ▪ 2f3fe95 Check access to user and password fields in APN db

 ▼ packages/services/Telecomm/
 ▪ 5a383110 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/packages/services/Telecomm into caf
 ▪ 2e83a95f Change UI to be consistency with dialer settings light M2 theme
 ▪ 51381c46 Snap for 5623383 from c7b559464f25669793db41676c766d5cd1dd6ce6 to p-keystone-qcom-release
 ▪ c7b55946 Merge SPL-2019-05-05
 ▪ d937c0f6 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into caf
 ▪ 26f988ee Snap for 5450365 from 6cfe5e382d9c3fb5e5d68c33ead16f96f6315759 to pi-platform-release am: 8e331fc822

 ▼ packages/services/Telephony/
 ▪ c486facc6 Merge tag 'android-9.0.0_r42' of https://android.googlesource.com/platform/packages/services/Telephony into caf
 ▪ b8bd27fec Add missing null check on start of SipIncomingCallReceiver received.
 ▪ 0a15f28ab Change action bar icon and text color from white to grey
 ▪ 0d02064c1 Fix the drawable resource can't be loaded from RRO package
 ▪ bf7a596ab Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into caf

 ▼ prebuilts/build-tools/
 ▪ 7240fd8 build-tools: Update ccache to 3.7.1
 ▪ 421a164 build-tools: Update the rest of the prebuilts
 ▪ 1ef7c1f build-tools: Update ninja using latest source
 ▪ de8b5f7 build-tools: Rebuild for new glibc and sources

 ▼ prebuilts/r8/
 ▪ 51b762f r8: Update D8 and R8 to 1.6.3-dev
 ▪ eab4308 r8: Update D8 and R8 to 1.6.1-dev

 ▼ system/bt/
 ▪ d429b3d31 Snap for 5524043 from d0b9f6155d878426fa948b28b51b4b4c5989201e to pi-platform-release am: ff073f8bbf
 ▪ ff073f8bb Snap for 5524043 from d0b9f6155d878426fa948b28b51b4b4c5989201e to pi-platform-release
 ▪ dd6509256 Merge tag 'android-9.0.0_r42' into pie
 ▪ 720b0f709 Allow to disable the rootcanal test console with a property
 ▪ fef57bda2 Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ 6e72bb784 Fix potential OOB read in sdpu_get_len_from_type
 ▪ 31eef242f DO NOT MERGE: osi: Offload mutex pointer to local scope
 ▪ 13d541ed3 Fall back to CLOCK_BOOTTIME if CLOCK_BOOTTIME_ALARM fails
 ▪ 2d3cdf31b Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ 3a9677202 Fix potential OOB read in sdpu_get_len_from_type
 ▪ b117c7f98 DO NOT MERGE: osi: Offload mutex pointer to local scope
 ▪ 7134b9a64 Snap for 5450365 from f8a5ce9945240777b0d5cd2ba68fdda48e1484a8 to pi-platform-release am: 74d1c7f21a
 ▪ 23c8efe27 DO NOT MERGE: osi: Offload mutex pointer to local scope
 ▪ b78df7426 Fix potential OOB read in sdpu_get_len_from_type

 ▼ system/gatekeeper/
 ▪ 0d9bdfd Remove potential double free

 ▼ system/libhidl/
 ▪ 95ff7b1 Zero-initialize hidl_vec data
 ▪ 42dbb56 Zero-init HIDL core types (all)

 ▼ system/libhwbinder/
 ▪ 17d29d6 Merge tag 'android-9.0.0_r42' into pie
 ▪ 109b4ae Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ 3332ca8 Rely on compiler to zero out structs.
 ▪ fc69df6 Snap for 5450365 from 14418a7f30d925c320ba27dc8a7339ffb349ced6 to pi-platform-release am: 9809f43dd3
 ▪ c157304 Rely on compiler to zero out structs.

 ▼ system/netd/
 ▪ 5170497 Skip permission checking for binder call from system server
 ▪ 81c9f39 Modernize codebase by replacing NULL with nullptr
 ▪ 1ba507f Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ d3cb7fe Fix DnsTlsSocket fast shutdown path
 ▪ 3c50825 Copy queries synchronously in DnsTlsSocket
 ▪ 3c3c62e Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ b4378a5 Fix DnsTlsSocket fast shutdown path
 ▪ 3c12d05 Copy queries synchronously in DnsTlsSocket
 ▪ fe295e9 Snap for 5450365 from f1b1f1ee211b074ef19aac47ae0f8e511b5381cc to pi-platform-release am: 75b9964708
 ▪ ab60917 Fix DnsTlsSocket fast shutdown path
 ▪ 009d06c Copy queries synchronously in DnsTlsSocket

 ▼ system/qcom/
 ▪ 3df6831 Merge tag 'LA.UM.7.6.2.r1-08800-89xx.0' into HEAD

 ▼ system/security/
 ▪ 0137c89 Fix keystore wifi concurrency issue.

 ▼ system/sepolicy/
 ▪ e745a6740 Snap for 5623383 from cb7a79ed1f824d8fc08f36cfac2e104fc2a3ae5d to p-keystone-qcom-release
 ▪ cb7a79ed1 Merge SPL-2019-05-05
 ▪ 902ee1c51 A2dp sink SHO: Add bluetooth support to access mediametrics service
 ▪ 0f8fd3de7 health: allow wake_alarm capability.
 ▪ 0b6245eb7 Merge "Allow mmap for vendor_init" into pie-gsi
 ▪ c589437eb Merge "more mmaps" into pie-gsi
 ▪ 98d69e078 Merge "sepolicy: grant dac_read_search to domains with dac_override" into pie-gsi
 ▪ a4a0a44c1 Allow stats_companion to register thermal throttling event listener.
 ▪ 813df38cc access to /proc/slabinfo
 ▪ a0e4cb211 sepolicy: grant dac_read_search to domains with dac_override
 ▪ 6e29d6d5f more mmaps
 ▪ 3a46b00f4 Allow mmap for vendor_init
 ▪ 6a5590d90 Merge "isolated_app: add mmaps" into pie-gsi
 ▪ b233196f6 Merge "add map permission to rw_socket_perms" into pie-gsi
 ▪ 55b90ac1a isolated_app: add mmaps
 ▪ f0459702d domain.te: Add map permissions to vendor_config_files
 ▪ e6f36b69f add map permission to rw_socket_perms
 ▪ e8f40a97e Merge "sepolicy: Add mmap for profman" into pie-gsi
 ▪ 929dfc5c8 sepolicy: Add mmap for profman
 ▪ 3112c3007 Relax some neverallow rules
 ▪ dcc08a3af Snap for 5450365 from 3feb8646fe27f3ca87b590d163eb0645c8281398 to pi-platform-release am: b8f90dd88f
 ▪ 1a5277b75 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/system/sepolicy into pie

 ▼ system/timezone/
 ▪ 6582db0 Snap for 5450365 from 5ba7ee543f392661ebd91748f1a1f4b287da6c46 to pi-platform-release am: 48b3245d2e

 ▼ system/tools/hidl/
 ▪ 71f3191 Merge cherrypicks of [7513497, 7518418, 7517880, 7517881, 7517882, 7517883, 7517884, 7517885, 7517886, 7517956, 7517957, 7518438, 7518102, 7517887, 7518141, 7518142, 7518143, 7518144, 7517888, 7517889, 7517890, 7517891, 7518439, 7518440, 7518441, 7518442, 7518443, 7518029, 7518104, 7517892, 7517893, 7518061, 7518444, 7517894, 7517895, 7518030, 7518031, 7518445, 7517896, 7517969, 7517897, 7518105, 7518145, 7518146, 7518446] into pi-qpr3-b-release
 ▪ 8b49de0 Zero hidl-generated structs
 ▪ 8b20a45 Merge cherrypicks of [7496339, 7495273, 7495624, 7496340, 7496341, 7496342, 7496343, 7495658, 7494789, 7494790, 7494791, 7496344, 7496345, 7496346, 7496347, 7496574, 7496348, 7496575, 7496576, 7496260, 7496349, 7496350, 7496440, 7496577, 7496578, 7496261, 7495625, 7496442, 7496351] into pi-qpr3-release
 ▪ 60c9678 Zero hidl-generated structs
 ▪ f2f41a7 Snap for 5450365 from fab4a3fa419158001944ec0a439fd4471881aa77 to pi-platform-release am: a31de7c898
 ▪ 3bc44c7 Zero hidl-generated structs

 ▼ system/vold/
 ▪ 90ce226 Merge "resolve merge conflicts of 1571f66c29afebcb7952c03c61f546cc9c3e3135 to pie-gsi" into pie-gsi
 ▪ 0295cd1 resolve merge conflicts of 1571f66c29afebcb7952c03c61f546cc9c3e3135 to pie-gsi
 ▪ 1571f66 Snap for 5524043 from a736dde3f4625ffbc6487065c53545e76f7433b4 to pi-platform-release
 ▪ 756a932 Merge tag 'android-9.0.0_r42' into pie

 ▼ vendor/codeaurora/telephony/
 ▪ 8081ac3 Merge 3b08f080ab3df40fa80a17d6d01ae3c61fc429ff on remote branch
 ▪ 7f0eb92 Merge 3b08f080ab3df40fa80a17d6d01ae3c61fc429ff on remote branch
 ▪ ef175aa Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie

 ▼ vendor/havoc/
 ▪ 538911c0 Havoc 2.6
 ▪ b80dc04f update prebuilt apps
 ▪ 104337f4 add support for custom CROSS_COMPILE_ARM32
 ▪ 1bb73003 fix havoc fingerprint
 ▪ 5cb674b1 vendor: Smart Charging (4/4)
 ▪ f25a68bb soong_config: Add flag for devices use metadata as FDE key

 ▼ vendor/qcom/opensource/audio/
 ▪ 681a5b9 Merge b8875565a5f2ab666831ae9e5f6a3f51ee9514d8 on remote branch
 ▪ 97376a9 policy_hal: fix CTS concurrent audio playback
 ▪ f303a89 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ be26026 Merge b8875565a5f2ab666831ae9e5f6a3f51ee9514d8 on remote branch

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ 98278cb ipacm: Add check to avoid array out of bound
 ▪ 84edb4e Merge c0f433cec15fcedb71ed648f554fa069606884d6 on remote branch
 ▪ 298c2ca Merge "ipacm: fix duplicated entry in nonnat_iface_ipv4_list"
 ▪ a1ef5f9 Merge c0f433cec15fcedb71ed648f554fa069606884d6 on remote branch
 ▪ c0f433c Merge "ipacm: not support xlat on 2st tethered iface"
 ▪ 3879c8e Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ d8210ab Merge ffd769f2a4302f3cbdcc393c203f8b3e6adef630 on remote branch
 ▪ 890105f Merge ffd769f2a4302f3cbdcc393c203f8b3e6adef630 on remote branch
 ▪ ffd769f ipacm: add support on softap intra-bss hw-offload

 ▼ vendor/qcom/opensource/interfaces/
 ▪ a01c238 Bluetooth: Move A2DP HAL 2.0 interface to opensource
 ▪ 6b55634 Merge "Add Hash Version for Servicetracker HAL"
 ▪ f504d22 IQtiMapper: Add interface to get plane layout information
 ▪ 885d4c6 Merge 93071bf7476a2fe0bfb1f42074d19af7975425e2 on remote branch
 ▪ 6a493f7 Merge "display: Add API to set luminance"
 ▪ 5d89f55 Merge 93071bf7476a2fe0bfb1f42074d19af7975425e2 on remote branch
 ▪ f70e204 display: Add API to set luminance
 ▪ a746351 Merge tag 'LA.UM.7.5.2.r1-02900-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ 93071bf display: Add extensions for mapper3.0 and allocator 3.0
 ▪ a49a147 Merge c98005e701b03f78d8585aa1afb3295b694276f3 on remote branch
 ▪ 65c8bb9 Merge c98005e701b03f78d8585aa1afb3295b694276f3 on remote branch

 ▼ vendor/themes/
 ▪ de10d16 themes: Fix package name
 ▪ 938c917 themes: Add Q Green accent [3/3]
 ▪ e8b5a2b themes: Add Sweet Q Purple accent [3/3]

 ▼ vendor/xiaomi/
 ▪ 50004ca7 update Postprocessing
 ▪ 5b56302a adreno
 ▪ c10e873b vulkan

====================
     05-10-2019
====================
 ▼ art/
 ▪ fb50648a99 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/art into pie
 ▪ 3240f9d877 Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' of https://source.codeaurora.org/quic/la/platform/art into pie
 ▪ ace3e457f8 Merge b529bd7902d5cf0f0a8818da3658074006799391 on remote branch
 ▪ 5067f7504e ART: Disable use of dex2oat pgo profile [2/2]
 ▪ 384eb32512 Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/art into pie

 ▼ bionic/
 ▪ 03d4f19e4 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/bionic into pie
 ▪ 245e08f39 Snap for 5450365 from dad73ef232034dd0f4f46bda90c74e8727d840cc to pi-platform-release
 ▪ 5ac5fa6ef Merge tag 'android-9.0.0_r37' into pie
 ▪ 88be090fe Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie
 ▪ c3312955d Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/bionic into pie
 ▪ 2b757643d libc: Optimize ARM memcmp by using NEON.
 ▪ 2a734c5a3 Merge f6551beda08b869b080e303fe8566f61c592fbd7 on remote branch
 ▪ be4b285bf Merge f6551beda08b869b080e303fe8566f61c592fbd7 on remote branch
 ▪ d4539898a Merge f6551beda08b869b080e303fe8566f61c592fbd7 on remote branch
 ▪ d8cdbe508 Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie

 ▼ build/make/
 ▪ b6f635f5c Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/build into pie
 ▪ 24df732a9 Make change and version bump to PPRL.190505.001
 ▪ 96bdddc91 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/build into pie
 ▪ ef415547f proguard_flags: Remove -useuniqueclassmembernames
 ▪ 92dc13f53 Version bump to PQ3B.190605.005 [core/build_id.mk]
 ▪ 7161acd14 Make change and version bump to PQ3B.190503.001
 ▪ eb3829d30 Version bump to PQ3B.190605.004 [core/build_id.mk]
 ▪ cf860f2ab Version bump to PQ3A.190605.003 [core/build_id.mk]
 ▪ b1ea2493b Makefile: don't generate changelog twice
 ▪ 21b6f5a32 Make change and version bump to PQ3B.190605.003
 ▪ 78d61e203 Update Security String to 2019-06-05
 ▪ 3ced66d63 Version bump to PQ3B.190605.002
 ▪ 91b67be5c Version bump to PQ3A.190605.002
 ▪ 59736b363 Version bump to PQ3B.190605.001
 ▪ 72a0a1e90 Version bump to PQ3B.190408.015
 ▪ 40bea2aa2 Make change and version bump to PQ3B.190408.014
 ▪ 27ea4bbda Version bump to PQ3B.190408.013
 ▪ 14b9abe3b Version bump to PQ3B.190408.012
 ▪ c154573a5 Make change and version bump to PQ3A.190605.001
 ▪ ce4fc1a01 Update Security String to 2019-06-05 Bug:129374896 Merged-In: 2c26c3d4c0314f8a3f905e5a7081556f7b4b353a (cherry picked from commit 3ae4e858b7c169b19a4994dd6b124a68fa234ff0)
 ▪ d623fbbe6 Make change and version bump to PQ3A.190601.001
 ▪ 6a7fa4018 [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 (cherry picked from commit 2db03695f4fccc312947155ae724f48885e472c5)
 ▪ 50b6fc601 Version bump to PQ3B.190408.011
 ▪ 4ccaae495 Version bump to PQ3B.190408.010
 ▪ 593be3c49 Update Security String to 2019-06-05 Bug:129374896 Merged-In: 2c26c3d4c0314f8a3f905e5a7081556f7b4b353a am: 3ae4e858b7 am: cce67c52c9 am: e90b407c2f
 ▪ e90b407c2 Update Security String to 2019-06-05 Bug:129374896 Merged-In: 2c26c3d4c0314f8a3f905e5a7081556f7b4b353a am: 3ae4e858b7 am: cce67c52c9
 ▪ cce67c52c Update Security String to 2019-06-05 Bug:129374896 Merged-In: 2c26c3d4c0314f8a3f905e5a7081556f7b4b353a am: 3ae4e858b7
 ▪ 3ae4e858b Update Security String to 2019-06-05 Bug:129374896 Merged-In: 2c26c3d4c0314f8a3f905e5a7081556f7b4b353a
 ▪ 26ce518ac Make change and version bump to PQ3B.190408.009
 ▪ 190daf9cd Version bump to PQ3B.190408.008

 ▼ build/soong/
 ▪ b84b19dd Fix formatting

 ▼ development/
 ▪ 3eec2e57b Snap for 5450365 from 33a187438ef781129865711235b2ab4d6a7ec69d to pi-platform-release
 ▪ f028b9675 Merge tag 'android-9.0.0_r37' into staging/lineage-16.0_merge-android-9.0.0_r37

 ▼ device/havoc/sepolicy/
 ▪ 098d4fd sepolicy: Fix moar ota app denials
 ▪ 6592060 [2/2] sepolicy: update_engine neverallows
 ▪ 6abf76c sepolicy: Allow CPUInfo access to thermal sysfs
 ▪ 109c44c Init Havoc...
 ▪ ce1a64a sepolicy: recovery: allow reading fbe key version
 ▪ a5673f1 sepolicy: recovery: allow mounting of usb storage
 ▪ 23055a1 sepolicy: recovery: allow recovery to read battery info
 ▪ 96d0e6e sepolicy: recovery: Allow setting sys.usb.config
 ▪ f5ebb5a sepolicy: recovery: Allow volume manager write to /sys/*/uevent
 ▪ d767f42 sepolicy: recovery: Add policy for /dev/block/volmgr
 ▪ 6e71acf sepolicy: recovery: Fix the volume manager blkid.tab denial
 ▪ 7b886bc sepolicy: recovery: Allow reading proc_filesystems
 ▪ 42c3067 sepolicy: recovery: Add policy for volume manager

 ▼ device/qcom/sepolicy/
 ▪ 8dc6d73b Merge tag 'LA.UM.7.5.r1-04800-8x96.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ daf54a9c Merge "sepolicy: audio: Define file context for audio files"
 ▪ c1753d6b sepolicy: audio: Define file context for audio files
 ▪ 9bda41be Merge "Bluetooth: Adding permission for rfkill failure"
 ▪ 82b4c853 Bluetooth: Adding permission for rfkill failure
 ▪ d3cecede Revert "Revert "Revert "Adding permission for rfkill failure"."
 ▪ 3e2a8b03 Bluetooth: Adding permission for rfkill failure
 ▪ 372f4da3 Revert "Revert "Adding permission for rfkill failure".
 ▪ 6de6c464 Revert "Adding permission for rfkill failure".
 ▪ e5e47424 Merge cb33a0ebaf9bf5868695e01e5e9c7118ec2baed6 on remote branch
 ▪ 485a15dd Adding permission for rfkill failure
 ▪ 4e44a003 sepolicy : allow system_app to access system_server_tmpfs files
 ▪ a93fe110 Merge "sepolicy: Allow the write access to persist property"
 ▪ bc4c234d sepolicy: Allow the write access to persist property
 ▪ 283a6fea sepolicy: Add required sepolicy for vulkan.adreno.so
 ▪ 10a41157 Merge 72bc038b99a3c4c36ba37a039e0048b2f93597bb on remote branch
 ▪ cb33a0eb Merge "sepolicy: Add persist file access rules for USTA test App"
 ▪ 9fac4383 Merge 72bc038b99a3c4c36ba37a039e0048b2f93597bb on remote branch
 ▪ 06e87e2c sepolicy: Add persist file access rules for USTA test App
 ▪ c6bc1341 sepolicy: Remove setgid/setuid rules for time-services
 ▪ 3b459514 sepolicy: adress few denials
 ▪ f4f45c20 Merge 72bc038b99a3c4c36ba37a039e0048b2f93597bb on remote branch
 ▪ 1b52c854 sepolicy: Add required sysfs nodes access for display
 ▪ 68ad03ea Allow perf hal to access service tracker hal
 ▪ 63d01d8e Merge tag 'LA.UM.7.4.r1-05000-8x98.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ 97ba8049 Merge "sepolicy: Adding sepolicy rules for servicetracker HAL"

 ▼ device/xiaomi/gemini/
 ▪ 47ec4516c caf tag: LA.UM.7.5.r1-04800-8x96.0
 ▪ dfdee3b54 Android 9.0.0 Release 39 (PD2A.190115.032)
 ▪ d12538ea9 msm8996-common: Add 2 more notification icons
 ▪ 11613cc91 Revert "Add power off alarm service"
 ▪ a4ab4cd27 Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' from https://source.codeaurora.org/quic/la/device/qcom/common
 ▪ 6155df6e9 update vendor_framework_compatibility_matrix.xml
 ▪ a4823fdbb capricorn: Add power off alarm service
 ▪ 4be647a4e Revert "msm8996-common: sepolicy: Label sys.post_boot.parsed"
 ▪ 0d08e09cc manifest: add android.hardware.wifi.offload
 ▪ 928a6c8a1 Add API to read the device SOC ID.
 ▪ c3d43d8af update mixer_paths_tasha.xml from V10.2.2.0.OAAMIXM
 ▪ 3ce991aac build kernel with clang 9.0.3
 ▪ 81cfc83d1 init.qcom.rc: label vendor services
 ▪ 31294e613 Add power off alarm service
 ▪ 0a0cfe299 add PRODUCT_PACKAGE_OVERLAYS
 ▪ fbb1e64e0 fix sepolicy warnings
 ▪ f1342d3d7 update vendorsetup.sh
 ▪ 9283b4c79 overlay: PIN critical apps and system services that get swapped
 ▪ 571f8be5e Revert "PIN critical apps and system services that get swapped"
 ▪ 26d8818a2 Pin HOME application
 ▪ e0bc5895c capricorn: use gcc-arm-8.3-2019.03
 ▪ 4dee7724b fix SDCLANG_LTO_DEFS path
 ▪ 06bb8ad20 vndk fixes 2
 ▪ d660b1f7e hw-qcom-camera: Completed FR49059 and FR49058
 ▪ df2c1e401 kernel: TARGET_KERNEL_USE_LLD := true
 ▪ 3dae3a761 drop prebuilt Kiwi & Phonograph
 ▪ 2c2dbe70e add SysUI to PRODUCT_DEXPREOPT_SPEED_APPS
 ▪ 02bcf0fc4 vndk fixes
 ▪ 278ea6c99 restore audio from jasmine_sprout

 ▼ device/xiaomi/translations/
 ▪ 64f93cb LiveDisplay RU
 ▪ e4244f3 2

 ▼ external/aac/
 ▪ 3f61fd1 Add sanity check in huff_decode()

 ▼ external/icu/
 ▪ 1d56f7edc Merge tag 'android-9.0.0_r37' into staging/lineage-16.0_merge-android-9.0.0_r37
 ▪ 44dab7d4d Snap for 5450365 from 403985900949c50752009df72c38c1e59c295a3c to pi-platform-release

 ▼ external/nano/
 ▪ 4fb9f298 tweaks: adjust some indentation after the previous change
 ▪ c338d868 tweaks: rename some single-letter variables to the same significant word
 ▪ 247dd8f0 tweaks: rename a variable, reshuffle declarations, and drop an assert
 ▪ 71d0847b tweaks: merge two functions, as the one is used only by the other
 ▪ c55d1447 tweaks: drop most of the remaining debugging code, and some timing code
 ▪ da91a44f tweaks: reshuffle two #ifdefs, to avoid an unpaired brace
 ▪ 02d3a2c0 tweaks: remove some unneeded braces, and reshuffle for more symmetry
 ▪ 57646196 search: stay in the Search menu when trying to Replace in view mode
 ▪ 3c959fd0 tweaks: drop a useless tidying-up call, as spelling does not use regexes
 ▪ f0bc94fd tweaks: move the tyding-up-after-a-search to a single exit point
 ▪ 8720cfcc tweaks: rename two more functions, to be simpler too
 ▪ 954c4d03 tweaks: rename two functions, to be simpler
 ▪ edf6995b zapping: use the 'keep_cutbuffer' logic to keep undo items apart
 ▪ b50d5758 zapping: disjoin a zap command from earlier ones when the mark is set
 ▪ 6c4d0d87 tweaks: remove a condition that has become superfluous
 ▪ a962bcec copying: let a copy command break a chain of cut or zap commands
 ▪ e0c5c589 tweaks: remove a superfluous condition, in three places
 ▪ dfe87540 syntax: po: colorize also escaped hex and octal codes
 ▪ 6c4f228f tweaks: invert two conditions, in order to elide an extra variable
 ▪ fe06ae5f tweaks: normalize the indentation after the previous two changes
 ▪ 07289f43 tweaks: invert a condition, in order to return earlier
 ▪ 99d155d8 tweaks: reshuffle an assignment, to be able to return earlier
 ▪ 3346c539 tweaks: place a function better, and reduce some comments to a single one
 ▪ 083218ac tweaks: rename two parameters, to differentiate them from function names
 ▪ fd3b3bc1 cutting: clear the cutbuffer when the previous operation was copying
 ▪ 9bc6bc83 tweaks: rename two variables, for more contrast
 ▪ d4468b2d tweaks: condense a comment and reshuffle a couple of lines
 ▪ 404a6862 tweaks: really don't bother renumbering the lines in the cutbuffer
 ▪ 85fc4147 tweaks: stop passing 'cutbuffer' and 'cutbottom' back and forth
 ▪ 2b9dd6c5 tweaks: don't bother saving and restoring 'cutbottom' all the time
 ▪ 9e44a53b copying: scroll just one line when M-6 is pressed on the bottom row
 ▪ 0c561f03 copying: make M-6 do nothing when at end of buffer
 ▪ e5831f81 tweaks: rename two variables, to be less cryptic
 ▪ fa21986e oops: apparently the line numbers in the cutbuffer do matter
 ▪ 772137ca tweaks: rename a variable, to fit a bit better
 ▪ 4c53e2f5 tweaks: elide two unneeded variables
 ▪ 14140d52 tweaks: don't bother renumbering the lines in the cutbuffer
 ▪ 17aa9371 tweaks: rename a function, to better indicate what it does
 ▪ 208995e4 tweaks: move a bit of timing code to where it will be needed
 ▪ b5036707 tweaks: rename a variable, to match another with the same meaning
 ▪ 7c08e8ea cutting: ignore the mark when a word is deleted
 ▪ 542426f1 tweaks: add a warning for something that shouldn't occur
 ▪ 6319a861 tweaks: improve some comments, reshuffle a line, and rename a variable
 ▪ 9888e67b tweaks: rename two variables, for more contrast with the partition stuff
 ▪ 8fe19e34 tweaks: use a more direct call when a single linestruct is deleted
 ▪ 896cfcef tweaks: when OR'ing, put the most likely condition first
 ▪ d54180ad tweaks: reduce a bit of mark-adjusting code to its essence
 ▪ 065afe6e tweaks: reshuffle a bit of code, to be less intertwined
 ▪ 37eccd31 tweaks: rename a function, to be more fitting
 ▪ b9dd572a tweaks: set a boolean directly, instead of using a function call
 ▪ 3fe17e03 docs: adjust the wording of the README to be factually correct
 ▪ 6e3a3964 tweaks: adjust the indentation after the previous change
 ▪ 18eb7e6d tweaks: elide an unneeded 'if' and 'break'
 ▪ e84a790b tweaks: rename a variable, to better indicate it contains two characters
 ▪ 20d9070a tweaks: move an assignment that is useful only when searching forward
 ▪ 482b2814 tweaks: step away one character from the current bracket, not one byte
 ▪ e92c3110 po: update translations and regenerate POT file and PO files
 ▪ 1ca9241e bump version numbers and add a news item for the 4.2 release
 ▪ 0b6889cb tweaks: rename another function, to be distinct and fitting
 ▪ 00410d83 tweaks: rename a function, to be distinct and fitting
 ▪ fcad442d tweaks: declare a function as const and let its allocated string leak
 ▪ 34d22d3f wrapping: improve the persistence of the prepending behavior
 ▪ 1326af7e tweaks: drop an unneeded saving and restoring of a variable
 ▪ 11aa191b tweaks: rename a variable, to distinguish it from a browser function
 ▪ ea844d28 tweaks: exclude a bit more code from a single-buffer build
 ▪ 7668bfe6 tweaks: remove a redundant, enclosed #ifdef
 ▪ 493f2155 speller: do not crash by trying to free something that cannot be freed
 ▪ 723451a5 tweaks: adjust a few comments and some indentation
 ▪ 326e41d7 tweaks: elide an unneeded intermediate variable
 ▪ 3ce74eb8 wrapping: compute the width of a succeeding line in the correct manner
 ▪ ec4883b6 tweaks: remove an unneeded condition
 ▪ e8f69e40 wrapping: add a missing space only when the remainder will be prepended
 ▪ 297fb013 wrapping: trim any trailing blanks when cursor goes to next line
 ▪ 4e52c755 options: make --breaklonglines work also when --ignorercfiles is used
 ▪ 192a303e tweaks: condense and improve a handful of comments
 ▪ dcec8a41 tweaks: rename a variable, for a little more meaning
 ▪ 5316f507 tweaks: elide an unneeded variable
 ▪ 286c8778 tweaks: elide an unneeded parameter, as the function already assumes it
 ▪ 86132853 build: be more specific and avoid committing accidentally changed files
 ▪ 8a4639cd docs: put the 'set guidestripe' option into its alphabetical position
 ▪ 576c20c4 po: update translations and regenerate POT file and PO files
 ▪ 3a0a6b5d bump version numbers and add a news item for the 4.1 release
 ▪ c039aaad tweaks: remove several unneeded bad-state checks and their messages
 ▪ 145bb6e0 build: don't do fuzzy matching when merging PO files against the POT file
 ▪ 9cc70d20 tweaks: shorten a comment to its essence
 ▪ 3604ad29 build: remove obsolete translations from the PO files after merging
 ▪ 1fe3e2ed docs: mention that -b is the opposite of -w also in the latter's item
 ▪ baca8bb1 indenting, commenting: ensure a partial line stays displayed properly
 ▪ 1c707d4f unindent: ensure that a partial line gets displayed properly afterwards
 ▪ c0e37794 display: report and catch a bad state, to prevent a possible hang
 ▪ bf6bcde0 tweaks: initialize a boolean before it is referenced  [valgrind]
 ▪ 167a8e5c options: make --nowrap override again a contrary nanorc setting
 ▪ 90cbdbbe docs: mention that M-S now toggles softwrap and M-N line numbers
 ▪ d83a8eb3 justify: correctly compute the number of lines to take, to avoid a crash
 ▪ 98cc39e8 tweaks: reshuffle some lines, to elide an 'if'
 ▪ b20fadd6 tweaks: free the copy of a linter message in all cases  [valgrind]
 ▪ cdf0f8e6 tweaks: drop two 'const' qualifiers, to silence the compiler
 ▪ f645009a tweaks: free the result string from an invocation error  [coverity]
 ▪ 2b2736d4 tweaks: free some memory before a possible error exit  [coverity]
 ▪ 5a6029a9 tweaks: rename some variables, for more contrast and to match others
 ▪ 8d272db4 tweaks: rename two variables, for more contrast
 ▪ 70885d0f tweaks: use a signed type for a result that could be negative  [coverity]

 ▼ external/openssh/
 ▪ fd0fa130 makedepend

 ▼ external/skia/
 ▪ 8dd03c05b0 Snap for 5450365 from 18676d83b37934a493980899f89acb5ce6f36527 to pi-platform-release
 ▪ b9a8f7e40f Merge tag 'android-9.0.0_r37' into pie
 ▪ 6f78a83cfd Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/external/skia into pie
 ▪ b1e7a30f15 Revert "Revert "switched from NUM_SHADER_BINARY_FORMATS to NUM_PROGRAM_BINARY_FORMATS""
 ▪ d4e30f397d Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/external/skia into pie
 ▪ 104ff01147 Merge cherrypicks of [7077329, 7077440, 7077330, 7077468, 7076852, 7077469, 7077580, 7077581, 7077582, 7074025, 7077706, 7077707, 7077708, 7077388, 7077583, 7077584, 7077585, 7077726, 7077727, 7077331, 7077332, 7077459, 7077709, 7077710, 7077711, 7077712, 7077460, 7077461, 7077333, 7077334, 7077696] into pi-qpr3-release
 ▪ b4a8cb3baa RESTRICT AUTOMERGE: Make listener lists threadsafe with a mutex.
 ▪ 8b86cd71c2 RESTRICT AUTOMERGE: Make listener lists threadsafe with a mutex.

 ▼ external/turbine/
 ▪ 2eae284 Merge tag 'android-9.0.0_r37' into pie

 ▼ external/v8/
 ▪ 90feea47 Fix type confusion in libpac

 ▼ external/vim/
 ▪ 4ca41534b patch 8.1.1312: Coverity warning for using uninitialized variable
 ▪ 23b513923 patch 8.1.1311: aborting an autocmd with an exception is not tested
 ▪ 42ae78cff patch 8.1.1310: named function arguments are never optional
 ▪ 6b528fa06 patch 8.1.1309: test for Normal highlight fails on MS-Windows GUI
 ▪ f90b6e03a patch 8.1.1308: the Normal highlight is not defined when compiled with GUI
 ▪ a6c27c47d Update runtime files
 ▪ d4aa83af1 patch 8.1.1307: cannot reconnect to the X server after it restarted
 ▪ eae1b91fe patch 8.1.1306: Borland support is outdated and doesn't work
 ▪ 691ddeefb patch 8.1.1305: there is no easy way to manipulate environment variables
 ▪ 68cbb14ba patch 8.1.1304: MS-Windows: compiler warning for unused value
 ▪ be0a2597a patch 8.1.1303: not possible to hide a balloon
 ▪ 06bd82486 patch 8.1.1302: v:beval_text is not tested in Visual mode
 ▪ 0b75f7c97 patch 8.1.1301: when compiled with VIMDLL some messages are not shown
 ▪ 2f10658b0 patch 8.1.1300: in a terminal 'ballooneval' does not work right away
 ▪ a5c6a0b6c patch 8.1.1299: "extends" from 'listchars' is used when 'list' is off
 ▪ 5416b7503 patch 8.1.1298: invalid argument test fails without X clipboard
 ▪ 240f7abab patch 8.1.1297: invalid argument test fails without GTK
 ▪ 27821260c patch 8.1.1296: crash when using invalid command line argument
 ▪ 98ffe4c6d patch 8.1.1295: when vimrun.exe does not exist external command may fail
 ▪ 93d77b2cb patch 8.1.1294: MS-Windows: Some fonts return wrong average char width
 ▪ fda9784dc patch 8.1.1293: MSVC files are no longer useful
 ▪ ba9ea91be patch 8.1.1292: invalid command line arguments not tested
 ▪ 1063f3d20 patch 8.1.1291: not easy to change directory and restore
 ▪ fd31e45e4 patch 8.1.1290: .hgignore and .gitignore are either distributed or in git
 ▪ b6cb26ffe patch 8.1.1289: may not have enough space to add "W" to search stats
 ▪ 9ce3fa828 patch 8.1.1288: search stats don't show for mapped command
 ▪ 7e1a5af54 patch 8.1.1287: cannot build with +eval but without +mouse
 ▪ 4fa06870e patch 8.1.1286: running tests leaves XTest_tabpage_cmdheight file behind
 ▪ f0ab01f6d patch 8.1.1285: test17 is old style
 ▪ d13622112 patch 8.1.1284: detecting *.tmpl as htmlcheetah is outdated
 ▪ c7a10b35d patch 8.1.1283: delaying half a second after the top-bot message
 ▪ 91882cf71 patch 8.1.1282: running make in src/po leaves LINGUAS file behind
 ▪ 8ffc7c8b5 patch 8.1.1281: cannot specify a count with :chistory
 ▪ 25c9c680e patch 8.1.1280: remarks about functionality not in Vi clutters the help
 ▪ 9a061cb78 patch 8.1.1279: cannot set 'spellang' to "sr@latin"
 ▪ 58187f1c8 patch 8.1.1278: missing change for "combine" field
 ▪ 8fc0271e9 patch 8.1.1277: missing screenshot update
 ▪ de24a8701 patch 8.1.1276: cannot combine text properties with syntax highlighting
 ▪ cf6a55c4b patch 8.1.1275: cannot navigate to errors before/after the cursor
 ▪ ce79353ac patch 8.1.1274: after :unmenu can still execute the menu with :emenu
 ▪ f653a6bcf patch 8.1.1273: compiler warning in direct write code
 ▪ 711f02da6 patch 8.1.1272: click on WinBar of other window not tested
 ▪ b3de6c4a7 patch 8.1.1271: compiler warnings for use of STRNCPY()
 ▪ 9dfa31391 patch 8.1.1270: cannot see current match position
 ▪ ed5ab2a95 patch 8.1.1269: MS-Windows GUI: multibyte chars with a 0x80 byte do not work
 ▪ 510671a05 patch 8.1.1268: map completion test fails in GUI
 ▪ 4b8366b56 patch 8.1.1267: cannot check if GPM mouse support is working
 ▪ 8caef443b patch 8.1.1266: winbar test doesn't test enough
 ▪ bedf091a9 patch 8.1.1265: when GPM mouse support is enabled double clicks do not work
 ▪ d2fad67e3 patch 8.1.1264: crash when closing window from WinBar click
 ▪ 66f831115 patch 8.1.1263: mouse clicks in WinBar not tested
 ▪ bb8476be8 patch 8.1.1262: cannot simulate a mouse click in a test
 ▪ 25190db22 patch 8.1.1261: no error for quickfix commands with negative range
 ▪ e4f5f3aa3 patch 8.1.1260: comparing with pointer instead of value
 ▪ e5c83286b patch 8.1.1259: crash when exiting early
 ▪ 9404a18ad patch 8.1.1258: the "N files to edit" message can not be surpressed
 ▪ 819d3e52a patch 8.1.1257: MSVC: name of object directory now always right
 ▪ 3ff33114d patch 8.1.1256: cannot navigate through errors relative to the cursor
 ▪ 12e91862c patch 8.1.1255: building desktop files fails on FreeBSD
 ▪ 61df0c799 patch 8.1.1254: mapping completion contains dead code
 ▪ 92b9e60cb patch 8.1.1253: mapping completion test fails
 ▪ 1776a28e9 patch 8.1.1252: not all mapping completion is tested
 ▪ 2cb9f0253 patch 8.1.1251: no test for completion of mapping keys
 ▪ d788543ac patch 8.1.1250: no test for netterm mouse
 ▪ c6b1cc967 patch 8.1.1249: compiler warning for uninitialized variable
 ▪ 92fd599e0 patch 8.1.1248: no test for dec mouse
 ▪ d0621d85a patch 8.1.1247: urxvt mouse codes are not tested
 ▪ bb7e1b4ba patch 8.1.1246: cannot handle negative mouse coordinate from urxvt
 ▪ 36d502225 patch 8.1.1245: ":copen 10" sets height in full-height window
 ▪ 1ee36d6ff patch 8.1.1244: no tests for CTRL-mouse-click
 ▪ 26f0cb145 patch 8.1.1243: compiler warnings for incomplete switch statement
 ▪ 0fef0aeb1 patch 8.1.1242: no cmdline redraw when tabpages have different 'cmdheight'
 ▪ b731689e8 patch 8.1.1241: Ex command info contains confusing information
 ▪ d96dbd6f9 patch 8.1.1240: runtime desktop files are overwritten by build
 ▪ a9dd2d3c7 patch 8.1.1239: key with byte sequence containing CSI does not work
 ▪ a0e67fc16 patch 8.1.1238: MS-Windows: compiler warning for sprintf() format
 ▪ 52111f823 patch 8.1.1237: error for using "compl", reserved word in C++
 ▪ fe368edcc patch 8.1.1236: sjiscorr.c not found in shadow directory
 ▪ 602abeb20 Update .gitignore
 ▪ c0af78fa0 patch 8.1.1235: compiler warnings for using STRLEN() value
 ▪ 701df4eb6 patch 8.1.1234: swap file test fails on MS-Windows
 ▪ c779c674a patch 8.1.1233: cannot build tiny version
 ▪ 1b243eafb patch 8.1.1232: can't build on MS-Windows
 ▪ 67cf86bff patch 8.1.1231: asking about existing swap file unnecessarily
 ▪ afde13b62 patch 8.1.1230: a lot of code is shared between vim.exe and gvim.exe
 ▪ ab4cece60 patch 8.1.1229: warning for posix_openpt() not declared
 ▪ 45e18cbdc patch 8.1.1228: not possible to process tags with a function
 ▪ 7a9df9dd0 patch 8.1.1227: duplicate entries in the generate .desktop files
 ▪ 6c60f47fb patch 8.1.1226: {not in Vi} remarks get in the way of useful help text
 ▪ 1e4496878 patch 8.1.1225: cannot create a pty to use with :terminal on FreeBSD
 ▪ f720d0a77 patch 8.1.1224: MS-Windows: cannot specify font weight
 ▪ 564344ace patch 8.1.1223: middle mouse click test fails without a clipboard
 ▪ dcaa54dde patch 8.1.1222: build still fails on MS-Windows
 ▪ ad6dc49a7 patch 8.1.1221: filtering does not work when listing marks
 ▪ 0ee1bdff7 patch 8.1.1220: build fails on MS-Windows
 ▪ 6ee965877 patch 8.1.1219: not checking for NULL return from alloc()
 ▪ 00aa069db patch 8.1.1218: cannot set a directory for a tab page
 ▪ 2155a6aba patch 8.1.1217: MS-Windows: no space reserved for font quality name
 ▪ c1b8160b4 patch 8.1.1216: mouse middle click is not tested
 ▪ 49543fbce patch 8.1.1215: "make clean" does not remove generated src/po files
 ▪ c6b37db1b patch 8.1.1214: old style tests
 ▪ e13a3901c patch 8.1.1213: "make clean" in top dir does not cleanup indent test output
 ▪ 520e24523 patch 8.1.1212: signal PWR is not tested
 ▪ e61e548dd patch 8.1.1211: not all user command code is tested
 ▪ ac9fb1802 patch 8.1.1210: support for user commands is spread out
 ▪ 5431589d2 patch 8.1.1209: clever compiler warns for buffer being too small
 ▪ c8cc0ad47 patch 8.1.1208: links to repository use wrong file name
 ▪ 1f3601e92 patch 8.1.1207: some compilers give warning messages
 ▪ d1f90bbca patch 8.1.1206: user command parsing and listing not properly tested
 ▪ a68e59590 patch 8.1.1205: a BufReadPre autocommand may cause the cursor to move
 ▪ a561a41a7 patch 8.1.1204: output of :command with address completion is not nice
 ▪ 69ea58728 patch 8.1.1203: some autocmd tests are old style
 ▪ c2d09c9f2 patch 8.1.1202: always get regexp debugging logs when building with -DDEBUG
 ▪ 725310d89 patch 8.1.1201: output of :command is hard to read
 ▪ 31fc39e47 patch 8.1.1200: old style comments in debugger source
 ▪ 8485be4e4 patch 8.1.1199: no test for :abclear
 ▪ 958eabe5e patch 8.1.1198: bracketed paste may remain active after Vim exists
 ▪ c75e81262 patch 8.1.1197: when starting with multiple tabs file messages is confusing
 ▪ 7bde95a46 patch 8.1.1196: parallel build may fail
 ▪ eead75c5e patch 8.1.1195: Vim script debugger functionality needs cleanup
 ▪ 911ead126 Update runtime files
 ▪ ad3ec76bb patch 8.1.1194: typos and small problems in source files
 ▪ 037c54f26 patch 8.1.1193: typos and small problems in test files
 ▪ 4c25bd785 patch 8.1.1192: mode is not cleared when leaving Insert mode with mapped Esc
 ▪ 0fdd94359 patch 8.1.1191: not all debug commands are covered by a test
 ▪ 93a4879c2 patch 8.1.1190: has('vimscript-3') does not work
 ▪ abc7c7fc5 patch 8.1.1189: mode is not cleared when leaving Insert mode
 ▪ d2e716e6d patch 8.1.1188: not all Vim variables require the v: prefix
 ▪ 3a4c53ba5 patch 8.1.1187: cannot recognize Pipfile
 ▪ 334ad4150 patch 8.1.1186: readdir() allocates list twice
 ▪ 86ec6d7e1 patch 8.1.1185: mapping for CTRL-X is inconsistent
 ▪ 137c14bb4 patch 8.1.1184: undo file left behind after running test
 ▪ b49e3563b patch 8.1.1183: typos in VisVim comments
 ▪ b9cdb3717 patch 8.1.1182: some function prototypes are outdated
 ▪ 2b00b9b0f patch 8.1.1181: tests for mouse clicks are a bit flaky
 ▪ 113bf0672 patch 8.1.1180: Vim script debugger tests are old style
 ▪ 696d63772 patch 8.1.1179: no test for mouse clicks in the fold column
 ▪ 4945219b9 patch 8.1.1178: when mouse click tests fails value of 'ttytype' is unknown
 ▪ 1a4dce7ca patch 8.1.1177: .ts files are recognized as xml, typescript is more common
 ▪ 7f2797658 patch 8.1.1176: test for dragging a tab is flaky
 ▪ e3e3828f9 patch 8.1.1175: no test for dragging a tab and double click for new tab
 ▪ 8dc4c7292 patch 8.1.1174: cannot build with Ruby 1.8
 ▪ a8356bc17 patch 8.1.1173: suspend test has duplicated lines
 ▪ 74e3d4ec1 patch 8.1.1172: cursor properties were not fully tested
 ▪ 316c16797 patch 8.1.1171: statusline test could fail in large terminal
 ▪ a0aaf3c4d patch 8.1.1170: terminal ANSI color test does not cover all colors
 ▪ 837854d1b patch 8.1.1169: writing coverage info in a separate dir is not needed
 ▪ 87dcfd75c patch 8.1.1168: not all screen update code of terminal is executed in tests
 ▪ 39f76c6ac patch 8.1.1167: no test for closing tab by click in tabline
 ▪ 9c35d05f4 patch 8.1.1166: gettitle test can still fail when another Vim is running
 ▪ ca57ab54d patch 8.1.1165: no test for mouse clicks in the terminal tabpage line
 ▪ 700dfaa86 patch 8.1.1164: gettitle test is failing when server name differs
 ▪ 5d48e0d99 patch 8.1.1163: codecov does not report all the coverage information
 ▪ f587ef345 patch 8.1.1162: incorrect coverage information; typo in color name
 ▪ 1d79ce81e patch 8.1.1161: unreachable code
 ▪ c8b3ddab5 patch 8.1.1160: termcodes test would fail in a very big terminal
 ▪ a8d22e3a4 patch 8.1.1159: MS-Windows: with a silent (un)install $VIM/_vimrc is removed
 ▪ 04af19637 patch 8.1.1158: json encoded string is sometimes missing the final NUL
 ▪ f9b89b467 patch 8.1.1157: Unicode tables are out of date
 ▪ d489c9801 patch 8.1.1156: Unicode emoji and other image characters not recognized
 ▪ 3fbd2d7c3 patch 8.1.1155: termcodes tests can be improved
 ▪ 496555fd1 patch 8.1.1154: getting a newer msgfmt on Travis is too complicated
 ▪ 9a419ffb9 patch 8.1.1154
 ▪ 7edf0baef patch 8.1.1152: compiler warning with VS2019
 ▪ 679beba80 patch 8.1.1151: build fails when using shadow directory
 ▪ 29a9baa07 patch 8.1.1150: generating desktop files not tested on Travis
 ▪ 26096cc96 patch 8.1.1149: building desktop files fails with older msgfmt
 ▪ 730f48fe3 patch 8.1.1148: CTRL-L with 'incsearch' does not pick up char under cursor
 ▪ a60e536a2 patch 8.1.1147: desktop file translations are requiring manual updates
 ▪ ef8c83c55 patch 8.1.1146: in MS-Windows console colors in a terminal window are wrong
 ▪ a7be0f245 patch 8.1.1145: compiler warning for unused function
 ▪ 862f1e17e patch 8.1.1144: too strict checking of the 'spellfile' option
 ▪ 8f130eda4 patch 8.1.1143: may pass weird strings to file name expansion

 ▼ external/wpa_supplicant_8/
 ▪ 36dfa10a Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/external/wpa_supplicant_8 into HEAD

 ▼ frameworks/av/
 ▪ b855638c7d Snap for 5450365 from a24ab5c987af6e14a8e92970630f4ae19091eebd to pi-platform-release
 ▪ 871d171ec3 Merge tag 'android-9.0.0_r37' into pie
 ▪ 13b64c45ee Snap for 5526913 from fd93c075bdb8d5ceb02568df61f372e637cf1c0d to pi-qpr3-b-release
 ▪ e8803d70b7 CameraMetadata: HAX - Fix front cam on Playground
 ▪ f6b0c9c69c Merge cherrypicks of [7077329, 7077440, 7077330, 7077468, 7076852, 7077469, 7077580, 7077581, 7077582, 7074025, 7077706, 7077707, 7077708, 7077388, 7077583, 7077584, 7077585, 7077726, 7077727, 7077331, 7077332, 7077459, 7077709, 7077710, 7077711, 7077712, 7077460, 7077461, 7077333, 7077334, 7077696] into pi-qpr3-release
 ▪ 1aa4d4e7a9 AudioFlinger: Prevent multiple effect chains with same sessionId
 ▪ 6d37377266 audio: ensure effect chain with specific session id is unique
 ▪ f12ed30fc4 NuPlayerCCDecoder: fix memory OOB
 ▪ fd3447b94e Merge cherrypicks of [7070078, 7070079, 7070080, 7070608, 7069857, 7069858, 7069859, 7070136, 7070137, 7070138, 7071045, 7071046, 7071047, 7071048, 7070081, 7070863, 7070082, 7069862, 7069863, 7069864, 7071085, 7070118] into pi-qpr3-b-release
 ▪ 40e32d5e91 AudioFlinger: Prevent multiple effect chains with same sessionId
 ▪ d5f4612112 audio: ensure effect chain with specific session id is unique
 ▪ 992389668e NuPlayerCCDecoder: fix memory OOB
 ▪ f7b0943e0c Snap for 5447620 from b94a3d3e5461e6148bcb3be96f51e51c8f57c7e2 to pi-qpr3-b-release
 ▪ ce478cfc92 Merge cherrypicks of [7068682, 7066360, 7066361, 7066362, 7068985, 7068986, 7068987, 7068800, 7068004] into pi-qpr3-b-release
 ▪ bd3b26b4cb AudioFlinger: Prevent multiple effect chains with same sessionId
 ▪ 7d5e6c32cd audio: ensure effect chain with specific session id is unique
 ▪ 74555ae768 NuPlayerCCDecoder: fix memory OOB
 ▪ bd199b1576 NuPlayerCCDecoder: fix memory OOB
 ▪ b00af62ae4 audio: ensure effect chain with specific session id is unique
 ▪ fd3e7ca28b AudioFlinger: Prevent multiple effect chains with same sessionId
 ▪ fd93c075bd Merge changes from topic "am-f4faa2c1-7416-4076-9f85-b0cd734dba65" into oc-dev am: 58f5458e2e am: 759c3299f0 am: 11de5b4bd6
 ▪ ceb63ffd42 Merge changes from topic "am-99626481-1222-4690-a6c3-4a3db61755f9" into oc-dev am: eedc6cb657 am: d9f8d9181a am: baee23668b
 ▪ 11de5b4bd6 Merge changes from topic "am-f4faa2c1-7416-4076-9f85-b0cd734dba65" into oc-dev am: 58f5458e2e am: 759c3299f0
 ▪ baee23668b Merge changes from topic "am-99626481-1222-4690-a6c3-4a3db61755f9" into oc-dev am: eedc6cb657 am: d9f8d9181a
 ▪ 759c3299f0 Merge changes from topic "am-f4faa2c1-7416-4076-9f85-b0cd734dba65" into oc-dev am: 58f5458e2e
 ▪ d9f8d9181a Merge changes from topic "am-99626481-1222-4690-a6c3-4a3db61755f9" into oc-dev am: eedc6cb657
 ▪ 58f5458e2e Merge changes from topic "am-f4faa2c1-7416-4076-9f85-b0cd734dba65" into oc-dev
 ▪ eedc6cb657 Merge changes from topic "am-99626481-1222-4690-a6c3-4a3db61755f9" into oc-dev

 ▼ frameworks/base/
 ▪ 3f439014233 SystemUI: Fix notification lag
 ▪ 0cc9ce5a059 Fix translation derps
 ▪ 910f16a6dc0 pocket: Allow to listen for fingerprint
 ▪ b67436c217d base: Smart Charging (1/4)
 ▪ fe2631fc0da Android Q text clock Turkish translation
 ▪ a73cdc203b9 Fix Russian translation
 ▪ 9a5735e9237 Fix derp on "Fix screen pinning unlock with hwkeys"
 ▪ af02dafd1d6 carrierlabel & left clock: Properly handle View Visibility
 ▪ 97245b88ba9 Merge tag 'android-9.0.0_r37' into pie
 ▪ 659aa372e4a LiveDisplay: Disable 'Reduce power consumption'
 ▪ a7c822b8166 SystemUI: Set proper color for battery text view
 ▪ 7dd64e2b320 Improvements for swipe to screenshot
 ▪ 974e13d556c Cutout force full screen: Remove fullscreen checks
 ▪ ca7289f032a Android Q text clock Vietnamese translation
 ▪ a615e92e7cb Android Q text clock Russian translation
 ▪ 99c92ab648a Android Q text clock Spanish translation
 ▪ a869526b2ba Android Q text clock Persian translation
 ▪ 61e41cfe3e8 Pocket lock improvements
 ▪ e7a5e359d99 pocket: Don't show immersive mode confirmation when UI showing
 ▪ aacd27da738 pocket: Fix pocket lock view for display cutouts
 ▪ 75571eaabd4 pocket: Adjust sleep timeout for pocket lock view to 10 secs
 ▪ 235de4c4a3e pocket: introduce pocket bridge
 ▪ 368fb959bb1 PocketService: Adjust light sensor rate to 400ms
 ▪ b6ac06ba151 pocket: Add hardware acceleration and properly maintain SYSTEM_UI flags
 ▪ bbc95934c03 policy: introduce pocket lock
 ▪ af68b044876 pocket: introduce pocket judge
 ▪ 6e89a6738b4 Revert "Proximity check on wake"
 ▪ b00b82e02d7 LiveDisplay: Disable by default
 ▪ ae247ab7dde LiveDisplay: don't start services if phone is encrypted
 ▪ c60248eff9e SystemUI: Add reading mode tile
 ▪ bdd50d730a1 SystemUI: Add LiveDisplay tile
 ▪ 43549d33fea Introduce LiveDisplay from Lineage
 ▪ a463a989c1a fwb: [1/2] Implement cutout force full screen
 ▪ 97845224c92 SystemUI: Change NFC icon
 ▪ 09c6c33db25 Logo: fix warnings
 ▪ c1d41563553 SystemUI: Battery icon padding fixes
 ▪ 81c1634e97a SystemUI: Fix percentage issues with Q style battery icon
 ▪ 0cc246b1115 QS: Add advanced location tile options
 ▪ cffcc04eb01 Revert "QS: LocationTile: make it cycle modes"
 ▪ e80875e0733 SystemUI: Enable/fix QS detail view & adapt to Pie
 ▪ bfd7a824c7e Fix inaccurate power algorithm of mobile radio
 ▪ 238e249ba6c Update Korean translation
 ▪ aadf3044824 base: Add Q style to battery icon chooser [1/2]
 ▪ 7d4e27ac0cc fod: dont show FP icons if FOD is in use
 ▪ fc540266709 fod: prevent reapplying modes if theres no changes
 ▪ 15d6f1500e2 fod: differentiate dreaming and pulse
 ▪ aea796be776 Initial support for OnePlus in-display fingerprint sensor
 ▪ a055923aa84 Lockscreen Visualizer: Automatic color based on wallpaper if no album art found
 ▪ 63483fb38d9 Add lockscreen visualizer customization for solid lines [1/2]
 ▪ 7c2cd6a19aa Snap for 5450365 from 2a21bea448c56d892cf7c726771889ff2299f4d5 to pi-platform-release
 ▪ 42dd8b626b9 Merge cherrypicks of [7316389, 7315812, 7315813, 7316457, 7316055, 7315736, 7316390, 7316458, 7316459, 7316460, 7316561, 7316562, 7316563, 7316564, 7316565, 7316566, 7316567, 7316391, 7315814, 7316548] into pi-qpr3-b-release
 ▪ caadc532ae1 Revert "DO NOT MERGE Refactor passwords/pins/patterns to byte[]"
 ▪ 9cb88f8e11f Revert "DO NOT MERGE Make a copy of data stored in LockSettingsStorage cache"
 ▪ e87069a0410 Snap for 5526913 from 0f512b2ebacfa6c3aa51113f1de40d9c44290afc to pi-qpr3-b-release
 ▪ e2b10273607 Merge "Fix ExifInterface for .heic when meta is at the end" into pie-gsi
 ▪ 44d06fdef90 Fix ExifInterface for .heic when meta is at the end
 ▪ da5e6c54e36 fonts: Fix 23d135738da
 ▪ cc623dd0552 SUPL ES Extension - June 2019 rollup
 ▪ 2fd61f1e718 CustomTextClock: Change 'It's' color according to wallpaper
 ▪ 12a39efafd1 CustomTextClock: Code improvements [1/2]
 ▪ e31b34fa0cd Merge cherrypicks of [7077329, 7077440, 7077330, 7077468, 7076852, 7077469, 7077580, 7077581, 7077582, 7074025, 7077706, 7077707, 7077708, 7077388, 7077583, 7077584, 7077585, 7077726, 7077727, 7077331, 7077332, 7077459, 7077709, 7077710, 7077711, 7077712, 7077460, 7077461, 7077333, 7077334, 7077696] into pi-qpr3-release
 ▪ e4061052379 Add cross user permission check - areNotificationsEnabledForPackage
 ▪ dcf3d9f84bb Limit IsSeparateProfileChallengeAllowed to system callers
 ▪ bac376dd409 Added missing permission check to isPackageDeviceAdminOnAnyUser.
 ▪ c5a33f83c66 DO NOT MERGE Atoms: Add BluetoothClassicPairingEvent
 ▪ a06c135e449 CustomTextClock: Use arrays
 ▪ fd0ff339776 CustomTextClock: Match Android Q
 ▪ cf2388ca83b CustomTextClock: Make clock strings translatable
 ▪ 917deddd550 CustomTextClock: Improve UI and optimisations
 ▪ 7838d517db9 Lockscreen Clock Styles: Introduce Q style text clock A gist of what happened: - Use a custom TextView to achieve the text - Use Rounded Elegance font cuz why not - Use a attribute to differenciate between hour hand and minute hand - Use a retarded yet simple method to get Strings for given integer - Set text according to system time format (12h/24h) - Set a top margin to push the lockscreen date (Unuglify) - Set a left padding for clock layout (Might need to be overlayed for some devices)
 ▪ 4f8486a2946 Use proper context for prevent ringing gesture toast
 ▪ 3bfb3cfc346 Merge cherrypicks of [7070078, 7070079, 7070080, 7070608, 7069857, 7069858, 7069859, 7070136, 7070137, 7070138, 7071045, 7071046, 7071047, 7071048, 7070081, 7070863, 7070082, 7069862, 7069863, 7069864, 7071085, 7070118] into pi-qpr3-b-release
 ▪ 9162b8635bb Add cross user permission check - areNotificationsEnabledForPackage
 ▪ 0fc5dbf3d1d Limit IsSeparateProfileChallengeAllowed to system callers
 ▪ 1d1faf36c7e Added missing permission check to isPackageDeviceAdminOnAnyUser.
 ▪ f783a68c02f Snap for 5447620 from 5b09928b2273cff78f64673e0ac8459ffe0f16bc to pi-qpr3-b-release
 ▪ ecd88adca0a Merge cherrypicks of [7068682, 7066360, 7066361, 7066362, 7068985, 7068986, 7068987, 7068800, 7068004] into pi-qpr3-b-release
 ▪ 1dfce98d9dc Add cross user permission check - areNotificationsEnabledForPackage
 ▪ d7008c0ba38 Limit IsSeparateProfileChallengeAllowed to system callers
 ▪ c7c26cc8e9c Added missing permission check to isPackageDeviceAdminOnAnyUser.
 ▪ 29315b575cf Add cross user permission check - areNotificationsEnabledForPackage
 ▪ fcbaf8a5160 Limit IsSeparateProfileChallengeAllowed to system callers
 ▪ 6ffe579a405 Added missing permission check to isPackageDeviceAdminOnAnyUser.
 ▪ 03c319e3407 DO NOT MERGE Atoms: Add BluetoothClassicPairingEvent
 ▪ ffb19a13d2d Lockscreen Visualizer: Add pulse magic [1/2]
 ▪ cec6977aa29 base: Lockscreen visualizer cleanup
 ▪ f9899f7ecae The surface hang up when screen on and screen off
 ▪ 425cf286855 backup: right way to check canonical file path
 ▪ 0bb832efa9a Fixes crash/race condition when destroyActivity
 ▪ 5ccf241d74f Fixed setting incorrect mode of vibration
 ▪ 0f512b2ebac [automerger skipped] Merge changes from topic "am-09249f80-e618-46fc-ac06-c7fdc73c36ae" into oc-dev am: 07a485743a am: 30826bd658 am: d89cac1562 -s ours am skip reason: change_id I8ee3f876fcaffa63636645f0f59709cd147254ef with SHA1 5ab98de315 is in history
 ▪ 9456d1e079d Merge "[RESTRICT_AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage" into oc-dev am: 2256fd4e11 am: 51fee974a9 am: 19ad060bf0
 ▪ 00f5cf45c7d Merge changes from topic "am-3ca7326a-cbf1-4f97-a1b5-a4fdfac0fb47" into oc-dev am: 652a666500 am: 5d35ad7446 am: 03cddd8562
 ▪ cbffcf9c24d [automerger skipped] [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b am: 39f5432697 am: 9c0bc5405e am: 55209aca88 am: d5ce9a41b6 am: 20007cb46f am: 3ae9c5c63b -s ours am: 8a317effc2 -s ours am skip reason: change_id I2fef9ab13614627c0f1bcca04759d0974fc6181a with SHA1 1b6301cf24 is in history
 ▪ d89cac1562e Merge changes from topic "am-09249f80-e618-46fc-ac06-c7fdc73c36ae" into oc-dev am: 07a485743a am: 30826bd658
 ▪ 19ad060bf0f Merge "[RESTRICT_AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage" into oc-dev am: 2256fd4e11 am: 51fee974a9
 ▪ 03cddd85629 Merge changes from topic "am-3ca7326a-cbf1-4f97-a1b5-a4fdfac0fb47" into oc-dev am: 652a666500 am: 5d35ad7446
 ▪ 30826bd6587 Merge changes from topic "am-09249f80-e618-46fc-ac06-c7fdc73c36ae" into oc-dev am: 07a485743a
 ▪ 8a317effc2d [automerger skipped] [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b am: 39f5432697 am: 9c0bc5405e am: 55209aca88 am: d5ce9a41b6 am: 20007cb46f am: 3ae9c5c63b -s ours am skip reason: change_id I2fef9ab13614627c0f1bcca04759d0974fc6181a with SHA1 1b6301cf24 is in history
 ▪ 51fee974a96 Merge "[RESTRICT_AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage" into oc-dev am: 2256fd4e11
 ▪ 5d35ad74469 Merge changes from topic "am-3ca7326a-cbf1-4f97-a1b5-a4fdfac0fb47" into oc-dev am: 652a666500
 ▪ 3ae9c5c63b1 [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b am: 39f5432697 am: 9c0bc5405e am: 55209aca88 am: d5ce9a41b6 am: 20007cb46f
 ▪ 07a485743ad Merge changes from topic "am-09249f80-e618-46fc-ac06-c7fdc73c36ae" into oc-dev
 ▪ 2256fd4e111 Merge "[RESTRICT_AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage" into oc-dev
 ▪ e4c6ce23af5 Merge "Add cross user permission check - areNotificationsEnabledForPackage" into pi-dev
 ▪ 652a6665001 Merge changes from topic "am-3ca7326a-cbf1-4f97-a1b5-a4fdfac0fb47" into oc-dev
 ▪ 46ec3c4d04e base: Add overlay for BoostFramework
 ▪ 406229f0c84 Limit IsSeparateProfileChallengeAllowed to system callers am: 1b6301cf24
 ▪ 63846a7093c Add cross user permission check - areNotificationsEnabledForPackage

 ▼ frameworks/native/
 ▪ 9e7f3806d Snap for 5450365 from 94c1d740cfe001e5faf62d3c447c4e1e9f4aa325 to pi-platform-release
 ▪ eaaf1f29c Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/frameworks/native into pie
 ▪ 116e3cc8f Snap for 5526913 from d637081295eabcf20cea0ecd2dff1b2444b8e8ca to pi-qpr3-b-release
 ▪ d63708129 Merge "TimeStats: fix a racing case" into pi-dev
 ▪ 64773ea2a Merge a259a78f7280fe8f7d23a94f213dade4df3eaf74 on remote branch
 ▪ c8288466d Snap for 5505623 from 3a557a6ab6824a3216fddb5a8c34819ad8dfcde9 to p-keystone-qcom-release
 ▪ 3a557a6ab sf: Trigger resync instantaneously on fps change.
 ▪ 6b495a186 Merge a259a78f7280fe8f7d23a94f213dade4df3eaf74 on remote branch
 ▪ a5da6fe76 TimeStats: fix a racing case
 ▪ ee7a9ca85 [RESTRICT AUTOMERGE] libvulkan: drop the advertised swapchain spec version to 68

 ▼ frameworks/opt/net/wifi/
 ▪ b6fe3c4de Merge tag 'android-9.0.0_r37' into pie
 ▪ 9b235c995 Merge 0bf07df3a5a5defe31a427d7d817ca3ae1123ef4 on remote branch
 ▪ f0a226d67 Snap for 5526913 from f88d296d36abd371ef11d074bbb95e47f04e8ed0 to pi-qpr3-b-release
 ▪ ab619c380 Snap for 5521471 from c70812e91531703856bfddf46f3062d777cb6f84 to p-keystone-qcom-release
 ▪ e0e91e691 Merge 0bf07df3a5a5defe31a427d7d817ca3ae1123ef4 on remote branch
 ▪ b37be9bb7 Merge 39bba6a4622022cbfeeb79290668a797574ce75c on remote branch
 ▪ ab4c3e6cf wifi: Indicate AUTH_FAILURE for WEP password error
 ▪ c70812e91 wifi: Fix reconnect sequence on IP change.
 ▪ 0bf07df3a Snap for 5466560 from 3af0b54154b1a9c88aa104f71fc9732a768c74c5 to p-keystone-qcom-release
 ▪ 3af0b5415 Merge "wifi: Handle wifi ON state while processing CMD_DELAY_DISCONNECT." into p-keystone-qcom

 ▼ frameworks/opt/telephony/
 ▪ 5ba0dc8ea1 Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/frameworks/opt/telephony into caf
 ▪ 7d9ab97d8e Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into caf
 ▪ 35dfc2b380 Snap for 5450365 from 4ea0190392fe4d8c18c9c9c3599c9a68cdd67e59 to pi-platform-release
 ▪ 9fe0ed2bdc Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/frameworks/opt/telephony into caf
 ▪ 4aba93480b Merge 1bfb72160d19e552143e8da01ab176edc1fe4683 on remote branch
 ▪ cd219177c4 Merge 1bfb72160d19e552143e8da01ab176edc1fe4683 on remote branch
 ▪ dfb1a228d9 Merge 1bfb72160d19e552143e8da01ab176edc1fe4683 on remote branch
 ▪ 72c54cc474 Snap for 5470778 from 049b7fe356abb855e9364f83a850a35174c4c211 to p-keystone-qcom-release
 ▪ 2e2180ccd8 Merge tag 'LA.UM.7.4.r1-05000-8x98.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into caf
 ▪ 049b7fe356 MSIM: Fix data call issue on powerup

 ▼ hardware/broadcom/wlan/
 ▪ df369a1 Snap for 5450365 from f632b64f225162de0c7e8dee5953d44bbfcf353f to pi-platform-release
 ▪ b6cf251 Merge tag 'android-9.0.0_r37' into staging/lineage-16.0_merge-android-9.0.0_r37

 ▼ hardware/interfaces/
 ▪ aa3fea9ef Merge tag 'LA.UM.7.5.r1-04800-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 8af0151aa Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/hardware/interfaces into 9.0
 ▪ 1d3a299fe Snap for 5450365 from b18f050a4e354e817cec1d01a4b30a98bbb158e5 to pi-platform-release
 ▪ f9dcbc2bc Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 4c758f82d Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/hardware/interfaces into 9.0
 ▪ 3ffa6e19f Merge c0b45346f4343dfd416c8a72af3c697c93aad81e on remote branch
 ▪ b095226d9 Snap for 5526913 from 480839576729af028dee8128fe18b185c51238e1 to pi-qpr3-b-release
 ▪ 4696b5874 Merge c0b45346f4343dfd416c8a72af3c697c93aad81e on remote branch
 ▪ 480839576 Fix VtsHalWifiV1_0Host#WifiStaIfaceHidlTest.SetScanningMacOui fail am: eb73bff276
 ▪ 836c33d38 Merge c0b45346f4343dfd416c8a72af3c697c93aad81e on remote branch
 ▪ 73670a84d Wifi: Syncronization on reading and writing ringbuffer
 ▪ eb73bff27 Fix VtsHalWifiV1_0Host#WifiStaIfaceHidlTest.SetScanningMacOui fail
 ▪ c0b45346f Snap for 5454658 from 648c163f7f9b350793d01f9c4534ea0f8b9746fd to p-keystone-qcom-release
 ▪ d9a9f6bb5 Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

 ▼ hardware/nxp/nfc/
 ▪ 64337a6 Snap for 5450365 from 210180d4eb8971f74aa17d1677e97a342c29c7b1 to pi-platform-release
 ▪ 0aa8b67 Merge tag 'android-9.0.0_r37' into pie

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ cb1865e1 Merge tag 'LA.UM.7.5.r1-04800-8x96.0' into 9.0
 ▪ 4441a1a7 Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' into 9.0
 ▪ 6fe6bb24 hal: Fix no audio during voice call with concurrent combo use case
 ▪ 9209b412 Merge 8a314f777c2d599988e457512a8bffe530db3a52 on remote branch
 ▪ b4bf2231 Merge e9a97f4e2f34a0a653feb86536b2c049168fd773 on remote branch
 ▪ 8a314f77 Merge "configs: sdm710: Enable feature flag for APTX decoder"
 ▪ d5d09965 Merge "hal: Add changes to send pspd coefficients during out_write"
 ▪ b3a38e0e Merge "configs: Remove Dolby formats by default."
 ▪ 557b56c1 Merge e9a97f4e2f34a0a653feb86536b2c049168fd773 on remote branch
 ▪ e9a97f4e Merge "Revert "hal: fix no sound issue when using some USB headset.""
 ▪ af91fb96 Merge "configs: sdm660: Add support for suspend mixer ctls"
 ▪ 0b30f6a1 Merge ce1be84e0da375df8bb04739ca0bbd8eed0bf625 on remote branch
 ▪ d6f23b6a Revert "hal: fix no sound issue when using some USB headset."
 ▪ 73f5d966 Merge "hal: Backend port specific channel mapping for afe-loopback"
 ▪ 988a66d8 hal: Add changes to send pspd coefficients during out_write
 ▪ b2f1bd91 vndk fixes
 ▪ 16dd1be0 configs: sdm710: Enable feature flag for APTX decoder
 ▪ ce1be84e Merge "hal: Increase ffv process thread priority"
 ▪ 05d2b62f Merge "hal: Add support for Backend port specific channel map"
 ▪ 3272ed5d configs: Remove Dolby formats by default.
 ▪ a8106a40 configs: sdm660: Add support for suspend mixer ctls
 ▪ fb122f75 hal: Update in_snd_device for USB headphone device use cases
 ▪ fc67a9a7 hal: Backend port specific channel mapping for afe-loopback
 ▪ 2e039564 hal: Add support for Backend port specific channel map
 ▪ 39c10a98 hal: Fix incall recording calibration issue

 ▼ hardware/qcom/bt-caf/
 ▪ f22bc5a Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' into 9.0
 ▪ 1689fc9 Merge 9573899be2ff2b9d387d549608feea0617e26dec on remote branch
 ▪ 1f6031e Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into 9.0

 ▼ hardware/qcom/data/ipacfg-mgr/
 ▪ 2e3ed98 msm8998: ipanat: Add missing kernel header dep

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ 049b98c6 sdm: Fix display resolution change in destination scaler.
 ▪ 16aec782 Merge 21177de14753fe774a58bf5cb085c32bdb5be314 on remote branch
 ▪ 3d3e6654 sdm: Add support to turn on/off destination scalar using property
 ▪ 64c330e8 sdm: Define error type for critical resource allocation failure
 ▪ 6c40a33a sdm: Add support for destination scaler.
 ▪ 40c3c865 Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into 9.0

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 96267d59 Merge 9e0d0b25225e7a717df78462702a518fdd46f7da on remote branch
 ▪ 9e0d0b25 venc: Fix the size for EOS buffer

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 1876ce7e4 Merge 9e0d0b25225e7a717df78462702a518fdd46f7da on remote branch
 ▪ 5f98a2e3a Merge 9e0d0b25225e7a717df78462702a518fdd46f7da on remote branch
 ▪ 9e0d0b252 venc: Fix the size for EOS buffer

 ▼ hardware/qcom/wlan-caf/
 ▪ 67f676a Merge tag 'LA.UM.7.5.r1-04800-8x96.0' into 9.0
 ▪ 5d816fb Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' into 9.0
 ▪ 0c123ec Merge f6ca612d4abac4d3dcab6e9e421435e092cde4e6 on remote branch
 ▪ deaea4b Merge 63772381d128474323de8e66a11ca68b6f61f76a on remote branch
 ▪ c0d0e62 wpa_supplicant_8_lib: Add support for LE platform
 ▪ d01f5d1 Merge f6ca612d4abac4d3dcab6e9e421435e092cde4e6 on remote branch
 ▪ f6ca612 WiFi-Hal: Free struct nl_cb to address memory leak
 ▪ ca57c36 Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into 9.0

 ▼ hardware/ril/
 ▪ 9ab43fab Merge f342b3f55ebae0001df727a40c5c87f298128201 on remote branch

 ▼ kernel/xiaomi/msm8996/
 ▪ 2459157e2f98 Merge "diag: Validate command length against size of command structure"
 ▪ 82fa25f67a9d Merge "msm: ais: handle the error value returned during get clock"
 ▪ 945cdbe49fe6 Merge "msm: camera_v2: handle the error value returned during get clock"
 ▪ 4d60efb6e4ac diag: Validate command length against size of command structure
 ▪ d66285241a6a msm: ais: handle the error value returned during get clock
 ▪ fa3003ae2667 msm: camera_v2: handle the error value returned during get clock
 ▪ 93677967d14c Merge tag 'LA.UM.7.5.r1-04800-8x96.0' into kernel.lnx.3.18.r34-rel
 ▪ b77565dd733f Merge "msm: sps: Update debug message format specifier"
 ▪ 5cb939465a88 Merge tag 'LA.UM.7.5.r1-04800-8x96.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into 9.0
 ▪ b05dcc96ee1f Merge "msm: qdsp6v2: Check size of payload before access"
 ▪ b88c7e762451 msm: sps: Update debug message format specifier
 ▪ 26b87cfd68a1 diag: dci: Validate dci response length before parsing
 ▪ 5423a8abdd77 Merge "soc: qcom: Bail out when number of clusters is set to 0"
 ▪ 1ca283b1b270 soc: qcom: Bail out when number of clusters is set to 0
 ▪ 7c7b3d3ca377 msm: mdss: Ignore overflow errors in dma_tpg_tx path
 ▪ fc277a9e434d Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 07e306dabafc Merge "qcacld-2.0: Fix OOB read in sme_RrmProcessBeaconReportReqInd" into wlan-cld2.driver.lnx.1.0
 ▪ 543cf1e8d40c update captouch driver & capricorn defconfig
 ▪ 02c15cc81ba0 lsm: check payload size validity before using it as array index
 ▪ 2c38e20677eb qcacld-2.0: Add ppdu tx stats
 ▪ b978d59d194b Merge branch 'kernel.lnx.3.18.r34-rel' of https://github.com/android-linux-stable/msm-3.18 into 9.0
 ▪ 982931088d00 qcacld-2.0: Propagate fw PPDU stats APIs
 ▪ b81d814d8e5f qcacld-2.0: Fix OOB read in sme_RrmProcessBeaconReportReqInd
 ▪ 7e363b255da4 Merge 3.18.139 into kernel.lnx.3.18.r34-rel
 ▪ dc3e913edf94 Linux 3.18.139
 ▪ 55383294bf60 kernel/sysctl.c: fix out-of-bounds access when setting file-max
 ▪ 6d3eb3b2333f arm64: futex: Restore oldval initialization to work around buggy compilers
 ▪ 73d117dcbb1d device_cgroup: fix RCU imbalance in error case
 ▪ bd860d65dff1 sched/fair: Limit sched_cfs_period_timer() loop to avoid hard lockup
 ▪ 89c254ec3365 kprobes: Fix error check when reusing optimized probes
 ▪ 71dc273de2d2 x86/kprobes: Verify stack frame on kretprobe
 ▪ 8ad4179e47f7 ALSA: core: Fix card races between register and disconnect
 ▪ 38b45533b64f staging: comedi: ni_usb6501: Fix possible double-free of ->usb_rx_buf
 ▪ 911176ad4df2 staging: comedi: vmk80xx: Fix possible double-free of ->usb_rx_buf
 ▪ afb7cd602189 staging: comedi: vmk80xx: Fix use of uninitialized semaphore
 ▪ fd10344b7c0a iio: adc: at91: disable adc channel interrupt in timeout case
 ▪ 9d4f298b95e4 iio: ad_sigma_delta: select channel when reading register
 ▪ 55b4957dcc74 tcp: tcp_grow_window() needs to respect tcp_space()
 ▪ f769967110b6 ipv4: ensure rcu_read_lock() in ipv4_link_failure()
 ▪ 6c2fa855d817 ipv4: recompile ip options in ipv4_link_failure
 ▪ c63dcecbc234 net: bridge: multicast: use rcu to access port list from br_multicast_start_querier
 ▪ dd70ca6724cb bonding: fix event handling for stacked bonds
 ▪ 0e6fdf586a39 tpm/tpm_i2c_atmel: Return -E2BIG when the transfer is incomplete
 ▪ f777415bb945 crypto: crypto4xx - properly set IV after de- and encrypt
 ▪ 27c72725a63a appletalk: Fix compile regression
 ▪ 55f0fc7a02de inet: update the IP ID generation algorithm to higher standards.
 ▪ 8620392634e7 include/linux/swap.h: use offsetof() instead of custom __swapoffset macro
 ▪ 08e137dc700e lib/div64.c: off by one in shift
 ▪ ab885986b630 appletalk: Fix use-after-free in atalk_proc_exit
 ▪ 88f8bbd24dfe iommu/dmar: Fix buffer overflow during PCI bus notification
 ▪ 51758f1b9ec7 ACPI / SBS: Fix GPE storm on recent MacBookPro's
 ▪ 6a701889a8f9 ARM: samsung: Limit SAMSUNG_PM_CHECK config option to non-Exynos platforms
 ▪ e8672b3c8690 serial: uartps: console_setup() can't be placed to init section
 ▪ ee6acb13285b 9p locks: add mount option for lock retry interval
 ▪ db8207b7ac30 9p: do not trust pdu content for stat item size
 ▪ d8f70ad66032 rsi: improve kernel thread handling to fix kernel panic
 ▪ 15863a0dfa9d fix incorrect error code mapping for OBJECTID_NOT_FOUND
 ▪ 13ad4729e686 iommu/vt-d: Check capability before disabling protected memory
 ▪ d7201786ea98 x86/cpu/cyrix: Use correct macros for Cyrix calls on Geode processors
 ▪ f57149631d43 x86/hpet: Prevent potential NULL pointer dereference
 ▪ 72cee3afd885 perf tests: Fix a memory leak in test__perf_evsel__tp_sched_test()
 ▪ 43eaf0403422 perf top: Fix error handling in cmd_top()
 ▪ 742007f6898a tools/power turbostat: return the exit status of a command
 ▪ b91640967bb4 thermal/int340x_thermal: fix mode setting
 ▪ 80d182c2af80 ALSA: opl3: fix mismatch between snd_opl3_drum_switch definition and declaration
 ▪ 55a440ee396e mmc: davinci: remove extraneous __init annotation
 ▪ 24d4c2b9ce12 IB/mlx4: Fix race condition between catas error reset and aliasguid flows
 ▪ e3de185c7f2f ALSA: sb8: add a check for request_region
 ▪ 77eed592753f ALSA: echoaudio: add a check for ioremap_nocache
 ▪ 006aaba6a666 ext4: report real fs size after failed resize
 ▪ d251e36ed70e perf/core: Restore mmap record type correctly
 ▪ 3107d24b7bb8 string: drop __must_check from strscpy() and restore strscpy() usages in cgroup
 ▪ ef04853210b0 PCI: Add function 1 DMA alias quirk for Marvell 9170 SATA controller
 ▪ 7073b8698e38 xtensa: fix return_address
 ▪ b6c4c3e7d303 sched/fair: Do not re-read ->h_load_next during hierarchical load calculation
 ▪ cfa402909d9c xen: Prevent buffer overflow in privcmd ioctl
 ▪ ab6ce574b2c9 arm64: futex: Fix FUTEX_WAKE_OP atomic ops with non-zero result value
 ▪ fa3ce990acc9 block: do not leak memory in bio_copy_user_iov()
 ▪ 6040571bec16 ASoC: fsl_esai: fix channel swap issue when stream starts
 ▪ 96d59a75b37b ALSA: seq: Fix OOB-reads from strlcpy
 ▪ eab63566720f ip6_tunnel: Match to ARPHRD_TUNNEL6 for dev type
 ▪ c20f5d00dc42 net: ethtool: not call vzalloc for zero sized memory request
 ▪ c2bca92ba948 netns: provide pure entropy for net_hash_mix()
 ▪ 01418a991494 sctp: initialize _pad of sockaddr_in before copying to user memory
 ▪ 41805942734c qmi_wwan: add Olicard 600
 ▪ ad4895026b43 openvswitch: fix flow actions reallocation
 ▪ 4d8a182051ba tty: ldisc: add sysctl to prevent autoloading of ldiscs
 ▪ 20d4e7627b14 tty: mark Siemens R3964 line discipline as BROKEN
 ▪ 8a34ae9b87f0 lib/string.c: implement a basic bcmp
 ▪ 119b8e38491b binfmt_elf: switch to new creds when switching to new mm
 ▪ 33016f5f792b drm/dp/mst: Configure no_stop_bit correctly for remote i2c xfers
 ▪ 76b3afa0fdfa dmaengine: tegra: avoid overflow of byte tracking
 ▪ 1ce302656f6a x86/build: Mark per-CPU symbols as absolute explicitly for LLD
 ▪ 4e740644056d wlcore: Fix memory leak in case wl12xx_fetch_firmware failure
 ▪ 9a8fb4d20d09 media: s5p-jpeg: Check for fmt_ver_flag when doing fmt enumeration
 ▪ 90fa452d6e8b dmaengine: imx-dma: fix warning comparison of distinct pointer types
 ▪ 57e5f1a70465 hpet: Fix missing '=' character in the __setup() code of hpet_mmap_enable
 ▪ d55c5d7c8874 hwrng: virtio - Avoid repeated init of completion
 ▪ efb2fec63a93 media: mt9m111: set initial frame size other than 0x0
 ▪ becaaec31075 tty: increase the default flip buffer limit to 2*640K
 ▪ f21094c240a3 cdrom: Fix race condition in cdrom_sysctl_register
 ▪ 2f8782c2a147 fbdev: fbmem: fix memory access if logo is bigger than the screen
 ▪ 956f1121b7a0 bcache: improve sysfs_strtoul_clamp()
 ▪ 8d10e79327e6 bcache: fix input overflow to sequential_cutoff
 ▪ 794d02435dca bcache: fix input overflow to cache set sysfs file io_error_halflife
 ▪ 674bb02c0fdf ALSA: PCM: check if ops are defined before suspending PCM
 ▪ bbe1b801e389 ARM: 8833/1: Ensure that NEON code always compiles with Clang
 ▪ 9bac786e36ab kprobes: Prohibit probing on bsearch()
 ▪ 3c81153bc6da leds: lp55xx: fix null deref on firmware load failure
 ▪ 51cc117b7b0c SoC: imx-sgtl5000: add missing put_device()
 ▪ 9670c4d542aa scsi: megaraid_sas: return error when create DMA pool failed
 ▪ e63fbce08bb9 IB/mlx4: Increase the timeout for CM cache
 ▪ 2edeb33e013c e1000e: Fix -Wformat-truncation warnings
 ▪ 3d2d028d77f6 mmc: omap: fix the maximum timeout setting
 ▪ 61c4d9023651 ARM: 8840/1: use a raw_spinlock_t in unwind
 ▪ c63d19680793 scsi: core: replace GFP_ATOMIC with GFP_KERNEL in scsi_scan.c
 ▪ e70758e06ee2 tools lib traceevent: Fix buffer overflow in arg_eval
 ▪ 43c51c42cdce fs: fix guard_bio_eod to check for real EOD errors
 ▪ 5213ffd0b6fc cifs: Fix NULL pointer dereference of devname
 ▪ 03bb19bec59c dm thin: add sanity checks to thin-pool and external snapshot creation
 ▪ 712516d97ee0 cifs: use correct format characters
 ▪ 281b1be2c691 ocfs2: fix a panic problem caused by o2cb_ctl
 ▪ c090f4c8a0d9 mm/slab.c: kmemleak no scan alien caches
 ▪ 9dc553ad1d67 mm/vmalloc.c: fix kernel BUG at mm/vmalloc.c:512!
 ▪ d87d326145ef mm/cma.c: cma_declare_contiguous: correct err handling
 ▪ c882239931a9 sysctl: handle overflow for file-max
 ▪ 33da87e946be tracing: kdb: Fix ftdump to not sleep
 ▪ e045c806436d i2c: core-smbus: prevent stack corruption on read I2C_BLOCK_DATA
 ▪ 1084676c5849 ext4: cleanup bh release code in ext4_ind_remove_space()
 ▪ 9d1b71028c14 Merge e1134fc9b3c44ef8cc4ad8025bf3f25a48d9bb3a on remote branch
 ▪ 5f976a45538a qcacld-2.0: Enable CONFIG_WLAN_FEATURE_SAE by default
 ▪ 49935dba3fa5 scripts: update mkcompile_h
 ▪ ff3b743d8f8a fix build with gcc
 ▪ 772bb3d029e9 Merge "qcacld-2.0: Clear up DFS rules for multiple interfaces" into wlan-cld2.driver.lnx.1.0
 ▪ 27fb182943e6 dsp: q6core: validate payload size before memory copy
 ▪ 91fa1989060f qcacld-2.0: Add RX stats indication to SA
 ▪ 11fdab25545b Merge "qcacld-2.0: Fix buffer overflow in process_rx_info etc" into wlan-cld2.driver.lnx.1.0
 ▪ ba8e69b06e11 Merge "lsm: check payload size validity before using it as array index"
 ▪ a6a524ff1b08 Merge "diag: dci: Validate dci client entries prior read"
 ▪ 01f644635fea Merge "qcacld-2.0: Define CONFIG_VOS_MEM_PRE_ALLOC" into wlan-cld2.driver.lnx.1.0
 ▪ c51d168896b3 Merge db2e29267dc9a93d36ccd873782617bf4822d2fd on remote branch
 ▪ 6228788154ba Merge "qcacld-2.0: Add WMI_COEX_CONFIG_BTC_DUTYCYCLE" into wlan-cld2.driver.lnx.1.0
 ▪ adf709fa2986 Merge 3ad2b2b803592916ef0d254ded94ed9c70f07cb6 on remote branch
 ▪ 1b8e1b605696 Merge "qcacld-2.0: Add iwpriv command to support TDCC" into wlan-cld2.driver.lnx.1.0
 ▪ 663840517a08 Merge "qcacld-2.0: Enable survey dump on SAP" into wlan-cld2.driver.lnx.1.0
 ▪ 471aab5f7127 lsm: check payload size validity before using it as array index
 ▪ 7f7640a37d76 msm: qdsp6v2: Check size of payload before access
 ▪ 55c1e3b18be8 qcacld-2.0: Define CONFIG_VOS_MEM_PRE_ALLOC
 ▪ c1bcb10778af msm: kgsl: Only wake GPU upon ioctl receipt when it isn't awake
 ▪ b54aa50716bd Initialize ata before graphics
 ▪ dba0dd729485 msm: pcie: Mark MSI cascade ISR as IRQF_NO_THREAD
 ▪ cf94e2fc2fdc cpufreq: schedutil: Fix error path mutex unlock
 ▪ 07cbb7292c68 Merge "qcacld-2.0: Add primary peer setting for MAC counter" into wlan-cld2.driver.lnx.1.0
 ▪ 317a6bd0d355 qcacld-2.0: Clear up DFS rules for multiple interfaces
 ▪ fa7f094c3541 qcacld-2.0: Add WMI_COEX_CONFIG_BTC_DUTYCYCLE
 ▪ d345688de3f7 defconfig: disable more debugging configs
 ▪ 3ad2b2b80359 Merge "msm: kgsl: Limit log frequency in case of context count maxed out"
 ▪ 80fcf84f41fb qcacld-2.0: Add iwpriv command to support TDCC
 ▪ 93c18a45068d qcacld-2.0: Add primary peer setting for MAC counter
 ▪ 1c783f10e0ab qcacld-2.0: Add interference stats for smart antenna
 ▪ e1134fc9b3c4 Merge "qcacld-2.0: Update PMK cache and fix SAE PMK Cache Auth failure" into wlan-cld2.driver.lnx.1.0
 ▪ 9cdd40e95b92 qcacld-2.0: Update PMK cache and fix SAE PMK Cache Auth failure
 ▪ 87cb45fe5b07 Merge "qcacld-2.0: Add coverity change" into wlan-cld2.driver.lnx.1.0
 ▪ f2aa245a1582 qcacld-2.0: Add coverity change
 ▪ 51fd4c2bbb2c qcacld-2.0: CL 6712641-6856758 - Update fw common interface files
 ▪ a24febdc19a2 ASoC: msm: Modify buf size check to prevent OOB error
 ▪ 6cd6926f7c0b qcacld-2.0: CL 6565901-6699888 - Update fw common interface files
 ▪ 73ebbac158f6 qcacld-2.0: CL 6535788 - Update fw common interface files
 ▪ f10f0702c861 qcacld-2.0: CL 6529657 - Update fw common interface files
 ▪ 25e73b692539 qcacld-2.0: CL 6521585 - Update fw common interface files
 ▪ ec56e9c1b01d qcacld-2.0: CL 6467333 - Update fw common interface files
 ▪ 2cfa8556c3a0 qcacld-2.0: CL 6460094 - Update fw common interface files
 ▪ 04442e30b854 qcacld-2.0: CL 6443430 - Update fw common interface files
 ▪ 0263cba29b42 qcacld-2.0: CL 6438294 - Update fw common interface files
 ▪ 48a705b7a7a3 qcacld-2.0: CL 6432735 - Update fw common interface files
 ▪ 798a60e83f3a qcacld-2.0: CL 6418415 - Update fw common interface files
 ▪ 21583324e38d qcacld-2.0: CL 6413865 - Update fw common interface files
 ▪ 101e80bdd838 Merge "qcacld-2.0: CSA optimization for bandwidth switch" into wlan-cld2.driver.lnx.1.0
 ▪ ebfd59fecc7a Merge "qcacld-2.0: Possible OOB access in wlan_hdd_cfg80211_start_bss()" into wlan-cld2.driver.lnx.1.0
 ▪ 38c629721c16 Merge "qcacld-2.0: Fix incorrect challenge text length" into wlan-cld2.driver.lnx.1.0
 ▪ 77ec26e06654 Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into HEAD

 ▼ packages/apps/Bluetooth/
 ▪ d148dc56 Merge tag 'android-9.0.0_r37' into pie
 ▪ 80be8843 Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/apps/Bluetooth into HEAD
 ▪ b457a290 Merge cherrypicks of [7316389, 7315812, 7315813, 7316457, 7316055, 7315736, 7316390, 7316458, 7316459, 7316460, 7316561, 7316562, 7316563, 7316564, 7316565, 7316566, 7316567, 7316391, 7315814, 7316548] into pi-qpr3-b-release
 ▪ 70e92152 DO NOT MERGE Revert "BondStateMachine: Check for null before calling getDeviceType"
 ▪ 6521057e Snap for 5526913 from bc628e96249b2cfc38015b97d7d8e12afc37da1d to pi-qpr3-b-release
 ▪ bc628e96 [automerger skipped] [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313 am: 32fb537700 am: 5039e3df88 am: dfca097027 skipped: 01143285bf am: 6dd7bb0e75 am: 527fc68bc6 am: 7ef7414f96 -s ours am skip reason: subject contains skip directive
 ▪ 7ef7414f [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313 am: 32fb537700 am: 5039e3df88 am: dfca097027 skipped: 01143285bf am: 6dd7bb0e75 am: 527fc68bc6
 ▪ 527fc68b [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313 am: 32fb537700 am: 5039e3df88 am: dfca097027 skipped: 01143285bf am: 6dd7bb0e75
 ▪ 6dd7bb0e [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313 am: 32fb537700 am: 5039e3df88 am: dfca097027 skipped: 01143285bf
 ▪ 01143285 [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313 am: 32fb537700 am: 5039e3df88 am: dfca097027
 ▪ dfca0970 [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313 am: 32fb537700 am: 5039e3df88
 ▪ 5039e3df [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313 am: 32fb537700
 ▪ 32fb5377 [automerger] Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" am: 903b0f6313
 ▪ 903b0f63 Revert "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType"
 ▪ 907cc115 Fix leak of registerReceiver
 ▪ eb1429ed HID: Fix the potential NPE in HidHostService jni callback
 ▪ be8789d0 Fix setting of BLE scan parameters
 ▪ a7176001 Add BLE Scan Phy parameter to scan API
 ▪ 76b2d12d Support to startScan with DELIVERY_MODE_ROUTE
 ▪ 5ce14b60 Merge cherrypicks of [7070078, 7070079, 7070080, 7070608, 7069857, 7069858, 7069859, 7070136, 7070137, 7070138, 7071045, 7071046, 7071047, 7071048, 7070081, 7070863, 7070082, 7069862, 7069863, 7069864, 7071085, 7070118] into pi-qpr3-b-release
 ▪ ffd80d67 BondStateMachine: Check for null before calling getDeviceType
 ▪ da86064e Snap for 5447620 from ac82b0cdc0ab96ac0dbc8b67287718ae7c4e73a5 to pi-qpr3-b-release
 ▪ 3ddbb5b0 Merge cherrypicks of [7068682, 7066360, 7066361, 7066362, 7068985, 7068986, 7068987, 7068800, 7068004] into pi-qpr3-b-release
 ▪ 71117c99 BondStateMachine: Check for null before calling getDeviceType
 ▪ 7dc18468 [automerger skipped] Merge "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" into oc-dev am: 8e45731c05 -s ours am: 5b78550b20 -s ours am: bf6a7c0652 -s ours am skip reason: subject contains skip directive
 ▪ bf6a7c06 [automerger skipped] Merge "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" into oc-dev am: 8e45731c05 -s ours am: 5b78550b20 -s ours am skip reason: change_id I711e08b076adb7b4808d04a47cb067cb95606f96 with SHA1 39cda2a286 is in history
 ▪ 5b78550b [automerger skipped] Merge "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" into oc-dev am: 8e45731c05 -s ours am skip reason: change_id I711e08b076adb7b4808d04a47cb067cb95606f96 with SHA1 39cda2a286 is in history
 ▪ 8e45731c Merge "DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType" into oc-dev
 ▪ b6ad28d7 Merge "BondStateMachine: Check for null before calling getDeviceType" into oc-mr1-dev am: 7a11b2cf89
 ▪ 73c9932c [automerger skipped] [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286 am: ecc5b62100 am: 090b2dd50f am: c510171295 skipped: a5fb533ed4 am: 77d4863bd1 am: 5e2e6697ec am: df5f053fb0 -s ours am skip reason: subject contains skip directive
 ▪ 7a11b2cf Merge "BondStateMachine: Check for null before calling getDeviceType" into oc-mr1-dev
 ▪ df5f053f [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286 am: ecc5b62100 am: 090b2dd50f am: c510171295 skipped: a5fb533ed4 am: 77d4863bd1 am: 5e2e6697ec
 ▪ 5e2e6697 [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286 am: ecc5b62100 am: 090b2dd50f am: c510171295 skipped: a5fb533ed4 am: 77d4863bd1
 ▪ 9c0ec84c DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType
 ▪ d1dd037d BondStateMachine: Check for null before calling getDeviceType
 ▪ 77d4863b [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286 am: ecc5b62100 am: 090b2dd50f am: c510171295 skipped: a5fb533ed4
 ▪ a5fb533e [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286 am: ecc5b62100 am: 090b2dd50f am: c510171295
 ▪ c5101712 [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286 am: ecc5b62100 am: 090b2dd50f
 ▪ 090b2dd5 [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286 am: ecc5b62100
 ▪ ecc5b621 [automerger] DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType am: 39cda2a286
 ▪ 39cda2a2 DO NOT MERGE: BondStateMachine: Check for null before calling getDeviceType

 ▼ packages/apps/Camera2/
 ▪ 5e09aec11 Snap for 5450365 from fff27838050900ba7f4a9ed3c6e4adff9c9cb6cc to pi-platform-release
 ▪ 3d314109b Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/apps/CarrierConfig/
 ▪ 2fec918 Snap for 5450365 from fb861f45b48b80a222f2a2186cd56858b1ac1ab1 to pi-platform-release
 ▪ 0a273b2 Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/apps/CellBroadcastReceiver/
 ▪ 84bd5b1 Snap for 5450365 from 554370746d809d956fb267cf5b93d22115308400 to pi-platform-release
 ▪ a1c4dfe Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/apps/Contacts/
 ▪ 75f9693ae Snap for 5450365 from ed1ec620984c2334c3ff84264ca80a1d5bf48c7f to pi-platform-release
 ▪ f53751077 Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/apps/CustomDoze/
 ▪ 72fb66e Update Korean translation

 ▼ packages/apps/Dialer/
 ▪ db23b54a8 Dialer: fix a few full screen photo issues
 ▪ 0aab3cf1d Dialer: Add full screen photo option
 ▪ 35052dab1 Make proxi sensor smart-case friendly
 ▪ 52ded1e79 Fix incorrect proximity sensor behaviour

 ▼ packages/apps/Dirac/
 ▪ 1808d69 Dirac: Change QS tile icon
 ▪ d5ed6ba Dirac: Add QS tile

 ▼ packages/apps/DocumentsUI/
 ▪ 72783c75 Snap for 5450365 from 25e59678a28b01362736a55f07fd219073d65b8a to pi-platform-release
 ▪ 6087363c Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/apps/EmergencyInfo/
 ▪ 40709a2 Snap for 5450365 from 5289b203a085f1365b80e1fc163b581f9b656141 to pi-platform-release
 ▪ aea52d0 Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/apps/HavocSettings/
 ▪ d5825cd Update Turkish translations
 ▪ 31541f7 Add new maintainer for Redmi 4 Prime
 ▪ c6163d9 Add nx531j to devices
 ▪ 8629aea Settings: [2/2] Implement cutout force full screen
 ▪ 4845d7b Revert "Revert "Pocket judge""
 ▪ 340ee0e Update Korean translation
 ▪ 5162059 Settings: Add Q style to battery icon chooser [2/2]
 ▪ fc51cde Unlink automatic color for ls visualizer with albumart
 ▪ 8e9b2ae Add lockscreen visualizer customization for solid lines [2/2]
 ▪ d19f6df Add violet in devices
 ▪ 0f5f4d4 Add S7 and S7 Edge
 ▪ 36d90cb settings: correct Mi A2 name typo
 ▪ d77142d Update Turkish translations
 ▪ f854813 CustomTextClock: Code improvements [2/2]
 ▪ 4e15cdd Update translations
 ▪ 6081806 Lockscreen Clock Styles: Introduce Q style TextClock
 ▪ dd850e2 Settings: Cleanup and fixes
 ▪ de2ca53 Lockscreen Visualizer: Add pulse magic [2/2]
 ▪ 5290321 Settings: Lockscreen visualizer cleanup

 ▼ packages/apps/Nfc/
 ▪ 8e7094f4 Snap for 5450365 from 4bcd27dc660f436491f532f58eb800418e212be9 to pi-platform-release
 ▪ 77004b0d Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/apps/PackageInstaller/
 ▪ 4f09f8e9 Snap for 5450365 from b101f7ec0e6142b31946ae1a4da58ec4ef9ea690 to pi-platform-release
 ▪ 643a9971 Merge tag 'android-9.0.0_r37' into pie
 ▪ 74217a18 Update Turkish translation

 ▼ packages/apps/Settings/
 ▪ 8772b85d44 Settings: Smart Charging (2/4)
 ▪ 4af6b3c5af Update Turkish translations
 ▪ c54ebfa7e3 Snap for 5450365 from 1fb5b5100d642d0a3ab9ca34cdcf2f444ca9e852 to pi-platform-release
 ▪ d54031894b Merge tag 'android-9.0.0_r37' into pie
 ▪ ad8520a077 Revert "Settings: Add toggle for proximity wake"
 ▪ f3991fa9b3 Settings: Changes for LiveDisplay
 ▪ 1b07627044 Settings: Fix missing battery icon
 ▪ fd365ae91e Merge cherrypicks of [7316389, 7315812, 7315813, 7316457, 7316055, 7315736, 7316390, 7316458, 7316459, 7316460, 7316561, 7316562, 7316563, 7316564, 7316565, 7316566, 7316567, 7316391, 7315814, 7316548] into pi-qpr3-b-release
 ▪ 9804cf5b7d Revert "DO NOT MERGE Refactor passwords/pins/patterns to byte[]"
 ▪ 50e1cb5bb5 Update Turkish language

 ▼ packages/apps/SmartNavSettings/
 ▪ e8827d0 Fix typo in Turkish translation
 ▪ 210d246 SmartNavSettings: Cleanup and fixes

 ▼ packages/inputmethods/LatinIME/
 ▪ 39f2d9a3b Snap for 5450365 from b25378ea06605978ca8f30b75b500ba8f39014d0 to pi-platform-release
 ▪ d29bef2c2 Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/providers/DownloadProvider/
 ▪ a10cb23 Snap for 5450365 from 57fb22ac21d2aa8bdc65c6984567e04a93d27256 to pi-platform-release
 ▪ 145807f Merge tag 'android-9.0.0_r37' into pie

 ▼ packages/providers/MediaProvider/
 ▪ 23ae57a Snap for 5450365 from 33d84b73b9009df74073c718a293617db7a768fa to pi-platform-release
 ▪ 51de237 Merge tag 'android-9.0.0_r37' into pie
 ▪ 3750847 Snap for 5526913 from 99586b04120ea4994712f1494919e84f1f345f56 to pi-qpr3-b-release

 ▼ packages/services/Telecomm/
 ▪ 700363bc Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/services/Telecomm into caf
 ▪ 8e331fc8 Snap for 5450365 from 6cfe5e382d9c3fb5e5d68c33ead16f96f6315759 to pi-platform-release
 ▪ 30a9d92d Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/services/Telecomm into caf
 ▪ 245f4026 Merge 11b998775b5de2a2764297a4c796ddb8966b24b8 on remote branch
 ▪ c91510df Merge 11b998775b5de2a2764297a4c796ddb8966b24b8 on remote branch
 ▪ 96821495 Merge 11b998775b5de2a2764297a4c796ddb8966b24b8 on remote branch

 ▼ packages/services/Telephony/
 ▪ 8265cb9ea Merge tag 'android-9.0.0_r39' of https://android.googlesource.com/platform/packages/services/Telephony into caf
 ▪ aaf17a3ff Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/packages/services/Telephony into caf
 ▪ 900567cc0 Merge ffa0d45258e84f5a5d76b19027f111e7dbda0a91 on remote branch
 ▪ e7c203dde Fix non-protected broadcasts sent from phone process.
 ▪ 28833cffa Telephony: Add missing protected broadcasts
 ▪ 532c72ac9 Merge ffa0d45258e84f5a5d76b19027f111e7dbda0a91 on remote branch
 ▪ 62b22cab1 Merge ffa0d45258e84f5a5d76b19027f111e7dbda0a91 on remote branch
 ▪ 07ebb5ff3 Merge 3f58354626d05aa83f0e5a44ac7b17ad18cb7fc7 on remote branch
 ▪ ffa0d4525 Snap for 5466560 from e65c9f9e68a428cb231bbbf948b3a8a0da304233 to p-keystone-qcom-release

 ▼ prebuilts/r8/
 ▪ 2cfede7 r8: Update D8 and R8 to 1.5.23-dev
 ▪ 01b10b1 r8: Update D8 and R8 to 1.5.22-dev
 ▪ f988252 r8: Update D8 and R8 to 1.5.21-dev
 ▪ 6935423 r8: Update D8 and R8 to 1.5.20-dev
 ▪ dbbedca r8: Update D8 and R8 to 1.5.19-dev
 ▪ d0f904c r8: Update D8 and R8 to 1.5.18-dev
 ▪ 7527f3d Update D8 and R8 to 1.5.12-dev
 ▪ 5392e09 r8: Update D8 and R8 to 1.5.10-dev

 ▼ system/bt/
 ▪ 74d1c7f21 Snap for 5450365 from f8a5ce9945240777b0d5cd2ba68fdda48e1484a8 to pi-platform-release
 ▪ ed00153ec Merge tag 'android-9.0.0_r37' into pie
 ▪ c5e34370d Merge cherrypicks of [7316389, 7315812, 7315813, 7316457, 7316055, 7315736, 7316390, 7316458, 7316459, 7316460, 7316561, 7316562, 7316563, 7316564, 7316565, 7316566, 7316567, 7316391, 7315814, 7316548] into pi-qpr3-b-release
 ▪ cbc1ca17b Revert "[DO NOT MERGE] Implement key attestation using AndroidKeystore."
 ▪ 8045c16f4 Revert "[DO NOT MERGE] btif: Lighter weight file existence check"
 ▪ e6220dd32 Revert "[DO NOT MERGE] btif: Avoid a couple string copies"
 ▪ 6387e3156 Revert "[DO NOT MERGE] btif: Avoid resource leak in error case"
 ▪ 63b07f4c7 Revert "[DO NOT MERGE] Handle edge cases where input or hash/data could be null."
 ▪ f7f1d4db6 Revert "[DO NOT MERGE] btif/osi: move I/O to OSI layer. disable for multi-user."
 ▪ c6cf8f6d5 DO NOT MERGE Revert "DO NOT MERGE Separate SDP procedure from bonding state (1/2)"
 ▪ d0b9f6155 Merge cherrypicks of [7293852, 7293854, 7292377, 7293923] into pi-qpr3-release
 ▪ 29faf5890 DO NOT MERGE Revert "DO NOT MERGE Separate SDP procedure from bonding state (1/2)"
 ▪ 676e99447 Merge cherrypicks of [7077329, 7077440, 7077330, 7077468, 7076852, 7077469, 7077580, 7077581, 7077582, 7074025, 7077706, 7077707, 7077708, 7077388, 7077583, 7077584, 7077585, 7077726, 7077727, 7077331, 7077332, 7077459, 7077709, 7077710, 7077711, 7077712, 7077460, 7077461, 7077333, 7077334, 7077696] into pi-qpr3-release
 ▪ 2afc121dc DO NOT MERGE Log encryption key size MERGE CONFLCIT RESOLUTION TO PI-QPR3-RELEASE * Log result from HCI_READ_ENCR_KEY_SIZE command
 ▪ 9de0e030e DO NOT MERGE Don't persist bonds using sample LTK
 ▪ e66923f99 DO NOT MERGE Drop Bluetooth connection with weak encryption key
 ▪ 859dc4b72 DO NOT MERGE Don't persist bonds using sample LTK
 ▪ 41453cf2a DO NOT MERGE Log encryption key size
 ▪ 5396002a2 DO NOT MERGE Drop Bluetooth connection with weak encryption key

 ▼ system/core/
 ▪ bd9b031cc lmkd: bump process priority and set to FOREGROUND group before kill
 ▪ 468dccd34 Run BoringSSL self test during startup

 ▼ system/libhwbinder/
 ▪ 9809f43 Snap for 5450365 from 14418a7f30d925c320ba27dc8a7339ffb349ced6 to pi-platform-release
 ▪ 307ab5e Merge tag 'android-9.0.0_r37' into pie
 ▪ aa22afd Snap for 5526913 from 2f99aacc93a99412046dd2b78153b00add92839a to pi-qpr3-b-release
 ▪ 2f99aac [automerger skipped] Rely on compiler to zero out structs. am: 6dc48681df am: a2c71652e7 am: 8e37454292 -s ours am skip reason: change_id I96e4bea47f99e00ef33cfce74621e5869b1ff3d7 with SHA1 16786a76b2 is in history
 ▪ 8e37454 Rely on compiler to zero out structs. am: 6dc48681df am: a2c71652e7
 ▪ a2c7165 Rely on compiler to zero out structs. am: 6dc48681df
 ▪ 6dc4868 Rely on compiler to zero out structs.
 ▪ 16786a7 Rely on compiler to zero out structs.

 ▼ system/netd/
 ▪ 75b9964 Snap for 5450365 from f1b1f1ee211b074ef19aac47ae0f8e511b5381cc to pi-platform-release
 ▪ 2af70af Merge tag 'android-9.0.0_r37' into pie

 ▼ system/nfc/
 ▪ 995e732 Merge cherrypicks of [7293852, 7293854, 7292377, 7293923] into pi-qpr3-release
 ▪ c651a06 [DO NOT MERGE]Revert "Add null check in nfa_ce_deactivate_ntf"
 ▪ ffde3a8 Merge cherrypicks of [7077329, 7077440, 7077330, 7077468, 7076852, 7077469, 7077580, 7077581, 7077582, 7074025, 7077706, 7077707, 7077708, 7077388, 7077583, 7077584, 7077585, 7077726, 7077727, 7077331, 7077332, 7077459, 7077709, 7077710, 7077711, 7077712, 7077460, 7077461, 7077333, 7077334, 7077696] into pi-qpr3-release
 ▪ 7f23643 Add null check in nfa_ce_deactivate_ntf
 ▪ e47adf8 Fix heap overflow in nfa_rw_store_ndef_rx_buf
 ▪ c68b53b Fix heap overflow in nfa_rw_store_ndef_rx_buf

 ▼ system/sepolicy/
 ▪ b8f90dd88 Snap for 5450365 from 3feb8646fe27f3ca87b590d163eb0645c8281398 to pi-platform-release
 ▪ 746b070af Merge tag 'android-9.0.0_r37' of https://android.googlesource.com/platform/system/sepolicy into pie
 ▪ ae523ed88 Update socket ioctl restrictions

 ▼ system/timezone/
 ▪ 5822955 Merge tag 'android-9.0.0_r37' into staging/lineage-16.0_merge-android-9.0.0_r37
 ▪ 48b3245 Snap for 5450365 from 5ba7ee543f392661ebd91748f1a1f4b287da6c46 to pi-platform-release

 ▼ system/tools/hidl/
 ▪ a31de7c Snap for 5450365 from fab4a3fa419158001944ec0a439fd4471881aa77 to pi-platform-release
 ▪ 57e363b Merge tag 'android-9.0.0_r37' into pie

 ▼ system/vold/
 ▪ 5017501 Merge tag 'android-9.0.0_r37' into pie
 ▪ 59295fb Snap for 5526913 from a598e04a91c64741f9f71c6511a7ced7f71d194e to pi-qpr3-b-release
 ▪ a736dde Merge cherrypicks of [7077329, 7077440, 7077330, 7077468, 7076852, 7077469, 7077580, 7077581, 7077582, 7074025, 7077706, 7077707, 7077708, 7077388, 7077583, 7077584, 7077585, 7077726, 7077727, 7077331, 7077332, 7077459, 7077709, 7077710, 7077711, 7077712, 7077460, 7077461, 7077333, 7077334, 7077696] into pi-qpr3-release
 ▪ 0496e36 Fsync directories before delete key
 ▪ 4b9c47d Fsync directories after creating files

 ▼ vendor/codeaurora/telephony/
 ▪ 3b08f08 Add NR ENDC AIDL APIs
 ▪ aea5e16 Merge b98b950ca5636cd9ed13ff4a6a90afca45457dce on remote branch
 ▪ 4f253f3 Merge tag 'LA.UM.7.4.r1-05000-8x98.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie

 ▼ vendor/havoc/
 ▪ 4d03c84c update Lawnchair to alpha-2066
 ▪ bf5a7aa2 Havoc 2.5
 ▪ 44c60b62 vendor: Import LiveDisplay init file
 ▪ 3c91be6b vendor: Whitelist LiveDisplay permissions
 ▪ f13dfdcb update Google Calculator to 7.6 (246215570)
 ▪ 8e0ff40f apns: Update IRAN APNs
 ▪ e576ad38 update Lawnchair to alpha-2057
 ▪ 38051773 apns : Update the KT IMS apn
 ▪ deaeff10 images: Add 420dpi symlink
 ▪ 3e678396 update Lawnchair to alpha-2048
 ▪ 679fd29b update Lawnchair to alpha-2035
 ▪ f8999aae update changelog generate logic
 ▪ 9396645a update Lawnchair to alpha-2013
 ▪ b4898780 kernel: Add option for using LLD as linker
 ▪ 750a175c update Lawnchair to alpha-1983

 ▼ vendor/qcom/opensource/audio/
 ▪ 9c1a243 Merge b8875565a5f2ab666831ae9e5f6a3f51ee9514d8 on remote branch
 ▪ b887556 policy_hal: handle compress offload concurrency
 ▪ c7d796f Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

 ▼ vendor/qcom/opensource/cryptfs_hw/
 ▪ e5b753c Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/cryptfs_hw into pie

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ 5e48b2b ipacm: fix duplicated entry in nonnat_iface_ipv4_list
 ▪ e6d5507 Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ 17272e2 Merge 11e3a7639c5e38668f744c8713f69c76219b0076 on remote branch
 ▪ ee39342 ipacm: post IPA_HANDLE_WAN_UP_TETHER event when routing is set
 ▪ 42a5eee Merge 2f329b3b7d319e725f81c663ec070794b9a25c2d on remote branch
 ▪ 11e3a76 Merge "ipacm: reset ext prop flag and ext_prop when received SSR event."
 ▪ e68ba2d ipacm: reset ext prop flag and ext_prop when received SSR event.
 ▪ 83a6282 ipacm: not support xlat on 2st tethered iface
 ▪ 1766931 vndk fixes
 ▪ 0fa2ca9 ipacm: support clat on non-internet PDN
 ▪ abdb87d Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 1a45ac2 Merge tag 'LA.UM.7.5.r1-04800-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ ce19f08 Add Hash Version for Servicetracker HAL
 ▪ 6a364f8 add missing Android.bp for vendor.qti.hardware.wifi@1.0
 ▪ ca81ee4 Merge tag 'LA.UM.7.5.2.r1-02600-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ c98005e wifi: create vendor.qti.hardware.wifi.hostapd@1.1 hal.
 ▪ f7fea3e Merge 7f364cd7b8a4ba3668f35c60aab162b1e4f04148 on remote branch
 ▪ 1d3b5e6 Merge 7f364cd7b8a4ba3668f35c60aab162b1e4f04148 on remote branch
 ▪ d2d1b8e Merge 7f364cd7b8a4ba3668f35c60aab162b1e4f04148 on remote branch
 ▪ 7f364cd Merge "wifi: Extend ISupplicantVendorStaIface to get Wi-Fi generation info."
 ▪ fd9f1e8 Merge "Introduce vendor.qti.hardware.servicetracker@1.0 HAL"

 ▼ vendor/xiaomi/
 ▪ 98a0002a add power_off_alarm
 ▪ b0c0a862 clean

====================
     04-10-2019
====================
 ▼ art/
 ▪ 58aba43081 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/art into pie
 ▪ 0772c8073f Merge b529bd7902d5cf0f0a8818da3658074006799391 on remote branch

 ▼ bionic/
 ▪ 87e6ab514 bionic: Prefer /sbin/sh if it exists
 ▪ 18995096f bionic: Prefer /sbin/sh if it exists
 ▪ 481970244 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie
 ▪ 885f051f8 Merge 30551b577877170934f081981b15aab1130e9a28 on remote branch
 ▪ ad011d0d9 Merge 30551b577877170934f081981b15aab1130e9a28 on remote branch
 ▪ f6551beda Snap for 5421909 from f3224fad5712deccd6652e3f2f923d2630e63fb0 to p-keystone-qcom-release
 ▪ f3224fad5 Merge SPL-2019-03-05

 ▼ bootable/recovery/
 ▪ 58074bfe recovery: Allow custom bootloader msg offset in block misc

 ▼ build/kati/
 ▪ 64200d7 Sort results of output from the "find" command
 ▪ deb7807 Ignore TMPDIR when calculating the kati stamp
 ▪ 5e93bef Silence FindEmulator

 ▼ build/make/
 ▪ da108d051 Version bump to PQ3B.190408.007
 ▪ 6fafcf78d Version bump to PQ3B.190408.006
 ▪ ac3ae589d Merge changes from topic "am-25a1f704-80e7-4c0b-a6ef-9bda09527573" into oc-dev am: e95d55db1c am: b293d74a3c am: c7c7763e18
 ▪ 91441ca65 [automerger skipped] [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 Merged-In:1f8f84de6133f82df8210fa9214475d7c5aaa2f0 am: 3e8a1393a7 am: 9231b34069 am: ee14e56c76 -s ours am skip reason: subject contains skip directive
 ▪ c7c7763e1 Merge changes from topic "am-25a1f704-80e7-4c0b-a6ef-9bda09527573" into oc-dev am: e95d55db1c am: b293d74a3c
 ▪ ee14e56c7 [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 Merged-In:1f8f84de6133f82df8210fa9214475d7c5aaa2f0 am: 3e8a1393a7 am: 9231b34069
 ▪ b293d74a3 Merge changes from topic "am-25a1f704-80e7-4c0b-a6ef-9bda09527573" into oc-dev am: e95d55db1c
 ▪ 9231b3406 [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 Merged-In:1f8f84de6133f82df8210fa9214475d7c5aaa2f0 am: 3e8a1393a7
 ▪ e95d55db1 Merge changes from topic "am-25a1f704-80e7-4c0b-a6ef-9bda09527573" into oc-dev
 ▪ 0ad5c1fe8 Merge "[DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896" into pi-dev
 ▪ 9f4db7673 Version bump to PQ3A.190505.002
 ▪ e64f2a16a Version bump to PQ3B.190408.005
 ▪ f7f1a06ff Merge "Make change and version bump to PPRL.190405.003 am: 505063f5ad" into pie-gsi
 ▪ 598f34d64 Make change and version bump to PPRL.190405.003 am: 505063f5ad
 ▪ f4a8b359c Merge "Make change and version bump to PPRL.190405.001 am: 10d2ada411" into pie-gsi
 ▪ d85d3e824 Make change and version bump to PPRL.190405.001 am: 10d2ada411
 ▪ f7bf2350a Make change and version bump to PQ3B.190408.004
 ▪ 3e8a1393a [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 Merged-In:1f8f84de6133f82df8210fa9214475d7c5aaa2f0
 ▪ 9c6046fb3 [automerger skipped] [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 am: 1f8f84de61 -s ours am skip reason: subject contains skip directive
 ▪ 505063f5a Make change and version bump to PPRL.190405.003
 ▪ 10d2ada41 Make change and version bump to PPRL.190405.001
 ▪ 1f8f84de6 [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896
 ▪ 5a5debe90 Version bump to PQ3B.190408.003
 ▪ e559f0700 Version bump to PQ3B.190408.002
 ▪ ced912cc7 Make change and version bump to PQ3B.190408.001
 ▪ 4876989d7 Make change and version bump to PQ3B.190407.001
 ▪ 2db03695f [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896
 ▪ c9025d983 [automerger] [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 am: bcdb638d6a am: f3e105e648 am: 41611b89ea am: ef4f971f0a skipped: 04ba31ff57
 ▪ 04ba31ff5 [automerger] [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 am: bcdb638d6a am: f3e105e648 am: 41611b89ea am: ef4f971f0a
 ▪ ef4f971f0 [automerger] [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 am: bcdb638d6a am: f3e105e648 am: 41611b89ea
 ▪ 41611b89e [automerger] [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 am: bcdb638d6a am: f3e105e648
 ▪ f3e105e64 [automerger] [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896 am: bcdb638d6a
 ▪ bcdb638d6 [DO NOT MERGE] Update Security String to 2019-06-01 Bug:129374896
 ▪ fff56b21c Version bump to PQ3B.190402.002
 ▪ 0f3ee81c9 Make change and version bump to PQ3B.190402.001
 ▪ 3b4e32ab7 Merge tag 'android-9.0.0_r35' of https://android.googlesource.com/platform/build into pie
 ▪ 72f2d9b30 Version bump to PQ3B.190401.002
 ▪ c3ee56120 Make change and version bump to PQ3B.190401.001
 ▪ 172174752 Make change and version bump to PQ3B.190331.001
 ▪ 51649760d Version bump to PQ3B.190326.005
 ▪ 863823a73 Version bump to PQ3B.190326.004
 ▪ 5df60cb93 Version bump to PQ3B.190326.003
 ▪ b96621747 Version bump to PQ3B.190326.002
 ▪ e24098e90 Make change and version bump to PQ3B.190326.001
 ▪ 2cdea72d9 Make change and version bump to PQ3B.190324.001
 ▪ 2387d8e20 build: Move custom buildinfo to vendor/havoc [1/2]
 ▪ cb604b32e Make change and version bump to PQ3B.190322.001
 ▪ f2da0cae8 Quote message in echo-error/echo-warning macros
 ▪ 1984535e8 Make change and version bump to PQ3B.190319.001
 ▪ 42d3d5cf9 Make change and version bump to PQ3B.190318.001
 ▪ 2ddc929d3 Make change and version bump to PQ3B.190317.001
 ▪ 3492223e5 build: Stop installing the sample APN list
 ▪ 6bc61b890 Enable dynamic linker and hidden API warnings only on eng build
 ▪ 347c41ead Make change and version bump to PQ3B.190313.001
 ▪ 2b091f594 build: Allow build-image-kernel-modules to be called from shell
 ▪ e8a051499 Make change and version bump to PQ3A.190505.001
 ▪ 16206a687 [DO NOT MERGE] Update Platform Security string to 2019-05-05 for Pi-dev Bug:128322951 (cherry picked from commit 7d44fc8d59547bc583bad61fe2cae9fa14d31baf)
 ▪ afc4feea6 Make change and version bump to PQ3A.190501.001
 ▪ cd380a812 [DO NOT MERGE] Update Security String to 2019-05-01 in pi-dev Bug: 128322951 (cherry picked from commit 1159bb8b17df6caf1ce075d120c811b17eb73554)
 ▪ 88ea185d5 Make change and version bump to PQ3B.190312.001
 ▪ 3d75a015a [automerger skipped] [Do Not Merge] Update Platform Security String to 2019-05-05 for oc-mr1-dev Bug:128322951 am: 796d90c141 -s ours am skip reason: subject contains skip directive
 ▪ 53a4d1651 Merge "[DO NOT MERGE] Update Platform Security string to 2019-05-05 for Pi-dev Bug:128322951" into pi-dev
 ▪ d6e24caa4 [automerger skipped] [DO NOT MERGE] Update Security String to 2019-05-01 in oc-mr1-dev Bug: 128322951 am: 801e91776e -s ours am skip reason: subject contains skip directive
 ▪ 796d90c14 [Do Not Merge] Update Platform Security String to 2019-05-05 for oc-mr1-dev Bug:128322951
 ▪ 7d44fc8d5 [DO NOT MERGE] Update Platform Security string to 2019-05-05 for Pi-dev Bug:128322951
 ▪ 801e91776 [DO NOT MERGE] Update Security String to 2019-05-01 in oc-mr1-dev Bug: 128322951
 ▪ 1159bb8b1 [DO NOT MERGE] Update Security String to 2019-05-01 in pi-dev Bug: 128322951
 ▪ 28ed15b66 Make change and version bump to PQ3B.190310.001

 ▼ build/soong/
 ▪ bd254918 androidmk: Skip obsolete JACK flags
 ▪ dc0c0de9 update cleanbuild
 ▪ d69abe33 soong: Add targetclean to the mix
 ▪ 2b000349 Optimize CPU time when running d8 and r8
 ▪ 4390a034 Stop using GCC in toolchain_library

 ▼ device/havoc/sepolicy/
 ▪ 491ee3b move havoc_updates lable system/sepolicy

 ▼ device/qcom/sepolicy/
 ▪ 0108f70c sepolicy: Adding sepolicy rules for servicetracker HAL
 ▪ f3b55ee0 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ a249a8a2 Merge 0cdc3d54329b9c4135a4e925e61565d7d49be525 on remote branch
 ▪ 72bc038b Merge "sepolicy: vendor: Allow vold to read attribute of metadata directory"
 ▪ b85fd59c Merge "sepolicy: allow gnss hal to access health hal"
 ▪ 8204ab38 Merge 0cdc3d54329b9c4135a4e925e61565d7d49be525 on remote branch
 ▪ 9cfa8c05 sepolicy: allow gnss hal to access health hal
 ▪ 3c6fd98e Adding Kill capability to perf hal service.
 ▪ d8543ff2 Allow socket creation, permission to access IOP.
 ▪ 166f6f29 sepolicy: camera: Allow camera daemon to access graphics
 ▪ 80a9dbbd Merge tag 'LA.UM.7.6.2.r1-07600-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ c9e5d57a Merge c739cd610af72c23bfac9c5574596bc3379dc8b9 on remote branch
 ▪ 396ca9c6 sepolicy : Adding shell permissions to hal-perf
 ▪ 0cdc3d54 Merge "Adding module for listening to Uevents for debugging purpose"
 ▪ 71d82da8 Merge 6ea46336a7f190b67eb18ef51a6ffcbbe4457cc0 on remote branch
 ▪ 5ec73d8e Adding module for listening to Uevents for debugging purpose
 ▪ 7657420f Merge c739cd610af72c23bfac9c5574596bc3379dc8b9 on remote branch
 ▪ 3f600645 Merge "Adding self kill capability for perf hal"
 ▪ d6f17ce0 Merge tag 'LA.UM.7.6.2.r1-07300-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ 6ea46336 Merge "sepolicy: move camera debugfs entries to genfs"
 ▪ 3104cbd4 Merge "sepolicy: Adding rule for reading qfprom node"
 ▪ 291afeae sepolicy: vendor: Allow vold to read attribute of metadata directory
 ▪ 691d6a7e sepolicy: move camera debugfs entries to genfs
 ▪ 5c347025 Adding self kill capability for perf hal
 ▪ c739cd61 Merge "sepolicy:esgda: add app domain for esgda test app"
 ▪ 69be22f2 sepolicy: Adding rule for reading qfprom node
 ▪ 18e4e71e Merge "sepolicy: Adding rule for reading qfprom node"
 ▪ f0845452 sepolicy: Adding rule for reading qfprom node

 ▼ device/qcom/sepolicy-legacy/
 ▪ 96f30d3 sepolicy: Label persist partition for all SoCs

 ▼ device/xiaomi/gemini/
 ▪ bf71f3036 build kernel with clang 9.0.2
 ▪ 77090c490 build SyberiaOS
 ▪ 4e5031c99 msm8996-common: Update qseecom daemon service name
 ▪ cbfb18d73 msm8996-common: init.rc: Changes to stop rtp daemon during shutdown
 ▪ ce03ec11b Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' from https://source.codeaurora.org/quic/la/device/qcom/common
 ▪ 563e398b8 Android 9.0.0 release 35 (PQ2A.190405.003)
 ▪ 51e8ab9fe Update blobs
 ▪ 1e063b82b update su sepolicy
 ▪ d6a56e4ad capricorn: update brightness overlays
 ▪ a98cc39ce try to mount ext4 before f2fs
 ▪ d4adae838 priv-app control: fix missing microG permissions
 ▪ bf900ce5b add recovery sepolicy
 ▪ ec01a7d75 CAF tag: LA.UM.7.6.2.r1-07600-89xx.0
 ▪ da652c88b TWRP: Fix HW FDE when building with Pie tree
 ▪ 46431ce85 update sepolicy
 ▪ 2bd48d31e build miui camera
 ▪ 8da182680 update init.qcom*.rc files
 ▪ 1a580286e audio_effects: add JamesDSP effect library
 ▪ 56c4658fd CAF tag: LA.UM.7.6.2.r1-07300-89xx.0
 ▪ 1cac4b9a3 update sepolicy
 ▪ 2eb888511 Revert "Enable workaround for old MCC/MNC format"
 ▪ 6a02761f3 Enable TARGET_USES_ALTERNATIVE_MANUAL_NETWORK_SELECT
 ▪ 7d8088f26 update tree

 ▼ device/xiaomi/translations/
 ▪ 433bbfa DO NOT MERGE Fix summary text for advanced button.
 ▪ a884b10 add new

 ▼ external/exfat/
 ▪ e346c7c exfat: Rename utf conversion symbols
 ▪ 9e9dc69 exfat: Add static libs for recovery

 ▼ external/f2fs-tools/
 ▪ 5442202 f2fs-tools: Add sload.f2fs support to libf2fs_fsck
 ▪ 6e67812 f2fs-tools: Rename utf conversion symbols
 ▪ d445c41 f2fs-tools: Rename quota symbols
 ▪ 20e8f06 f2fs-tools: Add static libs for recovery

 ▼ external/google/
 ▪ 39d0cdb SmartNav: Fix NPE when navbar is not set to stock mode
 ▪ 5d47a24 elmyra: Adapt to smartnav changes
 ▪ f3917f0 Init Havoc...
 ▪ 59f0ad0 Dreamliner: Add SystemUIGoogleFactory
 ▪ 13ef44b Dreamliner: Start dreamliner service conditionally
 ▪ 749a175 Dreamliner: Clean up
 ▪ 31e1fad Dreamliner: Initial import for Settings [1/2]
 ▪ 394c748 Dreamliner: Reorganise the external repo [1/2]
 ▪ 37be410 Dreamliner: Initial import for SystemUI

 ▼ external/icu/
 ▪ 7ca8e5403 DO NOT MERGE: Apply 2019a tzdb updates
 ▪ 1e7ba5d1a DO NOT MERGE: Apply upstream fix to use rearguard data

 ▼ external/nano/
 ▪ f1e5da6c help: don't doubly list toggles that have two keys assigned to them
 ▪ d79b9823 bindings: add easier keystrokes for the linenumber and softwrap toggles
 ▪ 82f1ce8e bindings: remove the jumpy-scrolling toggle entirely
 ▪ 50ee655f gnulib: update to its current upstream state
 ▪ 5459f56f build: add gnulib modules to the list of files with translatable strings
 ▪ 209531a7 docs: remove all mention of --finalnewline, and undefault --nonewlines
 ▪ 25523070 options: remove -f (--finalnewline); go back to auto-adding this newline
 ▪ 5601b9a6 tweaks: switch back from checking FINAL_NEWLINE to checking NO_NEWLINES
 ▪ 81dcb137 tweaks: remove an unpaired closing parenthesis from the NEWS file
 ▪ 580fd134 tweaks: do a check up front instead of every time round the loop
 ▪ 790ce379 tweaks: reshuffle some lines, condense a comment and drop another
 ▪ 97cd62a8 tweaks: rename two variables, to make more sense
 ▪ 2f68bbb5 tweaks: reword a comment, and drop an unneeded assert
 ▪ 55952c09 tweaks: adjust the indentation after the previous change
 ▪ d9cfdd36 tweaks: don't bother special-casing non-UTF8 when seeking a character
 ▪ c9605e73 syntax: c: change the highlighting of preprocessor directives
 ▪ c3f97bc9 rcfile: read the syntax files in alphabetical order when globbing
 ▪ 4399b734 bindings: disallow executing an external command when in view mode
 ▪ b9581bd5 tweaks: rename two variables, to match others
 ▪ 408f1595 feedback: replace an assert with a check plus error message at startup
 ▪ f585403b build: add src/cut.c to the list of files with translatable strings
 ▪ 601973dd tweaks: rename another variable, to be more descriptive
 ▪ 25a5fb82 tweaks: rename a variable, to get out of the way for another rename
 ▪ 897e557c tweaks: rename a variable, to be more distinct and more descriptive
 ▪ 81bee1f5 tweaks: shorten and improve some comments, and reshuffle a few lines
 ▪ 691eb114 tweaks: remove a function that is now unused
 ▪ fb04dff6 tweaks: don't bother reallocating the data when a line gets hard-wrapped
 ▪ c224ea3c tweaks: reshuffle two lines, and reword a comment
 ▪ 2a2fe720 tweaks: condense a bit of copying code
 ▪ 3f9d8011 tweaks: don't bother copying the NUL byte -- it is set nine lines down
 ▪ 4788c5f9 tweaks: don't bother reallocating the squeezed string, just terminate it
 ▪ a5869ba4 tweaks: rename another variable, to be more fitting
 ▪ 7bc324f2 tweaks: rename two variables, to be more distinct and more fitting
 ▪ 8d40b568 tweaks: rename a variable, to be more distinct and more apt
 ▪ 0c0afb00 tweaks: simplify a message, and normalize the spelling of another one
 ▪ 2281ec9a tweaks: remove an unneeded check for NULL  [coverity]
 ▪ cd0917fe tweaks: remove an unneeded check for NULL and its associated message
 ▪ 1a1519b6 tweaks: drop an assignment whose value is never used  [scan-build]
 ▪ 947ccbb5 rcfile: don't break a chain of 'else if'  [scan-build]
 ▪ 671db5e1 tweaks: rename an overshort type to something that makes some sense
 ▪ acfee253 tweaks: rename a cryptic type to something that makes a little sense
 ▪ 32431cdd files: block the resizing signal while reading from an external command
 ▪ 8e302738 bindings: recognize the ^W^Y and ^W^V legacy keystrokes again
 ▪ aa256885 tweaks: remove a superfluous check for NULL plus the associated message
 ▪ 5375403b syntax: nanorc: colorize also strings preceded by 'start=' or 'end='
 ▪ b0c9809a speller: block the resizing signal also during an integrated spell check
 ▪ 19c82e6a feedback: spare the user a superfluous scaring when trying to exit
 ▪ 84d21b09 tweaks: consistently use .sp instead of .PP to insert a blank line
 ▪ f8e03207 syntax: nanorc: require whitespace both before and after a quoted string
 ▪ e5a8c351 feedback: show a message while executing an external command
 ▪ 7ad232d7 files: initialize a variable before referencing it
 ▪ 85804ec7 syntax: man: require the dot to be at start of line, not the comment
 ▪ e473ba5e syntax: man: anchor macros at start of line, as only then they are valid
 ▪ 9120a62c syntax: man: add comments, and color all the safe lowercase macros
 ▪ 53ecb322 syntax: default: color in red also versions 4.x of nano
 ▪ 3f695b8f speller: resizing can happen also when configured with --enable-tiny
 ▪ 55699dc1 tweaks: rename some variables, to be less repititious
 ▪ fa48d523 tweaks: stop doing tandem assignments (one passing through the other)
 ▪ 92cbc7c4 syntax: c: color as a type any lowercase word that ends with "_t"
 ▪ 6f07f2b4 tweaks: rename a function plus parameter, to stay closer to what it does
 ▪ f58869d0 tweaks: put the unblocking of SIGWINCHes in a better place
 ▪ 978c121d speller: block the resizing signal again during an external spell check
 ▪ f6a7983a docs: for two of the toggles, mention the new instead of the old option
 ▪ a1375474 docs: remove the AUTHOR section, per advice from 'man man-pages'
 ▪ d0cc75f1 docs: put paths and filenames in italics, per 'man man-pages'
 ▪ 0fccfc03 docs: re-title the temporary section about the changed defaults
 ▪ d0a7e6e6 docs: give the FILES section in the man page its canonical title
 ▪ d7a5bacf po: update translations and regenerate POT file and PO files
 ▪ 20facb40 build: ensure that also new PO files are committed to git
 ▪ a5498fee build: stop using the --disable-wrapping-as-root configure option
 ▪ 3e4edb2a bump version numbers and add a news item for the 4.0 release
 ▪ 92ad431b tweaks: escape hyphens that must be hard hyphens in the man pages
 ▪ 123a102c docs: remove the mentioning of --disable-wrapping-as-root from the FAQ
 ▪ 37477bfb tweaks: slightly reword, for esthetics of the resulting Info document
 ▪ bc40dd64 docs: adjust and extend the Pico-compatibility section in the manual
 ▪ e02c8aeb tweaks: adjust indentation after previous change, and rename a parameter
 ▪ 003ddc76 tweaks: don't bother special-casing non-UTF8 when checking for a blank
 ▪ 1c395370 tweaks: avoid parsing the same character twice
 ▪ b58418b3 tweaks: rename a variable, to be more distinct
 ▪ 23190aa6 tweaks: make an assignment only when the option is valid, like elsewhere
 ▪ 01e6d435 tweaks: rename a function, to be simpler and more accurate
 ▪ 2b21d538 tweaks: elide a function that is called just once
 ▪ cddfcb1b tweaks: rename a struct element, to make sense
 ▪ 6755b7c0 tweaks: rename four functions, to make more sense
 ▪ aac4fc46 tweaks: rename a type, to make more sense
 ▪ 04cfe5a2 tweaks: rename a function for aptness, and two variables for shortness
 ▪ 954cab81 tweaks: improve and condense some comments, and remove an unneeded one
 ▪ 69601315 docs: add notes to draw attention to the changed defaults
 ▪ 43c6bc66 tweaks: add a consistency check plus a corresponding warning
 ▪ e0fab690 tweaks: don't pass a pointer when a boolean is expected
 ▪ 513d2ae9 build: fix compilation when configured with --disable-utf8
 ▪ 47f3dc75 display: use non-breaking space instead of dot for VTE-bug workaround
 ▪ 5f529a48 tweaks: don't bother trying to draw characters beyond the screen's edge
 ▪ d9faac61 display: dot the stripe when it's in the last column, to defeat a VTE bug
 ▪ 93ee0a8a display: show the guide stripe for double-width/multi-byte characters
 ▪ 15959346 tweaks: exclude the guide-stripe code from the tiny version
 ▪ 902b4674 display: account for horizontal scrolling when drawing the guide stripe
 ▪ 37be9b54 justify: initialize a variable before making use of its value
 ▪ 19a833c9 startup: check again for a Linux console after reading all files
 ▪ 169da8ae docs: mention three features in their proper place
 ▪ 20514eca feedback: make two error messages better match the option
 ▪ f54f1226 gnulib: update to its current upstream state
 ▪ d5b21d7b copyright: update the years for the FSF in the documentation too

 ▼ external/openssh/
 ▪ 5de397a8 second thoughts: leave README in place
 ▪ 5d3127d9 Revert "rewrite README"
 ▪ 9444d826 rewrite README
 ▪ a924de0c update versions
 ▪ 312dcee7 upstream: openssh-8.0
 ▪ 885bc114 session: Do not use removed API
 ▪ 9d7b2882 upstream: when logging/fataling on error, include a bit more detail
 ▪ 79a87d32 Remove "struct ssh" from sys_auth_record_login.
 ▪ 138c0d52 Adapt custom_failed_login to new prototype.
 ▪ a0ca4009 Add includes.h for compat layer.
 ▪ 00991151 Stop USL compilers for erroring with "integral constant expression expected"
 ▪ 43f47ebb Only use O_NOFOLLOW in fchownat and fchmodat if defined
 ▪ 342d6e51 Adjust softhsm2 path on Fedora Linux for regress
 ▪ f5abb05f Only use O_NOFOLLOW in utimensat if defined.
 ▪ 786cd4c1 drop old Cygwin considerations
 ▪ 21da87f4 upstream: fix interaction between ClientAliveInterval and RekeyLimit
 ▪ 4f0019a9 upstream: Fix authentication failures when "AuthenticationMethods
 ▪ d6e5def3 upstream: whitespace
 ▪ 26e0cef0 upstream: Expand comment to document rationale for default key
 ▪ f47269ea upstream: Increase the default RSA key size to 3072 bits. Based on
 ▪ 62949c5b upstream: full stop in the wrong place;
 ▪ 1b1332b5 upstream: benno helped me clean up the tcp forwarding section;
 ▪ 2aee9a49 upstream: fix use-after-free in ssh-pkcs11; found by hshoexer w/AFL
 ▪ 9edbd782 Fix build when configured --without-openssl.
 ▪ 825ab32f On Cygwin run sshd as SYSTEM where possible.
 ▪ a212107b Replace alloca with xcalloc.
 ▪ daa7505a Use Cygwin-specific matching only for users+groups.

 ▼ external/roboto-fonts/
 ▪ fd30717 Add missing glyphs from Roboto

 ▼ external/skia/
 ▪ 7d3f57c7b3 Merge 22516de1424095cdf378411511aede2c40d6206c on remote branch
 ▪ 1ea77383a6 Merge branch '9.0' of https://github.com/syberia-project/platform_external_skia into pie
 ▪ 7b904fb014 Snap for 5385651 from bf999383abd128f8db32fc2f24606679280a5b7d to pi-qpr3-b-release

 ▼ external/toybox/
 ▪ 7d5cb84f toybox: Use toybox for dd, getprop and grep in recovery
 ▪ fd4a589c Revert "Reland: Stop building getprop"
 ▪ fd080612 toybox: Add install to symlinks

 ▼ external/v8/
 ▪ c985a0cd [RESTRICT AUTOMERGE] Fix OOB Access in libpac
 ▪ c61d1fd9 Fix Integer Overflow in libpac
 ▪ 2acb366b Fix type confusion in libpac
 ▪ 983b7f46 Fix OOB read in libpac ast-numbering.cc
 ▪ c0626e31 Fix type confusion in libpac

 ▼ external/vim/
 ▪ 3fb01a53c patch 8.1.1142: no test for dragging the window separators with the mouse
 ▪ 1b55797e9 patch 8.1.1141: terminal winpos test fails with very large terminal
 ▪ 46ad288b9 patch 8.1.1140: not easy to find out what neighbors a window has
 ▪ 9845f36aa patch 8.1.1139: no test for what is fixed in patch 8.1.0716
 ▪ d7f246c68 patch 8.1.1138: plugins don't get notified when the popup menu changes
 ▪ 62e1bb4a1 Update runtime files.
 ▪ 049736fa8 patch 8.1.1137: xterm mouse wheel escape sequence is not tested
 ▪ 905dd905d patch 8.1.1136: decoding of mouse click escape sequence is not tested
 ▪ d85c396d5 patch 8.1.1135: build failure for small version
 ▪ 39803d82d patch 8.1.1134: buffer for quickfix window is reused for another file
 ▪ 08499f5a4 patch 8.1.1133: compiler warning for uninitialized struct member
 ▪ 616aeef21 patch 8.1.1132: getwinpos() test fails on MS-Windows
 ▪ 16c34c376 patch 8.1.1131: getwinpos() does not work in the MS-Windows console
 ▪ 116402382 patch 8.1.1130: MS-Windows: warning for unused variable
 ▪ 2d7260d66 patch 8.1.1129: when making a new screendump test have to create the file
 ▪ 94a7242ad patch 8.1.1128: getwinpos() test does not work on MS-Windows
 ▪ 6bc9305a0 patch 8.1.1127: getwinpos() doesn't work in terminal on MS-Windows console
 ▪ 3d3f21764 patch 8.1.1126: build failure with +terminal but without tgetent
 ▪ fa1e90cd4 patch 8.1.1125: libvterm does not handle the window position report
 ▪ d9eefe315 patch 8.1.1124: insert completion flags are mixed up
 ▪ 73655cf0c patch 8.1.1123: no way to avoid filtering for autocomplete function
 ▪ 9d40128af patch 8.1.1122: char2nr() does not handle composing characters
 ▪ 4a5711b5e patch 8.1.1121: test for term_gettitle() was disabled
 ▪ 543c9b192 patch 8.1.1120: cannot easily get directory entry matches
 ▪ 577fadfc1 patch 8.1.1119: no support for Windows on ARM64.
 ▪ 652de23dc patch 8.1.1118: a couple of conditions are hard to understand
 ▪ 1cd4dc444 patch 8.1.1117: build failure without the +eval feature
 ▪ 558ca4ae5 patch 8.1.1116: cannot enforce a Vim script style
 ▪ 8f4aeb557 patch 8.1.1115: cannot build with older C compiler
 ▪ 0f248b006 patch 8.1.1114: confusing overloaded operator "." for string concatenation
 ▪ eb93f3f0e patch 8.1.1113: making an autocommand trigger once is not so easy
 ▪ 87f59b09e patch 8.1.1112: duplicate code in quickfix file
 ▪ fda1bff39 patch 8.1.1111: it is not easy to check for infinity
 ▪ e5e4e22c1 patch 8.1.1110: composing chars on space wrong when 'listchars' is set
 ▪ 39b76b7df patch 8.1.1109: deleted file still in list of distributed files
 ▪ 723dd946f Update runtime files.
 ▪ 7a66627cf patch 8.1.1108: test for 'visualbell' doesn't work
 ▪ b4e6a2d07 patch 8.1.1107: no test for 'visualbell'
 ▪ 449ac47f9 patch 8.1.1106: no test for 'writedelay'
 ▪ 5da04ef1b patch 8.1.1105: long escape sequences may be split up
 ▪ 796cc42d3 patch 8.1.1104: MS-Windows: not all environment variables can be used
 ▪ 0eb035c97 patch 8.1.1103: MS-Windows: old API calls are no longer needed
 ▪ b26705afb patch 8.1.1102: Win32 exe file contains unused code
 ▪ 690a905a0 patch 8.1.1101: signals test may fail in the GUI
 ▪ fd700393b patch 8.1.1100: tag file without trailing newline no longer works
 ▪ b4a6020ac patch 8.1.1099: the do_tag() function is too long
 ▪ 95946f120 patch 8.1.1098: quickfix code duplication
 ▪ 4fc8e2f8b patch 8.1.1097: Motif build fails
 ▪ b70a47b77 patch 8.1.1096: MS-Windows: cannot distinguish BS and CTRL-H
 ▪ 866218973 patch 8.1.1095: MS-Windows: executable() fails on very long filename
 ▪ 5209334c5 patch 8.1.1094: long line in tags file causes error
 ▪ 96428dd4e patch 8.1.1093: support for outdated tags format slows down tag parsing
 ▪ 372674fca patch 8.1.1092: setting 'guifont' when maximized resizes the Vim window
 ▪ f0908e6fe patch 8.1.1091: MS-Windows: cannot use multi-byte chars in environment var
 ▪ 2d04a91d6 patch 8.1.1090: MS-Windows: modify_fname() has problems with some 'encoding'
 ▪ b44b7add8 patch 8.1.1089: tutor does not check $LC_MESSAGES
 ▪ 9e1e358d3 patch 8.1.1088: height of quickfix window not retained with vertical split
 ▪ 7559dcef6 patch 8.1.1087: tag stack is incorrect after CTRL-T and then :tag
 ▪ abab0b0fd patch 8.1.1086: too many curly braces
 ▪ bd9bf266f patch 8.1.1085: compiler warning for possibly uninitialized variable
 ▪ aff749145 patch 8.1.1084: cannot delete a match from another window
 ▪ 8bb41b3d0 patch 8.1.1083: MS-Windows: hang when opening a file on network share
 ▪ ab62c19ea patch 8.1.1082: "Conceal" match is mixed up with 'hlsearch' match.
 ▪ 433a5eb9d patch 8.1.1081: MS-Windows: cannot use some fonts
 ▪ ef7f0e367 patch 8.1.1080: when a screendump test fails, moving the file is a hassle
 ▪ 48aed0824 patch 8.1.1079: no need for a separate ScreenLinesUtf8() test function
 ▪ 5f8069bbf patch 8.1.1078: when 'listchars' is set a composing char on a space is wrong
 ▪ 9a2c091a7 patch 8.1.1077: reg_executing() is reset by calling input()
 ▪ 7591bb39d patch 8.1.1076: file for Insert mode is much too big
 ▪ de5b38004 patch 8.1.1075: function reference count wrong in Python code
 ▪ bfd360367 patch 8.1.1074: Python test doesn't wipe out hidden buffer
 ▪ e73f911c5 patch 8.1.1073: space in number column is on wrong side with 'rightleft' set
 ▪ 8ee4c01b8 patch 8.1.1072: extending sign and foldcolumn below the text is confusing
 ▪ 2912abb3a patch 8.1.1071: cannot get composing characters from the screen
 ▪ e46736b23 patch 8.1.1070: issue templates are not good enough
 ▪ 8ac8a77f2 patch 8.1.1069: source README file doesn't look nice on github
 ▪ fd133323d patch 8.1.1068: cannot get all the information about current completion
 ▪ 723d165c2 patch 8.1.1067: issues added on github are unstructured
 ▪ 89828e9fe patch 8.1.1066: VIMDLL isn't actually used
 ▪ 47cf1cc25 patch 8.1.1065: no test for using and deleting menu in the GUI
 ▪ c701f320e patch 8.1.1064: no test for output conversion in the GTK GUI
 ▪ 37db64208 patch 8.1.1063: insufficient testing for wildmenu completion
 ▪ a16123a66 patch 8.1.1062: quickfix code is repeated
 ▪ 0e97b9487 patch 8.1.1061: when substitute string throws error, substitute happens anyway
 ▪ 760285dd4 patch 8.1.1060: MS-Windows: get_cmd_args() is no longer needed
 ▪ 90d0cf69a patch 8.1.1059: MS-Windows: PlatformId() is called unnecessarily
 ▪ 3a731ee0c patch 8.1.1058: memory usage test may still fail on some systems
 ▪ 6a95c889b patch 8.1.1057: nsis config is too complicated
 ▪ e99be0e6d patch 8.1.1056: no eval function for Ruby
 ▪ 75bf3d22f patch 8.1.1055: CTRL-G U in Insert mode doesn't work for shift-Left
 ▪ 6fb5c9724 patch 8.1.1054: not checking return value of ga_grow()
 ▪ d6c3f1fa2 patch 8.1.1053: warning for missing return statement
 ▪ 553e5a5c5 patch 8.1.1052: test for CTRL-C message sometimes fails
 ▪ a4c2a24cc patch 8.1.1051: not all ways to switch terminal mode are tested
 ▪ 3dd174abb patch 8.1.1050: blank srceen when DirectWrite failed
 ▪ a84a3dd66 patch 8.1.1049: when user tries to exit with CTRL-C message is confusing
 ▪ b45125b37 patch 8.1.1048: minor issues with tests
 ▪ 63b74a836 Update runtime files.
 ▪ db77b84ac patch 8.1.1047: WINCH signal is not tested
 ▪ 82b033eff patch 8.1.1046: the "secure" variable is used inconsistently
 ▪ 63dbfd33c patch 8.1.1045: E315 ml_get error when using Python and hidden buffer
 ▪ c3e92c161 patch 8.1.1044: no way to check the reference count of objects
 ▪ b78286903 patch 8.1.1043: Lua interface does not support Blob
 ▪ 832615be1 patch 8.1.1042: the paste test doesn't work properly in the Windows console
 ▪ 295e3ba31 patch 8.1.1041: test for Arabic no longer needed
 ▪ b99abaa48 patch 8.1.1040: FEAT_TAG_ANYWHITE is not enabled in any build
 ▪ e37368c49 patch 8.1.1039: MS-Windows build fails
 ▪ dc4fa190e patch 8.1.1038: Arabic support excludes Farsi
 ▪ 6b6f7aae4 patch 8.1.1037: memory usage test may still fail on some systems
 ▪ 9afe5e9cc patch 8.1.1036: quickfix function arguments are inconsistent
 ▪ 0a2f578e2 patch 8.1.1035: prop_remove() second argument is not optional
 ▪ 2ace1bd65 patch 8.1.1034: too many #ifdefs
 ▪ ba64ba093 patch 8.1.1033: memory usage test may still fail on some systems
 ▪ 2c519cf3b patch 8.1.1032: warnings from clang static analyzer
 ▪ f7e47af77 patch 8.1.1031: memory usage test may still fail
 ▪ 0398e00a1 patch 8.1.1030: quickfix function arguments are inconsistent
 ▪ 60ebd524c patch 8.1.1029: DirectWrite doesn't take 'linespace' into account
 ▪ 9029b918f patch 8.1.1028: MS-Windows: memory leak when creating terminal fails
 ▪ 08cda65dd patch 8.1.1027: memory usage test sometimes fails
 ▪ d00e024d9 patch 8.1.1026: unused condition
 ▪ 64c8ed366 patch 8.1.1025: checking NULL pointer after addition
 ▪ 697005f2c patch 8.1.1024: stray log calls in terminal code
 ▪ 61be37633 patch 8.1.1023: may use NULL pointer when indexing a blob
 ▪ e142a9467 patch 8.1.1022: may use NULL pointer when out of memory
 ▪ 8e9a24a12 patch 8.1.1021: pyeval() and py3eval() leak memory
 ▪ 828bff1f9 patch 8.1.1020: compiler warning for Python3 interface
 ▪ 4eefe47ea patch 8.1.1019: Lua: may garbage collect function reference in use
 ▪ 8376c3d32 patch 8.1.1018: window cleared when entering Terminal-Normal twice
 ▪ 493fbe4ab patch 8.1.1017: off-by-one error in filetype detection
 ▪ 26967617a Update runtime files.
 ▪ 049ca5923 patch 8.1.1016: MS-Windows: No color in shell when using "!" in 'guioptions
 ▪ 647e24ba3 patch 8.1.1015: quickfix buffer shows up in list, can't get buffer number
 ▪ 38db5276c patch 8.1.1014: MS-Windows: /analyze only defined for non-debug version
 ▪ 3b5fef6a9 patch 8.1.1013: MS-Windows: Scrolling fails when dividing the screen
 ▪ ab89d7ab8 patch 8.1.1012: memory leak with E461
 ▪ 2ba423881 patch 8.1.1011: indent from autoindent not removed from blank line
 ▪ 713bf9e99 patch 8.1.1010: Lua interface leaks memory
 ▪ 1f271efbb patch 8.1.1009: MS-Windows: some text is not baseline aligned
 ▪ 0251d2d81 patch 8.1.1008: MS-Windows: HAVE_STDINT_H only defined for non-debug version
 ▪ 209b8e3e3 patch 8.1.1007: using closure may consume a lot of memory
 ▪ 4aa47b28f patch 8.1.1006: repeated code in quickfix support
 ▪ 55d81cd2a patch 8.1.1005: test fails because t_F2 is not set

 ▼ external/vixl/
 ▪ 33132247 libvixl: Disable use of dex2oat pgo profile [1/2]

 ▼ external/wpa_supplicant_8/
 ▪ 8610e284 Merge cherrypicks of [6716922, 6716923, 6716413, 6717023, 6717024, 6716716, 6715859, 6717160, 6717161, 6717162, 6717163, 6716295, 6717141, 6717181, 6717183, 6717184, 6717185, 6714937, 6717028, 6716717, 6716927, 6717200, 6717029, 6717030, 6717031, 6717032, 6717033, 6716928, 6717034, 6717035, 6716929, 6717201, 6716930, 6712377, 6712378, 6716643, 6717164, 6712379] into pi-qpr3-release
 ▪ 040d17d5 [wpa_supplicant] Fix security vulnerability wpa_supplicant/wnm_sta.c:376

 ▼ frameworks/av/
 ▪ 1a78f68a22 [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737 am: db59f63ffc am: e612be07a0 am: f98c4b76f6 am: ac98681b83 am: d8817bc29c am: 8194f1d220 am: 597ba8081b
 ▪ 597ba8081b [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737 am: db59f63ffc am: e612be07a0 am: f98c4b76f6 am: ac98681b83 am: d8817bc29c am: 8194f1d220
 ▪ 8194f1d220 [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737 am: db59f63ffc am: e612be07a0 am: f98c4b76f6 am: ac98681b83 am: d8817bc29c
 ▪ d8817bc29c [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737 am: db59f63ffc am: e612be07a0 am: f98c4b76f6 am: ac98681b83
 ▪ ac98681b83 [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737 am: db59f63ffc am: e612be07a0 am: f98c4b76f6
 ▪ f98c4b76f6 [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737 am: db59f63ffc am: e612be07a0
 ▪ e612be07a0 [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737 am: db59f63ffc
 ▪ db59f63ffc [automerger] NuPlayerCCDecoder: fix memory OOB am: 0f7ff70737
 ▪ 0f7ff70737 NuPlayerCCDecoder: fix memory OOB
 ▪ 5ec17e29aa Snap for 5443865 from b94a3d3e5461e6148bcb3be96f51e51c8f57c7e2 to pi-qpr3-b-release
 ▪ ec01e6f61d Merge cherrypicks of [6916730, 6913831, 6916555, 6916731, 6916732, 6916733, 6916734, 6916735, 6916736, 6916738, 6916739, 6916740, 6916741, 6916942, 6916715, 6916717, 6916718, 6916719, 6916720, 6916721, 6916962, 6916964, 6916966, 6916967, 6916968, 6916970, 6916972, 6916974] into pi-qpr3-b-release
 ▪ 3f176f572f setDequeueTimeout(-1) on the output surface
 ▪ 86f616a74c Snap for 5429421 from b94a3d3e5461e6148bcb3be96f51e51c8f57c7e2 to pi-qpr3-b-release
 ▪ b94a3d3e54 Merge "Camera: add QCIF resolution exception" into pi-dev
 ▪ 370a8e2628 Merge cherrypicks of [6909075, 6907367, 6908059, 6905571, 6905572, 6905573, 6905574, 6905575, 6905576, 6905577, 6905578, 6905579, 6905580, 6907712, 6907713, 6907714, 6907715, 6907716, 6907717, 6907718, 6907719, 6907720, 6907721, 6909142, 6909143, 6909144, 6909145] into pi-qpr3-b-release
 ▪ e397f431e2 setDequeueTimeout(-1) on the output surface
 ▪ 7307cc0f67 Camera: add QCIF resolution exception
 ▪ e1336214cd Snap for 5422807 from 34f058f9075820c2270238b3e49f524c9edc948e to pi-qpr3-b-release
 ▪ d2bd46115b Merge "av: stop puller before releasing encoder" into pie-gsi
 ▪ f73fa82ee9 av: stop puller before releasing encoder
 ▪ 7729649e9b Merge cherrypicks of [6841458, 6845109, 6844203, 6845110, 6845111, 6845112, 6845113, 6845114, 6845115, 6845116, 6845117, 6845118, 6845119, 6845376, 6845444, 6845377, 6844204, 6844205, 6844206, 6844207, 6844208, 6844209, 6844210, 6844211, 6844212, 6844213] into pi-qpr3-b-release
 ▪ 8ae9755560 setDequeueTimeout(-1) on the output surface
 ▪ 50b4ed6a98 Fixed audioserver crash in monkey test
 ▪ afc6302dfe audioflinger: do not idle thread if active tracks exist
 ▪ 55272b5233 audio: ensure effect chain with specific session id is unique
 ▪ b7b4d787d3 audioflinger: Throttle output if no active tracks
 ▪ a209cae7bb audio: don't apply ramp if track is paused before the first mix
 ▪ 995cf80e1b Request to reset effect buffer in clearInputBuffer
 ▪ e6bf186f8d [automerger] audio: ensure effect chain with specific session id is unique am: 5945746bca am: d2967d3fba am: 63539c399a am: d98b2019db am: a29ede5e56
 ▪ a29ede5e56 [automerger] audio: ensure effect chain with specific session id is unique am: 5945746bca am: d2967d3fba am: 63539c399a am: d98b2019db
 ▪ d98b2019db [automerger] audio: ensure effect chain with specific session id is unique am: 5945746bca am: d2967d3fba am: 63539c399a
 ▪ 63539c399a [automerger] audio: ensure effect chain with specific session id is unique am: 5945746bca am: d2967d3fba
 ▪ d2967d3fba [automerger] audio: ensure effect chain with specific session id is unique am: 5945746bca
 ▪ 5945746bca audio: ensure effect chain with specific session id is unique
 ▪ e786ae13e3 [automerger] AudioFlinger: Prevent multiple effect chains with same sessionId am: f963b2bfda am: fa4876957a am: 982715021c am: d6b2f10642 am: 426b85d639
 ▪ 426b85d639 [automerger] AudioFlinger: Prevent multiple effect chains with same sessionId am: f963b2bfda am: fa4876957a am: 982715021c am: d6b2f10642
 ▪ d6b2f10642 [automerger] AudioFlinger: Prevent multiple effect chains with same sessionId am: f963b2bfda am: fa4876957a am: 982715021c
 ▪ 982715021c [automerger] AudioFlinger: Prevent multiple effect chains with same sessionId am: f963b2bfda am: fa4876957a
 ▪ fa4876957a [automerger] AudioFlinger: Prevent multiple effect chains with same sessionId am: f963b2bfda
 ▪ f963b2bfda AudioFlinger: Prevent multiple effect chains with same sessionId
 ▪ a24ab5c987 Merge cherrypicks of [6716922, 6716923, 6716413, 6717023, 6717024, 6716716, 6715859, 6717160, 6717161, 6717162, 6717163, 6716295, 6717141, 6717181, 6717183, 6717184, 6717185, 6714937, 6717028, 6716717, 6716927, 6717200, 6717029, 6717030, 6717031, 6717032, 6717033, 6716928, 6717034, 6717035, 6716929, 6717201, 6716930, 6712377, 6712378, 6716643, 6717164, 6712379] into pi-qpr3-release
 ▪ ea5aa166f8 Reserve enough space for RTSP CSD
 ▪ b4a78584e5 Reserve enough space for RTSP CSD
 ▪ 96bbdd1561 Snap for 5363709 from 34f058f9075820c2270238b3e49f524c9edc948e to pi-qpr3-b-release

 ▼ frameworks/base/
 ▪ bed6193b595 [RESTRICT_AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage
 ▪ 20007cb46fa [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b am: 39f5432697 am: 9c0bc5405e am: 55209aca88 am: d5ce9a41b6
 ▪ d5ce9a41b6f [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b am: 39f5432697 am: 9c0bc5405e am: 55209aca88
 ▪ 55209aca882 [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b am: 39f5432697 am: 9c0bc5405e
 ▪ 9c0bc5405e1 [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b am: 39f5432697
 ▪ 39f54326978 [automerger] Limit IsSeparateProfileChallengeAllowed to system callers am: 9061fcc46b
 ▪ 9061fcc46bb Limit IsSeparateProfileChallengeAllowed to system callers
 ▪ 1b6301cf243 Limit IsSeparateProfileChallengeAllowed to system callers
 ▪ f4e7659df7c Fix Russian translation
 ▪ 801aa2dc7b3 base: Fix crash when changing default phone app
 ▪ 19dbbcc8a01 Less aggressive way of updating mobile type icons
 ▪ 73ed8e9f65b [automerger] [RESTRICT AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage am: a2b2e377a0 am: 00121902b0 am: 777c45416e am: 0bf87880d8 skipped: 9f3fca716a
 ▪ 9f3fca716a4 [automerger] [RESTRICT AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage am: a2b2e377a0 am: 00121902b0 am: 777c45416e am: 0bf87880d8
 ▪ f8db29bdf51 Merge changes from topic "am-e391c592-eeb3-4cc9-85fd-fa5d3bf694c5" into oc-dev am: 2833e406e0 am: ed9361ce1c am: f5c11a0a27
 ▪ 0bf87880d8a [automerger] [RESTRICT AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage am: a2b2e377a0 am: 00121902b0 am: 777c45416e
 ▪ 777c45416ee [automerger] [RESTRICT AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage am: a2b2e377a0 am: 00121902b0
 ▪ 00121902b01 [automerger] [RESTRICT AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage am: a2b2e377a0
 ▪ a2b2e377a0a [RESTRICT AUTOMERGE]: Add cross user permission check - areNotificationsEnabledForPackage
 ▪ 6b830afbad0 Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 18e7dedf6c am: 5e3ef6a1ea am: 4ff24d34d3
 ▪ f5c11a0a271 Merge changes from topic "am-e391c592-eeb3-4cc9-85fd-fa5d3bf694c5" into oc-dev am: 2833e406e0 am: ed9361ce1c
 ▪ 4ff24d34d38 Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 18e7dedf6c am: 5e3ef6a1ea
 ▪ ed9361ce1ca Merge changes from topic "am-e391c592-eeb3-4cc9-85fd-fa5d3bf694c5" into oc-dev am: 2833e406e0
 ▪ 2833e406e07 Merge changes from topic "am-e391c592-eeb3-4cc9-85fd-fa5d3bf694c5" into oc-dev
 ▪ 5e3ef6a1ea6 Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 18e7dedf6c
 ▪ d63b2d51026 Merge "Snap for 5310204 from 1b1681a8b0a3f95062c8f6f7fe31890629264e37 to pi-platform-release am: a104dea550" into pie-gsi
 ▪ 8d0b5aa0b4b Snap for 5310204 from 1b1681a8b0a3f95062c8f6f7fe31890629264e37 to pi-platform-release am: a104dea550
 ▪ a104dea550a Snap for 5310204 from 1b1681a8b0a3f95062c8f6f7fe31890629264e37 to pi-platform-release
 ▪ 46aaa416855 SystemUI: fix no service and emergency calls only placement
 ▪ 4c14c6f1016 qs_footer: Update visibilities after inflate finish
 ▪ 8b38a1048d9 base: Add OnePlus Red accent [1/3]
 ▪ 30e596483e7 base: Add Black Pearl theme [1/3]
 ▪ 0f6516d6d66 Custom logo customizations [1/2]
 ▪ 1b3f820fa7a Use alphaoptimized layout for custom icons on left
 ▪ aeaa4570a2b Slim recents old enter/exit animation [1/3]
 ▪ 1d9d566eb24 base: LS filters: Add 2 more variants
 ▪ 8e5c88b1ea6 [automerger] [RESTRICT AUTOMERGE] Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 7b5a576965 am: 0494ac6568 am: 70b534799b am: 49a505f4f9 skipped: 022bfaa808
 ▪ 022bfaa8088 [automerger] [RESTRICT AUTOMERGE] Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 7b5a576965 am: 0494ac6568 am: 70b534799b am: 49a505f4f9
 ▪ 49a505f4f9b [automerger] [RESTRICT AUTOMERGE] Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 7b5a576965 am: 0494ac6568 am: 70b534799b
 ▪ 70b534799b8 [automerger] [RESTRICT AUTOMERGE] Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 7b5a576965 am: 0494ac6568
 ▪ 0494ac65682 [automerger] [RESTRICT AUTOMERGE] Added missing permission check to isPackageDeviceAdminOnAnyUser. am: 7b5a576965
 ▪ 7b5a5769656 [RESTRICT AUTOMERGE] Added missing permission check to isPackageDeviceAdminOnAnyUser.
 ▪ 2408cfa7d3e base: Optimize toGrayscale function
 ▪ 5640564aa1a base: Intensify the blur amount on LS cover art
 ▪ 1f0748607e8 base: Fix old mobile signal icons
 ▪ 4355645372b Add wakelock option for flashlight
 ▪ ea44fa0a9bf Fix screen pinning unlock with hwkeys
 ▪ e193ec51006 Allow screen unpinning on devices without navbar
 ▪ 2fd3c37f9d2 core: Implement Aggressive Battery [1/2]
 ▪ 2d3e72f6fd8 Smart Pixels: Update default grid pattern
 ▪ 4ff0ccb6fd5 Smart Pixels: Bypass check for obscured window
 ▪ 6ece3a62a2e Smart Pixels: Dynamically register receiver
 ▪ df3742a3fe0 EdgeGestures: fix unregistering input filter
 ▪ 3725afa3049 ImageUtils: Switch blur lib to SimpleImageBlur
 ▪ 18e7dedf6c3 Added missing permission check to isPackageDeviceAdminOnAnyUser.
 ▪ 1517310f064 Snap for 5429421 from 5b09928b2273cff78f64673e0ac8459ffe0f16bc to pi-qpr3-b-release
 ▪ 5b09928b227 Merge "Camera: add QCIF resolution exception" into pi-dev
 ▪ bac95159512 Merge tag 'android-9.0.0_r35' into pie
 ▪ 8617b162174 Merge "Catch egl errors when drawIntoSurfaces" into pie-gsi
 ▪ 4a127c6ce48 GamingModeTile: stop adjusting volume
 ▪ 0f3746cca3b Catch egl errors when drawIntoSurfaces
 ▪ 428256d2588 Camera: add QCIF resolution exception
 ▪ 5e994a3c4a8 LTE tile: Remove oreo style slashes
 ▪ 24005c2812a base: Add Lockscreen cover art filter [1/2]
 ▪ 77368697353 ImageHelper: add getBlurredImage
 ▪ 4bfb71245d1 Dreamliner: Disable DockObserver conditionally
 ▪ dc5a685b6eb Dreamliner: Reorganise the external repo [2/2]
 ▪ 077ba49cf29 ActionUtils: Reverse actions for QS and notification panel
 ▪ 5354d7ae854 Active Edge: allow to choose a specific app activity [4/4]
 ▪ 05ad0b3835d Introduce long squeeze action [3/3]
 ▪ fcb37a8eeb2 Snap for 5422807 from 9bdc35b2dfa6cc95d08efa589cfffb6ab9b2aeb1 to pi-qpr3-b-release
 ▪ 9bdc35b2dfa Merge "DO NOT MERGE Make a copy of data stored in LockSettingsStorage cache" into pi-dev
 ▪ 157f05eb043 Merge "DO NOT MERGE Refactor passwords/pins/patterns to byte[]" into pi-dev
 ▪ 0c9ce0913c7 Merge "DO NOT MERGE Atoms: Add BluetoothClassicPairingEvent" into pi-dev
 ▪ 19072e7f7e9 Snap for 5408106 from 1b82db4c3e129b2e0baff9008739948d63352857 to pi-qpr3-b-release
 ▪ 895f1c10326 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ ffb83eb07ce Ambient music ticker: fix text scrolling on AoD
 ▪ 9f15d22758b Merge "DO NOT MERGE Fix CtsActivityManagerDeviceTestCases fails" into pie-gsi
 ▪ a7c959176c5 [automerger] Permission Check For DPM.getPermittedAccessibilityServices am: 4fd13eefcf am: 39eef269be am: 5d66886b4c am: 75b579135c am: 0f19d41748
 ▪ 0f19d417480 [automerger] Permission Check For DPM.getPermittedAccessibilityServices am: 4fd13eefcf am: 39eef269be am: 5d66886b4c am: 75b579135c
 ▪ 75b579135c2 [automerger] Permission Check For DPM.getPermittedAccessibilityServices am: 4fd13eefcf am: 39eef269be am: 5d66886b4c
 ▪ 5d66886b4cd [automerger] Permission Check For DPM.getPermittedAccessibilityServices am: 4fd13eefcf am: 39eef269be
 ▪ 39eef269bee [automerger] Permission Check For DPM.getPermittedAccessibilityServices am: 4fd13eefcf
 ▪ 0f3d6534bca DO NOT MERGE Fix CtsActivityManagerDeviceTestCases fails
 ▪ 49b7a55cd73 Import translations. DO NOT MERGE
 ▪ 38c5771c613 base: Adaptive icon system-wide setting [1/3]
 ▪ 3ec9f6862a1 base: Fix partial screenshot
 ▪ 8b16537b9c9 SettingsLib: Increase battery saver outline thickness
 ▪ 4fd13eefcf9 Permission Check For DPM.getPermittedAccessibilityServices
 ▪ f6419292167 SystemUI: Fix multiuser icon glitch in QS footer
 ▪ 4b53510542a SystemUI: Add Cellular tile icon from OOS
 ▪ 9f4f73efb0d Revert "Navbar: Do not fiddle with haptic feedback"
 ▪ a0f527fffa0 base: Cleanup SystemUI tuner
 ▪ 1b82db4c3e1 Import translations. DO NOT MERGE
 ▪ 0375302fffc ColorFade: Silence logspam
 ▪ b12bd87ccc9 Revert "Revert "base: screen off animation config [1/2]""
 ▪ 478e7efeba3 base: Make vendor mismatch message optional
 ▪ 3df01015f8e base: Let's use MD2 icons for Powermenu
 ▪ 63d6be741a9 Revert "ViewRoot: Ensure we release surface from setWindowStopped"
 ▪ c7c72b0413c core: view: Add property to disable VSync for CPU rendered apps
 ▪ d0872f29380 add VSYNC scheduled flag and avoid two doFrame calls in one period
 ▪ 68b8fe7203c Fix potential crash when per-procstate cpu times tracking is turned on
 ▪ 3c5931cd60f Return null on failed insert due to permissions
 ▪ 27c88efd79d Fix RouterAdvertisementDaemon thread leakage problem
 ▪ bd9d1e9789a Volume panel: Fix incorrect positioning
 ▪ ffcdf0ae2cb OP Gestures: Fix navbar detection and landscape mode
 ▪ 1a19739c3f5 SettingsLib: Bring the dividers back to life
 ▪ 19e91055d24 QSPanel: Always show divider like OOS
 ▪ fd2b666609f base: Persistent settings icon on qs panel for 9.x
 ▪ c99131b338f Revert "base: SystemUI: add tuner to hide qs drag handle"
 ▪ e9add4667c3 Revert "services: allow to force "never" mode for display cutout [1/2]"
 ▪ 5098a447397 Ambient music ticker: fix text scrolling glitches
 ▪ 4eb5f92764b Improve ambient play layout on keyguard
 ▪ a06b2c4cb89 Ambient music: do not extend pulse notification when not needed
 ▪ ba8c13ff863 Revert "Ambient music: Use animated icon"
 ▪ 6110c95184c DO NOT MERGE Atoms: Add BluetoothClassicPairingEvent
 ▪ 567f2357f9f DO NOT MERGE Make a copy of data stored in LockSettingsStorage cache
 ▪ 820b2504f36 DO NOT MERGE Refactor passwords/pins/patterns to byte[]
 ▪ fda3be78eee Snap for 5385651 from ddaa6338c89cc17388f4f9b86594fa2869bf1101 to pi-qpr3-b-release
 ▪ aa704a30f35 Merge "DO NOT MERGE Let isLocationEnabledForUser() return true location setting" into pie-gsi
 ▪ ddaa6338c89 Merge "Revert "Revert "Update VPN capabilities when its underlying network set is null.""" into pi-dev
 ▪ a24113f030b Merge "Remove ConnectivityManager and its usages from NetworkStatsService." into pi-dev
 ▪ f17d05b748f DO NOT MERGE Let isLocationEnabledForUser() return true location setting
 ▪ 76e5e4eeace Clean up screenshot if nothing selected
 ▪ 6edf3897716 IMMS should preserve selected IME upon boot
 ▪ a4334517999 Add bluetooth icon.
 ▪ 322b446a4d5 base: Cleanup FP controller
 ▪ 8a6383d3c9f SystemUI: Reduce padding between wifi and signal icon
 ▪ 844892ef4de KeyguardStatusBarView: Request batteryview update only when required
 ▪ aeb43aa95ad PowerManager: Don't bother devices not using wait for MPCTL
 ▪ 6d684a1803d PerformanceManager: Allow wait for MPCTL to start on boot
 ▪ 67e063df5c4 AudioService: Fix camera shutter sound toggle
 ▪ c48b25b0fe9 Navbar: Do not fiddle with haptic feedback
 ▪ c197ee75bcf SystemUI: Separate global actions theme from qs
 ▪ 9f98789d3f3 Revert "Revert "Update VPN capabilities when its underlying network set is null.""
 ▪ 1321215e460 Re-add WPS implementation (2/3)
 ▪ d2ceb722e11 base: Fix less frequent notification sounds value
 ▪ 357ab2a8045 base: Add vibrate util methods
 ▪ de6005fee92 base: Turn on display if Doze On Charge is Enabled
 ▪ c2ce0cd906e Volume panel: Add notification volume row if unlinked
 ▪ 1c43a913abd Code improvements for expanded volume panel
 ▪ 007ea41e0ea Merge "Should return the number of supported SIM cards" into pie-gsi
 ▪ 4822c23a095 Snap for 5375030 from b0103b5ebba3b7beb8b5836228fb0b07254bb4c6 to pi-qpr3-b-release
 ▪ 30d420e91bc Should return the number of supported SIM cards
 ▪ a64871a54da Volume panel: Visual improvements
 ▪ b0103b5ebba Change target SDK to '28'
 ▪ 2a21bea448c Merge cherrypicks of [6716922, 6716923, 6716413, 6717023, 6717024, 6716716, 6715859, 6717160, 6717161, 6717162, 6717163, 6716295, 6717141, 6717181, 6717183, 6717184, 6717185, 6714937, 6717028, 6716717, 6716927, 6717200, 6717029, 6717030, 6717031, 6717032, 6717033, 6716928, 6717034, 6717035, 6716929, 6717201, 6716930, 6712377, 6712378, 6716643, 6717164, 6712379] into pi-qpr3-release
 ▪ 645724023a9 DO NOT MERGE: Don't let previous activity wait if next activity won't be visible
 ▪ 7cc0421a736 DO NOT MERGE Add carrier config to use 3GPP application on CDMA/CDMA-LTE phone.
 ▪ 0aa677c7590 Revert "Update VPN capabilities when its underlying network set is null."
 ▪ d374204d68d DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot
 ▪ 9e04b0d2695 base: Redo expanded volume panel for 9.x
 ▪ 9dd6055f3b2 Merge "DO NOT MERGE: Don't let previous activity wait if next activity won't be visible" into pie-gsi
 ▪ 28a5a76c8db DO NOT MERGE: Don't let previous activity wait if next activity won't be visible
 ▪ 33d7fccb005 DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot
 ▪ 2eec1279c61 Merge "DO NOT MERGE: Don't let previous activity wait if next activity won't be visible" into pi-dev
 ▪ f55f113a75b Volume panel: Do the same with less
 ▪ 6491c1a654e Volume panel: Fixes for unlinked notifications
 ▪ aa677d1f0f9 Snap for 5369966 from dfd3a1b8522a42ba3a713d62cae04b00bf46f044 to pi-qpr3-b-release
 ▪ d0e8013be14 Revert "Extended audio panel [1/2]"
 ▪ dfd3a1b8522 Merge "onPageFinished javadoc cleanup" into pi-dev
 ▪ ce222afda74 onPageFinished javadoc cleanup
 ▪ 69cdb751566 base: Code improvements QS footer visibilities
 ▪ 4ccfc811e87 BatteryMeterView: Fix logcat spam
 ▪ 1d8fbbe9be2 Snap for 5363709 from 04d262db157f15c2d822708e57715d80e3f14585 to pi-qpr3-b-release

 ▼ frameworks/native/
 ▪ 78a11714d Snap for 5443865 from 94c1d740cfe001e5faf62d3c447c4e1e9f4aa325 to pi-qpr3-b-release
 ▪ 67c374eec Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into pie
 ▪ 8ec19d04d Merge 8652fe445c1562eabc327fcebec65e81238a6ef8 on remote branch
 ▪ a259a78f7 Snap for 5436220 from 99f039ae639d05fe07c2908f39ddef1c6ab54064 to p-keystone-qcom-release
 ▪ 81513a128 Snap for 5431430 from ef4f48b5b6a845ee6e51ad9749ce4a505b4d75fd to p-keystone-qcom-release
 ▪ 99f039ae6 sf: Clean up vsync switch implementation.
 ▪ bbd1669c4 Merge cherrypicks of [6916730, 6913831, 6916555, 6916731, 6916732, 6916733, 6916734, 6916735, 6916736, 6916738, 6916739, 6916740, 6916741, 6916942, 6916715, 6916717, 6916718, 6916719, 6916720, 6916721, 6916962, 6916964, 6916966, 6916967, 6916968, 6916970, 6916972, 6916974] into pi-qpr3-b-release
 ▪ 8f7b62748 RESTRICT AUTOMERGE BQ: retain buffer drop from BufferQueueProducer
 ▪ 4012cda2a Snap for 5429421 from 94c1d740cfe001e5faf62d3c447c4e1e9f4aa325 to pi-qpr3-b-release
 ▪ 6dc3d8936 Merge cherrypicks of [6909075, 6907367, 6908059, 6905571, 6905572, 6905573, 6905574, 6905575, 6905576, 6905577, 6905578, 6905579, 6905580, 6907712, 6907713, 6907714, 6907715, 6907716, 6907717, 6907718, 6907719, 6907720, 6907721, 6909142, 6909143, 6909144, 6909145] into pi-qpr3-b-release
 ▪ cf4ab6166 RESTRICT AUTOMERGE BQ: retain buffer drop from BufferQueueProducer
 ▪ 902f8c681 Snap for 5422807 from 94c1d740cfe001e5faf62d3c447c4e1e9f4aa325 to pi-qpr3-b-release
 ▪ ef4f48b5b sf: Set FIFO priority if any of the displays is active.
 ▪ 428fdcd5c Snap for 5421909 from 6a1871889b29b7b0677c535e49386bae7b83d35c to p-keystone-qcom-release
 ▪ 6a1871889 Merge "Merge SPL-2019-03-05" into p-keystone-qcom
 ▪ 84ef2f945 Snap for 5415625 from f7538cc7c4ca6dda0cecc7c602afe3bd06935bb5 to p-keystone-qcom-release
 ▪ f7538cc7c Merge "sf: Remove display from active displays list upon disconnect" into p-keystone-qcom
 ▪ 0a93e1f17 Merge "sf: Force model update on boot." into p-keystone-qcom
 ▪ ebe3748c5 Snap for 5410636 from 9c91d30ee36b6d84284152dc4d33719606a0711e to p-keystone-qcom-release
 ▪ b11d290e1 Merge cherrypicks of [6841458, 6845109, 6844203, 6845110, 6845111, 6845112, 6845113, 6845114, 6845115, 6845116, 6845117, 6845118, 6845119, 6845376, 6845444, 6845377, 6844204, 6844205, 6844206, 6844207, 6844208, 6844209, 6844210, 6844211, 6844212, 6844213] into pi-qpr3-b-release
 ▪ 8d75246dc RESTRICT AUTOMERGE BQ: retain buffer drop from BufferQueueProducer
 ▪ 9c91d30ee [SurfaceFlinger] Checking nullptr for HWC layer
 ▪ 9182c9f67 sf: Remove display from active displays list upon disconnect
 ▪ 963815195 sf: Force model update on boot.
 ▪ f4a0415e2 Merge SPL-2019-03-05
 ▪ 8652fe445 Snap for 5370022 from 8d376bde6f0972dcfdd4bdf2701fd4af0d09c4f7 to p-keystone-qcom-release
 ▪ 8d376bde6 Merge "sf : fix dolphin use case race condition" into p-keystone-qcom
 ▪ 4c602fbf3 sf : fix dolphin use case race condition
 ▪ 2d6a1d8a4 sf: remove mustRecompose check to drop refresh cycles

 ▼ frameworks/opt/net/wifi/
 ▪ 93882b9c4 wifi: Use WifiStateMachine looper for TrafficPoller.
 ▪ e38af068c Snap for 5448897 from 448c6d8e67752026860fcd0a58a65b41dc228821 to p-keystone-qcom-release
 ▪ f88d296d3 DO NOT MERGE Add data integrity checking for wifi passwords
 ▪ 448c6d8e6 Merge "wifi: Add support for wifi latency level using vendor wifi@1.0" into p-keystone-qcom
 ▪ ec545c2ba wifi: Handle wifi ON state while processing CMD_DELAY_DISCONNECT.
 ▪ 60c2e8c40 Merge a45b60490d58e1f484bec36abd557ea4a8ef75ee on remote branch
 ▪ 39bba6a46 Snap for 5424637 from 1b111027c4a8193f24fe06fef2465327669e4ab4 to p-keystone-qcom-release
 ▪ 1b111027c Merge "WifiVendorHal: improve handling of HalDeviceManager callback" into p-keystone-qcom
 ▪ 3d9826b0c Snap for 5415625 from eb9f752d3fb9e52b28e314cba40548219a064055 to p-keystone-qcom-release
 ▪ eb9f752d3 Merge "wifi: Retain wifi state after airplane mode toggle." into p-keystone-qcom
 ▪ bec640a96 Snap for 5410636 from eef4aeaed7a2240e367cfc30b9e4197512f791ea to p-keystone-qcom-release
 ▪ 93b86b54f Snap for 5407983 from f11fe21de4fc0c3e0c20cbe112e2a21ad9df9244 to p-keystone-qcom-release
 ▪ eef4aeaed Merge "wifi: Stop hostapd only when there are no active IFACE_TYPE_AP" into p-keystone-qcom
 ▪ f11fe21de Merge "Do not deviate from the default expectations set on WIFI_SAVED_STATE" into p-keystone-qcom
 ▪ ffc81a539 WifiVendorHal: improve handling of HalDeviceManager callback
 ▪ b6b9c7e45 wifi: Retain wifi state after airplane mode toggle.
 ▪ cc782b1a2 Do not deviate from the default expectations set on WIFI_SAVED_STATE
 ▪ 65c666ec1 wifi: Stop hostapd only when there are no active IFACE_TYPE_AP
 ▪ 79d8a51e0 wifi: Native registerForNotifications to pass the "default" instance name.
 ▪ 1d20bcb7d Re-add WPS implementation (3/3)
 ▪ 18362e15d Snap for 5375030 from 84522169bed37020285a7484067b64c4161d8c5b to pi-qpr3-b-release
 ▪ 1ed8ffb8f Merge cherrypicks of [6716922, 6716923, 6716413, 6717023, 6717024, 6716716, 6715859, 6717160, 6717161, 6717162, 6717163, 6716295, 6717141, 6717181, 6717183, 6717184, 6717185, 6714937, 6717028, 6716717, 6716927, 6717200, 6717029, 6717030, 6717031, 6717032, 6717033, 6716928, 6717034, 6717035, 6716929, 6717201, 6716930, 6712377, 6712378, 6716643, 6717164, 6712379] into pi-qpr3-release
 ▪ 223155001 Revert "DO NOT MERGE Add data integrity checking for wifi passwords"
 ▪ 84522169b Revert "DO NOT MERGE Add data integrity checking for wifi passwords"
 ▪ a45b60490 Snap for 5366464 from 109bbc76eea12e99be090be31c9b4dafd3746b85 to p-keystone-qcom-release
 ▪ 109bbc76e Merge "P2P: Avoid P2P initialization after continuous setup failures." into p-keystone-qcom

 ▼ frameworks/opt/slimrecent/
 ▪ 42bbeeb Slim recents old enter/exit animation [2/3]
 ▪ e282441 Slimrecents: catch IllegalArgumentException too

 ▼ frameworks/opt/telephony/
 ▪ 5d87fd60c5 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into caf
 ▪ c3aed91789 Merge 1439b2240e7cea8dc294c276170e08425efac63c on remote branch
 ▪ d35c8cd447 Merge 1439b2240e7cea8dc294c276170e08425efac63c on remote branch
 ▪ c43e22a964 Merge 1439b2240e7cea8dc294c276170e08425efac63c on remote branch
 ▪ 1bfb72160d Snap for 5395070 from 9d2b1e40235b081f19c31361ff629ef339431e4a to p-keystone-qcom-release
 ▪ 9d2b1e4023 Merge "Fix ANR after setup data call with failure" into p-keystone-qcom
 ▪ fe4b8179b6 Snap for 5385651 from abd2e6056a57aba0f55b8f2b8ae6f0ce5a8ab2f3 to pi-qpr3-b-release
 ▪ abd2e6056a Merge "Remove getAllVpnInfo from ConnectivityServiceMock." into pi-dev
 ▪ 4ea0190392 Merge cherrypicks of [6716922, 6716923, 6716413, 6717023, 6717024, 6716716, 6715859, 6717160, 6717161, 6717162, 6717163, 6716295, 6717141, 6717181, 6717183, 6717184, 6717185, 6714937, 6717028, 6716717, 6716927, 6717200, 6717029, 6717030, 6717031, 6717032, 6717033, 6716928, 6717034, 6717035, 6716929, 6717201, 6716930, 6712377, 6712378, 6716643, 6717164, 6712379] into pi-qpr3-release
 ▪ 42e7097adc DO NOT MERGE Return MSISDN as Line1 number if carrier config requires it.
 ▪ 6605646e28 Snap for 5363709 from 1b75d80ffff871e31a69d77a865c8309ed64c6ff to pi-qpr3-b-release

 ▼ hardware/interfaces/
 ▪ 648c163f7 Merge "wifi: Add wifi latency level support to vendor wifi@1.0" into p-keystone-qcom
 ▪ 88e0d4a9f Merge bf1767d55ecf08dfeafefa0995a5a2fccebc33a8 on remote branch
 ▪ b92650762 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ d835949c4 Merge bf1767d55ecf08dfeafefa0995a5a2fccebc33a8 on remote branch
 ▪ 3a1916e9d Snap for 5422807 from 1905955bafb569ddfa676597e45e2218a834f3e3 to pi-qpr3-b-release
 ▪ f799a688f Merge tag 'LA.UM.7.6.2.r1-07600-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 1905955ba wifi(vts): Don't enforce interface combination in VTS tests am: f638d0a43a
 ▪ f638d0a43 wifi(vts): Don't enforce interface combination in VTS tests
 ▪ 8842304a8 Merge fac3cc17c59b4a82beda9fdda312bb4f5b8963b2 on remote branch
 ▪ 6ae4f1e7f Snap for 5375030 from e3c3d56907af23d92e74a355b50a2f97c6938aa7 to pi-qpr3-b-release
 ▪ e3c3d5690 Merge "Sleep one second after connect." into pie-vts-dev am: e1704f3fd6
 ▪ e1704f3fd Merge "Sleep one second after connect." into pie-vts-dev
 ▪ cbeda2839 Merge "VTS tests to work with depth Y16" into pie-vts-dev am: 0e802961e2
 ▪ 0e802961e Merge "VTS tests to work with depth Y16" into pie-vts-dev
 ▪ f0047a84c Snap for 5369966 from b77950c85041af1be64085d6445dcd99b501de7c to pi-qpr3-b-release
 ▪ b2aa43ae9 Sleep one second after connect.
 ▪ b77950c85 Merge changes from topic "healthd_vts_skip" into pie-vts-dev am: a35c8253db
 ▪ a35c8253d Merge changes from topic "healthd_vts_skip" into pie-vts-dev
 ▪ f31fd7f8c omx:component: add support for tunneled components in ComponentTest am: 4609857ee4

 ▼ hardware/libhardware_legacy/
 ▪ f46f6b0 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/libhardware_legacy into 9.0

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 0e3d5f4c Merge "hal: restore device for other active usecases when VOICE stopped"
 ▪ 4f4f95a9 Merge "hal: retry all of un-detected sound card"
 ▪ 6b2274c6 hal: Increase ffv process thread priority
 ▪ 799d8071 Merge "hal: align ref_cnt of combo device and its split devices"
 ▪ 027b48bb Merge "configs: sdm660: update hal buffering configuration"
 ▪ fdd87778 Merge "post_proc: release vol listener object based on context"
 ▪ 5466b284 Merge 2b86010b2d51c43969cbd73a26c15a1d0ee49622 on remote branch
 ▪ 0ff50458 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' into 9.0
 ▪ d9da833b hal: fix no sound issue when using some USB headset.
 ▪ 79596197 Merge 2b86010b2d51c43969cbd73a26c15a1d0ee49622 on remote branch
 ▪ 60c17e7c hal: restore device for other active usecases when VOICE stopped
 ▪ 3b7089ae post_proc: release vol listener object based on context
 ▪ d8e23b7a Merge tag 'LA.UM.7.6.2.r1-07600-89xx.0' into 9.0
 ▪ 22c9723c add support for msm8996-tasha-mtp-snd-card
 ▪ d7ba5d3e hal: align ref_cnt of combo device and its split devices
 ▪ 597a47e9 configs: sdm660: update hal buffering configuration
 ▪ c6cbd762 Merge 079d264c0ed9e99b4f3f739de096d37fd1da748f on remote branch
 ▪ 2b86010b hal: Fix incall recording calibration issue
 ▪ 54717d81 Merge 39f686088cb387fa10fd8bda1098b26096fbe88e on remote branch
 ▪ 079d264c Merge "hal: Avoid setting wrong sample rate for headset device"
 ▪ 5045a5a1 Merge "hal: Add missing entries for voice speaker stereo."
 ▪ 8fcfc258 Merge tag 'LA.UM.7.6.2.r1-07300-89xx.0' into 9.0
 ▪ fc743088 hal: Avoid setting wrong sample rate for headset device
 ▪ 0457c449 hal: Add missing entries for voice speaker stereo.
 ▪ 39f68608 hal: Update TX capabilities when adding USB output device as well.
 ▪ 363b9422 Merge "hal: set default sample rate during voice/voip call"
 ▪ 6b6e2688 hal: spk_prot: Update lock for v-validation and timestamp calculation

 ▼ hardware/qcom/bt-caf/
 ▪ da0b9d7 Merge 9573899be2ff2b9d387d549608feea0617e26dec on remote branch
 ▪ ac84067 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' into 9.0
 ▪ debfa83 Merge 9573899be2ff2b9d387d549608feea0617e26dec on remote branch
 ▪ 9573899 Send Peer device MTU value in case of AAC codec to MM.

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ 21177de1 hwc :  Add null display during bootup.
 ▪ 7af887da Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0
 ▪ 835bbf94 Merge 091cd20be54ef70f58526bc84604ffc8932d57b1 on remote branch
 ▪ d4569ea9 Merge 091cd20be54ef70f58526bc84604ffc8932d57b1 on remote branch
 ▪ 5c4d6148 Merge 10cb74856ac429e18348742f48667d8ef1c27a1b on remote branch
 ▪ 091cd20b Merge "sdm: Trigger safemode on primary when secure starts on external"
 ▪ 9917784c Merge "Revert "display: Replace libqdmetadata.system with libqdmetadata""
 ▪ 66e7aca7 sdm: Trigger safemode on primary when secure starts on external
 ▪ 5cffa56e Revert "display: Replace libqdmetadata.system with libqdmetadata"
 ▪ cdddbab4 hwc2: Do not honor cursor position when cursor layer is not present

 ▼ hardware/qcom/fm/

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 1bb1cb64 Merge "venc: Add support for secure input port"
 ▪ 501fd831 Merge 035814827739ef53dd6420413dea5e891fdc80f4 on remote branch
 ▪ b17e46c0 mm-video-v4l2: Add support for CbYCrY color format in c2d
 ▪ 88fb23ff venc: Add support for secure input port
 ▪ 03581482 sideband: Fix VNDK compilation issue in sidebandstreamhandle

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ a52ba63b4 Merge b17e46c06449a8e269b445695a7ef08430ebc65b on remote branch
 ▪ 1bb1cb646 Merge "venc: Add support for secure input port"
 ▪ b17e46c06 mm-video-v4l2: Add support for CbYCrY color format in c2d
 ▪ db1fdf072 Merge 035814827739ef53dd6420413dea5e891fdc80f4 on remote branch
 ▪ 88fb23ff6 venc: Add support for secure input port
 ▪ 035814827 sideband: Fix VNDK compilation issue in sidebandstreamhandle

 ▼ hardware/qcom/wlan-caf/
 ▪ 8148b24 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' into 9.0
 ▪ 41ad0b8 Merge 3a03588b7727af2b5dfc142cfd269b0ac894b65d on remote branch
 ▪ 87c3e54 Merge tag 'LA.UM.7.6.2.r1-07600-89xx.0' into 9.0
 ▪ 0317a78 Merge 4cbafc31a019e7d6d12c4482a81c3a392ed9f9f6 on remote branch
 ▪ 6377238 Merge "WiFi-Hal: De-couple roaming feature with Gscan" into wlan-aosp.lnx.4.0
 ▪ e51fa2f Merge "WiFi-Hal : Decouple NUD track and Data stats." into wlan-aosp.lnx.4.0
 ▪ e7af054 WiFi-Hal: De-couple roaming feature with Gscan
 ▪ 87ccf6a Merge 3a03588b7727af2b5dfc142cfd269b0ac894b65d on remote branch
 ▪ b882739 Merge tag 'LA.UM.7.6.2.r1-07300-89xx.0' into 9.0
 ▪ 3a03588 Merge "wifi-hal: Add LOCAL_ADDITIONAL_DEPENDENCIES" into wlan-aosp.lnx.4.0
 ▪ cad97c8 wifi-hal: Add LOCAL_ADDITIONAL_DEPENDENCIES
 ▪ b1819f5 wifihal: Refine sigpipe fix to minimal change
 ▪ f36c54a WiFi-Hal : Decouple NUD track and Data stats.

 ▼ hardware/ril/
 ▪ 0b62ad32 Merge f342b3f55ebae0001df727a40c5c87f298128201 on remote branch

 ▼ kernel/xiaomi/msm8996/
 ▪ 9c927ca40501 diag: dci: Validate dci client entries prior read
 ▪ 44202f0d2e39 qcacld-2.0: CSA optimization for bandwidth switch
 ▪ 8f397ec8a923 Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into kernel.lnx.3.18.r34-rel
 ▪ 9135ea57b623 qcacld-2.0: Enable survey dump on SAP
 ▪ fca976b65e9f soc: qcom: qmi_encdec: Restrict string length in decode
 ▪ 48f95c885bc6 qcacld-2.0: Fix potential OOB read when indicate mgmt frame
 ▪ 26a0602fa0b7 Merge "dsp: q6usm: Release spinlock before return if invalid payload size"
 ▪ dffd1ffde350 Merge tag '67d84005cea13adb53525f2777310bae66b70632' into HEAD
 ▪ 71fd848bfb1e Merge branch 'kernel.lnx.3.18.r34-rel' of https://github.com/android-linux-stable/msm-3.18 into HEAD
 ▪ cf5c6666c21f Merge "drivers: soc: qcom: Added check to avoid opening multiple instance"
 ▪ f5dd60e3b7c0 Merge "dsp: afe: check for payload size before payload access"
 ▪ 969427f17aae qcacld-2.0: Support to pass HW version to userspace
 ▪ d82d2d34edd3 dsp: afe: check for payload size before payload access
 ▪ 5c92de2c9571 msm: adm: validate ADSP payload size before access
 ▪ 73c851075199 Merge cd2b065f83e92d23bd9600c9521f53848a2e26ef on remote branch
 ▪ d694a5f11081 Merge a3654a83a5ccf0574517103dd9dc1ce80527a582 on remote branch
 ▪ 119eb1c91ac4 dsp: q6usm: Release spinlock before return if invalid payload size
 ▪ 233870be3b30 Merge 3.18.138 into kernel.lnx.3.18.r34-rel
 ▪ a1a43d6522bc Linux 3.18.138
 ▪ 33807cfab9fd arm64: support keyctl() system call in 32-bit mode
 ▪ ecc5b776ffd0 ARM: imx6q: cpuidle: fix bug that CPU might not wake up at expected time
 ▪ 7e9e474e6448 xhci: Fix port resume done detection for SS ports with LPM enabled
 ▪ ffc2152394fb KVM: Reject device ioctls from processes other than the VM's creator
 ▪ 17874c300308 gpio: adnp: Fix testing wrong value in adnp_gpio_direction_input
 ▪ beb70e5c511c fs/proc/proc_sysctl.c: fix NULL pointer dereference in put_links
 ▪ 69c9fdb685b7 Disable kgdboc failed by echo space to /sys/module/kgdboc/parameters/kgdboc
 ▪ 30a07c0446cc USB: serial: mos7720: fix mos_parport refcount imbalance on error path
 ▪ 96c80c460995 USB: serial: ftdi_sio: add additional NovaTech products
 ▪ 62008c0dc3f7 USB: serial: cp210x: add new device id
 ▪ cdae8c6fc96e serial: max310x: Fix to avoid potential NULL pointer dereference
 ▪ 9f2c21278892 scsi: zfcp: fix scsi_eh host reset with port_forced ERP for non-NPIV FCP devices
 ▪ 7a5259dd0eef ALSA: pcm: Don't suspend stream in unrecoverable PCM state
 ▪ 59c86007ad49 ALSA: pcm: Fix possible OOB access in PCM oss plugins
 ▪ 1801ffbc7de8 mac8390: Fix mmio access size probe
 ▪ 8567f315cdb5 sctp: get sctphdr by offset in sctp_compute_cksum
 ▪ 69dfb9c8d69d tcp: do not use ipv6 header for ipv4 flow
 ▪ 62d2192b9663 packets: Always register packet sk in the same order
 ▪ 3bfc4e0ecb9c Add hlist_add_tail_rcu() (Merge git://git.kernel.org/pub/scm/linux/kernel/git/davem/net)
 ▪ 2d4d5d7afba5 net: rose: fix a possible stack overflow
 ▪ 8887183fcd3b net/packet: Set __GFP_NOWARN upon allocation in alloc_pg_vec
 ▪ 4ce7f9851c97 mISDN: hfcpci: Test both vendor & device ID for Digium HFC4S
 ▪ 6b703ff23cb9 dccp: do not use ipv6 header for ipv4 flow
 ▪ cf2afae3abba cfg80211: size various nl80211 messages correctly
 ▪ f93063f1575b mmc: mmc: fix switch timeout issue caused by jiffies precision
 ▪ 08422dc1dd31 arm64: kconfig: drop CONFIG_RTC_LIB dependency
 ▪ 19edccec7408 video: fbdev: Set pixclock = 0 in goldfishfb
 ▪ bf925b4fe5f9 usb: gadget: configfs: add mutex lock before unregister gadget
 ▪ 91366a76f2ea ipv6: fix endianness error in icmpv6_err
 ▪ b62638938193 arm64: kernel: Include _AC definition in page.h
 ▪ 0c99d0dc291d arm64/kernel: fix incorrect EL0 check in inv_entry macro
 ▪ ea4147e61820 ARM: 8510/1: rework ARM_CPU_SUSPEND dependencies
 ▪ f9ff1fd0c147 staging: goldfish: audio: fix compiliation on arm
 ▪ 5b96c46521e2 staging: ion: Set minimum carveout heap allocation order to PAGE_SHIFT
 ▪ 113e4806435d staging: ashmem: Add missing include
 ▪ 0d9aeed2703d staging: ashmem: Avoid deadlock with mmap/shrink
 ▪ 2e82280512d9 asm-generic: Fix local variable shadow in __set_fixmap_offset
 ▪ 60bb79a488db android: unconditionally remove callbacks in sync_fence_free()
 ▪ 0b86bf5d0715 ARM: 8458/1: bL_switcher: add GIC dependency
 ▪ 495dde2d8ea6 arm64: fix COMPAT_SHMLBA definition for large pages
 ▪ e88dd5c0a4c3 mmc: block: Allow more than 8 partitions per card
 ▪ ac7c597c465e Bluetooth: Verify that l2cap_get_conf_opt provides large enough buffer
 ▪ 8f9c5ea93aa7 Bluetooth: Check L2CAP option sizes returned from l2cap_get_conf_opt
 ▪ 71b7a0a59c7d media: v4l2-ctrls.c/uvc: zero v4l2_event
 ▪ e303ade336a0 mmc: tmio_mmc_core: don't claim spurious interrupts
 ▪ a03af61e4353 ext4: brelse all indirect buffer in ext4_ind_remove_space()
 ▪ 068b08bc9e75 ext4: fix data corruption caused by unaligned direct AIO
 ▪ 9696bac59661 ext4: fix NULL pointer dereference while journal is aborted
 ▪ 543b86a1e4c1 futex: Ensure that futex address is aligned in handle_futex_death()
 ▪ 824289e104f9 udf: Fix crash on IO error during truncate
 ▪ 203db8efc8e2 qcacld-2.0: Fix buffer overflow in process_rx_info etc
 ▪ 64fab10d8633 qcacld-2.0: Fix incorrect challenge text length
 ▪ 48bbfadd209b qcacld-2.0: Possible OOB access in wlan_hdd_cfg80211_start_bss()
 ▪ c003aab0484b Merge "dsp: q6voice: Check size of shared memory buffer before access"
 ▪ d1bae716b914 Merge "qdsp6v2: q6usm: Check size of payload before access"
 ▪ 7aa061d73a1e dsp: q6voice: Check size of shared memory buffer before access
 ▪ 5ff911aa8665 qdsp6v2: q6usm: Check size of payload before access
 ▪ b7df1191cf16 qdsp6v2: q6usm: Check size of payload before access
 ▪ db2e29267dc9 qcacld-2.0: Fix wild pointer issue for AC tx queue optimization
 ▪ 8a7b0e88d168 Merge "qcacld-2.0: Dynamic Power Control when do Suspend/Resume" into wlan-cld2.driver.lnx.1.0
 ▪ 5706d92f35a6 Merge "qcacld-2.0: Add a state for SA" into wlan-cld2.driver.lnx.1.0
 ▪ ba542196c380 qcacld-2.0: Dynamic Power Control when do Suspend/Resume
 ▪ fc23666a2eda qcacld-2.0: Add smart antenna matrix
 ▪ 703f4854d949 qcacld-2.0: Add a state for SA
 ▪ 36007825b232 drivers: soc: qcom: Added check to avoid opening multiple instance
 ▪ a3654a83a5cc Merge "msm: vidc: fix KCFI errors"
 ▪ 9dfb3f1270de msm: vidc: fix KCFI errors
 ▪ 90b5521792dc scripts: gcc-wrapper: Route the GCC errors to stderr
 ▪ cbf60a7e09da Merge branch 'kernel.lnx.3.18.r34-rel' of https://github.com/android-linux-stable/msm-3.18 into HEAD
 ▪ 7c90459655d4 Merge 3.18.137 into kernel.lnx.3.18.r34-rel
 ▪ 24fbbeb15685 Linux 3.18.137
 ▪ 0f404510f81a tmpfs: fix uninitialized return value in shmem_link
 ▪ 1f8ef009efe1 drm/radeon/evergreen_cs: fix missing break in switch statement
 ▪ 920ee78174ad media: uvcvideo: Avoid NULL pointer dereference at the end of streaming
 ▪ 73929a01c565 md: Fix failed allocation of md_register_thread
 ▪ 3127b10f2e45 nfsd: fix wrong check in write_v4_end_grace()
 ▪ 695cf5a1c7f8 nfsd: fix memory corruption caused by readdir
 ▪ 4d01d0bef261 ARM: s3c24xx: Fix boolean expressions in osiris_dvs_notify
 ▪ 86e74461bcc5 powerpc/83xx: Also save/restore SPRG4-7 during suspend
 ▪ 8302f8d9ff19 powerpc/powernv: Make opal log only readable by root
 ▪ 251b9649c10b powerpc/wii: properly disable use of BATs when requested.
 ▪ e89f1814df0a powerpc/32: Clear on-stack exception marker upon exception return
 ▪ b30e5af1adf9 jbd2: clear dirty flag when revoking a buffer from an older transaction
 ▪ b364a52e5171 parport_pc: fix find_superio io compare code, should use equal test.
 ▪ 0c6ea710cf58 kernel/sysctl.c: add missing range check in do_proc_dointvec_minmax_conv
 ▪ cc3dc9fd8009 mm/vmalloc: fix size check for remap_vmalloc_range_partial()
 ▪ c7e2728472da ext2: Fix underflow in ext2_max_size()
 ▪ 5df54f47cd02 ext4: fix crash during online resizing
 ▪ 9c069be87377 cpufreq: pxa2xx: remove incorrect __init annotation
 ▪ 51febb43d09c crypto: pcbc - remove bogus memcpy()s with src == dest
 ▪ 0ece4f706a10 Btrfs: fix corruption reading shared and compressed extents after hole punching
 ▪ 6086051bd2eb m68k: Add -ffreestanding to CFLAGS
 ▪ c91bf13da255 scsi: target/iscsi: Avoid iscsit_release_commands_from_conn() deadlock
 ▪ dc22a28021fb scsi: virtio_scsi: don't send sc payload with tmfs
 ▪ f6dc882865ab regulator: s2mpa01: Fix step values for some LDOs
 ▪ c9807601d36b regulator: s2mps11: Fix steps for buck7, buck8 and LDO35
 ▪ ed6d71db0ea0 CIFS: Fix read after write for files with read caching
 ▪ 6439ade58583 net: set static variable an initial value in atl2_probe()
 ▪ afeeaae3f36c tmpfs: fix link accounting when a tmpfile is linked in
 ▪ 7e7a77e27dc8 arm64: Relax GIC version check during early boot
 ▪ a27a25af72b4 net: mv643xx_eth: disable clk on error path in mv643xx_eth_shared_probe()
 ▪ 4abfd43cd64a net: systemport: Fix reception of BPDUs
 ▪ a55576b3f24e scsi: libiscsi: Fix race between iscsi_xmit_task and iscsi_complete_task
 ▪ 103d3fba10e6 assoc_array: Fix shortcut creation
 ▪ 5c00ee71ac0b Input: st-keyscan - fix potential zalloc NULL dereference
 ▪ 8086ef79de57 i2c: cadence: Fix the hold bit setting
 ▪ 3c05cf982f0e Input: matrix_keypad - use flush_delayed_work()
 ▪ fab8ee03386f s390/dasd: fix using offset into zero size array error
 ▪ 5331f95d4243 crypto: ahash - fix another early termination in hash walk
 ▪ 492290b4342e ASoC: fsl_esai: fix register setting issue in RIGHT_J mode
 ▪ f314a706df8b 9p/net: fix memory leak in p9_client_create
 ▪ 010feb981f75 It's wrong to add len to sector_nr in raid10 reshape twice
 ▪ a7e24e00f8e9 ALSA: bebob: use more identical mod_alias for Saffire Pro 10 I/O against Liquid Saffire 56
 ▪ 415d81c3fe31 gro_cells: make sure device is up in gro_cells_receive()
 ▪ c9978f642e0e net/hsr: fix possible crash in add_timer()
 ▪ 54e31274f8c1 vxlan: test dev->flags & IFF_UP before calling gro_cells_receive()
 ▪ 10a16ff0ef80 missing barriers in some of unix_sock ->addr and ->path accesses
 ▪ b929a3603b8d net: Set rtm_table to RT_TABLE_COMPAT for ipv6 for tables > 255
 ▪ 077a353641d2 mdio_bus: Fix use-after-free on device_register fails
 ▪ f14e4744b29a net/x25: fix a race in x25_bind()
 ▪ 65b511dda573 net/mlx4_core: Fix qp mtt size calculation
 ▪ 223458ad034b pptp: dst_release sk_dst_cache in pptp_sock_destruct
 ▪ 0052542ed3bb net/x25: reset state in x25_connect()
 ▪ 311d9ca2cfd7 net/x25: fix use-after-free in x25_device_event()
 ▪ 5f23b7a9fff5 net: sit: fix UBSAN Undefined behaviour in check_6rd
 ▪ e3d6490ad2b4 net: hsr: fix memory leak in hsr_dev_finalize()
 ▪ af12857379c8 l2tp: fix infoleak in l2tp_ip6_recvmsg()
 ▪ 19d0200ab9fb iscsi_ibft: Fix missing break in switch statement
 ▪ a91258c06c37 Input: wacom_serial4 - add support for Wacom ArtPad II tablet
 ▪ c8a52bb99462 perf symbols: Filter out hidden symbols from labels
 ▪ 6acb293d7cf2 s390/qeth: fix use-after-free in error path
 ▪ 3c26324ee549 dmaengine: dmatest: Abort test in case of mapping error
 ▪ 66a0097e462b irqchip/mmp: Only touch the PJ4 IRQ & FIQ bits on enable/disable
 ▪ c35a43a4aa4f ARM: pxa: ssp: unneeded to free devm_ allocated data
 ▪ e098697e51d2 autofs: fix error return in autofs_fill_super()
 ▪ b581cd7a149c autofs: drop dentry reference only when it is never used
 ▪ a3f3491953c4 mm, memory_hotplug: is_mem_section_removable do not pass the end of a zone
 ▪ 12c154964e79 x86/kexec: Don't setup EFI info if EFI runtime is not enabled
 ▪ 4b3cc96fa270 cifs: fix computation for MAX_SMB2_HDR_SIZE
 ▪ bdde0a895403 platform/x86: Fix unmet dependency warning for SAMSUNG_Q10
 ▪ 36fb86505290 scsi: libfc: free skb when receiving invalid flogi resp
 ▪ 03e8aa634f85 nfs: Fix NULL pointer dereference of dev_name
 ▪ ddd02ed6687c net: altera_tse: fix msgdma_tx_completion on non-zero fill_level case
 ▪ 47bf7dbba48f xtensa: SMP: limit number of possible CPUs by NR_CPUS
 ▪ 245fa9e4c8b8 xtensa: SMP: mark each possible CPU as present
 ▪ d4e922c05e88 xtensa: smp_lx200_defconfig: fix vectors clash
 ▪ 1c0a5536b07e xtensa: SMP: fix secondary CPU initialization
 ▪ 83237244df9c iommu/amd: Fix IOMMU page flush when detach device from a domain
 ▪ c7b9cfdb7c9a ipvs: Fix signed integer overflow when setsockopt timeout
 ▪ aef2907d0f4e perf tools: Handle TOPOLOGY headers with no CPU
 ▪ ed5ade9696ec vti4: Fix a ipip packet processing bug in 'IPCOMP' virtual tunnel
 ▪ 7828fe7452f1 media: uvcvideo: Fix 'type' check leading to overflow
 ▪ e37f1f9158e0 hugetlbfs: fix races and page leaks during migration
 ▪ 28ee96bc28a1 ip6mr: Do not call __IP6_INC_STATS() from preemptible context
 ▪ c61d01faa555 netlabel: fix out-of-bounds memory accesses
 ▪ ffd0f56df5d0 net: phy: Micrel KSZ8061: link failure after cable connect
 ▪ 5202d2fb4e15 net: avoid use IPCB in cipso_v4_error
 ▪ b5cd9b572169 net: Add __icmp_send helper.
 ▪ e89106985667 net: nfc: Fix NULL dereference on nfc_llcp_build_tlv fails
 ▪ c152a71bfd2a team: Free BPF filter when unregistering netdev
 ▪ 39915595c028 sky2: Disable MSI on Dell Inspiron 1545 and Gateway P-79
 ▪ a7053bc3aeef net-sysfs: Fix mem leak in netdev_register_kobject
 ▪ 70628d623780 USB: serial: cp210x: add ID for Ingenico 3070
 ▪ f290a73f3e91 mm: enforce min addr even if capable() in expand_downwards()
 ▪ c3ccbb431fe1 mmc: spi: Fix card detection during probe
 ▪ eea042978351 KVM: nSVM: clear events pending from svm_complete_interrupts() when exiting to L1
 ▪ 1d26f9b68ba2 cfg80211: extend range deviation for DMG
 ▪ a0b1e4d45abb mac80211: don't initiate TDLS connection if station is not associated to AP
 ▪ 2c91f0b916c9 ibmveth: Do not process frames after calling napi_reschedule
 ▪ 16618e65b6a0 net: altera_tse: fix connect_local_phy error path
 ▪ cf5dda0109a8 scsi: csiostor: fix NULL pointer dereference in csio_vport_set_state()
 ▪ e3fa9f464464 serial: fsl_lpuart: fix maximum acceptable baud rate with over-sampling
 ▪ c1b8a5c7566f mac80211: fix miscounting of ttl-dropped frames
 ▪ e5c6f5b545fa ASoC: imx-audmux: change snprintf to scnprintf for possible overflow
 ▪ bbda75dd25ed usb: gadget: Potential NULL dereference on allocation error
 ▪ def42cb2eae3 usb: dwc3: gadget: Fix the uninitialized link_state when udc starts
 ▪ 7af73b5fcbc4 ALSA: compress: prevent potential divide by zero bugs
 ▪ d1f9176b550c ASoC: Intel: Haswell/Broadwell: fix setting for .dynamic field
 ▪ 7b8a6f60ad99 drm/msm: Unblock writer if reader closes file
 ▪ 505b786aefc0 scsi: libsas: Fix rphy phy_identifier for PHYs with end devices attached
 ▪ a4954e0f5d6b libceph: handle an empty authorize reply
 ▪ 5821948648ca netlink: Trim skb to alloc size to avoid MSG_TRUNC
 ▪ 9f4487f15f15 sit: check if IPv6 enabled before calling ip6_err_gen_icmpv6_unreach()
 ▪ a68a134d81c6 team: avoid complex list operations in team_nl_cmd_options_set()
 ▪ c51049494a19 net/packet: fix 4gb buffer limit due to overflow check
 ▪ d2b09171e666 batman-adv: fix uninit-value in batadv_interface_tx()
 ▪ 15ef496907f6 KEYS: always initialize keyring_index_key::desc_len
 ▪ 0b49d56ed77d KEYS: user: Align the payload buffer
 ▪ 32cd768c6176 isdn: avm: Fix string plus integer warning from Clang
 ▪ 33951e5f8885 leds: lp5523: fix a missing check of return value of lp55xx_read
 ▪ f11255bf3bc6 atm: he: fix sign-extension overflow on large shift
 ▪ 627e11b13177 isdn: i4l: isdn_tty: Fix some concurrency double-free bugs
 ▪ bcec1dc4ffdf MIPS: jazz: fix 64bit build
 ▪ 39b0655ec07c scsi: isci: initialize shost fully before calling scsi_add_host()
 ▪ c5c4e7508b6a scsi: qla4xxx: check return code of qla4xxx_copy_from_fwddb_param
 ▪ 9605606af0c3 MIPS: ath79: Enable OF serial ports in the default config
 ▪ 5bc9daa97d9c mfd: mc13xxx: Fix a missing check of a register-read failure
 ▪ 984e3c2f901c mfd: wm5110: Add missing ASRC rate register
 ▪ 886781430b3e mfd: ab8500-core: Return zero in get_register_interruptible()
 ▪ 6e9dc1bafd83 mfd: db8500-prcmu: Fix some section annotations
 ▪ 70e6b9be49c0 mfd: twl-core: Fix section annotations on {,un}protect_pm_master
 ▪ fd02ebd37172 mfd: ti_am335x_tscadc: Use PLATFORM_DEVID_AUTO while registering mfd cells
 ▪ b4043fbb9960 KEYS: allow reaching the keys quotas exactly
 ▪ 5b9e59cb12b4 numa: change get_mempolicy() to use nr_node_ids instead of MAX_NUMNODES
 ▪ f202aae418e5 ceph: avoid repeatedly adding inode to mdsc->snap_flush_list
 ▪ cd2b065f83e9 Merge "qcacld-2.0: Set tsf host gpio as invalid by default" into wlan-cld2.driver.lnx.1.0
 ▪ 20822d8314cf Merge "qcacld-2.0: Remove the restriction of neighbor report number" into wlan-cld2.driver.lnx.1.0
 ▪ 8fce0afff504 Merge "qcacld-2.0: Fix compile error" into wlan-cld2.driver.lnx.1.0
 ▪ e667f9e47b25 qcacld-2.0: Set tsf host gpio as invalid by default
 ▪ b9784d04304d qcacld-2.0: Fix compile error
 ▪ 8cfd74972f4c Merge "qcacld-2.0: Do unmap dma only for mapped and non ipa dma" into wlan-cld2.driver.lnx.1.0
 ▪ 8d439d41709d qcacld-2.0: Do unmap dma only for mapped and non ipa dma
 ▪ 914b7b85ea30 Merge "dsp: asm: validate payload size before access"
 ▪ cd8f04cafc70 Merge "qcacld-2.0: Fix possible buffer overflow in sirConvertAddtsRsp2Struct" into wlan-cld2.driver.lnx.1.0
 ▪ c6b7fd7f2381 Merge "qcacld-2.0: fix the null pointer access issue when shutdown" into wlan-cld2.driver.lnx.1.0
 ▪ e56e369d9c3c dsp: asm: validate payload size before access
 ▪ d74d0a986d13 dsp: validate token before usage as array index
 ▪ f2c88f035b02 Merge "msm: mdss: correct the DTV panel fps calculation"
 ▪ 88f853c6f2ed qcacld-2.0: Fix possible buffer overflow in sirConvertAddtsRsp2Struct
 ▪ 8b93a484b6a2 qcacld-2.0: fix the null pointer access issue when shutdown
 ▪ dd636070eba5 qcacld-2.0: Fix NULL point may be dereferenced
 ▪ 51bea6b67ec7 Merge "qcacld-2.0: Add a host interest flag to tell target do reset resume" into wlan-cld2.driver.lnx.1.0
 ▪ 192158e80ee6 qcacld-2.0: Add a host interest flag to tell target do reset resume
 ▪ dac57dae5209 Merge "msm: vidc: do not set video state to DEINIT very early"
 ▪ e5e6a06441d3 Merge "msm: vidc: ignore processing responses in invalid state"
 ▪ ea76e1362f7d msm: vidc: ignore processing responses in invalid state
 ▪ bf30cda8dc66 msm: mdss: correct the DTV panel fps calculation
 ▪ af84607bfce8 msm: vidc: do not set video state to DEINIT very early
 ▪ 4b61c206728d msm: ipa: fix to validate the ioctl WAN_IOC_SEND_LAN_CLIENT_MSG params
 ▪ 0a8042ad685e Merge "qcacld-2.0: Purge neighbor report cache if unsolicited" into wlan-cld2.driver.lnx.1.0
 ▪ 48e543db174c qcacld-2.0: Purge neighbor report cache if unsolicited
 ▪ 85c1f9e7163b Merge "diag: Add missing protection while accessing session's info"
 ▪ a3dcf90b86ec Merge "msm: ice: check for crypto engine availability"
 ▪ fbc3fc18489b Merge "diag: Update msg mask's ranges properly"
 ▪ e7c490db1e4d diag: Update msg mask's ranges properly
 ▪ d50c0e507e1d diag: Add missing protection while accessing session's info
 ▪ c789afa3d802 msm: ice: check for crypto engine availability
 ▪ f35b63be65bd msm: asm: validate ADSP data before access
 ▪ 153e62a54791 qcacld-2.0: Do sanity check about usb interface data in suspend
 ▪ bad90da0ae7d qcacld-2.0: Remove the restriction of neighbor report number
 ▪ 113510449f09 Merge "qcacld-2.0: Memory leak fix in athdiagpfs" into wlan-cld2.driver.lnx.1.0
 ▪ 521c366e8337 Merge "qcacld-2.0: Dynamic Power Control when do Suspend/Resume" into wlan-cld2.driver.lnx.1.0
 ▪ e87faed797ce qcacld-2.0: Memory leak fix in athdiagpfs
 ▪ 25ce3ec2532f Merge "diag: Increment data ready only if it is first update"
 ▪ e9b6bc345d18 Merge "qcacld-2.0: Add smart antenna module" into wlan-cld2.driver.lnx.1.0
 ▪ 7648922434b6 Merge "qcacld-2.0: Fix OOB read in hdd_populate_wifi_signal_info" into wlan-cld2.driver.lnx.1.0
 ▪ 170e2975a1d0 qcacld-2.0: Add smart antenna module
 ▪ fda5831cba8d qcacld-2.0: Dynamic Power Control when do Suspend/Resume
 ▪ 0008a0a5de42 qcacld-2.0: Do sanity check about pci dirver data
 ▪ cacea13baac7 qcacld-2.0: Fix OOB read in hdd_populate_wifi_signal_info
 ▪ 7219a706cd82 Merge "ASoC: msm: qdsp6v2: add range check for audio port index"
 ▪ 18ed8c97c56d diag: Increment data ready only if it is first update
 ▪ 84da5137cb89 Merge changes Ifb5b11c3,I20eb7aa7,I70a52030 into wlan-cld2.driver.lnx.1.0
 ▪ 2a8d58bb50a0 Merge "qcacld-2.0: Disable roaming for OWE" into wlan-cld2.driver.lnx.1.0
 ▪ c92d432a1f36 dsp: codecs: fix range check for audio buffer copying

 ▼ packages/apps/Bluetooth/
 ▪ a9ec77e3 Snap for 5443865 from ac82b0cdc0ab96ac0dbc8b67287718ae7c4e73a5 to pi-qpr3-b-release
 ▪ ac82b0cd Import translations. DO NOT MERGE
 ▪ 9cee3b33 Merge tag 'android-9.0.0_r35' into pie
 ▪ 04e228eb Merge pull request #2 from coderzstas/9.0
 ▪ 48f85d80 Merge tag 'android-9.0.0_r35' of https://android.googlesource.com/platform/packages/apps/Bluetooth into 9.0

 ▼ packages/apps/Browser/
 ▪ 6cf19b0 Browser: Update assets to use outline style
 ▪ ac48339 Browser: Increase content padding for search bar
 ▪ 09e187b Browser: Use round search bar
 ▪ ad897aa Browser: Use Pixel blue accent
 ▪ c271bf4 Browser: QuickTiles for Favorites, Incognito, and New Tabs
 ▪ 6807d03 Browser: QuickTiles for Favorites, Incognito, and New Tabs
 ▪ 309478e Browser: Add save form data setting
 ▪ 4de469a Browser: Add Adblocker capabilities
 ▪ 788eecd Browser: Let the system know we're changing bar colors
 ▪ c9fe68d Browser: Add a setting to set incognito defaults
 ▪ cceb503 Browser: Don't save form data in incognito mode
 ▪ 9e981e7 Browser: Begin rebase onto newer Jelly

 ▼ packages/apps/Camera2/
 ▪ 2955637f8 Fix crash if Exif-Tag buffer-length and component-count are both 0
 ▪ d228776a1 Camera2: Fix Undo button behaviour
 ▪ ba14cda59 Camera2: Remove google help preference
 ▪ 248891132 Camera2: Add option to set max screen brightness
 ▪ 5ce0ec2c8 Camera: Powerkey shutter (2/2)
 ▪ ed40cf3be Camera2: Request for ACCESS_FINE_LOCATION permission
 ▪ fd3ae8269 Camera2: Stop using GPS when going to background
 ▪ c4e1d9091 Camera2: Remove settings preferences only once
 ▪ f566be2b5 Camera2: Only autofocus before a snap if we are actually in "auto" mode.
 ▪ 6d40b4956 Don't attempt to convert degree to orientation enum twice
 ▪ bb86cc623 Camera2: Target API 27
 ▪ d7bc0391e Camera2: adaptive icon

 ▼ packages/apps/CellBroadcastReceiver/
 ▪ 9f6cd24 Snap for 5443865 from 0ee26541f21613998814ac4435c3dc35eb288ee7 to pi-qpr3-b-release
 ▪ 0ee2654 Import translations. DO NOT MERGE

 ▼ packages/apps/Contacts/
 ▪ 4f49c1c22 Snap for 5443865 from cf1f1d5dc1d5123f979eaa2dff7c7b7f03e9e346 to pi-qpr3-b-release
 ▪ cf1f1d5dc Import translations. DO NOT MERGE
 ▪ 0afa5da5c Snap for 5422807 from 9ac964f68f7bf681dfc0073fafffa60bb8fd6e35 to pi-qpr3-b-release
 ▪ 9ac964f68 Import translations. DO NOT MERGE

 ▼ packages/apps/CustomDoze/

 ▼ packages/apps/Dirac/
 ▪ 8329e99 Prevent failures when toggling
 ▪ 9037c79 Only call setEnabled on boot completed
 ▪ d3856fc Refactor Dirac setup
 ▪ 5d23300 Dirac fixes
 ▪ 2b01382 Refactor dirac strings
 ▪ e0d910d Add summary for dirac
 ▪ 6515719 Add DiracSound backend
 ▪ 70b11a0 Introduce Dirac preferences

 ▼ packages/apps/DocumentsUI/
 ▪ 9b6f2643 Snap for 5422807 from 8050ffc978c1f8be76f0c262405070f3dd5140a9 to pi-qpr3-b-release
 ▪ 8050ffc9 Fix FileOperationService starts foreground service failed.
 ▪ 2078e440 Merge cherrypicks of [6841458, 6845109, 6844203, 6845110, 6845111, 6845112, 6845113, 6845114, 6845115, 6845116, 6845117, 6845118, 6845119, 6845376, 6845444, 6845377, 6844204, 6844205, 6844206, 6844207, 6844208, 6844209, 6844210, 6844211, 6844212, 6844213] into pi-qpr3-b-release
 ▪ 8e55cdca Fix FileOperationService starts foreground service failed.
 ▪ 2752868d DocumentsUI: Improve dark theme

 ▼ packages/apps/EmergencyInfo/
 ▪ 1f34f13 Snap for 5443865 from 01a12f48dbcfa028857bb84d8364efd80b46f012 to pi-qpr3-b-release
 ▪ 01a12f4 Import translations. DO NOT MERGE

 ▼ packages/apps/FMRadio/

 ▼ packages/apps/HavocSettings/
 ▪ c41ee74 Translate more strings in Russian
 ▪ 58fb26e Fix Russian translation
 ▪ 63015e7 Settings: Add Black Pearl theme [2/3]
 ▪ 2eaba71 Settings: Add our discord server
 ▪ 52e28fe Custom logo customizations [2/2]
 ▪ 6534670 Slim recents old enter/exit animation [3/3]
 ▪ a38bd6c Fix J7 prime codename
 ▪ 6a1f429 Settings: LS filters: Add 2 more variants
 ▪ 19da1d7 Settings: Implement Aggressive Battery [2/2]
 ▪ 8be2d6f Settings: Fix typos
 ▪ e79ac79 Settings: Add Lockscreen cover art filter [2/2]
 ▪ 1264f64 Fallback to "no action" when an application gets removed [2/2]
 ▪ 3c939ca Active Edge: allow to choose a specific app activity [3/4]
 ▪ 74a291a Introduce long squeeze action [2/3]
 ▪ 18f9e1a Add natrium in devices
 ▪ 50b8b8a Give Tushar a promotion
 ▪ 8bb45d8 Drop tulip
 ▪ 7bf0703 Settings: Adaptive icon system-wide setting [2/3]
 ▪ cdfedc5 Interface: Get rid of Controllers
 ▪ 970692b Settings: Cleanup and fixes
 ▪ 8647b01 Revert "Revert "Screen off animations [2/2]""
 ▪ 774d40c Revert "Add toggle for hiding QS drag handle [2/2]"
 ▪ c483fad Add mido in devices
 ▪ e824dff Add cancro in devices
 ▪ c8d2c3d Add sagit in devices
 ▪ 6f0e376 Revert "Extended audio panel [2/2]"
 ▪ 48a91d0 Add toggle for QS footer user switcher icon

 ▼ packages/apps/Messaging/

 ▼ packages/apps/Nfc/
 ▪ 18ad94ed Snap for 5443865 from 9923dc99e1c1419a99dcee0d252d8a67a321990d to pi-qpr3-b-release
 ▪ 9923dc99 Import translations. DO NOT MERGE
 ▪ 1c574eee NfcNci: make T3T/Nfc-F HCE optional

 ▼ packages/apps/OmniStyle/

 ▼ packages/apps/PackageInstaller/

 ▼ packages/apps/Recorder/

 ▼ packages/apps/Settings/
 ▪ c35d177743 Fix Russian translation
 ▪ 5667fb42c8 Fix Impossible to add fingerprint
 ▪ 9615074f51 Fix Russian translation
 ▪ feddc93ab6 Snap for 5443865 from 83d678bdc471f1e8eb14ac9bbfe5fe0718cc6ec3 to pi-qpr3-b-release
 ▪ 2186612247 Settings: Add OnePlus Red accent [2/3]
 ▪ da95f0c35d Settings: Add deep sleep info to uptime
 ▪ 5f329cd65d Settings: Move 'About phone' to the bottom
 ▪ 83d678bdc4 Import translations. DO NOT MERGE
 ▪ 468a189129 Snap for 5422807 from 5d9189fab232610b2a543f617faf4cb29b0968fc to pi-qpr3-b-release
 ▪ 5d9189fab2 Merge "DO NOT MERGE Refactor passwords/pins/patterns to byte[]" into pi-dev
 ▪ 56cbe0bb50 Snap for 5408106 from e6d11ed962c90500527393e242e85fc77741b2ad to pi-qpr3-b-release
 ▪ e6d11ed962 Import translations. DO NOT MERGE
 ▪ 8cdd773a26 Settings: Fix actionbar title for HAFR
 ▪ e4220b2504 Revert "Settings: Move Notch settings to display"
 ▪ 34042bbf1d DO NOT MERGE Refactor passwords/pins/patterns to byte[]
 ▪ 7a9cc0d166 Update the timestamp used for time zone filtering
 ▪ 41351028d4 Settings: fix eject sdcard icon color
 ▪ 7fc597f456 Re-add WPS implementation (1/3)
 ▪ 1fb5b5100d Merge cherrypicks of [6716922, 6716923, 6716413, 6717023, 6717024, 6716716, 6715859, 6717160, 6717161, 6717162, 6717163, 6716295, 6717141, 6717181, 6717183, 6717184, 6717185, 6714937, 6717028, 6716717, 6716927, 6717200, 6717029, 6717030, 6717031, 6717032, 6717033, 6716928, 6717034, 6717035, 6716929, 6717201, 6716930, 6712377, 6712378, 6716643, 6717164, 6712379] into pi-qpr3-release
 ▪ 3002f27a6f Do not allow draw on top for default sms picker.
 ▪ e7fbf98e1f Snap for 5363709 from 1b29c28aef2bf20560e2dbd7b1f5f0c7a1d7eb36 to pi-qpr3-b-release

 ▼ packages/apps/SmartNav/

 ▼ packages/apps/Snap/
 ▪ 253ab00b0 Snap: Remove Lineage SDK dependency
 ▪ e313b99c2 Snap: Fix picture size preference

 ▼ packages/apps/Terminal/

 ▼ packages/apps/Updater/
 ▪ e6d1d22 Updater: Expose dialogs and popup items
 ▪ 9431f3e default branch
 ▪ d35d7ac fix
 ▪ 38d4d18 Updater: Mark as persistent
 ▪ c8c18d8 Updater: Change export path
 ▪ fbd7ec9 Updater: Correct cleanup notification action
 ▪ d54d7bf Updater: Add little delay before sending broadcast
 ▪ 9a688d2 Updater: Add network speed into some parts
 ▪ e54af2c Updater: Refresh list when update get deleted
 ▪ d69530b Updater: Pixel UI redesign
 ▪ 1bbdc1a rework
 ▪ 32bf6c9 set header_title_text as untranslatable string
 ▪ f2e4a82 Updater: Nuke Lineage's website on installation blocked dialog
 ▪ ba2826a Updater: Theme actionbar text too
 ▪ d94e8dd Updater: Use accent for actionbar items
 ▪ b467155 Updater: Add changelog dialog
 ▪ c0a461c refactor to Havoc
 ▪ f8c1fbc Be serious
 ▪ 4f74f6e theme: use accent color in header
 ▪ 5b0af25 Updater: Complete UI Redesign
 ▪ 3accb14 Update RU translation
 ▪ 601dd32 Updater: Implement auto update check interval preference
 ▪ f1d2e27 Don't check version before install
 ▪ 02d0ef6 Added ability to install updates from local files
 ▪ 6c920c3 Updater: refactor for Syberia
 ▪ 42a12be Updater: Expose the lower background color

 ▼ packages/inputmethods/LatinIME/
 ▪ e035e3c31 Snap for 5443865 from 7209c0f07494c20b22ac5fca22ff33108411425d to pi-qpr3-b-release
 ▪ 7209c0f07 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 990b77d2b Import translations. DO NOT MERGE
 ▪ d34bbca09 Import translations. DO NOT MERGE
 ▪ da93a1cca Snap for 5422807 from 145808acade246bd8f2e66b2f2d8ed2b0b4484d4 to pi-qpr3-b-release
 ▪ 145808aca Import translations. DO NOT MERGE

 ▼ packages/providers/DownloadProvider/
 ▪ 0d3a49f DownloadProvider: Stop using Arrays.checkOffsetAndCount
 ▪ c4579dd Downloaded content is deleted if Download folder is renamed using MTP
 ▪ c61600e DownloadProvider: allow more redirects
 ▪ 363c0c9 Stop download from the site with invalid certificate
 ▪ 3ad8e0a Add support to manually pause/resume downloads [2/2]
 ▪ 983e6cd Remove download notification after preview
 ▪ a6c6ab6 Add download speed, remaining time, and percentage in notification

 ▼ packages/providers/MediaProvider/
 ▪ 99586b0 [automerger] Use canonical path before checking access. am: 93a200d703 am: 57a180e240 am: 4b9d6ef495 am: 8545432013 am: d6b1b74e29 am: 3267bf1236 am: 622dcea5cb am: 479f23d9f0
 ▪ 479f23d [automerger] Use canonical path before checking access. am: 93a200d703 am: 57a180e240 am: 4b9d6ef495 am: 8545432013 am: d6b1b74e29 am: 3267bf1236 am: 622dcea5cb
 ▪ 622dcea [automerger] Use canonical path before checking access. am: 93a200d703 am: 57a180e240 am: 4b9d6ef495 am: 8545432013 am: d6b1b74e29 am: 3267bf1236
 ▪ 3267bf1 [automerger] Use canonical path before checking access. am: 93a200d703 am: 57a180e240 am: 4b9d6ef495 am: 8545432013 am: d6b1b74e29
 ▪ d6b1b74 [automerger] Use canonical path before checking access. am: 93a200d703 am: 57a180e240 am: 4b9d6ef495 am: 8545432013
 ▪ 8545432 [automerger] Use canonical path before checking access. am: 93a200d703 am: 57a180e240 am: 4b9d6ef495
 ▪ 4b9d6ef [automerger] Use canonical path before checking access. am: 93a200d703 am: 57a180e240
 ▪ 57a180e [automerger] Use canonical path before checking access. am: 93a200d703
 ▪ 93a200d Use canonical path before checking access.

 ▼ packages/services/Telecomm/
 ▪ 11b99877 Snap for 5445705 from c1176c17b78c7ece15385fe6047a3f0a1b110de8 to p-keystone-qcom-release
 ▪ c1176c17 Merge "Fix the SCO connection disconnected by telephony." into p-keystone-qcom
 ▪ 1a843400 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into caf
 ▪ 1edf4bfe Merge b0a9c9f35dca917d123f9e7afdd2e970375b42e3 on remote branch
 ▪ 0830a09a Merge b0a9c9f35dca917d123f9e7afdd2e970375b42e3 on remote branch
 ▪ e0cf2d17 Fix the SCO connection disconnected by telephony.
 ▪ b65ecc5a Snap for 5408106 from 45c210fe179278257fe53064e23f713f289d7e64 to pi-qpr3-b-release
 ▪ 45c210fe Import translations. DO NOT MERGE
 ▪ c5eb300e Telecomm: Update code for in-call vibrations

 ▼ packages/services/Telephony/
 ▪ 62c282888 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into caf
 ▪ 8f4c22cf7 Merge 9ca13a6958a0122bb376b84387c432f880361aa0 on remote branch
 ▪ 8677b5948 Telephony: Fix dark theme after https://github.com/HavocGemini/android_packages_services_Telephony/commit/85ddea8b91e0fe0b0b9f98be74aa33e025667c46
 ▪ a2a1eda50 Merge 9ca13a6958a0122bb376b84387c432f880361aa0 on remote branch
 ▪ 52aaa945e Merge tag 'LA.UM.7.6.2.r1-07600-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into caf
 ▪ fafbcf32a ToggleLte: Add missed TDSCDMA modes
 ▪ e65c9f9e6 Fix to dismiss depersonalization dialog on sim LOADED
 ▪ b1eb1007c Telephony: Implement alternative method for manual network select
 ▪ c9341c73a Snap for 5408106 from cb86c13df93be59906c1871f92252c81c6fbffe1 to pi-qpr3-b-release
 ▪ cb86c13df Import translations. DO NOT MERGE
 ▪ 7b21743a7 Snap for 5402153 from 5a02e9ed216747aa328b0e40df8f3e18cefbb4c9 to pi-qpr3-b-release
 ▪ 5a02e9ed2 Import translations. DO NOT MERGE
 ▪ e92a653cb Merge 59a81dcb2fa4b976db31f84d5aef794c4e6a1117 on remote branch
 ▪ 68549d080 Import translations. DO NOT MERGE
 ▪ 3f5835462 Snap for 5395070 from b3dea468f8a3734e17d3194175d103c73dfe4183 to p-keystone-qcom-release
 ▪ 1e1541120 Change UI styles to match dialer settings light M2 theme
 ▪ dfb2314a8 Disable EmergencyDialer multi window mode
 ▪ b7bb93bed Fix EmergencyDialer UI when display size change
 ▪ b3dea468f Fix for MMI **05*PUK*NEW*NEW# for PUK unlock from Emergency dialer.
 ▪ 9ca13a695 Snap for 5370022 from e8b1843b9024d2f063bd862e5b19d10ba4412fc0 to p-keystone-qcom-release
 ▪ e8b1843b9 Merge "Telephony: Use IEC standard to update data usage" into p-keystone-qcom
 ▪ d955d24de Snap for 5363709 from 99564aaf0417c9ddf7d6aeb10d326e5b24fa8f55 to pi-qpr3-b-release

 ▼ prebuilts/abi-dumps/ndk/
 ▪ 06eee4e Update libnativewindow ABI dump

 ▼ system/bt/
 ▪ 9dbf9703d Snap for 5310204 from 817facf4bc2a956fafa8a38c15ab5963f2d0bc0e to pi-platform-release am: 3855e3f52b
 ▪ 3865c8b6f Snap for 5447620 from 6c931823ceab77b3698be3a0eafe4f70cdc03e09 to pi-qpr3-b-release
 ▪ 3855e3f52 Snap for 5310204 from 817facf4bc2a956fafa8a38c15ab5963f2d0bc0e to pi-platform-release
 ▪ 6c931823c [automerger skipped] DO NOT MERGE Don't persist bonds using sample LTK am: 292fcf8612 -s ours am: e8dea68f6a -s ours am: dc17388efd -s ours am skip reason: subject contains skip directive
 ▪ dc17388ef [automerger skipped] DO NOT MERGE Don't persist bonds using sample LTK am: 292fcf8612 -s ours am: e8dea68f6a -s ours am skip reason: change_id I52fd484d42bf87e96dbc9e6456090f231ed48111 with SHA1 c0fb2a25f9 is in history
 ▪ e8dea68f6 [automerger skipped] DO NOT MERGE Don't persist bonds using sample LTK am: 292fcf8612 -s ours am skip reason: change_id I52fd484d42bf87e96dbc9e6456090f231ed48111 with SHA1 c0fb2a25f9 is in history
 ▪ 292fcf861 DO NOT MERGE Don't persist bonds using sample LTK
 ▪ 3f9df87eb Snap for 5443865 from a07ff2d7ded1ed282e8577105e8eb386ddfecda4 to pi-qpr3-b-release
 ▪ a07ff2d7d [automerger skipped] [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9 am: c544656a68 am: 0fd5b5de7d am: 1dec8a9f3e skipped: 05e4e07328 am: c07f304de8 am: fc58eb3c8d am: 97e9e1540a -s ours am skip reason: subject contains skip directive
 ▪ 97e9e1540 [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9 am: c544656a68 am: 0fd5b5de7d am: 1dec8a9f3e skipped: 05e4e07328 am: c07f304de8 am: fc58eb3c8d
 ▪ 109132404 [automerger skipped] DO NOT MERGE Don't persist bonds using sample LTK am: 054dcec1c9 -s ours am skip reason: subject contains skip directive
 ▪ fc58eb3c8 [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9 am: c544656a68 am: 0fd5b5de7d am: 1dec8a9f3e skipped: 05e4e07328 am: c07f304de8
 ▪ 1128e8c70 Merge tag 'android-9.0.0_r35' into pie
 ▪ c07f304de [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9 am: c544656a68 am: 0fd5b5de7d am: 1dec8a9f3e skipped: 05e4e07328
 ▪ 05e4e0732 [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9 am: c544656a68 am: 0fd5b5de7d am: 1dec8a9f3e
 ▪ 1dec8a9f3 [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9 am: c544656a68 am: 0fd5b5de7d
 ▪ 0fd5b5de7 [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9 am: c544656a68
 ▪ c544656a6 [automerger] DO NOT MERGE Don't persist bonds using sample LTK am: c0fb2a25f9
 ▪ c0fb2a25f DO NOT MERGE Don't persist bonds using sample LTK
 ▪ 054dcec1c DO NOT MERGE Don't persist bonds using sample LTK
 ▪ 250529d6f DO NOT MERGE Don't persist bonds using sample LTK
 ▪ cff058e7b Snap for 5422807 from 9515d91c6f4433bbe91e52668721a0fd539a3261 to pi-qpr3-b-release
 ▪ 8e407eed7 Bluetooth: Fix BT calls
 ▪ 9515d91c6 Merge "DO NOT MERGE Log encryption key size" into pi-dev
 ▪ 45342e5ca [automerger skipped] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 049bf4ec4e -s ours am: 5237f6add3 -s ours am: 6caf0b031f -s ours am skip reason: subject contains skip directive
 ▪ 90f6b713f [automerger skipped] [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367 am: 5f48bc8a86 am: b788f8394e am: a46c2b03a2 skipped: f0213c3937 am: 1ecc29885a am: 262bb16a7e am: 633bf7e310 -s ours am skip reason: subject contains skip directive
 ▪ 6caf0b031 [automerger skipped] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 049bf4ec4e -s ours am: 5237f6add3 -s ours am skip reason: change_id Id4b6b4e765628397a79e6806f45c2cd27acebd5b with SHA1 027532b367 is in history
 ▪ 633bf7e31 [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367 am: 5f48bc8a86 am: b788f8394e am: a46c2b03a2 skipped: f0213c3937 am: 1ecc29885a am: 262bb16a7e
 ▪ 5237f6add [automerger skipped] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 049bf4ec4e -s ours am skip reason: change_id Id4b6b4e765628397a79e6806f45c2cd27acebd5b with SHA1 027532b367 is in history
 ▪ 8818d4bb5 [automerger skipped] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: e32d4aa7a4 -s ours am skip reason: subject contains skip directive
 ▪ 262bb16a7 [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367 am: 5f48bc8a86 am: b788f8394e am: a46c2b03a2 skipped: f0213c3937 am: 1ecc29885a
 ▪ 049bf4ec4 DO NOT MERGE Drop Bluetooth connection with weak encryption key
 ▪ 7e8dbcd40 DO NOT MERGE Log encryption key size
 ▪ 1ecc29885 [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367 am: 5f48bc8a86 am: b788f8394e am: a46c2b03a2 skipped: f0213c3937
 ▪ f0213c393 [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367 am: 5f48bc8a86 am: b788f8394e am: a46c2b03a2
 ▪ a46c2b03a [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367 am: 5f48bc8a86 am: b788f8394e
 ▪ b788f8394 [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367 am: 5f48bc8a86
 ▪ 5f48bc8a8 [automerger] DO NOT MERGE Drop Bluetooth connection with weak encryption key am: 027532b367
 ▪ 027532b36 DO NOT MERGE Drop Bluetooth connection with weak encryption key
 ▪ e32d4aa7a DO NOT MERGE Drop Bluetooth connection with weak encryption key
 ▪ 398473b74 DO NOT MERGE Drop Bluetooth connection with weak encryption key
 ▪ bd589528f DO NOT MERGE: Use a weak pointer to deliver updates to AVRCP devices.
 ▪ e3f5d8818 Revert "DO NOT MERGE Separate SDP procedure from bonding state (1/2)"
 ▪ f8a5ce994 Merge cherrypicks of [6716922, 6716923, 6716413, 6717023, 6717024, 6716716, 6715859, 6717160, 6717161, 6717162, 6717163, 6716295, 6717141, 6717181, 6717183, 6717184, 6717185, 6714937, 6717028, 6716717, 6716927, 6717200, 6717029, 6717030, 6717031, 6717032, 6717033, 6716928, 6717034, 6717035, 6716929, 6717201, 6716930, 6712377, 6712378, 6716643, 6717164, 6712379] into pi-qpr3-release
 ▪ 80e24410b DO NOT MERGE: Use a weak pointer to deliver updates to AVRCP devices.
 ▪ 1d03444d5 Snap for 5369966 from e689266be5f841e601a614bfc13daaa31f9c0ce2 to pi-qpr3-b-release
 ▪ e689266be [DO NOT MERGE] btif/osi: move I/O to OSI layer. disable for multi-user.
 ▪ 8fce4bca6 [DO NOT MERGE] Handle edge cases where input or hash/data could be null.
 ▪ 1c981598b [DO NOT MERGE] btif: Avoid resource leak in error case
 ▪ f7e12c2ea [DO NOT MERGE] btif: Avoid a couple string copies
 ▪ 169ddca90 [DO NOT MERGE] btif: Lighter weight file existence check
 ▪ e0f1e9a32 [DO NOT MERGE] Implement key attestation using AndroidKeystore.
 ▪ dcdcd3569 Snap for 5363709 from cac66ef6599582224bf17780c669bdbc912660a6 to pi-qpr3-b-release

 ▼ system/connectivity/wificond/
 ▪ c1f4c99 wificond: Mark scanner impl instance invalid

 ▼ system/core/
 ▪ 8a93a8f9e Revert "sdcard: Allow building as a static library"
 ▪ b994bc437 fs_mgr: Skip filesystem check unless fs_type matches
 ▪ f49bc4c1d Revert "fs_mgr_fstab: removing fs_mgr_get_entry_for_mount_point_after()"
 ▪ 5aa1b1606 Fix path for treble default prop
 ▪ db08c342f Filter out QTI performance spam
 ▪ 0f5db3580 Shut up camera and wcnss debug output
 ▪ e0aa9113a Filter GalleryDatab*
 ▪ b3b777a81 healthd: make periodic battery status a debug message
 ▪ 614ff9d8e storaged: change log level for health HAL calls

 ▼ system/extras/
 ▪ 265f8e14 Merge "libfscrypt: Add Adiantum support" into pie-gsi
 ▪ 0e038637 libfscrypt: Add Adiantum support

 ▼ system/netd/
 ▪ 1547fcc Snap for 5310204 from 19f2a2b61f393852e0aa02d7285e830b607a9b9c to pi-platform-release am: 4fbf3249f7
 ▪ 4fbf324 Snap for 5310204 from 19f2a2b61f393852e0aa02d7285e830b607a9b9c to pi-platform-release
 ▪ a5767e1 Merge tag 'android-9.0.0_r35' into pie

 ▼ system/qcom/
 ▪ 5dc2631 Merge 48b8ac4b240b6237eafb9279088aed95e57c883a on remote branch

 ▼ system/sepolicy/
 ▪ 8c517c61a Merge fd0e3749b5f92b1db03c26698c0c8a875b1dab9f on remote branch
 ▪ 6a34e28a2 Merge fd0e3749b5f92b1db03c26698c0c8a875b1dab9f on remote branch
 ▪ 884fb1f35 sepolicy: Adaptive icon system-wide-setting [3/3]
 ▪ d6992c2f5 replace ota_package with havoc_updates

 ▼ system/timezone/
 ▪ 63540a1 DO NOT MERGE: Changes associated with the tzdb 2019a update
 ▪ e150721 DO NOT MERGE: Track changes in external/icu for rearguard data

 ▼ system/vold/
 ▪ 97e1b94 vold: Add linkage for fs_mgr changes
 ▪ f7bdc95 increase timeout for waiting on block device
 ▪ 4d8b817 Merge changes from topic "userspace_adiantum_support_pie-gsi" into pie-gsi
 ▪ 9820d1e cryptfs: improve logging of dm-crypt device creation
 ▪ 668c23f cryptfs: round down dm-crypt device size to crypto sector boundary
 ▪ 8c63b57 cryptfs: Allow setting dm-crypt sector size
 ▪ d0285a2 cryptfs: Add Adiantum support
 ▪ a598e04 Fsync directories before delete key
 ▪ 2e58acb Fsync directories after creating files

 ▼ vendor/MiuiCamera/
 ▪ b002a3d Ready For Build
 ▪ d9260f9 Fix Buiding Error

 ▼ vendor/codeaurora/telephony/
 ▪ f4a38f6 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into HEAD
 ▪ ab8fd4e Merge b98b950ca5636cd9ed13ff4a6a90afca45457dce on remote branch
 ▪ 54961fc Merge tag 'LA.UM.7.6.2.r1-07300-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into HEAD

 ▼ vendor/havoc/
 ▪ 41690375 Revert "Use SoundPicker instead of AOSP"
 ▪ ebbe4844 update Lawnchair to alpha-1957
 ▪ f297e585 vendor: Enable vibrate when ringing by default
 ▪ 5301f4db calling havoc sepolicy from vendor
 ▪ 1ec64139 update Lawnchair to alpha-1947
 ▪ 70d2dcd1 update Lawnchair to alpha-1940 update Google DeskClock
 ▪ db42ffae update Lawnchair to alpha-1912
 ▪ 7b9088ba Havoc 2.4
 ▪ c00252fe update Device Health Services to 1.8.0.240160720.release
 ▪ 80ba2ab4 update WallpaperPickerGooglePrebuilt
 ▪ e73bf33c update Lawnchair to alpha-1056
 ▪ 81bd1fc1 vendor: add BUILD_RRO_SYSTEM_PACKAGE target
 ▪ 58673dbc vendor: Move custom buildinfo to vendor/havoc [2/2]
 ▪ 880245a6 update Lawnchair to alpha-1040
 ▪ 21f1730b update Lawnchair to alpha-972
 ▪ 80d39a89 move tools/generate_build_info.sh from device tree
 ▪ e898f587 soong_config: Add BOOTLOADER_MESSAGE_OFFSET
 ▪ 5bbd4470 Add APN ION Mobile & APN for Roaming
 ▪ 49aa94ab libbfqio: Remove vendor variant
 ▪ e206684a sensitive_pn: New United Kingdom helplines
 ▪ 3433718e vendor: Add missing prop
 ▪ 3e38079f update Lawnchair to alpha-968
 ▪ 51b5f068 Set google autofill service as default
 ▪ 9efc20c2 Add APN for XFINITY Mobile
 ▪ edcca6d0 apns: Add new Virgin Mobile apn
 ▪ 728fcec2 apn: Update the Ultra Mobile apn
 ▪ b4eb2aeb build in UTC time
 ▪ 0e52afed update Lawnchair to alpha-959
 ▪ cf6a946d update Lawnchair to alpha-943

 ▼ vendor/nxp/opensource/commonsys/packages/apps/Nfc/
 ▪ 40380405 fix typo

 ▼ vendor/qcom/opensource/audio/
 ▪ dec3e54 Merge bd53c965253e9c405e6ddf497ac1d26a08a8bab8 on remote branch
 ▪ 7f9a5b0 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ c97428c Merge bd53c965253e9c405e6ddf497ac1d26a08a8bab8 on remote branch
 ▪ 3310c01 Merge bd53c965253e9c405e6ddf497ac1d26a08a8bab8 on remote branch
 ▪ 146749a Merge tag 'LA.UM.7.6.2.r1-07300-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie
 ▪ bd53c96 policy_hal: avoid open stereo channel output for voip_rx flag

 ▼ vendor/qcom/opensource/cryptfs_hw/
 ▪ 236374e Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/cryptfs_hw into pie
 ▪ 68a0cfa Merge 684bb8d924b4cf54544060f8a3eebce301dbc120 on remote branch
 ▪ ee66f82 Merge tag 'LA.UM.7.6.2.r1-07300-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/cryptfs_hw into pie

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ 6b6c850 Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie
 ▪ a629351 Merge 2f329b3b7d319e725f81c663ec070794b9a25c2d on remote branch
 ▪ dc14512 Merge 2f329b3b7d319e725f81c663ec070794b9a25c2d on remote branch
 ▪ 2f329b3 Merge "ipacm: Add check for size of IPACM_cfg xml element's content"
 ▪ e0e0934 ipacm: Add check for size of IPACM_cfg xml element's content

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 3248c4c Introduce vendor.qti.hardware.servicetracker@1.0 HAL
 ▪ 524103b Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie
 ▪ 3528215 wifi: Extend ISupplicantVendorStaIface to get Wi-Fi generation info.
 ▪ 4fe7f1f IQtiMapper: Add HAL for QtiMapper getters.

 ▼ vendor/support/
 ▪ 66b4a13 Fix displaying units for CustomSeekBarPreference
 ▪ a1166d1 App Picker: Add back press override
 ▪ 261216d Active Edge: allow to choose a specific app activity [2/4]
 ▪ 9abcdbe Add SystemPropListPreference

 ▼ vendor/themes/
 ▪ 3e7f1f8 themes: Add OnePlus Red accent [3/3]
 ▪ 68858eb themes: Add Black Pearl theme [3/3]
 ▪ 07dbfc8 themes: Fix volume panel footer background
 ▪ cc7a998 themes: Dark theme improvements

 ▼ vendor/xiaomi/
 ▪ f844cff3 Revert "update sound"
 ▪ 9fb08042 update vulkan libs from LA.UM.7.5.r1-03700-8x96.0
 ▪ bd3323df update ADSP
 ▪ f4ec24c3 update DRM Widevine
 ▪ 504c216f update sound
 ▪ 041a1085 update sensors
 ▪ 36d98911 update sensors calibration
 ▪ 498c23f4 update wfd
 ▪ 7bd0f92c update CNE
 ▪ f1939121 update peripheral
 ▪ 7f864335 update dpm
 ▪ c7c4a079 update Postprocessing & power-off
 ▪ c51960b9 update media
 ▪ 063858d5 update gnss from daisy_sprout:9/PKQ1.180917.001/V10.0.7.0.PDLMIXM:user/release-keys
 ▪ 5b481d0b Merge branch '9.0' of https://github.com/SyberiaProject-Devices/proprietary_vendor_xiaomi into pie
 ▪ 4c199c1c chiron: update default display mode
 ▪ b6a7d32f msm8998-common: Add MIUI offmode charging daemon
 ▪ 0e031c2d msm8998-common: update perf stack from taimen q preview
 ▪ 70f40c6f msm8998-common: update graphics stack from taimen q preview
 ▪ 4ed9b4bd msm8998-common: add blobs for miui camera
 ▪ 1c65ba6d msm8998-common: update perf stack from taimen
 ▪ 57544043 msm8998-common: remove qti perf stack
 ▪ d6a7380c msm8998-common: Decommonize thermal-engine-8998-high.conf
 ▪ 56283c4d msm8998-common: Update blobs from 9.3.7
 ▪ 17d3130c msm8998-common: Add power_off_alarm blob
 ▪ 05a0bb7d msm8998-common: Hax libaudcal.so to store acdbdata in new path
 ▪ 633e38c4 msm8998-common: kang system-side ims blobs from daisy
 ▪ 3f74dc97 msm8998-common: remove libmedia.so libdirac dependency
 ▪ 46577631 msm8998-common: add missing blobs
 ▪ 5269370d chiron/msm8998-common: update blobs from 9.2.28
 ▪ 3eb43059 msm8998-common: add mlipay blobs
 ▪ 93a1eaa7 msm8998-common: Add QCOM's WFD implementation
 ▪ 1c51261a chiron: kang aptX blobs from taimen
 ▪ 673729f7 msm8998-common: switch to stock nfc firmware
 ▪ 38c653e4 msm8998-common: update SDM from LA.UM.7.4.r1-04100-8x98.0
 ▪ 44e6734e msm8998-common: Kang msm irqbalance from OnePlus5T
 ▪ ced90519 msm8998-common: Update ANT+ system blobs to P
 ▪ 2fd1e6ba msm8998-common: Kang sensors.qti from daisy
 ▪ a4fab4b6 msm8998-common: Kang CNEService.apk from daisy
 ▪ 49aa763c msm8998-common: Update tftp_server blobs to P from daisy
 ▪ 2d6b081e msm8998-common: Hack IMS apk to get rid of the stupid HD notification
 ▪ 8b37db89 msm8998-common: Kang ims.apk and qti-telephony-common.jar from daisy
 ▪ 155bfb53 chiron: remove unused elliptic dependencies
 ▪ 0eb8a175 msm8998-common: remove unused libmedia dependency of lib-dplmedia
 ▪ c330e801 msm8998-common: remove libandroid.so dependencies in camera stack
 ▪ df9add0b chiron/msm8998-common: update blobs from 9.1.24
 ▪ 6705fd4e msm8998-common: remove wcnss_filter
 ▪ 0e1f6f24 msm8998-common: add stock libraries needed for camera stack
 ▪ e3c32193 Revert "msm8998-common: shim missing skia symbols"
 ▪ 51a18d5f msm8998-common: kang cne from mata
 ▪ 8c5275fd msm8998-common: kang ims from mata
 ▪ 5a8e4d24 msm8998-common: remove qti gnss stack
 ▪ 2f6483eb msm8998-common: Move NFC firmware to /vendor/lib
 ▪ db4ca38a msm8998-common: switch to QCOM HIDL bluetooth stack
 ▪ 46ccdb58 sdm845-common: update blobs from 9.3.11 beta
 ▪ e78770ea sdm845-common: delete unneeded blob, regenerate makefile
 ▪ c3fb0bad msm8996-common: Move to proper thermal blobs
 ▪ ba55ccf6 kang blobs
 ▪ 82cfc301 gemini: makefile: Move NFC firmware to /vendor/lib
 ▪ f3a20267 gemini: Restore accidentaly killed hals.conf after b57c93fa090822232f6956d21b965f2b43200633
 ▪ 13f254dd gemini: Restore accidentaly killed QCDM files after f90c0d5442c8c6edd916d7da0efa5d130820645a
 ▪ be35f95e gemini: restore accidentally killed acdb data after 1ec595dcad1ca4eeb72a1cd5832a245f746f34e0
 ▪ cc8daa52 Import land
 ▪ 505756ec Update QPerformance.jar from sakura
 ▪ 43032cba sdm845-common: patch QPerformance.jar to get perfGetFeedback working
 ▪ bd9c86e7 sdm845-common: Update Perf stack from Mi A2 Lite (Daisy)
 ▪ a13ecfa9 sdm845-common: Add system Perf stack from stock
 ▪ 6bac5441 Drop santoni from common repo
 ▪ 4df9155e Drop whyred from common repo
 ▪ abaa9024 msm8996-common: Build some vendor blobs as modules
 ▪ a21ab225 msm8996-common: Update tftp_server from daisy
 ▪ 675f38a2 msm8996-common: Update sensor blobs from daisy
 ▪ 871a619b msm8996-common: Revert "Reset to stock sensor blobs"
 ▪ 09dce72e msm8996-common: Import msm_irqbalance from sailfish PPR2.181005.003
 ▪ 9073f3ad msm8996-common: remove cnss-daemon
 ▪ 69d7b71b msm8996-common: Import perf stack from wahoo
 ▪ 4374dc9c Update SDM blobs from LA.UM.7.5.r1-03700-8x96.0
 ▪ 9c757d69 jason: Add QCOM WFD stack
 ▪ 72522c24 jason: Move aptx blobs to system
 ▪ cf2817c9 jason: Update tftp_server blobs to P from nitrogen
 ▪ b6274057 jason: Drop unused vendor library dependencies
 ▪ be9ef0d0 jason: Remove prebuilt camera HAL and dependencies
 ▪ bad8c39f jason: Fix GCAM HDR on front camera
 ▪ 91cab819 jason: Update SDM blobs from LA.UM.7.4.r1-04100-8x98.0
 ▪ 4c73d68c jason: Kang nqnfcinfo from B2N_sprout
 ▪ 011508e3 jason: Massive blob update from nitrogen
 ▪ 7be4c3ce jason: Remove ipacm-diag
 ▪ b3efad22 jason: Remove unused jars
 ▪ cea6cd5b jason: Remove prebuilt libsensorndkbridge
 ▪ 8efc4309 jason: Remove unused 64bit sound trigger blobs
 ▪ 43417895 jason: Remove unused widevine blobs
 ▪ 8d4d4fe2 jason: Remove prebuilt ClearKey HIDL plugin
 ▪ 4a44ed54 jason: Hax to load MBN from /data/vendor/modem_config
 ▪ ca42ff1a jason: Remove unused libril-qc-qmi-1.so
 ▪ cdbb9126 jason: Add mlipay stack for Alipay fingerprint payment
 ▪ 6d185726 jason: Hack camera HAL to workaround the broken HAL3
 ▪ 6c539f59 jason: Update blobs from MIUI 10.2.3.0
 ▪ 413a7f54 jason: Drop unused secure UI blobs
 ▪ 836df963 jason: Add MIUI offmode charging daemon
 ▪ cf4df8dd jason: Add missing blobs
 ▪ 7c492245 jason: Update blobs from miui_MINote3_V10.0.5.0.OCHCNFH_c48c33b395_8.1
 ▪ e5a62248 jason: Fix some dependency issues found by static analysis
 ▪ c9a21281 jason: Update ANT+ system blobs to P
 ▪ 6afb7354 jason: Move NFC firmware to lib
 ▪ e19ad1a0 jason: Rename qti sensors daemon
 ▪ ccc22ab6 jason: Use vndk-27 sensorservice for libvideorefiner.so
 ▪ b49ce78f jason: add stock libraries needed for camera stack
 ▪ 56abf05c jason: Update blobs from B2N_sprout PPR1.180610.011
 ▪ 8e75aaf2 jason: Remove unused 64bit audio blobs
 ▪ 6e9ede43 jason: Add missing xtwifi certificate
 ▪ aa21b266 jason: Add xtwifi daemons
 ▪ 6a629d6e jason: Update blobs from miui_MINote3_V10.0.4.0.OCHCNFH_a5262b4c65_8.1
 ▪ 0cfc33a9 jason: Load camera configs from vendor
 ▪ c0c66831 jason: Move hardware specific files to vendor
 ▪ 07576402 jason: Add msm_irqbalance
 ▪ 89150e87 jason: Cleanup blob list
 ▪ c8d0b1af jason: Add libqminvapi.so
 ▪ d5eb4fd8 jason: Add QTI bluetooth stack
 ▪ b3d30387 jason: Add power-off alarm blobs
 ▪ 91ca6162 jason: Initial Oreo blobs
 ▪ 8b3e7fbb mido: Regen makefiles to use LOCAL_VENDOR_MODULE
 ▪ 8a705846 mido: Update blobs
 ▪ 72154a0d mido: drop unused consumerir blobs (replaced with oss earlier)
 ▪ dcb2e5e6 mido: revert all camera blobs to miui 7.5.4 to make ov13855 work
 ▪ ec0ee5a7 mido: Update blobs
 ▪ 1171face mido: camera: Revert ov13855 blobs to pre 7.5.25 state (7.4.24)
 ▪ b0597b7d mido: drop Camera HAL blobs, use OSS
 ▪ ff3c494c mido: Initial blobs
 ▪ 9f5e6e30 sagit: update blobs from MIUI 8.7.5
 ▪ f6295ed7 sagit: generate treble-compatible makefiles
 ▪ a78dbb1c sagit: move camera configs to vendor
 ▪ 6d36ad8a sagit: move tfa98xx firmware to vendor
 ▪ 509a889d sagit: move consumer ir to vendor
 ▪ 0a38fd82 sagit: add camera watermark
 ▪ a6eff90f chiron: update blobs from MIUI 8.7.5
 ▪ 52416c1a chiron: add camera watermark
 ▪ 77229c74 chiron: move ultrasound blobs to vendor
 ▪ 5b24c693 chiron: move tas2559 firmware to vendor
 ▪ 8bfe5d2e chiron: move camera configs to vendor
 ▪ f4eff166 chiron: generate treble-compatible makefiles
 ▪ 58c45c25 chiron/sagit: Move display calibration to vendor
 ▪ 613e7a2c capricorn: Update to MIUI 8.11.8 Global dev blobs
 ▪ 9dc90832 scorpio: Update to MIUI 8.11.8 Global dev blobs
 ▪ b8064d44 natrium: Update to MIUI 8.11.23 Global dev blobs
 ▪ 4dee0ed1 msm8996 targets: Decommonize Dirac ADSP module
 ▪ 91783bdf natrium: Update to MIUI 8.9.6 global dev blobs
 ▪ a4e4ec00 capricorn: Update to MIUI 8.9.6 global dev blobs
 ▪ 50c510eb msm8996 targets: Move NFC firmware to /vendor/lib
 ▪ 1394c297 lithium: Update to MIUI 8.5.10 Global dev blobs
 ▪ 8a2d9f03 lithium: Update to MIUI 8.4.19 Oreo blobs
 ▪ 5c445267 capricorn: Update fingerprint HAL
 ▪ 3c46ec26 capricorn: Remove 32-bit fingerprint libs
 ▪ 0d761660 capricorn: Regenerate makefiles
 ▪ a6cc0a58 capricorn / gemini / lithium: Move TFA calibration file to vendor
 ▪ 52841ce0 natrium: Regenerate makefiles
 ▪ 9337d234 natrium: Update QDCM calibration for JDI and Sharp panels
 ▪ b5f803fe natrium: Adjust FFC mount angle for OSS camera
 ▪ ad77c97a scorpio: Update to MIUI 8.5.10 Global dev blobs
 ▪ 3a529c4f scorpio: Update to MIUI 8.3.1 Oreo blobs
 ▪ 2c4991b8 scorpio: Restore stock camera config
 ▪ 1497975c capricorn: Update QDCM calibration for JDI and LGD panels
 ▪ b429392f lithium: Remove MSM ultrasound cruft
 ▪ 007a9b36 lithium: Restore stock camera config
 ▪ c100bd38 msm8996 targets: Regen makefiles for Treble compatibility
 ▪ 766d6f63 msm8996 targets: Move firmware blobs to /vendor
 ▪ 145cb437 msm8996 targets: Remove encrypted thermal engine configs
 ▪ f90c0d54 msm8996 targets: Move qdcm calibration files to /vendor
 ▪ 1ec595dc msm8996-common: Update audio stack and ADSP to O
 ▪ 77d38b85 lithium: Update to 8.1.4 dev blobs
 ▪ 782f1a90 lithium: Update to 7.10.19 dev blobs
 ▪ b0363a8f natrium: Update blobs to 8.1.4
 ▪ 21b084f3 natrium: Update blobs to 7.10.12
 ▪ 7df54c76 scorpio: Update blobs to 8.1.4
 ▪ f5934bd6 capricorn: Update blobs to 8.1.4
 ▪ 73a7bf73 capricorn: gemini: lithium: Add TFA calibration sound file
 ▪ d7a9aacf capricorn: Update blobs to 7.10.12
 ▪ bb974756 capricorn: Move qfp-daemon to vendor
 ▪ b57c93fa capricorn: gemini: lithium: natrium: scorpio: Move multihal config to vendor
 ▪ b77106f2 capricorn: Update blobs to 7.9.22
 ▪ 2778f097 capricorn: Update blobs from latest 7.0 release
 ▪ c6f85649 capricorn: Update blobs from latest 7.0 release
 ▪ 4f7bc0b0 capricorn: Update blobs from latest 7.0 release
 ▪ e90a92bf capricorn: Update blobs from latest 7.0 release
 ▪ 615faffb capricorn: Update blobs from latest 7.0 release
 ▪ faff326a capricorn: Update blobs from latest 7.0 release
 ▪ cfe49b3f capricorn: Update blobs from latest 7.0 release
 ▪ 6b989df3 capricorn: Update QFingerprintService app
 ▪ 9e158fdc capricorn: Update QFingerprintService app
 ▪ 59b44e11 capricorn: Update QFingerprintService app
 ▪ 607b0399 capricorn: Update blobs from latest 7.0 release
 ▪ e9cd4270 scorpio: Update to MIUI 7.6.5 dev blobs
 ▪ bbdd4b08 natrium: Update blobs to 7.9.22
 ▪ df8adda5 natrium: Update to MIUI 7.8.24 Global dev blobs
 ▪ ef2f0d6a natrium: Update fpc blobs
 ▪ 46ba9574 natrium: Update ACDB data
 ▪ 09d58c2e natrium: Fix default display mode
 ▪ a8444ad5 natrium: Update blobs from latest 7.0 release
 ▪ 74f072c5 natrium: Update blobs from latest 7.0 release
 ▪ 58afa488 lithium: Update to 7.9.21 dev blobs
 ▪ 128fbff5 lithium: Update to 7.7.20 dev blobs
 ▪ 285efb61 lithium: Update to MIUI 7.6.5 dev blobs
 ▪ 07d14402 msm8996-common: Decommonize sensor and thermal configs
 ▪ f0c79b31 lithium: Fix front camera mount angle
 ▪ b1b95039 lithium: Add initial blobs
 ▪ 0165e0d4 capricorn: Update blobs from latest 7.0 release
 ▪ f1d326d5 capricorn: Add IMX378 PDAF blobs
 ▪ c315e715 capricorn: Update blobs from latest 7.0 release
 ▪ 2efbc7fa capricorn: Initial commit
 ▪ e5205149 natrium: Initial commit
 ▪ d9571240 scorpio: Fix front camera mount angle
 ▪ bd8126f5 scorpio: Add initial blobs
 ▪ f16a5060 sdm845-common: Add QCOM's WFD implementation
 ▪ 22603337 sdm845-common: Remove unused jars and not required libs
 ▪ 49ee3a2e sdm845-common: Update to MIUI 9.2.15 blobs
 ▪ 64daf054 sdm845-common: Add dependencies required by MIUI 9.2.15 vendor images
 ▪ f559c6d2 sdm845-common: Ship system variant of postprocessing blobs
 ▪ e6e6608f polaris: Update to MIUI 9.2.15 blobs
 ▪ 244fb165 sdm845 targets: Regen makefiles and add new targets to build guard
 ▪ 1a177b15 sdm845-common: Add SDM blob needed for LiveDisplay HAL
 ▪ b4c18526 sdm845-common: Add SoterService app and remove unnecessary deps
 ▪ 770b66b9 sdm845-common: Add common aptX and aptX-HD audio blobs
 ▪ de5435a7 sdm845-common: Update to MIUI 8.12.20 Global dev blobs
 ▪ da354006 sdm845-common: Allow qcrilmsgtunnel to access android.hidl.manager
 ▪ fd8e026e sdm845-common: Update to MIUI 8.11.15 Global dev blobs
 ▪ bab2136f polaris: Add hotword enrollment
 ▪ 0b164c4a beryllium: Add FM libs
 ▪ 83ce787e sdm845 targets: Move to common P blobs
 ▪ 0472c7f5 sdm845-common: Ship proper postprocessing soundfx libs
 ▪ 3f299f05 beryllium: Add aptX libs
 ▪ e5d62e7f beryllium: Add initial system blobs
 ▪ 3b82c764 ursa: Add initial system blobs
 ▪ f86dc5de sdm845-common: Add MIUI offmode charging daemon
 ▪ 1fa38017 dipper: Add initial system blobs
 ▪ 4099aaf3 polaris: Remove VNDK compat blobs
 ▪ 94b31b7e polaris: Ship KTPI patched time daemon
 ▪ c0280c14 sdm845-common: Add permission for power-off alarm framework
 ▪ 2eb47064 polaris: Import VNDK blobs
 ▪ fa24b727 polaris: Add initial system blobs
 ▪ d7f5d889 whyred: Regenerate makefiles
 ▪ cb62a699 whyred: update blobs from 8.7.26 global
 ▪ 01b13393 whyred: update blobs from 8.7.5 global
 ▪ bb4cfd3a whyred: Remove all wayne camera libs
 ▪ be1f47e4 whyred: Add proprietary HIDL libantradio
 ▪ 418ae165 Add support for whyred (Redmi Note 5 pro)
 ▪ 542971d6 import land, santoni, and msm8937-common
 ▪ 1e57820f msm8953-common/tissot: Update blobs
 ▪ 074dd751 tissot: Drop unused camera blobs
 ▪ 924b5e53 msm8953-common: Update SDM blobs from LA.UM.7.5.r1-03700-8x96.0
 ▪ 855d56fb msm8953-common/tissot: Update blobs from V10.0.4.0
 ▪ b8f4ffd0 msm8953-common/tissot: Regenerate and fix
 ▪ 90b6e66c msm8953-common/tissot: Update blobs to P
 ▪ 46df69f8 tissot: Initial blobs
 ▪ 4aa5bfbb msm8953-common: Update blobs to 8.1
 ▪ 2255086e msm8953-common: dont build jars just copy them
 ▪ 6bb1ccd7 msm8953-common: Move telephony apps back to system
 ▪ 84c6c84f msm8953-common: Move thermal config to common tree
 ▪ 24eb3817 msm8953-common: Add initial blobs
 ▪ be2d74bd msm8956-common: Decommonize time service blobs
 ▪ 157b9b9f kenzo: Start using msm8956-common
 ▪ a16afe9c kenzo: Rename fingerprint HALs
 ▪ a2729924 kenzo: Update
 ▪ 8a809ac9 kenzo: Use OSS Camera HAL
 ▪ 97c562b2 kenzo: Update to MIUI 7.3.16 global dev blobs
 ▪ 6a813462 kenzo: Add bullhead widevine blobs
 ▪ b61e15d0 kenzo: Update blobs
 ▪ b545b2a3 kenzo: Ship prebuilt wcnss_service
 ▪ c71b3a3f kenzo: Update blobs
 ▪ 87db51c1 kenzo: Initial nougat checkout
 ▪ 0c0cb243 kenzo: Update blobs (#15)
 ▪ a1b165c9 kenzo: Regenerate makefiles (#14)
 ▪ 09143091 kenzo: Revert to previous radio blobs (#12)
 ▪ 1036f24e kenzo: Update blobs (#11)
 ▪ bda3792e kenzo: Update blobs
 ▪ e936d43a kenzo: Update blobs (#9)
 ▪ f8296b2c Add kenzo (Redmi Note 3)
 ▪ 3ffd3dea hydrogen: Start using msm8956-common
 ▪ c5be43c0 hydrogen: Update
 ▪ 3b972aca hydrogen: Use OSS Camera HAL
 ▪ f1416c60 hydrogen: Update to MIUI 7.3.16 global dev blobs
 ▪ af66dfb1 hydrogen: Update blobs
 ▪ 137dd771 hydrogen: Add bullhead widevine blobs
 ▪ a6b2b12b hydrogen: Update blobs from MIUI N
 ▪ 643b430e hydrogen: Ship prebuilt wcnss_service
 ▪ c4ea58cd Add Mi Max (hydrogen)
 ▪ 6320c808 msm8956-common: Add initial common blobs
 ▪ 7f837dce msm8998-common: add power off alarm blobs
 ▪ edaad6f4 msm8998-common: move RIL apps to vendor
 ▪ aad1363e msm8998-common: shim missing skia symbols
 ▪ a5d026b2 msm8998-common: remove unused 32bit ubi focus lib
 ▪ ae8763ce msm8998-common: remove unused sensors calibration lib
 ▪ 3daedb26 msm8998-common: add missing hazebuster lib
 ▪ be6aa996 msm8998-common: Really update blobs from MIUI 8.7.5
 ▪ 56fba666 msm8998-common: add libMiCameraHal dependency
 ▪ 09e0a6e4 msm8998-common: update blobs from MIUI 8.7.5
 ▪ 8e792f3a msm8998-common: Remove machine learning blobs
 ▪ 804691ba msm8998-common: Move qti-vzw-ims-internal permission to vendor
 ▪ 8f85229e msm8998-common: Move QTI permissions to vendor
 ▪ 1cff343f msm8998-common: remove port-bridge
 ▪ fc67b6a8 msm8998-common: generate treble-compatible makefiles
 ▪ 9c5ead86 msm8998-common: move non-jni camera libs to vendor
 ▪ 233a6598 msm8998-common: sed blobs to load camera configs from vendor
 ▪ 60eb21ba msm8998-common: move camera firmware to vendor
 ▪ 05c6e602 msm8998-common: move libqminvapi to vendor
 ▪ 16493488 msm8998-common: remove energy awareness daemon
 ▪ 5fc55ac2 msm8998-common: remove 64bit audio blobs
 ▪ f7ab97c0 msm8998-common: import polaris pn553 firmware
 ▪ 81bc3ba8 msm8998-common: sync with device tree
 ▪ 4b32bb75 msm8998-common: sync with device tree
 ▪ 13bf04e1 msm8998-common: add atfwd dependency
 ▪ 79d4f4e0 msm8998-common: Add atfwd daemon
 ▪ b1fa63b0 msm8998-common: Update blobs from 8.4.19
 ▪ 65dac5f9 msm8998-common: Allow qcrilmsgtunnel to access android.hidl.manager
 ▪ febb20b5 msm8998-common: Readd 32bit libsdm-disp-vndapis
 ▪ dd1433a3 msm8998-common: Cleanup camera blob list
 ▪ bafd9d22 msm8998-common: add and pin libskia copy for libMiCameraHal
 ▪ 5c057f7d msm8998-common: Add uce service
 ▪ 4813c82b msm8998-common: Remove unlinked blobs
 ▪ cf5afc23 msm8998-common: Remove unused camera blobs
 ▪ 420b9050 msm8998-common: Update blobs from 8.3.29
 ▪ 6d07fc20 msm8998-common: add dpm libs
 ▪ e1105485 msm8998-common: sync with device tree
 ▪ 925dc37d msm8998-common: add missing bluetooth qti blobs
 ▪ 11abf09d xiaomi: Import chiron and sagit blobs from MIUI 8.3.1

====================
     03-10-2019
====================
 ▼ art/
 ▪ 7397a8fd88 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/art into pie
 ▪ 62d0887a74 Merge branch 'pie' of https://github.com/Havoc-OS/android_art into pie
 ▪ b529bd7902 Snap for 5354036 from 0819df3536f7f461276f269a76a97410ec5c5d01 to p-keystone-qcom-release
 ▪ 0819df3536 Merge SPL-2019-02-05
 ▪ 9c3eee882a Merge "Snap for 5180536 from 1f5f55bfaa13923bc5483a6f9d8189ed4edc74a6 to pi-platform-release am: 242cf1b7d4" into pie-gsi
 ▪ af147371b8 Snap for 5180536 from 1f5f55bfaa13923bc5483a6f9d8189ed4edc74a6 to pi-platform-release am: 242cf1b7d4
 ▪ 016b254b71 Revert "Assume all x86/x86_64 hosts support at least sse4.x/popcount."

 ▼ bionic/
 ▪ 45a766773 Merge "Snap for 5240760 from 68f7efc044b4ff9813fba79e3e16e5804c4df651 to pi-platform-release am: 1863ecbca3" into pie-gsi
 ▪ b655aac27 Snap for 5240760 from 68f7efc044b4ff9813fba79e3e16e5804c4df651 to pi-platform-release am: 1863ecbca3
 ▪ 1863ecbca Snap for 5240760 from 68f7efc044b4ff9813fba79e3e16e5804c4df651 to pi-platform-release
 ▪ 30551b577 Snap for 5354036 from b085ef948306fb899219c3e3e50db029b8e8549d to p-keystone-qcom-release
 ▪ c8b427003 Merge tag 'android-9.0.0_r34' into pie
 ▪ 2f22fcca6 Merge tag 'android-9.0.0_r34' of https://android.googlesource.com/platform/bionic into pie
 ▪ b085ef948 Merge SPL-2019-02-05
 ▪ 06926c5ef Merge tag 'LA.UM.7.6.2.r1-06900-89xx.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie
 ▪ d3c8eccb3 Merge "Snap for 5180536 from b32be3f072132a2833e5ab963ce4a2592436805f to pi-platform-release am: d307fa248c" into pie-gsi
 ▪ 16b4bf518 Snap for 5180536 from b32be3f072132a2833e5ab963ce4a2592436805f to pi-platform-release am: d307fa248c

 ▼ bootable/recovery/
 ▪ bd8ed91d Snap for 5322077 from fc8af23e97cc29d4af5f3d4df05ffb339e34b08e to pi-qpr3-release
 ▪ fc8af23e Import translations. DO NOT MERGE

 ▼ build/kati/
 ▪ f4f43e6 Snap for 5180536 from 2a49513da00436f434281a98dfb118db855db013 to pi-platform-release am: a4c87794d2

 ▼ build/make/
 ▪ 28419b509 Merge "Make change and version bump to PPRL.190305.001 am: 0b004435b8" into pie-gsi
 ▪ c02d0cd84 Make change and version bump to PPRL.190305.001 am: 0b004435b8
 ▪ 0b004435b Make change and version bump to PPRL.190305.001
 ▪ 5f9f3e85b Make change and version bump to PQ3B.190305.001
 ▪ 7eca0ef0e Use flags from Soong for d8 and r8
 ▪ 5d9a0c8d1 build capricorn
 ▪ b703a4f48 Merge tag 'android-9.0.0_r34' of https://android.googlesource.com/platform/build into pie
 ▪ 63cca7773 Make change and version bump to PQ3B.190304.001
 ▪ 8420d3fb0 Make change and version bump to PQ3B.190303.001
 ▪ d59178c99 Version bump to PD2A.190115.032
 ▪ 75e9ab5da Version bump to PD2A.190115.031
 ▪ 6a392a163 Make change and version bump to PQ3A.190227.001
 ▪ 9c149d4e3 Merge "Adding per-partition SPL into AVB prop descriptors" into pie-gsi
 ▪ 3d5042ec3 Version bump to PD2A.190115.030
 ▪ 2fbceeaaf Version bump to PQ3B.190225.001
 ▪ d4b41e888 Adding per-partition SPL into AVB prop descriptors
 ▪ 406a81d94 Version bump to PQ3A.190220.002
 ▪ 3a44ce0c3 Merge "GSI vbmeta.img: set rollback_index to zero" into pie-gsi
 ▪ 5b005e21e GSI vbmeta.img: set rollback_index to zero
 ▪ 063cc7793 Make change and version bump to PQ3A.190220.001
 ▪ 8d68f91aa [automerger skipped] [DO NOT MERGE] Update platform security string to 2019-04-01 on oc-mr1-dev Bug:124119313 am: 7d7a3cbcc8 -s ours am skip reason: subject contains skip directive
 ▪ 7d7a3cbcc [DO NOT MERGE] Update platform security string to 2019-04-01 on oc-mr1-dev Bug:124119313
 ▪ 19bc5dc42 Version bump to PD2A.190115.029
 ▪ f44f4f617 Version bump to PD2A.190115.028
 ▪ 77db5b24a Version bump to PD2A.190115.027
 ▪ ced97517e Version bump to PD2A.190115.026
 ▪ a7c28c8b7 Version bump to PD2A.190115.025
 ▪ 3677ecfb4 Version bump to PD2A.190115.024
 ▪ 3b2883af6 Version bump to PD2A.190115.023
 ▪ de4669b4a Make change and version bump to PQ2A.190405.003
 ▪ 4e41f6550 Update Security String to 2019-04-05 Bug: 124119313 (cherry picked from commit 0b5a344dc3b1f13b69983a711467dbe94251011a)
 ▪ cbe4d3231 Version bump to PQ2A.190405.002
 ▪ 9886f404c Version bump to PQ2A.190405.001
 ▪ af2091dc1 Version bump to PQ2A.190401.002
 ▪ d9d31408f Make change and version bump to PQ3A.190213.001
 ▪ de89602c4 Version bump to PD2A.190115.022
 ▪ c013cf9df Version bump to PD2A.190115.021
 ▪ 767da03f5 Version bump to PD2A.190115.020
 ▪ b586161e0 Merge "Make change and version bump to PPRL.190205.001 am: 641da2907b" into pie-gsi
 ▪ 8710ed839 Make change and version bump to PPRL.190205.001 am: 641da2907b
 ▪ 3142b47f3 Version bump to PD2A.190115.019
 ▪ af791fc78 Version bump to PD2A.190115.018
 ▪ d3ffeda72 Version bump to PQ2A.190401.001
 ▪ b6c85ea97 Make change and version bump to PQ2A.190305.003
 ▪ a9da159ce Update Security String to 2019-04-01 Bug: 124119313 (cherry picked from commit f9835d9f4d39c78ddf35899b058498f1908e906e)

 ▼ development/
 ▪ 33a187438 Snap for 5339334 from 943d60667ab79c81ab65446b04a2c48145944115 to pi-qpr3-release
 ▪ 239859423 Snap for 5335558 from 943d60667ab79c81ab65446b04a2c48145944115 to pi-qpr3-b-release
 ▪ 943d60667 Import translations. DO NOT MERGE
 ▪ 169d5341f Merge "Snap for 5180536 from 38db7cf10596b743cf0c5e0c67809e384190f4e6 to pi-platform-release am: 37919f4f6f" into pie-gsi
 ▪ 0a7b19765 Snap for 5180536 from 38db7cf10596b743cf0c5e0c67809e384190f4e6 to pi-platform-release am: 37919f4f6f

 ▼ device/havoc/sepolicy/
 ▪ a7a7955 Allow Gallery to access system_app_data_file
 ▪ 4320af8 Merge branch 'pie' of https://github.com/Havoc-OS/android_device_havoc_sepolicy into pie
 ▪ 4d243cf Move snap/gallery definitions back to private
 ▪ 8e54518 Label adb.network.port as system_prop
 ▪ 0af9570 Make backuptool permissive only in non user builds
 ▪ 4135901 Make sysinit permissive
 ▪ 3fc7abf havoc: Use set_prop() macro for setting adb tcp property
 ▪ 717dfce qcom: Remove power HAL 1.0 label
 ▪ c64b044 sepolicy: Allow recovery update_engine to setexec backuptool
 ▪ 82b4901 Remove not allowed rule
 ▪ 1781204 Snap and gallery require to run vendor code
 ▪ abab8d2 sepolicy: common: Add a label for /data/havoc_updates
 ▪ 1b85ee8 Revert "sepolicy: remove local adb port property"
 ▪ f7befb2 Make A/B backuptool permissive
 ▪ e8a3125 common: Improve label of I/O sched tuning nodes
 ▪ 481bd67 havoc: Address perf HAL denial with boost enabled

 ▼ device/qcom/sepolicy/
 ▪ 34fc44b0 sepolicy: Label persist.nfc.hci_network_reset_req
 ▪ 42ffdb29 Merge 7db348e4bc6bd8a300d1968ef4f5945c984a6c15 on remote branch
 ▪ 9462846f sepolicy:esgda: add app domain for esgda test app
 ▪ 2177fc68 Merge b6482e7620927269a32c71fb8f30560544991021 on remote branch
 ▪ 35ce010a Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ 2dfaf3d6 trinket: Remove vendor media trinket version property
 ▪ 8590ece7 Merge tag 'LA.UM.7.6.2.r1-07100-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ 7db348e4 Merge "Sepolicy : Do not audit system process access to vendor_gles_data_file"
 ▪ aa2dcf0e Sepolicy : Do not audit system process access to vendor_gles_data_file
 ▪ 03cf20e3 Merge "sepolicy: add rule to allow operations on USBPD and QG nodes"
 ▪ cfd94b10 Merge "Allow qvrd to use binder for checking camera permissions"
 ▪ 630a065e sepolicy: Label vendor.camera.* lists
 ▪ 26ff7ac7 sepolicy: Whitelist vold from reading mnt_vendor_file
 ▪ 5ccf0169 Merge b6482e7620927269a32c71fb8f30560544991021 on remote branch
 ▪ a92accc1 sepolicy: add rule to allow operations on USBPD and QG nodes
 ▪ ec77564e Merge 13d2d3ba44df2b61f6251fa456a8729032c7ac02 on remote branch
 ▪ fb2cbc1f Sepolicy: Update sepolicy ops listener
 ▪ 0f91eedf Merge 13d2d3ba44df2b61f6251fa456a8729032c7ac02 on remote branch
 ▪ 6d3984bb sepolicy: vendor network time sync property accessiable
 ▪ b6482e76 sepolicy: add sepolicy for usta_app to open system_data_file
 ▪ 13d2d3ba Merge "Sepolicy: add rule for seempd"
 ▪ 6b2ffca7 sepolicy: Add sepolicy rules for msm8996
 ▪ 9ad031d5 Adding sepolicy rules for qvrservice
 ▪ f2fd0f0f Sepolicy: add rule for seempd

 ▼ device/qcom/sepolicy-legacy/
 ▪ 8cd0ca1 sepolicy: Resolve cameraserver denials
 ▪ 18203e2 legacy: Resolve hal_camera_default denials
 ▪ 2310fa8 sepolicy: Label vendor.post_boot.parsed
 ▪ 78c6497 sepolicy: Resolve hal_nfc denials
 ▪ 6447cb7 legacy: Resolve rome BT denials
 ▪ 6185be5 sepolicy: Correctly label display.qservice per SoC
 ▪ 62e0e65 Revert "legacy: allow init to read /proc/device-tree"
 ▪ 21dd2e0 legacy: Label /data/misc/display again
 ▪ 9f1e187 legacy: Ignore neverallows

 ▼ device/xiaomi/gemini/
 ▪ 987c94c11 update clang to 9.0.0-20190309
 ▪ e2fd455cb priv-app control: restore com.android.camera2 permissions
 ▪ 14d786820 update sepolicy
 ▪ 26bfc259a Enable workaround for old MCC/MNC format
 ▪ 5dfa1b125 LocIpc could be using data member from a deleted obj
 ▪ 3bf49517b Havoc 2.3
 ▪ 8634ef785 Android 9.0.0 Release 34 (PQ2A.190305.002)
 ▪ 528c0c90d update ueventd.qcom.rc
 ▪ a72935421 build capricorn
 ▪ 51f05623b stop tracking my patches
 ▪ 5f530ef99 caf tag: LA.UM.7.6.2.r1-07100-89xx.0
 ▪ 08269a82e prop: Disable VSync for CPU rendered apps
 ▪ 624a17c07 overlay: Increase system_icon_area weight
 ▪ 3f345ee43 Build some vendor blobs as modules
 ▪ 9b2003ba2 Add hostapd configs needed for CAF wlan
 ▪ 77e69e565 address some priv-apps permissions
 ▪ dfa2eb648 update generate_gemini_info.sh
 ▪ c10eac432 cleanup device tree
 ▪ 4c6eb93c9 small fstab update
 ▪ b8156aee0 update patches 23022019
 ▪ 467d430df msm8996-common: Switch to HIDL ANT+ HAL
 ▪ 547ece742 track frameworks/native
 ▪ 528e6f380 update patches to lastest havoc sources
 ▪ 138e0b884 DragonTC clang version 9.0.0-20190216 (based on LLVM 9.0.0svn)
 ▪ 5bbb1227e update tools/generate_gemini_info.sh
 ▪ be058055f move google prebuilts to vendor/havoc
 ▪ 01c8ff696 Unofficial from now

 ▼ device/xiaomi/translations/
 ▪ 4c757a6 s
 ▪ 6c9d8e5 init

 ▼ external/bash/
 ▪ a40f251 bash: Silence all build warnings

 ▼ external/chromium-webview/
 ▪ 7390467 Update x86/x86_64 Chromium Webview to 72.0.3626.121
 ▪ 87831f7 Update arm/arm64 Chromium Webview to 72.0.3626.121
 ▪ fbc003a Update x86/x64 Chromium Webviews to 71.0.3578.99

 ▼ external/exfat/
 ▪ 5e45863 Android: remove "tags" from Android.bp.

 ▼ external/f2fs-tools/
 ▪ ce78365 Snap for 5180536 from eeedf7c7d04c223ea9e27674fd3809b5506ca5f4 to pi-platform-release am: befee77b22

 ▼ external/google/
 ▪ 2f619e2 Code improvements for application fall-back
 ▪ 095c665 Restore accidental removal of HapticClick logic
 ▪ 69c5347 App Picker: Move back press override to vendor/support
 ▪ cae3995 Fallback to "no action" when an application gets removed [1/2]
 ▪ f7a179d Active Edge: allow to choose a specific app activity [1/4]
 ▪ 0206ad0 Introduce long squeeze action [1/3]
 ▪ 9d96620 CustomActions: Use settings provider to store value [1/3]
 ▪ 3443a22 Actions: Add ringer modes
 ▪ 62ea15d NavigationBarEffect code cleanup
 ▪ 6009c35 SquishyNavbar: If power saver is on, don't allow feedback
 ▪ 758feef CustomActions: Add support to launch applications [1/2]
 ▪ e563263 CustomActions: Screen off availability
 ▪ 48994c1 Gestures: Add camera action
 ▪ 75a6e42 Remove more machine like cycles from ElmyraService
 ▪ 9cff1c0 Remove more loggers and rename classes as I found them
 ▪ d5ce050 Additional cleanup for janky methods

 ▼ external/icu/
 ▪ 8a37e093e Snap for 5180536 from de2840610207b58bede6041532b5db77173aad33 to pi-platform-release am: c6aa8e95a6

 ▼ external/libjpeg-turbo/
 ▪ 2432a51 libjpeg-turbo: update to 2.0.2

 ▼ external/libmpeg2/
 ▪ 86fb3af Add push-pop for Neon D8-D15 registers

 ▼ external/nano/
 ▪ 4240423b help: in the tiny version, don't list an option that is the default
 ▪ 74752686 help: don't list the obsoleted -O and -S options in the --help output
 ▪ 4205567b tweaks: add deprecation comments to the four superseded options
 ▪ a20340b5 copyright: update the years for significantly changed files
 ▪ 932a35c0 tweaks: normalize the indentation, and remove unneeded braces
 ▪ 877a6498 justify: when justifying a marked region, strip whitespace after the lead
 ▪ 5d7b723c justify: put a mid-line marked region onto separate lines
 ▪ 053244db justify: handle the leading part when justifying a marked region
 ▪ f7f5514e new feature: marked text gets justified into a single, new paragraph
 ▪ afa0097c tweaks: rename a variable, to prepare for its new role
 ▪ 6e960012 tweaks: split justify_paragraph() into three separate functions
 ▪ 311a7138 tweaks: adapt find_paragraph()/justify_paragraph() for multiple quotes
 ▪ 0ac04347 tweaks: remove unnecessary variable initializations
 ▪ 610be482 docs: suggest a setting for 'stripecolor' in the sample nanorc
 ▪ 9ad3a179 syntax: nanorc: stop coloring 'unset fill ...' as if it were valid
 ▪ 6e04d697 docs: describe the new options -J, --guidestripe, and 'set stripecolor'
 ▪ 916b4d81 rcfile: add 'stripecolor' for changing the color of the guiding stripe
 ▪ 66c6eb51 new feature: option --guidestripe that shows a vertical guiding bar
 ▪ 43b42246 display: properly handle double-width characters when spotlighting
 ▪ 40a74e46 display: correct the logic for making room for the ">" character
 ▪ c3cd0f34 help: reword the description of ^U to avoid the impression of "Undo"
 ▪ 85e89550 display: scroll horizontally one column earlier
 ▪ 37c8232f bindings: provide usable shortcuts for prevword/nextword in tiny version
 ▪ f13dd140 display: correctly trim an overshooting character from a prompt answer
 ▪ de47b58d tweaks: move declaration of variable that does not need to be global
 ▪ a5ef013e history: use an unfreed 'position_history' to avoid a possible crash
 ▪ 70da1889 feedback: complete the removal of some superfluous words
 ▪ 1eb639d5 display: show "[" for half of two-column character also when softwrapping
 ▪ 79ca3cea copyright: update the years for the FSF
 ▪ b5ca8a00 tweaks: rename three functions and two symbols, to match the new wording
 ▪ 2c7d3367 bindings: rename 'cutwordleft' to 'chopwordleft', and similar for right
 ▪ 15c3e924 help: reword the tags for deleting a word left and right
 ▪ 1053a3c4 feedback: remove some superfluous words from Undid/Redid messages
 ▪ 7c30d1fa display: account for zero-width characters when reserving space for '>'
 ▪ 031166c3 help: don't list the unbound <Alt+Up> and <Alt+Down> in the tiny version
 ▪ 5e769686 docs: mention that 'cutwordleft' is bound to <Shift+Ctrl+Delete>
 ▪ df4d1819 help, docs: say "Delete" when things don't go into the cutbuffer
 ▪ 7fcf6e60 menus: don't show ^S and ^Q in the help lines in the tiny version
 ▪ 0f9d60a3 tweaks: split a variable into two, as they have different roles
 ▪ 11a66d74 tweaks: condense and correct a comment
 ▪ d3fdd204 tweaks: rename an overlooked variable from a single letter to a word
 ▪ 82492ead tweaks: rename two variables, to be less confusing
 ▪ 00713a7c docs: deprecate the use of morespace, smooth, nonewlines, and nowrap
 ▪ 420fe4d1 tweaks: switch from checking MORE_SPACE to checking EMPTY_LINE
 ▪ 322a6f46 tweaks: switch from checking SMOOTH_SCROLL to checking JUMPY_SCROLLING
 ▪ b6a76223 tweaks: switch from referencing NO_NEWLINES to referencing FINAL_NEWLINE
 ▪ 54055b61 tweaks: switch from referencing NO_WRAP to referencing BREAK_LONG_LINES
 ▪ 32702501 docs: mention that --morespace and --smooth are obsolete and ignored
 ▪ cb7c8255 options: warn when option -O or -S is given, and ignore them
 ▪ 60bdac2b docs: describe breaklonglines, emptyline, finalnewline, jumpyscrolling
 ▪ f6c767a3 docs: describe the four new options (-b, -f, -j, -e)
 ▪ 6c89815e docs: stop saying that --fill switches on automatic hard-wrapping
 ▪ 894aff08 options: let --fill no longer imply automatic hard-wrapping
 ▪ 556c0a38 rcfile: when an old flag is unset, set the corresponding new flag
 ▪ 4d40bea5 rcfile: add the options that correspond to -b, -f, -j, and -e
 ▪ ee979ae7 options: add -e, --emptyline, the counterpart of --morespace
 ▪ 401e4396 options: add -j, --jumpyscrolling, the counterpart of --smooth
 ▪ 5dbd9c00 options: add -f, --finalnewline, the counterpart of --nonewlines
 ▪ cd9328fb options: add -b, --breaklonglines, the counterpart of --nowrap
 ▪ 7811f3fc menus: put the ^T toggle in Search in the same position as in Goto-Line
 ▪ 5f07b96d menus: move the paragraph-jumping functions from Search to Goto-Line
 ▪ bc98dbca menus: remove the ^Y and ^V shortcuts from the Search menus
 ▪ 252bb600 display: highlight the ">"/"<" continuation characters in reverse video
 ▪ 6d34b8a5 display: change the "$" continuation character to ">" and "<"
 ▪ ad505e7f display: represent half of a double-width character with "[" and "]"
 ▪ e7557a92 tweaks: condense a handful of comments
 ▪ 757d2230 tweaks: don't bother executing two functions that are empty
 ▪ ea4ba3a1 tweaks: add an alias for a string variable, so the code makes more sense
 ▪ 32d7d390 tweaks: reshuffle a few lines, and condense some comments
 ▪ b57336ad tweaks: rename some variables, to match others that have the same task
 ▪ ebfe7528 tweaks: rename some variables from a single letter to meaningful word
 ▪ 14f32577 display: ensure that spotlighted text is not treated as a prompt answer

 ▼ external/openssh/
 ▪ fd10cf02 upstream: Move checks for lists of users or groups into their own
 ▪ ab5fee8e upstream: Reset last-seen time when sending a keepalive. Prevents
 ▪ c13b7453 upstream: PKCS#11 support is no longer limited to RSA; ok benno@
 ▪ e9552d60 upstream: in ssh_set_newkeys(), mention the direction that we're
 ▪ 729a9063 openssh: Silence build warnings
 ▪ 76a24b3f upstream: Fix two race conditions in sshd relating to SIGHUP:
 ▪ de817e9d upstream: mention PKCS11Provide=none, reword a little and remove
 ▪ 95a8058c upstream: let PKCS11Provider=none do what users expect
 ▪ 8e7bac35 upstream: dup stdout/in for proxycommand=-, otherwise stdout might
 ▪ 9b61130f upstream: openssh-7.9 accidentally reused the server's algorithm lists
 ▪ 37638c75 Cygwin: implement case-insensitive Unicode user and group name matching
 ▪ bed1d436 Revert unintended parts of previous commit.
 ▪ f02afa35 Revert "[auth.c] On Cygwin, refuse usernames that have differences in case"
 ▪ 4c55b674 Add tags to .gitignore
 ▪ 625b6263 upstream: perform removal of agent-forwarding directory in forward
 ▪ d9ecfaba upstream: sync the description of ~/.ssh/config with djm's updated
 ▪ 38e83e4f upstream: fix regression in r1.302 reported by naddy@ - only the first
 ▪ 5c68ea8d upstream: cleanup GSSAPI authentication context after completion of the
 ▪ a8c807f1 upstream: ssh-keygen -D pkcs11.so needs to initialize pkcs11

 ▼ external/p7zip/
 ▪ b3b6f89 p7zip: Silence all warnings

 ▼ external/proguard/
 ▪ 118ffd4 Allow passing extra java arguments to proguard

 ▼ external/rsync/
 ▪ 4a30b87d rsync: Silence build warnings

 ▼ external/skia/
 ▪ 22516de142 Snap for 5354036 from b95f1fff74da7210d45ac88ff3fc629ca0449997 to p-keystone-qcom-release
 ▪ bf999383ab RESTRICT AUTOMERGE: Make listener lists threadsafe with a mutex.
 ▪ 986a6682e5 Revert "Add rect-parameter to makeImageSnapshot and stop using chromium config options"
 ▪ b95f1fff74 Merge SPL-2019-02-05
 ▪ 18676d83b3 Snap for 5304822 from 5b3adf422c7fc2271b45970b00f105e2e65c3555 to pi-qpr3-release
 ▪ 27de54bf63 Add rect-parameter to makeImageSnapshot and stop using chromium config options
 ▪ 65c79392a9 fGpu is null when GrGpuResource::release
 ▪ 734565b39f Merge "Snap for 5180536 from 68d9148bf8426539a323adb3a7b6cb422101ae0d to pi-platform-release am: 6d8eb3c792" into pie-gsi
 ▪ d0bc9c2b34 Snap for 5180536 from 68d9148bf8426539a323adb3a7b6cb422101ae0d to pi-platform-release am: 6d8eb3c792

 ▼ external/sqlite/
 ▪ c23543f sqlite: upgrade to SQLite 3.27.2

 ▼ external/tremolo/
 ▪ e841f0f Add some error/overflow checks in codebook handling

 ▼ external/unrar/
 ▪ 9b2e2b9 unrar: Silence more build warnings

 ▼ external/vim/
 ▪ e165f6359 patch 8.1.1004: function "luaV_setref()" not covered with tests
 ▪ 6edbbd811 patch 8.1.1003: playing back recorded key sequence mistakes key code
 ▪ cbef8e1aa patch 8.1.1002: "gf" does not always work when URL has a port number
 ▪ 8156ed375 patch 8.1.1001: Visual area not correct when using 'cursorline'
 ▪ fd731b0e3 patch 8.1.1000: indenting is off
 ▪ 9d7fdd403 patch 8.1.0999: use register one too often and not properly tested
 ▪ 19a66858a patch 8.1.0998: getcurpos() unexpectedly changes "curswant"
 ▪ d5a5886ce patch 8.1.0997: using GUI colors in vim.exe when 'termguicolors' is off
 ▪ 6bb8c66c8 patch 8.1.0996: a few screendump tests fail because of scrolling
 ▪ f0fab3046 patch 8.1.0995: a getchar() call resets the reg_executing() result
 ▪ 8fcb60f96 patch 8.1.0994: relative cursor position is not calculated correctly
 ▪ 772153f8d patch 8.1.0993: ch_read() may return garbage if terminating NL is missing
 ▪ cce713ddc patch 8.1.0992: a :normal command resets the reg_executing() result
 ▪ 975880b6e patch 8.1.0991: cannot build with a mix of features
 ▪ e21c1580b patch 8.1.0990: floating point exception with "%= 0" and "/= 0"
 ▪ bdace838c patch 8.1.0989: various small code ugliness
 ▪ d82a81cad patch 8.1.0988: deleting location list buffer breaks location list window
 ▪ 6ef8f9eac patch 8.1.0987: unnecessary condition in #ifdef
 ▪ ef8c95617 patch 8.1.0986: rename() is not propertly tested
 ▪ ab350f89f patch 8.1.0985: crash with large number in regexp
 ▪ c69efcb42 patch 8.1.0984: unnecessary #ifdefs
 ▪ 1eed53299 patch 8.1.0983: checking __CYGWIN32__ unnecessarily
 ▪ 32033d239 patch 8.1.0982: update_cursor() called twice in :shell
 ▪ 5b868a82e patch 8.1.0981: pasting in terminal insufficiently tested
 ▪ 58d63a0a2 patch 8.1.0980: extend() insufficiently tested
 ▪ 1fa8fdd61 patch 8.1.0979: compiler warning for unused functions
 ▪ 2472ae81d patch 8.1.0978: blob not tested with Perl
 ▪ 0d13cce34 patch 8.1.0977: blob not tested with Ruby
 ▪ e4963c543 patch 8.1.0976: dosinstall still has buffer overflow problems
 ▪ c66638836 patch 8.1.0975: using STRNCPY() wrongly. Warning for uninitialized variable
 ▪ 882d02eeb patch 8.1.0974: cannot switch from terminal window to previous tabpage
 ▪ cd62512c5 patch 8.1.0973: pattern with syntax error gives threee error messages
 ▪ 72e83c1ae patch 8.1.0972: cannot switch from terminal window to next tabpage
 ▪ f6b401090 Update runtime files
 ▪ 55d3bdbbe patch 8.1.0971: failure for selecting quoted text object moves cursor
 ▪ ed79d1e34 patch 8.1.0970: text properties test fails when 'encoding' is not utf-8
 ▪ 97c2c05ea patch 8.1.0969: message written during startup is truncated
 ▪ 527a2d86f patch 8.1.0968: crash when using search pattern \%Ufffffc23
 ▪ 1417031cf patch 8.1.0967: stray dependency in test Makefile
 ▪ 3876789b2 patch 8.1.0966: one terminal test is flaky
 ▪ e86ecbd92 patch 8.1.0965: search test fails
 ▪ 353aca121 patch 8.1.0964: cannot see in CI why a screenshot test failed
 ▪ 4a7d2d3b4 patch 8.1.0963: illegal memory access when using 'incsearch'
 ▪ d91e5dafd patch 8.1.0962: building with MinGW and static libs doesn't work
 ▪ 916683842 patch 8.1.0961: Mac: fsync may fail sometimes
 ▪ 8caa43d81 patch 8.1.0960: when using ConPTY garbage collection has undefined behavior
 ▪ a25e3d069 patch 8.1.0959: sorting large numbers is not tested
 ▪ 38f08e76a patch 8.1.0958: compiling weird regexp pattern is very slow
 ▪ 358567188 patch 8.1.0957: Mac: fsync fails on network share
 ▪ b9ddda6c2 patch 8.1.0956: using context:0 in 'diffopt' does not work well
 ▪ 66ae3d199 patch 8.1.0955: matchit autoload directory not in installer
 ▪ 0d8562a99 patch 8.1.0954: arguments of semsg() and siemsg() are not checked
 ▪ c9629251a patch 8.1.0953: a very long file is truncated at 2^31 lines
 ▪ bbd854dc5 patch 8.1.0952: compilation warnings when building the MS-Windows installer
 ▪ 44b443c5d patch 8.1.0951: using WIN64 even though it is never defined
 ▪ 14816ad6e patch 8.1.0950: using :python sets 'pyxversion' even when not executed
 ▪ 0472b6d14 patch 8.1.0949: MS-windows defines GUI macros different than other systems
 ▪ d53931ae7 patch 8.1.0948: when built without +eval "Vim --clean" produces errors
 ▪ 7dca2ebbc patch 8.1.0947: using MSWIN before it is defined
 ▪ c85489888 Revert change accidentally included in runtime file updates.  Closes #3998.
 ▪ b0e2da2b2 patch 8.1.0946: Coveralls is not very useful
 ▪ 4c92e75dd Update runtime files.
 ▪ a5483448c patch 8.1.0945: internal error when using pattern with NL in the range
 ▪ c85c8fcb9 patch 8.1.0944: format of nbdbg() arguments is not checked
 ▪ 749f07c0d patch 8.1.0943: still a trace of Farsi support
 ▪ 76cbe811d patch 8.1.0942: options window still checks for the multi_byte feature
 ▪ 4f97475d3 patch 8.1.0941: macros for MS-Windows are inconsistent
 ▪ 78d21dae9 patch 8.1.0940: MS-Windows console resizing not handled properly
 ▪ 3678f65d4 patch 8.1.0939: no completion for sign group names
 ▪ 21edde874 patch 8.1.0938: background color is wrong in MS-Windows console
 ▪ f1b57ab2a patch 8.1.0937: invalid memory access in search pattern
 ▪ 55c77cf2e patch 8.1.0936: may leak memory when using 'vartabstop'
 ▪ 8bfd9469c patch 8.1.0935: old regexp engine may use invalid buffer
 ▪ 985079c51 patch 8.1.0934: invalid memory access in search pattern
 ▪ 6982f42f3 patch 8.1.0933: When using VTP scroll region isn't used properly
 ▪ 14184a313 patch 8.1.0932: Farsi support is outdated and unused
 ▪ 6902c0eb2 patch 8.1.0931: vtp_working included in GUI build but unused
 ▪ 0a1b17bbe patch 8.1.0930: typo in Makefile
 ▪ 5acd98725 patch 8.1.0929: no error when requesting ConPTY but it's not available
 ▪ d634024b9 patch 8.1.0928: stray log function call
 ▪ 005907400 patch 8.1.0927: USE_CR is never defined
 ▪ e93e5a504 patch 8.1.0926: no test for :wnext, :wNext and :wprevious
 ▪ 5ff7df509 patch 8.1.0925: terminal scrollback test still still flaky
 ▪ 7e841e3ce patch 8.1.0924: terminal scrollback test still flaky
 ▪ c3ef89660 patch 8.1.0923: terminal dump diff swap does not update file names
 ▪ 96baf02aa patch 8.1.0922: terminal scrollback test is flaky
 ▪ 81aa0f56f patch 8.1.0921: terminal test sometimes fails; using memory after free
 ▪ 29ae223dd patch 8.1.0920: in Terminal-Normal mode job output messes up the window
 ▪ 0f77d6afd patch 8.1.0919: compiler warnings
 ▪ 9b5c1fcde patch 8.1.0918: MS-Windows: startup messages are not converted
 ▪ 445e71c5e patch 8.1.0917: double free when running out of memory
 ▪ b999ba277 patch 8.1.0916: with Python 3.7 "find_module" is not made available
 ▪ a78701951 patch 8.1.0915: fsync() may not work properly on Mac
 ▪ 5fd0f5052 patch 8.1.0914: code related to findfile() is spread out
 ▪ 688b3983d patch 8.1.0913: CI crashes when running out of memory
 ▪ 18442cbcc patch 8.1.0912: MS-Windows: warning for signed/unsigned
 ▪ 943e9639a patch 8.1.0911: tag line with Ex command cannot have extra fields
 ▪ 15bbd6ec8 patch 8.1.0910: crash with tricky search pattern
 ▪ d9ef1b8d7 patch 8.1.0909: MS-Windows: using ConPTY even though it is not stable
 ▪ 9403a2168 patch 8.1.0908: can't handle large value for %{nr}v in regexp
 ▪ 5382f12c9 patch 8.1.0907: CI tests on AppVeyor are failing
 ▪ e1ed53f3f patch 8.1.0906: using clumsy way to get console window handle
 ▪ 5567ad48b patch 8.1.0905: complicated regexp causes a crash
 ▪ 00f148d2f patch 8.1.0904: USE_LONG_FNAME never defined
 ▪ beb7574d6 patch 8.1.0903: struct uses more bytes than needed
 ▪ ff697e6ce patch 8.1.0902: incomplete set of assignment operators
 ▪ 57ee2b6e0 patch 8.1.0901: index in getjumplist() may be wrong
 ▪ 48773f1f8 patch 8.1.0900: ConPTY many crash with 32-bit build
 ▪ e0fb7d1e3 patch 8.1.0899: no need to check restricted mode for setwinvar()
 ▪ 0ea21e41c patch 8.1.0898: a messed up rgb.txt can crash Vim
 ▪ 05c00c038 patch 8.1.0897: can modify a:000 when using a reference
 ▪ 5a6698169 patch 8.1.0896: tests for restricted mode no run for MS-Windows GUI
 ▪ ec0f50a35 patch 8.1.0895: MS-Windows: dealing with temp name encoding not quite right
 ▪ dce1e89be patch 8.1.0894: MS-Windows: resolve() does not return a reparse point
 ▪ 3615abb69 patch 8.1.0893: terminal test is a bit flaky
 ▪ eeb1b9c7e patch 8.1.0892: failure when closing a window when location list is in use
 ▪ d77aa4d22 patch 8.1.0891: substitute command inssuficiently tested
 ▪ 593864817 patch 8.1.0890: pty allocation wrong if using file for out channel
 ▪ 6524068ff patch 8.1.0889: MS-Windows: a channel write may hang
 ▪ 31b816042 patch 8.1.0888: the a: dict is not immutable as documented
 ▪ 9474716d3 patch 8.1.0887: the 'l' flag in :subsitute is sticky
 ▪ b76336116 patch 8.1.0886: compiler warning for NULL pointer and condition always true

 ▼ external/wpa_supplicant_8/
 ▪ f1e24465 wpa_supplicant: Disable EAP_PROXY
 ▪ 6cba6c5f Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/external/wpa_supplicant_8 into 9.0

 ▼ external/zip/
 ▪ c4117e1 zip: Silence build warnings

 ▼ frameworks/av/
 ▪ 797d8d644a Merge "Snap for 5240760 from accfc6586bce6ff5bceea8969fb5c0d5db6e4f04 to pi-platform-release am: a31eb276a3" into pie-gsi
 ▪ e68c2c684d Snap for 5240760 from accfc6586bce6ff5bceea8969fb5c0d5db6e4f04 to pi-platform-release am: a31eb276a3
 ▪ a31eb276a3 Snap for 5240760 from accfc6586bce6ff5bceea8969fb5c0d5db6e4f04 to pi-platform-release
 ▪ 34f058f907 [automerger] Reserve enough space for RTSP CSD am: c025be8ce5 am: 0e201db242 am: b3854525d1 am: 0f33fc35ea am: 81f909cdd7 am: 6b7b14ad4c am: b8ecdb9b57 am: 85dcd68ebc
 ▪ 85dcd68ebc [automerger] Reserve enough space for RTSP CSD am: c025be8ce5 am: 0e201db242 am: b3854525d1 am: 0f33fc35ea am: 81f909cdd7 am: 6b7b14ad4c am: b8ecdb9b57
 ▪ b8ecdb9b57 [automerger] Reserve enough space for RTSP CSD am: c025be8ce5 am: 0e201db242 am: b3854525d1 am: 0f33fc35ea am: 81f909cdd7 am: 6b7b14ad4c
 ▪ a3a06f02cf Merge tag 'android-9.0.0_r34' into pie
 ▪ 95a03429db av: Fix Derp
 ▪ 67f618d25b effects: Initialize volume at -96
 ▪ bdd6d24fb0 Snap for 5339334 from bd6dc464586edade39b3bcac6f6f0d3b2d5d1077 to pi-qpr3-release
 ▪ 6b7b14ad4c [automerger] Reserve enough space for RTSP CSD am: c025be8ce5 am: 0e201db242 am: b3854525d1 am: 0f33fc35ea am: 81f909cdd7
 ▪ 81f909cdd7 [automerger] Reserve enough space for RTSP CSD am: c025be8ce5 am: 0e201db242 am: b3854525d1 am: 0f33fc35ea
 ▪ 0f33fc35ea [automerger] Reserve enough space for RTSP CSD am: c025be8ce5 am: 0e201db242 am: b3854525d1
 ▪ b3854525d1 [automerger] Reserve enough space for RTSP CSD am: c025be8ce5 am: 0e201db242
 ▪ 0e201db242 [automerger] Reserve enough space for RTSP CSD am: c025be8ce5
 ▪ c025be8ce5 Reserve enough space for RTSP CSD
 ▪ 4d85447e56 Merge "AAudio: Change dumpsys denial to Denial" into pie-gsi
 ▪ 4bd7a750b0 Snap for 5335558 from bd6dc464586edade39b3bcac6f6f0d3b2d5d1077 to pi-qpr3-b-release
 ▪ bd6dc46458 Visualizer: fix native crash when visualizer release
 ▪ a44cd868f0 AAudio: Change dumpsys denial to Denial
 ▪ 9d6ddc8112 SoftXaac: Handle error cases when decoder fails to initialize
 ▪ d8d570e5cf Visualizer: fix native crash when visualizer release
 ▪ 031d2a3236 Merge "Snap for 5180536 from dba05b7c7c2782c88056a3f53615a66a6945426e to pi-platform-release am: 993d76204d" into pie-gsi
 ▪ e3f167953e Snap for 5180536 from dba05b7c7c2782c88056a3f53615a66a6945426e to pi-platform-release am: 993d76204d

 ▼ frameworks/base/
 ▪ c4d1cdb8bd6 WeatherClient: Check boot completed prop
 ▪ ca8b6dca106 OP gestures: fix APP switch triggering
 ▪ bc4ae6cb7c9 Merge "Snap for 5240760 from 988624eda2c566551f75b48231cdeff2b0142d93 to pi-platform-release am: 33e0de46b6" into pie-gsi
 ▪ f4886153cc4 Snap for 5240760 from 988624eda2c566551f75b48231cdeff2b0142d93 to pi-platform-release am: 33e0de46b6
 ▪ 9824ee03058 Show mobile icons with left-to-right in order of slot index
 ▪ 8e39919ff56 Revert "SystemUI: Sort subscriptions in reversed order"
 ▪ a3d60dd7a95 Revert "base: SystemUI: tuner: fix reorder of mobile slots"
 ▪ 4e7c92f1114 Keyguard: Remove carrier text for disabled SIMs
 ▪ 2e5f0162db8 Code improvements for "SystemUI: Refresh themes on dirty flash"
 ▪ 33e0de46b6b Snap for 5240760 from 988624eda2c566551f75b48231cdeff2b0142d93 to pi-platform-release
 ▪ 04d262db157 DO NOT MERGE Add carrier config to use 3GPP application on CDMA/CDMA-LTE phone.
 ▪ a487c5840f1 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ aa7b93b167c Merge "Revert "Update VPN capabilities when its underlying network set is null."" into pi-dev
 ▪ 35723fb2b1d Import translations. DO NOT MERGE
 ▪ 721ee3d68c5 Automagically set night mode when dark or black theme is turned on
 ▪ 0143a72a994 Revert "base: Add Gboard overlay [1/2]"
 ▪ 6a050c7c50f Revert "Update VPN capabilities when its underlying network set is null."
 ▪ beafb6fa702 Merge "WIFI cannot be automatically connected" into pie-gsi
 ▪ 17d763eb96d WIFI cannot be automatically connected
 ▪ df120e91ba6 Snap for 5353599 from 3148adad10cdac897820241e52d6f6c769c7cc3c to pi-qpr3-b-release
 ▪ cafce753548 Merge tag 'android-9.0.0_r34' into pie
 ▪ c4ce24fec89 base: Fix camera hal1 prop
 ▪ 3148adad10c [automerger skipped] Merge "DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot" into oc-dev am: 809231680f am: 21c4a58435 am: 499b803c52 -s ours am skip reason: subject contains skip directive
 ▪ 499b803c520 Merge "DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot" into oc-dev am: 809231680f am: 21c4a58435
 ▪ 74bc239b240 [automerger skipped] [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8 am: 1bb102e37d am: 1c348395f5 am: 26fda93676 skipped: cf76183e6c am: cf81345649 am: 94029593c4 am: c03d767ee8 -s ours am skip reason: subject contains skip directive
 ▪ c03d767ee85 [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8 am: 1bb102e37d am: 1c348395f5 am: 26fda93676 skipped: cf76183e6c am: cf81345649 am: 94029593c4
 ▪ 21c4a584354 Merge "DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot" into oc-dev am: 809231680f
 ▪ 94029593c44 [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8 am: 1bb102e37d am: 1c348395f5 am: 26fda93676 skipped: cf76183e6c am: cf81345649
 ▪ 809231680f4 Merge "DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot" into oc-dev
 ▪ 598118ffe13 Merge "DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot" into pi-dev
 ▪ 1981ac20dfc SystemUI: Remove unused resources
 ▪ d86b25fd0ae SystemUI: OneHandMode QS tile
 ▪ e382a6dac63 SystemUI: Update SoundTile
 ▪ 1a54bf6bc23 SystemUI: Update ScreenRecord tile
 ▪ 610d899a3d7 SystemUI: Update OnTheGo tile
 ▪ 9b36c4a9ecd base: migrate isServiceRunning check to HavocUtils
 ▪ b7e78c7f6dc UpdateEngine: Add perf mode binder interface
 ▪ 49930c4e622 SystemUI: Fix Powermenu layout
 ▪ 23d59883f57 Network Traffic: Add more customizations and improvement [2/2]
 ▪ f55a341cd96 base: Add Gboard overlay [1/2]
 ▪ 1c92e033971 SystemUI: Fix margin for small QS icons
 ▪ 9c3cf7428f9 base: Expose system icon area weight
 ▪ 601cae9a1f1 ColorDisplayService: change default night light brightness (2/2)
 ▪ e48751dfc82 Revert "SettingsProvider: Hide sensitive notification content"
 ▪ e6eaa3ac460 Do not apply date customization to QS clock
 ▪ 70f75f83b33 SystemUI: Always show date in QS header
 ▪ cb6399f11d2 Clock: Always show time in the quickstatusbar
 ▪ ab520a10b74 Network traffic: Retain our notch check
 ▪ f81c5b02f56 Notch friendly carrier label [1/2]
 ▪ 31b7ddc1c32 base: Link more things to a common dimen
 ▪ 1103cbd0ba2 SystemUI: Make recents grid view accept more than 8 tasks
 ▪ 85049f58bf7 Revert "Disable grid recents [1/2]"
 ▪ fa7abbf51fd base: Supress telephony crashing platform
 ▪ 01ac1bc1a81 am: Avoid scheduling service restart twice
 ▪ 675549bac3b base: screenrecord: update notif text for high aspect ratio devices
 ▪ e4cffa346a5 Method to detect a notch'd device
 ▪ 0f806af7f38 VisualizerView: Don't add null end actions to animators
 ▪ ebcd84dc5fc SystemUI: grant missing READ_PHONE_STATE permission
 ▪ b7c983d2d32 base: Fix Auto-hide clock overlapping on keyguard
 ▪ e5d10d6c1b3 Add option to auto hide status-bar clock [1/2]
 ▪ 19d7631f254 Power button flashlight: allow to skip proximity check per device
 ▪ e48dac2c66a Power button flashlight toggle: add proximity sensor check
 ▪ 5ae948fb041 Allow doubletap/longpress power to toggle torch [1/3]
 ▪ 456b598393c Revert "Power button flashlight"
 ▪ 0a7e24b81a1 Helper functions for SmartActions action binding [1/2]
 ▪ 97e79d9bc1d CustomActions: Use settings provider to store value [2/3]
 ▪ 4653509aff8 ActionUtils: Improve ringer modes
 ▪ 3f54a935f64 ActionUtils: Ringer modes
 ▪ 5d56bcf4d12 Snap for 5348424 from c4ce1a631fd86104cd51c9331006408335d00308 to pi-qpr3-b-release
 ▪ c4ce1a631fd Import translations. DO NOT MERGE
 ▪ b0de585dece DO NOT MERGE: Don't let previous activity wait if next activity won't be visible
 ▪ fbcb41f9fbc DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot
 ▪ a7cb82eb85c DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot
 ▪ cf81345649d [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8 am: 1bb102e37d am: 1c348395f5 am: 26fda93676 skipped: cf76183e6c
 ▪ cf76183e6c0 [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8 am: 1bb102e37d am: 1c348395f5 am: 26fda93676
 ▪ 26fda936760 [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8 am: 1bb102e37d am: 1c348395f5
 ▪ 1c348395f52 [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8 am: 1bb102e37d
 ▪ 1bb102e37dc [automerger] DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot am: b5e7bbe5b8
 ▪ b5e7bbe5b8e DO NOT MERGE - SUPL ES Extension - Safer Init and Not After Boot
 ▪ d9ac335ea88 VolumeDialog: avoid multiple animations on touch spam
 ▪ 47a6760c760 Remove ConnectivityManager and its usages from NetworkStatsService.
 ▪ a84433b7b7c Snap for 5339334 from cd8eace91d4b3b2c3de29304f226dbefa9214216 to pi-qpr3-release
 ▪ cd8eace91d4 Merge "DO NOT MERGE: Disable night UI mode in battery saver." into pi-dev
 ▪ 1ee83da73b2 Snap for 5335558 from 987ec033abd594b6a10717f0af4bb39b38e881b7 to pi-qpr3-b-release
 ▪ ce1770b7783 DO NOT MERGE: Disable night UI mode in battery saver.
 ▪ b4bee255d2a Revert "Adding SUPL NI Emergency Extension Time"
 ▪ 987ec033abd Merge "Revert "Fix a11y cache correctness bug"" into pi-dev
 ▪ d4d9e1a08c4 Merge "Visualizer: fix native crash when visualizer release" into pi-dev
 ▪ 52f7adec6c7 Visualizer: fix native crash when visualizer release
 ▪ 6d19f33ca61 Merge "DO NOT MERGE Fix flaky tests in OverheatAlarm feature" into pi-dev
 ▪ 4d70022b884 Revert "Fix a11y cache correctness bug"
 ▪ ec9d9834aa4 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 820aa0a32cb Import translations. DO NOT MERGE
 ▪ c45da18fbb9 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 6024de3b89d Merge "Skip empty slice permissions files during backup" into pi-dev
 ▪ 3293ab62293 Merge "Make notifications from the default dialer and SMS app unblockable." into pi-dev
 ▪ 46f2805eb75 SystemUI: Fix an issue where unlocking the SIM PIN failed
 ▪ fda7e758b9e Unbreak ambient display while Heads up is disabled
 ▪ c5d7fed4a0a SystemUI: Make dark theme switch more sane
 ▪ bec9d394d33 Merge "Clarify WebResourceResponse's stream handling." into pi-dev
 ▪ 98684aa82a7 Merge "Improve the performance when loading image wallpaper colors" into pi-dev
 ▪ 2ab75b2b2e8 Merge "Override old alarms in zen schedule" into pi-dev
 ▪ b4b64ad6025 Merge "Update VPN capabilities when its underlying network set is null." into pi-dev
 ▪ ad8805a6c21 Update VPN capabilities when its underlying network set is null.
 ▪ a0a2a7c670f Import translations. DO NOT MERGE
 ▪ 31dccf9f698 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 85288a5e3c8 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ e937b2703ed Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 93f661ab3b1 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 92d5986cc52 SystemUI: Refresh themes on dirty flash
 ▪ e2e65cbc78c ThermalController: Send out active package broadcast only if allowed
 ▪ 35c0429fd1a WeatherClient: Fix horrible allocation abuse
 ▪ 1f585d49acd ActionUtils: cleanup screen On action code
 ▪ 520ea63d80b ActionUtils: Add screen on action
 ▪ 89b9fd2e19b framework: Grant READ_WEATHER permission
 ▪ 54244012078 Import translations. DO NOT MERGE
 ▪ 8bf1a45ae4f Import translations. DO NOT MERGE
 ▪ 7ee7db55dc6 Import translations. DO NOT MERGE
 ▪ 5812c578522 Snap for 5322077 from 5a50cb42b7e22ded08047524464fa360647b2785 to pi-qpr3-release
 ▪ ae15ee43e44 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ beb0a940cab Import translations. DO NOT MERGE
 ▪ aebba25f554 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 60685350c61 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ e6b0455e71c Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ c691b7e52c6 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 6670b2287a5 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 85c48edc697 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 8dfcae263ac Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 6fe3e60d9ab Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ b3581e7602c Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 5a50cb42b7e Merge "[DO NOT MERGE] AML: Handle NoDisplayActivities correctly" into pi-dev
 ▪ 48181b43d20 Import translations. DO NOT MERGE
 ▪ 7b1a75ad75f Import translations. DO NOT MERGE
 ▪ 1e72862bb8c Import translations. DO NOT MERGE
 ▪ d79f2bcab01 Import translations. DO NOT MERGE
 ▪ 970bf5a6b3d Make notifications from the default dialer and SMS app unblockable.
 ▪ 6b25c191089 Import translations. DO NOT MERGE
 ▪ 7ee646771b9 Override old alarms in zen schedule
 ▪ 3213d050d49 Import translations. DO NOT MERGE
 ▪ e9d2674411b Import translations. DO NOT MERGE
 ▪ d12a24183c5 Import translations. DO NOT MERGE
 ▪ d5ac0463766 Import translations. DO NOT MERGE
 ▪ 06cfb175bd9 Merge "Update keyguard charging text to indicate wireless" into pi-dev
 ▪ 5abc71b27b5 Improve the performance when loading image wallpaper colors
 ▪ 986eb612d72 Keyguard: Multiuser switch [1/2]
 ▪ a5bce5a1db9 Full gestures navbar: add missing haptic feedback events
 ▪ e967e4baa59 Full gestures navbar: don't break IME navbar button
 ▪ 23a1818729f BrightnessDialog: dismiss on focus lost
 ▪ 1801a6da387 Avoid Ambient indicator overlap with multiple keyguard notifications
 ▪ 83e65469005 base: wake from aod on unplug if we show on charging only
 ▪ c94ba204164 SystemUI: Decrease padding for statusbar icons
 ▪ 9ae2241d708 base: Allow tuning extra padding for status bar
 ▪ 2579557c12b base: Remove round corner padding from statusbar
 ▪ 9295032b4d0 SystemUI: Network traffic improvements
 ▪ 7a76587eb73 Only inherit Elmyra for Pixel devices
 ▪ badc0cd9a92 Active edge settings 1/?
 ▪ 1daceaba699 Elmyra: Move to external repo
 ▪ 05ab8ab277d Elmyra: initial base for the service porting
 ▪ bac0e10c31c Merge "Fix for testLifecycleOnMoveToFromSplitScreenRelaunch" into pie-gsi
 ▪ 3e598a0948b Fix for testLifecycleOnMoveToFromSplitScreenRelaunch
 ▪ 1bbf6007467 Import translations. DO NOT MERGE
 ▪ 8098c5f1a82 Import translations. DO NOT MERGE
 ▪ a2e313930f0 QS Header: Fix gradient view after device is rotated
 ▪ f63da1e99e2 Update keyguard charging text to indicate wireless
 ▪ 3872fed0762 Fix action bar font family on material themes
 ▪ 5c3f50a87b6 OP like gestures: more tweaks [1/2]
 ▪ fd40f27a42a Animate visibility change for Keyguard Inidication Area
 ▪ cc08f31daf4 base: QS: Allow coloring bg with accent [1/2]
 ▪ 438073d5bb4 base: Custom theming [1/3]
 ▪ b6b1d90a157 base: Cleanup themes
 ▪ f31daadb418 base: Nuke Theme tile
 ▪ 89bbfa4e591 base: Force white bg on autofill dialog
 ▪ b3ac49d2de4 base: Cleanup colors
 ▪ 6bc8db0eefb Improve Volume dialog timeout
 ▪ a3c30fa4f01 NetworkTraffic: Make QS header net monitor play nice with the scrim
 ▪ c65e639b38b Keyguard: Avoid starting FP authentication right after cancelling
 ▪ 1b1681a8b0a Merge cherrypicks of [6391991, 6392011, 6391992, 6391993, 6392031, 6392051, 6392052, 6392091, 6392111, 6392032, 6391994, 6391995, 6391996, 6391997, 6391998, 6391999, 6392000, 6392001, 6392002, 6392003, 6392004, 6392005, 6392006, 6392112, 6392113, 6392151, 6392152] into pi-qpr2-release
 ▪ 21863a0cb74 Be more comprehensive about boot time RTC check
 ▪ d14c8a2a724 Merge "RESTRICT AUTOMERGE Close TextClassifier native resources." into pi-dev
 ▪ 8a5f23791cd Merge "Fixed temporary brightness getting stuck bug." into pi-dev
 ▪ cd7def71595 Merge "Added hysteresis check to screen brightness." into pi-dev
 ▪ b5f3f030a0c Snap for 5304822 from 7ed81d17bae3a68d6fe921853fb7dbde9c5e10ed to pi-qpr3-release
 ▪ 7ed81d17bae Merge "Do not load xml metadata for unchanged packages in RegisteredServicesCache" into pi-dev
 ▪ e6472fe5206 Merge "Snap for 5180536 from eb71e821edd929d48a824a9a4bbdfb710b50d324 to pi-platform-release am: 04898ff564" into pie-gsi
 ▪ 3affd5dcda9 Snap for 5180536 from eb71e821edd929d48a824a9a4bbdfb710b50d324 to pi-platform-release am: 04898ff564
 ▪ 8094880025d Do not load xml metadata for unchanged packages in RegisteredServicesCache

 ▼ frameworks/native/
 ▪ cc4b88e32 Snap for 5240760 from 3ce2b66f92ea8c50005b38595bb1aed4c80135ed to pi-platform-release
 ▪ c0c039c2b Snap for 5357986 from 29828f54c9942ff35dfda7d269d5e0401f91fc2f to p-keystone-qcom-release
 ▪ a6c47b640 Merge 3b58869059f2a3cb4efb4a8662470305ad7fd7ba on remote branch
 ▪ 29828f54c Merge "sf : Print all layers name in case of max limit reached" into p-keystone-qcom
 ▪ 83c4e49a0 Snap for 5354036 from 4be14476fde02f3f4dfbbd69c73e75129f5205a7 to p-keystone-qcom-release
 ▪ ede29fdf1 sf : Print all layers name in case of max limit reached
 ▪ 55285320f Snap for 5353175 from e2609136d533bbb7b1dd5ad45c039acf8718fcb0 to p-keystone-qcom-release
 ▪ 4be14476f Merge "Merge SPL-2019-02-05" into p-keystone-qcom
 ▪ 013629bfa Merge tag 'android-9.0.0_r34' of https://android.googlesource.com/platform/frameworks/native into pie
 ▪ 6d56a6e1b Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into pie
 ▪ e2609136d sf: Pass display cutout hint to hwc.
 ▪ 4d4d87235 Merge tag 'LA.UM.7.6.2.r1-07100-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into pie
 ▪ d7992b1b6 Already included in https://github.com/HavocGemini/android_vendor_havoc/commit/44dc2be3703f3519b8c8c2a409c4a35e30d9aadc
 ▪ ec7c870e8 Merge 81aa6740ea8c6ce91857ef4887bd4fb77aa3b582 on remote branch
 ▪ 3776e7c8a Merge 3b58869059f2a3cb4efb4a8662470305ad7fd7ba on remote branch
 ▪ 660627700 Merge SPL-2019-02-05
 ▪ f4a2532ca Revert "libbinder: Don't log call trace when waiting for vendor service on non-eng builds"
 ▪ 4860b469d Merge tag 'LA.UM.7.6.2.r1-06900-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into pie
 ▪ f11aeff20 Merge branch '9.0' of https://github.com/syberia-project/platform_frameworks_native into pie
 ▪ 932dd6f3e touch response optimizations
 ▪ 5dc13aee1 Revert "sf: Add support for multiple displays"
 ▪ 5216b85a5 Fix incorrect print starved time of binder pool
 ▪ 13a8874ec libbinder: auto-choose between binder/vndbinder
 ▪ 3500610aa Fix bugs regarding calculate dalvik-cache size
 ▪ b9b62ca33 binder: Remove thread shutdown logic
 ▪ 97eff5a11 Remove more "template" keywords from non templated calls
 ▪ 122bdb778 Cleanup previous replacing NULL with nullptr
 ▪ 8467a85da binder: Replace NULL/0 with nullptr
 ▪ 097ecdb6e Modernize codebase by replacing NULL with nullptr
 ▪ b18a0aeea Modernize codebase by replacing NULL with nullptr
 ▪ 2ca697e95 binder: Release tracking lock before invoking binder_proxy_limit_callback

 ▼ frameworks/opt/net/wifi/
 ▪ 7b7c211ad Snap for 5354036 from f94d2725e76052612dc38b525709131a75bcde6a to p-keystone-qcom-release
 ▪ f94d2725e Merge "Merge SPL-2019-02-05" into p-keystone-qcom
 ▪ fbc688903 Snap for 5348424 from fe21aeee563b916a738c2a21e824e9ecf4b03416 to pi-qpr3-b-release
 ▪ 107415a03 Snap for 5345368 from 2ac0d5bc731ea6a122d34e8f64be8aa83117b7f7 to p-keystone-qcom-release
 ▪ bf97fc378 P2P: Avoid P2P initialization after continuous setup failures.
 ▪ 31553dd46 Snap for 5339334 from fe21aeee563b916a738c2a21e824e9ecf4b03416 to pi-qpr3-release
 ▪ fe21aeee5 DO NOT MERGE Add data integrity checking for wifi passwords
 ▪ 4d0cdba58 Merge 38412732be0033180662a3e4232f598a7618adef on remote branch
 ▪ 2ac0d5bc7 Revert "wifi: Register to ACTION_SHUTDOWN to shutdown Wi-Fi"
 ▪ a3e354fe4 Snap for 5322077 from 0b7dfd2253af0f4713af3a7f6ca5f233f0fbf8b9 to pi-qpr3-release
 ▪ e5f557c87 Merge SPL-2019-02-05
 ▪ 0b7dfd225 Support SAR for OTT VOWifi Apps

 ▼ frameworks/opt/telephony/
 ▪ 1b75d80fff DO NOT MERGE Return MSISDN as Line1 number if carrier config requires it.
 ▪ 1439b2240e Snap for 5354036 from 670259b39661cec9f8b3240d886c9a2066044c95 to p-keystone-qcom-release
 ▪ 2261e4a575 Snap for 5353175 from 711d5481cd9d0359709b1eda034a0605565d7a69 to p-keystone-qcom-release
 ▪ 670259b396 Merge "Merge SPL-2019-02-05" into p-keystone-qcom
 ▪ 79f4bde712 Merge tag 'LA.UM.7.6.2.r1-07100-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into caf
 ▪ 711d5481cd Set service class with SERVICE_CLASS_NONE over CS
 ▪ dcc6fd78cc Remove getAllVpnInfo from ConnectivityServiceMock.
 ▪ c628a55edd Fix ANR after setup data call with failure
 ▪ 959ae7ee22 Merge SPL-2019-02-05
 ▪ 21b963e469 Snap for 5304822 from 1be3fdb76daba1226748881f2a5ced94934b29b1 to pi-qpr3-release
 ▪ 536dc0b60e Merge cherrypicks of [6333255, 6333230, 6333232, 6333337, 6333338, 6333339, 6333853, 6333199, 6333874, 6333875, 6333876, 6333877, 6333274, 6333275, 6333276, 6333277, 6333814, 6333256, 6333815, 6333278, 6333236, 6333854, 6333816] into pi-b4s4-release
 ▪ e3d99b8446 Expand onCallHandover logging and add data enabled check.

 ▼ hardware/google/av/
 ▪ ae27f43 C2SoftXaacDec: Handle error cases when decoder fails to initialize

 ▼ hardware/havoc/interfaces/
 ▪ cfe0369 livedisplay: Remove deprecated 1.0 HAL

 ▼ hardware/interfaces/
 ▪ 68c09adf4 health vts: implement GTEST_SKIP if not defined.
 ▪ 0d48dc81d health: skip VTS on healthd if vendor HAL is present.
 ▪ bf1767d55 Snap for 5354036 from 20b2ade3c1ffcc330c1bd173c55fdedcb4684805 to p-keystone-qcom-release
 ▪ 20b2ade3c Merge "Merge SPL-2019-02-05" into p-keystone-qcom
 ▪ b18f050a4 Snap for 5339334 from d0a5c1dda521c07e2cca4cf426490e8da399f481 to pi-qpr3-release
 ▪ c6c2a0d2f Snap for 5335558 from d0a5c1dda521c07e2cca4cf426490e8da399f481 to pi-qpr3-b-release
 ▪ b8524954e VTS tests to work with depth Y16
 ▪ d0a5c1dda [DO NOT MERGE] keymaster: add an EC attestation test
 ▪ fac3cc17c Snap for 5324269 from 37fe3b6cb6d9b565cac0d7680b8cdd3716e5ac06 to p-keystone-qcom-release
 ▪ 37fe3b6cb Merge "Interfaces: Query HDR and WCG support from display services" into p-keystone-qcom
 ▪ 0514dddf1 Snap for 5319882 from 972fcf6cc94da9fcfee9f7d5384a044fbf3b930a to p-keystone-qcom-release
 ▪ 2a1af89bd Merge SPL-2019-02-05
 ▪ 71d37fcb8 Merge tag 'LA.UM.7.6.2.r1-06900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0
 ▪ 88a0aca80 Interfaces: Query HDR and WCG support from display services

 ▼ hardware/libhardware_legacy/
 ▪ 48050e4 Merge a017c3f217e545de3581ffb490768793c99f7ecc on remote branch
 ▪ 3984c0f Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/libhardware_legacy into 9.0
 ▪ bf97d12 Merge tag 'LA.UM.7.6.2.r1-07100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/libhardware_legacy into 9.0
 ▪ e0a388b Merge a017c3f217e545de3581ffb490768793c99f7ecc on remote branch
 ▪ f4b3f82 Merge a017c3f217e545de3581ffb490768793c99f7ecc on remote branch

 ▼ hardware/lineage/livedisplay/
 ▪ d84525d Revert "livedisplay: sdm: Fix restoring default mode"
 ▪ 8d13803 livedisplay: sysfs: Wire it up

 ▼ hardware/nxp/nfc/
 ▪ b4cc814 Snap for 5240760 from d6afaec61a6a4114d0f89f72d2b7404376061595 to pi-platform-release am: 1417ebacbd
 ▪ 1417eba Snap for 5240760 from d6afaec61a6a4114d0f89f72d2b7404376061595 to pi-platform-release
 ▪ 1a42707 Merge tag 'android-9.0.0_r34' into pie
 ▪ 02fea83 Snap for 5180536 from 1a7ca2f8c750c84c17bf3fd6e97810b7cee176ba to pi-platform-release am: 3140e98d08

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 089ccc2e Merge "hal: Deinit EC reference loopback"
 ▪ 552d4717 Merge e33b7d6be5e97e6efa2267d9da610cf4d61b0435 on remote branch
 ▪ 2d895590 Merge 7ea1a8e2747b85e105df3836b7f0dfb6513417e5 on remote branch
 ▪ 8827cf62 hal: set default sample rate during voice/voip call
 ▪ 6462fc30 hal: retry all of un-detected sound card
 ▪ ad630027 Merge "hal: Resolves rewound and restart issue during SSR/PDR."
 ▪ d1d43759 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' into 9.0
 ▪ 3a10cc4f hal: Deinit EC reference loopback
 ▪ e33b7d6b hal: spk_prot: add custom support to trigger v-validation
 ▪ 224842f1 hal: spk_prot: add custom support to trigger initial cal
 ▪ 7d3c9fe3 hal: Resolves rewound and restart issue during SSR/PDR.
 ▪ 7ea1a8e2 Merge "hal: Fix NULL pointer dereference in get acdb snd card name"
 ▪ b7746e00 Merge dc5f1e0ce9af5b96ad18bb701b43ff089146504a on remote branch
 ▪ 1c116421 Merge "Fix build error for a new SP"
 ▪ d3af1403 Merge dc5f1e0ce9af5b96ad18bb701b43ff089146504a on remote branch
 ▪ 4ca086ba Fix build error for a new SP
 ▪ ae3b0b73 hal: Fix NULL pointer dereference in get acdb snd card name
 ▪ 3421784e Merge "hal: set different echo reference based on output device"
 ▪ c0c23c21 Merge "mm-audio: Remove malloc allocation for ptr pointer"
 ▪ f88e6593 Merge "hal: Add SSR/PDR handling in voice call"
 ▪ 15fa682c mm-audio: Remove malloc allocation for ptr pointer
 ▪ 01bda41c Merge "hal: Set correct mono mode for TWS+."
 ▪ 1498ba1c Merge "hal: Add support for APTX and AAC  decoding in DSP."
 ▪ 9aa0b924 hal: Add SSR/PDR handling in voice call
 ▪ dc5f1e0c hal: Do not delete DEVICE_CONNECT and DISCONNECT params
 ▪ 5be66f3a hal: set different echo reference based on output device
 ▪ 016e273c Merge "configs: mixer path changes for ADSP SVA"
 ▪ ef40adb8 hal: add support to check sva and audio echo reference
 ▪ 1b3084a5 Merge "hal: use version 3 as default for speaker protection"
 ▪ 9bb0662c configs: mixer path changes for ADSP SVA
 ▪ 045692a0 hal: Add support for APTX and AAC  decoding in DSP.
 ▪ 28fce0ea hal: Set correct mono mode for TWS+.
 ▪ 3629d269 configs: trinket: Update Tx DEC volume to 102
 ▪ a866d9a2 Fix build errors.
 ▪ 755d1925 Merge "audio: hal: adding talosAU hw information"
 ▪ 4a70b988 Merge "configs: trinket: Change ACDB ID of speaker to mono"
 ▪ 5122e9e7 hal: use version 3 as default for speaker protection
 ▪ b4fb2c4b Merge "audiohal: Modifications in hal_play_test for trumpet certification"

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ 04c6914a Merge 8fd9eb0ae3270f4e782e2c3c3b2534888a12a898 on remote branch
 ▪ 62396d67 Merge 7db5e98edef455dd5de8ada8e74ee773a173c236 on remote branch
 ▪ 1e122135 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0
 ▪ 10cb7485 hwc2: Validate bounds check for input parcel.
 ▪ 7b037a60 Merge 7db5e98edef455dd5de8ada8e74ee773a173c236 on remote branch
 ▪ 1e9bd4ca Merge 7db5e98edef455dd5de8ada8e74ee773a173c236 on remote branch
 ▪ 8fd9eb0a display: Replace libqdmetadata.system with libqdmetadata
 ▪ 4494d4d1 Revert "display: Define soong namespace"
 ▪ caf6fa48 Merge tag 'LA.UM.7.6.2.r1-06900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0

 ▼ hardware/qcom/fm/
 ▪ 1b4078d Merge tag 'LA.UM.7.3.r1-06900-sdm845.0' into HEAD

 ▼ hardware/qcom/gps/
 ▪ da85b0af Merge "Snap for 5180536 from dd6c5546adc4715854182358c2dd68691434efe9 to pi-platform-release am: 722730b090" into pie-gsi
 ▪ 806e9341 Snap for 5180536 from dd6c5546adc4715854182358c2dd68691434efe9 to pi-platform-release am: 722730b090

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 90ee914b mm-video-v4l2: Moved post_event() call out of m_lock
 ▪ 5e77a6cb Merge a7912e137f058d10bd4c094bddf839510a6b9350 on remote branch
 ▪ a7912e13 vdec: Allow setting default fps to driver.
 ▪ 3345d4ea mm-video-v4l2: Fix CTS failure
 ▪ 61fa918d  mm-video-v4l2: Fix Build Error

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 0c7471191 Merge 3345d4ea0b564250e0fb07660f5c716a0557c56c on remote branch
 ▪ 90ee914b7 mm-video-v4l2: Moved post_event() call out of m_lock
 ▪ e70034823 Merge a7912e137f058d10bd4c094bddf839510a6b9350 on remote branch
 ▪ 125f38c75 Fix invalid logical constant creation.
 ▪ 7afc850e6 Merge 0392d8a4a7a9ea111f8ac6fb761ca8c4f6cbcc5a on remote branch
 ▪ a7912e137 vdec: Allow setting default fps to driver.
 ▪ 9a441ee9c media: Don't link libgpustats
 ▪ 3345d4ea0 mm-video-v4l2: Fix CTS failure

 ▼ hardware/qcom/power/
 ▪ 3e3113d Merge pull request #1 from rashedsahaji/9.0

 ▼ hardware/qcom/sdm845/data/ipacfg-mgr/
 ▪ 7db5efa os_pickup: Guard to avoid conflicts with CAF repos

 ▼ hardware/qcom/wlan-caf/
 ▪ c160cc0 Merge e23466fe0e6f5a12e51bcf788001995c32f40f75 on remote branch
 ▪ 4cbafc3 Merge "wifihal: Fix SIGPIPE when stopHal calls writing into exit sockets" into wlan-aosp.lnx.4.0
 ▪ b3646c1 Merge 9de2dd243660764c870cfe086f575da641d091c9 on remote branch
 ▪ ff394cb WiFi-Hal: Add support to set wifi latency level
 ▪ 49cc033 wifihal: Fix SIGPIPE when stopHal calls writing into exit sockets
 ▪ 18da2ef Merge tag 'LA.UM.7.6.2.r1-06900-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/wlan into 9.0
 ▪ e23466f WiFi-Hal: Sync qca-vendor_copy.h to upstream qca-vendor.h

 ▼ hardware/ril/
 ▪ f342b3f5 Snap for 5354036 from 45efc6becb8fc648ccae48904332148f2407dccd to p-keystone-qcom-release
 ▪ 45efc6be Merge SPL-2019-02-05

 ▼ hardware/ril-caf/
 ▪ b475875 Encode the Number of MNC Digits in CellIdentity

 ▼ kernel/xiaomi/msm8996/
 ▪ 8338cb547361 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' into kernel.lnx.3.18.r34-rel
 ▪ 2fc4002f2d79 ASoC: msm: qdsp6v2: add range check for audio port index
 ▪ 1c853955563c qcacld-2.0: Abort scan if connecting in progress
 ▪ 9ccab8d86c27 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into HEAD
 ▪ 1babb78aee17 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' into drivers/staging/qcacld-2.0
 ▪ 90d9eadcecb8 Merge 9e58e91cb1ec9a6a4683253c426c40632ad1860b on remote branch
 ▪ ca708bf8c823 dsp: asm: Add check for num_channels before calling q6asm_map_channels
 ▪ fb8e383ea233 Merge "qcacld-2.0: Add support to configure tx use 2 chain" into wlan-cld2.driver.lnx.1.0
 ▪ 70663f8f0d77 Merge "qcacld-2.0: Add register key per_chain_stats" into wlan-cld2.driver.lnx.1.0
 ▪ 5f4bed838482 qcacld-2.0: Add support to configure tx use 2 chain
 ▪ a7c677c20688 Merge "qcacld-2.0: Avoid buffer overflow when process SA query action frame" into wlan-cld2.driver.lnx.1.0
 ▪ bd49dbc6e699 Merge "qcacld-2.0: Add support to get customized wow reason"
 ▪ 0c05b31fb53d Merge "qcacld-2.0: Add regdb"
 ▪ f2ec807f3b14 Merge "qcacld-2.0: Add support for OWE" into wlan-cld2.driver.lnx.1.0
 ▪ af844c928dbc qcacld-2.0: Avoid buffer overflow when process SA query action frame
 ▪ c8fb95609efb Merge "qcacld-2.0: Support reading GC TSF file after GC interface freed"
 ▪ 0245213ef9b7 Merge "qdsp6v2: apr: check for packet size to header size comparison"
 ▪ 2484c66b5daa Merge changes  into msm-3.18.c13
 ▪ 6a7e842b4c3e Merge "qcacld-2.0: Always send assoc req/rsp" into wlan-cld2.driver.lnx.1.0
 ▪ 06a5c262e90f qcacld-2.0: Add regdb
 ▪ 130d898bea13 Merge "qcacld-2.0: Fix possible OOB read in ProcDnldRsp" into wlan-cld2.driver.lnx.1.0
 ▪ c8982fd0122d Merge "msm: vidc: Handle perf mode configuration"
 ▪ c621a8049d40 Merge "ARM: dts: msm: Define power configuration for msm8996 and msm8998"
 ▪ 112b05aa02ea qcacld-2.0: Add register key per_chain_stats
 ▪ fab299301b20 qdsp6v2: apr: check for packet size to header size comparison
 ▪ 611c7b834b65 msm: vidc: Initialize DCVS load properly
 ▪ fcd67a361cec qcacld-2.0: Support reading GC TSF file after GC interface freed
 ▪ d7c1fc4d02f5 qcacld-2.0: Add support to get customized wow reason
 ▪ fe3219a50a37 cleanup gemini_defconfig
 ▪ c67f4c2069b2 Merge branch 'kernel.lnx.3.18.r34-rel' of https://github.com/android-linux-stable/msm-3.18 into 9.0
 ▪ 63ea3bbf4d58 Merge "qcacld-2.0: Reset Hpcs when all params of setHpcsParams are 0" into wlan-cld2.driver.lnx.1.0
 ▪ b0808480de74 Merge "qcacld-2.0: Add smart antenna APIs" into wlan-cld2.driver.lnx.1.0
 ▪ 689a3d282b2f msm: vidc: Handle perf mode configuration
 ▪ 7c6094154de5 ARM: dts: msm: Define power configuration for msm8996 and msm8998
 ▪ bc9afd11e6af qcacld-2.0: Reset Hpcs when all params of setHpcsParams are 0
 ▪ f068c00ffb19 qcacld-2.0: Add smart antenna APIs
 ▪ c50ce3350d72 qcacld-2.0: Fix loading failure on 32bit platform
 ▪ 1cfd87c31c01 Merge changes Ie113f84d,I53a03a3e,Id8f48a18,I474cfe9e,I65f0cb01,I0b28b755,I6807f49a,Ia87088dc into wlan-cld2.driver.lnx.1.0
 ▪ 8cc7f0d25f55 Merge "qcacld-2.0: Add SAE related ini and cap exchange changes"
 ▪ b36e6d1dd5b2 Merge "qcacld-2.0: Add support for SAE AKM suites"
 ▪ 3da96c074d73 Linux kernel 3.18.136
 ▪ b1490158def4 Merge "qcacld-2.0: Fix possible OOB in limProcessAssocReqFrame" into wlan-cld2.driver.lnx.1.0
 ▪ ad2299d6ffea Merge "qcacld-2.0: Compare the length of command in hdd_driver_command"
 ▪ d68d7c96ad30 qcacld-2.0: Add OWE IEs
 ▪ de53a4bc574d qcacld-2.0: Remove the ssidlen check in get_sta_stats
 ▪ 1189c189ea1d qcacld-2.0: Fix possible OOB in limProcessAssocReqFrame
 ▪ 5c0f5b708cc1 qcacld-2.0: Enable SAE by default
 ▪ a55ad29e3284 qcacld-2.0: Disable roaming for OWE
 ▪ 3f6aa4ba0350 qcacld-2.0: Add support for OWE
 ▪ 13a31272763b qcacld-2.0: Always send assoc req/rsp
 ▪ d4c19205d8ba qcacld-2.0: Trigger/handle SAE using cfg80211
 ▪ 985bd570ab37 qcacld-2.0: Disable roaming for SAE
 ▪ 8f4bc322c473 qcacld-2.0: Changes to support PMK caching for SAE
 ▪ a3d962e10b92 qcacld-2.0: Add changes to handle SAE status
 ▪ 9b93efa4bdb7 qcacld-2.0: Add SAE auth timer
 ▪ 533237b5a8d3 qcacld-2.0: Add changes to send SAE auth frame to user space
 ▪ 638d88ef34ec qcacld-2.0: Add changes for auth in send mgmt path
 ▪ 9ae712e9d13d qcacld-2.0: Add changes to trigger SAE in supplicant
 ▪ 8fe5ad91d56a Merge "qcacld-2.0: oob_irq_handler should be called if oob gpio is low" into wlan-cld2.driver.lnx.1.0
 ▪ 9e58e91cb1ec Merge "qcacld-2.0: Correct cb mode in vht40/80 channel switch" into wlan-cld2.driver.lnx.1.0
 ▪ 7442b7cf8525 qcacld-2.0: Add SAE related ini and cap exchange changes
 ▪ 779f8b7d7ea4 qcacld-2.0: Add support for SAE AKM suites
 ▪ 582eef5fd139 qcacld-2.0: Add check for bss_list size in wma_group_num_bss_to_scan_id
 ▪ d7947e86c69f qcacld-2.0: Compare the length of command in hdd_driver_command
 ▪ 6683e9268bfe msm: ipa3: Fix to validate the buffer size
 ▪ a1514e75f2fc qcacld-2.0: Add support for customized firmware path
 ▪ 91fc7710f0af qcacld-2.0: Correct cb mode in vht40/80 channel switch
 ▪ 27e17fa1aafc qcacld-2.0: Add macro to Enable/Disable Perf features
 ▪ 68ab5f46024e Merge 3.18.136 into kernel.lnx.3.18.r34-rel
 ▪ e128f16fddb6 Linux 3.18.136
 ▪ d39dbbe135d3 ax25: fix possible use-after-free
 ▪ f955600ff20d mISDN: fix a race in dev_expire_timer()
 ▪ 72bd16e67ac7 net/x25: do not hold the cpu too long in x25_new_lci()
 ▪ 673f9cf4a99f kvm: fix kvm_ioctl_create_device() reference counting (CVE-2019-6974)
 ▪ c1fee7732a5f hwmon: (lm80) Fix missing unlock on error in set_fan_div()
 ▪ ae5e148272fd net: ipv4: use a dedicated counter for icmp_v4 redirect packets
 ▪ 9954fa277dfb net: stmmac: Fix a race in EEE enable callback
 ▪ f9dc437b8fc6 vsock: cope with memory allocation failure at socket creation time
 ▪ 37dfe56ea55a vxlan: test dev->flags & IFF_UP before calling netif_rx()
 ▪ 191d1615f206 tcp: clear icsk_backoff in tcp_write_queue_purge()
 ▪ 2440ee336c4f tcp: tcp_v4_err() should be more careful
 ▪ 6ac641052b29 sky2: Increase D3 delay again
 ▪ 9b7b36398cea net: fix IPv6 prefix route residue
 ▪ 960b3b6c58cb Merge "fbdev: mdss: Signal pending retire fence"
 ▪ 7035c6434729 Merge d190cf2e9d9d4a92866b0e4975d5240bb26c38c2 on remote branch
 ▪ 6afdb9981e07 fbdev: mdss: Signal pending retire fence
 ▪ 01982670fa0e mdss: mdp3: Optimize power save in lp mode
 ▪ 75b76f3632d2 Merge 63e9c809386e0bd72512684ea0c2af53e0785a79 on remote branch
 ▪ fb091e6a9c8f qcacld-2.0: Update max TX power after reg set by user
 ▪ abf92c9cd475 Merge branch 'upstream-linux-3.18.y' of https://android.googlesource.com/kernel/common into dts
 ▪ ba456d7f188c ASoC: msm: Initialize global Mutex in audio_cal_utils
 ▪ 4f4d783607f3 Merge 3.18.135 into kernel.lnx.3.18.r34-rel
 ▪ b8fa9d76c58c Linux 3.18.135
 ▪ ca82c95c00ae pinctrl: msm: fix gpio-hog related boot issues
 ▪ 7e5c77104be2 usb: dwc2: Remove unnecessary kfree
 ▪ 4a96103a8420 kaweth: use skb_cow_head() to deal with cloned skbs
 ▪ d14da01ad342 smsc95xx: Use skb_cow_head to deal with cloned skbs
 ▪ 390bb181dcd2 x86/a.out: Clear the dump structure initially
 ▪ f7e684c1a5bc signal: Restore the stop PTRACE_EVENT_EXIT
 ▪ 6f0d202b2d56 tracing/uprobes: Fix output for multiple string arguments
 ▪ 5205a12327f7 alpha: Fix Eiger NR_IRQS to 128
 ▪ 8a1e1e4cf588 alpha: fix page fault handling for r16-r18 targets
 ▪ 2d8cfdac3872 Input: elantech - enable 3rd button support on Fujitsu CELSIUS H780
 ▪ 382fc3571870 Input: bma150 - register input device after setting private data
 ▪ 51700aa4bfed ALSA: usb-audio: Fix implicit fb endpoint setup by quirk
 ▪ e7cda3ff4d64 perf/core: Fix impossible ring-buffer sizes warning
 ▪ 32f501297e0c cifs: Limit memory used by lock request calls to a page
 ▪ 95dd551264fd gpio: pl061: handle failed allocations
 ▪ b99b873675cb ARM: dts: kirkwood: Fix polarity of GPIO fan lines
 ▪ e5cd1083a5cd ARM: dts: da850-evm: Correct the sound card name
 ▪ 36c3e2f0890b Revert "exec: load_script: don't blindly truncate shebang string"
 ▪ 0ed044e3db5d usb: host: ehci-msm: fix handling platform_get_irq result
 ▪ d86449d2b4d1 batman-adv: Force mac header to start of data on xmit
 ▪ 863938b84c4b batman-adv: Avoid WARN on net_device without parent in netns
 ▪ 98af4f7e3377 xfrm: refine validation of template and selector families
 ▪ e85998a9e10f libceph: avoid KEEPALIVE_PENDING races in ceph_con_keepalive()
 ▪ be120f656b4f HID: debug: fix the ring buffer implementation
 ▪ 568a25a1f548 drm/vmwgfx: Return error code from vmw_execbuf_copy_fence_user
 ▪ 5b102a170e21 drm/vmwgfx: Fix setting of dma masks
 ▪ 3351b1504d40 drm/modes: Prevent division by zero htotal
 ▪ ece07807c132 ARM: iop32x/n2100: fix PCI IRQ mapping
 ▪ c4fe6f07e5d2 MIPS: OCTEON: don't set octeon_dma_bar_type if PCI is disabled
 ▪ 64870211efd5 debugfs: fix debugfs_rename parameter checking
 ▪ cc44bfd608e2 misc: vexpress: Off by one in vexpress_syscfg_exec()
 ▪ db2e3ba117bd signal: Better detection of synchronous signals
 ▪ c63a38a937c5 signal: Always notice exiting tasks
 ▪ a5f2927775e7 mtd: rawnand: gpmi: fix MX28 bus master lockup problem
 ▪ bd0506104bcc perf tests evsel-tp-sched: Fix bitwise operator
 ▪ 3a4608dd185c perf/core: Don't WARN() for impossible ring-buffer sizes
 ▪ bc6d3bf92616 perf/x86/intel/uncore: Add Node ID mask
 ▪ 8767556995ad KVM: nVMX: unconditionally cancel preemption timer in free_nested (CVE-2019-7221)
 ▪ d283b5404655 KVM: x86: work around leak of uninitialized stack contents (CVE-2019-7222)
 ▪ fb046e01d81e usb: gadget: udc: net2272: Fix bitwise and boolean operations
 ▪ d6055cc520ab usb: phy: am335x: fix race condition in _probe
 ▪ 76b24a3f462d dmaengine: imx-dma: fix wrong callback invoke
 ▪ 95ae6d14def2 fuse: handle zero sized retrieve correctly
 ▪ 5791673ddc33 fuse: decrement NR_WRITEBACK_TEMP on the right page
 ▪ b9feaad40644 fuse: call pipe_buf_release() under pipe lock
 ▪ f93d1086fd34 ALSA: compress: Fix stop handling on compressed capture streams
 ▪ 9b22306f2221 enic: fix checksum validation for IPv6
 ▪ e4153e237ffa net: dsa: slave: Don't propagate flag changes on down slave interfaces
 ▪ 1e0b03637316 net: systemport: Fix WoL with password after deep sleep
 ▪ a4e92261fcc6 skge: potential memory corruption in skge_get_regs()
 ▪ 2f57176ac23a dccp: fool proof ccid_hc_[rt]x_parse_options()
 ▪ 523c0bea45f0 thermal: hwmon: inline helpers when CONFIG_THERMAL_HWMON is not set
 ▪ 818b4b090104 exec: load_script: don't blindly truncate shebang string
 ▪ 684a31662760 fs/epoll: drop ovflist branch prediction
 ▪ 521ca866e391 kernel/hung_task.c: break RCU locks based on jiffies
 ▪ 47a63b2b2e37 block/swim3: Fix -EBUSY error when re-opening device after unmount
 ▪ aff0981b2ab5 gdrom: fix a memory leak bug
 ▪ e5d77ee7a33f isdn: hisax: hfc_pci: Fix a possible concurrency use-after-free bug in HFCPCI_l1hw()
 ▪ 51e3522fcd10 ocfs2: don't clear bh uptodate for block read
 ▪ c9b6ec4adc49 scripts/decode_stacktrace: only strip base path when a prefix of the path
 ▪ 3896d308f19c niu: fix missing checks of niu_pci_eeprom_read
 ▪ e4a2ebdb56d9 um: Avoid marking pages with "changed protection"
 ▪ c20306485299 cifs: check ntwrk_buf_start for NULL before dereferencing it
 ▪ d360258d2b00 crypto: ux500 - Use proper enum in hash_set_dma_transfer
 ▪ f6e6bef189de crypto: ux500 - Use proper enum in cryp_set_dma_transfer
 ▪ b2ef4e8f5207 hwmon: (lm80) fix a missing check of bus read in lm80 probe
 ▪ 8aaf06edb200 hwmon: (lm80) fix a missing check of the status of SMBus read
 ▪ 077b6cadfe61 NFS: nfs_compare_mount_options always compare auth flavors.
 ▪ 40bb3dad12e2 fbdev: fbcon: Fix unregister crash when more than one framebuffer
 ▪ 9c98ab970365 igb: Fix an issue that PME is not enabled during runtime suspend
 ▪ 19b0a7021641 fbdev: fbmem: behave better with small rotated displays and many CPUs
 ▪ 0a6b1213f823 video: clps711x-fb: release disp device node in probe()
 ▪ f98b0b6695b6 drbd: Avoid Clang warning about pointless switch statment
 ▪ 787ef136f287 drbd: skip spurious timeout (ping-timeo) when failing promote
 ▪ a3d91d7d9ff4 drbd: disconnect, if the wrong UUIDs are attached on a connected peer
 ▪ a53e09acae97 drbd: narrow rcu_read_lock in drbd_sync_handshake
 ▪ 13174e174f2d xfrm6_tunnel: Fix spi check in __xfrm6_tunnel_alloc_spi
 ▪ 4a653aac3ed8 powerpc/uaccess: fix warning/error with access_ok()
 ▪ 39e6fd28a1bf arm64: KVM: Skip MMIO insn after emulation
 ▪ a6e15ccc870a memstick: Prevent memstick host from getting runtime suspended during card detection
 ▪ 230337445337 ASoC: fsl: Fix SND_SOC_EUKREA_TLV320 build error on i.MX8M
 ▪ 7b17070e7bf1 ARM: pxa: avoid section mismatch warning
 ▪ 673123dacfee udf: Fix BUG on corrupted inode
 ▪ 2fb9814cfd43 cpuidle: big.LITTLE: fix refcount leak
 ▪ 2f7d3d882e85 clk: imx6sl: ensure MMDC CH0 handshake is bypassed
 ▪ 8fd78e817478 sata_rcar: fix deferred probing
 ▪ 919b36dba259 mips: bpf: fix encoding bug for mm_srlv32_op
 ▪ 1293c56f7eb3 ARM: dts: Fix OMAP4430 SDP Ethernet startup
 ▪ 1f28d7f2b348 timekeeping: Use proper seqcount initializer
 ▪ e40c219934a5 usb: hub: delay hub autosuspend if USB3 port is still link training
 ▪ e51ff4fd1f0c smack: fix access permissions for keyring
 ▪ 901adf68e568 media: DaVinci-VPBE: fix error handling in vpbe_initialize()
 ▪ a19ea93f42e6 arm64: ftrace: don't adjust the LR value
 ▪ 9fb787cb5f2d nfsd4: fix crash on writing v4_end_grace before nfsd startup
 ▪ 88331aa2d322 f2fs: move dir data flush to write checkpoint process
 ▪ d31660b9452e soc/tegra: Don't leak device tree node reference
 ▪ a49c4cee2981 perf tools: Add Hygon Dhyana support
 ▪ c17921884cfb modpost: validate symbol names also in find_elf_symbol
 ▪ ad62a83632b9 ARM: OMAP2+: hwmod: Fix some section annotations
 ▪ 1718fda55ba0 staging: iio: ad7780: update voltage on read
 ▪ bc6b5abc2a18 staging:iio:ad2s90: Make probe handle spi_setup failure
 ▪ 62d61e6320c3 serial: fsl_lpuart: clear parity enable bit when disable parity
 ▪ c4d9c7a7b786 powerpc/pseries: add of_node_put() in dlpar_detach_node()
 ▪ ed169a8fc31d x86/PCI: Fix Broadcom CNB20LE unintended sign extension (redux)
 ▪ c2808e35c913 dlm: Don't swamp the CPU with callbacks queued during recovery
 ▪ a160cf4ee87a ARM: 8808/1: kexec:offline panic_smp_self_stop CPU
 ▪ a3d19b2bb430 staging: iio: adc: ad7280a: handle error from __ad7280_read32()
 ▪ fb564db819a6 qcacld-2.0: Add dummy function for supplicant deprecated commands
 ▪ 63e9c809386e iommu: iommu-debug: don't pass null character to copy_to_user
 ▪ 2190f6c44a19 gemini_defconfig: try to enable fm radio
 ▪ 2c9f63a591a9 Merge "arm64: Move BP hardening to check_and_switch_context"
 ▪ 5c9ab5c29ee4 Merge "soc: qcom: Validate read and write index before calculating ptr"
 ▪ c9609c326bef Merge "ARM: dts: msm: Disable APC CPR at cold for 9x07"
 ▪ b15046d951b4 qcacld-2.0: oob_irq_handler should be called if oob gpio is low
 ▪ b37a6ca5d3b8 arm64: Move BP hardening to check_and_switch_context
 ▪ 59ff1eb16f53 qcacld-2.0: Validate all channels for avoid_freq channel list
 ▪ dd89f83a0b40 soc: qcom: Validate read and write index before calculating ptr
 ▪ d923e0bb32df Remove moar polly optimization flags
 ▪ 830c149f5509 ARM: dts: msm: Disable APC CPR at cold for 9x07
 ▪ 7fbd5a06b86b msm: ipa: Fix to validate the buffer size

 ▼ packages/apps/Bluetooth/
 ▪ 87879be3 Bluetooth: Fix AAPT warning
 ▪ 14579714 Bluetooth: Remove unused string resources
 ▪ 6e7a55d0 Snap for 5322077 from dc53994d0f78066319d8e01966c9dd562b86e7ab to pi-qpr3-release
 ▪ dc53994d Import translations. DO NOT MERGE
 ▪ db7a51d9 Merge cherrypicks of [6391991, 6392011, 6391992, 6391993, 6392031, 6392051, 6392052, 6392091, 6392111, 6392032, 6391994, 6391995, 6391996, 6391997, 6391998, 6391999, 6392000, 6392001, 6392002, 6392003, 6392004, 6392005, 6392006, 6392112, 6392113, 6392151, 6392152] into pi-qpr2-release
 ▪ a7acf031 DO NOT MERGE Separate SDP procedure from bonding state (2/2)
 ▪ 49d9444b Snap for 5304822 from 05aa041a0041b4ac9dce21981a766eebd9173c59 to pi-qpr3-release

 ▼ packages/apps/Camera2/
 ▪ fff278380 Snap for 5322077 from b7419efc90ace578cdf0318f57717d3ffd65c800 to pi-qpr3-release
 ▪ b7419efc9 Import translations. DO NOT MERGE
 ▪ 8e7a25a14 Merge "Snap for 5180536 from 838861c5f58bfd1750ec83354b7c01d3bc41ac74 to pi-platform-release am: 0cfea440d3" into pie-gsi
 ▪ af7ccae64 Snap for 5180536 from 838861c5f58bfd1750ec83354b7c01d3bc41ac74 to pi-platform-release am: 0cfea440d3

 ▼ packages/apps/CarrierConfig/
 ▪ 7155a6a Snap for 5180536 from b9bad705178410c34bf4e4ed4f60964c45d0c2a5 to pi-platform-release am: 01ecac7c15

 ▼ packages/apps/CellBroadcastReceiver/
 ▪ 029fa53 Fix a warning in generating id in android namespace.
 ▪ 4ec03d3 Fix resource warnings.
 ▪ 5543707 Snap for 5322077 from c34232318429b0c0563e01b9a08f2b11fa6f7d73 to pi-qpr3-release
 ▪ c342323 Import translations. DO NOT MERGE
 ▪ 1e6e354 Merge "Snap for 5180536 from d51900a0b9ac2cc775dc5c7a9c53331ba7dd83e8 to pi-platform-release am: 1e41394675" into pie-gsi
 ▪ f7aa9a1 Snap for 5180536 from d51900a0b9ac2cc775dc5c7a9c53331ba7dd83e8 to pi-platform-release am: 1e41394675

 ▼ packages/apps/Contacts/
 ▪ d45121bda Contacts: Remove unused boolean resource
 ▪ 18aae7960 Fix casting warnings in ContactSaveService
 ▪ ed1ec6209 Snap for 5339334 from 32d567d53fc4beeaf62a89992aa883137bf192f8 to pi-qpr3-release
 ▪ 8456a75c0 Snap for 5335558 from 32d567d53fc4beeaf62a89992aa883137bf192f8 to pi-qpr3-b-release
 ▪ 32d567d53 Import translations. DO NOT MERGE
 ▪ 1a9c0a591 Merge "Snap for 5180536 from 166e3c8d175852bb21cf1b36cca361ff20c5ce35 to pi-platform-release am: 57240e7dfa" into pie-gsi
 ▪ d4c69d8ed Snap for 5180536 from 166e3c8d175852bb21cf1b36cca361ff20c5ce35 to pi-platform-release am: 57240e7dfa

 ▼ packages/apps/CustomDoze/
 ▪ 0452be9 CustomDoze: Add option to show AOD on charge only [2/2]

 ▼ packages/apps/DocumentsUI/
 ▪ 25e59678 Snap for 5339334 from af3625b9e530d01366a5933ccc6846d57d027a39 to pi-qpr3-release
 ▪ dc22f0d6 Snap for 5335558 from af3625b9e530d01366a5933ccc6846d57d027a39 to pi-qpr3-b-release
 ▪ af3625b9 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ df3e39e5 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 12508d02 Import translations. DO NOT MERGE
 ▪ bab2bba2 Import translations. DO NOT MERGE
 ▪ c1f7a824 Import translations. DO NOT MERGE
 ▪ a37e2252 Snap for 5180536 from 84fbb75721e04ca207ba4e29dd3120076db066f3 to pi-platform-release am: 9a562d7aca

 ▼ packages/apps/EmergencyInfo/
 ▪ 5289b20 Snap for 5322077 from 03a9e6ae773549281aab3b7d2d46de803d3a1138 to pi-qpr3-release
 ▪ 03a9e6a Import translations. DO NOT MERGE
 ▪ 9dcf5dd Snap for 5180536 from f9f7193d45b9fc3abbffa11d61c369c07cf4e993 to pi-platform-release am: a577a6e428

 ▼ packages/apps/FMRadio/

 ▼ packages/apps/HavocSettings/
 ▪ f858b4a Add lettuce in devices
 ▪ 64b5e6b Add trlte in devices
 ▪ 918e35b Settings: Fixes
 ▪ dd44649 Settings: Add back About section
 ▪ 84201f0 Settings: Increase rounded content padding
 ▪ 88e53ec Network Traffic: Add more customizations and improvement [1/2]
 ▪ cfd9c6a Notch friendly carrier label [2/2]
 ▪ ebaa809 Revert "Disable grid recents [2/2]"
 ▪ 89da9bb Add option to auto hide status-bar clock [2/2]
 ▪ e8d9d79 Allow to doubletap or longpress power to toggle flashlight [3/3]
 ▪ b9d9719 Revert "Power button flashlight"
 ▪ c1e9ef9 CustomActions: Use settings provider to store value [3/3]
 ▪ 6711ad3 CustomActions: Add ringer modes
 ▪ 9295968 CustomActions: Add support to launch applications [2/2]
 ▪ 106efdf Settings: Multiuser switch [2/2]
 ▪ 27bbb35 Allow tuning extra padding for status bar
 ▪ e6a5125 Add a footer to Active Edge settings
 ▪ 5a2825e Only inherit Elmyra for Pixel devices
 ▪ b6c8757 Active edge settings 3/?
 ▪ 9753b45 BatteryLight: Fix NPE
 ▪ 97ea53a OP like gestures: more tweaks [2/2]
 ▪ 81e36bb QS: Allow coloring bg with accent [2/2]
 ▪ e343c7d Settings: Custom theming [2/3]
 ▪ 0b448ee Settings: Cleanup themes
 ▪ 89986d1 Carrier label: Ensure the dialog matches other dialogs
 ▪ dae4672 Set a text length on the carrier label
 ▪ eed94d8 Settings: Switch logic of some settings
 ▪ 5355bfd Settings: Cleanup
 ▪ fb39ae1 Settings: Adapt for vendor_support

 ▼ packages/apps/Messaging/
 ▪ a8efd2c Messaging: Fix generating id in android namespace

 ▼ packages/apps/Nfc/
 ▪ 4bcd27dc Snap for 5322077 from 0ff8ee3a757ceb566a1d7ff8f4d265a57ce851a4 to pi-qpr3-release
 ▪ 0ff8ee3a Import translations. DO NOT MERGE
 ▪ 6e5dfb23 Merge "Snap for 5180536 from 81ed378559c43c8da4a4b20a290e4519d29a4598 to pi-platform-release am: c04e4026a8" into pie-gsi
 ▪ 2307da0b Snap for 5180536 from 81ed378559c43c8da4a4b20a290e4519d29a4598 to pi-platform-release am: c04e4026a8

 ▼ packages/apps/PackageInstaller/
 ▪ 0c1c6128 PackageInstaller: Fix generating id in android namespace
 ▪ 43fe700e Merge "Snap for 5240760 from 2d763bd5d06c08402d32a18260e56fee79c763df to pi-platform-release am: bd0a23fe61" into pie-gsi
 ▪ d28be301 Snap for 5240760 from 2d763bd5d06c08402d32a18260e56fee79c763df to pi-platform-release am: bd0a23fe61
 ▪ bd0a23fe Snap for 5240760 from 2d763bd5d06c08402d32a18260e56fee79c763df to pi-platform-release
 ▪ 29e48bf4 Merge tag 'android-9.0.0_r34' into pie
 ▪ b101f7ec Snap for 5339334 from c51083ab879a3f4c020f00eeb19c4627d35a8e04 to pi-qpr3-release
 ▪ 32836611 Snap for 5335558 from c51083ab879a3f4c020f00eeb19c4627d35a8e04 to pi-qpr3-b-release
 ▪ c51083ab Import translations. DO NOT MERGE
 ▪ 21bc16d0 Merge "Snap for 5180536 from ded9a473ea2f7691b7e65296ec7d19c06d6dee99 to pi-platform-release am: 0e9d43d382" into pie-gsi
 ▪ fe0458a0 Snap for 5180536 from ded9a473ea2f7691b7e65296ec7d19c06d6dee99 to pi-platform-release am: 0e9d43d382

 ▼ packages/apps/Recorder/

 ▼ packages/apps/Settings/
 ▪ 1b29c28aef [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49 am: b810aee20f am: 7a58589114 am: 7926131837 am: d6bde3f5b8 am: ba87cf7444 am: 9366d11e6d am: 657f8713ff
 ▪ 657f8713ff [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49 am: b810aee20f am: 7a58589114 am: 7926131837 am: d6bde3f5b8 am: ba87cf7444 am: 9366d11e6d
 ▪ 9366d11e6d [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49 am: b810aee20f am: 7a58589114 am: 7926131837 am: d6bde3f5b8 am: ba87cf7444
 ▪ 40dafa984a Changelog: Fix title on actionbar
 ▪ 046443c5f6 Changelog: Add left padding
 ▪ 091dc40239 Settings: update changelog activity * improve code
 ▪ 48aec6ce33 Changelog: Fix text selection with dot
 ▪ 40c4c9ccce Changelog: clean and make themeable before: https://imgur.com/a/ylSQG after: https://imgur.com/a/GdnPN
 ▪ 8dbd4b8fe8 Changelog: prettify
 ▪ c651d5971b Settings: Changelog
 ▪ 343e5f9986 Snap for 5339334 from 02681df33f0830102b77be68858180f8243aa8a5 to pi-qpr3-release
 ▪ 25aa39eeb2 Snap for 5335558 from 02681df33f0830102b77be68858180f8243aa8a5 to pi-qpr3-b-release
 ▪ 9e354af83e Settings: Fix empty summary for VPN and SIM Card
 ▪ 6df440d96b Settings: change default night light brightness (1/2)
 ▪ 5cfd4c9fb6 Revert "Add advanced battery info"
 ▪ 02681df33f Import translations. DO NOT MERGE
 ▪ 69ad162c58 LEDs: Add "All Apps" to LED per-app list. Also make it the default.
 ▪ 9bb267258c Allow to doubletap or longpress power to toggle flashlight [2/3]
 ▪ 83c218b65f Revert "Make batterysaver dark mode state configurable [2/2]"
 ▪ ba87cf7444 [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49 am: b810aee20f am: 7a58589114 am: 7926131837 am: d6bde3f5b8
 ▪ d6bde3f5b8 [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49 am: b810aee20f am: 7a58589114 am: 7926131837
 ▪ 7926131837 [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49 am: b810aee20f am: 7a58589114
 ▪ 7a58589114 [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49 am: b810aee20f
 ▪ b810aee20f [automerger] Do not allow draw on top for default sms picker. am: 95d0fb7f49
 ▪ 95d0fb7f49 Do not allow draw on top for default sms picker.
 ▪ bd9413dd4b Make home button wake up opt-in [2/2]
 ▪ a881072ec2 PrivacyGuard: Add missing permission icons
 ▪ b4b3557fc6 Themes: Expose suggestion and condition cards
 ▪ 1fcfbd1103 Revert "Use colorPrimary for search bar and suggestion background"
 ▪ 9c593f3a23 Settings: Cleanup themes
 ▪ 86b874f41e Settings: Expose searchbar background color
 ▪ d46b2d9e22 Merge "Snap for 5180536 from c103b546d2e33aacd8187a6bf54b28efa325ffbe to pi-platform-release am: 98cdb732ce" into pie-gsi
 ▪ e0fc68a489 Snap for 5180536 from c103b546d2e33aacd8187a6bf54b28efa325ffbe to pi-platform-release am: 98cdb732ce
 ▪ e5f88c5c2c Improve accent picker layout

 ▼ packages/apps/SettingsIntelligence/
 ▪ 4a49462 Themes: Expose search bar

 ▼ packages/apps/SmartNav/
 ▪ cdf4c2d Navigator: Add isFullGestureMode method

 ▼ packages/apps/SmartNavSettings/
 ▪ 9fafe61 Fix "white on white" in SmartActions dialog list adapter
 ▪ 23f249b Settings: Fixes
 ▪ 969aefb Disable all gestures when navbar enabled
 ▪ 003e47b SmartActions backend support [2/2]

 ▼ packages/apps/Snap/
 ▪ d11351354 Snap: Add back original-package in manifest
 ▪ a0be5c22f Snap: Remove unused resources
 ▪ 39f672bed Merge tag 'LA.UM.7.3.r1-06900-sdm845.0' into HEAD
 ▪ c1f9b6c4d Snap: Fix shutter button size

 ▼ packages/apps/Terminal/

 ▼ packages/inputmethods/LatinIME/
 ▪ b25378ea0 Snap for 5339334 from 289a72634b06b499c6554f485158c0baacaa061d to pi-qpr3-release
 ▪ 80eee44c2 Snap for 5335558 from 289a72634b06b499c6554f485158c0baacaa061d to pi-qpr3-b-release
 ▪ 289a72634 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 624bac2cd Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ a921223fe Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 01900e65f Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ e95183534 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 35ac417ae Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 9e73c487e Import translations. DO NOT MERGE
 ▪ 621f24c94 Import translations. DO NOT MERGE
 ▪ 463afb44e Import translations. DO NOT MERGE
 ▪ c57cda4a3 Import translations. DO NOT MERGE
 ▪ 42f8490ea Import translations. DO NOT MERGE
 ▪ 685f41288 Import translations. DO NOT MERGE
 ▪ f82540f2d Import translations. DO NOT MERGE
 ▪ 64c485868 Merge "Snap for 5180536 from 556b091a754cadd239102086bbcfa77e5afe6ba4 to pi-platform-release am: 20de0ce610" into pie-gsi
 ▪ bea63f406 Snap for 5180536 from 556b091a754cadd239102086bbcfa77e5afe6ba4 to pi-platform-release am: 20de0ce610

 ▼ packages/providers/DownloadProvider/
 ▪ 57fb22a Snap for 5322077 from 2b3342d3efe30f55f37fb8cce94d0a12baee92f6 to pi-qpr3-release
 ▪ 2b3342d Import translations. DO NOT MERGE
 ▪ 9b670c2 Merge "Snap for 5180536 from 91873a4c1851268f0b7f86cc33bb3403fe24b2ad to pi-platform-release am: ac2c2c0eea" into pie-gsi
 ▪ f3046ac Snap for 5180536 from 91873a4c1851268f0b7f86cc33bb3403fe24b2ad to pi-platform-release am: ac2c2c0eea

 ▼ packages/providers/MediaProvider/
 ▪ 33d84b7 Snap for 5339334 from 80b46f91427481e7ab888b1a40a7bb6c7b264a85 to pi-qpr3-release
 ▪ 2c3e8e6 Snap for 5335558 from 80b46f91427481e7ab888b1a40a7bb6c7b264a85 to pi-qpr3-b-release
 ▪ 80b46f9 Import translations. DO NOT MERGE
 ▪ b5ee1fd Merge "Snap for 5180536 from 01ba7e7dd6506c59bd25312c9e910424a20d113f to pi-platform-release am: f0d22e1f09" into pie-gsi
 ▪ 8d16ca2 Snap for 5180536 from 01ba7e7dd6506c59bd25312c9e910424a20d113f to pi-platform-release am: f0d22e1f09

 ▼ packages/providers/WeatherProvider/
 ▪ 46e8f56 WeatherProvider: Fix conditions
 ▪ 0120a37 WeatherChannelApi: Fix allocation abuse

 ▼ packages/services/Telecomm/
 ▪ b0a9c9f3 Snap for 5354036 from 974e10054a92850e9a8499114758e03ec9a6864b to p-keystone-qcom-release
 ▪ 44e9c9ae Merge tag 'LA.UM.7.6.2.r1-07100-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into caf
 ▪ 347851e7 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_services_Telecomm into caf
 ▪ 6cfe5e38 Snap for 5339334 from 695beedd70a2e227f2373a8b5a67bfd7d89d8b0b to pi-qpr3-release
 ▪ d37a18bc Snap for 5335558 from 695beedd70a2e227f2373a8b5a67bfd7d89d8b0b to pi-qpr3-b-release
 ▪ 695beedd Merge "DO NOT MERGE Speculative fix for BT race condition" into pi-dev
 ▪ d32fb75a Snap for 5322077 from 259fd1e08bf2233a1c825649832276e9a178a4a7 to pi-qpr3-release
 ▪ 974e1005 Merge SPL-2019-02-05
 ▪ 259fd1e0 Import translations. DO NOT MERGE
 ▪ 3424bea3 DO NOT MERGE Speculative fix for BT race condition
 ▪ 6e294fc7 Snap for 5180536 from 5980327bb95f8bdcf49f6cea4dcd5ae8e40df6c9 to pi-platform-release am: 053978e21f

 ▼ packages/services/Telephony/
 ▪ 63274e6e9 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_services_Telephony into caf
 ▪ fbdc8c914 Stop generating ids in android namespace.
 ▪ e696ae2d0 Fix resource warnings.
 ▪ becbf758b Snap for 5354036 from aeab0bb926e80f1dc39e1e127bd1b57509155510 to p-keystone-qcom-release
 ▪ 039ea3697 Telephony: Use IEC standard to update data usage
 ▪ e5b02a32f Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_packages_services_Telephony into caf
 ▪ 4256b9fd4 Merge tag 'LA.UM.7.6.2.r1-07100-89xx.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into caf
 ▪ aeab0bb92 Merge SPL-2019-02-05
 ▪ 9cc3db0d5 Telephony: Fix AAPT warnings
 ▪ 4a49292c1 Telephony: Mark enhanced_4g_lte_mode_title_variant as untranslatable
 ▪ a7d255500 Telephony: Mark enhanced_4g_lte_mode_title_variant as untranslatable
 ▪ 2f5f6c143 Merge cherrypicks of [6541047, 6541028, 6541180, 6540905] into pi-b4s4-release
 ▪ 42f3a3f7a DO NOT MERGE ANYWHERE 1x options be removed from specific preferred network list.
 ▪ 99564aaf0 DO NOT MERGE ANYWHERE 1x options be removed from specific preferred network list.
 ▪ 404958e8f Snap for 5322077 from 782e60ff33b34795f142e4ceecabb1bc657281c8 to pi-qpr3-release
 ▪ 59a81dcb2 Snap for 5319882 from a9148a0daf808ec1acacba63608b518f6e2e58c0 to p-keystone-qcom-release
 ▪ 85ddea8b9 Telephony: Improve theme
 ▪ 6bbeb978d ToggleLte: Add missed LTE modes
 ▪ e5c0d4e3b Vectorize sip icon
 ▪ a9148a0da Avoid sending two CLIR requests while enter additional settings
 ▪ 782e60ff3 Import translations. DO NOT MERGE
 ▪ f826bad87 set config_enabled_lte to true by default
 ▪ 52d98103f Merge cherrypicks of [6333255, 6333230, 6333232, 6333337, 6333338, 6333339, 6333853, 6333199, 6333874, 6333875, 6333876, 6333877, 6333274, 6333275, 6333276, 6333277, 6333814, 6333256, 6333815, 6333278, 6333236, 6333854, 6333816] into pi-b4s4-release
 ▪ 9ce6ec9b2 fix translations. DO NOT MERGE

 ▼ prebuilts/r8/
 ▪ 2e25531 r8: Update D8 and R8 to 1.5.9-dev
 ▪ 464e98b r8: Update D8 and R8 to 1.5.7-dev
 ▪ c6b5efe r8: Update D8 and R8 to 1.5.5-dev

 ▼ system/bt/
 ▪ cac66ef65 Merge "DO NOT MERGE: Use a weak pointer to deliver updates to AVRCP devices." into pi-dev
 ▪ f083d1e07 DO NOT MERGE: Use a weak pointer to deliver updates to AVRCP devices.
 ▪ 2c4c54708 Snap for 5240760 from b9dd3863033facdd8608904e4dd59ff3cc52871b to pi-platform-release am: abb707675a
 ▪ abb707675 Snap for 5240760 from b9dd3863033facdd8608904e4dd59ff3cc52871b to pi-platform-release
 ▪ 3b4b1a082 [automerger skipped] [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe am: 066e401178 am: c97a452b7c am: a2661852ce skipped: 3c413e34d2 am: ec1eca1dfb am: 294210a1a2 am: aa03b49791 -s ours am skip reason: subject contains skip directive
 ▪ aa03b4979 [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe am: 066e401178 am: c97a452b7c am: a2661852ce skipped: 3c413e34d2 am: ec1eca1dfb am: 294210a1a2
 ▪ 294210a1a [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe am: 066e401178 am: c97a452b7c am: a2661852ce skipped: 3c413e34d2 am: ec1eca1dfb
 ▪ 9d0694a77 Merge "DO NOT MERGE Fix length for L2CAP config type EXT FLOW" into nyc-dev
 ▪ fe73464f0 Clear the link key when releasing security records
 ▪ ec1eca1df [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe am: 066e401178 am: c97a452b7c am: a2661852ce skipped: 3c413e34d2
 ▪ 3c413e34d [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe am: 066e401178 am: c97a452b7c am: a2661852ce
 ▪ a2661852c [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe am: 066e401178 am: c97a452b7c
 ▪ c97a452b7 [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe am: 066e401178
 ▪ 066e40117 [automerger] DO NOT MERGE Fix length for L2CAP config type EXT FLOW am: 1fa0f29dbe
 ▪ 1fa0f29db DO NOT MERGE Fix length for L2CAP config type EXT FLOW
 ▪ b3c794b73 Merge tag 'android-9.0.0_r34' into pie
 ▪ 04c6c2121 Snap for 5339334 from 2a1ee659eaa5eb6a03d963f2b8e3ded860a1cc52 to pi-qpr3-release
 ▪ de1a29326 Snap for 5335558 from 2a1ee659eaa5eb6a03d963f2b8e3ded860a1cc52 to pi-qpr3-b-release
 ▪ 2a1ee659e Merge "Fix mtu assignment with correct value" into pi-dev
 ▪ fdd0bb033 Merge "Do not close dump file descriptor" into pi-dev
 ▪ 80c748c40 Merge "Fix for Bluetooth device name is resetting to default name after reboot" into pi-dev
 ▪ 817facf4b Merge cherrypicks of [6391991, 6392011, 6391992, 6391993, 6392031, 6392051, 6392052, 6392091, 6392111, 6392032, 6391994, 6391995, 6391996, 6391997, 6391998, 6391999, 6392000, 6392001, 6392002, 6392003, 6392004, 6392005, 6392006, 6392112, 6392113, 6392151, 6392152] into pi-qpr2-release
 ▪ 348f7e996 btm_proc_smp_cback: Don't access p_dev_rec if freed
 ▪ 7365db832 DO NOT MERGE Separate SDP procedure from bonding state (1/2)
 ▪ 5474692f7 resolve merge conflicts of ec78d74706c3e81f91eee53e3d9f959f66e5d77f to pi-dev
 ▪ 209ce3d05 btm_ble_multi_adv: Check data length in HCI interface
 ▪ 0db97596f Snap for 5304822 from 5980eefcfb684c4f2006be9a767d90fce99973c0 to pi-qpr3-release
 ▪ 5cd56bc3d resolve merge conflicts of ec78d74706c3e81f91eee53e3d9f959f66e5d77f to pi-dev
 ▪ 583a7016e DO NOT MERGE Separate SDP procedure from bonding state (1/2)
 ▪ 97575010a btm_proc_smp_cback: Don't access p_dev_rec if freed
 ▪ be319c63e btm_ble_multi_adv: Check data length in HCI interface
 ▪ 9c0243e9e Snap for 5180536 from 6f2759c64311b505b1ddc73e2bfc9f0330845780 to pi-platform-release am: 21dba69f70

 ▼ system/core/
 ▪ 6f9956b09 Export maximum number of fds/ints in a native_handle.

 ▼ system/extras/
 ▪ 0457fdf6 Remove -Wno-error from system/extras
 ▪ b30375e4 Merge "Snap for 5180536 from 9ec7ba8443caa905c2ebdf6eadd5e6148a348d37 to pi-platform-release am: 971f83995e" into pie-gsi
 ▪ 92f9f35a Snap for 5180536 from 9ec7ba8443caa905c2ebdf6eadd5e6148a348d37 to pi-platform-release am: 971f83995e

 ▼ system/libhwbinder/
 ▪ 2311229 Snap for 5240760 from e2aef07780285f4d39d589b3933e22ef226d0dd2 to pi-platform-release am: 1893ef69a2
 ▪ 1893ef6 Snap for 5240760 from e2aef07780285f4d39d589b3933e22ef226d0dd2 to pi-platform-release
 ▪ 3a1f28e Merge tag 'android-9.0.0_r34' into pie

 ▼ system/netd/
 ▪ 19f2a2b Merge cherrypicks of [6391991, 6392011, 6391992, 6391993, 6392031, 6392051, 6392052, 6392091, 6392111, 6392032, 6391994, 6391995, 6391996, 6391997, 6391998, 6391999, 6392000, 6392001, 6392002, 6392003, 6392004, 6392005, 6392006, 6392112, 6392113, 6392151, 6392152] into pi-qpr2-release
 ▪ 04ba32f Clear Element.mRef immediately after deallocating it
 ▪ 8d67a8b Fix fortify_fatal issue during DNSServiceProcessResult()
 ▪ e00529f Fix use-after-free in NetworkController::removeInterfaceAddress()
 ▪ f1b1f1e Snap for 5304822 from 9762bc1964a37ec56091ee2b6070e19c5206f615 to pi-qpr3-release
 ▪ 2edfa62 Clear Element.mRef immediately after deallocating it
 ▪ 4e65fc1 Fix fortify_fatal issue during DNSServiceProcessResult()
 ▪ 782424c Fix use-after-free in NetworkController::removeInterfaceAddress()
 ▪ f7b06bf Snap for 5180536 from a80475564fdced61fa9853468e441a352b11ae08 to pi-platform-release am: 3e51dd168b

 ▼ system/nfc/
 ▪ 8a86b1f Prevent OOB error in rw_i93_process_ext_sys_info()
 ▪ 9b406b6 Prevent OOB error in rw_i93_sm_update_ndef()
 ▪ 46defd3 Prevent OOB error in rw_i93_sm_read_ndef()
 ▪ 6e267b3 Prevent OOB error in rw_i93_sm_detect_ndef()
 ▪ ba95bb1 Prevent OOB read in rw_i93_process_sys_info()
 ▪ 4a115a7 Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()

 ▼ system/qcom/
 ▪ ae5b6b1 Merge tag 'LA.UM.7.8.r4-00800-SDM710.0' of https://source.codeaurora.org/quic/la/platform/system/qcom into HEAD
 ▪ 7904b20 Merge tag 'LA.UM.7.8.r1-04800-SDM710.0' of https://source.codeaurora.org/quic/la/platform/system/qcom into HEAD
 ▪ 3daedcc Merge e0c1c7780a741a191748986a0d1cf598486a6597 on remote branch

 ▼ system/sepolicy/
 ▪ 8f3d77f13 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_system_sepolicy into pie
 ▪ fd0e3749b Snap for 5354036 from 77e0f5397f374af213a7e1b7b353e0f19e0adc73 to p-keystone-qcom-release
 ▪ c74b6f660 sepolicy: Allow init to chown sysfs LED files
 ▪ 982db16a7 Revert "Add adb over network tile sepolicy"
 ▪ d3c76de67 Merge branch 'pie' of https://github.com/Havoc-OS/android_system_sepolicy into pie
 ▪ dc85c1082 sepolicy: Treat proc-based DT fstab the same and sys-based
 ▪ cead5e1c3 Allow stats_companion to register thermal throttling event listener.
 ▪ 1e9fe567f sepolicy: public: Exclude Recovery from system mount neverallow
 ▪ 23d2addb1 Ignore newly added selinux objects
 ▪ 28f93c95d sepolicy: Treat proc-based DT fstab the same and sys-based
 ▪ 77e0f5397 Merge SPL-2019-02-05
 ▪ 687995ed5 Allow stats_companion to register thermal throttling event listener.
 ▪ 4c9031e4e sepolicy: public: Exclude Recovery from system mount neverallow
 ▪ 9b391e9b6 Snap for 5180536 from 6308216c6c5afc1caf2d34e7865ca546bf760450 to pi-platform-release am: 362a69242b

 ▼ system/timezone/
 ▪ 5e15ef1 Snap for 5180536 from 9fff3df46bcab5c3575b40b7c3b2910e8bb21286 to pi-platform-release am: 94c787cadc

 ▼ system/tools/hidl/
 ▪ 3462d9c Snap for 5240760 from db3dd8187ce35f26ab0542718f585833975b937f to pi-platform-release am: 00e5fcd14e
 ▪ 00e5fcd Snap for 5240760 from db3dd8187ce35f26ab0542718f585833975b937f to pi-platform-release
 ▪ 30d29fd Merge tag 'android-9.0.0_r34' into pie

 ▼ system/update_engine/
 ▪ 1d58c95 Move performance mode to top app
 ▪ dd8878b Snap for 5180536 from 0eb2fd56a234e5f1279c2a401219646d9635f023 to pi-platform-release am: 0d0e2e11ab

 ▼ system/vold/
 ▪ bb14c3c Merge "resolve merge conflicts of c03435f532753b8bd6816d4500ffeb3dcb167a57 to pie-gsi" into pie-gsi
 ▪ dfc7eb4 resolve merge conflicts of c03435f532753b8bd6816d4500ffeb3dcb167a57 to pie-gsi

 ▼ vendor/MiuiCamera/
 ▪ 595708a add priv-app permissions
 ▪ b403e6b initial release

 ▼ vendor/codeaurora/telephony/
 ▪ d450aea Merge b98b950ca5636cd9ed13ff4a6a90afca45457dce on remote branch
 ▪ 758efa2 Merge 49d6361156734d022e0df7229f99d96cab69c8a1 on remote branch
 ▪ 517f60b Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie
 ▪ 912edd0 Merge 49d6361156734d022e0df7229f99d96cab69c8a1 on remote branch
 ▪ e6fbd99 Merge 49d6361156734d022e0df7229f99d96cab69c8a1 on remote branch
 ▪ e86c65f Merge 49d6361156734d022e0df7229f99d96cab69c8a1 on remote branch
 ▪ b98b950 Introduce a new 5G AIDL API for 5G icon changes
 ▪ 49d6361 IMS: Use AOSP RTT_CALLING_MODE key for RTT settings.

 ▼ vendor/havoc/
 ▪ 1d045cca vendor: Changes for OTA
 ▪ 4fae783d Havoc 2.3
 ▪ 21f25a8f Create /data/havoc_updates to store updates
 ▪ e491b449 vendor: Add A/B Updater priv-app permissions
 ▪ 6fc479e0 update Lawnchair to alpha-914
 ▪ fb7c87e6 update Lawnchair to alpha-909
 ▪ c4c5a3ac update google deskclock
 ▪ 4b3b2bc2 address Wellbeing permissions
 ▪ 04f91395 Active edge settings 4/?
 ▪ 2db9cd1f Merge branch 'pie' of https://github.com/Havoc-OS/android_vendor_havoc into pie
 ▪ 44dc2be3 qcom: Mark some gralloc bits as valid
 ▪ 8a7bb2c8 fix LD_LIBRARY_PATH
 ▪ 73f91413 Switch to vendor_themes [1/2]
 ▪ 88e3dc63 Build CustomDoze for all devices
 ▪ a8621419 Use Cloudflare DNS servers as hints
 ▪ a79e3b29 Use Cloudflare DNS as the default fallback
 ▪ 3bb879f8 Fix light statusbar and navbar on Wellbeing
 ▪ a155f942 Add wellbeing dark theme
 ▪ 54af49d5 Remove proxy for Koodo
 ▪ 67679e2d do we really need all this shit?
 ▪ d2474568 bring back Google DeskClock
 ▪ 8f845306 bring back Google Markup, Digital Wellbeing and Turbo
 ▪ 73c0212a replace PixelLauncher with Lawnchair
 ▪ 1a2fc758 update vendor
 ▪ f334298a add Google Assistant support
 ▪ 0eea673c Set some default values

 ▼ vendor/qcom/opensource/audio/
 ▪ 6360d7c Merge fea6ea0a7032c050bc5273b74b11537a7578cc9d on remote branch
 ▪ 3beb7a6 Merge fea6ea0a7032c050bc5273b74b11537a7578cc9d on remote branch
 ▪ fea6ea0 policy_hal: do not check MODE_IN_COMMUNICATION for voip_rx flag

 ▼ vendor/qcom/opensource/cryptfs_hw/
 ▪ 6d8a4fb Merge 684bb8d924b4cf54544060f8a3eebce301dbc120 on remote branch
 ▪ 1c9483b Merge 684bb8d924b4cf54544060f8a3eebce301dbc120 on remote branch
 ▪ f4dc741 Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/cryptfs_hw into pie
 ▪ 7d767c7 Merge tag 'LA.UM.7.6.2.r1-06900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/cryptfs_hw into pie

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ c41fb73 Merge cca4c15198f1fc0c04cd08645e8b32300a609e79 on remote branch
 ▪ 4f0ea34 Merge tag 'LA.UM.7.3.r1-06900-sdm845.0' into HEAD
 ▪ 27b11cf Merge cca4c15198f1fc0c04cd08645e8b32300a609e79 on remote branch
 ▪ 2d559da Merge cca4c15198f1fc0c04cd08645e8b32300a609e79 on remote branch

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 99d321e Merge e6bbd7f8a9dfe6393929e35fbc5120a4902e9c8d on remote branch
 ▪ cfba4df Merge tag 'LA.UM.7.5.r1-04300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into HEAD
 ▪ 19ea064 Merge tag 'LA.UM.7.6.2.r1-07100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into HEAD
 ▪ 7a97589 Merge e6bbd7f8a9dfe6393929e35fbc5120a4902e9c8d on remote branch
 ▪ bc669bd Merge e6bbd7f8a9dfe6393929e35fbc5120a4902e9c8d on remote branch
 ▪ 1af7e1d Merge tag 'LA.UM.7.6.2.r1-06900-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

 ▼ vendor/qcom/opensource/thermal-engine/
 ▪ 3e8495d Merge tag 'LA.UM.7.3.r1-06900-sdm845.0' into HEAD

 ▼ vendor/support/
 ▪ 18ca7c5 AppPicker: Import from external/google for other uses
 ▪ c71504b Color Picker: Remove OnClick listener to fix disabling
 ▪ 46945fe Extend custom seekbar preferences

 ▼ vendor/themes/
 ▪ 11a8a23 themes: Update GBoard MD2 themes
 ▪ 52c3f50 Revert "themes: Add Gboard overlay [2/2]"
 ▪ 9e2e0e5 themes: Add Gboard overlay [2/2]
 ▪ 7e5f8b0 themes: Custom theming [3/3]
 ▪ 2e567a1 Switch to vendor_themes [2/2]

====================
     02-10-2019
====================
 ▼ art/
 ▪ 242cf1b7d4 Snap for 5180536 from 1f5f55bfaa13923bc5483a6f9d8189ed4edc74a6 to pi-platform-release
 ▪ f84939d885 Merge 1d93c022c9f0beb17c2bed8d24929d7e7d66455d on remote branch
 ▪ d4daa2214c Merge tag 'android-9.0.0_r33' into pie
 ▪ 7e6bc6f2ec Merge 1d93c022c9f0beb17c2bed8d24929d7e7d66455d on remote branch
 ▪ 20664d9195 Pause GC during deoptimization work

 ▼ bionic/
 ▪ d307fa248 Snap for 5180536 from b32be3f072132a2833e5ab963ce4a2592436805f to pi-platform-release
 ▪ 4011ad31b Merge 68ea667c147b2e6bb994688984e7a57e783465a7 on remote branch
 ▪ 0a932344b Merge tag 'android-9.0.0_r33' into pie
 ▪ 1479daf86 Merge tag 'android-9.0.0_r31' of https://android.googlesource.com/platform/bionic into pie
 ▪ 08a749496 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' of https://source.codeaurora.org/quic/la/platform/bionic into pie
 ▪ 4281bac64 Merge 68ea667c147b2e6bb994688984e7a57e783465a7 on remote branch
 ▪ d8e72eeaa Merge 68ea667c147b2e6bb994688984e7a57e783465a7 on remote branch
 ▪ 68f7efc04 Merge cherrypicks of [6086654] into pi-qpr2-release
 ▪ 973b64c3e Remove some PR_SET_VMAs during pthread_create
 ▪ 840c9b0ad Revert "Revert "Remove __overloadable/__RENAME_CLANG""
 ▪ ac2b34901 Implement per-process target SDK version override.
 ▪ bb1b91fc7 bionic: Use legacy pthread_mutex_init() behavior on pre-P API levels
 ▪ c783240fe libc: Mark libstdc++ as vendor available
 ▪ d61e0321e bionic: Sort and cache hosts file data for fast lookup
 ▪ ec505e046 linker: Make platform text relocations denial optional

 ▼ bootable/recovery/
 ▪ 79df274d Merge remote-tracking branch 'AOSP/pie-gsi' into pie

 ▼ build/blueprint/
 ▪ 759c5ac Fix issues found by `go vet`
 ▪ cf71e18 Add go.mod for go1.11 module support
 ▪ 8a4bdfd Improve indentation for multi-line expressions
 ▪ 4e9a653 Don't Cap the number of cpus for Go compiles

 ▼ build/kati/
 ▪ a4c8779 Snap for 5180536 from 2a49513da00436f434281a98dfb118db855db013 to pi-platform-release
 ▪ bc2319a Merge tag 'android-9.0.0_r33' into pie

 ▼ build/make/
 ▪ cae98e97b Remove extra $ in soong_app_prebuilt
 ▪ 641da2907 Make change and version bump to PPRL.190205.001
 ▪ 0b5a344dc Update Security String to 2019-04-05 Bug: 124119313
 ▪ f9835d9f4 Update Security String to 2019-04-01 Bug: 124119313
 ▪ e917a5176 Make change and version bump to PQ3A.190206.001
 ▪ 72f59d9fd Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/build into pie
 ▪ 19b6b9981 Merge tag 'android-9.0.0_r31' of https://android.googlesource.com/platform/build into pie
 ▪ bf47a387a proguard_flags: Disable -optimizations flag for r8 1.5.2
 ▪ 4816f5df5 Don't export BUILD_NUMBER in envsetup
 ▪ d27fed42e Accept TARGET_DEVICE_DIR preserved from previous product load
 ▪ 400d188a6 Make change and version bump to PQ3A.190130.001
 ▪ 6c12d1474 Version bump to PD2A.190115.017
 ▪ 8c34dfc67 Version bump to PD2A.190115.016
 ▪ e48a72210 Version bump to PD2A.190115.015
 ▪ 69adbbccf Version bump to PD2A.190115.014
 ▪ b9e69fa08 Version bump to PD2A.190115.013
 ▪ 417fc25e2 Version bump to PD2A.190115.012
 ▪ 585ce1159 Make change and version bump to PQ3A.190124.001
 ▪ e6414a2bc Make change and version bump to PQ3A.190123.001
 ▪ 50ee91f6c Version bump to PQ3A.190122.001
 ▪ cab122d90 Version bump to PD2A.190115.011
 ▪ bfd57a2db Version bump to PD2A.190115.010
 ▪ 0a0e22512 Version bump to PD2A.190115.009
 ▪ c2f5ee930 Version bump to PD2A.190115.008
 ▪ 53150fa92 Version bump to PD2A.190115.007
 ▪ fb11caea3 Version bump to PD2A.190115.006
 ▪ 598c330ee change persist_file to mnt_vendor_file for gsi
 ▪ 1bb45f072 Version bump to PD2A.190115.005
 ▪ 51b00a10c Version bump to PQ2A.190305.002
 ▪ bcf1b9658 Version bump to PD2A.190115.004
 ▪ 4fde3a771 Make change and version bump to PQ2A.190305.001
 ▪ 4ce3b412d Update Platform Security String to 2019-03-05 for pi-dev Bug:122541777 (cherry picked from commit ac6eac206d0e4b0604a362d1bcbfae3e1b03bfc2)
 ▪ 6d7ba6e93 Version bump to PQ2A.190301.002
 ▪ 7b4e1a7d4 Version bump to PD2A.190115.003
 ▪ bf4ad8a74 Version bump to PD2A.190115.002
 ▪ cc77ba0cb Make change and version bump to PD2A.190115.001
 ▪ 240748840 [automerger skipped] [DO NOT MERGE] Update Platform Security String to 2019-03-05 for oc-mr1-dev Bug:122541777 am: eb164e06b2 -s ours am skip reason: subject contains skip directive
 ▪ 12567b09b Make change and version bump to PQ2A.190301.001
 ▪ f627655b7 Update Platform Security String to 2019-03-01 for pi-dev Bug:122541777 (cherry picked from commit a1165c3723c9d58afc83202ff63c6f691737effb)
 ▪ eb164e06b [DO NOT MERGE] Update Platform Security String to 2019-03-05 for oc-mr1-dev Bug:122541777
 ▪ 5be53c95d Make change and version bump to PD2A.190114.001
 ▪ ecc206199 [automerger skipped] Merge "[DO NOT MERGE] Update Platform Security String to 2019-03-01 for oc-mr1-dev Bug:122541777" into oc-mr1-dev am: 7e8e840f61 -s ours am skip reason: subject contains skip directive
 ▪ 7e8e840f6 Merge "[DO NOT MERGE] Update Platform Security String to 2019-03-01 for oc-mr1-dev Bug:122541777" into oc-mr1-dev
 ▪ e46ada4f2 [automerger skipped] [automerger] [DO NOT MERGE] Update Platform Security String to 2019-03-01 for nyc-dev Bug:122541777 am: 7a403979d6 am: e56e5efec9 am: 87877d530a am: 33ecfffc1f skipped: 440db90921 am: ed56062889 am: f583da6005 am: 04bc1f36da -s ours am skip reason: subject contains skip directive
 ▪ 04bc1f36d [automerger] [DO NOT MERGE] Update Platform Security String to 2019-03-01 for nyc-dev Bug:122541777 am: 7a403979d6 am: e56e5efec9 am: 87877d530a am: 33ecfffc1f skipped: 440db90921 am: ed56062889 am: f583da6005
 ▪ 1beeb0c07 Merge "Make change and version bump to PPRL.190105.001 am: 0252b84cf1" into pie-gsi
 ▪ 6a253997a Make change and version bump to PPRL.190105.001 am: 0252b84cf1
 ▪ f583da600 [automerger] [DO NOT MERGE] Update Platform Security String to 2019-03-01 for nyc-dev Bug:122541777 am: 7a403979d6 am: e56e5efec9 am: 87877d530a am: 33ecfffc1f skipped: 440db90921 am: ed56062889
 ▪ fef62e30c Merge "Version bump to PPRL.181205.002 am: 6d1164be43" into pie-gsi
 ▪ 213320d1c Version bump to PPRL.181205.002 am: 6d1164be43
 ▪ 6698efad0 [DO NOT MERGE] Update Platform Security String to 2019-03-01 for oc-mr1-dev Bug:122541777
 ▪ 0252b84cf Make change and version bump to PPRL.190105.001
 ▪ 157c307f7 Version bump to PD2A.190113.002
 ▪ 143590e7d Make change and version bump to PD2A.190113.001
 ▪ 9da554085 Make change and version bump to PD2A.190112.001
 ▪ e0ea6a558 clean
 ▪ 2f19e51ae Merge platform/build into pi-platform-dev for January builds
 ▪ 7fe92cd09 Make change and version bump to PD2A.190111.002
 ▪ dfc786700 Merge remote-tracking branch 'aosp/pie-gsi' into pie
 ▪ 07fddc867 build: Add ability to use preinstalled vendor.img
 ▪ 7f091dffe sign_target_files: also replace fingerprint in system/vendor/build.prop
 ▪ 6c6c672e6 Use 0 compression when creating the target_files package
 ▪ 7ac1ae6e8 Revert "build: Allow devices to provide prebuilt vbmeta image"
 ▪ 70f3024c0 Revert "build: Allow building disabled vbmeta images in signing process"
 ▪ 9d9fbac03 envsetup: Make mgrep take a directory argument
 ▪ 18ee35141 Revert "Comment out assertions"
 ▪ 29d7593ad build: get rid of the sparse expand stuff
 ▪ 11e450838 Allow device tree to override audio_effects.conf
 ▪ 6106c1098 Do not use the default APN
 ▪ c622500ff Change havoc sepolicy path
 ▪ 8c377fbe3 remove dt_image.mk
 ▪ 2e9647209 Make change and version bump to PD2A.190111.001
 ▪ c67abafc7 Make change and version bump to PD2A.190110.001

 ▼ development/
 ▪ 37919f4f6 Snap for 5180536 from 38db7cf10596b743cf0c5e0c67809e384190f4e6 to pi-platform-release
 ▪ 86865adca Merge tag 'android-9.0.0_r31' into lineage-16.0-android-9.0.0_r31
 ▪ 8e09e639b make-key: Enforce PBEv1 password-protected signing keys
 ▪ 0d9797de8 Remove useless build warning

 ▼ device/havoc/sepolicy/
 ▪ dba7036 common: Improve label of I/O sched tuning nodes
 ▪ 097caf4 lineage: Address perf HAL denial with boost enabled
 ▪ e3b9cb7 Merge branch 'pie' of github.com:Havoc-OS/android_device_havoc_sepolicy into pie
 ▪ 0233ab5 update sepolicy for gemini
 ▪ c1fa3f7 common: Expand labeling of sysfs_vibrator nodes using genfscon
 ▪ 993b6d4 common: Allow init to relabel I/O sched tuning nodes
 ▪ 90308a3 common: Allow init to relabel I/O sched tuning nodes
 ▪ f3f4408 common: Label and allow init to write to I/O sched tuning nodes

 ▼ device/qcom/sepolicy/
 ▪ 45905c4c Merge tag 'LA.UM.7.5.r1-04100-8x96.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0
 ▪ 483694e5 Merge 2c59f0c719debc5aea62e32a6275134391cf6cca on remote branch
 ▪ ce3343b6 Merge "sepolicy: Add sepolicy rules for msm8996"
 ▪ a0bee207 sepolicy: Add sepolicy rules for msm8996
 ▪ 340ef5e2 Merge "sepolicy: allow camera process to access synx device node"
 ▪ dc46ea42 Merge 21e29f1982c6385907fbf713334fbd39e29bfbfb on remote branch
 ▪ a7f9afac sepolicy: allow camera process to access synx device node
 ▪ a67196dd Merge "Sepolicy: Allow permission to set brightness."
 ▪ 74c8caca Merge "Add label to the init.mlvm_boot.sh"
 ▪ e3fc755a Add label to the init.mlvm_boot.sh
 ▪ be42509d Merge "Fix hal_gnss sepolicy denial for sysfs file read permission"
 ▪ c3b731e2 Merge "sepolicy: Add permission for audio to read/write device latency node"
 ▪ e93237ed Sepolicy: Allow permission to set brightness.
 ▪ 7a044416 sepolicy: Add permission for audio to read/write device latency node
 ▪ 7a0cfcc3 Fix hal_gnss sepolicy denial for sysfs file read permission
 ▪ 0299f25e sepolicy: resolve avc denied issue
 ▪ dbf81a41 Merge 21e29f1982c6385907fbf713334fbd39e29bfbfb on remote branch
 ▪ 19c67945 sepolicy: Define security context for "ro.build.software.version"
 ▪ 2c59f0c7 Merge "sepolicy: add rules to access sensors power scripts from app"
 ▪ a3385d61 Merge 3142d144eff66a67fa326089f9010c53c80af83a on remote branch
 ▪ b98b1186 sepolicy:fix subsys,devfreq,coresight and fps path
 ▪ bff3ead5 vendor: trinket: Fix spmi devices address
 ▪ 51e2b947 Merge "sepolicy: Add SEPolicy for Power 1.2 HAL service"
 ▪ 66301719 Merge 3142d144eff66a67fa326089f9010c53c80af83a on remote branch
 ▪ 582d60b0 update msm8996 sepolicy
 ▪ b14718dc Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into 9.0
 ▪ 58a2e3c2 Merge branch 'lineage-16.0' of https://github.com/LineageOS/android_device_qcom_sepolicy into 9.0
 ▪ 82820d1d set context for twrp files
 ▪ 21e29f19 Merge "Adding dev nodes for qvrservice"
 ▪ 9c395d0e Adding dev nodes for qvrservice
 ▪ da676625 sepolicy: Allow system_server to read vendor camera props
 ▪ 8095e051 sepolicy: Allow all apps to read vendor camera props
 ▪ cc51d468 msm8996: Consider additional ssr nodes
 ▪ 5d696f8f msm8996: Label persist partition
 ▪ 0d4f8002 sepolicy : Correcting path regexp in file_context for  sysfs_usbpd_device
 ▪ 3142d144 Merge "sepolicy: conditionally stop CHRE daemon for SM6150"
 ▪ 3bd94f47 update file_contexts
 ▪ fb8e63eb sepolicy: allow vold to read persist dirs
 ▪ fbd6b7be sepolicy: Label mpctl_socket as data_file_type
 ▪ 86406aeb dpm: avoid file context denials.
 ▪ 8c4810cb Merge "Allow dnsmasq access to netd unix socket"
 ▪ 58635ac4 Merge "sepolicy: msm8937: Add sepolicy rules to support smb1360 on qm215"
 ▪ 4ec3c4c8 sepolicy: add rules to access sensors power scripts from app
 ▪ 0028ae10 Allow dnsmasq access to netd unix socket
 ▪ a07fc39b sepolicy: Add SEPolicy for Power 1.2 HAL service
 ▪ 53e137a2 sepolicy: msm8937: Add sepolicy rules to support smb1360 on qm215
 ▪ 818f7be6 Merge "sepolicy for face3d"
 ▪ 2e138786 Merge "Add rule for get/set prop of workload classifier property"
 ▪ 64121303 sepolicy for face3d

 ▼ device/qcom/sepolicy-legacy/
 ▪ 35ecc09 Display: Remove vendor property context for lcd density
 ▪ 2304abb legacy: Label some more sysfs_net
 ▪ 12e1f42 common: Allow webview_zygote to read /dev/ion
 ▪ 37d02ce sepolicy: legacy: add additional usb charging path label
 ▪ 78ac369 legacy: Label msm8916 sysfs_disk_stat
 ▪ 3cfd890 legacy: Label msm8916 sysfs_android_usb
 ▪ df16578 sepolicy: Add vendor prefix to FM properties
 ▪ 3507982 legacy: Label msm8916 sysfs_{battery,usb}_supply
 ▪ 5f7b17f common: relabel /sys/module/tcp_cubic for netmgrd access
 ▪ 7df6c91 common: grant cnss-daemon access to sysfs_net
 ▪ de12171 common: grant netmgrd access to sysfs_net nodes
 ▪ ddb2abf common: label /sys/devices/virtual/net/* as sysfs_net
 ▪ 9f8cc09 common: allow sensors HIDL HAL to access /dev/sensors
 ▪ 548752e common: grant DRM HIDL HAL ownership access to /data/{misc,vendor}/media/
 ▪ cbc73fd sepolicy: Add permissions for LCD brightness control
 ▪ d6b9b76 sepolicy: Allow mm-qcamerad use appdomain fd
 ▪ b7d2adf sepolicy: Label msm8974 devfreq sysfs
 ▪ d6e44fa sepolicy: Label msm_pm sysfs as sysfs_msm_perf
 ▪ 835d67c sepolicy: Label msm8974 leds-qpnp sysfs
 ▪ bcce192 sepolicy: Label msm8974 lcd-backlight sysfs
 ▪ 3f9a830 sepolicy: Label msm8974 sysfs_ssr_toggle
 ▪ a74e87f sepolicy: Label sysfs_android_usb
 ▪ e9302a4 sepolicy: Label sysfs_disk_stat nodes
 ▪ 181e026 sepolicy: Label more qpnp-charger sysfs as sysfs_battery_supply
 ▪ ae0bc3e Use new vendor_wifi_prop label for bluetooth_loader
 ▪ ceb9004 wcnss-service: Add sepolicy to access "vendor.wlan." property
 ▪ 3f0cdea sepolicy: Add vendor wifi prop in vendor partition access
 ▪ ff0a5d4 Revert "sepolicy: Allow wcnss_service to set wlan.driver properties"
 ▪ 86b27fa legacy: Label /sys/devices/mdp.0/caps
 ▪ 17deac3 sepolicy: Fix label of qpnp-charger sysfs
 ▪ 6ef96d7 sepolicy: Add type vendor_display_prop for legacy devices
 ▪ 2432980 sepolicy: Add additional restricted permissions to vendor_init

 ▼ device/xiaomi/gemini/
 ▪ 7fd09c9b6 Update google prebuilts to PQ2A.190205.003
 ▪ c2ba6a0cb Havoc 2.2
 ▪ c4e62999c Revert "Revert "gemini: removing AUDIO_OUTPUT_FLAG_RAW""
 ▪ 6a719e8c9 Android 9.0.0 Release 33 (PQ2A.190205.003)
 ▪ 143d38098 Android 9.0.0 Release 31 (PQ2A.190205.001)
 ▪ 1e9fad46d Revert "msm8996-common: readmac: Convert symbolic permissions to octal"
 ▪ b1abba912 Reset MSA/MSB capabilities for APQ targets.
 ▪ fc7b4e9ec caf tag: LA.UM.7.5.r1-04100-8x96.0
 ▪ ff593c4cb DragonTC clang version 9.0.0-20190131 (based on LLVM 9.0.0svn)
 ▪ b7c8c301e fix pico gapps 27012019 permissions
 ▪ 0a7f81a3d build Lawnchair
 ▪ 349f17262 gemini: Set MIUI 8.11.15 as the currently required firmware version
 ▪ 1d298618b gemini: Do not cleanup unused fingerprints
 ▪ b139f57c0 gemini: overlay: Update fingerprint dot location
 ▪ 8b708540c msm8996-common: gps: Disable xtwifi related services
 ▪ ff6b93f03 msm8996-common: readmac: Convert symbolic permissions to octal
 ▪ 8e746901d Update SDM blobs from LA.UM.7.5.r1-03700-8x96.0
 ▪ 7aee2432d update props & generate_gemini_info.sh
 ▪ d8fe8cb9a add toggle torch proximity check
 ▪ 4ce20496f clean and rebase tree
 ▪ d9e565ff4 proximity check for waking up from HOME key
 ▪ 1bf2cf90b caf tag: LA.UM.7.6.2.r1-05700-89xx.0
 ▪ d6c6ed1b6 update init.qcom.rc
 ▪ 9baa61254 fix keyhandler
 ▪ 95c845346 update privapp-permissions
 ▪ e200bea40 havoc 2.1

 ▼ external/arm-optimized-routines/
 ▪ 041ded7 fix
 ▪ 2561f08 Merge branch 'master' of https://android.googlesource.com/platform/external/arm-optimized-routines into pie
 ▪ f033957 Merge tag 'LA.UM.7.6.r1-04000-89xx.0' of https://source.codeaurora.org/quic/la/platform/external/arm-optimized-routines into pie
 ▪ 4ced35f Merge remote-tracking branch 'aosp/upstream-master' into arm-optimized-routines

 ▼ external/chromium-webview/
 ▪ 1ae1f17 Update X86/X64 Chromium webview to 69.0.3497.109
 ▪ fd4ffea Import Chromium webview

 ▼ external/f2fs-tools/
 ▪ befee77 Snap for 5180536 from eeedf7c7d04c223ea9e27674fd3809b5506ca5f4 to pi-platform-release
 ▪ f2dba35 Merge tag 'android-9.0.0_r31' into lineage-16.0-android-9.0.0_r31

 ▼ external/fsck_msdos/
 ▪ ba60a1a fsck_msdos: Build static lib for recovery

 ▼ external/google/
 ▪ 1388d23 Bypass screen off adjustment and go back to 0-8 for sensitivity
 ▪ 03d1ea7 Elmyra: Move the manifest here
 ▪ 25e430b Remove unused resources
 ▪ 0a5cc17 Elmyra: Bring in the resources
 ▪ 2d581d9 Active edge Settings 5/?
 ▪ aec691a Partial removal of weird cycles in ElmyraService
 ▪ 9588521 Properly cleanup CHREGestureSensor
 ▪ c79ccd6 Merge branch 'dev'
 ▪ be11ed7 Clean up gesture configuration in preparation for user config
 ▪ 3d633d7 Move calls to System.Secure instead
 ▪ c754003 Switch to the assist manager for the Assistant action
 ▪ d33c098 Remove various dumps methods, the sensor works just fine
 ▪ d1cf98a JNIGestureSensor isn't used anymore
 ▪ 38bf166 Cleanup UserContentObserver
 ▪ e86e308 Merge branch 'dev'
 ▪ 03c608c Animation and vibration: Ensure it respects 'no action' in multiuser
 ▪ 066537f Add more gestures
 ▪ a74565b Disable navbar animation and vibration with no action
 ▪ 41a9448 Remove useless qualifiers for other classes
 ▪ cc5ad4f Google's protobuf isn't needed
 ▪ c90ced9 Last synthetic lambda conversions
 ▪ 4a66a7c Oh, our CustomAction class is now alone
 ▪ 63723a0 Move and convert "syntethic" lambdas down Action
 ▪ 73e5e8c Remove OPA classes and references
 ▪ 409d018 Remove SetupWizard action and gate
 ▪ 27f8d44 Delete classes CameraAction and CameraVisibility
 ▪ 5aff109 Convert jank lambdas to clean anonymous classes
 ▪ 9f16f4b Finally add Google assistant action
 ▪ 49491dc Elmyra: clean-up a bunch of classes with automated tools
 ▪ 12fa980 Active edge settings 2/?
 ▪ e0a031d Elmyra: Move to external repo

 ▼ external/gptfdisk/
 ▪ 4a15cd1 gptfdisk: Provide sgdisk_read for direct reads of the partition table

 ▼ external/icu/
 ▪ c6aa8e95a Snap for 5180536 from de2840610207b58bede6041532b5db77173aad33 to pi-platform-release
 ▪ 403985900 Snap for 5285806 from f32e1e66ad894d71466b9854826262ca51f34800 to pi-qpr3-release
 ▪ f32e1e66a DO NOT MERGE: Fix Morocco to use rearguard format correctly in ICU.
 ▪ feb17e869 DO NOT MERGE: Update Android ICU tzdata from 2018g to 2018i.
 ▪ 0d011198e DO NOT MERGE: Fix Morocco to use rearguard format correctly in ICU.
 ▪ 9e0ab1daa DO NOT MERGE: Update Android ICU tzdata from 2018g to 2018i.
 ▪ ca0fde0a8 Revert "Update Android ICU tzdata from 2018g to 2018i"

 ▼ external/libavc/
 ▪ 46680e4 decoder: Signal IVD_RES_CHANGED error for change in crop params

 ▼ external/nano/
 ▪ 56181896 prompt: trim a double-width character at the screen's edge
 ▪ cf634d1a browser: show the ^G item again in the help lines
 ▪ edc0d628 display: properly trim double-width characters at the edit window's edge
 ▪ 6470106e docs: mention nano's major features directly instead of referring
 ▪ b8954021 tweaks: add two comments, and reduce the scope of another variable
 ▪ 77c60201 tweaks: reduce the scope of a variable, and rename it
 ▪ 2482cfca build: eradicate the --disable-wrapping-as-root configure option
 ▪ 946755a3 options: disable hard-wrapping and automatic newlines by default
 ▪ 98b1f8f0 options: stop recognizing and ignoring -b, -e, -f, -j, and -q
 ▪ 38e3318e tweaks: reword the description of the disadvantages of Pico
 ▪ 6aad99bd docs: stop implying that nano wants to be fully compatible with Pico
 ▪ 4b8bd27d bindings: change the action of <Alt+Up>/<Alt+Down> to 'scroll linewise'
 ▪ 757f558f tweaks: renumber some FAQ items, to compensate for the deleted ones
 ▪ 1f9283ec docs: remove from the FAQ some items that are no longer relevant
 ▪ 2eb19605 docs: mention that 'quotestr' enables the rewrapping of comment blocks
 ▪ 4bf650f0 tweaks: condense a comment, and drop two others
 ▪ 63db58cb docs: adjust for the enhancement of the default quoting regex
 ▪ c5a72103 justify: extend the quoting regex, to cover more types of comments
 ▪ da4b7e43 files: retain a Shift-selected region when switching between buffers
 ▪ e771503e tweaks: adjust indentation after the previous commit
 ▪ 194d1858 input: properly handle <Escape>s followed by a shifted Meta+letter
 ▪ e1a6f58d startup: check that a backup directory is valid also when backups are off

 ▼ external/ntfs-3g/
 ▪ a1129548 ntfs-3g: Add static libs for recovery

 ▼ external/openssh/
 ▪ 3d896c15 upstream: when checking that filenames sent by the server side
 ▪ 318e4f85 upstream: syslog when connection is dropped for attempting to run a
 ▪ 2ff2e196 don't set $MAIL if UsePam=yes
 ▪ 03e92dd2 use same close logic for stderr as stdout
 ▪ 8c53d409 upstream: Adapt code in the non-USE_PIPES codepath to the new packet
 ▪ 7a7fdca7 upstream: fix NULL-deref crash in PKCS#11 code when attempting
 ▪ cac302a4 upstream: Remove obsolete "Protocol" from commented out examples. Patch
 ▪ 483b3b63 upstream: Save connection timeout and restore for 2nd and
 ▪ 5f004620 upstream: Add authors for public domain sntrup4591761 code;
 ▪ 2c21b75a upstream: add -T to usage();
 ▪ 19a0f052 upstream: The test sshd_config in in $OBJ.
 ▪ 8fe25440 upstream: Remove leftover debugging.
 ▪ e30d3236 upstream: Enable ssh-dss for the agent test. Disable it for the
 ▪ ffdde469 upstream: Count the number of key types instead of assuming there
 ▪ 1d05b4ad Cygwin: only tweak sshd_config file if it's new, drop creating sshd user
 ▪ 89843de0 Cygwin: Change service name to cygsshd
 ▪ 2a9b3a2c upstream: Generate all key supported key types and enable for keyscan
 ▪ 391ffc4b upstream: check in scp client that filenames sent during
 ▪ c2c18a39 upstream: make ssh-keyscan return a non-zero exit status if it
 ▪ 05b9a466 upstream: Accept the host key fingerprint as a synonym for "yes"
 ▪ bdc6c63c upstream: Have progressmeter force an update at the beginning and
 ▪ 258e6ca0 upstream: Check for both EAGAIN and EWOULDBLOCK. This is a no-op
 ▪ 281ce042 upstream: Always initialize 2nd arg to hpdelim2. It populates that
 ▪ d05ea255 upstream: Remove support for obsolete host/port syntax.
 ▪ 177d6c80 upstream: Remove duplicate word. bz#2958, patch from jjelen at
 ▪ be3e6cba upstream: Remove 3 as a guess for possible generator during moduli
 ▪ 8976f1c4 upstream: Sanitize scp filenames via snmprintf. To do this we move
 ▪ 6249451f For broken read/readv comparisons, poll(RW).
 ▪ 5cb503df Include unistd.h for strmode().
 ▪ f236ca27 Also undef SIMPLEQ_FOREACH_SAFE.
 ▪ be063945 upstream: allow auto-incrementing certificate serial number for certs
 ▪ 851f8032 upstream: move a bunch of global flag variables to main(); make the
 ▪ 2265402d depend
 ▪ 2c223878 upstream: switch mainloop from select(2) to poll(2); ok deraadt@
 ▪ bb956eaa upstream: pass most arguments to the KEX hash functions as sshbuf
 ▪ d691588b upstream: backoff reading messages from active connections when the
 ▪ f99ef8de upstream: add -m to usage(); reminded by jmc@
 ▪ 41923ce0 upstream: Correct some bugs in PKCS#11 token PIN handling at
 ▪ 2162171a upstream: Support keys that set the CKA_ALWAYS_AUTHENTICATE by
 ▪ 7a2cb18a upstream: Mention that configuration for the destination host is
 ▪ ecd2f33c upstream: Include -m in the synopsis for a few more commands that
 ▪ ff5d2cf4 upstream: print the full pubkey being attempted at loglevel >=
 ▪ 180b520e upstream: clarify: ssh-keygen -e only writes public keys, never
 ▪ c45616a1 upstream: mention the new vs. old key formats in the introduction
 ▪ fd8eb138 upstream: tweak previous;
 ▪ 68e924d5 upstream: Forgot to add -J to the synopsis.
 ▪ 622dedf1 upstream: Add a -J option as a shortcut for -o Proxyjump= to scp(1)
 ▪ c882d746 Allow building against OpenSSL dev (3.x) version.
 ▪ d5520393 typo
 ▪ 2de9cec5 add missing header
 ▪ 533cfb01 upstream: switch sntrup implementation source from supercop to
 ▪ d50ab3cd new files need includes.h
 ▪ c7670b09 upstream: add "-v" flags to ssh-add and ssh-pkcs11-helper to turn up
 ▪ 49d8c8e2 upstream: adapt to changes in KEX APIs and file removals
 ▪ 35ecc53a upstream: adapt to changes in KEX API and file removals
 ▪ 7d69aae6 upstream: adapt to bignum1 API removal and bignum2 API change
 ▪ beab553f upstream: remove hack to use non-system libcrypto
 ▪ 4dc06bd5 depend
 ▪ 70edd73e upstream: fix reversed arguments to kex_load_hostkey(); manifested as
 ▪ f1185abb upstream: forgot to cvs add this file in previous series of commits;
 ▪ 7bef390b upstream: nothing shall escape this purge
 ▪ aaca72d6 upstream: rename kex->kem_client_pub -> kex->client_pub now that
 ▪ 70867e1c upstream: merge kexkem[cs] into kexgen
 ▪ 71e67fff upstream: pass values used in KEX hash computation as sshbuf
 ▪ 4b83e2a2 upstream: remove kex_derive_keys_bn wrapper; no unused since the
 ▪ 92dda34e upstream: use KEM API for vanilla ECDH
 ▪ b7235721 fixup missing ssherr.h
 ▪ 9c9c97e1 upstream: use KEM API for vanilla DH KEX
 ▪ 2f6a9ddb upstream: use KEM API for vanilla c25519 KEX
 ▪ dfd59161 upstream: Add support for a PQC KEX/KEM:
 ▪ b1b2ff4e upstream: factor out kex_verify_hostkey() - again, duplicated
 ▪ bb39bafb upstream: factor out kex_load_hostkey() - this is duplicated in
 ▪ dec5e9d3 upstream: factor out kex_dh_compute_key() - it's shared between
 ▪ e93bd98e upstream: factor out DH keygen; it's identical between the client
 ▪ 5ae3f6d3 upstream: save the derived session id in kex_derive_keys() rather
 ▪ 7be8572b upstream: Make sshpkt_get_bignum2() allocate the bignum it is
 ▪ 803178bd upstream: remove obsolete (SSH v.1) sshbuf_get/put_bignum1
 ▪ f3ebaffd upstream: fix all-zero check in kexc25519_shared_key
 ▪ 9d1a9771 upstream: - -T was added to the first synopsis by mistake - since
 ▪ 2f0bad2b Make --with-rpath take a flag instead of yes/no.
 ▪ 23490a6c fix previous test
 ▪ b6dd3277 Wrap ECC static globals in EC_KEY_METHOD_NEW too.
 ▪ b2eb9db3 pass TEST_SSH_SSHPKCS11HELPER to regress tests
 ▪ ba58a529 make agent-pkcs11 search harder for softhsm2.so
 ▪ 662be40c upstream: always print the caller's error message in ossl_error(),
 ▪ ce46c3a0 upstream: get the ex_data (pkcs11_key object) back from the keys at
 ▪ 0a5f2ea3 upstream: GSSAPI code got missed when converting to new packet API
 ▪ 2efcf812 Fix -Wunused when compiling PKCS#11 without ECDSA
 ▪ 3c0c657e upstream: allow override of ssh-pkcs11-helper binary via
 ▪ 760ae37b upstream: adapt agent-pkcs11.sh test to softhsm2 and add support
 ▪ b2ce8b31 upstream: add "extra:" target to run some extra tests that are not
 ▪ 63297641 upstream: use ECDSA_SIG_set0() instead of poking signature values into
 ▪ 5de6ac2b remove HAVE_DLOPEN that snuck in
 ▪ e2cb445d conditionalise ECDSA PKCS#11 support
 ▪ fcb1b093 upstream: we use singleton pkcs#11 RSA_METHOD and EC_KEY_METHOD
 ▪ 6529409e upstream: KNF previous; from markus@
 ▪ 58622a8c upstream: use OpenSSL's RSA reference counting hooks to
 ▪ f118542f upstream: make the PKCS#11 RSA code more like the new PKCS#11
 ▪ 445cfce4 upstream: fix leak of ECDSA pkcs11_key objects
 ▪ 8a246758 upstream: use EVP_PKEY_get0_EC_KEY() instead of direct access of
 ▪ 24757c1a upstream: cleanup PKCS#11 ECDSA pubkey loading: the returned
 ▪ 749aef30 upstream: cleanup unnecessary code in ECDSA pkcs#11 signature
 ▪ 0c50992a upstream: cleanup pkcs#11 client code: use sshkey_new in instead
 ▪ 854bd867 upstream: allow override of the pkcs#11 helper binary via
 ▪ 93f02107 upstream: add support for ECDSA keys in PKCS#11 tokens
 ▪ aa22c20e upstream: add option to test whether keys in an agent are usable,
 ▪ a36b0b14 upstream: Fix BN_is_prime_* calls in SSH, the API returns -1 on
 ▪ ec4776bb upstream: DH-GEX min value is now specified in RFC8270. ok djm@
 ▪ c90a7928 Check for cc before gcc.
 ▪ 9b655dc9 last bits of old packet API / active_state global
 ▪ 3f0786bb remove PAM dependencies on old packet API
 ▪ 08f66d9f remove vestiges of old packet API from loginrec.c
 ▪ c327813e depend
 ▪ 135e302c upstream: fix error in refactor: use ssh_packet_disconnect() instead of
 ▪ 245c6a0b upstream: remove last traces of old packet API!
 ▪ 04c091fc upstream: remove last references to active_state
 ▪ ec00f918 upstream: convert monitor.c to new packet API
 ▪ 6350e031 upstream: convert sshd.c to new packet API
 ▪ a5e2ad88 upstream: convert session.c to new packet API
 ▪ 3a00a921 upstream: convert auth.c to new packet API
 ▪ 7ec5cb4d upstream: convert serverloop.c to new packet API
 ▪ 64c9598a upstream: convert the remainder of sshconnect2.c to new packet
 ▪ bc5e1169 upstream: convert the remainder of clientloop.c to new packet API
 ▪ 5ebce136 upstream: convert auth2.c to new packet API
 ▪ 172a592a upstream: convert servconf.c to new packet API
 ▪ 8cc7a679 upstream: convert channels.c to new packet API
 ▪ 06232038 upstream: convert sshconnect.c to new packet API
 ▪ 25b2ed66 upstream: convert ssh.c to new packet API
 ▪ e3128b38 upstream: convert mux.c to new packet API
 ▪ ed1df722 upstream: convert sshconnect2.c to new packet API
 ▪ 23f22a4a upstream: convert clientloop.c to new packet API
 ▪ ad60b117 upstream: allow sshpkt_fatal() to take a varargs format; we'll
 ▪ 0fa174eb upstream: begin landing remaining refactoring of packet parsing
 ▪ 4ae7f80d upstream: Print an \r in front of the password prompt so parts of
 ▪ a6258e5d Add minimal fchownat and fchmodat implementations.
 ▪ 091093d2 Add a minimal implementation of utimensat().
 ▪ 60964402 upstream: regress bits for banner processing refactor (this test was
 ▪ f47d72dd upstream: tun_fwd_ifnames variable should b
 ▪ 943d0965 upstream: include time.h for time(3)/nanosleep(2); from Ian
 ▪ dbb4dec6 upstream: many of the global variables in this file can be made static;
 ▪ 60d8c84e upstream: Add "-h" flag to sftp chown/chgrp/chmod commands to
 ▪ dbbc7e0e upstream: add support for a "lsetstat@openssh.com" extension. This

 ▼ external/perfetto/
 ▪ 358eed14 Merge remote-tracking branch 'AOSP/pie-gsi' into pie

 ▼ external/skia/
 ▪ 6d8eb3c792 Snap for 5180536 from 68d9148bf8426539a323adb3a7b6cb422101ae0d to pi-platform-release
 ▪ 5b3adf422c Make sure we mark Plots in use for all regenerate cases
 ▪ 40a3402492 Merge remote-tracking branch 'AOSP/pie-gsi' into pie
 ▪ 96660a66af Merge tag 'android-9.0.0_r33' into pie
 ▪ 33a1b14eeb Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/external/skia into HEAD
 ▪ 11d31401bc Snap for 5280131 from e69570de6ea5b180c57858c844bcf828dfc5cd98 to p-keystone-qcom-release
 ▪ e69570de6e Merge SPL-2019-01-05
 ▪ ad8db00fbc external/skia: Take Fast Jpeg Decoding Path
 ▪ 7ab7f34c16 skia: Silence a few warnings for cpp
 ▪ 9bf9e75094 skia: Clean up -Wextra-semi-stmt warnings
 ▪ fd2fed1de4 libskia: Build using ThinLTO
 ▪ ffee60abcc fGpu is null when GrGpuResource::release
 ▪ ad11440a43 Fix native crash when some png bitmap decoded
 ▪ 6b8bf6ad63 ARGB Blitter:  Remove unused variable
 ▪ b3b274845b skia: Use std::move() to prevent unnecessary copying
 ▪ ef3e29ebf9 Optimize the for loop in onGetYUV8Planes
 ▪ c49e6c60ec Skia performance optimize for bitmap

 ▼ external/sqlite/
 ▪ 81b4df7 sqlite: upgrade to SQLite 3.27.1
 ▪ 171e89a sqlite: upgrade to SQLite 3.27.0
 ▪ 15d4747 sqlite: Remove useless function of tokenize

 ▼ external/vim/
 ▪ 18c5632ca patch 8.1.0885: test for restricted hangs on MS-Windows GUI
 ▪ af630d4f7 patch 8.1.0884: double check for bsd systems
 ▪ 54d6fe5e6 patch 8.1.0883: missing some changes for Ex commands
 ▪ 1aa43755e patch 8.1.0882: checking for FEAT_MBYTE which doesn't exist anymore
 ▪ 8c62a08fa patch 8.1.0881: can execute shell commands in rvim through interfaces
 ▪ c6ddce3f2 patch 8.1.0880: MS-Windows: inconsistent selection of winpty/conpty
 ▪ 0036201a1 patch 8.1.0879: MS-Windows: temp name encoding can be wrong
 ▪ a02e3f65c patch 8.1.0878: test for has('bsd') fails on some BSD systems
 ▪ ee8188fc7 patch 8.1.0877: new buffer used every time the quickfix window is opened
 ▪ 2a78b7c70 patch 8.1.0876: completion match not displayed when popup menu is not shown
 ▪ 71b13e92a patch 8.1.0875: not all errors of marks and findfile()/finddir() are tested
 ▪ 94688b8a2 Add missing matchit file.
 ▪ 9c46efd7d patch 8.1.0874: using old style comments in new file
 ▪ 970076468 patch 8.1.0873: list if distributed files does not include matchit autoload
 ▪ 34a587457 patch 8.1.0872: confusing condition
 ▪ 314dd79ca Update runtime files.
 ▪ 63d1fea81 patch 8.1.0871: build error when building with Ruby 2.6.0
 ▪ aa5df7e31 patch 8.1.0870: Vim doesn't use the new ConPTY support in Windows 10
 ▪ 01a6c2169 patch 8.1.0869: Travis CI script is too complicated
 ▪ 889da2f24 patch 8.1.0868: crash if triggering garbage collector after a function call
 ▪ 65951258d patch 8.1.0867: cannot build Python interface with Python 2.4
 ▪ 1c321dcee patch 8.1.0866: build file dependencies are outdated
 ▪ 895d966e3 patch 8.1.0865: when 'listchars' only contains "nbsp:X" it does not work
 ▪ 375e33900 patch 8.1.0864: cannot have a local value for 'scrolloff' and 'sidescrolloff'
 ▪ b3051ce82 patch 8.1.0863: cannot see what signal caused a job to end
 ▪ 221cd9f4d patch 8.1.0862: no verbose version of character classes
 ▪ 60f807b3f patch 8.1.0861: building with MinGW and static libc doesn't work
 ▪ 77255cab7 patch 8.1.0860: debug lines left in the code
 ▪ c45eb770a patch 8.1.0859: "%v" in 'errorformat' does handle multi-byte characters
 ▪ ce655743b patch 8.1.0858: 'indentkeys' and 'cinkeys' defaults are different
 ▪ 4b47162cc patch 8.1.0857: indent functionality is not separated
 ▪ bbb5f8d4c patch 8.1.0856: when scrolling a window the cursorline is not always updated
 ▪ af703585a patch 8.1.0855: cannot build xxd with MSVC 10
 ▪ d8c56a0d2 patch 8.1.0854: xxd does not work with more than 32 bit addresses
 ▪ cbbd0f657 patch 8.1.0853: options test fails on Mac
 ▪ ed71ed37b patch 8.1.0852: findfile() and finddir() are not properly tested
 ▪ 8d4ce56a1 patch 8.1.0851: feedkeys() with "L" does not work properly
 ▪ 98ad1e17c patch 8.1.0850: test for 'backupskip' is not correct
 ▪ c07ff5c60 patch 8.1.0849: cursorline highlight is not always updated
 ▪ b191be2f0 patch 8.1.0848: cannot build with Ruby 1.8
 ▪ 9172d23d0 patch 8.1.0847: may use terminal after it was cleaned up
 ▪ 39536dd55 patch 8.1.0846: not easy to recognize the system Vim runs on
 ▪ 2a4857a1f patch 8.1.0845: having job_status() free the job causes problems
 ▪ 50948e4ac patch 8.1.0844: when timer fails test will hang forever
 ▪ e0de2164f patch 8.1.0843: memory leak when running "make test_cd"
 ▪ cb908a813 patch 8.1.0842: getchar_zero test fails on MS-Windows
 ▪ 2339fa335 patch 8.1.0841: travis config to get Lua on MacOS is too complicated
 ▪ 12dfc9eef patch 8.1.0840: getchar(0) never returns a character in the terminal
 ▪ f58d81a18 patch 8.1.0839: when using VTP wrong colors after a color scheme change
 ▪ dec01206b patch 8.1.0838: compiler warning for type conversion
 ▪ 26d982185 patch 8.1.0837: timer interrupting cursorhold and mapping not tested
 ▪ 346d2a359 patch 8.1.0836: user completion test can fail on MS-Windows
 ▪ 3e9d4d85c patch 8.1.0835: GUI build fails on MS-Windows
 ▪ e40b9d47b patch 8.1.0834: GUI may wait too long before dealing with messages
 ▪ d93090f41 patch 8.1.0833: memory leak when jumps output is filtered
 ▪ 2e0500921 patch 8.1.0832: confirm() is not tested
 ▪ 0eb220c03 patch 8.1.0831: xxd test fails if man page has dos fileformat
 ▪ e3d065454 patch 8.1.0830: test leaves directory behind on MS-Windows
 ▪ d39e275b5 patch 8.1.0829: when 'hidden' is set session creates extra buffers
 ▪ 6aba96dd5 patch 8.1.0828: still using FEAT_VIRTUALEDIT
 ▪ 2a953fcf1 Updated runtime files.
 ▪ 8e59a1e12 patch 8.1.0827: missing dependency in Makefile
 ▪ 29ddebef4 patch 8.1.0826: too many #ifdefs
 ▪ 3e460fd8b patch 8.1.0825: code for autocommands is mixed with file I/O code
 ▪ 1ecc5e4a9 patch 8.1.0824: SunOS/Solaris has a problem with ttys
 ▪ 203651b9b patch 8.1.0823: not sufficient testing of xxd
 ▪ cb574f415 patch 8.1.0822: peeking and flushing output slows down execution
 ▪ 970f5d39f patch 8.1.0821: xxd "usage" output and other arguments not tested
 ▪ e295609be patch 8.1.0820: test for sending large data over channel sometimes fails
 ▪ 865767126 patch 8.1.0819: a failed assert with a long string is hard to read
 ▪ 240583869 patch 8.1.0818: MS-Windows: cannot send large data with ch_sendraw()
 ▪ 99531a760 patch 8.1.0817: ":=" command is not tested
 ▪ 681b6bc86 patch 8.1.0816: test for 'runtimepath' in session fails on MS-Windows
 ▪ 5e66b42aa patch 8.1.0815: dialog for file changed outside of Vim not tested
 ▪ ed18f2c03 patch 8.1.0814: :mksession cannot handle a very long 'runtimepath'
 ▪ 0566e891f patch 8.1.0813: FileChangedShell not sufficiently tested
 ▪ 9ba6117de patch 8.1.0812: Unicode 16 feature is not useful
 ▪ 30276f2be patch 8.1.0811: too many #ifdefs
 ▪ 264b74fa5 patch 8.1.0810: too many #ifdefs
 ▪ a12a161b8 patch 8.1.0809: too many #ifdefs
 ▪ 091806d6f patch 8.1.0808: MS-Windows: build error with GUI
 ▪ 9e79ccbe9 patch 8.1.0807: session test fails on MS-Windows
 ▪ fc3abf47f patch 8.1.0806: too many #ifdefs
 ▪ 135059724 patch 8.1.0805: too many #ifdefs
 ▪ 4b9e91f0b patch 8.1.0804: crash when setting v:errmsg to empty list
 ▪ ad36a3588 patch 8.1.0803: session file has problem with single quote in file name
 ▪ a5be9b624 patch 8.1.0802: negative index doesn't work for Blob
 ▪ fb1199d93 patch 8.1.0801: MinGW: no hint that tests fail because of small terminal
 ▪ 4456ab527 patch 8.1.0800: may use a lot of memory when a function refers itself
 ▪ cfc15237a patch 8.1.0799: calling deleted function; test doesn't work on Mac
 ▪ dd29ea180 patch 8.1.0798: changing a blob while iterating over it works strangely
 ▪ bf821bccf patch 8.1.0797: error E898 is used twice
 ▪ 31faed60b patch 8.1.0796: MS-Windows 7: problem with named pipe on channel
 ▪ f88af6e67 patch 8.1.0795: cannot build without popup menu
 ▪ 82a12468b patch 8.1.0794: white space before " -Ntabmove" causes problems
 ▪ 0d17f0d1c patch 8.1.0793: incorrect error messages for functions that take a Blob
 ▪ 9e26f7d31 patch 8.1.0792: bad display if opening cmdline window from Insert completion
 ▪ 563bbeabc patch 8.1.0791: a few compiler warnings on VMS
 ▪ 57a6bf056 patch 8.1.0790: code for creating tabpages in session is too complex
 ▪ 555de4e3b patch 8.1.0789: sourcing a session sets v:errmsg
 ▪ b2148f586 patch 8.1.0788: cannot build with tiny features
 ▪ edce7420d patch 8.1.0787: compiler warning for unused function
 ▪ 10772307c patch 8.1.0786: ml_get error when updating the status line
 ▪ 113e10721 patch 8.1.0785: depending on the configuration some functions are unused
 ▪ 1f20daa1d patch 8.1.0784: messy indent in if statement
 ▪ 63c0ccd2b patch 8.1.0783: compiler warning for signed/unsigned
 ▪ 2d951a486 patch 8.1.0782: Win32: cursor blinks when Vim is not active
 ▪ a502caab8 patch 8.1.0781: build error when using if_xcmdsrv.c
 ▪ e25bbc3b2 patch 8.1.0780: terminal test fails on Mac
 ▪ 32526b3c1 patch 8.1.0779: argument for message functions is inconsistent
 ▪ d383c92ec patch 8.1.0778: terminal test fails on MS-Windows
 ▪ b091f30bf patch 8.1.0777: Win32: using pipes for channel does not work well
 ▪ b2e54b009 patch 8.1.0776: Travis does not build a version without GUI on Linux
 ▪ 2bf60b300 patch 8.1.0775: matching too many files as zsh
 ▪ 05a2907cd patch 8.1.0774: VMS build is missing the blob file
 ▪ 987411db9 patch 8.1.0773: not all crypt code is tested
 ▪ 0314236aa patch 8.1.0772: the sign_define_by_name() function is too long
 ▪ 147e7d0ca patch 8.1.0771: some shell filetype patterns end in a star
 ▪ 1ac56c2d1 patch 8.1.0770: inconsistent use of ELAPSED_FUNC
 ▪ 3020ccb11 patch 8.1.0769: :stop is covered in two tests
 ▪ ae654385d patch 8.1.0768: updating completions may cause the popup menu to flicker
 ▪ c771bf901 patch 8.1.0767: when deleting lines at the bottom signs are misplaced
 ▪ 88c86eb75 patch 8.1.0766: various problems when using Vim on VMS
 ▪ 4131fd550 patch 8.1.0765: string format of a Blob can't be parsed back
 ▪ 6e0b6a0be patch 8.1.0764: list of distributed files is outdated
 ▪ d09091d49 Update runtime files.
 ▪ bb1969b6a patch 8.1.0763: nobody is using the Sun Workshop support
 ▪ e40742526 patch 8.1.0762: compiler warning
 ▪ e299bbdf6 patch 8.1.0761: default value for brief_wait is wrong
 ▪ 617d7ef04 patch 8.1.0760: no proper test for using 'termencoding'
 ▪ 83a52171b patch 8.1.0759: showing two characters for tab is limited
 ▪ 500f36108 patch 8.1.0758: font number is always one instead of the actual
 ▪ d89682477 patch 8.1.0757: not enough documentation for Blobs
 ▪ 3d28b58c5 patch 8.1.0756: copy() does not make a copy of a Blob
 ▪ 2ea773b46 patch 8.1.0755: error message for get() on a Blob with invalid index
 ▪ 177ab9e02 patch 8.1.0754: preferred column is lost when setting 'cursorcolumn'
 ▪ b5443cc46 patch 8.1.0753: printf format not checked for semsg()
 ▪ 8e481e8df patch 8.1.0752: one more compiler warning for signed/unsigned string
 ▪ 6057ed472 patch 8.1.0751: some regexp errors are not tested
 ▪ 8144acbec patch 8.1.0750: when the last sign is deleted the signcolumn may remain
 ▪ 6acc79f5d patch 8.1.0749: error message contains garbage
 ▪ 1be45b2ea patch 8.1.0748: using sprintf() instead of semsg()
 ▪ ce9d50df0 patch 8.1.0747: map() with a bad expression doesn't give an error
 ▪ bbee8d512 patch 8.1.0746: highlighting not updated with conceal and 'cursorline'
 ▪ 99b1272f8 patch 8.1.0745: compiler warnings for signed/unsigned string
 ▪ b1443b480 patch 8.1.0744: compiler warnings for signed/unsigned strings
 ▪ f9e3e09fd patch 8.1.0743: giving error messages is not flexible
 ▪ 05500ece6 patch 8.1.0742: not all Blob operations are tested
 ▪ 8c8b8bb56 patch 8.1.0741: viminfo with Blob is not tested
 ▪ 8309b0559 patch 8.1.0740: Tcl test fails
 ▪ 81b1ba4be patch 8.1.0739: text objects in not sufficiently tested
 ▪ ecc8bc482 patch 8.1.0738: using freed memory, for loop over blob leaks memory
 ▪ e519dfd71 patch 8.1.0737: compiler warning for uninitialized variable
 ▪ c0f5a78c1 patch 8.1.0736: code for Blob not sufficiently tested
 ▪ 6e5ea8d2a patch 8.1.0735: cannot handle binary data
 ▪ e3c74d249 patch 8.1.0734: the hlsearch state is not stored in a session file
 ▪ 2be7cb73f patch 8.1.0733: too many #ifdefs for the multi-byte feature
 ▪ ea56e167c patch 8.1.0732: cannot build without the eval feature
 ▪ 5f6b379ff patch 8.1.0731: JS encoding does not handle negative infinity
 ▪ ec9d3001c patch 8.1.0730: compiler warning for get_buf_arg() unused
 ▪ 2b6185287 patch 8.1.0729: there is a SourcePre autocommand event but not a SourcePost
 ▪ c3c315875 patch 8.1.0728: cannot avoid breaking after a single space.
 ▪ 44a7db4ff patch 8.1.0727: compiler warning for sprintf() argument
 ▪ 535d5b653 patch 8.1.0726: redrawing specifically for conceal feature
 ▪ 465e8b598 patch 8.1.0725: conceal mode is not completely tested
 ▪ 46fd6bf2b patch 8.1.0724: build for MinGW fails
 ▪ ec50401e1 patch 8.1.0723: cannot easily run specific test when in src/testdir
 ▪ 977239ef5 patch 8.1.0722: cannot build without the virtualedit feature
 ▪ 429ab1761 patch 8.1.0721: conceal mode is not sufficiently tested
 ▪ 5b69c22fd patch 8.1.0720: cannot easily change the current quickfx list index
 ▪ 870ba5f6d patch 8.1.0719: too many #ifdefs
 ▪ 402385a7f patch 8.1.0718: a couple compiler warnings
 ▪ 6b7b7190a patch 8.1.0717: there is no function for the ":sign jump" command
 ▪ cee9bc2e3 patch 8.1.0716: get warning message when 'completefunc' returns nothing
 ▪ 6f7e555f7 patch 8.1.0715: superfluous call to redraw_win_later()
 ▪ c95152294 patch 8.1.0714: unessesary #if lines in GTK code
 ▪ 24877cf22 patch 8.1.0713: images for NSIS take up too much space

 ▼ external/vixl/
 ▪ 187fa018 libvixl: Do not mark the module as VNDK or VNDK-SP

 ▼ external/wpa_supplicant_8/
 ▪ e3a0c6a9 Merge 73e53c71f1c107d3f19afa324a8f775fdbe71a5e on remote branch
 ▪ 73e53c71 Snap for 5255917 from d35a3df1b355d1fd7a2bf3188145cc9de4267433 to p-keystone-qcom-release
 ▪ d35a3df1 Merge "hostapd(hidl): Reset ht_capab, vht_oper_chwidth before set hw_mode" into p-keystone-qcom
 ▪ 10ea6019 Snap for 5239956 from e7001663897430d92042cc9515d341c2b2d5c0b0 to p-keystone-qcom-release
 ▪ 388e8c2b wpa_supplicant(hidl): Set 'ieee80211w' when PMF required
 ▪ e7001663 Merge "nl80211: Do not ignore disconnect event in case of !drv->associated" into p-keystone-qcom
 ▪ 6c8f4fb4 Snap for 5235762 from d5bccee92f8dea9499e8f7a627a410107c064be7 to p-keystone-qcom-release
 ▪ 9a980770 hostapd(hidl): Reset ht_capab, vht_oper_chwidth before set hw_mode

 ▼ frameworks/av/
 ▪ 993d76204d Snap for 5180536 from dba05b7c7c2782c88056a3f53615a66a6945426e to pi-platform-release
 ▪ ec4035e41a Merge tag 'android-9.0.0_r33' into pie
 ▪ cdbd8e1d4e CameraService: Fix missing torch state callback
 ▪ 04be413c84 libstagefright: Allow HFR-60 in HAL-3 recording
 ▪ a505431f2a stagefrightrecorder: don't modify timeOffset in surface source case
 ▪ 8d1c4e3fb4 cameraservice: Lazy loading of audio files can speed up camera startup
 ▪ 044bb9ca31 Camera: Add extensions to CameraClient
 ▪ 242b91f6c4 Revert "Camera: Add support for ZSL burst mode."
 ▪ 062e821933 Camera: CameraHardwareInterface: Releasing mHIDLMemoryMapLock in QdataCallback
 ▪ 6b605996ed Camera:CameraService: Added lock on mHIDLMemPoolId in QDataCallback..
 ▪ eb634efb87 Camera: Add support for preview frame fd
 ▪ accfc6586b Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 49d89e9df8 AudioFlinger: put effect desc lookup under mutex for createEffect
 ▪ f6a40939fb audioserver: Use '_exit' instead of 'exit' in HalDeathHandler
 ▪ 7436115ffe RESTRICT AUTOMERGE: aaudio: improve test_atomic_fifo
 ▪ 8cb1c83742 RESTRICT AUTOMERGE: aaudio: Fix converting negative FIFO counters to index
 ▪ 9a55e6eb67 Merge "Snap for 5230900 from e1879a18d2bc015d78c6278bb5a6d3c755754a8e to pi-platform-release am: 64c1d2cf45" into pie-gsi
 ▪ fb6e972085 Snap for 5230900 from e1879a18d2bc015d78c6278bb5a6d3c755754a8e to pi-platform-release am: 64c1d2cf45
 ▪ 26bc4732d8 AudioFlinger: put effect desc lookup under mutex for createEffect
 ▪ ea22519d81 audioserver: Use '_exit' instead of 'exit' in HalDeathHandler
 ▪ de85c0a232 RESTRICT AUTOMERGE: aaudio: improve test_atomic_fifo
 ▪ 884a56bf7f RESTRICT AUTOMERGE: aaudio: Fix converting negative FIFO counters to index
 ▪ 64c1d2cf45 Snap for 5230900 from e1879a18d2bc015d78c6278bb5a6d3c755754a8e to pi-platform-release
 ▪ e1879a18d2 January Pi-platform-release merges
 ▪ a504d888d4 AudioFlinger: put effect desc lookup under mutex for createEffect am: a41770b682 am: ef52b30f9c am: b6a54df739
 ▪ b6a54df739 AudioFlinger: put effect desc lookup under mutex for createEffect am: a41770b682 am: ef52b30f9c
 ▪ ef52b30f9c AudioFlinger: put effect desc lookup under mutex for createEffect am: a41770b682
 ▪ a41770b682 AudioFlinger: put effect desc lookup under mutex for createEffect

 ▼ frameworks/base/
 ▪ e4a6fc375c7 Merge "DO NOT MERGE Add CarrierConfig to overlay incorrect country ISO" into pi-dev
 ▪ 0ea8646adf0 Visualizer: fix native crash when visualizer release
 ▪ 06afffac8fa Clear all lingering notifications when network is disconnected
 ▪ 700fb81f2d0 Rounded Corner: Code improvement and clean up
 ▪ 8d5be0ea2db base: SystemUI: fix compact navbar layout placing of rotate button
 ▪ 5a67654f31c base: add option to enable AOD on charging only [1/2]
 ▪ f5dd7ed222c Revert "display: Add support for multiple displays."
 ▪ bc5cc676356 base: Switch logic of some settings
 ▪ 111e7a2692e Ambient music: code cleanup and glitch fixes
 ▪ 7c38da299c0 Ambient music: show on lockscreen only for Google's Now Playing
 ▪ 2994bf09a67 Revert "base: screen off animation config [1/2]"
 ▪ 5538177e71b Revert "Blacklist apps in the ChooserAcitivity (e.g. Share button) [1/2]"
 ▪ d73f7b18ae1 base: Update colors
 ▪ 8875526fdc3 SystemUI: Cleanup strings
 ▪ e5a78faf09d base: Disable SmartPixels
 ▪ a93015502bc base: Disable AOD by default
 ▪ 758ae39bed0 Revert "Volume wake/skip track: Make it work independently"
 ▪ 72940678509 base: Make home button wake up opt-in [1/2]
 ▪ afc42d698b6 base: Enable home button wake
 ▪ 449333eb8b6 Utils: Add method to check for CustomDoze
 ▪ 4df132afe6f base: Add CustomDoze
 ▪ 4e2b242c6b9 Ambient brightness values: use a custom system setting [1/2]
 ▪ 17373579558 Revert "Allow tuning ambient display with sensors [1/3]"
 ▪ b3b00dd592f base: Fix the bug that toasts show only icons in RTL layout.
 ▪ 6966261f3ef Statusbar clock: restore qsheader check within a saved instance
 ▪ a302fbb29c3 NotificationEntryManager: Fix ClassCastException
 ▪ 1763c839fd8 StatusBar: Silence logspam
 ▪ 53c711de2e2 Fix minutes in full accent clock
 ▪ 48cffb441fd Add wellbeing dark theme
 ▪ 682fb819666 SystemUI: Fix Lockscreen not dismissing with AOD enabled
 ▪ 57c46c1ab71 Implement per-app thermal control [2/3]
 ▪ 2769a8e1a98 SystemUI: Add optional notch friendly VoLTE icon
 ▪ 04898ff564f Snap for 5180536 from eb71e821edd929d48a824a9a4bbdfb710b50d324 to pi-platform-release
 ▪ ec1b164923f RESTRICT AUTOMERGE Close TextClassifier native resources.
 ▪ 4dbab056a2d [automerger skipped] DO NOT MERGE No smart text assist for unprovisioned device. am: 7c8a46e0dd -s ours am: 67722b0557 -s ours am: 447f279010 -s ours am skip reason: subject contains skip directive
 ▪ 447f2790100 [automerger skipped] DO NOT MERGE No smart text assist for unprovisioned device. am: 7c8a46e0dd -s ours am: 67722b0557 -s ours am skip reason: change_id I360250a5c2a92d09c8d8f559b51c74f490f70c2c with SHA1 9796a1bd00 is in history
 ▪ 67722b0557e [automerger skipped] DO NOT MERGE No smart text assist for unprovisioned device. am: 7c8a46e0dd -s ours am skip reason: change_id I360250a5c2a92d09c8d8f559b51c74f490f70c2c with SHA1 9796a1bd00 is in history
 ▪ cb3c850ea0a ActivityRecord: add fw boost after r33 merge
 ▪ ebf4d27285f Merge remote-tracking branch 'AOSP/pie-gsi' into pie
 ▪ 46b8c6b82fd Merge tag 'android-9.0.0_r33' into pie
 ▪ bfbd98868e5 Be more comprehensive about boot time RTC check
 ▪ b4ddb4a4fa9 Snap for 5285806 from a3a280e4d839fd3ac0bc2896122cc1b7064329e1 to pi-qpr3-release
 ▪ 80e465634bb Fix the distorted clock hands
 ▪ a056cd68693 Hide analog clocks while pulsing new notifications
 ▪ fa7e6368903 Add sneeky analog clock (1/2)
 ▪ b02c9d56284 Add Spectrum clock (1/2)
 ▪ 5b89f7e4b67 Add dot Analog clock [1/2]
 ▪ e3f95a04b62 Let's use bold in accent clocks
 ▪ 0af797beaf3 Add stock clocks with accent color
 ▪ 0da2c0f5199 Add in analog clock with numbers
 ▪ 86e08f09c66 LS: Add spidey clock style [1/2]
 ▪ e6b7598a17b base: QS header improvements
 ▪ 7c8a46e0dd3 DO NOT MERGE No smart text assist for unprovisioned device.
 ▪ a3a280e4d83 Merge "Add closing div tag for ContentResolver javadoc" into pi-dev
 ▪ 860c7c39e5b base: SystemUI: header image tweaks [1/2]
 ▪ ee362f6df8a Revert "Check if notification is valid before it finally vibrates"
 ▪ b270f550028 Carrier Label: Bring back the scroll (marquee) effect
 ▪ e4955449960 Slim recents: cleaner enable
 ▪ 99c768da782 base: Fix signature spoofing
 ▪ 44c9719bd23 screenrecord: add support for 18:9 resolutions
 ▪ 7e40b01a1be Frameworks: PA PIE Controls 3.0 [1/3]
 ▪ 2e902f10e7a LatinIME: fix navigation bar for expanded desktop
 ▪ e58bd9744ef AD Visualizer: Use white when cutom color not enabled
 ▪ 2b24279d498 Remove the check of mService when BluetoothHidDevice doUnbind
 ▪ 75064f2ad19 SystemUI: Fix FC after disabling navbar and unlocking phone
 ▪ e4ab861a0af PrivacyGuard: Pull in more changes from lineage
 ▪ c57d310d9c5 Update boot image profile to include Object.wait()
 ▪ 03df155ce82 AccountManagerService: Fix ConnectionRecord Leak
 ▪ 78c3ef92442 ActivityRecord: .app must not be null when you call .setVisible
 ▪ ee22f038c7b Get new surface if it was released from setWindowStopped
 ▪ 330d5165162 Pass correct preserve window value to performStop
 ▪ 65d90a3f4a6 Fix to hide phone number printed in the log
 ▪ 2e150c14725 AppOpsManager: Fix bluetooth scan op permission
 ▪ 9c28f4acfd4 Update sim colors [1/4]
 ▪ e449795c86d base: add Cookie QS style [2/3]
 ▪ d9d8bf75daa Screenrecorder: don't show tmp in some apps and improve code
 ▪ 4d23d383297 Revert "Screenrecord: removed scanning the tmp file"
 ▪ 565ff1e4e2c base: Keyguard: Hide check button when using PIN quick unlock
 ▪ 48684cb54f7 MicroG: Allow location providers also outside of /system
 ▪ c0684ad9a34 UiModeManagerService: Store messaging night state on Settings class
 ▪ ba879191344 fwb: Fix animation issue when opening Messaging app
 ▪ 0a7eab95f47 base: qs status bar header image [1/4]
 ▪ 2ab706f9bef Add synchronization for invokeForAllObservers call
 ▪ eba5334c122 SystemUI: Fix an issue where jumping to black after screen turned on
 ▪ a9113efe293 SystemUI: Fix NPE when DozeService is destroyed
 ▪ 954a490c27f UXE: Recents app detection & Refactor
 ▪ 63076fbade3 uxe: Check memory pressure before starting empty app.
 ▪ 80d136704c4 framework/base: optimize multi-thread code
 ▪ ce6be28fdd0 AlarmManagerService: Add null check to QCNsrmAlarmExtension call
 ▪ 2e4edc38df3 base: Add additional builtins to scan ids.
 ▪ 7ed1b6eeef8 EdgeGestureService: silence debug logging
 ▪ cd0698b94d6 EdgeGestureService: add more sensitivity steps
 ▪ bee2775cdae Add ChargingStarted + InCallNotif to AudioPackage
 ▪ 3c783af8356 RecentsIconPack: Fallback to default icons on icon pack removal
 ▪ f7c4274d9c3 Fix disappearing home/recents button
 ▪ bd39d644299 DefaultPermissionGrantPolicy: grant Google sounds picker storage perms
 ▪ 5e663e1a858 WeatherClient: Conditionally allow query when adding observer
 ▪ 8c84690db5d Fix system ui crash when pinning screen
 ▪ 455a196a6a1 Revert "Auto switch to a dark analog clock when using dark system theme"
 ▪ 44567b69814 base: Add support for DiracSound FX
 ▪ 128d666afc5 base: App picker Tile
 ▪ c54f501c356 Dark theme: Fix notification channel info text color
 ▪ b8c9dace531 Merge "Use the correct Smart Storage flag in SettingsLib." into pi-dev
 ▪ 7c93cefc819 Fixed temporary brightness getting stuck bug.
 ▪ fe87cf3e5aa Added hysteresis check to screen brightness.
 ▪ f636191beaa DO NOT MERGE Add CarrierConfig to overlay incorrect country ISO
 ▪ d3ecd46659e Merge "Informing app idle listeners on enabled state changes." into pie-gsi
 ▪ 546a799e6de Informing app idle listeners on enabled state changes.
 ▪ e2ff1b26b6f Snap for 5268384 from 83924aca2c958102ceeebc35eadaa39c6295e956 to pi-qpr3-release
 ▪ 83924aca2c9 Merge "v3 keys use SP800 derivation" into pi-dev
 ▪ dbf0f79d4a4 Merge "[DO NOT MERGE]Add check for slot index value" into pi-dev
 ▪ 71045287a56 DO NOT MERGE Fix flaky tests in OverheatAlarm feature
 ▪ ff52e55ab1e Merge "Fix for CTS testAllowWhileIdleJobInTempwhitelist" into pie-gsi
 ▪ e532469994f Merge "[DO NOT MERGE] ViewRoot: Notify app when surface is released from setWindowStopped" into pi-dev
 ▪ 36d759a55a1 Fix for CTS testAllowWhileIdleJobInTempwhitelist
 ▪ 7a118345e33 Use the correct Smart Storage flag in SettingsLib.
 ▪ 8dca21054f4 [DO NOT MERGE]Add check for slot index value
 ▪ 6397dd1c922 [DO NOT MERGE] AML: Handle NoDisplayActivities correctly
 ▪ dee98726bf8 Merge "Fix theme cannot change due to there is no wallpaper colors." into pi-dev
 ▪ 3ca513070bc Add closing div tag for ContentResolver javadoc
 ▪ 47d2d1e46a5 [DO NOT MERGE] ViewRoot: Notify app when surface is released from setWindowStopped
 ▪ 5d378dfeacb Keep PluginManager reference to avoid NPE
 ▪ 63ef1511b47 v3 keys use SP800 derivation
 ▪ 7d5479e8dbf Snap for 5249487 from 64ca10b75bb7e8b8b9633b57f2a5fcaeb3c395b3 to pi-qpr3-release
 ▪ 64ca10b75bb Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ d3f3709b300 Import translations. DO NOT MERGE
 ▪ 6d16e858237 Revert "Kill some lockscreen related animations"
 ▪ 9d4de34297c Add sammy accent clock and a variant [1/2]
 ▪ c605980a4f6 SystemUI: Use VoLTE icon from OOS
 ▪ fccf9d031f9 Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 7378bd5761d Screenrecord notification: tap on it to open the video
 ▪ a0a89b2698d base: Fix power off animation
 ▪ 104bb9b64ef Import translations. DO NOT MERGE
 ▪ bcd7520f7a0 MountService: Prevent NPE with DropBoxManager
 ▪ 353483e97e7 connectivity: Configure additional TCP parameters
 ▪ 120d9273e64 Display 'Dash charging' for dash charge in battery settings [1/2]
 ▪ 85f4d48f08b base: Workaround to fix dark theme on Messaging app
 ▪ c0cf4978e13 base: Lock day night mode
 ▪ 04eace19be5 SystemUI: Fix flickering issue when live wallpaper is showing on aod/pulsing
 ▪ ace8f3b92df base: Theme improvements
 ▪ 1bedca51b3f base: make settings_dark colors same as material_dark
 ▪ ff571eb824a WeatherClient: Don't enforce READ_WEATHER permission
 ▪ 46e35c90053 Implement animations for back edge gestures
 ▪ f84f75c0719 Add edge gesture (1/2)
 ▪ 3a43eb02dd3 Add NPE handling to the Edge Gesture Manager
 ▪ 8e271563d07 Add ability to use EdgeGestureService for system gestures
 ▪ df9c59e4ead Add EdgeGesture service
 ▪ 9f726cd2800 WebView: clean up onReceivedSslError docs
 ▪ cdacf4d02cc Ambient music: more improvements
 ▪ e4a96ac6f40 Dash charging: Add the battery percent back
 ▪ 11eeb27066b Decrease line spacing in sammy clock styles
 ▪ 9d96eec20a5 Set font type for some statusbar, qs items
 ▪ 2c7226e8876 base: notch-city: Add 3 mode display cutout handler [1/3]
 ▪ 26f39038fc0 Screenrecord: removed scanning the tmp file
 ▪ dc501d09020 Edit Icon Toggle [1/2]
 ▪ 548fb3a2300 fonts: Fix compiling generic fonts
 ▪ 1987d9d7553 Fix dual clock after heads up notification
 ▪ fc4dec32aff Merge "Don't log account name on logcat (cherry-pick from master)" into pi-dev
 ▪ 988624eda2c Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 1607141d0d6 DPM: Fix regression from I54376f60ac53451ace22965d331b47cd8c2e614e
 ▪ 5acf81a1f4d RESTRICT AUTOMERGE Do not linkify text with RLO/LRO characters.
 ▪ e385b32862e Adding SUPL NI Emergency Extension Time
 ▪ c0b85f9e76f FRP: save password quality in DPM.resetPassword
 ▪ f69dfb9b2fb Merge "BluetoothManagerService: catch NoSuchElementException for unlinkToDeath" into pi-dev
 ▪ 31d70a1d5a9 Fix theme cannot change due to there is no wallpaper colors.
 ▪ 5fc6002de59 Don't log account name on logcat (cherry-pick from master)
 ▪ 4e3076b1a21 Merge "AdapterService: Only bind HeadsetService in ON state." into pi-dev
 ▪ 571afb3b78e Merge "Actually use listener hints?" into pi-dev
 ▪ 9aee2841e85 Actually use listener hints?
 ▪ 81cb5e99198 Skip empty slice permissions files during backup
 ▪ de18a38e312 Merge changes from topic "b/121448199" into pi-dev
 ▪ 2a8a4d56fec Merge "Fix stuck notifications" into pi-dev
 ▪ bcb59884f0f Merge "Snap for 5230900 from 5c3a8421b419bf983810cbfd5e9e9ee999c17e54 to pi-platform-release am: 9fcdc1f9e0" into pie-gsi
 ▪ b6315c2e347 Snap for 5230900 from 5c3a8421b419bf983810cbfd5e9e9ee999c17e54 to pi-platform-release am: 9fcdc1f9e0
 ▪ 06fb16617ce DPM: Fix regression from I54376f60ac53451ace22965d331b47cd8c2e614e
 ▪ bddb4bb99eb RESTRICT AUTOMERGE Do not linkify text with RLO/LRO characters.
 ▪ 13d3aecd1b0 Adding SUPL NI Emergency Extension Time
 ▪ 9fd6c676512 FRP: save password quality in DPM.resetPassword
 ▪ 9fcdc1f9e0d Snap for 5230900 from 5c3a8421b419bf983810cbfd5e9e9ee999c17e54 to pi-platform-release
 ▪ ac3f14ef089 Fix stuck notifications
 ▪ 697b1bde88c Battery saver: Ensure warning doesn't pop up while plugged in
 ▪ a703fdce3bc data: Fix weather provider permission
 ▪ dfa86e4b698 SystemUI: Fix too big spacing between QS icons in landscape on sw600dp
 ▪ 568de76bea6 Remove unnecessary right padding from time picker
 ▪ c1301c2a502 SystemUI: Modify ime navigation bar layout
 ▪ 1082d101f9b fonts: Clean up absent fonts if EXCLUDE_SERIF_FONTS is true
 ▪ 163ba46418c base: fix signature spoofing and microg
 ▪ 5eda6660189 Force disable PlayServices OTA checks
 ▪ 009b5943894 Bring back vendor mismatch message
 ▪ ef002d49f02 Dynamically tell the user which vendor image is needed
 ▪ 2086a4fb7b1 Show a more descriptive message when vendor.img is out of date
 ▪ 567616a4435 Full gesture navbar: fix swipe to back glitches
 ▪ 14baa9f5e18 Lockscreen analog clock: improve minute hands looking
 ▪ acbb1f00291 Auto switch to a dark analog clock when using dark system theme
 ▪ 73652481177 Always use standard small clock when pulsing on new notifications
 ▪ ad48a050eeb Lockscreen clock styles: Fix bottom margins & ambient display/AOD visibility
 ▪ 05b7b22e939 Lockscreen items/clocks: KeyguardSliceView improvements/cleanup
 ▪ c5a7f9a4d62 Lockscreen clock styles: Move everything to the keyguard [1/2]
 ▪ 3aa4b6a0bb9 Lockscreen/ambient analog clock: improve design
 ▪ 0b20ec782ef Ensure the clockview is aligned correctly each time
 ▪ c33524465a2 Remove the 0 from the 12 hour format from the 'Digital (bold)' option
 ▪ 0b9d7e1d533 Keyguard items: code improvements
 ▪ bdc6aa78898 Introduce lockscreen clock/date styles [1/2]
 ▪ 6f1f06725b3 Always keep clock/date & other items visible while dozing
 ▪ a1f68563190 Hide lockscreen items [1/2]
 ▪ 4ed570b7056 Add support for the .opus file format
 ▪ 003d076db1b fix deadlock of binder thread and ActivityManager
 ▪ a9086650772 Fix deadlock in AcitivityManagerService
 ▪ 4f2e33d5944 hwui: fix mmap leak of graphicsstats service
 ▪ 273e07d78dd Import translations. DO NOT MERGE
 ▪ 5c3a8421b41 January Pi-platform-release merges
 ▪ 5b0a3215eb1 Clarify WebResourceResponse's stream handling.
 ▪ 3f3c8f812e8 Merge "Nullify the default wallpaper component if it does not exist" into pi-dev
 ▪ 8f70a490dab [automerger skipped] [automerger] Select only preinstalled Spell Checker Services am: ed5973b8a8 am: 5ab7f995ba am: d71a5db522 am: 276e18c147 am: d962aabf4c am: 3c2abaa4da am: 04206067b9 -s ours am: cf8145858c -s ours am skip reason: change_id Idab3ecc246fe9344a09e6907a0ba39f8ea6506f9 with SHA1 dd8b0a6bc8 is in history
 ▪ 07ca0e8747b [automerger skipped] [automerger] Revert "Select only preinstalled Spell Checker Services" am: 170e24d4e1 am: fb3b187f10 am: 7abf49d3b7 am: 1684713f2e am: cd6eba50ba am: 576e4ac184 am: d596c0e4ef -s ours am: 34a17e0e25 -s ours am skip reason: change_id Idab3ecc246fe9344a09e6907a0ba39f8ea6506f9 with SHA1 dd8b0a6bc8 is in history
 ▪ cf8145858c6 [automerger skipped] [automerger] Select only preinstalled Spell Checker Services am: ed5973b8a8 am: 5ab7f995ba am: d71a5db522 am: 276e18c147 am: d962aabf4c am: 3c2abaa4da am: 04206067b9 -s ours am skip reason: change_id Idab3ecc246fe9344a09e6907a0ba39f8ea6506f9 with SHA1 dd8b0a6bc8 is in history
 ▪ 34a17e0e250 [automerger skipped] [automerger] Revert "Select only preinstalled Spell Checker Services" am: 170e24d4e1 am: fb3b187f10 am: 7abf49d3b7 am: 1684713f2e am: cd6eba50ba am: 576e4ac184 am: d596c0e4ef -s ours am skip reason: change_id Idab3ecc246fe9344a09e6907a0ba39f8ea6506f9 with SHA1 dd8b0a6bc8 is in history
 ▪ 04206067b90 [automerger] Select only preinstalled Spell Checker Services am: ed5973b8a8 am: 5ab7f995ba am: d71a5db522 am: 276e18c147 am: d962aabf4c am: 3c2abaa4da
 ▪ d596c0e4ef0 [automerger] Revert "Select only preinstalled Spell Checker Services" am: 170e24d4e1 am: fb3b187f10 am: 7abf49d3b7 am: 1684713f2e am: cd6eba50ba am: 576e4ac184

 ▼ frameworks/native/
 ▪ a4514a36b Snap for 5180536 from cb5531e3576fec2be6e366f16dd85696a20552b3 to pi-platform-release
 ▪ a01b4c93b Merge 3b58869059f2a3cb4efb4a8662470305ad7fd7ba on remote branch
 ▪ 69e255a89 Merge 331d0f2eda2bb1378f17ab9cf34e715be724e414 on remote branch
 ▪ b012bf593 Merge tag 'android-9.0.0_r33' into pie
 ▪ 59dd73309 Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/frameworks/native into HEAD
 ▪ e47e59dd2 libs: ui: Fix shadow-field warnings
 ▪ 7324cc994 [HAX] remove stylus shit from touchscreen input
 ▪ 0b6290bd6 APP may display abnormally in landscape LCM
 ▪ 05b546a2f sf: Workaround BufferLayer::setBuffers issue on 1440p msm8974
 ▪ aed936dc9 Revert "native: touch response optimizations"
 ▪ 9eb2b06ac Revert "APP may display abnormally in landscape LCM"
 ▪ 564dc306f input: Adjust priority
 ▪ 81aa6740e Snap for 5267285 from 6154687719770ea8990e527be7549bde06789e6a to p-keystone-qcom-release
 ▪ 615468771 Merge "Clamp input color for BT2020_PQ EOTF" into p-keystone-qcom
 ▪ 47fd0157f Avoid calling into HWC in onFirstRef
 ▪ de58be0c2 DO NOT MERGE Change the logic of ContainerLayer's isVisible()
 ▪ 28faaf3b6 SurfaceFlinger: Expose construction of container layers.
 ▪ fb0fd0ba2 Merge 331d0f2eda2bb1378f17ab9cf34e715be724e414 on remote branch
 ▪ 3b5886905 Snap for 5255917 from 55c2e6c70bdffeba8ac590f7ee7262877e1e1dd1 to p-keystone-qcom-release
 ▪ 55c2e6c70 Merge "SF: Protect activeTransparentRegion from multi thread access" into p-keystone-qcom
 ▪ a0dad5ab7 Merge commit '331d0f2eda2bb1378f17ab9cf34e715be724e414' into HEAD
 ▪ 0795d10cf libs: ui: Fix shadow-field warnings
 ▪ b55d7aedc Snap for 5247868 from 247d96095c34a61647bae0a17fec01d523206c11 to p-keystone-qcom-release
 ▪ 247d96095 Merge "sf: Check for support before updating vsync source change" into p-keystone-qcom
 ▪ 331d0f2ed Snap for 5235762 from 64c60d78a4dfb0777db425e95e408f13bc79ecbf to p-keystone-qcom-release
 ▪ 3ce2b66f9 Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 86c2985b0 Sanitize InputMessage before sending
 ▪ 8db926636 Clamp input color for BT2020_PQ EOTF
 ▪ 64c60d78a sf: remove dolphin lib related property check.
 ▪ 2cac34e7f Sanitize InputMessage before sending

 ▼ frameworks/opt/net/ims/
 ▪ aa4fd67 Merge 42654652d71a0f58d9206f62d86433284c0301ee on remote branch
 ▪ 6b690b6 Merge 42654652d71a0f58d9206f62d86433284c0301ee on remote branch
 ▪ 32dc211 Merge 42654652d71a0f58d9206f62d86433284c0301ee on remote branch

 ▼ frameworks/opt/net/wifi/
 ▪ 7e4dad125 Snap for 5180536 from e3696132f209dfa4e635b2fa397ddf3ae8f9aa4b to pi-platform-release
 ▪ 78b3f5e32 Merge 44e7520e2cadbc0398fa0d69d2791b49466a23c3 on remote branch
 ▪ 0cca8cdab Merge tag 'android-9.0.0_r33' into pie
 ▪ 38412732b Snap for 5278091 from d76a8ddcbc953276fe39093fcbda1dbb641ca96b to p-keystone-qcom-release
 ▪ d76a8ddcb Merge "wifi: Register to ACTION_SHUTDOWN to shutdown Wi-Fi" into p-keystone-qcom
 ▪ 0786c0455 wifi: Register to ACTION_SHUTDOWN to shutdown Wi-Fi
 ▪ 447a9f73b Snap for 5264258 from 0b5ba1f99f24d4debe64823a49f38166827e90d9 to p-keystone-qcom-release
 ▪ 0b5ba1f99 wifi: Retain WIFI_SAVED_STATE during device bootup with Airplane mode
 ▪ b50658d69 wifi: Add support for wifi latency level using vendor wifi@1.0
 ▪ ec17841e3 Merge 44e7520e2cadbc0398fa0d69d2791b49466a23c3 on remote branch

 ▼ frameworks/opt/slimrecent/
 ▪ 06fcab1 Hide screenshot view if no screenshot is available
 ▪ 138a0b6 Slim recents: re-enable expanded mode always [1/2]
 ▪ 5d37814 Enable predictive item animations

 ▼ frameworks/opt/telephony/
 ▪ 867980edfc Snap for 5180536 from e2b71fbd1f36abac5a9fa55647083f54dc50d508 to pi-platform-release
 ▪ 77829405c1 Merge 9a4a94f1cbad39438737489f92c68f3aaa227328 on remote branch
 ▪ fdebdebd4a Snap for 5285806 from ba0b55d44f579148b70ffc36791bd374f0dd0655 to pi-qpr3-release
 ▪ 1be3fdb76d Amend SMS over IMS proto and metrics collection
 ▪ a59b7d168d Adds metrics for SMS over IMS using ImsService
 ▪ a93f2732ed Merge branch 'pie' of https://github.com/Havoc-OS/android_frameworks_opt_telephony into caf
 ▪ 907b5d922a Merge remote-tracking branch 'AOSP/pie-gsi' into pie
 ▪ 200d4fe1d3 Merge tag 'android-9.0.0_r33' into pie
 ▪ 025a6129d8 Update sim colors [3/4]
 ▪ b1fbccb860 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into caf
 ▪ 32bf5d15c5 Merge 9a4a94f1cbad39438737489f92c68f3aaa227328 on remote branch
 ▪ a9885d9e08 Merge 9a4a94f1cbad39438737489f92c68f3aaa227328 on remote branch
 ▪ ba0b55d44f Expand onCallHandover logging and add data enabled check.
 ▪ 89b0aacee7 Merge 9a4a94f1cbad39438737489f92c68f3aaa227328 on remote branch
 ▪ 9a4a94f1cb Snap for 5242636 from c73510198923c58fb301a82fbf350c3c9f9faf2c to p-keystone-qcom-release
 ▪ c735101989 Merge "Revert "Make radio power off immediately after data cleanup is complete"" into p-keystone-qcom
 ▪ 323ee681af Merge cherrypicks of [6077490, 6076917] into pi-b4s4-release
 ▪ 266745dc47 Update sharedPreference to false when exits new device provisioning
 ▪ be52a39055 Merge "Update sharedPreference to false when exits new device provisioning" into pi-dev
 ▪ 4e152fab4a Update sharedPreference to false when exits new device provisioning
 ▪ ed70d4d99d Revert "Make radio power off immediately after data cleanup is complete"

 ▼ hardware/broadcom/libbt/
 ▪ 0919027 libbt: Align Samsung CID strings to those created by macloader

 ▼ hardware/havoc/interfaces/
 ▪ c6e0e42 trust: create service
 ▪ 4b1c700 interfaces: Add trust 1.0 HAL
 ▪ 73c5a16 interfaces: Add touch HIDL interface definitions
 ▪ 47208dd interfaces: Add 2.0 livedisplay interfaces
 ▪ b0384be aw2013: lets not crash service on missing LED

 ▼ hardware/interfaces/
 ▪ b683609c9 Snap for 5180536 from 412352b37accb6e8f3684aae162b82e1a6a2d528 to pi-platform-release
 ▪ c23113c7b Merge 2e68f2ba19aada1d22657e2b815d31041c2f9aaa on remote branch
 ▪ fc06f4144 Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/hardware/interfaces into 9.0
 ▪ 4609857ee omx:component: add support for tunneled components in ComponentTest
 ▪ d4a33ad85 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into 9.0
 ▪ 972fcf6cc configstore: Fix CFLAG issue in configstore makefile
 ▪ 4defd7db4 Snap for 5268384 from e233a7c98dcee605c70ea9cf1b91831575871770 to pi-qpr3-release
 ▪ cefd383f9 Merge 2e68f2ba19aada1d22657e2b815d31041c2f9aaa on remote branch
 ▪ e233a7c98 The test failed when one of the three cameras was configured with a maximum android.scaler.availableStreamConfiguration size of 1600*1200 am: 6f6fe9a5e2
 ▪ 0e6ba012a wifi: Add wifi latency level support to vendor wifi@1.0
 ▪ ddf3f0635 Merge 2e68f2ba19aada1d22657e2b815d31041c2f9aaa on remote branch
 ▪ 6f6fe9a5e The test failed when one of the three cameras was configured with a maximum android.scaler.availableStreamConfiguration size of 1600*1200
 ▪ 459454b7a Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into 9.0
 ▪ 318a1ebb0 Snap for 5232626 from 31ad8ce667cfb926e11a3df8c128a6cdb3e76442 to pi-b4s4-release
 ▪ 31ad8ce66 Merge "Camera: fill in bufferSize correctly" into pie-vts-dev am: d04f64ef24
 ▪ d04f64ef2 Merge "Camera: fill in bufferSize correctly" into pie-vts-dev
 ▪ 9d4ff706e Camera: fill in bufferSize correctly

 ▼ hardware/libhardware/
 ▪ ca30eda7 Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into 9.0

 ▼ hardware/libhardware_legacy/
 ▪ a017c3f Snap for 5274539 from a88b1faf71f148efe740cc09338067937bf1066f to p-keystone-qcom-release
 ▪ bf8b0a8 Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into 9.0

 ▼ hardware/lineage/livedisplay/
 ▪ 781eb9d livedisplay: sysfs: Remove unused HALs
 ▪ 8475e6c livedisplay: sysfs: Add LineageOS copyrights
 ▪ 733de0b livedisplay: sysfs: Add autogenerated code
 ▪ 62d6ecd livedisplay: sdm: Fix restoring default mode
 ▪ 36ab575 livedisplay: sdm: Fix isSupported() checks
 ▪ d4eb8a8 livedisplay: The module isn't proprietary
 ▪ 0d26b6b livedisplay: Nuke color balance
 ▪ d421085 livedisplay: Minor code cleanup
 ▪ 950336a livedisplay: Fix racy init
 ▪ 75ac2f2 livedisplay: Use 1 thread
 ▪ 7a5da24 livedisplay: sdm: Wire it up
 ▪ 2667bbd livedisplay: sdm: Remove unused HALs
 ▪ ce53d14 livedisplay: legacymm: Wire it up
 ▪ c6e1c35 livedisplay: legacymm: Remove unused HALs
 ▪ d723625 livedisplay: Add clang-format from hardware/interfaces
 ▪ 986bd64 livedisplay: Split impls into legacymm and sdm
 ▪ 7193ce2 livedisplay: qti: Add LineageOS copyrights
 ▪ 948ade8 livedisplay: Update for new .hal definitions

 ▼ hardware/nxp/nfc/
 ▪ 3140e98 Snap for 5180536 from 1a7ca2f8c750c84c17bf3fd6e97810b7cee176ba to pi-platform-release
 ▪ 30bc03a Merge tag 'android-9.0.0_r33' into pie
 ▪ d6afaec Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 35f34c2 Prevent Out of bound error in phNxpNciHal_process_ext_rsp

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 12351c27 Merge f722e912d5dab8501663cd26af6fe0c7cfdc7b20 on remote branch
 ▪ 0f2791a9 configs: trinket: Change ACDB ID of speaker to mono
 ▪ 5b31d479 Merge "hal: add support for trinket qrd sound card"
 ▪ 7f93d4f5 Merge "audio: Add flags to makefiles"
 ▪ e70a4aa3 audiohal: Modifications in hal_play_test for trumpet certification
 ▪ f1de7fc9 Merge 17bad40b723035bd001e3795374bbede65eede80 on remote branch
 ▪ fcee7439 audio: hal: adding talosAU hw information
 ▪ f722e912 Merge "audio: Add support for quad EC capture"
 ▪ 2a72c6d4 Build audio.primary.* with BOARD_VNDK_VERSION
 ▪ 939e43a6 Merge "hal: Modify logic to get acdb snd card name"
 ▪ b37fdb1f Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into 9.0
 ▪ a63a0659 audio: Add support for quad EC capture
 ▪ db258aee Merge "config: remove USB devices in policy config file"
 ▪ ba22f7b5 Merge "hal: sndmonitor: Add support for trinket sound card in sndmonitor"
 ▪ 0bc24256 Merge "configs: kona: Add ACDB device for headset SVA support"
 ▪ 7ed1cede Merge "config: Remove 2 instance support for "primary input""
 ▪ e46b2fe3 hal: add support for trinket qrd sound card
 ▪ 916c7afc Merge "hal: add support to set custom channel configs"
 ▪ 2f2a70fe configs: kona: Add ACDB device for headset SVA support
 ▪ 8b27046e hal: sndmonitor: Add support for trinket sound card in sndmonitor
 ▪ 35254a8e Merge changes  into audio-hal.lnx.5.0
 ▪ ce33ee79 Merge "hal: Enable stereo speaker config in trinket"
 ▪ 80fd90d8 Merge "hal: kona: update device setting for kona"
 ▪ 2a7f75b0 hal: add support to set custom channel configs
 ▪ 37ca3ac9 config: Remove 2 instance support for "primary input"
 ▪ 5585fb1a Merge "configs: sdm710: Update xml files with acdb id and flags"
 ▪ c95af7f0 Merge "hal: Changes to enable multi-turn"
 ▪ 2cafaa0b Merge "configs: trinket: Config changes on trinket"
 ▪ d8548771 hal: Changes to enable multi-turn
 ▪ d8d10185 configs: sdm710: Update xml files with acdb id and flags
 ▪ a62c7512 Merge "hal: Add EC reference changes for FFV"
 ▪ ee976d73 hal: kona: update device setting for kona
 ▪ 45ed5178 config: remove USB devices in policy config file
 ▪ 1363ed53 Merge "hal: kona: update missed audio properties for kona"
 ▪ 28b6e4c0 Merge "Hal: Add check for usb in device"
 ▪ c86331fe hal: kona: update missed audio properties for kona
 ▪ cc3f6a94 Merge 17bad40b723035bd001e3795374bbede65eede80 on remote branch
 ▪ 0f1dfd54 hal: Add EC reference changes for FFV
 ▪ 5760b061 Merge "configs: trinket: Add mixer paths for tasha variants"
 ▪ 9714e346 configs: trinket: Config changes on trinket
 ▪ ff570a05 hal: Enable stereo speaker config in trinket
 ▪ a1bfc8d1 Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into 9.0
 ▪ d19f4e18 Merge "msmsteppe: Add mixer path for audio-playback-voip"
 ▪ b019e814 Merge "msmsteppe: Update the ACDB ID."
 ▪ 0a8ef83d hal: Modify logic to get acdb snd card name
 ▪ 97cafa74 Hal: Add check for usb in device
 ▪ 04116ecf Merge "removed TARGET_USES_AOSP_FOR_AUDIO flag from msmnile_au.mk"
 ▪ 58a4e26d msmsteppe: Update the ACDB ID.
 ▪ 8ec61508 msmsteppe: Add mixer path for audio-playback-voip
 ▪ 0e9397b3 configs: trinket: Add mixer paths for tasha variants
 ▪ 6608c211 hal: kona: update soundtrigger mixer paths to fix compilation error
 ▪ 6ea5d6d8 Merge "hal: kona: update soundtrigger mixer paths and platform info"
 ▪ c914d503 Merge "hal: add audio support for kona"
 ▪ 3e0de0f7 hal: Add support for trinket soundcard

 ▼ hardware/qcom/bt-caf/
 ▪ 5075514 Merge eb05e369e3392221400660ea188eda54939c30ec on remote branch
 ▪ ca91611 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into 9.0
 ▪ 06f780e Merge eb05e369e3392221400660ea188eda54939c30ec on remote branch
 ▪ c1b704e Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into 9.0

 ▼ hardware/qcom/display-caf/msm8996/
 ▪ b1254079 Merge 72346a65ecb153ddf5ae9fa927e4ea6197275c13 on remote branch
 ▪ 7dd04cbb Merge 8d63cfc7d1118ba25b1e1dcb9709e768f1a5b8b2 on remote branch
 ▪ 7db5e98e Merge "hqd: add qservice binder for blocking dpps"
 ▪ c92bca4f Merge "libgralloc1: Fix ion handle leak when metadata import fails"
 ▪ 64d8aebb Merge tag 'LA.UM.7.5.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0
 ▪ 8628f28d libgralloc1: Fix ion handle leak when metadata import fails
 ▪ 72346a65 hwc2: avoid flush on command mode with secure display
 ▪ 3cfb2358 Merge tag 'LA.UM.7.6.2.r1-04300-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into HEAD
 ▪ a471276c Merge "updating <CEC Version> information."
 ▪ d6de594d Merge "Hdmi-cec:fix for cpu hogging by event-monitor thread."
 ▪ e5d07204 Merge 8d63cfc7d1118ba25b1e1dcb9709e768f1a5b8b2 on remote branch
 ▪ 6ec06be2 Hdmi-cec : fix cec message send failures.
 ▪ 1556c4bb Hdmi-cec:fix for cpu hogging by event-monitor thread.
 ▪ 3862a6b6 updating <CEC Version> information.
 ▪ 7d7da265 Merge 8d63cfc7d1118ba25b1e1dcb9709e768f1a5b8b2 on remote branch
 ▪ dcf2ebae hwc2: Reset validated flag only for specific display
 ▪ 8d63cfc7 Merge "hwc2: Fix compile errors in switch statement."
 ▪ 831a9bbc hwc2: Fix compile errors in switch statement.

 ▼ hardware/qcom/fm/
 ▪ 68d2314 Merge b560846c1872bba40b68acdcee6c97745ef6d190 on remote branch
 ▪ b560846 FM: add synchronization fix across hal init and hal close
 ▪ dd027a3 FM: make correct sequence of slimbus and audio port
 ▪ af17486 libfm_jni: Fix typo in ctl.stop
 ▪ 131be18 libfm_jni: Rename the QC introduced props to have vendor tag added
 ▪ 20f8971 FM: FM: Add user space changes to enable fm for Richwave chip
 ▪ b2ce009 Merge "FM: Query and apply STREAM_MUSIC volume     when output device routing changes."
 ▪ 08a9d18 Merge "FM: Ignore VOLUME_CHANGED_ACTION intent when     fm is turned off."
 ▪ 3a615df FM: Query and apply STREAM_MUSIC volume     when output device routing changes.

 ▼ hardware/qcom/gps/
 ▪ 722730b0 Snap for 5180536 from dd6c5546adc4715854182358c2dd68691434efe9 to pi-platform-release
 ▪ 5dc7ab48 Merge tag 'android-9.0.0_r31' into lineage-16.0-android-9.0.0_r31

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ 0392d8a4 mm-video-v4l2: Avoid extradata handling for empty input buffer
 ▪ c4ea3419 Merge 1faa62c652e6d95dc7dc58fdd7a0530739c59fc6 on remote branch
 ▪ 2ba01439 mm-video-v4l2: Support Secure encode session for RGBA8888 input

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 0392d8a4a mm-video-v4l2: Avoid extradata handling for empty input buffer
 ▪ 2ba014395 mm-video-v4l2: Support Secure encode session for RGBA8888 input
 ▪ ede29a9cd Merge 1faa62c652e6d95dc7dc58fdd7a0530739c59fc6 on remote branch
 ▪ e077da5e4 Merge tag 'LA.UM.7.4.r1-04100-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into lineage-16.0-caf-8998

 ▼ hardware/qcom/wlan-caf/
 ▪ d545676 Merge ac0207228887c87d80644d5b384c762864fc7b44 on remote branch
 ▪ e83d001 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into 9.0
 ▪ e8fba8b Merge ac0207228887c87d80644d5b384c762864fc7b44 on remote branch
 ▪ 59d9d42 Merge ac0207228887c87d80644d5b384c762864fc7b44 on remote branch
 ▪ 9de2dd2 Revert "WiFi-HAL: Return success if blacklist/whitelist BSS number is zero"
 ▪ 0377459 Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into 9.0

 ▼ hardware/ril/
 ▪ 57f40b33 Snap for 5180536 from 082e32effc07dddd06b67d2be2c2c6ee554d5d52 to pi-platform-release

 ▼ hardware/ril-caf/
 ▪ e3d006f libril: Fix manual network selection with old modem

 ▼ kernel/xiaomi/msm8996/
 ▪ d0749530714a disable calling scm_version() function
 ▪ cd172d2bdb85 drivers: iio: imu: Fix NULL pointer dereference in bmi160 driver
 ▪ 7e5b990b4903 Merge branch 'upstream-linux-3.18.y' of https://android.googlesource.com/kernel/common into dts
 ▪ 5c5b61937193 Merge 3.18.134 into kernel.lnx.3.18.r34-rel
 ▪ e91e51d0b4c0 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into kernel.lnx.3.18.r34-rel
 ▪ 49ab1e524f6a Linux 3.18.134
 ▪ 9b59612715f8 mm: migrate: don't rely on __PageMovable() of newpage after unlocking it
 ▪ 98ea95b83600 mm, oom: fix use-after-free in oom_kill_process
 ▪ 844e011513fb platform/x86: asus-nb-wmi: Drop mapping of 0x33 and 0x34 scan codes
 ▪ 15890adab2e6 platform/x86: asus-nb-wmi: Map 0x35 to KEY_SCREENLOCK
 ▪ 01c06a455310 gfs2: Revert "Fix loop in gfs2_rbm_find"
 ▪ 2eca8cac47ad fs/dcache: Fix incorrect nr_dentry_unused accounting in shrink_dcache_sb()
 ▪ 3a4b0cbdca06 CIFS: Do not count -ENODATA as failure for query directory
 ▪ ed38538f3833 l2tp: fix reading optional fields of L2TPv3
 ▪ 78e36d3887bc l2tp: remove l2specific_len dependency in l2tp_core
 ▪ c970a01de93a ucc_geth: Reset BQL queue when stopping device
 ▪ 537e674b96f8 net/rose: fix NULL ax25_cb kernel panic
 ▪ f1d9a1f2ef6f netrom: switch to sock timer API
 ▪ 5f91b3a3ef75 l2tp: copy 4 more bytes to linear part if necessary
 ▪ 85d72db87183 ipv6: Consider sk_bound_dev_if when binding a socket to an address
 ▪ 41dd4d647330 f2fs: read page index before freeing
 ▪ 1330478d468c perf unwind: Take pgoff into account when reporting elf to libdwfl
 ▪ 0ebdf0080949 perf unwind: Unwind with libdw doesn't take symfs into account
 ▪ 3a1dab76b849 vt: invoke notifier on screen size change
 ▪ c84fb9ca5f7b can: bcm: check timer values before ktime conversion
 ▪ 3670c9c5ca57 can: dev: __can_get_echo_skb(): fix bogous check for non-existing skb by removing it
 ▪ 444fc5b3c804 x86/kaslr: Fix incorrect i8254 outb() parameters
 ▪ bed3eafc0d60 Input: xpad - add support for SteelSeries Stratus Duo
 ▪ e2a07b39388f CIFS: Fix possible hang during async MTU reads and writes
 ▪ 19a17b01d7e0 tty/n_hdlc: fix __might_sleep warning
 ▪ ccf4ecf43373 tty: Handle problem if line discipline does not have receive_buf
 ▪ bf9702a73e24 staging: rtl8188eu: Add device code for D-Link DWA-121 rev B1
 ▪ 0c4373e61d68 s390/smp: fix CPU hotplug deadlock with CPU rescan
 ▪ 345304901feb USB: serial: pl2303: add new PID to support PL2303TB
 ▪ 09a42430830e USB: serial: simple: add Motorola Tetra TPG2200 device id
 ▪ af9ab7855765 openvswitch: Avoid OOB read when parsing flow nlattrs
 ▪ 456abd7e6906 Merge e4646b07ba96d4110362310266f05f27d42bc360 on remote branch
 ▪ 31511c45450c msm: vidc: ensure codec count is in supported session range
 ▪ 1cd5dca726fc iommu: dma-mapping-fast: Add a check for count in fast_smmu_alloc
 ▪ bbf63965d13c ARM: dts: mdm: Disable dynamic address for wlan ramdump
 ▪ 7a456f3b681b gemini_defconfig: enable Ainur DTS hardware driver
 ▪ 8ced5cf42fde defconfig: enable dts eagle and mbhc
 ▪ 40fd6159f879 sound: soc: codecs: wcd-mbhc-v2: Uncomment g_DebugMode check
 ▪ 06a9c344f462 sound: wcd9335: Disable g_DebugMode
 ▪ 5eb09b047657 Initial AudioWizard bringup
 ▪ 42ca9843f9c7 sound: DTS-Eagle integration
 ▪ a4b9aea62332 drivers: import of dts_eagle hardware driver
 ▪ 95a8490effb4 Kconfig: msm: remove deprecated dts eagle driver
 ▪ d190cf2e9d9d Merge "qcacld-2.0: Support P2P by one wlan interface"
 ▪ 7d1008d4e336 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into 9.0
 ▪ c7da3ff8d4d9 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into 9.0
 ▪ dc33120a6c58 Merge "qcacld-2.0: Get tsf by register" into wlan-cld2.driver.lnx.1.0
 ▪ d52cdfb97c31 Merge "qcacld-2.0: Add macro WLAN_FEATURE_11W" into wlan-cld2.driver.lnx.1.0
 ▪ b81f2f1cca0a Merge "qcacld-2.0: Adjust motion detection threshold variables as 32bit" into wlan-cld2.driver.lnx.1.0
 ▪ a3dd75596f0d checkpatch: Treat duplicate signatures as a different error class
 ▪ 8ef3339ceb94 Merge "qcacld-2.0: Break out of OOB task after entering suspend mode" into wlan-cld2.driver.lnx.1.0
 ▪ ef56d315e42e gemini: update defconfig
 ▪ f3ad210c3dbe qcacld-2.0: Break out of OOB task after entering suspend mode
 ▪ 9b71f4ece3d8 qcacld-2.0: Get tsf by register
 ▪ 63d421f545c2 qcacld-2.0: Add macro WLAN_FEATURE_11W
 ▪ 4681ca54cf29 qcacld-2.0: CL 5538220 - CL 6359821 Update fw common interface files
 ▪ e2ece667fca3 Merge branch 'upstream-linux-3.18.y' of https://android.googlesource.com/kernel/common into 9.0
 ▪ c9e9a631b93f Merge 3.18.133 into kernel.lnx.3.18.r34-rel
 ▪ 4c35624dcb3b Linux 3.18.133
 ▪ aa2f510a0698 mm, proc: be more verbose about unstable VMA flags in /proc/<pid>/smaps
 ▪ fd1f97162fc5 ocfs2: fix panic due to unrecovered local alloc
 ▪ 5f95437eca3a sysfs: Disable lockdep for driver bind/unbind files
 ▪ 98b701339c76 ALSA: bebob: fix model-id of unit for Apogee Ensemble
 ▪ 1d8db45d3178 dm snapshot: Fix excessive memory usage and workqueue stalls
 ▪ 4982226e1d2d dm kcopyd: Fix bug causing workqueue stalls
 ▪ 4f7d2b60ce73 perf parse-events: Fix unchecked usage of strncpy()
 ▪ 7b20a6d4059a perf svghelper: Fix unchecked usage of strncpy()
 ▪ a8734066c0e0 mmc: atmel-mci: do not assume idle after atmci_request_end
 ▪ b0787de81787 kconfig: fix memory leak when EOF is encountered in quotation
 ▪ 8cd9a9440366 clk: imx6q: reset exclusive gates on init
 ▪ 2ace487a93fb scsi: target: use consistent left-aligned ASCII INQUIRY data
 ▪ 5a571a9e9d11 net: call sk_dst_reset when set SO_DONTROUTE
 ▪ 90463551f5c2 media: firewire: Fix app_info parameter type in avc_ca{,_app}_info
 ▪ 15a6405ca56d powerpc/pseries/cpuidle: Fix preempt warning
 ▪ ec7f99261da9 pstore/ram: Do not treat empty buffers as valid
 ▪ fa1e3a488c3d jffs2: Fix use of uninitialized delayed_work, lockdep breakage
 ▪ 84a9b63d087c MIPS: SiByte: Enable swiotlb for SWARM, LittleSur and BigSur
 ▪ f9eb72f770b8 r8169: Add support for new Realtek Ethernet
 ▪ e23a15823085 media: vb2: be sure to unlock mutex on errors
 ▪ 661fda257248 drm/fb-helper: Ignore the value of fb_var_screeninfo.pixclock
 ▪ a17189a0e107 block/loop: Use global lock for ioctl() operation.
 ▪ ca554dae5b07 sctp: allocate sctp_sockaddr_entry with kzalloc
 ▪ f643372c915b selinux: fix GPF on invalid policy
 ▪ 855486747309 sunrpc: handle ENOMEM in rpcb_getport_async
 ▪ babd8d8ca362 media: vb2: vb2_mmap: move lock up
 ▪ 3c2350d7ef6b media: vivid: set min width/height to a value > 0
 ▪ 16e187691b47 media: vivid: fix error handling of kthread_run
 ▪ c089cbb7c47f omap2fb: Fix stack memory disclosure
 ▪ 1f884727597e Disable MSI also when pcie-octeon.pcie_disable on
 ▪ 14e1fc9488db mfd: tps6586x: Handle interrupts on suspend
 ▪ 6f5685a49afe scsi: sd: Fix cache_type_store()
 ▪ d90b262c51ce Yama: Check for pid death before checking ancestry
 ▪ ca225877ef6e btrfs: wait on ordered extents on abort cleanup
 ▪ 98d2b2486aea crypto: authenc - fix parsing key with misaligned rta_len
 ▪ 23009dc3d4ff net: bridge: fix a bug on using a neighbour cache entry without checking its state
 ▪ 8c871bdbd02f packet: Do not leak dev refcounts on error exit
 ▪ 4d97ac0053d1 ipv6: fix kernel-infoleak in ipv6_local_error()
 ▪ 3ce837acc94f media: em28xx: Fix misplaced reset of dev->v4l::field_count
 ▪ 4c3b21c842de can: gw: ensure DLC boundaries after CAN frame modification
 ▪ 975156125866 tty/ldsem: Wake up readers after timed out down_write()
 ▪ b1c0a2b920e6 sunrpc: use-after-free in svc_process_common()
 ▪ ddcd89ca5313 crypto: cts - fix crash on short inputs
 ▪ 96e2cd7a68cf i2c: dev: prevent adapter retries and timeout being set as minus value
 ▪ fe19dc973bbd ACPI: power: Skip duplicate power resource references in _PRx
 ▪ 67dd0eda360a slab: alien caches must not be initialized if the allocation of the alien cache failed
 ▪ 84fe5c6e95e6 USB: storage: add quirk for SMI SM3350
 ▪ 5a2cac02dc5d USB: storage: don't insert sane sense for SPC3+ when bad sense specified
 ▪ 93e95567e918 usb: cdc-acm: send ZLP for Telit 3G Intel based modems
 ▪ ac72ab69de66 cifs: Fix potential OOB access of lock element array
 ▪ de92e4baf2b8 CIFS: Do not hide EINTR after sending network packets
 ▪ 0c9c58b95e9f sparc32: Fix inverted invalid_frame_pointer checks on sigreturns
 ▪ 783763b498e3 Merge "qcacld-2.0: Implement OOB"
 ▪ fb273167b276 Merge "usb: gadget: f_mbim: Handle response complete before notify_complete"
 ▪ 7da17324159e Merge "usb: gadget: f_mbim: Remove usage of notify_state"
 ▪ 05785d3ef7cf Merge "msm: ais: ispif: Fix invalid type conversion"
 ▪ fcf2003ca763 usb: gadget: f_mbim: Handle response complete before notify_complete
 ▪ ea0b49d0aedc usb: gadget: f_mbim: Use notify_req_queued instead of notify_count
 ▪ 2fd9d83d0f79 usb: gadget: f_mbim: Remove usage of notify_state
 ▪ d6ca021d836c Merge "SoC: msm: Add global mutex lock to fix the panic issue"
 ▪ d5c38b659dc0 fs: sdfat: Update to version 2.1.8
 ▪ 6904e1d4071f SoC: msm: Add global mutex lock to fix the panic issue
 ▪ 896c52389f66 Merge "iommu/iommu-debug: fix buffer overflows in debugfs read functions"
 ▪ 2da4cabe233d diag: Mark Buffer as NULL after freeing
 ▪ 2139c12dc521 Merge e4646b07ba96d4110362310266f05f27d42bc360 on remote branch
 ▪ b47ea715bc8d Merge f30aab2c62ed507f70ac4e556c8aeec56d2e3512 on remote branch
 ▪ 0665566fadbe iommu/iommu-debug: fix buffer overflows in debugfs read functions
 ▪ 574f07b177d3 qcacld-2.0: Support P2P by one wlan interface
 ▪ 0c17021acf84 qcacld-2.0: Adjust motion detection threshold variables as 32bit
 ▪ 073157f132a0 Merge "ARM: dts: mdm: Enable dynamic address for wlan ramdump"
 ▪ 4ad3c68a6159 Merge "msm: camera: isp: Fix invalid type conversion"
 ▪ def889f031f6 Merge "qcacld-2.0: Add reset resume rather than cold reset target" into wlan-cld2.driver.lnx.1.0
 ▪ 2dc96e8f3253 qcacld-2.0: Add reset resume rather than cold reset target
 ▪ abd7c6679c00 ARM: dts: mdm: Enable dynamic address for wlan ramdump
 ▪ bec96ef8d22e msm: ais: ispif: Fix invalid type conversion
 ▪ cc299d2ae99c diag: Handle data ready notification properly
 ▪ ef23d54b4bd1 Merge changes  into msm-3.18.c13
 ▪ f5b56a441064 Merge "msm: wlan: Update ETSI1 and ETSI13 countries"
 ▪ 8cb0444808b8 msm: wlan: Update ETSI1 and ETSI13 countries
 ▪ 59e5f7693d9e Merge branch 'upstream-linux-3.18.y' of https://android.googlesource.com/kernel/common into test
 ▪ 2a73ead40ed3 Merge "qcacld-2.0: Check connected peer number before enable MAC Counter"
 ▪ a158b3824d3e msm: camera: isp: Fix invalid type conversion
 ▪ e5c0af54a75e Merge "qcacld-2.0: Validate all channels for avoid_freq channel list" into wlan-cld2.driver.lnx.1.0
 ▪ cf86e7b4eceb qcacld-2.0: Implement OOB
 ▪ ca80b231a620 qcacld-2.0: Enable 11W feature for pci interface
 ▪ 2e8f09947e3c qcacld-2.0: Check connected peer number before enable MAC Counter
 ▪ 88a2955b0e2d Merge "mdm: Update frequence & Tx power in the regulatory database"
 ▪ 6d2a86f35ba4 mdm: Update frequence & Tx power in the regulatory database
 ▪ ce471b3b6c6e netfilter: x_tables: kill check_entry helper
 ▪ e4646b07ba96 qcacld-2.0: Fix KW issues in WLAN driver
 ▪ e0755445fd70 qcacld-2.0: Validate all channels for avoid_freq channel list
 ▪ 73f8ae5803ec drivers: iio: imu: increased the ASM buffer size
 ▪ 6702aaecbc88 Merge "qcacld-2.0: Update regulatory information" into wlan-cld2.driver.lnx.1.0
 ▪ 41a73ec02310 qcacld-2.0: Update regulatory information
 ▪ 787d6ca0b685 Merge 3.18.132 into kernel.lnx.3.18.r34-rel
 ▪ 9b5eed105a45 Linux 3.18.132
 ▪ a7e728f9bb0d power: supply: olpc_battery: correct the temperature units
 ▪ 6ca24838257b genwqe: Fix size check
 ▪ de7700c6e16c ceph: don't update importing cap's mseq when handing cap export
 ▪ d5b64fa4b0a4 9p/net: put a lower bound on msize
 ▪ a246a603cee7 b43: Fix error in cordic routine
 ▪ 69473af5e6dc gfs2: Fix loop in gfs2_rbm_find
 ▪ dc64743ba847 dlm: memory leaks on error path in dlm_user_request()
 ▪ edabeee7db8a dlm: lost put_lkb on error path in receive_convert() and receive_unlock()
 ▪ 96c0e283b5b2 dlm: possible memory leak on error path in create_lkb()
 ▪ 7d5345b7eeb5 dlm: fixed memory leaks after failed ls_remove_names allocation
 ▪ 0ba61349a8b3 ALSA: usb-audio: Fix an out-of-bound read in create_composite_quirks
 ▪ 172236e69b71 ALSA: usb-audio: Avoid access before bLength check in build_audio_procunit()
 ▪ cfd3b3d7b2ca ALSA: cs46xx: Potential NULL dereference in probe
 ▪ d6033169228e sunrpc: use SVC_NET() in svcauth_gss_* functions
 ▪ fde5c5a25420 sunrpc: fix cache_head leak due to queued request
 ▪ 0b2758fb10d9 fork: record start_time late
 ▪ 5f7387d7a014 scsi: zfcp: fix posting too many status read buffers leading to adapter shutdown
 ▪ 7336f81f5a20 CIFS: Fix error mapping for SMB2_LOCK command which caused OFD lock problem
 ▪ 5a4eafc735f7 MIPS: Align kernel load address to 64KB
 ▪ a0615204e659 MIPS: Ensure pmd_present() returns false after pmd_mknotpresent()
 ▪ 4816ed56768a media: vivid: free bitmap_cap when updating std/timings/etc.
 ▪ 9db4e7e1723c cdc-acm: fix abnormal DATA RX issue for Mediatek Preloader.
 ▪ b7c6fd47260a ext4: force inode writes when nfsd calls commit_metadata()
 ▪ cf161cde3d8e ext4: missing unlock/put_page() in ext4_try_to_write_inline_data()
 ▪ d3f10a011652 ext4: fix possible use after free in ext4_quota_enable
 ▪ af860a6a026a KVM: x86: Use jmp to invoke kvm_spurious_fault() from .fixup
 ▪ f47e855a6f8d usb: r8a66597: Fix a possible concurrency use-after-free bug in r8a66597_endpoint_disable()
 ▪ 35fb697e42c1 USB: serial: pl2303: add ids for Hewlett-Packard HP POS pole displays
 ▪ ef5dd2c94a7a sock: Make sock->sk_stamp thread-safe
 ▪ b12bad3dbdba xen/netfront: tolerate frags with no data
 ▪ 18167f943824 VSOCK: Send reset control packet when socket is partially bound
 ▪ 66506fe26abe vhost: make sure used idx is seen before log in vhost_add_used_n()
 ▪ 0302c665336f sctp: initialize sin6_flowinfo for ipv6 addrs in sctp_inet6addr_event
 ▪ a782cc8f6fcb packet: validate address length if non-zero
 ▪ 6a40c2da9c01 packet: validate address length
 ▪ 1c85a9064fbf netrom: fix locking in nr_find_socket()
 ▪ 3f312889bd81 isdn: fix kernel-infoleak in capi_unlocked_ioctl
 ▪ 364d1d5ae51f ipv6: explicitly initialize udp6_addr in udp_sock_create6()
 ▪ 9514524de958 ibmveth: fix DMA unmap error in ibmveth_xmit_start error path
 ▪ 7f93d703e276 ax25: fix a use-after-free in ax25_fillin_cb()
 ▪ ce6308a393a1 x86/mtrr: Don't copy uninitialized gentry fields back to userspace
 ▪ 0035d2a8e715 Drivers: hv: vmbus: Return -EINVAL for the sys files for unopened channels
 ▪ fdf0f5820b2f gpio: max7301: fix driver for use with CONFIG_VMAP_STACK
 ▪ 8bf6720ca034 mmc: omap_hsmmc: fix DMA API warning
 ▪ 7007d9ea8cdc mmc: core: Reset HPI enabled state during re-init and in case of errors
 ▪ 73cc953b0130 USB: serial: option: add HP lt4132
 ▪ 2dbfeb339325 USB: hso: Fix OOB memory access in hso_probe/hso_get_config_data
 ▪ ff71e8a509bf qcacld-2.0: Avoid possible buffer over-read in wma_wow_wakeup_host_event

 ▼ packages/apps/Bluetooth/
 ▪ 05aa041a [automerger skipped] Merge "DO NOT MERGE Separate SDP procedure from bonding state (2/2)" into oc-dev am: ed55dbca29 -s ours am: c025c672c6 -s ours am: 1afe196758 -s ours am skip reason: subject contains skip directive
 ▪ 1afe1967 [automerger skipped] Merge "DO NOT MERGE Separate SDP procedure from bonding state (2/2)" into oc-dev am: ed55dbca29 -s ours am: c025c672c6 -s ours am skip reason: change_id Ic43bb63fa5d4f10e08e577483f568f8025f0b1f3 with SHA1 36ba892cf9 is in history
 ▪ c025c672 [automerger skipped] Merge "DO NOT MERGE Separate SDP procedure from bonding state (2/2)" into oc-dev am: ed55dbca29 -s ours am skip reason: change_id Ic43bb63fa5d4f10e08e577483f568f8025f0b1f3 with SHA1 36ba892cf9 is in history
 ▪ ed55dbca Merge "DO NOT MERGE Separate SDP procedure from bonding state (2/2)" into oc-dev
 ▪ 2ba23e71 [automerger skipped] [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9 am: a37455ef23 am: 2ef64864b7 am: 0603c80387 skipped: 42b2fd9bd5 am: 88476a1f2e am: 8119536c70 am: 08f3a876f6 -s ours am skip reason: subject contains skip directive
 ▪ 08f3a876 [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9 am: a37455ef23 am: 2ef64864b7 am: 0603c80387 skipped: 42b2fd9bd5 am: 88476a1f2e am: 8119536c70
 ▪ 8119536c [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9 am: a37455ef23 am: 2ef64864b7 am: 0603c80387 skipped: 42b2fd9bd5 am: 88476a1f2e
 ▪ cf2d818b [automerger skipped] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 43a19bd8c8 -s ours am skip reason: subject contains skip directive
 ▪ 88476a1f [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9 am: a37455ef23 am: 2ef64864b7 am: 0603c80387 skipped: 42b2fd9bd5
 ▪ 42b2fd9b [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9 am: a37455ef23 am: 2ef64864b7 am: 0603c80387
 ▪ 0603c803 [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9 am: a37455ef23 am: 2ef64864b7
 ▪ 2ef64864 [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9 am: a37455ef23
 ▪ a37455ef [automerger] DO NOT MERGE Separate SDP procedure from bonding state (2/2) am: 36ba892cf9
 ▪ 36ba892c DO NOT MERGE Separate SDP procedure from bonding state (2/2)
 ▪ 00636461 DO NOT MERGE Separate SDP procedure from bonding state (2/2)
 ▪ 43a19bd8 DO NOT MERGE Separate SDP procedure from bonding state (2/2)
 ▪ a29d5580 DO NOT MERGE Separate SDP procedure from bonding state (2/2)
 ▪ 88081626 Merge tag 'android-9.0.0_r33' into pie
 ▪ 15a58f55 Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/packages/apps/Bluetooth into HEAD
 ▪ 49a2fc59 Merge "MAP: Don't start/stop on broadcast intent" into pi-dev
 ▪ 74f0625d Import translations. DO NOT MERGE

 ▼ packages/apps/Camera2/
 ▪ 0cfea440d Snap for 5180536 from 838861c5f58bfd1750ec83354b7c01d3bc41ac74 to pi-platform-release

 ▼ packages/apps/CarrierConfig/
 ▪ 01ecac7 Snap for 5180536 from b9bad705178410c34bf4e4ed4f60964c45d0c2a5 to pi-platform-release
 ▪ e0f0803 CarrierConfig: HoT and tele.ring (232 07) may roam on T-Mobile (232 03)
 ▪ 691a8f9 Disable OTA for U.S. Cellular since there is no need for it
 ▪ cd73637 CarrierConfig: Load ERI configuration for U.S. Cellular
 ▪ dce191b CarrierConfig: Add selected configs for national roaming

 ▼ packages/apps/CellBroadcastReceiver/
 ▪ 1e41394 Snap for 5180536 from d51900a0b9ac2cc775dc5c7a9c53331ba7dd83e8 to pi-platform-release
 ▪ 8b65a10 Merge tag 'android-9.0.0_r33' into pie
 ▪ 3f37c34 Snap for 5251742 from 438adb6e7261b94698c7a4c0c1ba952ab14a2c39 to pi-qpr3-release
 ▪ 438adb6 Merge "Fixed that emergency alert not displayed when screen saver is on" into pi-dev
 ▪ acc8df3 Fixed that emergency alert not displayed when screen saver is on

 ▼ packages/apps/Contacts/
 ▪ 57240e7df Snap for 5180536 from 166e3c8d175852bb21cf1b36cca361ff20c5ce35 to pi-platform-release
 ▪ c0a911bb4 Merge tag 'android-9.0.0_r33' into pie
 ▪ 368d7cad1 Snap for 5249487 from cf0abd74545327f412d2b42c7b6d7e4a5af6741d to pi-qpr3-release
 ▪ cf0abd745 Import translations. DO NOT MERGE
 ▪ e6acaf57b Merge "Snap for 5230900 from 4be56a13f5ab9c9ac064f940a2e6f105e552c1a3 to pi-platform-release am: 6be4a615d8" into pie-gsi
 ▪ 6e4d6569f Snap for 5230900 from 4be56a13f5ab9c9ac064f940a2e6f105e552c1a3 to pi-platform-release am: 6be4a615d8
 ▪ 6be4a615d Snap for 5230900 from 4be56a13f5ab9c9ac064f940a2e6f105e552c1a3 to pi-platform-release
 ▪ 7e14b03d2 Import translations. DO NOT MERGE
 ▪ 4be56a13f January Pi-platform-release merges

 ▼ packages/apps/CustomDoze/
 ▪ 3320e77 Use some Pixel strings
 ▪ a1fa47e Make tilt and proximity sensor options optional
 ▪ f968bdc Ensure Tilt sensor preference is off when Always On is enabled
 ▪ 6038e7e TiltSensor:  I have been Triggered
 ▪ c7c43f1 Ambient brightness values: use a custom system setting [2/2]
 ▪ 95e775e Welcome Custom Doze
 ▪ b63b9fb Allow to change default Ambient brightness values
 ▪ 0a8569a Add AoD option to CustomDoze

 ▼ packages/apps/DocumentsUI/
 ▪ 9a562d7a Snap for 5180536 from 84fbb75721e04ca207ba4e29dd3120076db066f3 to pi-platform-release
 ▪ f7f98bda Theme improvements
 ▪ 074de58f Use white navbar for DocumentsUI as well
 ▪ 21855582 DocumentsUI: Thematize navbar on dark theme
 ▪ c4b814d2 Theme: Make sure swipe refresh follows the system theme
 ▪ d9cb80ae Merge tag 'android-9.0.0_r33' into pie
 ▪ 18af6766 DocumentsUI: Expose some layouts for themes
 ▪ 1d356f2c DocumentsUI: Fix actionbar color when selecting items

 ▼ packages/apps/EmergencyInfo/
 ▪ a577a6e Snap for 5180536 from f9f7193d45b9fc3abbffa11d61c369c07cf4e993 to pi-platform-release
 ▪ 79aad9c EmergencyInfo: Fix theme
 ▪ f3c7cbd Import translations. DO NOT MERGE

 ▼ packages/apps/FMRadio/
 ▪ 34db918 FMRadio: build with AAPT2

 ▼ packages/apps/HavocSettings/
 ▪ 2b7fb78 Settings: Add CustomDoze
 ▪ 68a50c1 Revert "Allow tuning ambient display with sensors [2/3]"
 ▪ 977c9a1 Add more lockscreen clock styles
 ▪ bdc8bcf Settings: PA PIE Controls 3.0 [3/3]
 ▪ 0ba8a00 Settings: add Cookie QS style [3/3]
 ▪ 5c3e589 Settings: qs status bar header image [2/4]
 ▪ 8e55bd2 Add sammy accent clock and a variant [2/2]
 ▪ e5416fe Implement animations for back edge gestures [2/2]
 ▪ 01efd7e Add edge gestures (2/2)
 ▪ a25a4a1 Set typeface to medium for statusbar texts
 ▪ 02ec876 Slim recents: re-enable expanded mode always [2/2]
 ▪ 458c17f Edit Icon Toggle [2/2]
 ▪ 3e97321 settings: notch-city: Add 3 mode display cutout handler [3/3]
 ▪ 4bf1d31 Introduce lockscreen clock/date styles [2/2]
 ▪ 5e65b89 Hide lockscreen items [2/2]
 ▪ d91a6eb Revert "Pocket judge"
 ▪ f465b35 Settings: Add double tap option to lockscreen shortcuts [2/2]
 ▪ 3f2c1de Settings: Lockscreen shortcuts improvements [2/2]
 ▪ 901ff21 Settings: add user configurable lockscreen shortcuts [2/2]
 ▪ d856c8a Ambient Visualizer [2/2]
 ▪ 52b07cd RoundCorners: Update seekbars when framework values toggled
 ▪ 4e07cea RoundCorners: Add fw values corner preferences

 ▼ packages/apps/Messaging/
 ▪ 98538d4 Messaging - Breathing missedcall/sms/voicemail [4/5]
 ▪ d9f9511 Messaging: adaptive icon
 ▪ 006cdae Messaging: define app category
 ▪ 18cb82c Messaging: Add "Mark as read" quick action for message notifications
 ▪ 9735ed6 Fix compilation warnings
 ▪ 9399924 Pixelize all things
 ▪ d88efb6 Vectorized checkmark drawable
 ▪ 9a3caaf Allow app disable
 ▪ dd339d2 Fixed vcard handling
 ▪ d74f6e5 Use light navigation bar
 ▪ 5627280 Add 'new message' shortcut using the API introduced in sdk25
 ▪ e351286 Messaging: Fix crash of blocked participant list activity
 ▪ 8f41e9b Messaging: Don't crash on unsupported shared content type
 ▪ 9320190 MediaPicker: Check for NPE
 ▪ 67ee0fd Messaging: fix bad recycle on sending two mms in a row
 ▪ b01e266 Use app settings for conversation settings if no custom set
 ▪ 1be5d6e Messaging app crashes after a few MMS
 ▪ b7d9778 Fixed storage permission issue for attachments
 ▪ 8b91c24 Added support for video and audio mms attachments
 ▪ c519dcc Play an audible notification on receiving a class zero message.
 ▪ dfc1805 Messaging: Implement saved video attachments in MMS
 ▪ f4c8d1c Messaging App is crashing when storage memory is full
 ▪ 9c9d5c7 Fix menu item highlight color.
 ▪ 5975d91 Messaging: Toggable keyboard emoticons access
 ▪ 575c3fd MessageQueue: Process pending messages per subscription
 ▪ f7b7f1d Messaging: change Avatar fontFamily to sans-serif-medium
 ▪ 1eea49d Messaging: Implement option for swipe right to delete.
 ▪ 2b80a2a Change theme for the open source license dialog

 ▼ packages/apps/Nfc/
 ▪ c04e4026 Snap for 5180536 from 81ed378559c43c8da4a4b20a290e4519d29a4598 to pi-platform-release
 ▪ bacf6891 Merge tag 'android-9.0.0_r33' into pie

 ▼ packages/apps/OmniStyle/
 ▪ ffd7046 OmniStyle: Use settings icon
 ▪ 61926a7 OmniStyle: Add itsaalex poison headers
 ▪ 79f391b OmniStyle: Add 'Space' headers
 ▪ 5cc5faa OmniStyle: Add 'Colorful' headers
 ▪ be4f9ad OmniStyle: Remove theme chooser
 ▪ b3552e1 OmniStyle: Remove omni headers
 ▪ 40ae12d OmniStyle: Remove translations
 ▪ a37f47c OmniStyle: Remove weather images
 ▪ c7eeac6 OmniStyle: Remove wallpaper settings
 ▪ dfb6484 OmniStyle: qs status bar header image [3/4]
 ▪ 26dcb77 OmniStyle: theme compose: fix button text color to white

 ▼ packages/apps/PackageInstaller/
 ▪ 0e9d43d3 Snap for 5180536 from ded9a473ea2f7691b7e65296ec7d19c06d6dee99 to pi-platform-release
 ▪ 0dea7339 Merge tag 'android-9.0.0_r33' into pie
 ▪ 1f32083c PackageInstaller: Change header color to match Settings
 ▪ 2d89e2cf PackageInstaller: make permissions header match settings style
 ▪ 2d763bd5 Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 6c613fd7 Ask for PIN when granting permissions in front of lock screen
 ▪ 4ca02067 Merge "Snap for 5230900 from 31195c7d898f1e59f04bc395727b17af3558e4dd to pi-platform-release am: 675955185b" into pie-gsi
 ▪ 0c7d90db Snap for 5230900 from 31195c7d898f1e59f04bc395727b17af3558e4dd to pi-platform-release am: 675955185b
 ▪ 7ab331fd Ask for PIN when granting permissions in front of lock screen
 ▪ 67595518 Snap for 5230900 from 31195c7d898f1e59f04bc395727b17af3558e4dd to pi-platform-release
 ▪ 31195c7d January Pi-platform-release merges

 ▼ packages/apps/Recorder/

 ▼ packages/apps/Settings/
 ▪ 6a1ce0b4fd Move in pin ripple settings
 ▪ 98cdb732ce Snap for 5180536 from c103b546d2e33aacd8187a6bf54b28efa325ffbe to pi-platform-release
 ▪ 416aeb83f8 Settings: Adapt for vendor_support
 ▪ 084b1e1a7c Utilize our support vendor
 ▪ 3717af8b12 Revert "Allow tuning ambient display with sensors [3/3]"
 ▪ ffbc7cfc9a Settings: Change some dashboard icon colors
 ▪ 46d9273eea Implement per-app thermal control [1/3]
 ▪ 5e4140f1a5 Merge tag 'android-9.0.0_r33' into pie
 ▪ 219a2222f8 Themes: Convert sync icons to vector so they theme correctly
 ▪ 294aeb605b Settings: Bring back Uptime
 ▪ 8f72fcedd9 Update sim colors [2/4]
 ▪ 60fb89c649 StorageSummaryPreference: Nuke hardcoded color
 ▪ 51baf217fe StorageSettings: Use pixel color in storage bar / icon
 ▪ 3a72abdabd Settings: PA PIE Controls 3.0 [2/3]
 ▪ 676c2e09ca Settings: Power detail pages: Finish off the rest of the icon tinting
 ▪ d204f7dd02 Settings: fix icon tinting in power detail pages
 ▪ 4613c85712 Settings: Add preference for EdgeGestureService [2/3]
 ▪ ff6b4b5cc4 Settings: Remove obsolete LOCAL_JACK_ENABLED
 ▪ fbdf6aa4cb Settings: Add FINE_LOCATION for Bluetooth scans
 ▪ c1cf4ceab9 Snap for 5249487 from e60e0d22916bdf6af214b2f3ff0237b6daf71ac7 to pi-qpr3-release
 ▪ 5bd5e79ea0 QS dev tiles: Don't set them to active area
 ▪ 82f0646992 Display 'Dash charging' for dash charge in battery settings [2/2]
 ▪ e60e0d2291 Import translations. DO NOT MERGE
 ▪ e18f734843 Import translations. DO NOT MERGE

 ▼ packages/apps/SmartNav/
 ▪ b513d9a Allow home action on keyguard
 ▪ 3163af8 Intercept one handed mode gesture

 ▼ packages/apps/SmartNavSettings/
 ▪ f4331e4 Settings: Adapt for vendor_support
 ▪ 4fedaf8 Add translations

 ▼ packages/apps/Snap/
 ▪ 3f64df285 Merge 4fc685f3217532da4d5d7bc0f2c8b289d1036c35 on remote branch
 ▪ c8c7085a9 Snap: make support for bokeh mode configurable per device
 ▪ 180423cf6 Snap: Yet Another String Improvement

 ▼ packages/apps/Terminal/

 ▼ packages/apps/ThermalController/
 ▪ 4bd4118 Implement per-app thermal control [3/3]
 ▪ c475703 Update README.md
 ▪ 1e7c2c7 Initial commit

 ▼ packages/apps/Updater/

 ▼ packages/inputmethods/LatinIME/
 ▪ 20de0ce61 Snap for 5180536 from 556b091a754cadd239102086bbcfa77e5afe6ba4 to pi-platform-release
 ▪ 478017a2f Merge tag 'android-9.0.0_r33' into pie
 ▪ 06c8063be Merge "Import translations. DO NOT MERGE" into pi-dev
 ▪ 54b7ed4a9 Import translations. DO NOT MERGE
 ▪ ab4f7ace7 Import translations. DO NOT MERGE

 ▼ packages/providers/DownloadProvider/
 ▪ ac2c2c0 Snap for 5180536 from 91873a4c1851268f0b7f86cc33bb3403fe24b2ad to pi-platform-release
 ▪ effe797 Import translations. DO NOT MERGE

 ▼ packages/providers/MediaProvider/
 ▪ f0d22e1 Snap for 5180536 from 01ba7e7dd6506c59bd25312c9e910424a20d113f to pi-platform-release
 ▪ 635ad6d Merge tag 'android-9.0.0_r33' into pie

 ▼ packages/providers/WeatherProvider/
 ▪ 108e29d Force stop application if running for more than 60 seconds
 ▪ c99fc2f WeatherProvider: Update google play services libs

 ▼ packages/services/Telecomm/
 ▪ 053978e2 Snap for 5180536 from 5980327bb95f8bdcf49f6cea4dcd5ae8e40df6c9 to pi-platform-release
 ▪ 30f01ff3 Merge tag 'android-9.0.0_r31' into lineage-16.0-android-9.0.0_r31
 ▪ a939225c Merge ef7b025686c0753db6af9ecea548c5990e793c06 on remote branch
 ▪ 2a8b5799 Merge branch 'pie' of https://github.com/Havoc-OS/android_packages_services_Telecomm into caf
 ▪ 89995355 Merge tag 'android-9.0.0_r33' into pie
 ▪ e7eea280 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telecomm into caf
 ▪ e3f8c254 Merge ef7b025686c0753db6af9ecea548c5990e793c06 on remote branch
 ▪ 07440056 Snap for 5249487 from afa277116433fbaef3f29efc533b80bdffb6acb4 to pi-qpr3-release
 ▪ f53bd911 Merge ef7b025686c0753db6af9ecea548c5990e793c06 on remote branch
 ▪ afa27711 Import translations. DO NOT MERGE
 ▪ ef7b0256 Snap for 5233155 from 45ab2da937367fd909b563bfb919142c49f0cbc3 to p-keystone-qcom-release
 ▪ 45ab2da9 Merge "Unable to add exsiting connection with emergency only account" into p-keystone-qcom
 ▪ 156a6051 Snap for 5232626 from bff092587223bc0ee2066de89e0b83121cd9aaf8 to pi-b4s4-release
 ▪ bff09258 Import translations. DO NOT MERGE

 ▼ packages/services/Telephony/
 ▪ 9fe4e2a7f Snap for 5180536 from 4c1f7769ecc14d90d005296607cf088df7625910 to pi-platform-release
 ▪ 97fbb7294 Merge tag 'android-9.0.0_r31' into lineage-16.0-android-9.0.0_r31
 ▪ 0c9611ea2 Merge 0541a0821ee048b070ef5d2a42724a8ef5beabe8 on remote branch
 ▪ b4ce1a003 Snap for 5285806 from a3e0e945722114b5b33ad0f0117feb4484b4190b to pi-qpr3-release
 ▪ dd66e3974 Merge branch 'pie' of https://github.com/Havoc-OS/android_packages_services_Telephony into caf
 ▪ c178c0b85 Merge remote-tracking branch 'AOSP/pie-gsi' into pie
 ▪ 567462ffc Merge tag 'android-9.0.0_r33' into pie
 ▪ a3e0e9457 fix translations. DO NOT MERGE
 ▪ 7135b6066 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' of https://source.codeaurora.org/quic/la/platform/packages/services/Telephony into caf
 ▪ e52cc512d Merge 0541a0821ee048b070ef5d2a42724a8ef5beabe8 on remote branch
 ▪ b9b465648 Snap for 5249487 from d5c22e2ca51a2bf9cede60380b70486f34b7c908 to pi-qpr3-release
 ▪ 96d7ddd49 Merge 0541a0821ee048b070ef5d2a42724a8ef5beabe8 on remote branch
 ▪ d5c22e2ca Import translations. DO NOT MERGE
 ▪ ee726bea5 Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into caf
 ▪ c7d3e6a23 Merge branch 'pie' of https://github.com/Havoc-OS/android_packages_services_Telephony into caf
 ▪ 57040bcf2 USSD: Fix alert dialog theme
 ▪ e35b898f8 Snap for 5232626 from e62fa81e386ece97fa970a6f868026dac0c2c45a to pi-b4s4-release
 ▪ 54022c5ee Fix carrier config option not hidden on a CDMA phone
 ▪ 37320861c Don't start SIP service before decrypted
 ▪ f0b327033 Fix non-protected broadcasts sent from phone process.
 ▪ e62fa81e3 Import translations. DO NOT MERGE
 ▪ 021b5271c Fix carrier config option not hidden on a CDMA phone
 ▪ 347d811c0 Snap for 5224434 from 5e3a62208d1ac512bd162f2df93f675281065c4a to pi-b4s4-release
 ▪ 5e3a62208 Merge "Fix null pointer exception" into pi-dev
 ▪ 579126f71 Snap for 5222977 from fa3961b43b4b671531518350bbf6bf6152c551a2 to pi-b4s4-release

 ▼ prebuilts/abi-dumps/vndk/
 ▪ 28acf66 Update dumps for getCallingSid.

 ▼ prebuilts/build-tools/
 ▪ bc02ab9 build-tools: Update regular and asan ninja to v1.9.0
 ▪ 853ff9a build-tools: Update using latest source and clang-9
 ▪ 4e2e1a4 build-tools: Update regular and asan ckati
 ▪ 572f294 build-tools: Update ccache version to 3.6

 ▼ prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8/
 ▪ 639243d Check in a glibc 2.17 + gcc 4.8.3 toolchain am: 33581f7b65 am: 38a84132fa am: 10b3b0d2fd

 ▼ prebuilts/r8/
 ▪ fb1e50b r8: Update D8 and R8 to 1.5.3-dev
 ▪ 719f130 r8: Update D8/R8 to version 1.5.2-dev
 ▪ 3082fe5 r8: Update D8/R8 to version 1.4.25
 ▪ fc32c12 r8: Update D8/R8 to version 1.4.22-dev
 ▪ 6d0cefd r8: Update D8 and R8 to 1.4.21-dev
 ▪ 1f114c8 r8: Update D8 and R8 to 1.4.20-dev

 ▼ system/bt/
 ▪ 21dba69f7 Snap for 5180536 from 6f2759c64311b505b1ddc73e2bfc9f0330845780 to pi-platform-release
 ▪ 5980eefcf [automerger skipped] Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into oc-dev am: 99495df519 -s ours am: 8d550cccd6 -s ours am: 8500500386 -s ours am skip reason: subject contains skip directive
 ▪ e14f845fa [automerger skipped] DO NOT MERGE Separate SDP procedure from bonding state (1/2) am: 0989441858 -s ours am: a6d6406255 -s ours am: feeb53795a -s ours am skip reason: subject contains skip directive
 ▪ 850050038 [automerger skipped] Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into oc-dev am: 99495df519 -s ours am: 8d550cccd6 -s ours am skip reason: change_id I023713e07308bfc0e5bb8d67f386bcc50f6a0f85 with SHA1 f3681c8616 is in history
 ▪ feeb53795 [automerger skipped] DO NOT MERGE Separate SDP procedure from bonding state (1/2) am: 0989441858 -s ours am: a6d6406255 -s ours am skip reason: change_id I023713e07308bfc0e5bb8d67f386bcc50f6a0f85 with SHA1 f3681c8616 is in history
 ▪ 8d550cccd [automerger skipped] Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into oc-dev am: 99495df519 -s ours am skip reason: change_id I023713e07308bfc0e5bb8d67f386bcc50f6a0f85 with SHA1 0989441858 is in history
 ▪ a6d640625 [automerger skipped] DO NOT MERGE Separate SDP procedure from bonding state (1/2) am: 0989441858 -s ours am skip reason: change_id I023713e07308bfc0e5bb8d67f386bcc50f6a0f85 with SHA1 edd7e731ed is in history
 ▪ 99495df51 Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into oc-dev
 ▪ 02bf171fb Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into oc-dev am: c59317a10a am: d73d5ace07 am: 0cd9890f74
 ▪ 0cd9890f7 Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into oc-dev am: c59317a10a am: d73d5ace07
 ▪ d73d5ace0 Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into oc-dev am: c59317a10a
 ▪ 73c0e55db Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into nyc-dev
 ▪ 344f5a6a8 Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into nyc-mr2-dev
 ▪ e83832b82 Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into cw-f-dev
 ▪ 51f79d155 Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into nyc-mr1-dev
 ▪ 70597b3b0 Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into nyc-dr1-dev
 ▪ c59317a10 Merge changes from topic "am-43952131-a4db-4e42-bfef-2d44a29b3fac" into oc-dev
 ▪ c3ea07116 Merge "btm_proc_smp_cback: Don't access p_dev_rec if freed" into oc-dev am: 4ac889b785 am: c87e949d53 am: d59c9ec72e
 ▪ d59c9ec72 Merge "btm_proc_smp_cback: Don't access p_dev_rec if freed" into oc-dev am: 4ac889b785 am: c87e949d53
 ▪ dc9d0d8f1 [automerger skipped] Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into oc-mr1-dev am: c48874b71b -s ours am skip reason: subject contains skip directive
 ▪ 9028a3164 [automerger skipped] DO NOT MERGE Separate SDP procedure from bonding state (1/2) am: f3681c8616 -s ours am skip reason: subject contains skip directive
 ▪ c87e949d5 Merge "btm_proc_smp_cback: Don't access p_dev_rec if freed" into oc-dev am: 4ac889b785
 ▪ 4ac889b78 Merge "btm_proc_smp_cback: Don't access p_dev_rec if freed" into oc-dev
 ▪ c48874b71 Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into oc-mr1-dev
 ▪ 7799b0915 Merge "DO NOT MERGE Separate SDP procedure from bonding state (1/2)" into pi-dev
 ▪ 8c5cac9ac Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into oc-dev am: e145805974 am: 9b0e9a32bb am: 53e961c220
 ▪ 53e961c22 Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into oc-dev am: e145805974 am: 9b0e9a32bb
 ▪ 9b0e9a32b Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into oc-dev am: e145805974
 ▪ 80e5f34c2 Merge "DO NOT MERGE btm_proc_smp_cback: Don't access p_dev_rec if freed" into nyc-dev
 ▪ 2d6a30aae Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into nyc-mr2-dev
 ▪ 851a6333c Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into cw-f-dev
 ▪ 4ce286605 Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into nyc-mr1-dev
 ▪ a8cbe2d1f Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into nyc-dr1-dev
 ▪ e14580597 Merge changes from topic "am-5380790e-42fb-4784-96c0-4412e4fdccd0" into oc-dev
 ▪ dfd381e10 Snap for 5285806 from 812588ad71bf672864ea4051a32419f15f2bff69 to pi-qpr3-release
 ▪ 28193950c Merge tag 'android-9.0.0_r33' into pie
 ▪ 812588ad7 Merge changes from topic "am-cdd47550-8877-443a-826f-db2b25d750ce" into oc-dev am: 8ea254e227 am: 04f9bde9ea am: a99a5f342a
 ▪ a99a5f342 Merge changes from topic "am-cdd47550-8877-443a-826f-db2b25d750ce" into oc-dev am: 8ea254e227 am: 04f9bde9ea
 ▪ 04f9bde9e Merge changes from topic "am-cdd47550-8877-443a-826f-db2b25d750ce" into oc-dev am: 8ea254e227
 ▪ 1d280d7b0 Merge "DO NOT MERGE process_l2cap_cmd: Fix OOB" into nyc-dev
 ▪ 8ea254e22 Merge changes from topic "am-cdd47550-8877-443a-826f-db2b25d750ce" into oc-dev
 ▪ 6c0f22f32 resolve merge conflicts of ec78d74706c3e81f91eee53e3d9f959f66e5d77f to pi-dev
 ▪ ec78d7470 Merge "process_l2cap_cmd: Fix OOB" into oc-dev am: 356edb4333 am: 82365b0e8d
 ▪ 82365b0e8 Merge "process_l2cap_cmd: Fix OOB" into oc-dev am: 356edb4333
 ▪ 356edb433 Merge "process_l2cap_cmd: Fix OOB" into oc-dev
 ▪ 70ea66638 Snap for 5268384 from f4aa4700287798485eed1f356a32422d87f3569e to pi-qpr3-release
 ▪ dc14eb8ba DO NOT MERGE Separate SDP procedure from bonding state (1/2)
 ▪ f4aa47002 Merge "btm_ble_multi_adv: Check data length in HCI interface" into oc-dev am: 19460901d8 am: 154230b832 am: a3a57067d0
 ▪ a3a57067d Merge "btm_ble_multi_adv: Check data length in HCI interface" into oc-dev am: 19460901d8 am: 154230b832
 ▪ 154230b83 Merge "btm_ble_multi_adv: Check data length in HCI interface" into oc-dev am: 19460901d8
 ▪ 19460901d Merge "btm_ble_multi_adv: Check data length in HCI interface" into oc-dev
 ▪ ade3e18ab [automerger] DO NOT MERGE btm_proc_smp_cback: Don't access p_dev_rec if freed am: 74c6d501ce am: 059e3c77e2 am: a244a4072c am: 90265d4ee0 skipped: 84ba34d57a
 ▪ 84ba34d57 [automerger] DO NOT MERGE btm_proc_smp_cback: Don't access p_dev_rec if freed am: 74c6d501ce am: 059e3c77e2 am: a244a4072c am: 90265d4ee0
 ▪ 90265d4ee [automerger] DO NOT MERGE btm_proc_smp_cback: Don't access p_dev_rec if freed am: 74c6d501ce am: 059e3c77e2 am: a244a4072c
 ▪ 953dd2795 btm_proc_smp_cback: Don't access p_dev_rec if freed
 ▪ a244a4072 [automerger] DO NOT MERGE btm_proc_smp_cback: Don't access p_dev_rec if freed am: 74c6d501ce am: 059e3c77e2
 ▪ 059e3c77e [automerger] DO NOT MERGE btm_proc_smp_cback: Don't access p_dev_rec if freed am: 74c6d501ce
 ▪ 74c6d501c DO NOT MERGE btm_proc_smp_cback: Don't access p_dev_rec if freed
 ▪ 31dd859b0 [automerger] DO NOT MERGE process_l2cap_cmd: Fix OOB am: 38f07a3c93 am: 14f6578d9e am: 53e323b2af am: d0584f3dcf skipped: 55b702e6c4
 ▪ 55b702e6c [automerger] DO NOT MERGE process_l2cap_cmd: Fix OOB am: 38f07a3c93 am: 14f6578d9e am: 53e323b2af am: d0584f3dcf
 ▪ d0584f3dc [automerger] DO NOT MERGE process_l2cap_cmd: Fix OOB am: 38f07a3c93 am: 14f6578d9e am: 53e323b2af
 ▪ 53e323b2a [automerger] DO NOT MERGE process_l2cap_cmd: Fix OOB am: 38f07a3c93 am: 14f6578d9e
 ▪ 14f6578d9 [automerger] DO NOT MERGE process_l2cap_cmd: Fix OOB am: 38f07a3c93
 ▪ 38f07a3c9 DO NOT MERGE process_l2cap_cmd: Fix OOB
 ▪ 94fd011bc process_l2cap_cmd: Fix OOB
 ▪ a99fe8a17 btm_ble_multi_adv: Check data length in HCI interface
 ▪ b9dd38630 Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 488aa8bef DO NOT MERGE A security fix to check buffer length in l2c_lcc_proc_pdu
 ▪ b1c8f804d Snap for 5230900 from aa9c1b4abdb2ca7beea467f7be82e83363a32b11 to pi-platform-release am: e40c363dfa
 ▪ 39545b91c DO NOT MERGE A security fix to check buffer length in l2c_lcc_proc_pdu
 ▪ e40c363df Snap for 5230900 from aa9c1b4abdb2ca7beea467f7be82e83363a32b11 to pi-platform-release
 ▪ aa9c1b4ab January Pi-platform-release merges
 ▪ bf4354a67 Add OOB check in avrc_pars_browse_rsp
 ▪ 1ffc00175 Fix buffer overflow in btif_dm_data_copy
 ▪ 31e987d89 Fix potential usage of freed memory in btif_hl_proc_sdp_query_cfm
 ▪ e83b6bf2f Revert "Fix OOB in avrc_pars_browse_rsp"

 ▼ system/core/
 ▪ 6218aad8d init: increase thermal shutdown timeout to 3s
 ▪ 040df4144 Read memory stats from /proc/pid/stat file.
 ▪ 85dc66575 lmkd: Implement pid purge command to clear old pids when zygote restarts
 ▪ 3697e521d reboot: only run fsck when detecting filesystem inconsistency
 ▪ 618cda411 liblog: Silence spammy logs from camera blobs (AEC_PORT and mm-camera)

 ▼ system/extras/
 ▪ 971f8399 Snap for 5180536 from 9ec7ba8443caa905c2ebdf6eadd5e6148a348d37 to pi-platform-release
 ▪ 98741355 Merge remote-tracking branch 'AOSP/pie-gsi' into pie
 ▪ 17acc62e Merge tag 'android-9.0.0_r33' into pie
 ▪ 770153f0 Merge "Merge cherrypicks of [5929407, 5929627, 5929597, 5929598] into pi-platform-release am: cc6534f8b1" into pie-gsi
 ▪ b14537cb Merge cherrypicks of [5929407, 5929627, 5929597, 5929598] into pi-platform-release am: cc6534f8b1

 ▼ system/hwservicemanager/
 ▪ e609036 ACL based on getCallingSid

 ▼ system/libhidl/
 ▪ ee9c635 Add gServiceSidMap.

 ▼ system/libhwbinder/
 ▪ e2aef07 Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 7375a87 getCallingSid: get calling security context
 ▪ 8708d35 Deserialize a native_handle safely.
 ▪ e3b635c getCallingSid: get calling security context
 ▪ fc9ced2 Deserialize a native_handle safely.
 ▪ 14418a7 [automerger skipped] getCallingSid: get calling security context am: 683b6d043d am: d7acd8a870 -s ours am: 7e6b6dfb36 -s ours am skip reason: change_id Ia8a4c0cb4a9c86dcc0d3b7583014237f879a3074 with SHA1 f0a7d7899e is in history
 ▪ 7e6b6df [automerger skipped] getCallingSid: get calling security context am: 683b6d043d am: d7acd8a870 -s ours am skip reason: change_id Ia8a4c0cb4a9c86dcc0d3b7583014237f879a3074 with SHA1 f0a7d7899e is in history
 ▪ d7acd8a getCallingSid: get calling security context am: 683b6d043d
 ▪ c2cf9a1 [automerger skipped] getCallingSid: get calling security context am: f0a7d7899e -s ours am skip reason: change_id Ia8a4c0cb4a9c86dcc0d3b7583014237f879a3074 with SHA1 b935356c42 is in history
 ▪ 683b6d0 getCallingSid: get calling security context
 ▪ f0a7d78 getCallingSid: get calling security context
 ▪ b935356 getCallingSid: get calling security context

 ▼ system/netd/
 ▪ 3e51dd1 Snap for 5180536 from a80475564fdced61fa9853468e441a352b11ae08 to pi-platform-release
 ▪ 9762bc1 Clear Element.mRef immediately after deallocating it
 ▪ 3eeb0e6 Fix fortify_fatal issue during DNSServiceProcessResult()
 ▪ 75b20f7 Merge tag 'android-9.0.0_r33' into pie
 ▪ ad883b9 Fix use-after-free in NetworkController::removeInterfaceAddress()

 ▼ system/nfc/
 ▪ a61f62c Snap for 5285806 from ed4fb4ef9fa2f1868ed23f245cd5ec0e13b7a7d3 to pi-qpr3-release
 ▪ ed4fb4e Merge "Prevent OOB error in rw_i93_process_ext_sys_info()" into pi-dev
 ▪ 34eb982 Merge "Prevent OOB read in rw_i93_process_sys_info()" into oc-dev am: 2c605825f8 am: 6430e95d82 am: 404c66d3f1
 ▪ 404c66d Merge "Prevent OOB read in rw_i93_process_sys_info()" into oc-dev am: 2c605825f8 am: 6430e95d82
 ▪ 6430e95 Merge "Prevent OOB read in rw_i93_process_sys_info()" into oc-dev am: 2c605825f8
 ▪ e40cbea Prevent OOB error in rw_i93_process_ext_sys_info()
 ▪ 2c60582 Merge "Prevent OOB read in rw_i93_process_sys_info()" into oc-dev
 ▪ baa27d0 Merge "Prevent OOB error in rw_i93_sm_read_ndef()" into oc-dev am: 46f44fd653 am: e010bdd3de am: e079b7a95a
 ▪ e079b7a Merge "Prevent OOB error in rw_i93_sm_read_ndef()" into oc-dev am: 46f44fd653 am: e010bdd3de
 ▪ e010bdd Merge "Prevent OOB error in rw_i93_sm_read_ndef()" into oc-dev am: 46f44fd653
 ▪ c23e375 Prevent OOB error in rw_i93_sm_update_ndef() am: 8617cbb1a8 am: 8081839dc8 am: c80b838093
 ▪ c80b838 Prevent OOB error in rw_i93_sm_update_ndef() am: 8617cbb1a8 am: 8081839dc8
 ▪ 46f44fd Merge "Prevent OOB error in rw_i93_sm_read_ndef()" into oc-dev
 ▪ 8081839 Prevent OOB error in rw_i93_sm_update_ndef() am: 8617cbb1a8
 ▪ 8909dbd Prevent OOB error in rw_i93_sm_detect_ndef() am: 9939edeb9f am: 2ee2f756d0 am: d4921e738b
 ▪ d4921e7 Prevent OOB error in rw_i93_sm_detect_ndef() am: 9939edeb9f am: 2ee2f756d0
 ▪ 2ee2f75 Prevent OOB error in rw_i93_sm_detect_ndef() am: 9939edeb9f
 ▪ 8617cbb Prevent OOB error in rw_i93_sm_update_ndef()
 ▪ 61fcf89 Prevent OOB error in rw_i93_sm_read_ndef()
 ▪ c1da325 Prevent OOB read in rw_i93_process_sys_info()
 ▪ 9939ede Prevent OOB error in rw_i93_sm_detect_ndef()
 ▪ a246861 [automerger skipped] Merge "Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()" into oc-dev am: 9f4e55ae19 am: 4c7225d51a am: af6a43fea5 -s ours am skip reason: change_id I25389b85b14e74b0a20eb2e41373b5708ea057b1 with SHA1 4d9b1dd02b is in history
 ▪ af6a43f Merge "Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()" into oc-dev am: 9f4e55ae19 am: 4c7225d51a
 ▪ 4c7225d Merge "Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()" into oc-dev am: 9f4e55ae19
 ▪ 6a47a8d Snap for 5268384 from 56401c8403c695293726b6b129dc2ddcabfc0173 to pi-qpr3-release
 ▪ 9f4e55a Merge "Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()" into oc-dev
 ▪ 56401c8 Merge "Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()" into pi-dev
 ▪ cbc4823 Fix heap overflow in NFA_SendRawFrame()
 ▪ b5f3ef4 Prevent integer underflow in rw_t2t_handle_tlv_detect_rsp()
 ▪ 7729db6 Prevent Out of bounds write in rw_t3t_handle_get_sc_poll_rsp()
 ▪ 8beb9a9 Prevent Integer Overflow in rw_t3t_act_handle_check_rsp()
 ▪ 71dd18c Prevent OOB read in rw_t3t_act_handle_ndef_detect_rsp()
 ▪ 3259277 Prevent OOB read in rw_t3t_update_block()
 ▪ ca0e071 Prevent Out of bounds read in ce_t4t.cc
 ▪ 4d30857 Prevent Out of bound error in llcp_dlc_proc_rr_rnr_pdu()
 ▪ 1d66989 [automerger skipped] Merge "Prevent integer underflow in rw_t2t_handle_tlv_detect_rsp()" into oc-dev am: 43e126f479 am: 1e7b5bb17a am: cbcd964dae -s ours am skip reason: change_id Ifa3e5fdf23f267a0d6c3aa8495c4c83f20153025 with SHA1 83439b5ca0 is in history
 ▪ cbcd964 Merge "Prevent integer underflow in rw_t2t_handle_tlv_detect_rsp()" into oc-dev am: 43e126f479 am: 1e7b5bb17a
 ▪ 1e7b5bb Merge "Prevent integer underflow in rw_t2t_handle_tlv_detect_rsp()" into oc-dev am: 43e126f479
 ▪ 43e126f Merge "Prevent integer underflow in rw_t2t_handle_tlv_detect_rsp()" into oc-dev
 ▪ 9c1db58 Prevent integer underflow in rw_t3t_act_handle_check_ndef_rsp()
 ▪ c609be9 Merge "Prevent integer underflow in rw_t2t_handle_tlv_detect_rsp()" into pi-dev

 ▼ system/qcom/
 ▪ 3a92990 Merge e0c1c7780a741a191748986a0d1cf598486a6597 on remote branch
 ▪ 48b8ac4 QSAP: Add support to set sae_require_mfp parameter
 ▪ 07f798c Merge e0c1c7780a741a191748986a0d1cf598486a6597 on remote branch

 ▼ system/sepolicy/
 ▪ 040aec066 Ignore newly added selinux objects
 ▪ 362a69242 Snap for 5180536 from 6308216c6c5afc1caf2d34e7865ca546bf760450 to pi-platform-release
 ▪ 3ab36a069 Merge tag 'android-9.0.0_r31' into lineage-16.0-android-9.0.0_r31
 ▪ cff41e03f Merge tag 'android-9.0.0_r33' of https://android.googlesource.com/platform/system/sepolicy into pie
 ▪ e21f49fbd Merge tag 'android-9.0.0_r33' into pie
 ▪ 65214a26f Merge tag 'LA.UM.7.5.r1-04100-8x96.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie
 ▪ 6e04e7566 Allow webview_zygote to read /dev/ion
 ▪ b2fe1d8c4 Allow webview_zygote to read /dev/ion
 ▪ 20da3a0ef Add init as a fs_type neverallow exemption
 ▪ 05ab40a14 sepolicy: public: add TCSETSF to the list of unprivileged TTY ioctls
 ▪ 4764b69ab Android.mk: remove some build-log spam
 ▪ 60620c910 Merge 4824a323ccecd0554d8f87760514d080e13cb3e4 on remote branch
 ▪ 9a24e8238 Merge cherrypicks of [6161352, 6161353, 6161354, 6161355, 6161236, 6161237, 6161238, 6161759, 6161608, 6161356, 6161760, 6161654, 6161422, 6161423, 6161424, 6161425, 6161426, 6161427, 6161819, 6161357, 6161358, 6161428, 6161429, 6161430, 6159952, 6159858] into pi-b4s4-release
 ▪ 6fd021989 Allow lmkd to renice process before killing
 ▪ 3feb8646f Snap for 5255085 from aadedb205127bfa019d1c1da9208aa41077258e9 to pi-qpr3-release
 ▪ aadedb205 Allow lmkd to renice process before killing
 ▪ 7acba2a16 Merge 4824a323ccecd0554d8f87760514d080e13cb3e4 on remote branch
 ▪ baa516831 uncrypt: Allow opening OTA package as rw
 ▪ e1f0f2354 Allow fsck_untrusted to getattr block_device
 ▪ 2bdb47426 Allow fsck_untrusted to getattr block_device
 ▪ 6f8ffeeac Add missing pm.* properties in property_contexts
 ▪ c7aa47de0 sepolicy: create rules for system properties
 ▪ e03c16d4e Allow dnsmasq to getattr netd unix_stream_socket
 ▪ d992cf2dd Use LOCAL_ADDITIONAL_M4DEFS for file_contexts
 ▪ fca705e49 Allow init to chmod/chown /proc/slabinfo
 ▪ 056738e0d Allow init to write to /proc/cpu/alignment
 ▪ 78a9a9985 sepolicy: Add policy for edgegestureservice
 ▪ 0a85cc837 Allow fsck_untrusted to getattr block_device
 ▪ 1455b4f9a sepolicy: Add policy for edgegestureservice
 ▪ dbccc561b sepolicy: Address denials for legacy last_kmsg file
 ▪ e4ba49b3c Add missing pm.* properties in property_contexts
 ▪ b3c147fba sepolicy: create rules for system properties
 ▪ 86199db38 Allow dnsmasq to getattr netd unix_stream_socket
 ▪ 5b3b22a77 Use LOCAL_ADDITIONAL_M4DEFS for file_contexts
 ▪ 81eda18b6 Snap for 5232626 from 63d07d75868e56f3fd40a4a1747b5af09528451a to pi-b4s4-release
 ▪ 487bb0168 Allow init to chmod/chown /proc/slabinfo
 ▪ 6213f5041 Allow init to write to /proc/cpu/alignment
 ▪ e4e8f5156 sepolicy: Address denials for legacy last_kmsg file
 ▪ dbf041ca8 Merge cherrypicks of [6026670, 6017608, 6017609, 6017610, 6017611, 6026671, 6026672, 6028544, 6029630, 6026673, 6026674] into pi-b4s4-release
 ▪ ea6b101a9 [Test Patch] Allow FP to execute cmd.
 ▪ 73fadeb01 Add adb over network tile sepolicy
 ▪ de9b016aa Merge tag 'LA.UM.7.6.r1-04000-89xx.0' of https://source.codeaurora.org/quic/la/platform/system/sepolicy into pie
 ▪ ffb6ef05a Allow charger access to /mnt/vendor
 ▪ 7e50e76af Fix storaged access to /sys/block/mmcblk0/stat after 48027a00
 ▪ ff6b7c2d5 Allow mediaserver to read device directories
 ▪ 05477957e Allow init to set powerctl property
 ▪ 2f18ac170 Snap for 5222977 from 63d07d75868e56f3fd40a4a1747b5af09528451a to pi-b4s4-release

 ▼ system/timezone/
 ▪ 94c787c Snap for 5180536 from 9fff3df46bcab5c3575b40b7c3b2910e8bb21286 to pi-platform-release
 ▪ 5ba7ee5 Snap for 5285806 from 44ebb70e4303e72de28fd3ad9200777f0b6212a4 to pi-qpr3-release
 ▪ 44ebb70 DO NOT MERGE: Fix Morocco to use rearguard format correctly in ICU.
 ▪ 506ecc2 DO NOT MERGE: Update Android tzdata from 2018g to 2018i.
 ▪ 378350a DO NOT MERGE: Fix Morocco to use rearguard format correctly in ICU.
 ▪ a545fe9 DO NOT MERGE: Update Android tzdata from 2018g to 2018i.
 ▪ 9477ff8 Revert "Update Android tzdata from 2018g to 2018i"

 ▼ system/tools/hidl/
 ▪ db3dd81 Merge cherrypicks of [6072697, 6072075, 6072758, 6072124, 6072885, 6072886, 6072887, 6072580, 6072581, 6072582, 6072583, 6072584, 6072132, 6072195, 6072133, 6072077, 6072134, 6072078, 6072211, 6072762, 6072763, 6072908, 6072909, 6072910, 6072911, 6072912, 6072913, 6072914, 6072930, 6072212, 6072743] into pi-qpr2-release
 ▪ 9393ade Fillout requesting SID.
 ▪ 895f9e5 Fillout requesting SID.
 ▪ fab4a3f [automerger skipped] Fillout requesting SID. am: e61254463c am: d32ee18e32 -s ours am: ac154da803 -s ours am skip reason: change_id I3a7f6c0b3cc8bab24e0639a3e7121ef536b2603b with SHA1 ca8cf63c53 is in history
 ▪ ac154da [automerger skipped] Fillout requesting SID. am: e61254463c am: d32ee18e32 -s ours am skip reason: change_id I3a7f6c0b3cc8bab24e0639a3e7121ef536b2603b with SHA1 3559fb01be is in history
 ▪ d32ee18 Fillout requesting SID. am: e61254463c
 ▪ bb4209b [automerger skipped] Fillout requesting SID. am: 3559fb01be -s ours am skip reason: change_id I3a7f6c0b3cc8bab24e0639a3e7121ef536b2603b with SHA1 ca8cf63c53 is in history
 ▪ e612544 Fillout requesting SID.
 ▪ 3559fb0 Fillout requesting SID.
 ▪ ca8cf63 Fillout requesting SID.

 ▼ system/update_engine/
 ▪ 0d0e2e1 Snap for 5180536 from 0eb2fd56a234e5f1279c2a401219646d9635f023 to pi-platform-release
 ▪ 8d95962 Merge tag 'android-9.0.0_r31' into lineage-16.0-android-9.0.0_r31

 ▼ system/vold/
 ▪ c03435f Snap for 5180536 from 2ab3b948d787852b2b34c4c7fe623c35ae214ae3 to pi-platform-release
 ▪ 724757c vold: Fix build
 ▪ 3841df6 Merge remote-tracking branch 'AOSP/pie-gsi' into pie
 ▪ 5262b8f vold: Fix FDE flags
 ▪ ab1cec2 Merge "resolve merge conflicts of 06084fee42078bf2e0fb1141e9de8dbc8e9daf2b to pie-gsi" into pie-gsi
 ▪ 15e7e44 resolve merge conflicts of 06084fee42078bf2e0fb1141e9de8dbc8e9daf2b to pie-gsi

 ▼ vendor/codeaurora/telephony/
 ▪ 22b0679 Merge 94379a7507d40f86dcd1486525418ee028b35608 on remote branch
 ▪ 1aa9694 Merge tag 'LA.UM.7.5.r1-04100-8x96.0' into pie
 ▪ cd29b73 Merge 94379a7507d40f86dcd1486525418ee028b35608 on remote branch
 ▪ b0760a7 Merge 94379a7507d40f86dcd1486525418ee028b35608 on remote branch
 ▪ 918b6ba Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into pie

 ▼ vendor/havoc/
 ▪ e6da3c38 Remove proxy for Koodo
 ▪ 387e14f6 soong: Fix FDE flags
 ▪ aaf714dd Havoc 2.2
 ▪ 711c9287 WallpaperPicker: Materialize the delete icon
 ▪ e531999a overlay: header image tweaks [2/2]
 ▪ c4a6304f soong_config: Add flag for msm8974 1440p EGL workaround
 ▪ 00bc5894 overlay: Fix icon mask
 ▪ 886e157b overlay: qs status bar header image [4/4]
 ▪ 29d81dd0 vendor: add Cookie QS style [1/3]
 ▪ 63fe3ad5 overlay: Disable pixel migrate service
 ▪ 08670cd0 Update sim colors [4/4]
 ▪ ce8c181c overlay: Show LTE icon instead of 4G on all devices
 ▪ 4c417846 overlay: Enable HSPA icon on all devices
 ▪ d67bd6f4 Change walls
 ▪ a4c94919 Allow Google Dialer notifications to be blocked
 ▪ b5f3ca0e Dark/Black theme improvements
 ▪ 9322e32e vendor: notch-city: Add 3 mode display cutout handler [2/3]
 ▪ 77902af6 New walls
 ▪ fff1596a Havoc 2.1
 ▪ 261f6922 havoc-iosched: restorecon scheduler tuneables before touching them
 ▪ 2d48ae1b config: Add Deskclock to power whitelist
 ▪ b51813b5 Remove deprecated ro.device.cache_dir
 ▪ 4a414c1a Don't explicitly build uneeded packages
 ▪ 34d7eff8 Disable art debug and enable minimize debug info
 ▪ 2e63f225 vendor: Cleanup

 ▼ vendor/qcom/opensource/cryptfs_hw/
 ▪ 47851da cryptfs_hw: Fix build warnings
 ▪ e37c00a cryptfs_hw: Featurize support for waiting on QSEE to start
 ▪ 4dd1313 cryptfs_hw: Add compatibility for pre-O hw crypto
 ▪ 684bb8d cryptfs_hw: remove block disk encryption dependency on metadata partition

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ 035b1a6 Merge baec5e4b5cdc68b2bde85d81f937ac7cf3b09a13 on remote branch
 ▪ cca4c15 ipacm: fix metadata replacement issue on modem xlat
 ▪ e32f051 Merge baec5e4b5cdc68b2bde85d81f937ac7cf3b09a13 on remote branch
 ▪ 04e14c3 ipacm: Add target SM6125 to IPA v3 target list
 ▪ c79bad2 Merge baec5e4b5cdc68b2bde85d81f937ac7cf3b09a13 on remote branch
 ▪ 0ee1c80 Merge baec5e4b5cdc68b2bde85d81f937ac7cf3b09a13 on remote branch

 ▼ vendor/qcom/opensource/interfaces/
 ▪ f8b4ecd Merge fe06faf5b392e4362732ceee6e2d78da611a7b1e on remote branch
 ▪ 8d9e15e Merge 5d5fa936a558dfbbe671e9a081493f8f70657d66 on remote branch
 ▪ e6bbd7f IDisplayConfig: Add interface to get attributes of active display
 ▪ 011af36 Merge tag 'LA.UM.7.6.2.r1-05700-89xx.0' into pie
 ▪ fe06faf wifi: Introduce qti.hardware.wifi@1.0 HAL interface

 ▼ vendor/qcom/opensource/thermal-engine/
 ▪ 9a1d1f4 Merge 285dd9dc52b660d608f633319aa26acd7d2760c5 on remote branch
 ▪ 285dd9d thermal-engine: Add bandwidth level request APIs to thermal client header

 ▼ vendor/support/
 ▪ 099eef4 Add GlobalSettingsMasterSwitchPreference
 ▪ 62d5730 Add SecureSettingsMasterSwitchPreference
 ▪ c7c2eb0 Fix MasterSwitchPreference
 ▪ d4663b9 MasterSwitchPreference: isChecked doesn't rely on existence of switch
 ▪ 9777a00 Add SystemSettingsMasterSwitchPreference
 ▪ dcd9587 Custom Seekbar improvements
 ▪ ed19f0d Add Color Blend Preference
 ▪ 5acfbbe CustomSeekbar: Fix auto reset in few cases
 ▪ fb4670d Adapt new custom seekbar preference for existing prefs
 ▪ 051e8ee Import new custom seekbar preference
 ▪ 813d2ec Icon pack preference: Reuse existing resources
 ▪ ff77a5a support: Adapt IconPackPreference class from Launcher3
 ▪ eb54a24 CustomSeekBarPreference: Align with other preferences
 ▪ 8b82fcd SlimRecents b.l. PackageListAdapter: really sync mInstalledPackages
 ▪ 42804d7 Add slimrecents packagelistadapter
 ▪ 1dbed3b Remove isPersisted override
 ▪ 80f6f3c Add EditText Preference
 ▪ 6baa63c Update and add preferences that hold system settings
 ▪ bdc8d50 Add SecureSettingsListPreference
 ▪ fee89a7 Add SystemSettingListPreferece for xml-only use
 ▪ ec269b3 Color picker: show hex input box on top
 ▪ 596edb5 Replace colorpicker action set png with vector
 ▪ 0d9bcdb Color Picker: use oval preview
 ▪ 2e21294 Improve color picker layout / cleaned up some of the code
 ▪ 57f8be2 margaritov color picker: add a proper landscape layout
 ▪ e646185 Colorpicker: Fix possible NPE
 ▪ 42c4069 Colorpicker: add method to set default values
 ▪ a5cb7dd Change color picker reset icon
 ▪ 8b4c618 Color picker reset button: refresh color preview on click
 ▪ 30301d5 Color Picker: don't show picker on click if preference is disabled
 ▪ 3b423a6 Color picker: don't show keyboard on start
 ▪ 1b18206 Color picker pref: allow tap also on the text to show the picker
 ▪ fd75e0f Introduce set default button when attribute is set
 ▪ b02cd24 Added modded marginov color picker
 ▪ 60ade29 Custom seekbar pref: allow to refresh values
 ▪ a92f904 Customseekbar: add method to set default values
 ▪ 35496cb New CustomSeekBar: allow to translate "Default" value string
 ▪ 9551d32 New custom seekbar: more improvements
 ▪ 46bbbc8 New fresh look for CustomSeekbar
 ▪ 709bf10 CustomSeekBar: fix progressbar glitch with custom min-max values
 ▪ 1773dae Fix seekbar attribute grabbing
 ▪ d167928 Add CustomSeekBarPreference
 ▪ 3dda60e Add ListPreference helpers backed by Settings
 ▪ e22d44d Add Global Setting Switch Preference
 ▪ 3762f50 Update imports for preferences
 ▪ 6abc4c0 Add Secure Setting Switch Preference
 ▪ 1cc0d90 Make easy to add a checkbox preference
 ▪ d6f1ba6 Create VendorSupportLib

====================
     30-09-2019
====================

 ▼ external/icu/
 ▪ e6af4b830 DO NOT MERGE: Update tzdb version from 2019b to 2019c

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 872acb95 Merge "configs:sdm429: Add mixer ctl for Headphone and WSA combo" into audio-hal.lnx.5.0.c5
 ▪ 06e2b9a2 Merge "hal: Allow hal to open Telephony RX as attached device" into audio-hal.lnx.5.0.c5

 ▼ system/timezone/
 ▪ e2ed9ed DO NOT MERGE: Update tzdb version from 2019b to 2019c

====================
     27-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 78cab3a55 Restore ANT+
 ▪ 9f4829bb6 gps: LocIpc derefs nullptr if stopping blocking listener
 ▪ f4e45070a gps: Set SV in use mask based on final fixes

 ▼ vendor/xiaomi/
 ▪ 2ea7c304 Revert "msm8996-common: Update Bluetooth blobs from LA.UM.7.5.r1-05300-8x96.0"
 ▪ 4e85d19a msm8996-common: Restore ANT+
 ▪ 10feabd2 convert some modules to Android.bp

====================
     26-09-2019
====================

 ▼ external/ant-wireless/ant_service/
 ▪ f760ac5 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/external/ant-wireless/ant_service into HEAD

====================
     24-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ c1267fabe overlays: move some values to fwb

 ▼ frameworks/base/
 ▪ bc18bee45f6 overlays: move some values from device path

 ▼ hardware/interfaces/
 ▪ ad3e3bc69 replace <cutils/log.h> with <log/log.h>

====================
     23-09-2019
====================

 ▼ vendor/nxp/opensource/commonsys/external/libnfc-nci/
 ▪ 145f3dd fix warnings

====================
     22-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 344d9285f move PRODUCT_BRAND var back to $(PRODUCT_NAME).mk

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 6e8c782c Merge "hal: fix voip usecase selection for voice_tx path" into audio-hal.lnx.5.0.c5

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 6f6a18573 fix build

====================
     21-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ ef3b8b2ef CAF tag: LA.UM.7.5.2.r1-03700-8x96.0
 ▪ ef828fd04 Add device info HIDL service

 ▼ external/chromium-webview/
 ▪ 880977b Update Chromium Webview to 77.0.3865.92

 ▼ kernel/xiaomi/msm8996/
 ▪ fc9782024b3c Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' into drivers/staging/qcacld-2.0

 ▼ packages/apps/Contacts/
 ▪ 2465a44cf Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Contacts into HEAD

 ▼ packages/apps/Dialer/
 ▪ bd439d6ba Revert "Fix in-call buttons layout"

 ▼ packages/apps/Nfc/
 ▪ 8751fc0b Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/Nfc into HEAD

 ▼ packages/apps/PackageInstaller/
 ▪ d61c91d5 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/apps/PackageInstaller into HEAD

 ▼ packages/apps/Settings/
 ▪ 1374c956d3 add SearchIndexProvider into HavocSettings [2/2]
 ▪ 10f01e413b Support to notify connected/disconnected stations
 ▪ e0d9c55902 Havoc Build Date [2/2]
 ▪ 0029aacfca DeviceInfoSettings: Bring back CAF/AOSP tags
 ▪ 0bb8d41306 my colors
 ▪ 60c187f11f Revert "Revert "Settings: Add toggle for proximity wake""

 ▼ packages/providers/DownloadProvider/
 ▪ 772c8c7 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/packages/providers/DownloadProvider into HEAD

 ▼ system/bt/
 ▪ 635243f0f Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
 ▪ 45b4ca732 RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
 ▪ 9d6bbb79e sdclang: true
 ▪ a466f7342 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

 ▼ system/core/
 ▪ 268c4a3d8 Allow adb root even in no debuggable builds

 ▼ system/tools/hidl/
 ▪ 201c894 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/tools/hidl into HEAD

 ▼ system/vold/
 ▪ d3faf27 Merge tag 'android-9.0.0_r48' of https://android.googlesource.com/platform/system/vold into HEAD

 ▼ vendor/qcom/opensource/data-ipa-cfg-mgr/
 ▪ 4751e2f Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 35fcb03 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     20-09-2019
====================

 ▼ hardware/interfaces/
 ▪ d80e1c1a2 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 8d84b06c Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0
 ▪ 5781b50b hal: Allow hal to open Telephony RX as attached device
 ▪ 7c73061b hal: Allow hal to open Telephony RX as attached device
 ▪ ca521c57 configs:sdm429: Add mixer ctl for Headphone and WSA combo
 ▪ 6ec3f1cb A2dp: Send default channel mapping for TWS+ mono.
 ▪ 2025baa7 hal: Unload modem wrt peripheral manager update

 ▼ vendor/qcom/opensource/audio/
 ▪ e052706 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

 ▼ vendor/qcom/opensource/interfaces/
 ▪ 35fcb03 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     19-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 60245cde0 DRM: import missing libops.so from sm8150
 ▪ 76ccf376e adsp: restore stock libadsp_fd_skel.so

 ▼ hardware/interfaces/
 ▪ 063247cc2 Snap for 5883521 from 905279fe6d022910938a67c6c32f615405cdc075 to p-keystone-qcom-release

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ a556d3a2 configs:sdm429: Add mixer ctl for Headphone and WSA combo
 ▪ c54f03b3 Merge 8588718cb0cf7ee2fc977135b807e44fe4e171b4 on remote branch

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ d417d8ee mm-video-v4l2: vdec: Correct order of reading color primaries

 ▼ kernel/xiaomi/msm8996/
 ▪ 452d3a1d855b Merge 8a0fcb0d8e45c03a63c979b911c47d5932d1e730 on remote branch

 ▼ vendor/qcom/opensource/audio/
 ▪ c0ba834 Merge 630c0c52c08b00b26efc82402a8e1b82bd65410a on remote branch

 ▼ vendor/qcom/opensource/interfaces/
 ▪ b8e4183 Merge "camera: Add offline post processor service support"
 ▪ 75aca03 Merge a9ab3a736069433263319c4c30dcae2340e66efb on remote branch

 ▼ vendor/xiaomi/
 ▪ 22d9b2b7 adsp: restore stock libadsp_fd_skel.so
 ▪ b4f5694d DRM: import missing libops.so from sm8150
 ▪ 28f93595 don't copy gnss libs twice
 ▪ acba925a msm8996-common: Update WFD blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ aa2ff50c msm8996-common: Import TUI blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 4f2628e4 msm8996-common: Update Time services blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ b28702fe msm8996-common: Update Thermal blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 3519a00d msm8996-common: Update Sensors blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 6d1fa0af msm8996-common: Update Power-off alarm blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 9ad4dd7e msm8996-common: Update Postprocessing blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ a10d6511 msm8996-common: Update Peripheral manager blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 6f37be00 msm8996-common: Update Media blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 1ad8276a msm8996-common: Update SoundTrigger blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ f8207bd7 msm8996-common: Update Keystore blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 6105c410 msm8996-common: Update Graphics blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 2efcaca1 msm8996-common: Update Gatekeeper blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ f8b58ddf msm8996-common: Update DRM Widevine blobs from Crosshatch - PQ3A.190801.002
 ▪ 801ac418 msm8996-common: Update DRM blobs from LA.UM.7.5.r1-05300-8x96.0

====================
     17-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 47b5b55cf update blobs from LA.UM.7.5.r1-05300-8x96.0

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ 25d77b76 Merge accff5940e271f72dcc2301ff9f9dc3eae2322ae on remote branch

 ▼ hardware/qcom/media-caf/msm8996/
 ▪ b3702481 Merge b107ffda0d09d62628456a2a9c373585c5ccf843 on remote branch

 ▼ hardware/qcom/media-caf/msm8998/
 ▪ 0d6147e1d Merge tag 'LA.UM.7.2.r2-02200-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into lineage-16.0-caf-8998

====================
     16-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 8fed04bd2 msm8996-common: Remove ANT+
 ▪ 6b8c0189e msm8996-common: Remove wcnss_filter

 ▼ hardware/interfaces/
 ▪ 905279fe6 Increase initWithMmapSize to 32k for cas service

 ▼ kernel/xiaomi/msm8996/
 ▪ 7690030177f8 defconfig: massive debloat

 ▼ vendor/xiaomi/
 ▪ c67b27ba msm8996-common: Update DPM blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 65287e95 msm8996-common: Update CNE blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 80b117cb msm8996-common: Update Bluetooth blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 192adf7e msm8996-common: Update ADSP blobs from LA.UM.7.5.r1-05300-8x96.0
 ▪ 94172d93  msm8996-common: Remove ANT+
 ▪ d32bdb68 msm8996-common: Remove wcnss_filter

====================
     15-09-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ b44c5c5e3 update sepolicy
 ▪ 703d730ca update qc3 path

 ▼ packages/apps/HavocSettings/
 ▪ 912f581 add qc3 control

