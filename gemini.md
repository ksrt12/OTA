
====================
     07-18-2019
====================


   * device/xiaomi/gemini/
cbe62860 update priv_app sepolicy
e559f1f9 add snapcam priv-app permissions
1a22e353 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' into 9.0

   * frameworks/base/
196d6839a94 wifi: Filter unsupported networks from scan results
c8783a6dbe4 Wifi: Connect indication on UI for STA when AP supports SAE+PSK

   * frameworks/opt/net/wifi/
524f3e98a Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/net/wifi into pie

   * frameworks/opt/telephony/
d9c81fa23b Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/frameworks/opt/telephony into HEAD

   * hardware/interfaces/
60df6dd80 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/interfaces into 9.0

   * hardware/qcom/audio-caf/msm8996/
979aa2e7 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/audio into 9.0

   * hardware/qcom/bt-caf/
fa39bcc Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/bt into 9.0

   * hardware/qcom/display-caf/msm8996/
aed97947 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/display into 9.0

   * hardware/qcom/media-caf/msm8996/
82b1c1ad Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/hardware/qcom/media into 9.0

   * kernel/xiaomi/msm8996/
4b9eca1dbcbc Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' into drivers/staging/qcacld-2.0

   * vendor/qcom/opensource/audio/
6c72725 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/audio into pie

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
2fa4b28 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/data-ipa-cfg-mgr into pie

   * vendor/qcom/opensource/interfaces/
4d73d69 Merge tag 'LA.UM.7.5.2.r1-03300-8x96.0' of https://source.codeaurora.org/quic/la/platform/vendor/qcom-opensource/interfaces into pie

====================
     07-17-2019
====================


   * vendor/havoc/
69574b39 update prebuilt apps

====================
     07-16-2019
====================

   * art/
37b0c5e2f1 oatdump: Only compile CompactDex conversion for host
755171d29e oatdump: Convert CompactDex to StandardDex before exporting

   * external/skia/
fbc77220c5 Add private save-behind and draw-behind methods to canvas.
780f94a577 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/external/skia into pie

   * frameworks/base/
6e369bdd7f4 GamingMode: Fix unnecessary unloading of gaming mode
ea9ea9904db MusicTile: Clean up redundant code
31ae1f2143e Improve performance of unclipped save layers.
8e257625331 base: Add Gaming Mode icons from OOS
480861a3f65 Aggressive Battery: Improve value substitution
e11a7a7af1e Guard in short-circuit evaluations for stringSplit methods
d2674eedef0 GamingMode: allow disable navigation gestures [1/2]
5b3f832bdde GamingModeTile: Long press to open settings [1/2]
36eba01ac6c base: Add Gaming mode tile
1e2d58c47f9 GamingMode: Exempt calls and alarms when headsup disabled
9b6d0b8beab core: Import more animations from Android Q
ae42c3ae424 SystemUI: Disable wellbeing grayscale tile if reading mode available
4c3b20c3316 LiveDisplay: Refactor for HWC devices and cleanup
e5789c10b81 Revert "SystemUI: Add LiveDisplay tile"
4ed2b1a2019 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/frameworks/base into pie

   * frameworks/opt/net/ims/
f047cdf Merge branch 'pie-gsi' of https://android.googlesource.com/platform/frameworks/opt/net/ims into pie

   * packages/apps/Dialer/
d5d1ef657 Revert "Fix in-call buttons layout"

   * packages/apps/HavocSettings/
eb06423 toggle torch proximity check [2/2]
ea8fc68 Rework hw button illumination
44d53c1 Revert "Pocket judge"
a7cb375 Revert "Settings: : Make FP detection in pocket mode configurable [2/2]"

   * packages/apps/Settings/
337bbbee29 Support to notify connected/disconnected stations
87fbab07ad Havoc Build Date [2/2]
b1016017e2 DeviceInfoSettings: Bring back CAF/AOSP tags
0d7a1b5d23 my colors
df95413012 Revert "Revert "Settings: Add toggle for proximity wake""

   * packages/services/Telecomm/
