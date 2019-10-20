
====================
     10-20-2019
====================


   * device/xiaomi/gemini/
068f3c2cb Revert "msm8996-common: Enable clearkey drm plugin v1.2"
8a17fc7c0 rootdir: clean up
e82f10ede rootdir: gemini: restore time_daemon
ced4cd99a vendor_prop: add some tweaks
414a17c6b Revert "msm8996: use stock USB hal"
c1689093b Revert "msm8996-common: add prop persist.vendor.usb.config.extra"
e56f85014 rootdir: update usb to LA.UM.7.5.2.r1-03700-8x96
abaef7ebf msm8996-common: Remove firmware class path for kernel firmware loading
f1da56a34 msm8996-common: Add /vendor/firmware_mnt/image to firmware_directory path
1f403a6b7 msm8996-common: Change ownership of /vendor/firmware_mnt/image
a71f29988 BoardConfig: use gcc 9.2 for TARGET_KERNEL_CROSS_COMPILE_ARM32
efda28dbd Revert "msm8996: use vidc from msm8998"

   * frameworks/native/
d18488724 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/native into HEAD

   * kernel/xiaomi/msm-4.4/
652712fa3e98 Revert "dmaengine: Fix memory leak in dma_async_device_register"

   * kernel/xiaomi/msm8996/
ef0d40464b8c defconfig: enable new feature
220e1d5dc2f8 kbuild: clean up link rule of composite modules
ac2763b47500 kbuild: improve linker compatibility with lib-ksyms.o build
009b8ad873cf kbuild: remove CONFIG_HAVE_UNDERSCORE_SYMBOL_PREFIX
e2ac227e4d20 kbuild: cmd_export_list: tighten the sed script
d50e77c8a1cc kbuild: reword help of LD_DEAD_CODE_DATA_ELIMINATION
4a5d45eca787 arm64: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selected
ad33fbbaa26c kbuild: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selectable if enabled
61f28a9f8da6 kbuild: LD_DEAD_CODE_DATA_ELIMINATION no -ffunction-sections/-fdata-sections for module build
dfbf3ebb4fae kbuild: Fix asm-generic/vmlinux.lds.h for LD_DEAD_CODE_DATA_ELIMINATION
bd21964549b1 FROMLIST: BACKPORT: arm64: keep .altinstructions and .altinstr_replacement
f5985aab108b arm64: fix LD_DEAD_CODE_DATA_ELIMINATION
7de5d49feffb FROMLIST: kbuild: fix LD_DEAD_CODE_DATA_ELIMINATION
3386608d72f9 kbuild: linker script do not match C names unless LD_DEAD_CODE_DATA_ELIMINATION is configured
cf89a0378daf kbuild: keep data tables through dead code elimination
aa482dee35cc kbuild: avoid conflict between -ffunction-sections and -pg on gcc-4.7
befb5c109437 kbuild: -ffunction-sections fix for archs with conflicting sections
fe8e06318321 kbuild: allow archs to select link dead code/data elimination
f5abc1c706d8 kbuild: clean up archive rule of built-in.a
8de7b79f4a2e kbuild: remove partial section mismatch detection for built-in.a
97fc33adecba kbuild: link $(real-obj-y) instead of $(obj-y) into built-in.a
2704d9327db1 [kbuild] handle exports in lib-y objects reliably
30ff70969cc8 kbuild: rename real-objs-y/m to real-obj-y/m
71aba6e171b1 kbuild: drop $(extra-y) from real-objs-y
150eceece93c kbuild: Allow to specify composite modules with modname-m
1dd33e7d5f44 kbuild: create built-in.o automatically if parent directory wants it
2f1dd3abf0d4 kbuild: rename built-in.o to built-in.a
f2bf961520b5 kbuild: remove incremental linking option
9225f8d9b72d kbuild: handle libs-y archives separately from built-in.o archives
c75cf715bc0d kbuild: thin archives make default for all archs
43d00c00983d kbuild: thin archives use P option to ar
1711bc67dc28 kbuild: thin archives for multi-y targets
a5dc222086eb kbuild: thin archives final link close --whole-archives option
c1825316834d kbuild: minor improvement for thin archives build
e88419826e62 kbuild: allow architectures to use thin archives instead of ld -r
5e25a2124a98 Makefile: add minimal flags
0d8744662235 Makefile: opt-out from 835769/843419 errata fixes
0357f18eea97 Makefile: O3 it up for host executables

   * vendor/xiaomi/
9bebc1e4 Revert "gemini: Update PN548 firmware"
a9c62172 gemini: Update PN548 firmware
6b805f46 gemini: Remove unused tfa firmware
e1337fef gemini: Move Forte acdbdata
6afadf04 msm8996-common: Move camera configs to /vendor

====================
     10-19-2019
====================


   * hardware/qcom/audio-caf/msm8996/
22478dcb audio-hal: always treat v4 as NULL

   * hardware/qcom/media-caf/msm8996/
d9ba2d86 msm8996: use generated kernel headers
4b2e84a6 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into lineage-17.0-caf-msm8996

   * kernel/xiaomi/msm-4.4/
