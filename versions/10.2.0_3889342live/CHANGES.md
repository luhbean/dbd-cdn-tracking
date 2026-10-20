# live · 10.2.0_3889342live

| | |
|---|---|
| Build date | 2026-10-15 20:19 UTC |
| CDN version | `10.2.0_3889342live-1792095573` |
| Key | `10.2.0_live` |
| Compared with | [10.2.1_3889339live](../10.2.1_3889339live/CHANGES.md) (2026-10-15 20:16 UTC) |

## Summary

**3** added · **4** modified · **0** removed · 206 unchanged

## New or updated images

<a href="images/T_UI_CollectionBanner_NieR.png"><img src="images/T_UI_CollectionBanner_NieR.png" alt="T_UI_CollectionBanner_NieR.png" width="240"></a>
<a href="images/T_UI_SpecialPack_NieR.png"><img src="images/T_UI_SpecialPack_NieR.png" alt="T_UI_SpecialPack_NieR.png" width="240"></a>
<a href="images/T_UI_SpecialPack_Rift7.png"><img src="images/T_UI_SpecialPack_Rift7.png" alt="T_UI_SpecialPack_Rift7.png" width="240"></a>

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=Recurring_Dev_Bundle_260929]
- $[id=Recurring_Dev_Bundle_261006]
+ $[id=VAN_016]
- $[id=PL_054].metaData.eventID: "DbdDay2025"
- $[id=XR_054].metaData.eventID: "DbdDay2025"
- $[id=10.1.2_Autumn_Fashion].metaData.sortOrder: 1999
+ $[id=10.1.2_Autumn_Fashion].metaData.sortOrder: 0
- $[id=10.1.2_Blighted_Bundle].metaData.sortOrder: 2002
+ $[id=10.1.2_Blighted_Bundle].metaData.sortOrder: 0
- $[id=SAW_Bundle].metaData.sortOrder: 2001
+ $[id=SAW_Bundle].metaData.sortOrder: 1001
- $[id=Tome_8_Bundle].metaData.sortOrder: 1998
+ $[id=Tome_8_Bundle].metaData.sortOrder: 1000
- $[id=From_The_Rift_Bundle_260929].consumptionReward[id=K21_Head010_01]
- $[id=From_The_Rift_Bundle_260929].consumptionReward[id=K21_Body010_01]
- $[id=From_The_Rift_Bundle_260929].consumptionReward[id=K21_W010_01]
+ $[id=From_The_Rift_Bundle_260929].consumptionReward[id=S29_Head009_01]
+ $[id=From_The_Rift_Bundle_260929].consumptionReward[id=S29_Torso008_01]
+ $[id=From_The_Rift_Bundle_260929].consumptionReward[id=S29_Legs008_01]
- $[id=From_The_Rift_Bundle_261006].consumptionReward[id=MT_Head012_01]
- $[id=From_The_Rift_Bundle_261006].consumptionReward[id=MT_Torso012_01]
- $[id=From_The_Rift_Bundle_261006].consumptionReward[id=MT_Legs015_01]
+ $[id=From_The_Rift_Bundle_261006].consumptionReward[id=TW_Head007_01]
+ $[id=From_The_Rift_Bundle_261006].consumptionReward[id=TW_Body02_01]
+ $[id=From_The_Rift_Bundle_261006].consumptionReward[id=TW_W03_03]
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.EpicGoldEdition
- $.dlcList.EpicJasonEdition
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[0].contentVersion: "32cc6581b8d75bbbf0fd776c45fe02fe3a96ff2b"
- $.entries[0].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Vanilla/T_UI_SpecialPack_Rift7.T_UI_SpecialPack_Rift7"
- $.entries[0].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_Rift7.png"
- $.entries[1].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[1].contentVersion: "6e0be28f89feec50ef5b63db35cbe4772125c0d1"
- $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Vanilla/T_UI_CollectionBanner_NieR.T_UI_CollectionBanner_NieR"
- $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[1].uri: "images/T_UI_CollectionBanner_NieR.png"
- $.entries[2].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[2].contentVersion: "5431a900fa21a3f14d4bd82b8fdaa4ecbb5436b0"
- $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Vanilla/T_UI_SpecialPack_NieR.T_UI_SpecialPack_NieR"
- $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[2].uri: "images/T_UI_SpecialPack_NieR.png"
- $.entries[3].contentVersion: "bad16fe55d1d95809d6e43fe95945e9e095638a4"
+ $.entries[3].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[3].downloadStrategy: "preferRemote"
+ $.entries[3].downloadStrategy: "preferPackaged"
- $.entries[3].enableChecksum: true
+ $.entries[3].enableChecksum: false
- $.entries[3].packagedPath: ""
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[3].schema: "s3ver://"
+ $.entries[3].schema: "s3verbin://"
- $.entries[3].uri: "catalog.json"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[4].contentVersion: "5543900e41899eeb43b0b8da501797aed68b7381"
+ $.entries[4].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[4].downloadStrategy: "preferRemote"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "bonusPointEventsContent.json"
+ $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[5].contentVersion: "45e2551b52a6eb96896760a46c7377147035eba3"
+ $.entries[5].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[5].downloadStrategy: "preferRemote"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "freetoplay/NA/event.json"
+ $.entries[5].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[6].contentVersion: "45e2551b52a6eb96896760a46c7377147035eba3"
+ $.entries[6].contentVersion: "6e0be28f89feec50ef5b63db35cbe4772125c0d1"
- $.entries[6].downloadStrategy: "preferRemote"
+ $.entries[6].downloadStrategy: "preferPackaged"
- $.entries[6].enableChecksum: true
+ $.entries[6].enableChecksum: false
- $.entries[6].packagedPath: ""
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Vanilla/T_UI_CollectionBanner_NieR.T_UI_CollectionBanner_NieR"
- $.entries[6].schema: "s3ver://"
+ $.entries[6].schema: "s3verbin://"
- $.entries[6].uri: "freetoplay/EU/event.json"
+ $.entries[6].uri: "images/T_UI_CollectionBanner_NieR.png"
- $.entries[7].contentVersion: "932af06683cd3f3f613c9a442c46f995767efe94"
+ $.entries[7].contentVersion: "5431a900fa21a3f14d4bd82b8fdaa4ecbb5436b0"
- $.entries[7].downloadStrategy: "preferRemote"
+ $.entries[7].downloadStrategy: "preferPackaged"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Vanilla/T_UI_SpecialPack_NieR.T_UI_SpecialPack_NieR"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[7].uri: "images/T_UI_SpecialPack_NieR.png"
- $.entries[8].contentVersion: "8b375f6fdd82984a312c590f7b8207472fdb71e6"
+ $.entries[8].contentVersion: "6eb2d90981fed73f043366546294fd1a7e712851"
- $.entries[8].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[8].uri: "catalog.json"
- $.entries[9].contentVersion: "83d3f4bfe3654b1efd7726546190ed06c119983f"
+ $.entries[9].contentVersion: "397dacff22230f3ee3e054623db2b1141ce298ad"
- $.entries[9].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[9].uri: "bonusPointEventsContent.json"
- $.entries[10].contentVersion: "6191f54eef7f99748fa19f697af5809368d63e1e"
+ $.entries[10].contentVersion: "2b013da0ff81422435027f073c3aecc85f89aac5"
- $.entries[10].uri: "archiveQuests/CalamariV1.json"
+ $.entries[10].uri: "freetoplay/NA/event.json"
- $.entries[11].contentVersion: "ff98a5e4f994fd1739f86a098af88eca09f1d398"
+ $.entries[11].contentVersion: "2b013da0ff81422435027f073c3aecc85f89aac5"
- $.entries[11].uri: "archiveQuests/CalamariV2.json"
+ $.entries[11].uri: "freetoplay/EU/event.json"
- $.entries[12].contentVersion: "1014809925170fee250003cc246f49f57b6b57cb"
+ $.entries[12].contentVersion: "297fb6ef56fef3a886b4bf87ba3ebd9481afccc4"
- $.entries[12].uri: "archiveQuests/CalamariV3.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2022.json"
- $.entries[13].contentVersion: "bb998f4bcb1754f57de0c28d1bcbaac8ed42a915"
+ $.entries[13].contentVersion: "7cd545430cfb015250c184327628c795cca7a12d"
- $.entries[13].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[13].uri: "archiveQuests/Anniversary2023.json"
- $.entries[14].contentVersion: "e3ab6318fdec75c69aaafff130761962a9ecf31b"
+ $.entries[14].contentVersion: "c9bfc1daa41e7ad68b4f3ce1a509c5581770fd24"
- $.entries[14].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[14].uri: "archiveQuests/Anniversary2024.json"
- $.entries[15].contentVersion: "ce038d0227c9f4071bc4c2456f4042a2af232f55"
+ $.entries[15].contentVersion: "5497b5acab4286641df03e77ea617c68e6a643eb"
- $.entries[15].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[15].uri: "archiveQuests/CalamariV1.json"
- $.entries[16].contentVersion: "c5948cc6b83cda7b99a96a50bbd8d552b8a7d4c9"
+ $.entries[16].contentVersion: "7b9fb6690128ef7d3224e667803f7eca8f205484"
- $.entries[16].uri: "archiveQuests/FireflyV1.json"
+ $.entries[16].uri: "archiveQuests/CalamariV2.json"
- $.entries[17].contentVersion: "02bab92fd9ab0f75091c10af25487f45cce0d0a0"
+ $.entries[17].contentVersion: "7594c53cc46047d855f2ed66d0c8dbf60d8be18f"
- $.entries[17].uri: "archiveQuests/Halloween2021.json"
+ $.entries[17].uri: "archiveQuests/CalamariV3.json"
- $.entries[18].contentVersion: "afec7b967621c19a9e9ef5625865697d63eaf350"
+ $.entries[18].contentVersion: "419e95ee61ce74b08b53cec80a76787da3fa3d56"
- $.entries[18].uri: "archiveQuests/Halloween2022.json"
+ $.entries[18].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[19].contentVersion: "8cf883c0add75c82f3deeaca59e07ca1939266e1"
+ $.entries[19].contentVersion: "169d6db6e1b48c8697604d09dbf8d468285cab02"
- $.entries[19].uri: "archiveQuests/Halloween2023.json"
+ $.entries[19].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[20].contentVersion: "79c143be5521fda908e03cc41f7ffd35e6ec6bf8"
+ $.entries[20].contentVersion: "28ae357545f6f64c44a1f4a0086764324aec2c7d"
- $.entries[20].uri: "archiveQuests/Halloween2024.json"
+ $.entries[20].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[21].contentVersion: "7f329f8e6e3a8c1c4fb35b42b8c9db02ee8db49e"
+ $.entries[21].contentVersion: "344daf4de9ec788e4d24dcdf327a91c89a4b7946"
- $.entries[21].uri: "archiveQuests/Spring2024.json"
+ $.entries[21].uri: "archiveQuests/FireflyV1.json"
- $.entries[22].contentVersion: "19349279d3432fc72d78bb62fa219d2dca6106dc"
+ $.entries[22].contentVersion: "76ce1f4a5ee03ae2d3ef3baa7991cb1ffee858be"
- $.entries[22].uri: "archiveQuests/Spring2025.json"
+ $.entries[22].uri: "archiveQuests/Halloween2021.json"
- $.entries[23].contentVersion: "faf4745a41b68ae0c0c252cecb1ba8a593b7c8a7"
+ $.entries[23].contentVersion: "e1cdc0a906a35e547df8325b32ae4f4a920aa38f"
- $.entries[23].uri: "archiveQuests/Summer2023.json"
+ $.entries[23].uri: "archiveQuests/Halloween2022.json"
- $.entries[24].contentVersion: "0a6606eb8a325b2a046acfa4140ef21188d5e2e2"
+ $.entries[24].contentVersion: "8ee0e817a8c10bc4a9cc6e004efb65b13d4903fa"
- $.entries[24].uri: "archiveQuests/Tome01.json"
+ $.entries[24].uri: "archiveQuests/Halloween2023.json"
- $.entries[25].contentVersion: "ce1dc526c417869ebd9f0a6d7110db8eb181726d"
+ $.entries[25].contentVersion: "796b24af030a9deb9fd0f42f46219d66fcb8d599"
- $.entries[25].uri: "archiveQuests/Tome02.json"
+ $.entries[25].uri: "archiveQuests/Halloween2024.json"
- $.entries[26].contentVersion: "92232ee462a32c7b44bf6f9b1104def60a04a218"
+ $.entries[26].contentVersion: "10571d92583cb6f8be48c5e2e21023b3670f60a9"
- $.entries[26].uri: "archiveQuests/Tome03.json"
+ $.entries[26].uri: "archiveQuests/Spring2024.json"
- $.entries[27].contentVersion: "be7ad3d8f56cacfeedd6f9670ccb878f1409dcc8"
+ $.entries[27].contentVersion: "7ccc34ba38fd0fd265575dcac1f5a93054da9594"
- $.entries[27].uri: "archiveQuests/Tome04.json"
+ $.entries[27].uri: "archiveQuests/Spring2025.json"
- $.entries[28].contentVersion: "39c505709dd38391206e1155860b760f21da749e"
+ $.entries[28].contentVersion: "d9c8da9f550f72e49cdbf0ca888e29fbdff7e63a"
- $.entries[28].uri: "archiveQuests/Tome05.json"
+ $.entries[28].uri: "archiveQuests/Summer2023.json"
- $.entries[29].contentVersion: "b588422a3ff780a031e13a5a41820378edf06e9c"
+ $.entries[29].contentVersion: "37d83aa657b4120fb4194298e0a71819df786a03"
- $.entries[29].uri: "archiveQuests/Tome06.json"
+ $.entries[29].uri: "archiveQuests/Tome01.json"
- $.entries[30].contentVersion: "1204007ae0752ac5417a7b9d5d31eacdc4ac364a"
+ $.entries[30].contentVersion: "bc5aae0e6c79b5808447dc733e56072685a03386"
- $.entries[30].uri: "archiveQuests/Tome07.json"
+ $.entries[30].uri: "archiveQuests/Tome02.json"
- $.entries[31].contentVersion: "6241e9293ee5937239bb0a29eca6fb4efe5eed96"
+ $.entries[31].contentVersion: "2d7d4be0c15c4727f8ef8b76d8cdaa9bae6b6e74"
- $.entries[31].uri: "archiveQuests/Tome08.json"
+ $.entries[31].uri: "archiveQuests/Tome03.json"
- $.entries[32].contentVersion: "1f75b5149594761592b0019d5e3432d867085dfe"
+ $.entries[32].contentVersion: "9cc82516b1b07b0177c8759b185fbf8d51cc5095"
- $.entries[32].uri: "archiveQuests/Tome09.json"
+ $.entries[32].uri: "archiveQuests/Tome04.json"
- $.entries[33].contentVersion: "0573437c0b409c9a7b6c7cc060a99472c65abc84"
+ $.entries[33].contentVersion: "b29f03ab839caf56730bb76543576ae1b76881a2"
- $.entries[33].uri: "archiveQuests/Tome10.json"
+ $.entries[33].uri: "archiveQuests/Tome05.json"
- $.entries[34].contentVersion: "ba07938dfd462bde958330f7356c6c2f20affac1"
+ $.entries[34].contentVersion: "9060c4dd7f5dd0cebf81d86d8a535cf8d3ea94fc"
- $.entries[34].uri: "archiveQuests/Tome11.json"
+ $.entries[34].uri: "archiveQuests/Tome06.json"
- $.entries[35].contentVersion: "9b44ae5c63ebd0f0c4b83cc05f709940dbb14452"
+ $.entries[35].contentVersion: "a5090c3e6e0e9c6ebc1c3015076a85fa950a645f"
- $.entries[35].uri: "archiveQuests/Tome12.json"
+ $.entries[35].uri: "archiveQuests/Tome07.json"
- $.entries[36].contentVersion: "6aed6fc92849dbf0dd68a2ceef5687da09cb24e8"
+ $.entries[36].contentVersion: "a5b0b9138870cb15a79649d744bdd2bf9ecb8726"
- $.entries[36].uri: "archiveQuests/Tome13.json"
+ $.entries[36].uri: "archiveQuests/Tome08.json"
- $.entries[37].contentVersion: "a6c2ba56b0882b15b30e8426107a0eef8f7e2226"
+ $.entries[37].contentVersion: "065e7adeb21f4adf8eff1eb6a9c238b11803aa10"
- $.entries[37].uri: "archiveQuests/Tome14.json"
+ $.entries[37].uri: "archiveQuests/Tome09.json"
- $.entries[38].contentVersion: "563515c7762f650b68aad7cfb3f54594b59613ba"
+ $.entries[38].contentVersion: "4177762171a2b86b5a5f44a605ef4f69984035af"
… 725 more change(s) — see the commit diff for everything
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Udon_W4].entries[0].weight: 15
+ $.featuredCard[id=Udon_W4].entries[0].weight: 14
- $.featuredCard[id=Udon_W4].entries[1].entryId: "10.1.2_Autumn_Fashion"
+ $.featuredCard[id=Udon_W4].entries[1].entryId: "Tome_8_Bundle"
- $.featuredCard[id=Udon_W4].entries[1].weight: 14
+ $.featuredCard[id=Udon_W4].entries[1].weight: 13
- $.featuredCard[id=Udon_W4].entries[2].entryId: "Tome_8_Bundle"
+ $.featuredCard[id=Udon_W4].entries[2].entryId: "10.1.0_GameplayExpo"
- $.featuredCard[id=Udon_W4].entries[2].type: "SpecialPack"
+ $.featuredCard[id=Udon_W4].entries[2].type: "Collection"
- $.featuredCard[id=Udon_W4].entries[2].weight: 13
+ $.featuredCard[id=Udon_W4].entries[2].weight: 12
- $.featuredCard[id=Udon_W4].entries[3].entryId: "10.1.0_GameplayExpo"
+ $.featuredCard[id=Udon_W4].entries[3].entryId: "10.1.0_Alien_Collection"
- $.featuredCard[id=Udon_W4].entries[3].weight: 12
+ $.featuredCard[id=Udon_W4].entries[3].weight: 11
- $.featuredCard[id=Udon_W4_1].entries[0].weight: 16
+ $.featuredCard[id=Udon_W4_1].entries[0].weight: 15
- $.featuredCard[id=Udon_W4_1].entries[1].entryId: "10.1.2_Autumn_Fashion"
+ $.featuredCard[id=Udon_W4_1].entries[1].entryId: "10.1.2_AutumnFashion"
- $.featuredCard[id=Udon_W4_1].entries[1].type: "SpecialPack"
+ $.featuredCard[id=Udon_W4_1].entries[1].type: "Collection"
- $.featuredCard[id=Udon_W4_1].entries[1].weight: 15
+ $.featuredCard[id=Udon_W4_1].entries[1].weight: 14
- $.featuredCard[id=Udon_W4_1].entries[2].entryId: "10.1.2_AutumnFashion"
+ $.featuredCard[id=Udon_W4_1].entries[2].entryId: "10.1.0_GameplayExpo"
- $.featuredCard[id=Udon_W4_1].entries[2].weight: 14
+ $.featuredCard[id=Udon_W4_1].entries[2].weight: 12
- $.featuredCard[id=Udon_W4_1].entries[3].entryId: "10.1.0_GameplayExpo"
+ $.featuredCard[id=Udon_W4_1].entries[3].entryId: "10.1.0_Alien_Collection"
- $.featuredCard[id=Udon_W4_1].entries[3].weight: 12
+ $.featuredCard[id=Udon_W4_1].entries[3].weight: 11
- $.featuredCard[id=Udon_W5].entries[1].entryId: "10.1.2_Blighted_Bundle"
+ $.featuredCard[id=Udon_W5].entries[1].entryId: "10.1.2_AutumnFashion"
- $.featuredCard[id=Udon_W5].entries[1].type: "SpecialPack"
+ $.featuredCard[id=Udon_W5].entries[1].type: "Collection"
- $.featuredCard[id=Udon_W5].entries[2].entryId: "10.1.2_AutumnFashion"
+ $.featuredCard[id=Udon_W5].entries[2].entryId: "10.1.0_Alien_Collection"
- $.featuredCustomizationRecommendations[id=Udon_W5]
- $.featuredCustomizationRecommendations[id=Udon_W6]
```