2b6280f1 Merge branch 'pie-gsi' of https://android.googlesource.com/platform/packages/services/Telecomm into pie

   * system/bt/
4f2602e61 Fix handling of BLE create connection when all PHYs are set When all PHYs are set during BLE create connection, there is an assert error seen in BT stack. This change fixes this issue.
96f6eba6f RFCOMM: Add new API to check port state based on SCN As there is no API in RFCOMM to check exact port status, AG checking port opening state and continuing outgoing connection even incoming port already opened.
4806fab69 sdclang: true
38fa15e14 Add BLE Scan Phy parameter to scan API Add BLE Scan Phy parameter to set scan parameters API.

   * system/core/
7bc7ce328 Allow adb root even in no debuggable builds

   * vendor/havoc/
751160af vendor: Dynamically add custom APNs
dfbd9bde common: Add getcap/setcap to PRODUCT_PACKAGES

   * vendor/support/
4125e3c add variables for buttom backlight

====================
     07-15-2019
====================


   * packages/apps/HavocSettings/
9620bcb Use SeekBar for OP gestures feedback duration
5af7426 Settings: Improve a few strings
e972e46 GamingMode: Allow disable navigation gestures [2/2]
0b35939 GamingMode: Move game add summary at bottom
8802e91 GamingMode: Disable modifying settings when GamingMode is turned on

====================
     07-14-2019
====================


   * kernel/xiaomi/msm8996/
377bad6c74ea ext4 crypto: Avoid dynamically allocating memory for file names
5737f06bff98 ANDROID: sdcardfs: Allocate temporary name buffer on the stack

   * system/core/
56d74c085 fs_mgr_fstab: Add Adiantum support
ff07f4613 Revert "Support Speck encryption."

   * system/vold/
61facd5 Merge remote-tracking branch 'aosp/pie-gsi' into pie

====================
     07-13-2019
====================


   * bootable/recovery/
6136f9dd Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * build/blueprint/
6c23f79 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * build/kati/
69cb715 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * build/soong/
eca3f313 Give Blueprint modules access to all namespaces

   * development/
9b8a35f8e Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * external/f2fs-tools/
bd0159a Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * external/fsck_msdos/
8eea348 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * external/icu/
c555ad468 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * external/jemalloc/
3c5b1fb Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * external/proguard/
56c2bf7 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * external/turbine/
4cba3b5 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * frameworks/av/
a768b60268 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * frameworks/support/
63e2472598 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * hardware/broadcom/wlan/
9610886 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * hardware/havoc/interfaces/
7d39191 Introduce camera motor hal

   * hardware/nxp/nfc/
6ea5be3 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * hardware/qcom/data/ipacfg-mgr/
7367dc7 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * hardware/qcom/gps/
a62882c9 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * packages/apps/Camera2/
741cefaa1 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/CarrierConfig/
b45beb0 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/CellBroadcastReceiver/
43089af Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/Contacts/
1c882fb88 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/DocumentsUI/
664edc29 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/EmergencyInfo/
d666d24 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/Nfc/
5fea3075 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/PackageInstaller/
615aabbc Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/apps/Settings/
2afaa963c3 BatteryUtils: Show anomalies of pre-O apps
22a1af3091 GamingMode: Long press tile to open settings [2/2]
d50018b91b LiveDisplay: Refactor
448c5a55c8 LiveDisplay: Rebrand to keep consistency
2a73fcb4bb LiveDisplaySettings: Fix outdoor mode preference on hwc2
79995fcde4 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/inputmethods/LatinIME/
7117b96ce Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/providers/DownloadProvider/
fed244c Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * packages/providers/MediaProvider/
2a3ab8e Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * system/bt/
f5b67d1e4 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * system/core/
569b60869 tombstoned: fixed tombstones failed issue
416039080 health: Add CAP_WAKE_ALARM to service via init
7c79b7ba2 Fix two clang-tidy issues in crasher.cpp.
564a7f79d Add native vsock support to ADB.

   * system/extras/
64531acb Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * system/libhwbinder/
26a8e76 Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * system/netd/
b3d581f Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * system/timezone/
de4a2bf Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * system/tools/hidl/
843066d Merge remote-tracking branch 'aosp/pie-gsi' into pie

   * system/update_engine/
