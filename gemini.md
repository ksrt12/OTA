
====================
     30-10-2019
====================

 ▼ device/xiaomi/gemini/
 ▪ dc8298fd9 rootdir: clean up
 ▪ 492ac6407 rootdir: restore time_daemon
 ▪ 4b0e2e0ef Revert "msm8996-common: Enable clearkey drm plugin v1.2"

 ▼ kernel/xiaomi/msm-4.4/
 ▪ 3c6f784842db Merge branch 'upstream-linux-4.4.y' of https://android.googlesource.com/kernel/common into HEAD
 ▪ da259d0284b6 Linux 4.4.198
 ▪ 3cd0698561d3 RDMA/cxgb4: Do not dma memory off of the stack
 ▪ 23e0c38d3099 net: sched: Fix memory exposure from short TCA_U32_SEL
 ▪ 439a1962649e PCI: PM: Fix pci_power_up()
 ▪ b3310bf507ee xen/netback: fix error path of xenvif_connect_data()
 ▪ 8bfa06ea6e81 cpufreq: Avoid cpufreq_suspend() deadlock on system shutdown
 ▪ 44137b2cfad1 memstick: jmb38x_ms: Fix an error handling path in 'jmb38x_ms_probe()'
 ▪ df514f91210c btrfs: block-group: Fix a memory leak due to missing btrfs_put_block_group()
 ▪ 0fef1c7da4b4 CIFS: avoid using MID 0xFFFF
 ▪ b7f9ec253c28 parisc: Fix vmap memory leak in ioremap()/iounmap()
 ▪ e1eccccb24b8 xtensa: drop EXPORT_SYMBOL for outs*/ins*
 ▪ cff989b79e3d mm/slub: fix a deadlock in show_slab_objects()
 ▪ 8af008849fe5 scsi: zfcp: fix reaction on bit error threshold notification
 ▪ b5b88cda3e8f drm/edid: Add 6 bpc quirk for SDC panel in Lenovo G50
 ▪ 86962d9a79b0 mac80211: Reject malformed SSID elements
 ▪ 3ca40f2f6015 cfg80211: wext: avoid copying malformed SSIDs
 ▪ 65ac31fb6e6d ASoC: rsnd: Reinitialize bit clock inversion flag for every format setting
 ▪ a7d04d58621d scsi: core: try to get module before removing device
 ▪ 44d3e9852350 USB: ldusb: fix read info leaks
 ▪ 3e4cf06e1938 USB: usblp: fix use-after-free on disconnect
 ▪ a81304eb043c USB: ldusb: fix memleak on disconnect
 ▪ be742b0bd9e9 USB: serial: ti_usb_3410_5052: fix port-close races
 ▪ ebcfd766cde6 usb: udc: lpc32xx: fix bad bit shift operation
 ▪ 5610f75e5ba8 USB: legousbtower: fix memleak on disconnect
 ▪ eb4058d8daf8 memfd: Fix locking when tagging pins
 ▪ 85088e38708c ipv4: Return -ENETUNREACH if we can't create route but saddr is valid
 ▪ ca0cd16beccc net: avoid potential infinite loop in tc_ctl_action()
 ▪ 9befdc6645ac sctp: change sctp_prot .no_autobind with true
 ▪ 0ed0978c29db net: bcmgenet: Set phydev->dev_flags only for internal PHYs
 ▪ 571e5f93e756 net: bcmgenet: Fix RGMII_MODE_EN value for GENET v1/2/3
 ▪ 896bb98754dc loop: Add LOOP_SET_DIRECT_IO to compat ioctl
 ▪ 27add8a99692 namespace: fix namespace.pl script to support relative paths
 ▪ 74b2bee56dc0 net: hisilicon: Fix usage of uninitialized variable in function mdio_sc_cfg_reg_write()
 ▪ ebc93dc0b776 mips: Loongson: Fix the link time qualifier of 'serial_exit()'
 ▪ 4f7a59b56a61 nl80211: fix null pointer dereference
 ▪ eb5aa18fbb9c ARM: dts: am4372: Set memory bandwidth limit for DISPC
 ▪ d08c1d749087 ARM: OMAP2+: Fix missing reset done flag for am3 and am43
 ▪ 36f88520f1e9 scsi: qla2xxx: Fix unbound sleep in fcport delete path.
 ▪ b0ba41e0a977 scsi: megaraid: disable device when probe failed after enabled device
 ▪ aa64c3afcb8c scsi: ufs: skip shutdown if hba is not powered

 ▼ kernel/xiaomi/msm8996/
 ▪ a8d69ba83556 arm64: configs: capricorn_defconfig: re-enable CONFIG_QPNP_HAPTIC
 ▪ 819f5a572c86 msm: ipa: Move NAT invalid protocol define to uapi
 ▪ ba814dab23e3 vdso: update Makefile

 ▼ vendor/xiaomi/
 ▪ 16dabd70 drop land

====================
     28-10-2019
====================

 ▼ hardware/qcom/audio-caf/msm8996/
 ▪ bd391c8c Merge tag 'LA.UM.8.6.r1-02300-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

====================
     27-10-2019
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

