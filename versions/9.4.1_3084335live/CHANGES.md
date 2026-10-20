# live · 9.4.1_3084335live

| | |
|---|---|
| Build date | 2026-02-06 16:20 UTC |
| CDN version | `9.4.1_3084335live-1770394857` |
| Key | `9.4.1_live` |
| Compared with | [9.4.0_3081856live](../9.4.0_3081856live/CHANGES.md) (2026-02-06 16:18 UTC) |

## Summary

**0** added · **10** modified · **6** removed · 201 unchanged

## Removed files

- `images/T_UI_ChapterBundle_StrangerThings_Chapter2.png`
- `images/T_UI_CollectionBanner_StrangerThings_Chapter2.png`
- `images/T_UI_SpecialPack_Rift4.png`
- `images/T_UI_SpecialPack_StrangerThings_Chapter2.png`
- `images/T_UI_icon_Event_FogCarnival.png`
- `images/T_UI_icon_Event_LunarYear.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.DSProviderOnShutdownNotificationDelay: 15.0
+ $.DSProviderOnShutdownNotificationDelay: 90.0
- $.enableAlwaysSendCrashWithUI: false
+ $.enableAlwaysSendCrashWithUI: true
```

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
+ $.TOME23.vignettes[id=TOME23_02].entries[9]
+ $.TOME23.vignettes[id=TOME23_03].entries[0]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=From_The_Rift_Bundle_260120]
- $[id=From_The_Rift_Bundle_260127]
- $[id=Recurring_Charm_Bundle_260120]
- $[id=Recurring_Charm_Bundle_260127]
- $[id=Recurring_Dev_Bundle_260120]
- $[id=Recurring_Dev_Bundle_260127]
- $[id=Recurring_Killer_Bundle_260120]
- $[id=Recurring_Killer_Bundle_260127]
- $[id=Recurring_Survivor_Bundle_260120]
- $[id=Recurring_Survivor_Bundle_260127]
- $[id=Recurring_Survivor_Bundle_2_260127]
+ $[id=SUS_017]
+ $[id=SilentHill_Omelet_Bundle]
- $[id=S22_outfit_02].metaData.temporaryDiscounts
- $[id=S22_outfit_02_01].metaData.temporaryDiscounts
- $[id=TorturedSoulsBundle].metaData.sortOrder: 600
+ $[id=TorturedSoulsBundle].metaData.sortOrder: 1100
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.ChocolateBoxOmeletSet.challengeList[0].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[0].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.challengeList[1].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[1].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.challengeList[2].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[2].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.challengeList[3].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[3].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.endDate: "2026-01-27T16:00:00"
- $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests1].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests1].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests2].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests2].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[0].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[0].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_ChaseOrBeChased].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_ChaseOrBeChased].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_CarryOrEscapeChase].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_CarryOrEscapeChase].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_BreakGen].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_BreakGen].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_Repair].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_Repair].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.endDate: "2026-02-24T16:00:00"
+ $.LNYPoutine.endDate: "2026-03-01T16:00:00"
- $.LNYPoutine.startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.startDate: "2026-02-15T16:00:00"
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[6]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "22f4426df683b6384ac0d61b71e28e3880e1c7ec"
+ $.entries[0].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_Rift4.T_UI_SpecialPack_Rift4"
+ $.entries[0].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[0].uri: "images/T_UI_SpecialPack_Rift4.png"
+ $.entries[0].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[1].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[2].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[3].contentVersion: "71da739acc05234bcde2dc3f02f5b684af477eba"
- $.entries[3].downloadStrategy: "preferPackaged"
+ $.entries[3].downloadStrategy: "preferRemote"
- $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_EldritchNightmares.T_UI_CollectionBanner_EldritchNightmares"
- $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[3].uri: "images/T_UI_CollectionBanner_EldritchNightmares.png"
- $.entries[4].contentVersion: "ecea0cbb601208988fb7e266e6339430fbd26066"
+ $.entries[4].contentVersion: "9555817f05628fe8332fe67c508a029dce563092"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].packagedPath: "/DBDUICore/Assets/Common/Event/T_UI_icon_Event_FogCarnival.T_UI_icon_Event_FogCarnival"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_EldritchNightmares.T_UI_SpecialPack_EldritchNightmares"
- $.entries[4].uri: "images/T_UI_icon_Event_FogCarnival.png"
+ $.entries[4].uri: "images/T_UI_SpecialPack_EldritchNightmares.png"
- $.entries[5].contentVersion: "ba5908d103a3c970227c15e80f8c1cedd3ed9bec"
+ $.entries[5].contentVersion: "84fb38c2c918b402b996ddf9911c599300b41eba"
- $.entries[5].packagedPath: "/DBDUICore/Assets/Common/Event/T_UI_icon_Event_LunarYear.T_UI_icon_Event_LunarYear"
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_ModernTales.T_UI_SpecialPack_ModernTales"
- $.entries[5].uri: "images/T_UI_icon_Event_LunarYear.png"
+ $.entries[5].uri: "images/T_UI_SpecialPack_ModernTales.png"
- $.entries[6].contentVersion: "36c04d7010039e4bbed2a8374fce6f33020d71f9"
+ $.entries[6].contentVersion: "22fc524dffa594a87663f7925d54138914bd937f"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_StrangerThings_Chapter2.T_UI_ChapterBundle_StrangerThings_Chapter2"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_ChapterBundle_StrangerThings_Chapter2.png"
+ $.entries[6].uri: "catalog.json"
- $.entries[7].contentVersion: "71da739acc05234bcde2dc3f02f5b684af477eba"
+ $.entries[7].contentVersion: "5d124c36de256559501744cadda80d8524b1753d"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_EldritchNightmares.T_UI_CollectionBanner_EldritchNightmares"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_CollectionBanner_EldritchNightmares.png"
+ $.entries[7].uri: "bonusPointEventsContent.json"
- $.entries[8].contentVersion: "9555817f05628fe8332fe67c508a029dce563092"
+ $.entries[8].contentVersion: "9a3480f6b6a4ac884b60d841509796280849c249"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_EldritchNightmares.T_UI_SpecialPack_EldritchNightmares"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_SpecialPack_EldritchNightmares.png"
+ $.entries[8].uri: "freetoplay/NA/event.json"
- $.entries[9].contentVersion: "84fb38c2c918b402b996ddf9911c599300b41eba"
+ $.entries[9].contentVersion: "9a3480f6b6a4ac884b60d841509796280849c249"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_ModernTales.T_UI_SpecialPack_ModernTales"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_SpecialPack_ModernTales.png"
+ $.entries[9].uri: "freetoplay/EU/event.json"
- $.entries[10].contentVersion: "f8b2414afc2858c35fed794667b3ba6f27a3e7a0"
+ $.entries[10].contentVersion: "bc006d92d29a5e6328e91285b11aa54a0e0c411f"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].enableChecksum: false
+ $.entries[10].enableChecksum: true
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_StrangerThings_Chapter2.T_UI_CollectionBanner_StrangerThings_Chapter2"
+ $.entries[10].packagedPath: ""
- $.entries[10].schema: "s3verbin://"
+ $.entries[10].schema: "s3ver://"
- $.entries[10].uri: "images/T_UI_CollectionBanner_StrangerThings_Chapter2.png"
+ $.entries[10].uri: "archiveQuests/Anniversary2022.json"
- $.entries[11].contentVersion: "12010aea83ad4e1ee56c50df0da8cd85a85498a2"
+ $.entries[11].contentVersion: "ab5e8b9e9ca68f4f8059f1b14449269d0ffeadb8"
- $.entries[11].downloadStrategy: "preferPackaged"
+ $.entries[11].downloadStrategy: "preferRemote"
- $.entries[11].enableChecksum: false
+ $.entries[11].enableChecksum: true
- $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/Poutine/T_UI_SpecialPack_StrangerThings_Chapter2.T_UI_SpecialPack_StrangerThings_Chapter2"
+ $.entries[11].packagedPath: ""
- $.entries[11].schema: "s3verbin://"
+ $.entries[11].schema: "s3ver://"
- $.entries[11].uri: "images/T_UI_SpecialPack_StrangerThings_Chapter2.png"
+ $.entries[11].uri: "archiveQuests/Anniversary2023.json"
- $.entries[12].contentVersion: "5e59003383435a2fe4dd68e7cd60ab66bb55d1b1"
+ $.entries[12].contentVersion: "7a0b19c453ff0736b3dbf7ba57fa907f66134ece"
- $.entries[12].uri: "catalog.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2024.json"
- $.entries[13].contentVersion: "0688a6020b52e6bd9500b266ac4b4b6baa60860d"
+ $.entries[13].contentVersion: "d27cd9bc810294e4fa260a00a26d9262c3df3b2f"
- $.entries[13].uri: "bonusPointEventsContent.json"
+ $.entries[13].uri: "archiveQuests/CalamariV1.json"
- $.entries[14].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
+ $.entries[14].contentVersion: "fe44212cf941925219bc4dc5d3a882350924d26a"
- $.entries[14].uri: "freetoplay/NA/event.json"
+ $.entries[14].uri: "archiveQuests/CalamariV2.json"
- $.entries[15].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
+ $.entries[15].contentVersion: "19ca4e16bcba6dd47a5cee03b8333bcf8b343ad2"
- $.entries[15].uri: "freetoplay/EU/event.json"
+ $.entries[15].uri: "archiveQuests/CalamariV3.json"
- $.entries[16].contentVersion: "dd527570e43d5227bc28afe72fb1f78e53ac6822"
+ $.entries[16].contentVersion: "76f1017394843b2d22851a5a6f9985c962a416d8"
- $.entries[16].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[17].contentVersion: "52fc655e6b41b211e455230a518f9846c8b5286a"
+ $.entries[17].contentVersion: "2fadd29ada397df69c995d89af3cb33c813b37a1"
- $.entries[17].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[18].contentVersion: "946926ad6e5fc8348d1f1132ac7b59cc676cff14"
+ $.entries[18].contentVersion: "ccdb1cf13b148d29fc66281c13aaf1543013b320"
- $.entries[18].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[19].contentVersion: "44a5c8ea54340fdfc9b01597243b454a8622e029"
+ $.entries[19].contentVersion: "7c6a8bf71078b820849b4630b11b29fb5f8791b8"
- $.entries[19].uri: "archiveQuests/CalamariV1.json"
+ $.entries[19].uri: "archiveQuests/FireflyV1.json"
- $.entries[20].contentVersion: "671675edb2bebab5f35c2e4b6b8e5fa78882ee92"
+ $.entries[20].contentVersion: "e7f9a9518d965a55b41ffca9e1cb2b3e107f4fbf"
- $.entries[20].uri: "archiveQuests/CalamariV2.json"
+ $.entries[20].uri: "archiveQuests/Halloween2021.json"
- $.entries[21].contentVersion: "c36008b30af60617d7038322e37ad3f3cd2754e5"
+ $.entries[21].contentVersion: "46204ae471ea73fd72d29cea51d914f10df01e9a"
- $.entries[21].uri: "archiveQuests/CalamariV3.json"
+ $.entries[21].uri: "archiveQuests/Halloween2022.json"
- $.entries[22].contentVersion: "680a0cf92894220d6b78184aef473d2da4c76013"
+ $.entries[22].contentVersion: "2257b9f00eb53b5dbf54eda8bb4b5805dc94bb1b"
- $.entries[22].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[22].uri: "archiveQuests/Halloween2023.json"
- $.entries[23].contentVersion: "eae70968d8423a3a0f61227e8b7da194f8856be1"
+ $.entries[23].contentVersion: "20013d8c29cdcc7f2abf90fe9db21811871df20e"
- $.entries[23].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[23].uri: "archiveQuests/Halloween2024.json"
- $.entries[24].contentVersion: "5210f96a51547ac1be938e0651440a5c5569ef3a"
+ $.entries[24].contentVersion: "67d4205d65da1a7ddcb442abe12b9ab56dc1f011"
- $.entries[24].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[24].uri: "archiveQuests/Spring2024.json"
- $.entries[25].contentVersion: "3de6169053b9db24bf1f8464a61002e16a417945"
+ $.entries[25].contentVersion: "02f1ba95f160a443d3d2134179f481519054eb01"
- $.entries[25].uri: "archiveQuests/FireflyV1.json"
+ $.entries[25].uri: "archiveQuests/Spring2025.json"
- $.entries[26].contentVersion: "69fe782985a5376bac4f588fac10e1f567cbeca4"
+ $.entries[26].contentVersion: "95528a855f0f57c424f8649b32daf3cba921b1a7"
- $.entries[26].uri: "archiveQuests/Halloween2021.json"
+ $.entries[26].uri: "archiveQuests/Summer2023.json"
- $.entries[27].contentVersion: "3b38b442968cdb458f8afd787c8e688df454f3ff"
+ $.entries[27].contentVersion: "1a53f6ac66d7a90847f8fc602da6113b4e4011b3"
- $.entries[27].uri: "archiveQuests/Halloween2022.json"
+ $.entries[27].uri: "archiveQuests/Tome01.json"
- $.entries[28].contentVersion: "0349ede198538537ff43da647cb4a6f17d238593"
+ $.entries[28].contentVersion: "3c508b1e5c472402c742a24f45598eb04ee53bbc"
- $.entries[28].uri: "archiveQuests/Halloween2023.json"
+ $.entries[28].uri: "archiveQuests/Tome02.json"
- $.entries[29].contentVersion: "1e181ef15456cd2d7365430e6a10805da93a4e04"
+ $.entries[29].contentVersion: "71d36cc34c08f37d6025d47867419be11ab8457a"
- $.entries[29].uri: "archiveQuests/Halloween2024.json"
+ $.entries[29].uri: "archiveQuests/Tome03.json"
- $.entries[30].contentVersion: "a362e2dc91965ba6c44c49cdaebac40ca88214b4"
+ $.entries[30].contentVersion: "113c61c02c94df30863c1d1e950667592e7fd3f9"
- $.entries[30].uri: "archiveQuests/Spring2024.json"
+ $.entries[30].uri: "archiveQuests/Tome04.json"
- $.entries[31].contentVersion: "30b252650a511f485554eb5e67b17aea7dbfef26"
+ $.entries[31].contentVersion: "1889ae6bcaa7d2e64f13dc16d26998a04ef57180"
- $.entries[31].uri: "archiveQuests/Spring2025.json"
+ $.entries[31].uri: "archiveQuests/Tome05.json"
- $.entries[32].contentVersion: "adab2d09b46d816bc7e799c9c630c7a5ebfa08ba"
+ $.entries[32].contentVersion: "46a11887e67b717e5c69d541d3146492f42e6fb0"
- $.entries[32].uri: "archiveQuests/Summer2023.json"
+ $.entries[32].uri: "archiveQuests/Tome06.json"
- $.entries[33].contentVersion: "b37423fb4e1b4e8acf9b8fe07224f0c038e96cff"
+ $.entries[33].contentVersion: "9c2b9cd73b5699250400e4266f6aee81df7f7974"
- $.entries[33].uri: "archiveQuests/Tome01.json"
+ $.entries[33].uri: "archiveQuests/Tome07.json"
- $.entries[34].contentVersion: "60d7af5b70c58eac3b28cc14dbc25328d2b847b0"
+ $.entries[34].contentVersion: "28579a3d46d6c5787869b036b5c8938f46959560"
- $.entries[34].uri: "archiveQuests/Tome02.json"
+ $.entries[34].uri: "archiveQuests/Tome08.json"
- $.entries[35].contentVersion: "3fb24f03ef3244a27f7aa961c96c2b55edd1ec3f"
+ $.entries[35].contentVersion: "3bb463544d259a291ef2473fd6c09b9a2a36b408"
… 748 more change(s) — see the commit diff for everything
```

### [`freetoplay/EU/event.json`](freetoplay/EU/event.json)

[Full line-by-line diff](diffs/freetoplay/EU/event.json.diff)

```diff
- $.event.end: "2025-11-03T16:00:00"
+ $.event.end: "2026-02-02T18:00:00"
- $.event.start: "2025-10-30T15:00:00"
+ $.event.start: "2026-01-29T18:00:00"
```

### [`freetoplay/NA/event.json`](freetoplay/NA/event.json)

[Full line-by-line diff](diffs/freetoplay/NA/event.json.diff)

```diff
- $.event.end: "2025-11-03T16:00:00"
+ $.event.end: "2026-02-02T18:00:00"
- $.event.start: "2025-10-30T15:00:00"
+ $.event.start: "2026-01-29T18:00:00"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Omelet_W6]
- $.featuredCard[id=Omelet_W5].activeTo: "2026-01-27T16:00:00"
+ $.featuredCard[id=Omelet_W5].activeTo: "2026-01-23T16:00:00"
+ $.specialsRecommendations[id=SilentHillSale]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[61].mainEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].mainEndTime: "2026-01-27T16:00:00"
- $.specialEvents[61].postEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].postEndTime: "2026-01-27T16:00:00"
- $.specialEvents[64].mainEndTime: "2026-02-24T16:00:00"
+ $.specialEvents[64].mainEndTime: "2026-03-01T16:00:00"
- $.specialEvents[64].postEndTime: "2026-02-24T16:00:00"
+ $.specialEvents[64].postEndTime: "2026-03-01T16:00:00"
- $.specialEvents[64].startTime: "2026-02-12T16:00:00"
+ $.specialEvents[64].startTime: "2026-02-15T16:00:00"
```

