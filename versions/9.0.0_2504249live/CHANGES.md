# live · 9.0.0_2504249live

| | |
|---|---|
| Build date | 2025-06-13 14:39 UTC |
| CDN version | `9.0.0_2504249live-1749825542` |
| Key | `9.0.0_live` |
| Compared with | [8.7.2_2502161live](../8.7.2_2502161live/CHANGES.md) (2025-06-13 14:11 UTC) |

## Summary

**0** added · **46** modified · **0** removed · 156 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.enableGammaPopup: true
+ $.analyticsRules.KA[]: "LightingAnalytics"
- $.analyticsRulesHVS.GameInitAnalytics: "HVSStrict"
+ $.analyticsRulesHVS.GameInitAnalytics: "HVSStrictDS"
- $.enableDeniedStateTransition: false
+ $.enableDeniedStateTransition: true
+ $.match.emblemBonusThresholds
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
+ $.UseLegacyMapOfferingsBehaviour: false
+ $.disconnectionPenalty
+ $.analyticsRulesDedicatedServer.KA[]: "SurvivorExposerChangedAnalytics"
```

### [`bloodwebGenerationRules.json`](bloodwebGenerationRules.json)

[Full line-by-line diff](diffs/bloodwebGenerationRules.json.diff)

```diff
+ $.BulkCost
+ $.PrestigeModifier
+ $.EventChestProbability[11]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=K40]
+ $[id=AV_Torso021_03]
+ $[id=BE_W029]
+ $[id=CM_Head032]
+ $[id=CM_Torso027_03]
+ $[id=DF_Torso030_02]
+ $[id=DK_Head030]
+ $[id=DK_Legs030]
+ $[id=DK_Torso021_02]
+ $[id=DK_Torso030]
+ $[id=DO_W027]
+ $[id=FM_Torso030_02]
+ $[id=GS_Torso028_02]
+ $[id=HK_W025]
+ $[id=HS_Torso022_03]
+ $[id=IC_BDG_11]
+ $[id=JP_Head031]
+ $[id=JP_Torso022_02]
+ $[id=K36_Body008]
+ $[id=K36_Head008]
+ $[id=K36_W008]
+ $[id=K38_Head008]
+ $[id=K40_Body006]
+ $[id=K40_Body007]
+ $[id=K40_Body008]
+ $[id=K40_Body009]
+ $[id=K40_Body01]
+ $[id=K40_Body01_P01]
+ $[id=K40_Head006]
+ $[id=K40_Head007]
+ $[id=K40_Head008]
+ $[id=K40_Head009]
+ $[id=K40_Head01]
+ $[id=K40_Head01_P01]
+ $[id=K40_PCharm001]
+ $[id=K40_PCharm002]
+ $[id=K40_PCharm003]
+ $[id=K40_W006]
+ $[id=K40_W007]
+ $[id=K40_W008]
+ $[id=K40_W009]
+ $[id=K40_W01_P01]
+ $[id=K40_Weapon01]
+ $[id=KE_BDG_01]
+ $[id=KE_BDG_02]
+ $[id=KE_BDG_03]
+ $[id=KE_BDG_04]
+ $[id=KE_BDG_05]
+ $[id=KE_BDG_06]
+ $[id=KE_BDG_09]
+ $[id=KE_BDG_10]
+ $[id=KE_BDG_11]
+ $[id=KE_BDG_12]
+ $[id=KE_BDG_13]
+ $[id=KE_BDG_14]
+ $[id=KE_BDG_15]
+ $[id=KE_BDG_16]
+ $[id=KE_BDG_17]
+ $[id=KE_BNR_01]
+ $[id=KE_BNR_02]
+ $[id=KE_BNR_03]
+ $[id=KE_BNR_04]
+ $[id=KE_BNR_05]
+ $[id=KE_BNR_06]
+ $[id=KE_BNR_08]
+ $[id=KE_BNR_09]
+ $[id=KE_BNR_10]
+ $[id=KE_BNR_11]
+ $[id=KET_001]
+ $[id=KS_Torso021_02]
+ $[id=MS_Torso022_02]
+ $[id=MT_Torso028_02]
+ $[id=NK_Torso028_03]
+ $[id=S23_Torso026_02]
+ $[id=S24_Torso020_02]
+ $[id=S25_Torso022_02]
+ $[id=S28_Torso022_02]
+ $[id=S29_Torso016_02]
+ $[id=S31_Torso015_02]
+ $[id=S34_Head024]
+ $[id=S34_Torso016_02]
+ $[id=S35_Torso014_02]
+ $[id=S36_Torso015_02]
+ $[id=S37_Torso014_02]
+ $[id=S41_Head018]
+ $[id=S41_Torso015_01]
+ $[id=S42_Accessory011]
+ $[id=S42_Legs011]
+ $[id=S42_Torso011]
+ $[id=S45_Head013]
+ $[id=S45_Torso009_01]
+ $[id=S46_Head010]
+ $[id=S46_Torso011]
+ $[id=SS_Torso023_02]
+ $[id=TN_W024]
+ $[id=TR_W028]
+ $[id=TW_Body023]
+ $[id=TW_Head023]
+ $[id=TW_W023]
+ $[id=US_Torso022_02]
+ $[id=DK_outfit_030]
+ $[id=K36_outfit_008]
+ $[id=K40_outfit_006]
+ $[id=K40_outfit_007]
+ $[id=K40_outfit_008]
+ $[id=K40_outfit_009]
+ $[id=K40_outfit_01]
+ $[id=K40_outfit_01_P01]
+ $[id=S42_outfit_011]
+ $[id=TW_outfit_023]
+ $[id=FNAF_Shirt_Bundle]
+ $[id=TM_Killer_Mask_Bundle]
+ $[id=TM_Survivor_Mask_Bundle]
+ $[id=TwistedMasqueradeBundle]
+ $[id=From_The_Rift_Bundle_250617]
+ $[id=Recurring_Charm_Bundle_250617]
+ $[id=Recurring_Dev_Bundle_250617]
+ $[id=Recurring_Killer_Bundle_250617]
+ $[id=Recurring_Survivor_Bundle_250617]
- $[id=K39].metaData.characterStartingInventory[itemId=Addon_K39_03]
+ $[id=K39].metaData.characterStartingInventory[itemId=Addon_K39_01]
- $[id=K39].metaData.characterStartingInventory[itemId=Addon_K39_08].autoEquip: true
+ $[id=K39].metaData.characterStartingInventory[itemId=Addon_K39_08].autoEquip: false
- $[id=AV_Head016].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=AV_Head016].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=AV_Head022].metaData.availablePeriods[1].endDate: "2025-04-29T15:00:00"
+ $[id=AV_Head022].metaData.availablePeriods[1].endDate: "2025-03-10T16:00:00"
- $[id=AV_Head022].metaData.availablePeriods[1].startDate: "2025-04-07T15:00:00"
+ $[id=AV_Head022].metaData.availablePeriods[1].startDate: "2025-01-07T16:00:00"
+ $[id=AV_Head022].metaData.availablePeriods[2]
- $[id=AV_Legs022].metaData.availablePeriods[1].endDate: "2025-04-29T15:00:00"
+ $[id=AV_Legs022].metaData.availablePeriods[1].endDate: "2025-03-10T16:00:00"
- $[id=AV_Legs022].metaData.availablePeriods[1].startDate: "2025-04-07T15:00:00"
+ $[id=AV_Legs022].metaData.availablePeriods[1].startDate: "2025-01-07T16:00:00"
+ $[id=AV_Legs022].metaData.availablePeriods[2]
- $[id=AV_Torso022].metaData.availablePeriods[1].endDate: "2025-04-29T15:00:00"
+ $[id=AV_Torso022].metaData.availablePeriods[1].endDate: "2025-03-10T16:00:00"
- $[id=AV_Torso022].metaData.availablePeriods[1].startDate: "2025-04-07T15:00:00"
+ $[id=AV_Torso022].metaData.availablePeriods[1].startDate: "2025-01-07T16:00:00"
+ $[id=AV_Torso022].metaData.availablePeriods[2]
- $[id=BE_Mask015].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=BE_Mask015].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=BO_Head008].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=BO_Head008].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=BO_Legs008].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=BO_Legs008].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=BO_Torso008].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=BO_Torso008].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=CM_Head030].metaData.availablePeriods[0].endDate: "2025-04-29T15:00:00"
+ $[id=CM_Head030].metaData.availablePeriods[0].endDate: "2025-04-29T16:00:00"
- $[id=CM_Legs030].metaData.availablePeriods[0].endDate: "2025-04-29T15:00:00"
+ $[id=CM_Legs030].metaData.availablePeriods[0].endDate: "2025-04-29T16:00:00"
- $[id=CM_Torso030].metaData.availablePeriods[0].endDate: "2025-04-29T15:00:00"
+ $[id=CM_Torso030].metaData.availablePeriods[0].endDate: "2025-04-29T16:00:00"
- $[id=DF_Head019].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=DF_Head019].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=DO_Body020].metaData.availablePeriods[1].endDate: "2025-04-29T15:00:00"
+ $[id=DO_Body020].metaData.availablePeriods[1].endDate: "2025-03-10T16:00:00"
- $[id=DO_Body020].metaData.availablePeriods[1].startDate: "2025-04-07T15:00:00"
+ $[id=DO_Body020].metaData.availablePeriods[1].startDate: "2025-01-07T16:00:00"
+ $[id=DO_Body020].metaData.availablePeriods[2]
- $[id=DO_Head020].metaData.availablePeriods[1].endDate: "2025-04-29T15:00:00"
+ $[id=DO_Head020].metaData.availablePeriods[1].endDate: "2025-03-10T16:00:00"
- $[id=DO_Head020].metaData.availablePeriods[1].startDate: "2025-04-07T15:00:00"
+ $[id=DO_Head020].metaData.availablePeriods[1].startDate: "2025-01-07T16:00:00"
+ $[id=DO_Head020].metaData.availablePeriods[2]
- $[id=DO_Head024].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=DO_Head024].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=DO_W020].metaData.availablePeriods[1].endDate: "2025-04-29T15:00:00"
+ $[id=DO_W020].metaData.availablePeriods[1].endDate: "2025-03-10T16:00:00"
- $[id=DO_W020].metaData.availablePeriods[1].startDate: "2025-04-07T15:00:00"
+ $[id=DO_W020].metaData.availablePeriods[1].startDate: "2025-01-07T16:00:00"
+ $[id=DO_W020].metaData.availablePeriods[2]
+ $[id=FK_Body010].metaData.eventID: "Anniversary2024"
- $[id=FK_Body010].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=FK_Body010].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
+ $[id=FK_Mask010].metaData.eventID: "Anniversary2024"
- $[id=FK_Mask010].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=FK_Mask010].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
+ $[id=FK_W010].metaData.eventID: "Anniversary2024"
- $[id=FK_W010].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=FK_W010].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
+ $[id=FM_Head025].metaData.eventID: "Anniversary2023"
- $[id=FM_Head025].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=FM_Head025].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
+ $[id=FM_Legs025].metaData.eventID: "Anniversary2023"
- $[id=FM_Legs025].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=FM_Legs025].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
+ $[id=FM_Torso025].metaData.eventID: "Anniversary2023"
- $[id=FM_Torso025].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=FM_Torso025].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=FS_Head011].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=FS_Head011].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=GE_BDG_03].metaData.eventID: "0"
- $[id=GE_BNR_03].metaData.eventID: "0"
- $[id=GK_Head021].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=GK_Head021].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=GS_Head031].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
+ $[id=GS_Head031].metaData.availablePeriods[0].endDate: "2025-07-16T16:00:00"
- $[id=HK_Head015].metaData.availablePeriods[0].endDate: "2024-07-04T15:00:00"
… 231 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
+ $.locText[200]
+ $.locText[201]
+ $.locText[202]
+ $.locText[203]
+ $.locText[204]
+ $.locText[205]
+ $.locText[206]
+ $.locText[207]
+ $.locText[208]
+ $.locText[209]
+ $.locText[210]
+ $.locText[211]
+ $.locText[212]
+ $.locText[213]
+ $.locText[214]
+ $.locText[215]
+ $.locText[216]
+ $.locText[217]
+ $.locText[218]
+ $.locText[219]
+ $.locText[220]
+ $.locText[221]
+ $.locText[222]
+ $.locText[223]
+ $.locText[224]
+ $.locText[225]
+ $.locText[226]
+ $.locText[227]
+ $.locText[228]
+ $.locText[229]
+ $.locText[230]
+ $.locText[231]
+ $.locText[232]
+ $.locText[233]
+ $.locText[234]
+ $.locText[235]
+ $.locText[236]
+ $.locText[237]
+ $.locText[238]
+ $.locText[239]
+ $.locText[240]
+ $.locText[241]
+ $.locText[242]
+ $.locText[243]
+ $.locText[244]
+ $.locText[245]
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
+ $.AnniversaryKetchupSet
+ $.CalamariJerky.challengeList[2].challenges[id=CalamariJerky-List_3-D_HitOrHeal].objectives.HealPerc.conditions[key=gameTypes]
+ $.CalamariJerky.challengeList[2].challenges[id=CalamariJerky-List_3-D_HitOrHeal].objectives.Hit.conditions[key=gameTypes]
- $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-B_CompleteTrial].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-B_CompleteTrial].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-D_HookOrUnhook].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-D_HookOrUnhook].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-B_Sacrifice].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-B_Sacrifice].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-B_Repair].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[1].challenges[id=ChocolateBoxJerkySet-List_2-B_Repair].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-B_EarnBloodpoints].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-B_EarnBloodpoints].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-D_DownOrSucceedHealSkillCheck].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-D_DownOrSucceedHealSkillCheck].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-B_Hit].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-B_Hit].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-B_Escape].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[2].challenges[id=ChocolateBoxJerkySet-List_3-B_Escape].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_EarnEmblemsGold].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_EarnEmblemsGold].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-D_ChaseOrBeChased].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-D_ChaseOrBeChased].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_BreakPallet].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_BreakPallet].rewards[id=BonusBloodpoints].amount: 15000
- $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_VaultInChase].isRecurring: true
+ $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_VaultInChase].isRecurring: false
- $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_VaultInChase].rewards[id=BonusBloodpoints].amount: 10000
+ $.ChocolateBoxJerkySet.challengeList[3].challenges[id=ChocolateBoxJerkySet-List_4-B_VaultInChase].rewards[id=BonusBloodpoints].amount: 15000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].rewards[id=BonusBloodpoints].amount: 2500
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].rewards[id=BonusBloodpoints].amount: 5000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HitOrHeal].rewards[id=BonusBloodpoints].amount: 2500
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HitOrHeal].rewards[id=BonusBloodpoints].amount: 5000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].rewards[id=BonusBloodpoints].amount: 2500
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].rewards[id=BonusBloodpoints].amount: 5000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].rewards[id=BonusBloodpoints].amount: 2500
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].rewards[id=BonusBloodpoints].amount: 5000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_EarnBloodpoints].rewards[id=BonusBloodpoints].amount: 15000
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_EarnBloodpoints].rewards[id=BonusBloodpoints].amount: 5000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_CompleteTrial].rewards[id=BonusBloodpoints].amount: 2500
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_CompleteTrial].rewards[id=BonusBloodpoints].amount: 5000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_ChaseOrBeChased].rewards[id=BonusBloodpoints].amount: 2500
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_ChaseOrBeChased].rewards[id=BonusBloodpoints].amount: 5000
- $.Rift_01_QuestSet.challengeList[3].challenges[id=Rift_01_QuestSet-List_4-B_CoopAction].rewards[id=Bloodpoints]
+ $.Rift_01_QuestSet.challengeList[3].challenges[id=Rift_01_QuestSet-List_4-B_CoopAction].rewards[id=BonusBloodpoints]
- $.Rift_01_QuestSet.challengeList[5].challenges[id=Rift_01_QuestSet-List_6-B_BeChased].lifetimeInDays: 200
- $.Rift_01_QuestSet.challengeList[5].challenges[id=Rift_01_QuestSet-List_6-B_BeChased].objectives.ChasedByKiller.neededProgression[]: 60
+ $.Rift_01_QuestSet.challengeList[5].challenges[id=Rift_01_QuestSet-List_6-B_BeChased].objectives.ChasedByKiller.neededProgression[]: 200
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[11].updatedDate: "2025-06-10T12:24:23.183Z"
+ $.collections[11].updatedDate: "2025-06-10T13:17:25.228Z"
+ $.collections[13].additionalImages[0]
- $.collections[13].collectionId: "Rockabilly"
+ $.collections[13].collectionId: "FNAF"
- $.collections[13].collectionTitle.de: "Rockabilly"
+ $.collections[13].collectionTitle.de: "Five Nights at Freddy’s"
- $.collections[13].collectionTitle.en: "Rockabilly"
+ $.collections[13].collectionTitle.en: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.es: "Rockabilly"
+ $.collections[13].collectionTitle.es: "Five Nights at Freddy's"
- $.collections[13].collectionTitle["es-MX"]: "Rockabilly"
+ $.collections[13].collectionTitle["es-MX"]: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.fr: "Rockabilly"
+ $.collections[13].collectionTitle.fr: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.it: "Rockabilly"
+ $.collections[13].collectionTitle.it: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.ja: "ロカビリー "
+ $.collections[13].collectionTitle.ja: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.ko: "로커빌리"
+ $.collections[13].collectionTitle.ko: "프레디의 피자 가게"
- $.collections[13].collectionTitle.pl: "Rockabilly"
+ $.collections[13].collectionTitle.pl: "Five Nights at Freddy's"
- $.collections[13].collectionTitle["pt-BR"]: "Rockabilly"
+ $.collections[13].collectionTitle["pt-BR"]: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.ru: "Рокабилли"
+ $.collections[13].collectionTitle.ru: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.th: "ร็อกอะบิลลี่"
+ $.collections[13].collectionTitle.th: "Five Nights at Freddy's"
- $.collections[13].collectionTitle.tr: "Rockabilly"
+ $.collections[13].collectionTitle.tr: "Five Nights at Freddy's"
- $.collections[13].collectionTitle["zh-Hans"]: "山区摇滚"
+ $.collections[13].collectionTitle["zh-Hans"]: "《玩具熊的五夜后宫》"
- $.collections[13].collectionTitle["zh-Hant"]: "鄉村搖滾"
+ $.collections[13].collectionTitle["zh-Hant"]: "《佛雷迪的五夜驚魂》"
- $.collections[13].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
+ $.collections[13].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_FNAF.T_UI_CollectionBanner_FNAF"
- $.collections[13].inclusionVersion: "7.7.0 PTB"
+ $.collections[13].inclusionVersion: "9.0.0"
- $.collections[13].items[]: "AV_outfit_015"
- $.collections[13].items[]: "MS_outfit_014"
- $.collections[13].items[]: "GS_outfit_014"
- $.collections[13].items[]: "MT_outfit_015"
- $.collections[13].items[]: "NK_outfit_014"
- $.collections[13].items[]: "S23_outfit_016"
- $.collections[13].items[]: "S24_outfit_013"
+ $.collections[13].items[]: "K40_outfit_006"
+ $.collections[13].items[]: "K40_outfit_007"
+ $.collections[13].items[]: "K40_outfit_008"
+ $.collections[13].items[]: "K40_outfit_009"
+ $.collections[13].items[]: "DF_Torso030_02"
+ $.collections[13].items[]: "MT_Torso028_02"
+ $.collections[13].items[]: "CM_Torso027_03"
+ $.collections[13].items[]: "JP_Torso022_02"
+ $.collections[13].items[]: "NK_Torso028_03"
+ $.collections[13].items[]: "AV_Torso021_03"
+ $.collections[13].items[]: "FM_Torso030_02"
+ $.collections[13].items[]: "DK_Torso021_02"
+ $.collections[13].items[]: "GS_Torso028_02"
+ $.collections[13].items[]: "HS_Torso022_03"
+ $.collections[13].items[]: "KS_Torso021_02"
+ $.collections[13].items[]: "MS_Torso022_02"
+ $.collections[13].items[]: "SS_Torso023_02"
+ $.collections[13].items[]: "US_Torso022_02"
+ $.collections[13].items[]: "S23_Torso026_02"
+ $.collections[13].items[]: "S24_Torso020_02"
+ $.collections[13].items[]: "S25_Torso022_02"
+ $.collections[13].items[]: "S28_Torso022_02"
+ $.collections[13].items[]: "S29_Torso016_02"
+ $.collections[13].items[]: "S31_Torso015_02"
+ $.collections[13].items[]: "S34_Torso016_02"
+ $.collections[13].items[]: "S35_Torso014_02"
+ $.collections[13].items[]: "S36_Torso015_02"
+ $.collections[13].items[]: "S37_Torso014_02"
+ $.collections[13].items[]: "S41_Torso015_01"
+ $.collections[13].items[]: "S45_Torso009_01"
+ $.collections[13].items[]: "S46_Torso011"
- $.collections[13].sortOrder: "-14"
+ $.collections[13].sortOrder: "-130"
- $.collections[13].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[13].updatedDate: "2025-03-24T13:48:40.504Z"
- $.collections[14].collectionId: "SpringEnsembles"
+ $.collections[14].collectionId: "Rockabilly"
- $.collections[14].collectionTitle.de: "Frühlings-Ensembles"
+ $.collections[14].collectionTitle.de: "Rockabilly"
- $.collections[14].collectionTitle.en: "Spring Ensembles"
+ $.collections[14].collectionTitle.en: "Rockabilly"
- $.collections[14].collectionTitle.es: "Conjuntos de primavera"
+ $.collections[14].collectionTitle.es: "Rockabilly"
- $.collections[14].collectionTitle["es-MX"]: "Conjuntos de primavera"
+ $.collections[14].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[14].collectionTitle.fr: "Ensembles printaniers"
+ $.collections[14].collectionTitle.fr: "Rockabilly"
- $.collections[14].collectionTitle.it: "Completi primaverili"
+ $.collections[14].collectionTitle.it: "Rockabilly"
- $.collections[14].collectionTitle.ja: "春のアンサンブル"
+ $.collections[14].collectionTitle.ja: "ロカビリー "
- $.collections[14].collectionTitle.ko: "봄의 조화"
+ $.collections[14].collectionTitle.ko: "로커빌리"
- $.collections[14].collectionTitle.pl: "Wiosenne stroje"
+ $.collections[14].collectionTitle.pl: "Rockabilly"
- $.collections[14].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
+ $.collections[14].collectionTitle["pt-BR"]: "Rockabilly"
- $.collections[14].collectionTitle.ru: "Весенний ансамбль"
+ $.collections[14].collectionTitle.ru: "Рокабилли"
- $.collections[14].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
+ $.collections[14].collectionTitle.th: "ร็อกอะบิลลี่"
- $.collections[14].collectionTitle.tr: "Bahar Kreasyonu"
+ $.collections[14].collectionTitle.tr: "Rockabilly"
- $.collections[14].collectionTitle["zh-Hans"]: "春日套装"
+ $.collections[14].collectionTitle["zh-Hans"]: "山区摇滚"
- $.collections[14].collectionTitle["zh-Hant"]: "春天靈魂"
+ $.collections[14].collectionTitle["zh-Hant"]: "鄉村搖滾"
- $.collections[14].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
+ $.collections[14].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
- $.collections[14].items[]: "Ace_outfit_008_01"
- $.collections[14].items[]: "HillBilly_outfit_008_01"
- $.collections[14].items[]: "FM_outfit_011"
- $.collections[14].items[]: "FM_outfit_011_01"
- $.collections[14].items[]: "S28_outfit_011"
- $.collections[14].items[]: "US_outfit_015"
- $.collections[14].items[]: "K21_outfit_010"
- $.collections[14].items[]: "K26_outfit_007"
- $.collections[14].items[]: "GK_outfit_013"
- $.collections[14].items[]: "S29_outfit_008"
+ $.collections[14].items[]: "AV_outfit_015"
+ $.collections[14].items[]: "MS_outfit_014"
+ $.collections[14].items[]: "GS_outfit_014"
+ $.collections[14].items[]: "MT_outfit_015"
+ $.collections[14].items[]: "NK_outfit_014"
+ $.collections[14].items[]: "S23_outfit_016"
+ $.collections[14].items[]: "S24_outfit_013"
- $.collections[14].sortOrder: "-15"
+ $.collections[14].sortOrder: "-14"
- $.collections[14].updatedDate: "2024-02-20T17:45:49Z"
+ $.collections[14].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[15].collectionId: "PopSuperstar"
+ $.collections[15].collectionId: "SpringEnsembles"
- $.collections[15].collectionTitle.de: "Superpopstar"
+ $.collections[15].collectionTitle.de: "Frühlings-Ensembles"
- $.collections[15].collectionTitle.en: "Pop Superstar"
+ $.collections[15].collectionTitle.en: "Spring Ensembles"
- $.collections[15].collectionTitle.es: "Superestrella del pop"
+ $.collections[15].collectionTitle.es: "Conjuntos de primavera"
- $.collections[15].collectionTitle["es-MX"]: "Superestrella del pop"
+ $.collections[15].collectionTitle["es-MX"]: "Conjuntos de primavera"
- $.collections[15].collectionTitle.fr: "Superstar de la pop"
+ $.collections[15].collectionTitle.fr: "Ensembles printaniers"
- $.collections[15].collectionTitle.it: "Superstar pop"
+ $.collections[15].collectionTitle.it: "Completi primaverili"
- $.collections[15].collectionTitle.ja: "ポップスター"
+ $.collections[15].collectionTitle.ja: "春のアンサンブル"
- $.collections[15].collectionTitle.ko: "팝 슈퍼스타"
+ $.collections[15].collectionTitle.ko: "봄의 조화"
- $.collections[15].collectionTitle.pl: "Supergwiazda popu"
+ $.collections[15].collectionTitle.pl: "Wiosenne stroje"
- $.collections[15].collectionTitle["pt-BR"]: "Estrela Pop"
+ $.collections[15].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
- $.collections[15].collectionTitle.ru: "Поп-суперзвезда"
+ $.collections[15].collectionTitle.ru: "Весенний ансамбль"
- $.collections[15].collectionTitle.th: "ซูเปอร์สตาร์ป็อป"
+ $.collections[15].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
- $.collections[15].collectionTitle.tr: "Popçu Süperstar"
+ $.collections[15].collectionTitle.tr: "Bahar Kreasyonu"
- $.collections[15].collectionTitle["zh-Hans"]: "流行巨星"
+ $.collections[15].collectionTitle["zh-Hans"]: "春日套装"
- $.collections[15].collectionTitle["zh-Hant"]: "流行巨星"
+ $.collections[15].collectionTitle["zh-Hant"]: "春天靈魂"
- $.collections[15].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_PopSuperstar.T_UI_CollectionBanner_PopSuperstar"
+ $.collections[15].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
- $.collections[15].items[]: "FM_outfit_020"
- $.collections[15].items[]: "GS_outfit_020"
- $.collections[15].items[]: "S25_outfit_013"
- $.collections[15].items[]: "K23_outfit_012"
+ $.collections[15].items[]: "Ace_outfit_008_01"
+ $.collections[15].items[]: "HillBilly_outfit_008_01"
+ $.collections[15].items[]: "FM_outfit_011"
+ $.collections[15].items[]: "FM_outfit_011_01"
+ $.collections[15].items[]: "S28_outfit_011"
+ $.collections[15].items[]: "US_outfit_015"
+ $.collections[15].items[]: "K21_outfit_010"
+ $.collections[15].items[]: "K26_outfit_007"
+ $.collections[15].items[]: "GK_outfit_013"
+ $.collections[15].items[]: "S29_outfit_008"
- $.collections[15].sortOrder: "-16"
+ $.collections[15].sortOrder: "-15"
- $.collections[15].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[15].updatedDate: "2024-02-20T17:45:49Z"
- $.collections[17].collectionId: "HookedOnYou"
+ $.collections[17].collectionId: "PopSuperstar"
- $.collections[17].collectionTitle.de: "Hooked on You"
+ $.collections[17].collectionTitle.de: "Superpopstar"
- $.collections[17].collectionTitle.en: "Hooked on You"
+ $.collections[17].collectionTitle.en: "Pop Superstar"
- $.collections[17].collectionTitle.es: "Hooked on You"
+ $.collections[17].collectionTitle.es: "Superestrella del pop"
- $.collections[17].collectionTitle["es-MX"]: "Hooked on You"
+ $.collections[17].collectionTitle["es-MX"]: "Superestrella del pop"
- $.collections[17].collectionTitle.fr: "Hooked on You"
+ $.collections[17].collectionTitle.fr: "Superstar de la pop"
… 3756 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
+ $.schedule[0].MapsWeight.Apl_Level_02: "750"
- $.schedule[0].MapsWeight.Apl_Level_01: "1000"
+ $.schedule[0].MapsWeight.Apl_Level_01: "750"
+ $.schedule[5]
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
+ $.dlcList.Ketchup
+ $.dlcList.ACPack_01.platforms.steam: "555"
+ $.dlcList.ACPack_02.platforms.steam: "556"
+ $.dlcList.ACPack_03.platforms.steam: "557"
+ $.dlcList.ACPack_04.platforms.steam: "558"
+ $.dlcList.ACPack_05.platforms.steam: "559"
+ $.dlcList.ACPack_06.platforms.steam: "560"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].downloadStrategy: "preferRemote"
+ $.entries[0].downloadStrategy: "preferPackaged"
- $.entries[1].contentVersion: "3084f38e5edcb7cd4aeb11eb7a348407c2eaef89"
+ $.entries[1].contentVersion: "50bce6cb7ae6795b14f8cc3e33991c49dfdc6826"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TheWitcherCharacters.T_UI_SpecialPack_TheWitcherCharacters"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_FiveNightsAtFreddys.T_UI_ChapterBundle_FiveNightsAtFreddys"
- $.entries[1].uri: "images/T_UI_SpecialPack_TheWitcherCharacters.png"
+ $.entries[1].uri: "images/T_UI_ChapterBundle_FiveNightsAtFreddys.png"
- $.entries[2].contentVersion: "aafe2985b23869cd78a102bf84b4620acddaa700"
+ $.entries[2].contentVersion: "2e79221d369501f1b160482045957fbffc1e7a77"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_TheWitcher.T_UI_CollectionBanner_TheWitcher"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_FNAF.T_UI_CollectionBanner_FNAF"
- $.entries[2].uri: "images/T_UI_CollectionBanner_TheWitcher.png"
+ $.entries[2].uri: "images/T_UI_CollectionBanner_FNAF.png"
- $.entries[3].contentVersion: "c94cbb47cd9932ab91b21f55c36eb8662ba2dc62"
+ $.entries[3].contentVersion: "7de10c5e7961a12c8616a769b69d684ae8aa47ef"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TheWitcher.T_UI_SpecialPack_TheWitcher"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_FNAF.T_UI_SpecialPack_FNAF"
- $.entries[3].uri: "images/T_UI_SpecialPack_TheWitcher.png"
+ $.entries[3].uri: "images/T_UI_SpecialPack_FNAF.png"
- $.entries[4].contentVersion: "6562f63daf105cf849eed7fbc5099a700e552b16"
+ $.entries[4].contentVersion: "7a974f9bf898fec538651311fa3fc4c4ebb9e796"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].enableChecksum: false
+ $.entries[4].enableChecksum: true
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_CatsAndDogs_2.T_UI_CollectionBanner_CatsAndDogs_2"
+ $.entries[4].packagedPath: ""
- $.entries[4].schema: "s3verbin://"
+ $.entries[4].schema: "s3ver://"
- $.entries[4].uri: "images/T_UI_CollectionBanner_CatsAndDogs_2.png"
+ $.entries[4].uri: "catalog.json"
- $.entries[5].contentVersion: "0ea7b469b098d6224e972dbd597f42995fb49d4d"
+ $.entries[5].contentVersion: "ee119afb003a3abe4599e4b70a42a6563365b9b3"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].enableChecksum: false
+ $.entries[5].enableChecksum: true
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_CatsAndDogs.T_UI_SpecialPack_CatsAndDogs"
+ $.entries[5].packagedPath: ""
- $.entries[5].schema: "s3verbin://"
+ $.entries[5].schema: "s3ver://"
- $.entries[5].uri: "images/T_UI_SpecialPack_CatsAndDogs.png"
+ $.entries[5].uri: "bonusPointEventsContent.json"
- $.entries[6].contentVersion: "b6e198ca0a1d1b4deba6aad6827ac4e0d103010a"
+ $.entries[6].contentVersion: "bbbc0d307d57d2edad6c97731f4dcd5385d4a64b"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Chrysalis_2.T_UI_CollectionBanner_Chrysalis_2"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_CollectionBanner_Chrysalis_2.png"
+ $.entries[6].uri: "freetoplay/NA/event.json"
- $.entries[7].contentVersion: "4713f2bd0c312750f2db839895d193501a7af8c9"
+ $.entries[7].contentVersion: "bbbc0d307d57d2edad6c97731f4dcd5385d4a64b"
- $.entries[7].uri: "catalog.json"
+ $.entries[7].uri: "freetoplay/EU/event.json"
- $.entries[8].contentVersion: "48c434c9568206d7a07219a16bb6030660ccbd0d"
+ $.entries[8].contentVersion: "3d79e5d3c0f38ac103d12f8a7216990f76887235"
- $.entries[8].uri: "bonusPointEventsContent.json"
+ $.entries[8].uri: "archiveQuests/Anniversary2022.json"
- $.entries[9].contentVersion: "07eb9b9415ed24d7cdfdc50f094026ef135e0f47"
+ $.entries[9].contentVersion: "5fc2e74b6547cad57aaa22fa61e18f24b1c6659d"
- $.entries[9].uri: "freetoplay/NA/event.json"
+ $.entries[9].uri: "archiveQuests/Anniversary2023.json"
- $.entries[10].contentVersion: "07eb9b9415ed24d7cdfdc50f094026ef135e0f47"
+ $.entries[10].contentVersion: "baac2c534846886f85a06f6e53c1900d9e2147c8"
- $.entries[10].uri: "freetoplay/EU/event.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2024.json"
- $.entries[11].contentVersion: "4bac4e19e047e62ec43c1b836d69ab8762a950fa"
+ $.entries[11].contentVersion: "ea1176851d28dda829d7a3483fdd65ee2f96252d"
- $.entries[11].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[11].uri: "archiveQuests/CalamariV1.json"
- $.entries[12].contentVersion: "13c02c24909062ef1334e57ec50c29717a748432"
+ $.entries[12].contentVersion: "a8701575be23d4eb00f57821e65b55126651c39c"
- $.entries[12].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[12].uri: "archiveQuests/CalamariV2.json"
- $.entries[13].contentVersion: "ede6f2158fc42858d544821ac8adf2eb514b795b"
+ $.entries[13].contentVersion: "fcc9d38ca8076c713715bdc3df7450093f99efa0"
- $.entries[13].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[13].uri: "archiveQuests/CalamariV3.json"
- $.entries[14].contentVersion: "511fcfe12d8932f327cb5cd91ff1aa40456d7d14"
+ $.entries[14].contentVersion: "0b3b85c9a115171243104b58cc30d455f193604b"
- $.entries[14].uri: "archiveQuests/CalamariV1.json"
+ $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[15].contentVersion: "e731647ace1a48d508e7bee52dc5d0352d95a1e3"
+ $.entries[15].contentVersion: "7f656c9cc903be74c6ada4c5a7d76d54dff6f6a3"
- $.entries[15].uri: "archiveQuests/CalamariV2.json"
+ $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[16].contentVersion: "e0b8dd88a1e3345edbe54900ae4c845400f46738"
+ $.entries[16].contentVersion: "78a5dae70495a089228cca71b5680813c39a760d"
- $.entries[16].uri: "archiveQuests/CalamariV3.json"
+ $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[17].contentVersion: "83bf5af0d56f10dbc8b978e3ddd73d49c2ead2f3"
+ $.entries[17].contentVersion: "f4bee6e3aac4fd6ff1018d424e5767e03b13d2e9"
- $.entries[17].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[17].uri: "archiveQuests/FireflyV1.json"
- $.entries[18].contentVersion: "5e924bb0450e87ee240172c2878adcd173325e74"
+ $.entries[18].contentVersion: "d0beaab94a8b37c6f7ac7f9cb889f7ab09421eae"
- $.entries[18].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[18].uri: "archiveQuests/Halloween2021.json"
- $.entries[19].contentVersion: "83f0ea53da71a92ec8507b28727c43032c1a96cd"
+ $.entries[19].contentVersion: "4ec20a78dde46c90f18875489757d6c3daf5bc3a"
- $.entries[19].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[19].uri: "archiveQuests/Halloween2022.json"
- $.entries[20].contentVersion: "cdeb9f32312f3aa5c5f6884aaed9d94cbc3067f6"
+ $.entries[20].contentVersion: "f1d5d934cc04c244c0229983dd79b67fc4c55beb"
- $.entries[20].uri: "archiveQuests/FireflyV1.json"
+ $.entries[20].uri: "archiveQuests/Halloween2023.json"
- $.entries[21].contentVersion: "8baf93bb073bd2b7039afe426126750ab77161af"
+ $.entries[21].contentVersion: "93bc73c450b3a5a6fd460fa190eb5bbfff78bce5"
- $.entries[21].uri: "archiveQuests/Halloween2021.json"
+ $.entries[21].uri: "archiveQuests/Halloween2024.json"
- $.entries[22].contentVersion: "54d10822aa7aefbd52abc8f9471f23c8088438ba"
+ $.entries[22].contentVersion: "a5e96d81cf9d60a62929e46bccad53702e589a77"
- $.entries[22].uri: "archiveQuests/Halloween2022.json"
+ $.entries[22].uri: "archiveQuests/Spring2024.json"
- $.entries[23].contentVersion: "e5e6d725f59bf4fc4d791c56f9988ec11f25bfe3"
+ $.entries[23].contentVersion: "acd27f87e9da430c2425ef37d7fe8012e038e88e"
- $.entries[23].uri: "archiveQuests/Halloween2023.json"
+ $.entries[23].uri: "archiveQuests/Spring2025.json"
- $.entries[24].contentVersion: "d7b7a12fb0cc409cba963b1f65fbbc81a1949d54"
+ $.entries[24].contentVersion: "a243d259c3909a0d195ac55823368c39272c1d82"
- $.entries[24].uri: "archiveQuests/Halloween2024.json"
+ $.entries[24].uri: "archiveQuests/Summer2023.json"
- $.entries[25].contentVersion: "847012e454a602876edb7893618e5f581f14c5f0"
+ $.entries[25].contentVersion: "4778974a5941f12c14a933f31bc0cb2a24fb972e"
- $.entries[25].uri: "archiveQuests/Spring2024.json"
+ $.entries[25].uri: "archiveQuests/Tome01.json"
- $.entries[26].contentVersion: "7be773dda3216d90fc6f5739863abb2a322b6301"
+ $.entries[26].contentVersion: "4cbff6c453c8bd64e47f94c926b94abd92e8cace"
- $.entries[26].uri: "archiveQuests/Spring2025.json"
+ $.entries[26].uri: "archiveQuests/Tome02.json"
- $.entries[27].contentVersion: "13ae11cd3030c12665d6b76df6034182352e621e"
+ $.entries[27].contentVersion: "5036305610c36c2e019a43e26de48f2ec452c42a"
- $.entries[27].uri: "archiveQuests/Summer2023.json"
+ $.entries[27].uri: "archiveQuests/Tome03.json"
- $.entries[28].contentVersion: "09d2f61b3030db8a0f349193c0d92df47b834ae1"
+ $.entries[28].contentVersion: "5220ef03719ae476e386fcca63fd1ee11ed3b9c7"
- $.entries[28].uri: "archiveQuests/Tome01.json"
+ $.entries[28].uri: "archiveQuests/Tome04.json"
- $.entries[29].contentVersion: "8bc4de6199abd068713f51424e3cee409b7404cc"
+ $.entries[29].contentVersion: "81e204ca4e3e7a08c4aba509a300d049e1bbf05e"
- $.entries[29].uri: "archiveQuests/Tome02.json"
+ $.entries[29].uri: "archiveQuests/Tome05.json"
- $.entries[30].contentVersion: "c997f7d1342a75f49bdc75bd665277427cfda7a4"
+ $.entries[30].contentVersion: "aab27337a175139675c6593640404462e0fb026a"
- $.entries[30].uri: "archiveQuests/Tome03.json"
+ $.entries[30].uri: "archiveQuests/Tome06.json"
- $.entries[31].contentVersion: "7030a9eaa188131580a6cd4d63bf7e112d9b7f6d"
+ $.entries[31].contentVersion: "d565bb24eee4033846f9c7b44e3fa79c65f22184"
- $.entries[31].uri: "archiveQuests/Tome04.json"
+ $.entries[31].uri: "archiveQuests/Tome07.json"
- $.entries[32].contentVersion: "b31561ce74b2ab9a724c722c9a92a7538e53f12a"
+ $.entries[32].contentVersion: "9a70cb6fdf8a2754a30d80b58f3a258a3a3dfbcd"
- $.entries[32].uri: "archiveQuests/Tome05.json"
+ $.entries[32].uri: "archiveQuests/Tome08.json"
- $.entries[33].contentVersion: "d0a5c110398f97d932f2da5ffcb6e54785a39a92"
+ $.entries[33].contentVersion: "462b3ea0ac866fd453deaf359362b53887993fe8"
- $.entries[33].uri: "archiveQuests/Tome06.json"
+ $.entries[33].uri: "archiveQuests/Tome09.json"
- $.entries[34].contentVersion: "52a9cc68dce35ad83e06f59a1ce2912d386e6995"
+ $.entries[34].contentVersion: "14f908e42c1515cdc605804fd964cb91748c4f09"
- $.entries[34].uri: "archiveQuests/Tome07.json"
+ $.entries[34].uri: "archiveQuests/Tome10.json"
- $.entries[35].contentVersion: "cec3f3b0e26a21e6eaad75dabccba2bd483a1556"
+ $.entries[35].contentVersion: "2c75df4a6364501da8cc736ace271acad3806fa8"
- $.entries[35].uri: "archiveQuests/Tome08.json"
+ $.entries[35].uri: "archiveQuests/Tome11.json"
- $.entries[36].contentVersion: "45e975478e5e97f8d13c231060cfee9de7052616"
+ $.entries[36].contentVersion: "7720fbc3ea7ebe343d23d5b08c0db0b310c77cf0"
- $.entries[36].uri: "archiveQuests/Tome09.json"
+ $.entries[36].uri: "archiveQuests/Tome12.json"
- $.entries[37].contentVersion: "a6dd6c1d027b29b9e6ca9fce7fa2751958db6053"
+ $.entries[37].contentVersion: "c6855eb665035513aaae3418054ef2de203c002d"
- $.entries[37].uri: "archiveQuests/Tome10.json"
+ $.entries[37].uri: "archiveQuests/Tome13.json"
- $.entries[38].contentVersion: "ac75f438a3bf314fd8923cbd3ec1636afa75fd89"
+ $.entries[38].contentVersion: "d1d8a99c35dc35ad58872df934ffac0c75437bd0"
- $.entries[38].uri: "archiveQuests/Tome11.json"
+ $.entries[38].uri: "archiveQuests/Tome14.json"
- $.entries[39].contentVersion: "063cf9749f0f408dcc236ee18ba3e926ebe3d592"
+ $.entries[39].contentVersion: "285100a3c684cad9445f9655dd0fb42c0e3bb42c"
- $.entries[39].uri: "archiveQuests/Tome12.json"
+ $.entries[39].uri: "archiveQuests/Tome15.json"
- $.entries[40].contentVersion: "511d9d66a894954ff759363cf86c39c7fa21ea47"
+ $.entries[40].contentVersion: "d74fa08fecca7edda0cb8c8a05da244b15a47b7a"
- $.entries[40].uri: "archiveQuests/Tome13.json"
+ $.entries[40].uri: "archiveQuests/Tome16.json"
- $.entries[41].contentVersion: "a9290b0c2609b7e269b1f742fc698b139cab21bd"
+ $.entries[41].contentVersion: "056013c7e688e685e0c10253d899f58345b823d3"
- $.entries[41].uri: "archiveQuests/Tome14.json"
+ $.entries[41].uri: "archiveQuests/Tome17.json"
- $.entries[42].contentVersion: "9e232a0277e63165da4d6c3ce0464c095dd15a48"
+ $.entries[42].contentVersion: "340f607da38694cf0ecfbc72cc0a2d7c8659e787"
- $.entries[42].uri: "archiveQuests/Tome15.json"
+ $.entries[42].uri: "archiveQuests/Tome18.json"
- $.entries[43].contentVersion: "ae39392102e421d679f9222cf7573fb01dea06e5"
+ $.entries[43].contentVersion: "630ce32e86268a45cd2bfafbc251e76d4d1eb1d7"
… 745 more change(s) — see the commit diff for everything
```

### [`emblemTunable.json`](emblemTunable.json)

[Full line-by-line diff](diffs/emblemTunable.json.diff)

```diff
+ $.emblemValues[id=Survivor_Lightbringer_PointsPerTotemBlessed]
+ $.emblemValues[id=Survivor_Lightbringer_MaxPointsPerTotemBlessed]
+ $.emblemValues[id=Survivor_Lightbringer_PointsPerPlayerBlessingTotemWhileChased]
+ $.emblemValues[id=Survivor_Lightbringer_MaxPointsPerPlayerBlessingWhileChased]
+ $.emblemValues[id=Survivor_Lightbringer_PointsPerInvocationPercentage]
+ $.emblemValues[id=Survivor_Lightbringer_MaxPointsPerInvocationPercentage]
+ $.emblemValues[id=Survivor_Lightbringer_PointsPerInvocationPercentagedWhileChased]
+ $.emblemValues[id=Survivor_Lightbringer_MaxPointsPerInvocationPercentageWhileChased]
- $.emblemValues[id=Survivor_Lightbringer_PointsPerDullTotemCleansedWhileChased].value: 5.0
+ $.emblemValues[id=Survivor_Lightbringer_PointsPerDullTotemCleansedWhileChased].value: 10.0
- $.emblemValues[id=Survivor_Lightbringer_PointsPerHexTotemCleansedWhileChased].value: 10.0
+ $.emblemValues[id=Survivor_Lightbringer_PointsPerHexTotemCleansedWhileChased].value: 25.0
```

### [`freetoplay/EU/event.json`](freetoplay/EU/event.json)

[Full line-by-line diff](diffs/freetoplay/EU/event.json.diff)

```diff
- $.event.end: "2025-04-07T15:00:00"
+ $.event.end: "2025-06-23T15:00:00"
- $.event.start: "2025-04-03T15:00:00"
+ $.event.start: "2025-06-19T15:00:00"
```

### [`freetoplay/NA/event.json`](freetoplay/NA/event.json)

[Full line-by-line diff](diffs/freetoplay/NA/event.json.diff)

```diff
- $.event.end: "2025-04-07T15:00:00"
+ $.event.end: "2025-06-23T15:00:00"
- $.event.start: "2025-04-03T15:00:00"
+ $.event.start: "2025-06-19T15:00:00"
```

### [`gameplayTunables.json`](gameplayTunables.json)

[Full line-by-line diff](diffs/gameplayTunables.json.diff)

```diff
+ $.data["f:/K40/Data/Game/K40_TunableValue.K40_TunableValue:distancethresholdforgeneratornearsecuritydoors"]: 1600.0
+ $.data["f:/K40/Data/Game/K40_TunableValue.K40_TunableValue:terrorradius"]: 2400.0
```

### [`loadingText/specialEventsLoadingText_de.json`](loadingText/specialEventsLoadingText_de.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_de.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_en.json`](loadingText/specialEventsLoadingText_en.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_en.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_es-MX.json`](loadingText/specialEventsLoadingText_es-MX.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_es-MX.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_es.json`](loadingText/specialEventsLoadingText_es.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_es.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_fr.json`](loadingText/specialEventsLoadingText_fr.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_fr.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_it.json`](loadingText/specialEventsLoadingText_it.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_it.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_ja.json`](loadingText/specialEventsLoadingText_ja.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_ja.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_ko.json`](loadingText/specialEventsLoadingText_ko.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_ko.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_pl.json`](loadingText/specialEventsLoadingText_pl.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_pl.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_pt-BR.json`](loadingText/specialEventsLoadingText_pt-BR.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_pt-BR.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_ru.json`](loadingText/specialEventsLoadingText_ru.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_ru.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_th.json`](loadingText/specialEventsLoadingText_th.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_th.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_tr.json`](loadingText/specialEventsLoadingText_tr.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_tr.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_zh-Hans.json`](loadingText/specialEventsLoadingText_zh-Hans.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_zh-Hans.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`loadingText/specialEventsLoadingText_zh-Hant.json`](loadingText/specialEventsLoadingText_zh-Hant.json)