27708b993796 defconifg: We are Soda now
ff061f8f8677 defconfig: tune entropy parameters
a358aa23ae7a Makefile: add minimal flags
ead5b942b911 defconfig: disable ultrasound
7a1798efabbd cpufreq: Drop unnecessary checks from show() and store()
dfacd246458b cpufreq: Make cpufreq_boost_supported() static
69fc351f4ca6 dma_buf: use kmem_cache pool for struct dma_buf_attachment
39e445ad1291 msm: kgsl: use kmem_cache pool for draw objects
f81578b0c2b4 kernfs: use kmem_cache pool for struct kernfs_open_node/file
7e961c4f17f1 cgroup: use kmem_cache pool for struct cgrp_cset_link
42894c4411c0 sdcardfs: use kmem_cache pool for struct sdcardfs_file_info
b2b4660a80b8 selinux: reduce calls to context_struct_to_string()
a8182b3ce439 cpuidle: enter_state: Don't needlessly calculate diff time
8b194bc1d5aa swait: strengthen language to discourage use
faa9186f437f sched/wait: Include <linux/wait.h> in <linux/swait.h>
a171fad914e5 sched/swait: Document it clearly that the swait facilities are special and shouldn't be used
51edecdf0021 sched/wait: Add swq_has_sleeper()
a7b256e18a23 swait: Add idle variants which don't contribute to load average
01ead1e7b3f9 sched/swait: Switch to full exclusive mode
151273985bbc sched/swait: Remove __prepare_to_swait
d733812d0f4d sched/wait: Remove the lockless swait_active() check in swake_up*()
63cb4be82250 wait.[ch]: Introduce the simple waitqueue (swait) implementation
20c7604ea2a1 rcuperf: Fix cleanup path for invalid perf_type strings
b041ed476276 tags: Fix DEFINE_PER_CPU expansions
2c92c14e61b5 rcu: Import rcu_segcblist_entrain()
01605db6e2cf srcu: Abstract multi-tail callback list handling
c49dbf7c2201 rcu: Prevent rcu_barrier() from starting needless grace periods
0674fefb914a rcu: Speed up calling of RCU tasks callbacks
7c8ead0b1e03 rcu: Use idle versions of swait to make idle-hack clear
11cb733b52e2 rcu: Don't wake rcuc/X kthreads on NOCB CPUs
4f881f8230a8 rcu: Abstract the dynticks snapshot operation
43b7125f3fd0 rcu: Abstract the dynticks momentary-idle operation
ecad0285eb26 rcu: Don't kick unless grace period or request
fa4cb60fe463 rcu: Make expedited grace periods recheck dyntick idle state
70a505f276be rcu: Squash commits through android kernel 4.9.96
fe23c6f5171f Revert "rcu: Speed up calling of RCU tasks callbacks"
b03a0c032c50 Revert "rcu: Prevent rcu_barrier() from starting needless grace periods"
9a51cd4e6a9e Revert "rcu: Make cond_resched_rcu_qs() supply RCU-sched expedited QS"
3155d19a6eff Revert "rcu: Don't wake rcuc/X kthreads on NOCB CPUs"
e2f36f267683 Revert "srcu: Abstract multi-tail callback list handling"
ded58202ece6 Revert "rcu: Import rcu_segcblist_entrain()"
a421c05fb104 Revert "tags: Fix DEFINE_PER_CPU expansions"
842e8e520b14 drivers: cpuidle: disallow userspace to disable cpuidle
51f4d24e0925 drivers: power: qpnp-fg: Don't copy states of non-ratelimited properties
c572dbd4338a [PORT] drivers: power: qpnp-fg: Limit how frequently fg data can be queried
22a777c73570 drivers: power: qpnp-fg: use power efficient queues for some works
b13a92bb46ed dts: strip unused panels
b1d9d26965cb dts: decommonize BCL mitigation freq
884e54a87dd5 ASoC: wcd-mbhc: Improve detection speed and accuracy
5b5164648145 ext4 crypto: Avoid dynamically allocating memory for file names
648257f5b642 dmaengine: Fix memory leak in dma_async_device_register
796c54c3bd0d mm/slab_common: Align all caches' objects to hardware cachelines
be73c94b4ccf power: msm-core: Fix mutex not getting unlocked in error path
3f614fcb5c02 zram: allow zram to allocate CMA pages
29039ee196fd fs/fs-writeback.c: remove redundant if check
b66aca6332af mm, writeback: flush plugged IO in wakeup_flusher_threads()
252b7d543cfb writeback: Write dirty times for WB_SYNC_ALL writeback
c57f9273539e fs/fs-writeback.c: inode writeback list tracking tracepoints
6b3b3fd0afba fs/fs-writeback.c: add a new writeback list for sync
fa06b2404cd8 writeback: inode cgroup wb switch should not call ihold()
69b6b62720d5 mm,writeback: don't use memory reserves for wb_start_writeback
c970185464df PM: devfreq: Use high priority workqueue
804b01f016dc sched/core: Enable increased load resolution on 64-bit kernels
333f97708027 msm: mdss: fix inconsistent mutex_lock
f10d736a8822 msm: mdss: fix inconsistent mutex_lock
2c7cdb1644c1 pwm: qpnp: Fix qcom HW known issue
fa984e82f298 msm_serial_hs: make the Bluetooth tty thread RT
683d9d6a450e tty: add tty_port_set_policy function
7732da0103a3 tty:  check before stopping kthread
c73d030fd112 tty: move tty_port workqueue to be a kthread
67a4165362e1 interactive: avoid calling usecs_to_jiffies() repeatedly
55a89459202b CHROMIUM: cpufreq: interactive: calculate load before freq change
7f11f0dbae12 cpufreq: interactive: Remove the jump_to_max hack
90cfd5505757 binfmt_elf.c: use get_random_int() to fix entropy depleting
315d1d324ed1 cpufreq: interactive: remove hispeed_freq init restriction
f253ba37ab8b sched/loadavg: Use {READ,WRITE}_ONCE() for sample window
550823faa904 msm: kgsl: Report correct GPU frequency in sysfs
fedc22a8b361 Make msm_serial_hs RT to improve bluetooth performance
57bf9a0adb28 msm: mdss: fix inconsistent mutex_lock
65cca7a32688 serial: msm_serial_hs: Protect spurious irqs after wakeup irq enablement
bdf5fc4a11d8 drivers: power: bcl: queue work on system_power_efficient_wq
560945a91799 power: bcl: queue work on system_power_efficient_wq
79ae5793c6da qcom: msm-core: queue work on system_power_efficient_wq
c911c1f825bc drivers: mdss: queue input handler functions to a high prio wq
4dd7f6fcdb05 drivers: thermal: queue work on system_power_efficient_wq
bf05a2caabc7 scsi: ufs: disable auto hibern8
e282b48dc686 scsi: ufs: Increase crypto thread priority
36e1e895c619 power: msm-core: Compile out temperature polling
69983c972bfd qcom: msm-core: uninterruptible wait - you can kiss my arse goodbye
66ebb4ade02c qcom: mpm: use interruptible wait to reduce load avg
447f8ce3b5d1 PM / devfreq: gpubw_mon: Add null check for governor private data
9ad8cbcdb7b8 devfreq: update freq variable in compute_freq function
57df97145fc7 PM / devfreq: memlat: Improve tracing of stats and votes
34cc5f066b59 PM / devfreq: arm-memlat-mon: Delete event count overflow handling code
6a829c421d7e PM / devfreq: bw_hwmon: Add missing mutex unlock
35289d81ef93 PM / devfreq: memlat: Don't ignore extremely latency sensitive workloads
fa218440c134 power: qpnp-fg: have sanity check beat once before wakelock
b24fe4788c9e Speed up console framebuffer imageblit function
720754703175 drivers: msm: ipa_v2: don't hold a wakelock
663e80d03dcb arm64: DT: MSM8996: Fix power management nodes for k4.9 LPM
d7373089d1b9 drivers: lpm-levels: fix GCC warning
e23ff8620bba drivers: lpm-levels: remove unused include
31759a7ecf29 drivers: cpuidle: lpm-levels: Update ordering for broadcast timer
465c68f49694 drivers: cpuidle: lpm-levels: Export symbols used by audio
50616a8fdadd drivers: cpuidle: lpm-levels: LPM prediction tuning
6bb6c3ddfd77 drivers: cpuidle: lpm-levels: Move local_irq_enable
9c8d20be994a drivers: cpuidle: lpm-levels: Check for null parent
2f7813d62055 cpuidle: lpm-levels: Suppress driver bind/unbind feature
17b02cb810a6 drivers: cpuidle: lpm-levels: Correctly check for list empty
3759b9393a04 drivers: cpuidle: lpm-levels: Fix KW issues with idle state idx < 0
698c4545102b drivers: cpuidle: lpm-levels: Update CPU prediction timer
e372343d2205 drivers: cpuidle: lpm-levels: Correct missing list initialize
439326c84986 cpuidle:lpm: Fix div by zero bug
3e376d0cacd4 cpuidle: check dev before usage in cpuidle_use_deepest_state()
37fd80bb26e1 cpuidle: Allow enforcing deepest idle state selection
46b7432f3481 drivers: cpuidle: lpm-levels: Reset suspend wake time
c2b6e6334200 cpuidle: lpm-levels: Do not predict LPM for isolated cpus
dac5e893a7b6 lpm_levels: Return true for CPU WFI mode allow check
a18049eb801d defconfig: disable AUDIT
03a2de7ad845 defconfig: set anxiety as default io scheduler
816c7d748b13 defconfig: disable frame pointers
c73c6bc6cbf0 block: anxiety: Clean up queue data variable initialization
0f4d7409aace block: anxiety: Use built-in former / latter handlers
47b67b2d6fdb block: anxiety: Add logic for sync block requests
5e2672eaa3d5 block: anxiety: Align list head to L1 cache line
359fff5372be block: Introduce Anxiety I/O Scheduler
bc49a05662d1 defconfig: disable menu
7a60ce301de3 defconfig: disable profiling
e41655ee87cc dcache: increase DNAME_INLINE_LEN
eca02561877a memory_state_time: Remove dependency on profiling support
96f41198d832 defconfig: enable RCU boost
5914bee4dfb3 uid_sys_stats: Remove dependency on the profiling subsystem
4f1ec0fa8898 dts: increase temperature polling interval
1d21e8412a5b defconfig: enable zram writeback
c705809057b6 defconfig: enable optimized inlining
a5f05feab274 mm: Always overcommit memory by default
531fc721d70b net: rmnet_data: disable logging
2b6059e62a44 usb_bam: disable event log by default
f78790d8e6be net: ipv4: enable support for TCP fast open on listeners
42b3c557f914 cpuidle: Make MENU cpuidle governor optional
37f6a82209f9 sched/fair: Make scheduling period more efficient
5a6efb88351f ashmem: Align slab caches to L1 cache line
46ec4fc0a02c sdcardfs: Align dentry slab cache to L1 cache line
6939198ed6f6 media: v4l: Use interruptible waits
2d6e1ea284ac msm: sde: Use interruptible waits
4d3d77609d63 genirq: Use interruptible wait
ed4a1f2cc7ef msm: kgsl: Use interruptible waits
f662ef1524ff block: Use interruptible waits
176351f1338e msm: mdss: Use interruptible waits
4fe536c90d0d block: Disable preemption during IPI consideration
19d3b7af9288 power: bcl: Improve power efficiency of the workqueue
8e4869b7fafb mm: Do not reserve memory for admins
12a14f5b9d16 mm: Increase vmstat interval
6ffe9ac6253a tcp: Enable fast recycling by default
f1cb0b930388 tcp: Reuse existing connections
30de2b07a8ac tcp: Disable slow start after idle by default
547b82b0d5bc arch: Allow all archs to select optimized inlining
b3d67972d15c usb: policy_engine: Remove workqueue high-priority flag
66129b702fae msm: ipa_v2: Remove workqueue high-priority flag
9bcb75d1910a thermal: qpnp-adc-tm: Remove workqueue high-priority flag
13fd4cee5361 cpuidle: lpm-workarounds: Remove workqueue high-priority flag
1721ee8fdfbd thermal: msm-tsens: Reduce workqueue priority
06c775f0d99c defconfig: Disable unused ethernet devices
6e33029e51ca defconfig: disable frame larger than warning
d37d5dc41b73 qseecom: Add empty functions to allow disable
12b39955b155 defconfig: disable unused stuff
3c72f96f55d8 irqchip: Allow show resume irq logging to be disabled
9bd8c4b37a7c defconfig: disable legacy camera
ba2919679b7a defconfig: disable mhi
317cd16d9728 defconfig: disable kernel debugging
d855b50fb92a defconfig: enable new features
ff6141b30c76 Makefile: opt-out from 835769/843419 errata fixes
dc1b7b5986d8 dts: remove emmc_therm
93ec0da7e4b0 qpnp-fg: Implement SUPPORT_SOC_SHOW_OPTIMIZATION
1927bdc1ef24 drivers: power: smbcharger: bring back some Xiaomi edits
cf7734ebf60f drivers: power: qpnp-smbcharger: correct power supply name
b038e2075d2f drivers: power: smb1351: import xiaomi changes
f833fc3c5ea4 arm64: use simpler API for random address requests
9e1a9e22183d arm64: kernel: Fix incorrect brk randomization
ed62adfae3fa [PORT] drv2604: Disable haptics while camera is in use
05193cb5d7f7 lib: chacha20: use NEON optimized library instead of standard one
25ae637e5e8c random: rate limit unseeded randomness warnings
36b2cfebf9cc random: fix possible sleeping allocation from irq context
29adf4f88a2f random: set up the NUMA crng instances after the CRNG is fully initialized
6280b43e1084 random: add new ioctl RNDRESEEDCRNG
99405099ca3b random: crng_reseed() should lock the crng instance that it is modifying
133afdf29a38 random: fix crng_ready() test
a2c8d3cd9964 random: use a tighter cap in credit_entropy_bits_safe()
efd7175e1767 random: convert get_random_int/long into get_random_u32/u64
074b294e555d random: use chacha20 for get_random_int/long
9d23638a62ab random: remove unused randomize_range()
3d22c923c420 random: simplify API for random address requests
355319f0093c random: Fix crashes with sparse node ids
f462ac6ab9ee random: use for_each_online_node() to iterate over NUMA nodes
edcd579321f6 random: strengthen input validation for RNDADDTOENTCNT
8417857f3b03 random: add backtracking protection to the CRNG
ba324aa4a212 random: make /dev/urandom scalable for silly userspace programs
e6f502eb544e random: replace non-blocking pool with a Chacha20-based CRNG
83551322a47f char: Kconfig: create default read/write entropy configs
fed142fc2e59 arm64: add support for int128
27ab759750d3 crypto: arm64/sha256 - increase cra_priority of scalar implementations
08aee7ff7ca7 crypto: arm64/sha256-neon - play nice with CONFIG_PREEMPT kernels
f028556e8784 crypto: arm64/sha2-ce - add non-SIMD scalar fallback
6e65fa37f8c0 crypto: arm64/sha2 - integrate OpenSSL implementations of SHA256/SHA512
c0bd577b4fae crypto: arm64/sha2-ce - move the round constant table to .rodata section
0ccd22c43fdb drivers: block: zram: set LZ4 as default compression algorithm
0f721aed4c25 lib/lz4: update LZ4 decompressor module
3f7414fc83a2 lib/lz4: make arrays static const, reduces object code size
c801d3e0be19 lib/lz4: remove back-compat wrappers
817e8f9e9721 crypto: lz4 - fixed decompress function to return error code
eea763e93a05 BACKPORT: crypto: change LZ4 modules to work with new LZ4 module version
9d1485643f48 lib: update LZ4 compressor module
3cbcdd6e015c lib/crc32.c: mark crc32_le_base/__crc32c_le_base aliases as __pure
b3a7d5a0f438 lib/crc32: make core crc32() routines weak so they can be overridden
b60007028127 arm64/lib: improve CRC32 performance for deep pipelines
331a50429d67 arm64/lib: add accelerated crc32 routines
6dcbb6898a5a arm64: crypto: add NEON accelerated XOR implementation
80619fdc3917 arm64: lib: memcmp: improve medium-large sizes
42b1d65170e4 arm64: lib: increase speed with prefetching
b0f0eb7d393b arm64: lib: update strlen function
84580959cf3c arm64: Add enchanted memcmp
25e3702525b6 arm64: libs: import enchanted strncmp
ed488b66c477 ANDROID: binder: correct the cmd print for BINDER_WORK_RETURN_ERROR
1f5c32e6e8d2 binder: fix incorrect cmd to binder_stat_br
e3f67001c8e7 fib_rules: Fix payload calculation
552424a4e602 net/ipv4: fib_trie: Avoid cryptic ternary expressions
9f2f3af31584 ANDROID: sdcardfs: Allocate temporary name buffer on the stack
09c26eb6c805 kobject_uevent: Allocate environment buffer on the stack
df3d17fbfc35 ion: system_heap: Speed up system heap allocations
fe990d4f3b94 ANDROID: crypto: heh - Avoid dynamically allocating memory for keys
cd8d086aff4a ext4: Avoid dynamically allocating memory in ext4_ext_remove_space
0034fd36a4b5 xattr: Avoid dynamically allocating memory in getxattr
76f0212fd3dc binfmt_elf: Don't allocate memory dynamically in load_elf_binary
a6bae5467b38 staging: sync: Use an on-stack allocation for fence info ioctl
d00c03658ab8 media: v4l2-ioctl: Use larger on-stack video copy buffers
5c4cf5c9625f msm: camera: Optimize memory allocation for small buffers
357d69301422 msm: kgsl: Don't allocate memory dynamically for temp command buffers
67e7f0648179 ext4 crypto: Use a larger on-stack file name buffer
80dffd2bf534 Revert "ext4 crypto: Use a larger on-stack file name buffer"
3a5975ece7ad selinux: Avoid dynamic memory allocation for small context buffers
34add377f49c Revert "selinux: Avoid dynamic memory allocation for small context buffers"
bd86eb2d6112 kernfs: Avoid dynamic memory allocation for small write buffers
be652172f566 msm: kgsl: Avoid dynamically allocating small command buffers
2957d9209244 Revert "msm: kgsl: Avoid dynamically allocating small command buffers"
0a34c398d226 scsi: ufs: Only apply pm_qos to the CPU servicing UFS interrupts
6d4539259886 qos: Don't disable interrupts while holding pm_qos_lock
1df6a5d7d9c5 scsi: ufs: Remove 10 ms CPU idle latency unvote timeout
ba8bb3a8f440 sched/tune: Hard-code top-app's stune boost to 1
b5b38160ce28 sched/tune: Hard-code top-app's stune boost to 1
57c2cbeb94a9 cpuidle: lpm-levels: Remove debug event logging
8ca83672fd1b soc: qcom: service-locator: Fix memory leak in pd_locator_work
1c73d4f4ce40 pinctrl: qcom: Update irq handle for GPIO pins
d0011d952393 drivers: drv2604: fix misleading identation
45741049b177 drv2604: convert wakelock to wakeup
6256b715e6d4 kbuild: clean up link rule of composite modules
0e5719c86052 kbuild: improve linker compatibility with lib-ksyms.o build
742d1eb26b04 kbuild: remove CONFIG_HAVE_UNDERSCORE_SYMBOL_PREFIX
c98d994793ca kbuild: cmd_export_list: tighten the sed script
45daa6f30804 kbuild: reword help of LD_DEAD_CODE_DATA_ELIMINATION
f08a9d5bbcde arm64: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selected
57aba1fa6676 kbuild: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selectable if enabled
bb225d1acf80 kbuild: LD_DEAD_CODE_DATA_ELIMINATION no -ffunction-sections/-fdata-sections for module build
f0d190b31237 kbuild: Fix asm-generic/vmlinux.lds.h for LD_DEAD_CODE_DATA_ELIMINATION
21679d554525 FROMLIST: BACKPORT: arm64: keep .altinstructions and .altinstr_replacement
0bb029b713b5 arm64: fix LD_DEAD_CODE_DATA_ELIMINATION
55066f0b37f5 FROMLIST: kbuild: fix LD_DEAD_CODE_DATA_ELIMINATION
bd465b01b3b2 kbuild: linker script do not match C names unless LD_DEAD_CODE_DATA_ELIMINATION is configured
7ff11fbf21f2 kbuild: keep data tables through dead code elimination
ff443ed7df32 kbuild: avoid conflict between -ffunction-sections and -pg on gcc-4.7
ffadd3dcc76e kbuild: -ffunction-sections fix for archs with conflicting sections
15cd96e17d99 kbuild: allow archs to select link dead code/data elimination
8e5eeb5d6723 kbuild: clean up archive rule of built-in.a
7d9dc245a8d0 kbuild: remove partial section mismatch detection for built-in.a
9dde3ce25f5e kbuild: link $(real-obj-y) instead of $(obj-y) into built-in.a
f648dcbae3d2 [kbuild] handle exports in lib-y objects reliably
5d65e46d6b7b kbuild: rename real-objs-y/m to real-obj-y/m
840a26e6b57b kbuild: drop $(extra-y) from real-objs-y
ccf1795ff7e4 kbuild: Allow to specify composite modules with modname-m
76777104b43e kbuild: create built-in.o automatically if parent directory wants it
4b83a1990836 kbuild: rename built-in.o to built-in.a
1a8887746ebb kbuild: remove incremental linking option
08f2be3136ff kbuild: handle libs-y archives separately from built-in.o archives
d0761c2c87ec kbuild: thin archives make default for all archs
13b377179221 kbuild: thin archives use P option to ar
ff39334b39a7 kbuild: thin archives for multi-y targets
d1234af4837c kbuild: thin archives final link close --whole-archives option
2c8496bcec3d kbuild: minor improvement for thin archives build
6fe6863a8724 kbuild: allow architectures to use thin archives instead of ld -r
0e009d24c2ed msm: vidc: Remove compiler dependent code
e3eef61c143f ext4: Allocate allocation-context on the stack
3d37a373dcb3 scatterlist: Don't allocate sg lists using __get_free_page
94133a4b4cb9 iommu: arm-smmu: Free pgtbl ops when domain contexts are destroyed
8cb81932508b ALSA: control_compat: Don't dynamically allocate single-use structs
b73d9eb482fb msm: mdss: Don't allocate memory dynamically for small layer buffers
4b10c1fbcf64 msm: kgsl: Don't allocate memory dynamically for drawobj sync structs
772247f2ada3 msm: kgsl: Don't try to wait for fences that have been signaled
8b15c8b062b8 staging: sync: Add a function to check if a fence has been signaled
cfe48830cbd8 binder: Reserve caches for small, high-frequency memory allocations
cf63cfb41f0a staging: android: ashmem: Get rid of the big mutex lock
e1f003e9e026 msm: camera: Undo pm_qos request upon error
f7965fc72295 kernel: Don't allow IRQ affinity masks to have more than one CPU
f60f01c961e4 qos: Don't disable interrupts while holding pm_qos_lock
270dda5c0cd3 staging: sync: Remove fence names by default
572c411c278f msm: kgsl: give GPU more freq
c07f8047606b fix some warnigs
19ab08b0dc26 FROMLIST: arm64: Build vDSO with -ffixed-x18
56c7e1940df4 FROMLIST: arm64: vdso32: Use full path to Clang instead of relying on PATH
a78ae97784d3 vdso32: Invoke clang with correct path to GCC toolchain
a570bc83ff86 ANDROID: clock_gettime(CLOCK_BOOTTIME,) slows down >20x
2cd2f2831586 ANDROID: CROSS_COMPILE_ARM32 must work if CONFIG_COMPAT_VDSO
8cc42673e85a FROMLIST: BACKPORT: [PATCH 6/6] arm64: Wire up and expose the new compat vDSO
a7bf81675aaa FROMLIST: BACKPORT: [PATCH 5/6] arm64: compat: 32-bit vDSO setup
f71a8edc92d5 FROMLIST: [PATCH 4/6] arm64: compat: Add a 32-bit vDSO
c6e6ec41d834 FROMLIST: [PATCH 3/6] arm64: Refactor vDSO init/setup
ae58bb6bc59b FROMLIST: [PATCH 2/6] arm64: elf: Set AT_SYSINFO_EHDR in compat processes
bfce768572a0 FROMLIST: [PATCH 1/6] arm64: compat: Use vDSO sigreturn trampolines if available
79daf75eaff8 FROMLIST: lib: vdso: add support for time
92bbb0906a21 FROMLIST: [PATCH] arm64: compat: Expose offset to registers in sigframes
bf670e816846 FROMLIST: [PATCH v5 12/12] lib: vdso: do not expose gettimeofday, if no arch supported timer
3f150aaad0ff FROMLIST: [PATCH v5 11/12] lib: vdso: Add support for CLOCK_BOOTTIME
5fc6eb463d4b FROMLIST: [PATCH v5 10/12] arm64: vdso: replace gettimeofday.S with global vgettimeofday.C
e647bbaecf53 FROMLIST: [PATCH v5 09/12] arm: vdso: move vgettimeofday.c to lib/vdso/
b4407dc7b543 FROMLIST: [PATCH v5 08/12] arm: vdso: Add ARCH_CLOCK_FIXED_MASK
b2a6f20166fd FROMLIST: [PATCH v5 07/12] arm: vdso: disable profiling
bfb8862c0e28 FROMLIST: [PATCH v5 06/12] arm: vdso: add support for clock_getres
06e8d1c2c850 FROMLIST: [PATCH v6 05/12] arm: vdso: Add support for CLOCK_MONOTONIC_RAW
89652e75d286 FROMLIST: [PATCH v5 04/12] arm: vdso: do calculations outside reader loops
80261359ef46 FROMLIST: [PATCH v5 03/12] arm: vdso: inline assembler operations to compiler.h
5d7fcb248342 FROMLIST: [PATCH v5 02/12] arm: vdso: add include file defining __get_datapage()
69ae99e747dc FROMLIST: [PATCH v5 01/12] arm: vdso: rename vdso_datapage variables
02ab3e1a659f FROMLIST: [PATCH v2 3/3] arm64: compat: Add CONFIG_KUSER_HELPERS
19247fdf20f9 FROMLIST: [PATCH v2 2/3] arm64: compat: Split the sigreturn trampolines and kuser helpers (assembler sources)
06fb1dbcdd5e FROMLIST: [PATCH v2 1/3] arm64: compat: Split the sigreturn trampolines and kuser helpers (C sources)
90c8c5ab75e9 Revert "arm64, vdso: Define vdso_{start,end} as array"
c90a67b2f3f3 Makefile: O3 it up for host executables
90d3877221b3 Makefile: Use O3 for Clang
d8cb7ab17c6c Makefile: Slim down CONFIG_CC_OPTIMIZE_FOR_SIZE block
0cc52ff8002c qcacld-2.0: Disable spammy enum-conversion warnings
a22db74eac14 hwmon: qpnp-adc: Fix enum conversion warning
68c56ac4f979 crypto: msm: Increase frame-larger-than warning
fc3286ae914a usb_bam: Fix usb bam_type assignment during suspend
7842abb37675 ion: Fix typecasting of msm_ion_heap_types
7e66349a0078 ANDROID: Kbuild, LLVMLinux: disable clang -Wpointer-bool-conversion
931d657ec6c0 slimbus: Add braces around suspicious indent
85c790b499ab msm: ipa_v2: fix misleading indentation warning
81fe1d767b54 Revert "drivers: iio: imu: enabled bmi and iam sensor compilation"
058f168882af i2c-msm-v2: Remove duplicate const specifier
7c51b9b9c9ce ASoC: msm: qdsp6v2: Remove duplicate const specifier
2f6aa50b1ef3 esoc: Remove duplicate const specifier
034e62fe3aa5 msm: mdss: Remove duplicate const specifier
b2a5d7446f06 Revert "fix some warnigs"
e85b51d62ee2 Revert "Treewide: Fix constant pointer declaration"
166a29979dcb PM / core: Add support to skip power management in device/driver model
f51953927e34 PM / devfreq: Skip status update on uninitialized previous_freq
69b821baf5e8 irq: Silence IRQ CPU migration message
f06c97671dae Silences WLAN, PCIe, and CPU suspend state kernel messages
70130c0d0fd2 sched_clock: shut. up.
5a2621abb15e kernel: irq: silence irq debugging
04e65cfaf7f4 msm: vidc: Silence debugfs creation failure spam
e111b8499ef5 msm: vidc: kill opening/closing video instance logspam
91e70efe9575 soc: glink: Silence really annoying spam
e02698383a6a dsp: asm: improve misleading logs
ac6d2fb02fde Revert "q6asm: Remove payload size check"
97e972a17c71 cnss_pci: fix memory leak in pic resume path
6df94fbd508b msm: camera: sensor: Fix memory leaks when sensor probe fails
625bd5e7de28 msm: sps: Fix memory leaks in sps_register_bam_device
3141329478fe leds-qpnp-flash, qpnp-fg: Don't bail out when debugfs is disabled
6ab9d907124c soc: qcom: rpm_stats: Enable debugfs usage for libperfmgr
8329869fd259 wakeup: Enable debugfs usage for Android even when debugfs is disabled
e7bd2b108777 debugfs: Always compile core debugfs driver for Android kernels
a0d1ba48640f arm64: kernel: Don't build perf_debug.o when debugfs is disabled
94af6d56e636 msm: thermal: Fix compile errors when debugfs is disabled
ab473cd56e45 msm: mdss: Fix compile errors when debugfs is disabled
f8065bd41d22 scsi: ufs: Fix compile errors when debugfs is disabled
a6e299dfb6ba msm: sps: Fix compile errors when debugfs is disabled
67553ea40163 msm: ipa: Fix compile errors when debugfs is disabled
d815fcefe4af ASoC: msm: qdsp6v2: Fix compile errors when debugfs is disabled
497fba6c8a1e clk: msm: Fix compile errors when debugfs is disabled
6343fdee2c21 firmware: qcom: Remove debugfs dependency from tz-log driver
37736e60f4ae init: Kconfig: Don't force DEBUG_KERNEL when EXPERT is enabled
3fb9546fae50 crypto: Make CRYPTO_DEV_QCE depend on CRYPTO_DEV_QCRYPTO being disabled
bf72d1eb0cad net: ipc_router: fix memleak with IPC_LOGGING disabled
377cc4716d5b soc: qcom: Further fixes for !IPC_LOGGING for IPA, SMD, SMEM.
3f7292139807 tty: serial: Correct IPC_LOGGING ifdef
6956fcc9ccd0 tty: serial: msm_serial_hs: fix sysfs create
a0e994156d6d tty: serial: msm_serial_hs: fix ipclog spam
ff8fedec82aa soc: qcom: stop spam when IPC_LOGGING is disabled
5e9e0d0a7072 ASoC: msm: Don't force APQ8096 sound card driver to be used
01df7d40703b Kconfig: msm: disable ultrasound driver
abccb1a35e76 asoc/msm: Disable unwanted modules in arch config
5f62e8042290 drivers: clk: msm: fix PLL lock failure
f579214e77f8 ARM: dts: msm: Add new property to DSPS IPC router node for MSM8996
3b5e86c05d6c arm: DT: MSM8996: Add efficiency parameter to each SoC CPU
139c62dbd462 ARM: dts: msm: change crypto driver bus setting for msm8996
7404e25a9828 ARM: dts: msm: Specify the temperature sensor name for msm8996
e9f51feb2522 arm: DT: MSM8996: Add 511 as a reserved channel for SPMI Arbitrator
90c6a71438ea ARM: dts: msm: Update the face detect clock rates for msm8996
a7bf32e559e7 arm: DT: MSM8996: Declare a memory region for autoconfigured CMA
5176ffe1cc61 arm: msm8996: Disable MHI ipcrouter by default

