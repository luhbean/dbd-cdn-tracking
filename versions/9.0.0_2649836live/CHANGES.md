# live · 9.0.0_2649836live

| | |
|---|---|
| Build date | 2025-08-04 13:52 UTC |
| CDN version | `9.0.0_2649836live-1754315559` |
| Key | `9.0.0_live` |
| Compared with | [9.1.0_2660852live](../9.1.0_2660852live/CHANGES.md) (2025-08-01 14:07 UTC) |

## Summary

**0** added · **38** modified · **2** removed · 164 unchanged

## Removed files

- `images/T_UI_SpecialPack_Rift2.png`
- `images/T_UI_SpecialPack_TombRaider_2.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.enableEncryption: true
- $.analyticsRules.KAL[]: "SpectatingAnalytics"
- $.krakenSdkValidation.enabled: false
+ $.krakenSdkValidation.enabled: true
- $.krakenSdkValidation.useWhitelist: false
+ $.krakenSdkValidation.useWhitelist: true
- $.online.hiddenProgressiveQueueDelays[]: 0.0
- $.online.hiddenProgressiveQueueDelays[]: 1.0
+ $.online.hiddenProgressiveQueueDelays[]: 0
+ $.online.hiddenProgressiveQueueDelays[]: 10
+ $.online.hiddenProgressiveQueueDelays[]: 20
+ $.online.hiddenProgressiveQueueDelays[]: 40
+ $.online.hiddenProgressiveQueueDelays[]: 60
- $.online.hiddenQueueDelayResetThreshold: 1.0
+ $.online.hiddenQueueDelayResetThreshold: 300
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
- $.disconnectionPenalty.ReasonsWhichSendAnalyticsWhenDisabled
```

### [`archiveQuests/Tome02.json`](archiveQuests/Tome02.json)

[Full line-by-line diff](diffs/archiveQuests/Tome02.json.diff)

```diff
- $.Tome02.level[1].nodes.node_L2_05.clientInfoId: "ConsumeMedkit"
+ $.Tome02.level[1].nodes.node_L2_05.clientInfoId: "AddItemToMap"
- $.Tome02.level[1].nodes.node_L2_05.objectives.ConsumeMedkit
+ $.Tome02.level[1].nodes.node_L2_05.objectives.AddItemToMap
```

### [`archiveQuests/Tome07.json`](archiveQuests/Tome07.json)

[Full line-by-line diff](diffs/archiveQuests/Tome07.json.diff)

```diff
- $.Tome07.level[3].nodes.node_T7L4_02.coordinates.y: 23.07692308
+ $.Tome07.level[3].nodes.node_T7L4_02.coordinates.y: 23.076923076923077
- $.Tome07.level[3].nodes.node_T7L4_03.coordinates.x: 73.33333333
+ $.Tome07.level[3].nodes.node_T7L4_03.coordinates.x: 73.33333333333333
- $.Tome07.level[3].nodes.node_T7L4_04.coordinates.x: 53.33333333
+ $.Tome07.level[3].nodes.node_T7L4_04.coordinates.x: 53.333333333333336
- $.Tome07.level[3].nodes.node_T7L4_05.coordinates.x: 33.33333333
+ $.Tome07.level[3].nodes.node_T7L4_05.coordinates.x: 33.333333333333336
- $.Tome07.level[3].nodes.node_T7L4_05.coordinates.y: 23.07692308
+ $.Tome07.level[3].nodes.node_T7L4_05.coordinates.y: 23.076923076923077
- $.Tome07.level[3].nodes.node_T7L4_06.coordinates.y: 46.15384615
+ $.Tome07.level[3].nodes.node_T7L4_06.coordinates.y: 46.15384615384615
- $.Tome07.level[3].nodes.node_T7L4_07.coordinates.x: 13.33333333
+ $.Tome07.level[3].nodes.node_T7L4_07.coordinates.x: 13.333333333333334
- $.Tome07.level[3].nodes.node_T7L4_07.coordinates.y: 46.15384615
+ $.Tome07.level[3].nodes.node_T7L4_07.coordinates.y: 46.15384615384615
- $.Tome07.level[3].nodes.node_T7L4_08.coordinates.x: 66.66666667
+ $.Tome07.level[3].nodes.node_T7L4_08.coordinates.x: 66.66666666666667
- $.Tome07.level[3].nodes.node_T7L4_08.coordinates.y: 46.15384615
+ $.Tome07.level[3].nodes.node_T7L4_08.coordinates.y: 46.15384615384615
- $.Tome07.level[3].nodes.node_T7L4_08.objectives.EscapeWithItemUltraRare.questEvent[0].parameters: "instigator:me;itemRarity:VeryRare"
+ $.Tome07.level[3].nodes.node_T7L4_08.objectives.EscapeWithItemUltraRare.questEvent[0].parameters: "instigator:me;itemRarity:UltraRare"
- $.Tome07.level[3].nodes.node_T7L4_09.coordinates.x: 86.66666667
+ $.Tome07.level[3].nodes.node_T7L4_09.coordinates.x: 86.66666666666667
- $.Tome07.level[3].nodes.node_T7L4_09.coordinates.y: 69.23076923
+ $.Tome07.level[3].nodes.node_T7L4_09.coordinates.y: 69.23076923076923
- $.Tome07.level[3].nodes.node_T7L4_10.coordinates.x: 53.33333333
+ $.Tome07.level[3].nodes.node_T7L4_10.coordinates.x: 53.333333333333336
- $.Tome07.level[3].nodes.node_T7L4_10.coordinates.y: 92.30769231
+ $.Tome07.level[3].nodes.node_T7L4_10.coordinates.y: 92.3076923076923
- $.Tome07.level[3].nodes.node_T7L4_11.coordinates.x: 6.666666667
+ $.Tome07.level[3].nodes.node_T7L4_11.coordinates.x: 6.666666666666667
- $.Tome07.level[3].nodes.node_T7L4_11.coordinates.y: 69.23076923
+ $.Tome07.level[3].nodes.node_T7L4_11.coordinates.y: 69.23076923076923
- $.Tome07.level[3].nodes.node_T7L4_12.coordinates.x: 33.33333333
+ $.Tome07.level[3].nodes.node_T7L4_12.coordinates.x: 33.333333333333336
- $.Tome07.level[3].nodes.node_T7L4_12.coordinates.y: 69.23076923
+ $.Tome07.level[3].nodes.node_T7L4_12.coordinates.y: 69.23076923076923
- $.Tome07.level[3].nodes.node_T7L4_13.coordinates.y: 69.23076923
+ $.Tome07.level[3].nodes.node_T7L4_13.coordinates.y: 69.23076923076923
- $.Tome07.level[3].nodes.node_T7L4_14.coordinates.y: 69.23076923
+ $.Tome07.level[3].nodes.node_T7L4_14.coordinates.y: 69.23076923076923
- $.Tome07.level[3].nodes.node_T7L4_15.coordinates.y: 46.15384615
+ $.Tome07.level[3].nodes.node_T7L4_15.coordinates.y: 46.15384615384615
- $.Tome07.level[3].nodes.node_T7L4_16.coordinates.x: 86.66666667
+ $.Tome07.level[3].nodes.node_T7L4_16.coordinates.x: 86.66666666666667
- $.Tome07.level[3].nodes.node_T7L4_17.coordinates.x: 66.66666667
+ $.Tome07.level[3].nodes.node_T7L4_17.coordinates.x: 66.66666666666667
- $.Tome07.level[3].nodes.node_T7L4_17.coordinates.y: 23.07692308
+ $.Tome07.level[3].nodes.node_T7L4_17.coordinates.y: 23.076923076923077
- $.Tome07.level[3].nodes.node_T7L4_18.coordinates.x: 46.66666667
+ $.Tome07.level[3].nodes.node_T7L4_18.coordinates.x: 46.666666666666664
- $.Tome07.level[3].nodes.node_T7L4_18.coordinates.y: 23.07692308
+ $.Tome07.level[3].nodes.node_T7L4_18.coordinates.y: 23.076923076923077
- $.Tome07.level[3].nodes.node_T7L4_19.coordinates.y: 92.30769231
+ $.Tome07.level[3].nodes.node_T7L4_19.coordinates.y: 92.3076923076923
- $.Tome07.level[3].nodes.node_T7L4_20.coordinates.x: 66.66666667
+ $.Tome07.level[3].nodes.node_T7L4_20.coordinates.x: 66.66666666666667
- $.Tome07.level[3].nodes.node_T7L4_20.coordinates.y: 92.30769231
+ $.Tome07.level[3].nodes.node_T7L4_20.coordinates.y: 92.3076923076923
- $.Tome07.level[3].nodes.node_T7L4_End01.coordinates.y: 46.15384615
+ $.Tome07.level[3].nodes.node_T7L4_End01.coordinates.y: 46.15384615384615
- $.Tome07.level[3].nodes.node_T7L4_End02.coordinates.y: 92.30769231
+ $.Tome07.level[3].nodes.node_T7L4_End02.coordinates.y: 92.3076923076923
- $.Tome07.level[3].nodes.node_T7L4_End03.coordinates.y: 23.07692308
+ $.Tome07.level[3].nodes.node_T7L4_End03.coordinates.y: 23.076923076923077
- $.Tome07.level[3].nodes.node_T7L4_Glyph01.coordinates.x: 53.33333333
+ $.Tome07.level[3].nodes.node_T7L4_Glyph01.coordinates.x: 53.333333333333336
- $.Tome07.level[3].nodes.node_T7L4_Glyph01.coordinates.y: 46.15384615
+ $.Tome07.level[3].nodes.node_T7L4_Glyph01.coordinates.y: 46.15384615384615
- $.Tome07.level[3].nodes.node_T7L4_Start01.coordinates.y: 46.15384615
+ $.Tome07.level[3].nodes.node_T7L4_Start01.coordinates.y: 46.15384615384615
```

### [`archiveQuests/Tome08.json`](archiveQuests/Tome08.json)

[Full line-by-line diff](diffs/archiveQuests/Tome08.json.diff)

