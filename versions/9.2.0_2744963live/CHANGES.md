# live · 9.2.0_2744963live

| | |
|---|---|
| Build date | 2025-09-17 20:16 UTC |
| CDN version | `9.2.0_2744963live-1758140197` |
| Key | `9.2.0_live` |
| Compared with | [9.2.0_2744004live](../9.2.0_2744004live/CHANGES.md) (2025-09-17 17:56 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 200 unchanged

## Modified files

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[380].text: "Accomplissez {0} quête(s)."
+ $.locText[380].text: "Accomplissez des quête(s)"
- $.locText[403].text: "Damage {0} generator(s) as {1}"
+ $.locText[403].text: "Endommagez {0} générateur(s) avec {1}"
- $.locText[404].text: "Damage {0} generator(s) as any Killer"
+ $.locText[404].text: "Endommagez {0} générateur(s) avec n'importe quel tueur"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[61].additionalImages[0]
```

### [`crossPromoCampaigns.json`](crossPromoCampaigns.json)

[Full line-by-line diff](diffs/crossPromoCampaigns.json.diff)

```diff
- $.Campaigns.ItHasMyFace_Promo.activeFromDate: "2025-01-01T04:00:00"
+ $.Campaigns.ItHasMyFace_Promo.activeFromDate: "2025-09-23T15:00:00"
- $.Campaigns.ItHasMyFace_Promo.activeToDate: "2025-10-09T15:00:00"
+ $.Campaigns.ItHasMyFace_Promo.activeToDate: "2025-10-23T15:00:00"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[4].contentVersion: "5e907dd9dc410eb9a1ff6bc1973ae825586f6887"
+ $.entries[4].contentVersion: "3c953ce75891597f0aadfd71e3dab2d16de12feb"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_SinisterGrace.T_UI_CollectionBanner_SinisterGrace"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_Specialpack_FallFashion.T_UI_Specialpack_FallFashion"
- $.entries[4].uri: "images/T_UI_CollectionBanner_SinisterGrace.png"
+ $.entries[4].uri: "images/T_UI_Specialpack_FallFashion.png"
- $.entries[5].contentVersion: "fbc8241b92a884ac6d866433ada0f9db766c66bc"
+ $.entries[5].contentVersion: "5e907dd9dc410eb9a1ff6bc1973ae825586f6887"
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_SinisterGrace.T_UI_SpecialPack_SinisterGrace"
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_SinisterGrace.T_UI_CollectionBanner_SinisterGrace"
- $.entries[5].uri: "images/T_UI_SpecialPack_SinisterGrace.png"
+ $.entries[5].uri: "images/T_UI_CollectionBanner_SinisterGrace.png"
- $.entries[6].contentVersion: "4deb0391cf08e15cd3c40d0cde2a17a1e284b1ae"
+ $.entries[6].contentVersion: "fbc8241b92a884ac6d866433ada0f9db766c66bc"
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_NOTLC.T_UI_CollectionBanner_NOTLC"
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_SinisterGrace.T_UI_SpecialPack_SinisterGrace"
- $.entries[6].uri: "images/T_UI_CollectionBanner_NOTLC.png"
+ $.entries[6].uri: "images/T_UI_SpecialPack_SinisterGrace.png"
- $.entries[7].contentVersion: "a0eb39e204ac7a589e860c5759293da82ed5b143"
+ $.entries[7].contentVersion: "4deb0391cf08e15cd3c40d0cde2a17a1e284b1ae"
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_NOTLC.T_UI_SpecialPack_NOTLC"
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_NOTLC.T_UI_CollectionBanner_NOTLC"
- $.entries[7].uri: "images/T_UI_SpecialPack_NOTLC.png"
+ $.entries[7].uri: "images/T_UI_CollectionBanner_NOTLC.png"
- $.entries[8].contentVersion: "ff437cc262850ea6df4a8ca3c5b64964964f7747"
+ $.entries[8].contentVersion: "a0eb39e204ac7a589e860c5759293da82ed5b143"
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_PartyHard.T_UI_CollectionBanner_PartyHard"
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_NOTLC.T_UI_SpecialPack_NOTLC"
- $.entries[8].uri: "images/T_UI_CollectionBanner_PartyHard.png"
+ $.entries[8].uri: "images/T_UI_SpecialPack_NOTLC.png"
- $.entries[9].contentVersion: "d16173b36a12e4a4ed82a5fc7650cf5d8a9f8bbf"
+ $.entries[9].contentVersion: "ff437cc262850ea6df4a8ca3c5b64964964f7747"
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_PartyHard.T_UI_SpecialPack_PartyHard"
+ $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_PartyHard.T_UI_CollectionBanner_PartyHard"
- $.entries[9].uri: "images/T_UI_SpecialPack_PartyHard.png"
+ $.entries[9].uri: "images/T_UI_CollectionBanner_PartyHard.png"
- $.entries[10].contentVersion: "5dcf648e29bcc2d37be0dc1e7ea6ff34fa9b1044"
+ $.entries[10].contentVersion: "d16173b36a12e4a4ed82a5fc7650cf5d8a9f8bbf"
- $.entries[10].downloadStrategy: "preferRemote"
+ $.entries[10].downloadStrategy: "preferPackaged"
- $.entries[10].enableChecksum: true
+ $.entries[10].enableChecksum: false
- $.entries[10].packagedPath: ""
+ $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_PartyHard.T_UI_SpecialPack_PartyHard"
- $.entries[10].schema: "s3ver://"
+ $.entries[10].schema: "s3verbin://"
- $.entries[10].uri: "catalog.json"
+ $.entries[10].uri: "images/T_UI_SpecialPack_PartyHard.png"
- $.entries[11].contentVersion: "a3ae9f58d0dee10bafa82f215593ff417d538e00"
+ $.entries[11].contentVersion: "5dcf648e29bcc2d37be0dc1e7ea6ff34fa9b1044"
- $.entries[11].uri: "bonusPointEventsContent.json"
+ $.entries[11].uri: "catalog.json"
- $.entries[12].contentVersion: "2b59e9761cec12be445ee8cca0a385e3504cb620"
+ $.entries[12].contentVersion: "a3ae9f58d0dee10bafa82f215593ff417d538e00"
- $.entries[12].uri: "freetoplay/NA/event.json"
+ $.entries[12].uri: "bonusPointEventsContent.json"
- $.entries[13].uri: "freetoplay/EU/event.json"
+ $.entries[13].uri: "freetoplay/NA/event.json"
- $.entries[14].contentVersion: "38a216303d6dda39cf30c4d2d786e4dda581597d"
+ $.entries[14].contentVersion: "2b59e9761cec12be445ee8cca0a385e3504cb620"
- $.entries[14].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[14].uri: "freetoplay/EU/event.json"
- $.entries[15].contentVersion: "054edff758b733e20dd587cfa33850a16595e39b"
+ $.entries[15].contentVersion: "38a216303d6dda39cf30c4d2d786e4dda581597d"
- $.entries[15].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[15].uri: "archiveQuests/Anniversary2022.json"
- $.entries[16].contentVersion: "4b3ae0806f1c01fceef0bd2835c47a4d41747aa8"
+ $.entries[16].contentVersion: "054edff758b733e20dd587cfa33850a16595e39b"
- $.entries[16].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[16].uri: "archiveQuests/Anniversary2023.json"
- $.entries[17].contentVersion: "baef1757018d93edaa5a4f9b61dce5a6edd3299b"
+ $.entries[17].contentVersion: "4b3ae0806f1c01fceef0bd2835c47a4d41747aa8"
- $.entries[17].uri: "archiveQuests/CalamariV1.json"
+ $.entries[17].uri: "archiveQuests/Anniversary2024.json"
- $.entries[18].contentVersion: "9de2b4ac74d629f27ec4b2490b92ea1a417ee37d"
+ $.entries[18].contentVersion: "baef1757018d93edaa5a4f9b61dce5a6edd3299b"
- $.entries[18].uri: "archiveQuests/CalamariV2.json"
+ $.entries[18].uri: "archiveQuests/CalamariV1.json"
- $.entries[19].contentVersion: "6c7e74aa941f63311638f9893ecbd86e3e8322fa"
+ $.entries[19].contentVersion: "9de2b4ac74d629f27ec4b2490b92ea1a417ee37d"
- $.entries[19].uri: "archiveQuests/CalamariV3.json"
+ $.entries[19].uri: "archiveQuests/CalamariV2.json"
- $.entries[20].contentVersion: "74f3f3c1d90061faa39c3b4d01eb43443685c913"
+ $.entries[20].contentVersion: "6c7e74aa941f63311638f9893ecbd86e3e8322fa"
- $.entries[20].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[20].uri: "archiveQuests/CalamariV3.json"
- $.entries[21].contentVersion: "a8777aa9d56731007f764d8db72edd760d9f472a"
+ $.entries[21].contentVersion: "74f3f3c1d90061faa39c3b4d01eb43443685c913"
- $.entries[21].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[21].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[22].contentVersion: "8bb66c93ec94f49bfe15f38642247168d6c42d3e"
+ $.entries[22].contentVersion: "a8777aa9d56731007f764d8db72edd760d9f472a"
- $.entries[22].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[22].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[23].contentVersion: "d20fefecc6996f8e8e470c61e3dd7ef3249cffca"
+ $.entries[23].contentVersion: "8bb66c93ec94f49bfe15f38642247168d6c42d3e"
- $.entries[23].uri: "archiveQuests/FireflyV1.json"
+ $.entries[23].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[24].contentVersion: "9a7b9d0f63aab4d1f0fe03128489fd18b86b70a1"
+ $.entries[24].contentVersion: "d20fefecc6996f8e8e470c61e3dd7ef3249cffca"
- $.entries[24].uri: "archiveQuests/Halloween2021.json"
+ $.entries[24].uri: "archiveQuests/FireflyV1.json"
- $.entries[25].contentVersion: "5c78246a1489a53155a418ee3045c952f0be1097"
+ $.entries[25].contentVersion: "9a7b9d0f63aab4d1f0fe03128489fd18b86b70a1"
- $.entries[25].uri: "archiveQuests/Halloween2022.json"
+ $.entries[25].uri: "archiveQuests/Halloween2021.json"
- $.entries[26].contentVersion: "f7f0c3923d2bc55db95d000e2d8b2e2b2866fa07"
+ $.entries[26].contentVersion: "5c78246a1489a53155a418ee3045c952f0be1097"
- $.entries[26].uri: "archiveQuests/Halloween2023.json"
+ $.entries[26].uri: "archiveQuests/Halloween2022.json"
- $.entries[27].contentVersion: "740ec264b473a0d9c25babc776c532fa63fc5305"
+ $.entries[27].contentVersion: "f7f0c3923d2bc55db95d000e2d8b2e2b2866fa07"
- $.entries[27].uri: "archiveQuests/Halloween2024.json"
+ $.entries[27].uri: "archiveQuests/Halloween2023.json"
- $.entries[28].contentVersion: "701b45da72a46b6c38dc378206ad81cf83169203"
+ $.entries[28].contentVersion: "740ec264b473a0d9c25babc776c532fa63fc5305"
- $.entries[28].uri: "archiveQuests/Spring2024.json"
+ $.entries[28].uri: "archiveQuests/Halloween2024.json"
- $.entries[29].contentVersion: "60711d0c789b221bf37444dc1944242477fb9fc3"
+ $.entries[29].contentVersion: "701b45da72a46b6c38dc378206ad81cf83169203"
- $.entries[29].uri: "archiveQuests/Spring2025.json"
+ $.entries[29].uri: "archiveQuests/Spring2024.json"
- $.entries[30].contentVersion: "1da7f57021a89276c5073ab5279c115497961c00"
+ $.entries[30].contentVersion: "60711d0c789b221bf37444dc1944242477fb9fc3"
- $.entries[30].uri: "archiveQuests/Summer2023.json"
+ $.entries[30].uri: "archiveQuests/Spring2025.json"
- $.entries[31].contentVersion: "a9e0c564b63ccaccd58073673d4fa153f7de921b"
+ $.entries[31].contentVersion: "1da7f57021a89276c5073ab5279c115497961c00"
- $.entries[31].uri: "archiveQuests/Tome01.json"
+ $.entries[31].uri: "archiveQuests/Summer2023.json"
- $.entries[32].contentVersion: "d70af22e9008a25b356d49e64da3aad3b7e2b184"
+ $.entries[32].contentVersion: "a9e0c564b63ccaccd58073673d4fa153f7de921b"
- $.entries[32].uri: "archiveQuests/Tome02.json"
+ $.entries[32].uri: "archiveQuests/Tome01.json"
- $.entries[33].contentVersion: "d874a6e85a40b0d4eae278d412b27ce3da381552"
+ $.entries[33].contentVersion: "d70af22e9008a25b356d49e64da3aad3b7e2b184"
- $.entries[33].uri: "archiveQuests/Tome03.json"
+ $.entries[33].uri: "archiveQuests/Tome02.json"
- $.entries[34].contentVersion: "41462530710091e7c94e55783bc6a812d0757738"
+ $.entries[34].contentVersion: "d874a6e85a40b0d4eae278d412b27ce3da381552"
- $.entries[34].uri: "archiveQuests/Tome04.json"
+ $.entries[34].uri: "archiveQuests/Tome03.json"
- $.entries[35].contentVersion: "0a4a3ef6c9c2fcebdacfbf57d6d327d3bb1dffc0"
+ $.entries[35].contentVersion: "41462530710091e7c94e55783bc6a812d0757738"
- $.entries[35].uri: "archiveQuests/Tome05.json"
+ $.entries[35].uri: "archiveQuests/Tome04.json"
- $.entries[36].contentVersion: "81779868567a64b0b5a01d7e537622fd6d293904"
+ $.entries[36].contentVersion: "0a4a3ef6c9c2fcebdacfbf57d6d327d3bb1dffc0"
- $.entries[36].uri: "archiveQuests/Tome06.json"
+ $.entries[36].uri: "archiveQuests/Tome05.json"
- $.entries[37].contentVersion: "2dc6e3896880b1f1029f4725e980d95d61ac3d33"
+ $.entries[37].contentVersion: "81779868567a64b0b5a01d7e537622fd6d293904"
- $.entries[37].uri: "archiveQuests/Tome07.json"
+ $.entries[37].uri: "archiveQuests/Tome06.json"
- $.entries[38].contentVersion: "7b37c32f0257448068150fac936e5379a55d86f9"
+ $.entries[38].contentVersion: "2dc6e3896880b1f1029f4725e980d95d61ac3d33"
- $.entries[38].uri: "archiveQuests/Tome08.json"
+ $.entries[38].uri: "archiveQuests/Tome07.json"
- $.entries[39].contentVersion: "06d5903847615e17f3147f56082852aa9db70e0a"
+ $.entries[39].contentVersion: "7b37c32f0257448068150fac936e5379a55d86f9"
- $.entries[39].uri: "archiveQuests/Tome09.json"
+ $.entries[39].uri: "archiveQuests/Tome08.json"
- $.entries[40].contentVersion: "ec3fd6ab3cecfcf3412737d6ca2adc622c0a306c"
+ $.entries[40].contentVersion: "06d5903847615e17f3147f56082852aa9db70e0a"
- $.entries[40].uri: "archiveQuests/Tome10.json"
+ $.entries[40].uri: "archiveQuests/Tome09.json"
- $.entries[41].contentVersion: "47ae4267a4053e08f9b733ca144c9631dac73f20"
+ $.entries[41].contentVersion: "ec3fd6ab3cecfcf3412737d6ca2adc622c0a306c"
- $.entries[41].uri: "archiveQuests/Tome11.json"
+ $.entries[41].uri: "archiveQuests/Tome10.json"
- $.entries[42].contentVersion: "fc15113d0266f217f44fe41c0dcedd4f2a0658fb"
+ $.entries[42].contentVersion: "47ae4267a4053e08f9b733ca144c9631dac73f20"
- $.entries[42].uri: "archiveQuests/Tome12.json"
+ $.entries[42].uri: "archiveQuests/Tome11.json"
- $.entries[43].contentVersion: "1f36458a019d94ede85fdb3c3a445687b737a217"
+ $.entries[43].contentVersion: "fc15113d0266f217f44fe41c0dcedd4f2a0658fb"
- $.entries[43].uri: "archiveQuests/Tome13.json"
+ $.entries[43].uri: "archiveQuests/Tome12.json"
- $.entries[44].contentVersion: "d5d071d257c9246d84ff2d0781552b2657adebfa"
+ $.entries[44].contentVersion: "1f36458a019d94ede85fdb3c3a445687b737a217"
- $.entries[44].uri: "archiveQuests/Tome14.json"
+ $.entries[44].uri: "archiveQuests/Tome13.json"
- $.entries[45].contentVersion: "5a9d0a2aa9abdf911bbb4e15dc28ad06e5979c7b"
+ $.entries[45].contentVersion: "d5d071d257c9246d84ff2d0781552b2657adebfa"
- $.entries[45].uri: "archiveQuests/Tome15.json"
+ $.entries[45].uri: "archiveQuests/Tome14.json"
- $.entries[46].contentVersion: "82bc4e081e80d73edc4380eaf473e0c0554d924a"
+ $.entries[46].contentVersion: "5a9d0a2aa9abdf911bbb4e15dc28ad06e5979c7b"
- $.entries[46].uri: "archiveQuests/Tome16.json"
+ $.entries[46].uri: "archiveQuests/Tome15.json"
- $.entries[47].contentVersion: "f6cfa74d70ed42356d296e5f22c57ffe987cb929"
+ $.entries[47].contentVersion: "82bc4e081e80d73edc4380eaf473e0c0554d924a"
- $.entries[47].uri: "archiveQuests/Tome17.json"
+ $.entries[47].uri: "archiveQuests/Tome16.json"
- $.entries[48].contentVersion: "e0ef24d6c7be5411121f0899615980b2da3cf52c"
+ $.entries[48].contentVersion: "f6cfa74d70ed42356d296e5f22c57ffe987cb929"
- $.entries[48].uri: "archiveQuests/Tome18.json"
+ $.entries[48].uri: "archiveQuests/Tome17.json"
- $.entries[49].contentVersion: "17c8834d577671f2184eeacf9deb4005a8809d1c"
+ $.entries[49].contentVersion: "e0ef24d6c7be5411121f0899615980b2da3cf52c"
… 673 more change(s) — see the commit diff for everything
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Maple].entries[1].entryId: "PartyGoneWrong"
+ $.featuredCard[id=Maple].entries[1].entryId: "ItHasMyFace_Promo"
- $.featuredCard[id=Maple].entries[1].type: "Collection"
+ $.featuredCard[id=Maple].entries[1].type: "CrossPromotion"
- $.featuredCard[id=Maple].entries[2].entryId: "Counterculture"
+ $.featuredCard[id=Maple].entries[2].entryId: "Axekick_Bundle"
- $.featuredCard[id=Maple].entries[2].type: "Collection"
+ $.featuredCard[id=Maple].entries[2].type: "SpecialPack"
- $.featuredCard[id=Maple_W2].entries[2].entryId: "Counterculture"
+ $.featuredCard[id=Maple_W2].entries[2].entryId: "ItHasMyFace_Promo"
- $.featuredCard[id=Maple_W2].entries[2].type: "Collection"
+ $.featuredCard[id=Maple_W2].entries[2].type: "CrossPromotion"
```

## Could not download

- `images/T_UI_ChapterBundle_SinisterGrace.png (HTTP 404)`
- `images/T_UI_CollectionBanner_NOTLC.png (HTTP 404)`
- `images/T_UI_CollectionBanner_PartyHard.png (HTTP 404)`
- `images/T_UI_CollectionBanner_SinisterGrace.png (HTTP 404)`
- `images/T_UI_SpecialPack_NOTLC.png (HTTP 404)`
- `images/T_UI_SpecialPack_PartyHard.png (HTTP 404)`
- `images/T_UI_SpecialPack_SinisterGrace.png (HTTP 404)`
- `images/T_UI_SpecialPack_Tome5.png (HTTP 404)`
- `images/T_UI_SpecialPack_Tome6.png (HTTP 404)`
- `images/T_UI_Specialpack_FallFashion.png (HTTP 404)`

