====================
     04-08-2019
====================


   * frameworks/base/
1424e0e13582 Revert "hwui: Enable quicksilver"
70330c89b194 Automatic translation import
46aaa4168556 SystemUI: fix no service and emergency calls only placement
4c14c6f1016f qs_footer: Update visibilities after inflate finish
8b38a1048d90 base: Add OnePlus Red accent [1/3]
30e596483e77 base: Add Black Pearl theme [1/3]

   * packages/apps/HavocSettings/
58fb26e Fix Russian translation
e3ed420 Automatic translation import
63015e7 Settings: Add Black Pearl theme [2/3]

   * packages/apps/Settings/
9615074f51 Fix Russian translation
c833e2eec7 Automatic translation import
2186612247 Settings: Add OnePlus Red accent [2/3]
da95f0c35d Settings: Add deep sleep info to uptime
5f329cd65d Settings: Move 'About phone' to the bottom

   * vendor/themes/
3e7f1f8 themes: Add OnePlus Red accent [3/3]
68858eb themes: Add Black Pearl theme [3/3]

====================
     04-07-2019
====================


   * frameworks/base/
0f6516d6d660 Custom logo customizations [1/2]

   * packages/apps/Contacts/
313a6aeb4 Automatic translation import

   * packages/apps/CustomDoze/
536b56c Automatic translation import

   * packages/apps/Dialer/
f35a412fc Automatic translation import

   * packages/apps/Dirac/
a92626d Automatic translation import

   * packages/apps/HavocSettings/
2eaba71 Settings: Add our discord server
52e28fe Custom logo customizations [2/2]

   * packages/apps/Messaging/
0455206 Automatic translation import

   * packages/apps/OmniStyle/
b642673 Automatic translation import

   * packages/apps/PackageInstaller/
54695789 Automatic translation import

   * packages/apps/SmartNav/
3646b96 Automatic translation import

   * packages/apps/SmartNavSettings/
6a19fde Automatic translation import

   * packages/providers/DownloadProvider/
48883b2 Automatic translation import

   * packages/providers/MediaProvider/
acde028 Automatic translation import

   * vendor/huawei/kiwi/
ee14d41 kiwi: Add build rule for libidl and libqmi_cci
acbd890 kiwi: Add build rule for libmdmdetect

====================
     04-06-2019
====================


   * frameworks/base/
1b3f820fa7a6 Use alphaoptimized layout for custom icons on left

   * packages/apps/HavocSettings/
6534670 Slim recents old enter/exit animation [3/3]

====================
     04-05-2019
====================


   * device/qcom/sepolicy-legacy/
96f30d3 sepolicy: Label persist partition for all SoCs

   * external/exfat/
e346c7c exfat: Rename utf conversion symbols
9e9dc69 exfat: Add static libs for recovery

   * external/f2fs-tools/
5442202 f2fs-tools: Add sload.f2fs support to libf2fs_fsck
6e67812 f2fs-tools: Rename utf conversion symbols
d445c41 f2fs-tools: Rename quota symbols
20e8f06 f2fs-tools: Add static libs for recovery

   * frameworks/base/
aeaa4570a2b6 Slim recents old enter/exit animation [1/3]
1d9d566eb246 base: LS filters: Add 2 more variants

   * frameworks/opt/slimrecent/
42bbeeb Slim recents old enter/exit animation [2/3]

   * packages/apps/HavocSettings/
a38bd6c Fix J7 prime codename

   * system/core/
8a93a8f9e Revert "sdcard: Allow building as a static library"
b994bc437 fs_mgr: Skip filesystem check unless fs_type matches
f49bc4c1d Revert "fs_mgr_fstab: removing fs_mgr_get_entry_for_mount_point_after()"
5aa1b1606 Fix path for treble default prop

   * system/vold/
97e1b94 vold: Add linkage for fs_mgr changes

   * vendor/huawei/kiwi/
881bb8e kiwi: Remove 32bit bt blobs
4068ca5 kiwi: Add build rule for QPerformance jar
037c15e kiwi: Clean up kiwi-vendor.mk
2f90567 kiwi: Add ANT, aptX, BT & FM blobs from Huawei Nova 2 Lite
d525615 kiwi: Refresh makefiles

====================
     04-04-2019
====================


   * frameworks/base/
