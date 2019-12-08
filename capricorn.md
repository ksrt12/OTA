
====================
     12-08-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 98b81c66f rootdir: init.qcom.rc: remove duplicate vendor.sensors service
 ▪ c6f4b3401 Android 9.0.0 revision 51

====================
     12-06-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ e6f7ad5f3491 Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie

 ▼ system/security/
 ▪ 3704004 patch

====================
     11-30-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 5e76fcf73e4d Merge 4.4.205 into kernel.lnx.4.4.r37-rel
 ▪ 2810f15bcb6e Linux 4.4.205
 ▪ 0d7c1e4be6d8 Revert "sock: Reset dst when changing sk_mark via setsockopt"

====================
     11-29-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 0614f991fcdf Merge 4.4.204 into kernel.lnx.4.4.r37-rel
 ▪ 01bc6b5c5503 Linux 4.4.204
 ▪ b54ecad48a56 KVM: PPC: Book3S HV: Flush link stack on guest exit to host kernel
 ▪ 3a79351beb54 powerpc/book3s64: Fix link stack flush on context switch
 ▪ 1efaf619f422 powerpc/64s: support nospectre_v2 cmdline option
 ▪ 4e23e97241b7 staging: comedi: usbduxfast: usbduxfast_ai_cmdtest rounding error
 ▪ ba9e9a9e1ef6 USB: serial: option: add support for Foxconn T77W968 LTE modules
 ▪ 41cdfa76aa99 USB: serial: option: add support for DW5821e with eSIM support
 ▪ 99c38ee6654b USB: serial: mos7840: fix remote wakeup
 ▪ 8cee13b7c185 USB: serial: mos7720: fix remote wakeup
 ▪ a6da8dce18d1 USB: serial: mos7840: add USB ID to support Moxa UPort 2210
 ▪ 6f10c432716f appledisplay: fix error handling in the scheduled work
 ▪ efb975b43222 usb-serial: cp201x: support Mark-10 digital force gauge
 ▪ b12818d70879 virtio_console: move removal code
 ▪ fa3c628897e6 virtio_console: drop custom control queue cleanup
 ▪ ba9e2c1190a6 virtio_console: fix uninitialized variable use
 ▪ abdd31f3744e virtio_console: allocate inbufs in add_port() only if it is needed
 ▪ 809ff9a14bde virtio_console: don't tie bufs to a vq
 ▪ 4cad8c2d8f8b virtio_console: reset on out of memory
 ▪ 7eb42039eb29 media: imon: invalid dereference in imon_touch_event
 ▪ b2bbdf42907a media: cxusb: detect cxusb_ctrl_msg error in query
 ▪ 89660684ceca media: b2c2-flexcop-usb: add sanity checking
 ▪ 71941ad643fd cpufreq: Add NULL checks to show() and store() methods of cpufreq
 ▪ 7f8286d2b526 media: vivid: Fix wrong locking that causes race conditions on streaming stop
 ▪ 840e3e22c41c media: vivid: Set vid_cap_streaming and vid_out_streaming to true
 ▪ 03e90f760c1d x86/speculation: Fix redundant MDS mitigation message
 ▪ a648358b152e x86/speculation: Fix incorrect MDS/TAA mitigation status
 ▪ 10d88bd90152 x86/insn: Fix awk regexp warnings
 ▪ 9fd988c55ceb ARC: perf: Accommodate big-endian CPU
 ▪ 0ef78c8d7ac6 mmc: block: Fix tag condition with packed writes
 ▪ 382896281b06 ocfs2: remove ocfs2_is_o2cb_active()
 ▪ 7181d93b44cb cpufreq: Skip cpufreq resume if it's not suspended
 ▪ cdae704b5db2 arm64: fix for bad_mode() handler to always result in panic
 ▪ 4a5bdc546ab4 dm: use blk_set_queue_dying() in __dm_destroy()
 ▪ 56f7de7b6d37 ath9k_hw: fix uninitialized variable data
 ▪ bc7c32ca28cc Bluetooth: Fix invalid-free in bcsp_close()
 ▪ 6dc6e94448a5 IB/hfi1: Ensure full Gen3 speed in a Gen4 system
 ▪ f8b496162504 spi: omap2-mcspi: Fix DMA and FIFO event trigger size mismatch
 ▪ d651d24224f2 PCI: keystone: Use quirk to limit MRRS for K2G
 ▪ 7d1b4fac74eb pinctrl: zynq: Use define directive for PIN_CONFIG_IO_STANDARD
 ▪ 14d1265f7dc8 pinctrl: qcom: spmi-gpio: fix gpio-hog related boot issues
 ▪ 4c5ce7ca90e0 sock: Reset dst when changing sk_mark via setsockopt
 ▪ 37464741cd55 net: bcmgenet: return correct value 'ret' from bcmgenet_power_down
 ▪ d9ee6bc81c1f dlm: don't leak kernel pointer to userspace
 ▪ acc555689f39 dlm: fix invalid free
 ▪ 9d4c8d7bae13 scsi: lpfc: fcoe: Fix link down issue after 1000+ link bounces
 ▪ 2eb7e4dd5834 scsi: megaraid_sas: Fix msleep granularity
 ▪ b5e72bab286e scsi: mpt3sas: Fix driver modifying persistent data in Manufacturing page11
 ▪ 0be977432127 scsi: mpt3sas: Fix Sync cache command failure during driver unload
 ▪ f9bfd6ec121b rtlwifi: rtl8192de: Fix misleading REG_MCUFWDL information
 ▪ 574161e0d97d wireless: airo: potential buffer overflow in sprintf()
 ▪ 46605d80ecdd brcmsmac: never log "tid x is not agg'able" by default
 ▪ f388d10de1e5 rtl8xxxu: Fix missing break in switch
 ▪ f1b5bdd410f8 wlcore: Fix the return value in case of error in 'wlcore_vendor_cmd_smart_config_start()'
 ▪ 044cc4e38cb9 audit: print empty EXECVE args
 ▪ e26e9e270b96 sched/fair: Don't increase sd->balance_interval on newidle balance
 ▪ ab96ac3814b2 net: do not abort bulk send on BQL status
 ▪ 80644c520cf9 ocfs2: fix clusters leak in ocfs2_defrag_extent()
 ▪ 01f93d5e3675 ocfs2: don't put and assigning null to bh allocated outside
 ▪ ea8db54207d1 ntb: intel: fix return value for ndev_vec_mask()
 ▪ e348885bd406 ntb_netdev: fix sleep time mismatch
 ▪ eb517bafc9ec igb: shorten maximum PHC timecounter update interval
 ▪ 11f353543474 fs/hfs/extent.c: fix array out of bounds read of array extent
 ▪ 976582682031 hfs: fix return value of hfs_get_block()
 ▪ f033c78a8b4f hfsplus: fix return value of hfsplus_get_block()
 ▪ c57684d5e2f4 hfs: prevent btree data loss on ENOSPC
 ▪ 1a7e07ee73cb hfsplus: prevent btree data loss on ENOSPC
 ▪ 4d7a54facf53 hfs: fix BUG on bnode parent update
 ▪ 8e147f0f415f hfsplus: fix BUG on bnode parent update
 ▪ dde263880cda linux/bitmap.h: fix type of nbits in bitmap_shift_right()
 ▪ 540d0d63403f linux/bitmap.h: handle constant zero-size bitmaps correctly
 ▪ 485a34ada909 um: Make line/tty semantics use true write IRQ
 ▪ 29f9d8d958ee mm/page-writeback.c: fix range_cyclic writeback vs writepages deadlock
 ▪ 05ea09fc71c1 fs/ocfs2/dlm/dlmdebug.c: fix a sleep-in-atomic-context bug in dlm_print_one_mle()
 ▪ 25b5a7a80d7f sparc64: Rework xchg() definition to avoid warnings.
 ▪ 044b9da12734 thermal: rcar_thermal: Prevent hardware access during system suspend
 ▪ 7916b0d824cd selftests/ftrace: Fix to test kprobe $comm arg only if available
 ▪ 072404a1e46e mfd: max8997: Enale irq-wakeup unconditionally
 ▪ cbbffd64d9d4 mfd: mc13xxx-core: Fix PMIC shutdown when reading ADC values
 ▪ 78cfa6b41849 qlcnic: fix a return in qlcnic_dcb_get_capability()
 ▪ 4c65f3274a55 mISDN: Fix type of switch control variable in ctrl_teimanager
 ▪ 7f1e41c76f79 rtc: s35390a: Change buf's type to u8 in s35390a_init
 ▪ f3f19ddcdbc6 ceph: fix dentry leak in ceph_readdir_prepopulate
 ▪ 0b13f3a612d7 sparc: Fix parport build warnings.
 ▪ e53300c4bf39 spi: omap2-mcspi: Set FIFO DMA trigger level to word length
 ▪ 8250c2a36a97 s390/perf: Return error when debug_register fails
 ▪ 2f3f3d9fcb93 atm: zatm: Fix empty body Clang warnings
 ▪ c3fe3831d9e5 SUNRPC: Fix a compile warning for cmpxchg64()
 ▪ fe238303b1eb USB: misc: appledisplay: fix backlight update_status return code
 ▪ 546114a5de94 macintosh/windfarm_smu_sat: Fix debug output
 ▪ 0ddf36f46a25 ALSA: i2c/cs8427: Fix int to char conversion
 ▪ 1f9d5f75a7cb kprobes, x86/ptrace.h: Make regs_get_kernel_stack_nth() not fault on bad stack
 ▪ fd773539c256 net: fix warning in af_unix
 ▪ edc8ac1342d1 scsi: dc395x: fix DMA API usage in sg_update_list
 ▪ 738fd69851a1 scsi: dc395x: fix dma API usage in srb_done
 ▪ 2b4c4bde8b6e clk: mmp2: fix the clock id for sdh2_clk and sdh3_clk
 ▪ c4f442204da8 scsi: iscsi_tcp: Explicitly cast param in iscsi_sw_tcp_host_get_param
 ▪ e9699da6cc18 scsi: isci: Change sci_controller_start_task's return type to sci_status
 ▪ daadc3c18f33 scsi: isci: Use proper enumerated type in atapi_d2h_reg_frame_handler
 ▪ 0a87d037a669 KVM/x86: Fix invvpid and invept register operand size in 64-bit mode
 ▪ afef263abab7 scsi: ips: fix missing break in switch
 ▪ 1282a5bda0e1 amiflop: clean up on errors during setup
 ▪ 5ca4fc0125b8 misc: mic: fix a DMA pool free failure
 ▪ 0097c8510dec gsmi: Fix bug in append_to_eventlog sysfs handler
 ▪ ea6c95031b68 btrfs: handle error of get_old_root
 ▪ 7a82e77fb2a5 mmc: mediatek: fix cannot receive new request when msdc_cmd_is_ready fail
 ▪ 89ca18b8f260 spi: sh-msiof: fix deferred probing
 ▪ f52cd3255ced brcmsmac: AP mode: update beacon when TIM changes
 ▪ 8e1f88a84da9 powerpc/eeh: Fix use of EEH_PE_KEEP on wrong field
 ▪ 22b804cadc78 powerpc: Fix signedness bug in update_flash_db()
 ▪ b283ffe1d5f5 synclink_gt(): fix compat_ioctl()
 ▪ b133f7fa7a33 gfs2: Fix marking bitmaps non-full
 ▪ ee49574a1105 printk: fix integer overflow in setup_log_buf()
 ▪ 2d29770ca69c ALSA: isight: fix leak of reference to firewire unit in error path of .probe callback
 ▪ 3fc6464c048d mwifiex: Fix NL80211_TX_POWER_LIMITED
 ▪ b1375615cde2 platform/x86: asus-wmi: add SERIO_I8042 dependency
 ▪ 83735f1afd3e platform/x86: asus-wmi: Only Tell EC the OS will handle display hotkeys from asus_nb_wmi
 ▪ f045a2851f9f platform/x86: asus-nb-wmi: Support ALS on the Zenbook UX430UQ
 ▪ d34fb39b5af4 platform/x86: asus-wmi: try to set als by default
 ▪ 32101be3235e asus-wmi: provide access to ALS control
 ▪ 0e0280b077f2 platform/x86: asus-wmi: Set specified XUSB2PR value for X550LB
 ▪ b124d2ae883e platform/x86: asus-wmi: fix asus ux303ub brightness issue
 ▪ ad1a346d3f39 platform/x86: asus-wmi: Filter buggy scan codes on ASUS Q500A
 ▪ d49dd420d455 asus-wmi: Add quirk_no_rfkill for the Asus Z550MA
 ▪ 6a3b84c3d553 asus-wmi: Add quirk_no_rfkill for the Asus U303LB
 ▪ dd3eecc0548f asus-wmi: Add quirk_no_rfkill for the Asus N552VW
 ▪ 080134ede70f asus-wmi: Add quirk_no_rfkill_wapf4 for the Asus X456UF
 ▪ 1f00125ed1ed asus-wmi: Create quirk for airplane_mode LED
 ▪ 4fed90d99b9f mm/ksm.c: don't WARN if page is still mapped in remove_stable_node()
 ▪ a13c463564d3 Revert "fs: ocfs2: fix possible null-pointer dereferences in ocfs2_xa_prepare_entry()"
 ▪ 096f1ebc461a net: rtnetlink: prevent underflows in do_setvfinfo()
 ▪ d3d6c678804c net/sched: act_pedit: fix WARN() in the traffic path
 ▪ b5c46c07d5e1 sfc: Only cancel the PPS workqueue if it exists
 ▪ 060cd045fbe2 net/mlx4_en: fix mlx4 ethtool -N insertion

