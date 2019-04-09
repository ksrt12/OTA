====================
     2019-04-09    
====================

 * packages/apps/HavocSettings
58fb26e  Fix Russian translation  [VisualDrug]

 * packages/apps/Settings
ef8c395  Havoc Build Date [2/2]  [Kazakov Stepan]
9360e8b  DeviceInfoSettings: Bring back CAF/AOSP tags  [Harsh Shandilya]
63690d9  my colors  [Kazakov Stepan]
9615074  Fix Russian translation  [VisualDrug]

 * system/core
6355546  Allow adb root even in no debuggable builds  [Nathan Chancellor]

====================
     2019-04-08    
====================

 * frameworks/base
1424e0e  Revert "hwui: Enable quicksilver"  [SKULSHADY]
70330c8  Automatic translation import  [SKULSHADY]
46aaa41  SystemUI: fix no service and emergency calls only placement  [Nick Filmer]
4c14c6f  qs_footer: Update visibilities after inflate finish  [Kshitij Gupta]
8b38a10  base: Add OnePlus Red accent [1/3]  [Anushek Prasal]
30e5964  base: Add Black Pearl theme [1/3]  [Anushek Prasal]
0f6516d  Custom logo customizations [1/2]  [Pranav Vashi]

 * packages/apps/Contacts
313a6ae  Automatic translation import  [SKULSHADY]

 * packages/apps/CustomDoze
536b56c  Automatic translation import  [SKULSHADY]

 * packages/apps/Dialer
f35a412  Automatic translation import  [SKULSHADY]

 * packages/apps/Dirac
a92626d  Automatic translation import  [SKULSHADY]

 * packages/apps/HavocSettings
e3ed420  Automatic translation import  [SKULSHADY]
63015e7  Settings: Add Black Pearl theme [2/3]  [Anushek Prasal]
2eaba71  Settings: Add our discord server  [Anushek Prasal]
52e28fe  Custom logo customizations [2/2]  [neobuddy89]

 * packages/apps/Messaging
0455206  Automatic translation import  [SKULSHADY]

 * packages/apps/OmniStyle
b642673  Automatic translation import  [SKULSHADY]

 * packages/apps/PackageInstaller
5469578  Automatic translation import  [SKULSHADY]

 * packages/apps/Settings
c833e2e  Automatic translation import  [SKULSHADY]
2186612  Settings: Add OnePlus Red accent [2/3]  [Anushek Prasal]
da95f0c  Settings: Add deep sleep info to uptime  [Stefan Berger]
5f329cd  Settings: Move 'About phone' to the bottom  [SuperDroidBond]

 * packages/apps/SmartNav
3646b96  Automatic translation import  [SKULSHADY]

 * packages/apps/SmartNavSettings
6a19fde  Automatic translation import  [SKULSHADY]

 * packages/providers/DownloadProvider
48883b2  Automatic translation import  [SKULSHADY]

 * packages/providers/MediaProvider
acde028  Automatic translation import  [SKULSHADY]

 * vendor/huawei/kiwi
ee14d41  kiwi: Add build rule for libidl and libqmi_cci  [Adithya R]

 * vendor/themes
3e7f1f8  themes: Add OnePlus Red accent [3/3]  [Anushek Prasal]
68858eb  themes: Add Black Pearl theme [3/3]  [Anushek Prasal]

====================
     2019-04-07    
====================

 * frameworks/base
1b3f820  Use alphaoptimized layout for custom icons on left  [Pranav Vashi]

 * vendor/huawei/kiwi
acbd890  kiwi: Add build rule for libmdmdetect  [Adithya R]

====================
     2019-04-06    
====================

 * device/qcom/sepolicy-legacy
96f30d3  sepolicy: Label persist partition for all SoCs  [Michael Bestas]

 * frameworks/base
aeaa457  Slim recents old enter/exit animation [1/3]  [SpiritCroc]
1d9d566  base: LS filters: Add 2 more variants  [ElDainosor]

 * frameworks/opt/slimrecent
