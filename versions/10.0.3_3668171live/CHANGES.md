# live · 10.0.3_3668171live

| | |
|---|---|
| Build date | 2026-08-25 13:02 UTC |
| CDN version | `10.0.3_3668171live-1787662940` |
| Key | `10.0.3_live` |
| Compared with | [10.1.0_3665864live](../10.1.0_3665864live/CHANGES.md) (2026-08-24 16:12 UTC) |

## Summary

**1** added · **71** modified · **5** removed · 138 unchanged

## New or updated images

<a href="images/T_UI_SpecialPack_Rift6.png"><img src="images/T_UI_SpecialPack_Rift6.png" alt="T_UI_SpecialPack_Rift6.png" width="240"></a>

## Removed files

- `images/T_UI_ChapterBundle_ChorusOfSin.png`
- `images/T_UI_CollectionBanner_GameplayExpo_Unknown.png`
- `images/T_UI_CollectionBanner_Xenomorph_King.png`
- `images/T_UI_SpecialPack_GameplayExpo_Unknown.png`
- `images/T_UI_SpecialPack_Xenomorph_King.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.enableUmgMatchmakingRefactor: true
+ $.enableUmgMatchmakingRefactor: false
```

### [`archiveQuests/Anniversary2022.json`](archiveQuests/Anniversary2022.json)

[Full line-by-line diff](diffs/archiveQuests/Anniversary2022.json.diff)

```diff
+ $.Anniversary2022.level[0].challengeRewards[id=star]
+ $.Anniversary2022.level[0].endNodeRewards[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_01.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_02.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_03.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_04.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_05.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_06.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_07.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_08.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_09.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_10.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_11.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_12.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_13.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_14.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_15.reward[id=star]
+ $.Anniversary2022.level[0].nodes.node_ANN1_16.reward[id=star]
+ $.Anniversary2022.level[0].taskRewards[id=star]
+ $.Anniversary2022.level[1].challengeRewards[id=star]
+ $.Anniversary2022.level[1].endNodeRewards[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_01.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_02.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_03.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_04.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_05.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_06.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_07.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_08.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_09.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_10.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_11.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_12.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_13.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_14.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_15.reward[id=star]
+ $.Anniversary2022.level[1].nodes.node_ANN2_16.reward[id=star]
+ $.Anniversary2022.level[1].taskRewards[id=star]
```

### [`archiveQuests/Anniversary2023.json`](archiveQuests/Anniversary2023.json)

[Full line-by-line diff](diffs/archiveQuests/Anniversary2023.json.diff)

```diff
+ $.Anniversary2023.level[0].challengeRewards[id=star]
+ $.Anniversary2023.level[0].endNodeRewards[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_01"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_02"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_03"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_04"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_05"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_06"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_07"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_08"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_09"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_10"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_11"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_12"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_13"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_14"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_15"].reward[id=star]
+ $.Anniversary2023.level[0].nodes["node_ANN2023-1_16"].reward[id=star]
+ $.Anniversary2023.level[0].taskRewards[id=star]
+ $.Anniversary2023.level[1].challengeRewards[id=star]
+ $.Anniversary2023.level[1].endNodeRewards[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_01"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_02"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_03"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_04"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_05"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_06"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_07"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_08"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_09"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_10"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_11"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_12"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_13"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_14"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_15"].reward[id=star]
+ $.Anniversary2023.level[1].nodes["node_ANN2023-2_16"].reward[id=star]
+ $.Anniversary2023.level[1].taskRewards[id=star]
```

### [`archiveQuests/Anniversary2024.json`](archiveQuests/Anniversary2024.json)

[Full line-by-line diff](diffs/archiveQuests/Anniversary2024.json.diff)

```diff
+ $.Anniversary2024.level[0].challengeRewards[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_01"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_02"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_03"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_04"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_05"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_06"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_07"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_08"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_09"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_10"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_11"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_12"].reward[id=star]
+ $.Anniversary2024.level[0].nodes["node_ANN2024-1_13"].reward[id=star]
+ $.Anniversary2024.level[0].taskRewards[id=star]
+ $.Anniversary2024.level[1].challengeRewards[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-1_01"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-1_02"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-1_03"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-1_04"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_05"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_06"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_07"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_08"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_09"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_10"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_11"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_12"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_13"].reward[id=star]
+ $.Anniversary2024.level[1].nodes["node_ANN2024-2_14"].reward[id=star]
+ $.Anniversary2024.level[1].taskRewards[id=star]
+ $.Anniversary2024.level[2].challengeRewards[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_01"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_02"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_03"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_04"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_05"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_06"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_07"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_08"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_09"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_10"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_11"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_12"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_13"].reward[id=star]
+ $.Anniversary2024.level[2].nodes["node_ANN2024-3_14"].reward[id=star]
+ $.Anniversary2024.level[2].taskRewards[id=star]
```

### [`archiveQuests/CalamariV1.json`](archiveQuests/CalamariV1.json)

[Full line-by-line diff](diffs/archiveQuests/CalamariV1.json.diff)

```diff
+ $.CalamariV1.level[0].challengeRewards[id=star]
+ $.CalamariV1.level[0].endNodeRewards[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_01.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_02.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_03.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_04.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_05.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_06.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_07.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_08.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_09.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_10.reward[id=star]
+ $.CalamariV1.level[0].nodes.node_CalamariV1_L1_11.reward[id=star]
+ $.CalamariV1.level[0].taskRewards[id=star]
+ $.CalamariV1.level[1].challengeRewards[id=star]
+ $.CalamariV1.level[1].endNodeRewards[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_01.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_02.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_03.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_04.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_05.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_06.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_07.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_08.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_09.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_10.reward[id=star]
+ $.CalamariV1.level[1].nodes.node_CalamariV1_L2_11.reward[id=star]
+ $.CalamariV1.level[1].taskRewards[id=star]
```

### [`archiveQuests/CalamariV2.json`](archiveQuests/CalamariV2.json)

[Full line-by-line diff](diffs/archiveQuests/CalamariV2.json.diff)

```diff
+ $.CalamariV2.level[0].challengeRewards[id=star]
+ $.CalamariV2.level[0].endNodeRewards[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_01.reward[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_02.reward[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_03.reward[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_04.reward[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_05.reward[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_06.reward[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_07.reward[id=star]
+ $.CalamariV2.level[0].nodes.node_CalamariV2_L1_08.reward[id=star]
+ $.CalamariV2.level[0].taskRewards[id=star]
+ $.CalamariV2.level[1].challengeRewards[id=star]
+ $.CalamariV2.level[1].endNodeRewards[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_01.reward[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_02.reward[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_03.reward[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_04.reward[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_05.reward[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_06.reward[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_07.reward[id=star]
+ $.CalamariV2.level[1].nodes.node_CalamariV2_L2_08.reward[id=star]
+ $.CalamariV2.level[1].taskRewards[id=star]
```

### [`archiveQuests/CalamariV3.json`](archiveQuests/CalamariV3.json)

[Full line-by-line diff](diffs/archiveQuests/CalamariV3.json.diff)

```diff
+ $.CalamariV3.level[0].challengeRewards[id=star]
+ $.CalamariV3.level[0].endNodeRewards[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_01.reward[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_02.reward[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_03.reward[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_04.reward[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_05.reward[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_06.reward[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_07.reward[id=star]
+ $.CalamariV3.level[0].nodes.node_CalamariV3_L1_08.reward[id=star]
+ $.CalamariV3.level[0].taskRewards[id=star]
+ $.CalamariV3.level[1].challengeRewards[id=star]
+ $.CalamariV3.level[1].endNodeRewards[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_01.reward[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_02.reward[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_03.reward[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_04.reward[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_05.reward[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_06.reward[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_07.reward[id=star]
+ $.CalamariV3.level[1].nodes.node_CalamariV3_L2_08.reward[id=star]
+ $.CalamariV3.level[1].taskRewards[id=star]
```

### [`archiveQuests/ChocolateBoxGelato.json`](archiveQuests/ChocolateBoxGelato.json)

[Full line-by-line diff](diffs/archiveQuests/ChocolateBoxGelato.json.diff)

```diff
+ $.ChocolateBoxGelato.level[0].challengeRewards[id=star]
+ $.ChocolateBoxGelato.level[0].endNodeRewards[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_01.reward[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_02.reward[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_03.reward[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_04.reward[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_05.reward[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_06.reward[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_07.reward[id=star]
+ $.ChocolateBoxGelato.level[0].nodes.node_ChocolateBoxGelato_L1_08.reward[id=star]
+ $.ChocolateBoxGelato.level[0].taskRewards[id=star]
+ $.ChocolateBoxGelato.level[1].challengeRewards[id=star]
+ $.ChocolateBoxGelato.level[1].endNodeRewards[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_01.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_02.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_03.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_04.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_05.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_06.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_07.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_08.reward[id=star]
+ $.ChocolateBoxGelato.level[1].nodes.node_ChocolateBoxGelato_L2_09.reward[id=star]
+ $.ChocolateBoxGelato.level[1].taskRewards[id=star]
```

### [`archiveQuests/ChocolateBoxV1.json`](archiveQuests/ChocolateBoxV1.json)

[Full line-by-line diff](diffs/archiveQuests/ChocolateBoxV1.json.diff)

```diff
+ $.ChocolateBoxV1.level[0].challengeRewards[id=star]
+ $.ChocolateBoxV1.level[0].endNodeRewards[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_01.reward[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_02.reward[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_03.reward[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_04.reward[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_05.reward[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_06.reward[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_07.reward[id=star]
+ $.ChocolateBoxV1.level[0].nodes.node_ChocolateBoxV1_L1_09.reward[id=star]
+ $.ChocolateBoxV1.level[0].taskRewards[id=star]
```

### [`archiveQuests/DreadByDaylightZodiac.json`](archiveQuests/DreadByDaylightZodiac.json)

[Full line-by-line diff](diffs/archiveQuests/DreadByDaylightZodiac.json.diff)

```diff
+ $.DreadByDaylightZodiac.level[0].challengeRewards[id=star]
+ $.DreadByDaylightZodiac.level[0].endNodeRewards[id=star]
+ $.DreadByDaylightZodiac.level[0].nodes.node_ZodiacLTE_L1_01.reward[id=star]
+ $.DreadByDaylightZodiac.level[0].nodes.node_ZodiacLTE_L1_02.reward[id=star]
+ $.DreadByDaylightZodiac.level[0].nodes.node_ZodiacLTE_L1_03.reward[id=star]
+ $.DreadByDaylightZodiac.level[0].nodes.node_ZodiacLTE_L1_04.reward[id=star]
+ $.DreadByDaylightZodiac.level[0].nodes.node_ZodiacLTE_L1_05.reward[id=star]
+ $.DreadByDaylightZodiac.level[0].nodes.node_ZodiacLTE_L1_06.reward[id=star]
+ $.DreadByDaylightZodiac.level[0].taskRewards[id=star]
```

### [`archiveQuests/FireflyV1.json`](archiveQuests/FireflyV1.json)

[Full line-by-line diff](diffs/archiveQuests/FireflyV1.json.diff)

```diff
+ $.FireflyV1.level[0].challengeRewards[id=star]
+ $.FireflyV1.level[0].endNodeRewards[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_01.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_02.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_03.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_04.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_05.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_06.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_07.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_08.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_09.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_10.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_11.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_12.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_13.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_14.reward[id=star]
+ $.FireflyV1.level[0].nodes.node_FireflyV1_L1_15.reward[id=star]
+ $.FireflyV1.level[0].taskRewards[id=star]
```

### [`archiveQuests/Halloween2021.json`](archiveQuests/Halloween2021.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2021.json.diff)

```diff
+ $.Halloween2021.level[0].challengeRewards[id=star]
+ $.Halloween2021.level[0].endNodeRewards[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_01.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_02.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_03.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_04.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_05.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_07.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_08.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_09.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_10.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_11.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_12.reward[id=star]
+ $.Halloween2021.level[0].nodes.node_HAL1_13.reward[id=star]
+ $.Halloween2021.level[0].taskRewards[id=star]
+ $.Halloween2021.level[1].challengeRewards[id=star]
+ $.Halloween2021.level[1].endNodeRewards[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_01.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_02.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_03.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_05.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_06.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_07.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_08.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_09.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_10.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_11.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_12.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_13.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_14.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_15.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_16.reward[id=star]
+ $.Halloween2021.level[1].nodes.node_HAL2_17.reward[id=star]
+ $.Halloween2021.level[1].taskRewards[id=star]
```

### [`archiveQuests/Halloween2022.json`](archiveQuests/Halloween2022.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2022.json.diff)

```diff
+ $.Halloween2022.level[0].challengeRewards[id=star]
+ $.Halloween2022.level[0].endNodeRewards[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_01.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_02.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_03.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_04.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_05.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_06.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_07.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_08.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_09.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_10.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_11.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_12.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_13.reward[id=star]
+ $.Halloween2022.level[0].nodes.node_HAL1_14.reward[id=star]
+ $.Halloween2022.level[0].taskRewards[id=star]
+ $.Halloween2022.level[1].challengeRewards[id=star]
+ $.Halloween2022.level[1].endNodeRewards[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_01.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_02.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_03.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_04.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_05.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_06.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_07.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_08.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_09.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_10.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_11.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_12.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_13.reward[id=star]
+ $.Halloween2022.level[1].nodes.node_HAL2_14.reward[id=star]
+ $.Halloween2022.level[1].taskRewards[id=star]
```

### [`archiveQuests/Halloween2023.json`](archiveQuests/Halloween2023.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2023.json.diff)

```diff
+ $.Halloween2023.level[0].challengeRewards[id=star]
+ $.Halloween2023.level[0].endNodeRewards[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_01"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_02"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_03"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_04"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_05"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_06"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_07"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_08"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_09"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_10"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_11"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_12"].reward[id=star]
+ $.Halloween2023.level[0].nodes["node_HAL2023-1_13"].reward[id=star]
+ $.Halloween2023.level[0].taskRewards[id=star]
+ $.Halloween2023.level[1].challengeRewards[id=star]
+ $.Halloween2023.level[1].endNodeRewards[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_01"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_02"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_03"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_04"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_05"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_06"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_07"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_08"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_09"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_10"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_11"].reward[id=star]
+ $.Halloween2023.level[1].nodes["node_HAL2023-2_12"].reward[id=star]
+ $.Halloween2023.level[1].taskRewards[id=star]
```

### [`archiveQuests/Halloween2024.json`](archiveQuests/Halloween2024.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2024.json.diff)

```diff
+ $.Halloween2024.level[0].challengeRewards[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_01.reward[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_02.reward[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_03.reward[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_04.reward[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_05.reward[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_06.reward[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_07.reward[id=star]
+ $.Halloween2024.level[0].nodes.node_DBDDay_08.reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_01"].reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_02"].reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_03"].reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_04"].reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_05"].reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_06"].reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_07"].reward[id=star]
+ $.Halloween2024.level[0].nodes["node_HAL2024-1_08"].reward[id=star]
+ $.Halloween2024.level[0].taskRewards[id=star]
+ $.Halloween2024.level[1].challengeRewards[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_01"].reward[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_02"].reward[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_03"].reward[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_04"].reward[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_05"].reward[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_06"].reward[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_07"].reward[id=star]
+ $.Halloween2024.level[1].nodes["node_HAL2024-2_08"].reward[id=star]
+ $.Halloween2024.level[1].taskRewards[id=star]
+ $.Halloween2024.level[2].challengeRewards[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_01"].reward[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_02"].reward[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_03"].reward[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_04"].reward[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_05"].reward[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_06"].reward[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_07"].reward[id=star]
+ $.Halloween2024.level[2].nodes["node_HAL2024-3_08"].reward[id=star]
+ $.Halloween2024.level[2].taskRewards[id=star]
```

### [`archiveQuests/Spring2024.json`](archiveQuests/Spring2024.json)

[Full line-by-line diff](diffs/archiveQuests/Spring2024.json.diff)

```diff
+ $.Spring2024.level[0].challengeRewards[id=star]
+ $.Spring2024.level[0].endNodeRewards[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_01.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_02.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_03.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_04.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_05.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_06.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_07.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_08.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_09.reward[id=star]
+ $.Spring2024.level[0].nodes.node_SPR2024_L1_10.reward[id=star]
+ $.Spring2024.level[0].taskRewards[id=star]
+ $.Spring2024.level[1].challengeRewards[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_01.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_02.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_03.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_04.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_05.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_06.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_07.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_08.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_09.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_10.reward[id=star]
+ $.Spring2024.level[1].nodes.node_SPR2024_L2_11.reward[id=star]
+ $.Spring2024.level[1].taskRewards[id=star]
```

