# live · 9.2.0_2763512live

| | |
|---|---|
| Build date | 2025-09-22 18:53 UTC |
| CDN version | `9.2.0_2763512live-1758567211` |
| Key | `9.2.0_live` |
| Compared with | [9.1.3_2762077live](../9.1.3_2762077live/CHANGES.md) (2025-09-22 16:17 UTC) |

## Summary

**3** added · **32** modified · **4** removed · 170 unchanged

## Added files

- [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)
- [`collectionsCampaigns.json`](collectionsCampaigns.json)
- [`sharedConfigs.json`](sharedConfigs.json)

## Removed files

- `images/T_UI_CollectionBanner_PartyHard.png`
- `images/T_UI_SpecialPack_PartyHard.png`
- `images/T_UI_SpecialPack_Tome5.png`
- `images/T_UI_SpecialPack_Tome6.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.communityChallengeRefreshSeconds: 1800.0
+ $.analytics.EnableAnalyticErrorIncludesRuleIds: false
+ $.analytics.EnableAnalyticFailureBlockIIS: false
+ $.analytics.detailedScoreTypeBlacklist[]: "GameEvent.KillerAbility.CurseAbility.Survivor.Modified"
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
+ $.TOME23
```

### [`archiveQuests/Tome07.json`](archiveQuests/Tome07.json)

[Full line-by-line diff](diffs/archiveQuests/Tome07.json.diff)

```diff
- $.Tome07.level[3].nodes.node_T7L4_08.objectives.EscapeWithItemUltraRare
+ $.Tome07.level[3].nodes.node_T7L4_08.objectives.EscapeWithItemVeryRare
- $.Tome07.level[3].nodes.node_T7L4_Glyph01.objectives.BlueGlyphEscape.specialBehaviours[id=BlueGlyph]
+ $.Tome07.level[3].nodes.node_T7L4_Glyph01.objectives.BlueGlyphEscape.specialBehaviours[id=RedGlyph]
```

### [`archiveQuests/Tome08.json`](archiveQuests/Tome08.json)

[Full line-by-line diff](diffs/archiveQuests/Tome08.json.diff)

```diff
- $.Tome08.level[3].nodes.node_T8L4_15.objectives.EscapeWithItemUltraRareAsCharacterInTrial
+ $.Tome08.level[3].nodes.node_T8L4_15.objectives.VeryRare
```

### [`archiveQuests/Tome19.json`](archiveQuests/Tome19.json)

[Full line-by-line diff](diffs/archiveQuests/Tome19.json.diff)

```diff
- $.Tome19.level[2].nodes.node_T19_L3_01.clientInfoId: "ExtendItemChargesWithStreetwiseAsS05InTrial"
+ $.Tome19.level[2].nodes.node_T19_L3_01.clientInfoId: "PlayWithPerkSurvivor"
- $.Tome19.level[2].nodes.node_T19_L3_01.objectives.ExtendItemChargesWithPerkAsCharacterInTrial
+ $.Tome19.level[2].nodes.node_T19_L3_01.objectives.PlayWithPerkInTrial
```

### [`bloodwebGenerationRules.json`](bloodwebGenerationRules.json)

[Full line-by-line diff](diffs/bloodwebGenerationRules.json.diff)

