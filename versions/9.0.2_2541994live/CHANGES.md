# live · 9.0.2_2541994live

| | |
|---|---|
| Build date | 2025-07-07 17:09 UTC |
| CDN version | `9.0.2_2541994live-1751908186` |
| Key | `9.0.2_live` |
| Compared with | [9.0.2_2537818live](../9.0.2_2537818live/CHANGES.md) (2025-07-04 18:03 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 199 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=Boulet_Brothers_Bundle]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "a0a0a03250bc8a8b03319aefdadb770c2ca7b193"
+ $.entries[0].contentVersion: "ae989e234341b7b4c634b497cfc79a60ce4cc9e8"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_BouletBrothers.T_UI_CollectionBanner_BouletBrothers"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_BouletBrothers.T_UI_SpecialPack_BouletBrothers"
- $.entries[0].uri: "images/T_UI_CollectionBanner_BouletBrothers.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_BouletBrothers.png"
- $.entries[1].contentVersion: "ae989e234341b7b4c634b497cfc79a60ce4cc9e8"
+ $.entries[1].contentVersion: "a0a0a03250bc8a8b03319aefdadb770c2ca7b193"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_BouletBrothers.T_UI_SpecialPack_BouletBrothers"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_BouletBrothers.T_UI_CollectionBanner_BouletBrothers"
- $.entries[1].uri: "images/T_UI_SpecialPack_BouletBrothers.png"
+ $.entries[1].uri: "images/T_UI_CollectionBanner_BouletBrothers.png"
- $.entries[2].contentVersion: "4ac8a4e7cb5c8f573ea69e5a0773e641918a1edb"
+ $.entries[2].contentVersion: "ae989e234341b7b4c634b497cfc79a60ce4cc9e8"
- $.entries[2].downloadStrategy: "preferRemote"
+ $.entries[2].downloadStrategy: "preferPackaged"
- $.entries[2].enableChecksum: true
+ $.entries[2].enableChecksum: false
- $.entries[2].packagedPath: ""
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_BouletBrothers.T_UI_SpecialPack_BouletBrothers"
- $.entries[2].schema: "s3ver://"
+ $.entries[2].schema: "s3verbin://"
- $.entries[2].uri: "catalog.json"
+ $.entries[2].uri: "images/T_UI_SpecialPack_BouletBrothers.png"
- $.entries[3].contentVersion: "b9fdb4fbb94996a12e7af5a8bb11bcb20697501a"
+ $.entries[3].contentVersion: "e77153102f1c010d12550751edff542629e8b43a"
- $.entries[3].uri: "bonusPointEventsContent.json"
+ $.entries[3].uri: "catalog.json"
- $.entries[4].contentVersion: "de4f2a42bd6b89f49ecf992de880068b24a54dc5"
+ $.entries[4].contentVersion: "b9fdb4fbb94996a12e7af5a8bb11bcb20697501a"
- $.entries[4].uri: "freetoplay/NA/event.json"
+ $.entries[4].uri: "bonusPointEventsContent.json"
- $.entries[5].uri: "freetoplay/EU/event.json"
+ $.entries[5].uri: "freetoplay/NA/event.json"
- $.entries[6].contentVersion: "4f9aca3a012339cde16fc6d8912a1d52eaa5bc70"
+ $.entries[6].contentVersion: "de4f2a42bd6b89f49ecf992de880068b24a54dc5"
- $.entries[6].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[6].uri: "freetoplay/EU/event.json"
- $.entries[7].contentVersion: "9d6c0d1e09a638b8f29918eb9719e6aeea4557e5"
+ $.entries[7].contentVersion: "4f9aca3a012339cde16fc6d8912a1d52eaa5bc70"
- $.entries[7].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[7].uri: "archiveQuests/Anniversary2022.json"
- $.entries[8].contentVersion: "f7597058088ac016ede397ec032f3421f35cb8e9"
+ $.entries[8].contentVersion: "9d6c0d1e09a638b8f29918eb9719e6aeea4557e5"
- $.entries[8].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[8].uri: "archiveQuests/Anniversary2023.json"
- $.entries[9].contentVersion: "199fa7e433ff4024134b05a0fa20d8532e0d54ef"
+ $.entries[9].contentVersion: "f7597058088ac016ede397ec032f3421f35cb8e9"
- $.entries[9].uri: "archiveQuests/CalamariV1.json"
+ $.entries[9].uri: "archiveQuests/Anniversary2024.json"
- $.entries[10].contentVersion: "1e5f63dabf035b675680d950b4314d172c1431f5"
+ $.entries[10].contentVersion: "199fa7e433ff4024134b05a0fa20d8532e0d54ef"
- $.entries[10].uri: "archiveQuests/CalamariV2.json"
+ $.entries[10].uri: "archiveQuests/CalamariV1.json"
- $.entries[11].contentVersion: "dd8467acf5301a2d429b65f0936d1559f3f0b09c"
+ $.entries[11].contentVersion: "1e5f63dabf035b675680d950b4314d172c1431f5"
- $.entries[11].uri: "archiveQuests/CalamariV3.json"
+ $.entries[11].uri: "archiveQuests/CalamariV2.json"
- $.entries[12].contentVersion: "8941545d1e0f0e0d1a0b7736a2f4a2e89a7af78f"
+ $.entries[12].contentVersion: "dd8467acf5301a2d429b65f0936d1559f3f0b09c"
- $.entries[12].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[12].uri: "archiveQuests/CalamariV3.json"
- $.entries[13].contentVersion: "1e56f345fd327eb84aee02a190bd5413432df5ff"
+ $.entries[13].contentVersion: "8941545d1e0f0e0d1a0b7736a2f4a2e89a7af78f"
- $.entries[13].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[13].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[14].contentVersion: "5c68955b302810f39cfd1b4cd52f4813e35f425b"
+ $.entries[14].contentVersion: "1e56f345fd327eb84aee02a190bd5413432df5ff"
- $.entries[14].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[14].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[15].contentVersion: "87608f9596688cae4045011b51c16be13c2f176a"
+ $.entries[15].contentVersion: "5c68955b302810f39cfd1b4cd52f4813e35f425b"
- $.entries[15].uri: "archiveQuests/FireflyV1.json"
+ $.entries[15].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[16].contentVersion: "033fe3f5c49abec987c912be9a512b4f323d7a3e"
+ $.entries[16].contentVersion: "87608f9596688cae4045011b51c16be13c2f176a"
- $.entries[16].uri: "archiveQuests/Halloween2021.json"
+ $.entries[16].uri: "archiveQuests/FireflyV1.json"
- $.entries[17].contentVersion: "f0fdeb7b1944687e7e7315542e02c2d227c78bed"
+ $.entries[17].contentVersion: "033fe3f5c49abec987c912be9a512b4f323d7a3e"
- $.entries[17].uri: "archiveQuests/Halloween2022.json"
+ $.entries[17].uri: "archiveQuests/Halloween2021.json"
- $.entries[18].contentVersion: "13180d9f098fc04633f2621d7a9e364b9ca4c228"
+ $.entries[18].contentVersion: "f0fdeb7b1944687e7e7315542e02c2d227c78bed"
- $.entries[18].uri: "archiveQuests/Halloween2023.json"
+ $.entries[18].uri: "archiveQuests/Halloween2022.json"
- $.entries[19].contentVersion: "e5fad710ae57c6cf705a076aa97617717e2d5c65"
+ $.entries[19].contentVersion: "13180d9f098fc04633f2621d7a9e364b9ca4c228"
- $.entries[19].uri: "archiveQuests/Halloween2024.json"
+ $.entries[19].uri: "archiveQuests/Halloween2023.json"
- $.entries[20].contentVersion: "1b2571a13ac023b84771c10d14fc6847e9d3147d"
+ $.entries[20].contentVersion: "e5fad710ae57c6cf705a076aa97617717e2d5c65"
- $.entries[20].uri: "archiveQuests/Spring2024.json"
+ $.entries[20].uri: "archiveQuests/Halloween2024.json"
- $.entries[21].contentVersion: "0272e7a125e37b2218b760cdd68f1d2fb26b1c84"
+ $.entries[21].contentVersion: "1b2571a13ac023b84771c10d14fc6847e9d3147d"
- $.entries[21].uri: "archiveQuests/Spring2025.json"
+ $.entries[21].uri: "archiveQuests/Spring2024.json"
- $.entries[22].contentVersion: "9b23d896cb451212a0acffcb59caf8d355985bf3"
+ $.entries[22].contentVersion: "0272e7a125e37b2218b760cdd68f1d2fb26b1c84"
- $.entries[22].uri: "archiveQuests/Summer2023.json"
+ $.entries[22].uri: "archiveQuests/Spring2025.json"
- $.entries[23].contentVersion: "1ebbe5d1897137efb11ce20ffac480a2dc0c4564"
+ $.entries[23].contentVersion: "9b23d896cb451212a0acffcb59caf8d355985bf3"
- $.entries[23].uri: "archiveQuests/Tome01.json"
+ $.entries[23].uri: "archiveQuests/Summer2023.json"
- $.entries[24].contentVersion: "f825d04180140f5dc0e1f0a6b9f3a21d86e15a1d"
+ $.entries[24].contentVersion: "1ebbe5d1897137efb11ce20ffac480a2dc0c4564"
- $.entries[24].uri: "archiveQuests/Tome02.json"
+ $.entries[24].uri: "archiveQuests/Tome01.json"
- $.entries[25].contentVersion: "b484c996dc18e62d72d0ce857448289ad8bb0d85"
+ $.entries[25].contentVersion: "f825d04180140f5dc0e1f0a6b9f3a21d86e15a1d"
- $.entries[25].uri: "archiveQuests/Tome03.json"
+ $.entries[25].uri: "archiveQuests/Tome02.json"
- $.entries[26].contentVersion: "32285f11a600d55a1628df98465526e8d1786fa3"
+ $.entries[26].contentVersion: "b484c996dc18e62d72d0ce857448289ad8bb0d85"
- $.entries[26].uri: "archiveQuests/Tome04.json"
+ $.entries[26].uri: "archiveQuests/Tome03.json"
- $.entries[27].contentVersion: "f45bff6bba882d0848ab93e5b7e303e7b722d5b4"
+ $.entries[27].contentVersion: "32285f11a600d55a1628df98465526e8d1786fa3"
- $.entries[27].uri: "archiveQuests/Tome05.json"
+ $.entries[27].uri: "archiveQuests/Tome04.json"
- $.entries[28].contentVersion: "4ffe76cb9032b296dae10583bdb6b98d7e9d3dba"
+ $.entries[28].contentVersion: "f45bff6bba882d0848ab93e5b7e303e7b722d5b4"
- $.entries[28].uri: "archiveQuests/Tome06.json"
+ $.entries[28].uri: "archiveQuests/Tome05.json"
- $.entries[29].contentVersion: "bc52d5b5b148549e98cc901ba15b5f2714a4445b"
+ $.entries[29].contentVersion: "4ffe76cb9032b296dae10583bdb6b98d7e9d3dba"
- $.entries[29].uri: "archiveQuests/Tome07.json"
+ $.entries[29].uri: "archiveQuests/Tome06.json"
- $.entries[30].contentVersion: "faa24099a193c1aa8ce1a56e98d748b81a982fa4"
+ $.entries[30].contentVersion: "bc52d5b5b148549e98cc901ba15b5f2714a4445b"
- $.entries[30].uri: "archiveQuests/Tome08.json"
+ $.entries[30].uri: "archiveQuests/Tome07.json"
- $.entries[31].contentVersion: "a2d9558c40ff856a182acb3c711d2b2caf6c369e"
+ $.entries[31].contentVersion: "faa24099a193c1aa8ce1a56e98d748b81a982fa4"
- $.entries[31].uri: "archiveQuests/Tome09.json"
+ $.entries[31].uri: "archiveQuests/Tome08.json"
- $.entries[32].contentVersion: "af05ece46cb07b849093c338c15443a69df48d46"
+ $.entries[32].contentVersion: "a2d9558c40ff856a182acb3c711d2b2caf6c369e"
- $.entries[32].uri: "archiveQuests/Tome10.json"
+ $.entries[32].uri: "archiveQuests/Tome09.json"
- $.entries[33].contentVersion: "f627afeac68fd092c9f2f093dec06e1b1796915d"
+ $.entries[33].contentVersion: "af05ece46cb07b849093c338c15443a69df48d46"
- $.entries[33].uri: "archiveQuests/Tome11.json"
+ $.entries[33].uri: "archiveQuests/Tome10.json"
- $.entries[34].contentVersion: "a4977a8c4249dc0e7d0eaa81592c9f574a370d18"
+ $.entries[34].contentVersion: "f627afeac68fd092c9f2f093dec06e1b1796915d"
- $.entries[34].uri: "archiveQuests/Tome12.json"
+ $.entries[34].uri: "archiveQuests/Tome11.json"
- $.entries[35].contentVersion: "b22623692752609730c27df6c1b960c5e142b089"
+ $.entries[35].contentVersion: "a4977a8c4249dc0e7d0eaa81592c9f574a370d18"
- $.entries[35].uri: "archiveQuests/Tome13.json"
+ $.entries[35].uri: "archiveQuests/Tome12.json"
- $.entries[36].contentVersion: "5640bff9a90c7f6291493786ca912fe402fb6b4f"
+ $.entries[36].contentVersion: "b22623692752609730c27df6c1b960c5e142b089"
- $.entries[36].uri: "archiveQuests/Tome14.json"
+ $.entries[36].uri: "archiveQuests/Tome13.json"
- $.entries[37].contentVersion: "80b823a2e4b7833fb28b790634c24213f1e393a0"
+ $.entries[37].contentVersion: "5640bff9a90c7f6291493786ca912fe402fb6b4f"
- $.entries[37].uri: "archiveQuests/Tome15.json"
+ $.entries[37].uri: "archiveQuests/Tome14.json"
- $.entries[38].contentVersion: "e66e40373584335b8cfa8fcf14fe7bd4f8f9c082"
+ $.entries[38].contentVersion: "80b823a2e4b7833fb28b790634c24213f1e393a0"
- $.entries[38].uri: "archiveQuests/Tome16.json"
+ $.entries[38].uri: "archiveQuests/Tome15.json"
- $.entries[39].contentVersion: "ab6a2503b883f0ca3fe6bfc0f8bf80cf4059b531"
+ $.entries[39].contentVersion: "e66e40373584335b8cfa8fcf14fe7bd4f8f9c082"
- $.entries[39].uri: "archiveQuests/Tome17.json"
+ $.entries[39].uri: "archiveQuests/Tome16.json"
- $.entries[40].contentVersion: "e033389440af1b3d92ea680c2d5cefadc8c0ca14"
+ $.entries[40].contentVersion: "ab6a2503b883f0ca3fe6bfc0f8bf80cf4059b531"
- $.entries[40].uri: "archiveQuests/Tome18.json"
+ $.entries[40].uri: "archiveQuests/Tome17.json"
- $.entries[41].contentVersion: "709d91e6570c8d3a45fc76c0cd3e6fac368b7577"
+ $.entries[41].contentVersion: "e033389440af1b3d92ea680c2d5cefadc8c0ca14"
- $.entries[41].uri: "archiveQuests/Tome19.json"
+ $.entries[41].uri: "archiveQuests/Tome18.json"
- $.entries[42].contentVersion: "fa9b125757259e06c3ba4c87e1fa43ab30b8f4f8"
+ $.entries[42].contentVersion: "709d91e6570c8d3a45fc76c0cd3e6fac368b7577"
- $.entries[42].uri: "archiveQuests/Tome20.json"
+ $.entries[42].uri: "archiveQuests/Tome19.json"
- $.entries[43].contentVersion: "87558ecfb3c97e9b32edbd1bffa0d4a87c27d3f4"
+ $.entries[43].contentVersion: "fa9b125757259e06c3ba4c87e1fa43ab30b8f4f8"
- $.entries[43].uri: "archiveQuests/Tome21.json"
+ $.entries[43].uri: "archiveQuests/Tome20.json"
- $.entries[44].contentVersion: "7828d427aa271d2df3ffb0b0d8cc043d01b75cef"
+ $.entries[44].contentVersion: "87558ecfb3c97e9b32edbd1bffa0d4a87c27d3f4"
- $.entries[44].uri: "archiveQuests/Tome22.json"
+ $.entries[44].uri: "archiveQuests/Tome21.json"
- $.entries[45].contentVersion: "f9ac6e28c5901285b89445260b2d80903c2cb644"
+ $.entries[45].contentVersion: "7828d427aa271d2df3ffb0b0d8cc043d01b75cef"
- $.entries[45].uri: "archiveQuests/Winter2022.json"
+ $.entries[45].uri: "archiveQuests/Tome22.json"
- $.entries[46].contentVersion: "1fe8ab8ad85a02220441e0d54c1777c5193df720"
+ $.entries[46].contentVersion: "f9ac6e28c5901285b89445260b2d80903c2cb644"
- $.entries[46].uri: "archiveQuests/Winter2023.json"
+ $.entries[46].uri: "archiveQuests/Winter2022.json"
- $.entries[47].contentVersion: "1ca232dadc6f30d1f97d375c1cbfea3d5c16f790"
+ $.entries[47].contentVersion: "1fe8ab8ad85a02220441e0d54c1777c5193df720"
… 701 more change(s) — see the commit diff for everything
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=KetchupW4].entries[0].entryId: "BouletBrothers"
+ $.featuredCard[id=KetchupW4].entries[0].entryId: "Boulet_Brothers_Bundle"
- $.featuredCard[id=KetchupW4].entries[0].type: "Collection"
+ $.featuredCard[id=KetchupW4].entries[0].type: "SpecialPack"
```

## Could not download

- `images/T_UI_CollectionBanner_BouletBrothers.png (HTTP 404)`
- `images/T_UI_SpecialPack_BouletBrothers.png (HTTP 404)`
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

