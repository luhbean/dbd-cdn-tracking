# live · 9.1.2_2699698live

| | |
|---|---|
| Build date | 2025-08-22 12:33 UTC |
| CDN version | `9.1.2_2699698live-1755865985` |
| Key | `9.1.2_live` |
| Compared with | [9.1.2_2688807live](../9.1.2_2688807live/CHANGES.md) (2025-08-20 20:43 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 198 unchanged

## Modified files

### [`archiveQuests/Tome18.json`](archiveQuests/Tome18.json)

[Full line-by-line diff](diffs/archiveQuests/Tome18.json.diff)

```diff
- $.Tome18.level[2].nodes.node_T18_L3_03.clientInfoId: "ExtendItemChargesWithStreetwiseAsS05InTrial"
+ $.Tome18.level[2].nodes.node_T18_L3_03.clientInfoId: "FallInChaseWithBalancedLandingInTrial"
- $.Tome18.level[2].nodes.node_T18_L3_03.objectives.ExtendItemChargesWithPerkAsCharacterInTrial
+ $.Tome18.level[2].nodes.node_T18_L3_03.objectives.FallInChaseWithPerkInTrial
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=BE_W023].defaultCost[1]
+ $[id=GK_Body022].defaultCost[1]
+ $[id=GK_Head022].defaultCost[1]
+ $[id=GK_W017].defaultCost[1]
+ $[id=GK_W022].defaultCost[1]
+ $[id=GS_Head033].defaultCost[1]
+ $[id=GS_Legs033].defaultCost[1]
+ $[id=GS_Torso018_01].defaultCost[1]
+ $[id=GS_Torso033].defaultCost[1]
- $[id=HK_W023].purchasable: false
+ $[id=HK_W023].purchasable: true
+ $[id=HS_Head025].defaultCost[1]
+ $[id=HS_Legs025].defaultCost[1]
+ $[id=HS_Torso025].defaultCost[1]
- $[id=K21_W019].purchasable: false
+ $[id=K21_W019].purchasable: true
+ $[id=K23_Body023].defaultCost[1]
+ $[id=K23_Head023].defaultCost[1]
+ $[id=K23_Weapon023].defaultCost[1]
- $[id=K26_W016].purchasable: false
+ $[id=K26_W016].purchasable: true
+ $[id=K28_W012].defaultCost[1]
+ $[id=K30_Body011].defaultCost[1]
+ $[id=K30_Head011].defaultCost[1]
+ $[id=K30_W011].defaultCost[1]
- $[id=K30_W015].purchasable: false
+ $[id=K30_W015].purchasable: true
+ $[id=K31_W011].defaultCost[1]
- $[id=K32_W011].purchasable: false
+ $[id=K32_W011].purchasable: true
- $[id=K35_W009].purchasable: false
+ $[id=K35_W009].purchasable: true
+ $[id=KK_W030].defaultCost[1]
+ $[id=MK_Body017].defaultCost[1]
+ $[id=MK_Mask017].defaultCost[1]
+ $[id=MK_W017].defaultCost[1]
+ $[id=MT_Head027].defaultCost[1]
+ $[id=MT_Legs027].defaultCost[1]
+ $[id=MT_Torso027].defaultCost[1]
- $[id=MT_Torso031].purchasable: false
+ $[id=MT_Torso031].purchasable: true
+ $[id=NK_Torso019_01].defaultCost[1]
+ $[id=S24_Torso007_01].defaultCost[1]
+ $[id=S28_Head028].defaultCost[1]
+ $[id=S28_Legs028].defaultCost[1]
+ $[id=S28_Torso008_02].defaultCost[1]
+ $[id=S28_Torso028].defaultCost[1]
- $[id=S29_Torso019].purchasable: false
+ $[id=S29_Torso019].purchasable: true
+ $[id=S31_Torso008_01].defaultCost[1]
+ $[id=S34_Head019].defaultCost[1]
+ $[id=S34_Legs019].defaultCost[1]
+ $[id=S34_Torso008_01].defaultCost[1]
+ $[id=S34_Torso019].defaultCost[1]
- $[id=S35_Torso018].purchasable: false
+ $[id=S35_Torso018].purchasable: true
- $[id=S36_Torso019].purchasable: false
+ $[id=S36_Torso019].purchasable: true
- $[id=S37_Torso017].purchasable: false
+ $[id=S37_Torso017].purchasable: true
+ $[id=S41_Head011].defaultCost[1]
+ $[id=S41_Head012].defaultCost[1]
+ $[id=S41_Legs011].defaultCost[1]
+ $[id=S41_Legs012].defaultCost[1]
+ $[id=S41_Torso011].defaultCost[1]
+ $[id=S41_Torso012].defaultCost[1]
+ $[id=SwedenSurvivor_Torso010_01].defaultCost[1]
+ $[id=TW_W018].defaultCost[1]
+ $[id=UK_W014].defaultCost[1]
+ $[id=US_Head025].defaultCost[1]
+ $[id=US_Legs025].defaultCost[1]
+ $[id=US_Torso025].defaultCost[1]
+ $[id=WI_W013].defaultCost[1]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[8].contentVersion: "2c00d3f083473cfa7fe3c0f3561b16ebde1e90df"
+ $.entries[8].contentVersion: "738e67dfbe1709f4c4a562700eb5f6f2351e3128"
- $.entries[46].contentVersion: "409aade466f06736fed55402dfb5d0305687c6b6"
+ $.entries[46].contentVersion: "60e740ccb511cad18bae91fbe0ca3f66f8990dec"
- $.entries[170].contentVersion: "af7716366da0dde861a4566362a487c44de06646"
+ $.entries[170].contentVersion: "8172eeed2826d3d05c7beb42a42bce1903cae663"
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
- $.disabledItems.S48P02
```

## Could not download

- `images/T_UI_CollectionBanner_PartyHard.png (HTTP 404)`
- `images/T_UI_SpecialPack_ModernBaroque.png (HTTP 404)`
- `images/T_UI_SpecialPack_PartyHard.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_GenQuest1.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_chest.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_cosmetic.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_generator.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_gift.png (HTTP 404)`

