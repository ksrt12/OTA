====================
     06-05-2019
====================

   * frameworks/av/
3092601cd6 Merge tag 'android-9.0.0_r42' into pie

   * frameworks/base/
a5e4ec936e60 Revert "hwui: Enable quicksilver"
50eefdf08461 Merge tag 'android-9.0.0_r42' into pie
473fc03cfbb1 KeyguardSliceProvider: Show dnd icon regardless of suppression mode
4e7ac60ee9e5 Q Style Clock: Set "It's" to accent color instead of gold / yellow color

   * packages/apps/CellBroadcastReceiver/
e100c47 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/Contacts/
3088d1b0e Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/Dialer/
c8040055f Revert "Fix in-call buttons layout"

   * packages/apps/DocumentsUI/
1ec25c71 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/EmergencyInfo/
c93fc34 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/Nfc/
2636c6df Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/PackageInstaller/
ed8e1766 Merge tag 'android-9.0.0_r42' into pie

   * packages/apps/Settings/
a4555eefd9 Merge tag 'android-9.0.0_r42' into pie
6758f9e75b Settings: Add battery saving mode for location
03d669d057 livedisplay: Don't show display mode and color tempertature on HWC2
76383f3983 Revert "Settings: Hide Night Mode suggestion if LiveDisplay feature is present"

   * packages/inputmethods/LatinIME/
40292fb36 Merge tag 'android-9.0.0_r42' into pie

   * packages/providers/MediaProvider/
b83152f Merge tag 'android-9.0.0_r42' into pie

   * system/bt/
dbb4e83f0 sdclang: true
dd6509256 Merge tag 'android-9.0.0_r42' into pie

   * system/libhwbinder/
17d29d6 Merge tag 'android-9.0.0_r42' into pie

   * system/vold/
756a932 Merge tag 'android-9.0.0_r42' into pie

====================
     06-02-2019
====================

   * external/zlib/
593a35c minizip: More build fixes
99fc328 minizip: Clean up the code
2c043d6 minizip: Fix build under Android 6.0 and higher
39df7f0 zlib: enable unaligned memory access

   * frameworks/base/
0fbb84c08992 Revert "NightDisplayController: report unavailable if livedisplay feature is present"

   * hardware/lineage/livedisplay/
fd1713f sdm: Fix restoring default mode when using prebuilt vendor

   * packages/apps/HavocSettings/
015fa4f QS Headers: Fix summary and add missing entry

   * prebuilts/r8/
51b762f r8: Update D8 and R8 to 1.6.3-dev

====================
     05-31-2019
====================

   * frameworks/base/
341fea02e78f BoostFramework: Trigger IOP at Displayed for duration.
4f7b9cf349c5 Boostframework: Adding reserved hint types for launch boost
90c200c88ec3 BoostFramework: Fix - Avoid Null Object Reference.
31e61fc71b10 BoostFramework : Modified Start Proc trigger and added Kill Hint.
806a56dd4a11 Revert "base: Add overlay for BoostFramework"
2df9bfdc877f base: Use wireless charging animation for wired charging too
d08585770fd7 Add toggle for charging animation [1/2]
aa88a4ed4827 base: SystemUI: Fix qs-alpha conditions
8a055c7a22a5 base: Set QS BG alpha even with set qs from resources [1/2]

====================
     05-29-2019
====================

   * packages/apps/HavocSettings/
b92117f Add toggle for charging animation [2/2]
34cc4e5 Settings: Set QS BG alpha even with set qs from resources [2/2]

====================
     05-27-2019
====================

   * frameworks/base/
0eefaf881216 Q Style Clock: Make it fully translatable
1ad102b2767f SystemUI: Cleanup keyguard_status_view layout
5ee5018da97e CustomTextClock: Code style cleanups
f07c3b2cae12 KeyguardStatusView: Cleanup pointless duplication
ac14cd09211b CustomTextClock: Cleanup
a03d881b7b70 base: Double tap to trigger doze [1/2]

   * packages/apps/CustomDoze/
c174fdf CustomDoze: Double tap to trigger doze [2/2]

