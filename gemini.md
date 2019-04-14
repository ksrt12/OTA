====================
     04-14-2019
====================


   * frameworks/base/
81793eebcbc9 Revert "SystemUI: Add Cellular tile icon from OOS"
da15f2c6af22 Keyguard: Don't listen for fingerprint when prox.sensor is covered
5ac771a3ca1b show bt battery for all devices
fda24d454564 change battery save color
1981b4db09c2 fix answer from home key
cbb2aa866b7a toggle torch proximity check [1/2]
41aa89035920 proximity check for all wake keys
4cd37667cb8c Havoc Build Date [1/2]
965806f1fce3 fix button backlight
01dc9840f07b fix priv-apps permissions
28b64d4aa947 Revert "hwui: Enable quicksilver"
bb59633a8f04 CustomTextClock: Set Text color based on wallpaper
6174713a4074 CustomTextClock: Match Android Q
e28d433d52e8 CustomTextClock: Make clock strings translatable
a9c5198e27f5 CustomTextClock: Improve UI and optimisations
be0bd1031fbf Lockscreen Clock Styles: Introduce Q style text clock A gist of what happened: - Use a custom TextView to achieve the text - Use Rounded Elegance font cuz why not - Use a attribute to differenciate between hour hand and minute hand - Use a retarded yet simple method to get Strings for given integer - Set text according to system time format (12h/24h) - Set a top margin to push the lockscreen date (Unuglify) - Set a left padding for clock layout (Might need to be overlayed for some devices)

   * packages/apps/Dialer/
70872618b Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
4cb5823 toggle torch proximity check [2/2]
4cd91cd Rework hw button illumination
6081806 Lockscreen Clock Styles: Introduce Q style TextClock

   * packages/apps/Settings/
2f6f92383e Havoc Build Date [2/2]
62f5c2c842 DeviceInfoSettings: Bring back CAF/AOSP tags
84d8e40d23 my colors

   * system/core/
50785a3b6 Allow adb root even in no debuggable builds

   * vendor/support/
b022a7c add variables for buttom backlight

====================
     04-13-2019
====================


   * packages/apps/Dirac/
1808d69 Dirac: Change QS tile icon

====================
     04-12-2019
====================


   * frameworks/base/
ffb19a13d2de Lockscreen Visualizer: Add pulse magic [1/2]
cec6977aa299 base: Lockscreen visualizer cleanup
f9899f7ecae9 The surface hang up when screen on and screen off
425cf2868551 backup: right way to check canonical file path
0bb832efa9af Fixes crash/race condition when destroyActivity
5ccf241d74fa Fixed setting incorrect mode of vibration

   * packages/apps/HavocSettings/
dd850e2 Settings: Cleanup and fixes
de2ca53 Lockscreen Visualizer: Add pulse magic [2/2]
5290321 Settings: Lockscreen visualizer cleanup

   * packages/apps/SmartNavSettings/
831a937 Automatic translation import
210d246 SmartNavSettings: Cleanup and fixes

====================
     04-11-2019
====================


   * frameworks/base/
46ec3c4d04e6 base: Add overlay for BoostFramework
f4e7659df7c8 Fix Russian translation

   * packages/apps/Dirac/
d5ed6ba Dirac: Add QS tile

   * packages/apps/Settings/
c35d177743 Fix Russian translation

====================
     04-10-2019
====================


   * frameworks/base/
801aa2dc7b3d base: Fix crash when changing default phone app
19dbbcc8a017 Less aggressive way of updating mobile type icons

   * packages/apps/HavocSettings/
c41ee74 Translate more strings in Russian

   * packages/apps/Settings/
5667fb42c8 Fix Impossible to add fingerprint

====================
     04-09-2019
====================


   * packages/apps/HavocSettings/
58fb26e Fix Russian translation

   * packages/apps/Settings/
9615074f51 Fix Russian translation

====================
     04-08-2019