### [`archiveQuests/Spring2025.json`](archiveQuests/Spring2025.json)

[Full line-by-line diff](diffs/archiveQuests/Spring2025.json.diff)

```diff
+ $.Spring2025.level[0].challengeRewards[id=star]
+ $.Spring2025.level[0].endNodeRewards[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_01.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_02.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_03.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_04.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_05.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_06.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_07.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_08.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_09.reward[id=star]
+ $.Spring2025.level[0].nodes.node_SPR2025_L1_10.reward[id=star]
+ $.Spring2025.level[0].taskRewards[id=star]
+ $.Spring2025.level[1].challengeRewards[id=star]
+ $.Spring2025.level[1].endNodeRewards[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_01.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_02.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_03.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_04.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_05.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_06.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_07.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_08.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_09.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_10.reward[id=star]
+ $.Spring2025.level[1].nodes.node_SPR2025_L2_11.reward[id=star]
+ $.Spring2025.level[1].taskRewards[id=star]
+ $.Spring2025.level[2].challengeRewards[id=star]
+ $.Spring2025.level[2].endNodeRewards[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_01.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_02.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_03.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_04.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_05.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_06.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_07.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_08.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_09.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_10.reward[id=star]
+ $.Spring2025.level[2].nodes.node_SPR2025_L3_11.reward[id=star]
+ $.Spring2025.level[2].taskRewards[id=star]
```

### [`archiveQuests/Summer2023.json`](archiveQuests/Summer2023.json)

[Full line-by-line diff](diffs/archiveQuests/Summer2023.json.diff)

```diff
+ $.Summer2023.level[0].challengeRewards[id=star]
+ $.Summer2023.level[0].endNodeRewards[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_01"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_02"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_03"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_04"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_05"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_06"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_07"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_08"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_09"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_10"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_11"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_12"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_13"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_14"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_15"].reward[id=star]
+ $.Summer2023.level[0].nodes["node_SUM2023-1_16"].reward[id=star]
+ $.Summer2023.level[0].taskRewards[id=star]
+ $.Summer2023.level[1].challengeRewards[id=star]
+ $.Summer2023.level[1].endNodeRewards[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_01"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_02"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_03"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_04"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_06"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_08"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_09"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_11"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_12"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_13"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_14"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_15"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_16"].reward[id=star]
+ $.Summer2023.level[1].nodes["node_SUM2023-2_20"].reward[id=star]
+ $.Summer2023.level[1].taskRewards[id=star]
```

### [`archiveQuests/Tome01.json`](archiveQuests/Tome01.json)

[Full line-by-line diff](diffs/archiveQuests/Tome01.json.diff)

```diff
+ $.Tome01.level[0].challengeRewards[id=star]
+ $.Tome01.level[0].endNodeRewards[id=star]
+ $.Tome01.level[0].nodes.nodeGenericTask01.reward[id=star]
+ $.Tome01.level[0].nodes.nodeGenericTask02.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerChallenge01.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerChallenge02.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerChallenge03.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerChallenge04.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerChallenge05.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerTask01.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerTask02.reward[id=star]
+ $.Tome01.level[0].nodes.nodeKillerTask03.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorChallenge01.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorChallenge02.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorChallenge03.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorChallenge04.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorChallenge05.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorTask01.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorTask02.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorTask03.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorTask04.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorTask05.reward[id=star]
+ $.Tome01.level[0].nodes.nodeSurvivorTask06.reward[id=star]
+ $.Tome01.level[0].taskRewards[id=star]
+ $.Tome01.level[1].challengeRewards[id=star]
+ $.Tome01.level[1].endNodeRewards[id=star]
+ $.Tome01.level[1].nodes.nodeKillerChallenge01.reward[id=star]
+ $.Tome01.level[1].nodes.nodeKillerChallenge02.reward[id=star]
+ $.Tome01.level[1].nodes.nodeKillerChallenge03.reward[id=star]
+ $.Tome01.level[1].nodes.nodeKillerChallenge04.reward[id=star]
+ $.Tome01.level[1].nodes.nodeKillerChallenge05.reward[id=star]
+ $.Tome01.level[1].nodes.nodeKillerTask01.reward[id=star]
+ $.Tome01.level[1].nodes.nodeKillerTask02.reward[id=star]
+ $.Tome01.level[1].nodes.nodeKillerTask03.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorChallenge01.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorChallenge02.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorChallenge03.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorChallenge04.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorChallenge05.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorTask01.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorTask02.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorTask03.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorTask04.reward[id=star]
+ $.Tome01.level[1].nodes.nodeSurvivorTask05.reward[id=star]
+ $.Tome01.level[1].taskRewards[id=star]
+ $.Tome01.level[2].challengeRewards[id=star]
+ $.Tome01.level[2].endNodeRewards[id=star]
+ $.Tome01.level[2].nodes.nodeGenericTask01.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerChallenge01.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerChallenge02.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerChallenge03.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerChallenge04.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerChallenge05.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerTask01.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerTask02.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerTask03.reward[id=star]
+ $.Tome01.level[2].nodes.nodeKillerTask04.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorChallenge01.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorChallenge02.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorChallenge03.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorChallenge04.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorChallenge05.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorTask01.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorTask02.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorTask03.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorTask04.reward[id=star]
+ $.Tome01.level[2].nodes.nodeSurvivorTask05.reward[id=star]
+ $.Tome01.level[2].taskRewards[id=star]
+ $.Tome01.level[3].challengeRewards[id=star]
+ $.Tome01.level[3].endNodeRewards[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge01.reward[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge02.reward[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge03.reward[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge04.reward[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge05.reward[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge06.reward[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge07.reward[id=star]
+ $.Tome01.level[3].nodes.nodeKillerChallenge08.reward[id=star]
+ $.Tome01.level[3].nodes.nodeSurvivorChallenge01.reward[id=star]
+ $.Tome01.level[3].nodes.nodeSurvivorChallenge02.reward[id=star]
+ $.Tome01.level[3].nodes.nodeSurvivorChallenge03.reward[id=star]
+ $.Tome01.level[3].nodes.nodeSurvivorChallenge04.reward[id=star]
+ $.Tome01.level[3].nodes.nodeSurvivorChallenge05.reward[id=star]
+ $.Tome01.level[3].nodes.nodeSurvivorChallenge06.reward[id=star]
+ $.Tome01.level[3].nodes.nodeSurvivorChallenge07.reward[id=star]
+ $.Tome01.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome02.json`](archiveQuests/Tome02.json)

[Full line-by-line diff](diffs/archiveQuests/Tome02.json.diff)

```diff
+ $.Tome02.level[0].challengeRewards[id=star]
+ $.Tome02.level[0].endNodeRewards[id=star]
+ $.Tome02.level[0].nodes.node_L1_01.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_02.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_03.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_04.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_05.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_06.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_07.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_08.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_09.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_10.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_11.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_12.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_13.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_14.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_15.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_16.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_17.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_18.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_19.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_20.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_21.reward[id=star]
+ $.Tome02.level[0].nodes.node_L1_22.reward[id=star]
+ $.Tome02.level[0].taskRewards[id=star]
+ $.Tome02.level[1].challengeRewards[id=star]
+ $.Tome02.level[1].endNodeRewards[id=star]
+ $.Tome02.level[1].nodes.node_L2_01.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_02.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_03.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_04.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_05.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_06.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_07.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_08.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_09.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_10.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_11.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_12.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_13.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_14.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_15.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_16.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_17.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_18.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_19.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_20.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_21.reward[id=star]
+ $.Tome02.level[1].nodes.node_L2_22.reward[id=star]
+ $.Tome02.level[1].taskRewards[id=star]
+ $.Tome02.level[2].challengeRewards[id=star]
+ $.Tome02.level[2].endNodeRewards[id=star]
+ $.Tome02.level[2].nodes.node_L3_01.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_02.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_03.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_04.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_05.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_06.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_07.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_08.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_09.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_10.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_11.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_12.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_13.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_14.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_15.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_16.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_17.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_18.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_19.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_20.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_21.reward[id=star]
+ $.Tome02.level[2].nodes.node_L3_22.reward[id=star]
+ $.Tome02.level[2].taskRewards[id=star]
+ $.Tome02.level[3].challengeRewards[id=star]
+ $.Tome02.level[3].endNodeRewards[id=star]
+ $.Tome02.level[3].nodes.node_L4_01.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_02.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_03.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_04.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_05.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_06.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_07.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_08.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_09.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_10.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_11.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_12.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_13.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_14.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_15.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_16.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_17.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_18.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_19.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_20.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_21.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_22.reward[id=star]
+ $.Tome02.level[3].nodes.node_L4_23.reward[id=star]
+ $.Tome02.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome03.json`](archiveQuests/Tome03.json)

[Full line-by-line diff](diffs/archiveQuests/Tome03.json.diff)

```diff
+ $.Tome03.level[0].challengeRewards[id=star]
+ $.Tome03.level[0].endNodeRewards[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_01.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_02.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_04.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_05.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_06.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_07.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_08.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_10.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_11.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_12.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_13.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_14.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_15.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_16.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_17.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_19.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_20.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_21.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_22.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_23.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_25.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_26.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_27.reward[id=star]
+ $.Tome03.level[0].nodes.node_T3L1_28.reward[id=star]
+ $.Tome03.level[0].taskRewards[id=star]
+ $.Tome03.level[1].challengeRewards[id=star]
+ $.Tome03.level[1].endNodeRewards[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_01.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_02.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_04.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_05.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_06.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_07.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_08.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_10.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_11.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_12.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_13.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_14.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_15.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_17.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_19.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_20.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_21.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_22.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_23.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_25.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_26.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_27.reward[id=star]
+ $.Tome03.level[1].nodes.node_T3L2_28.reward[id=star]
+ $.Tome03.level[1].taskRewards[id=star]
+ $.Tome03.level[2].challengeRewards[id=star]
+ $.Tome03.level[2].endNodeRewards[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_02.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_03.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_04.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_05.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_07.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_08.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_09.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_10.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_11.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_12.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_13.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_14.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_15.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_18.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_20.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_21.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_22.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_23.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_24.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_25.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_26.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_27.reward[id=star]
+ $.Tome03.level[2].nodes.node_T3L3_28.reward[id=star]
+ $.Tome03.level[2].taskRewards[id=star]
+ $.Tome03.level[3].challengeRewards[id=star]
+ $.Tome03.level[3].endNodeRewards[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_02.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_03.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_04.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_05.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_07.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_08.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_09.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_11.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_12.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_13.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_14.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_15.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_16.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_18.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_19.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_20.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_21.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_22.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_23.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_24.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_25.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_26.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_27.reward[id=star]
+ $.Tome03.level[3].nodes.node_T3L4_28.reward[id=star]
+ $.Tome03.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome04.json`](archiveQuests/Tome04.json)

[Full line-by-line diff](diffs/archiveQuests/Tome04.json.diff)

```diff
+ $.Tome04.level[0].challengeRewards[id=star]
+ $.Tome04.level[0].endNodeRewards[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_01.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_02.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_03.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_04.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_05.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_06.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_07.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_08.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_09.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_10.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_11.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_12.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_13.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_14.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_15.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_16.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_17.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_18.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_19.reward[id=star]
+ $.Tome04.level[0].nodes.node_T4L1_20.reward[id=star]
+ $.Tome04.level[0].taskRewards[id=star]
+ $.Tome04.level[1].challengeRewards[id=star]
+ $.Tome04.level[1].endNodeRewards[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_01.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_02.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_03.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_04.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_05.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_06.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_07.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_08.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_09.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_10.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_11.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_12.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_13.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_14.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_15.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_16.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_17.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_18.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_19.reward[id=star]
+ $.Tome04.level[1].nodes.node_T4L2_20.reward[id=star]
+ $.Tome04.level[1].taskRewards[id=star]
+ $.Tome04.level[2].challengeRewards[id=star]
+ $.Tome04.level[2].endNodeRewards[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_01.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_02.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_03.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_04.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_05.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_06.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_07.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_08.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_09.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_10.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_11.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_12.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_13.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_14.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_15.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_16.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_17.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_18.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_19.reward[id=star]
+ $.Tome04.level[2].nodes.node_T4L3_20.reward[id=star]
+ $.Tome04.level[2].taskRewards[id=star]
+ $.Tome04.level[3].challengeRewards[id=star]
+ $.Tome04.level[3].endNodeRewards[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_01.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_02.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_03.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_04.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_05.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_06.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_07.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_08.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_09.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_10.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_11.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_12.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_13.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_14.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_15.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_16.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_17.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_18.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_19.reward[id=star]
+ $.Tome04.level[3].nodes.node_T4L4_20.reward[id=star]
+ $.Tome04.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome05.json`](archiveQuests/Tome05.json)

[Full line-by-line diff](diffs/archiveQuests/Tome05.json.diff)

```diff
+ $.Tome05.level[0].challengeRewards[id=star]
+ $.Tome05.level[0].endNodeRewards[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_01.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_03.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_04.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_05.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_06.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_07.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_08.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_09.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_10.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_11.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_12.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_13.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_14.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_15.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_16.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_17.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_18.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_19.reward[id=star]
+ $.Tome05.level[0].nodes.node_T5L1_20.reward[id=star]
+ $.Tome05.level[0].taskRewards[id=star]
+ $.Tome05.level[1].challengeRewards[id=star]
+ $.Tome05.level[1].endNodeRewards[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_01.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_02.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_03.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_04.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_05.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_06.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_07.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_08.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_09.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_10.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_11.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_12.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_13.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_14.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_15.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_16.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_17.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_18.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_19.reward[id=star]
+ $.Tome05.level[1].nodes.node_T5L2_20.reward[id=star]
+ $.Tome05.level[1].taskRewards[id=star]
+ $.Tome05.level[2].challengeRewards[id=star]
+ $.Tome05.level[2].endNodeRewards[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_01.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_02.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_03.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_04.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_05.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_06.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_07.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_08.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_09.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_10.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_11.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_12.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_13.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_14.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_15.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_16.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_17.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_18.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_19.reward[id=star]
+ $.Tome05.level[2].nodes.node_T5L3_20.reward[id=star]
+ $.Tome05.level[2].taskRewards[id=star]
+ $.Tome05.level[3].challengeRewards[id=star]
+ $.Tome05.level[3].endNodeRewards[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_01.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_02.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_03.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_04.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_05.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_06.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_07.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_08.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_09.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_10.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_11.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_12.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_13.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_14.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_15.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_16.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_17.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_18.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_19.reward[id=star]
+ $.Tome05.level[3].nodes.node_T5L4_20.reward[id=star]
+ $.Tome05.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome06.json`](archiveQuests/Tome06.json)

[Full line-by-line diff](diffs/archiveQuests/Tome06.json.diff)

```diff
+ $.Tome06.level[0].challengeRewards[id=star]
+ $.Tome06.level[0].endNodeRewards[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_01.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_02.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_03.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_04.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_05.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_06.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_07.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_08.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_09.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_10.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_11.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_12.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_13.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_14.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_15.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_16.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_17.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_18.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_19.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_20.reward[id=star]
+ $.Tome06.level[0].nodes.node_T6L1_Glyph.reward[id=star]
+ $.Tome06.level[0].taskRewards[id=star]
+ $.Tome06.level[1].challengeRewards[id=star]
+ $.Tome06.level[1].endNodeRewards[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_01.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_02.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_03.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_04.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_05.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_06.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_07.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_08.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_09.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_10.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_11.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_12.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_13.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_14.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_15.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_16.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_17.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_18.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_19.reward[id=star]
+ $.Tome06.level[1].nodes.node_T6L2_Glyph.reward[id=star]
+ $.Tome06.level[1].taskRewards[id=star]
+ $.Tome06.level[2].challengeRewards[id=star]
+ $.Tome06.level[2].endNodeRewards[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_01.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_02.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_03.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_04.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_05.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_06.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_07.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_08.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_09.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_10.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_11.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_12.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_13.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_14.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_15.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_16.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_17.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_18.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_19.reward[id=star]
+ $.Tome06.level[2].nodes.node_T6L3_Glyph.reward[id=star]
+ $.Tome06.level[2].taskRewards[id=star]
+ $.Tome06.level[3].challengeRewards[id=star]
+ $.Tome06.level[3].endNodeRewards[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_01.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_02.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_03.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_04.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_05.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_06.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_07.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_08.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_09.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_10.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_11.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_12.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_13.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_14.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_15.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_16.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_17.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_18.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_19.reward[id=star]
+ $.Tome06.level[3].nodes.node_T6L4_Glyph.reward[id=star]
+ $.Tome06.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome07.json`](archiveQuests/Tome07.json)