```diff
- $.BulkCost[2].CostList[0].Value[]: 12500
- $.BulkCost[2].CostList[0].Value[]: 17000
- $.BulkCost[2].CostList[0].Value[]: 21500
- $.BulkCost[2].CostList[0].Value[]: 24750
- $.BulkCost[2].CostList[0].Value[]: 26250
- $.BulkCost[2].CostList[0].Value[]: 26750
+ $.BulkCost[2].CostList[0].Value[]: 18500
+ $.BulkCost[2].CostList[0].Value[]: 19750
+ $.BulkCost[2].CostList[0].Value[]: 13250
+ $.BulkCost[2].CostList[0].Value[]: 19000
+ $.BulkCost[2].CostList[0].Value[]: 27500
+ $.BulkCost[2].CostList[0].Value[]: 25500
+ $.BulkCost[2].CostList[0].Value[]: 28250
+ $.BulkCost[2].CostList[0].Value[]: 36000
- $.BulkCost[2].CostList[1].Value[]: 24750
- $.BulkCost[2].CostList[1].Value[]: 26250
- $.BulkCost[2].CostList[1].Value[]: 32750
+ $.BulkCost[2].CostList[1].Value[]: 18500
+ $.BulkCost[2].CostList[1].Value[]: 19750
+ $.BulkCost[2].CostList[1].Value[]: 13250
+ $.BulkCost[2].CostList[1].Value[]: 23500
+ $.BulkCost[2].CostList[1].Value[]: 19000
+ $.BulkCost[2].CostList[1].Value[]: 25500
+ $.BulkCost[2].CostList[1].Value[]: 28250
+ $.BulkCost[2].CostList[1].Value[]: 31500
+ $.BulkCost[2].CostList[1].Value[]: 34750
+ $.BulkCost[2].CostList[1].Value[]: 36000
- $.BulkCost[2].CostList[2].Value[]: 12500
- $.BulkCost[2].CostList[2].Value[]: 17000
- $.BulkCost[2].CostList[2].Value[]: 24750
- $.BulkCost[2].CostList[2].Value[]: 26250
- $.BulkCost[2].CostList[2].Value[]: 28750
- $.BulkCost[2].CostList[2].Value[]: 32750
+ $.BulkCost[2].CostList[2].Value[]: 14000
+ $.BulkCost[2].CostList[2].Value[]: 18500
+ $.BulkCost[2].CostList[2].Value[]: 19750
+ $.BulkCost[2].CostList[2].Value[]: 13250
+ $.BulkCost[2].CostList[2].Value[]: 23500
+ $.BulkCost[2].CostList[2].Value[]: 19000
+ $.BulkCost[2].CostList[2].Value[]: 25500
+ $.BulkCost[2].CostList[2].Value[]: 28250
+ $.BulkCost[2].CostList[2].Value[]: 29500
+ $.BulkCost[2].CostList[2].Value[]: 34750
+ $.BulkCost[2].CostList[2].Value[]: 36000
- $.BulkCost[2].CostList[3].Value[]: 12500
- $.BulkCost[2].CostList[3].Value[]: 17000
- $.BulkCost[2].CostList[3].Value[]: 24750
- $.BulkCost[2].CostList[3].Value[]: 26250
+ $.BulkCost[2].CostList[3].Value[]: 14000
+ $.BulkCost[2].CostList[3].Value[]: 18500
+ $.BulkCost[2].CostList[3].Value[]: 19750
+ $.BulkCost[2].CostList[3].Value[]: 13250
+ $.BulkCost[2].CostList[3].Value[]: 19000
+ $.BulkCost[2].CostList[3].Value[]: 25500
+ $.BulkCost[2].CostList[3].Value[]: 28250
+ $.BulkCost[2].CostList[3].Value[]: 34750
+ $.BulkCost[2].CostList[3].Value[]: 36000
- $.BulkCost[2].CostList[4].Value[]: 12500
- $.BulkCost[2].CostList[4].Value[]: 21500
- $.BulkCost[2].CostList[4].Value[]: 17000
- $.BulkCost[2].CostList[4].Value[]: 24750
- $.BulkCost[2].CostList[4].Value[]: 26250
+ $.BulkCost[2].CostList[4].Value[]: 14000
+ $.BulkCost[2].CostList[4].Value[]: 18500
+ $.BulkCost[2].CostList[4].Value[]: 19750
+ $.BulkCost[2].CostList[4].Value[]: 13250
+ $.BulkCost[2].CostList[4].Value[]: 19000
+ $.BulkCost[2].CostList[4].Value[]: 25500
+ $.BulkCost[2].CostList[4].Value[]: 28250
+ $.BulkCost[2].CostList[4].Value[]: 34750
+ $.BulkCost[2].CostList[4].Value[]: 36000
- $.BulkCost[2].CostList[5].Value[]: 12500
- $.BulkCost[2].CostList[5].Value[]: 21500
- $.BulkCost[2].CostList[5].Value[]: 17000
- $.BulkCost[2].CostList[5].Value[]: 24750
- $.BulkCost[2].CostList[5].Value[]: 26250
+ $.BulkCost[2].CostList[5].Value[]: 14000
+ $.BulkCost[2].CostList[5].Value[]: 18500
+ $.BulkCost[2].CostList[5].Value[]: 19750
+ $.BulkCost[2].CostList[5].Value[]: 13250
+ $.BulkCost[2].CostList[5].Value[]: 19000
+ $.BulkCost[2].CostList[5].Value[]: 25500
+ $.BulkCost[2].CostList[5].Value[]: 28250
+ $.BulkCost[2].CostList[5].Value[]: 34750
+ $.BulkCost[2].CostList[5].Value[]: 36000
- $.BulkCost[7].CostList[0].Value[]: 12500
- $.BulkCost[7].CostList[0].Value[]: 24750
- $.BulkCost[7].CostList[0].Value[]: 26250
- $.BulkCost[7].CostList[0].Value[]: 34500
+ $.BulkCost[7].CostList[0].Value[]: 18500
+ $.BulkCost[7].CostList[0].Value[]: 19750
+ $.BulkCost[7].CostList[0].Value[]: 13250
+ $.BulkCost[7].CostList[0].Value[]: 23500
+ $.BulkCost[7].CostList[0].Value[]: 19000
+ $.BulkCost[7].CostList[0].Value[]: 25500
+ $.BulkCost[7].CostList[0].Value[]: 28250
+ $.BulkCost[7].CostList[0].Value[]: 36000
- $.BulkCost[7].CostList[1].Value[]: 24750
- $.BulkCost[7].CostList[1].Value[]: 30000
- $.BulkCost[7].CostList[1].Value[]: 26250
- $.BulkCost[7].CostList[1].Value[]: 32750
- $.BulkCost[7].CostList[1].Value[]: 34500
+ $.BulkCost[7].CostList[1].Value[]: 18500
+ $.BulkCost[7].CostList[1].Value[]: 19750
+ $.BulkCost[7].CostList[1].Value[]: 13250
+ $.BulkCost[7].CostList[1].Value[]: 19000
+ $.BulkCost[7].CostList[1].Value[]: 26000
+ $.BulkCost[7].CostList[1].Value[]: 25500
+ $.BulkCost[7].CostList[1].Value[]: 28250
+ $.BulkCost[7].CostList[1].Value[]: 31500
+ $.BulkCost[7].CostList[1].Value[]: 33500
+ $.BulkCost[7].CostList[1].Value[]: 36000
- $.BulkCost[7].CostList[2].Value[]: 12500
- $.BulkCost[7].CostList[2].Value[]: 24750
- $.BulkCost[7].CostList[2].Value[]: 30000
- $.BulkCost[7].CostList[2].Value[]: 26250
- $.BulkCost[7].CostList[2].Value[]: 32750
- $.BulkCost[7].CostList[2].Value[]: 34500
+ $.BulkCost[7].CostList[2].Value[]: 18500
+ $.BulkCost[7].CostList[2].Value[]: 19750
+ $.BulkCost[7].CostList[2].Value[]: 13250
+ $.BulkCost[7].CostList[2].Value[]: 19000
+ $.BulkCost[7].CostList[2].Value[]: 29500
+ $.BulkCost[7].CostList[2].Value[]: 25500
+ $.BulkCost[7].CostList[2].Value[]: 28250
+ $.BulkCost[7].CostList[2].Value[]: 31500
+ $.BulkCost[7].CostList[2].Value[]: 33500
+ $.BulkCost[7].CostList[2].Value[]: 36000
- $.BulkCost[7].CostList[3].Value[]: 12500
- $.BulkCost[7].CostList[3].Value[]: 24750
- $.BulkCost[7].CostList[3].Value[]: 30000
- $.BulkCost[7].CostList[3].Value[]: 26250
- $.BulkCost[7].CostList[3].Value[]: 26750
- $.BulkCost[7].CostList[3].Value[]: 28750
- $.BulkCost[7].CostList[3].Value[]: 32750
- $.BulkCost[7].CostList[3].Value[]: 35250
+ $.BulkCost[7].CostList[3].Value[]: 18500
+ $.BulkCost[7].CostList[3].Value[]: 19750
+ $.BulkCost[7].CostList[3].Value[]: 13250
+ $.BulkCost[7].CostList[3].Value[]: 19000
+ $.BulkCost[7].CostList[3].Value[]: 27500
+ $.BulkCost[7].CostList[3].Value[]: 29500
+ $.BulkCost[7].CostList[3].Value[]: 25500
+ $.BulkCost[7].CostList[3].Value[]: 28250
+ $.BulkCost[7].CostList[3].Value[]: 31500
+ $.BulkCost[7].CostList[3].Value[]: 33500
+ $.BulkCost[7].CostList[3].Value[]: 36000
- $.BulkCost[7].CostList[4].Value[]: 12500
- $.BulkCost[7].CostList[4].Value[]: 24750
- $.BulkCost[7].CostList[4].Value[]: 26250
- $.BulkCost[7].CostList[4].Value[]: 28750
- $.BulkCost[7].CostList[4].Value[]: 32750
- $.BulkCost[7].CostList[4].Value[]: 35250
+ $.BulkCost[7].CostList[4].Value[]: 18500
+ $.BulkCost[7].CostList[4].Value[]: 19750
+ $.BulkCost[7].CostList[4].Value[]: 13250
+ $.BulkCost[7].CostList[4].Value[]: 23500
+ $.BulkCost[7].CostList[4].Value[]: 19000
+ $.BulkCost[7].CostList[4].Value[]: 25500
+ $.BulkCost[7].CostList[4].Value[]: 28250
+ $.BulkCost[7].CostList[4].Value[]: 29500
+ $.BulkCost[7].CostList[4].Value[]: 31500
+ $.BulkCost[7].CostList[4].Value[]: 33500
+ $.BulkCost[7].CostList[4].Value[]: 36000
- $.BulkCost[7].CostList[5].Value[]: 12500
- $.BulkCost[7].CostList[5].Value[]: 24750
- $.BulkCost[7].CostList[5].Value[]: 26250
- $.BulkCost[7].CostList[5].Value[]: 28750
- $.BulkCost[7].CostList[5].Value[]: 32750
- $.BulkCost[7].CostList[5].Value[]: 35250
+ $.BulkCost[7].CostList[5].Value[]: 18500
+ $.BulkCost[7].CostList[5].Value[]: 19750
+ $.BulkCost[7].CostList[5].Value[]: 13250
+ $.BulkCost[7].CostList[5].Value[]: 23500
+ $.BulkCost[7].CostList[5].Value[]: 19000
+ $.BulkCost[7].CostList[5].Value[]: 25500
+ $.BulkCost[7].CostList[5].Value[]: 28250
+ $.BulkCost[7].CostList[5].Value[]: 29500
+ $.BulkCost[7].CostList[5].Value[]: 31500
+ $.BulkCost[7].CostList[5].Value[]: 33500
+ $.BulkCost[7].CostList[5].Value[]: 36000
- $.BulkCost[11].CostList[0].Value[]: 12500
- $.BulkCost[11].CostList[0].Value[]: 24750
- $.BulkCost[11].CostList[0].Value[]: 29500
+ $.BulkCost[11].CostList[0].Value[]: 18500
+ $.BulkCost[11].CostList[0].Value[]: 19750
+ $.BulkCost[11].CostList[0].Value[]: 13250
+ $.BulkCost[11].CostList[0].Value[]: 23500
+ $.BulkCost[11].CostList[0].Value[]: 19000
+ $.BulkCost[11].CostList[0].Value[]: 27500
+ $.BulkCost[11].CostList[0].Value[]: 25500
+ $.BulkCost[11].CostList[0].Value[]: 28250
+ $.BulkCost[11].CostList[0].Value[]: 31500
+ $.BulkCost[11].CostList[0].Value[]: 36000
- $.BulkCost[11].CostList[1].Value[]: 24750
- $.BulkCost[11].CostList[1].Value[]: 32750
+ $.BulkCost[11].CostList[1].Value[]: 18500
+ $.BulkCost[11].CostList[1].Value[]: 19750
+ $.BulkCost[11].CostList[1].Value[]: 13250
+ $.BulkCost[11].CostList[1].Value[]: 23500
… 60 more change(s) — see the commit diff for everything
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=S49]
+ $[id=K41]
+ $[id=CHALLENGE_REWARD_TIER_Rift_03]
+ $[id=CHALLENGE_BATTLE_PASS_Rift_03]
+ $[id=GS_Head038]
+ $[id=GS_Legs038]
+ $[id=GS_Torso028_03]
+ $[id=GS_Torso038]
+ $[id=K41_Body006]
+ $[id=K41_Body01]
+ $[id=K41_Body01_01]
+ $[id=K41_Body01_02]
+ $[id=K41_Body01_03]
+ $[id=K41_Body01_04]
+ $[id=K41_Body01_CV01]
+ $[id=K41_Body01_CV02]
+ $[id=K41_Body01_CV03]
+ $[id=K41_Body01_CV04]
+ $[id=K41_Body01_P01]
+ $[id=K41_Body02]
+ $[id=K41_Body02_01]
+ $[id=K41_Head006]
+ $[id=K41_Head01]
+ $[id=K41_Head01_01]
+ $[id=K41_Head01_02]
+ $[id=K41_Head01_03]
+ $[id=K41_Head01_CV01]
+ $[id=K41_Head01_CV02]
+ $[id=K41_Head01_CV03]
+ $[id=K41_Head01_CV04]
+ $[id=K41_Head01_P01]
+ $[id=K41_Head02]
+ $[id=K41_Head02_01]
+ $[id=K41_PCharm001]
+ $[id=K41_PCharm002]
+ $[id=K41_PCharm003]
+ $[id=K41_W006]
+ $[id=K41_W01]
+ $[id=K41_W01_01]
+ $[id=K41_W01_02]
+ $[id=K41_W01_03]
+ $[id=K41_W01_P01]
+ $[id=K41_W02]
+ $[id=K41_W02_01]
+ $[id=KK_Body039]
+ $[id=KK_Mask039]
+ $[id=KK_W039]
+ $[id=KS_Torso021_03]
+ $[id=LS_BDG_14]
+ $[id=LS_BNR_12]
+ $[id=LS_BNR_13]
+ $[id=LS_BNR_14]
+ $[id=LS_BNR_15]
+ $[id=MA_001]
+ $[id=MA_002]
+ $[id=MA_BDG_02]
+ $[id=MA_BDG_04]
+ $[id=MA_BDG_05]
+ $[id=MA_BNR_01]
+ $[id=MA_BNR_02]
+ $[id=S25_Torso022_03]
+ $[id=S28_Head032]
+ $[id=S28_Legs032]
+ $[id=S28_Torso032]
+ $[id=S36_Torso015_03]
+ $[id=S46_Head012]
+ $[id=S46_Legs012]
+ $[id=S46_Torso012]
+ $[id=S49_Head006]
+ $[id=S49_Head006_01]
+ $[id=S49_Head01]
+ $[id=S49_Head01_01]
+ $[id=S49_Head01_02]
+ $[id=S49_Head01_03]
+ $[id=S49_Head01_P01]
+ $[id=S49_Head02]
+ $[id=S49_Head02_01]
+ $[id=S49_Legs006]
+ $[id=S49_Legs006_01]
+ $[id=S49_Legs01]
+ $[id=S49_Legs01_01]
+ $[id=S49_Legs01_02]
+ $[id=S49_Legs01_03]
+ $[id=S49_Legs01_CV01]
+ $[id=S49_Legs01_CV02]
+ $[id=S49_Legs01_CV03]
+ $[id=S49_Legs01_CV04]
+ $[id=S49_Legs01_P01]
+ $[id=S49_Legs02]
+ $[id=S49_Legs02_01]
+ $[id=S49_PCharm001]
+ $[id=S49_PCharm002]
+ $[id=S49_PCharm003]
+ $[id=S49_Torso006]
+ $[id=S49_Torso006_01]
+ $[id=S49_Torso01]
+ $[id=S49_Torso01_01]
+ $[id=S49_Torso01_02]
+ $[id=S49_Torso01_03]
+ $[id=S49_Torso01_04]
+ $[id=S49_Torso01_05]
+ $[id=S49_Torso01_CV01]
+ $[id=S49_Torso01_CV02]
+ $[id=S49_Torso01_CV03]
+ $[id=S49_Torso01_CV04]
+ $[id=S49_Torso01_P01]
+ $[id=S49_Torso02]
+ $[id=S49_Torso02_01]
+ $[id=SK_Body023]
+ $[id=SK_Mask023]
+ $[id=SK_W023]
+ $[id=SS_Head030]
+ $[id=SS_Legs030]
+ $[id=SS_Torso030]
+ $[id=GS_outfit_038]
+ $[id=K41_outfit_006]
+ $[id=K41_outfit_01]
+ $[id=K41_outfit_01_01]
+ $[id=K41_outfit_01_02]
+ $[id=K41_outfit_01_03]
+ $[id=K41_outfit_01_CV01]
+ $[id=K41_outfit_01_CV02]
+ $[id=K41_outfit_01_CV03]
+ $[id=K41_outfit_01_CV04]
+ $[id=K41_outfit_01_P01]
+ $[id=K41_outfit_02]
+ $[id=K41_outfit_02_01]
+ $[id=KK_outfit_039]
+ $[id=S28_outfit_032]
+ $[id=S46_outfit_012]
+ $[id=S49_outfit_006]
+ $[id=S49_outfit_006_01]
+ $[id=S49_outfit_01]
+ $[id=S49_outfit_01_01]
+ $[id=S49_outfit_01_02]
+ $[id=S49_outfit_01_03]
+ $[id=S49_outfit_01_CV01]
+ $[id=S49_outfit_01_CV02]
+ $[id=S49_outfit_01_CV03]
+ $[id=S49_outfit_01_CV04]
+ $[id=S49_outfit_01_P01]
+ $[id=S49_outfit_02]
+ $[id=S49_outfit_02_01]
+ $[id=SK_outfit_023]
+ $[id=SS_outfit_030]
+ $[id=Axekick_Bundle]
+ $[id=Fall_Fashion_Bundle]
+ $[id=From_The_Rift_Bundle_250923]
+ $[id=Recurring_Charm_Bundle_250923]
+ $[id=Recurring_Dev_Bundle_250923]
+ $[id=Recurring_Killer_Bundle_250923]
+ $[id=Recurring_Survivor_Bundle_250923]
- $[id=Shape].metaData.characterStartingInventory[itemId=Addon_Stalker_MemorialFlower]
- $[id=Shape].metaData.characterStartingInventory[itemId=Addon_Stalker_ReflectiveFragment]
+ $[id=Shape].metaData.characterStartingInventory[itemId=Addon_Stalker_Jewelry]
+ $[id=Shape].metaData.characterStartingInventory[itemId=Addon_Stalker_HairBow]
+ $[id=AV_Head010_01].metaData.availablePeriods[1]
+ $[id=AV_Legs010_01].metaData.availablePeriods[1]
+ $[id=AV_Torso003_04].metaData.availablePeriods[1]
+ $[id=AV_Torso025].metaData.availablePeriods[1]
+ $[id=BE_W023].metaData.availablePeriods[1]
+ $[id=CM_Head025].metaData.availablePeriods[1]
+ $[id=CM_Legs025].metaData.availablePeriods[1]
+ $[id=CM_Torso008_01].metaData.availablePeriods[1]
+ $[id=CM_Torso025].metaData.availablePeriods[1]
+ $[id=DF_Head005_01].metaData.availablePeriods[1]
+ $[id=DF_Head022].metaData.availablePeriods[1]
+ $[id=DF_Legs006_01].metaData.availablePeriods[1]
+ $[id=DF_Legs022].metaData.availablePeriods[1]
+ $[id=DF_Torso022].metaData.availablePeriods[1]
+ $[id=DF_Torso02_01].metaData.availablePeriods[1]
+ $[id=DK_Torso006_01].metaData.availablePeriods[1]
+ $[id=DO_Body013].metaData.availablePeriods[1]
+ $[id=DO_Head013].metaData.availablePeriods[1]
+ $[id=DO_W013].metaData.availablePeriods[1]
+ $[id=DO_W015].metaData.availablePeriods[1]
+ $[id=FM_Head01_05].metaData.availablePeriods[1]
+ $[id=FM_Head028].metaData.availablePeriods[1]
+ $[id=FM_Legs008_01].metaData.availablePeriods[1]
+ $[id=FM_Legs028].metaData.availablePeriods[1]
+ $[id=FM_Torso014_01].metaData.availablePeriods[1]
+ $[id=FM_Torso01_06].metaData.availablePeriods[1]
+ $[id=FM_Torso028].metaData.availablePeriods[1]
+ $[id=GK_Body02_04].metaData.availablePeriods[1]
+ $[id=GK_Head02_04].metaData.availablePeriods[1]
+ $[id=GK_W013_01].metaData.availablePeriods[1]
+ $[id=GK_W017].metaData.availablePeriods[1]
+ $[id=GS_Head021].metaData.availablePeriods[1]
+ $[id=GS_Legs021].metaData.availablePeriods[1]
+ $[id=GS_Torso018_01].metaData.availablePeriods[1]
+ $[id=GS_Torso021].metaData.availablePeriods[1]
+ $[id=HK_W023].metaData.availablePeriods[1]
- $[id=JE_014].metaData.rarity: "VeryRare"
+ $[id=JE_014].metaData.rarity: "Uncommon"
- $[id=JE_015].metaData.rarity: "VeryRare"
+ $[id=JE_015].metaData.rarity: "Uncommon"
+ $[id=JP_Head021].metaData.availablePeriods[1]
+ $[id=JP_Legs021].metaData.availablePeriods[1]
+ $[id=JP_Torso021].metaData.availablePeriods[1]
+ $[id=K21_W019].metaData.availablePeriods[1]
… 109 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
+ $.locText[374]
+ $.locText[375]
+ $.locText[376]
+ $.locText[377]
+ $.locText[378]
+ $.locText[379]
+ $.locText[380]
+ $.locText[381]
+ $.locText[382]
+ $.locText[383]
+ $.locText[384]
+ $.locText[385]
+ $.locText[386]
+ $.locText[387]
+ $.locText[388]
+ $.locText[389]
+ $.locText[390]
+ $.locText[391]
+ $.locText[392]
+ $.locText[393]
+ $.locText[394]
+ $.locText[395]
+ $.locText[396]
+ $.locText[397]
+ $.locText[398]
+ $.locText[399]
+ $.locText[400]
+ $.locText[401]
+ $.locText[402]
+ $.locText[403]
+ $.locText[404]
+ $.locText[405]
+ $.locText[406]
+ $.locText[407]
+ $.locText[408]
+ $.locText[409]
+ $.locText[410]
+ $.locText[411]
```