====================
     11-26-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ b61bca84bc22 Merge 4.4.203 into kernel.lnx.4.4.r37-rel
 ▪ 48a16935fdcd Linux 4.4.203
 ▪ f811dcf49abf arm64: uaccess: Ensure PAN is re-enabled after unhandled uaccess fault
 ▪ 736d201a5909 spi: rockchip: initialize dma_slave_config properly
 ▪ 344823879808 mac80211: minstrel: fix CCK rate group streams value
 ▪ 673f7373bd58 hwmon: (pwm-fan) Silence error on probe deferral
 ▪ 08fdf5bd19bf ARM: 8802/1: Call syscall_trace_exit even when system call skipped
 ▪ 91a9d24e3f04 spi: spidev: Fix OF tree warning logic
 ▪ 6d49b0992d02 gpio: syscon: Fix possible NULL ptr usage
 ▪ df3de9e92c3b x86/kexec: Correct KEXEC_BACKUP_SRC_END off-by-one error
 ▪ 0e74fb6274ff media: cx231xx: fix potential sign-extension overflow on large shift
 ▪ 560976f5b8d0 GFS2: Flush the GFS2 delete workqueue before stopping the kernel threads
 ▪ cc1c305ccaab media: isif: fix a NULL pointer dereference bug
 ▪ 55b2c1ccb821 printk: Give error on attempt to set log buffer length to over 2G
 ▪ 4e132c761b44 backlight: lm3639: Unconditionally call led_classdev_unregister
 ▪ 6c6ccfb81658 proc/vmcore: Fix i386 build error of missing copy_oldmem_page_encrypted()
 ▪ d6767e1f8eed bcache: recal cached_dev_sectors on detach
 ▪ c0dea2024671 fbdev: sbuslib: integer overflow in sbusfb_ioctl_helper()
 ▪ 6fc10fb9663d fbdev: sbuslib: use checked version of put_user()
 ▪ 682e2ea0ca94 ACPI / SBS: Fix rare oops when removing modules
 ▪ b88fa52436cf crypto: mxs-dcp - Fix AES issues
 ▪ 33378afbd12b crypto: mxs-dcp - Fix SHA null hashes and output length
 ▪ 429382a01778 x86/olpc: Fix build error with CONFIG_MFD_CS5535=m
 ▪ 12b6054e29f4 Input: st1232 - set INPUT_PROP_DIRECT property
 ▪ 9a8fb6b85ba1 dmaengine: ioat: fix prototype of ioat_enumerate_channels
 ▪ f3ec47899154 NFSv4.x: fix lock recovery during delegation recall
 ▪ 0deab3d2d62d brcmfmac: fix full timeout waiting for action frame on-channel tx
 ▪ 45a948f3b3df mtd: physmap_of: Release resources on error
 ▪ 3983567fba3c USB: serial: cypress_m8: fix interrupt-out transfer length
 ▪ 54a1440e13e5 KVM: PPC: Book3S PR: Exiting split hack mode needs to fixup both PC and LR
 ▪ 3ab6458a1cdf ALSA: hda/sigmatel - Disable automute for Elo VuPoint
 ▪ c4503c8ec56d ata: ep93xx: Use proper enums for directions
 ▪ 74a73932b861 IB/mthca: Fix error return code in __mthca_init_one()
 ▪ 957758e16f99 ixgbe: Fix crash with VFs and flow director on interface flap
 ▪ a43519c4322f mtd: rawnand: sh_flctl: Use proper enum for flctl_dma_fifo0_transfer
 ▪ 95ce46919f51 powerpc/pseries: Fix how we iterate over the DTL entries
 ▪ eb6ad2c27136 powerpc/pseries: Fix DTL buffer registration
 ▪ e045a47841c9 cxgb4: Use proper enum in IEEE_FAUX_SYNC
 ▪ 5ae0133d65b3 cxgb4: Use proper enum in cxgb4_dcb_handle_fw_update
 ▪ d094c54945e3 mei: samples: fix a signedness bug in amt_host_if_call()
 ▪ 208302af9211 dmaengine: timb_dma: Use proper enum in td_prep_slave_sg
 ▪ 1d6b58f039f1 dmaengine: ep93xx: Return proper enum in ep93xx_dma_chan_direction
 ▪ 97779e462452 nl80211: Fix a GET_KEY reply attribute
 ▪ c3f29441b103 usb: gadget: udc: fotg210-udc: Fix a sleep-in-atomic-context bug in fotg210_get_status()
 ▪ 6a9820f17c10 ath9k: fix reporting calculated new FFT upper max
 ▪ e12df1dc496b ath10k: fix vdev-start timeout on error
 ▪ 20cebfcc8312 SUNRPC: Fix priority queue fairness
 ▪ 8669a2782c05 f2fs: return correct errno in f2fs_gc
 ▪ e50b2964e383 net: ovs: fix return type of ndo_start_xmit function
 ▪ 5d784a2d4a0e libata: have ata_scsi_rw_xlat() fail invalid passthrough requests
 ▪ 642fa50e555d block: introduce blk_rq_is_passthrough
 ▪ b4ca3857b8e7 fbdev: Ditch fb_edid_add_monspecs
 ▪ 91b8ab30ff54 fbdev: Remove unused SH-Mobile HDMI driver
 ▪ 9b309cbd6fed uprobes/x86: Prohibit probing on MOV SS instruction
 ▪ 7ea99b43ef29 kprobes/x86: Prohibit probing on exception masking instructions
 ▪ 04b029c35949 apparmor: fix module parameters can be changed after policy is locked
 ▪ 3e6dec86bcd4 apparmor: fix update the mtime of the profile file on replacement
 ▪ 1c374c2c1a1a apparmor: fix uninitialized lsm_audit member
 ▪ 80989fa23c9f x86/atomic: Fix smp_mb__{before,after}_atomic()
 ▪ d940eddc8232 net: cdc_ncm: Signedness bug in cdc_ncm_set_dgram_size()
 ▪ c581f60b9886 slcan: Fix memory leak in error path
 ▪ 905bf98eb338 memfd: Use radix_tree_deref_slot_protected to avoid the warning.
 ▪ 29d9c5714096 Bluetooth: hci_ldisc: Postpone HCI_UART_PROTO_READY bit set in hci_uart_set_proto()
 ▪ eec0a9e1ca41 Bluetooth: hci_ldisc: Fix null pointer derefence in case of early data
 ▪ 67f038ba9cb7 fuse: use READ_ONCE on congestion_threshold and max_background
 ▪ 3670e11857f9 arm64: dts: amd: Fix SPI bus warnings
 ▪ 101125811f5b Bluetooth: L2CAP: Detect if remote is not able to use the whole MPS
 ▪ d4740658aba1 EDAC: Raise the maximum number of memory controllers
 ▪ 06da9c6f7c7e net: smsc: fix return type of ndo_start_xmit function
 ▪ baa4ca05d975 ARM: tegra: apalis_t30: fix mmc1 cmd pull-up
 ▪ 5aa891408eb1 ARM: dts: tegra30: fix xcvr-setup-use-fuses
 ▪ fdb5e9d2c2d3 scsi: libsas: always unregister the old device if going to discover new
 ▪ ac370e3d1f3b vfio/pci: Fix potential memory leak in vfio_msi_cap_len
 ▪ 76817839784f misc: genwqe: should return proper error value.
 ▪ dcfef35ef1a7 misc: kgdbts: Fix restrict error
 ▪ cc3ec27ddebe usb: gadget: uvc: Only halt video streaming endpoint in bulk mode
 ▪ e47af9e7c8f1 usb: gadget: uvc: Factor out video USB request queueing
 ▪ 66fc927508a0 usb: gadget: uvc: configfs: Prevent format changes after linking header
 ▪ 3adae6c6d3f4 usb: gadget: uvc: configfs: Drop leaked references to config items
 ▪ ba863f0d77fb media: davinci: Fix implicit enum conversion warning
 ▪ af9f80fa1e5a media: pci: ivtv: Fix a sleep-in-atomic-context bug in ivtv_yuv_init()
 ▪ fce9612b5f49 MIPS: kexec: Relax memory restriction
 ▪ d1b548815f61 x86/CPU: Use correct macros for Cyrix calls
 ▪ 819f6d97470d net: micrel: fix return type of ndo_start_xmit function
 ▪ 8f64a1a7ff42 bnx2x: Ignore bandwidth attention in single function mode
 ▪ 9d8e2f352c16 cpufeature: avoid warning when compiling with clang
 ▪ a6298e915763 ARM: dts: ste: Fix SPI controller node names
 ▪ 448d70e74bfa ARM: dts: ux500: Fix LCDA clock line muxing
 ▪ 1c4ec0531ee3 ARM: dts: ux500: Correct SCU unit address
 ▪ 68865d163c20 ARM: dts: am335x-evm: fix number of cpsw
 ▪ 7e15c9783625 usb: chipidea: Fix otg event handler
 ▪ 945536fb45e8 net: amd: fix return type of ndo_start_xmit function
 ▪ 166135e4cdaa net: broadcom: fix return type of ndo_start_xmit function
 ▪ 9431f720b820 net: xilinx: fix return type of ndo_start_xmit function
 ▪ a2e4caeac47b net: toshiba: fix return type of ndo_start_xmit function
 ▪ 6aa5efca2ba0 power: supply: twl4030_charger: disable eoc interrupt on linear charge
 ▪ 4e42816ac16b power: supply: twl4030_charger: fix charging current out-of-bounds
 ▪ 657f4204b23c libfdt: Ensure INT_MAX is defined in libfdt_env.h
 ▪ 092e18f0c326 powerpc/pseries: Disable CPU hotplug across migrations
 ▪ b5693ef77f14 powerpc/64s/hash: Fix stab_rr off by one initialization
 ▪ 6eb5dfdd4564 powerpc/iommu: Avoid derefence before pointer check
 ▪ 3b767de18989 serial: mxs-auart: Fix potential infinite loop
 ▪ f94cdf46eabb PCI/ACPI: Correct error message for ASPM disabling
 ▪ 83672bfe1cd5 s390/qeth: invoke softirqs after napi_schedule()
 ▪ 39bd6a7496fc kernfs: Fix range checks in kernfs_get_target_path
 ▪ 709426fc5746 power: supply: max8998-charger: Fix platform data retrieval
 ▪ 52741990fa56 power: supply: ab8500_fg: silence uninitialized variable warnings
 ▪ 1f6a7105b15b cxgb4: Fix endianness issue in t4_fwcache()
 ▪ 1a66e50c45e6 pinctrl: at91: don't use the same irqchip with multiple gpiochips
 ▪ a05541487b89 ARM: dts: socfpga: Fix I2C bus unit-address error
 ▪ 0b7600db547a powerpc/vdso: Correct call frame information
 ▪ db70320a71fb llc: avoid blocking in llc_sap_close()
 ▪ 7c235b44dc99 pinctrl: at91-pio4: fix has_config check in atmel_pctl_dt_subnode_to_map()
 ▪ 9df76cb7ec80 ALSA: intel8x0m: Register irq handler after register initializations
 ▪ 24293b23bca5 media: fix: media: pci: meye: validate offset to avoid arbitrary access
 ▪ cdf4e8eae639 nvmem: core: return error code instead of NULL from nvmem_device_get
 ▪ b99fc345d908 kprobes: Don't call BUG_ON() if there is a kprobe in use on free list
 ▪ 3d7ff04aae05 scsi: pm80xx: Fixed system hang issue during kexec boot
 ▪ 29e5cc0f417b scsi: pm80xx: Corrected dma_unmap_sg() parameter
 ▪ 103e46a0e177 ARM: imx6: register pm_power_off handler if "fsl,pmic-stby-poweroff" is set
 ▪ 9ddc4bd10d8a scsi: sym53c8xx: fix NULL pointer dereference panic in sym_int_sir()
 ▪ 79b1b5ec76bb signal: Properly deliver SIGSEGV from x86 uprobes
 ▪ dc9c09f5edc5 signal: Properly deliver SIGILL from uprobes
 ▪ bbf66e0d4239 signal: Always ignore SIGKILL and SIGSTOP sent to the global init
 ▪ 8f0c1696ecd0 dmaengine: dma-jz4780: Further residue status fix
 ▪ b8fac3d96f46 ARM: dts: omap3-gta04: keep vpll2 always on
 ▪ 9f7ff8063785 ARM: dts: omap3-gta04: make NAND partitions compatible with recent U-Boot
 ▪ 3a846792ca6d ARM: dts: omap3-gta04: tvout: enable as display1 alias
 ▪ 93d1d8095d16 ARM: dts: omap3-gta04: give spi_lcd node a label so that we can overwrite in other DTS files
 ▪ 1cbb52c15fff of: make PowerMac cache node search conditional on CONFIG_PPC_PMAC
 ▪ 1f2952dd752e mips: txx9: fix iounmap related issue
 ▪ 62396b1bfec4 ath10k: wmi: disable softirq's while calling ieee80211_rx
 ▪ 2792933670dd ASoC: sgtl5000: avoid division by zero if lo_vag is zero
 ▪ adb5b0917f69 net: lan78xx: Bail out if lan78xx_get_endpoints fails
 ▪ 3b63b0c7ceae rtl8187: Fix warning generated when strncpy() destination length matches the sixe argument
 ▪ 321cf3b60eee ARM: dts: pxa: fix power i2c base address
 ▪ 5b20928b65e2 i40e: Prevent deleting MAC address from VF when set by PF
 ▪ 0ef9b8f0b8ae i40e: hold the rtnl lock on clearing interrupt scheme
 ▪ 4e86098dbd1b i40e: use correct length for strncpy
 ▪ 420cb453d1b6 ARM: dts: exynos: Fix sound in Snow-rev5 Chromebook
 ▪ 78dbc2d2bb0b MIPS: BCM47XX: Enable USB power on Netgear WNDR3400v3
 ▪ e6a06024e068 ASoC: dpcm: Properly initialise hw->rate_max
 ▪ 0a7edede513d gfs2: Don't set GFS2_RDF_UPTODATE when the lvb is updated
 ▪ 39b3ce44939a ALSA: seq: Do error checks at creating system ports
 ▪ 8ad73373b8a7 ARM: dts: at91/trivial: Fix USART1 definition for at91sam9g45
 ▪ 6d9c2f7832a9 ALSA: pcm: signedness bug in snd_pcm_plug_alloc()
 ▪ cca358eaa474 iio: dac: mcp4922: fix error handling in mcp4922_write_raw
 ▪ b827e2fa580b mmc: sdhci-of-at91: fix quirk2 overwrite
 ▪ 69ab55f2bb3f mm: hugetlb: switch to css_tryget() in hugetlb_cgroup_charge_cgroup()
 ▪ f023333e92cb mm: memcg: switch to css_tryget() in get_mem_cgroup_from_mm()
 ▪ 41ca23069f12 iommu/vt-d: Fix QI_DEV_IOTLB_PFSID and QI_DEV_EIOTLB_PFSID macros
 ▪ 44b4e78bb327 ecryptfs_lookup_interpose(): lower_dentry->d_parent is not stable either
 ▪ c3c7cfbe975c ecryptfs_lookup_interpose(): lower_dentry->d_inode is not stable
 ▪ af618124c697 Input: ff-memless - kill timer in destroy()
 ▪ d99926e1ae70 ALSA: usb-audio: not submit urb for stopped endpoint
 ▪ 66aeb2294c22 ALSA: usb-audio: Fix missing error check at mixer resolution test
 ▪ 602ff39cf2b6 ax88172a: fix information leak on short answers
 ▪ 329cb706daab slip: Fix memory leak in slip_open error path