[Full line-by-line diff](diffs/archiveQuests/Tome07.json.diff)

```diff
+ $.Tome07.level[0].challengeRewards[id=star]
+ $.Tome07.level[0].endNodeRewards[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_01.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_02.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_03.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_04.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_05.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_06.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_07.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_08.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_09.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_10.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_11.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_12.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_13.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_14.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_15.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_16.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_17.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_18.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_19.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_20.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_21.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_22.reward[id=star]
+ $.Tome07.level[0].nodes.node_T7L1_Glyph01.reward[id=star]
+ $.Tome07.level[0].taskRewards[id=star]
+ $.Tome07.level[1].challengeRewards[id=star]
+ $.Tome07.level[1].endNodeRewards[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_01.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_02.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_03.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_04.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_05.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_06.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_07.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_08.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_09.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_10.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_11.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_12.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_13.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_14.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_15.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_16.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_17.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_18.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_19.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_20.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_21.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_22.reward[id=star]
+ $.Tome07.level[1].nodes.node_T7L2_Glyph01.reward[id=star]
+ $.Tome07.level[1].taskRewards[id=star]
+ $.Tome07.level[2].challengeRewards[id=star]
+ $.Tome07.level[2].endNodeRewards[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_01.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_02.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_03.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_04.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_05.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_06.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_07.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_08.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_09.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_10.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_11.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_12.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_13.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_14.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_15.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_16.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_17.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_18.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_19.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_20.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_21.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_22.reward[id=star]
+ $.Tome07.level[2].nodes.node_T7L3_Glyph01.reward[id=star]
+ $.Tome07.level[2].taskRewards[id=star]
+ $.Tome07.level[3].challengeRewards[id=star]
+ $.Tome07.level[3].endNodeRewards[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_01.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_02.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_03.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_04.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_05.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_06.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_07.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_08.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_09.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_10.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_11.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_12.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_13.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_14.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_15.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_16.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_17.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_18.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_19.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_20.reward[id=star]
+ $.Tome07.level[3].nodes.node_T7L4_Glyph01.reward[id=star]
+ $.Tome07.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome08.json`](archiveQuests/Tome08.json)

[Full line-by-line diff](diffs/archiveQuests/Tome08.json.diff)

```diff
+ $.Tome08.level[0].challengeRewards[id=star]
+ $.Tome08.level[0].endNodeRewards[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_01.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_02.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_03.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_04.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_05.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_06.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_07.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_08.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_09.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_10.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_11.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_12.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_13.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_14.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_15.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_16.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_17.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_18.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_19.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_20.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_21.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_22.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_Glyph01.reward[id=star]
+ $.Tome08.level[0].nodes.node_T8L1_Glyph02.reward[id=star]
+ $.Tome08.level[0].taskRewards[id=star]
+ $.Tome08.level[1].challengeRewards[id=star]
+ $.Tome08.level[1].endNodeRewards[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_01.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_02.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_03.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_04.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_05.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_06.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_07.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_08.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_09.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_10.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_11.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_12.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_13.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_14.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_15.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_16.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_17.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_18.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_19.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_20.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_21.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_22.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_23.reward[id=star]
+ $.Tome08.level[1].nodes.node_T8L2_Glyph01.reward[id=star]
+ $.Tome08.level[1].taskRewards[id=star]
+ $.Tome08.level[2].challengeRewards[id=star]
+ $.Tome08.level[2].endNodeRewards[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_01.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_02.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_03.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_04.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_05.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_06.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_07.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_08.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_09.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_10.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_11.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_12.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_13.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_14.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_15.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_16.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_17.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_18.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_19.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_20.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_21.reward[id=star]
+ $.Tome08.level[2].nodes.node_T8L3_Glyph01.reward[id=star]
+ $.Tome08.level[2].taskRewards[id=star]
+ $.Tome08.level[3].challengeRewards[id=star]
+ $.Tome08.level[3].endNodeRewards[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_01.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_02.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_03.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_04.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_05.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_06.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_07.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_08.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_09.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_10.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_11.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_12.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_13.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_14.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_15.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_16.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_17.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_18.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_Glyph01.reward[id=star]
+ $.Tome08.level[3].nodes.node_T8L4_Glyph02.reward[id=star]
+ $.Tome08.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome09.json`](archiveQuests/Tome09.json)

[Full line-by-line diff](diffs/archiveQuests/Tome09.json.diff)

```diff
+ $.Tome09.level[0].challengeRewards[id=star]
+ $.Tome09.level[0].endNodeRewards[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_01.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_02.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_03.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_04.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_05.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_06.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_07.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_08.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_09.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_10.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_11.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_12.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_13.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_14.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_15.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_16.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_17.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_19.reward[id=star]
+ $.Tome09.level[0].nodes.node_T9L1_Glyph01.reward[id=star]
+ $.Tome09.level[0].taskRewards[id=star]
+ $.Tome09.level[1].challengeRewards[id=star]
+ $.Tome09.level[1].endNodeRewards[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_01.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_02.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_03.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_04.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_05.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_06.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_07.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_08.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_09.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_10.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_11.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_12.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_13.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_14.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_15.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_16.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_17.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_Glyph01.reward[id=star]
+ $.Tome09.level[1].nodes.node_T9L2_Glyph02.reward[id=star]
+ $.Tome09.level[1].taskRewards[id=star]
+ $.Tome09.level[2].challengeRewards[id=star]
+ $.Tome09.level[2].endNodeRewards[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_01.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_02.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_03.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_04.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_05.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_06.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_07.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_08.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_09.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_10.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_11.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_12.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_13.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_14.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_15.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_Glyph01.reward[id=star]
+ $.Tome09.level[2].nodes.node_T9L3_Glyph02.reward[id=star]
+ $.Tome09.level[2].taskRewards[id=star]
+ $.Tome09.level[3].challengeRewards[id=star]
+ $.Tome09.level[3].endNodeRewards[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_01.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_02.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_03.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_04.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_05.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_06.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_07.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_08.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_09.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_11.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_12.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_13.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_14.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_15.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_Glyph01.reward[id=star]
+ $.Tome09.level[3].nodes.node_T9L4_Glyph02.reward[id=star]
+ $.Tome09.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome10.json`](archiveQuests/Tome10.json)

[Full line-by-line diff](diffs/archiveQuests/Tome10.json.diff)

```diff
+ $.Tome10.level[0].challengeRewards[id=star]
+ $.Tome10.level[0].endNodeRewards[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_01.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_02.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_03.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_04.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_05.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_06.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_07.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_08.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_09.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_10.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_11.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_12.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_13.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_14.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_15.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_16.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_17.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_18.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_19.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_20.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_21.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_22.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_Glyph01.reward[id=star]
+ $.Tome10.level[0].nodes.node_T10L1_Glyph02.reward[id=star]
+ $.Tome10.level[0].taskRewards[id=star]
+ $.Tome10.level[1].challengeRewards[id=star]
+ $.Tome10.level[1].endNodeRewards[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_01.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_02.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_03.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_04.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_05.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_06.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_07.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_08.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_09.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_10.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_11.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_12.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_13.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_14.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_15.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_16.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_17.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_18.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_19.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_20.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_Glyph01.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_Glyph02.reward[id=star]
+ $.Tome10.level[1].nodes.node_T10L2_Glyph03.reward[id=star]
+ $.Tome10.level[1].taskRewards[id=star]
+ $.Tome10.level[2].challengeRewards[id=star]
+ $.Tome10.level[2].endNodeRewards[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_01.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_02.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_03.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_04.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_05.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_06.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_07.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_08.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_09.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_10.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_11.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_12.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_13.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_14.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_15.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_16.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_17.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_18.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_19.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_20.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_Glyph01.reward[id=star]
+ $.Tome10.level[2].nodes.node_T10L3_Glyph02.reward[id=star]
+ $.Tome10.level[2].taskRewards[id=star]
+ $.Tome10.level[3].challengeRewards[id=star]
+ $.Tome10.level[3].endNodeRewards[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_01.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_02.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_03.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_04.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_05.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_06.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_07.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_08.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_09.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_10.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_11.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_12.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_13.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_14.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_15.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_16.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_17.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_18.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_19.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_20.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_21.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_22.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_Glyph01.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_Glyph02.reward[id=star]
+ $.Tome10.level[3].nodes.node_T10L4_Glyph03.reward[id=star]
+ $.Tome10.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome11.json`](archiveQuests/Tome11.json)

[Full line-by-line diff](diffs/archiveQuests/Tome11.json.diff)

```diff
+ $.Tome11.level[0].challengeRewards[id=star]
+ $.Tome11.level[0].endNodeRewards[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_01.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_02.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_03.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_04.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_05.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_06.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_07.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_08.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_09.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_10.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_11.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_12.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_13.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_14.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_15.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_16.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_17.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_18.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_19.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_20.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_Glyph01.reward[id=star]
+ $.Tome11.level[0].nodes.node_T11L1_Glyph02.reward[id=star]
+ $.Tome11.level[0].taskRewards[id=star]
+ $.Tome11.level[1].challengeRewards[id=star]
+ $.Tome11.level[1].endNodeRewards[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_01.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_02.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_03.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_04.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_05.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_06.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_07.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_08.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_09.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_10.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_11.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_12.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_13.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_14.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_15.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_16.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_17.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_18.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_19.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_20.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_21.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_Glyph01.reward[id=star]
+ $.Tome11.level[1].nodes.node_T11L2_Glyph02.reward[id=star]
+ $.Tome11.level[1].taskRewards[id=star]
+ $.Tome11.level[2].challengeRewards[id=star]
+ $.Tome11.level[2].endNodeRewards[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_01.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_02.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_03.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_04.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_05.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_06.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_07.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_08.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_09.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_10.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_11.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_12.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_13.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_14.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_15.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_16.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_17.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_18.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_19.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_20.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_21.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_22.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_Glyph01.reward[id=star]
+ $.Tome11.level[2].nodes.node_T11L3_Glyph02.reward[id=star]
+ $.Tome11.level[2].taskRewards[id=star]
+ $.Tome11.level[3].challengeRewards[id=star]
+ $.Tome11.level[3].endNodeRewards[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_01.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_02.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_03.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_04.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_05.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_06.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_07.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_08.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_09.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_10.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_11.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_12.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_13.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_14.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_15.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_16.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_17.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_18.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_Glyph01.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_Glyph02.reward[id=star]
+ $.Tome11.level[3].nodes.node_T11L4_Glyph03.reward[id=star]
+ $.Tome11.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome12.json`](archiveQuests/Tome12.json)

[Full line-by-line diff](diffs/archiveQuests/Tome12.json.diff)

```diff
+ $.Tome12.level[0].challengeRewards[id=star]
+ $.Tome12.level[0].endNodeRewards[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_01.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_02.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_03.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_04.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_05.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_06.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_07.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_09.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_10.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_11.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_12.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_13.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_14.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_15.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_16.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_17.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_18.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_19.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_20.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_21.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_Glyph01.reward[id=star]
+ $.Tome12.level[0].nodes.node_T12L1_Glyph02.reward[id=star]
+ $.Tome12.level[0].taskRewards[id=star]
+ $.Tome12.level[1].challengeRewards[id=star]
+ $.Tome12.level[1].endNodeRewards[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_01.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_02.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_03.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_04.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_05.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_06.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_07.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_08.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_09.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_10.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_11.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_12.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_13.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_14.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_15.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_16.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_17.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_18.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_19.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_Glyph01.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_Glyph02.reward[id=star]
+ $.Tome12.level[1].nodes.node_T12L2_Glyph03.reward[id=star]
+ $.Tome12.level[1].taskRewards[id=star]
+ $.Tome12.level[2].challengeRewards[id=star]
+ $.Tome12.level[2].endNodeRewards[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_01.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_02.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_03.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_04.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_05.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_06.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_07.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_08.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_09.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_10.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_11.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_12.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_13.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_14.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_15.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_16.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_17.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_18.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_19.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_20.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_Glyph01.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_Glyph02.reward[id=star]
+ $.Tome12.level[2].nodes.node_T12L3_Glyph03.reward[id=star]
+ $.Tome12.level[2].taskRewards[id=star]
+ $.Tome12.level[3].challengeRewards[id=star]
+ $.Tome12.level[3].endNodeRewards[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_01.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_02.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_03.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_04.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_05.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_06.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_07.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_08.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_09.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_10.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_11.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_12.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_13.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_14.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_15.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_16.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_17.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_18.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_Glyph01.reward[id=star]
+ $.Tome12.level[3].nodes.node_T12L4_Glyph02.reward[id=star]
+ $.Tome12.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome13.json`](archiveQuests/Tome13.json)

[Full line-by-line diff](diffs/archiveQuests/Tome13.json.diff)

```diff
+ $.Tome13.level[0].challengeRewards[id=star]
+ $.Tome13.level[0].endNodeRewards[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_01.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_02.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_03.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_04.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_05.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_06.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_07.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_08.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_09.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_10.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_11.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_12.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_13.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_14.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_15.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_16.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_17.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_Glyph01.reward[id=star]
+ $.Tome13.level[0].nodes.node_T13_L1_Glyph02.reward[id=star]
+ $.Tome13.level[0].taskRewards[id=star]
+ $.Tome13.level[1].challengeRewards[id=star]
+ $.Tome13.level[1].endNodeRewards[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_01.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_02.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_03.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_04.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_05.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_06.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_07.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_08.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_09.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_10.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_11.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_12.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_13.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_14.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_15.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_16.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_17.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_Glyph01.reward[id=star]
+ $.Tome13.level[1].nodes.node_T13_L2_Glyph02.reward[id=star]
+ $.Tome13.level[1].taskRewards[id=star]
+ $.Tome13.level[2].challengeRewards[id=star]
+ $.Tome13.level[2].endNodeRewards[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_01.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_02.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_03.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_04.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_05.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_06.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_07.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_08.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_09.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_10.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_11.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_12.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_13.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_14.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_15.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_16.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_17.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_Glyph01.reward[id=star]
+ $.Tome13.level[2].nodes.node_T13_L3_Glyph02.reward[id=star]
+ $.Tome13.level[2].taskRewards[id=star]
+ $.Tome13.level[3].challengeRewards[id=star]
+ $.Tome13.level[3].endNodeRewards[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_01.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_02.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_03.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_04.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_05.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_06.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_07.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_08.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_09.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_10.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_11.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_12.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_13.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_14.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_15.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_16.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_17.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_18.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_Glyph01.reward[id=star]
+ $.Tome13.level[3].nodes.node_T13_L4_Glyph02.reward[id=star]
+ $.Tome13.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome14.json`](archiveQuests/Tome14.json)

[Full line-by-line diff](diffs/archiveQuests/Tome14.json.diff)

```diff
+ $.Tome14.level[0].challengeRewards[id=star]
+ $.Tome14.level[0].endNodeRewards[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_01.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_02.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_03.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_04.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_05.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_06.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_07.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_08.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_09.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_10.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_11.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_12.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_13.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_14.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_15.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_16.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_17.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_18.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_19.reward[id=star]
+ $.Tome14.level[0].nodes.node_T14_L1_Glyph01.reward[id=star]
+ $.Tome14.level[0].taskRewards[id=star]
+ $.Tome14.level[1].challengeRewards[id=star]
+ $.Tome14.level[1].endNodeRewards[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_01.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_02.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_03.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_04.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_05.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_06.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_07.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_08.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_09.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_10.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_11.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_12.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_13.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_14.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_15.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_16.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_17.reward[id=star]
+ $.Tome14.level[1].nodes.node_T14_L2_Glyph01.reward[id=star]
+ $.Tome14.level[1].taskRewards[id=star]
+ $.Tome14.level[2].challengeRewards[id=star]
+ $.Tome14.level[2].endNodeRewards[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_01.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_02.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_03.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_04.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_05.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_06.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_07.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_08.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_09.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_10.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_11.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_12.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_13.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_14.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_15.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_16.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_Glyph01.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_Glyph02.reward[id=star]
+ $.Tome14.level[2].nodes.node_T14_L3_Glyph03.reward[id=star]
+ $.Tome14.level[2].taskRewards[id=star]
+ $.Tome14.level[3].challengeRewards[id=star]
+ $.Tome14.level[3].endNodeRewards[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_01.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_02.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_03.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_04.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_05.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_06.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_07.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_08.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_09.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_10.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_11.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_12.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_13.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_14.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_15.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_16.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_17.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_Glyph01.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_Glyph02.reward[id=star]
+ $.Tome14.level[3].nodes.node_T14_L4_Glyph03.reward[id=star]
+ $.Tome14.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome15.json`](archiveQuests/Tome15.json)