====================
     10-18-2019
====================


   * kernel/xiaomi/msm-4.4/
fb3c5c193867 Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie
5128dacd7431 Merge 4.4.197 into kernel.lnx.4.4.r37-rel
04858540ca84 Linux 4.4.197
748edae843c3 xfs: clear sb->s_fs_info on mount failure
f9c94a02d4c5 x86/asm: Fix MWAITX C-state hint value
35fa86e42bf4 tracing: Get trace_array reference for available_tracers files
d1de6f689d82 media: stkwebcam: fix runtime PM after driver unbind
91fdb3cf4cf5 CIFS: Force revalidate inode when dentry is stale
4701063a62a6 cifs: Check uniqueid for SMB2+ and return -ESTALE if necessary
c712daafe23b Staging: fbtft: fix memory leak in fbtft_framebuffer_alloc
bf0313653f03 arm64: Rename cpuid_feature field extract routines
8eba41684829 arm64: capabilities: Handle sign of the feature bit
db02f78d9609 kernel/sysctl.c: do not override max_threads provided by userspace
9dc8594cd7b7 CIFS: Force reval dentry if LOOKUP_REVAL flag is set
3ca705b89bb4 CIFS: Gracefully handle QueryInfo errors during open
6d4d8a07ba56 perf llvm: Don't access out-of-scope array
07bc13c09be6 iio: light: opt3001: fix mutex unlock race
2a736f3547c6 iio: adc: ad799x: fix probe error handling
cab8f7da72a9 staging: vt6655: Fix memory leak in vt6655_probe
a9640a94bb6f USB: legousbtower: fix use-after-free on release
72ff2f621462 USB: legousbtower: fix open after failed reset request
28f2c9460ea5 USB: legousbtower: fix potential NULL-deref on disconnect
2e0bcd20f6c7 USB: legousbtower: fix deadlock on disconnect
ce29fc8d8297 USB: legousbtower: fix slab info leak at probe
d6952c7b39b2 usb: renesas_usbhs: gadget: Fix usb_ep_set_{halt,wedge}() behavior
6207b7b8f096 usb: renesas_usbhs: gadget: Do not discard queues in usb_ep_set_{halt,wedge}()
0d86daeb0016 USB: dummy-hcd: fix power budget for SuperSpeed mode
c841eeea7497 USB: microtek: fix info-leak at probe
78b2e65cb55f USB: usblcd: fix I/O after disconnect
3ec2dabc9e44 USB: serial: fix runtime PM after driver unbind
22727bde284b USB: serial: option: add support for Cinterion CLS8 devices
2b08f6ffd9d8 USB: serial: option: add Telit FN980 compositions
35526e63dcae USB: serial: ftdi_sio: add device IDs for Sienna and Echelon PL-20
883457a6af8d USB: serial: keyspan: fix NULL-derefs on open() and write()
858841b7cb12 serial: uartlite: fix exit path null pointer
107ef3bb5e74 USB: ldusb: fix NULL-derefs on driver unbind
ebfb3be3b0af USB: chaoskey: fix use-after-free on release
8f7520133878 USB: usblp: fix runtime PM after driver unbind
ac7266d990f7 USB: iowarrior: fix use-after-free after driver unbind
ded3c707e373 USB: iowarrior: fix use-after-free on release
f723d7ea08e2 USB: iowarrior: fix use-after-free on disconnect
f14fed62a96b USB: adutux: fix use-after-free on release
ffb59e0701a9 USB: adutux: fix NULL-derefs on disconnect
cd3cfbafe8eb USB: adutux: fix use-after-free on disconnect
d5b8fadb2a05 USB: adutux: remove redundant variable minor
557b03eb4491 xhci: Increase STS_SAVE timeout in xhci_suspend()
384f906e724c usb: xhci: wait for CNR controller not ready bit in xhci resume
0cd0bbdad9a4 xhci: Check all endpoints for LPM timeout
8af575b89e49 xhci: Prevent device initiated U1/U2 link pm if exit latency is too long
f88d1294ee78 USB: usb-skeleton: fix NULL-deref on disconnect
d3488daeaa27 USB: usb-skeleton: fix runtime PM after driver unbind
591e060b72f4 USB: yurex: fix NULL-derefs on disconnect
d777eecf20bd USB: yurex: Don't retry on unexpected errors
b5583d6963d0 USB: rio500: Remove Rio 500 kernel driver
43b7a9d0d62a panic: ensure preemption is disabled during panic()
82ea9d14f753 ASoC: sgtl5000: Improve VAG power and mute control
fd27e0779cf6 nl80211: validate beacon head
a698649b8e32 cfg80211: Use const more consistently in for_each_element macros
933f4f10c928 cfg80211: add and use strongly typed element iteration macros
a3cda6a02043 crypto: caam - fix concurrency issue in givencrypt descriptor
0f714ca2b3f3 perf stat: Fix a segmentation fault when using repeat forever
bacdf1ea1671 tools lib traceevent: Do not free tep->cmdlines in add_new_comm() on failure
65514877299b kernel/elfcore.c: include proper prototypes
d082c610bce7 fuse: fix memleak in cuse_channel_open
b30c56ee03b6 thermal: Fix use-after-free when unregistering thermal zone device
e4165f2d4a4e drm/amdgpu: Check for valid number of registers to read
78ba94e80f84 ceph: fix directories inode i_blkbits initialization
6390b01bb706 xen/pci: reserve MCFG areas earlier
06453e2abdd2 9p: avoid attaching writeback_fid on mmap with type PRIVATE
5deaece94aa9 fs: nfs: Fix possible null-pointer dereferences in encode_attrs()
b1b8f7b23a28 ima: always return negative code for error
ef1bcee5e92e cfg80211: initialize on-stack chandefs
1fb673245b24 ieee802154: atusb: fix use-after-free at disconnect
448ad4ac56f8 crypto: qat - Silence smp_processor_id() warning
62db62a43134 can: mcp251x: mcp251x_hw_reset(): allow more time after a reset
cc5d103da444 powerpc/powernv: Restrict OPAL symbol map to only be readable by root
d4a8a6d767ce ASoC: Define a set of DAPM pre/post-up events
59b3647b86fc KVM: nVMX: handle page fault in vmread fix
a179b845b982 s390/cio: exclude subchannels with no parent from pseudo check
ea947b87349e s390/cio: avoid calling strlen on null pointer
399b4e062f76 s390/topology: avoid firing events before kobjs are created
126ed52d7cea KVM: s390: Test for bad access register and size at the start of S390_MEM_OP

