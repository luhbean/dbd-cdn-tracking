# live · 9.4.0_3085062live

| | |
|---|---|
| Build date | 2026-02-10 13:09 UTC |
| CDN version | `9.4.0_3085062live-1770728957` |
| Key | `9.4.0_live` |
| Compared with | [9.4.2_3086453live](../9.4.2_3086453live/CHANGES.md) (2026-02-09 14:26 UTC) |

## Summary

**6** added · **9** modified · **0** removed · 202 unchanged

## New or updated images

<a href="images/T_UI_ChapterBundle_StrangerThings_Chapter2.png"><img src="images/T_UI_ChapterBundle_StrangerThings_Chapter2.png" alt="T_UI_ChapterBundle_StrangerThings_Chapter2.png" width="240"></a>
<a href="images/T_UI_CollectionBanner_StrangerThings_Chapter2.png"><img src="images/T_UI_CollectionBanner_StrangerThings_Chapter2.png" alt="T_UI_CollectionBanner_StrangerThings_Chapter2.png" width="240"></a>
<a href="images/T_UI_SpecialPack_Rift4.png"><img src="images/T_UI_SpecialPack_Rift4.png" alt="T_UI_SpecialPack_Rift4.png" width="240"></a>
<a href="images/T_UI_SpecialPack_StrangerThings_Chapter2.png"><img src="images/T_UI_SpecialPack_StrangerThings_Chapter2.png" alt="T_UI_SpecialPack_StrangerThings_Chapter2.png" width="240"></a>
<a href="images/T_UI_icon_Event_FogCarnival.png"><img src="images/T_UI_icon_Event_FogCarnival.png" alt="T_UI_icon_Event_FogCarnival.png" width="240"></a>
<a href="images/T_UI_icon_Event_LunarYear.png"><img src="images/T_UI_icon_Event_LunarYear.png" alt="T_UI_icon_Event_LunarYear.png" width="240"></a>

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.DSProviderOnShutdownNotificationDelay: 90.0
+ $.DSProviderOnShutdownNotificationDelay: 15.0
- $.enableAlwaysSendCrashWithUI: true
+ $.enableAlwaysSendCrashWithUI: false
```

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
- $.TOME23.vignettes[id=TOME23_02].entries[9]
- $.TOME23.vignettes[id=TOME23_03].entries[0]
- $.TOME23.vignettes[id=TOME23_03].entries[1]
- $.TOME23.vignettes[id=TOME23_03].entries[2]
- $.TOME23.vignettes[id=TOME23_03].entries[3]
- $.TOME23.vignettes[id=TOME23_03].entries[4]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=K35_Head018]
- $[id=POU_BDG_15]
- $[id=POU_BDG_16]
- $[id=POU_BDG_17]
- $[id=POU_BDG_18]
- $[id=POU_BNR_17]
- $[id=PTN_016]
- $[id=SUS_017]
- $[id=Alice_In_Wonderland_Bundle]
- $[id=SilentHill_Omelet_Bundle]
+ $[id=K20].eventCostList
+ $[id=K20].metaData.temporaryDiscounts
+ $[id=S22].eventCostList
+ $[id=S22].metaData.temporaryDiscounts
+ $[id=S22_Torso01_01].eventCostList[0]
+ $[id=S22_Torso01_01].metaData.temporaryDiscounts
+ $[id=S22_Torso01_02].eventCostList[0]
+ $[id=S22_Torso01_02].metaData.temporaryDiscounts
+ $[id=S22_Torso01_03].eventCostList[0]
+ $[id=S22_Torso01_03].metaData.temporaryDiscounts
+ $[id=S22_Torso01_04].eventCostList[0]
+ $[id=S22_Torso01_04].metaData.temporaryDiscounts
+ $[id=S22_Torso01_05].eventCostList[0]
+ $[id=S22_Torso01_05].metaData.temporaryDiscounts
+ $[id=S22_Torso01_06].eventCostList[0]
+ $[id=S22_Torso01_06].metaData.temporaryDiscounts
- $[id=BO_outfit007].metaData.temporaryDiscounts
- $[id=CM_outfit_015].metaData.temporaryDiscounts
- $[id=FM_outfit_010].metaData.temporaryDiscounts
+ $[id=FM_outfit_022].metaData.temporaryDiscounts
- $[id=GK_outfit_010].metaData.temporaryDiscounts
- $[id=GK_outfit_019].metaData.temporaryDiscounts
+ $[id=K20_outfit_006].metaData.temporaryDiscounts
+ $[id=K20_outfit_007].metaData.temporaryDiscounts
+ $[id=K20_outfit_008].metaData.temporaryDiscounts
+ $[id=K20_outfit_009].metaData.temporaryDiscounts
- $[id=K26_outfit_010].metaData.temporaryDiscounts
+ $[id=KK_outfit_016].metaData.temporaryDiscounts
+ $[id=KK_outfit_016_01].metaData.temporaryDiscounts
+ $[id=KK_outfit_016_02].metaData.temporaryDiscounts
+ $[id=KK_outfit_016_03].metaData.temporaryDiscounts
- $[id=KK_outfit_017].metaData.temporaryDiscounts
- $[id=MK_outfit_011].metaData.temporaryDiscounts
+ $[id=S22_outfit_006].metaData.temporaryDiscounts
+ $[id=S22_outfit_007].metaData.temporaryDiscounts
+ $[id=S22_outfit_008].metaData.temporaryDiscounts
+ $[id=S22_outfit_010].metaData.temporaryDiscounts
+ $[id=S22_outfit_011].metaData.temporaryDiscounts
+ $[id=S22_outfit_012].metaData.temporaryDiscounts
+ $[id=S22_outfit_02].metaData.temporaryDiscounts
+ $[id=S22_outfit_02_01].metaData.temporaryDiscounts
- $[id=S24_outfit_012].metaData.temporaryDiscounts
- $[id=S25_outfit_021].metaData.temporaryDiscounts
- $[id=SwedenSurvivor_outfit_018].metaData.temporaryDiscounts
- $[id=TorturedSoulsBundle].metaData.sortOrder: 1100
+ $[id=TorturedSoulsBundle].metaData.sortOrder: 600
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.ChocolateBoxOmeletSet.challengeList[0].endDate: "2026-01-27T16:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[0].endDate: "2026-01-27T14:00:00"
- $.ChocolateBoxOmeletSet.challengeList[1].endDate: "2026-01-27T16:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[1].endDate: "2026-01-27T14:00:00"
- $.ChocolateBoxOmeletSet.challengeList[2].endDate: "2026-01-27T16:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[2].endDate: "2026-01-27T14:00:00"
- $.ChocolateBoxOmeletSet.challengeList[3].endDate: "2026-01-27T16:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[3].endDate: "2026-01-27T14:00:00"
- $.ChocolateBoxOmeletSet.endDate: "2026-01-27T16:00:00"
+ $.ChocolateBoxOmeletSet.endDate: "2026-01-27T14:00:00"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[0].contentVersion: "22f4426df683b6384ac0d61b71e28e3880e1c7ec"
- $.entries[0].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_Rift4.T_UI_SpecialPack_Rift4"
- $.entries[0].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_Rift4.png"
- $.entries[1].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[2].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[3].contentVersion: "71da739acc05234bcde2dc3f02f5b684af477eba"
+ $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_EldritchNightmares.T_UI_CollectionBanner_EldritchNightmares"
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[3].uri: "images/T_UI_CollectionBanner_EldritchNightmares.png"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[4].contentVersion: "9555817f05628fe8332fe67c508a029dce563092"
+ $.entries[4].contentVersion: "ecea0cbb601208988fb7e266e6339430fbd26066"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_EldritchNightmares.T_UI_SpecialPack_EldritchNightmares"
+ $.entries[4].packagedPath: "/DBDUICore/Assets/Common/Event/T_UI_icon_Event_FogCarnival.T_UI_icon_Event_FogCarnival"
- $.entries[4].uri: "images/T_UI_SpecialPack_EldritchNightmares.png"
+ $.entries[4].uri: "images/T_UI_icon_Event_FogCarnival.png"
- $.entries[5].contentVersion: "84fb38c2c918b402b996ddf9911c599300b41eba"
+ $.entries[5].contentVersion: "ba5908d103a3c970227c15e80f8c1cedd3ed9bec"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_ModernTales.T_UI_SpecialPack_ModernTales"
+ $.entries[5].packagedPath: "/DBDUICore/Assets/Common/Event/T_UI_icon_Event_LunarYear.T_UI_icon_Event_LunarYear"
- $.entries[5].uri: "images/T_UI_SpecialPack_ModernTales.png"
+ $.entries[5].uri: "images/T_UI_icon_Event_LunarYear.png"
- $.entries[6].contentVersion: "5114ba5ec9ed06e5bd9946635c0d50e0883a4341"
+ $.entries[6].contentVersion: "36c04d7010039e4bbed2a8374fce6f33020d71f9"
- $.entries[6].downloadStrategy: "preferRemote"
+ $.entries[6].downloadStrategy: "preferPackaged"
- $.entries[6].enableChecksum: true
+ $.entries[6].enableChecksum: false
- $.entries[6].packagedPath: ""
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_StrangerThings_Chapter2.T_UI_ChapterBundle_StrangerThings_Chapter2"
- $.entries[6].schema: "s3ver://"
+ $.entries[6].schema: "s3verbin://"
- $.entries[6].uri: "catalog.json"
+ $.entries[6].uri: "images/T_UI_ChapterBundle_StrangerThings_Chapter2.png"
- $.entries[7].contentVersion: "8901b96443a3bdf0e321f2d21a08066573a8ecfa"
+ $.entries[7].contentVersion: "71da739acc05234bcde2dc3f02f5b684af477eba"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_EldritchNightmares.T_UI_CollectionBanner_EldritchNightmares"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "bonusPointEventsContent.json"
+ $.entries[7].uri: "images/T_UI_CollectionBanner_EldritchNightmares.png"
- $.entries[8].contentVersion: "000828fd3685b8f4d440884f8e72171f7a64cc2b"
+ $.entries[8].contentVersion: "9555817f05628fe8332fe67c508a029dce563092"
- $.entries[8].enableChecksum: true
+ $.entries[8].enableChecksum: false
- $.entries[8].packagedPath: ""
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_EldritchNightmares.T_UI_SpecialPack_EldritchNightmares"
- $.entries[8].schema: "s3ver://"
+ $.entries[8].schema: "s3verbin://"
- $.entries[8].uri: "freetoplay/NA/event.json"
+ $.entries[8].uri: "images/T_UI_SpecialPack_EldritchNightmares.png"
- $.entries[9].contentVersion: "000828fd3685b8f4d440884f8e72171f7a64cc2b"
+ $.entries[9].contentVersion: "84fb38c2c918b402b996ddf9911c599300b41eba"
- $.entries[9].enableChecksum: true
+ $.entries[9].enableChecksum: false
- $.entries[9].packagedPath: ""
+ $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_ModernTales.T_UI_SpecialPack_ModernTales"
- $.entries[9].schema: "s3ver://"
+ $.entries[9].schema: "s3verbin://"
- $.entries[9].uri: "freetoplay/EU/event.json"
+ $.entries[9].uri: "images/T_UI_SpecialPack_ModernTales.png"
- $.entries[10].contentVersion: "5b63cfa56ee5d810bc1c53103a2d883fe33a868f"
+ $.entries[10].contentVersion: "f8b2414afc2858c35fed794667b3ba6f27a3e7a0"
- $.entries[10].downloadStrategy: "preferRemote"
+ $.entries[10].downloadStrategy: "preferPackaged"
- $.entries[10].enableChecksum: true
+ $.entries[10].enableChecksum: false
- $.entries[10].packagedPath: ""
+ $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_StrangerThings_Chapter2.T_UI_CollectionBanner_StrangerThings_Chapter2"
- $.entries[10].schema: "s3ver://"
+ $.entries[10].schema: "s3verbin://"
- $.entries[10].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[10].uri: "images/T_UI_CollectionBanner_StrangerThings_Chapter2.png"
- $.entries[11].contentVersion: "ef5cc41868c7170824aa35366b9b51ebdd535b6f"
+ $.entries[11].contentVersion: "12010aea83ad4e1ee56c50df0da8cd85a85498a2"
- $.entries[11].downloadStrategy: "preferRemote"
+ $.entries[11].downloadStrategy: "preferPackaged"
- $.entries[11].enableChecksum: true
+ $.entries[11].enableChecksum: false
- $.entries[11].packagedPath: ""
+ $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/Poutine/T_UI_SpecialPack_StrangerThings_Chapter2.T_UI_SpecialPack_StrangerThings_Chapter2"
- $.entries[11].schema: "s3ver://"
+ $.entries[11].schema: "s3verbin://"
- $.entries[11].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[11].uri: "images/T_UI_SpecialPack_StrangerThings_Chapter2.png"
- $.entries[12].contentVersion: "a7b22f6d2e09c54ef9d24f19a51881d5d607689c"
+ $.entries[12].contentVersion: "5e59003383435a2fe4dd68e7cd60ab66bb55d1b1"
- $.entries[12].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[12].uri: "catalog.json"
- $.entries[13].contentVersion: "13f9310ce97f55acad0027c557679002e4322f1f"
+ $.entries[13].contentVersion: "0688a6020b52e6bd9500b266ac4b4b6baa60860d"
- $.entries[13].uri: "archiveQuests/CalamariV1.json"
+ $.entries[13].uri: "bonusPointEventsContent.json"
- $.entries[14].contentVersion: "c875221ba5ff0ca25f102a774a3bf5475decea21"
+ $.entries[14].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
- $.entries[14].uri: "archiveQuests/CalamariV2.json"
+ $.entries[14].uri: "freetoplay/NA/event.json"
- $.entries[15].contentVersion: "805d59e5939fb041072d1e47890ded6d8ed5263d"
+ $.entries[15].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
- $.entries[15].uri: "archiveQuests/CalamariV3.json"
+ $.entries[15].uri: "freetoplay/EU/event.json"
- $.entries[16].contentVersion: "e97f6a65466e7b57ca7210ba6196584ab9f7276e"
+ $.entries[16].contentVersion: "dd527570e43d5227bc28afe72fb1f78e53ac6822"
- $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[16].uri: "archiveQuests/Anniversary2022.json"
- $.entries[17].contentVersion: "77ca18ec725c10cf60b5c94b67a6e6851bdd27d3"
+ $.entries[17].contentVersion: "52fc655e6b41b211e455230a518f9846c8b5286a"
- $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[17].uri: "archiveQuests/Anniversary2023.json"
- $.entries[18].contentVersion: "45bca9c5cae2d60df67959a8cbc4c9aa3ccaeda1"
+ $.entries[18].contentVersion: "946926ad6e5fc8348d1f1132ac7b59cc676cff14"
- $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[18].uri: "archiveQuests/Anniversary2024.json"
- $.entries[19].contentVersion: "593bd4eab6f2a40c403a6d2de673ba1102ed0070"
+ $.entries[19].contentVersion: "44a5c8ea54340fdfc9b01597243b454a8622e029"
- $.entries[19].uri: "archiveQuests/FireflyV1.json"
+ $.entries[19].uri: "archiveQuests/CalamariV1.json"
- $.entries[20].contentVersion: "c3d34566e029285f00bb599f7ca5e7fb4e2dabd6"
+ $.entries[20].contentVersion: "671675edb2bebab5f35c2e4b6b8e5fa78882ee92"
- $.entries[20].uri: "archiveQuests/Halloween2021.json"
+ $.entries[20].uri: "archiveQuests/CalamariV2.json"
- $.entries[21].contentVersion: "02b2231b6cf62e21e0a796ad2b1455c03e6ca652"
+ $.entries[21].contentVersion: "c36008b30af60617d7038322e37ad3f3cd2754e5"
- $.entries[21].uri: "archiveQuests/Halloween2022.json"
+ $.entries[21].uri: "archiveQuests/CalamariV3.json"
- $.entries[22].contentVersion: "8d0602f440d4445e898af4ad2564052e3595c166"
+ $.entries[22].contentVersion: "680a0cf92894220d6b78184aef473d2da4c76013"
- $.entries[22].uri: "archiveQuests/Halloween2023.json"
+ $.entries[22].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[23].contentVersion: "8f50aa15ca692c513921db7797b91cbd580860ee"
+ $.entries[23].contentVersion: "eae70968d8423a3a0f61227e8b7da194f8856be1"
- $.entries[23].uri: "archiveQuests/Halloween2024.json"
+ $.entries[23].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[24].contentVersion: "8ec46d7612aef925cab0e1453e3843f071f41273"
+ $.entries[24].contentVersion: "5210f96a51547ac1be938e0651440a5c5569ef3a"
- $.entries[24].uri: "archiveQuests/Spring2024.json"
+ $.entries[24].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[25].contentVersion: "ccb0021819a326564876ddf6ad1ab20e215abcdd"
+ $.entries[25].contentVersion: "3de6169053b9db24bf1f8464a61002e16a417945"
- $.entries[25].uri: "archiveQuests/Spring2025.json"
+ $.entries[25].uri: "archiveQuests/FireflyV1.json"
- $.entries[26].contentVersion: "cc01d41b339c81326b8a275c0af5c74309f9ddfe"
+ $.entries[26].contentVersion: "69fe782985a5376bac4f588fac10e1f567cbeca4"
- $.entries[26].uri: "archiveQuests/Summer2023.json"
+ $.entries[26].uri: "archiveQuests/Halloween2021.json"
- $.entries[27].contentVersion: "b88bcb8fe7628e26aed2981cc6d0ead10a01ba0c"
+ $.entries[27].contentVersion: "3b38b442968cdb458f8afd787c8e688df454f3ff"
- $.entries[27].uri: "archiveQuests/Tome01.json"
+ $.entries[27].uri: "archiveQuests/Halloween2022.json"
- $.entries[28].contentVersion: "4e4cb89a1a65f894c2a249e45ed52f9bafb05722"
+ $.entries[28].contentVersion: "0349ede198538537ff43da647cb4a6f17d238593"
- $.entries[28].uri: "archiveQuests/Tome02.json"
+ $.entries[28].uri: "archiveQuests/Halloween2023.json"
- $.entries[29].contentVersion: "8e09fd23b120b4eb070b7de0708ab77b015ba59a"
+ $.entries[29].contentVersion: "1e181ef15456cd2d7365430e6a10805da93a4e04"
- $.entries[29].uri: "archiveQuests/Tome03.json"
+ $.entries[29].uri: "archiveQuests/Halloween2024.json"
- $.entries[30].contentVersion: "1445cac2124a8a49cfac61854a3cb4e19930ab3b"
+ $.entries[30].contentVersion: "a362e2dc91965ba6c44c49cdaebac40ca88214b4"
- $.entries[30].uri: "archiveQuests/Tome04.json"
+ $.entries[30].uri: "archiveQuests/Spring2024.json"
- $.entries[31].contentVersion: "65667e34e34f6b906753541d7ffb30d0964d58e2"
+ $.entries[31].contentVersion: "30b252650a511f485554eb5e67b17aea7dbfef26"
- $.entries[31].uri: "archiveQuests/Tome05.json"
+ $.entries[31].uri: "archiveQuests/Spring2025.json"
- $.entries[32].contentVersion: "9b986b7a2b946df37090dfa6c55e44b82b3bfc80"
+ $.entries[32].contentVersion: "adab2d09b46d816bc7e799c9c630c7a5ebfa08ba"
- $.entries[32].uri: "archiveQuests/Tome06.json"
+ $.entries[32].uri: "archiveQuests/Summer2023.json"
- $.entries[33].contentVersion: "e0c62b74ef3462f1c839ee1823fe620c1069f680"
+ $.entries[33].contentVersion: "b37423fb4e1b4e8acf9b8fe07224f0c038e96cff"
- $.entries[33].uri: "archiveQuests/Tome07.json"
+ $.entries[33].uri: "archiveQuests/Tome01.json"
- $.entries[34].contentVersion: "e3b6bc4167c46692bbcad20acfc7f9d118297836"
+ $.entries[34].contentVersion: "60d7af5b70c58eac3b28cc14dbc25328d2b847b0"
- $.entries[34].uri: "archiveQuests/Tome08.json"
+ $.entries[34].uri: "archiveQuests/Tome02.json"
- $.entries[35].contentVersion: "c893e8080c4b19d0d9fbecc9e9bb9dab30a1d746"
+ $.entries[35].contentVersion: "3fb24f03ef3244a27f7aa961c96c2b55edd1ec3f"
- $.entries[35].uri: "archiveQuests/Tome09.json"
+ $.entries[35].uri: "archiveQuests/Tome03.json"
… 746 more change(s) — see the commit diff for everything
```