[Full line-by-line diff](diffs/archiveQuests/Tome15.json.diff)

```diff
+ $.Tome15.level[0].challengeRewards[id=star]
+ $.Tome15.level[0].endNodeRewards[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_01.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_02.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_03.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_04.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_05.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_06.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_07.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_08.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_09.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_10.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_11.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_12.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_13.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_14.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_15.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_16.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_17.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_18.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_19.reward[id=star]
+ $.Tome15.level[0].nodes.node_T15_L1_CM01.reward[id=star]
+ $.Tome15.level[0].taskRewards[id=star]
+ $.Tome15.level[1].challengeRewards[id=star]
+ $.Tome15.level[1].endNodeRewards[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_01.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_02.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_03.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_04.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_05.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_06.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_07.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_08.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_09.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_10.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_11.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_12.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_13.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_14.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_15.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_16.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_17.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_18.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_CM01.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_Glyph01.reward[id=star]
+ $.Tome15.level[1].nodes.node_T15_L2_Glyph02.reward[id=star]
+ $.Tome15.level[1].taskRewards[id=star]
+ $.Tome15.level[2].challengeRewards[id=star]
+ $.Tome15.level[2].endNodeRewards[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_01.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_02.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_03.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_04.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_05.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_06.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_07.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_08.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_09.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_10.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_11.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_12.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_13.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_14.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_15.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_16.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_17.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_CM01.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_Glyph01.reward[id=star]
+ $.Tome15.level[2].nodes.node_T15_L3_Glyph02.reward[id=star]
+ $.Tome15.level[2].taskRewards[id=star]
+ $.Tome15.level[3].challengeRewards[id=star]
+ $.Tome15.level[3].endNodeRewards[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_01.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_02.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_03.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_04.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_05.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_06.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_07.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_08.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_09.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_10.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_11.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_12.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_13.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_14.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_15.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_16.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_17.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_CM01.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_Glyph01.reward[id=star]
+ $.Tome15.level[3].nodes.node_T15_L4_Glyph02.reward[id=star]
+ $.Tome15.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome16.json`](archiveQuests/Tome16.json)

[Full line-by-line diff](diffs/archiveQuests/Tome16.json.diff)

```diff
+ $.Tome16.level[0].challengeRewards[id=star]
+ $.Tome16.level[0].endNodeRewards[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_01.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_02.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_03.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_04.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_05.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_06.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_07.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_08.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_09.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_10.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_11.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_12.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_14.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_15.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_16.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_17.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_18.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_19.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_20.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_CM01.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_Glyph01.reward[id=star]
+ $.Tome16.level[0].nodes.node_T16_L1_Glyph02.reward[id=star]
+ $.Tome16.level[0].taskRewards[id=star]
+ $.Tome16.level[1].challengeRewards[id=star]
+ $.Tome16.level[1].endNodeRewards[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_01.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_02.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_03.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_04.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_05.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_06.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_07.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_08.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_09.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_10.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_11.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_12.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_13.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_14.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_15.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_16.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_17.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_18.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_19.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_20.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_CM1.reward[id=star]
+ $.Tome16.level[1].nodes.node_T16_L2_Glyph01.reward[id=star]
+ $.Tome16.level[1].taskRewards[id=star]
+ $.Tome16.level[2].challengeRewards[id=star]
+ $.Tome16.level[2].endNodeRewards[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_01.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_02.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_03.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_04.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_05.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_07.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_08.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_09.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_10.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_11.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_12.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_13.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_14.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_15.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_16.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_17.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_18.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_19.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_20.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_Glyph01.reward[id=star]
+ $.Tome16.level[2].nodes.node_T16_L3_Glyph02.reward[id=star]
+ $.Tome16.level[2].taskRewards[id=star]
+ $.Tome16.level[3].challengeRewards[id=star]
+ $.Tome16.level[3].endNodeRewards[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_01.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_02.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_03.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_04.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_05.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_06.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_07.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_08.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_09.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_10.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_11.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_12.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_13.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_14.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_15.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_16.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_17.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_18.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_19.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_CM01.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_Glyph01.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_Glyph02.reward[id=star]
+ $.Tome16.level[3].nodes.node_T16_L4_Glyph03.reward[id=star]
+ $.Tome16.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome17.json`](archiveQuests/Tome17.json)

[Full line-by-line diff](diffs/archiveQuests/Tome17.json.diff)

```diff
+ $.Tome17.level[0].challengeRewards[id=star]
+ $.Tome17.level[0].endNodeRewards[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_01.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_02.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_03.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_04.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_05.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_06.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_07.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_08.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_09.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_10.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_11.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_12.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_13.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_CM01.reward[id=star]
+ $.Tome17.level[0].nodes.node_T17_L1_Glyph01.reward[id=star]
+ $.Tome17.level[0].taskRewards[id=star]
+ $.Tome17.level[1].challengeRewards[id=star]
+ $.Tome17.level[1].endNodeRewards[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_01.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_02.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_03.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_04.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_05.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_06.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_07.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_08.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_09.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_10.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_11.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_12.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_CM01.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_Glyph01.reward[id=star]
+ $.Tome17.level[1].nodes.node_T17_L2_Glyph02.reward[id=star]
+ $.Tome17.level[1].taskRewards[id=star]
+ $.Tome17.level[2].challengeRewards[id=star]
+ $.Tome17.level[2].endNodeRewards[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_01.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_02.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_03.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_04.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_05.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_06.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_07.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_08.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_09.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_10.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_11.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_12.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_13.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_14.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_15.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_16.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_17.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_18.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_CM01.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_Glyph01.reward[id=star]
+ $.Tome17.level[2].nodes.node_T17_L3_Glyph02.reward[id=star]
+ $.Tome17.level[2].taskRewards[id=star]
+ $.Tome17.level[3].challengeRewards[id=star]
+ $.Tome17.level[3].endNodeRewards[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_01.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_02.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_03.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_04.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_05.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_06.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_07.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_08.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_09.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_10.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_11.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_12.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_13.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_14.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_15.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_16.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_17.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_CM01.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_Glyph01.reward[id=star]
+ $.Tome17.level[3].nodes.node_T17_L4_Glyph02.reward[id=star]
+ $.Tome17.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome18.json`](archiveQuests/Tome18.json)

[Full line-by-line diff](diffs/archiveQuests/Tome18.json.diff)

```diff
+ $.Tome18.level[0].challengeRewards[id=star]
+ $.Tome18.level[0].endNodeRewards[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_01.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_02.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_03.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_04.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_05.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_06.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_07.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_08.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_09.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_10.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_11.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_12.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_13.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_14.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_15.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_16.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_CM01.reward[id=star]
+ $.Tome18.level[0].nodes.node_T18_L1_Glyph01.reward[id=star]
+ $.Tome18.level[0].taskRewards[id=star]
+ $.Tome18.level[1].challengeRewards[id=star]
+ $.Tome18.level[1].endNodeRewards[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_01.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_02.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_03.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_04.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_05.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_06.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_07.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_08.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_09.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_10.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_11.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_12.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_13.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_CM01.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_Glyph01.reward[id=star]
+ $.Tome18.level[1].nodes.node_T18_L2_Glyph02.reward[id=star]
+ $.Tome18.level[1].taskRewards[id=star]
+ $.Tome18.level[2].challengeRewards[id=star]
+ $.Tome18.level[2].endNodeRewards[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_01.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_02.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_03.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_04.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_05.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_06.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_07.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_08.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_09.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_10.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_11.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_12.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_13.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_14.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_15.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_CM01.reward[id=star]
+ $.Tome18.level[2].nodes.node_T18_L3_Glyph01.reward[id=star]
+ $.Tome18.level[2].taskRewards[id=star]
+ $.Tome18.level[3].challengeRewards[id=star]
+ $.Tome18.level[3].endNodeRewards[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_01.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_02.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_03.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_04.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_05.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_06.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_07.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_08.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_09.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_10.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_11.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_12.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_13.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_14.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_15.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_16.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_CM01.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_Glyph01.reward[id=star]
+ $.Tome18.level[3].nodes.node_T18_L4_Glyph02.reward[id=star]
+ $.Tome18.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome19.json`](archiveQuests/Tome19.json)

[Full line-by-line diff](diffs/archiveQuests/Tome19.json.diff)

```diff
+ $.Tome19.level[0].challengeRewards[id=star]
+ $.Tome19.level[0].endNodeRewards[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_01.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_02.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_03.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_04.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_05.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_06.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_07.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_08.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_09.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_10.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_11.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_12.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_13.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_14.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_15.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_CM01.reward[id=star]
+ $.Tome19.level[0].nodes.node_T19_L1_Glyph01.reward[id=star]
+ $.Tome19.level[0].taskRewards[id=star]
+ $.Tome19.level[1].challengeRewards[id=star]
+ $.Tome19.level[1].endNodeRewards[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_01.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_02.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_03.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_04.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_05.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_06.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_07.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_08.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_09.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_10.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_11.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_12.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_13.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_14.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_15.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_16.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_CM1.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_End01.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_Glyph01.reward[id=star]
+ $.Tome19.level[1].nodes.node_T19_L2_Start01.reward[id=star]
+ $.Tome19.level[1].taskRewards[id=star]
+ $.Tome19.level[2].challengeRewards[id=star]
+ $.Tome19.level[2].endNodeRewards[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_01.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_02.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_03.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_04.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_05.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_06.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_07.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_08.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_09.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_10.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_11.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_12.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_13.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_14.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_15.reward[id=star]
+ $.Tome19.level[2].nodes.node_T19_L3_Glyph01.reward[id=star]
+ $.Tome19.level[2].taskRewards[id=star]
+ $.Tome19.level[3].challengeRewards[id=star]
+ $.Tome19.level[3].endNodeRewards[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_01.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_02.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_03.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_04.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_05.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_06.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_07.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_08.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_09.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_10.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_11.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_12.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_13.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_14.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_15.reward[id=star]
+ $.Tome19.level[3].nodes.node_T19_L4_16.reward[id=star]
+ $.Tome19.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome20.json`](archiveQuests/Tome20.json)

[Full line-by-line diff](diffs/archiveQuests/Tome20.json.diff)

```diff
+ $.Tome20.level[0].challengeRewards[id=star]
+ $.Tome20.level[0].endNodeRewards[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_01.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_02.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_03.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_04.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_05.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_06.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_07.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_08.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_09.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_10.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_11.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_12.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_13.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_14.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_15.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_16.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_17.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_CM01.reward[id=star]
+ $.Tome20.level[0].nodes.node_T20_L1_Glyph01.reward[id=star]
+ $.Tome20.level[0].taskRewards[id=star]
+ $.Tome20.level[1].challengeRewards[id=star]
+ $.Tome20.level[1].endNodeRewards[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_01.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_02.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_03.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_04.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_05.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_06.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_07.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_08.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_09.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_10.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_11.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_12.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_13.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_14.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_15.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_16.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_17.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_CM01.reward[id=star]
+ $.Tome20.level[1].nodes.node_T20_L2_Glyph01.reward[id=star]
+ $.Tome20.level[1].taskRewards[id=star]
+ $.Tome20.level[2].challengeRewards[id=star]
+ $.Tome20.level[2].endNodeRewards[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_01.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_02.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_03.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_04.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_05.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_06.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_07.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_08.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_09.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_10.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_11.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_12.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_13.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_14.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_15.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_16.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_CM01.reward[id=star]
+ $.Tome20.level[2].nodes.node_T20_L3_Glyph01.reward[id=star]
+ $.Tome20.level[2].taskRewards[id=star]
+ $.Tome20.level[3].challengeRewards[id=star]
+ $.Tome20.level[3].endNodeRewards[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_01.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_02.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_03.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_04.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_05.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_06.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_07.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_08.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_09.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_10.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_11.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_12.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_13.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_14.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_15.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_16.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_CM01.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_Glyph01.reward[id=star]
+ $.Tome20.level[3].nodes.node_T20_L4_Glyph02.reward[id=star]
+ $.Tome20.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome21.json`](archiveQuests/Tome21.json)

[Full line-by-line diff](diffs/archiveQuests/Tome21.json.diff)

```diff
+ $.Tome21.level[0].challengeRewards[id=star]
+ $.Tome21.level[0].endNodeRewards[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_01.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_02.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_03.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_04.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_05.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_06.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_07.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_08.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_09.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_10.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_11.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_12.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_13.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_14.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_15.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_CM01.reward[id=star]
+ $.Tome21.level[0].nodes.node_T21_L1_Glyph01.reward[id=star]
+ $.Tome21.level[0].taskRewards[id=star]
+ $.Tome21.level[1].challengeRewards[id=star]
+ $.Tome21.level[1].endNodeRewards[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_01.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_02.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_03.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_04.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_05.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_06.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_07.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_08.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_09.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_10.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_11.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_12.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_13.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_14.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_15.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_16.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_CM1.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_End01.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_Glyph01.reward[id=star]
+ $.Tome21.level[1].nodes.node_T21_L2_Start01.reward[id=star]
+ $.Tome21.level[1].taskRewards[id=star]
+ $.Tome21.level[2].challengeRewards[id=star]
+ $.Tome21.level[2].endNodeRewards[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_01.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_02.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_03.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_04.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_05.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_06.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_07.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_08.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_09.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_10.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_11.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_12.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_13.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_14.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_15.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_CM1.reward[id=star]
+ $.Tome21.level[2].nodes.node_T21_L3_Glyph01.reward[id=star]
+ $.Tome21.level[2].taskRewards[id=star]
+ $.Tome21.level[3].challengeRewards[id=star]
+ $.Tome21.level[3].endNodeRewards[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_01.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_02.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_03.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_04.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_05.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_06.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_07.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_08.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_09.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_10.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_11.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_12.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_13.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_14.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_CM1.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_Glyph01.reward[id=star]
+ $.Tome21.level[3].nodes.node_T21_L4_Glyph02.reward[id=star]
+ $.Tome21.level[3].taskRewards[id=star]
```

### [`archiveQuests/Tome22.json`](archiveQuests/Tome22.json)

[Full line-by-line diff](diffs/archiveQuests/Tome22.json.diff)

```diff
+ $.Tome22.level[0].challengeRewards[id=star]
+ $.Tome22.level[0].endNodeRewards[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_01.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_02.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_03.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_04.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_05.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_06.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_07.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_08.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_09.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_10.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_11.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_12.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_13.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_14.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_15.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_16.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_17.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_CM01.reward[id=star]
+ $.Tome22.level[0].nodes.node_T22_L1_Glyph01.reward[id=star]
+ $.Tome22.level[0].taskRewards[id=star]
+ $.Tome22.level[1].challengeRewards[id=star]
+ $.Tome22.level[1].endNodeRewards[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_01.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_02.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_03.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_04.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_05.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_06.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_07.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_08.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_09.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_10.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_11.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_12.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_13.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_14.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_15.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_16.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_17.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_CM01.reward[id=star]
+ $.Tome22.level[1].nodes.node_T22_L2_Glyph01.reward[id=star]
+ $.Tome22.level[1].taskRewards[id=star]
+ $.Tome22.level[2].challengeRewards[id=star]
+ $.Tome22.level[2].endNodeRewards[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_01.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_02.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_03.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_04.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_05.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_06.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_07.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_08.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_09.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_10.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_11.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_12.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_13.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_14.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_15.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_16.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_CM01.reward[id=star]
+ $.Tome22.level[2].nodes.node_T22_L3_Glyph01.reward[id=star]
+ $.Tome22.level[2].taskRewards[id=star]
+ $.Tome22.level[3].challengeRewards[id=star]
+ $.Tome22.level[3].endNodeRewards[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_01.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_02.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_03.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_04.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_05.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_06.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_07.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_08.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_09.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_10.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_11.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_12.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_13.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_14.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_15.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_16.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_CM01.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_Glyph01.reward[id=star]
+ $.Tome22.level[3].nodes.node_T22_L4_Glyph02.reward[id=star]
+ $.Tome22.level[3].taskRewards[id=star]
```

### [`archiveQuests/Winter2022.json`](archiveQuests/Winter2022.json)

[Full line-by-line diff](diffs/archiveQuests/Winter2022.json.diff)