====================


   * frameworks/base/
70330c89b194 Automatic translation import
46aaa4168556 SystemUI: fix no service and emergency calls only placement
4c14c6f1016f qs_footer: Update visibilities after inflate finish
8b38a1048d90 base: Add OnePlus Red accent [1/3]
30e596483e77 base: Add Black Pearl theme [1/3]

   * hardware/qcom/fm/
d78abd7 Automatic translation import

   * packages/apps/Camera2/
5cb39a396 Automatic translation import
06220ace4 Automatic translation import
3e2195263 Automatic translation import
2955637f8 Fix crash if Exif-Tag buffer-length and component-count are both 0
d228776a1 Camera2: Fix Undo button behaviour
ba14cda59 Camera2: Remove google help preference
248891132 Camera2: Add option to set max screen brightness
5ce0ec2c8 Camera: Powerkey shutter (2/2)
ed40cf3be Camera2: Request for ACCESS_FINE_LOCATION permission
fd3ae8269 Camera2: Stop using GPS when going to background
c4e1d9091 Camera2: Remove settings preferences only once
f566be2b5 Camera2: Only autofocus before a snap if we are actually in "auto" mode.
6d40b4956 Don't attempt to convert degree to orientation enum twice
bb86cc623 Camera2: Target API 27
d7bc0391e Camera2: adaptive icon

   * packages/apps/Contacts/
313a6aeb4 Automatic translation import

   * packages/apps/CustomDoze/
536b56c Automatic translation import

   * packages/apps/Dialer/
f35a412fc Automatic translation import

   * packages/apps/Dirac/
a92626d Automatic translation import

   * packages/apps/FMRadio/
4743cbc Automatic translation import

   * packages/apps/HavocSettings/
e3ed420 Automatic translation import
63015e7 Settings: Add Black Pearl theme [2/3]

   * packages/apps/Messaging/
0455206 Automatic translation import

   * packages/apps/OmniStyle/
b642673 Automatic translation import

   * packages/apps/PackageInstaller/
54695789 Automatic translation import

   * packages/apps/Settings/
c833e2eec7 Automatic translation import
2186612247 Settings: Add OnePlus Red accent [2/3]
da95f0c35d Settings: Add deep sleep info to uptime
5f329cd65d Settings: Move 'About phone' to the bottom

   * packages/apps/SmartNav/
3646b96 Automatic translation import

   * packages/apps/Snap/
253ab00b0 Snap: Remove Lineage SDK dependency

   * packages/apps/Terminal/
d8c3d80 Automatic translation import

   * packages/providers/DownloadProvider/
48883b2 Automatic translation import

   * packages/providers/MediaProvider/
acde028 Automatic translation import

   * vendor/themes/
3e7f1f8 themes: Add OnePlus Red accent [3/3]
68858eb themes: Add Black Pearl theme [3/3]

====================
     04-07-2019
====================


   * frameworks/base/
0f6516d6d660 Custom logo customizations [1/2]
1b3f820fa7a6 Use alphaoptimized layout for custom icons on left

   * packages/apps/HavocSettings/
2eaba71 Settings: Add our discord server
52e28fe Custom logo customizations [2/2]

====================
     04-06-2019
====================


   * device/qcom/sepolicy-legacy/
96f30d3 sepolicy: Label persist partition for all SoCs

   * packages/apps/HavocSettings/
6534670 Slim recents old enter/exit animation [3/3]

   * system/core/
8a93a8f9e Revert "sdcard: Allow building as a static library"
b994bc437 fs_mgr: Skip filesystem check unless fs_type matches
f49bc4c1d Revert "fs_mgr_fstab: removing fs_mgr_get_entry_for_mount_point_after()"
5aa1b1606 Fix path for treble default prop

   * system/vold/
97e1b94 vold: Add linkage for fs_mgr changes

====================
     04-05-2019
====================


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
6a1f429 Settings: LS filters: Add 2 more variants

