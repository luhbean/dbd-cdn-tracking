# live · 9.1.2_2703397live

| | |
|---|---|
| Build date | 2025-08-25 14:27 UTC |
| CDN version | `9.1.2_2703397live-1756132028` |
| Key | `9.1.2_live` |
| Compared with | [9.1.3_2703197live](../9.1.3_2703197live/CHANGES.md) (2025-08-25 13:45 UTC) |

## Summary

**0** added · **1** modified · **2** removed · 201 unchanged

## Removed files

- `images/T_UI_CollectionBanner_PartyHard.png`
- `images/T_UI_SpecialPack_PartyHard.png`

## Modified files

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "ff437cc262850ea6df4a8ca3c5b64964964f7747"
+ $.entries[0].contentVersion: "e474279753aa454724f712a5eefdc89c9f4eddfd"
- $.entries[0].downloadStrategy: "preferRemote"
+ $.entries[0].downloadStrategy: "preferPackaged"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_PartyHard.T_UI_CollectionBanner_PartyHard"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_ModernBaroque.T_UI_SpecialPack_ModernBaroque"
- $.entries[0].uri: "images/T_UI_CollectionBanner_PartyHard.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_ModernBaroque.png"
- $.entries[1].contentVersion: "d16173b36a12e4a4ed82a5fc7650cf5d8a9f8bbf"
+ $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[1].downloadStrategy: "preferRemote"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_PartyHard.T_UI_SpecialPack_PartyHard"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[1].uri: "images/T_UI_SpecialPack_PartyHard.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[2].contentVersion: "ac639d7908ad347f04c9a1b884d23c6ea3afc8c0"
+ $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[2].downloadStrategy: "preferRemote"
+ $.entries[2].downloadStrategy: "preferPackaged"
- $.entries[2].enableChecksum: true
+ $.entries[2].enableChecksum: false
- $.entries[2].packagedPath: ""
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[2].schema: "s3ver://"
+ $.entries[2].schema: "s3verbin://"
- $.entries[2].uri: "catalog.json"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[3].contentVersion: "b4a6ffed58e6fcffb914939f09b9afa9f3da5268"
+ $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[3].downloadStrategy: "preferRemote"
+ $.entries[3].downloadStrategy: "preferPackaged"
- $.entries[3].enableChecksum: true
+ $.entries[3].enableChecksum: false
- $.entries[3].packagedPath: ""
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[3].schema: "s3ver://"
+ $.entries[3].schema: "s3verbin://"
- $.entries[3].uri: "bonusPointEventsContent.json"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[4].contentVersion: "807c86683510773f5b5540e21c207183cdd154a5"
+ $.entries[4].contentVersion: "5e5847bbaa9026df8974640c4221cb29dde49cd4"
- $.entries[4].downloadStrategy: "preferRemote"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_generator.T_UI_Tutorial_ImageBG_generator"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "freetoplay/NA/event.json"
+ $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_generator.png"
- $.entries[5].contentVersion: "807c86683510773f5b5540e21c207183cdd154a5"
+ $.entries[5].contentVersion: "8d51d9453eeec0693818a88be2da61dcea187d3b"
- $.entries[5].downloadStrategy: "preferRemote"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_chest.T_UI_Tutorial_ImageBG_chest"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "freetoplay/EU/event.json"
+ $.entries[5].uri: "images/T_UI_Tutorial_ImageBG_chest.png"
- $.entries[6].contentVersion: "8d5e48c3617ded37f978bed6f936b24ce4a4d84a"
+ $.entries[6].contentVersion: "ff437cc262850ea6df4a8ca3c5b64964964f7747"
- $.entries[6].enableChecksum: true
+ $.entries[6].enableChecksum: false
- $.entries[6].packagedPath: ""
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_PartyHard.T_UI_CollectionBanner_PartyHard"
- $.entries[6].schema: "s3ver://"
+ $.entries[6].schema: "s3verbin://"
- $.entries[6].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[6].uri: "images/T_UI_CollectionBanner_PartyHard.png"
- $.entries[7].contentVersion: "8ad9763626b20a285f86032454b700c0757ede9f"
+ $.entries[7].contentVersion: "d16173b36a12e4a4ed82a5fc7650cf5d8a9f8bbf"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_PartyHard.T_UI_SpecialPack_PartyHard"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[7].uri: "images/T_UI_SpecialPack_PartyHard.png"
- $.entries[8].contentVersion: "63b33bf43464cbc6c7cb6624ab4b2268f8b6bb82"
+ $.entries[8].contentVersion: "4cccc48530758d79097fbee62000032ff228b2f4"
- $.entries[8].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[8].uri: "catalog.json"
- $.entries[9].contentVersion: "f9c0c52ef3658340ea8c9b59454494ec8426dca0"
+ $.entries[9].contentVersion: "48e055df0359fad9a6a9262befc082d5af83b05e"
- $.entries[9].uri: "archiveQuests/CalamariV1.json"
+ $.entries[9].uri: "bonusPointEventsContent.json"
- $.entries[10].contentVersion: "a152f47cfedf53798388a9bcc47e2ff4926aeccd"
+ $.entries[10].contentVersion: "ae8a1f3e3f85348f3136bd89d3765c115722ce0f"
- $.entries[10].uri: "archiveQuests/CalamariV2.json"
+ $.entries[10].uri: "freetoplay/NA/event.json"
- $.entries[11].contentVersion: "20fc0a0a83e637d49dcf28e321dd0a225c5c420a"
+ $.entries[11].contentVersion: "ae8a1f3e3f85348f3136bd89d3765c115722ce0f"
- $.entries[11].uri: "archiveQuests/CalamariV3.json"
+ $.entries[11].uri: "freetoplay/EU/event.json"
- $.entries[12].contentVersion: "5a11bacc946ed364ed23d44fc56ead0b8dda574a"
+ $.entries[12].contentVersion: "8f6457105e669ccf0a8955196ade405ef6cc1ddc"
- $.entries[12].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2022.json"
- $.entries[13].contentVersion: "5b942b365217c66d205063b3803afb3a93b86d96"
+ $.entries[13].contentVersion: "8b5b87c312cc532ac8a440f3d5f3378b80c64313"
- $.entries[13].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[13].uri: "archiveQuests/Anniversary2023.json"
- $.entries[14].contentVersion: "fd773cf9c178d9e06982f15d465eef51c3df166b"
+ $.entries[14].contentVersion: "19d59e9ded874b3217bfea190386232201fc098d"
- $.entries[14].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[14].uri: "archiveQuests/Anniversary2024.json"
- $.entries[15].contentVersion: "d5bc15a7f80e1149a630aca336bd2a7f09462585"
+ $.entries[15].contentVersion: "4fe111368d7ba2ed35e6841cded0a4e5bdd92784"
- $.entries[15].uri: "archiveQuests/FireflyV1.json"
+ $.entries[15].uri: "archiveQuests/CalamariV1.json"
- $.entries[16].contentVersion: "f8d7b5c9cac6e56a352f6cc60bd89448fe6bdfc3"
+ $.entries[16].contentVersion: "928c9e0da989023fbe7f6688b6ad2dc6ed3188b9"
- $.entries[16].uri: "archiveQuests/Halloween2021.json"
+ $.entries[16].uri: "archiveQuests/CalamariV2.json"
- $.entries[17].contentVersion: "ee3ea9d3f96ceadf9cbaac4cf785bb7b99014628"
+ $.entries[17].contentVersion: "073b8cb998fd45e85967466a5639ead74fbe1a15"
- $.entries[17].uri: "archiveQuests/Halloween2022.json"
+ $.entries[17].uri: "archiveQuests/CalamariV3.json"
- $.entries[18].contentVersion: "9ce8211c3232135813a037398de1a77d92add255"
+ $.entries[18].contentVersion: "6bf902bc5a990a01fb8df77ed6cd8ee58c9c3fa3"
- $.entries[18].uri: "archiveQuests/Halloween2023.json"
+ $.entries[18].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[19].contentVersion: "d90f6ecee5119a351d84a54ce937cf44292c8596"
+ $.entries[19].contentVersion: "0d1ad33706b90e0a4de75c999302a4fbe78e175c"
- $.entries[19].uri: "archiveQuests/Halloween2024.json"
+ $.entries[19].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[20].contentVersion: "80be5626a97d561f41f1b5b432d35c5ddb3cf83f"
+ $.entries[20].contentVersion: "69969b335838f697962b46d7362089d6dcd28547"
- $.entries[20].uri: "archiveQuests/Spring2024.json"
+ $.entries[20].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[21].contentVersion: "8f05011ab417539f5df9235833669d43f0bb539f"
+ $.entries[21].contentVersion: "f02faf3fae195b4eb7e61a5baa6aed1c58e3e4d2"
- $.entries[21].uri: "archiveQuests/Spring2025.json"
+ $.entries[21].uri: "archiveQuests/FireflyV1.json"
- $.entries[22].contentVersion: "87cb4dfd91c3e8659efcd8f1b7a2dbb1f837cb85"
+ $.entries[22].contentVersion: "1e01cf158b036cc460be1df4c58f90f33be775db"
- $.entries[22].uri: "archiveQuests/Summer2023.json"
+ $.entries[22].uri: "archiveQuests/Halloween2021.json"
- $.entries[23].contentVersion: "b170191ae584f28f7aee8df2af8558ff4ab4b9bc"
+ $.entries[23].contentVersion: "08e1f926fc6f8fd89ac02e6f5acd4a6d94da9d2a"
- $.entries[23].uri: "archiveQuests/Tome01.json"
+ $.entries[23].uri: "archiveQuests/Halloween2022.json"
- $.entries[24].contentVersion: "37866ee77f5b0bf64388fc55c9666c453c7bf47f"
+ $.entries[24].contentVersion: "1f8005daf40b264c26ac0a55e364d399720af9ee"
- $.entries[24].uri: "archiveQuests/Tome02.json"
+ $.entries[24].uri: "archiveQuests/Halloween2023.json"
- $.entries[25].contentVersion: "990f486cff81f96429df95aa98e9101b69bd8534"
+ $.entries[25].contentVersion: "57080e7c9d0497671c2c9db17d1f0f2c4d1eb479"
- $.entries[25].uri: "archiveQuests/Tome03.json"
+ $.entries[25].uri: "archiveQuests/Halloween2024.json"
- $.entries[26].contentVersion: "86641472abbd427901d9c4c3416377ce84a2fc8f"
+ $.entries[26].contentVersion: "d9ac54e3c0e5570195654a07187294a77c4eeefb"
- $.entries[26].uri: "archiveQuests/Tome04.json"
+ $.entries[26].uri: "archiveQuests/Spring2024.json"
- $.entries[27].contentVersion: "62efe0dfc80e8a7457985bede64dbf3a87b8c2d3"
+ $.entries[27].contentVersion: "df9948e4e82a54c4b278ecffa6e65726a2439a91"
- $.entries[27].uri: "archiveQuests/Tome05.json"
+ $.entries[27].uri: "archiveQuests/Spring2025.json"
- $.entries[28].contentVersion: "44d4e86e48bd8b50a1ce1b581e7ad2a3101a077d"
+ $.entries[28].contentVersion: "cf09de5335894f8473cfc30eebe7f35df9a27f25"
- $.entries[28].uri: "archiveQuests/Tome06.json"
+ $.entries[28].uri: "archiveQuests/Summer2023.json"
- $.entries[29].contentVersion: "2f5851703b3b110d5827d28022bca97ba17afbb8"
+ $.entries[29].contentVersion: "7a6f407ee6d8a8fca015cea5d89eda056ffa2f4f"
- $.entries[29].uri: "archiveQuests/Tome07.json"
+ $.entries[29].uri: "archiveQuests/Tome01.json"
- $.entries[30].contentVersion: "385ecc465d26342ea882b87d25c217f9175bac00"
+ $.entries[30].contentVersion: "bd82358699ec38672c69d0414678c9db46e3d3d4"
- $.entries[30].uri: "archiveQuests/Tome08.json"
+ $.entries[30].uri: "archiveQuests/Tome02.json"
- $.entries[31].contentVersion: "3e56ab1b03848b78920a256dd1bb3ec2621c536a"
+ $.entries[31].contentVersion: "fdab3b6b1f0a4af21d2b873ade2312a73bc4cda3"
- $.entries[31].uri: "archiveQuests/Tome09.json"
+ $.entries[31].uri: "archiveQuests/Tome03.json"
- $.entries[32].contentVersion: "c783e3fc8623550e5f4f3abd53f48e69faf144a9"
+ $.entries[32].contentVersion: "82fa8655165f1e9faa8919623de3650871a8d19b"
- $.entries[32].uri: "archiveQuests/Tome10.json"
+ $.entries[32].uri: "archiveQuests/Tome04.json"
- $.entries[33].contentVersion: "e2c504216edd4432c4436dae7d3d8f47006e6190"
+ $.entries[33].contentVersion: "7ccdeea9a494bc96a3dc5ea07ebdd6158ff490c4"
- $.entries[33].uri: "archiveQuests/Tome11.json"
+ $.entries[33].uri: "archiveQuests/Tome05.json"
- $.entries[34].contentVersion: "9c4b0fce255a2c18d8ad33a4398113288cbcc0fa"
+ $.entries[34].contentVersion: "2932758b08c6a5a531924c7d95418e0cb6dd98c6"
- $.entries[34].uri: "archiveQuests/Tome12.json"
+ $.entries[34].uri: "archiveQuests/Tome06.json"
- $.entries[35].contentVersion: "aff6cbcb6f4a7e5019071d87a51e4a25d918260c"
+ $.entries[35].contentVersion: "bc38201f996a6ff40826c444c3440184c23d4ef7"
- $.entries[35].uri: "archiveQuests/Tome13.json"
+ $.entries[35].uri: "archiveQuests/Tome07.json"
- $.entries[36].contentVersion: "1417a3cba00b424c820efa3fd661af70539e1221"
+ $.entries[36].contentVersion: "24faf5b340c4c3a37a0fb3eae104fa9cd93a8b85"
- $.entries[36].uri: "archiveQuests/Tome14.json"
+ $.entries[36].uri: "archiveQuests/Tome08.json"
… 714 more change(s) — see the commit diff for everything
```

## Could not download

- `images/T_UI_CollectionBanner_PartyHard.png (HTTP 404)`
- `images/T_UI_SpecialPack_ModernBaroque.png (HTTP 404)`
- `images/T_UI_SpecialPack_PartyHard.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_GenQuest1.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_chest.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_cosmetic.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_generator.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_gift.png (HTTP 404)`