```diff
+ $.Winter2022.level[0].challengeRewards[id=star]
+ $.Winter2022.level[0].endNodeRewards[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_01.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_02.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_03.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_04.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_05.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_06.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_07.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_08.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_09.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_10.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_11.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_12.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_13.reward[id=star]
+ $.Winter2022.level[0].nodes.node_WIN1_14.reward[id=star]
+ $.Winter2022.level[0].taskRewards[id=star]
+ $.Winter2022.level[1].challengeRewards[id=star]
+ $.Winter2022.level[1].endNodeRewards[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_01.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_02.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_03.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_04.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_05.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_06.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_07.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_08.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_09.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_10.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_11.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_12.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_13.reward[id=star]
+ $.Winter2022.level[1].nodes.node_WIN2_14.reward[id=star]
+ $.Winter2022.level[1].taskRewards[id=star]
```

### [`archiveQuests/Winter2023.json`](archiveQuests/Winter2023.json)

[Full line-by-line diff](diffs/archiveQuests/Winter2023.json.diff)

```diff
+ $.Winter2023.level[0].challengeRewards[id=star]
+ $.Winter2023.level[0].endNodeRewards[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_01.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_04.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_05.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_06.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_07.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_08.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_09.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_11.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_13.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_14.reward[id=star]
+ $.Winter2023.level[0].nodes.node_WIN2023_1_15.reward[id=star]
+ $.Winter2023.level[0].taskRewards[id=star]
+ $.Winter2023.level[1].challengeRewards[id=star]
+ $.Winter2023.level[1].endNodeRewards[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_01.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_03.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_04.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_06.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_07.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_08.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_10.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_11.reward[id=star]
+ $.Winter2023.level[1].nodes.node_WIN2023_2_13.reward[id=star]
+ $.Winter2023.level[1].taskRewards[id=star]
+ $.Winter2023.level[2].challengeRewards[id=star]
+ $.Winter2023.level[2].endNodeRewards[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_01.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_03.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_05.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_06.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_07.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_08.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_10.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_11.reward[id=star]
+ $.Winter2023.level[2].nodes.node_WIN2023_3_12.reward[id=star]
+ $.Winter2023.level[2].taskRewards[id=star]
```

### [`archiveQuests/Winter2024.json`](archiveQuests/Winter2024.json)

[Full line-by-line diff](diffs/archiveQuests/Winter2024.json.diff)

```diff
+ $.Winter2024.level[0].challengeRewards[id=star]
+ $.Winter2024.level[0].endNodeRewards[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_01.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_02.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_03.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_04.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_05.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_06.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_07.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_08.reward[id=star]
+ $.Winter2024.level[0].nodes.node_WIN2024_1_09.reward[id=star]
+ $.Winter2024.level[0].taskRewards[id=star]
+ $.Winter2024.level[1].challengeRewards[id=star]
+ $.Winter2024.level[1].endNodeRewards[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_01.reward[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_02.reward[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_03.reward[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_04.reward[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_05.reward[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_06.reward[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_07.reward[id=star]
+ $.Winter2024.level[1].nodes.node_WIN2024_2_08.reward[id=star]
+ $.Winter2024.level[1].taskRewards[id=star]
+ $.Winter2024.level[2].challengeRewards[id=star]
+ $.Winter2024.level[2].endNodeRewards[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_01.reward[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_02.reward[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_03.reward[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_04.reward[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_05.reward[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_06.reward[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_07.reward[id=star]
+ $.Winter2024.level[2].nodes.node_WIN2024_3_08.reward[id=star]
+ $.Winter2024.level[2].taskRewards[id=star]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=S54]
- $[id=K44]
- $[id=K33_Body013]
- $[id=K33_Head013]
- $[id=K33_W013]
- $[id=K35_Body019]
- $[id=K35_Head019]
- $[id=K35_W019]
- $[id=K44_BDG_P100]
- $[id=K44_BDG_P25]
- $[id=K44_BDG_P50]
- $[id=K44_BDG_P75]
- $[id=K44_Body002]
- $[id=K44_Body002_01]
- $[id=K44_Body006]
- $[id=K44_Body01]
- $[id=K44_Body01_01]
- $[id=K44_Body01_02]
- $[id=K44_Body01_03]
- $[id=K44_Body01_04]
- $[id=K44_Body01_CV01]
- $[id=K44_Body01_CV02]
- $[id=K44_Body01_CV03]
- $[id=K44_Body01_CV04]
- $[id=K44_Body01_P01]
- $[id=K44_Head002]
- $[id=K44_Head002_01]
- $[id=K44_Head006]
- $[id=K44_Head01]
- $[id=K44_Head01_01]
- $[id=K44_Head01_02]
- $[id=K44_Head01_03]
- $[id=K44_Head01_CV01]
- $[id=K44_Head01_CV02]
- $[id=K44_Head01_CV03]
- $[id=K44_Head01_CV04]
- $[id=K44_Head01_P01]
- $[id=K44_PCharm001]
- $[id=K44_PCharm002]
- $[id=K44_PCharm003]
- $[id=K44_W002]
- $[id=K44_W002_01]
- $[id=K44_W006]
- $[id=K44_W01_01]
- $[id=K44_W01_02]
- $[id=K44_W01_03]
- $[id=K44_W01_P01]
- $[id=K44_Weapon01]
- $[id=RAM_BDG_05]
- $[id=S28_Head035]
- $[id=S28_Legs035]
- $[id=S28_Torso035]
- $[id=S41_Head023]
- $[id=S41_Legs023]
- $[id=S41_Torso023]
- $[id=S54_BDG_P100]
- $[id=S54_BDG_P25]
- $[id=S54_BDG_P50]
- $[id=S54_BDG_P75]
- $[id=S54_Head006]
- $[id=S54_Head006_01]
- $[id=S54_Head01]
- $[id=S54_Head01_01]
- $[id=S54_Head01_02]
- $[id=S54_Head01_03]
- $[id=S54_Head01_P01]
- $[id=S54_Head02]
- $[id=S54_Head02_01]
- $[id=S54_Legs006]
- $[id=S54_Legs006_01]
- $[id=S54_Legs01]
- $[id=S54_Legs01_01]
- $[id=S54_Legs01_02]
- $[id=S54_Legs01_03]
- $[id=S54_Legs01_CV01]
- $[id=S54_Legs01_CV02]
- $[id=S54_Legs01_CV03]
- $[id=S54_Legs01_CV04]
- $[id=S54_Legs01_P01]
- $[id=S54_Legs02]
- $[id=S54_Legs02_01]
- $[id=S54_PCharm001]
- $[id=S54_PCharm002]
- $[id=S54_PCharm003]
- $[id=S54_Torso006]
- $[id=S54_Torso006_01]
- $[id=S54_Torso007]
- $[id=S54_Torso01]
- $[id=S54_Torso01_01]
- $[id=S54_Torso01_02]
- $[id=S54_Torso01_03]
- $[id=S54_Torso01_04]
- $[id=S54_Torso01_CV01]
- $[id=S54_Torso01_CV02]
- $[id=S54_Torso01_CV03]
- $[id=S54_Torso01_CV04]
- $[id=S54_Torso01_P01]
- $[id=S54_Torso02]
- $[id=S54_Torso02_01]
- $[id=UDO_001]
- $[id=UDO_002]
- $[id=UDO_003]
- $[id=UDO_BDG_03]
- $[id=UDO_BDG_04]
- $[id=UDO_BDG_05]
- $[id=UDO_BDG_06]
- $[id=UDO_BDG_07]
- $[id=UDO_BDG_08]
- $[id=UDO_BDG_09]
- $[id=UDO_BDG_10]
- $[id=UDO_BDG_12]
- $[id=UDO_BDG_13]
- $[id=UDO_BDG_14]
- $[id=UDO_BNR_01]
- $[id=UDO_BNR_02]
- $[id=UDO_BNR_03]
- $[id=UDO_BNR_04]
- $[id=UDO_BNR_05]
- $[id=UDO_BNR_08]
- $[id=UDO_BNR_10]
- $[id=K33_outfit_013]
- $[id=K35_outfit_019]
- $[id=K44_outfit_002]
- $[id=K44_outfit_002_01]
- $[id=K44_outfit_006]
- $[id=K44_outfit_01]
- $[id=K44_outfit_01_01]
- $[id=K44_outfit_01_02]
- $[id=K44_outfit_01_03]
- $[id=K44_outfit_01_CV01]
- $[id=K44_outfit_01_CV02]
- $[id=K44_outfit_01_CV03]
- $[id=K44_outfit_01_CV04]
- $[id=K44_outfit_01_P01]
- $[id=S28_outfit_035]
- $[id=S41_outfit_023]
- $[id=S54_outfit_006]
- $[id=S54_outfit_006_01]
- $[id=S54_outfit_01]
- $[id=S54_outfit_01_01]
- $[id=S54_outfit_01_02]
- $[id=S54_outfit_01_03]
- $[id=S54_outfit_01_CV01]
- $[id=S54_outfit_01_CV02]
- $[id=S54_outfit_01_CV03]
- $[id=S54_outfit_01_CV04]
- $[id=S54_outfit_01_P01]
- $[id=S54_outfit_02]
- $[id=S54_outfit_02_01]
- $[id=10.1.0_Gameplay_Expo]
- $[id=10.1.0_ChorusOfSin_collection_item]
- $[id=10.1.0_GameplayExpo_collection_item]
- $[id=10.1.0_Alien_Collection_collection_item]
+ $[id=WaterfrontMassacre_collection_item]
+ $[id=Ace].eventCostList
+ $[id=Ace].metaData.temporaryDiscounts
+ $[id=Witch].eventCostList
+ $[id=Witch].metaData.temporaryDiscounts
+ $[id=Feng].eventCostList
+ $[id=Feng].metaData.temporaryDiscounts
+ $[id=Killer07].eventCostList
+ $[id=Killer07].metaData.temporaryDiscounts
+ $[id=Kate].eventCostList
+ $[id=Kate].metaData.temporaryDiscounts
+ $[id=Cannibal].eventCostList
+ $[id=Cannibal].metaData.temporaryDiscounts
+ $[id=Quentin].eventCostList
+ $[id=Quentin].metaData.temporaryDiscounts
+ $[id=Nightmare].eventCostList
+ $[id=Nightmare].metaData.temporaryDiscounts
+ $[id=Eric].eventCostList
+ $[id=Eric].metaData.temporaryDiscounts
+ $[id=Pig].eventCostList
+ $[id=Pig].metaData.temporaryDiscounts
+ $[id=Clown].eventCostList
+ $[id=Clown].metaData.temporaryDiscounts
+ $[id=Adam].eventCostList
+ $[id=Adam].metaData.temporaryDiscounts
+ $[id=Spirit].eventCostList
+ $[id=Spirit].metaData.temporaryDiscounts
+ $[id=Legion].eventCostList
+ $[id=Legion].metaData.temporaryDiscounts
+ $[id=Jeff].eventCostList
+ $[id=Jeff].metaData.temporaryDiscounts
+ $[id=Plague].eventCostList
+ $[id=Plague].metaData.temporaryDiscounts
+ $[id=Jane].eventCostList
+ $[id=Jane].metaData.temporaryDiscounts
+ $[id=Ash].eventCostList
+ $[id=Ash].metaData.temporaryDiscounts
+ $[id=Ghostface].eventCostList
+ $[id=Ghostface].metaData.temporaryDiscounts
+ $[id=Oni].eventCostList
+ $[id=Oni].metaData.temporaryDiscounts
+ $[id=Yui].eventCostList
+ $[id=Yui].metaData.temporaryDiscounts
+ $[id=Gunslinger].eventCostList
+ $[id=Gunslinger].metaData.temporaryDiscounts
+ $[id=Zarina].eventCostList
+ $[id=Zarina].metaData.temporaryDiscounts
… 1591 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[375].text: "DbD-Tag"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[375].text: "DBD Day"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[375].text: "Día de DbD"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[375].text: "Día de DbD"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[375].text: "Journée de DbD"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[375].text: "DBD Day"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[375].text: "デドバの日"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[375].text: "데바데 데이"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[375].text: "Dzień DBD"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[375].text: "Dia de DbD"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[375].text: "День DBD"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[375].text: "วัน DBD"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[375].text: "DBD Günü"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[375].text: "DBD日"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[375].text: "黎明死線節"
+ $.locText[375].text: "@#CHALLENGESET_DbdDay_INFO"
- $.locText[375].textId: "CHALLENGESET_DbDDay_INFO"
+ $.locText[375].textId: "CHALLENGESET_DbdDay_INFO"
- $.locText[646]
- $.locText[647]
- $.locText[648]
- $.locText[649]
- $.locText[650]
- $.locText[651]
- $.locText[652]
- $.locText[653]
- $.locText[654]
- $.locText[655]
- $.locText[656]
- $.locText[657]
- $.locText[658]
- $.locText[659]
- $.locText[660]
- $.locText[661]
- $.locText[662]
- $.locText[663]
- $.locText[664]
- $.locText[665]
- $.locText[666]
- $.locText[667]
- $.locText[668]
- $.locText[669]
- $.locText[670]
- $.locText[671]
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.CalamariUdon
- $.ChapterQuests_Udon
- $.Summer2026.startDate: "2026-07-25T15:00:00"
+ $.Summer2026.startDate: "2026-07-28T15:00:00"
- $.Summer2026.startDateInMs: 1784991600000
+ $.Summer2026.startDateInMs: 1785250800000
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[9].limitedAvailabilityEndDate: "2026-07-28T14:00:00Z"
+ $.collections[9].visibleAfterEndDate: false
+ $.collections[9].additionalImages[0]
- $.collections[9].collectionId: "Rockabilly"
+ $.collections[9].collectionId: "WaterfrontMassacre"
- $.collections[9].collectionTitle.de: "Rockabilly"
+ $.collections[9].collectionTitle.de: "Hafenmassaker"
- $.collections[9].collectionTitle.en: "Rockabilly"
+ $.collections[9].collectionTitle.en: "Waterfront Massacre"
- $.collections[9].collectionTitle.es: "Rockabilly"
+ $.collections[9].collectionTitle.es: "Masacre de la costa"
- $.collections[9].collectionTitle["es-MX"]: "Rockabilly"
+ $.collections[9].collectionTitle["es-MX"]: "Masacre en la costa"
- $.collections[9].collectionTitle.fr: "Rockabilly"
+ $.collections[9].collectionTitle.fr: "Massacre au bord de la mer"
- $.collections[9].collectionTitle.it: "Rockabilly"
+ $.collections[9].collectionTitle.it: "Collezione Massacro sul lungomare"
- $.collections[9].collectionTitle.ja: "ロカビリー "
+ $.collections[9].collectionTitle.ja: "水辺の殺戮"
- $.collections[9].collectionTitle.ko: "로커빌리"
+ $.collections[9].collectionTitle.ko: "해안가 대학살"
- $.collections[9].collectionTitle.pl: "Rockabilly"
+ $.collections[9].collectionTitle.pl: "Nadbrzeżna masakra"
- $.collections[9].collectionTitle["pt-BR"]: "Rockabilly"
+ $.collections[9].collectionTitle["pt-BR"]: "Massacre da Costa"
- $.collections[9].collectionTitle.ru: "Рокабилли"
+ $.collections[9].collectionTitle.ru: "Пляжная резня"
- $.collections[9].collectionTitle.th: "ร็อกอะบิลลี่"
+ $.collections[9].collectionTitle.th: "การสังหารหมู่ริมน้ำ"
- $.collections[9].collectionTitle.tr: "Rockabilly"
+ $.collections[9].collectionTitle.tr: "Su Kenarı Katliamı"
- $.collections[9].collectionTitle["zh-Hans"]: "山区摇滚"
+ $.collections[9].collectionTitle["zh-Hans"]: "滨水屠杀"
- $.collections[9].collectionTitle["zh-Hant"]: "鄉村搖滾"
+ $.collections[9].collectionTitle["zh-Hant"]: "水邊屠殺"
- $.collections[9].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
+ $.collections[9].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_WaterfrontMassacreXenomorph.T_UI_CollectionBanner_WaterfrontMassacreXenomorph"
- $.collections[9].items[]: "AV_outfit_015"
- $.collections[9].items[]: "GS_outfit_014"
- $.collections[9].items[]: "MS_outfit_014"
- $.collections[9].items[]: "MT_outfit_015"
- $.collections[9].items[]: "NK_outfit_014"
- $.collections[9].items[]: "S23_outfit_016"
- $.collections[9].items[]: "S24_outfit_013"
+ $.collections[9].items[]: "AV_outfit_028"
+ $.collections[9].items[]: "CM_outfit_012"
+ $.collections[9].items[]: "DF_outfit_015"
+ $.collections[9].items[]: "DK_outfit_014"
+ $.collections[9].items[]: "FM_outfit_019"
+ $.collections[9].items[]: "GS_outfit_015"
+ $.collections[9].items[]: "HS_outfit_023"
+ $.collections[9].items[]: "K23_outfit_016"
+ $.collections[9].items[]: "K33_outfit_012"
+ $.collections[9].items[]: "KS_outfit_017"
+ $.collections[9].items[]: "MS_outfit_008"
+ $.collections[9].items[]: "MT_outfit_024"
+ $.collections[9].items[]: "NK_outfit_015"
+ $.collections[9].items[]: "S23_outfit_017"
+ $.collections[9].items[]: "S24_outfit_025"
+ $.collections[9].items[]: "S25_outfit_016"
+ $.collections[9].items[]: "S28_outfit_012"
+ $.collections[9].items[]: "S31_outfit_006"
+ $.collections[9].items[]: "S37_outfit_016"
+ $.collections[9].items[]: "S41_outfit_009"
+ $.collections[9].items[]: "S46_outfit_009"
+ $.collections[9].items[]: "SwedenSurvivor_outfit_010"
+ $.collections[9].items[]: "TC_outfit_009"
+ $.collections[9].items[]: "TC_outfit_009_01"
+ $.collections[9].items[]: "TR_outfit_010"
- $.collections[9].sortOrder: "-14"
+ $.collections[9].sortOrder: "-134"
- $.collections[9].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[9].updatedDate: "2025-07-17T16:18:41.657Z"
- $.collections[10].limitedAvailabilityStartDate: "2025-05-15T15:00:00Z"
- $.collections[10].visibleBeforeStartDate: false
- $.collections[10].additionalImages[0]
- $.collections[10].collectionId: "GuardiansAndShadows"
+ $.collections[10].collectionId: "Rockabilly"
- $.collections[10].collectionTitle.de: "Wächter und Schatten"
+ $.collections[10].collectionTitle.de: "Rockabilly"
- $.collections[10].collectionTitle.en: "Guardians & Shadows"
+ $.collections[10].collectionTitle.en: "Rockabilly"
- $.collections[10].collectionTitle.es: "Guardianes y sombras"
+ $.collections[10].collectionTitle.es: "Rockabilly"
- $.collections[10].collectionTitle["es-MX"]: "Guardianes y sombras"
+ $.collections[10].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[10].collectionTitle.fr: "Gardiens et ombres"
+ $.collections[10].collectionTitle.fr: "Rockabilly"
- $.collections[10].collectionTitle.it: "Guardiani e ombre"
+ $.collections[10].collectionTitle.it: "Rockabilly"
- $.collections[10].collectionTitle.ja: "守護者と影"
+ $.collections[10].collectionTitle.ja: "ロカビリー "
- $.collections[10].collectionTitle.ko: "수호자와 그림자"
+ $.collections[10].collectionTitle.ko: "로커빌리"
- $.collections[10].collectionTitle.pl: "Strażnicy i cienie"
+ $.collections[10].collectionTitle.pl: "Rockabilly"
- $.collections[10].collectionTitle["pt-BR"]: "Guardiões e Sombras"
+ $.collections[10].collectionTitle["pt-BR"]: "Rockabilly"
- $.collections[10].collectionTitle.ru: "Стражи и тени"
+ $.collections[10].collectionTitle.ru: "Рокабилли"
- $.collections[10].collectionTitle.th: "ผู้พิทักษ์กับเงา"
+ $.collections[10].collectionTitle.th: "ร็อกอะบิลลี่"
- $.collections[10].collectionTitle.tr: "Muhafızlar ve Gölgeler"
+ $.collections[10].collectionTitle.tr: "Rockabilly"
- $.collections[10].collectionTitle["zh-Hans"]: "守护者&暗影"
+ $.collections[10].collectionTitle["zh-Hans"]: "山区摇滚"
- $.collections[10].collectionTitle["zh-Hant"]: "守衛與暗影"
+ $.collections[10].collectionTitle["zh-Hant"]: "鄉村搖滾"
- $.collections[10].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_GuardiansAndShadows.T_UI_CollectionBanner_GuardiansAndShadows"
+ $.collections[10].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
- $.collections[10].inclusionVersion: "8.7.0"
+ $.collections[10].inclusionVersion: "7.7.0 PTB"
- $.collections[10].items[]: "DK_outfit_023"
- $.collections[10].items[]: "GK_outfit_022"
- $.collections[10].items[]: "HK_outfit_020"
- $.collections[10].items[]: "K23_outfit_023"
- $.collections[10].items[]: "KK_outfit_038"
- $.collections[10].items[]: "OK_outfit_016"
- $.collections[10].items[]: "S24_outfit_022"
- $.collections[10].items[]: "S25_outfit_030"
- $.collections[10].items[]: "S34_outfit_019"
- $.collections[10].items[]: "S37_outfit_021"
- $.collections[10].items[]: "S41_outfit_011"
- $.collections[10].items[]: "S43_outfit_009"
- $.collections[10].items[]: "SwedenSurvivor_outfit_025"
- $.collections[10].items[]: "TW_outfit_021"
+ $.collections[10].items[]: "AV_outfit_015"
+ $.collections[10].items[]: "GS_outfit_014"
+ $.collections[10].items[]: "MS_outfit_014"
+ $.collections[10].items[]: "MT_outfit_015"
+ $.collections[10].items[]: "NK_outfit_014"
+ $.collections[10].items[]: "S23_outfit_016"
+ $.collections[10].items[]: "S24_outfit_013"
- $.collections[10].sortOrder: "-146"
+ $.collections[10].sortOrder: "-14"
- $.collections[10].updatedDate: "2025-08-05T13:26:33.435Z"
+ $.collections[10].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[11].limitedAvailabilityStartDate: "2025-05-15T15:00:00Z"
+ $.collections[11].visibleBeforeStartDate: false
- $.collections[11].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Lasagna/T_UI_SpecialPack_TombRaider_2.T_UI_SpecialPack_TombRaider_2"
+ $.collections[11].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_GuardiansAndShadows.T_UI_SpecialPack_GuardiansAndShadows"
- $.collections[11].collectionId: "TombRaider"
+ $.collections[11].collectionId: "GuardiansAndShadows"
- $.collections[11].collectionTitle.de: "Tomb Raider"
+ $.collections[11].collectionTitle.de: "Wächter und Schatten"
- $.collections[11].collectionTitle.en: "Tomb Raider"
+ $.collections[11].collectionTitle.en: "Guardians & Shadows"
- $.collections[11].collectionTitle.es: "Tomb Raider"
+ $.collections[11].collectionTitle.es: "Guardianes y sombras"
- $.collections[11].collectionTitle["es-MX"]: "Tomb Raider"
+ $.collections[11].collectionTitle["es-MX"]: "Guardianes y sombras"
- $.collections[11].collectionTitle.fr: "Tomb Raider"
+ $.collections[11].collectionTitle.fr: "Gardiens et ombres"
- $.collections[11].collectionTitle.it: "Tomb Raider"
+ $.collections[11].collectionTitle.it: "Guardiani e ombre"
- $.collections[11].collectionTitle.ja: "トゥームレイダー"
+ $.collections[11].collectionTitle.ja: "守護者と影"
- $.collections[11].collectionTitle.ko: "툼 레이더"
+ $.collections[11].collectionTitle.ko: "수호자와 그림자"
- $.collections[11].collectionTitle.pl: "Tomb Raider"
+ $.collections[11].collectionTitle.pl: "Strażnicy i cienie"
- $.collections[11].collectionTitle["pt-BR"]: "Tomb Raider"
+ $.collections[11].collectionTitle["pt-BR"]: "Guardiões e Sombras"
- $.collections[11].collectionTitle.ru: "Tomb Raider"
+ $.collections[11].collectionTitle.ru: "Стражи и тени"
- $.collections[11].collectionTitle.th: "Tomb Raider"
+ $.collections[11].collectionTitle.th: "ผู้พิทักษ์กับเงา"
- $.collections[11].collectionTitle.tr: "Tomb Raider"
+ $.collections[11].collectionTitle.tr: "Muhafızlar ve Gölgeler"
- $.collections[11].collectionTitle["zh-Hans"]: "《Tomb Raider》"
+ $.collections[11].collectionTitle["zh-Hans"]: "守护者&暗影"
- $.collections[11].collectionTitle["zh-Hant"]: "古墓奇兵"
+ $.collections[11].collectionTitle["zh-Hant"]: "守衛與暗影"
- $.collections[11].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Lasagna/T_UI_CollectionBanner_TombRaider_2.T_UI_CollectionBanner_TombRaider_2"
+ $.collections[11].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_GuardiansAndShadows.T_UI_CollectionBanner_GuardiansAndShadows"
- $.collections[11].inclusionVersion: "8.1.0"
+ $.collections[11].inclusionVersion: "8.7.0"
- $.collections[11].items[]: "S43_outfit_006"
- $.collections[11].items[]: "S43_outfit_007"
- $.collections[11].items[]: "S43_outfit_008"
- $.collections[11].items[]: "S43_outfit_010"
- $.collections[11].items[]: "S43_outfit_011"
- $.collections[11].items[]: "S43_outfit_02"
+ $.collections[11].items[]: "DK_outfit_023"
+ $.collections[11].items[]: "GK_outfit_022"
+ $.collections[11].items[]: "HK_outfit_020"
+ $.collections[11].items[]: "K23_outfit_023"
+ $.collections[11].items[]: "KK_outfit_038"
+ $.collections[11].items[]: "OK_outfit_016"
+ $.collections[11].items[]: "S24_outfit_022"
+ $.collections[11].items[]: "S25_outfit_030"
+ $.collections[11].items[]: "S34_outfit_019"
+ $.collections[11].items[]: "S37_outfit_021"
+ $.collections[11].items[]: "S41_outfit_011"
+ $.collections[11].items[]: "SwedenSurvivor_outfit_025"
+ $.collections[11].items[]: "TW_outfit_021"
- $.collections[11].sortOrder: "-147"
+ $.collections[11].sortOrder: "-146"
- $.collections[11].updatedDate: "2025-08-05T13:27:53.149Z"
+ $.collections[11].updatedDate: "2025-08-05T13:26:33.435Z"
… 6442 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[1].MapsWeight.Wrm_Level_Calamari: "200"
```