```diff
- $.Tome08.level[3].nodes.node_T8L4_01.coordinates.y: 23.07692308
+ $.Tome08.level[3].nodes.node_T8L4_01.coordinates.y: 23.076923076923077
- $.Tome08.level[3].nodes.node_T8L4_02.coordinates.x: 6.666666667
+ $.Tome08.level[3].nodes.node_T8L4_02.coordinates.x: 6.666666666666667
- $.Tome08.level[3].nodes.node_T8L4_02.coordinates.y: 23.07692308
+ $.Tome08.level[3].nodes.node_T8L4_02.coordinates.y: 23.076923076923077
- $.Tome08.level[3].nodes.node_T8L4_03.coordinates.x: 26.66666667
+ $.Tome08.level[3].nodes.node_T8L4_03.coordinates.x: 26.666666666666668
- $.Tome08.level[3].nodes.node_T8L4_03.coordinates.y: 23.07692308
+ $.Tome08.level[3].nodes.node_T8L4_03.coordinates.y: 23.076923076923077
- $.Tome08.level[3].nodes.node_T8L4_04.coordinates.x: 66.66666667
+ $.Tome08.level[3].nodes.node_T8L4_04.coordinates.x: 66.66666666666667
- $.Tome08.level[3].nodes.node_T8L4_04.coordinates.y: 69.23076923
+ $.Tome08.level[3].nodes.node_T8L4_04.coordinates.y: 69.23076923076923
- $.Tome08.level[3].nodes.node_T8L4_05.coordinates.x: 46.66666667
+ $.Tome08.level[3].nodes.node_T8L4_05.coordinates.x: 46.666666666666664
- $.Tome08.level[3].nodes.node_T8L4_06.coordinates.x: 53.33333333
+ $.Tome08.level[3].nodes.node_T8L4_06.coordinates.x: 53.333333333333336
- $.Tome08.level[3].nodes.node_T8L4_06.coordinates.y: 23.07692308
+ $.Tome08.level[3].nodes.node_T8L4_06.coordinates.y: 23.076923076923077
- $.Tome08.level[3].nodes.node_T8L4_07.coordinates.y: 46.15384615
+ $.Tome08.level[3].nodes.node_T8L4_07.coordinates.y: 46.15384615384615
- $.Tome08.level[3].nodes.node_T8L4_08.coordinates.x: 33.33333333
+ $.Tome08.level[3].nodes.node_T8L4_08.coordinates.x: 33.333333333333336
- $.Tome08.level[3].nodes.node_T8L4_08.coordinates.y: 46.15384615
+ $.Tome08.level[3].nodes.node_T8L4_08.coordinates.y: 46.15384615384615
- $.Tome08.level[3].nodes.node_T8L4_09.coordinates.y: 46.15384615
+ $.Tome08.level[3].nodes.node_T8L4_09.coordinates.y: 46.15384615384615
- $.Tome08.level[3].nodes.node_T8L4_10.coordinates.y: 69.23076923
+ $.Tome08.level[3].nodes.node_T8L4_10.coordinates.y: 69.23076923076923
- $.Tome08.level[3].nodes.node_T8L4_11.coordinates.x: 86.66666667
+ $.Tome08.level[3].nodes.node_T8L4_11.coordinates.x: 86.66666666666667
- $.Tome08.level[3].nodes.node_T8L4_11.coordinates.y: 46.15384615
+ $.Tome08.level[3].nodes.node_T8L4_11.coordinates.y: 46.15384615384615
- $.Tome08.level[3].nodes.node_T8L4_12.coordinates.x: 53.33333333
+ $.Tome08.level[3].nodes.node_T8L4_12.coordinates.x: 53.333333333333336
- $.Tome08.level[3].nodes.node_T8L4_12.coordinates.y: 69.23076923
+ $.Tome08.level[3].nodes.node_T8L4_12.coordinates.y: 69.23076923076923
- $.Tome08.level[3].nodes.node_T8L4_13.coordinates.y: 69.23076923
+ $.Tome08.level[3].nodes.node_T8L4_13.coordinates.y: 69.23076923076923
- $.Tome08.level[3].nodes.node_T8L4_14.coordinates.x: 33.33333333
+ $.Tome08.level[3].nodes.node_T8L4_14.coordinates.x: 33.333333333333336
- $.Tome08.level[3].nodes.node_T8L4_14.coordinates.y: 92.30769231
+ $.Tome08.level[3].nodes.node_T8L4_14.coordinates.y: 92.3076923076923
- $.Tome08.level[3].nodes.node_T8L4_15.coordinates.y: 69.23076923
+ $.Tome08.level[3].nodes.node_T8L4_15.coordinates.y: 69.23076923076923
- $.Tome08.level[3].nodes.node_T8L4_15.objectives.EscapeWithItemUltraRareAsCharacterInTrial.questEvent[0].parameters: "instigator:me;ItemRarity:VeryRare"
+ $.Tome08.level[3].nodes.node_T8L4_15.objectives.EscapeWithItemUltraRareAsCharacterInTrial.questEvent[0].parameters: "instigator:me;ItemRarity:UltraRare"
- $.Tome08.level[3].nodes.node_T8L4_16.coordinates.x: 86.66666667
+ $.Tome08.level[3].nodes.node_T8L4_16.coordinates.x: 86.66666666666667
- $.Tome08.level[3].nodes.node_T8L4_16.coordinates.y: 92.30769231
+ $.Tome08.level[3].nodes.node_T8L4_16.coordinates.y: 92.3076923076923
- $.Tome08.level[3].nodes.node_T8L4_17.coordinates.y: 92.30769231
+ $.Tome08.level[3].nodes.node_T8L4_17.coordinates.y: 92.3076923076923
- $.Tome08.level[3].nodes.node_T8L4_18.coordinates.x: 73.33333333
+ $.Tome08.level[3].nodes.node_T8L4_18.coordinates.x: 73.33333333333333
- $.Tome08.level[3].nodes.node_T8L4_18.coordinates.y: 23.07692308
+ $.Tome08.level[3].nodes.node_T8L4_18.coordinates.y: 23.076923076923077
- $.Tome08.level[3].nodes.node_T8L4_End01.coordinates.y: 69.23076923
+ $.Tome08.level[3].nodes.node_T8L4_End01.coordinates.y: 69.23076923076923
- $.Tome08.level[3].nodes.node_T8L4_End02.coordinates.x: 86.66666667
+ $.Tome08.level[3].nodes.node_T8L4_End02.coordinates.x: 86.66666666666667
- $.Tome08.level[3].nodes.node_T8L4_Glyph01.coordinates.x: 13.33333333
+ $.Tome08.level[3].nodes.node_T8L4_Glyph01.coordinates.x: 13.333333333333334
- $.Tome08.level[3].nodes.node_T8L4_Glyph01.coordinates.y: 92.30769231
+ $.Tome08.level[3].nodes.node_T8L4_Glyph01.coordinates.y: 92.3076923076923
- $.Tome08.level[3].nodes.node_T8L4_Glyph02.coordinates.x: 66.66666667
+ $.Tome08.level[3].nodes.node_T8L4_Glyph02.coordinates.x: 66.66666666666667
- $.Tome08.level[3].nodes.node_T8L4_Start01.coordinates.y: 46.15384615
+ $.Tome08.level[3].nodes.node_T8L4_Start01.coordinates.y: 46.15384615384615
```

### [`archiveQuests/Tome14.json`](archiveQuests/Tome14.json)

[Full line-by-line diff](diffs/archiveQuests/Tome14.json.diff)

```diff
- $.Tome14.level[0].nodes.node_T14_L1_06.clientInfoId: "VaultInChaseInTrial"
+ $.Tome14.level[0].nodes.node_T14_L1_06.clientInfoId: "InteractWithItemAddedToMapInTrial"
- $.Tome14.level[0].nodes.node_T14_L1_06.objectives.VaultInChaseInTrial
+ $.Tome14.level[0].nodes.node_T14_L1_06.objectives.InteractWithItemAddedToMapInTrial
```

### [`archiveQuests/Tome15.json`](archiveQuests/Tome15.json)

[Full line-by-line diff](diffs/archiveQuests/Tome15.json.diff)

```diff
- $.Tome15.level[1].nodes.node_T15_L2_03.clientInfoId: "BreakPalletsGensInTrial"
+ $.Tome15.level[1].nodes.node_T15_L2_03.clientInfoId: "TrapSurvivorGoInActiveInTrial"
- $.Tome15.level[1].nodes.node_T15_L2_03.objectives.BreakPalletsGensInTrial
+ $.Tome15.level[1].nodes.node_T15_L2_03.objectives.DownAfterClawTrapInTrial
- $.Tome15.level[1].nodes.node_T15_L2_CM01.objectives.TitanCML2.specialBehaviours[id=TitanCoreMemory].params: "FragmentsToSpawn:9;FragmentsToCollect:4"
+ $.Tome15.level[1].nodes.node_T15_L2_CM01.objectives.TitanCML2.specialBehaviours[id=TitanCoreMemory].params: "fragmentsToSpawn:9;fragmentsToCollect:4"
```

### [`archiveQuests/Tome16.json`](archiveQuests/Tome16.json)

[Full line-by-line diff](diffs/archiveQuests/Tome16.json.diff)