2408cfa7d3ef base: Optimize toGrayscale function
5640564aa1a0 base: Intensify the blur amount on LS cover art
1f0748607e8b base: Fix old mobile signal icons
4355645372b4 Add wakelock option for flashlight
ea44fa0a9bf1 Fix screen pinning unlock with hwkeys
e193ec510060 Allow screen unpinning on devices without navbar

   * packages/apps/HavocSettings/
6a1f429 Settings: LS filters: Add 2 more variants

====================
     04-03-2019
====================


   * frameworks/base/
2fd3c37f9d2a core: Implement Aggressive Battery [1/2]
2d3e72f6fd8c Smart Pixels: Update default grid pattern
4ff0ccb6fd56 Smart Pixels: Bypass check for obscured window
6ece3a62a2ed Smart Pixels: Dynamically register receiver
df3742a3fe0a EdgeGestures: fix unregistering input filter
3725afa30494 ImageUtils: Switch blur lib to SimpleImageBlur

   * packages/apps/HavocSettings/
19da1d7 Settings: Implement Aggressive Battery [2/2]
8be2d6f Settings: Fix typos

   * prebuilts/clang/host/linux-x86/
61537703 Update prebuilt Clang to r353983b.

====================
     04-02-2019
====================


   * external/vixl/
33132247 libvixl: Disable use of dex2oat pgo profile [1/2]

   * frameworks/base/
bac951595126 Merge tag 'android-9.0.0_r35' into pie
4a127c6ce48f GamingModeTile: stop adjusting volume

   * packages/apps/Bluetooth/
9cee3b33 Merge tag 'android-9.0.0_r35' into pie

   * packages/apps/Browser/
6cf19b0 Browser: Update assets to use outline style
ac48339 Browser: Increase content padding for search bar
09e187b Browser: Use round search bar
ad897aa Browser: Use Pixel blue accent
c271bf4 Browser: QuickTiles for Favorites, Incognito, and New Tabs
6807d03 Browser: QuickTiles for Favorites, Incognito, and New Tabs
309478e Browser: Add save form data setting
4de469a Browser: Add Adblocker capabilities
788eecd Browser: Let the system know we're changing bar colors
c9fe68d Browser: Add a setting to set incognito defaults
cceb503 Browser: Don't save form data in incognito mode
9e981e7 Browser: Begin rebase onto newer Jelly

   * system/bt/
1128e8c70 Merge tag 'android-9.0.0_r35' into pie

   * system/netd/
a5767e1 Merge tag 'android-9.0.0_r35' into pie

====================
     04-01-2019
====================


   * external/google/
39d0cdb SmartNav: Fix NPE when navbar is not set to stock mode
5d47a24 elmyra: Adapt to smartnav changes
f3917f0 Init Havoc...

   * frameworks/base/
5e994a3c4a8c LTE tile: Remove oreo style slashes
24005c2812a8 base: Add Lockscreen cover art filter [1/2]
77368697353c ImageHelper: add getBlurredImage
4bfb71245d11 Dreamliner: Disable DockObserver conditionally
dc5a685b6eb9 Dreamliner: Reorganise the external repo [2/2]
077ba49cf291 ActionUtils: Reverse actions for QS and notification panel
5354d7ae854d Active Edge: allow to choose a specific app activity [4/4]
05ad0b3835d7 Introduce long squeeze action [3/3]

   * frameworks/opt/slimrecent/
e282441 Slimrecents: catch IllegalArgumentException too

   * packages/apps/HavocSettings/
e79ac79 Settings: Add Lockscreen cover art filter [2/2]
1264f64 Fallback to "no action" when an application gets removed [2/2]
3c939ca Active Edge: allow to choose a specific app activity [3/4]
74a291a Introduce long squeeze action [2/3]

   * system/core/
db08c342f Filter out QTI performance spam
0f5db3580 Shut up camera and wcnss debug output
e0aa9113a Filter GalleryDatab*

   * system/vold/
f7bdc95 increase timeout for waiting on block device

   * vendor/support/
66b4a13 Fix displaying units for CustomSeekBarPreference
a1166d1 App Picker: Add back press override
261216d Active Edge: allow to choose a specific app activity [2/4]

====================
     03-31-2019
====================


   * external/toybox/
7d5cb84f toybox: Use toybox for dd, getprop and grep in recovery
fd4a589c Revert "Reland: Stop building getprop"
fd080612 toybox: Add install to symlinks

   * kernel/huawei/kiwi/
c3917bf4ac0 kiwi: defconfig: Set CONFIG_USB_MSM_OTG flag

====================
     03-30-2019
====================