### [`crossPromoCampaigns.json`](crossPromoCampaigns.json)

[Full line-by-line diff](diffs/crossPromoCampaigns.json.diff)

```diff
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabel: "NSLOCTEXT(\"[3F11D6A8EE02B1F39C1CCB88BA4628AE]\", \"6CB54E17434C20FB2FE796B0B6828160\", \"DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL\")"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabel: "NSLOCTEXT(\"[3F11D6A8EE02B1F39C1CCB88BA4628AE]\", \"6CB54E17434C20FB2FE796B0B6828160\", \"DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL \")"
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.de: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.de: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.en: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.en: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.es: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.es: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["es-MX"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["es-MX"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.fr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.fr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.it: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.it: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.ja: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.ja: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.ko: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.ko: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.pl: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.pl: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["pt-BR"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["pt-BR"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.ru: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.ru: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.th: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.th: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.tr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations.tr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["zh-Hans"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["zh-Hans"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["zh-Hant"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.ps4.buttonLabelTranslations["zh-Hant"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.de: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.de: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.en: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.en: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.es: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.es: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["es-MX"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["es-MX"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.fr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.fr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.it: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.it: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.ja: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.ja: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.ko: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.ko: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.pl: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.pl: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["pt-BR"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["pt-BR"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.ru: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.ru: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.th: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.th: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.tr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations.tr: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["zh-Hans"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["zh-Hans"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
- $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["zh-Hant"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL"
+ $.Campaigns.DBDStats.platformSpecificContent.switch.buttonLabelTranslations["zh-Hant"]: "@#DBDSTATS_POPUP_INSTRUCTION_LINK_LABEL "
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.Udon
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "6ad1cf5875c504b324b2c8aab95125751e99e446"
+ $.entries[0].contentVersion: "2e3756add2be7d9465389e75b953933bf07bf33c"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_Xenomorph_King.T_UI_CollectionBanner_Xenomorph_King"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Rift6.T_UI_SpecialPack_Rift6"
- $.entries[0].uri: "images/T_UI_CollectionBanner_Xenomorph_King.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_Rift6.png"
- $.entries[1].contentVersion: "ca487a772a08014f6d0a3e74742e79c5faedcabc"
+ $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_Xenomorph_King.T_UI_SpecialPack_Xenomorph_King"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[1].uri: "images/T_UI_SpecialPack_Xenomorph_King.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[2].contentVersion: "35d3b861df2c981a9225a5163c411552507da85c"
+ $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_GameplayExpo_Unknown.T_UI_CollectionBanner_GameplayExpo_Unknown"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[2].uri: "images/T_UI_CollectionBanner_GameplayExpo_Unknown.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[3].contentVersion: "274d4251fdd8df990a72352dfb0ab845a3c82815"
+ $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_GameplayExpo_Unknown.T_UI_SpecialPack_GameplayExpo_Unknown"
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[3].uri: "images/T_UI_SpecialPack_GameplayExpo_Unknown.png"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[4].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[4].contentVersion: "9ebc3ab1870be6603f236ef165b901e4a9086fd9"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].enableChecksum: false
+ $.entries[4].enableChecksum: true
- $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[4].packagedPath: ""
- $.entries[4].schema: "s3verbin://"
+ $.entries[4].schema: "s3ver://"
- $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[4].uri: "catalog.json"
- $.entries[5].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[5].contentVersion: "e3c0c8452df5534be306d4bc15511854f46937e8"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].enableChecksum: false
+ $.entries[5].enableChecksum: true
- $.entries[5].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[5].packagedPath: ""
- $.entries[5].schema: "s3verbin://"
+ $.entries[5].schema: "s3ver://"
- $.entries[5].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[5].uri: "bonusPointEventsContent.json"
- $.entries[6].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[6].contentVersion: "1d937a9bfe5bf3c5741e1be40fd3e3ae58d18be5"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[6].uri: "freetoplay/NA/event.json"
- $.entries[7].contentVersion: "f2780391ab1bfefe81feb4d2f6db4d91fba90962"
+ $.entries[7].contentVersion: "1d937a9bfe5bf3c5741e1be40fd3e3ae58d18be5"
- $.entries[7].downloadStrategy: "preferPackaged"
+ $.entries[7].downloadStrategy: "preferRemote"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_ChorusOfSin.T_UI_ChapterBundle_ChorusOfSin"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_ChapterBundle_ChorusOfSin.png"
+ $.entries[7].uri: "freetoplay/EU/event.json"
- $.entries[8].contentVersion: "6ad1cf5875c504b324b2c8aab95125751e99e446"
+ $.entries[8].contentVersion: "e3d7f9f1c014f1b61a5a92272a7aa406d2b0cc8d"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_Xenomorph_King.T_UI_CollectionBanner_Xenomorph_King"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_CollectionBanner_Xenomorph_King.png"
+ $.entries[8].uri: "archiveQuests/Anniversary2022.json"
- $.entries[9].contentVersion: "ca487a772a08014f6d0a3e74742e79c5faedcabc"
+ $.entries[9].contentVersion: "f65c70bdd1fe7f485ab79fd257b4f5258f26b998"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_Xenomorph_King.T_UI_SpecialPack_Xenomorph_King"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_SpecialPack_Xenomorph_King.png"
+ $.entries[9].uri: "archiveQuests/Anniversary2023.json"
- $.entries[10].contentVersion: "35d3b861df2c981a9225a5163c411552507da85c"
+ $.entries[10].contentVersion: "4574587fb5121d8f0b1c0bb8907aa4161b7da27f"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].enableChecksum: false
+ $.entries[10].enableChecksum: true
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Udon/T_UI_CollectionBanner_GameplayExpo_Unknown.T_UI_CollectionBanner_GameplayExpo_Unknown"
+ $.entries[10].packagedPath: ""
- $.entries[10].schema: "s3verbin://"
+ $.entries[10].schema: "s3ver://"
- $.entries[10].uri: "images/T_UI_CollectionBanner_GameplayExpo_Unknown.png"
+ $.entries[10].uri: "archiveQuests/Anniversary2024.json"
- $.entries[11].contentVersion: "274d4251fdd8df990a72352dfb0ab845a3c82815"
+ $.entries[11].contentVersion: "0033222d5874c34279a718c63abda3ebd7aa68a8"
- $.entries[11].downloadStrategy: "preferPackaged"
+ $.entries[11].downloadStrategy: "preferRemote"
- $.entries[11].enableChecksum: false
+ $.entries[11].enableChecksum: true
- $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Udon/T_UI_SpecialPack_GameplayExpo_Unknown.T_UI_SpecialPack_GameplayExpo_Unknown"
+ $.entries[11].packagedPath: ""
- $.entries[11].schema: "s3verbin://"
+ $.entries[11].schema: "s3ver://"
- $.entries[11].uri: "images/T_UI_SpecialPack_GameplayExpo_Unknown.png"
+ $.entries[11].uri: "archiveQuests/CalamariV1.json"
- $.entries[12].contentVersion: "c204b4714341b1c334f8a67b9ba2d3b8925c8b10"
+ $.entries[12].contentVersion: "c26643c869e9ad47e8fdfb56af4c23d1db1b4926"
- $.entries[12].uri: "catalog.json"
+ $.entries[12].uri: "archiveQuests/CalamariV2.json"
- $.entries[13].contentVersion: "696b13e774ba1cfa685a5703047d7c0af3b77d34"
+ $.entries[13].contentVersion: "37b3a378f67c212f42ee68750eb5d06455571d78"
- $.entries[13].uri: "bonusPointEventsContent.json"
+ $.entries[13].uri: "archiveQuests/CalamariV3.json"
- $.entries[14].contentVersion: "173a2638e3b1857de63abeb944eb9b0ff6218e21"
+ $.entries[14].contentVersion: "04c46d54365083e5fb9483d999084d7ab06afabe"
- $.entries[14].uri: "freetoplay/NA/event.json"
+ $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[15].contentVersion: "173a2638e3b1857de63abeb944eb9b0ff6218e21"
+ $.entries[15].contentVersion: "5b962cf5e3e1e9bee34b2ba583bf75f80bd920a6"
- $.entries[15].uri: "freetoplay/EU/event.json"
+ $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[16].contentVersion: "ac77ac7a1642a7efb4bc864e9c67f747f86a5f92"
+ $.entries[16].contentVersion: "a4fdd1b9b9590a3b29de0436474534af2e50bddc"
- $.entries[16].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[17].contentVersion: "c4fb8d2666ec6657aa45c12ddb27cf2449b94ba0"
+ $.entries[17].contentVersion: "3a9b9a2d29c3075723c633a86ff937a5e4f614c5"
- $.entries[17].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[17].uri: "archiveQuests/FireflyV1.json"
- $.entries[18].contentVersion: "55039826f66fc353004b940f0815607ecfddaeb1"
+ $.entries[18].contentVersion: "7074b5a33354f9a5c7aec0f18b164e0c6825e9ff"
- $.entries[18].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[18].uri: "archiveQuests/Halloween2021.json"
- $.entries[19].contentVersion: "36a63c830ed5d93297877f0fc8ef2fd0bfe6627e"
+ $.entries[19].contentVersion: "9f4c61db43da8b379f6505a532361c4204878b6f"
- $.entries[19].uri: "archiveQuests/CalamariV1.json"
+ $.entries[19].uri: "archiveQuests/Halloween2022.json"
- $.entries[20].contentVersion: "c3f0412daa48318e89213205faa02ae4502b3c5b"
+ $.entries[20].contentVersion: "2e251bc337c3032b4fba4dc06a81823a14a97ee2"
- $.entries[20].uri: "archiveQuests/CalamariV2.json"
+ $.entries[20].uri: "archiveQuests/Halloween2023.json"
- $.entries[21].contentVersion: "6abc65cf2e027f908bfced528deed6166a1e73f0"
+ $.entries[21].contentVersion: "ccbc840a6eef4ddeb32149d05b3fc19626a8c452"
- $.entries[21].uri: "archiveQuests/CalamariV3.json"
+ $.entries[21].uri: "archiveQuests/Halloween2024.json"
- $.entries[22].contentVersion: "6afdc17527a235432ea0abd3e9958a983b67bb5c"
+ $.entries[22].contentVersion: "0601bff58b0fc86d1e52a2c558539c3d1209b4c5"
- $.entries[22].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[22].uri: "archiveQuests/Spring2024.json"
- $.entries[23].contentVersion: "62ce66e582e6bb182e82439e0a3f4d1c226587d2"
+ $.entries[23].contentVersion: "c3a5e6209a14903e40459e13a7c5444f2439eef9"
- $.entries[23].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[23].uri: "archiveQuests/Spring2025.json"
- $.entries[24].contentVersion: "88b006d567786b29cff8ec45147cbde1cd708f8d"
+ $.entries[24].contentVersion: "e21988b7dcef18d5a9f03687c418c3ac3bf98a22"
- $.entries[24].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[24].uri: "archiveQuests/Summer2023.json"
- $.entries[25].contentVersion: "36f8593031737abc44ddd1bf12bb22fafffca9ef"
+ $.entries[25].contentVersion: "1a31f2be80552e18ba433ae0b6c2b7f96778a0c0"
- $.entries[25].uri: "archiveQuests/FireflyV1.json"
+ $.entries[25].uri: "archiveQuests/Tome01.json"
- $.entries[26].contentVersion: "b71b6b29853eb26367396ad8a9993fa7b3226191"
+ $.entries[26].contentVersion: "e9623b0d38488c5053205909e207d486278f5db8"
- $.entries[26].uri: "archiveQuests/Halloween2021.json"
+ $.entries[26].uri: "archiveQuests/Tome02.json"
- $.entries[27].contentVersion: "42bd9b11fc3be7da347cb19e9116bafaccc85383"
+ $.entries[27].contentVersion: "139fe217ea6a3c71c6984bac11a115f185e378f2"
- $.entries[27].uri: "archiveQuests/Halloween2022.json"
+ $.entries[27].uri: "archiveQuests/Tome03.json"
- $.entries[28].contentVersion: "74c37a58b17659788ab8212a58a5bbaf368fe7b3"
+ $.entries[28].contentVersion: "7fe476d386baa2974c1b537db663dd9582ea64a2"
- $.entries[28].uri: "archiveQuests/Halloween2023.json"
+ $.entries[28].uri: "archiveQuests/Tome04.json"
- $.entries[29].contentVersion: "cfbc3949e82318270d00804a7addee4d7d62a8df"
+ $.entries[29].contentVersion: "03d5c65a9b73e022aca1d043d772e045fd796518"
- $.entries[29].uri: "archiveQuests/Halloween2024.json"
+ $.entries[29].uri: "archiveQuests/Tome05.json"
- $.entries[30].contentVersion: "3998c2f5e7998503f2341546e00e0b18cde874e2"
+ $.entries[30].contentVersion: "d9ce567684eff4b4a8ecc27b99ac30a48d9e8de9"
- $.entries[30].uri: "archiveQuests/Spring2024.json"
+ $.entries[30].uri: "archiveQuests/Tome06.json"
- $.entries[31].contentVersion: "13b1f038133b7d852322befdc2f1cb734acd8572"
+ $.entries[31].contentVersion: "1ac85d35598aca0c1ccc020d9fc78b350c16eefa"
- $.entries[31].uri: "archiveQuests/Spring2025.json"
+ $.entries[31].uri: "archiveQuests/Tome07.json"
… 772 more change(s) — see the commit diff for everything
```