### [`challengeRewardTrackers.json`](challengeRewardTrackers.json)

[Full line-by-line diff](diffs/challengeRewardTrackers.json.diff)

```diff
- $.Rift_02.endDate: "2025-10-08T15:00:00"
+ $.Rift_02.endDate: "2025-10-07T15:00:00"
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.CalamariLasagna
+ $.Chapter_37_QuestSet
+ $.DbdDay_2025_Set
- $.Milestone_02_Set.challengeList[0].endDate: "2025-10-08T15:00:00"
+ $.Milestone_02_Set.challengeList[0].endDate: "2025-10-07T15:00:00"
- $.Milestone_02_Set.endDate: "2025-10-08T15:00:00"
+ $.Milestone_02_Set.endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[0].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[0].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[1].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[1].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[2].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[2].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[3].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[3].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[4].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[4].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[5].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[5].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[6].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[6].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[7].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[7].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[8].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[8].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[9].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[9].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.challengeList[10].endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.challengeList[10].endDate: "2025-10-07T15:00:00"
- $.Rift_02_QuestSet.endDate: "2025-10-08T15:00:00"
+ $.Rift_02_QuestSet.endDate: "2025-10-07T15:00:00"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[0].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_IronMaiden.T_UI_SpecialPack_IronMaiden"
+ $.collections[0].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Hotdog/T_UI_SpecialPack_IronMaiden.T_UI_SpecialPack_IronMaiden"
~ $.collections[0].items: order changed
- $.collections[1].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TokyoGhoul.T_UI_SpecialPack_TokyoGhoul"
+ $.collections[1].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/IceCream/T_UI_SpecialPack_TokyoGhoul.T_UI_SpecialPack_TokyoGhoul"
- $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_TokyoGhoul.T_UI_CollectionBanner_TokyoGhoul"
+ $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/IceCream/T_UI_CollectionBanner_TokyoGhoul.T_UI_CollectionBanner_TokyoGhoul"
~ $.collections[1].items: order changed
- $.collections[2].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Bloodmoon.T_UI_SpecialPack_Bloodmoon"
+ $.collections[2].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/IceCream/T_UI_SpecialPack_Bloodmoon.T_UI_SpecialPack_Bloodmoon"
- $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Bloodmoon.T_UI_CollectionBanner_Bloodmoon"
+ $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/IceCream/T_UI_CollectionBanner_Bloodmoon.T_UI_CollectionBanner_Bloodmoon"
~ $.collections[2].items: order changed
- $.collections[3].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Techwear.T_UI_SpecialPack_Techwear"
+ $.collections[3].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/IceCream/T_UI_SpecialPack_Techwear.T_UI_SpecialPack_Techwear"
- $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
+ $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/IceCream/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
~ $.collections[3].items: order changed
- $.collections[4].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_SteadyPulse.T_UI_SpecialPack_SteadyPulse"
+ $.collections[4].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_SteadyPulse.T_UI_SpecialPack_SteadyPulse"
~ $.collections[4].items: order changed
- $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AlienReimagined_BC.T_UI_CollectionBanner_AlienReimagined_BC"
+ $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Fudge/T_UI_CollectionBanner_AlienReimagined_BC.T_UI_CollectionBanner_AlienReimagined_BC"
~ $.collections[5].items: order changed
- $.collections[5].updatedDate: "2025-08-22T12:46:51.285Z"
+ $.collections[5].updatedDate: "2025-08-27T12:51:13.197Z"
~ $.collections[6].items: order changed
- $.collections[7].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Chrysalis_1.T_UI_SpecialPack_Chrysalis_1"
+ $.collections[7].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_Chrysalis_1.T_UI_SpecialPack_Chrysalis_1"
~ $.collections[7].items: order changed
- $.collections[8].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_CatsAndDogs.T_UI_SpecialPack_CatsAndDogs"
+ $.collections[8].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_CatsAndDogs.T_UI_SpecialPack_CatsAndDogs"
- $.collections[8].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_CatsAndDogs_2.T_UI_CollectionBanner_CatsAndDogs_2"
+ $.collections[8].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_CatsAndDogs_2.T_UI_CollectionBanner_CatsAndDogs_2"
~ $.collections[8].items: order changed
- $.collections[9].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TheWitcher.T_UI_SpecialPack_TheWitcher"
+ $.collections[9].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_TheWitcher.T_UI_SpecialPack_TheWitcher"
~ $.collections[9].items: order changed
~ $.collections[10].items: order changed
~ $.collections[11].items: order changed
~ $.collections[12].items: order changed
~ $.collections[13].items: order changed
~ $.collections[14].items: order changed
~ $.collections[15].items: order changed
~ $.collections[16].items: order changed
~ $.collections[17].items: order changed
- $.collections[18].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_GuardiansAndShadows.T_UI_SpecialPack_GuardiansAndShadows"
+ $.collections[18].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_GuardiansAndShadows.T_UI_SpecialPack_GuardiansAndShadows"
~ $.collections[18].items: order changed
~ $.collections[19].items: order changed
~ $.collections[20].items: order changed
~ $.collections[21].items: order changed
~ $.collections[22].items: order changed
- $.collections[23].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Castlevania.T_UI_CollectionBanner_Castlevania"
+ $.collections[23].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Eclair/T_UI_CollectionBanner_Castlevania.T_UI_CollectionBanner_Castlevania"
~ $.collections[23].items: order changed
- $.collections[23].updatedDate: "2025-08-22T19:53:47.138Z"
+ $.collections[23].updatedDate: "2025-08-27T12:53:24.592Z"
~ $.collections[24].items: order changed
- $.collections[24].updatedDate: "2025-08-29T20:35:52.552Z"
+ $.collections[24].updatedDate: "2025-09-02T17:21:44.146Z"
~ $.collections[25].items: order changed
- $.collections[25].updatedDate: "2025-08-29T20:37:46.082Z"
+ $.collections[25].updatedDate: "2025-09-02T17:20:43.888Z"
- $.collections[26].collectionId: "PopSuperstar"
+ $.collections[26].collectionId: "Leatherface"
- $.collections[26].collectionTitle.de: "Superpopstar"
+ $.collections[26].collectionTitle.de: "Leatherface"
- $.collections[26].collectionTitle.en: "Pop Superstar"
+ $.collections[26].collectionTitle.en: "Leatherface"
- $.collections[26].collectionTitle.es: "Superestrella del pop"
+ $.collections[26].collectionTitle.es: "Cara de cuero"
- $.collections[26].collectionTitle["es-MX"]: "Superestrella del pop"
+ $.collections[26].collectionTitle["es-MX"]: "Cara de cuero"
- $.collections[26].collectionTitle.fr: "Superstar de la pop"
+ $.collections[26].collectionTitle.fr: "Leatherface"
- $.collections[26].collectionTitle.it: "Superstar pop"
+ $.collections[26].collectionTitle.it: "Faccia di cuoio"
- $.collections[26].collectionTitle.ja: "ポップスター"
+ $.collections[26].collectionTitle.ja: "レザーフェイス"
- $.collections[26].collectionTitle.ko: "팝 슈퍼스타"
+ $.collections[26].collectionTitle.ko: "가죽 가면"
- $.collections[26].collectionTitle.pl: "Supergwiazda popu"
+ $.collections[26].collectionTitle.pl: "Leatherface"
- $.collections[26].collectionTitle["pt-BR"]: "Estrela Pop"
+ $.collections[26].collectionTitle["pt-BR"]: "Leatherface"
- $.collections[26].collectionTitle.ru: "Поп-суперзвезда"
+ $.collections[26].collectionTitle.ru: "Кожаное Лицо"
- $.collections[26].collectionTitle.th: "ซูเปอร์สตาร์ป็อป"
+ $.collections[26].collectionTitle.th: "หน้ากากหนัง"
- $.collections[26].collectionTitle.tr: "Popçu Süperstar"
+ $.collections[26].collectionTitle.tr: "Deri Surat"
- $.collections[26].collectionTitle["zh-Hans"]: "流行巨星"
+ $.collections[26].collectionTitle["zh-Hans"]: "人皮脸"
- $.collections[26].collectionTitle["zh-Hant"]: "流行巨星"
+ $.collections[26].collectionTitle["zh-Hant"]: "皮臉"
- $.collections[26].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_PopSuperstar.T_UI_CollectionBanner_PopSuperstar"
+ $.collections[26].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Donut/T_UI_CollectionBanner_Leatherface.T_UI_CollectionBanner_Leatherface"
- $.collections[26].inclusionVersion: "7.7.0 PTB"
+ $.collections[26].inclusionVersion: "8.1.0"
- $.collections[26].items[]: "FM_outfit_020"
- $.collections[26].items[]: "GS_outfit_020"
- $.collections[26].items[]: "S25_outfit_013"
- $.collections[26].items[]: "K23_outfit_012"
+ $.collections[26].items[]: "CA_outfit_006"
+ $.collections[26].items[]: "CA_outfit_007"
- $.collections[26].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[26].updatedDate: "2024-06-25T12:13:35Z"
- $.collections[27].collectionId: "Leatherface"
+ $.collections[27].collectionId: "PopSuperstar"
- $.collections[27].collectionTitle.de: "Leatherface"
+ $.collections[27].collectionTitle.de: "Superpopstar"
- $.collections[27].collectionTitle.en: "Leatherface"
+ $.collections[27].collectionTitle.en: "Pop Superstar"
- $.collections[27].collectionTitle.es: "Cara de cuero"
+ $.collections[27].collectionTitle.es: "Superestrella del pop"
- $.collections[27].collectionTitle["es-MX"]: "Cara de cuero"
+ $.collections[27].collectionTitle["es-MX"]: "Superestrella del pop"
- $.collections[27].collectionTitle.fr: "Leatherface"
+ $.collections[27].collectionTitle.fr: "Superstar de la pop"
- $.collections[27].collectionTitle.it: "Faccia di cuoio"
+ $.collections[27].collectionTitle.it: "Superstar pop"
- $.collections[27].collectionTitle.ja: "レザーフェイス"
+ $.collections[27].collectionTitle.ja: "ポップスター"
- $.collections[27].collectionTitle.ko: "가죽 가면"
+ $.collections[27].collectionTitle.ko: "팝 슈퍼스타"
- $.collections[27].collectionTitle.pl: "Leatherface"
+ $.collections[27].collectionTitle.pl: "Supergwiazda popu"
- $.collections[27].collectionTitle["pt-BR"]: "Leatherface"
+ $.collections[27].collectionTitle["pt-BR"]: "Estrela Pop"
- $.collections[27].collectionTitle.ru: "Кожаное Лицо"
+ $.collections[27].collectionTitle.ru: "Поп-суперзвезда"
- $.collections[27].collectionTitle.th: "หน้ากากหนัง"
+ $.collections[27].collectionTitle.th: "ซูเปอร์สตาร์ป็อป"
- $.collections[27].collectionTitle.tr: "Deri Surat"
+ $.collections[27].collectionTitle.tr: "Popçu Süperstar"
- $.collections[27].collectionTitle["zh-Hans"]: "人皮脸"
+ $.collections[27].collectionTitle["zh-Hans"]: "流行巨星"
- $.collections[27].collectionTitle["zh-Hant"]: "皮臉"
+ $.collections[27].collectionTitle["zh-Hant"]: "流行巨星"
- $.collections[27].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Leatherface.T_UI_CollectionBanner_Leatherface"
+ $.collections[27].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_PopSuperstar.T_UI_CollectionBanner_PopSuperstar"
- $.collections[27].inclusionVersion: "8.1.0"
+ $.collections[27].inclusionVersion: "7.7.0 PTB"
- $.collections[27].items[]: "CA_outfit_006"
- $.collections[27].items[]: "CA_outfit_007"
+ $.collections[27].items[]: "FM_outfit_020"
+ $.collections[27].items[]: "GS_outfit_020"
+ $.collections[27].items[]: "K23_outfit_012"
+ $.collections[27].items[]: "S25_outfit_013"
- $.collections[27].updatedDate: "2024-06-25T12:13:35Z"
+ $.collections[27].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[28].additionalImages[0]
- $.collections[28].collectionId: "HookedOnYou"
+ $.collections[28].collectionId: "MapleCollection"
- $.collections[28].collectionTitle.de: "Hooked on You"
+ $.collections[28].collectionTitle.de: "Sinister Grace"
- $.collections[28].collectionTitle.en: "Hooked on You"
+ $.collections[28].collectionTitle.en: "Sinister Grace"
- $.collections[28].collectionTitle.es: "Hooked on You"
+ $.collections[28].collectionTitle.es: "Sinister Grace"
- $.collections[28].collectionTitle["es-MX"]: "Hooked on You"
+ $.collections[28].collectionTitle["es-MX"]: "Sinister Grace"
- $.collections[28].collectionTitle.fr: "Hooked on You"
+ $.collections[28].collectionTitle.fr: "Sinister Grace"
- $.collections[28].collectionTitle.it: "Hooked on You"
+ $.collections[28].collectionTitle.it: "Sinister Grace"
- $.collections[28].collectionTitle.ja: "Hooked on You"
+ $.collections[28].collectionTitle.ja: "Sinister Grace"
- $.collections[28].collectionTitle.ko: "Hooked on You"
+ $.collections[28].collectionTitle.ko: "사악한 품위"
- $.collections[28].collectionTitle.pl: "Hooked On You"
+ $.collections[28].collectionTitle.pl: "Sinister Grace"
- $.collections[28].collectionTitle["pt-BR"]: "Hooked on You"
+ $.collections[28].collectionTitle["pt-BR"]: "Sinister Grace"
- $.collections[28].collectionTitle.ru: "На твоем крючке"
+ $.collections[28].collectionTitle.ru: "Sinister Grace"
- $.collections[28].collectionTitle.th: "Hooked on You"
+ $.collections[28].collectionTitle.th: "ความงามอันอัปมงคล"
- $.collections[28].collectionTitle.tr: "Sana Tutuldum"
+ $.collections[28].collectionTitle.tr: "Sinister Grace"
- $.collections[28].collectionTitle["zh-Hans"]: "心醉魂迷"
+ $.collections[28].collectionTitle["zh-Hans"]: "邪恶恩典"
- $.collections[28].collectionTitle["zh-Hant"]: "《鉤魂迷戀》"
+ $.collections[28].collectionTitle["zh-Hant"]: "邪惡優雅"
- $.collections[28].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_HookedOnYou.T_UI_CollectionBanner_HookedOnYou"
+ $.collections[28].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_SinisterGrace.T_UI_CollectionBanner_SinisterGrace"
- $.collections[28].inclusionVersion: "7.7.0 PTB"
+ $.collections[28].inclusionVersion: "9.2.0 PTB"
- $.collections[28].items[]: "CM_outfit_021"
- $.collections[28].items[]: "DF_outfit_023"
- $.collections[28].items[]: "BE_outfit_017"
- $.collections[28].items[]: "K23_outfit_014"
- $.collections[28].items[]: "HK_outfit_017"
+ $.collections[28].items[]: "GS_Torso028_03"
+ $.collections[28].items[]: "K41_outfit_006"
+ $.collections[28].items[]: "K41_outfit_01_01"
+ $.collections[28].items[]: "K41_outfit_01_02"
+ $.collections[28].items[]: "K41_outfit_01_03"
+ $.collections[28].items[]: "K41_outfit_01_CV01"
… 3525 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[0].FeaturedMap
```

