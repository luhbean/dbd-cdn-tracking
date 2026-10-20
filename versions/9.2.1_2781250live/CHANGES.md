# live · 9.2.1_2781250live

| | |
|---|---|
| Build date | 2025-09-29 21:40 UTC |
| CDN version | `9.2.1_2781250live-1759182025` |
| Key | `9.2.1_live` |
| Compared with | [9.2.0_2781074live](../9.2.0_2781074live/CHANGES.md) (2025-09-29 19:13 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 202 unchanged

## Modified files

### [`collectionsCampaigns.json`](collectionsCampaigns.json)

[Full line-by-line diff](diffs/collectionsCampaigns.json.diff)

```diff
+ $.Campaigns.NOTLC
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "3c953ce75891597f0aadfd71e3dab2d16de12feb"
+ $.entries[0].contentVersion: "000fec334f10217255d8d1c60c8f213fc9fdd5b5"
- $.entries[0].downloadStrategy: "preferPackaged"
+ $.entries[0].downloadStrategy: "preferRemote"
- $.entries[0].enableChecksum: false
+ $.entries[0].enableChecksum: true
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_Specialpack_FallFashion.T_UI_Specialpack_FallFashion"
+ $.entries[0].packagedPath: ""
- $.entries[0].schema: "s3verbin://"
+ $.entries[0].schema: "s3ver://"
- $.entries[0].uri: "images/T_UI_Specialpack_FallFashion.png"
+ $.entries[0].uri: "catalog.json"
- $.entries[1].contentVersion: "88643dee1e6c57bd767605036473e939094fccf9"
+ $.entries[1].contentVersion: "0445e9b53741e73e096eaa60db9dc0935928c86c"
- $.entries[1].downloadStrategy: "preferPackaged"
+ $.entries[1].downloadStrategy: "preferRemote"
- $.entries[1].enableChecksum: false
+ $.entries[1].enableChecksum: true
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_Tome5.T_UI_SpecialPack_Tome5"
+ $.entries[1].packagedPath: ""
- $.entries[1].schema: "s3verbin://"
+ $.entries[1].schema: "s3ver://"
- $.entries[1].uri: "images/T_UI_SpecialPack_Tome5.png"
+ $.entries[1].uri: "bonusPointEventsContent.json"
- $.entries[2].contentVersion: "8a15d416ef70b4c552d109bc091b52cbda5ad932"
+ $.entries[2].contentVersion: "064280961f401d507030a56aa3edb1f7fe58e686"
- $.entries[2].downloadStrategy: "preferPackaged"
+ $.entries[2].downloadStrategy: "preferRemote"
- $.entries[2].enableChecksum: false
+ $.entries[2].enableChecksum: true
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_Tome6.T_UI_SpecialPack_Tome6"
+ $.entries[2].packagedPath: ""
- $.entries[2].schema: "s3verbin://"
+ $.entries[2].schema: "s3ver://"
- $.entries[2].uri: "images/T_UI_SpecialPack_Tome6.png"
+ $.entries[2].uri: "freetoplay/NA/event.json"
- $.entries[3].contentVersion: "a0e2201ffb426f174ff31dd43e4d3d74661912f0"
+ $.entries[3].contentVersion: "064280961f401d507030a56aa3edb1f7fe58e686"
- $.entries[3].downloadStrategy: "preferPackaged"
+ $.entries[3].downloadStrategy: "preferRemote"
- $.entries[3].enableChecksum: false
+ $.entries[3].enableChecksum: true
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_SinisterGrace.T_UI_ChapterBundle_SinisterGrace"
+ $.entries[3].packagedPath: ""
- $.entries[3].schema: "s3verbin://"
+ $.entries[3].schema: "s3ver://"
- $.entries[3].uri: "images/T_UI_ChapterBundle_SinisterGrace.png"
+ $.entries[3].uri: "freetoplay/EU/event.json"
- $.entries[4].contentVersion: "3c953ce75891597f0aadfd71e3dab2d16de12feb"
+ $.entries[4].contentVersion: "da04b229f98654aa4512586974f07ebc1a9ac6e3"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].enableChecksum: false
+ $.entries[4].enableChecksum: true
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_Specialpack_FallFashion.T_UI_Specialpack_FallFashion"
+ $.entries[4].packagedPath: ""
- $.entries[4].schema: "s3verbin://"
+ $.entries[4].schema: "s3ver://"
- $.entries[4].uri: "images/T_UI_Specialpack_FallFashion.png"
+ $.entries[4].uri: "archiveQuests/Anniversary2022.json"
- $.entries[5].contentVersion: "5e907dd9dc410eb9a1ff6bc1973ae825586f6887"
+ $.entries[5].contentVersion: "56214b6a9ea5453ee0d0dc53d2d6ae258cfc7e2d"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].enableChecksum: false
+ $.entries[5].enableChecksum: true
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_SinisterGrace.T_UI_CollectionBanner_SinisterGrace"
+ $.entries[5].packagedPath: ""
- $.entries[5].schema: "s3verbin://"
+ $.entries[5].schema: "s3ver://"
- $.entries[5].uri: "images/T_UI_CollectionBanner_SinisterGrace.png"
+ $.entries[5].uri: "archiveQuests/Anniversary2023.json"
- $.entries[6].contentVersion: "fbc8241b92a884ac6d866433ada0f9db766c66bc"
+ $.entries[6].contentVersion: "410d854d3e6f2f53514ceb5293f6461cac851229"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_SinisterGrace.T_UI_SpecialPack_SinisterGrace"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_SpecialPack_SinisterGrace.png"
+ $.entries[6].uri: "archiveQuests/Anniversary2024.json"
- $.entries[7].contentVersion: "4deb0391cf08e15cd3c40d0cde2a17a1e284b1ae"
+ $.entries[7].contentVersion: "23a39d3a2127b3da974e83740c890c974a1ba3c7"
- $.entries[7].downloadStrategy: "preferPackaged"
+ $.entries[7].downloadStrategy: "preferRemote"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_NOTLC.T_UI_CollectionBanner_NOTLC"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_CollectionBanner_NOTLC.png"
+ $.entries[7].uri: "archiveQuests/CalamariV1.json"
- $.entries[8].contentVersion: "a0eb39e204ac7a589e860c5759293da82ed5b143"
+ $.entries[8].contentVersion: "521594505706afe1bee97d6e817a24bea93746be"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_NOTLC.T_UI_SpecialPack_NOTLC"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_SpecialPack_NOTLC.png"
+ $.entries[8].uri: "archiveQuests/CalamariV2.json"
- $.entries[9].contentVersion: "ff437cc262850ea6df4a8ca3c5b64964964f7747"
+ $.entries[9].contentVersion: "960dcd4b8b314ae81bffd306d1d30d5e7203b6d5"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_PartyHard.T_UI_CollectionBanner_PartyHard"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_CollectionBanner_PartyHard.png"
+ $.entries[9].uri: "archiveQuests/CalamariV3.json"
- $.entries[10].contentVersion: "d16173b36a12e4a4ed82a5fc7650cf5d8a9f8bbf"
+ $.entries[10].contentVersion: "8e5a21f308b79af1e10e67de3356ec99fd8a2334"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].enableChecksum: false
+ $.entries[10].enableChecksum: true
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_PartyHard.T_UI_SpecialPack_PartyHard"
+ $.entries[10].packagedPath: ""
- $.entries[10].schema: "s3verbin://"
+ $.entries[10].schema: "s3ver://"
- $.entries[10].uri: "images/T_UI_SpecialPack_PartyHard.png"
+ $.entries[10].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[11].contentVersion: "81206bb8a704c17f8088b96c259e78b04876a848"
+ $.entries[11].contentVersion: "782077a5aa8a290b23149168bf3d03962da69f50"
- $.entries[11].uri: "catalog.json"
+ $.entries[11].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[12].contentVersion: "a3ae9f58d0dee10bafa82f215593ff417d538e00"
+ $.entries[12].contentVersion: "e4fb16835af6347a0f5b46e151f78960f4441a04"
- $.entries[12].uri: "bonusPointEventsContent.json"
+ $.entries[12].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[13].contentVersion: "2b59e9761cec12be445ee8cca0a385e3504cb620"
+ $.entries[13].contentVersion: "ca480b5f1d4bf1e51d1d27a49c88f093db3f5df0"
- $.entries[13].uri: "freetoplay/NA/event.json"
+ $.entries[13].uri: "archiveQuests/FireflyV1.json"
- $.entries[14].contentVersion: "2b59e9761cec12be445ee8cca0a385e3504cb620"
+ $.entries[14].contentVersion: "3c240b344ff4349391b8b42b968b573ff8d27298"
- $.entries[14].uri: "freetoplay/EU/event.json"
+ $.entries[14].uri: "archiveQuests/Halloween2021.json"
- $.entries[15].contentVersion: "38a216303d6dda39cf30c4d2d786e4dda581597d"
+ $.entries[15].contentVersion: "5247dffd42a2145b907167a48226e957e962cd25"
- $.entries[15].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[15].uri: "archiveQuests/Halloween2022.json"
- $.entries[16].contentVersion: "054edff758b733e20dd587cfa33850a16595e39b"
+ $.entries[16].contentVersion: "96d08a9965d021b82c5f9c80858be90ac703bc3c"
- $.entries[16].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[16].uri: "archiveQuests/Halloween2023.json"
- $.entries[17].contentVersion: "4b3ae0806f1c01fceef0bd2835c47a4d41747aa8"
+ $.entries[17].contentVersion: "6ea2b2712abcdda9c672c0a61e2c6c947e8fd1b1"
- $.entries[17].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[17].uri: "archiveQuests/Halloween2024.json"
- $.entries[18].contentVersion: "baef1757018d93edaa5a4f9b61dce5a6edd3299b"
+ $.entries[18].contentVersion: "51bb2cf7e35e2937f2db1401251bd02d7bc5ad23"
- $.entries[18].uri: "archiveQuests/CalamariV1.json"
+ $.entries[18].uri: "archiveQuests/Spring2024.json"
- $.entries[19].contentVersion: "9de2b4ac74d629f27ec4b2490b92ea1a417ee37d"
+ $.entries[19].contentVersion: "276580f6e67ab970b724c7d3ff863a9d363b8b94"
- $.entries[19].uri: "archiveQuests/CalamariV2.json"
+ $.entries[19].uri: "archiveQuests/Spring2025.json"
- $.entries[20].contentVersion: "6c7e74aa941f63311638f9893ecbd86e3e8322fa"
+ $.entries[20].contentVersion: "a483672fc8c3667d2079e365020b91e8dbcbf796"
- $.entries[20].uri: "archiveQuests/CalamariV3.json"
+ $.entries[20].uri: "archiveQuests/Summer2023.json"
- $.entries[21].contentVersion: "74f3f3c1d90061faa39c3b4d01eb43443685c913"
+ $.entries[21].contentVersion: "d9832f5fd1fe3f63ee7ae69df2927755272864dd"
- $.entries[21].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[21].uri: "archiveQuests/Tome01.json"
- $.entries[22].contentVersion: "a8777aa9d56731007f764d8db72edd760d9f472a"
+ $.entries[22].contentVersion: "4a03119bce8b9cac64460ded149e976824721a92"
- $.entries[22].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[22].uri: "archiveQuests/Tome02.json"
- $.entries[23].contentVersion: "8bb66c93ec94f49bfe15f38642247168d6c42d3e"
+ $.entries[23].contentVersion: "6171f928a73c843f21bb35a88ddd0e0a3f50d83f"
- $.entries[23].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[23].uri: "archiveQuests/Tome03.json"
- $.entries[24].contentVersion: "d20fefecc6996f8e8e470c61e3dd7ef3249cffca"
+ $.entries[24].contentVersion: "636554b90bd6a84ee657d3423db5a6f437543f69"
- $.entries[24].uri: "archiveQuests/FireflyV1.json"
+ $.entries[24].uri: "archiveQuests/Tome04.json"
- $.entries[25].contentVersion: "9a7b9d0f63aab4d1f0fe03128489fd18b86b70a1"
+ $.entries[25].contentVersion: "741b740b5c08793c5dc9659d8dc81a7dd5dcef1b"
- $.entries[25].uri: "archiveQuests/Halloween2021.json"
+ $.entries[25].uri: "archiveQuests/Tome05.json"
- $.entries[26].contentVersion: "5c78246a1489a53155a418ee3045c952f0be1097"
+ $.entries[26].contentVersion: "9c46e0366d0c1afc06d209c27608b1ae549dcd8a"
- $.entries[26].uri: "archiveQuests/Halloween2022.json"
+ $.entries[26].uri: "archiveQuests/Tome06.json"
- $.entries[27].contentVersion: "f7f0c3923d2bc55db95d000e2d8b2e2b2866fa07"
+ $.entries[27].contentVersion: "47e39cd05cb2dc9b4b87dc573d8c58ded963e7df"
- $.entries[27].uri: "archiveQuests/Halloween2023.json"
+ $.entries[27].uri: "archiveQuests/Tome07.json"
… 789 more change(s) — see the commit diff for everything
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCustomizationRecommendations[id=MapleW3]
```