5be3b00 Merge remote-tracking branch 'aosp/pie-gsi' into lineage-16.0-pie-gsi

   * vendor/havoc/
3e596962 update Lawnchair to alpha-2319

====================
     07-12-2019
====================


   * external/nano/
1d23c7f7 nano: Zero entire struct sigaction struct
5f71cf2e nano: Bump PACKAGE_STRING to 4.3 too

   * frameworks/av/
c24c924da9 CameraService: Support hooks for motorized camera

====================
     07-11-2019
====================


   * external/nano/
37aec986 Properly 0 initialize sigaction
10fe4835 Merge tag 'v4.3' into HEAD

   * kernel/xiaomi/msm8996/
1f5d51b1f324 qcacld-2.0: limit time for scan when miracast is running

====================
     07-10-2019
====================


   * frameworks/base/
f43265ba00a SystemUI: Protect against terrible music players
266e6c68dac perfLock: Enable ActivityBoost
2d685898458 Prevent crash in TTS engine due to improper configuration

   * frameworks/opt/net/wifi/
949794745 Merge 11660e39288d6f63a017fd92dade956de8746176 on remote branch

   * frameworks/opt/telephony/
3baad630a5 Merge b2cba5ec1e7dc77ad76c136f31aab57bc927ce4e on remote branch

   * hardware/interfaces/
64020a935 Merge 2f57e8e3ad3588e10bbbcd56c22c03c7c78e5e0e on remote branch

   * hardware/qcom/audio-caf/msm8996/
a638831c Merge 880800db1da4ae6b90e0670e65af240bbbc66f49 on remote branch

   * hardware/qcom/bt-caf/
9cd3b55 Merge b7bdccd743d37f592cf4e407c5ae9c9e1f130043 on remote branch

   * hardware/qcom/display-caf/msm8996/
30c4250c Merge b361ad8b63a12b11bbadd6adca4ffcb632bba8dc on remote branch

   * hardware/qcom/media-caf/msm8996/
96d2d1e4 Merge 429b73b3990f743f16b292cbd6a78ccfb80b1222 on remote branch

   * kernel/xiaomi/msm8996/
b70247d7b061 Merge f66a9554da973ef80498e3f0a6547fa31a7b9872 on remote branch

   * prebuilts/r8/
1e2b56a r8: Update D8 and R8 to 1.6.13-local
efa16a4 Fix d8 and r8-compat-proguard scripts to handle quoted options
63493ac Provide 2GB of heap space to the Java VM when running D8 and R8

   * vendor/qcom/opensource/audio/
18ed1b6 Merge 97376a9080990e1bd2929eb865f691b8e9b7f37e on remote branch

   * vendor/qcom/opensource/data-ipa-cfg-mgr/
a95d12a Merge 98278cbab83c8bc876c7c6f041576de599233fb3 on remote branch

   * vendor/qcom/opensource/interfaces/
cfc0872 Merge b2d3ce3b31cdf6090b88ed7623262af69379b893 on remote branch

====================
     07-09-2019
====================


   * development/
ff5079718 Merge "Snap for 5622519 from 239859423412edda2096927910dd8164e6475865 to pi-platform-release am: 8ef31cb46b" into pie-gsi
6207d9d0c Snap for 5622519 from 239859423412edda2096927910dd8164e6475865 to pi-platform-release am: 8ef31cb46b
8ef31cb46 Snap for 5622519 from 239859423412edda2096927910dd8164e6475865 to pi-platform-release

   * external/icu/
bd4c5fe40 Snap for 5622519 from 81023f4194eeb6e8123445d2441869bf55bf2f87 to pi-platform-release am: 16b3c0277e
b9cd61962 Snap for 5600800 from cf06cc7772c2bbad4d6ce91609dd17050a56cf59 to pi-platform-release am: a63df92ad9
16b3c0277 Snap for 5622519 from 81023f4194eeb6e8123445d2441869bf55bf2f87 to pi-platform-release

   * external/skia/