### [`freetoplay/EU/event.json`](freetoplay/EU/event.json)

[Full line-by-line diff](diffs/freetoplay/EU/event.json.diff)

```diff
- $.event.end: "2026-02-02T18:00:00"
+ $.event.end: "2025-11-03T16:00:00"
- $.event.start: "2026-01-29T18:00:00"
+ $.event.start: "2025-10-30T15:00:00"
```

### [`freetoplay/NA/event.json`](freetoplay/NA/event.json)

[Full line-by-line diff](diffs/freetoplay/NA/event.json.diff)

```diff
- $.event.end: "2026-02-02T18:00:00"
+ $.event.end: "2025-11-03T16:00:00"
- $.event.start: "2026-01-29T18:00:00"
+ $.event.start: "2025-10-30T15:00:00"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Omelet_W6]
- $.featuredCard[id=Omelet_W5].activeTo: "2026-01-23T16:00:00"
+ $.featuredCard[id=Omelet_W5].activeTo: "2026-01-27T16:00:00"
- $.specialsRecommendations[id=SilentHillSale]
- $.specialsRecommendations[id=IriShardSale]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[61].mainEndTime: "2026-01-27T16:00:00"
+ $.specialEvents[61].mainEndTime: "2026-01-27T14:00:00"
- $.specialEvents[61].postEndTime: "2026-01-27T16:00:00"
+ $.specialEvents[61].postEndTime: "2026-01-27T14:00:00"
```