```diff
- $.Tome16.level[3].nodes.node_T16_L4_14.clientInfoId: "ConsumeMedkit"
+ $.Tome16.level[3].nodes.node_T16_L4_14.clientInfoId: "Interact90WithItemAddedToMap"
- $.Tome16.level[3].nodes.node_T16_L4_14.objectives.ConsumeMedkit
+ $.Tome16.level[3].nodes.node_T16_L4_14.objectives.Interact90WithItemAddedToMap
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=S47]
- $[id=S48]
- $[id=CHALLENGE_REWARD_TIER_Rift_02]
- $[id=CHALLENGE_BATTLE_PASS_Rift_02]
- $[id=AV_Head028]
- $[id=AV_Legs028]
- $[id=AV_Torso028]
- $[id=BE_Body028]
- $[id=BE_Mask028]
- $[id=BE_W028]
- $[id=FM_Head002_04]
- $[id=FM_Legs031_01]
- $[id=FM_Torso027_02]
- $[id=HS_Head012_01]
- $[id=HS_Legs019_02]
- $[id=HS_Torso008_01]
- $[id=JP_Head011_01]
- $[id=JP_Legs019_01]
- $[id=JP_Torso08_03]
- $[id=K26_Body021]
- $[id=K26_Head021]
- $[id=K26_W021]
- $[id=K30_Body019]
- $[id=K30_Body019_01]
- $[id=K30_Body019_02]
- $[id=K30_Body019_03]
- $[id=K30_Head019]
- $[id=K30_Head019_01]
- $[id=K30_Head019_02]
- $[id=K30_Head019_03]
- $[id=K30_W019]
- $[id=K30_W019_01]
- $[id=K30_W019_02]
- $[id=K30_W019_03]
- $[id=K33_Body012]
- $[id=K33_Head012]
- $[id=K33_W012]
- $[id=K35_Body014]
- $[id=K35_Head014]
- $[id=K35_W014]
- $[id=KE_BNR_07]
- $[id=KET_002]
- $[id=KK_Body027_01]
- $[id=KK_Mask006_01]
- $[id=KK_W011_01]
- $[id=LS_001]
- $[id=LS_002]
- $[id=LS_003]
- $[id=LS_004]
- $[id=LS_005]
- $[id=LS_006]
- $[id=LS_007]
- $[id=LS_008]
- $[id=LS_009]
- $[id=LS_010]
- $[id=LS_012]
- $[id=LS_BDG_01]
- $[id=LS_BDG_02]
- $[id=LS_BDG_03]
- $[id=LS_BDG_04]
- $[id=LS_BDG_05]
- $[id=LS_BDG_06]
- $[id=LS_BDG_07]
- $[id=LS_BDG_08]
- $[id=LS_BDG_09]
- $[id=LS_BDG_10]
- $[id=LS_BDG_11]
- $[id=LS_BNR_01]
- $[id=LS_BNR_02]
- $[id=LS_BNR_03]
- $[id=LS_BNR_04]
- $[id=LS_BNR_05]
- $[id=LS_BNR_06]
- $[id=LS_BNR_07]
- $[id=LS_BNR_08]
- $[id=LS_BNR_09]
- $[id=LS_BNR_10]
- $[id=LS_BNR_11]
- $[id=S23_Head033]
- $[id=S23_Head033_01]
- $[id=S23_Head033_02]
- $[id=S23_Head033_03]
- $[id=S23_Legs033]
- $[id=S23_Legs033_01]
- $[id=S23_Legs033_02]
- $[id=S23_Legs033_03]
- $[id=S23_Torso033]
- $[id=S23_Torso033_01]
- $[id=S23_Torso033_02]
- $[id=S23_Torso033_03]
- $[id=S24_Head025]
- $[id=S24_Head026]
- $[id=S24_Head026_01]
- $[id=S24_Head026_02]
- $[id=S24_Head026_03]
- $[id=S24_Legs025]
- $[id=S24_Legs026]
- $[id=S24_Legs026_01]
- $[id=S24_Legs026_02]
- $[id=S24_Legs026_03]
- $[id=S24_Torso025]
- $[id=S24_Torso026]
- $[id=S24_Torso026_01]
- $[id=S24_Torso026_02]
- $[id=S24_Torso026_03]
- $[id=S28_Head031]
- $[id=S28_Head031_01]
- $[id=S28_Head031_02]
- $[id=S28_Head031_03]
- $[id=S28_Legs031]
- $[id=S28_Legs031_01]
- $[id=S28_Legs031_02]
- $[id=S28_Legs031_03]
- $[id=S28_Torso031]
- $[id=S28_Torso031_01]
- $[id=S28_Torso031_02]
- $[id=S28_Torso031_03]
- $[id=S31_Head023]
- $[id=S31_Legs023]
- $[id=S31_Torso023]
- $[id=S35_Head022]
- $[id=S35_Head023]
- $[id=S35_Head023_01]
- $[id=S35_Head023_02]
- $[id=S35_Head023_03]
- $[id=S35_Legs022]
- $[id=S35_Legs023]
- $[id=S35_Legs023_01]
- $[id=S35_Legs023_02]
- $[id=S35_Legs023_03]
- $[id=S35_Torso022]
- $[id=S35_Torso023]
- $[id=S35_Torso023_01]
- $[id=S35_Torso023_02]
- $[id=S35_Torso023_03]
- $[id=S37_Head022]
- $[id=S37_Legs022]
- $[id=S37_Torso022]
- $[id=S41_Head019]
- $[id=S41_Legs019]
- $[id=S41_Torso019]
- $[id=S43_Head010]
- $[id=S43_Head011]
- $[id=S43_Legs010]
- $[id=S43_Legs011]
- $[id=S43_Torso010]
- $[id=S43_Torso011]
- $[id=S45_Head012]
- $[id=S45_Legs012]
- $[id=S45_Torso012]
- $[id=S46_Head009]
- $[id=S46_Legs009]
- $[id=S46_Torso009]
- $[id=S47_Head006]
- $[id=S47_Head007]
- $[id=S47_Head008]
- $[id=S47_Head01]
- $[id=S47_Head01_P01]
- $[id=S47_Legs006]
- $[id=S47_Legs007]
- $[id=S47_Legs008]
- $[id=S47_Legs01]
- $[id=S47_Legs01_P01]
- $[id=S47_PCharm001]
- $[id=S47_PCharm002]
- $[id=S47_PCharm003]
- $[id=S47_Torso006]
- $[id=S47_Torso007]
- $[id=S47_Torso008]
- $[id=S47_Torso01]
- $[id=S47_Torso01_01]
- $[id=S47_Torso01_02]
- $[id=S47_Torso01_03]
- $[id=S47_Torso01_P01]
- $[id=S48_Head006]
- $[id=S48_Head007]
- $[id=S48_Head01]
- $[id=S48_Head01_P01]
- $[id=S48_Legs006]
- $[id=S48_Legs007]
- $[id=S48_Legs01]
- $[id=S48_Legs01_P01]
- $[id=S48_PCharm001]
- $[id=S48_PCharm002]
- $[id=S48_PCharm003]
- $[id=S48_Torso006]
- $[id=S48_Torso007]
- $[id=S48_Torso01]
- $[id=S48_Torso01_01]
- $[id=S48_Torso01_02]
- $[id=S48_Torso01_03]
- $[id=S48_Torso01_P01]
- $[id=TW_Body03_01]
- $[id=TW_Head009_02]
- $[id=TW_W007_02]
- $[id=WI_Body019]
- $[id=WI_Body019_01]
- $[id=WI_Body019_02]
- $[id=WI_Body019_03]
- $[id=WI_Hair019]
… 265 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "TÄGLICHE QUESTS"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2 gegen 8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Zerstöre {0} Palette(n)."
+ $.locText[30].text: "Quests müssen in 2 gegen 8 abgeschlossen werden"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Stoße während einer Jagd {0} Palette(n) um."
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "TÄGLICHE QUESTS"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2 gegen 8"
+ $.locText[33].text: "Schließe {0} Quest(s) in 2 gegen 8 ab."
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Quests müssen in 2 gegen 8 abgeschlossen werden"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Schließe {0} Quest(s) in 2 gegen 8 ab."
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Schließe {0} Quest(s) in 2 gegen 8 ab."
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Schließe {0} Quest(s) in 2 gegen 8 ab."
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Schließe {0} Quest(s) in 2 gegen 8 ab."
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Spiele {0} Prüfung(en) als {1}."
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Schließe {0} Quest(s) in 2 gegen 8 ab."
+ $.locText[43].text: "Spiele als {1} in {0} Prüfung(en)."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Spiele {0} Prüfung(en) als {1}."
+ $.locText[46].text: "Störe {0} Krähe(n)."
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Spiele als {1} in {0} Prüfung(en)."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Zerstöre {0} Palette(n)."
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Störe {0} Krähe(n)."
+ $.locText[50].text: "Stoße während einer Jagd {0} Palette(n) um."
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "DAILY QUESTS"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2V8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Destroy {0} pallet(s)"
+ $.locText[30].text: "Quests must be completed in 2v8"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Drop {0} pallet(s) while in chase"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "DAILY QUESTS"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2V8"
+ $.locText[33].text: "Complete {0} 2v8 quest(s)"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Quests must be completed in 2v8"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Complete {0} 2v8 quest(s)"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Complete {0} 2v8 quest(s)"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Complete {0} 2v8 quest(s)"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Complete {0} 2v8 quest(s)"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Play as {1} for {0} trial(s)"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Complete {0} 2v8 quest(s)"
+ $.locText[43].text: "Play as {1} in {0} trial(s)"
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Play as {1} for {0} trial(s)"
+ $.locText[46].text: "Disturb {0} crow(s)"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Play as {1} in {0} trial(s)"
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Destroy {0} pallet(s)"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Disturb {0} crow(s)"
+ $.locText[50].text: "Drop {0} pallet(s) while in chase"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "MISIONES DIARIAS"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2v8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Rompe {0} tarima(s)."
+ $.locText[30].text: "Las misiones deben completarse en 2v8"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Deja caer {0} tarima(s) durante una persecución."
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "MISIONES DIARIAS"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2v8"
+ $.locText[33].text: "Completa {0} misión/misiones de 2v8."
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Las misiones deben completarse en 2v8"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Completa {0} misión/misiones de 2v8."
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Completa {0} misión/misiones de 2v8."
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Completa {0} misión/misiones de 2v8."
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Completa {0} misión/misiones de 2v8."
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Juega como {1} durante {0} partida(s)."
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Completa {0} misión/misiones de 2v8."
+ $.locText[43].text: "En {0} partida(s), juega como {1}."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Juega como {1} durante {0} partida(s)."
+ $.locText[46].text: "Molesta a {0} cuervo(s)."
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "En {0} partida(s), juega como {1}."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Rompe {0} tarima(s)."
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Molesta a {0} cuervo(s)."
+ $.locText[50].text: "Deja caer {0} tarima(s) durante una persecución."
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "MISIONES DIARIAS"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2c8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Rompe {0} palé(s)."
+ $.locText[30].text: "Las misiones deben completarse en 2c8."
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Suelta {0} palé(s) durante una persecución."
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "MISIONES DIARIAS"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2c8"
+ $.locText[33].text: "Completa {0} misión/misiones de 2c8."
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Las misiones deben completarse en 2c8."
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Completa {0} misión/misiones de 2c8."
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Completa {0} misión/misiones de 2c8."
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Completa {0} misión/misiones de 2c8."
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Completa {0} misión/misiones de 2c8."
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Juega como {1} durante {0} partida(s)."
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Completa {0} misión/misiones de 2c8."
+ $.locText[43].text: "Juega como {1} en {0} partida(s)."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Juega como {1} durante {0} partida(s)."
+ $.locText[46].text: "Molesta a {0} cuervo(s)."
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Juega como {1} en {0} partida(s)."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Rompe {0} palé(s)."
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Molesta a {0} cuervo(s)."
+ $.locText[50].text: "Suelta {0} palé(s) durante una persecución."
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "QUÊTES JOURNALIÈRES"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2V8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Détruire {0} palette(s)"
+ $.locText[30].text: "Les quêtes doivent être accomplies en 2v8"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Renversez {0} palette(s) pendant une poursuite"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "QUÊTES JOURNALIÈRES"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2V8"
+ $.locText[33].text: "Accomplir {0} quête(s) de 2v8"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Les quêtes doivent être accomplies en 2v8"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Accomplir {0} quête(s) de 2v8"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Accomplir {0} quête(s) de 2v8"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Accomplir {0} quête(s) de 2v8"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Accomplir {0} quête(s) de 2v8"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Jouez avec {1} dans {0} épreuve(s)"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Accomplir {0} quête(s) de 2v8"
+ $.locText[43].text: "Jouez avec {1} dans {0} Épreuve(s)"
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Jouez avec {1} dans {0} épreuve(s)"
+ $.locText[46].text: "Dérangez {0} corbeau(x)"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Jouez avec {1} dans {0} Épreuve(s)"
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Détruire {0} palette(s)"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Dérangez {0} corbeau(x)"
+ $.locText[50].text: "Renversez {0} palette(s) pendant une poursuite"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "MISSIONI GIORNALIERE"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2v8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Distruggi {0} bancale/i"
+ $.locText[30].text: "Le missioni devono essere completate in 2v8"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Lancia {0} bancale/i durante un inseguimento"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "MISSIONI GIORNALIERE"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2v8"
+ $.locText[33].text: "Completa {0} missione/i 2v8"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Le missioni devono essere completate in 2v8"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Completa {0} missione/i 2v8"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Completa {0} missione/i 2v8"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Completa {0} missione/i 2v8"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Completa {0} missione/i 2v8"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Gioca nei panni di {1} per {0} prova/e"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Completa {0} missione/i 2v8"
+ $.locText[43].text: "Gioca nei panni di {1} in {0} prova/e."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Gioca nei panni di {1} per {0} prova/e"
+ $.locText[46].text: "Disturba {0} corvo/i"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Gioca nei panni di {1} in {0} prova/e."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Distruggi {0} bancale/i"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Disturba {0} corvo/i"
+ $.locText[50].text: "Lancia {0} bancale/i durante un inseguimento"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "デイリークエスト"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2対8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "パレットを{0}枚破壊する"
+ $.locText[30].text: "クエストは2対8で完了する必要があります"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "追跡中にパレットを{0}枚倒す"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "デイリークエスト"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2対8"
+ $.locText[33].text: "2対8クエストを{0}個完了する"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "クエストは2対8で完了する必要があります"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "2対8クエストを{0}個完了する"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "2対8クエストを{0}個完了する"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "2対8クエストを{0}個完了する"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "2対8クエストを{0}個完了する"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "{0}回の儀式で{1}としてプレイする"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "2対8クエストを{0}個完了する"
+ $.locText[43].text: "{0}回の儀式で{1}としてプレイする"
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "{0}回の儀式で{1}としてプレイする"
+ $.locText[46].text: "カラスを{0}羽騒がせる"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "{0}回の儀式で{1}としてプレイする"
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "パレットを{0}枚破壊する"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "カラスを{0}羽騒がせる"
+ $.locText[50].text: "追跡中にパレットを{0}枚倒す"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "일일 퀘스트"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2V8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "판자를 {0}개 부수기"
+ $.locText[30].text: "퀘스트는 2V8에서 완료해야 합니다"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "추격 중 판자 {0}개 내리기"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "일일 퀘스트"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2V8"
+ $.locText[33].text: "2v8 퀘스트 {0}개 완료하기"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "퀘스트는 2V8에서 완료해야 합니다"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "2v8 퀘스트 {0}개 완료하기"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "2v8 퀘스트 {0}개 완료하기"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "2v8 퀘스트 {0}개 완료하기"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "2v8 퀘스트 {0}개 완료하기"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "희생제 {0}회 동안 {1}(으)로 플레이하기"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "2v8 퀘스트 {0}개 완료하기"
+ $.locText[43].text: "{0} 희생제에서 {1}(으)로 플레이하기."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "희생제 {0}회 동안 {1}(으)로 플레이하기"
+ $.locText[46].text: "까마귀 {0}마리 방해하기"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "{0} 희생제에서 {1}(으)로 플레이하기."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "판자를 {0}개 부수기"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "까마귀 {0}마리 방해하기"
+ $.locText[50].text: "추격 중 판자 {0}개 내리기"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "CODZIENNE ZADANIA"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2 na 8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Uszkodź tyle palet: {0}"
+ $.locText[30].text: "Zadania należy ukończyć w trybie 2 na 8"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Przewróć tyle palet w pościgu: {0}"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "CODZIENNE ZADANIA"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2 na 8"
+ $.locText[33].text: "Ukończ tyle zadań 2 na 8: {0}"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Zadania należy ukończyć w trybie 2 na 8"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Ukończ tyle zadań 2 na 8: {0}"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Ukończ tyle zadań 2 na 8: {0}"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Ukończ tyle zadań 2 na 8: {0}"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Ukończ tyle zadań 2 na 8: {0}"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Graj jako {1} przez tyle prób: {0}"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Ukończ tyle zadań 2 na 8: {0}"
+ $.locText[43].text: "Zagraj jako {1} w tylu próbach: {0}."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Graj jako {1} przez tyle prób: {0}"
+ $.locText[46].text: "Wystrasz tyle wron: {0}"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Zagraj jako {1} w tylu próbach: {0}."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Uszkodź tyle palet: {0}"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Wystrasz tyle wron: {0}"
+ $.locText[50].text: "Przewróć tyle palet w pościgu: {0}"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "MISSÕES DIÁRIAS"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "Modo 2x8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "Quebre {0} barricada(s)"
+ $.locText[30].text: "Missões devem ser concluídas no Modo 2x8"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Derrube {0} barricada(s) durante uma perseguição"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "MISSÕES DIÁRIAS"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "Modo 2x8"
+ $.locText[33].text: "Complete {0} missão(ões) do Modo 2x8"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Missões devem ser concluídas no Modo 2x8"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Complete {0} missão(ões) do Modo 2x8"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Complete {0} missão(ões) do Modo 2x8"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Complete {0} missão(ões) do Modo 2x8"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Complete {0} missão(ões) do Modo 2x8"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Jogue como {1} por {0} partida(s)"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Complete {0} missão(ões) do Modo 2x8"
+ $.locText[43].text: "Jogue como {1} em {0} partida(s)."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Jogue como {1} por {0} partida(s)"
+ $.locText[46].text: "Perturbe {0} corvo(s)"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Jogue como {1} em {0} partida(s)."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "Quebre {0} barricada(s)"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "Perturbe {0} corvo(s)"
+ $.locText[50].text: "Derrube {0} barricada(s) durante uma perseguição"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "ЗАДАНИЯ ДНЯ"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2 против 8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "{0} раз(а) сломайте доски"
+ $.locText[30].text: "Задания необходимо выполнить в режиме «2 против 8»"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "{0} раз(а) уроните доски во время погони"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "ЗАДАНИЯ ДНЯ"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2 против 8"
+ $.locText[33].text: "Выполните задания «2 против 8»: {0}"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Задания необходимо выполнить в режиме «2 против 8»"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "Выполните задания «2 против 8»: {0}"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "Выполните задания «2 против 8»: {0}"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "Выполните задания «2 против 8»: {0}"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "Выполните задания «2 против 8»: {0}"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "Сыграйте как {1} {0} р."
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "Выполните задания «2 против 8»: {0}"
+ $.locText[43].text: "Сыграйте за персонажа {1} {0} раз(а)."
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "Сыграйте как {1} {0} р."
+ $.locText[46].text: "{0} раз(а) потревожьте ворон"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "Сыграйте за персонажа {1} {0} раз(а)."
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "{0} раз(а) сломайте доски"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "{0} раз(а) потревожьте ворон"
+ $.locText[50].text: "{0} раз(а) уроните доски во время погони"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "เควสต์ประจำวัน"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2V8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "ทำลายแท่นไม้ {0} แท่น"
+ $.locText[30].text: "ต้องพิชิตเควสต์ใน 2v8"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "ล้มแท่นไม้ {0} แท่นระหว่างการไล่ล่า"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "เควสต์ประจำวัน"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2V8"
+ $.locText[33].text: "ผ่านเควสต์ 2v8 {0} เควสต์"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "ต้องพิชิตเควสต์ใน 2v8"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "ผ่านเควสต์ 2v8 {0} เควสต์"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "ผ่านเควสต์ 2v8 {0} เควสต์"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "ผ่านเควสต์ 2v8 {0} เควสต์"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "ผ่านเควสต์ 2v8 {0} เควสต์"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "เล่นเป็น{1} {0} เกม"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "ผ่านเควสต์ 2v8 {0} เควสต์"
+ $.locText[43].text: "เล่นเป็น{1}ใน {0} เกม"
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "เล่นเป็น{1} {0} เกม"
+ $.locText[46].text: "รบกวนอีกา {0} ตัว"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "เล่นเป็น{1}ใน {0} เกม"
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "ทำลายแท่นไม้ {0} แท่น"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "รบกวนอีกา {0} ตัว"
+ $.locText[50].text: "ล้มแท่นไม้ {0} แท่นระหว่างการไล่ล่า"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "GÜNLÜK GÖREVLER"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2'ye 8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "{0} palet kır"
+ $.locText[30].text: "Görevlerin 2'ye 8'de tamamlanması gerekir"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "Kovalama sırasında {0} palet düşür"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "GÜNLÜK GÖREVLER"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2'ye 8"
+ $.locText[33].text: "{0} 2'ye 8 Görevi tamamla."
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "Görevlerin 2'ye 8'de tamamlanması gerekir"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "{0} 2'ye 8 Görevi tamamla."
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "{0} 2'ye 8 Görevi tamamla."
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "{0} 2'ye 8 Görevi tamamla."
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "{0} 2'ye 8 Görevi tamamla."
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "{0} Mücadele boyunca {1} olarak oyna"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "{0} 2'ye 8 Görevi tamamla."
+ $.locText[43].text: "{1} olarak {0} mücadele oyna"
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "{0} Mücadele boyunca {1} olarak oyna"
+ $.locText[46].text: "{0} karga ürküt"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "{1} olarak {0} mücadele oyna"
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "{0} palet kır"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "{0} karga ürküt"
+ $.locText[50].text: "Kovalama sırasında {0} palet düşür"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "每日任务"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2V8"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "破坏{0}处木板"
+ $.locText[30].text: "任务必须在2V8中完成。"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "被追杀时，扔下{0}处木板"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "每日任务"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2V8"
+ $.locText[33].text: "完成{0}项2v8任务"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "任务必须在2V8中完成。"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "完成{0}项2v8任务"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "完成{0}项2v8任务"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "完成{0}项2v8任务"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "完成{0}项2v8任务"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "扮演{1}，完成{0}场比赛"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "完成{0}项2v8任务"
+ $.locText[43].text: "扮演{1}职能，完成{0}场比赛。"
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "扮演{1}，完成{0}场比赛"
+ $.locText[46].text: "惊扰{0}只乌鸦"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "扮演{1}职能，完成{0}场比赛。"
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "破坏{0}处木板"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "惊扰{0}只乌鸦"
+ $.locText[50].text: "被追杀时，扔下{0}处木板"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[28].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].text: "每日任務"
- $.locText[28].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
+ $.locText[28].textId: "LIST_Daily_TITLE"
- $.locText[29].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].text: "2v8模式"
- $.locText[29].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
+ $.locText[29].textId: "CHALLENGESET_CalamariJerky_TITLE"
- $.locText[30].text: "擊破{0}個木板"
+ $.locText[30].text: "任務必須在2V8中完成"
- $.locText[30].textId: "CHALLENGE_BreakPallets_INFO"
+ $.locText[30].textId: "CHALLENGESET_CalamariJerky_INFO"
- $.locText[31].text: "在追殺時掉落木板{0}次"
+ $.locText[31].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[31].textId: "CHALLENGE_PalletDropInChase_INFO"
+ $.locText[31].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
- $.locText[32].text: "每日任務"
+ $.locText[32].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[32].textId: "LIST_Daily_TITLE"
+ $.locText[32].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
- $.locText[33].text: "2v8模式"
+ $.locText[33].text: "完成{0}個2v8任務"
- $.locText[33].textId: "CHALLENGESET_CalamariJerky_TITLE"
+ $.locText[33].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
- $.locText[34].text: "任務必須在2V8中完成"
+ $.locText[34].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[34].textId: "CHALLENGESET_CalamariJerky_INFO"
+ $.locText[34].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
- $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests1_TITLE"
+ $.locText[35].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
- $.locText[36].text: "@#CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].text: "完成{0}個2v8任務"
- $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests1_DESC"
+ $.locText[36].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
- $.locText[37].text: "完成{0}個2v8任務"
+ $.locText[37].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests1_INFO"
+ $.locText[37].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
- $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests2_TITLE"
+ $.locText[38].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
- $.locText[39].text: "@#CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].text: "完成{0}個2v8任務"
- $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests2_DESC"
+ $.locText[39].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
- $.locText[40].text: "完成{0}個2v8任務"
+ $.locText[40].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[40].textId: "CHALLENGE_CompleteCalamariQuests2_INFO"
+ $.locText[40].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
- $.locText[41].text: "@#CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[41].textId: "CHALLENGE_CompleteCalamariQuests3_TITLE"
+ $.locText[41].textId: "CHALLENGE_PlayAsCharacterOrClass_"
- $.locText[42].text: "@#CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].text: "在{0}場遊戲中扮演{1}"
- $.locText[42].textId: "CHALLENGE_CompleteCalamariQuests3_DESC"
+ $.locText[42].textId: "CHALLENGE_PlayAsCharacter_INFO"
- $.locText[43].text: "完成{0}個2v8任務"
+ $.locText[43].text: "扮演{1}進行{0}場遊戲。"
- $.locText[43].textId: "CHALLENGE_CompleteCalamariQuests3_INFO"
+ $.locText[43].textId: "CHALLENGE_PlayAsClass_INFO"
- $.locText[44].text: "@#CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].text: "@#CHALLENGE_Crow_TITLE"
- $.locText[44].textId: "CHALLENGE_PlayAsCharacterOrClass_TITLE"
+ $.locText[44].textId: "CHALLENGE_Crow_TITLE"
- $.locText[45].text: "@#CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].text: "@#CHALLENGE_Crow_DESC"
- $.locText[45].textId: "CHALLENGE_PlayAsCharacterOrClass_"
+ $.locText[45].textId: "CHALLENGE_Crow_DESC"
- $.locText[46].text: "在{0}場遊戲中扮演{1}"
+ $.locText[46].text: "驚動烏鴉{0}次"
- $.locText[46].textId: "CHALLENGE_PlayAsCharacter_INFO"
+ $.locText[46].textId: "CHALLENGE_Crow_INFO"
- $.locText[47].text: "扮演{1}進行{0}場遊戲。"
+ $.locText[47].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[47].textId: "CHALLENGE_PlayAsClass_INFO"
+ $.locText[47].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_TITLE"
- $.locText[48].text: "@#CHALLENGE_Crow_TITLE"
+ $.locText[48].text: "@#CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[48].textId: "CHALLENGE_Crow_TITLE"
+ $.locText[48].textId: "CHALLENGE_BreakPalletsOrPalletDropInChase_DESC"
- $.locText[49].text: "@#CHALLENGE_Crow_DESC"
+ $.locText[49].text: "擊破{0}個木板"
- $.locText[49].textId: "CHALLENGE_Crow_DESC"
+ $.locText[49].textId: "CHALLENGE_BreakPallets_INFO"
- $.locText[50].text: "驚動烏鴉{0}次"
+ $.locText[50].text: "在追殺時掉落木板{0}次"
- $.locText[50].textId: "CHALLENGE_Crow_INFO"
+ $.locText[50].textId: "CHALLENGE_PalletDropInChase_INFO"
- $.locText[247]
- $.locText[248]
- $.locText[249]
- $.locText[250]
- $.locText[251]
- $.locText[252]
- $.locText[253]
- $.locText[254]
- $.locText[255]
- $.locText[256]
- $.locText[257]
- $.locText[258]
- $.locText[259]
- $.locText[260]
- $.locText[261]
- $.locText[262]
- $.locText[263]
- $.locText[264]
- $.locText[265]
- $.locText[266]
- $.locText[267]
- $.locText[268]
- $.locText[269]
- $.locText[270]
- $.locText[271]
- $.locText[272]
- $.locText[273]
- $.locText[274]
- $.locText[275]
- $.locText[276]
- $.locText[277]
- $.locText[278]
- $.locText[279]
- $.locText[280]
- $.locText[281]
- $.locText[282]
- $.locText[283]
- $.locText[284]
- $.locText[285]
- $.locText[286]
- $.locText[287]
- $.locText[288]
- $.locText[289]
- $.locText[290]
- $.locText[291]
- $.locText[292]
- $.locText[293]
- $.locText[294]
- $.locText[295]
- $.locText[296]
- $.locText[297]
- $.locText[298]
- $.locText[299]
- $.locText[300]
- $.locText[301]
- $.locText[302]
- $.locText[303]
- $.locText[304]
- $.locText[305]
- $.locText[306]
- $.locText[307]
- $.locText[308]
- $.locText[309]
- $.locText[310]
- $.locText[311]
- $.locText[312]
- $.locText[313]
- $.locText[314]
- $.locText[315]
- $.locText[316]
- $.locText[317]
- $.locText[318]
- $.locText[319]
- $.locText[320]
- $.locText[321]
- $.locText[322]
- $.locText[323]
- $.locText[324]
- $.locText[325]
- $.locText[326]
- $.locText[327]
- $.locText[328]
- $.locText[329]
- $.locText[330]
- $.locText[331]
- $.locText[332]
- $.locText[333]
- $.locText[334]
- $.locText[335]
- $.locText[336]
- $.locText[337]
- $.locText[338]
- $.locText[339]
- $.locText[340]
- $.locText[341]
- $.locText[342]
- $.locText[343]
- $.locText[344]
- $.locText[345]
- $.locText[346]
- $.locText[347]
- $.locText[348]
- $.locText[349]
- $.locText[350]
- $.locText[351]
- $.locText[352]
- $.locText[353]
- $.locText[354]
… 15 more change(s) — see the commit diff for everything
```

