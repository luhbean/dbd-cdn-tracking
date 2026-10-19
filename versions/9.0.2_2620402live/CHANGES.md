# live · 9.0.2_2620402live

| | |
|---|---|
| Build date | 2025-07-15 20:53 UTC |
| CDN version | `9.0.2_2620402live-1752612804` |
| Key | `9.0.2_live` |
| Compared with | [9.0.2_2619854live](../9.0.2_2619854live/CHANGES.md) (2025-07-15 18:42 UTC) |

## Summary

**0** added · **2** modified · **0** removed · 200 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=Waterfront_Massacre_Bundle]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[1].contentVersion: "a0a0a03250bc8a8b03319aefdadb770c2ca7b193"
+ $.entries[1].contentVersion: "18860694ec28b762cec51dd8c052dcdf43a6d14b"
- $.entries[1].downloadStrategy: "preferPackaged"
+ $.entries[1].downloadStrategy: "preferRemote"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_BouletBrothers.T_UI_CollectionBanner_BouletBrothers"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_WaterfrontMassacreBundle.T_UI_SpecialPack_WaterfrontMassacreBundle"
- $.entries[1].uri: "images/T_UI_CollectionBanner_BouletBrothers.png"
+ $.entries[1].uri: "images/T_UI_SpecialPack_WaterfrontMassacreBundle.png"
- $.entries[2].contentVersion: "ae989e234341b7b4c634b497cfc79a60ce4cc9e8"
+ $.entries[2].contentVersion: "a0a0a03250bc8a8b03319aefdadb770c2ca7b193"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_BouletBrothers.T_UI_SpecialPack_BouletBrothers"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_BouletBrothers.T_UI_CollectionBanner_BouletBrothers"
- $.entries[2].uri: "images/T_UI_SpecialPack_BouletBrothers.png"
+ $.entries[2].uri: "images/T_UI_CollectionBanner_BouletBrothers.png"
- $.entries[3].contentVersion: "25ff6fc37e10dad46ab67f052faa5b7ea64b00de"
+ $.entries[3].contentVersion: "ae989e234341b7b4c634b497cfc79a60ce4cc9e8"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_WaterfrontMassacreXenomorph.T_UI_SpecialPack_WaterfrontMassacreXenomorph"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_BouletBrothers.T_UI_SpecialPack_BouletBrothers"
- $.entries[3].uri: "images/T_UI_SpecialPack_WaterfrontMassacreXenomorph.png"
+ $.entries[3].uri: "images/T_UI_SpecialPack_BouletBrothers.png"
- $.entries[4].contentVersion: "73a4d8553f28e7019e43258b59f836ced66874a9"
+ $.entries[4].contentVersion: "25ff6fc37e10dad46ab67f052faa5b7ea64b00de"
- $.entries[4].downloadStrategy: "preferRemote"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_WaterfrontMassacreXenomorph.T_UI_SpecialPack_WaterfrontMassacreXenomorph"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "catalog.json"
+ $.entries[4].uri: "images/T_UI_SpecialPack_WaterfrontMassacreXenomorph.png"
- $.entries[5].contentVersion: "b9fdb4fbb94996a12e7af5a8bb11bcb20697501a"
+ $.entries[5].contentVersion: "ffdcefc1bb9fc2184e9f8310f72d459e4b22baae"
- $.entries[5].uri: "bonusPointEventsContent.json"
+ $.entries[5].uri: "catalog.json"
- $.entries[6].contentVersion: "de4f2a42bd6b89f49ecf992de880068b24a54dc5"
+ $.entries[6].contentVersion: "b9fdb4fbb94996a12e7af5a8bb11bcb20697501a"
- $.entries[6].uri: "freetoplay/NA/event.json"
+ $.entries[6].uri: "bonusPointEventsContent.json"
- $.entries[7].uri: "freetoplay/EU/event.json"
+ $.entries[7].uri: "freetoplay/NA/event.json"
- $.entries[8].contentVersion: "4f9aca3a012339cde16fc6d8912a1d52eaa5bc70"
+ $.entries[8].contentVersion: "de4f2a42bd6b89f49ecf992de880068b24a54dc5"
- $.entries[8].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[8].uri: "freetoplay/EU/event.json"
- $.entries[9].contentVersion: "9d6c0d1e09a638b8f29918eb9719e6aeea4557e5"
+ $.entries[9].contentVersion: "4f9aca3a012339cde16fc6d8912a1d52eaa5bc70"
- $.entries[9].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[9].uri: "archiveQuests/Anniversary2022.json"
- $.entries[10].contentVersion: "f7597058088ac016ede397ec032f3421f35cb8e9"
+ $.entries[10].contentVersion: "9d6c0d1e09a638b8f29918eb9719e6aeea4557e5"
- $.entries[10].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2023.json"
- $.entries[11].contentVersion: "199fa7e433ff4024134b05a0fa20d8532e0d54ef"
+ $.entries[11].contentVersion: "f7597058088ac016ede397ec032f3421f35cb8e9"
- $.entries[11].uri: "archiveQuests/CalamariV1.json"
+ $.entries[11].uri: "archiveQuests/Anniversary2024.json"
- $.entries[12].contentVersion: "1e5f63dabf035b675680d950b4314d172c1431f5"
+ $.entries[12].contentVersion: "199fa7e433ff4024134b05a0fa20d8532e0d54ef"
- $.entries[12].uri: "archiveQuests/CalamariV2.json"
+ $.entries[12].uri: "archiveQuests/CalamariV1.json"
- $.entries[13].contentVersion: "dd8467acf5301a2d429b65f0936d1559f3f0b09c"
+ $.entries[13].contentVersion: "1e5f63dabf035b675680d950b4314d172c1431f5"
- $.entries[13].uri: "archiveQuests/CalamariV3.json"
+ $.entries[13].uri: "archiveQuests/CalamariV2.json"
- $.entries[14].contentVersion: "8941545d1e0f0e0d1a0b7736a2f4a2e89a7af78f"
+ $.entries[14].contentVersion: "dd8467acf5301a2d429b65f0936d1559f3f0b09c"
- $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[14].uri: "archiveQuests/CalamariV3.json"
- $.entries[15].contentVersion: "1e56f345fd327eb84aee02a190bd5413432df5ff"
+ $.entries[15].contentVersion: "8941545d1e0f0e0d1a0b7736a2f4a2e89a7af78f"
- $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[15].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[16].contentVersion: "5c68955b302810f39cfd1b4cd52f4813e35f425b"
+ $.entries[16].contentVersion: "1e56f345fd327eb84aee02a190bd5413432df5ff"
- $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[16].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[17].contentVersion: "87608f9596688cae4045011b51c16be13c2f176a"
+ $.entries[17].contentVersion: "5c68955b302810f39cfd1b4cd52f4813e35f425b"
- $.entries[17].uri: "archiveQuests/FireflyV1.json"
+ $.entries[17].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[18].contentVersion: "033fe3f5c49abec987c912be9a512b4f323d7a3e"
+ $.entries[18].contentVersion: "87608f9596688cae4045011b51c16be13c2f176a"
- $.entries[18].uri: "archiveQuests/Halloween2021.json"
+ $.entries[18].uri: "archiveQuests/FireflyV1.json"
- $.entries[19].contentVersion: "f0fdeb7b1944687e7e7315542e02c2d227c78bed"
+ $.entries[19].contentVersion: "033fe3f5c49abec987c912be9a512b4f323d7a3e"
- $.entries[19].uri: "archiveQuests/Halloween2022.json"
+ $.entries[19].uri: "archiveQuests/Halloween2021.json"
- $.entries[20].contentVersion: "13180d9f098fc04633f2621d7a9e364b9ca4c228"
+ $.entries[20].contentVersion: "f0fdeb7b1944687e7e7315542e02c2d227c78bed"
- $.entries[20].uri: "archiveQuests/Halloween2023.json"
+ $.entries[20].uri: "archiveQuests/Halloween2022.json"
- $.entries[21].contentVersion: "e5fad710ae57c6cf705a076aa97617717e2d5c65"
+ $.entries[21].contentVersion: "13180d9f098fc04633f2621d7a9e364b9ca4c228"
- $.entries[21].uri: "archiveQuests/Halloween2024.json"
+ $.entries[21].uri: "archiveQuests/Halloween2023.json"
- $.entries[22].contentVersion: "1b2571a13ac023b84771c10d14fc6847e9d3147d"
+ $.entries[22].contentVersion: "e5fad710ae57c6cf705a076aa97617717e2d5c65"
- $.entries[22].uri: "archiveQuests/Spring2024.json"
+ $.entries[22].uri: "archiveQuests/Halloween2024.json"
- $.entries[23].contentVersion: "0272e7a125e37b2218b760cdd68f1d2fb26b1c84"
+ $.entries[23].contentVersion: "1b2571a13ac023b84771c10d14fc6847e9d3147d"
- $.entries[23].uri: "archiveQuests/Spring2025.json"
+ $.entries[23].uri: "archiveQuests/Spring2024.json"
- $.entries[24].contentVersion: "9b23d896cb451212a0acffcb59caf8d355985bf3"
+ $.entries[24].contentVersion: "0272e7a125e37b2218b760cdd68f1d2fb26b1c84"
- $.entries[24].uri: "archiveQuests/Summer2023.json"
+ $.entries[24].uri: "archiveQuests/Spring2025.json"
- $.entries[25].contentVersion: "1ebbe5d1897137efb11ce20ffac480a2dc0c4564"
+ $.entries[25].contentVersion: "9b23d896cb451212a0acffcb59caf8d355985bf3"
- $.entries[25].uri: "archiveQuests/Tome01.json"
+ $.entries[25].uri: "archiveQuests/Summer2023.json"
- $.entries[26].contentVersion: "f825d04180140f5dc0e1f0a6b9f3a21d86e15a1d"
+ $.entries[26].contentVersion: "1ebbe5d1897137efb11ce20ffac480a2dc0c4564"
- $.entries[26].uri: "archiveQuests/Tome02.json"
+ $.entries[26].uri: "archiveQuests/Tome01.json"
- $.entries[27].contentVersion: "b484c996dc18e62d72d0ce857448289ad8bb0d85"
+ $.entries[27].contentVersion: "f825d04180140f5dc0e1f0a6b9f3a21d86e15a1d"
- $.entries[27].uri: "archiveQuests/Tome03.json"
+ $.entries[27].uri: "archiveQuests/Tome02.json"
- $.entries[28].contentVersion: "32285f11a600d55a1628df98465526e8d1786fa3"
+ $.entries[28].contentVersion: "b484c996dc18e62d72d0ce857448289ad8bb0d85"
- $.entries[28].uri: "archiveQuests/Tome04.json"
+ $.entries[28].uri: "archiveQuests/Tome03.json"
- $.entries[29].contentVersion: "f45bff6bba882d0848ab93e5b7e303e7b722d5b4"
+ $.entries[29].contentVersion: "32285f11a600d55a1628df98465526e8d1786fa3"
- $.entries[29].uri: "archiveQuests/Tome05.json"
+ $.entries[29].uri: "archiveQuests/Tome04.json"
- $.entries[30].contentVersion: "4ffe76cb9032b296dae10583bdb6b98d7e9d3dba"
+ $.entries[30].contentVersion: "f45bff6bba882d0848ab93e5b7e303e7b722d5b4"
- $.entries[30].uri: "archiveQuests/Tome06.json"
+ $.entries[30].uri: "archiveQuests/Tome05.json"
- $.entries[31].contentVersion: "bc52d5b5b148549e98cc901ba15b5f2714a4445b"
+ $.entries[31].contentVersion: "4ffe76cb9032b296dae10583bdb6b98d7e9d3dba"
- $.entries[31].uri: "archiveQuests/Tome07.json"
+ $.entries[31].uri: "archiveQuests/Tome06.json"
- $.entries[32].contentVersion: "faa24099a193c1aa8ce1a56e98d748b81a982fa4"
+ $.entries[32].contentVersion: "bc52d5b5b148549e98cc901ba15b5f2714a4445b"
- $.entries[32].uri: "archiveQuests/Tome08.json"
+ $.entries[32].uri: "archiveQuests/Tome07.json"
- $.entries[33].contentVersion: "a2d9558c40ff856a182acb3c711d2b2caf6c369e"
+ $.entries[33].contentVersion: "faa24099a193c1aa8ce1a56e98d748b81a982fa4"
- $.entries[33].uri: "archiveQuests/Tome09.json"
+ $.entries[33].uri: "archiveQuests/Tome08.json"
- $.entries[34].contentVersion: "af05ece46cb07b849093c338c15443a69df48d46"
+ $.entries[34].contentVersion: "a2d9558c40ff856a182acb3c711d2b2caf6c369e"
- $.entries[34].uri: "archiveQuests/Tome10.json"
+ $.entries[34].uri: "archiveQuests/Tome09.json"
- $.entries[35].contentVersion: "f627afeac68fd092c9f2f093dec06e1b1796915d"
+ $.entries[35].contentVersion: "af05ece46cb07b849093c338c15443a69df48d46"
- $.entries[35].uri: "archiveQuests/Tome11.json"
+ $.entries[35].uri: "archiveQuests/Tome10.json"
- $.entries[36].contentVersion: "a4977a8c4249dc0e7d0eaa81592c9f574a370d18"
+ $.entries[36].contentVersion: "f627afeac68fd092c9f2f093dec06e1b1796915d"
- $.entries[36].uri: "archiveQuests/Tome12.json"
+ $.entries[36].uri: "archiveQuests/Tome11.json"
- $.entries[37].contentVersion: "b22623692752609730c27df6c1b960c5e142b089"
+ $.entries[37].contentVersion: "a4977a8c4249dc0e7d0eaa81592c9f574a370d18"
- $.entries[37].uri: "archiveQuests/Tome13.json"
+ $.entries[37].uri: "archiveQuests/Tome12.json"
- $.entries[38].contentVersion: "5640bff9a90c7f6291493786ca912fe402fb6b4f"
+ $.entries[38].contentVersion: "b22623692752609730c27df6c1b960c5e142b089"
- $.entries[38].uri: "archiveQuests/Tome14.json"
+ $.entries[38].uri: "archiveQuests/Tome13.json"
- $.entries[39].contentVersion: "80b823a2e4b7833fb28b790634c24213f1e393a0"
+ $.entries[39].contentVersion: "5640bff9a90c7f6291493786ca912fe402fb6b4f"
- $.entries[39].uri: "archiveQuests/Tome15.json"
+ $.entries[39].uri: "archiveQuests/Tome14.json"
- $.entries[40].contentVersion: "e66e40373584335b8cfa8fcf14fe7bd4f8f9c082"
+ $.entries[40].contentVersion: "80b823a2e4b7833fb28b790634c24213f1e393a0"
- $.entries[40].uri: "archiveQuests/Tome16.json"
+ $.entries[40].uri: "archiveQuests/Tome15.json"
- $.entries[41].contentVersion: "ab6a2503b883f0ca3fe6bfc0f8bf80cf4059b531"
+ $.entries[41].contentVersion: "e66e40373584335b8cfa8fcf14fe7bd4f8f9c082"
- $.entries[41].uri: "archiveQuests/Tome17.json"
+ $.entries[41].uri: "archiveQuests/Tome16.json"
- $.entries[42].contentVersion: "e033389440af1b3d92ea680c2d5cefadc8c0ca14"
+ $.entries[42].contentVersion: "ab6a2503b883f0ca3fe6bfc0f8bf80cf4059b531"
- $.entries[42].uri: "archiveQuests/Tome18.json"
+ $.entries[42].uri: "archiveQuests/Tome17.json"
- $.entries[43].contentVersion: "709d91e6570c8d3a45fc76c0cd3e6fac368b7577"
+ $.entries[43].contentVersion: "e033389440af1b3d92ea680c2d5cefadc8c0ca14"
- $.entries[43].uri: "archiveQuests/Tome19.json"
+ $.entries[43].uri: "archiveQuests/Tome18.json"
- $.entries[44].contentVersion: "fa9b125757259e06c3ba4c87e1fa43ab30b8f4f8"
+ $.entries[44].contentVersion: "709d91e6570c8d3a45fc76c0cd3e6fac368b7577"
- $.entries[44].uri: "archiveQuests/Tome20.json"
+ $.entries[44].uri: "archiveQuests/Tome19.json"
- $.entries[45].contentVersion: "87558ecfb3c97e9b32edbd1bffa0d4a87c27d3f4"
+ $.entries[45].contentVersion: "fa9b125757259e06c3ba4c87e1fa43ab30b8f4f8"
- $.entries[45].uri: "archiveQuests/Tome21.json"
+ $.entries[45].uri: "archiveQuests/Tome20.json"
- $.entries[46].contentVersion: "7828d427aa271d2df3ffb0b0d8cc043d01b75cef"
+ $.entries[46].contentVersion: "87558ecfb3c97e9b32edbd1bffa0d4a87c27d3f4"
- $.entries[46].uri: "archiveQuests/Tome22.json"
+ $.entries[46].uri: "archiveQuests/Tome21.json"
- $.entries[47].contentVersion: "f9ac6e28c5901285b89445260b2d80903c2cb644"
+ $.entries[47].contentVersion: "7828d427aa271d2df3ffb0b0d8cc043d01b75cef"
… 709 more change(s) — see the commit diff for everything
```

## Could not download

- `images/T_UI_CollectionBanner_BouletBrothers.png (HTTP 404)`
- `images/T_UI_SpecialPack_BouletBrothers.png (HTTP 404)`
- `images/T_UI_SpecialPack_WaterfrontMassacreBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_WaterfrontMassacreXenomorph.png (HTTP 404)`
- `news/versionedNews.json (HTTP 404)`
- `news/versionedNews_de.json (HTTP 404)`
- `news/versionedNews_en.json (HTTP 404)`
- `news/versionedNews_es-MX.json (HTTP 404)`
- `news/versionedNews_es.json (HTTP 404)`
- `news/versionedNews_fr.json (HTTP 404)`
- `news/versionedNews_it.json (HTTP 404)`
- `news/versionedNews_ja.json (HTTP 404)`
- `news/versionedNews_ko.json (HTTP 404)`
- `news/versionedNews_pl.json (HTTP 404)`
- `news/versionedNews_pt-BR.json (HTTP 404)`
- `news/versionedNews_ru.json (HTTP 404)`
- `news/versionedNews_th.json (HTTP 404)`
- `news/versionedNews_tr.json (HTTP 404)`
- `news/versionedNews_zh-Hans.json (HTTP 404)`
- `news/versionedNews_zh-Hant.json (HTTP 404)`