1193a855ff Merge "Snap for 5622519 from 7b904fb0143c85626198c8b65f9f9ea2de8cc271 to pi-platform-release am: 9d46f09202" into pie-gsi
afe8ba9906 Snap for 5622519 from 7b904fb0143c85626198c8b65f9f9ea2de8cc271 to pi-platform-release am: 9d46f09202
9d46f09202 Snap for 5622519 from 7b904fb0143c85626198c8b65f9f9ea2de8cc271 to pi-platform-release

   * frameworks/av/
377dd121d8 Merge "Snap for 5622519 from f29ab2dbaaf2635f403be82238b18ad3ff673514 to pi-platform-release am: bcb87e5568" into pie-gsi
1997ff037c Snap for 5622519 from f29ab2dbaaf2635f403be82238b18ad3ff673514 to pi-platform-release am: bcb87e5568
6d33ddd453 Merge "Snap for 5600800 from 127949a9f35c23446a2ce4d8821fd7df21a3fa77 to pi-platform-release am: 8a898328aa" into pie-gsi
98bc67e01b Snap for 5600800 from 127949a9f35c23446a2ce4d8821fd7df21a3fa77 to pi-platform-release am: 8a898328aa
bcb87e5568 Snap for 5622519 from f29ab2dbaaf2635f403be82238b18ad3ff673514 to pi-platform-release

   * frameworks/base/
4cf1c0fbbbe Merge "Snap for 5622519 from b869620327dabaebe715a7d8fb3d12cdddd5a221 to pi-platform-release am: 5c3946d093" into pie-gsi
01577783a25 Snap for 5622519 from b869620327dabaebe715a7d8fb3d12cdddd5a221 to pi-platform-release am: 5c3946d093
b1cec28b95d Merge "Snap for 5600800 from b3f4ac23836263a1f7844b12455a81150c92bace to pi-platform-release am: f84f3454c7" into pie-gsi
d8814cdc190 Snap for 5600800 from b3f4ac23836263a1f7844b12455a81150c92bace to pi-platform-release am: f84f3454c7
5c3946d0935 Snap for 5622519 from b869620327dabaebe715a7d8fb3d12cdddd5a221 to pi-platform-release

   * hardware/qcom/power/
2846b24 qcom: power: Stop log spam "QCOM PowerHAL: Failed to acquire lock"

   * packages/apps/CellBroadcastReceiver/
54e2dfb Merge "Snap for 5622519 from 9f6cd249778d11d394692e9ef79840dfe28b9dc8 to pi-platform-release am: cb84ec2751" into pie-gsi
6d13c9a Snap for 5622519 from 9f6cd249778d11d394692e9ef79840dfe28b9dc8 to pi-platform-release am: cb84ec2751
cb84ec2 Snap for 5622519 from 9f6cd249778d11d394692e9ef79840dfe28b9dc8 to pi-platform-release

   * packages/apps/Contacts/
29db2b04d Merge "Snap for 5622519 from 4f49c1c228daab1861c2e0d13dda03b2df2a9582 to pi-platform-release am: 5889de7669" into pie-gsi
c106966d7 Snap for 5622519 from 4f49c1c228daab1861c2e0d13dda03b2df2a9582 to pi-platform-release am: 5889de7669
5889de766 Snap for 5622519 from 4f49c1c228daab1861c2e0d13dda03b2df2a9582 to pi-platform-release

   * packages/apps/DocumentsUI/
0252d26f Snap for 5622519 from 9b6f2643661e4667493debdcccbba3ec518eb963 to pi-platform-release am: 003bac8220
003bac82 Snap for 5622519 from 9b6f2643661e4667493debdcccbba3ec518eb963 to pi-platform-release

   * packages/apps/EmergencyInfo/
5c9a761 Snap for 5622519 from 1f34f131bd37703b5162c65ee4d276eb05248595 to pi-platform-release am: 9a5e31527f
9a5e315 Snap for 5622519 from 1f34f131bd37703b5162c65ee4d276eb05248595 to pi-platform-release

   * packages/apps/Nfc/