====================
     10-17-2019
====================


   * kernel/xiaomi/msm-4.4/
afc91a11c3d2 Merge tag 'LA.UM.7.5.2.r1-03700-8x96.0' into kernel.lnx.4.4.r37-rel

====================
     10-16-2019
====================


====================
     10-15-2019
====================


====================
     10-14-2019
====================


   * device/xiaomi/gemini/
7d11f9983 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/device/qcom/common into HEAD
1fe195bc6 Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/device/common into HEAD

   * hardware/qcom/audio-caf/msm8996/
8094d5ef correct audio features for gemini

   * hardware/qcom/media-caf/msm8998/
489859014 Merge tag 'LA.UM.7.4.r1-05700-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD

   * kernel/xiaomi/msm8996/
45d41f42d4f8 Bluetooth: Fix regression with minimum encryption key size alignment
9808efed03ea skge: fix checksum byte order
6080d7be9127 sch_netem: fix a divide by zero in tabledist()
5120f1a0aa51 openvswitch: change type of UPCALL_PID attribute to NLA_UNSPEC
a8a805103e99 net/phy: fix DP83865 10 Mbps HDX loopback disable function
bfc754d46523 cdc_ncm: fix divide-by-zero caused by invalid wMaxPacketSize
e74760286bb5 ASoC: fsl: Fix of-node refcount unbalance in fsl_ssi_probe_from_dt()
e7e48dbd81fe mtd: cfi_cmdset_0002: Use chip_good() to retry in do_write_oneword()
eac82785e60f HID: hidraw: Fix invalid read in hidraw_ioctl
bd091567fc8b HID: lg: make transfer buffers DMA capable
b00700543eb8 HID: prodikeys: Fix general protection fault during probe
7826c0499717 media: technisat-usb2: break out of loop at end of buffer
b804f7682fb0 mwifiex: Fix three heap overflow at parsing element in cfg80211_ap_settings
1e076858b0bd KVM: coalesced_mmio: add bounds checking
c79477dac963 media: tm6000: double free if usb disconnect while streaming
b6512600afac crypto: talitos - check data blocksize in ablkcipher.
3bfc73a8870c crypto: talitos - check AES key size
8b0ded0609e2 genirq: Prevent NULL pointer dereference in resend_irqs()
42e2ceead5ff tun: fix use-after-free when register netdev failed
c76bd47f8a4a tcp: fix tcp_ecn_withdraw_cwr() to clear TCP_ECN_QUEUE_CWR
ed260d244cd0 sctp: Fix the link time qualifier of 'sctp_ctrlsock_exit()'
991af43ea325 sch_hhf: ensure quantum and hhf_non_hh_weight are non-zero
607c1d711971 net: Fix null de-reference of device refcount
22d5557ce264 isdn/capi: check message length in capi_write()
c74ed225324a ipv6: Fix the link time qualifier of 'ping_v6_proc_exit_net()'
0040f23bb049 net_sched: let qdisc_put() accept NULL pointer
fada34a3a9cc vhost: make sure log_num < in_num
87eab9883343 xfrm: clean up xfrm protocol checks
057c93598fb2 ALSA: hda - Fix potential endless loop at applying quirks
b5dedf3ba3fc ovl: filter of trusted xattr results in audit
f2e560ab9e13 NFC: fix attrs checks in netlink interface
60d9016d7bdc Smack: Don't ignore other bprm->unsafe flags if LSM_UNSAFE_PTRACE is set
6b00756e3db3 sch_cbq: validate TCA_CBQ_WRROPT to avoid crash
344f22a7d70f net/rds: Fix error handling in rds_ib_add_one()
99b6f7c840c7 sch_dsmark: fix potential NULL deref in dsmark_init()
848792540504 nfc: fix memory leak in llcp_sock_bind()
758a02e91b32 net: qlogic: Fix memory leak in ql_alloc_large_buffers
7459e8dcc06f net: ipv4: avoid mixed n_redirects and rate_tokens usage
70af816b2aa7 ipv6: drop incoming packets having a v4mapped source address
8fea9ec0156b hso: fix NULL-deref on tty open
62d21821bb96 msm: kgsl: Make the "scratch" global buffer use a random GPU address
0b4b79344b35 msm: kgsl: Use a bitmap allocator for global addressing
d33d8c6f92b2 defconfig: msm: Disable EXT2 and EXT3 FS configs for MSM8937/53
310033e9c202 msm: kgsl: Change data type for GPU ib vote
db6ea37dca6f icnss: Add check on msa region

   * vendor/havoc/