### [`gameplayTunables.json`](gameplayTunables.json)

[Full line-by-line diff](diffs/gameplayTunables.json.diff)

```diff
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:benevolent_protectionhit_pointspervalue"]: 15.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:benevolent_protectionhitendgame_pointspervalue"]: 20.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:benevolent_savefromkiller_pointspervalue"]: 35.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:benevolent_unhooksafe_pointspervalue"]: 20.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:benevolent_unhooksafeendgame_pointspervalue"]: 20.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:chaser_chasesurvivorescape_pointspervalue"]: -2.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:evader_chasesurvivordowned_pointspervalue"]: 3.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:evader_chasesurvivorescape_pointspervalue"]: 7.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:evader_chasetimesurvivor_pointspervalue"]: 0.3
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:evader_timestealthed_pointspervalue"]: 0.15
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:gatekeeper_timebetweenchasesaverage_pointspervalue"]: 2.75
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:gatekeeper_timebetweenchasesquick_pointspervalue"]: 3.5
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:lightbringer_genchargesdone_pointspervalue"]: 0.5
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:malicious_firsttimehook_pointspervalue"]: 4.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:malicious_survivorhealthlost_pointspervalue"]: 3.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:unbroken_survivorescapehatch_pointspervalue"]: 75.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:unbroken_survivorhooked_pointspervalue"]: -20.0
+ $.data["f:/Game/Data/MMRScore/MMRScoreTunableDB.MMRScoreTunableDB:unbroken_survivorinjured_pointspervalue"]: -18.0
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
+ $.disabledItems.K40_Body010
+ $.disabledItems.K40_Head010
+ $.disabledItems.K40_W010
+ $.disabledItems.K40_outfit_010
```

### [`narrativeCollections.json`](narrativeCollections.json)

[Full line-by-line diff](diffs/narrativeCollections.json.diff)

```diff
- $.DefaultChunk.collections[id=COLL_002]
```

### [`prestige/prestige.json`](prestige/prestige.json)

[Full line-by-line diff](diffs/prestige/prestige.json.diff)

