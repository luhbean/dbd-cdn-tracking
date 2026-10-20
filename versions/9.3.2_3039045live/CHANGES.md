# live · 9.3.2_3039045live

| | |
|---|---|
| Build date | 2026-01-19 16:00 UTC |
| CDN version | `9.3.2_3039045live-1768838411` |
| Key | `9.3.2_live` |
| Compared with | [9.3.2_3025872live](../9.3.2_3025872live/CHANGES.md) (2026-01-13 15:23 UTC) |

## Summary

**0** added · **10** modified · **0** removed · 195 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=SilentHill_Omelet_Bundle]
- $[id=Laurie].eventCostList
- $[id=Laurie].metaData.temporaryDiscounts
- $[id=Laurie].metaData.hiddenIfNotOwned: false
+ $[id=Laurie].metaData.hiddenIfNotOwned: true
- $[id=Shape].eventCostList
- $[id=Shape].metaData.temporaryDiscounts
- $[id=Shape].metaData.hiddenIfNotOwned: false
+ $[id=Shape].metaData.hiddenIfNotOwned: true
+ $[id=K20].eventCostList
+ $[id=K20].metaData.temporaryDiscounts
+ $[id=S22].eventCostList
+ $[id=S22].metaData.temporaryDiscounts
- $[id=AV_Torso006].eventCostList[0]
- $[id=AV_Torso006].metaData.temporaryDiscounts
- $[id=BE_W016].eventCostList[0]
- $[id=BE_W016].metaData.temporaryDiscounts
- $[id=CM_Torso008].eventCostList[0]
- $[id=CM_Torso008].metaData.temporaryDiscounts
- $[id=DF_Torso007].eventCostList[0]
- $[id=DF_Torso007].metaData.temporaryDiscounts
- $[id=DK_Torso006].eventCostList[0]
- $[id=DK_Torso006].metaData.temporaryDiscounts
- $[id=FM_Torso006].eventCostList[0]
- $[id=FM_Torso006].metaData.temporaryDiscounts
- $[id=FS_Torso009].eventCostList[0]
- $[id=FS_Torso009].metaData.temporaryDiscounts
- $[id=GK_W018].eventCostList[0]
- $[id=GK_W018].metaData.temporaryDiscounts
- $[id=GS_Torso008].eventCostList[0]
- $[id=GS_Torso008].metaData.temporaryDiscounts
- $[id=HS_Torso007].eventCostList[0]
- $[id=HS_Torso007].metaData.temporaryDiscounts
- $[id=JP_Torso008].eventCostList[0]
- $[id=JP_Torso008].metaData.temporaryDiscounts
- $[id=K21_W016].eventCostList[0]
- $[id=K21_W016].metaData.temporaryDiscounts
- $[id=K34_Body008].eventCostList[0]
- $[id=K34_Body008].metaData.temporaryDiscounts
- $[id=KK_Body012].eventCostList[0]
- $[id=KK_Body012].metaData.temporaryDiscounts
- $[id=KK_Body013].eventCostList[0]
- $[id=KK_Body013].metaData.temporaryDiscounts
- $[id=KS_Torso006].eventCostList[0]
- $[id=KS_Torso006].metaData.temporaryDiscounts
- $[id=LS_Head006].eventCostList[0]
- $[id=LS_Head006].metaData.temporaryDiscounts
- $[id=LS_Head006].purchasable: true
+ $[id=LS_Head006].purchasable: false
- $[id=LS_Legs006].eventCostList[0]
- $[id=LS_Legs006].metaData.temporaryDiscounts
- $[id=LS_Legs006].purchasable: true
+ $[id=LS_Legs006].purchasable: false
- $[id=LS_Torso006].eventCostList[0]
- $[id=LS_Torso006].metaData.temporaryDiscounts
- $[id=LS_Torso006].purchasable: true
+ $[id=LS_Torso006].purchasable: false
- $[id=ML_Torso009].eventCostList[0]
- $[id=ML_Torso009].metaData.temporaryDiscounts
- $[id=MM_Body02].eventCostList[0]
- $[id=MM_Body02].metaData.temporaryDiscounts
- $[id=MM_Body02].purchasable: true
+ $[id=MM_Body02].purchasable: false
- $[id=MM_W02_01].eventCostList[0]
- $[id=MM_W02_01].metaData.temporaryDiscounts
- $[id=MM_W02_01].purchasable: true
+ $[id=MM_W02_01].purchasable: false
- $[id=MM_W02_02].eventCostList[0]
- $[id=MM_W02_02].metaData.temporaryDiscounts
- $[id=MM_W02_02].purchasable: true
+ $[id=MM_W02_02].purchasable: false
- $[id=MM_W02_03].eventCostList[0]
- $[id=MM_W02_03].metaData.temporaryDiscounts
- $[id=MM_W02_03].purchasable: true
+ $[id=MM_W02_03].purchasable: false
- $[id=MS_Torso010].eventCostList[0]
- $[id=MS_Torso010].metaData.temporaryDiscounts
- $[id=MT_Torso007].eventCostList[0]
- $[id=MT_Torso007].metaData.temporaryDiscounts
- $[id=NK_Torso007].eventCostList[0]
- $[id=NK_Torso007].metaData.temporaryDiscounts
- $[id=S22_Torso009].eventCostList[0]
- $[id=S22_Torso009].metaData.temporaryDiscounts
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
- $[id=S23_Torso009].eventCostList[0]
- $[id=S23_Torso009].metaData.temporaryDiscounts
- $[id=S24_Torso007].eventCostList[0]
- $[id=S24_Torso007].metaData.temporaryDiscounts
- $[id=S25_Torso012].eventCostList[0]
- $[id=S25_Torso012].metaData.temporaryDiscounts
- $[id=S26_Torso007].eventCostList[0]
- $[id=S26_Torso007].metaData.temporaryDiscounts
- $[id=S27_Torso007].eventCostList[0]
- $[id=S27_Torso007].metaData.temporaryDiscounts
- $[id=S28_Torso009].eventCostList[0]
- $[id=S28_Torso009].metaData.temporaryDiscounts
- $[id=S29_Torso007].eventCostList[0]
- $[id=S29_Torso007].metaData.temporaryDiscounts
- $[id=S30_Torso007].eventCostList[0]
- $[id=S30_Torso007].metaData.temporaryDiscounts
- $[id=S31_Torso008].eventCostList[0]
- $[id=S31_Torso008].metaData.temporaryDiscounts
- $[id=S32_Torso007].eventCostList[0]
- $[id=S32_Torso007].metaData.temporaryDiscounts
- $[id=S33_Torso007].eventCostList[0]
- $[id=S33_Torso007].metaData.temporaryDiscounts
- $[id=S34_Torso008].eventCostList[0]
- $[id=S34_Torso008].metaData.temporaryDiscounts
- $[id=S35_Torso012].eventCostList[0]
- $[id=S35_Torso012].metaData.temporaryDiscounts
- $[id=S36_Torso012].eventCostList[0]
- $[id=S36_Torso012].metaData.temporaryDiscounts
- $[id=S37_Torso012].eventCostList[0]
- $[id=S37_Torso012].metaData.temporaryDiscounts
- $[id=S39_Torso008].eventCostList[0]
- $[id=S39_Torso008].metaData.temporaryDiscounts
- $[id=S40_Torso011].eventCostList[0]
- $[id=S40_Torso011].metaData.temporaryDiscounts
- $[id=S41_Torso013].eventCostList[0]
- $[id=S41_Torso013].metaData.temporaryDiscounts
- $[id=S42_Torso009].eventCostList[0]
- $[id=S42_Torso009].metaData.temporaryDiscounts
- $[id=S42_Torso010].eventCostList[0]
- $[id=S42_Torso010].metaData.temporaryDiscounts
- $[id=S45_Torso008].eventCostList[0]
- $[id=S45_Torso008].metaData.temporaryDiscounts
- $[id=SwedenSurvivor_Torso008].eventCostList[0]
- $[id=SwedenSurvivor_Torso008].metaData.temporaryDiscounts
- $[id=TC_W017].eventCostList[0]
- $[id=TC_W017].metaData.temporaryDiscounts
- $[id=TR_W020].eventCostList[0]
- $[id=TR_W020].metaData.temporaryDiscounts
- $[id=TW_W04_03].eventCostList[0]
- $[id=TW_W04_03].metaData.temporaryDiscounts
- $[id=UK_W012].eventCostList[0]
- $[id=UK_W012].metaData.temporaryDiscounts
- $[id=US_Torso011].eventCostList[0]
- $[id=US_Torso011].metaData.temporaryDiscounts
- $[id=WI_W007_01].eventCostList[0]
- $[id=WI_W007_01].metaData.temporaryDiscounts
- $[id=Ace_outfit_001].metaData.temporaryDiscounts
- $[id=AV_outfit_012].metaData.temporaryDiscounts
- $[id=BE_outfit_010].metaData.temporaryDiscounts
- $[id=BE_outfit_024].metaData.temporaryDiscounts
- $[id=Clown_outfit_001].metaData.temporaryDiscounts
- $[id=Clown_outfit_007].metaData.temporaryDiscounts
- $[id=CM_outfit_016].metaData.temporaryDiscounts
- $[id=DF_outfit_011].metaData.temporaryDiscounts
- $[id=DF_outfit_013].metaData.temporaryDiscounts
- $[id=DF_outfit_028].metaData.temporaryDiscounts
- $[id=DK_outfit_017].metaData.temporaryDiscounts
+ $[id=FM_outfit_022].metaData.temporaryDiscounts
- $[id=FM_outfit_031].metaData.temporaryDiscounts
- $[id=FM_outfit_036].metaData.temporaryDiscounts
- $[id=GS_outfit_014].metaData.temporaryDiscounts
- $[id=GS_outfit_022].metaData.temporaryDiscounts
- $[id=HS_outfit_020].metaData.temporaryDiscounts
- $[id=JP_outfit_014].metaData.temporaryDiscounts
+ $[id=K20_outfit_006].metaData.temporaryDiscounts
+ $[id=K20_outfit_007].metaData.temporaryDiscounts
+ $[id=K20_outfit_008].metaData.temporaryDiscounts
- $[id=K20_outfit_009].metaData.temporaryDiscounts[0].discountPercentage: 0.5000001
+ $[id=K20_outfit_009].metaData.temporaryDiscounts[0].discountPercentage: 0.3000001
- $[id=K20_outfit_009].metaData.temporaryDiscounts[0].endDate: "2025-12-01T16:00:00"
+ $[id=K20_outfit_009].metaData.temporaryDiscounts[0].endDate: "2026-01-30T16:00:00"
- $[id=K20_outfit_009].metaData.temporaryDiscounts[0].startDate: "2025-11-28T16:00:00"
+ $[id=K20_outfit_009].metaData.temporaryDiscounts[0].startDate: "2026-01-23T16:00:00"
- $[id=K21_outfit_020].metaData.temporaryDiscounts
- $[id=K22_outfit_006].metaData.temporaryDiscounts
- $[id=K23_outfit_008].metaData.temporaryDiscounts
- $[id=K23_outfit_015].metaData.temporaryDiscounts
- $[id=K24_outfit_008].metaData.temporaryDiscounts
- $[id=K26_outfit_020].metaData.temporaryDiscounts
- $[id=K27_outfit_008].metaData.temporaryDiscounts
- $[id=K28_outfit_008].metaData.temporaryDiscounts
- $[id=K28_outfit_013].metaData.temporaryDiscounts
- $[id=K29_outfit_008].metaData.temporaryDiscounts
- $[id=K31_outfit_016].metaData.temporaryDiscounts
- $[id=K36_outfit_006].metaData.temporaryDiscounts
- $[id=K39_outfit_008].metaData.temporaryDiscounts
- $[id=K40_outfit_006].metaData.temporaryDiscounts
- $[id=K40_outfit_007].metaData.temporaryDiscounts
+ $[id=KK_outfit_016].metaData.temporaryDiscounts
+ $[id=KK_outfit_016_01].metaData.temporaryDiscounts
+ $[id=KK_outfit_016_02].metaData.temporaryDiscounts
+ $[id=KK_outfit_016_03].metaData.temporaryDiscounts
- $[id=KK_outfit_034].metaData.temporaryDiscounts
- $[id=KK_outfit_036].metaData.temporaryDiscounts
- $[id=KS_outfit_020].metaData.temporaryDiscounts
… 59 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[117].text: "Schaffe {0} Fähigkeitscheck(s) an einem Generator in einer einzigen Prüfung."
+ $.locText[117].text: "Schaffe {0} Reparatur-Fähigkeitscheck(s) in einer einzigen Prüfung."
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[517].text: "Powieś na haku ocalałych"
+ $.locText[517].text: "Powieś na haku ocalałego lub ocalałych"
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[517].text: "Kurban'ı Kancaya As"
+ $.locText[517].text: "Kancaya Kurban(lar) As"
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
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[0].MapsWeight.Sub_Street: "200"
+ $.schedule[0].MapsWeight.Sub_Street: "0"
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.halloween.isShownInGameStore: true
+ $.dlcList.halloween.isShownInGameStore: false
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[8].contentVersion: "61168829bbea2965cc63d2bcd46cf0cff71341fd"
+ $.entries[8].contentVersion: "ecb0290f30801891012945f1e447c552f3795e37"
- $.entries[82].contentVersion: "8b70affcba76241087913ee31b6aa1ae48748d0f"
+ $.entries[82].contentVersion: "859772c3ba992b1c4662fa191694c0b8ea117b27"
- $.entries[84].contentVersion: "b8a72c39a55c7ae57efb35901e2148db2fc0bee4"
+ $.entries[84].contentVersion: "fa820a91ef48d12aebefc790939fda54be26b147"
- $.entries[86].contentVersion: "c1b2ed9d38e02d1dde9443ff5745ca74dc27f03a"
+ $.entries[86].contentVersion: "e0a1441424aced0de48182787ecfa5b89e951a92"
- $.entries[168].contentVersion: "b4322ead90f2c431a4515207937979b92cdb5136"
+ $.entries[168].contentVersion: "739623a93bccb248bbf690a7263ab70601d6884e"
- $.entries[176].contentVersion: "5d398b08fba83a4acb7f0af846bd9de64f682c72"
+ $.entries[176].contentVersion: "fe6c5e5269494d759af1d68970f673e63d9083f1"
- $.entries[196].contentVersion: "08a5e7bed45e8d8cbc030ea9b57b25b95fd4601c"
+ $.entries[196].contentVersion: "5478e595186cf0d7e93a238a6b455f578c8d0bec"
- $.entries[203].contentVersion: "4faa2a2af47382262d50251071fb54c6a2a6722e"
+ $.entries[203].contentVersion: "ef38ce93f22733e17ce9e3c932408ba54f6bb5c1"
- $.entries[207].contentVersion: "10b3837d1a91646aeca7b58c21fb212fbfd420cf"
+ $.entries[207].contentVersion: "2fc3480f779bf5f061b659c9e9f70f67b45471e0"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Omelet_W6]
- $.featuredCard[id=Omelet_W5].activeTo: "2026-01-27T16:00:00"
+ $.featuredCard[id=Omelet_W5].activeTo: "2026-01-23T16:00:00"
- $.featuredCharacterRecommendations[id=Featured_Characters]
- $.featuredCharacterRecommendations[id=Featured_Characters_2]
- $.featuredCharacterRecommendations[id=Featured_Characters_3]
- $.featuredCharacterRecommendations[id=Featured_Characters_ST]
- $.featuredCharacterRecommendations[id=Featured_Characters_4].activeFrom: "2026-01-19T16:00:00Z"
+ $.featuredCharacterRecommendations[id=Featured_Characters_4].activeFrom: "2026-01-10T16:00:00Z"
- $.featuredCharacterRecommendations[id=Featured_Characters_4].activeTo: "2026-01-29T16:00:00Z"
+ $.featuredCharacterRecommendations[id=Featured_Characters_4].activeTo: "2026-01-27T16:00:00Z"
- $.featuredCustomizationRecommendations[id=OmeletW8].recommendations[id=MM_outfit_02]
- $.featuredCustomizationRecommendations[id=OmeletW8].recommendations[id=LS_outfit_006]
- $.featuredCustomizationRecommendations[id=OmeletW8].recommendations[id=MM_W02_02]
- $.featuredCustomizationRecommendations[id=OmeletW8].recommendations[id=MM_W02_03]
+ $.specialsRecommendations[id=SilentHillSale]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[61].mainEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].mainEndTime: "2026-01-27T16:00:00"
- $.specialEvents[61].postEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].postEndTime: "2026-01-27T16:00:00"
```

## Could not download

- `images/T_UI_CollectionBanner_HolidayHorror_GhostFace.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TorturedSouls.png (HTTP 404)`
- `images/T_UI_SpecialPack_HolidayHorror_GhostFace.png (HTTP 404)`
- `images/T_UI_SpecialPack_TorturedSouls.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_GenQuest1.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_cosmetic.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_gift.png (HTTP 404)`