### [`crossPromoCampaigns.json`](crossPromoCampaigns.json)

[Full line-by-line diff](diffs/crossPromoCampaigns.json.diff)

```diff
- $.Campaigns.CYOC_Popup
+ $.Campaigns.ItHasMyFace_Promo
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
+ $.dlcList.Maple
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "88643dee1e6c57bd767605036473e939094fccf9"
+ $.entries[0].contentVersion: "3c953ce75891597f0aadfd71e3dab2d16de12feb"
- $.entries[0].downloadStrategy: "preferRemote"
+ $.entries[0].downloadStrategy: "preferPackaged"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_Tome5.T_UI_SpecialPack_Tome5"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_Specialpack_FallFashion.T_UI_Specialpack_FallFashion"
- $.entries[0].uri: "images/T_UI_SpecialPack_Tome5.png"
+ $.entries[0].uri: "images/T_UI_Specialpack_FallFashion.png"
- $.entries[1].contentVersion: "8a15d416ef70b4c552d109bc091b52cbda5ad932"
+ $.entries[1].contentVersion: "88643dee1e6c57bd767605036473e939094fccf9"
- $.entries[1].downloadStrategy: "preferRemote"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_Tome6.T_UI_SpecialPack_Tome6"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_Tome5.T_UI_SpecialPack_Tome5"
- $.entries[1].uri: "images/T_UI_SpecialPack_Tome6.png"
+ $.entries[1].uri: "images/T_UI_SpecialPack_Tome5.png"
- $.entries[2].contentVersion: "ff437cc262850ea6df4a8ca3c5b64964964f7747"
+ $.entries[2].contentVersion: "8a15d416ef70b4c552d109bc091b52cbda5ad932"
- $.entries[2].downloadStrategy: "preferRemote"
+ $.entries[2].downloadStrategy: "preferPackaged"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_PartyHard.T_UI_CollectionBanner_PartyHard"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_Tome6.T_UI_SpecialPack_Tome6"
- $.entries[2].uri: "images/T_UI_CollectionBanner_PartyHard.png"
+ $.entries[2].uri: "images/T_UI_SpecialPack_Tome6.png"
- $.entries[3].contentVersion: "d16173b36a12e4a4ed82a5fc7650cf5d8a9f8bbf"
+ $.entries[3].contentVersion: "a0e2201ffb426f174ff31dd43e4d3d74661912f0"
- $.entries[3].downloadStrategy: "preferRemote"
+ $.entries[3].downloadStrategy: "preferPackaged"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_PartyHard.T_UI_SpecialPack_PartyHard"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_SinisterGrace.T_UI_ChapterBundle_SinisterGrace"
- $.entries[3].uri: "images/T_UI_SpecialPack_PartyHard.png"
+ $.entries[3].uri: "images/T_UI_ChapterBundle_SinisterGrace.png"
- $.entries[4].contentVersion: "ef944b5a0632219686363eca2b07cb4773434f72"
+ $.entries[4].contentVersion: "3c953ce75891597f0aadfd71e3dab2d16de12feb"
- $.entries[4].downloadStrategy: "preferRemote"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_Specialpack_FallFashion.T_UI_Specialpack_FallFashion"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "catalog.json"
+ $.entries[4].uri: "images/T_UI_Specialpack_FallFashion.png"
- $.entries[5].contentVersion: "b4a6ffed58e6fcffb914939f09b9afa9f3da5268"
+ $.entries[5].contentVersion: "5e907dd9dc410eb9a1ff6bc1973ae825586f6887"
- $.entries[5].downloadStrategy: "preferRemote"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_SinisterGrace.T_UI_CollectionBanner_SinisterGrace"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "bonusPointEventsContent.json"
+ $.entries[5].uri: "images/T_UI_CollectionBanner_SinisterGrace.png"
- $.entries[6].contentVersion: "807c86683510773f5b5540e21c207183cdd154a5"
+ $.entries[6].contentVersion: "fbc8241b92a884ac6d866433ada0f9db766c66bc"
- $.entries[6].downloadStrategy: "preferRemote"
+ $.entries[6].downloadStrategy: "preferPackaged"
- $.entries[6].enableChecksum: true
+ $.entries[6].enableChecksum: false
- $.entries[6].packagedPath: ""
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_SinisterGrace.T_UI_SpecialPack_SinisterGrace"
- $.entries[6].schema: "s3ver://"
+ $.entries[6].schema: "s3verbin://"
- $.entries[6].uri: "freetoplay/NA/event.json"
+ $.entries[6].uri: "images/T_UI_SpecialPack_SinisterGrace.png"
- $.entries[7].contentVersion: "807c86683510773f5b5540e21c207183cdd154a5"
+ $.entries[7].contentVersion: "4deb0391cf08e15cd3c40d0cde2a17a1e284b1ae"
- $.entries[7].downloadStrategy: "preferRemote"
+ $.entries[7].downloadStrategy: "preferPackaged"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_NOTLC.T_UI_CollectionBanner_NOTLC"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "freetoplay/EU/event.json"
+ $.entries[7].uri: "images/T_UI_CollectionBanner_NOTLC.png"
- $.entries[8].contentVersion: "8d5e48c3617ded37f978bed6f936b24ce4a4d84a"
+ $.entries[8].contentVersion: "a0eb39e204ac7a589e860c5759293da82ed5b143"
- $.entries[8].downloadStrategy: "preferRemote"
+ $.entries[8].downloadStrategy: "preferPackaged"
- $.entries[8].enableChecksum: true
+ $.entries[8].enableChecksum: false
- $.entries[8].packagedPath: ""
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_NOTLC.T_UI_SpecialPack_NOTLC"
- $.entries[8].schema: "s3ver://"
+ $.entries[8].schema: "s3verbin://"
- $.entries[8].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[8].uri: "images/T_UI_SpecialPack_NOTLC.png"
- $.entries[9].contentVersion: "8ad9763626b20a285f86032454b700c0757ede9f"
+ $.entries[9].contentVersion: "ff437cc262850ea6df4a8ca3c5b64964964f7747"
- $.entries[9].downloadStrategy: "preferRemote"
+ $.entries[9].downloadStrategy: "preferPackaged"
- $.entries[9].enableChecksum: true
+ $.entries[9].enableChecksum: false
- $.entries[9].packagedPath: ""
+ $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_PartyHard.T_UI_CollectionBanner_PartyHard"
- $.entries[9].schema: "s3ver://"
+ $.entries[9].schema: "s3verbin://"
- $.entries[9].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[9].uri: "images/T_UI_CollectionBanner_PartyHard.png"
- $.entries[10].contentVersion: "63b33bf43464cbc6c7cb6624ab4b2268f8b6bb82"
+ $.entries[10].contentVersion: "d16173b36a12e4a4ed82a5fc7650cf5d8a9f8bbf"
- $.entries[10].downloadStrategy: "preferRemote"
+ $.entries[10].downloadStrategy: "preferPackaged"
- $.entries[10].enableChecksum: true
+ $.entries[10].enableChecksum: false
- $.entries[10].packagedPath: ""
+ $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_PartyHard.T_UI_SpecialPack_PartyHard"
- $.entries[10].schema: "s3ver://"
+ $.entries[10].schema: "s3verbin://"
- $.entries[10].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[10].uri: "images/T_UI_SpecialPack_PartyHard.png"
- $.entries[11].contentVersion: "f9c0c52ef3658340ea8c9b59454494ec8426dca0"
+ $.entries[11].contentVersion: "2caf9ad308ee3f8c6cf300122aecb55c8a10d730"
- $.entries[11].uri: "archiveQuests/CalamariV1.json"
+ $.entries[11].uri: "catalog.json"
- $.entries[12].contentVersion: "a152f47cfedf53798388a9bcc47e2ff4926aeccd"
+ $.entries[12].contentVersion: "a3ae9f58d0dee10bafa82f215593ff417d538e00"
- $.entries[12].uri: "archiveQuests/CalamariV2.json"
+ $.entries[12].uri: "bonusPointEventsContent.json"
- $.entries[13].contentVersion: "20fc0a0a83e637d49dcf28e321dd0a225c5c420a"
+ $.entries[13].contentVersion: "2b59e9761cec12be445ee8cca0a385e3504cb620"
- $.entries[13].uri: "archiveQuests/CalamariV3.json"
+ $.entries[13].uri: "freetoplay/NA/event.json"
- $.entries[14].contentVersion: "5a11bacc946ed364ed23d44fc56ead0b8dda574a"
+ $.entries[14].contentVersion: "2b59e9761cec12be445ee8cca0a385e3504cb620"
- $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[14].uri: "freetoplay/EU/event.json"
- $.entries[15].contentVersion: "5b942b365217c66d205063b3803afb3a93b86d96"
+ $.entries[15].contentVersion: "38a216303d6dda39cf30c4d2d786e4dda581597d"
- $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[15].uri: "archiveQuests/Anniversary2022.json"
- $.entries[16].contentVersion: "fd773cf9c178d9e06982f15d465eef51c3df166b"
+ $.entries[16].contentVersion: "054edff758b733e20dd587cfa33850a16595e39b"
- $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[16].uri: "archiveQuests/Anniversary2023.json"
- $.entries[17].contentVersion: "d5bc15a7f80e1149a630aca336bd2a7f09462585"
+ $.entries[17].contentVersion: "4b3ae0806f1c01fceef0bd2835c47a4d41747aa8"
- $.entries[17].uri: "archiveQuests/FireflyV1.json"
+ $.entries[17].uri: "archiveQuests/Anniversary2024.json"
- $.entries[18].contentVersion: "f8d7b5c9cac6e56a352f6cc60bd89448fe6bdfc3"
+ $.entries[18].contentVersion: "baef1757018d93edaa5a4f9b61dce5a6edd3299b"
- $.entries[18].uri: "archiveQuests/Halloween2021.json"
+ $.entries[18].uri: "archiveQuests/CalamariV1.json"
- $.entries[19].contentVersion: "ee3ea9d3f96ceadf9cbaac4cf785bb7b99014628"
+ $.entries[19].contentVersion: "9de2b4ac74d629f27ec4b2490b92ea1a417ee37d"
- $.entries[19].uri: "archiveQuests/Halloween2022.json"
+ $.entries[19].uri: "archiveQuests/CalamariV2.json"
- $.entries[20].contentVersion: "9ce8211c3232135813a037398de1a77d92add255"
+ $.entries[20].contentVersion: "6c7e74aa941f63311638f9893ecbd86e3e8322fa"
- $.entries[20].uri: "archiveQuests/Halloween2023.json"
+ $.entries[20].uri: "archiveQuests/CalamariV3.json"
- $.entries[21].contentVersion: "d90f6ecee5119a351d84a54ce937cf44292c8596"
+ $.entries[21].contentVersion: "74f3f3c1d90061faa39c3b4d01eb43443685c913"
- $.entries[21].uri: "archiveQuests/Halloween2024.json"
+ $.entries[21].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[22].contentVersion: "80be5626a97d561f41f1b5b432d35c5ddb3cf83f"
+ $.entries[22].contentVersion: "a8777aa9d56731007f764d8db72edd760d9f472a"
- $.entries[22].uri: "archiveQuests/Spring2024.json"
+ $.entries[22].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[23].contentVersion: "8f05011ab417539f5df9235833669d43f0bb539f"
+ $.entries[23].contentVersion: "8bb66c93ec94f49bfe15f38642247168d6c42d3e"
- $.entries[23].uri: "archiveQuests/Spring2025.json"
+ $.entries[23].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[24].contentVersion: "87cb4dfd91c3e8659efcd8f1b7a2dbb1f837cb85"
+ $.entries[24].contentVersion: "d20fefecc6996f8e8e470c61e3dd7ef3249cffca"
- $.entries[24].uri: "archiveQuests/Summer2023.json"
+ $.entries[24].uri: "archiveQuests/FireflyV1.json"
- $.entries[25].contentVersion: "b170191ae584f28f7aee8df2af8558ff4ab4b9bc"
+ $.entries[25].contentVersion: "9a7b9d0f63aab4d1f0fe03128489fd18b86b70a1"
- $.entries[25].uri: "archiveQuests/Tome01.json"
+ $.entries[25].uri: "archiveQuests/Halloween2021.json"
- $.entries[26].contentVersion: "37866ee77f5b0bf64388fc55c9666c453c7bf47f"
+ $.entries[26].contentVersion: "5c78246a1489a53155a418ee3045c952f0be1097"
- $.entries[26].uri: "archiveQuests/Tome02.json"
+ $.entries[26].uri: "archiveQuests/Halloween2022.json"
- $.entries[27].contentVersion: "990f486cff81f96429df95aa98e9101b69bd8534"
+ $.entries[27].contentVersion: "f7f0c3923d2bc55db95d000e2d8b2e2b2866fa07"
- $.entries[27].uri: "archiveQuests/Tome03.json"
+ $.entries[27].uri: "archiveQuests/Halloween2023.json"
- $.entries[28].contentVersion: "86641472abbd427901d9c4c3416377ce84a2fc8f"
+ $.entries[28].contentVersion: "740ec264b473a0d9c25babc776c532fa63fc5305"
- $.entries[28].uri: "archiveQuests/Tome04.json"
+ $.entries[28].uri: "archiveQuests/Halloween2024.json"
- $.entries[29].contentVersion: "62efe0dfc80e8a7457985bede64dbf3a87b8c2d3"
+ $.entries[29].contentVersion: "701b45da72a46b6c38dc378206ad81cf83169203"
- $.entries[29].uri: "archiveQuests/Tome05.json"
+ $.entries[29].uri: "archiveQuests/Spring2024.json"
- $.entries[30].contentVersion: "44d4e86e48bd8b50a1ce1b581e7ad2a3101a077d"
+ $.entries[30].contentVersion: "60711d0c789b221bf37444dc1944242477fb9fc3"
- $.entries[30].uri: "archiveQuests/Tome06.json"
+ $.entries[30].uri: "archiveQuests/Spring2025.json"
- $.entries[31].contentVersion: "2f5851703b3b110d5827d28022bca97ba17afbb8"
+ $.entries[31].contentVersion: "1da7f57021a89276c5073ab5279c115497961c00"
- $.entries[31].uri: "archiveQuests/Tome07.json"
+ $.entries[31].uri: "archiveQuests/Summer2023.json"
… 766 more change(s) — see the commit diff for everything
```

