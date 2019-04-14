====================
     2019-04-14    
====================

 * device/xiaomi/gemini
bb76787  add SysUI to PRODUCT_DEXPREOPT_SPEED_APPS  [Wei Wang]
3a828e2  overlays: set default corener paddings and radius  [Kazakov Stepan]
02bcf0f  vndk fixes  [Kazakov Stepan]
278ea6c  restore audio from jasmine_sprout  [Kazakov Stepan]

 * vendor/syberia
e953c38  update Lawnchair to alpha-1983  [Kazakov Stepan]

====================
     2019-04-13    
====================

 * device/qcom/sepolicy
63d01d8  Merge tag 'LA.UM.7.4.r1-05000-8x98.0' of https://source.codeaurora.org/quic/la/device/qcom/sepolicy into 9.0  [Kazakov Stepan]

 * packages/apps/Settings
9720ac1  Settings UI: Open UserSettings fragment on user icon click  [DennySPB]

 * vendor/codeaurora/telephony
4f253f3  Merge tag 'LA.UM.7.4.r1-05000-8x98.0' of https://source.codeaurora.org/quic/la/platform/vendor/codeaurora/telephony into pie  [Kazakov Stepan]

====================
     2019-04-12    
====================

 * packages/apps/Settings
078a39f  Brandify settings title  [DennySPB]
06be20d  BatteryMeterView: unhardcode charging strings  [DennySPB]
531a57e  UI : Increase toolbar size and misc fixes  [IacobIonut01]
504298d  Settings UI : Show User Icon in dashboard  [IacobIonut01]
146dbe7  Settings UI : Tint Storage ProgressBar & Redesign Toolbar  [IacobIonut01]
0792518f  Dashboard : Quick Redesign  [IacobIonut01]
1edabdd  Battery : Redesign BatteryMeterView  [IacobIonut01]

====================
     2019-04-11    
====================
 * art
2d7d845  ART: Support kryo385 CPU  [Artem Serov]

 * build/make
3e38a88  Correctly configure armv8-2a for 32-bit  [Miao Wang]
cb693f8  Enable armv8-2a supporting on 2nd arch. variant  [Isaac Lee]

 * build/soong
9fce16e  re-add kryo300 cpu variant after f7bd3bb1  [DennySPB]
b940191  androidmk: Skip obsolete JACK flags  [Ng Zhi An]
4cab171  Stop using GCC in toolchain_library  [Dan Willemsen]
246f59c  Support Qualcomm Kryo 385 CPU variant  [Artem Serov]
7d789cd  Add to support armv8-2a on 2nd arch. variant  [mtk15504]
f7bd3bb  Move arch variants registering code to arch.go  [Jaewoong Jung]
f1f5857  Configure the default arch variant features per-OS  [Dan Willemsen]
3c36a6b  Fix multilib first with multiple 64-bit architectures  [Colin Cross]

 * hardware/interfaces
d9a9f6b  Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0  [Kazakov Stepan]

 * hardware/qcom/audio-caf/msm8996
b2c9f5e  include <log/log.h> instead of <cutils/log.h>  [Kazakov Stepan]
39c10a9  hal: Fix incall recording calibration issue  [Aditya Bavanari]

 * hardware/qcom/bt
1f6031e  Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into 9.0  [Kazakov Stepan]

 * hardware/qcom/display-caf/msm8996
40c3c86  Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into 9.0  [Kazakov Stepan]

 * hardware/qcom/media-caf/msm8996
7f0d4d7  Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into 9.0  [Kazakov Stepan]

 * hardware/qcom/wlan
ca57c36  Merge tag 'LA.UM.7.5.r1-04500-8x96.0' into 9.0  [Kazakov Stepan]

 * packages/apps/Settings
751fbe3  Team: we are looking for new santoni maintainer  [DennySPB]

 * vendor/qcom/opensource/audio
c7d796f  Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie  [Kazakov Stepan]

 * vendor/qcom/opensource/data-ipa-cfg-mgr
abdb87d  Merge tag 'LA.UM.7.5.r1-04500-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie  [Kazakov Stepan]

