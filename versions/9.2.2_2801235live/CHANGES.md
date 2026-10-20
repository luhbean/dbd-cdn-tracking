# live · 9.2.2_2801235live

| | |
|---|---|
| Build date | 2025-10-14 14:23 UTC |
| CDN version | `9.2.2_2801235live-1760451830` |
| Key | `9.2.2_live` |
| Compared with | [9.2.2_2799571live](../9.2.2_2799571live/CHANGES.md) (2025-10-10 18:36 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 206 unchanged

## Modified files

### [`archiveQuests/Tome07.json`](archiveQuests/Tome07.json)

[Full line-by-line diff](diffs/archiveQuests/Tome07.json.diff)

```diff
- $.Tome07.level[3].nodes.node_T7L4_Glyph01.objectives.BlueGlyphEscape.specialBehaviours[id=RedGlyph]
+ $.Tome07.level[3].nodes.node_T7L4_Glyph01.objectives.BlueGlyphEscape.specialBehaviours[id=BlueGlyph]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_251014]
+ $[id=Recurring_Charm_Bundle_251014]
+ $[id=Recurring_Dev_Bundle_251014]
+ $[id=Recurring_Killer_Bundle_251014]
+ $[id=Recurring_Survivor_Bundle_251014]
+ $[id=Recurring_Survivor_Bundle_2_251014]
- $[id=DK_Head019].metaData.availablePeriods
- $[id=DK_Head019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=DK_Head019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=DK_Head019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=DK_Legs019].metaData.availablePeriods
- $[id=DK_Legs019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=DK_Legs019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=DK_Legs019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=DK_Torso019].metaData.availablePeriods
- $[id=DK_Torso019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=DK_Torso019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=DK_Torso019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=GS_Head033].metaData.availablePeriods
- $[id=GS_Head033].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=GS_Head033].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=GS_Head033].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=GS_Legs033].metaData.availablePeriods
- $[id=GS_Legs033].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=GS_Legs033].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=GS_Legs033].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=GS_Torso033].metaData.availablePeriods
- $[id=GS_Torso033].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=GS_Torso033].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=GS_Torso033].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=HS_Head025].metaData.availablePeriods
- $[id=HS_Head025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=HS_Head025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=HS_Head025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=HS_Legs025].metaData.availablePeriods
- $[id=HS_Legs025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=HS_Legs025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=HS_Legs025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=HS_Torso025].metaData.availablePeriods
- $[id=HS_Torso025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=HS_Torso025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=HS_Torso025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=MK_Body017].metaData.availablePeriods
- $[id=MK_Body017].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=MK_Body017].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=MK_Body017].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=MK_Mask017].metaData.availablePeriods
- $[id=MK_Mask017].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=MK_Mask017].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=MK_Mask017].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=MK_W017].metaData.availablePeriods
- $[id=MK_W017].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=MK_W017].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=MK_W017].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S25_Head019].metaData.availablePeriods
- $[id=S25_Head019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S25_Head019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S25_Head019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S25_Legs019].metaData.availablePeriods
- $[id=S25_Legs019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S25_Legs019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S25_Legs019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S25_Torso019].metaData.availablePeriods
- $[id=S25_Torso019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S25_Torso019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S25_Torso019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S31_Head013].metaData.availablePeriods
- $[id=S31_Head013].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S31_Head013].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S31_Head013].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S31_Legs013].metaData.availablePeriods
- $[id=S31_Legs013].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S31_Legs013].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S31_Legs013].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S31_Torso013].metaData.availablePeriods
- $[id=S31_Torso013].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S31_Torso013].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S31_Torso013].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=US_Head025].metaData.availablePeriods
- $[id=US_Head025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=US_Head025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=US_Head025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=US_Legs025].metaData.availablePeriods
- $[id=US_Legs025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=US_Legs025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=US_Legs025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=US_Torso025].metaData.availablePeriods
- $[id=US_Torso025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=US_Torso025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=US_Torso025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=DK_outfit_019].metaData.availablePeriods
- $[id=DK_outfit_019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=DK_outfit_019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=DK_outfit_019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=GS_outfit_033].metaData.availablePeriods
- $[id=GS_outfit_033].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=GS_outfit_033].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=GS_outfit_033].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=HS_outfit_025].metaData.availablePeriods
- $[id=HS_outfit_025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=HS_outfit_025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=HS_outfit_025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=MK_outfit_017].metaData.availablePeriods
- $[id=MK_outfit_017].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=MK_outfit_017].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=MK_outfit_017].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S25_outfit_019].metaData.availablePeriods
- $[id=S25_outfit_019].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S25_outfit_019].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S25_outfit_019].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=S31_outfit_013].metaData.availablePeriods
- $[id=S31_outfit_013].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=S31_outfit_013].metaData.releaseDate: "2023-10-18T18:00:00"
+ $[id=S31_outfit_013].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=US_outfit_025].metaData.availablePeriods
- $[id=US_outfit_025].metaData.limitedTimeEndDate: "2024-11-07T16:00:00"
- $[id=US_outfit_025].metaData.releaseDate: "2024-10-17T15:00:00"
+ $[id=US_outfit_025].metaData.releaseDate: "2025-10-14T15:00:00"
- $[id=Bone_Shirt_Bundle].metaData.sortOrder: 401
+ $[id=Bone_Shirt_Bundle].metaData.sortOrder: 1050
- $[id=Candy_Weapon_Bundle].metaData.sortOrder: 401
+ $[id=Candy_Weapon_Bundle].metaData.sortOrder: 1050
- $[id=Halloween_2024_Bundle].metaData.sortOrder: 401
+ $[id=Halloween_2024_Bundle].metaData.sortOrder: 1100
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[34].items[]: "K31_W011"
+ $.collections[34].items[]: "S35_outfit_024"
+ $.collections[34].items[]: "S36_outfit_024"
- $.collections[34].updatedDate: "2025-10-06T13:45:35.486Z"
+ $.collections[34].updatedDate: "2025-10-14T13:51:02.002Z"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[6].contentVersion: "f636d1350bd6d9488e860ea108cd22a5fc34d077"
+ $.entries[6].contentVersion: "c83d04a2647a3fbfd63962568375c46f1bd37acf"
- $.entries[33].contentVersion: "5c47faa387f1708077ebbcbededeafbd9d8b4325"
+ $.entries[33].contentVersion: "6d3d7fed991b72f2e109a1ded4cfbf2f311f5473"
- $.entries[82].contentVersion: "1dda1fca14689b3a0fa01981df0bfe92fe0b1b46"
+ $.entries[82].contentVersion: "d04686c06093703d92991e61fd847b079b9b1d7c"
- $.entries[177].contentVersion: "7f23713489e69be0903df4473a7bd17c2090c3b0"
+ $.entries[177].contentVersion: "fb56e299859fcb2a814caf016e6e029c6da2a120"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Maple_W5]
+ $.featuredCustomizationRecommendations[id=MapleW5]
+ $.specialsRecommendations[id=HalloweenSale]
```