bd9db4f5 Merge "Snap for 5622519 from 18ad94ed67b2dfc3dfe59c7d6eb980e7ef1f9914 to pi-platform-release am: f6d7678d7e" into pie-gsi
59960655 Snap for 5622519 from 18ad94ed67b2dfc3dfe59c7d6eb980e7ef1f9914 to pi-platform-release am: f6d7678d7e
f6d7678d Snap for 5622519 from 18ad94ed67b2dfc3dfe59c7d6eb980e7ef1f9914 to pi-platform-release

   * packages/apps/PackageInstaller/
80892d48 Merge "Snap for 5622519 from 73e82477c145d8178180382a5ad2b9f9fa4b8235 to pi-platform-release am: dbd2ae2b63" into pie-gsi
fed0811f Snap for 5622519 from 73e82477c145d8178180382a5ad2b9f9fa4b8235 to pi-platform-release am: dbd2ae2b63
f39dc13e Merge "Snap for 5600800 from d6b752934f71c3c59b6339900f07b204dce0d505 to pi-platform-release am: b5641733bf" into pie-gsi
1ca66ade Snap for 5600800 from d6b752934f71c3c59b6339900f07b204dce0d505 to pi-platform-release am: b5641733bf
dbd2ae2b Snap for 5622519 from 73e82477c145d8178180382a5ad2b9f9fa4b8235 to pi-platform-release

   * packages/apps/Settings/
dabc81c058 Merge "Snap for 5622519 from fd365ae91ebe924197c5f443c889928eb07bd02c to pi-platform-release am: ec58694ae8" into pie-gsi
783d0549dd Snap for 5622519 from fd365ae91ebe924197c5f443c889928eb07bd02c to pi-platform-release am: ec58694ae8
ec58694ae8 Snap for 5622519 from fd365ae91ebe924197c5f443c889928eb07bd02c to pi-platform-release

   * packages/inputmethods/LatinIME/
3f40ccc26 Merge "Snap for 5622519 from e035e3c31904c790e5c3d88a78b98d5566038af3 to pi-platform-release am: 8c6c1e2be6" into pie-gsi
55f5ab770 Snap for 5622519 from e035e3c31904c790e5c3d88a78b98d5566038af3 to pi-platform-release am: 8c6c1e2be6
8c6c1e2be Snap for 5622519 from e035e3c31904c790e5c3d88a78b98d5566038af3 to pi-platform-release

   * packages/providers/MediaProvider/
62abcea Merge "Snap for 5622519 from 3750847861dd817fe5a3ec3d5d7ac0bb6e3d5016 to pi-platform-release am: f5e8f5b0d5" into pie-gsi
6525cbc Snap for 5622519 from 3750847861dd817fe5a3ec3d5d7ac0bb6e3d5016 to pi-platform-release am: f5e8f5b0d5
f5e8f5b Snap for 5622519 from 3750847861dd817fe5a3ec3d5d7ac0bb6e3d5016 to pi-platform-release

   * packages/services/Telecomm/
e0f8071b Snap for 5622519 from b65ecc5a1264c78e2543dc6beade501c4d60b282 to pi-platform-release am: c83df82dbc
c83df82d Snap for 5622519 from b65ecc5a1264c78e2543dc6beade501c4d60b282 to pi-platform-release

   * prebuilts/clang/host/linux-x86/
39dbc541 Update prebuilt Clang to r353983e.

   * system/bt/
4b1d4904a Snap for 5622519 from fef57bda2a3cf2dca83848db5b8e789cb32dac1d to pi-platform-release am: db4e774cab
abff8cd5f Snap for 5600800 from 2d3cdf31bb8d8452380a3398e57e87f88318a274 to pi-platform-release am: 1e2fde1e24
db4e774ca Snap for 5622519 from fef57bda2a3cf2dca83848db5b8e789cb32dac1d to pi-platform-release

   * system/libhwbinder/
4959830 Snap for 5622519 from aa22afd88b4ff0fc467fa57d88ebc87de3021319 to pi-platform-release am: a5a8a516d4
b0c7f46 Snap for 5600800 from 109b4ae7734e85c094c9446bb2f63932dcfa7207 to pi-platform-release am: 592f9f276b
a5a8a51 Snap for 5622519 from aa22afd88b4ff0fc467fa57d88ebc87de3021319 to pi-platform-release

   * system/netd/