### [`challengeRewardTrackers.json`](challengeRewardTrackers.json)

[Full line-by-line diff](diffs/challengeRewardTrackers.json.diff)

```diff
- $.Rift_02
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.Milestone_02_Set
- $.Onboarding_Set
- $.Rift_02_QuestSet
+ $.CalamariJerky
+ $.ChocolateBoxJerkySet
- $.AnniversaryKetchupSet.mask: 0
- $.AnniversaryKetchupSet.titleLocalizationText
- $.Daily_Set.mask: 0
- $.Daily_Set.titleLocalizationText
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakPalletsOrPalletDropInChase]
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].objectives.Hook.neededProgression[]: 5
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].objectives.Hook.neededProgression[]: 3
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].objectives.Unhook.neededProgression[]: 3
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].objectives.Unhook.neededProgression[]: 1
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].riftPoints: 25
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HookOrUnhook].riftPoints: 15
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HitOrHeal].objectives.Hit.neededProgression[]: 20
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HitOrHeal].objectives.Hit.neededProgression[]: 4
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HitOrHeal].riftPoints: 25
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_HitOrHeal].riftPoints: 15
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].objectives.BreakGens.neededProgression[]: 5
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].objectives.BreakGens.neededProgression[]: 3
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].objectives.GenSkillCheckGreatSuccessInTrialWithPerk.neededProgression[]: 10
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].objectives.GenSkillCheckGreatSuccessInTrialWithPerk.neededProgression[]: 3
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].riftPoints: 25
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_BreakGenOrGenSkillCheck].riftPoints: 15
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].objectives.Kill.neededProgression[]: 3
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].objectives.Kill.neededProgression[]: 1
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].objectives.RepairPerc.neededProgression[]: 300
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].objectives.RepairPerc.neededProgression[]: 100
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].riftPoints: 25
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_KillSurvivorOrRepairGens].riftPoints: 15
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_EarnBloodpoints].objectives.EarnBloodpoints.neededProgression[]: 30000
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_EarnBloodpoints].objectives.EarnBloodpoints.neededProgression[]: 15000
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_EarnBloodpoints].riftPoints: 25
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_EarnBloodpoints].riftPoints: 15
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_CompleteTrial].riftPoints: 25
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-B_CompleteTrial].riftPoints: 15
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_ChaseOrBeChased].objectives.Chase.neededProgression[]: 180
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_ChaseOrBeChased].objectives.Chase.neededProgression[]: 30
- $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_ChaseOrBeChased].riftPoints: 25
+ $.Daily_Set.challengeList[0].challenges[id=Daily_Set-Daily-D_ChaseOrBeChased].riftPoints: 15
- $.Milestone_Set.endDate: "2025-07-29T15:00:00"
- $.Milestone_Set.mask: 0
- $.Milestone_Set.titleLocalizationText
- $.Milestone_Set.challengeList[0].endDate: "2025-07-29T15:00:00"
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_CompleteTrial].lifetimeInDays: 84
- $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_CompleteTrial].isRecurring: false
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_CompleteTrial].isRecurring: true
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Hook].lifetimeInDays: 84
- $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Hook].isRecurring: false
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Hook].isRecurring: true
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Kill].lifetimeInDays: 84
- $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Kill].isRecurring: false
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Kill].isRecurring: true
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_BreakGen].lifetimeInDays: 84
- $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_BreakGen].isRecurring: false
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_BreakGen].isRecurring: true
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Repair].lifetimeInDays: 84
- $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Repair].isRecurring: false
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Repair].isRecurring: true
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Heal].lifetimeInDays: 84
- $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Heal].isRecurring: false
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Heal].isRecurring: true
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Escape].lifetimeInDays: 84
- $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Escape].isRecurring: false
+ $.Milestone_Set.challengeList[0].challenges[id=Milestone_Set-Milestone-M_Escape].isRecurring: true
- $.Rift_01_QuestSet.mask: 0
- $.Rift_01_QuestSet.titleLocalizationText
- $.Rift_01_QuestSet.challengeList[3].challenges[id=Rift_01_QuestSet-List_4-B_CoopAction].rewards[id=Bloodpoints]
+ $.Rift_01_QuestSet.challengeList[3].challenges[id=Rift_01_QuestSet-List_4-B_CoopAction].rewards[id=BonusBloodpoints]
- $.Rift_01_QuestSet.challengeList[9].challenges[id=Rift_01_QuestSet-List_10-D_BreakGenSingleTrialOrEscapeChaseLockerSingleTrial].objectives.BreakGensInTrial
+ $.Rift_01_QuestSet.challengeList[9].challenges[id=Rift_01_QuestSet-List_10-D_BreakGenSingleTrialOrEscapeChaseLockerSingleTrial].objectives.BreakGenSameInTrial
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_SteadyPulse.T_UI_CollectionBanner_SteadyPulse"
+ $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SteadyPulse.T_UI_CollectionBanner_SteadyPulse"
- $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_Chrysalis_2.T_UI_CollectionBanner_Chrysalis_2"
+ $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Chrysalis_2.T_UI_CollectionBanner_Chrysalis_2"
- $.collections[9].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_TheWitcher.T_UI_CollectionBanner_TheWitcher"
+ $.collections[9].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_TheWitcher.T_UI_CollectionBanner_TheWitcher"
- $.collections[13].limitedAvailabilityEndDate: "2025-07-17T15:00:00Z"
+ $.collections[13].limitedAvailabilityEndDate: "2025-07-24T15:00:00Z"
- $.collections[14].limitedAvailabilityStartDate: "2025-07-02T15:00:00Z"
- $.collections[14].visibleBeforeStartDate: false
- $.collections[14].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_Casual.T_UI_SpecialPack_Casual"
+ $.collections[14].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_WaterfrontMassacreXenomorph.T_UI_SpecialPack_WaterfrontMassacreXenomorph"
- $.collections[14].collectionId: "Casual"
+ $.collections[14].collectionId: "WaterfrontMassacre"
- $.collections[14].collectionTitle.de: "Leger"
+ $.collections[14].collectionTitle.de: "Hafenmassaker"
- $.collections[14].collectionTitle.en: "Casual"
+ $.collections[14].collectionTitle.en: "Waterfront Massacre"
- $.collections[14].collectionTitle.es: "Casual"
+ $.collections[14].collectionTitle.es: "Masacre de la costa"
- $.collections[14].collectionTitle["es-MX"]: "Casual"
+ $.collections[14].collectionTitle["es-MX"]: "Masacre en la costa"
- $.collections[14].collectionTitle.fr: "Décontracté"
+ $.collections[14].collectionTitle.fr: "Massacre au bord de la mer"
- $.collections[14].collectionTitle.it: "Casual"
+ $.collections[14].collectionTitle.it: "Collezione Massacro sul lungomare"
- $.collections[14].collectionTitle.ja: "カジュアル"
+ $.collections[14].collectionTitle.ja: "水辺の殺戮"
- $.collections[14].collectionTitle.ko: "캐주얼"
+ $.collections[14].collectionTitle.ko: "해안가 대학살"
- $.collections[14].collectionTitle.pl: "Casual"
+ $.collections[14].collectionTitle.pl: "Nadbrzeżna masakra"
- $.collections[14].collectionTitle["pt-BR"]: "Casual"
+ $.collections[14].collectionTitle["pt-BR"]: "Massacre da Costa"
- $.collections[14].collectionTitle.ru: "Повседневная"
+ $.collections[14].collectionTitle.ru: "Пляжная резня"
- $.collections[14].collectionTitle.th: "ลำลอง"
+ $.collections[14].collectionTitle.th: "การสังหารหมู่ริมน้ำ"
- $.collections[14].collectionTitle.tr: "Günlük"
+ $.collections[14].collectionTitle.tr: "Su Kenarı Katliamı"
- $.collections[14].collectionTitle["zh-Hans"]: "休闲"
+ $.collections[14].collectionTitle["zh-Hans"]: "滨水屠杀"
- $.collections[14].collectionTitle["zh-Hant"]: "休閒"
+ $.collections[14].collectionTitle["zh-Hant"]: "水邊屠殺"
- $.collections[14].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_Casual.T_UI_CollectionBanner_Casual"
+ $.collections[14].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_WaterfrontMassacreXenomorph.T_UI_CollectionBanner_WaterfrontMassacreXenomorph"
- $.collections[14].inclusionVersion: "9.0.1"
+ $.collections[14].inclusionVersion: "7.7.0 PTB"
- $.collections[14].items[]: "S31_outfit_023"
- $.collections[14].items[]: "S45_outfit_012"
- $.collections[14].items[]: "S37_outfit_022"
- $.collections[14].items[]: "S35_outfit_022"
+ $.collections[14].items[]: "CM_outfit_012"
+ $.collections[14].items[]: "DK_outfit_014"
+ $.collections[14].items[]: "DF_outfit_015"
+ $.collections[14].items[]: "FM_outfit_019"
+ $.collections[14].items[]: "MS_outfit_008"
+ $.collections[14].items[]: "GS_outfit_015"
+ $.collections[14].items[]: "NK_outfit_015"
+ $.collections[14].items[]: "SwedenSurvivor_outfit_010"
+ $.collections[14].items[]: "TC_outfit_009"
+ $.collections[14].items[]: "TC_outfit_009_01"
+ $.collections[14].items[]: "TR_outfit_010"
+ $.collections[14].items[]: "K23_outfit_016"
+ $.collections[14].items[]: "KS_outfit_017"
+ $.collections[14].items[]: "MT_outfit_024"
+ $.collections[14].items[]: "S23_outfit_017"
+ $.collections[14].items[]: "S25_outfit_016"
+ $.collections[14].items[]: "S28_outfit_012"
+ $.collections[14].items[]: "S31_outfit_006"
+ $.collections[14].items[]: "S41_outfit_009"
+ $.collections[14].items[]: "HS_outfit_023"
+ $.collections[14].items[]: "S37_outfit_016"
+ $.collections[14].items[]: "AV_outfit_028"
+ $.collections[14].items[]: "S24_outfit_025"
+ $.collections[14].items[]: "K33_outfit_012"
+ $.collections[14].items[]: "S46_outfit_009"
- $.collections[14].sortOrder: "-132"
+ $.collections[14].sortOrder: "-134"
- $.collections[14].updatedDate: "2025-05-23T13:05:39.676Z"
+ $.collections[14].updatedDate: "2025-07-17T12:33:39.197Z"
- $.collections[15].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_BouletBrothers.T_UI_SpecialPack_BouletBrothers"
+ $.collections[15].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_GuardiansAndShadows.T_UI_SpecialPack_GuardiansAndShadows"
- $.collections[15].collectionId: "BouletBrothers"
+ $.collections[15].collectionId: "GuardiansAndShadows"
- $.collections[15].collectionTitle.de: "Boulet Brothers"
+ $.collections[15].collectionTitle.de: "Wächter und Schatten"
- $.collections[15].collectionTitle.en: "Boulet Brothers"
+ $.collections[15].collectionTitle.en: "Guardians & Shadows"
- $.collections[15].collectionTitle.es: "Los hermanos Boulet"
+ $.collections[15].collectionTitle.es: "Guardianes y sombras"
- $.collections[15].collectionTitle["es-MX"]: "Boulet Brothers"
+ $.collections[15].collectionTitle["es-MX"]: "Guardianes y sombras"
- $.collections[15].collectionTitle.fr: "Boulet Brothers"
+ $.collections[15].collectionTitle.fr: "Gardiens et ombres"
- $.collections[15].collectionTitle.it: "Boulet Brothers"
+ $.collections[15].collectionTitle.it: "Guardiani e ombre"
- $.collections[15].collectionTitle.ja: "Boulet Brothers"
+ $.collections[15].collectionTitle.ja: "守護者と影"
- $.collections[15].collectionTitle.ko: "불릿 브라더스"
+ $.collections[15].collectionTitle.ko: "수호자와 그림자"
- $.collections[15].collectionTitle.pl: "Boulet Brothers"
+ $.collections[15].collectionTitle.pl: "Strażnicy i cienie"
- $.collections[15].collectionTitle["pt-BR"]: "Irmãos Boulet"
+ $.collections[15].collectionTitle["pt-BR"]: "Guardiões e Sombras"
- $.collections[15].collectionTitle.ru: "Братья Буле"
+ $.collections[15].collectionTitle.ru: "Стражи и тени"
- $.collections[15].collectionTitle.th: "พี่น้องบูเลต์"
+ $.collections[15].collectionTitle.th: "ผู้พิทักษ์กับเงา"
- $.collections[15].collectionTitle.tr: "Boulet Kardeşler"
+ $.collections[15].collectionTitle.tr: "Muhafızlar ve Gölgeler"
- $.collections[15].collectionTitle["zh-Hans"]: "布蕾兄弟"
+ $.collections[15].collectionTitle["zh-Hans"]: "守护者&暗影"
- $.collections[15].collectionTitle["zh-Hant"]: "砲彈兄弟"
+ $.collections[15].collectionTitle["zh-Hant"]: "守衛與暗影"
- $.collections[15].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_BouletBrothers.T_UI_CollectionBanner_BouletBrothers"
+ $.collections[15].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GuardiansAndShadows.T_UI_CollectionBanner_GuardiansAndShadows"
- $.collections[15].inclusionVersion: "9.0.2"
+ $.collections[15].inclusionVersion: "8.7.0"
- $.collections[15].items[]: "K26_outfit_021"
- $.collections[15].items[]: "BE_outfit_028"
+ $.collections[15].items[]: "KK_outfit_038"
+ $.collections[15].items[]: "OK_outfit_016"
+ $.collections[15].items[]: "S25_outfit_030"
+ $.collections[15].items[]: "S37_outfit_021"
+ $.collections[15].items[]: "HK_outfit_020"
+ $.collections[15].items[]: "SwedenSurvivor_outfit_025"
+ $.collections[15].items[]: "DK_outfit_023"
+ $.collections[15].items[]: "TW_outfit_021"
+ $.collections[15].items[]: "S24_outfit_022"
+ $.collections[15].items[]: "S41_outfit_011"
+ $.collections[15].items[]: "S34_outfit_019"
+ $.collections[15].items[]: "GK_outfit_022"
+ $.collections[15].items[]: "K23_outfit_023"
- $.collections[15].limitedAvailabilityStartDate: "2025-07-08T15:00:00Z"
+ $.collections[15].limitedAvailabilityStartDate: "2025-05-15T15:00:00Z"
- $.collections[15].sortOrder: "-133"
+ $.collections[15].sortOrder: "-135"
- $.collections[15].updatedDate: "2025-05-23T13:06:03.449Z"
+ $.collections[15].updatedDate: "2025-07-21T15:22:15.623Z"
- $.collections[16].additionalImages[0]
- $.collections[16].collectionId: "WaterfrontMassacre"
+ $.collections[16].collectionId: "Rockabilly"
- $.collections[16].collectionTitle.de: "Hafenmassaker"
+ $.collections[16].collectionTitle.de: "Rockabilly"
- $.collections[16].collectionTitle.en: "Waterfront Massacre"
+ $.collections[16].collectionTitle.en: "Rockabilly"
- $.collections[16].collectionTitle.es: "Masacre de la costa"
+ $.collections[16].collectionTitle.es: "Rockabilly"
- $.collections[16].collectionTitle["es-MX"]: "Masacre en la costa"
+ $.collections[16].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[16].collectionTitle.fr: "Massacre au bord de la mer"
+ $.collections[16].collectionTitle.fr: "Rockabilly"
- $.collections[16].collectionTitle.it: "Collezione Massacro sul lungomare"
+ $.collections[16].collectionTitle.it: "Rockabilly"
- $.collections[16].collectionTitle.ja: "水辺の殺戮"
+ $.collections[16].collectionTitle.ja: "ロカビリー "
- $.collections[16].collectionTitle.ko: "해안가 대학살"
+ $.collections[16].collectionTitle.ko: "로커빌리"
- $.collections[16].collectionTitle.pl: "Nadbrzeżna masakra"
+ $.collections[16].collectionTitle.pl: "Rockabilly"
- $.collections[16].collectionTitle["pt-BR"]: "Massacre da Costa"
+ $.collections[16].collectionTitle["pt-BR"]: "Rockabilly"
- $.collections[16].collectionTitle.ru: "Пляжная резня"
+ $.collections[16].collectionTitle.ru: "Рокабилли"
- $.collections[16].collectionTitle.th: "การสังหารหมู่ริมน้ำ"
+ $.collections[16].collectionTitle.th: "ร็อกอะบิลลี่"
- $.collections[16].collectionTitle.tr: "Su Kenarı Katliamı"
+ $.collections[16].collectionTitle.tr: "Rockabilly"
- $.collections[16].collectionTitle["zh-Hans"]: "滨水屠杀"
+ $.collections[16].collectionTitle["zh-Hans"]: "山区摇滚"
- $.collections[16].collectionTitle["zh-Hant"]: "水邊屠殺"
+ $.collections[16].collectionTitle["zh-Hant"]: "鄉村搖滾"
- $.collections[16].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_WaterfrontMassacreXenomorph.T_UI_CollectionBanner_WaterfrontMassacreXenomorph"
+ $.collections[16].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
- $.collections[16].items[]: "CM_outfit_012"
- $.collections[16].items[]: "DK_outfit_014"
- $.collections[16].items[]: "DF_outfit_015"
- $.collections[16].items[]: "FM_outfit_019"
- $.collections[16].items[]: "MS_outfit_008"
- $.collections[16].items[]: "GS_outfit_015"
- $.collections[16].items[]: "NK_outfit_015"
- $.collections[16].items[]: "SwedenSurvivor_outfit_010"
- $.collections[16].items[]: "TC_outfit_009"
- $.collections[16].items[]: "TC_outfit_009_01"
- $.collections[16].items[]: "TR_outfit_010"
- $.collections[16].items[]: "K23_outfit_016"
- $.collections[16].items[]: "KS_outfit_017"
- $.collections[16].items[]: "MT_outfit_024"
- $.collections[16].items[]: "S23_outfit_017"
- $.collections[16].items[]: "S25_outfit_016"
- $.collections[16].items[]: "S28_outfit_012"
- $.collections[16].items[]: "S31_outfit_006"
- $.collections[16].items[]: "S41_outfit_009"
- $.collections[16].items[]: "HS_outfit_023"
- $.collections[16].items[]: "S37_outfit_016"
- $.collections[16].items[]: "K33_outfit_012"
- $.collections[16].items[]: "S46_outfit_009"
- $.collections[16].items[]: "S24_outfit_025"
- $.collections[16].items[]: "AV_outfit_028"
… 3884 more change(s) — see the commit diff for everything
```