====================
     11-24-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 1def1f695343 Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie

====================
     11-21-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 6d92ef733 rootdir: drop spectrum
 ▪ 2c23282dc Misc power.rc improvements (#7)
 ▪ c2e4634d8 Misc power.rc improvements
 ▪ 8d97a4e8f Change the default/idle GPU frequency to 214 MHz

====================
     11-20-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ 8b390b467 rootdir: merge and rebase gemini & capricorn configs
 ▪ e3194f853 Merge tag 'android-9.0.0_r50' into 9.0

 ▼ external/arm-optimized-routines/
 ▪ 268f6c1 Merge tag 'LA.UM.8.6.2.r2-00600-89xx.0' of https://source.codeaurora.org/quic/la/platform/external/arm-optimized-routines into HEAD

 ▼ vendor/havoc/
 ▪ 6c3ec374 update google prebuilt apps

====================
     11-19-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 693e648be99b Merge 4.4.202 into kernel.lnx.4.4.r37-rel

====================
     11-18-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 85cccf893139 Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie

====================
     11-17-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ bc69c961f595 Linux 4.4.202
 ▪ 6534fc5ddf88 x86/bugs: Add ITLB_MULTIHIT bug infrastructure
 ▪ b081576edd67 x86/speculation/taa: Fix printing of TAA_MSG_SMT on IBRS_ALL CPUs
 ▪ faaa0750f5c4 x86/tsx: Add config options to set tsx=on|off|auto
 ▪ d4ce17c877b1 x86/speculation/taa: Add documentation for TSX Async Abort
 ▪ f6eabafe0fa2 x86/tsx: Add "auto" option to the tsx= cmdline parameter
 ▪ 5b3b71385e07 kvm/x86: Export MDS_NO=0 to guests when TSX is enabled
 ▪ d601096be42c x86/speculation/taa: Add sysfs reporting for TSX Async Abort
 ▪ 1cdc174d7996 x86/speculation/taa: Add mitigation for TSX Async Abort
 ▪ ab7b39b99f03 x86/cpu: Add a "tsx=" cmdline option with TSX disabled by default
 ▪ 725afc0d60cf x86/cpu: Add a helper function x86_read_arch_cap_msr()
 ▪ 124635392ef3 x86/msr: Add the IA32_TSX_CTRL MSR
 ▪ b6b8d3bde6be KVM: x86: use Intel speculation bugs and features as derived in generic x86 code
 ▪ f5850490b49c kvm: x86: IA32_ARCH_CAPABILITIES is always supported
 ▪ eb5a31b4b374 KVM: x86: Emulate MSR_IA32_ARCH_CAPABILITIES on AMD hosts
 ▪ 873e2f25ccb7 KVM: Introduce kvm_get_arch_capabilities()
 ▪ 0b42886a355c powerpc/boot: Request no dynamic linker for boot wrapper
 ▪ c311fe2c7457 powerpc: Fix compiling a BE kernel with a powerpc64le toolchain
 ▪ bd52aa88e296 powerpc/Makefile: Use cflags-y/aflags-y for setting endian options
 ▪ 615ae6716945 MIPS: BCM63XX: fix switch core reset on BCM6368
 ▪ 411b1be44169 kvm: mmu: Don't read PDPTEs when paging is not enabled

====================
     11-14-2019
====================

 ▼ build/make/
 ▪ 9568d1aa2 Bump Security String to 2019-11-05
 ▪ ee6af017a gcc 5.4 arm

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 0505ddb745c8 Merge 4.4.201 into kernel.lnx.4.4.r37-rel
 ▪ 44c842b25b3c Merge 4.4.200 into kernel.lnx.4.4.r37-rel

====================
     11-13-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 6186d66524c2 Linux 4.4.201
 ▪ 6dd52bae8a01 drm/i915/cmdparser: Fix jump whitelist clearing
 ▪ 284d38667f7e drm/i915/gen8+: Add RC6 CTX corruption WA
 ▪ 1433b8d41b1a drm/i915: Lower RM timeout to avoid DSI hard hangs
 ▪ 362917ebcfac drm/i915/cmdparser: Ignore Length operands during command matching
 ▪ d88d2d3fc607 drm/i915/cmdparser: Add support for backward jumps
 ▪ 57c2c8f58ca0 drm/i915: Add gen9 BCS cmdparsing
 ▪ 2ac501479a13 drm/i915: Allow parsing of unsized batches
 ▪ 77524398bcce drm/i915: Support ro ppgtt mapped cmdparser shadow buffers
 ▪ 17e89f38212d drm/i915: Add support for mandatory cmdparsing
 ▪ 544fd7d9d4cf drm/i915: Remove Master tables from cmdparser
 ▪ 3122671a5df3 drm/i915: Disable Secure Batches for gen6+
 ▪ e5e3c0154c19 drm/i915: Rename gen7 cmdparser tables
 ▪ 3fd1c2e65c60 drm/i915/gtt: Disable read-only support under GVT
 ▪ 774b68aa2105 drm/i915/gtt: Read-only pages for insert_entries on bdw+
 ▪ 6d0cfddc7afc drm/i915/gtt: Add read only pages to gen8_pte_encode
 ▪ b575bf8be323 net: prevent load/store tearing on sk->sk_stamp
 ▪ 6c9b44791dfe cgroup,writeback: don't switch wbs immediately on dead wbs if the memcg is dead
 ▪ bfb01e6a4fb9 mm/filemap.c: don't initiate writeback if mapping has no dirty pages
 ▪ a2c0d9a93499 can: flexcan: disable completely the ECC mechanism
 ▪ 47886f293361 e1000: fix memory leaks
 ▪ 1b374b0762da igb: Fix constant media auto sense switching when no cable is connected
 ▪ 9eecc1310ff0 NFSv4: Don't allow a cached open with a revoked delegation
 ▪ 5c2da8de678b net: hisilicon: Fix "Trying to free already-free IRQ"
 ▪ 913a2c73e1e6 scsi: qla2xxx: stop timer in shutdown path
 ▪ c4dc7c7af4cc USB: Skip endpoints with 0 maxpacket length
 ▪ 123d58e1ac8a perf/x86/amd/ibs: Fix reading of the IBS OpData register and thus precise RIP validity
 ▪ a6af4089638e usb: gadget: configfs: fix concurrent issue between composite APIs
 ▪ ef4590495118 usb: gadget: composite: Fix possible double free memory bug
 ▪ 8748e69e7e3d usb: gadget: udc: atmel: Fix interrupt storm in FIFO mode.
 ▪ 260f8a602775 usb: fsl: Check memory resource before releasing it
 ▪ 6c67be51113e bonding: fix unexpected IFF_BONDING bit unset
 ▪ f00565130bde ipvs: move old_secure_tcp into struct netns_ipvs
 ▪ 43165d64b74a scsi: lpfc: Honor module parameter lpfc_use_adisc
 ▪ 9f21002d3b8a scsi: qla2xxx: fixup incorrect usage of host_byte
 ▪ dd47fd5ba80a PCI: tegra: Enable Relaxed Ordering only for Tegra20 & Tegra30
 ▪ 0120fc18b347 configfs: fix a deadlock in configfs_symlink()
 ▪ d1d4c4364724 drivers: usb: usbip: Add missing break statement to switch
 ▪ 1afef2b7a5d8 can: peak_usb: fix slab info leak
 ▪ 7f18860337d7 can: gs_usb: gs_can_open(): prevent memory leak
 ▪ c41a025d6411 can: peak_usb: fix a potential out-of-sync while decoding packets
 ▪ def6b03f667b can: c_can: c_can_poll(): only read status register after status IRQ
 ▪ 4096b1402ea4 can: usb_8dev: fix use-after-free on disconnect
 ▪ 119f371c0936 netfilter: ipset: Fix an error code in ip_set_sockfn_get()
 ▪ b10f57eb8982 netfilter: nf_tables: Align nft_expr private data to 64-bit
 ▪ c1bbd9808c40 iio: imu: adis16480: make sure provided frequency is positive
 ▪ 2c5e0e605073 ceph: fix use-after-free in __ceph_remove_cap()
 ▪ b7ac794ec5af drm/radeon: fix si_enable_smc_cac() failed issue
 ▪ 9aeedfc71ce8 perf tools: Fix time sorting
 ▪ b9b313249172 dump_stack: avoid the livelock of the dump_lock
 ▪ a6d17aa291ca mm, vmstat: hide /proc/pagetypeinfo from normal users
 ▪ 72f99285e2c1 ALSA: hda/ca0132 - Fix possible workqueue stall
 ▪ 70f79945ade2 ALSA: bebob: fix to detect configured source of sampling clock for Focusrite Saffire Pro i/o series
 ▪ 73463008aa79 nfc: netlink: fix double device reference drop
 ▪ 9025d23cfc30 qede: fix NULL pointer deref in __qede_remove()
 ▪ 0c5f54da3387 NFC: st21nfca: fix double free
 ▪ a5f9f1aca5d5 NFC: fdp: fix incorrect free object
 ▪ 817e5140ed12 net: fix data-race in neigh_event_send()
 ▪ 7ff40996bb2f CDC-NCM: handle incomplete transfer of MTU

====================
     11-11-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 1b8629e7c9b5 Linux 4.4.200
 ▪ bb756a3f302c fs/dcache: move security_d_instantiate() behind attaching dentry to inode
 ▪ 87fb5df32174 alarmtimer: Change remaining ENOTSUPP to EOPNOTSUPP
 ▪ 9370e15d54f1 ARM: fix the cockup in the previous patch
 ▪ 52117da87994 ARM: ensure that processor vtables is not lost after boot
 ▪ 7e1992962129 ARM: spectre-v2: per-CPU vtables to work around big.Little systems
 ▪ 4628d245b5f5 ARM: add PROC_VTABLE and PROC_TABLE macros
 ▪ afa68159e492 ARM: clean up per-processor check_bugs method call
 ▪ 0350343ee6fd ARM: split out processor lookup
 ▪ 14899ca00b30 ARM: make lookup_processor_type() non-__init
 ▪ 2e9ae9a66fbb ARM: 8810/1: vfp: Fix wrong assignement to ufp_exc
 ▪ 56e635e9c9ba ARM: 8796/1: spectre-v1,v1.1: provide helpers for address sanitization
 ▪ 6bb42e6d1400 ARM: 8795/1: spectre-v1.1: use put_user() for __put_user()
 ▪ f8c5a575c5dd ARM: 8794/1: uaccess: Prevent speculative use of the current addr_limit
 ▪ 796e5eb9683b ARM: 8793/1: signal: replace __put_user_error with __put_user
 ▪ b905a10fd986 ARM: 8792/1: oabi-compat: copy oabi events using __copy_to_user()
 ▪ 8d81dfc05007 ARM: 8791/1: vfp: use __copy_to_user() when saving VFP state
 ▪ 97af4d1a2fee ARM: 8789/1: signal: copy registers using __copy_to_user()
 ▪ e0a0a5eede17 ARM: spectre-v1: mitigate user accesses
 ▪ 3ff229a261ff ARM: spectre-v1: use get_user() for __get_user()
 ▪ 5156abdf3eb8 ARM: use __inttype() in get_user()
 ▪ 0253fb210164 ARM: oabi-compat: copy semops using __copy_from_user()
 ▪ 318625c2b852 ARM: vfp: use __copy_from_user() when restoring VFP state
 ▪ d9230bf9127d ARM: signal: copy registers using __copy_from_user()
 ▪ e4f30ae336f6 ARM: spectre-v1: fix syscall entry
 ▪ 362508264436 ARM: spectre-v1: add array_index_mask_nospec() implementation
 ▪ 8143a0f9c063 ARM: spectre-v1: add speculation barrier (csdb) macros
 ▪ 0df031995c65 ARM: spectre-v2: warn about incorrect context switching functions
 ▪ 81482138c8a5 ARM: spectre-v2: add firmware based hardening
 ▪ a645847f4435 ARM: spectre-v2: harden user aborts in kernel space
 ▪ 4d027736deef ARM: spectre-v2: add Cortex A8 and A15 validation of the IBE bit
 ▪ 521bb23af00c ARM: spectre-v2: harden branch predictor on context switches
 ▪ 22b1077759ad ARM: spectre: add Kconfig symbol for CPUs vulnerable to Spectre
 ▪ 564f56594e9f ARM: bugs: add support for per-processor bug checking
 ▪ 71dd24046bfd ARM: bugs: hook processor bug checking into SMP and suspend paths
 ▪ 1797ff1ac57c ARM: bugs: prepare processor bug infrastructure
 ▪ 6ba73321bb93 ARM: add more CPU part numbers for Cortex and Brahma B15 CPUs
 ▪ 8ca266df65a4 arm/arm64: smccc-1.1: Handle function result as parameters
 ▪ 1b8430525195 arm/arm64: smccc-1.1: Make return values unsigned long
 ▪ 0d4e2980b38b arm/arm64: smccc: Add SMCCC-specific return codes
 ▪ deb97e65fa57 arm/arm64: smccc: Implement SMCCC v1.1 inline primitive
 ▪ 36329b1d312e arm/arm64: smccc: Make function identifiers an unsigned quantity
 ▪ 2217fa9f8875 firmware/psci: Expose SMCCC version through psci_ops
 ▪ 0a65b836f2bf firmware/psci: Expose PSCI conduit
 ▪ d10ce9593da9 arm64: KVM: Report SMCCC_ARCH_WORKAROUND_1 BP hardening support
 ▪ f13582bcc607 arm/arm64: KVM: Advertise SMCCC v1.1
 ▪ 3759abdf7aa7 ARM: Move system register accessors to asm/cp15.h
 ▪ a6e65291d418 ARM: uaccess: remove put_user() code duplication
 ▪ 8e0a4c101250 ARM: 8481/2: drivers: psci: replace psci firmware calls
 ▪ 596efa35fb66 ARM: 8480/2: arm64: add implementation for arm-smccc
 ▪ 91719b66d595 ARM: 8479/2: add implementation for arm-smccc
 ▪ 36e7c2e68760 ARM: 8478/2: arm/arm64: add arm-smccc
 ▪ b4fe083f59a6 ARM: 8051/1: put_user: fix possible data corruption in put_user
 ▪ e4cea4d4c5d9 dmaengine: qcom: bam_dma: Fix resource leak
 ▪ 491cd03f3b44 net/flow_dissector: switch to siphash
 ▪ 993e400581c3 inet: stop leaking jiffies on the wire
 ▪ 1475db309435 net/mlx4_core: Dynamically set guaranteed amount of counters per VF
 ▪ a1014da65697 vxlan: check tun_info options_len properly
 ▪ af26f04e074f net: add READ_ONCE() annotation in __skb_wait_for_more_packets()
 ▪ 8ac802ed7049 net: Zeroing the structure ethtool_wolinfo in ethtool_get_wol()
 ▪ 4ef32dfb62cb net: hisilicon: Fix ping latency when deal with high throughput
 ▪ 2f036ae97f3d net: fix sk_page_frag() recursion from memory reclaim
 ▪ 888913ed7d7a dccp: do not leak jiffies on the wire
 ▪ ad56882f0cba cifs: Fix cifsInodeInfo lock_sem deadlock when reconnect occurs
 ▪ 771fd6cdb9f8 MIPS: bmips: mark exception vectors as char arrays
 ▪ 265c6b8ab54c of: unittest: fix memory leak in unittest_data_add
 ▪ 550049416024 scsi: target: core: Do not overwrite CDB byte 1
 ▪ 5952dc84e22d perf kmem: Fix memory leak in compact_gfp_flags()
 ▪ e45c51514417 scsi: fix kconfig dependency warning related to 53C700_LE_ON_BE
 ▪ 880c4664458b scsi: sni_53c710: fix compilation error
 ▪ 15d24beb35ad ARM: mm: fix alignment handler faults under memory pressure
 ▪ c8561c787235 ARM: dts: logicpd-torpedo-som: Remove twl_keypad
 ▪ 04f85d1992c0 ASoc: rockchip: i2s: Fix RPM imbalance
 ▪ 43de4298fb86 regulator: pfuze100-regulator: Variable "val" in pfuze100_regulator_probe() could be uninitialized
 ▪ e5b219fb25c8 regulator: ti-abb: Fix timeout in ti_abb_wait_txdone/ti_abb_clear_all_txdone
 ▪ 5fc9e98768f7 kbuild: add -fcf-protection=none when using retpoline flags

====================
     11-10-2019
====================

 ▼ kernel/xiaomi/msm-4.4/
 ▪ f7b3cc9abc4e Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie
 ▪ cbdfb9320727 Merge branch 'android-4.4-p-release' of https://android.googlesource.com/kernel/common into pie

 ▼ kernel/xiaomi/msm8996/
 ▪ a3218a13dbde Ar

 ▼ vendor/havoc/
 ▪ 39c7af00 update changelog generation

====================
     11-09-2019
====================

 ▼ frameworks/base/
 ▪ 87289f46d50 Add MANAGED_PROVISIONING_DPC_DOWNLOADED.

