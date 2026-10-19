# live · 9.0.1_2520463live

| | |
|---|---|
| Build date | 2025-06-26 14:08 UTC |
| CDN version | `9.0.1_2520463live-1750946911` |
| Key | `9.0.1_live` |
| Compared with | [9.0.1_2518194live](../9.0.1_2518194live/CHANGES.md) (2025-06-25 15:02 UTC) |

## Summary

**0** added · **6** modified · **0** removed · 196 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=TM_Killer_Mask_Bundle].metaData.sortOrder: 0
+ $[id=TM_Killer_Mask_Bundle].metaData.sortOrder: 1400
- $[id=TM_Survivor_Mask_Bundle].metaData.sortOrder: 0
+ $[id=TM_Survivor_Mask_Bundle].metaData.sortOrder: 1400
- $[id=TwistedMasqueradeBundle].metaData.sortOrder: 0
+ $[id=TwistedMasqueradeBundle].metaData.sortOrder: 1500
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[16].text: "Kill {0} Survivor(s)"
+ $.locText[16].text: "Sacrifice or kill {0} Survivor(s)"
- $.locText[120].text: "Kill {0} Survivor(s) with your hands"
+ $.locText[120].text: "Kill {0} Survivor(s)"
- $.locText[150].text: "Once downed, you can kill the last Survivor in a trial without hooking them."
+ $.locText[150].text: "The more Survivors you sacrifice or kill, the more The Entity rewards you."
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[19].text: "@#CHALENGE_EarnBloodpoints_DESC"
+ $.locText[19].text: "De nombreuses actions vous donnent des points de sang en récompense, comme coopérer avec d'autres survivants et utiliser vos pouvoirs de tueur."
- $.locText[87].text: "@#CHALLENGE_VaultInChase_DESC"
+ $.locText[87].text: "Sauter par-dessus les palettes et les fenêtres peut vous aider à prolonger les poursuites, puisque les tueurs sont généralement ralentis par ces obstacles."
- $.locText[138].text: "@#CHALLENGE_GrabSurvivor_DESC"
+ $.locText[138].text: "Vous pouvez saisir un survivant en train d'interagir avec un générateur ou un totem, ou qui est en train de sauter."
- $.locText[148].text: "@#CHALLENGE_BeChased_DESC"
+ $.locText[148].text: "Faites durer les poursuites le plus possible. Les autres survivants auront plus de temps pour réparer les générateurs."
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[8].text: "发起{0}次普通攻击"
+ $.locText[8].text: "普通攻击命中{0}名逃生者。"
- $.locText[13].text: "完成{0}次发电机检定成功"
+ $.locText[13].text: "完成{0}次修理检定成功"
- $.locText[120].text: "亲手击杀{0}名逃生者"
+ $.locText[120].text: "击杀{0}名逃生者"
- $.locText[150].text: "最后一名逃生者被击倒后，你无需将其挂上钩子就可以击杀该名逃生者。"
+ $.locText[150].text: "你献祭或击杀越多的逃生者，恶灵给你的奖励就越多。"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[4].contentVersion: "3055a66fd38a55073e25f0fe4bd62b101a2c5d03"
+ $.entries[4].contentVersion: "0ae191bf37ea7fa5aaa604ae16fae2e9bad9ccdf"
- $.entries[79].contentVersion: "5379a06bbc2523a21cc367ebb950e1e054761f52"
+ $.entries[79].contentVersion: "4f32c587ddc3491b4ffc04321b0eab319c055cd2"
- $.entries[188].contentVersion: "90d3cc547b62e845a79927b896aa6e66a29ee3e0"
+ $.entries[188].contentVersion: "7d04bc2940ee54ed1fcf362d861b285dcefff9b0"
- $.entries[192].contentVersion: "d2087499d596ce23132fbd7e0801b9f66eb29c95"
+ $.entries[192].contentVersion: "37f2220086a7a3dcd41dfae9632e04265c2d2033"
- $.entries[201].contentVersion: "1c13b3eb889aeb3f1bb354f9324c36ae28632c89"
+ $.entries[201].contentVersion: "3532151674b5343991c22506d93146b04aed23a5"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=KetchupW2].entries[1].entryId: "TM_Survivor_Mask_Bundle"
+ $.featuredCard[id=KetchupW2].entries[1].entryId: "TwistedMasqueradeBundle"
- $.featuredCard[id=KetchupW2].entries[2].entryId: "TM_Killer_Mask_Bundle"
+ $.featuredCard[id=KetchupW2].entries[2].entryId: "FNAF"
- $.featuredCard[id=KetchupW2].entries[2].type: "SpecialPack"
+ $.featuredCard[id=KetchupW2].entries[2].type: "Collection"
- $.featuredCard[id=KetchupW2].entries[3].entryId: "FNAF"
+ $.featuredCard[id=KetchupW2].entries[3].entryId: "Rift_1_Bundle"
- $.featuredCard[id=KetchupW2].entries[3].type: "Collection"
+ $.featuredCard[id=KetchupW2].entries[3].type: "SpecialPack"
- $.featuredCard[id=KetchupW2].entries[4]
```

## Could not download

- `images/T_UI_CollectionBanner_Casual.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TwistedMasquerade.png (HTTP 404)`
- `images/T_UI_SpecialPack_Casual.png (HTTP 404)`
- `images/T_UI_SpecialPack_TwistedMasquerade.png (HTTP 404)`
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

