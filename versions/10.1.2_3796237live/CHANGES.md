# live · 10.1.2_3796237live

| | |
|---|---|
| Build date | 2026-09-18 14:03 UTC |
| CDN version | `10.1.2_3796237live-1789740223` |
| Key | `10.1.2_live` |
| Compared with | [10.1.2_3793194live](../10.1.2_3793194live/CHANGES.md) (2026-09-17 20:20 UTC) |

## Summary

**2** added · **3** modified · **0** removed · 208 unchanged

## New or updated images

<a href="images/T_UI_SpecialPack_SAW_Bundle.png"><img src="images/T_UI_SpecialPack_SAW_Bundle.png" alt="T_UI_SpecialPack_SAW_Bundle.png" width="240"></a>
<a href="images/T_UI_SpecialPack_Tome8.png"><img src="images/T_UI_SpecialPack_Tome8.png" alt="T_UI_SpecialPack_Tome8.png" width="240"></a>

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=SAW_Bundle]
+ $[id=Tome_8_Bundle]
+ $[id=FM_outfit_015].metaData.temporaryDiscounts
+ $[id=K23_outfit_024].metaData.temporaryDiscounts
+ $[id=K32_outfit_010].metaData.temporaryDiscounts
+ $[id=KK_outfit_020].metaData.temporaryDiscounts
+ $[id=MS_outfit_015].metaData.temporaryDiscounts
+ $[id=NK_outfit_032].metaData.temporaryDiscounts
+ $[id=SwedenSurvivor_outfit_026].metaData.temporaryDiscounts
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "50957483ec91d6b5c2d6930d4fbec8f379e11c8b"
+ $.entries[0].contentVersion: "cf64d25de2095c9750fa33b18ff694834057aa78"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_HallowedBlight_Jason.T_UI_CollectionBanner_HallowedBlight_Jason"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_SAW_Bundle.T_UI_SpecialPack_SAW_Bundle"
- $.entries[0].uri: "images/T_UI_CollectionBanner_HallowedBlight_Jason.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_SAW_Bundle.png"
- $.entries[1].contentVersion: "fe3f266d086baf8ab0546e1d2715211f7fa708d5"
+ $.entries[1].contentVersion: "4e1a37960b1b0020f3e674a28350cd20af5f775b"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_HallowedBlight_Jason.T_UI_SpecialPack_HallowedBlight_Jason"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_Tome8.T_UI_SpecialPack_Tome8"
- $.entries[1].uri: "images/T_UI_SpecialPack_HallowedBlight_Jason.png"
+ $.entries[1].uri: "images/T_UI_SpecialPack_Tome8.png"
- $.entries[2].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[2].contentVersion: "50957483ec91d6b5c2d6930d4fbec8f379e11c8b"
- $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_HallowedBlight_Jason.T_UI_CollectionBanner_HallowedBlight_Jason"
- $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[2].uri: "images/T_UI_CollectionBanner_HallowedBlight_Jason.png"
- $.entries[3].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[3].contentVersion: "fe3f266d086baf8ab0546e1d2715211f7fa708d5"
- $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_HallowedBlight_Jason.T_UI_SpecialPack_HallowedBlight_Jason"
- $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[3].uri: "images/T_UI_SpecialPack_HallowedBlight_Jason.png"
- $.entries[4].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[4].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[5].contentVersion: "50957483ec91d6b5c2d6930d4fbec8f379e11c8b"
+ $.entries[5].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_HallowedBlight_Jason.T_UI_CollectionBanner_HallowedBlight_Jason"
+ $.entries[5].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[5].uri: "images/T_UI_CollectionBanner_HallowedBlight_Jason.png"
+ $.entries[5].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[6].contentVersion: "fe3f266d086baf8ab0546e1d2715211f7fa708d5"
+ $.entries[6].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_HallowedBlight_Jason.T_UI_SpecialPack_HallowedBlight_Jason"
+ $.entries[6].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[6].uri: "images/T_UI_SpecialPack_HallowedBlight_Jason.png"
+ $.entries[6].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[7].contentVersion: "e0e0d66e18bb076fd25c708fd781a5163a13939f"
+ $.entries[7].contentVersion: "50957483ec91d6b5c2d6930d4fbec8f379e11c8b"
- $.entries[7].downloadStrategy: "preferRemote"
+ $.entries[7].downloadStrategy: "preferPackaged"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_HallowedBlight_Jason.T_UI_CollectionBanner_HallowedBlight_Jason"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "catalog.json"
+ $.entries[7].uri: "images/T_UI_CollectionBanner_HallowedBlight_Jason.png"
- $.entries[8].contentVersion: "33b08ab576345ec86e26472b9411c56c81dc528b"
+ $.entries[8].contentVersion: "fe3f266d086baf8ab0546e1d2715211f7fa708d5"
- $.entries[8].downloadStrategy: "preferRemote"
+ $.entries[8].downloadStrategy: "preferPackaged"
- $.entries[8].enableChecksum: true
+ $.entries[8].enableChecksum: false
- $.entries[8].packagedPath: ""
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_HallowedBlight_Jason.T_UI_SpecialPack_HallowedBlight_Jason"
- $.entries[8].schema: "s3ver://"
+ $.entries[8].schema: "s3verbin://"
- $.entries[8].uri: "bonusPointEventsContent.json"
+ $.entries[8].uri: "images/T_UI_SpecialPack_HallowedBlight_Jason.png"
- $.entries[9].contentVersion: "95d4affcdcad2de1f4eb0144d08561461d1dd971"
+ $.entries[9].contentVersion: "bd7ad53575caf58fd815c0f5da706e35aace2254"
- $.entries[9].uri: "freetoplay/NA/event.json"
+ $.entries[9].uri: "catalog.json"
- $.entries[10].contentVersion: "95d4affcdcad2de1f4eb0144d08561461d1dd971"
+ $.entries[10].contentVersion: "33b08ab576345ec86e26472b9411c56c81dc528b"
- $.entries[10].uri: "freetoplay/EU/event.json"
+ $.entries[10].uri: "bonusPointEventsContent.json"
- $.entries[11].contentVersion: "ed6c0d8e2b19e05f3c3b8f5f827c91649527ef52"
+ $.entries[11].contentVersion: "95d4affcdcad2de1f4eb0144d08561461d1dd971"
- $.entries[11].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[11].uri: "freetoplay/NA/event.json"
- $.entries[12].contentVersion: "828234cff37360ac44089af8a5fce20c936ae7ea"
+ $.entries[12].contentVersion: "95d4affcdcad2de1f4eb0144d08561461d1dd971"
- $.entries[12].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[12].uri: "freetoplay/EU/event.json"
- $.entries[13].contentVersion: "b8c6e34c138c8254da327d925c8286613b7e1196"
+ $.entries[13].contentVersion: "ed6c0d8e2b19e05f3c3b8f5f827c91649527ef52"
- $.entries[13].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[13].uri: "archiveQuests/Anniversary2022.json"
- $.entries[14].contentVersion: "5206d7ac243b495101a44b463db367f70b879b3f"
+ $.entries[14].contentVersion: "828234cff37360ac44089af8a5fce20c936ae7ea"
- $.entries[14].uri: "archiveQuests/CalamariV1.json"
+ $.entries[14].uri: "archiveQuests/Anniversary2023.json"
- $.entries[15].contentVersion: "adb9cefe00e088e9aad3e7685f36c860930b64ea"
+ $.entries[15].contentVersion: "b8c6e34c138c8254da327d925c8286613b7e1196"
- $.entries[15].uri: "archiveQuests/CalamariV2.json"
+ $.entries[15].uri: "archiveQuests/Anniversary2024.json"
- $.entries[16].contentVersion: "40d150294f1451a4f8136847342fe9821259ef4f"
+ $.entries[16].contentVersion: "5206d7ac243b495101a44b463db367f70b879b3f"
- $.entries[16].uri: "archiveQuests/CalamariV3.json"
+ $.entries[16].uri: "archiveQuests/CalamariV1.json"
- $.entries[17].contentVersion: "c33ced63a2ae92fb054f30407f524cc29712c406"
+ $.entries[17].contentVersion: "adb9cefe00e088e9aad3e7685f36c860930b64ea"
- $.entries[17].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[17].uri: "archiveQuests/CalamariV2.json"
- $.entries[18].contentVersion: "1feb0b7951c7513f7c68c86b1d8ae030d1fb10d5"
+ $.entries[18].contentVersion: "40d150294f1451a4f8136847342fe9821259ef4f"
- $.entries[18].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[18].uri: "archiveQuests/CalamariV3.json"
- $.entries[19].contentVersion: "8b1087ee9fc1e3e9e02c85ad419f8bcccf6486f1"
+ $.entries[19].contentVersion: "c33ced63a2ae92fb054f30407f524cc29712c406"
- $.entries[19].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[19].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[20].contentVersion: "d67dedd78d161d2c1a9d5486082096913524cf69"
+ $.entries[20].contentVersion: "1feb0b7951c7513f7c68c86b1d8ae030d1fb10d5"
- $.entries[20].uri: "archiveQuests/FireflyV1.json"
+ $.entries[20].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[21].contentVersion: "20b1901dc05b99cc1822445fd15300ed850e9737"
+ $.entries[21].contentVersion: "8b1087ee9fc1e3e9e02c85ad419f8bcccf6486f1"
- $.entries[21].uri: "archiveQuests/Halloween2021.json"
+ $.entries[21].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[22].contentVersion: "c028ed930b25455e6754372a1b01d2c40c2eea58"
+ $.entries[22].contentVersion: "d67dedd78d161d2c1a9d5486082096913524cf69"
- $.entries[22].uri: "archiveQuests/Halloween2022.json"
+ $.entries[22].uri: "archiveQuests/FireflyV1.json"
- $.entries[23].contentVersion: "5cf99c72371a0a143aa24f2f7c0c24291adf9429"
+ $.entries[23].contentVersion: "20b1901dc05b99cc1822445fd15300ed850e9737"
- $.entries[23].uri: "archiveQuests/Halloween2023.json"
+ $.entries[23].uri: "archiveQuests/Halloween2021.json"
- $.entries[24].contentVersion: "47ab95056bc77824677debfd03fdad7a831ef87a"
+ $.entries[24].contentVersion: "c028ed930b25455e6754372a1b01d2c40c2eea58"
- $.entries[24].uri: "archiveQuests/Halloween2024.json"
+ $.entries[24].uri: "archiveQuests/Halloween2022.json"
- $.entries[25].contentVersion: "db4a819f74db8c33a2188e4ae01014053ce6b28e"
+ $.entries[25].contentVersion: "5cf99c72371a0a143aa24f2f7c0c24291adf9429"
- $.entries[25].uri: "archiveQuests/Spring2024.json"
+ $.entries[25].uri: "archiveQuests/Halloween2023.json"
- $.entries[26].contentVersion: "410bffda1bd2e11a285e809005bef3c010ad5974"
+ $.entries[26].contentVersion: "47ab95056bc77824677debfd03fdad7a831ef87a"
- $.entries[26].uri: "archiveQuests/Spring2025.json"
+ $.entries[26].uri: "archiveQuests/Halloween2024.json"
- $.entries[27].contentVersion: "f591417b16e610a9c2eaa8da51c3507a381348ef"
+ $.entries[27].contentVersion: "db4a819f74db8c33a2188e4ae01014053ce6b28e"
- $.entries[27].uri: "archiveQuests/Summer2023.json"
+ $.entries[27].uri: "archiveQuests/Spring2024.json"
- $.entries[28].contentVersion: "08a18bd37fb29609068d94666098444a32186780"
+ $.entries[28].contentVersion: "410bffda1bd2e11a285e809005bef3c010ad5974"
- $.entries[28].uri: "archiveQuests/Tome01.json"
+ $.entries[28].uri: "archiveQuests/Spring2025.json"
- $.entries[29].contentVersion: "2762069a6939a68ea984520297b936d755ce0417"
+ $.entries[29].contentVersion: "f591417b16e610a9c2eaa8da51c3507a381348ef"
- $.entries[29].uri: "archiveQuests/Tome02.json"
+ $.entries[29].uri: "archiveQuests/Summer2023.json"
- $.entries[30].contentVersion: "e750d79c818c82dc65dbe3e657e82fab9b620309"
+ $.entries[30].contentVersion: "08a18bd37fb29609068d94666098444a32186780"
- $.entries[30].uri: "archiveQuests/Tome03.json"
+ $.entries[30].uri: "archiveQuests/Tome01.json"
- $.entries[31].contentVersion: "8ff1b882e879cedb851495a650c663102239a6a0"
+ $.entries[31].contentVersion: "2762069a6939a68ea984520297b936d755ce0417"
- $.entries[31].uri: "archiveQuests/Tome04.json"
+ $.entries[31].uri: "archiveQuests/Tome02.json"
- $.entries[32].contentVersion: "4af903a2c911c1d4ff69fd2f4444cbb921f65b09"
+ $.entries[32].contentVersion: "e750d79c818c82dc65dbe3e657e82fab9b620309"
- $.entries[32].uri: "archiveQuests/Tome05.json"
+ $.entries[32].uri: "archiveQuests/Tome03.json"
- $.entries[33].contentVersion: "9b574877f8953ccbdd136b6721e68e49df76eab5"
+ $.entries[33].contentVersion: "8ff1b882e879cedb851495a650c663102239a6a0"
- $.entries[33].uri: "archiveQuests/Tome06.json"
+ $.entries[33].uri: "archiveQuests/Tome04.json"
- $.entries[34].contentVersion: "fc919d3dd465972d0354d73bf427f7ccad3ac832"
+ $.entries[34].contentVersion: "4af903a2c911c1d4ff69fd2f4444cbb921f65b09"
- $.entries[34].uri: "archiveQuests/Tome07.json"
+ $.entries[34].uri: "archiveQuests/Tome05.json"
- $.entries[35].contentVersion: "026f033b1546798f6f6acaaa6b9a980570b77efb"
+ $.entries[35].contentVersion: "9b574877f8953ccbdd136b6721e68e49df76eab5"
- $.entries[35].uri: "archiveQuests/Tome08.json"
+ $.entries[35].uri: "archiveQuests/Tome06.json"
- $.entries[36].contentVersion: "bcbc9d692577ae1a974a7e52046ba60905b9423a"
+ $.entries[36].contentVersion: "fc919d3dd465972d0354d73bf427f7ccad3ac832"
- $.entries[36].uri: "archiveQuests/Tome09.json"
+ $.entries[36].uri: "archiveQuests/Tome07.json"
- $.entries[37].contentVersion: "8e0642ca5151ce76f9ab72bb851d2cdc79974179"
+ $.entries[37].contentVersion: "026f033b1546798f6f6acaaa6b9a980570b77efb"
- $.entries[37].uri: "archiveQuests/Tome10.json"
+ $.entries[37].uri: "archiveQuests/Tome08.json"
- $.entries[38].contentVersion: "3e9a522a77ff0b8a502ae13c9a5df9018a7cbf8e"
+ $.entries[38].contentVersion: "bcbc9d692577ae1a974a7e52046ba60905b9423a"
- $.entries[38].uri: "archiveQuests/Tome11.json"
+ $.entries[38].uri: "archiveQuests/Tome09.json"
- $.entries[39].contentVersion: "e6b686f87e946096f80095119d664b85a67a4587"
+ $.entries[39].contentVersion: "8e0642ca5151ce76f9ab72bb851d2cdc79974179"
- $.entries[39].uri: "archiveQuests/Tome12.json"
+ $.entries[39].uri: "archiveQuests/Tome10.json"
- $.entries[40].contentVersion: "400943e513cab9dbe6fa7eb4aa814fbb5f363e9a"
+ $.entries[40].contentVersion: "3e9a522a77ff0b8a502ae13c9a5df9018a7cbf8e"
- $.entries[40].uri: "archiveQuests/Tome13.json"
+ $.entries[40].uri: "archiveQuests/Tome11.json"
- $.entries[41].contentVersion: "bc07d7919c93efbfda92c5ed85e814f0125b88a0"
+ $.entries[41].contentVersion: "e6b686f87e946096f80095119d664b85a67a4587"
- $.entries[41].uri: "archiveQuests/Tome14.json"
+ $.entries[41].uri: "archiveQuests/Tome12.json"
- $.entries[42].contentVersion: "b53b55edadb7ca90bca77f32aa92809818ef456a"
+ $.entries[42].contentVersion: "400943e513cab9dbe6fa7eb4aa814fbb5f363e9a"
… 700 more change(s) — see the commit diff for everything
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Udon_W3_1]
+ $.featuredCard[id=Udon_W4_1]
- $.featuredCard[id=Udon_W3].activeTo: "2026-09-22T15:00:00"
+ $.featuredCard[id=Udon_W3].activeTo: "2026-09-18T15:00:00"
- $.featuredCard[id=Udon_W3].activeToInMs: 1790089200000
+ $.featuredCard[id=Udon_W3].activeToInMs: 1789743600000
- $.featuredCard[id=Udon_W4].activeTo: "2026-10-01T15:00:00"
+ $.featuredCard[id=Udon_W4].activeTo: "2026-09-25T15:00:00"
- $.featuredCard[id=Udon_W4].activeToInMs: 1790866800000
+ $.featuredCard[id=Udon_W4].activeToInMs: 1790348400000
- $.featuredCard[id=Udon_W4].entries[0].weight: 13
+ $.featuredCard[id=Udon_W4].entries[0].weight: 14
- $.featuredCard[id=Udon_W4].entries[1].entryId: "10.1.0_GameplayExpo"
+ $.featuredCard[id=Udon_W4].entries[1].entryId: "Tome_8_Bundle"
- $.featuredCard[id=Udon_W4].entries[1].type: "Collection"
+ $.featuredCard[id=Udon_W4].entries[1].type: "SpecialPack"
- $.featuredCard[id=Udon_W4].entries[1].weight: 12
+ $.featuredCard[id=Udon_W4].entries[1].weight: 13
- $.featuredCard[id=Udon_W4].entries[2].entryId: "10.1.0_Alien_Collection"
+ $.featuredCard[id=Udon_W4].entries[2].entryId: "10.1.0_GameplayExpo"
- $.featuredCard[id=Udon_W4].entries[2].weight: 11
+ $.featuredCard[id=Udon_W4].entries[2].weight: 12
- $.featuredCard[id=Udon_W4].entries[3].entryId: "10.1.0_ChorusOfSin"
+ $.featuredCard[id=Udon_W4].entries[3].entryId: "10.1.0_Alien_Collection"
- $.featuredCard[id=Udon_W4].entries[3].weight: 10
+ $.featuredCard[id=Udon_W4].entries[3].weight: 11
```