42bbeeb  Slim recents old enter/exit animation [2/3]  [SpiritCroc]

 * packages/apps/HavocSettings
6534670  Slim recents old enter/exit animation [3/3]  [SpiritCroc]

 * system/core
8a93a8f  Revert "sdcard: Allow building as a static library"  [Michael Bestas]
b994bc4  fs_mgr: Skip filesystem check unless fs_type matches  [Dan Pasanen]
f49bc4c  Revert "fs_mgr_fstab: removing fs_mgr_get_entry_for_mount_point_after()"  [Alessandro Astone]
5aa1b16  Fix path for treble default prop  [Wei Wang]

 * system/vold
97e1b94  vold: Add linkage for fs_mgr changes  [Steve Kondik]

 * vendor/huawei/kiwi
881bb8e  kiwi: Remove 32bit bt blobs  [joelh]
4068ca5  kiwi: Add build rule for QPerformance jar  [joelh]
037c15e  kiwi: Clean up kiwi-vendor.mk  [joelh]
2f90567  kiwi: Add ANT, aptX, BT & FM blobs from Huawei Nova 2 Lite  [joelh]
d525615  kiwi: Refresh makefiles  [joelh]

====================
     2019-04-05    
====================

 * external/exfat
e346c7c  exfat: Rename utf conversion symbols  [Tom Marshall]
9e9dc69  exfat: Add static libs for recovery  [Tom Marshall]

 * external/f2fs-tools
5442202  f2fs-tools: Add sload.f2fs support to libf2fs_fsck  [Tom Marshall]
6e67812  f2fs-tools: Rename utf conversion symbols  [Tom Marshall]
d445c41  f2fs-tools: Rename quota symbols  [Tom Marshall]
20e8f06  f2fs-tools: Add static libs for recovery  [Tom Marshall]

 * frameworks/base
2408cfa  base: Optimize toGrayscale function  [ElDainosor]
5640564  base: Intensify the blur amount on LS cover art  [ElDainosor]
1f074860  base: Fix old mobile signal icons  [umikaki]

 * packages/apps/HavocSettings
a38bd6c  Fix J7 prime codename  [Anushek Prasal]
6a1f429  Settings: LS filters: Add 2 more variants  [ElDainosor]

====================
     2019-04-04    
====================

 * frameworks/base
4355645  Add wakelock option for flashlight  [Dominggoes Isakh]
ea44fa0  Fix screen pinning unlock with hwkeys  [Henrique Silva]
e193ec5  Allow screen unpinning on devices without navbar  [Utkarsh Gupta]
2fd3c37  core: Implement Aggressive Battery [1/2]  [Joe Maples]
2d3e72f  Smart Pixels: Update default grid pattern  [Adin Kwok]
4ff0ccb  Smart Pixels: Bypass check for obscured window  [Alex]
6ece3a6  Smart Pixels: Dynamically register receiver  [Adin Kwok]
df3742a  EdgeGestures: fix unregistering input filter  [Jens Lody]
3725afa  ImageUtils: Switch blur lib to SimpleImageBlur  [ElDainosor]

 * packages/apps/HavocSettings
19da1d7  Settings: Implement Aggressive Battery [2/2]  [Joe Maples]
8be2d6f  Settings: Fix typos  [governmentissuejoe]

 * prebuilts/clang/host/linux-x86
6153770  Update prebuilt Clang to r353983b.  [Yi Kong]

====================
     2019-04-03    
====================

 * external/vixl
3313224  libvixl: Disable use of dex2oat pgo profile [1/2]  [mydongistiny]

 * frameworks/base
bac9515  Merge tag 'android-9.0.0_r35' into pie  [Anushek Prasal]
4a127c6  GamingModeTile: stop adjusting volume  [HolyAngel]

 * packages/apps/Bluetooth
9cee3b3  Merge tag 'android-9.0.0_r35' into pie  [SKULSHADY]

 * system/bt
1128e8c  Merge tag 'android-9.0.0_r35' into pie  [SKULSHADY]

 * system/netd
a5767e1  Merge tag 'android-9.0.0_r35' into pie  [SKULSHADY]