[Full line-by-line diff](diffs/loadingText/specialEventsLoadingText_zh-Hant.json.diff)

```diff
- $.loadingText[id=Anniversary2024_001]
- $.loadingText[id=Anniversary2024_002]
- $.loadingText[id=Anniversary2024_003]
- $.loadingText[id=Anniversary2024_004]
- $.loadingText[id=Anniversary2024_005]
- $.loadingText[id=Anniversary2024_006]
- $.loadingText[id=Anniversary2024_007]
- $.loadingText[id=Anniversary2024_008]
- $.loadingText[id=Anniversary2024_010]
- $.loadingText[id=Anniversary2024_011]
- $.loadingText[id=Anniversary2024_012]
- $.loadingText[id=Anniversary2024_013]
- $.loadingText[id=Anniversary2024_014]
- $.loadingText[id=Anniversary2024_016]
- $.loadingText[id=Anniversary2024_017]
- $.loadingText[id=Anniversary2024_018]
- $.loadingText[id=Anniversary2024_019]
- $.loadingText[id=Anniversary2024_020]
- $.loadingText[id=Anniversary2024_022]
- $.loadingText[id=Anniversary2024_023]
- $.loadingText[id=Anniversary2024_024]
- $.loadingText[id=Anniversary2024_025]
- $.loadingText[id=Anniversary2024_027]
- $.loadingText[id=Anniversary2024_028]
- $.loadingText[id=Anniversary2024_029]
- $.loadingText[id=Anniversary2024_030]
- $.loadingText[id=Anniversary2024_031]
- $.loadingText[id=Anniversary2024_033]
- $.loadingText[id=Anniversary2024_034]
- $.loadingText[id=Anniversary2024_035]
- $.loadingText[id=Anniversary2024_036]
- $.loadingText[id=Anniversary2024_037]
- $.loadingText[id=Anniversary2024_039]
- $.loadingText[id=Anniversary2024_040]
- $.loadingText[id=Anniversary2024_041]
- $.loadingText[id=Anniversary2024_042]
- $.loadingText[id=Anniversary2024_043]
- $.loadingText[id=Anniversary2024_044]
- $.loadingText[id=Anniversary2024_045]
- $.loadingText[id=Anniversary2024_046]
- $.loadingText[id=Anniversary2024_047]
- $.loadingText[id=Anniversary2024_048]
- $.loadingText[id=Anniversary2024_049]
- $.loadingText[id=Anniversary2024_050]
- $.loadingText[id=Anniversary2024_051]
- $.loadingText[id=Anniversary2024_052]
- $.loadingText[id=Anniversary2024_053]
- $.loadingText[id=Anniversary2024_054]
- $.loadingText[id=Anniversary2024_055]
- $.loadingText[id=Anniversary2024_056]
- $.loadingText[id=Anniversary2024_057]
- $.loadingText[id=Anniversary2024_058]
- $.loadingText[id=Anniversary2024_059]
- $.loadingText[id=Anniversary2024_060]
- $.loadingText[id=Anniversary2024_061]
- $.loadingText[id=Anniversary2024_062]
- $.loadingText[id=Anniversary2024_063]
- $.loadingText[id=Anniversary2024_064]
- $.loadingText[id=Anniversary2024_065]
- $.loadingText[id=Anniversary2024_066]
- $.loadingText[id=Anniversary2024_067]
- $.loadingText[id=Anniversary2024_068]
- $.loadingText[id=Anniversary2024_069]
- $.loadingText[id=Anniversary2024_070]
- $.loadingText[id=Anniversary2024_071]
- $.loadingText[id=Anniversary2024_072]
- $.loadingText[id=Anniversary2024_073]
- $.loadingText[id=Anniversary2024_074]
- $.loadingText[id=Anniversary2024_075]
- $.loadingText[id=Anniversary2024_076]
- $.loadingText[id=Anniversary2024_077]
- $.loadingText[id=Anniversary2024_078]
- $.loadingText[id=Anniversary2024_079]
- $.loadingText[id=Anniversary2024_080]
- $.loadingText[id=Anniversary2024_081]
- $.loadingText[id=Anniversary2024_082]
- $.loadingText[id=Anniversary2024_083]
- $.loadingText[id=Anniversary2024_084]
- $.loadingText[id=Anniversary2024_085]
- $.loadingText[id=Anniversary2024_086]
- $.loadingText[id=Anniversary2024_087]
- $.loadingText[id=Anniversary2024_088]
- $.loadingText[id=Anniversary2024_089]
- $.loadingText[id=Anniversary2024_090]
- $.loadingText[id=Anniversary2024_091]
- $.loadingText[id=Anniversary2024_092]
- $.loadingText[id=Anniversary2024_093]
- $.loadingText[id=Anniversary2024_094]
- $.loadingText[id=Anniversary2024_095]
- $.loadingText[id=Anniversary2024_096]
- $.loadingText[id=Anniversary2024_097]
- $.loadingText[id=Anniversary2024_098]
- $.loadingText[id=Anniversary2024_099]
- $.loadingText[id=Anniversary2024_100]
- $.loadingText[id=Anniversary2024_101]
- $.loadingText[id=Anniversary2024_102]
- $.loadingText[id=Anniversary2024_103]
- $.loadingText[id=Anniversary2024_104]
- $.loadingText[id=Anniversary2024_105]
- $.loadingText[id=Anniversary2024_106]
- $.loadingText[id=Anniversary2024_109]
- $.loadingText[id=Anniversary2024_110]
- $.loadingText[id=Anniversary2024_111]
- $.loadingText[id=Anniversary2024_112]
- $.loadingText[id=Anniversary2024_113]
- $.loadingText[id=Anniversary2024_114]
- $.loadingText[id=Anniversary2024_115]
- $.loadingText[id=Anniversary2024_116]
- $.loadingText[id=Anniversary2024_117]
- $.loadingText[id=Anniversary2024_118]
- $.loadingText[id=Anniversary2024_119]
- $.loadingText[id=Anniversary2024_120]
- $.loadingText[id=Anniversary2024_121]
- $.loadingText[id=Anniversary2024_122]
- $.loadingText[id=Anniversary2024_123]
- $.loadingText[id=Anniversary2024_124]
- $.loadingText[id=Anniversary2024_125]
- $.loadingText[id=Anniversary2024_126]
- $.loadingText[id=Anniversary2024_127]
- $.loadingText[id=Anniversary2024_128]
- $.loadingText[id=Anniversary2024_129]
- $.loadingText[id=Anniversary2024_130]
- $.loadingText[id=Anniversary2024_131]
- $.loadingText[id=Anniversary2024_132]
- $.loadingText[id=Anniversary2024_133]
- $.loadingText[id=Anniversary2024_134]
- $.loadingText[id=Anniversary2024_135]
- $.loadingText[id=Anniversary2024_136]
- $.loadingText[id=Anniversary2024_137]
- $.loadingText[id=Anniversary2024_138]
- $.loadingText[id=Anniversary2024_139]
- $.loadingText[id=Anniversary2024_140]
- $.loadingText[id=Anniversary2024_141]
- $.loadingText[id=Anniversary2024_142]
- $.loadingText[id=Anniversary2024_143]
- $.loadingText[id=Anniversary2024_145]
- $.loadingText[id=Anniversary2024_146]
- $.loadingText[id=Anniversary2024_147]
- $.loadingText[id=Anniversary2024_148]
- $.loadingText[id=Anniversary2024_149]
- $.loadingText[id=Anniversary2024_150]
- $.loadingText[id=Anniversary2024_151]
- $.loadingText[id=Anniversary2024_152]
- $.loadingText[id=Anniversary2024_153]
- $.loadingText[id=Anniversary2024_154]
- $.loadingText[id=Anniversary2024_155]
- $.loadingText[id=Anniversary2024_156]
- $.loadingText[id=Anniversary2024_157]
- $.loadingText[id=Anniversary2024_158]
- $.loadingText[id=Anniversary2024_159]
- $.loadingText[id=Anniversary2024_160]
- $.loadingText[id=Anniversary2024_161]
- $.loadingText[id=Anniversary2024_162]
- $.loadingText[id=Anniversary2024_163]
- $.loadingText[id=Anniversary2024_164]
- $.loadingText[id=Anniversary2024_165]
- $.loadingText[id=Anniversary2024_166]
- $.loadingText[id=Anniversary2024_167]
- $.loadingText[id=Anniversary2024_168]
- $.loadingText[id=Anniversary2024_169]
- $.loadingText[id=Anniversary2024_170]
- $.loadingText[id=Anniversary2024_171]
- $.loadingText[id=Anniversary2024_172]
- $.loadingText[id=Anniversary2024_173]
- $.loadingText[id=Anniversary2024_174]
- $.loadingText[id=Anniversary2024_175]
- $.loadingText[id=Anniversary2024_176]
- $.loadingText[id=Anniversary2024_177]
- $.loadingText[id=Anniversary2024_178]
- $.loadingText[id=Anniversary2024_179]
- $.loadingText[id=Anniversary2024_180]
- $.loadingText[id=Anniversary2024_181]
- $.loadingText[id=Anniversary2024_182]
- $.loadingText[id=Anniversary2024_183]
- $.loadingText[id=Anniversary2024_184]
- $.loadingText[id=Anniversary2024_185]
- $.loadingText[id=Anniversary2024_186]
- $.loadingText[id=Anniversary2024_187]
- $.loadingText[id=Anniversary2024_188]
- $.loadingText[id=Anniversary2024_189]
- $.loadingText[id=Anniversary2024_190]
- $.loadingText[id=Anniversary2024_191]
- $.loadingText[id=Anniversary2024_192]
- $.loadingText[id=Anniversary2024_193]
- $.loadingText[id=Anniversary2024_194]
- $.loadingText[id=Anniversary2024_195]
- $.loadingText[id=Anniversary2024_197]
- $.loadingText[id=Anniversary2024_198]
- $.loadingText[id=Anniversary2024_199]
- $.loadingText[id=Anniversary2024_201]
- $.loadingText[id=Anniversary2024_202]
- $.loadingText[id=Anniversary2024_203]
- $.loadingText[id=Anniversary2024_204]
- $.loadingText[id=Anniversary2024_205]
- $.loadingText[id=Anniversary2024_206]
- $.loadingText[id=Anniversary2024_207]
- $.loadingText[id=Anniversary2024_208]
- $.loadingText[id=Anniversary2024_209]
- $.loadingText[id=Anniversary2024_210]
- $.loadingText[id=Anniversary2024_211]
… 221 more change(s) — see the commit diff for everything
```

