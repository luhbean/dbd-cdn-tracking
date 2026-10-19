# live · 8.7.2_2495438live

| | |
|---|---|
| Build date | 2025-06-06 20:23 UTC |
| CDN version | `8.7.2_2495438live-1749241413` |
| Key | `8.7.2_live` |
| Compared with | [8.7.2_2489515live](../8.7.2_2489515live/CHANGES.md) (2025-06-04 13:53 UTC) |

## Summary

**0** added · **7** modified · **0** removed · 195 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.analyticsRules.BL[]: "CustomerSupportClientLoginAnalytics"
+ $.analyticsRules.BL[]: "InboxLoadedAnalytics"
+ $.analyticsRules.BL[]: "MatchmakingJoinCompleteAnalytics"
- $.analyticsRules.KL[]: "CustomerSupportClientLoginAnalytics"
- $.analyticsRules.KL[]: "InboxLoadedAnalytics"
- $.analyticsRules.KL[]: "MatchmakingJoinCompleteAnalytics"
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
+ $.analyticsRulesDedicatedServer.KA[]: "MatchIncentivesGrantedAnalytics"
- $.analyticsRulesDedicatedServer.KAL[]: "MatchIncentivesGrantedAnalytics"
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[89].text: "Twisted Masquerade Completion Quests"
+ $.locText[89].text: "Chaos Shuffle Completion Quests"
- $.locText[150].text: "@#CHALLENGE_Kill_DESC"
+ $.locText[150].text: "Once downed, you can Kill the last Survivor in a trial without hooking them."
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[150].text: "@#CHALLENGE_Kill_DESC"
+ $.locText[150].text: "Une fois qu'il est à terre, vous pouvez tuer le dernier survivant dans une épreuve sans l'accrocher."
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[150].text: "@#CHALLENGE_Kill_DESC"
+ $.locText[150].text: "最後の生存者は、ダウンさせるとフックに吊るさず直接殺害できます。"
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[89].text: "随技应变已完成任务"
+ $.locText[89].text: "扭曲假面舞会完成任务"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[191].contentVersion: "7e7d1bc38c5cb6ec5064681f7ad6d8e0575757f6"
+ $.entries[191].contentVersion: "f92e95db69f5c292142d9cf97808f8ecd9e9e7df"
- $.entries[195].contentVersion: "f27c92332cad3d4ace75431e13cd87dbff0edd71"
+ $.entries[195].contentVersion: "1efb3d9a96baa0438be7e43f4ab6be4b668b2ec4"
- $.entries[197].contentVersion: "76e3af6ea9b58164f908792ec081c0ae93b304b2"
+ $.entries[197].contentVersion: "a92d029af40548d8f90bc18e8f73df874d19759a"
- $.entries[204].contentVersion: "7baac58effd2d75f2ac2f9d9c143885b99e8b0d6"
+ $.entries[204].contentVersion: "57cc0f271877f886548086e0bd8144bad1e70af1"
```

## Could not download

- `images/T_UI_CollectionBanner_CatsAndDogs_2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_Chrysalis_2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TheWitcher.png (HTTP 404)`
- `images/T_UI_SpecialPack_CatsAndDogs.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcher.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherCharacters.png (HTTP 404)`
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