### [`consents/eula_psn_eu/v5/en.json`](consents/eula_psn_eu/v5/en.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/en.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
+ $[id=eula_psn_eu].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
```

### [`consents/eula_psn_na/v5/en.json`](consents/eula_psn_na/v5/en.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/en.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
+ $[id=eula_psn_na].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[0].MapsWeight.Apl_Shack: "1200"
- $.schedule[0].MapsWeight.Fin_Hideout: "0"
+ $.schedule[0].MapsWeight.Fin_Hideout: "1000"
```

### [`crossPromoCampaigns.json`](crossPromoCampaigns.json)

[Full line-by-line diff](diffs/crossPromoCampaigns.json.diff)

```diff
- $.Campaigns.CYOC_Popup
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.Lasagna
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "a7a641e983d0a73a05f9cf7c36abc38aaadf91d0"
+ $.entries[0].contentVersion: "f15472ee9d269e11f8ab5991a6e5d5d5b3d685e8"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_TombRaider_2.T_UI_SpecialPack_TombRaider_2"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TheWitcherBundle.T_UI_SpecialPack_TheWitcherBundle"
- $.entries[0].uri: "images/T_UI_SpecialPack_TombRaider_2.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_TheWitcherBundle.png"
- $.entries[1].contentVersion: "134f970ea383b09ad301321d2a6be91363299df5"
+ $.entries[1].contentVersion: "50bce6cb7ae6795b14f8cc3e33991c49dfdc6826"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_Rift2.T_UI_SpecialPack_Rift2"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_FiveNightsAtFreddys.T_UI_ChapterBundle_FiveNightsAtFreddys"
- $.entries[1].uri: "images/T_UI_SpecialPack_Rift2.png"
+ $.entries[1].uri: "images/T_UI_ChapterBundle_FiveNightsAtFreddys.png"
- $.entries[2].contentVersion: "c17a8e93352b290e8a7563e8cba7dca49a0becb9"
+ $.entries[2].contentVersion: "e5c398c4d42d1dc9b538dd7ce651ca2cab38bd87"
- $.entries[2].enableChecksum: true
+ $.entries[2].enableChecksum: false
- $.entries[2].packagedPath: ""
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_WaterfrontMassacreXenomorph.T_UI_CollectionBanner_WaterfrontMassacreXenomorph"
- $.entries[2].schema: "s3ver://"
+ $.entries[2].schema: "s3verbin://"
- $.entries[2].uri: "catalog.json"
+ $.entries[2].uri: "images/T_UI_CollectionBanner_WaterfrontMassacreXenomorph.png"
- $.entries[3].contentVersion: "c475d13427ca9ac7bb1fe0994050cb768fdbfd93"
+ $.entries[3].contentVersion: "25ff6fc37e10dad46ab67f052faa5b7ea64b00de"
- $.entries[3].enableChecksum: true
+ $.entries[3].enableChecksum: false
- $.entries[3].packagedPath: ""
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_WaterfrontMassacreXenomorph.T_UI_SpecialPack_WaterfrontMassacreXenomorph"
- $.entries[3].schema: "s3ver://"
+ $.entries[3].schema: "s3verbin://"
- $.entries[3].uri: "bonusPointEventsContent.json"
+ $.entries[3].uri: "images/T_UI_SpecialPack_WaterfrontMassacreXenomorph.png"
- $.entries[4].contentVersion: "e3c874f4ad4f65f0cb153ce7a08e38e8387106a6"
+ $.entries[4].contentVersion: "bb3aaf0683e73f31223ec3354d2275c46ebe7276"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_TwistedMasquerade.T_UI_CollectionBanner_TwistedMasquerade"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "freetoplay/NA/event.json"
+ $.entries[4].uri: "images/T_UI_CollectionBanner_TwistedMasquerade.png"
- $.entries[5].contentVersion: "e3c874f4ad4f65f0cb153ce7a08e38e8387106a6"
+ $.entries[5].contentVersion: "05a1ede9d276bf83d241e70b2a1a64263321fb8e"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_TwistedMasquerade.T_UI_SpecialPack_TwistedMasquerade"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "freetoplay/EU/event.json"
+ $.entries[5].uri: "images/T_UI_SpecialPack_TwistedMasquerade.png"
- $.entries[6].contentVersion: "54a6fb6f7db6e7a5193a5fc1491e28ba0e3ac8b3"
+ $.entries[6].contentVersion: "2e79221d369501f1b160482045957fbffc1e7a77"
- $.entries[6].downloadStrategy: "preferRemote"
+ $.entries[6].downloadStrategy: "preferPackaged"
- $.entries[6].enableChecksum: true
+ $.entries[6].enableChecksum: false
- $.entries[6].packagedPath: ""
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_FNAF.T_UI_CollectionBanner_FNAF"
- $.entries[6].schema: "s3ver://"
+ $.entries[6].schema: "s3verbin://"
- $.entries[6].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[6].uri: "images/T_UI_CollectionBanner_FNAF.png"
- $.entries[7].contentVersion: "537abb3ccab895a11dd5ef37a30d156a287c8e1e"
+ $.entries[7].contentVersion: "7de10c5e7961a12c8616a769b69d684ae8aa47ef"
- $.entries[7].downloadStrategy: "preferRemote"
+ $.entries[7].downloadStrategy: "preferPackaged"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_FNAF.T_UI_SpecialPack_FNAF"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[7].uri: "images/T_UI_SpecialPack_FNAF.png"
- $.entries[8].contentVersion: "b4019d1b83d72ed4f20a5156ea98f7be7a9d21dc"
+ $.entries[8].contentVersion: "27bef8e6b4d9790b517bc50eea284c64e7a73d55"
- $.entries[8].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[8].uri: "catalog.json"
- $.entries[9].contentVersion: "f41993733b4c0c89a46cbade4a472521c5092700"
+ $.entries[9].contentVersion: "ee119afb003a3abe4599e4b70a42a6563365b9b3"
- $.entries[9].uri: "archiveQuests/CalamariV1.json"
+ $.entries[9].uri: "bonusPointEventsContent.json"
- $.entries[10].contentVersion: "a24ecfecdda9fa43f7c5dea98b366bc5157416bf"
+ $.entries[10].contentVersion: "bbbc0d307d57d2edad6c97731f4dcd5385d4a64b"
- $.entries[10].uri: "archiveQuests/CalamariV2.json"
+ $.entries[10].uri: "freetoplay/NA/event.json"
- $.entries[11].contentVersion: "2c7ddedd07c3a44d21bea6ca62ebc504a12621d3"
+ $.entries[11].contentVersion: "bbbc0d307d57d2edad6c97731f4dcd5385d4a64b"
- $.entries[11].uri: "archiveQuests/CalamariV3.json"
+ $.entries[11].uri: "freetoplay/EU/event.json"
- $.entries[12].contentVersion: "d1d5340fc8a820caed56ec611500c08d99f38acd"
+ $.entries[12].contentVersion: "3d79e5d3c0f38ac103d12f8a7216990f76887235"
- $.entries[12].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2022.json"
- $.entries[13].contentVersion: "2b96f3a2ae57ee78d0def7af79c810973286530a"
+ $.entries[13].contentVersion: "5fc2e74b6547cad57aaa22fa61e18f24b1c6659d"
- $.entries[13].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[13].uri: "archiveQuests/Anniversary2023.json"
- $.entries[14].contentVersion: "d04e87c85214d3edeefdff180146ed61b573a31c"
+ $.entries[14].contentVersion: "baac2c534846886f85a06f6e53c1900d9e2147c8"
- $.entries[14].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[14].uri: "archiveQuests/Anniversary2024.json"
- $.entries[15].contentVersion: "b1fff5078efba95251760ff4d01e4b763a8faa31"
+ $.entries[15].contentVersion: "ea1176851d28dda829d7a3483fdd65ee2f96252d"
- $.entries[15].uri: "archiveQuests/FireflyV1.json"
+ $.entries[15].uri: "archiveQuests/CalamariV1.json"
- $.entries[16].contentVersion: "e611a950479b638f9a8b7d5b5ecab5a486b988c3"
+ $.entries[16].contentVersion: "a8701575be23d4eb00f57821e65b55126651c39c"
- $.entries[16].uri: "archiveQuests/Halloween2021.json"
+ $.entries[16].uri: "archiveQuests/CalamariV2.json"
- $.entries[17].contentVersion: "c3787a0c95065b801e16630dba1a2ae1cbc77ae4"
+ $.entries[17].contentVersion: "fcc9d38ca8076c713715bdc3df7450093f99efa0"
- $.entries[17].uri: "archiveQuests/Halloween2022.json"
+ $.entries[17].uri: "archiveQuests/CalamariV3.json"
- $.entries[18].contentVersion: "6a78a8c42dd3f0c3c68c4d2a44c57bebc57f22bd"
+ $.entries[18].contentVersion: "0b3b85c9a115171243104b58cc30d455f193604b"
- $.entries[18].uri: "archiveQuests/Halloween2023.json"
+ $.entries[18].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[19].contentVersion: "f3b1d3c4ff239118287ffcc420c8b85ae4279ca5"
+ $.entries[19].contentVersion: "7f656c9cc903be74c6ada4c5a7d76d54dff6f6a3"
- $.entries[19].uri: "archiveQuests/Halloween2024.json"
+ $.entries[19].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[20].contentVersion: "a6136fbeb645d10c481385c4cbf7d860c9023d01"
+ $.entries[20].contentVersion: "78a5dae70495a089228cca71b5680813c39a760d"
- $.entries[20].uri: "archiveQuests/Spring2024.json"
+ $.entries[20].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[21].contentVersion: "a7fed0b82c2348272fe98b20bcb8e17a3567e7fa"
+ $.entries[21].contentVersion: "f4bee6e3aac4fd6ff1018d424e5767e03b13d2e9"
- $.entries[21].uri: "archiveQuests/Spring2025.json"
+ $.entries[21].uri: "archiveQuests/FireflyV1.json"
- $.entries[22].contentVersion: "eeb8348e1be2920c1e29f949c25e34d9c15740db"
+ $.entries[22].contentVersion: "d0beaab94a8b37c6f7ac7f9cb889f7ab09421eae"
- $.entries[22].uri: "archiveQuests/Summer2023.json"
+ $.entries[22].uri: "archiveQuests/Halloween2021.json"
- $.entries[23].contentVersion: "d15028be84670cfb719fb5b099b951e308cf20f1"
+ $.entries[23].contentVersion: "4ec20a78dde46c90f18875489757d6c3daf5bc3a"
- $.entries[23].uri: "archiveQuests/Tome01.json"
+ $.entries[23].uri: "archiveQuests/Halloween2022.json"
- $.entries[24].contentVersion: "bf0139eb9531d2e3d00ea6e07bb1003f057bfe6c"
+ $.entries[24].contentVersion: "f1d5d934cc04c244c0229983dd79b67fc4c55beb"
- $.entries[24].uri: "archiveQuests/Tome02.json"
+ $.entries[24].uri: "archiveQuests/Halloween2023.json"
- $.entries[25].contentVersion: "a260bcb87fc5d8b464d2d42dd15232c345e8b8f2"
+ $.entries[25].contentVersion: "93bc73c450b3a5a6fd460fa190eb5bbfff78bce5"
- $.entries[25].uri: "archiveQuests/Tome03.json"
+ $.entries[25].uri: "archiveQuests/Halloween2024.json"
- $.entries[26].contentVersion: "7fbbdafda211506c75afcb15965da6dda50232b2"
+ $.entries[26].contentVersion: "a5e96d81cf9d60a62929e46bccad53702e589a77"
- $.entries[26].uri: "archiveQuests/Tome04.json"
+ $.entries[26].uri: "archiveQuests/Spring2024.json"
- $.entries[27].contentVersion: "9cd36618bb6119e63181a4b851ed934d4e600d1e"
+ $.entries[27].contentVersion: "acd27f87e9da430c2425ef37d7fe8012e038e88e"
- $.entries[27].uri: "archiveQuests/Tome05.json"
+ $.entries[27].uri: "archiveQuests/Spring2025.json"
- $.entries[28].contentVersion: "a7e45ab5132432cc0595b807a01914fd49c39b83"
+ $.entries[28].contentVersion: "a243d259c3909a0d195ac55823368c39272c1d82"
- $.entries[28].uri: "archiveQuests/Tome06.json"
+ $.entries[28].uri: "archiveQuests/Summer2023.json"
- $.entries[29].contentVersion: "abc9d7db57e548fff91873a35670167c362eade5"
+ $.entries[29].contentVersion: "4778974a5941f12c14a933f31bc0cb2a24fb972e"
- $.entries[29].uri: "archiveQuests/Tome07.json"
+ $.entries[29].uri: "archiveQuests/Tome01.json"
- $.entries[30].contentVersion: "5f01effe1ee9ac1bfa8f854100ab058f6f119748"
+ $.entries[30].contentVersion: "4cbff6c453c8bd64e47f94c926b94abd92e8cace"
- $.entries[30].uri: "archiveQuests/Tome08.json"
+ $.entries[30].uri: "archiveQuests/Tome02.json"
- $.entries[31].contentVersion: "ad08e7cc6c9adb507a7cf6f15ebdcbfbc5bad509"
+ $.entries[31].contentVersion: "5036305610c36c2e019a43e26de48f2ec452c42a"
- $.entries[31].uri: "archiveQuests/Tome09.json"
+ $.entries[31].uri: "archiveQuests/Tome03.json"
- $.entries[32].contentVersion: "306dc21e63c26db58dbcef0eef13fba1daeaf1f4"
+ $.entries[32].contentVersion: "5220ef03719ae476e386fcca63fd1ee11ed3b9c7"
- $.entries[32].uri: "archiveQuests/Tome10.json"
+ $.entries[32].uri: "archiveQuests/Tome04.json"
- $.entries[33].contentVersion: "eb8bb09118d59efe45d058301d607217ebe2fdf0"
+ $.entries[33].contentVersion: "81e204ca4e3e7a08c4aba509a300d049e1bbf05e"
- $.entries[33].uri: "archiveQuests/Tome11.json"
+ $.entries[33].uri: "archiveQuests/Tome05.json"
- $.entries[34].contentVersion: "48b511e5eb13db408fba4469bdcc0b7b36f0035a"
+ $.entries[34].contentVersion: "aab27337a175139675c6593640404462e0fb026a"
- $.entries[34].uri: "archiveQuests/Tome12.json"
+ $.entries[34].uri: "archiveQuests/Tome06.json"
- $.entries[35].contentVersion: "d08b4a4a433004477c0ccedab50ee894378f5aa6"
+ $.entries[35].contentVersion: "d565bb24eee4033846f9c7b44e3fa79c65f22184"
- $.entries[35].uri: "archiveQuests/Tome13.json"
+ $.entries[35].uri: "archiveQuests/Tome07.json"
- $.entries[36].contentVersion: "9221f599d6ea5c41b3ac36741e27c381a235d3dc"
+ $.entries[36].contentVersion: "9a70cb6fdf8a2754a30d80b58f3a258a3a3dfbcd"
- $.entries[36].uri: "archiveQuests/Tome14.json"
+ $.entries[36].uri: "archiveQuests/Tome08.json"
- $.entries[37].contentVersion: "efdc58c553f5bb2ef84461235f67d705e246527a"
+ $.entries[37].contentVersion: "462b3ea0ac866fd453deaf359362b53887993fe8"
- $.entries[37].uri: "archiveQuests/Tome15.json"
+ $.entries[37].uri: "archiveQuests/Tome09.json"
- $.entries[38].contentVersion: "49dd15dc923a7c2b067d8d3dbdf85943749f1bab"
+ $.entries[38].contentVersion: "14f908e42c1515cdc605804fd964cb91748c4f09"
- $.entries[38].uri: "archiveQuests/Tome16.json"
+ $.entries[38].uri: "archiveQuests/Tome10.json"
… 722 more change(s) — see the commit diff for everything
```

