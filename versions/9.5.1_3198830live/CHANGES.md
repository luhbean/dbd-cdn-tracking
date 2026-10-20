# live · 9.5.1_3198830live

| | |
|---|---|
| Build date | 2026-03-23 14:12 UTC |
| CDN version | `9.5.1_3198830live-1774275153` |
| Key | `9.5.1_live` |
| Compared with | [9.5.0_3196161live](../9.5.0_3196161live/CHANGES.md) (2026-03-19 19:31 UTC) |

## Summary

**0** added · **5** modified · **8** removed · 204 unchanged

## Removed files

- `images/T_UI_ChapterBundle_AllKillComeback.png`
- `images/T_UI_CollectionBanner_AllKillComeback.png`
- `images/T_UI_CollectionBanner_Bloodmoon_Quiche.png`
- `images/T_UI_SpecialPack_AllKillComeback.png`
- `images/T_UI_SpecialPack_ArtistsFromTheFog_Haddie.png`
- `images/T_UI_SpecialPack_Bloodmoon_Bundle.png`
- `images/T_UI_SpecialPack_Bloodmoon_Quiche.png`
- `images/T_UI_SpecialPack_EntombedRemains.png`

## Modified files

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
+ $.TOME23.vignettes[id=TOME23_03].entries[6]
+ $.TOME23.vignettes[id=TOME23_03].entries[7]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=S52].metaData.defaultCustomization[]: "S52_Torso01_04"
+ $[id=AV_Head022].metaData.eventID: "Spring2025"
+ $[id=AV_Legs022].metaData.eventID: "Spring2025"
+ $[id=AV_Torso022].metaData.eventID: "Spring2025"
+ $[id=CM_Head030].metaData.eventID: "Spring2025"
+ $[id=CM_Legs030].metaData.eventID: "Spring2025"
+ $[id=CM_Torso030].metaData.eventID: "Spring2025"
+ $[id=DO_Body020].metaData.eventID: "Spring2025"
+ $[id=DO_Head020].metaData.eventID: "Spring2025"
+ $[id=DO_Head022].metaData.eventID: "Spring2025"
+ $[id=HK_Body027].metaData.eventID: "Spring2025"
+ $[id=HK_Head027].metaData.eventID: "Spring2025"
+ $[id=HK_W027].metaData.eventID: "Spring2025"
+ $[id=JP_Head033].metaData.eventID: "Spring2025"
+ $[id=JP_Legs033].metaData.eventID: "Spring2025"
+ $[id=JP_Torso033].metaData.eventID: "Spring2025"
+ $[id=K21_Body022].metaData.eventID: "Spring2025"
+ $[id=K21_Head022].metaData.eventID: "Spring2025"
+ $[id=K21_W022].metaData.eventID: "Spring2025"
+ $[id=K26_Body019].metaData.eventID: "Spring2025"
+ $[id=K26_Head019].metaData.eventID: "Spring2025"
+ $[id=K26_W019].metaData.eventID: "Spring2025"
+ $[id=K30_Body012].defaultCost[1]
+ $[id=K30_Body012].metaData.eventID: "Spring2025"
+ $[id=K30_Head012].defaultCost[1]
+ $[id=K30_Head012].metaData.eventID: "Spring2025"
+ $[id=K30_W012].defaultCost[1]
+ $[id=K30_W012].metaData.eventID: "Spring2025"
+ $[id=K31_Body012].metaData.eventID: "Spring2025"
+ $[id=K31_Head012].metaData.eventID: "Spring2025"
+ $[id=K31_W012].metaData.eventID: "Spring2025"
+ $[id=K38_Body007].metaData.eventID: "Spring2025"
+ $[id=K38_Head007].metaData.eventID: "Spring2025"
+ $[id=K38_W007].metaData.eventID: "Spring2025"
+ $[id=S28_Head023].metaData.eventID: "Spring2025"
+ $[id=S28_Legs023].metaData.eventID: "Spring2025"
+ $[id=S28_Torso023].metaData.eventID: "Spring2025"
+ $[id=S41_Head021].metaData.eventID: "Spring2025"
+ $[id=S41_Legs021].metaData.eventID: "Spring2025"
+ $[id=S41_Torso021].metaData.eventID: "Spring2025"
+ $[id=S45_Head011].metaData.eventID: "Spring2025"
+ $[id=S45_Legs011].metaData.eventID: "Spring2025"
+ $[id=S45_Torso011].metaData.eventID: "Spring2025"
+ $[id=S46_Head015].metaData.eventID: "Spring2025"
+ $[id=S46_Legs015].metaData.eventID: "Spring2025"
+ $[id=S46_Torso015].metaData.eventID: "Spring2025"
+ $[id=S52_Torso01_04].categories[]: "default"
- $[id=S52_Torso01_04].metaData.entitledByDefault: false
+ $[id=S52_Torso01_04].metaData.entitledByDefault: true
+ $[id=UK_Body020].metaData.eventID: "Spring2025"
+ $[id=UK_Head020].metaData.eventID: "Spring2025"
+ $[id=UK_W020].metaData.eventID: "Spring2025"
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.ChapterQuests_Quiche.challengeList[0].challenges[id=ChapterQuests_Quiche-Overarching-O_CompleteRiftQuestsB].objectives.Overarching.objectiveInfo: "CHALLENGE_CompleteRiftQuests_INFO"
+ $.ChapterQuests_Quiche.challengeList[0].challenges[id=ChapterQuests_Quiche-Overarching-O_CompleteRiftQuestsB].objectives.Overarching.objectiveInfo: "CHALLENGE_CompleteChapterQuests_INFO"
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.Quiche.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.Quiche.platforms.grdk: "9N2DHTZ1D9CC"
- $.dlcList.Quiche.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.Quiche.platforms.xbox: "9PH26HVZK5CJ"
- $.dlcList.Quiche.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.Quiche.platforms.xsx: "9PH26HVZK5CJ"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "372f56e4ce889f50dc5ac47446d35c1dea0ee9ca"
+ $.entries[0].contentVersion: "cf7cf00b919d33db2cac5803060754bacc45871e"
- $.entries[0].downloadStrategy: "preferPackaged"
+ $.entries[0].downloadStrategy: "preferRemote"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_Bloodmoon_Bundle.T_UI_SpecialPack_Bloodmoon_Bundle"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_MiNABundle.T_UI_SpecialPack_MiNABundle"
- $.entries[0].uri: "images/T_UI_SpecialPack_Bloodmoon_Bundle.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_MiNABundle.png"
- $.entries[1].contentVersion: "cf7cf00b919d33db2cac5803060754bacc45871e"
+ $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[1].downloadStrategy: "preferRemote"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_MiNABundle.T_UI_SpecialPack_MiNABundle"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[1].uri: "images/T_UI_SpecialPack_MiNABundle.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[2].contentVersion: "7b6a8c3f1f8a8150a5bfc76ffb1c0308d8d00dae"
+ $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllKillComeback.T_UI_ChapterBundle_AllKillComeback"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[2].uri: "images/T_UI_ChapterBundle_AllKillComeback.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[3].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[4].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[4].contentVersion: "9c83ed428340d28f18f6fd8505aeca6d28c054f2"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].enableChecksum: false
+ $.entries[4].enableChecksum: true
- $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[4].packagedPath: ""
- $.entries[4].schema: "s3verbin://"
+ $.entries[4].schema: "s3ver://"
- $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[4].uri: "catalog.json"
- $.entries[5].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[5].contentVersion: "2faec738e528579cdb4ce216a6e682823b470805"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].enableChecksum: false
+ $.entries[5].enableChecksum: true
- $.entries[5].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[5].packagedPath: ""
- $.entries[5].schema: "s3verbin://"
+ $.entries[5].schema: "s3ver://"
- $.entries[5].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[5].uri: "bonusPointEventsContent.json"
- $.entries[6].contentVersion: "91e8518ba9c09aef7d41865cbd8fbe7f4fdf5fb3"
+ $.entries[6].contentVersion: "7e235914cb1520954aaf79ed27a227f3d9968c55"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_ArtistsFromTheFog_Haddie.T_UI_SpecialPack_ArtistsFromTheFog_Haddie"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_SpecialPack_ArtistsFromTheFog_Haddie.png"
+ $.entries[6].uri: "freetoplay/NA/event.json"
- $.entries[7].contentVersion: "959fabeeccb034819147e5d0ba2cdd5401766d60"
+ $.entries[7].contentVersion: "7e235914cb1520954aaf79ed27a227f3d9968c55"
- $.entries[7].downloadStrategy: "preferPackaged"
+ $.entries[7].downloadStrategy: "preferRemote"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Quiche/T_UI_CollectionBanner_Bloodmoon_Quiche.T_UI_CollectionBanner_Bloodmoon_Quiche"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_CollectionBanner_Bloodmoon_Quiche.png"
+ $.entries[7].uri: "freetoplay/EU/event.json"
- $.entries[8].contentVersion: "78209c89723d44a3f77e31b1fedcc4ad9cad795b"
+ $.entries[8].contentVersion: "cc800af79b80d68a97638e8bef9cdd689c439e6e"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_Bloodmoon_Quiche.T_UI_SpecialPack_Bloodmoon_Quiche"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_SpecialPack_Bloodmoon_Quiche.png"
+ $.entries[8].uri: "archiveQuests/Anniversary2022.json"
- $.entries[9].contentVersion: "708c753f60235b611acd71990e30ee888440e536"
+ $.entries[9].contentVersion: "d9c6c13fa45df08e71f60e984d0d4d323c600642"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Quiche/T_UI_CollectionBanner_AllKillComeback.T_UI_CollectionBanner_AllKillComeback"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_CollectionBanner_AllKillComeback.png"
+ $.entries[9].uri: "archiveQuests/Anniversary2023.json"
- $.entries[10].contentVersion: "f10501984992cfbf10084409d5d0bc4a69117c54"
+ $.entries[10].contentVersion: "4940aa091648dca19a79d9b8aac8dd20dd4ca88d"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].enableChecksum: false
+ $.entries[10].enableChecksum: true
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_AllKillComeback.T_UI_SpecialPack_AllKillComeback"
+ $.entries[10].packagedPath: ""
- $.entries[10].schema: "s3verbin://"
+ $.entries[10].schema: "s3ver://"
- $.entries[10].uri: "images/T_UI_SpecialPack_AllKillComeback.png"
+ $.entries[10].uri: "archiveQuests/Anniversary2024.json"
- $.entries[11].contentVersion: "618875b6f64dbdcbcf0224a32a85a5c84083dc5c"
+ $.entries[11].contentVersion: "aae9d286e50fc9707620906ff774c4992b2fb326"
- $.entries[11].downloadStrategy: "preferPackaged"
+ $.entries[11].downloadStrategy: "preferRemote"
- $.entries[11].enableChecksum: false
+ $.entries[11].enableChecksum: true
- $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_EntombedRemains.T_UI_SpecialPack_EntombedRemains"
+ $.entries[11].packagedPath: ""
- $.entries[11].schema: "s3verbin://"
+ $.entries[11].schema: "s3ver://"
- $.entries[11].uri: "images/T_UI_SpecialPack_EntombedRemains.png"
+ $.entries[11].uri: "archiveQuests/CalamariV1.json"
- $.entries[12].contentVersion: "8d150266e5d944f70a45286e9bc547e4c3827d7a"
+ $.entries[12].contentVersion: "848d325a533eca323a1dcd220dd71b419a281873"
- $.entries[12].uri: "catalog.json"
+ $.entries[12].uri: "archiveQuests/CalamariV2.json"
- $.entries[13].contentVersion: "5b039bbeee491d0b93ceda679c4ace6bbf1de269"
+ $.entries[13].contentVersion: "eb162419b832ab1ba040667d9689971741929643"
- $.entries[13].uri: "bonusPointEventsContent.json"
+ $.entries[13].uri: "archiveQuests/CalamariV3.json"
- $.entries[14].contentVersion: "24497671b5d28e596507549ba1b390368e004229"
+ $.entries[14].contentVersion: "32fd3a92a6cf67463de180d84e2d418613199576"
- $.entries[14].uri: "freetoplay/NA/event.json"
+ $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[15].contentVersion: "24497671b5d28e596507549ba1b390368e004229"
+ $.entries[15].contentVersion: "d60d9b1f27933561f3af2503062e589d11e46641"
- $.entries[15].uri: "freetoplay/EU/event.json"
+ $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[16].contentVersion: "a6ab361537fd669c667020c309c139dd9169726a"
+ $.entries[16].contentVersion: "572c3225bd59a9f10db5dd2b35d973e45136eff7"
- $.entries[16].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[17].contentVersion: "7af95658408629d63b385a32df713142dc4daf9a"
+ $.entries[17].contentVersion: "f354376fa077c2c631fba9ee80a564f31d3aea2d"
- $.entries[17].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[17].uri: "archiveQuests/FireflyV1.json"
- $.entries[18].contentVersion: "caedd3c30c156efdba80ba2450969344f3f06de8"
+ $.entries[18].contentVersion: "639df7a4422cab03e67a257fdb842f06a90db237"
- $.entries[18].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[18].uri: "archiveQuests/Halloween2021.json"
- $.entries[19].contentVersion: "2c2d8c2f09d5ec34505cd93465105517e954dd1f"
+ $.entries[19].contentVersion: "633c92a0169a8f5670bde911dc3d9e8b23a821cf"
- $.entries[19].uri: "archiveQuests/CalamariV1.json"
+ $.entries[19].uri: "archiveQuests/Halloween2022.json"
- $.entries[20].contentVersion: "fb525c4d73f0614c7a23505500fde5d54327c1a5"
+ $.entries[20].contentVersion: "2ae3766086526066d40a62ba3e5eda79836f7858"
- $.entries[20].uri: "archiveQuests/CalamariV2.json"
+ $.entries[20].uri: "archiveQuests/Halloween2023.json"
- $.entries[21].contentVersion: "e82aae4ae097d3fb68186c0a39dd153ec885130c"
+ $.entries[21].contentVersion: "cd039412a0de844521fa41a6d49631c6bee55ea5"
- $.entries[21].uri: "archiveQuests/CalamariV3.json"
+ $.entries[21].uri: "archiveQuests/Halloween2024.json"
- $.entries[22].contentVersion: "5086ad9a1a1a189159c66c03828a2ca5633b45bc"
+ $.entries[22].contentVersion: "a5eb2638115f739dc067efe1a1bb03c61ac921ed"
- $.entries[22].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[22].uri: "archiveQuests/Spring2024.json"
- $.entries[23].contentVersion: "0a0fb13155fa8131aa1dffec559ed4cea9ee1248"
+ $.entries[23].contentVersion: "e92659907a52af28df5581d32133520b214b333c"
- $.entries[23].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[23].uri: "archiveQuests/Spring2025.json"
- $.entries[24].contentVersion: "d8a5bf3acb11316221ac613a48ef082d54295cd7"
+ $.entries[24].contentVersion: "aea5500cc5358a7244630b2a70b7d7306ed22f3d"
- $.entries[24].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[24].uri: "archiveQuests/Summer2023.json"
- $.entries[25].contentVersion: "5f9ca96219895f64faf52892740543ff15386289"
+ $.entries[25].contentVersion: "8e0d36de96fbe9eff1d5644a375b64fbac5bc79d"
- $.entries[25].uri: "archiveQuests/FireflyV1.json"
+ $.entries[25].uri: "archiveQuests/Tome01.json"
- $.entries[26].contentVersion: "01097afbbdec37d09ff591dd9bb6ef310e525ba5"
+ $.entries[26].contentVersion: "78386cd3f66c6278522305718bdffdd2b0999b0e"
- $.entries[26].uri: "archiveQuests/Halloween2021.json"
+ $.entries[26].uri: "archiveQuests/Tome02.json"
- $.entries[27].contentVersion: "b185cd1ff0408d8ec7bd78e651adcf2239efa6a1"
+ $.entries[27].contentVersion: "ea217f51aab4d533a0b7b219c0cd1e4cf344daf5"
- $.entries[27].uri: "archiveQuests/Halloween2022.json"
+ $.entries[27].uri: "archiveQuests/Tome03.json"
- $.entries[28].contentVersion: "8f0046ba012d7daa8a3788679ec72153b27d45c5"
+ $.entries[28].contentVersion: "93a5e14a40afe915f07c00ed30599565763d614e"
- $.entries[28].uri: "archiveQuests/Halloween2023.json"
+ $.entries[28].uri: "archiveQuests/Tome04.json"
- $.entries[29].contentVersion: "330f90e261b32487bb4580abaa84230ac8bf7b77"
+ $.entries[29].contentVersion: "dab89b7a16d73479922e98745479a3243aa63517"
- $.entries[29].uri: "archiveQuests/Halloween2024.json"
+ $.entries[29].uri: "archiveQuests/Tome05.json"
- $.entries[30].contentVersion: "4eb83fa8ed7a4a416f976130cd94eeaee376e8cc"
+ $.entries[30].contentVersion: "ffe94e3a87693351dc0165023707c3fdd6e25f30"
- $.entries[30].uri: "archiveQuests/Spring2024.json"
+ $.entries[30].uri: "archiveQuests/Tome06.json"
… 772 more change(s) — see the commit diff for everything
```