### [`prestige/prestige.json`](prestige/prestige.json)

[Full line-by-line diff](diffs/prestige/prestige.json.diff)

```diff
+ $.rewards.K41
+ $.rewards.S49
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Maple]
+ $.featuredCard[id=Maple_W2]
+ $.featuredChapterPackRecommendations[id=Maple]
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "47"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "48"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S48_MichonneGrimes_Portrait.S48_MichonneGrimes_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Maple/T_UI_S49_VeeBoonyasak_Portrait.T_UI_S49_VeeBoonyasak_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "46"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "268435496"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S47_RickGrimes_Portrait.S47_RickGrimes_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Maple/T_UI_K41_TheKrasue_Portrait.T_UI_K41_TheKrasue_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "268435495"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "47"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Ketchup/K40_TheAnimatronic_Portrait.K40_TheAnimatronic_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S48_MichonneGrimes_Portrait.S48_MichonneGrimes_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "45"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "46"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S47_RickGrimes_Portrait.S47_RickGrimes_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "268435494"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "268435495"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Ketchup/K40_TheAnimatronic_Portrait.K40_TheAnimatronic_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "268435493"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "45"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].characterIndex: "44"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].characterIndex: "268435494"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].characterIndex: "268435492"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].characterIndex: "268435493"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].characterIndex: "43"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].characterIndex: "44"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/S44_TrevorBelmont_Portrait.S44_TrevorBelmont_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[9]
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[10]
- $.featuredCustomizationRecommendations[id=LasagnaW1]
- $.featuredCustomizationRecommendations[id=LasagnaW2]
- $.featuredCustomizationRecommendations[id=LasagnaW3]
- $.featuredCustomizationRecommendations[id=LasagnaW4]
- $.featuredCustomizationRecommendations[id=LasagnaW5]
- $.featuredCustomizationRecommendations[id=LasagnaW6]
+ $.featuredCustomizationRecommendations[id=MapleW1]
+ $.featuredCustomizationRecommendations[id=MapleW2]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[54].mainEndTime: "2025-09-09T15:00:00"
+ $.specialEvents[54].mainEndTime: "2025-08-26T15:00:00"
- $.specialEvents[54].postEndTime: "2025-09-09T15:00:00"
+ $.specialEvents[54].postEndTime: "2025-08-26T15:00:00"
- $.specialEvents[54].startTime: "2025-08-19T15:00:00"
+ $.specialEvents[54].startTime: "2025-08-12T15:00:00"
+ $.specialEvents[55]
+ $.specialEvents[56]
+ $.specialEvents[57]
+ $.specialEventsData[23].lteData
- $.specialEventsData[23].eventId: "Lunar2022"
+ $.specialEventsData[23].eventId: "Halloween2025"
- $.specialEventsData[23].miscRewards[id=killerStaticReward]
- $.specialEventsData[23].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[23].scoreEventRewards[0]
- $.specialEventsData[23].scoreEventRewards[1]
- $.specialEventsData[23].scoreEventRewards[2]
- $.specialEventsData[23].scoreEventRewards[3]
- $.specialEventsData[23].scoreEventRewards[4]
- $.specialEventsData[23].scoreEventRewards[5]
- $.specialEventsData[23].scoreEventRewards[6]
- $.specialEventsData[23].scoreEventRewards[7]
- $.specialEventsData[24].eventId: "Lunar2023"
+ $.specialEventsData[24].eventId: "Lunar2022"
- $.specialEventsData[24].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 5000
+ $.specialEventsData[24].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 4000
- $.specialEventsData[24].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[24].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[24].scoreEventRewards[2].weight: 15
+ $.specialEventsData[24].scoreEventRewards[2].weight: 20
- $.specialEventsData[24].scoreEventRewards[3].weight: 25
+ $.specialEventsData[24].scoreEventRewards[3].weight: 20
- $.specialEventsData[24].scoreEventRewards[5].weight: 20
+ $.specialEventsData[24].scoreEventRewards[5].weight: 15
- $.specialEventsData[24].scoreEventRewards[6].weight: 10
+ $.specialEventsData[24].scoreEventRewards[6].weight: 8
- $.specialEventsData[24].scoreEventRewards[7].weight: 5
+ $.specialEventsData[24].scoreEventRewards[7].weight: 2
- $.specialEventsData[25].lteData
- $.specialEventsData[25].eventId: "MapShowcaseKetchup"
+ $.specialEventsData[25].eventId: "Lunar2023"
+ $.specialEventsData[25].miscRewards[id=killerStaticReward]
+ $.specialEventsData[25].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[25].scoreEventRewards[0]
+ $.specialEventsData[25].scoreEventRewards[1]
+ $.specialEventsData[25].scoreEventRewards[2]
+ $.specialEventsData[25].scoreEventRewards[3]
+ $.specialEventsData[25].scoreEventRewards[4]
+ $.specialEventsData[25].scoreEventRewards[5]
+ $.specialEventsData[25].scoreEventRewards[6]
+ $.specialEventsData[25].scoreEventRewards[7]
+ $.specialEventsData[26].lteData
- $.specialEventsData[26].eventId: "Spring2024"
+ $.specialEventsData[26].eventId: "MapShowcaseKetchup"
- $.specialEventsData[26].eventTrackerObjectives[id=main]
- $.specialEventsData[27].lteData
- $.specialEventsData[27].eventId: "Spring2025"
+ $.specialEventsData[27].eventId: "Spring2024"
- $.specialEventsData[27].eventTrackerObjectives[id=main].additionalEventIdsWithMilestoneBonus
- $.specialEventsData[27].eventTrackerObjectives[id=main].questEventConditions
- $.specialEventsData[27].eventTrackerObjectives[id=main].questEvents
+ $.specialEventsData[27].eventTrackerObjectives[id=main].questEventId: "QuestEvent.SpringEventPlaceZone"
+ $.specialEventsData[27].eventTrackerObjectives[id=main].questEventParams: "instigator:me"
- $.specialEventsData[27].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 16
+ $.specialEventsData[27].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 10
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
+ $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.0
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
+ $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 2.0
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
+ $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[1].neededProgression: 7000000
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
+ $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 3.0
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
+ $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[2].neededProgression: 20000000
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
+ $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 4.0
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
+ $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[3].neededProgression: 35000000
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[4]
- $.specialEventsData[27].eventTrackerObjectives[id=main].milestones[5]
- $.specialEventsData[27].milestoneRewards[0]
- $.specialEventsData[27].milestoneRewards[1]
- $.specialEventsData[27].milestoneRewards[2]
+ $.specialEventsData[28].lteData
- $.specialEventsData[28].eventId: "Winter2023"
+ $.specialEventsData[28].eventId: "Spring2025"
+ $.specialEventsData[28].eventTrackerObjectives[id=main]
- $.specialEventsData[28].milestoneRewards[0].rewards[id=YE_005]
+ $.specialEventsData[28].milestoneRewards[0].rewards[id=IC_001]
- $.specialEventsData[28].milestoneRewards[1].pointsCost: 6
+ $.specialEventsData[28].milestoneRewards[1].pointsCost: 8
- $.specialEventsData[28].milestoneRewards[1].rewards[id=YE_BDG_01]
+ $.specialEventsData[28].milestoneRewards[1].rewards[id=IC_BDG_03]
- $.specialEventsData[28].milestoneRewards[2].pointsCost: 9
+ $.specialEventsData[28].milestoneRewards[2].pointsCost: 15
- $.specialEventsData[28].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[28].milestoneRewards[2].rewards[id=IC_BNR_03]
- $.specialEventsData[28].milestoneRewards[3]
- $.specialEventsData[28].milestoneRewards[4]
- $.specialEventsData[29].lteData
- $.specialEventsData[29].eventId: "Winter2024"
+ $.specialEventsData[29].eventId: "Winter2023"
- $.specialEventsData[29].eventPeriods[id=Winter2024]
- $.specialEventsData[29].milestoneRewards[0].pointsCost: 6
+ $.specialEventsData[29].milestoneRewards[0].pointsCost: 3
- $.specialEventsData[29].milestoneRewards[0].rewards[id=GEL_001]
+ $.specialEventsData[29].milestoneRewards[0].rewards[id=YE_005]
- $.specialEventsData[29].milestoneRewards[1].pointsCost: 12
+ $.specialEventsData[29].milestoneRewards[1].pointsCost: 6
- $.specialEventsData[29].milestoneRewards[1].rewards[id=GE_BDG_08]
+ $.specialEventsData[29].milestoneRewards[1].rewards[id=YE_BDG_01]
- $.specialEventsData[29].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[29].milestoneRewards[2].pointsCost: 9
- $.specialEventsData[29].milestoneRewards[2].rewards[id=GE_BNR_07]
+ $.specialEventsData[29].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[29].milestoneRewards[3]
+ $.specialEventsData[29].milestoneRewards[4]
+ $.specialEventsData[30]
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