```diff
- $.rewards.K44
- $.rewards.S54
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Udon_PTB]
- $.featuredCard[id=Udon_W1]
- $.featuredCard[id=Udon_W2]
- $.featuredCard[id=Udon_W3]
- $.featuredCard[id=KetchupW1].entries[2].entryId: "Rift_1_Bundle"
+ $.featuredCard[id=KetchupW1].entries[2].entryId: "TheWitcherBundle"
+ $.featuredCard[id=KetchupW1].entries[3]
- $.featuredCard[id=Sushi_W4].entries[0].weight: 14
+ $.featuredCard[id=Sushi_W4].entries[0].weight: 15
- $.featuredCard[id=Sushi_W4].entries[1].entryId: "10.0.0_SilentHill"
+ $.featuredCard[id=Sushi_W4].entries[1].entryId: "10.0.2_Iron_Maiden_Killer_Bundle"
- $.featuredCard[id=Sushi_W4].entries[1].type: "Collection"
+ $.featuredCard[id=Sushi_W4].entries[1].type: "SpecialPack"
- $.featuredCard[id=Sushi_W4].entries[1].weight: 13
+ $.featuredCard[id=Sushi_W4].entries[1].weight: 14
- $.featuredCard[id=Sushi_W4].entries[2].entryId: "10.0.1_Chapter40"
+ $.featuredCard[id=Sushi_W4].entries[2].entryId: "10.0.0_SilentHill"
- $.featuredCard[id=Sushi_W4].entries[2].weight: 11
+ $.featuredCard[id=Sushi_W4].entries[2].weight: 13
- $.featuredCard[id=Sushi_W4_2].entries[0].weight: 14
+ $.featuredCard[id=Sushi_W4_2].entries[0].weight: 15
- $.featuredCard[id=Sushi_W4_2].entries[1].entryId: "10.0.0_SilentHill"
+ $.featuredCard[id=Sushi_W4_2].entries[1].entryId: "10.0.2_Iron_Maiden_Killer_Bundle"
- $.featuredCard[id=Sushi_W4_2].entries[1].type: "Collection"
+ $.featuredCard[id=Sushi_W4_2].entries[1].type: "SpecialPack"
- $.featuredCard[id=Sushi_W4_2].entries[1].weight: 13
+ $.featuredCard[id=Sushi_W4_2].entries[1].weight: 14
- $.featuredCard[id=Sushi_W4_2].entries[2].entryId: "10.0.1_Chapter40"
+ $.featuredCard[id=Sushi_W4_2].entries[2].entryId: "10.0.2_Iron_Maiden_Shirt_Bundle"
- $.featuredCard[id=Sushi_W4_2].entries[2].type: "Collection"
+ $.featuredCard[id=Sushi_W4_2].entries[2].type: "SpecialPack"
- $.featuredCard[id=Sushi_W4_2].entries[2].weight: 11
+ $.featuredCard[id=Sushi_W4_2].entries[2].weight: 13
- $.featuredCard[id=Sushi_W4_2].entries[3].entryId: "Rift_5_Bundle"
+ $.featuredCard[id=Sushi_W4_2].entries[3].entryId: "10.0.0_SilentHill"
- $.featuredCard[id=Sushi_W4_2].entries[3].type: "SpecialPack"
+ $.featuredCard[id=Sushi_W4_2].entries[3].type: "Collection"
- $.featuredCard[id=Sushi_W4_2].entries[3].weight: 7
+ $.featuredCard[id=Sushi_W4_2].entries[3].weight: 12
+ $.featuredCard[id=Sushi_W4_2].entries[4]
- $.featuredChapterPackRecommendations[id=Udon]
- $.featuredChapterPackRecommendations[id=Sushi_2].activeTo: "2026-08-25T15:00:00Z"
+ $.featuredChapterPackRecommendations[id=Sushi_2].activeTo: "2039-05-25T15:00:00Z"
+ $.featuredCharacterRecommendations[id=Featured_Characters_Sushi]
- $.featuredCharacterRecommendations[id=Featured_Characters].activeFrom: "2026-06-25T15:00:00Z"
+ $.featuredCharacterRecommendations[id=Featured_Characters].activeFrom: "2025-04-04T16:00:00Z"
- $.featuredCharacterRecommendations[id=Featured_Characters].activeTo: "2033-09-04T00:00:00Z"
+ $.featuredCharacterRecommendations[id=Featured_Characters].activeTo: "2026-06-25T15:00:00Z"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "53"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "268435498"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Udon/T_UI_S54_Aurora_Portrait.T_UI_S54_Aurora_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Sushi/T_UI_K43_TheSlasher_Portrait.T_UI_K43_TheSlasher_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].weight: "3"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].weight: "0"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "268435499"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "51"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Udon/T_UI_K44_TheJudgment_Portrait.T_UI_K44_TheJudgment_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Quiche/T_UI_S52_KwonTaeYoung_Portrait.T_UI_S52_KwonTaeYoung_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].weight: "2"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].weight: "0"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "52"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "268435478"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Sushi/T_UI_S53_ShaneWiigwaas_Portrait.T_UI_S53_ShaneWiigwaas_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Comet/K23_TheTrickster_Portrait.K23_TheTrickster_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "268435498"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "24"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Sushi/T_UI_K43_TheSlasher_Portrait.T_UI_K43_TheSlasher_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Comet/S25_YunJinLee_Portrait.S25_YunJinLee_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "51"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "268435497"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Quiche/T_UI_S52_KwonTaeYoung_Portrait.T_UI_S52_KwonTaeYoung_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Poutine/T_UI_K42_TheFirst_Portrait.T_UI_K42_TheFirst_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "268435478"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].characterIndex: "50"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Comet/K23_TheTrickster_Portrait.K23_TheTrickster_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Poutine/T_UI_S51_Eleven_Portrait.T_UI_S51_Eleven_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].characterIndex: "24"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].characterIndex: "49"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Comet/S25_YunJinLee_Portrait.S25_YunJinLee_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[6].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Poutine/T_UI_S50_DustinHenderson_Portrait.T_UI_S50_DustinHenderson_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].characterIndex: "268435497"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].characterIndex: "48"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Poutine/T_UI_K42_TheFirst_Portrait.T_UI_K42_TheFirst_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[7].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Maple/T_UI_S49_VeeBoonyasak_Portrait.T_UI_S49_VeeBoonyasak_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].characterIndex: "50"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].characterIndex: "268435496"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Poutine/T_UI_S51_Eleven_Portrait.T_UI_S51_Eleven_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[8].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Maple/T_UI_K41_TheKrasue_Portrait.T_UI_K41_TheKrasue_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[9].characterIndex: "49"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[9].characterIndex: "47"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[9].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Poutine/T_UI_S50_DustinHenderson_Portrait.T_UI_S50_DustinHenderson_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[9].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S48_MichonneGrimes_Portrait.S48_MichonneGrimes_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[10].characterIndex: "48"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[10].characterIndex: "46"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[10].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Maple/T_UI_S49_VeeBoonyasak_Portrait.T_UI_S49_VeeBoonyasak_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[10].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S47_RickGrimes_Portrait.S47_RickGrimes_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[11].characterIndex: "268435496"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[11].characterIndex: "268435495"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[11].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Maple/T_UI_K41_TheKrasue_Portrait.T_UI_K41_TheKrasue_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[11].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Ketchup/K40_TheAnimatronic_Portrait.K40_TheAnimatronic_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[12].characterIndex: "47"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[12].characterIndex: "45"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[12].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S48_MichonneGrimes_Portrait.S48_MichonneGrimes_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[12].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[13].characterIndex: "46"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[13].characterIndex: "268435494"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[13].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Lasagna/S47_RickGrimes_Portrait.S47_RickGrimes_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[13].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[14].characterIndex: "268435495"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[14].characterIndex: "268435493"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[14].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Ketchup/K40_TheAnimatronic_Portrait.K40_TheAnimatronic_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[14].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[15].characterIndex: "45"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[15].characterIndex: "44"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[15].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[15].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[16].characterIndex: "268435494"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[16].characterIndex: "268435492"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[16].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[16].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[17].characterIndex: "268435493"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[17].characterIndex: "43"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[17].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[17].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/S44_TrevorBelmont_Portrait.S44_TrevorBelmont_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[18]
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[19]
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[20]
- $.featuredCustomizationRecommendations[id=Udon_PTB]
- $.featuredCustomizationRecommendations[id=Udon_W1]
- $.featuredCustomizationRecommendations[id=Udon_W2]
- $.featuredCustomizationRecommendations[id=Udon_W3]
- $.featuredCustomizationRecommendations[id=Sushi_W2].recommendations[id=Sushi]
- $.specialsRecommendations[id=Alien_Sale_2026]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[73].startTime: "2026-07-25T15:00:00"
+ $.specialEvents[73].startTime: "2026-07-28T15:00:00"
+ $.specialEvents[74].eventName
+ $.specialEvents[74].eventType: "MapShowcase"
- $.specialEvents[74].eventId: "CalamariV9"
+ $.specialEvents[74].eventId: "MapShowcaseQuiche"
- $.specialEvents[74].mainEndTime: "2026-09-29T15:00:00"
+ $.specialEvents[74].mainEndTime: "2026-03-24T15:00:00"
- $.specialEvents[74].postEndTime: "2026-09-29T15:00:00"
+ $.specialEvents[74].postEndTime: "2026-03-24T15:00:00"
- $.specialEvents[74].startTime: "2026-09-08T15:00:00"
+ $.specialEvents[74].startTime: "2026-03-17T15:00:00"
- $.specialEvents[74].useCommonData: false
+ $.specialEvents[74].useCommonData: true
- $.specialEvents[75].eventId: "MapShowcaseQuiche"
+ $.specialEvents[75].eventId: "MapShowcaseSushi01"
- $.specialEvents[75].eventName.de: "Illusion des Tricksters"
+ $.specialEvents[75].eventName.de: "Sprithimmel"
- $.specialEvents[75].eventName.en: "Trickster's Delusion"
+ $.specialEvents[75].eventName.en: "Gas Heaven"
- $.specialEvents[75].eventName.es: "Delirio del Traicionero"
+ $.specialEvents[75].eventName.es: "Gasolinera"
- $.specialEvents[75].eventName["es-MX"]: "Delirio del Embaucador"
+ $.specialEvents[75].eventName["es-MX"]: "Gasolinera"
- $.specialEvents[75].eventName.fr: "Illusion du Farceur"
+ $.specialEvents[75].eventName.fr: "Gas Heaven"
- $.specialEvents[75].eventName.it: "Illusione dell'Ingannatore"
+ $.specialEvents[75].eventName.it: "Gas Heaven"
- $.specialEvents[75].eventName.ja: "トリックスターの妄想"
+ $.specialEvents[75].eventName.ja: "ガス・ヘヴン"
- $.specialEvents[75].eventName.ko: "트릭스터의 망상"
+ $.specialEvents[75].eventName.ko: "가스 헤븐"
- $.specialEvents[75].eventName.pl: "Urojenia Magika"
+ $.specialEvents[75].eventName.pl: "Stacja Paliw"
- $.specialEvents[75].eventName["pt-BR"]: "Desilusão do Trapaça"
+ $.specialEvents[75].eventName["pt-BR"]: "Paraíso do Combustível"
- $.specialEvents[75].eventName.ru: "Морок Трюкача"
+ $.specialEvents[75].eventName.ru: "Гэс Хевен"
- $.specialEvents[75].eventName.th: "ภาพหลอนของทริกสเตอร์"
+ $.specialEvents[75].eventName.th: "ร้านแก๊สเฮเว่น"
- $.specialEvents[75].eventName.tr: "Dümenci'nin Yanılması"
+ $.specialEvents[75].eventName.tr: "Benzin İstasyonu"
- $.specialEvents[75].eventName["zh-Hans"]: "骗术师的妄想"
+ $.specialEvents[75].eventName["zh-Hans"]: "汽油天堂"
- $.specialEvents[75].eventName["zh-Hant"]: "騙術師的妄想"
+ $.specialEvents[75].eventName["zh-Hant"]: "廢棄加油站"
- $.specialEvents[75].mainEndTime: "2026-03-24T15:00:00"
+ $.specialEvents[75].mainEndTime: "2026-05-26T15:00:00"
- $.specialEvents[75].postEndTime: "2026-03-24T15:00:00"
+ $.specialEvents[75].postEndTime: "2026-05-26T15:00:00"
- $.specialEvents[75].startTime: "2026-03-17T15:00:00"
+ $.specialEvents[75].startTime: "2026-05-25T15:00:00"
- $.specialEvents[76].eventId: "MapShowcaseSushi01"
+ $.specialEvents[76].eventId: "MapShowcaseSushi02"
- $.specialEvents[76].eventName.de: "Sprithimmel"
+ $.specialEvents[76].eventName.de: "Pater Campbells Kapelle"
- $.specialEvents[76].eventName.en: "Gas Heaven"
+ $.specialEvents[76].eventName.en: "Father Campbell's Chapel"
- $.specialEvents[76].eventName.es: "Gasolinera"
+ $.specialEvents[76].eventName.es: "Capilla del padre Campbell"
- $.specialEvents[76].eventName["es-MX"]: "Gasolinera"
+ $.specialEvents[76].eventName["es-MX"]: "Capilla del padre Campbell"
- $.specialEvents[76].eventName.fr: "Gas Heaven"
+ $.specialEvents[76].eventName.fr: "Chapelle du père Campbell"
- $.specialEvents[76].eventName.it: "Gas Heaven"
+ $.specialEvents[76].eventName.it: "Chiesa di Padre Campbell"
- $.specialEvents[76].eventName.ja: "ガス・ヘヴン"
+ $.specialEvents[76].eventName.ja: "ファザー・キャンベルズ・チャペル"
- $.specialEvents[76].eventName.ko: "가스 헤븐"
+ $.specialEvents[76].eventName.ko: "캠벨 신부의 예배당"
- $.specialEvents[76].eventName.pl: "Stacja Paliw"
+ $.specialEvents[76].eventName.pl: "Kaplica Ojca Campbella"
- $.specialEvents[76].eventName["pt-BR"]: "Paraíso do Combustível"
+ $.specialEvents[76].eventName["pt-BR"]: "Capela do Padre Campbell"
- $.specialEvents[76].eventName.ru: "Гэс Хевен"
+ $.specialEvents[76].eventName.ru: "Часовня Отца Кэмпбелла"
- $.specialEvents[76].eventName.th: "ร้านแก๊สเฮเว่น"
+ $.specialEvents[76].eventName.th: "โบสถ์น้อยของบาทหลวงแคมป์เบล"
- $.specialEvents[76].eventName.tr: "Benzin İstasyonu"
+ $.specialEvents[76].eventName.tr: "Peder Campbell'in Kilisesi"
- $.specialEvents[76].eventName["zh-Hans"]: "汽油天堂"
+ $.specialEvents[76].eventName["zh-Hans"]: "坎贝尔神父的教堂"
- $.specialEvents[76].eventName["zh-Hant"]: "廢棄加油站"
+ $.specialEvents[76].eventName["zh-Hant"]: "坎貝爾神父的教堂"
- $.specialEvents[77].eventId: "MapShowcaseSushi02"
+ $.specialEvents[77].eventId: "MapShowcaseSushi03"
- $.specialEvents[77].eventName.de: "Pater Campbells Kapelle"
+ $.specialEvents[77].eventName.de: "Mutters Behausung"
- $.specialEvents[77].eventName.en: "Father Campbell's Chapel"
+ $.specialEvents[77].eventName.en: "Mother's Dwelling"
- $.specialEvents[77].eventName.es: "Capilla del padre Campbell"
+ $.specialEvents[77].eventName.es: "Morada maternal"
- $.specialEvents[77].eventName["es-MX"]: "Capilla del padre Campbell"
+ $.specialEvents[77].eventName["es-MX"]: "Morada maternal"
- $.specialEvents[77].eventName.fr: "Chapelle du père Campbell"
+ $.specialEvents[77].eventName.fr: "La maison maternelle"
- $.specialEvents[77].eventName.it: "Chiesa di Padre Campbell"
+ $.specialEvents[77].eventName.it: "La casetta della mamma"
- $.specialEvents[77].eventName.ja: "ファザー・キャンベルズ・チャペル"
+ $.specialEvents[77].eventName.ja: "マザーズ・ドゥエリング"
- $.specialEvents[77].eventName.ko: "캠벨 신부의 예배당"
+ $.specialEvents[77].eventName.ko: "어머니의 집"
- $.specialEvents[77].eventName.pl: "Kaplica Ojca Campbella"
+ $.specialEvents[77].eventName.pl: "Dom Matki"
- $.specialEvents[77].eventName["pt-BR"]: "Capela do Padre Campbell"
+ $.specialEvents[77].eventName["pt-BR"]: "A Casa da Mamãe"
- $.specialEvents[77].eventName.ru: "Часовня Отца Кэмпбелла"
+ $.specialEvents[77].eventName.ru: "Обитель Матери"
- $.specialEvents[77].eventName.th: "โบสถ์น้อยของบาทหลวงแคมป์เบล"
+ $.specialEvents[77].eventName.th: "ที่พำนักของแม่"
- $.specialEvents[77].eventName.tr: "Peder Campbell'in Kilisesi"
+ $.specialEvents[77].eventName.tr: "Ana Yuvası"
- $.specialEvents[77].eventName["zh-Hans"]: "坎贝尔神父的教堂"
+ $.specialEvents[77].eventName["zh-Hans"]: "母亲的住所"
- $.specialEvents[77].eventName["zh-Hant"]: "坎貝爾神父的教堂"
+ $.specialEvents[77].eventName["zh-Hant"]: "母親的住所"
- $.specialEvents[78].eventId: "MapShowcaseSushi03"
+ $.specialEvents[78].eventId: "MapShowcaseSushi04"
- $.specialEvents[78].eventName.de: "Mutters Behausung"
+ $.specialEvents[78].eventName.de: "Skiort am Mount Ormond"
- $.specialEvents[78].eventName.en: "Mother's Dwelling"
+ $.specialEvents[78].eventName.en: "Mount Ormond Resort"
- $.specialEvents[78].eventName.es: "Morada maternal"
+ $.specialEvents[78].eventName.es: "Complejo del monte Ormond"
- $.specialEvents[78].eventName["es-MX"]: "Morada maternal"
+ $.specialEvents[78].eventName["es-MX"]: "Complejo del monte Ormond"
- $.specialEvents[78].eventName.fr: "La maison maternelle"
+ $.specialEvents[78].eventName.fr: "Station du mont Ormond"
- $.specialEvents[78].eventName.it: "La casetta della mamma"
+ $.specialEvents[78].eventName.it: "Resort del Monte Ormond"
- $.specialEvents[78].eventName.ja: "マザーズ・ドゥエリング"
+ $.specialEvents[78].eventName.ja: "オーモンド山のリゾート"
- $.specialEvents[78].eventName.ko: "어머니의 집"
+ $.specialEvents[78].eventName.ko: "오르몬드 산 리조트"
- $.specialEvents[78].eventName.pl: "Dom Matki"
+ $.specialEvents[78].eventName.pl: "Ośrodek Mount Ormond"
- $.specialEvents[78].eventName["pt-BR"]: "A Casa da Mamãe"
+ $.specialEvents[78].eventName["pt-BR"]: "Resort do Monte Ormond"
- $.specialEvents[78].eventName.ru: "Обитель Матери"
+ $.specialEvents[78].eventName.ru: "Курорт «Гора Ормонд»"
- $.specialEvents[78].eventName.th: "ที่พำนักของแม่"
+ $.specialEvents[78].eventName.th: "ที่พักตากอากาศเขาออร์มอนด์"
- $.specialEvents[78].eventName.tr: "Ana Yuvası"
+ $.specialEvents[78].eventName.tr: "Ormond Dağı Tatil Yeri"
- $.specialEvents[78].eventName["zh-Hans"]: "母亲的住所"
+ $.specialEvents[78].eventName["zh-Hans"]: "奥蒙德山度假村"
- $.specialEvents[78].eventName["zh-Hant"]: "母親的住所"
+ $.specialEvents[78].eventName["zh-Hant"]: "奧蒙德山度假村"
- $.specialEvents[79].eventId: "MapShowcaseSushi04"
+ $.specialEvents[79].eventId: "MapShowcaseSushi05"
- $.specialEvents[79].eventName.de: "Skiort am Mount Ormond"
+ $.specialEvents[79].eventName.de: "Heiligtum des Zorns"
- $.specialEvents[79].eventName.en: "Mount Ormond Resort"
+ $.specialEvents[79].eventName.en: "Sanctum of Wrath"
- $.specialEvents[79].eventName.es: "Complejo del monte Ormond"
+ $.specialEvents[79].eventName.es: "Santuario de la cólera"
- $.specialEvents[79].eventName["es-MX"]: "Complejo del monte Ormond"
+ $.specialEvents[79].eventName["es-MX"]: "Santuario de la ira"
- $.specialEvents[79].eventName.fr: "Station du mont Ormond"
+ $.specialEvents[79].eventName.fr: "Sanctuaire du courroux"
- $.specialEvents[79].eventName.it: "Resort del Monte Ormond"
+ $.specialEvents[79].eventName.it: "Sacrario dell'Ira"
- $.specialEvents[79].eventName.ja: "オーモンド山のリゾート"
+ $.specialEvents[79].eventName.ja: "怒りの聖所"
- $.specialEvents[79].eventName.ko: "오르몬드 산 리조트"
+ $.specialEvents[79].eventName.ko: "분노의 성소"
- $.specialEvents[79].eventName.pl: "Ośrodek Mount Ormond"
+ $.specialEvents[79].eventName.pl: "Sanktuarium Gniewu"
- $.specialEvents[79].eventName["pt-BR"]: "Resort do Monte Ormond"
+ $.specialEvents[79].eventName["pt-BR"]: "Santuário da Ira"
- $.specialEvents[79].eventName.ru: "Курорт «Гора Ормонд»"
+ $.specialEvents[79].eventName.ru: "Прибежище гнева"
- $.specialEvents[79].eventName.th: "ที่พักตากอากาศเขาออร์มอนด์"
+ $.specialEvents[79].eventName.th: "สักการสถานแห่งโทสะ"
- $.specialEvents[79].eventName.tr: "Ormond Dağı Tatil Yeri"
+ $.specialEvents[79].eventName.tr: "Hiddet Sunağı"
- $.specialEvents[79].eventName["zh-Hans"]: "奥蒙德山度假村"
+ $.specialEvents[79].eventName["zh-Hans"]: "愤怒圣所"
- $.specialEvents[79].eventName["zh-Hant"]: "奧蒙德山度假村"
+ $.specialEvents[79].eventName["zh-Hant"]: "怒火聖地"
- $.specialEvents[80].eventId: "MapShowcaseSushi05"
+ $.specialEvents[80].eventId: "MapShowcaseSushi06"
- $.specialEvents[80].eventName.de: "Heiligtum des Zorns"
+ $.specialEvents[80].eventName.de: "Dead Dawg Saloon"
- $.specialEvents[80].eventName.en: "Sanctum of Wrath"
+ $.specialEvents[80].eventName.en: "Dead Dawg Saloon"
- $.specialEvents[80].eventName.es: "Santuario de la cólera"
+ $.specialEvents[80].eventName.es: "Salón Dead Dawg"
- $.specialEvents[80].eventName["es-MX"]: "Santuario de la ira"
+ $.specialEvents[80].eventName["es-MX"]: "Cantina el perro muerto"
- $.specialEvents[80].eventName.fr: "Sanctuaire du courroux"
+ $.specialEvents[80].eventName.fr: "Saloon de Dead Dawg"
- $.specialEvents[80].eventName.it: "Sacrario dell'Ira"
+ $.specialEvents[80].eventName.it: "Saloon Dead Dawg"
- $.specialEvents[80].eventName.ja: "怒りの聖所"
+ $.specialEvents[80].eventName.ja: "死んだ犬の酒場"
- $.specialEvents[80].eventName.ko: "분노의 성소"
+ $.specialEvents[80].eventName.ko: "폐허가 된 술집"
- $.specialEvents[80].eventName.pl: "Sanktuarium Gniewu"
+ $.specialEvents[80].eventName.pl: "Knajpa pod Martwym Ziomkiem"
… 380 more change(s) — see the commit diff for everything
```