97625f53 update Lawnchair to alpha-2500

   * vendor/xiaomi/
46065230 drop land
40cca111 msm8996-common: Update hvdcp_opti from LA.UM.7.5.r1-05300-8x96.0

====================
     10-13-2019
====================


   * hardware/interfaces/
e48a12518 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

   * hardware/qcom/audio-caf/msm8996/
4997af15 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/media-caf/msm8998/
2ccf5291f Merge tag 'LA.UM.7.2.r2-02600-8x98.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD

   * kernel/xiaomi/msm-4.4/
f147b1ac2e0e Merge branch 'kernel.lnx.4.4.r37-rel' of https://github.com/android-linux-stable/msm-4.4 into pie

   * kernel/xiaomi/msm8996/
200cef711098 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' into drivers/staging/qcacld-2.0

   * vendor/qcom/opensource/audio/
cd76f92 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/interfaces/
6daae03 Merge tag 'LA.UM.7.6.r1-06400-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     10-12-2019
====================


====================
     10-11-2019
====================


====================
     10-10-2019
====================


   * hardware/qcom/media-caf/msm8996/
6573821c media: Don't link libgpustats
eadb4951 media: Add extrapolated gpustats header for PQ
37ca2142 media: libOmxSw encoders require prop headers :(
abdaa6ba venc: Fix VQZip issue
26f4dc5a media: Use    * pathmap

====================
     10-09-2019
====================


   * frameworks/av/
0e48c9ceeb Merge tag 'android-9.0.0_r49' of https://android.googlesource.com/platform/frameworks/av into HEAD

====================
     10-08-2019
====================


   * kernel/xiaomi/msm-4.4/
65ee150f4c32 Merge 4.4.196 into kernel.lnx.4.4.r37-rel
c61ebb668f2c Linux 4.4.196
2e486758901d NFC: fix attrs checks in netlink interface
ac375073bb39 smack: use GFP_NOFS while holding inode_smack::smk_lock
cfaf71c99319 Smack: Don't ignore other bprm->unsafe flags if LSM_UNSAFE_PTRACE is set
3aa452bf9baa sch_cbq: validate TCA_CBQ_WRROPT to avoid crash
fc9752bceab7 net/rds: Fix error handling in rds_ib_add_one()
ac37c4e04728 xen-netfront: do not use ~0U as error return value for xennet_fill_frags()
f411ce016913 sch_dsmark: fix potential NULL deref in dsmark_init()
031183e85d5f nfc: fix memory leak in llcp_sock_bind()
a35f1bb8c300 net: qlogic: Fix memory leak in ql_alloc_large_buffers
7b1341b8e511 net: ipv4: avoid mixed n_redirects and rate_tokens usage
31849614f85e ipv6: drop incoming packets having a v4mapped source address
8e3dadbf40d6 hso: fix NULL-deref on tty open
fcf46dcedbc4 ANDROID: binder: synchronize_rcu() when using POLLFREE.
80eb98a4ee70 ANDROID: binder: remove waitqueue when thread exits.
9add3e08a8fd kmemleak: increase DEBUG_KMEMLEAK_EARLY_LOG_SIZE default to 16K
68fb386f396a ocfs2: wait for recovering done after direct unlock request
fe276165b081 hypfs: Fix error number left in struct pointer member
5ba8ad0cc3a4 fat: work around race with userspace's read via blockdev while mounting
2c84c48466b9 security: smack: Fix possible null-pointer dereferences in smack_socket_sock_rcv_skb()
9b3458c19b1a HID: apple: Fix stuck function keys when using FN
29f62e3db89f ARM: 8898/1: mm: Don't treat faults reported from cache maintenance as writes
59610f8b04ef mfd: intel-lpss: Remove D3cold delay
764029c0aaa6 scsi: core: Reduce memory required for SCSI logging
e0fe918193a2 powerpc/pseries: correctly track irq state in default idle
90666ada1a81 powerpc/64s/exception: machine check use correct cfar for late handler
95fed5c9b1ce vfio_pci: Restore original state on release
4e197fe04060 pinctrl: tegra: Fix write barrier placement in pmx_writel
a7a59733e741 powerpc/pseries/mobility: use cond_resched when updating device tree
45dc36ca54ea powerpc/futex: Fix warning: 'oldval' may be used uninitialized in this function
f8e62b01bb98 powerpc/rtas: use device model APIs and serialization during LPM
dde75090314d clk: sirf: Don't reference clk_init_data after registration
41a943ca1fb4 clk: qoriq: Fix -Wunused-const-variable
d9e87b4415c7 ipmi_si: Only schedule continuously in the thread in maintenance mode
3c803c155292 gpu: drm: radeon: Fix a possible null-pointer dereference in radeon_connector_set_property()
512013196156 video: ssd1307fb: Start page range at page_offset

====================
     10-07-2019
====================


   * device/xiaomi/gemini/
76027807d msm8996-common: configs: Remove 2 instance support for "primary input"
5b124957e msm8996-common: Enable clearkey drm plugin v1.2

====================
     10-06-2019
====================


   * build/make/
d7e8a3d4c update gcc to 9.2

   * build/soong/
326e8dfe update gcc to 9.2

   * kernel/xiaomi/msm-4.4/
626712489318 capricorn: try to debug this sh*t
6ba8708e14e4 Merge branch 'upstream-linux-4.4.y' of https://android.googlesource.com/kernel/common into HEAD
b2d13ba5164c Merge 4.4.195 into kernel.lnx.4.4.r37-rel

====================
     10-05-2019
====================


   * hardware/qcom/media-caf/msm8998/
f2b45b2bc Merge 321949846222a4726f0ea90ff115fb9c5c5a0bc8 on remote branch

   * kernel/xiaomi/msm-4.4/
5164f0c3740d Linux 4.4.195
ec9a11a0b2f8 Btrfs: fix race setting up and completing qgroup rescan workers
87bd41e20d9f btrfs: Relinquish CPUs in btrfs_compare_trees
2cd8f741aa12 Btrfs: fix use-after-free when using the tree modification log
05f4bc30f5a0 ovl: filter of trusted xattr results in audit
0d9cc53fde52 CIFS: Fix oplock handling for SMB 2.1+ protocols
ba8d9cdbe5a2 i2c: riic: Clear NACK in tend isr
c648d4350015 hwrng: core - don't wait on add_early_randomness()
70a2b17f151e quota: fix wrong condition in is_quota_modification()
39950e657d5e ext4: fix punch hole for inline_data file systems
4e9518d21cf0 /dev/mem: Bail out upon SIGKILL.
b85938f66b6e cfg80211: Purge frame registrations on iftype change
c7925cc21fb2 md/raid6: Set R5_ReadError when there is read failure on parity disk
c22df8ea7c58 alarmtimer: Use EOPNOTSUPP instead of ENOTSUPP
8b49a407ce25 ARM: zynq: Use memcpy_toio instead of memcpy on smp bring-up
789536b7f014 ASoC: Intel: Fix use of potentially uninitialized variable
16740be2f6b5 media: sn9c20x: Add MSI MS-1039 laptop to flip_dmi_table
10ec9d66ff15 KVM: x86: Manually calculate reserved bits when loading PDPTRS
bcb66cfc3fcf KVM: x86: set ctxt->have_exception in x86_decode_insn()
5de105cc60f8 KVM: x86: always stop emulation on page fault
f5c0d4a616cf parisc: Disable HP HSC-PCI Cards to prevent kernel crash
d9768d068b4e fuse: fix missing unlock_page in fuse_writepage()
291697f621a0 printk: Do not lose last line in kmsg buffer dump
82a136986dbc ALSA: firewire-tascam: check intermediate state of clock status and retry
02842b98ab1e ALSA: firewire-tascam: handle error code when getting current source of clock
e875c35b74ac media: omap3isp: Set device on omap3isp subdevs
6454910f3171 btrfs: extent-tree: Make sure we only allocate extents from block groups with the same type
22404e0663c9 ALSA: hda/realtek - Blacklist PC beep for Lenovo ThinkCentre M73/93
b54d1e51bba7 media: ttusb-dec: Fix info-leak in ttusb_dec_send_command()
a580cba06adc libertas: Add missing sentinel at end of if_usb.c fw_table
16b6055dcbc2 mmc: sdhci: Fix incorrect switch to HS mode
e328a6282d42 ASoC: dmaengine: Make the pcm->name equal to pcm->id if the name is not set
c0505afc8a8e kprobes: Prohibit probing on BUG() and WARN() address
77a4084872bb dmaengine: ti: edma: Do not reset reserved paRAM slots
b8c11e01be7f md/raid1: fail run raid1 array when active disk less than one
a8d1f3f88922 hwmon: (acpi_power_meter) Change log level for 'unsafe software power cap'
4bda2b79a9d0 ACPI: custom_method: fix memory leaks
bf3afb03d4d5 libtraceevent: Change users plugin directory
318e486d4ed9 ACPI / CPPC: do not require the _PSD method
7ff7d1e7a749 media: ov9650: add a sanity check
9dfd33530c94 media: saa7134: fix terminology around saa7134_i2c_eeprom_md7134_gate()
a9df2fd8e064 media: cpia2_usb: fix memory leaks
70e2968f3bf2 media: saa7146: add cleanup in hexium_attach()
11b1a42a99d3 media: hdpvr: add terminating 0 at end of string
4678cdb0851c media: radio/si470x: kill urb on error
0fc9c24adca9 net: lpc-enet: fix printk format strings
f39c1742f807 media: omap3isp: Don't set streaming state on random subdevs
89052e706600 dmaengine: iop-adma: use correct printk format strings
3553e7fb0b9c media: gspca: zero usb_buf on error
f39d3370a3e4 efi: cper: print AER info of PCIe fatal error
6b544c54638b md: don't set In_sync if array is frozen
6809adb82cea md: don't call spare_active in md_reap_sync_thread if all member devices can't work
41330a743f73 ia64:unwind: fix double free for mod->arch.init_unw_table
9812dc6f0db6 ALSA: usb-audio: Skip bSynchAddress endpoint check if it is invalid
fe120e1253bc base: soc: Export soc_device_register/unregister APIs
a8d7151b7f3a media: iguanair: add sanity checks
9916480fc2b6 ALSA: i2c: ak4xxx-adda: Fix a possible null pointer dereference in build_adc_controls()
c5f680b2ca2c ALSA: hda - Show the fatal CORB/RIRB error more clearly
3b6cccf414ac x86/apic: Soft disable APIC before initializing it
03b8c7430457 x86/reboot: Always use NMI fallback when shutdown via reboot vector IPI fails
5043f2cf144a sched/core: Fix CPU controller for !RT_GROUP_SCHED
5da394bd2dc1 sched/fair: Fix imbalance due to CPU affinity
84a6dd572b18 media: hdpvr: Add device num check and handling
78335bc692d7 media: dib0700: fix link error for dibx000_i2c_set_speed
28b772b68901 leds: leds-lp5562 allow firmware files up to the maximum length
2989ee3412b7 dmaengine: bcm2835: Print error in case setting DMA mask fails
ae6be6302e18 ASoC: sgtl5000: Fix charge pump source assignment
f49a9f57ed39 ALSA: hda: Flush interrupts on disabling
001ff467264f nfc: enforce CAP_NET_RAW for raw sockets
a279cd311c1e ieee802154: enforce CAP_NET_RAW for raw sockets
c15d89b5cb86 ax25: enforce CAP_NET_RAW for raw sockets
ec1e04b89794 appletalk: enforce CAP_NET_RAW for raw sockets
a03818269bfb mISDN: enforce CAP_NET_RAW for raw sockets
a4d63b410231 usbnet: sanity checking of packet sizes and device mtu
608557096364 usbnet: ignore endpoints with invalid wMaxPacketSize
2a7604cde62b skge: fix checksum byte order
9601d33226ba sch_netem: fix a divide by zero in tabledist()
4c8afdc16e45 openvswitch: change type of UPCALL_PID attribute to NLA_UNSPEC
cecefdab590b net/phy: fix DP83865 10 Mbps HDX loopback disable function
b5f703829cf6 cdc_ncm: fix divide-by-zero caused by invalid wMaxPacketSize
d7065a5e68ef arcnet: provide a buffer big enough to actually receive packets
e76fb5f7e8b9 Bluetooth: btrtl: Additional Realtek 8822CE Bluetooth devices
736a524bf6ef drm: Flush output polling on shutdown
c9aac2ca3403 f2fs: fix to do sanity check on segment bitmap of LFS curseg
810394b3917f Revert "f2fs: avoid out-of-range memory access"
bf0b3b4b81c2 f2fs: check all the data segments against all node ones
ba118859b4bc irqchip/gic-v3-its: Fix LPI release for Multi-MSI devices
2a8d47d551f3 locking/lockdep: Add debug_locks check in __lock_downgrade()
3fea925a915a mac80211: handle deauthentication/disassociation from TDLS peer
943341211598 mac80211: Print text for disassociation reason
7703936b97b6 ALSA: hda - Add laptop imic fixup for ASUS M9V laptop
e68c9b0f48b6 ASoC: fsl: Fix of-node refcount unbalance in fsl_ssi_probe_from_dt()
91573ae4aed0 net: rds: Fix NULL ptr use in rds_tcp_kill_sock
b19b5a895ad3 crypto: talitos - fix missing break in switch statement
9ce51a5b414a mtd: cfi_cmdset_0002: Use chip_good() to retry in do_write_oneword()
0bbb24a30e1a HID: hidraw: Fix invalid read in hidraw_ioctl
ffc62dc252e1 HID: logitech: Fix general protection fault caused by Logitech driver
30d86e698c28 HID: lg: make transfer buffers DMA capable
c03d9a82384c HID: prodikeys: Fix general protection fault during probe
4f1af2bcab13 Revert "Bluetooth: validate BLE connection interval updates"

====================
     10-04-2019
====================


   * hardware/interfaces/
410cad195 Merge 063247cc2a3cbd90f52bf1de191bad17d6a3d961 on remote branch
f7d2262e1 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

   * hardware/qcom/audio-caf/msm8996/
de34d823 Merge 6b015e0b353fedf409a5c5ecf51582308341e462 on remote branch
17c900ad Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/media-caf/msm8998/
919063e04 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into HEAD
c6656a5c0 Merge c89450b6a36d1a73bd97843d73e5656294a09858 on remote branch

   * kernel/xiaomi/msm8996/
5154ab91138d Merge 442f13d9530d094814d5d6626149e19b8eae331e on remote branch

   * vendor/qcom/opensource/audio/
ccf33dc Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
e3e4246 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
6ae63b5 Merge b8e4183b95aa72ad25ff2bdd1890cf73003f0030 on remote branch
f45d900 Merge tag 'LA.UM.7.6.2.r1-10100-89xx.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     10-03-2019
====================


   * device/xiaomi/gemini/
4a6581204 msm8996-common: bluetooth: Push×pop PROPERTY_VALUE_MAX in buildcfg header
a448126a9 msm8996-common: Append 'Xiaomi' to BT name
b36bb3477 merge bdroid_buildcfg.h
92f2cc732 change HAVOC_BUILD_TYPE logic
5dc0221d3 drop wcnss_filter sepolicy rules

   * kernel/xiaomi/msm8996/
a095cd303834 Merge tag 'LA.UM.7.6.r1-05900-89xx.0' of https://source.codeaurora.org/quic/la/kernel/msm-3.18 into 9.0

====================
     10-02-2019
====================


====================
     10-01-2019
====================


   * hardware/interfaces/
0564c3370 Merge 063247cc2a3cbd90f52bf1de191bad17d6a3d961 on remote branch

   * hardware/qcom/audio-caf/msm8996/
6b015e0b Merge "A2dp: Send default channel mapping for TWS+ mono." into audio-hal.lnx.5.0
637433f5 Merge "hal: Unload modem wrt peripheral manager update" into audio-hal.lnx.5.0
052dba06 Merge d033707810af0d64b1df7c9e8684ea6209783d32 on remote branch

   * hardware/qcom/media-caf/msm8998/
0273e0eaf Merge c89450b6a36d1a73bd97843d73e5656294a09858 on remote branch

   * vendor/qcom/opensource/interfaces/
fbd0516 Merge b8e4183b95aa72ad25ff2bdd1890cf73003f0030 on remote branch

====================
     09-30-2019
====================


====================
     09-29-2019
====================


====================
     09-28-2019
====================


