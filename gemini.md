
====================
     05-16-2019
====================


   * external/sqlite/
cc954ee sqlite: upgrade to SQLite 3.28.0

   * frameworks/base/
5cbeeb56520e Revert "hwui: Enable quicksilver"
52c48bc81b50 SystemUI: Fix clicking battery icon in QS header
6d4c6632d551 base: Add toggle to disable battery estimates in QS [1/2]

   * packages/apps/Settings/
9ef94508eb Settings: Add toggle to disable battery estimates in QS [2/2]
3071dfd096 Settings: Add Q Green accent [2/3]
a508b726ab Settings: Add Sweet Q Purple accent [2/3]

====================
     05-15-2019
====================


   * frameworks/base/
06ad5054235e LiveDisplay tile: allow FEATURE_MANAGED_OUTDOOR_MODE
82a23130e6ae Improve checks for lockscreen visualizer
67f378a349be SystemUI: Improve Circle battery size
0d33701ab6a2 SettingsLib: Increase Signal icon size
d5abed856975 SystemUI: Improve battery estimate layout in QS
36a7ead8b76f base: Add Q Green accent [1/3]
4a26bdf6daf6 base: Add Sweet Q Purple accent [1/3]
02f48c75f146 KeyguardUpdateMonitor: Fix SystemUI crash with auto face unlock
7071a7daa42a Fix conflict between pulse auto color and lockscreen wallpaper
38a3a9f402b4 Lockscreen Visualizer: Check for media playing before displaying artwork
9f4d2a9956e8 Lockscreen Visualizer: Automatic color based on wallpaper if no album art found
efcccaed78cc Update Turkish translations
da7176dc1e4b base: Add seekbar to media notification
fe96ed992c65 Q Always-On Display: Add double tap media slice to skip song
442c2fc80b51 Q Always-On Display: Show media info in keyguard slice
8b990d24dd12 SystemUI: Fix ambient music ticker double tap detection
1a4d9b283706 base: Use headline font in notification texts
9a7df1c69300 SystemUI: Use headline font in various parts
cbefd388fc70 Fix weird artifact in battery icon
f5f4b075cc3e Improve Q battery icon and unify with portrait style
1e68302218b8 SettingsLib: Expose Q battery icon paths
800bd85bc55f SystemUI: Implement enhanced battery estimates in QS

   * vendor/themes/
938c917 themes: Add Q Green accent [3/3]
e8b5a2b themes: Add Sweet Q Purple accent [3/3]

====================
     05-14-2019
====================


   * frameworks/av/
51a046ed70 Explicitly initialise base class in copy constructor

   * frameworks/base/
b4a4ab9ae432 SystemUI: Set proper color for battery text view
5016d7ee783b base: Add Q style to battery icon chooser [1/2]
aa20c35a248b Battery icon: Don't force show percentage
060b13fad9aa Settings: inherit battery meter style in view [1/2]
3559137908e8 BatteryMeterView: Fix logcat spam
0ff74b7fde33 Battery icon style: improve text/hidden switch
f5b1e68a20bd Battery icon: force show pct in QS header and when charging/powersave
ce23aafedd5d Battery icon: show outside percentage on charging
8cf773bac3d3 Text battery style: show a bolt ⚡ when charging
2064e9228f3b SystemUI: clean up battery styles code
b0ac58eb099b Add the powersave hint to the circle battery
02a35117efe7 BatteryMeterDrawable: add dotted circle style (1/2)
36e430a01699 BatteryMeterDrawable: add hidden option (1/2)
040ad9d475fc BatteryMeterDrawable: add text style (1/2)
39e1af5b0640 BatteryMeterDrawable: add battery styles
c1cf0cf6a34a Implement battery percent styles (1/2)
21d4775ad23b base: Cleanup battery styles implementation
e9517c501117 CustomTextClock: Improvements and translations

   * packages/apps/CarrierConfig/
4c189b9 CarrierConfig: Enable VOLTE, WFC, VT on Singapore carriers

   * packages/apps/Settings/
7514d7a601 Update Turkish translations

====================
     05-13-2019
====================


   * packages/apps/HavocSettings/
bfc78b8 Add montana to devices

====================
     05-12-2019
====================

   * bootable/recovery/
214565e5 recovery: Mark unused variable

   * frameworks/base/
07523095420d base: SystemUI: fix themeing of notification shelf dot
fb5f843c2614 Remove useless warning when dismissing notification
8506599337ab KeyguardSliceView: Align as per the Clock Style
a99fb871186b Don't force show battery percentage while charging or powersave
ff1bbb393b86 Android Q text clock Portuguese translation
a958d29cf6ce Update Turkish translations
7184d38586d8 Android Q text clock Greek translation

   * packages/apps/Settings/
c274d5ae0e Update Russian translations

====================
     05-11-2019
====================


   * frameworks/base/
c92c383d8d37 SystemUI: Fix NavBar tuner crash when using Oreo QS style
3f439014233c SystemUI: Fix notification lag
0cc9ce5a0597 Fix translation derps

   * packages/apps/HavocSettings/
6d6235d Update Russian translations
c2d18a4 Add Potter to devices

   * packages/apps/Settings/
8772b85d44 Settings: Smart Charging (2/4)
4af6b3c5af Update Turkish translations

====================
     05-10-2019
====================


   * frameworks/base/
b67436c217d7 base: Smart Charging (1/4)

   * packages/apps/SmartNavSettings/
e8827d0 Fix typo in Turkish translation