### [`gameplayTunables.json`](gameplayTunables.json)

[Full line-by-line diff](diffs/gameplayTunables.json.diff)

```diff
+ $.tunables
+ $.data["f:/Game/Data/BehaviourDetection/Tunables/GoingNextTunableDB.GoingNextTunableDB:requiredemblempoints"]: 0.0
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
- $.disabledItems.Jigsawpiece
```

### [`prestige/prestige.json`](prestige/prestige.json)

[Full line-by-line diff](diffs/prestige/prestige.json.diff)

```diff
- $.rewards.S47
- $.rewards.S48
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Lasagna]
- $.featuredCard[id=KetchupW4].entries[0].entryId: "BouletBrothers"
+ $.featuredCard[id=KetchupW4].entries[0].entryId: "Boulet_Brothers_Bundle"
- $.featuredCard[id=KetchupW4].entries[0].type: "Collection"
+ $.featuredCard[id=KetchupW4].entries[0].type: "SpecialPack"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[0]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[1]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[2]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[3]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[4]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[5]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[6]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[7]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[8]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[9]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[10]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[11]
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[12]
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "47"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "268435495"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S48_MichonneGrimes_Portrait.S48_MichonneGrimes_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Ketchup/K40_TheAnimatronic_Portrait.K40_TheAnimatronic_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "46"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "45"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S47_RickGrimes_Portrait.S47_RickGrimes_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "268435495"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "268435494"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Ketchup/K40_TheAnimatronic_Portrait.K40_TheAnimatronic_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "45"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "268435493"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "268435494"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "44"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "268435493"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "268435492"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].characterIndex: "44"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].characterIndex: "43"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/S44_TrevorBelmont_Portrait.S44_TrevorBelmont_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[7]
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[8]
- $.featuredCustomizationRecommendations[id=GelatoW5]
- $.featuredCustomizationRecommendations[id=GelatoW6]
- $.featuredCustomizationRecommendations[id=GelatoW6_2]
- $.featuredCustomizationRecommendations[id=GelatoW7]
- $.featuredCustomizationRecommendations[id=GelatoW8]
- $.featuredCustomizationRecommendations[id=GelatoW9]
- $.featuredCustomizationRecommendations[id=LasagnaW1]
- $.featuredCustomizationRecommendations[id=LasagnaW2]
- $.featuredCustomizationRecommendations[id=GelatoW4].activeTo: "2024-12-17T16:00:00"
+ $.featuredCustomizationRecommendations[id=GelatoW4].activeTo: "2025-01-07T16:00:00"
- $.specialsRecommendations[id=Anniversary]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[53]
- $.specialEventsData[15].eventId: "ChocolateBoxKetchup"
+ $.specialEventsData[15].eventId: "ChocolateBoxV1"
- $.specialEventsData[16].eventId: "ChocolateBoxV1"
+ $.specialEventsData[16].eventId: "DreadByDaylightZodiac"
- $.specialEventsData[16].lteData.affectsMMR: true
+ $.specialEventsData[16].lteData.affectsMMR: false
- $.specialEventsData[16].lteData.gameModeQueue: "ChocolateBox"
+ $.specialEventsData[16].lteData.gameModeQueue: "DreadByDaylight"
- $.specialEventsData[16].lteData.gameType: "ChocolateBox"
+ $.specialEventsData[16].lteData.gameType: "DreadByDaylight"
- $.specialEventsData[17].eventId: "DreadByDaylightZodiac"
+ $.specialEventsData[17].eventId: "FireflyV1"
- $.specialEventsData[17].lteData.gameModeQueue: "DreadByDaylight"
+ $.specialEventsData[17].lteData.gameModeQueue: "Firefly"
- $.specialEventsData[17].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[17].lteData.gameType: "Firefly"
- $.specialEventsData[18].lteData
- $.specialEventsData[18].eventId: "FireflyV1"
+ $.specialEventsData[18].eventId: "Halloween2022"
+ $.specialEventsData[18].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[19].eventId: "Halloween2022"
+ $.specialEventsData[19].eventId: "Halloween2023"
+ $.specialEventsData[19].milestoneRewards[0]
+ $.specialEventsData[19].milestoneRewards[1]
+ $.specialEventsData[19].milestoneRewards[2]
- $.specialEventsData[19].ownerRewards[id=Halloween2022Reward]
+ $.specialEventsData[20].lteData
- $.specialEventsData[20].eventId: "Halloween2023"
+ $.specialEventsData[20].eventId: "Halloween2024"
+ $.specialEventsData[20].eventPeriods[id=Halloween2024]
- $.specialEventsData[20].milestoneRewards[0].rewards[id=XR_037]
+ $.specialEventsData[20].milestoneRewards[0].rewards[id=FU_012]
- $.specialEventsData[20].milestoneRewards[1].rewards[id=MT_Head027]
+ $.specialEventsData[20].milestoneRewards[1].rewards[id=FU_BDG_18]
- $.specialEventsData[20].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[20].milestoneRewards[2].pointsCost: 20
- $.specialEventsData[20].milestoneRewards[2].rewards[id=K30_Head011]
+ $.specialEventsData[20].milestoneRewards[2].rewards[id=FU_BNR_12]
- $.specialEventsData[21].lteData
- $.specialEventsData[21].eventId: "Halloween2024"
+ $.specialEventsData[21].eventId: "Lunar2022"
- $.specialEventsData[21].eventPeriods[id=Halloween2024]
- $.specialEventsData[21].milestoneRewards[0]
- $.specialEventsData[21].milestoneRewards[1]
- $.specialEventsData[21].milestoneRewards[2]
+ $.specialEventsData[21].miscRewards[id=killerStaticReward]
+ $.specialEventsData[21].ownerRewards[id=Lunar2022Reward]
+ $.specialEventsData[21].scoreEventRewards[0]
+ $.specialEventsData[21].scoreEventRewards[1]
+ $.specialEventsData[21].scoreEventRewards[2]
+ $.specialEventsData[21].scoreEventRewards[3]
+ $.specialEventsData[21].scoreEventRewards[4]
+ $.specialEventsData[21].scoreEventRewards[5]
+ $.specialEventsData[21].scoreEventRewards[6]
+ $.specialEventsData[21].scoreEventRewards[7]
- $.specialEventsData[22].eventId: "Lunar2022"
+ $.specialEventsData[22].eventId: "Lunar2023"
- $.specialEventsData[22].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 4000
+ $.specialEventsData[22].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 5000
- $.specialEventsData[22].ownerRewards[id=Lunar2022Reward]
+ $.specialEventsData[22].ownerRewards[id=Lunar2023Reward]
- $.specialEventsData[22].scoreEventRewards[2].weight: 20
+ $.specialEventsData[22].scoreEventRewards[2].weight: 15
- $.specialEventsData[22].scoreEventRewards[3].weight: 20
+ $.specialEventsData[22].scoreEventRewards[3].weight: 25
- $.specialEventsData[22].scoreEventRewards[5].weight: 15
+ $.specialEventsData[22].scoreEventRewards[5].weight: 20
- $.specialEventsData[22].scoreEventRewards[6].weight: 8
+ $.specialEventsData[22].scoreEventRewards[6].weight: 10
- $.specialEventsData[22].scoreEventRewards[7].weight: 2
+ $.specialEventsData[22].scoreEventRewards[7].weight: 5
+ $.specialEventsData[23].lteData
- $.specialEventsData[23].eventId: "Lunar2023"
+ $.specialEventsData[23].eventId: "MapShowcaseKetchup"
- $.specialEventsData[23].miscRewards[id=killerStaticReward]
- $.specialEventsData[23].ownerRewards[id=Lunar2023Reward]
- $.specialEventsData[23].scoreEventRewards[0]
- $.specialEventsData[23].scoreEventRewards[1]
- $.specialEventsData[23].scoreEventRewards[2]
- $.specialEventsData[23].scoreEventRewards[3]
- $.specialEventsData[23].scoreEventRewards[4]
- $.specialEventsData[23].scoreEventRewards[5]
- $.specialEventsData[23].scoreEventRewards[6]
- $.specialEventsData[23].scoreEventRewards[7]
- $.specialEventsData[24].lteData
- $.specialEventsData[24].eventId: "MapShowcaseKetchup"
+ $.specialEventsData[24].eventId: "Spring2024"
+ $.specialEventsData[24].eventTrackerObjectives[id=main]
+ $.specialEventsData[25].lteData
- $.specialEventsData[25].eventId: "Spring2024"
+ $.specialEventsData[25].eventId: "Spring2025"
- $.specialEventsData[25].eventTrackerObjectives[id=main].questEventId: "QuestEvent.SpringEventPlaceZone"
- $.specialEventsData[25].eventTrackerObjectives[id=main].questEventParams: "instigator:me"
+ $.specialEventsData[25].eventTrackerObjectives[id=main].additionalEventIdsWithMilestoneBonus
+ $.specialEventsData[25].eventTrackerObjectives[id=main].questEventConditions
+ $.specialEventsData[25].eventTrackerObjectives[id=main].questEvents
- $.specialEventsData[25].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 10
+ $.specialEventsData[25].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 16
- $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.0
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
- $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 2.0
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
- $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[1].neededProgression: 7000000
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
- $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 3.0
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
- $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[2].neededProgression: 20000000
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
- $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 4.0
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
- $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[3].neededProgression: 35000000
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[4]
+ $.specialEventsData[25].eventTrackerObjectives[id=main].milestones[5]
+ $.specialEventsData[25].milestoneRewards[0]
+ $.specialEventsData[25].milestoneRewards[1]
+ $.specialEventsData[25].milestoneRewards[2]
- $.specialEventsData[26].lteData
- $.specialEventsData[26].eventId: "Spring2025"
+ $.specialEventsData[26].eventId: "Winter2023"
- $.specialEventsData[26].eventTrackerObjectives[id=main]
- $.specialEventsData[26].milestoneRewards[0].rewards[id=IC_001]
+ $.specialEventsData[26].milestoneRewards[0].rewards[id=YE_005]
- $.specialEventsData[26].milestoneRewards[1].pointsCost: 8
+ $.specialEventsData[26].milestoneRewards[1].pointsCost: 6
- $.specialEventsData[26].milestoneRewards[1].rewards[id=IC_BDG_03]
+ $.specialEventsData[26].milestoneRewards[1].rewards[id=YE_BDG_01]
- $.specialEventsData[26].milestoneRewards[2].pointsCost: 15
+ $.specialEventsData[26].milestoneRewards[2].pointsCost: 9
- $.specialEventsData[26].milestoneRewards[2].rewards[id=IC_BNR_03]
+ $.specialEventsData[26].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[26].milestoneRewards[3]
+ $.specialEventsData[26].milestoneRewards[4]
+ $.specialEventsData[27].lteData
- $.specialEventsData[27].eventId: "Winter2023"
+ $.specialEventsData[27].eventId: "Winter2024"
+ $.specialEventsData[27].eventPeriods[id=Winter2024]
- $.specialEventsData[27].milestoneRewards[0].pointsCost: 3
+ $.specialEventsData[27].milestoneRewards[0].pointsCost: 6
- $.specialEventsData[27].milestoneRewards[0].rewards[id=YE_005]
+ $.specialEventsData[27].milestoneRewards[0].rewards[id=GEL_001]
- $.specialEventsData[27].milestoneRewards[1].pointsCost: 6
+ $.specialEventsData[27].milestoneRewards[1].pointsCost: 12
- $.specialEventsData[27].milestoneRewards[1].rewards[id=YE_BDG_01]
+ $.specialEventsData[27].milestoneRewards[1].rewards[id=GE_BDG_08]
- $.specialEventsData[27].milestoneRewards[2].pointsCost: 9
+ $.specialEventsData[27].milestoneRewards[2].pointsCost: 21
- $.specialEventsData[27].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[27].milestoneRewards[2].rewards[id=GE_BNR_07]
- $.specialEventsData[27].milestoneRewards[3]
- $.specialEventsData[27].milestoneRewards[4]
- $.specialEventsData[28]
```

## Could not download

- `images/T_UI_ChapterBundle_FiveNightsAtFreddys.png (HTTP 404)`
- `images/T_UI_CollectionBanner_FNAF.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TwistedMasquerade.png (HTTP 404)`
- `images/T_UI_CollectionBanner_WaterfrontMassacreXenomorph.png (HTTP 404)`
- `images/T_UI_SpecialPack_FNAF.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_TwistedMasquerade.png (HTTP 404)`
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