### [`prestige/prestige.json`](prestige/prestige.json)

[Full line-by-line diff](diffs/prestige/prestige.json.diff)

```diff
+ $.rewards.K40
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Jerky_W7]
+ $.featuredCard[id=KetchupW1]
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].associatedDlcId: "Jerky"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].associatedDlcId: "Ketchup"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_SteadyPulse.T_UI_ChapterBundle_SteadyPulse"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_FiveNightsAtFreddys.T_UI_ChapterBundle_FiveNightsAtFreddys"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].associatedDlcId: "Icecream"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].associatedDlcId: "Jerky"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TokyoGhoul.T_UI_ChapterBundle_TokyoGhoul"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_SteadyPulse.T_UI_ChapterBundle_SteadyPulse"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].associatedDlcId: "Gelato"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].associatedDlcId: "Icecream"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DoomedCourse.T_UI_ChapterBundle_DoomedCourse"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TokyoGhoul.T_UI_ChapterBundle_TokyoGhoul"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].associatedDlcId: "Eclair"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].associatedDlcId: "Gelato"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Castlevania.T_UI_ChapterBundle_Castlevania"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DoomedCourse.T_UI_ChapterBundle_DoomedCourse"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].associatedDlcId: "Donut"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].associatedDlcId: "Eclair"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TombRaider.T_UI_ChapterBundle_TombRaider"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Castlevania.T_UI_ChapterBundle_Castlevania"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].associatedDlcId: "Churros"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].associatedDlcId: "Donut"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DungeonsAndDragons.T_UI_ChapterBundle_DungeonsAndDragons"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TombRaider.T_UI_ChapterBundle_TombRaider"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].associatedDlcId: "ApplePie"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].associatedDlcId: "Churros"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllThingsWicked.T_UI_ChapterBundle_AllThingsWicked"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DungeonsAndDragons.T_UI_ChapterBundle_DungeonsAndDragons"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].associatedDlcId: "Zodiac"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].associatedDlcId: "ApplePie"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AlanWake.T_UI_ChapterBundle_AlanWake"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllThingsWicked.T_UI_ChapterBundle_AllThingsWicked"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].associatedDlcId: "Yerkes"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].associatedDlcId: "Zodiac"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Chucky.T_UI_ChapterBundle_Chucky"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AlanWake.T_UI_ChapterBundle_AlanWake"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].associatedDlcId: "Wormhole"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].associatedDlcId: "Yerkes"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Alien.T_UI_ChapterBundle_Alien"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Chucky.T_UI_ChapterBundle_Chucky"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].associatedDlcId: "Venus"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].associatedDlcId: "Wormhole"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_NicolasCage.T_UI_ChapterBundle_NicolasCage"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Alien.T_UI_ChapterBundle_Alien"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[11].associatedDlcId: "Umbra"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[11].associatedDlcId: "Venus"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[11].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_EndTransmission.T_UI_ChapterBundle_EndTransmission"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[11].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_NicolasCage.T_UI_ChapterBundle_NicolasCage"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[12]
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "45"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "268435495"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Ketchup/K40_TheAnimatronic_Portrait.K40_TheAnimatronic_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "268435494"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "45"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "268435493"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "268435494"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "44"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "268435493"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "268435492"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "44"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "43"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "268435492"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/S44_TrevorBelmont_Portrait.S44_TrevorBelmont_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[6]
- $.featuredCustomizationRecommendations[id=JerkyW6]
+ $.featuredCustomizationRecommendations[id=Ketchup_W1]
- $.featuredCustomizationRecommendations[id=JerkyW5].activeTo: "2025-06-10T15:00:00"
+ $.featuredCustomizationRecommendations[id=JerkyW5].activeTo: "2025-06-17T15:00:00"
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S39_outfit_011]
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S38_outfit_007]
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=K35_outfit_007]
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S34_outfit_023].weight: 40
+ $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S34_outfit_023].weight: 10
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=K26_outfit_020].weight: 39
+ $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=K26_outfit_020].weight: 9
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S41_outfit_017].weight: 38
+ $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S41_outfit_017].weight: 8
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S28_outfit_030].weight: 37
+ $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=S28_outfit_030].weight: 7
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=GS_outfit_037].weight: 36
+ $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=GS_outfit_037].weight: 6
- $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=K30_outfit_018].weight: 35
+ $.featuredCustomizationRecommendations[id=JerkyW5].recommendations[id=K30_outfit_018].weight: 5
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
+ $.specialEvents[50]
+ $.specialEvents[51]
+ $.specialEvents[52]
+ $.specialEventsData[3].lteData
- $.specialEventsData[3].eventId: "Barrel2023"
+ $.specialEventsData[3].eventId: "Anniversary2025"
- $.specialEventsData[3].eventPeriods[id=Barrel2023EventPeriod1]
- $.specialEventsData[3].eventPeriods[id=Barrel2023EventPeriod2]
- $.specialEventsData[3].eventPeriods[id=Barrel2023EventPeriod3]
- $.specialEventsData[3].miscRewards[id=BarrelCharm1]
- $.specialEventsData[3].miscRewards[id=BarrelCharm2]
- $.specialEventsData[3].miscRewards[id=BarrelCharm3]
- $.specialEventsData[4].lteData
- $.specialEventsData[4].eventId: "CakeApplepie"
+ $.specialEventsData[4].eventId: "Barrel2023"
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod1]
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod2]
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod3]
- $.specialEventsData[4].miscRewards[id=playReward]
+ $.specialEventsData[4].miscRewards[id=BarrelCharm1]
+ $.specialEventsData[4].miscRewards[id=BarrelCharm2]
+ $.specialEventsData[4].miscRewards[id=BarrelCharm3]
- $.specialEventsData[5].eventId: "CalamariV1"
+ $.specialEventsData[5].eventId: "CakeApplepie"
- $.specialEventsData[5].lteData.gameModeQueue: "Calamari"
+ $.specialEventsData[5].lteData.gameModeQueue: "CakeQueue"
- $.specialEventsData[5].lteData.gameType: "Calamari"
+ $.specialEventsData[5].lteData.gameType: "Cake"
+ $.specialEventsData[5].miscRewards[id=playReward]
- $.specialEventsData[6].eventId: "CalamariV2"
+ $.specialEventsData[6].eventId: "CalamariV1"
- $.specialEventsData[7].eventId: "CalamariV3"
+ $.specialEventsData[7].eventId: "CalamariV2"
- $.specialEventsData[8].eventId: "CalamariV4"
+ $.specialEventsData[8].eventId: "CalamariV3"
- $.specialEventsData[9].eventId: "ChocolateBoxEclair"
+ $.specialEventsData[9].eventId: "CalamariV4"
- $.specialEventsData[9].lteData.affectsMMR: true
+ $.specialEventsData[9].lteData.affectsMMR: false
- $.specialEventsData[9].lteData.gameModeQueue: "ChocolateBox"
+ $.specialEventsData[9].lteData.gameModeQueue: "Calamari"
- $.specialEventsData[9].lteData.gameType: "ChocolateBox"
+ $.specialEventsData[9].lteData.gameType: "Calamari"
- $.specialEventsData[10].eventId: "ChocolateBoxGelato"
+ $.specialEventsData[10].eventId: "ChocolateBoxEclair"
- $.specialEventsData[11].eventId: "ChocolateBoxHotdog"
+ $.specialEventsData[11].eventId: "ChocolateBoxGelato"
- $.specialEventsData[12].eventId: "ChocolateBoxIcecream"
+ $.specialEventsData[12].eventId: "ChocolateBoxHotdog"
- $.specialEventsData[13].eventId: "ChocolateBoxJerky"
+ $.specialEventsData[13].eventId: "ChocolateBoxIcecream"
- $.specialEventsData[14].eventId: "ChocolateBoxV1"
+ $.specialEventsData[14].eventId: "ChocolateBoxJerky"
- $.specialEventsData[15].eventId: "DreadByDaylightZodiac"
+ $.specialEventsData[15].eventId: "ChocolateBoxV1"
- $.specialEventsData[15].lteData.affectsMMR: false
+ $.specialEventsData[15].lteData.affectsMMR: true
- $.specialEventsData[15].lteData.gameModeQueue: "DreadByDaylight"
+ $.specialEventsData[15].lteData.gameModeQueue: "ChocolateBox"
- $.specialEventsData[15].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[15].lteData.gameType: "ChocolateBox"
- $.specialEventsData[16].eventId: "FireflyV1"
+ $.specialEventsData[16].eventId: "DreadByDaylightZodiac"
- $.specialEventsData[16].lteData.gameModeQueue: "Firefly"
+ $.specialEventsData[16].lteData.gameModeQueue: "DreadByDaylight"
- $.specialEventsData[16].lteData.gameType: "Firefly"
+ $.specialEventsData[16].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[17].lteData
- $.specialEventsData[17].eventId: "Halloween2022"
+ $.specialEventsData[17].eventId: "FireflyV1"
- $.specialEventsData[17].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[18].eventId: "Halloween2023"
+ $.specialEventsData[18].eventId: "Halloween2022"
- $.specialEventsData[18].milestoneRewards[0]
- $.specialEventsData[18].milestoneRewards[1]
- $.specialEventsData[18].milestoneRewards[2]
+ $.specialEventsData[18].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[19].lteData
- $.specialEventsData[19].eventId: "Halloween2024"
+ $.specialEventsData[19].eventId: "Halloween2023"
- $.specialEventsData[19].eventPeriods[id=Halloween2024]
- $.specialEventsData[19].milestoneRewards[0].rewards[id=FU_012]
+ $.specialEventsData[19].milestoneRewards[0].rewards[id=XR_037]
- $.specialEventsData[19].milestoneRewards[1].rewards[id=FU_BDG_18]
+ $.specialEventsData[19].milestoneRewards[1].rewards[id=MT_Head027]
- $.specialEventsData[19].milestoneRewards[2].pointsCost: 20
+ $.specialEventsData[19].milestoneRewards[2].pointsCost: 21
- $.specialEventsData[19].milestoneRewards[2].rewards[id=FU_BNR_12]
+ $.specialEventsData[19].milestoneRewards[2].rewards[id=K30_Head011]
+ $.specialEventsData[20].lteData
- $.specialEventsData[20].eventId: "Lunar2022"
+ $.specialEventsData[20].eventId: "Halloween2024"
+ $.specialEventsData[20].eventPeriods[id=Halloween2024]
+ $.specialEventsData[20].milestoneRewards[0]
+ $.specialEventsData[20].milestoneRewards[1]
+ $.specialEventsData[20].milestoneRewards[2]
- $.specialEventsData[20].miscRewards[id=killerStaticReward]
- $.specialEventsData[20].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[20].scoreEventRewards[0]
- $.specialEventsData[20].scoreEventRewards[1]
- $.specialEventsData[20].scoreEventRewards[2]
- $.specialEventsData[20].scoreEventRewards[3]
- $.specialEventsData[20].scoreEventRewards[4]
- $.specialEventsData[20].scoreEventRewards[5]
- $.specialEventsData[20].scoreEventRewards[6]
- $.specialEventsData[20].scoreEventRewards[7]
- $.specialEventsData[21].eventId: "Lunar2023"
+ $.specialEventsData[21].eventId: "Lunar2022"
- $.specialEventsData[21].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 5000
+ $.specialEventsData[21].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 4000
- $.specialEventsData[21].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[21].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[21].scoreEventRewards[2].weight: 15
+ $.specialEventsData[21].scoreEventRewards[2].weight: 20
- $.specialEventsData[21].scoreEventRewards[3].weight: 25
+ $.specialEventsData[21].scoreEventRewards[3].weight: 20
- $.specialEventsData[21].scoreEventRewards[5].weight: 20
+ $.specialEventsData[21].scoreEventRewards[5].weight: 15
- $.specialEventsData[21].scoreEventRewards[6].weight: 10
+ $.specialEventsData[21].scoreEventRewards[6].weight: 8
- $.specialEventsData[21].scoreEventRewards[7].weight: 5
+ $.specialEventsData[21].scoreEventRewards[7].weight: 2
- $.specialEventsData[22].eventId: "Spring2024"
+ $.specialEventsData[22].eventId: "Lunar2023"
- $.specialEventsData[22].eventTrackerObjectives[id=main]
+ $.specialEventsData[22].miscRewards[id=killerStaticReward]
+ $.specialEventsData[22].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[22].scoreEventRewards[0]
+ $.specialEventsData[22].scoreEventRewards[1]
+ $.specialEventsData[22].scoreEventRewards[2]
+ $.specialEventsData[22].scoreEventRewards[3]
+ $.specialEventsData[22].scoreEventRewards[4]
+ $.specialEventsData[22].scoreEventRewards[5]
+ $.specialEventsData[22].scoreEventRewards[6]
+ $.specialEventsData[22].scoreEventRewards[7]
- $.specialEventsData[23].eventId: "Spring2025"
+ $.specialEventsData[23].eventId: "MapShowcaseKetchup"
- $.specialEventsData[23].eventTrackerObjectives[id=main]
- $.specialEventsData[23].lteData.gameModeQueue: "Spring2025"
+ $.specialEventsData[23].lteData.gameModeQueue: "MapShowcase"
- $.specialEventsData[23].lteData.gameType: "SeasonalEvent_FuelGenerator"
+ $.specialEventsData[23].lteData.gameType: "MapShowcase"
- $.specialEventsData[23].milestoneRewards[0]
- $.specialEventsData[23].milestoneRewards[1]
- $.specialEventsData[23].milestoneRewards[2]
- $.specialEventsData[24].eventId: "Winter2023"
+ $.specialEventsData[24].eventId: "Spring2024"
+ $.specialEventsData[24].eventTrackerObjectives[id=main]
- $.specialEventsData[24].milestoneRewards[0]
- $.specialEventsData[24].milestoneRewards[1]
- $.specialEventsData[24].milestoneRewards[2]
- $.specialEventsData[24].milestoneRewards[3]
- $.specialEventsData[24].milestoneRewards[4]
- $.specialEventsData[25].eventId: "Winter2024"
+ $.specialEventsData[25].eventId: "Spring2025"
- $.specialEventsData[25].eventPeriods[id=Winter2024]
+ $.specialEventsData[25].eventTrackerObjectives[id=main]
- $.specialEventsData[25].lteData.gameModeQueue: "Winter2024"
+ $.specialEventsData[25].lteData.gameModeQueue: "Spring2025"
- $.specialEventsData[25].lteData.gameType: "SeasonalEvent"
+ $.specialEventsData[25].lteData.gameType: "SeasonalEvent_FuelGenerator"
- $.specialEventsData[25].lteData.incentiveBonus: 100.0
+ $.specialEventsData[25].lteData.incentiveBonus: 0.0
- $.specialEventsData[25].milestoneRewards[0].pointsCost: 6
+ $.specialEventsData[25].milestoneRewards[0].pointsCost: 3
- $.specialEventsData[25].milestoneRewards[0].rewards[id=GEL_001]
+ $.specialEventsData[25].milestoneRewards[0].rewards[id=IC_001]
- $.specialEventsData[25].milestoneRewards[1].pointsCost: 12
+ $.specialEventsData[25].milestoneRewards[1].pointsCost: 8
- $.specialEventsData[25].milestoneRewards[1].rewards[id=GE_BDG_08]
+ $.specialEventsData[25].milestoneRewards[1].rewards[id=IC_BDG_03]
- $.specialEventsData[25].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[25].milestoneRewards[2].pointsCost: 15
- $.specialEventsData[25].milestoneRewards[2].rewards[id=GE_BNR_07]
+ $.specialEventsData[25].milestoneRewards[2].rewards[id=IC_BNR_03]
+ $.specialEventsData[26]
+ $.specialEventsData[27]
```

## Could not download

- `images/T_UI_ChapterBundle_FiveNightsAtFreddys.png (HTTP 404)`
- `images/T_UI_CollectionBanner_FNAF.png (HTTP 404)`
- `images/T_UI_SpecialPack_FNAF.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherBundle.png (HTTP 404)`
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