====================
     05-26-2019
====================

   * external/jemalloc/
5636650 Fix performance of multiple same size allocations
0eb3b7d [HAX] background_threads: explictly disable libdl usage
8bd657b jemalloc: update to version 5.2.0
8d70d0c jemalloc: Further updates to code
8e277a1 jemalloc: update to version 5.1.0

   * frameworks/base/
35982d769905 Add toggle for lockscreen weather and improve code
d867b6c54b6d AmbientIndicationContainer: Fix crash when adding statusbar view
3a1da5012866 HeadsUpAppearanceController: allow heads-up to draw beyond bounds

   * packages/apps/HavocSettings/
41d3596 Add toggle for lockscreen weather
97f1afe Fix Vietnamese translation

   * prebuilts/build-tools/
7240fd8 build-tools: Update ccache to 3.7.1
421a164 build-tools: Update the rest of the prebuilts
1ef7c1f build-tools: Update ninja using latest source
de8b5f7 build-tools: Rebuild for new glibc and sources

   * system/netd/
5170497 Skip permission checking for binder call from system server
81c9f39 Modernize codebase by replacing NULL with nullptr

====================
     05-25-2019
====================

   * frameworks/base/
612deefc5da5 Update Spanish translations
cb541e7b4b4f Update French translations
d07e4539c887 Update Spanish translations
08f249233a0b Update Portuguese-BR translations
e86e54b94db2 SystemUI: fix the behavior of QS with isDualTarget=true

   * packages/apps/HavocSettings/
cab175e Update Hungarian translations
447469b Add new maintainer for tulip

   * packages/apps/Settings/
cd95dec45f Update French translations
59a23b3b9d Update Russian translations
60716d20dc Update Spanish translations
9da0a58092 Settings: Update NFC drawable

====================
     05-24-2019
====================

   * frameworks/base/
fc43176e9b3b Use headline font on battery percentage
ba4ece075327 Fix NPE on navbar
850708cb6e8c LiveDisplay: Improve sunrise/sunset calculator

====================
     05-23-2019
====================

   * frameworks/base/
7f93dc9d015b Add in camera action to bindable actions (1/2)
16f8f894d250 HW: Fix Home button during call
5fb97a207dba SmartActions: Turn on Tri-state ringer toggle [1/2]
1ed16049fd5a SmartActions: Add media controls to bindable actions [1/2]

   * packages/apps/HavocSettings/
033c75f Add a6000 in devices

   * packages/apps/SmartNav/
97d8dce SmartActions: Add in camera action to bindable actions (2/2)
920983b SmartActions: Turn on Tri-state ringer toggle [2/2]
f02521b SmartActions: Add Play/Pause media to bindable actions [2/2]
888b755 SmartNav: update smartbar home drawable
b97a6ef SmartNav: Use correct colors for popup

====================
     05-22-2019
====================

   * frameworks/base/
f6e7afa1266a Fixed auto-brightness first screen update
6afc419556ea Smart Charging: allow using device overlays
dca5ad082376 Smart Charging: rework for using more common sysfs node [1/2]
7eb07f181896 SettingsLib: Don't show system overlays on apps list
1321cd40478b LiveDisplay: Change night/day mode transition behavior
1b43e81ecb8f OpaLayout: Fix IllegalStateException
aad0a79a3039 PagedTileLayout: Fix IllegalStateException
e2b390a39ca3 Fix NPE on ExpandableNotificationRow
6edb1eb38755 Use headline font in preference title
0c07c4a03b08 appops: put @hide back to opToDefaultMode
d424bfbe1a35 ActivityThread: Remove Failed to find provider info logspam
57df0e2bc97d LS Artwork: Intensify blur more to make Clock styles more prominent
2b87e2de3eb4 CustomTextClock: Fix disappearing clock and SystemUI crash

   * packages/apps/HavocSettings/
3223538 Add rosy in devices
9ff9c99 Add YUREKA2 to devices

   * prebuilts/r8/
eab4308 r8: Update D8 and R8 to 1.6.1-dev

   * vendor/themes/
de10d16 themes: Fix package name