====================
     2019-04-10    
====================

 * external/bromite-webview
df003ce  rebase  [Kazakov Stepan]

 * frameworks/base
09adfa9  Connectivity: Trigger network permission change for non DDS network  [Sunmeet Gill]
8ac2369  connectivity: Make http(s) probe connections non-persistent.  [Devi Sandeep Endluri V V]
5ed5c43  FrameworkBase: Fix NullPointerException of AMS  [xiaohuin]
b90d8c7  IconsHandler: Really update the icon packs available  [Giuseppe Maggio]
b479d71  Support per-app icon and label customization [2/2]  [Anas Karbila]
b2a4ea6  LTE tile: Remove oreo style slashes  [Pranav Vashi]
daf4f5e  The surface hang up when screen on and screen off  [Guo Li]
86b59b3  Fixed setting incorrect mode of vibration  [Sun Changqing]
8860e20  backup: right way to check canonical file path  [pip.zhang]
65bf3e3  Fixes crash/race condition when destroyActivity  [katao]

 * frameworks/opt/net/wifi
a94c0f5  Merge tag 'LA.UM.7.6.r1-04500-89xx.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi  [DennySPB]

 * packages/apps/Launcher3
08f665c  Launcher3: Switch to actual compiled library for SystemUI  [Pranav Vashi]
5dd0629  Add INTERACT_ACROSS_USERS_FULL permission for quickstep  [Pranav Vashi]
7fa10ea  Launcher3: Add permission to allow updating database  [neobuddy89]
5e2456b  Launcher3: Improve label hide logic  [neobuddy89]
c917f0f  proguard: Also keep FixedScaleDrawable  [Diogo Ferreira]
d27d40e  Launcher3: Fix NPE in PagedView  [Pranav Vashi]
9e82928  Launcher3: Bump sdk version  [Pranav Vashi]
22022d2  Settings: fix method to hide dividers  [Alex]
293900d  Icon edit: Add fast scrolling to icon pack RecyclerView  [Alex]
8428543  Beautify icon edit dialog  [Alex]
6c192f8  Fix icon editor picking the wrong icon on tap  [ezio84]
32dad73  Support per-app icon and label customization [1/2]  [Anas Karbila]
98e2746  Launcher3: Use generic android icon for IconPack chooser  [Giuseppe Maggio]

 * vendor/nxp/opensource/commonsys/packages/apps/Nfc
4038040  fix typo  [Kazakov Stepan]

 * vendor/qcom/opensource/data-ipa-cfg-mgr
6b6c850  Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie  [Kazakov Stepan]

====================
     2019-04-09    
====================

 * device/xiaomi/gemini
bf71f30  build kernel with clang 9.0.2  [Kazakov Stepan]
77090c4  build SyberiaOS  [Kazakov Stepan]

 * external/bromite-webview
31d4090  Bromite System WebView 73.0.3683.107  [Kazakov Stepan]

 * packages/apps/Settings
0398731  Team: add maintainer for Xiaomi 6X (Wayne) Also cleanup "About Team" screen  [blinoff82]

 * packages/apps/SyberiaSettings
401d91d  Implement Aggressive Battery [2/2]  [Joe Maples]

 * vendor/syberia
3318868  jenkins: add Xiaomi 6x (Wayne)  [blinoff82]

====================
     2019-04-08    
====================

 * external/bromite-webview
623885a  Bromite System WebView 73.0.3683.105  [Kazakov Stepan]

 * frameworks/base
4b878c0  EdgeGestures: fix unregistering input filter  [Jens Lody]
38a8916  core: Implement Aggressive Battery [1/2]  [Joe Maples]

 * hardware/qcom/display-caf/msm8996
7af887d  Merge tag 'LA.UM.7.5.2.r1-02000-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0  [Kazakov Stepan]

 * hardware/qcom/fm
d78abd7  Automatic translation import  [Michael Bestas]

 * packages/apps/FMRadio
4743cbc  Automatic translation import  [Michael Bestas]

 * prebuilts/clang/host/linux-x86
01b4a3d  Update prebuilt Clang to r353983b.  [Yi Kong]

