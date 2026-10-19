# live · 7.5.0_1589372live

| | |
|---|---|
| Build date | 2024-02-07 19:38 UTC |
| CDN version | `7.5.0_1589372live-1707334716` |
| Key | `7.5.0_live` |
| Compared with | [7.4.0_1576463live](../7.4.0_1576463live/CHANGES.md) (2024-01-30 15:18 UTC) |

## Summary

**0** added · **2** modified · **0** removed · 1 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.loading
+ $.enableConsoleSuspendSave: true
+ $.enableLimitRegressionEvents: true
+ $.enableLobbyLeaveSave: false
+ $.hangTimes
- $.analytics.performanceSamplingLocalisation
- $.analytics.performanceSamplingRate: 3600
+ $.analytics.performanceSamplingRate: 300
- $.dlc.dlcAdditionalInfo[0].availableStartDate: "2024-01-08T11:00:00"
+ $.dlc.dlcAdditionalInfo[0].isShownInGameStore: false
- $.dlc.dlcAdditionalInfo[0].dlcId: "HeritagePack1"
+ $.dlc.dlcAdditionalInfo[0].dlcId: "development"
- $.dlc.dlcAdditionalInfo[1].availableStartDate: "2024-01-08T11:00:00"
+ $.dlc.dlcAdditionalInfo[1].isShownInGameStore: false
- $.dlc.dlcAdditionalInfo[1].dlcId: "HeritagePack2"
+ $.dlc.dlcAdditionalInfo[1].dlcId: "80suitcase"
- $.dlc.dlcAdditionalInfo[2].availableStartDate: "2024-01-08T11:00:00"
+ $.dlc.dlcAdditionalInfo[2].isShownInGameStore: false
- $.dlc.dlcAdditionalInfo[2].dlcId: "HeritagePack3"
+ $.dlc.dlcAdditionalInfo[2].dlcId: "bloodletting"
- $.dlc.dlcAdditionalInfo[3].availableEndDate: "2024-01-08T11:00:00"
- $.dlc.dlcAdditionalInfo[3].availableStartDate: "2020-01-01T01:00:00"
+ $.dlc.dlcAdditionalInfo[3].isShownInGameStore: false
- $.dlc.dlcAdditionalInfo[3].dlcId: "Guam"
+ $.dlc.dlcAdditionalInfo[3].dlcId: "bloodstainedSack"
- $.dlc.dlcAdditionalInfo[4].availableEndDate: "2024-01-08T11:00:00"
- $.dlc.dlcAdditionalInfo[4].availableStartDate: "2020-01-01T01:00:00"
+ $.dlc.dlcAdditionalInfo[4].isShownInGameStore: false
- $.dlc.dlcAdditionalInfo[4].dlcId: "Haiti"
+ $.dlc.dlcAdditionalInfo[4].dlcId: "charityChest"
+ $.dlc.dlcAdditionalInfo[5]
+ $.dlc.dlcAdditionalInfo[6]
+ $.dlc.dlcAdditionalInfo[7]
+ $.dlc.dlcAdditionalInfo[8]
+ $.dlc.dlcAdditionalInfo[9]
+ $.dlc.dlcAdditionalInfo[10]
+ $.dlc.dlcAdditionalInfo[11]
+ $.dlc.dlcAdditionalInfo[12]
+ $.dlc.dlcAdditionalInfo[13]
+ $.dlc.dlcAdditionalInfo[14]
+ $.dlc.dlcAdditionalInfo[15]
+ $.dlc.dlcAdditionalInfo[16]
+ $.dlc.dlcAdditionalInfo[17]
+ $.dlc.dlcAdditionalInfo[18]
+ $.dlc.dlcAdditionalInfo[19]
+ $.dlc.dlcAdditionalInfo[20]
+ $.dlc.dlcAdditionalInfo[21]
+ $.dlc.dlcAdditionalInfo[22]
+ $.dlc.dlcAdditionalInfo[23]
+ $.dlc.dlcAdditionalInfo[24]
+ $.dlc.dlcAdditionalInfo[25]
+ $.dlc.dlcAdditionalInfo[26]
+ $.dlc.dlcAdditionalInfo[27]
+ $.dlc.dlcAdditionalInfo[28]
+ $.dlc.dlcAdditionalInfo[29]
+ $.dlc.dlcAdditionalInfo[30]
+ $.dlc.dlcAdditionalInfo[31]
+ $.dlc.dlcAdditionalInfo[32]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
+ $.entries[0].downloadStrategy: "preferPackaged"
- $.entries[0].contentVersion: "48ef11165dfa82328c8f3a711641dd73f99b82c2"
+ $.entries[0].contentVersion: "071415a9ce4baff98042e5a934578bc760092b7c"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_ECK_small.Banner_ECK_small"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_NOV8.Banner_NOV8"
- $.entries[0].uri: "images/Banner_ECK_small.png"
+ $.entries[0].uri: "images/Banner_NOV8.png"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[1].contentVersion: "2e9db2457161cc0fbce43c95b16a65d272f5fc92"
+ $.entries[1].contentVersion: "24c8d1a79fded41359e441bfcab1c924e20ce419"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_ECK.Banner_ECK"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN13.Banner_VEN13"
- $.entries[1].uri: "images/Banner_ECK.png"
+ $.entries[1].uri: "images/Banner_VEN13.png"
+ $.entries[2].downloadStrategy: "preferPackaged"
- $.entries[2].contentVersion: "990689504b05f2db27efc32d978a1151618d70a2"
+ $.entries[2].contentVersion: "49a95ec44a3cc6e882e45d3dbe80d03c458e2fb7"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_DLC_Chapter_16_Small.Banner_DLC_Chapter_16_Small"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_NOV14.Banner_NOV14"
- $.entries[2].uri: "images/Banner_DLC_Chapter_16_Small.png"
+ $.entries[2].uri: "images/Banner_NOV14.png"
+ $.entries[3].downloadStrategy: "preferPackaged"
- $.entries[3].contentVersion: "245cfdb74e82658a9379b9b90fc1f95c2c934ff5"
+ $.entries[3].contentVersion: "db1b4a3f34e8ac868f82232b2fda1640b3953b53"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN12.Banner_VEN12"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN8.Banner_VEN8"
- $.entries[3].uri: "images/Banner_VEN12.png"
+ $.entries[3].uri: "images/Banner_VEN8.png"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[4].contentVersion: "071415a9ce4baff98042e5a934578bc760092b7c"
+ $.entries[4].contentVersion: "1ffd09c9760baa63c2bbe8e475460e8bdead520b"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_NOV8.Banner_NOV8"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XCY.storeBanner__XCY"
- $.entries[4].uri: "images/Banner_NOV8.png"
+ $.entries[4].uri: "images/storeBanner__XCY.png"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].contentVersion: "24c8d1a79fded41359e441bfcab1c924e20ce419"
+ $.entries[5].contentVersion: "d0f2fabd61cff6c5ede3d18efd1f435e8053c783"
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN13.Banner_VEN13"
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XFJ.storeBanner__XFJ"
- $.entries[5].uri: "images/Banner_VEN13.png"
+ $.entries[5].uri: "images/storeBanner__XFJ.png"
+ $.entries[6].downloadStrategy: "preferPackaged"
- $.entries[6].contentVersion: "49a95ec44a3cc6e882e45d3dbe80d03c458e2fb7"
+ $.entries[6].contentVersion: "57a4d1a444ef4ce5705b593b7d377f5fa2296968"
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_NOV14.Banner_NOV14"
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XOD.storeBanner__XOD"
- $.entries[6].uri: "images/Banner_NOV14.png"
+ $.entries[6].uri: "images/storeBanner__XOD.png"
+ $.entries[7].downloadStrategy: "preferPackaged"
- $.entries[7].contentVersion: "db1b4a3f34e8ac868f82232b2fda1640b3953b53"
+ $.entries[7].contentVersion: "398ff39d6b22ad4c66eccdc3d651b2fd23419c6b"
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN8.Banner_VEN8"
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XSA.storeBanner__XSA"
- $.entries[7].uri: "images/Banner_VEN8.png"
+ $.entries[7].uri: "images/storeBanner__XSA.png"
+ $.entries[8].downloadStrategy: "preferPackaged"
- $.entries[8].contentVersion: "1ffd09c9760baa63c2bbe8e475460e8bdead520b"
+ $.entries[8].contentVersion: "990689504b05f2db27efc32d978a1151618d70a2"
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XCY.storeBanner__XCY"
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_DLC_Chapter_16_Small.Banner_DLC_Chapter_16_Small"
- $.entries[8].uri: "images/storeBanner__XCY.png"
+ $.entries[8].uri: "images/Banner_DLC_Chapter_16_Small.png"
+ $.entries[9].downloadStrategy: "preferPackaged"
- $.entries[9].contentVersion: "d0f2fabd61cff6c5ede3d18efd1f435e8053c783"
+ $.entries[9].contentVersion: "245cfdb74e82658a9379b9b90fc1f95c2c934ff5"
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XFJ.storeBanner__XFJ"
+ $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN12.Banner_VEN12"
- $.entries[9].uri: "images/storeBanner__XFJ.png"
+ $.entries[9].uri: "images/Banner_VEN12.png"
+ $.entries[10].downloadStrategy: "preferPackaged"
- $.entries[10].contentVersion: "57a4d1a444ef4ce5705b593b7d377f5fa2296968"
+ $.entries[10].contentVersion: "48ef11165dfa82328c8f3a711641dd73f99b82c2"
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XOD.storeBanner__XOD"
+ $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_ECK_small.Banner_ECK_small"
- $.entries[10].uri: "images/storeBanner__XOD.png"
+ $.entries[10].uri: "images/Banner_ECK_small.png"
+ $.entries[11].downloadStrategy: "preferPackaged"
- $.entries[11].contentVersion: "398ff39d6b22ad4c66eccdc3d651b2fd23419c6b"
+ $.entries[11].contentVersion: "2e9db2457161cc0fbce43c95b16a65d272f5fc92"
- $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/storeBanner__XSA.storeBanner__XSA"
+ $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_ECK.Banner_ECK"
- $.entries[11].uri: "images/storeBanner__XSA.png"
+ $.entries[11].uri: "images/Banner_ECK.png"
+ $.entries[12].downloadStrategy: "preferPackaged"
- $.entries[12].contentVersion: "f3a3e216465dbd9de93edfce5ab0ebfb7b7f8932"
+ $.entries[12].contentVersion: "82e8459095c041b65af5e284be0449d8bd3b99e8"
- $.entries[12].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_PLU5.Banner_PLU5"
+ $.entries[12].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_LIB8.Banner_LIB8"
- $.entries[12].uri: "images/Banner_PLU5.png"
+ $.entries[12].uri: "images/Banner_LIB8.png"
+ $.entries[13].downloadStrategy: "preferPackaged"
- $.entries[13].contentVersion: "094dd3381f76b3426f42df764038084768592bc0"
+ $.entries[13].contentVersion: "8ab514d068df0d46c4658026c4f9199bb6f23f0f"
- $.entries[13].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_PLU6.Banner_PLU6"
+ $.entries[13].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_LIB9.Banner_LIB9"
- $.entries[13].uri: "images/Banner_PLU6.png"
+ $.entries[13].uri: "images/Banner_LIB9.png"
+ $.entries[14].downloadStrategy: "preferPackaged"
- $.entries[14].contentVersion: "24c8d1a79fded41359e441bfcab1c924e20ce419"
+ $.entries[14].contentVersion: "e6ad8d3c4ba1d5141e1ce1ef8f0e7bba7a0bac91"
- $.entries[14].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN13.Banner_VEN13"
+ $.entries[14].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_MDSA.Banner_MDSA"
- $.entries[14].uri: "images/Banner_VEN13.png"
+ $.entries[14].uri: "images/Banner_MDSA.png"
+ $.entries[15].downloadStrategy: "preferPackaged"
- $.entries[15].contentVersion: "c862a5fbbf492919d1d6f0ec4a4185bd478ea362"
+ $.entries[15].contentVersion: "64f6d1da54945331b3d9418b46b0a3f7e3207b14"
- $.entries[15].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN10.Banner_VEN10"
+ $.entries[15].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_BB_RCJKNM.Banner_BB_RCJKNM"
- $.entries[15].uri: "images/Banner_VEN10.png"
+ $.entries[15].uri: "images/Banner_BB_RCJKNM.png"
+ $.entries[16].downloadStrategy: "preferPackaged"
- $.entries[16].contentVersion: "abcd7fd62132a25f55c842b0f8609dfefff77bd9"
+ $.entries[16].contentVersion: "b599e1ca3621e0beba356b7ce1998df8e4f7ea44"
- $.entries[16].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_VEN11.Banner_VEN11"
+ $.entries[16].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/Banner_UMB9.Banner_UMB9"
- $.entries[16].uri: "images/Banner_VEN11.png"
+ $.entries[16].uri: "images/Banner_UMB9.png"
+ $.entries[17]
+ $.entries[18]
+ $.entries[19]
+ $.entries[20]
+ $.entries[21]
+ $.entries[22]
+ $.entries[23]
+ $.entries[24]
+ $.entries[25]
+ $.entries[26]
+ $.entries[27]
+ $.entries[28]
+ $.entries[29]
+ $.entries[30]
+ $.entries[31]
+ $.entries[32]
+ $.entries[33]
+ $.entries[34]
+ $.entries[35]
+ $.entries[36]
+ $.entries[37]
+ $.entries[38]
+ $.entries[39]
+ $.entries[40]
+ $.entries[41]
+ $.entries[42]
+ $.entries[43]
+ $.entries[44]
+ $.entries[45]
+ $.entries[46]
+ $.entries[47]
+ $.entries[48]
+ $.entries[49]
+ $.entries[50]
+ $.entries[51]
+ $.entries[52]
+ $.entries[53]
+ $.entries[54]
+ $.entries[55]
+ $.entries[56]
+ $.entries[57]
+ $.entries[58]
+ $.entries[59]
+ $.entries[60]
+ $.entries[61]
+ $.entries[62]
+ $.entries[63]
+ $.entries[64]
+ $.entries[65]
+ $.entries[66]
+ $.entries[67]
+ $.entries[68]
+ $.entries[69]
+ $.entries[70]
+ $.entries[71]
+ $.entries[72]
+ $.entries[73]
+ $.entries[74]
+ $.entries[75]
+ $.entries[76]
+ $.entries[77]
+ $.entries[78]
+ $.entries[79]
+ $.entries[80]
+ $.entries[81]
```

## Could not download

- `images/Banner_BB_RCJKNM.png (HTTP 404)`
- `images/Banner_DLC_Chapter_16_Small.png (HTTP 404)`
- `images/Banner_ECK.png (HTTP 404)`
- `images/Banner_ECK_small.png (HTTP 404)`
- `images/Banner_GAS.png (HTTP 404)`
- `images/Banner_HRS1.png (HTTP 404)`
- `images/Banner_IRD.png (HTTP 404)`
- `images/Banner_IRF.png (HTTP 404)`
- `images/Banner_JUP4.png (HTTP 404)`
- `images/Banner_JUP7.png (HTTP 404)`
- `images/Banner_KEP3.png (HTTP 404)`
- `images/Banner_LIB8.png (HTTP 404)`
- `images/Banner_LIB9.png (HTTP 404)`
- `images/Banner_LPF.png (HTTP 404)`
- `images/Banner_MDSA.png (HTTP 404)`
- `images/Banner_MET5.png (HTTP 404)`
- `images/Banner_MET6.png (HTTP 404)`
- `images/Banner_NOV13.png (HTTP 404)`
- `images/Banner_NOV14.png (HTTP 404)`
- `images/Banner_NOV8.png (HTTP 404)`
- `images/Banner_NTYJ.png (HTTP 404)`
- `images/Banner_ORI1_small.png (HTTP 404)`
- `images/Banner_ORI2.png (HTTP 404)`
- `images/Banner_PLMC.png (HTTP 404)`
- `images/Banner_PLU5.png (HTTP 404)`
- `images/Banner_PLU6.png (HTTP 404)`
- `images/Banner_PLU8.png (HTTP 404)`
- `images/Banner_QUA12.png (HTTP 404)`
- `images/Banner_QUA1_small.png (HTTP 404)`
- `images/Banner_QUA8.png (HTTP 404)`
- `images/Banner_QUA9.png (HTTP 404)`
- `images/Banner_ROC6.png (HTTP 404)`
- `images/Banner_ROC8.png (HTTP 404)`
- `images/Banner_ROC9.png (HTTP 404)`
- `images/Banner_SAT11.png (HTTP 404)`
- `images/Banner_SAT12.png (HTTP 404)`
- `images/Banner_SAT13.png (HTTP 404)`
- `images/Banner_SAT14.png (HTTP 404)`
- `images/Banner_SAT15.png (HTTP 404)`
- `images/Banner_SAT1_small.png (HTTP 404)`
- `images/Banner_TIT5.png (HTTP 404)`
- `images/Banner_TIT7.png (HTTP 404)`
- `images/Banner_UMB10.png (HTTP 404)`
- `images/Banner_UMB11.png (HTTP 404)`
- `images/Banner_UMB1_small.png (HTTP 404)`
- `images/Banner_UMB8.png (HTTP 404)`
- `images/Banner_UMB9.png (HTTP 404)`
- `images/Banner_USWEAT.png (HTTP 404)`
- `images/Banner_VAULTHDH.png (HTTP 404)`
- `images/Banner_VEN10.png (HTTP 404)`
- `images/Banner_VEN11.png (HTTP 404)`
- `images/Banner_VEN12.png (HTTP 404)`
- `images/Banner_VEN13.png (HTTP 404)`
- `images/Banner_VEN1_small.png (HTTP 404)`
- `images/Banner_VEN8.png (HTTP 404)`
- `images/Banner_VEN9.png (HTTP 404)`
- `images/Banner_WFMC.png (HTTP 404)`
- `images/Banner_WMH10.png (HTTP 404)`
- `images/Banner_WMH11.png (HTTP 404)`
- `images/Banner_WMH1_small.png (HTTP 404)`
- `images/Banner_WMH8.png (HTTP 404)`
- `images/Banner_WMH9.png (HTTP 404)`
- `images/Banner_XRAY13.png (HTTP 404)`
- `images/Banner_XRAY7.png (HTTP 404)`
- `images/Banner_XRAY8.png (HTTP 404)`
- `images/Banner_XRAY9.png (HTTP 404)`
- `images/K29_TheMasterMind_Portrait.png (HTTP 404)`
- `images/K30_TheKnight_Portrait.png (HTTP 404)`
- `images/K31_TheSkullMerchant_Portrait.png (HTTP 404)`
- `images/K32_TheSingularity_Portrait.png (HTTP 404)`
- `images/K33_TheXenomorph_Portrait.png (HTTP 404)`
- `images/S35_ThalitaLyra_Portrait.png (HTTP 404)`
- `images/S36_RenatoLyra_Portrait.png (HTTP 404)`
- `images/S37_GabrielSoma_Portrait.png (HTTP 404)`
- `images/S38_NicolasCage_Portrait.png (HTTP 404)`
- `images/S39_EllenRipley_Portrait.png (HTTP 404)`
- `images/storeBanner_HCC.png (HTTP 404)`
- `images/storeBanner__XCY.png (HTTP 404)`
- `images/storeBanner__XFJ.png (HTTP 404)`
- `images/storeBanner__XOD.png (HTTP 404)`
- `images/storeBanner__XSA.png (HTTP 404)`

