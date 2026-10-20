# live · 10.0.1_3457527live

| | |
|---|---|
| Build date | 2026-06-22 14:07 UTC |
| CDN version | `10.0.1_3457527live-1782137256` |
| Key | `10.0.1_live` |
| Compared with | [10.0.0_3457423live](../10.0.0_3457423live/CHANGES.md) (2026-06-19 20:04 UTC) |

## Summary

**0** added · **17** modified · **9** removed · 194 unchanged

## Removed files

- `images/T_UI_ChapterBundle_Jason.png`
- `images/T_UI_ChapterBundle_TheLifeRoad.png`
- `images/T_UI_CollectionBanner_Black_Banquet.png`
- `images/T_UI_CollectionBanner_Ice_Nine_Kills.png`
- `images/T_UI_CollectionBanner_Jason.png`
- `images/T_UI_S53_ShaneWiigwaas_Portrait.png`
- `images/T_UI_SpecialPack_Ice_Nine_Kills.png`
- `images/T_UI_SpecialPack_Jason.png`
- `images/T_UI_SpecialPack_TwistedMasquerade_2025_Bundle.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.enableBetaHub: false
+ $.enableBetaHub: true
```

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
+ $.TOME24.vignettes[id=TOME24_02]
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
+ $.TOME24.TOME24_02
```

### [`archiveQuests/Tome10.json`](archiveQuests/Tome10.json)

[Full line-by-line diff](diffs/archiveQuests/Tome10.json.diff)

```diff
- $.Tome10.level[0].nodes.node_T10L1_01.coordinates.x: 6.666666667
+ $.Tome10.level[0].nodes.node_T10L1_01.coordinates.x: 6.666666666666667
- $.Tome10.level[0].nodes.node_T10L1_01.coordinates.y: 23.07692308
+ $.Tome10.level[0].nodes.node_T10L1_01.coordinates.y: 23.076923076923077
- $.Tome10.level[0].nodes.node_T10L1_02.coordinates.x: 6.666666667
+ $.Tome10.level[0].nodes.node_T10L1_02.coordinates.x: 6.666666666666667
- $.Tome10.level[0].nodes.node_T10L1_02.coordinates.y: 92.30769231
+ $.Tome10.level[0].nodes.node_T10L1_02.coordinates.y: 92.3076923076923
- $.Tome10.level[0].nodes.node_T10L1_03.coordinates.x: 63.33333333
+ $.Tome10.level[0].nodes.node_T10L1_03.coordinates.x: 63.333333333333336
- $.Tome10.level[0].nodes.node_T10L1_04.coordinates.x: 43.33333333
+ $.Tome10.level[0].nodes.node_T10L1_04.coordinates.x: 43.333333333333336
- $.Tome10.level[0].nodes.node_T10L1_05.coordinates.y: 23.07692308
+ $.Tome10.level[0].nodes.node_T10L1_05.coordinates.y: 23.076923076923077
- $.Tome10.level[0].nodes.node_T10L1_06.coordinates.x: 46.66666667
+ $.Tome10.level[0].nodes.node_T10L1_06.coordinates.x: 46.666666666666664
- $.Tome10.level[0].nodes.node_T10L1_06.coordinates.y: 92.30769231
+ $.Tome10.level[0].nodes.node_T10L1_06.coordinates.y: 92.3076923076923
- $.Tome10.level[0].nodes.node_T10L1_07.coordinates.x: 93.33333333
+ $.Tome10.level[0].nodes.node_T10L1_07.coordinates.x: 93.33333333333333
- $.Tome10.level[0].nodes.node_T10L1_07.coordinates.y: 92.30769231
+ $.Tome10.level[0].nodes.node_T10L1_07.coordinates.y: 92.3076923076923
- $.Tome10.level[0].nodes.node_T10L1_08.coordinates.x: 73.33333333
+ $.Tome10.level[0].nodes.node_T10L1_08.coordinates.x: 73.33333333333333
- $.Tome10.level[0].nodes.node_T10L1_08.coordinates.y: 46.15384615
+ $.Tome10.level[0].nodes.node_T10L1_08.coordinates.y: 46.15384615384615
- $.Tome10.level[0].nodes.node_T10L1_09.coordinates.x: 33.33333333
+ $.Tome10.level[0].nodes.node_T10L1_09.coordinates.x: 33.333333333333336
- $.Tome10.level[0].nodes.node_T10L1_09.coordinates.y: 69.23076923
+ $.Tome10.level[0].nodes.node_T10L1_09.coordinates.y: 69.23076923076923
- $.Tome10.level[0].nodes.node_T10L1_11.coordinates.y: 92.30769231
+ $.Tome10.level[0].nodes.node_T10L1_11.coordinates.y: 92.3076923076923
- $.Tome10.level[0].nodes.node_T10L1_12.coordinates.x: 26.66666667
+ $.Tome10.level[0].nodes.node_T10L1_12.coordinates.x: 26.666666666666668
- $.Tome10.level[0].nodes.node_T10L1_12.coordinates.y: 46.15384615
+ $.Tome10.level[0].nodes.node_T10L1_12.coordinates.y: 46.15384615384615
- $.Tome10.level[0].nodes.node_T10L1_13.coordinates.x: 13.33333333
+ $.Tome10.level[0].nodes.node_T10L1_13.coordinates.x: 13.333333333333334
- $.Tome10.level[0].nodes.node_T10L1_13.coordinates.y: 69.23076923
+ $.Tome10.level[0].nodes.node_T10L1_13.coordinates.y: 69.23076923076923
- $.Tome10.level[0].nodes.node_T10L1_14.coordinates.x: 53.33333333
+ $.Tome10.level[0].nodes.node_T10L1_14.coordinates.x: 53.333333333333336
- $.Tome10.level[0].nodes.node_T10L1_14.coordinates.y: 69.23076923
+ $.Tome10.level[0].nodes.node_T10L1_14.coordinates.y: 69.23076923076923
- $.Tome10.level[0].nodes.node_T10L1_15.coordinates.x: 86.66666667
+ $.Tome10.level[0].nodes.node_T10L1_15.coordinates.x: 86.66666666666667
- $.Tome10.level[0].nodes.node_T10L1_15.coordinates.y: 46.15384615
+ $.Tome10.level[0].nodes.node_T10L1_15.coordinates.y: 46.15384615384615
- $.Tome10.level[0].nodes.node_T10L1_17.coordinates.y: 92.30769231
+ $.Tome10.level[0].nodes.node_T10L1_17.coordinates.y: 92.3076923076923
- $.Tome10.level[0].nodes.node_T10L1_18.coordinates.x: 86.66666667
+ $.Tome10.level[0].nodes.node_T10L1_18.coordinates.x: 86.66666666666667
- $.Tome10.level[0].nodes.node_T10L1_18.coordinates.y: 23.07692308
+ $.Tome10.level[0].nodes.node_T10L1_18.coordinates.y: 23.076923076923077
- $.Tome10.level[0].nodes.node_T10L1_19.coordinates.x: 33.33333333
+ $.Tome10.level[0].nodes.node_T10L1_19.coordinates.x: 33.333333333333336
- $.Tome10.level[0].nodes.node_T10L1_19.coordinates.y: 23.07692308
+ $.Tome10.level[0].nodes.node_T10L1_19.coordinates.y: 23.076923076923077
- $.Tome10.level[0].nodes.node_T10L1_20.coordinates.x: 73.33333333
+ $.Tome10.level[0].nodes.node_T10L1_20.coordinates.x: 73.33333333333333
- $.Tome10.level[0].nodes.node_T10L1_20.coordinates.y: 23.07692308
+ $.Tome10.level[0].nodes.node_T10L1_20.coordinates.y: 23.076923076923077
- $.Tome10.level[0].nodes.node_T10L1_21.coordinates.x: 66.66666667
+ $.Tome10.level[0].nodes.node_T10L1_21.coordinates.x: 66.66666666666667
- $.Tome10.level[0].nodes.node_T10L1_21.coordinates.y: 69.23076923
+ $.Tome10.level[0].nodes.node_T10L1_21.coordinates.y: 69.23076923076923
- $.Tome10.level[0].nodes.node_T10L1_22.coordinates.y: 69.23076923
+ $.Tome10.level[0].nodes.node_T10L1_22.coordinates.y: 69.23076923076923
- $.Tome10.level[0].nodes.node_T10L1_End01.coordinates.y: 23.07692308
+ $.Tome10.level[0].nodes.node_T10L1_End01.coordinates.y: 23.076923076923077
- $.Tome10.level[0].nodes.node_T10L1_Glyph01.coordinates.x: 53.33333333
+ $.Tome10.level[0].nodes.node_T10L1_Glyph01.coordinates.x: 53.333333333333336
- $.Tome10.level[0].nodes.node_T10L1_Glyph01.coordinates.y: 23.07692308
+ $.Tome10.level[0].nodes.node_T10L1_Glyph01.coordinates.y: 23.076923076923077
- $.Tome10.level[0].nodes.node_T10L1_Glyph02.clientInfoId: "YellowGlyph"
+ $.Tome10.level[0].nodes.node_T10L1_Glyph02.clientInfoId: "WhiteGlyph"
- $.Tome10.level[0].nodes.node_T10L1_Glyph02.coordinates.x: 43.33333333
+ $.Tome10.level[0].nodes.node_T10L1_Glyph02.coordinates.x: 43.333333333333336
- $.Tome10.level[0].nodes.node_T10L1_Glyph02.coordinates.y: 46.15384615
+ $.Tome10.level[0].nodes.node_T10L1_Glyph02.coordinates.y: 46.15384615384615
- $.Tome10.level[0].nodes.node_T10L1_Glyph02.objectives.YellowGlyph
+ $.Tome10.level[0].nodes.node_T10L1_Glyph02.objectives.WhiteGlyph
- $.Tome10.level[0].nodes.node_T10L1_Start01.coordinates.y: 46.15384615
+ $.Tome10.level[0].nodes.node_T10L1_Start01.coordinates.y: 46.15384615384615
- $.Tome10.level[1].nodes.node_T10L2_Glyph01.clientInfoId: "YellowGlyph"
+ $.Tome10.level[1].nodes.node_T10L2_Glyph01.clientInfoId: "WhiteGlyph"
- $.Tome10.level[1].nodes.node_T10L2_Glyph01.objectives.YellowGlyph
+ $.Tome10.level[1].nodes.node_T10L2_Glyph01.objectives.WhiteGlyph
- $.Tome10.level[2].nodes.node_T10L3_01.coordinates.x: 33.33333333
+ $.Tome10.level[2].nodes.node_T10L3_01.coordinates.x: 33.333333333333336
- $.Tome10.level[2].nodes.node_T10L3_01.coordinates.y: 46.15384615
+ $.Tome10.level[2].nodes.node_T10L3_01.coordinates.y: 46.15384615384615
- $.Tome10.level[2].nodes.node_T10L3_02.coordinates.x: 73.33333333
+ $.Tome10.level[2].nodes.node_T10L3_02.coordinates.x: 73.33333333333333
- $.Tome10.level[2].nodes.node_T10L3_03.coordinates.x: 33.33333333
+ $.Tome10.level[2].nodes.node_T10L3_03.coordinates.x: 33.333333333333336
- $.Tome10.level[2].nodes.node_T10L3_03.coordinates.y: 69.23076923
+ $.Tome10.level[2].nodes.node_T10L3_03.coordinates.y: 69.23076923076923
- $.Tome10.level[2].nodes.node_T10L3_04.coordinates.x: 86.66666667
+ $.Tome10.level[2].nodes.node_T10L3_04.coordinates.x: 86.66666666666667
- $.Tome10.level[2].nodes.node_T10L3_04.coordinates.y: 23.07692308
+ $.Tome10.level[2].nodes.node_T10L3_04.coordinates.y: 23.076923076923077
- $.Tome10.level[2].nodes.node_T10L3_05.coordinates.x: 46.66666667
+ $.Tome10.level[2].nodes.node_T10L3_05.coordinates.x: 46.666666666666664
- $.Tome10.level[2].nodes.node_T10L3_06.coordinates.y: 92.30769231
+ $.Tome10.level[2].nodes.node_T10L3_06.coordinates.y: 92.3076923076923
- $.Tome10.level[2].nodes.node_T10L3_08.coordinates.x: 66.66666667
+ $.Tome10.level[2].nodes.node_T10L3_08.coordinates.x: 66.66666666666667
- $.Tome10.level[2].nodes.node_T10L3_08.coordinates.y: 92.30769231
+ $.Tome10.level[2].nodes.node_T10L3_08.coordinates.y: 92.3076923076923
- $.Tome10.level[2].nodes.node_T10L3_09.coordinates.y: 23.07692308
+ $.Tome10.level[2].nodes.node_T10L3_09.coordinates.y: 23.076923076923077
- $.Tome10.level[2].nodes.node_T10L3_10.coordinates.x: 13.33333333
+ $.Tome10.level[2].nodes.node_T10L3_10.coordinates.x: 13.333333333333334
- $.Tome10.level[2].nodes.node_T10L3_10.coordinates.y: 23.07692308
+ $.Tome10.level[2].nodes.node_T10L3_10.coordinates.y: 23.076923076923077
- $.Tome10.level[2].nodes.node_T10L3_11.coordinates.y: 46.15384615
+ $.Tome10.level[2].nodes.node_T10L3_11.coordinates.y: 46.15384615384615
- $.Tome10.level[2].nodes.node_T10L3_12.coordinates.x: 93.33333333
+ $.Tome10.level[2].nodes.node_T10L3_12.coordinates.x: 93.33333333333333
- $.Tome10.level[2].nodes.node_T10L3_12.coordinates.y: 69.23076923
+ $.Tome10.level[2].nodes.node_T10L3_12.coordinates.y: 69.23076923076923
- $.Tome10.level[2].nodes.node_T10L3_13.coordinates.y: 92.30769231
+ $.Tome10.level[2].nodes.node_T10L3_13.coordinates.y: 92.3076923076923
- $.Tome10.level[2].nodes.node_T10L3_14.coordinates.x: 13.33333333
+ $.Tome10.level[2].nodes.node_T10L3_14.coordinates.x: 13.333333333333334
- $.Tome10.level[2].nodes.node_T10L3_14.coordinates.y: 92.30769231
+ $.Tome10.level[2].nodes.node_T10L3_14.coordinates.y: 92.3076923076923
- $.Tome10.level[2].nodes.node_T10L3_15.coordinates.x: 53.33333333
+ $.Tome10.level[2].nodes.node_T10L3_15.coordinates.x: 53.333333333333336
- $.Tome10.level[2].nodes.node_T10L3_15.coordinates.y: 46.15384615
+ $.Tome10.level[2].nodes.node_T10L3_15.coordinates.y: 46.15384615384615
- $.Tome10.level[2].nodes.node_T10L3_16.coordinates.x: 46.66666667
+ $.Tome10.level[2].nodes.node_T10L3_16.coordinates.x: 46.666666666666664
- $.Tome10.level[2].nodes.node_T10L3_16.coordinates.y: 23.07692308
+ $.Tome10.level[2].nodes.node_T10L3_16.coordinates.y: 23.076923076923077
- $.Tome10.level[2].nodes.node_T10L3_17.coordinates.x: 6.666666667
+ $.Tome10.level[2].nodes.node_T10L3_17.coordinates.x: 6.666666666666667
- $.Tome10.level[2].nodes.node_T10L3_17.coordinates.y: 46.15384615
+ $.Tome10.level[2].nodes.node_T10L3_17.coordinates.y: 46.15384615384615
- $.Tome10.level[2].nodes.node_T10L3_18.coordinates.x: 46.66666667
+ $.Tome10.level[2].nodes.node_T10L3_18.coordinates.x: 46.666666666666664
- $.Tome10.level[2].nodes.node_T10L3_18.coordinates.y: 69.23076923
+ $.Tome10.level[2].nodes.node_T10L3_18.coordinates.y: 69.23076923076923
- $.Tome10.level[2].nodes.node_T10L3_19.coordinates.x: 73.33333333
+ $.Tome10.level[2].nodes.node_T10L3_19.coordinates.x: 73.33333333333333
- $.Tome10.level[2].nodes.node_T10L3_19.coordinates.y: 69.23076923
+ $.Tome10.level[2].nodes.node_T10L3_19.coordinates.y: 69.23076923076923
- $.Tome10.level[2].nodes.node_T10L3_20.coordinates.x: 73.33333333
+ $.Tome10.level[2].nodes.node_T10L3_20.coordinates.x: 73.33333333333333
- $.Tome10.level[2].nodes.node_T10L3_20.coordinates.y: 23.07692308
+ $.Tome10.level[2].nodes.node_T10L3_20.coordinates.y: 23.076923076923077
- $.Tome10.level[2].nodes.node_T10L3_End01.coordinates.x: 93.33333333
+ $.Tome10.level[2].nodes.node_T10L3_End01.coordinates.x: 93.33333333333333
- $.Tome10.level[2].nodes.node_T10L3_End02.coordinates.y: 92.30769231
+ $.Tome10.level[2].nodes.node_T10L3_End02.coordinates.y: 92.3076923076923
- $.Tome10.level[2].nodes.node_T10L3_Glyph01.clientInfoId: "YellowGlyph"
+ $.Tome10.level[2].nodes.node_T10L3_Glyph01.clientInfoId: "WhiteGlyph"
- $.Tome10.level[2].nodes.node_T10L3_Glyph01.coordinates.x: 26.66666667
+ $.Tome10.level[2].nodes.node_T10L3_Glyph01.coordinates.x: 26.666666666666668
- $.Tome10.level[2].nodes.node_T10L3_Glyph01.coordinates.y: 23.07692308
+ $.Tome10.level[2].nodes.node_T10L3_Glyph01.coordinates.y: 23.076923076923077
- $.Tome10.level[2].nodes.node_T10L3_Glyph01.objectives.YellowGlyph
+ $.Tome10.level[2].nodes.node_T10L3_Glyph01.objectives.WhiteGlyph
- $.Tome10.level[2].nodes.node_T10L3_Glyph02.coordinates.y: 69.23076923
+ $.Tome10.level[2].nodes.node_T10L3_Glyph02.coordinates.y: 69.23076923076923
- $.Tome10.level[2].nodes.node_T10L3_Start01.coordinates.y: 23.07692308
+ $.Tome10.level[2].nodes.node_T10L3_Start01.coordinates.y: 23.076923076923077
- $.Tome10.level[2].nodes.node_T10L3_Start02.coordinates.x: 6.666666667
+ $.Tome10.level[2].nodes.node_T10L3_Start02.coordinates.x: 6.666666666666667
- $.Tome10.level[2].nodes.node_T10L3_Start02.coordinates.y: 69.23076923
+ $.Tome10.level[2].nodes.node_T10L3_Start02.coordinates.y: 69.23076923076923
- $.Tome10.level[3].nodes.node_T10L4_Glyph03.clientInfoId: "YellowGlyph"
+ $.Tome10.level[3].nodes.node_T10L4_Glyph03.clientInfoId: "WhiteGlyph"
- $.Tome10.level[3].nodes.node_T10L4_Glyph03.objectives.YellowGlyph
+ $.Tome10.level[3].nodes.node_T10L4_Glyph03.objectives.WhiteGlyph
```

### [`archiveQuests/Tome11.json`](archiveQuests/Tome11.json)

[Full line-by-line diff](diffs/archiveQuests/Tome11.json.diff)

```diff
- $.Tome11.level[3].nodes.node_T11L4_01.coordinates.x: 73.33333333
+ $.Tome11.level[3].nodes.node_T11L4_01.coordinates.x: 73.33333333333333
- $.Tome11.level[3].nodes.node_T11L4_01.coordinates.y: 34.61538462
+ $.Tome11.level[3].nodes.node_T11L4_01.coordinates.y: 34.61538461538461
- $.Tome11.level[3].nodes.node_T11L4_02.coordinates.y: 23.07692308
+ $.Tome11.level[3].nodes.node_T11L4_02.coordinates.y: 23.076923076923077
- $.Tome11.level[3].nodes.node_T11L4_03.coordinates.x: 86.66666667
+ $.Tome11.level[3].nodes.node_T11L4_03.coordinates.x: 86.66666666666667
- $.Tome11.level[3].nodes.node_T11L4_03.coordinates.y: 34.61538462
+ $.Tome11.level[3].nodes.node_T11L4_03.coordinates.y: 34.61538461538461
- $.Tome11.level[3].nodes.node_T11L4_04.coordinates.x: 53.33333333
+ $.Tome11.level[3].nodes.node_T11L4_04.coordinates.x: 53.333333333333336
- $.Tome11.level[3].nodes.node_T11L4_04.coordinates.y: 34.61538462
+ $.Tome11.level[3].nodes.node_T11L4_04.coordinates.y: 34.61538461538461
- $.Tome11.level[3].nodes.node_T11L4_05.coordinates.y: 69.23076923
+ $.Tome11.level[3].nodes.node_T11L4_05.coordinates.y: 69.23076923076923
- $.Tome11.level[3].nodes.node_T11L4_06.coordinates.y: 69.23076923
+ $.Tome11.level[3].nodes.node_T11L4_06.coordinates.y: 69.23076923076923
- $.Tome11.level[3].nodes.node_T11L4_07.coordinates.y: 46.15384615
+ $.Tome11.level[3].nodes.node_T11L4_07.coordinates.y: 46.15384615384615
- $.Tome11.level[3].nodes.node_T11L4_09.coordinates.x: 46.66666667
+ $.Tome11.level[3].nodes.node_T11L4_09.coordinates.x: 46.666666666666664
- $.Tome11.level[3].nodes.node_T11L4_09.coordinates.y: 69.23076923
+ $.Tome11.level[3].nodes.node_T11L4_09.coordinates.y: 69.23076923076923
- $.Tome11.level[3].nodes.node_T11L4_10.coordinates.y: 69.23076923
+ $.Tome11.level[3].nodes.node_T11L4_10.coordinates.y: 69.23076923076923
- $.Tome11.level[3].nodes.node_T11L4_11.coordinates.x: 86.66666667
+ $.Tome11.level[3].nodes.node_T11L4_11.coordinates.x: 86.66666666666667
- $.Tome11.level[3].nodes.node_T11L4_12.coordinates.y: 92.30769231
+ $.Tome11.level[3].nodes.node_T11L4_12.coordinates.y: 92.3076923076923
- $.Tome11.level[3].nodes.node_T11L4_13.coordinates.x: 73.33333333
+ $.Tome11.level[3].nodes.node_T11L4_13.coordinates.x: 73.33333333333333
- $.Tome11.level[3].nodes.node_T11L4_13.coordinates.y: 92.30769231
+ $.Tome11.level[3].nodes.node_T11L4_13.coordinates.y: 92.3076923076923
- $.Tome11.level[3].nodes.node_T11L4_14.coordinates.y: 92.30769231
+ $.Tome11.level[3].nodes.node_T11L4_14.coordinates.y: 92.3076923076923
- $.Tome11.level[3].nodes.node_T11L4_15.coordinates.y: 23.07692308
+ $.Tome11.level[3].nodes.node_T11L4_15.coordinates.y: 23.076923076923077
- $.Tome11.level[3].nodes.node_T11L4_16.coordinates.y: 46.15384615
+ $.Tome11.level[3].nodes.node_T11L4_16.coordinates.y: 46.15384615384615
- $.Tome11.level[3].nodes.node_T11L4_17.coordinates.x: 53.33333333
+ $.Tome11.level[3].nodes.node_T11L4_17.coordinates.x: 53.333333333333336
- $.Tome11.level[3].nodes.node_T11L4_17.coordinates.y: 11.53846154
+ $.Tome11.level[3].nodes.node_T11L4_17.coordinates.y: 11.538461538461538
- $.Tome11.level[3].nodes.node_T11L4_18.coordinates.x: 53.33333333
+ $.Tome11.level[3].nodes.node_T11L4_18.coordinates.x: 53.333333333333336
- $.Tome11.level[3].nodes.node_T11L4_18.coordinates.y: 57.69230769
+ $.Tome11.level[3].nodes.node_T11L4_18.coordinates.y: 57.69230769230769
- $.Tome11.level[3].nodes.node_T11L4_End01.coordinates.x: 93.33333333
+ $.Tome11.level[3].nodes.node_T11L4_End01.coordinates.x: 93.33333333333333
- $.Tome11.level[3].nodes.node_T11L4_End01.coordinates.y: 69.23076923
+ $.Tome11.level[3].nodes.node_T11L4_End01.coordinates.y: 69.23076923076923
- $.Tome11.level[3].nodes.node_T11L4_End02.coordinates.y: 23.07692308
+ $.Tome11.level[3].nodes.node_T11L4_End02.coordinates.y: 23.076923076923077
- $.Tome11.level[3].nodes.node_T11L4_Glyph01.coordinates.x: 33.33333333
+ $.Tome11.level[3].nodes.node_T11L4_Glyph01.coordinates.x: 33.333333333333336
- $.Tome11.level[3].nodes.node_T11L4_Glyph01.coordinates.y: 46.15384615
+ $.Tome11.level[3].nodes.node_T11L4_Glyph01.coordinates.y: 46.15384615384615
- $.Tome11.level[3].nodes.node_T11L4_Glyph02.coordinates.x: 73.33333333
+ $.Tome11.level[3].nodes.node_T11L4_Glyph02.coordinates.x: 73.33333333333333
- $.Tome11.level[3].nodes.node_T11L4_Glyph03.clientInfoId: "YellowGlyph"
+ $.Tome11.level[3].nodes.node_T11L4_Glyph03.clientInfoId: "WhiteGlyph"
- $.Tome11.level[3].nodes.node_T11L4_Glyph03.coordinates.y: 92.30769231
+ $.Tome11.level[3].nodes.node_T11L4_Glyph03.coordinates.y: 92.3076923076923
- $.Tome11.level[3].nodes.node_T11L4_Glyph03.objectives.YellowGlyph
+ $.Tome11.level[3].nodes.node_T11L4_Glyph03.objectives.WhiteGlyph
- $.Tome11.level[3].nodes.node_T11L4_Start01.coordinates.y: 46.15384615
+ $.Tome11.level[3].nodes.node_T11L4_Start01.coordinates.y: 46.15384615384615
```

### [`archiveQuests/Tome12.json`](archiveQuests/Tome12.json)

[Full line-by-line diff](diffs/archiveQuests/Tome12.json.diff)

```diff
- $.Tome12.level[3].nodes.node_T12L4_Glyph01.clientInfoId: "YellowGlyph"
+ $.Tome12.level[3].nodes.node_T12L4_Glyph01.clientInfoId: "WhiteGlyph"
- $.Tome12.level[3].nodes.node_T12L4_Glyph01.objectives.YellowGlyph
+ $.Tome12.level[3].nodes.node_T12L4_Glyph01.objectives.WhiteGlyph
```

### [`archiveQuests/Tome15.json`](archiveQuests/Tome15.json)

[Full line-by-line diff](diffs/archiveQuests/Tome15.json.diff)

```diff
- $.Tome15.level[2].nodes.node_T15_L3_Glyph02.clientInfoId: "YellowGlyph"
+ $.Tome15.level[2].nodes.node_T15_L3_Glyph02.clientInfoId: "WhiteGlyph"
- $.Tome15.level[2].nodes.node_T15_L3_Glyph02.objectives.YellowGlyph
+ $.Tome15.level[2].nodes.node_T15_L3_Glyph02.objectives.WhiteGlyph
```

### [`archiveQuests/Tome16.json`](archiveQuests/Tome16.json)

[Full line-by-line diff](diffs/archiveQuests/Tome16.json.diff)

```diff
- $.Tome16.level[2].nodes.node_T16_L3_Glyph01.clientInfoId: "YellowGlyph"
+ $.Tome16.level[2].nodes.node_T16_L3_Glyph01.clientInfoId: "WhiteGlyph"
- $.Tome16.level[2].nodes.node_T16_L3_Glyph01.objectives.YellowGlyph
+ $.Tome16.level[2].nodes.node_T16_L3_Glyph01.objectives.WhiteGlyph
```

### [`archiveQuests/Tome17.json`](archiveQuests/Tome17.json)

[Full line-by-line diff](diffs/archiveQuests/Tome17.json.diff)

```diff
- $.Tome17.level[2].nodes.node_T17_L3_Glyph02.clientInfoId: "YellowGlyph"
+ $.Tome17.level[2].nodes.node_T17_L3_Glyph02.clientInfoId: "WhiteGlyph"
- $.Tome17.level[2].nodes.node_T17_L3_Glyph02.objectives.YellowGlyph
+ $.Tome17.level[2].nodes.node_T17_L3_Glyph02.objectives.WhiteGlyph
```

### [`archiveQuests/Tome20.json`](archiveQuests/Tome20.json)

[Full line-by-line diff](diffs/archiveQuests/Tome20.json.diff)

```diff
- $.Tome20.level[3].nodes.node_T20_L4_Glyph01.clientInfoId: "YellowGlyph"
+ $.Tome20.level[3].nodes.node_T20_L4_Glyph01.clientInfoId: "WhiteGlyph"
- $.Tome20.level[3].nodes.node_T20_L4_Glyph01.objectives.YellowGlyph
+ $.Tome20.level[3].nodes.node_T20_L4_Glyph01.objectives.WhiteGlyph
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=From_The_Rift_Bundle_260616]
- $[id=Recurring_Charm_Bundle_260616]
- $[id=Recurring_Dev_Bundle_260616]
- $[id=10.0.0_Dev_Items_collection_item]
+ $[id=10.0.1_Chapter40_collection_item]
- $[id=Ace].eventCostList
- $[id=Ace].metaData.temporaryDiscounts
- $[id=Witch].eventCostList
- $[id=Witch].metaData.temporaryDiscounts
- $[id=Feng].eventCostList
- $[id=Feng].metaData.temporaryDiscounts
- $[id=Killer07].eventCostList
- $[id=Killer07].metaData.temporaryDiscounts
- $[id=Kate].eventCostList
- $[id=Kate].metaData.temporaryDiscounts
- $[id=Cannibal].eventCostList
- $[id=Cannibal].metaData.temporaryDiscounts
- $[id=Quentin].eventCostList
- $[id=Quentin].metaData.temporaryDiscounts
- $[id=Nightmare].eventCostList
- $[id=Nightmare].metaData.temporaryDiscounts
- $[id=Eric].eventCostList
- $[id=Eric].metaData.temporaryDiscounts
- $[id=Pig].eventCostList
- $[id=Pig].metaData.temporaryDiscounts
- $[id=Clown].eventCostList
- $[id=Clown].metaData.temporaryDiscounts
- $[id=Adam].eventCostList
- $[id=Adam].metaData.temporaryDiscounts
- $[id=Spirit].eventCostList
- $[id=Spirit].metaData.temporaryDiscounts
- $[id=Legion].eventCostList
- $[id=Legion].metaData.temporaryDiscounts
- $[id=Jeff].eventCostList
- $[id=Jeff].metaData.temporaryDiscounts
- $[id=Plague].eventCostList
- $[id=Plague].metaData.temporaryDiscounts
- $[id=Jane].eventCostList
- $[id=Jane].metaData.temporaryDiscounts
- $[id=Ash].eventCostList
- $[id=Ash].metaData.temporaryDiscounts
- $[id=Ghostface].eventCostList
- $[id=Ghostface].metaData.temporaryDiscounts
- $[id=Oni].eventCostList
- $[id=Oni].metaData.temporaryDiscounts
- $[id=Yui].eventCostList
- $[id=Yui].metaData.temporaryDiscounts
- $[id=Gunslinger].eventCostList
- $[id=Gunslinger].metaData.temporaryDiscounts
- $[id=Zarina].eventCostList
- $[id=Zarina].metaData.temporaryDiscounts
- $[id=K20].eventCostList
- $[id=K20].metaData.temporaryDiscounts
- $[id=S22].eventCostList
- $[id=S22].metaData.temporaryDiscounts
- $[id=K21].eventCostList
- $[id=K21].metaData.temporaryDiscounts
- $[id=S23].eventCostList
- $[id=S23].metaData.temporaryDiscounts
- $[id=K22].eventCostList
- $[id=K22].metaData.temporaryDiscounts
- $[id=S24].eventCostList
- $[id=S24].metaData.temporaryDiscounts
- $[id=K23].eventCostList
- $[id=K23].metaData.temporaryDiscounts
- $[id=S25].eventCostList
- $[id=S25].metaData.temporaryDiscounts
- $[id=S26].eventCostList
- $[id=S26].metaData.temporaryDiscounts
- $[id=S27].eventCostList
- $[id=S27].metaData.temporaryDiscounts
- $[id=K24].eventCostList
- $[id=K24].metaData.temporaryDiscounts
- $[id=S28].eventCostList
- $[id=S28].metaData.temporaryDiscounts
- $[id=S29].eventCostList
- $[id=S29].metaData.temporaryDiscounts
- $[id=K26].eventCostList
- $[id=K26].metaData.temporaryDiscounts
- $[id=K27].eventCostList
- $[id=K27].metaData.temporaryDiscounts
- $[id=S30].eventCostList
- $[id=S30].metaData.temporaryDiscounts
- $[id=K28].eventCostList
- $[id=K28].metaData.temporaryDiscounts
- $[id=S31].eventCostList
- $[id=S31].metaData.temporaryDiscounts
- $[id=K29].eventCostList
- $[id=K29].metaData.temporaryDiscounts
- $[id=S32].eventCostList
- $[id=S32].metaData.temporaryDiscounts
- $[id=S33].eventCostList
- $[id=S33].metaData.temporaryDiscounts
- $[id=K30].eventCostList
- $[id=K30].metaData.temporaryDiscounts
- $[id=S34].eventCostList
- $[id=S34].metaData.temporaryDiscounts
- $[id=K31].eventCostList
- $[id=K31].metaData.temporaryDiscounts
- $[id=S35].eventCostList
- $[id=S35].metaData.temporaryDiscounts
- $[id=S36].eventCostList
- $[id=S36].metaData.temporaryDiscounts
- $[id=K32].eventCostList
- $[id=K32].metaData.temporaryDiscounts
- $[id=S37].eventCostList
- $[id=S37].metaData.temporaryDiscounts
- $[id=S38].eventCostList
- $[id=S38].metaData.temporaryDiscounts
- $[id=K33].eventCostList
- $[id=K33].metaData.temporaryDiscounts
- $[id=S39].eventCostList
- $[id=S39].metaData.temporaryDiscounts
- $[id=K34].eventCostList
- $[id=K34].metaData.temporaryDiscounts
- $[id=S40].eventCostList
- $[id=S40].metaData.temporaryDiscounts
- $[id=K35].eventCostList
- $[id=K35].metaData.temporaryDiscounts
- $[id=S41].eventCostList
- $[id=S41].metaData.temporaryDiscounts
- $[id=K36].eventCostList
- $[id=K36].metaData.temporaryDiscounts
- $[id=S42].eventCostList
- $[id=S42].metaData.temporaryDiscounts
- $[id=S43].eventCostList
- $[id=S43].metaData.temporaryDiscounts
- $[id=K37].eventCostList
- $[id=K37].metaData.temporaryDiscounts
- $[id=S44].eventCostList
- $[id=S44].metaData.temporaryDiscounts
- $[id=K38].eventCostList
- $[id=K38].metaData.temporaryDiscounts
- $[id=S45].eventCostList
- $[id=S45].metaData.temporaryDiscounts
- $[id=K39].eventCostList
- $[id=K39].metaData.temporaryDiscounts
- $[id=S46].eventCostList
- $[id=S46].metaData.temporaryDiscounts
- $[id=K40].eventCostList
- $[id=K40].metaData.temporaryDiscounts
- $[id=S47].eventCostList
- $[id=S47].metaData.temporaryDiscounts
- $[id=S48].eventCostList
- $[id=S48].metaData.temporaryDiscounts
- $[id=S49].eventCostList
- $[id=S49].metaData.temporaryDiscounts
- $[id=K41].eventCostList
- $[id=K41].metaData.temporaryDiscounts
- $[id=S52].eventCostList
- $[id=S52].metaData.temporaryDiscounts
- $[id=GS_Torso036_01].purchasable: true
+ $[id=GS_Torso036_01].purchasable: false
- $[id=KS_Torso025_01].purchasable: true
+ $[id=KS_Torso025_01].purchasable: false
- $[id=S45_Head015].defaultCost[1]
- $[id=S45_Legs015].defaultCost[1]
- $[id=S45_Torso015].defaultCost[1]
- $[id=S49_Head011].defaultCost[1]
- $[id=S49_Legs011].defaultCost[1]
- $[id=S49_Torso011].defaultCost[1]
- $[id=Ace_outfit_001].metaData.temporaryDiscounts
- $[id=Ace_outfit_002].metaData.temporaryDiscounts
- $[id=Ace_outfit_003].metaData.temporaryDiscounts
- $[id=Ace_outfit_004].metaData.temporaryDiscounts
- $[id=Ace_outfit_005].metaData.temporaryDiscounts
- $[id=Ace_outfit_006].metaData.temporaryDiscounts
- $[id=Ace_outfit_007].metaData.temporaryDiscounts
- $[id=Ace_outfit_007_01].metaData.temporaryDiscounts
- $[id=Ace_outfit_008].metaData.temporaryDiscounts
- $[id=Ace_outfit_008_01].metaData.temporaryDiscounts
- $[id=Ace_outfit_009].metaData.temporaryDiscounts
- $[id=Ace_outfit_010].metaData.temporaryDiscounts
- $[id=Ace_outfit_014].metaData.temporaryDiscounts
- $[id=Ace_outfit_015].metaData.temporaryDiscounts
- $[id=Ace_outfit_016].metaData.temporaryDiscounts
- $[id=Ace_outfit_017].metaData.temporaryDiscounts
- $[id=Adam_outfit_001].metaData.temporaryDiscounts
- $[id=Adam_outfit_002].metaData.temporaryDiscounts
- $[id=Adam_outfit_003].metaData.temporaryDiscounts
- $[id=Adam_outfit_004].metaData.temporaryDiscounts
- $[id=Adam_outfit_005].metaData.temporaryDiscounts
- $[id=Adam_outfit_006].metaData.temporaryDiscounts
- $[id=Adam_outfit_006_01].metaData.temporaryDiscounts
- $[id=Adam_outfit_007].metaData.temporaryDiscounts
- $[id=Adam_outfit_008].metaData.temporaryDiscounts
- $[id=Adam_outfit_008_01].metaData.temporaryDiscounts
- $[id=Adam_outfit_009].metaData.temporaryDiscounts
- $[id=AV_outfit02_03].metaData.temporaryDiscounts
- $[id=AV_outfit_009].metaData.temporaryDiscounts
- $[id=AV_outfit_010].metaData.temporaryDiscounts
- $[id=AV_outfit_011].metaData.temporaryDiscounts
- $[id=AV_outfit_013].metaData.temporaryDiscounts
- $[id=AV_outfit_014].metaData.temporaryDiscounts
- $[id=AV_outfit_015].metaData.temporaryDiscounts
- $[id=AV_outfit_017].metaData.temporaryDiscounts
- $[id=AV_outfit_018].metaData.temporaryDiscounts
- $[id=AV_outfit_019].metaData.temporaryDiscounts
- $[id=AV_outfit_020].metaData.temporaryDiscounts
- $[id=AV_outfit_024].metaData.temporaryDiscounts
… 1770 more change(s) — see the commit diff for everything
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[63].items[]: "GS_Torso036_01"
- $.collections[63].items[]: "KS_Torso025_01"
- $.collections[63].updatedDate: "2026-06-16T15:57:55.957Z"
+ $.collections[63].updatedDate: "2026-03-26T13:30:27.895Z"
- $.collections[67].limitedAvailabilityEndDate: "2026-07-16T15:00:00Z"
- $.collections[67].visibleAfterEndDate: false
- $.collections[67].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
+ $.collections[67].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Help/iconHelp_loadingMissing.iconHelp_loadingMissing"
- $.collections[67].collectionId: "10.0.0_BlackBanquet"
+ $.collections[67].collectionId: "10.0.1_Chapter40"
- $.collections[67].collectionTitle.de: "Schwarzes Bankett"
+ $.collections[67].collectionTitle.de: "The Life Road"
- $.collections[67].collectionTitle.en: "Black Banquet"
+ $.collections[67].collectionTitle.en: "The Life Road"
- $.collections[67].collectionTitle.es: "Banquete oscuro"
+ $.collections[67].collectionTitle.es: "The Life Road"
- $.collections[67].collectionTitle["es-MX"]: "Banquete negro"
+ $.collections[67].collectionTitle["es-MX"]: "The Life Road"
- $.collections[67].collectionTitle.fr: "Sombre banquet"
+ $.collections[67].collectionTitle.fr: "The Life Road"
- $.collections[67].collectionTitle.it: "Banchetto nero"
+ $.collections[67].collectionTitle.it: "The Life Road"
- $.collections[67].collectionTitle.ja: "ブラックバンケット"
+ $.collections[67].collectionTitle.ja: "The Life Road"
- $.collections[67].collectionTitle.ko: "검은 연회"
+ $.collections[67].collectionTitle.ko: "인생의 길"
- $.collections[67].collectionTitle.pl: "Czarny bankiet"
+ $.collections[67].collectionTitle.pl: "Droga życia"
- $.collections[67].collectionTitle["pt-BR"]: "Banquete Sombrio"
+ $.collections[67].collectionTitle["pt-BR"]: "The Life Road"
- $.collections[67].collectionTitle.ru: "Black Banquet"
+ $.collections[67].collectionTitle.ru: "Дорога жизни"
- $.collections[67].collectionTitle.th: "งานเลี้ยงสีดำ"
+ $.collections[67].collectionTitle.th: "ถนนสายชีวิต"
- $.collections[67].collectionTitle.tr: "Siyah Şölen"
+ $.collections[67].collectionTitle.tr: "Hayat Yolu"
- $.collections[67].collectionTitle["zh-Hans"]: "黑暗盛宴"
+ $.collections[67].collectionTitle["zh-Hans"]: "The Life Road"
- $.collections[67].collectionTitle["zh-Hant"]: "黑色饗宴"
+ $.collections[67].collectionTitle["zh-Hant"]: "The Life Road"
- $.collections[67].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_Black_Banquet.T_UI_CollectionBanner_Black_Banquet"
+ $.collections[67].heroImage.path: "/Game/UI/UMGAssets/Icons/Help/iconHelp_loadingMissing.iconHelp_loadingMissing"
- $.collections[67].inclusionVersion: "10.0.0"
+ $.collections[67].inclusionVersion: "10.0.1"
- $.collections[67].items[]: "CM_outfit_036"
- $.collections[67].items[]: "DO_outfit_028"
- $.collections[67].items[]: "GS_outfit_040"
- $.collections[67].items[]: "KK_outfit_041"
+ $.collections[67].items[]: "S53_outfit_006"
+ $.collections[67].items[]: "S53_outfit_006_01"
+ $.collections[67].items[]: "S53_outfit_01_01"
+ $.collections[67].items[]: "S53_outfit_01_02"
+ $.collections[67].items[]: "S53_outfit_01_03"
+ $.collections[67].items[]: "S53_outfit_01_CV01"
+ $.collections[67].items[]: "S53_outfit_01_CV02"
+ $.collections[67].items[]: "S53_outfit_01_CV03"
+ $.collections[67].items[]: "S53_outfit_01_CV04"
+ $.collections[67].items[]: "S53_outfit_02"
+ $.collections[67].items[]: "S53_outfit_02_01"
- $.collections[67].sortOrder: "-239"
+ $.collections[67].sortOrder: "-238"
- $.collections[67].updatedDate: "2026-03-26T13:31:17.979Z"
+ $.collections[67].updatedDate: "2026-03-26T13:27:24.213Z"
+ $.collections[68].limitedAvailabilityEndDate: "2026-07-16T15:00:00Z"
+ $.collections[68].visibleAfterEndDate: false
- $.collections[68].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_SilentHill2_BC.T_UI_SpecialPack_SilentHill2_BC"
+ $.collections[68].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
- $.collections[68].collectionId: "10.0.0_SilentHill"
+ $.collections[68].collectionId: "10.0.0_BlackBanquet"
- $.collections[68].collectionTitle.de: "Silent Hill"
+ $.collections[68].collectionTitle.de: "Schwarzes Bankett"
- $.collections[68].collectionTitle.en: "Silent Hill"
+ $.collections[68].collectionTitle.en: "Black Banquet"
- $.collections[68].collectionTitle.es: "Silent Hill"
+ $.collections[68].collectionTitle.es: "Banquete oscuro"
- $.collections[68].collectionTitle["es-MX"]: "Silent Hill"
+ $.collections[68].collectionTitle["es-MX"]: "Banquete negro"
- $.collections[68].collectionTitle.fr: "Silent Hill"
+ $.collections[68].collectionTitle.fr: "Sombre banquet"
- $.collections[68].collectionTitle.it: "Silent Hill"
+ $.collections[68].collectionTitle.it: "Banchetto nero"
- $.collections[68].collectionTitle.ja: "サイレントヒル"
+ $.collections[68].collectionTitle.ja: "ブラックバンケット"
- $.collections[68].collectionTitle.ko: "사일런트 힐"
+ $.collections[68].collectionTitle.ko: "검은 연회"
- $.collections[68].collectionTitle.pl: "Silent Hill"
+ $.collections[68].collectionTitle.pl: "Czarny bankiet"
- $.collections[68].collectionTitle["pt-BR"]: "Silent Hill"
+ $.collections[68].collectionTitle["pt-BR"]: "Banquete Sombrio"
- $.collections[68].collectionTitle.ru: "Сайлент Хилл"
+ $.collections[68].collectionTitle.ru: "Black Banquet"
- $.collections[68].collectionTitle.th: "ไซเลนต์ฮิล"
+ $.collections[68].collectionTitle.th: "งานเลี้ยงสีดำ"
- $.collections[68].collectionTitle.tr: "Silent Hill"
+ $.collections[68].collectionTitle.tr: "Siyah Şölen"
- $.collections[68].collectionTitle["zh-Hans"]: "寂静岭"
+ $.collections[68].collectionTitle["zh-Hans"]: "黑暗盛宴"
- $.collections[68].collectionTitle["zh-Hant"]: "沉默之丘"
+ $.collections[68].collectionTitle["zh-Hant"]: "黑色饗宴"
- $.collections[68].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SilentHill.T_UI_CollectionBanner_SilentHill"
+ $.collections[68].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_Black_Banquet.T_UI_CollectionBanner_Black_Banquet"
- $.collections[68].items[]: "FM_outfit_022"
- $.collections[68].items[]: "K20_outfit_006"
- $.collections[68].items[]: "K20_outfit_007"
- $.collections[68].items[]: "K20_outfit_008"
- $.collections[68].items[]: "K20_outfit_009"
- $.collections[68].items[]: "K20_outfit_010"
- $.collections[68].items[]: "KK_outfit_016"
- $.collections[68].items[]: "KK_outfit_016_01"
- $.collections[68].items[]: "KK_outfit_016_02"
- $.collections[68].items[]: "KK_outfit_016_03"
- $.collections[68].items[]: "S22_outfit_006"
- $.collections[68].items[]: "S22_outfit_007"
- $.collections[68].items[]: "S22_outfit_008"
- $.collections[68].items[]: "S22_outfit_010"
- $.collections[68].items[]: "S22_outfit_011"
- $.collections[68].items[]: "S22_outfit_012"
- $.collections[68].items[]: "S22_outfit_013"
- $.collections[68].items[]: "S22_outfit_014"
- $.collections[68].items[]: "S22_outfit_02"
- $.collections[68].items[]: "S22_outfit_02_01"
- $.collections[68].items[]: "S22_Torso01_01"
- $.collections[68].items[]: "S22_Torso01_02"
- $.collections[68].items[]: "S22_Torso01_03"
- $.collections[68].items[]: "S22_Torso01_04"
- $.collections[68].items[]: "S22_Torso01_05"
- $.collections[68].items[]: "S22_Torso01_06"
+ $.collections[68].items[]: "CM_outfit_036"
+ $.collections[68].items[]: "DO_outfit_028"
+ $.collections[68].items[]: "GS_outfit_040"
+ $.collections[68].items[]: "KK_outfit_041"
- $.collections[68].limitedAvailabilityStartDate: "2026-06-30T15:00:00Z"
+ $.collections[68].limitedAvailabilityStartDate: "2026-06-25T15:00:00Z"
- $.collections[68].sortOrder: "-240"
+ $.collections[68].sortOrder: "-239"
- $.collections[68].updatedDate: "2026-03-26T13:29:45.882Z"
+ $.collections[68].updatedDate: "2026-03-26T13:31:17.979Z"
+ $.collections[69].limitedAvailabilityStartDate: "2026-06-30T15:00:00Z"
+ $.collections[69].visibleBeforeStartDate: false
+ $.collections[69].additionalImages[0]
- $.collections[69].collectionId: "GreekLegends"
+ $.collections[69].collectionId: "10.0.0_SilentHill"
- $.collections[69].collectionTitle.de: "Griechische Legenden"
+ $.collections[69].collectionTitle.de: "Silent Hill"
- $.collections[69].collectionTitle.en: "Greek Legends"
+ $.collections[69].collectionTitle.en: "Silent Hill"
- $.collections[69].collectionTitle.es: "Leyendas griegas"
+ $.collections[69].collectionTitle.es: "Silent Hill"
- $.collections[69].collectionTitle["es-MX"]: "Leyendas griegas"
+ $.collections[69].collectionTitle["es-MX"]: "Silent Hill"
- $.collections[69].collectionTitle.fr: "Légendes grecques"
+ $.collections[69].collectionTitle.fr: "Silent Hill"
- $.collections[69].collectionTitle.it: "Leggende greche"
+ $.collections[69].collectionTitle.it: "Silent Hill"
- $.collections[69].collectionTitle.ja: "ギリシャの伝説"
+ $.collections[69].collectionTitle.ja: "サイレントヒル"
- $.collections[69].collectionTitle.ko: "그리스 전설"
+ $.collections[69].collectionTitle.ko: "사일런트 힐"
- $.collections[69].collectionTitle.pl: "Greckie legendy"
+ $.collections[69].collectionTitle.pl: "Silent Hill"
- $.collections[69].collectionTitle["pt-BR"]: "Lendas Gregas"
+ $.collections[69].collectionTitle["pt-BR"]: "Silent Hill"
- $.collections[69].collectionTitle.ru: "Легенды Греции"
+ $.collections[69].collectionTitle.ru: "Сайлент Хилл"
- $.collections[69].collectionTitle.th: "ตำนานกรีก"
+ $.collections[69].collectionTitle.th: "ไซเลนต์ฮิล"
- $.collections[69].collectionTitle.tr: "Yunan Efsaneleri"
+ $.collections[69].collectionTitle.tr: "Silent Hill"
- $.collections[69].collectionTitle["zh-Hans"]: "希腊传说"
+ $.collections[69].collectionTitle["zh-Hans"]: "寂静岭"
- $.collections[69].collectionTitle["zh-Hant"]: "希臘傳奇"
+ $.collections[69].collectionTitle["zh-Hant"]: "沉默之丘"
- $.collections[69].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GreekLegends.T_UI_CollectionBanner_GreekLegends"
+ $.collections[69].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SilentHill.T_UI_CollectionBanner_SilentHill"
- $.collections[69].inclusionVersion: "7.7.0 PTB"
+ $.collections[69].inclusionVersion: "10.0.0"
- $.collections[69].items[]: "AV_outfit_014"
- $.collections[69].items[]: "DK_outfit_012"
- $.collections[69].items[]: "FM_outfit_012"
- $.collections[69].items[]: "GK_outfit_011"
- $.collections[69].items[]: "GS_outfit_016"
- $.collections[69].items[]: "HK_outfit_011"
- $.collections[69].items[]: "HS_outfit_010"
- $.collections[69].items[]: "K21_outfit_008"
- $.collections[69].items[]: "K26_outfit_009"
- $.collections[69].items[]: "K28_outfit_010"
- $.collections[69].items[]: "KS_outfit_012"
- $.collections[69].items[]: "MK_outfit_013"
- $.collections[69].items[]: "MS_outfit_013"
- $.collections[69].items[]: "NK_outfit_022"
- $.collections[69].items[]: "S24_outfit_009"
- $.collections[69].items[]: "S28_outfit_014"
- $.collections[69].items[]: "S35_outfit_009"
- $.collections[69].items[]: "S36_outfit_009"
- $.collections[69].items[]: "SwedenKiller_outfit_009"
- $.collections[69].items[]: "SwedenSurvivor_outfit_011"
- $.collections[69].items[]: "TN_outfit_013"
- $.collections[69].items[]: "US_outfit_009"
+ $.collections[69].items[]: "FM_outfit_022"
+ $.collections[69].items[]: "K20_outfit_006"
… 2063 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[4].MapsWeight.Asy_Chapel: "50"
+ $.schedule[4].MapsWeight.Asy_Chapel: "0"
+ $.schedule[5].LinkedEventId: "MapShowcaseSushi01"
- $.schedule[5].Description: "Killswitch"
+ $.schedule[5].Description: "MapShowcase Map List"
- $.schedule[5].GameModes[]: "Online"
- $.schedule[5].GameModes[]: "KillYourFriends"
- $.schedule[5].GameModes[]: "SecretBotMatch"
- $.schedule[5].GameModes[]: "TutorialBotMatch"
- $.schedule[5].GameModes[]: "ChocolateBox"
- $.schedule[5].GameModes[]: "SeasonalEvent"
- $.schedule[5].GameModes[]: "SeasonalEvent_FuelGenerator"
+ $.schedule[5].GameModes[]: "MapShowcase"
- $.schedule[5].MapsWeight.Eng_Street_01: "0"
- $.schedule[5].MapsWeight.Swp_GrimPantry: "0"
- $.schedule[5].MapsWeight.Swp_PaleRose: "0"
+ $.schedule[5].MapsWeight.Jnk_GasStation: "1000"
+ $.schedule[6]
+ $.schedule[7]
+ $.schedule[8]
+ $.schedule[9]
+ $.schedule[10]
+ $.schedule[11]
+ $.schedule[12]
+ $.schedule[13]
+ $.schedule[14]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "dfd9448cd4b776d86b9efc8edfd389e5246e4a17"
+ $.entries[0].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_TwistedMasquerade_2025_Bundle.T_UI_SpecialPack_TwistedMasquerade_2025_Bundle"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
- $.entries[0].uri: "images/T_UI_SpecialPack_TwistedMasquerade_2025_Bundle.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
- $.entries[1].downloadStrategy: "preferPackaged"
+ $.entries[1].downloadStrategy: "preferRemote"
- $.entries[2].contentVersion: "db5309baacf020722b4fb45023708df4d48fc820"
+ $.entries[2].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Ice_Nine_Kills.T_UI_SpecialPack_Ice_Nine_Kills"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[2].uri: "images/T_UI_SpecialPack_Ice_Nine_Kills.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[3].contentVersion: "e44e4a7791219404be660d1cc9f395396f41fa54"
+ $.entries[3].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TheLifeRoad.T_UI_ChapterBundle_TheLifeRoad"
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[3].uri: "images/T_UI_ChapterBundle_TheLifeRoad.png"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[4].contentVersion: "201d2c22c95e6cfa6cfa270728145726e7973c63"
+ $.entries[4].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_Black_Banquet.T_UI_CollectionBanner_Black_Banquet"
+ $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[4].uri: "images/T_UI_CollectionBanner_Black_Banquet.png"
+ $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[5].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
+ $.entries[5].contentVersion: "1a73827d53e583dd03efaac5b38ab8fb04610088"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
+ $.entries[5].packagedPath: "/DBDUICore/Assets/Common/Event/Community/T_UI_icon_Event_LaFogata.T_UI_icon_Event_LaFogata"
- $.entries[5].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
+ $.entries[5].uri: "images/T_UI_icon_Event_LaFogata.png"
- $.entries[6].contentVersion: "e24e946eb73c45120942d89c2de73814cc1a2e99"
+ $.entries[6].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_Ice_Nine_Kills.T_UI_CollectionBanner_Ice_Nine_Kills"
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
- $.entries[6].uri: "images/T_UI_CollectionBanner_Ice_Nine_Kills.png"
+ $.entries[6].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
- $.entries[7].contentVersion: "db5309baacf020722b4fb45023708df4d48fc820"
+ $.entries[7].contentVersion: "0c384b89ec3ee2a698816988e7ab852a4a584662"
- $.entries[7].downloadStrategy: "preferPackaged"
+ $.entries[7].downloadStrategy: "preferRemote"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Ice_Nine_Kills.T_UI_SpecialPack_Ice_Nine_Kills"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_SpecialPack_Ice_Nine_Kills.png"
+ $.entries[7].uri: "catalog.json"
- $.entries[8].contentVersion: "47c2ee482573517676b096d0f2c295d2e7751af7"
+ $.entries[8].contentVersion: "81034fe5efd667a7bed072051acdc04a0d5e4868"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_Jason.T_UI_CollectionBanner_Jason"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_CollectionBanner_Jason.png"
+ $.entries[8].uri: "bonusPointEventsContent.json"
- $.entries[9].contentVersion: "89cd6761baa172e7467e358fd33d57a45f38c845"
+ $.entries[9].contentVersion: "898051766e5a8c40db1b33642c972d78dda97739"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Jason.T_UI_SpecialPack_Jason"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_SpecialPack_Jason.png"
+ $.entries[9].uri: "freetoplay/NA/event.json"
- $.entries[10].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[10].contentVersion: "898051766e5a8c40db1b33642c972d78dda97739"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].enableChecksum: false
+ $.entries[10].enableChecksum: true
- $.entries[10].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[10].packagedPath: ""
- $.entries[10].schema: "s3verbin://"
+ $.entries[10].schema: "s3ver://"
- $.entries[10].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[10].uri: "freetoplay/EU/event.json"
- $.entries[11].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[11].contentVersion: "23b1f95aaea33a5eb00ef8deb32d515af3be02b1"
- $.entries[11].downloadStrategy: "preferPackaged"
+ $.entries[11].downloadStrategy: "preferRemote"
- $.entries[11].enableChecksum: false
+ $.entries[11].enableChecksum: true
- $.entries[11].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[11].packagedPath: ""
- $.entries[11].schema: "s3verbin://"
+ $.entries[11].schema: "s3ver://"
- $.entries[11].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[11].uri: "archiveQuests/Anniversary2022.json"
- $.entries[12].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[12].contentVersion: "60542d2a101497b73a338989942ef496ae13d010"
- $.entries[12].downloadStrategy: "preferPackaged"
+ $.entries[12].downloadStrategy: "preferRemote"
- $.entries[12].enableChecksum: false
+ $.entries[12].enableChecksum: true
- $.entries[12].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[12].packagedPath: ""
- $.entries[12].schema: "s3verbin://"
+ $.entries[12].schema: "s3ver://"
- $.entries[12].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[12].uri: "archiveQuests/Anniversary2023.json"
- $.entries[13].contentVersion: "1a73827d53e583dd03efaac5b38ab8fb04610088"
+ $.entries[13].contentVersion: "53077fd04e446bfa797e36d08f46746b74d7d514"
- $.entries[13].enableChecksum: false
+ $.entries[13].enableChecksum: true
- $.entries[13].packagedPath: "/DBDUICore/Assets/Common/Event/Community/T_UI_icon_Event_LaFogata.T_UI_icon_Event_LaFogata"
+ $.entries[13].packagedPath: ""
- $.entries[13].schema: "s3verbin://"
+ $.entries[13].schema: "s3ver://"
- $.entries[13].uri: "images/T_UI_icon_Event_LaFogata.png"
+ $.entries[13].uri: "archiveQuests/Anniversary2024.json"
- $.entries[14].contentVersion: "14bd21a042f1ed4a0789bb0b95e7d362b731172a"
+ $.entries[14].contentVersion: "30f6f91bea1afbf1b488a777cbd35039848da3dd"
- $.entries[14].downloadStrategy: "preferPackaged"
+ $.entries[14].downloadStrategy: "preferRemote"
- $.entries[14].enableChecksum: false
+ $.entries[14].enableChecksum: true
- $.entries[14].packagedPath: "/Game/UI/UMGAssets/Icons/CharPortraits/Sushi/T_UI_S53_ShaneWiigwaas_Portrait.T_UI_S53_ShaneWiigwaas_Portrait"
+ $.entries[14].packagedPath: ""
- $.entries[14].schema: "s3verbin://"
+ $.entries[14].schema: "s3ver://"
- $.entries[14].uri: "images/T_UI_S53_ShaneWiigwaas_Portrait.png"
+ $.entries[14].uri: "archiveQuests/CalamariV1.json"
- $.entries[15].contentVersion: "54d5075735b1b4725094ae412868732d720ee188"
+ $.entries[15].contentVersion: "979deafa6eaa6e239324ae0bb63a325b0b954060"
- $.entries[15].downloadStrategy: "preferPackaged"
+ $.entries[15].downloadStrategy: "preferRemote"
- $.entries[15].enableChecksum: false
+ $.entries[15].enableChecksum: true
- $.entries[15].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Jason.T_UI_ChapterBundle_Jason"
+ $.entries[15].packagedPath: ""
- $.entries[15].schema: "s3verbin://"
+ $.entries[15].schema: "s3ver://"
- $.entries[15].uri: "images/T_UI_ChapterBundle_Jason.png"
+ $.entries[15].uri: "archiveQuests/CalamariV2.json"
- $.entries[16].contentVersion: "201d2c22c95e6cfa6cfa270728145726e7973c63"
+ $.entries[16].contentVersion: "a929110e9b2f53b4ad7d9984a3619abad514c4bc"
- $.entries[16].downloadStrategy: "preferPackaged"
+ $.entries[16].downloadStrategy: "preferRemote"
- $.entries[16].enableChecksum: false
+ $.entries[16].enableChecksum: true
- $.entries[16].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_Black_Banquet.T_UI_CollectionBanner_Black_Banquet"
+ $.entries[16].packagedPath: ""
- $.entries[16].schema: "s3verbin://"
+ $.entries[16].schema: "s3ver://"
- $.entries[16].uri: "images/T_UI_CollectionBanner_Black_Banquet.png"
+ $.entries[16].uri: "archiveQuests/CalamariV3.json"
- $.entries[17].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
+ $.entries[17].contentVersion: "c4a0c4fb3e9426161dab7bdeb23c586d22c0b1b5"
- $.entries[17].downloadStrategy: "preferPackaged"
+ $.entries[17].downloadStrategy: "preferRemote"
- $.entries[17].enableChecksum: false
+ $.entries[17].enableChecksum: true
- $.entries[17].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
+ $.entries[17].packagedPath: ""
- $.entries[17].schema: "s3verbin://"
+ $.entries[17].schema: "s3ver://"
- $.entries[17].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
+ $.entries[17].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[18].contentVersion: "e24e946eb73c45120942d89c2de73814cc1a2e99"
+ $.entries[18].contentVersion: "2bc9034be7302a71d8eb0ee4309188a1c7534a99"
- $.entries[18].downloadStrategy: "preferPackaged"
+ $.entries[18].downloadStrategy: "preferRemote"
- $.entries[18].enableChecksum: false
+ $.entries[18].enableChecksum: true
- $.entries[18].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_Ice_Nine_Kills.T_UI_CollectionBanner_Ice_Nine_Kills"
+ $.entries[18].packagedPath: ""
- $.entries[18].schema: "s3verbin://"
+ $.entries[18].schema: "s3ver://"
- $.entries[18].uri: "images/T_UI_CollectionBanner_Ice_Nine_Kills.png"
+ $.entries[18].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[19].contentVersion: "db5309baacf020722b4fb45023708df4d48fc820"
+ $.entries[19].contentVersion: "6906a8dc3327bc3dccaab96311adec8bc16eadf4"
- $.entries[19].downloadStrategy: "preferPackaged"
+ $.entries[19].downloadStrategy: "preferRemote"
- $.entries[19].enableChecksum: false
+ $.entries[19].enableChecksum: true
- $.entries[19].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Ice_Nine_Kills.T_UI_SpecialPack_Ice_Nine_Kills"
+ $.entries[19].packagedPath: ""
- $.entries[19].schema: "s3verbin://"
+ $.entries[19].schema: "s3ver://"
- $.entries[19].uri: "images/T_UI_SpecialPack_Ice_Nine_Kills.png"
+ $.entries[19].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[20].contentVersion: "47c2ee482573517676b096d0f2c295d2e7751af7"
+ $.entries[20].contentVersion: "c710af6ea9bb8cb30b3487d9ef9f67e06d7ae543"
- $.entries[20].downloadStrategy: "preferPackaged"
+ $.entries[20].downloadStrategy: "preferRemote"
… 885 more change(s) — see the commit diff for everything
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
- $.disabledItems.GranmasCookbook
- $.disabledItems.ThePiedPiper
```

### [`narrativeCollections.json`](narrativeCollections.json)

[Full line-by-line diff](diffs/narrativeCollections.json.diff)

```diff
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_01].interaction[0].isClientOnly: false
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_02].interaction[0].isClientOnly: true
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_03].interaction[0].isClientOnly: true
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_04].interaction[0].isClientOnly: false
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_05].interaction[0].isClientOnly: true
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_06].interaction[0].isClientOnly: true
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_07].interaction[0].isClientOnly: true
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCharacterRecommendations[id=Featured_Characters_Sushi]
- $.featuredCharacterRecommendations[id=Featured_Characters].activeTo: "2026-06-25T15:00:00Z"
+ $.featuredCharacterRecommendations[id=Featured_Characters].activeTo: "2033-09-04T00:00:00Z"
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=KS_Torso025_01]
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=GS_Torso036_01]
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=KS_Torso021_05].weight: 13
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=KS_Torso021_05].weight: 15
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=GS_Torso028_05].weight: 12
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=GS_Torso028_05].weight: 14
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S49_Torso008_02].weight: 11
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S49_Torso008_02].weight: 13
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S25_Torso022_05].weight: 10
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S25_Torso022_05].weight: 12
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=MT_Torso028_04].weight: 9
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=MT_Torso028_04].weight: 11
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=DF_Torso030_04].weight: 8
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=DF_Torso030_04].weight: 10
```