76448f5 Snap for 5622519 from 1ba507fb361520149b5683c363b85bf1d1e1fd00 to pi-platform-release am: 02ebe2a46c
6dcdfc8 Snap for 5600800 from 3c3c62e4d9ef34dbb9460fa9cde7945cd6486f5e to pi-platform-release am: f138d4c17e
02ebe2a Snap for 5622519 from 1ba507fb361520149b5683c363b85bf1d1e1fd00 to pi-platform-release

   * system/tools/hidl/
25a76d8 Snap for 5622519 from 71f3191f2c88f9cb4ad9e232d2bdb7b8208c40bf to pi-platform-release am: a5f1137806
607da63 Snap for 5600800 from 8b20a45f29ebb35324b0fba2fc5e0b856047aebb to pi-platform-release am: 1df6c91f83
a5f1137 Snap for 5622519 from 71f3191f2c88f9cb4ad9e232d2bdb7b8208c40bf to pi-platform-release

   * system/vold/
ca19a84 Merge "Snap for 5622519 from 59295fbb94e3a75c3341419aadbc66c560296179 to pi-platform-release am: ec0cb71ca1" into pie-gsi
f2fb54f Snap for 5622519 from 59295fbb94e3a75c3341419aadbc66c560296179 to pi-platform-release am: ec0cb71ca1
ec0cb71 Snap for 5622519 from 59295fbb94e3a75c3341419aadbc66c560296179 to pi-platform-release

====================
     07-08-2019
====================


   * external/icu/
a63df92ad Snap for 5600800 from cf06cc7772c2bbad4d6ce91609dd17050a56cf59 to pi-platform-release

   * frameworks/av/
8a898328aa Snap for 5600800 from 127949a9f35c23446a2ce4d8821fd7df21a3fa77 to pi-platform-release

   * frameworks/base/
f84f3454c7f Snap for 5600800 from b3f4ac23836263a1f7844b12455a81150c92bace to pi-platform-release

   * packages/apps/PackageInstaller/
b5641733 Snap for 5600800 from d6b752934f71c3c59b6339900f07b204dce0d505 to pi-platform-release

   * system/bt/
1e2fde1e2 Snap for 5600800 from 2d3cdf31bb8d8452380a3398e57e87f88318a274 to pi-platform-release

   * system/libhwbinder/
592f9f2 Snap for 5600800 from 109b4ae7734e85c094c9446bb2f63932dcfa7207 to pi-platform-release

   * system/netd/
f138d4c Snap for 5600800 from 3c3c62e4d9ef34dbb9460fa9cde7945cd6486f5e to pi-platform-release

   * system/tools/hidl/
1df6c91 Snap for 5600800 from 8b20a45f29ebb35324b0fba2fc5e0b856047aebb to pi-platform-release

====================
     07-07-2019
====================


====================
     07-06-2019
====================


   * hardware/qcom/fm/
647ae02 Automatic translation import

   * kernel/xiaomi/msm8996/
b10c66ab6149 mbcache2: Speed up cache entry creation
bf2a2cdbf3f0 Makefile: Force ARCH to be arm64
3f40b5396126 dmaengine: Fix memory leak in dma_async_device_register
b1185ab52571 msm: kgsl: Avoid dynamically allocating small command buffers
2c2058cbf59a ext4 crypto: Use a larger on-stack file name buffer

====================
     07-05-2019
====================


   * kernel/xiaomi/msm8996/
5d3ae62631f3 Update defconfigs
3aa18820db4a Let Google Camera work in the background
034e25227a10 proc: Don't let Google Camera and Settings run in the background
a5fd062f1fbd selinux: Avoid dynamic memory allocation for small context buffers
ef32d8aac4c9 soc: qcom: smp2p: Fix compile errors when testing is disabled

   * vendor/havoc/
fa356e62 update Lawnchair to alpha-2268

