# live · 9.0.1_2530010live

| | |
|---|---|
| Build date | 2025-07-01 14:34 UTC |
| CDN version | `9.0.1_2530010live-1751380490` |
| Key | `9.0.1_live` |
| Compared with | [9.0.1_2528542live](../9.0.1_2528542live/CHANGES.md) (2025-06-27 17:15 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 197 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_250701]
+ $[id=Recurring_Charm_Bundle_250701]
+ $[id=Recurring_Dev_Bundle_250701]
+ $[id=Recurring_Killer_Bundle_250701]
+ $[id=Recurring_Survivor_Bundle_250701]
+ $[id=Recurring_Survivor_Bundle_2_250701]
- $[id=From_The_Rift_Bundle_250624].consumptionReward[id=NK_Head013_01].gameSpecificData.hasPriorityForPackImageComposition: true
+ $[id=From_The_Rift_Bundle_250624].consumptionReward[id=NK_Head013_01].gameSpecificData.hasPriorityForPackImageComposition: false
- $[id=From_The_Rift_Bundle_250624].consumptionReward[id=NK_Torso013_01].gameSpecificData.hasPriorityForPackImageComposition: true
+ $[id=From_The_Rift_Bundle_250624].consumptionReward[id=NK_Torso013_01].gameSpecificData.hasPriorityForPackImageComposition: false
- $[id=From_The_Rift_Bundle_250624].consumptionReward[id=NK_Legs013_01].gameSpecificData.hasPriorityForPackImageComposition: true
+ $[id=From_The_Rift_Bundle_250624].consumptionReward[id=NK_Legs013_01].gameSpecificData.hasPriorityForPackImageComposition: false
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[8].text: "Hit {0} Survivors with a basic attack."
+ $.locText[8].text: "Hit {0} Survivors with a basic attack"
- $.locText[27].text: "Be Chased for {0} seconds"
+ $.locText[27].text: "Be chased for {0} seconds"
- $.locText[33].text: "Complete {0} 2v8 Quest(s)"
+ $.locText[33].text: "Complete {0} 2v8 quest(s)"
- $.locText[36].text: "Complete {0} 2v8 Quest(s)"
+ $.locText[36].text: "Complete {0} 2v8 quest(s)"
- $.locText[39].text: "Complete {0} 2v8 Quest(s)"
+ $.locText[39].text: "Complete {0} 2v8 quest(s)"
- $.locText[65].text: "Complete {0} Chaos Shuffle Quest(s)"
+ $.locText[65].text: "Complete {0} Chaos Shuffle quest(s)"
- $.locText[68].text: "Complete {0} Chaos Shuffle Quest(s)"
+ $.locText[68].text: "Complete {0} Chaos Shuffle quest(s)"
- $.locText[71].text: "Complete {0} Chaos Shuffle Quest(s)"
+ $.locText[71].text: "Complete {0} Chaos Shuffle quest(s)"
- $.locText[97].text: "Complete {0} Quest(s) This Week"
+ $.locText[97].text: "Complete {0} quest(s) this week"
- $.locText[181].text: "Complete {0} Rift Pass Quest(s)"
+ $.locText[181].text: "Complete {0} Rift Pass quest(s)"
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[8].text: "通常攻撃を{0}回命中させる"
+ $.locText[8].text: "生存者に通常攻撃を{0}回命中させる"
- $.locText[13].text: "発電機のスキルチェックに{0}回成功する"
+ $.locText[13].text: "修理のスキルチェックに{0}回成功する"
- $.locText[16].text: "生存者{0}人を殺害する"
+ $.locText[16].text: "生存者{0}人を処刑するか殺害する"
- $.locText[19].text: "@#CHALENGE_EarnBloodpoints_DESC"
+ $.locText[19].text: "他の生存者と協力したり殺人鬼の特殊能力を使うことなど、様々なアクションを行うことでブラッドポイントを獲得できます。"
- $.locText[120].text: "自らの手で生存者{0}人を殺害する"
+ $.locText[120].text: "生存者{0}人を殺害する"
- $.locText[148].text: "@#CHALLENGE_BeChased_DESC"
+ $.locText[148].text: "追跡をできる限り長引かせましょう。そうすることで、他の生存者が発電機の修理に専念できます。"
- $.locText[150].text: "最後の生存者は、ダウンさせるとフックに吊るさず直接殺害できます。"
+ $.locText[150].text: "生存者を処刑したり殺害したりするほど、エンティティからより多くの報酬が得られます。"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[4].contentVersion: "41d35e19773330dc674f63b566bbcdb6227033d6"
+ $.entries[4].contentVersion: "af59308ea7c91f012550455df52ca0e75c1237ed"
- $.entries[79].contentVersion: "4f32c587ddc3491b4ffc04321b0eab319c055cd2"
+ $.entries[79].contentVersion: "16adf5fc00350ee21b308f03ddc8fb47bba67a89"
- $.entries[188].contentVersion: "7d04bc2940ee54ed1fcf362d861b285dcefff9b0"
+ $.entries[188].contentVersion: "120badc43405526cdc16290ac04c509228af633b"
- $.entries[194].contentVersion: "1578b65a85b2e7620909abcff104b1a3f0a2884f"
+ $.entries[194].contentVersion: "49058e2b4886b564dfcb020e98946da2a20e3a29"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=KetchupW3]
+ $.featuredCard[id=KetchupW4]
+ $.featuredCustomizationRecommendations[id=Ketchup_W3]
+ $.featuredCustomizationRecommendations[id=Ketchup_W4]
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

