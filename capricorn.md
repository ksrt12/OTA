
====================
     05-23-2019
====================


   * frameworks/base/
3ab70c754fba Revert "HW: Fix Home button during call"
5f5b5dfe601f Support CALLBACK_TYPE_SENSOR_ROUTING
a79d0884d8c0 Revert "SystemUI: Add Cellular tile icon from OOS"
a34afc035404 Keyguard: Don't listen for fingerprint when prox.sensor is covered
b38438c1984c show bt battery for all devices
726c4830d1bc change battery save color
97cc9e3eacc0 fix answer from home key
351b65366894 toggle torch proximity check [1/2]
4f3c1182614f proximity check for all wake keys
3445f081187e Havoc Build Date [1/2]
dc92ca72b483 fix button backlight
08bddb0bcf96 fix priv-apps permissions
6259c1c4f3b3 for gemini: Revert "Revert "Proximity check on wake""
dd30c04c7520 Revert "hwui: Enable quicksilver"

   * packages/apps/Dialer/
525c6c42d Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
1993d4c toggle torch proximity check [2/2]
8833987 Rework hw button illumination
618ef24 Revert "Pocket judge"
e605974 Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"
033c75f Add a6000 in devices

   * packages/apps/Settings/
10fd28639c Havoc Build Date [2/2]
2e6d9dca10 DeviceInfoSettings: Bring back CAF/AOSP tags
5e656037c2 my colors
a02f99ce1d Revert "Revert "Settings: Add toggle for proximity wake""

   * system/bt/
c7997373f Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
bbcdce43f RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
d6bcf2de9 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
e19da87df Allow adb root even in no debuggable builds

   * vendor/support/
de27e5c add variables for buttom backlight

====================
     05-22-2019
====================


   * frameworks/base/
7f93dc9d015b Add in camera action to bindable actions (1/2)
16f8f894d250 HW: Fix Home button during call
5fb97a207dba SmartActions: Turn on Tri-state ringer toggle [1/2]
1ed16049fd5a SmartActions: Add media controls to bindable actions [1/2]
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

   * packages/apps/HavocSettings/
3223538 Add rosy in devices
9ff9c99 Add YUREKA2 to devices

   * packages/apps/SmartNav/
97d8dce SmartActions: Add in camera action to bindable actions (2/2)
920983b SmartActions: Turn on Tri-state ringer toggle [2/2]
f02521b SmartActions: Add Play/Pause media to bindable actions [2/2]
888b755 SmartNav: update smartbar home drawable
b97a6ef SmartNav: Use correct colors for popup

   * prebuilts/r8/
eab4308 r8: Update D8 and R8 to 1.6.1-dev

   * vendor/themes/
de10d16 themes: Fix package name

====================
     05-21-2019
====================


   * frameworks/base/
2b87e2de3eb4 CustomTextClock: Fix disappearing clock and SystemUI crash

====================
     05-20-2019
====================


   * frameworks/base/
e61abc712a89 base: Optimize the size of statusbar icons
24c3865d7870 Battery Estimates: Show only in QSB Header
b741785c11fa SystemUI: Allow Pixel 3 live wallpapers to work in Ambient Display
9c7aeb24d23b Lockscreen visualizer: Fix color transitions
26087765d628 Revert "Q Always-On Display: Show media info in keyguard slice"
5e26acb082c3 Revert "Q Always-On Display: Add double tap media slice to skip song"

====================
     05-19-2019
====================


====================
     05-18-2019
====================


   * prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-9.1/
8f8b95b Add aarch64-elf GCC 9.1.0 toolchain for x86_64 hosts
c615e81 Initial commit

====================
     05-17-2019
====================


   * frameworks/base/
f4ce5749cad6 Battery Estimates: Disable by default [1/2]
e9434d09fe54 Battery Estimates: Move battery icon to QS header when disabled
61116db2f680 Aggressive Battery: fix auto enable on battery saver
0bb14d1fcb2e base: SystemUI: make qs edit repect header image
7e61cca7ce03 Revert "Network traffic: Retain our notch check"
f4312b75048e LiveDisplay tile: allow override outdoor capablity

   * hardware/havoc/interfaces/
a8b523d havoc/interfaces: Remove lineage trust hal
3dde4e9 havoc/interfaces: Remove lineage power hal
f99f0f8 Init Havoc...

   * packages/apps/Settings/
d492b42374 Battery Estimates: Disable by default [2/2]
3aa40abc7e Settings: Restart SystemUI when toggling battery estimates
8fcef4284a Settings: Add User icon to the searchbar

