# live · 9.3.2_2958598live

| | |
|---|---|
| Build date | 2025-12-09 22:00 UTC |
| CDN version | `9.3.2_2958598live-1765317619` |
| Key | `9.3.2_live` |
| Compared with | [9.3.2_2954546live](../9.3.2_2954546live/CHANGES.md) (2025-12-09 16:00 UTC) |

## Summary

**0** added · **13** modified · **0** removed · 192 unchanged

## Modified files

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "Schließe {0} „Silent Hill“-Quest(s) ab."
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "Completa {0} misión/misiones de Silent Hill"
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "Completa {0} misión/misiones de Silent Hill."
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "Completa {0} missione/i di Silent Hill"
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "사일런트 힐 퀘스트 {0}개 완료하기"
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "Ukończ tyle zadań Silent Hill: {0}"
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "Cumpra {0} missão(ões) de Silent Hill"
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "Завершите задания «Сайлент Хилла»: {0}"
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "พิชิตเควสต์ไซเลนต์ฮิล {0} เควสต์"
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "{0} Silent Hill görevi tamamla"
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[511].text: "Complete {0} Silent Hill quest(s)"
+ $.locText[511].text: "完成{0}個《沉默之丘》任務"
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[6].LinkedEventId: "MapShowcase_Omelet_01"
- $.schedule[6].Description: "MapShowcase Map List"
+ $.schedule[6].Description: "Killswitch"
- $.schedule[6].GameModes[]: "MapShowcase"
+ $.schedule[6].GameModes[]: "Online"
+ $.schedule[6].GameModes[]: "KillYourFriends"
+ $.schedule[6].GameModes[]: "SecretBotMatch"
+ $.schedule[6].GameModes[]: "TutorialBotMatch"
+ $.schedule[6].GameModes[]: "ChocolateBox"
+ $.schedule[6].GameModes[]: "SeasonalEvent"
+ $.schedule[6].GameModes[]: "SeasonalEvent_FuelGenerator"
- $.schedule[6].MapsWeight.Kny_Cottage: "1300"
+ $.schedule[6].MapsWeight.Qtm_Level_02: "0"
- $.schedule[7]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[175].contentVersion: "e8f196db6154bab2faf17c24303ad14b01f6bd94"
+ $.entries[175].contentVersion: "5d398b08fba83a4acb7f0af846bd9de64f682c72"
- $.entries[195].contentVersion: "efc218eba82f00d4b65cac9d9196332cd25bc273"
+ $.entries[195].contentVersion: "b54a9dbc4b736585af8fd4b2e977ee0d64c7bf61"
- $.entries[196].contentVersion: "3aa9777e2a964e8e840b0640f942254be042e091"
+ $.entries[196].contentVersion: "ee67c1f21d5290cf2cdfa8bbf5b4a81a1fa637bb"
- $.entries[197].contentVersion: "92c67533ffc5223c2805c3d8d3394c7dc13f4b92"
+ $.entries[197].contentVersion: "ddad96036cec4239f897d930c08b4e8aad1ba068"
- $.entries[199].contentVersion: "0d9173c7db93d73e9c829d02985fbf147ef1f508"
+ $.entries[199].contentVersion: "2079a270480a129d281385a1c42547528069dc3c"
- $.entries[201].contentVersion: "b20adc8498bb18f418afa26b4ed673e785a84b00"
+ $.entries[201].contentVersion: "0c98f5781f2266eaf0071958effae69e4942e1a3"
- $.entries[202].contentVersion: "e11b1ce5d8215be1005346b1eb5d9c6dcbd5cb1c"
+ $.entries[202].contentVersion: "990198a91681e56fb35fe951c152cb858154c06f"
- $.entries[203].contentVersion: "a6fff2fc178d4180b6767d7daf2a1f282b81b8b3"
+ $.entries[203].contentVersion: "5eb33653d6e0150e7e7c877f2178535b413d5aee"
- $.entries[204].contentVersion: "19294f936af715f6803ce5d2f9aeb8b2090d3d89"
+ $.entries[204].contentVersion: "a11e0214562d4a29d45c8f8eb53b8b1c5dbd72cc"
- $.entries[205].contentVersion: "91298cf5fec9ae1a4f157a5fd02e6cd08822aa63"
+ $.entries[205].contentVersion: "29b2e0a03925367a96e5370b699e9471efa3f0b6"
- $.entries[206].contentVersion: "2d462dab42c4ee48cbeb2ff904889788833f1053"
+ $.entries[206].contentVersion: "c7c666191541d455f7b78ec8bbf6a1504d7238eb"
- $.entries[208].contentVersion: "a3a50f54e58157c58963e9f58a5171e8ccfd2616"
+ $.entries[208].contentVersion: "f01714f92f59855239261ddc218dd9445cd49e52"
```

## Could not download

- `images/T_UI_CollectionBanner_HolidayHorror_GhostFace.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TorturedSouls.png (HTTP 404)`
- `images/T_UI_SpecialPack_HolidayHorror_GhostFace.png (HTTP 404)`
- `images/T_UI_SpecialPack_TorturedSouls.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_GenQuest1.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_cosmetic.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_gift.png (HTTP 404)`

