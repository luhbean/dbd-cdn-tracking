# live · 9.3.0_2954260live

| | |
|---|---|
| Build date | 2025-12-09 14:08 UTC |
| CDN version | `9.3.0_2954260live-1765289333` |
| Key | `9.3.0_live` |
| Compared with | [9.3.2_2954235live](../9.3.2_2954235live/CHANGES.md) (2025-12-09 13:59 UTC) |

## Summary

**0** added · **21** modified · **0** removed · 184 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.dynamicContent.DynamicContentKillswitchPlatforms[]: "switch"
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=K38_Body009]
- $[id=K38_Head009]
- $[id=K38_W009]
- $[id=OM_BDG_09]
- $[id=OM_BNR_08]
- $[id=OML_004]
- $[id=OML_005]
- $[id=S25_Head032]
- $[id=S25_Legs032]
- $[id=S25_Torso032]
- $[id=S46_Head014]
- $[id=S46_Legs014]
- $[id=S46_Torso014]
- $[id=K38_outfit_009]
- $[id=S25_outfit_032]
- $[id=S46_outfit_014]
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Hake Überlebende fest."
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Rette Überlebende sicher vom Haken."
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Hook Survivor(s)"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Safely unhook Survivor(s)"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Cuelga sobreviviente(s)"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Descuelga de forma segura a sobreviviente(s)"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Cuelga a superviviente(s)."
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Desengancha a superviviente(s) de forma segura."
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Accrocher des survivants"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Décrocher des survivants de manière sécuritaire"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Appendi sopravvissuto/i al gancio"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Libera sopravvissuto/i dal gancio"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "生存者をフックに吊るす"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "生存者を安全にフックから救出する"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "갈고리에 생존자 걸기"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "생존자를 안전하게 갈고리에서 구출하기"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Powieś na haku ocalałych"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Bezpiecznie zdejmij z haka ocalałych"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Enganche Sobrevivente(s)"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Desenganche Sobrevivente(s) com segurança"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Подвесьте выживших на крюк"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Снимите выживших с крюка"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "จับผู้รอดชีวิตแขวนตะขอ"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "ปลดผู้รอดชีวิตลงจากตะขออย่างปลอดภัย"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "Kurban'ı Kancaya As"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "Kurban'ı güvenle kancadan kurtar"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "钩住逃生者"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "安全解救逃生者"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[504].text: "@#CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].text: "@#TEST_CommunityQuests_INFO"
- $.locText[504].textId: "CHALLENGESET_ChocolateBoxOmelet_INFO"
+ $.locText[504].textId: "TEST_CommunityQuests_INFO"
- $.locText[505].text: "@#CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].text: "把倖存者掛上鉤子"
- $.locText[505].textId: "CHALLENGE_EarnBenevolentGold_TITLE"
+ $.locText[505].textId: "CHALLENGE_CommunityHook_INFO"
- $.locText[506].text: "@#CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].text: "將倖存者平安救下鉤子"
- $.locText[506].textId: "CHALLENGE_EarnBenevolentGold_DESC"
+ $.locText[506].textId: "CHALLENGE_CommunityUnhook_INFO"
- $.locText[507]
- $.locText[508]
- $.locText[509]
- $.locText[510]
- $.locText[511]
- $.locText[512]
- $.locText[513]
- $.locText[514]
- $.locText[515]
- $.locText[516]
- $.locText[517]
- $.locText[518]
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.ChocolateBoxOmeletSet
- $.SilentHillMovie_Set
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[43].limitedAvailabilityStartDate: "2026-01-13T16:00:00Z"
- $.collections[43].visibleBeforeStartDate: false
- $.collections[43].additionalImages[0]
- $.collections[43].collectionId: "TorturedSouls"
+ $.collections[43].collectionId: "HookedOnYou"
- $.collections[43].collectionTitle.de: "Tortured Souls"
+ $.collections[43].collectionTitle.de: "Hooked on You"
- $.collections[43].collectionTitle.en: "Tortured Souls"
+ $.collections[43].collectionTitle.en: "Hooked on You"
- $.collections[43].collectionTitle.es: "Almas torturadas"
+ $.collections[43].collectionTitle.es: "Hooked on You"
- $.collections[43].collectionTitle["es-MX"]: "Almas torturadas"
+ $.collections[43].collectionTitle["es-MX"]: "Hooked on You"
- $.collections[43].collectionTitle.fr: "Âmes torturées"
+ $.collections[43].collectionTitle.fr: "Hooked on You"
- $.collections[43].collectionTitle.it: "Anime torturate"
+ $.collections[43].collectionTitle.it: "Hooked on You"
- $.collections[43].collectionTitle.ja: "苦悶する魂"
+ $.collections[43].collectionTitle.ja: "Hooked on You"
- $.collections[43].collectionTitle.ko: "고통 받는 영혼"
+ $.collections[43].collectionTitle.ko: "Hooked on You"
- $.collections[43].collectionTitle.pl: "Umęczone dusze"
+ $.collections[43].collectionTitle.pl: "Hooked On You"
- $.collections[43].collectionTitle["pt-BR"]: "Almas Torturadas"
+ $.collections[43].collectionTitle["pt-BR"]: "Hooked on You"
- $.collections[43].collectionTitle.ru: "Страдающие души"
+ $.collections[43].collectionTitle.ru: "На твоем крючке"
- $.collections[43].collectionTitle.th: "วิญญาณที่ถูกทรมาน"
+ $.collections[43].collectionTitle.th: "Hooked on You"
- $.collections[43].collectionTitle.tr: "Acılı Ruhlar"
+ $.collections[43].collectionTitle.tr: "Sana Tutuldum"
- $.collections[43].collectionTitle["zh-Hans"]: "受难灵魂"
+ $.collections[43].collectionTitle["zh-Hans"]: "心醉魂迷"
- $.collections[43].collectionTitle["zh-Hant"]: "受折磨的靈魂"
+ $.collections[43].collectionTitle["zh-Hant"]: "《鉤魂迷戀》"
- $.collections[43].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_TorturedSouls.T_UI_CollectionBanner_TorturedSouls"
+ $.collections[43].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_HookedOnYou.T_UI_CollectionBanner_HookedOnYou"
- $.collections[43].inclusionVersion: "9.3.2"
+ $.collections[43].inclusionVersion: "7.7.0 PTB"
- $.collections[43].items[]: "DK_outfit_027"
- $.collections[43].items[]: "K21_outfit_021"
- $.collections[43].items[]: "K38_outfit_009"
- $.collections[43].items[]: "MK_outfit_018"
- $.collections[43].items[]: "S25_outfit_032"
- $.collections[43].items[]: "S46_outfit_014"
+ $.collections[43].items[]: "BE_outfit_017"
+ $.collections[43].items[]: "CM_outfit_021"
+ $.collections[43].items[]: "DF_outfit_023"
+ $.collections[43].items[]: "HK_outfit_017"
+ $.collections[43].items[]: "K23_outfit_014"
- $.collections[43].sortOrder: "-187"
+ $.collections[43].sortOrder: "-19"
- $.collections[43].updatedDate: "2025-08-20T15:56:07.341Z"
+ $.collections[43].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[44].collectionId: "HookedOnYou"
+ $.collections[44].collectionId: "GrimMatsuri"
- $.collections[44].collectionTitle.de: "Hooked on You"
+ $.collections[44].collectionTitle.de: "Düsteres Matsuri-Fest"
- $.collections[44].collectionTitle.en: "Hooked on You"
+ $.collections[44].collectionTitle.en: "Grim Matsuri"
- $.collections[44].collectionTitle.es: "Hooked on You"
+ $.collections[44].collectionTitle.es: "Matsuri tenebrosa"
- $.collections[44].collectionTitle["es-MX"]: "Hooked on You"
+ $.collections[44].collectionTitle["es-MX"]: "Matsuri tenebrosa"
- $.collections[44].collectionTitle.fr: "Hooked on You"
+ $.collections[44].collectionTitle.fr: "Matsuri sinistre"
- $.collections[44].collectionTitle.it: "Hooked on You"
+ $.collections[44].collectionTitle.it: "Matsuri funebre"
- $.collections[44].collectionTitle.ja: "Hooked on You"
+ $.collections[44].collectionTitle.ja: "おぞましい祭り"
- $.collections[44].collectionTitle.ko: "Hooked on You"
+ $.collections[44].collectionTitle.ko: "음산한 축제"
- $.collections[44].collectionTitle.pl: "Hooked On You"
+ $.collections[44].collectionTitle.pl: "Ponury Festiwal"
- $.collections[44].collectionTitle["pt-BR"]: "Hooked on You"
+ $.collections[44].collectionTitle["pt-BR"]: "Festival Japonês Sombrio"
- $.collections[44].collectionTitle.ru: "На твоем крючке"
+ $.collections[44].collectionTitle.ru: "Мрачный Мацури"
- $.collections[44].collectionTitle.th: "Hooked on You"
+ $.collections[44].collectionTitle.th: "เทศกาลสยอง"
- $.collections[44].collectionTitle.tr: "Sana Tutuldum"
+ $.collections[44].collectionTitle.tr: "Kasvetli Festival"
- $.collections[44].collectionTitle["zh-Hans"]: "心醉魂迷"
+ $.collections[44].collectionTitle["zh-Hans"]: "冷血祭"
- $.collections[44].collectionTitle["zh-Hant"]: "《鉤魂迷戀》"
+ $.collections[44].collectionTitle["zh-Hant"]: "冷血祭"
- $.collections[44].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_HookedOnYou.T_UI_CollectionBanner_HookedOnYou"
+ $.collections[44].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GrimMatsuri.T_UI_CollectionBanner_GrimMatsuri"
- $.collections[44].items[]: "BE_outfit_017"
- $.collections[44].items[]: "CM_outfit_021"
- $.collections[44].items[]: "DF_outfit_023"
- $.collections[44].items[]: "HK_outfit_017"
- $.collections[44].items[]: "K23_outfit_014"
+ $.collections[44].items[]: "Bear_outfit_003"
+ $.collections[44].items[]: "Claudette_outfit_018"
+ $.collections[44].items[]: "GS_outfit_011"
+ $.collections[44].items[]: "Jake_outfit_017"
+ $.collections[44].items[]: "Meg_outfit_023"
+ $.collections[44].items[]: "Nea_outfit_010"
+ $.collections[44].items[]: "SwedenSurvivor_outfit_009"
+ $.collections[44].items[]: "TN_outfit_010"
- $.collections[44].sortOrder: "-19"
+ $.collections[44].sortOrder: "-2"
- $.collections[44].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[44].updatedDate: "2024-03-06T20:44:22Z"
- $.collections[45].collectionId: "GrimMatsuri"
+ $.collections[45].collectionId: "AliceInWonderland"
- $.collections[45].collectionTitle.de: "Düsteres Matsuri-Fest"
+ $.collections[45].collectionTitle.de: "Alice im Wunderland"
- $.collections[45].collectionTitle.en: "Grim Matsuri"
+ $.collections[45].collectionTitle.en: "Alice in Wonderland"
- $.collections[45].collectionTitle.es: "Matsuri tenebrosa"
+ $.collections[45].collectionTitle.es: "Alicia en el País de las Maravillas"
- $.collections[45].collectionTitle["es-MX"]: "Matsuri tenebrosa"
+ $.collections[45].collectionTitle["es-MX"]: "Alicia en el País de las Maravillas"
- $.collections[45].collectionTitle.fr: "Matsuri sinistre"
+ $.collections[45].collectionTitle.fr: "Alice au pays des merveilles"
- $.collections[45].collectionTitle.it: "Matsuri funebre"
+ $.collections[45].collectionTitle.it: "Alice nel paese delle meraviglie"
- $.collections[45].collectionTitle.ja: "おぞましい祭り"
+ $.collections[45].collectionTitle.ja: "不思議の国のアリス"
- $.collections[45].collectionTitle.ko: "음산한 축제"
+ $.collections[45].collectionTitle.ko: "이상한 나라의 앨리스"
- $.collections[45].collectionTitle.pl: "Ponury Festiwal"
+ $.collections[45].collectionTitle.pl: "Alicja w Krainie Czarów"
- $.collections[45].collectionTitle["pt-BR"]: "Festival Japonês Sombrio"
+ $.collections[45].collectionTitle["pt-BR"]: "Alice no País das Maravilhas"
- $.collections[45].collectionTitle.ru: "Мрачный Мацури"
+ $.collections[45].collectionTitle.ru: "Алиса в Стране чудес"
- $.collections[45].collectionTitle.th: "เทศกาลสยอง"
+ $.collections[45].collectionTitle.th: "อลิซในแดนมหัศจรรย์"
- $.collections[45].collectionTitle.tr: "Kasvetli Festival"
+ $.collections[45].collectionTitle.tr: "Alice Harikalar Diyarında"
- $.collections[45].collectionTitle["zh-Hans"]: "冷血祭"
+ $.collections[45].collectionTitle["zh-Hans"]: "爱丽丝梦游仙境收藏"
- $.collections[45].collectionTitle["zh-Hant"]: "冷血祭"
+ $.collections[45].collectionTitle["zh-Hant"]: "《愛麗絲夢遊仙境》"
- $.collections[45].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GrimMatsuri.T_UI_CollectionBanner_GrimMatsuri"
+ $.collections[45].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AliceInWonderland.T_UI_CollectionBanner_AliceInWonderland"
- $.collections[45].items[]: "Bear_outfit_003"
- $.collections[45].items[]: "Claudette_outfit_018"
- $.collections[45].items[]: "GS_outfit_011"
- $.collections[45].items[]: "Jake_outfit_017"
- $.collections[45].items[]: "Meg_outfit_023"
- $.collections[45].items[]: "Nea_outfit_010"
- $.collections[45].items[]: "SwedenSurvivor_outfit_009"
- $.collections[45].items[]: "TN_outfit_010"
+ $.collections[45].items[]: "AV_outfit_018"
+ $.collections[45].items[]: "BE_outfit_020"
+ $.collections[45].items[]: "GS_outfit_023"
+ $.collections[45].items[]: "K26_outfit_011"
+ $.collections[45].items[]: "NK_outfit_023"
- $.collections[45].sortOrder: "-2"
+ $.collections[45].sortOrder: "-20"
- $.collections[45].updatedDate: "2024-03-06T20:44:22Z"
+ $.collections[45].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[46].collectionId: "AliceInWonderland"
+ $.collections[46].collectionId: "Wasteland"
- $.collections[46].collectionTitle.de: "Alice im Wunderland"
+ $.collections[46].collectionTitle.de: "Ödland"
- $.collections[46].collectionTitle.en: "Alice in Wonderland"
+ $.collections[46].collectionTitle.en: "Wasteland"
- $.collections[46].collectionTitle.es: "Alicia en el País de las Maravillas"
+ $.collections[46].collectionTitle.es: "Páramo"
- $.collections[46].collectionTitle["es-MX"]: "Alicia en el País de las Maravillas"
+ $.collections[46].collectionTitle["es-MX"]: "Páramo"
- $.collections[46].collectionTitle.fr: "Alice au pays des merveilles"
+ $.collections[46].collectionTitle.fr: "Terre dévastée"
- $.collections[46].collectionTitle.it: "Alice nel paese delle meraviglie"
+ $.collections[46].collectionTitle.it: "Landa desolata"
- $.collections[46].collectionTitle.ja: "不思議の国のアリス"
+ $.collections[46].collectionTitle.ja: "荒れ地"
- $.collections[46].collectionTitle.ko: "이상한 나라의 앨리스"
+ $.collections[46].collectionTitle.ko: "황무지"
- $.collections[46].collectionTitle.pl: "Alicja w Krainie Czarów"
+ $.collections[46].collectionTitle.pl: "Pustkowie"
- $.collections[46].collectionTitle["pt-BR"]: "Alice no País das Maravilhas"
+ $.collections[46].collectionTitle["pt-BR"]: "Desolação"
- $.collections[46].collectionTitle.ru: "Алиса в Стране чудес"
+ $.collections[46].collectionTitle.ru: "Пустошь"
- $.collections[46].collectionTitle.th: "อลิซในแดนมหัศจรรย์"
+ $.collections[46].collectionTitle.th: "แดนรกร้าง"
- $.collections[46].collectionTitle.tr: "Alice Harikalar Diyarında"
+ $.collections[46].collectionTitle.tr: "Çorak"
- $.collections[46].collectionTitle["zh-Hans"]: "爱丽丝梦游仙境收藏"
+ $.collections[46].collectionTitle["zh-Hans"]: "荒芜之地"
- $.collections[46].collectionTitle["zh-Hant"]: "《愛麗絲夢遊仙境》"
+ $.collections[46].collectionTitle["zh-Hant"]: "荒地"
- $.collections[46].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AliceInWonderland.T_UI_CollectionBanner_AliceInWonderland"
+ $.collections[46].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Wasteland.T_UI_CollectionBanner_Wasteland"
- $.collections[46].items[]: "AV_outfit_018"
- $.collections[46].items[]: "BE_outfit_020"
- $.collections[46].items[]: "GS_outfit_023"
- $.collections[46].items[]: "K26_outfit_011"
- $.collections[46].items[]: "NK_outfit_023"
+ $.collections[46].items[]: "K30_outfit_008"
+ $.collections[46].items[]: "S23_outfit_021"
+ $.collections[46].items[]: "S31_outfit_009"
- $.collections[46].sortOrder: "-20"
+ $.collections[46].sortOrder: "-21"
… 2463 more change(s) — see the commit diff for everything
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[0].contentVersion: "7ae4f22f2b3292022e85b68983603896896a84b5"
- $.entries[0].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_Specialpack_Bonechill2024.T_UI_Specialpack_Bonechill2024"
- $.entries[0].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[0].uri: "images/T_UI_Specialpack_Bonechill2024.png"
- $.entries[1].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[2].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[3].contentVersion: "2403e6a96d01b6a837a9ca6dbd4fcc72423ae404"
+ $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_SpecialPack_HolidayHorror_GhostFace.T_UI_SpecialPack_HolidayHorror_GhostFace"
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[3].uri: "images/T_UI_SpecialPack_HolidayHorror_GhostFace.png"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[4].contentVersion: "d0bae9dc95e1038bedf96178259a76d2653ed51f"
+ $.entries[4].contentVersion: "2403e6a96d01b6a837a9ca6dbd4fcc72423ae404"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_TorturedSouls.T_UI_CollectionBanner_TorturedSouls"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_SpecialPack_HolidayHorror_GhostFace.T_UI_SpecialPack_HolidayHorror_GhostFace"
- $.entries[4].uri: "images/T_UI_CollectionBanner_TorturedSouls.png"
+ $.entries[4].uri: "images/T_UI_SpecialPack_HolidayHorror_GhostFace.png"
- $.entries[5].contentVersion: "1f90c86a7812b83089bbb5ca93ab494a410fdd68"
+ $.entries[5].contentVersion: "9fb6a693bfb5b80a098b6637558dc4c5d2f5896a"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_SpecialPack_TorturedSouls.T_UI_SpecialPack_TorturedSouls"
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_StrangerThings_Collection.T_UI_SpecialPack_StrangerThings_Collection"
- $.entries[5].uri: "images/T_UI_SpecialPack_TorturedSouls.png"
+ $.entries[5].uri: "images/T_UI_SpecialPack_StrangerThings_Collection.png"
- $.entries[6].contentVersion: "4241aea41d8825311b2c46ebb460c00302e462bb"
+ $.entries[6].contentVersion: "8d46698a5041a06f7a8dc32e70aeec82d2facfb0"
- $.entries[6].downloadStrategy: "preferRemote"
+ $.entries[6].downloadStrategy: "preferPackaged"
- $.entries[6].enableChecksum: true
+ $.entries[6].enableChecksum: false
- $.entries[6].packagedPath: ""
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_TWD_Rick.T_UI_CollectionBanner_TWD_Rick"
- $.entries[6].schema: "s3ver://"
+ $.entries[6].schema: "s3verbin://"
- $.entries[6].uri: "catalog.json"
+ $.entries[6].uri: "images/T_UI_CollectionBanner_TWD_Rick.png"
- $.entries[7].contentVersion: "a9570350b09251633ed30c94e8e0b7ac26158e0e"
+ $.entries[7].contentVersion: "7581c1cbf61cc1c05871d23c18f302ac23bddef2"
- $.entries[7].downloadStrategy: "preferRemote"
+ $.entries[7].downloadStrategy: "preferPackaged"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_SpecialPack_TWD_Rick.T_UI_SpecialPack_TWD_Rick"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "bonusPointEventsContent.json"
+ $.entries[7].uri: "images/T_UI_SpecialPack_TWD_Rick.png"
- $.entries[8].contentVersion: "0bf4ade3635c2b7e2963c904c94378abbc86d3a4"
+ $.entries[8].contentVersion: "faf1dcbc557a2c576691ca028a80046270faf2cd"
- $.entries[8].downloadStrategy: "preferRemote"
+ $.entries[8].downloadStrategy: "preferPackaged"
- $.entries[8].enableChecksum: true
+ $.entries[8].enableChecksum: false
- $.entries[8].packagedPath: ""
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_SpecialPack_UglySweaters2025.T_UI_SpecialPack_UglySweaters2025"
- $.entries[8].schema: "s3ver://"
+ $.entries[8].schema: "s3verbin://"
- $.entries[8].uri: "freetoplay/NA/event.json"
+ $.entries[8].uri: "images/T_UI_SpecialPack_UglySweaters2025.png"
- $.entries[9].contentVersion: "0bf4ade3635c2b7e2963c904c94378abbc86d3a4"
+ $.entries[9].contentVersion: "0ca29cfad66e60ac7b6109b34477af03daa15e6e"
- $.entries[9].uri: "freetoplay/EU/event.json"
+ $.entries[9].uri: "catalog.json"
- $.entries[10].contentVersion: "060829ab50ef0746441d345eba0be945d7cf3153"
+ $.entries[10].contentVersion: "61e326f637e6bb4d1581461141d7fb19e41c5476"
- $.entries[10].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[10].uri: "bonusPointEventsContent.json"
- $.entries[11].contentVersion: "4fba6589313c492828b84cf0684019ca2801df53"
+ $.entries[11].contentVersion: "569d5ca67db3c24bd78c379fc7c2a83b521e4e9b"
- $.entries[11].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[11].uri: "freetoplay/NA/event.json"
- $.entries[12].contentVersion: "3bab01f37e3e246b4c6850919b0faedc57af842f"
+ $.entries[12].contentVersion: "569d5ca67db3c24bd78c379fc7c2a83b521e4e9b"
- $.entries[12].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[12].uri: "freetoplay/EU/event.json"
- $.entries[13].contentVersion: "f0a8ee660be572c5c1f5189a16a3fc63ef42880d"
+ $.entries[13].contentVersion: "610e8ad65e82a61dd1be8cdc5f2a837cb4544499"
- $.entries[13].uri: "archiveQuests/CalamariV1.json"
+ $.entries[13].uri: "archiveQuests/Anniversary2022.json"
- $.entries[14].contentVersion: "afc4666c2c7402d59f3dc6c6dd5c490bc113c042"
+ $.entries[14].contentVersion: "cc103090bf7e4bacacbbeafbd96c406fba59bf5d"
- $.entries[14].uri: "archiveQuests/CalamariV2.json"
+ $.entries[14].uri: "archiveQuests/Anniversary2023.json"
- $.entries[15].contentVersion: "be33dc3eabe88389e27ccf8fa0c1d43f45f04d02"
+ $.entries[15].contentVersion: "83b89d1bababbcccde765b193bd4d0b7544dde7f"
- $.entries[15].uri: "archiveQuests/CalamariV3.json"
+ $.entries[15].uri: "archiveQuests/Anniversary2024.json"
- $.entries[16].contentVersion: "48560b4cb3fdc501cf12a779616152a67a865b65"
+ $.entries[16].contentVersion: "efdb60c6c39a3ab4fd5b91f39fde980d15a521bf"
- $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[16].uri: "archiveQuests/CalamariV1.json"
- $.entries[17].contentVersion: "20099ae62e0a566a48b11766a0c3b3582ff3ade4"
+ $.entries[17].contentVersion: "b2baebb5d3b6ab54513e2877af4c5761261e019b"
- $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[17].uri: "archiveQuests/CalamariV2.json"
- $.entries[18].contentVersion: "08d3567110c8ba64c654180e69d2d342000d2db9"
+ $.entries[18].contentVersion: "171d9db1545bd3478a75457e9f2890e4759d2f53"
- $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[18].uri: "archiveQuests/CalamariV3.json"
- $.entries[19].contentVersion: "5822e1fcf9e8db7137476e0c05564f3ad7b78db3"
+ $.entries[19].contentVersion: "becae62e2ae06436d6ab794ffa352fb13087eb47"
- $.entries[19].uri: "archiveQuests/FireflyV1.json"
+ $.entries[19].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[20].contentVersion: "3ee30bf8395ae04fdf7b5ff0e70fa5278cc3dd94"
+ $.entries[20].contentVersion: "b858822dadd89aa3bc6ba780d46d7149fdc0e400"
- $.entries[20].uri: "archiveQuests/Halloween2021.json"
+ $.entries[20].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[21].contentVersion: "72fb2d1c886c67189254d1892634be9cc78e1ad7"
+ $.entries[21].contentVersion: "c4841e99ba54380f9e849b5f92b6d48c87d59761"
- $.entries[21].uri: "archiveQuests/Halloween2022.json"
+ $.entries[21].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[22].contentVersion: "d446c45163794dba6a1ebf5213c9b07f1a6c1907"
+ $.entries[22].contentVersion: "fbc1a0dcaa3daa3d3413d427ad2832cd0eafbd07"
- $.entries[22].uri: "archiveQuests/Halloween2023.json"
+ $.entries[22].uri: "archiveQuests/FireflyV1.json"
- $.entries[23].contentVersion: "13e2226d01fd4290aa543abb0f9ad1f9331a744e"
+ $.entries[23].contentVersion: "a2b8193299ed415793b71aa71d62084b4d9b542d"
- $.entries[23].uri: "archiveQuests/Halloween2024.json"
+ $.entries[23].uri: "archiveQuests/Halloween2021.json"
- $.entries[24].contentVersion: "0910f5f1ea5b0f52792b4c6b115ae6cc5e03d1ba"
+ $.entries[24].contentVersion: "4285f990ef342b18e46d5b90cf4a621a252a0dda"
- $.entries[24].uri: "archiveQuests/Spring2024.json"
+ $.entries[24].uri: "archiveQuests/Halloween2022.json"
- $.entries[25].contentVersion: "9c3dbd07d43b9bf2d68a5052aa7e1b7f9b328e2d"
+ $.entries[25].contentVersion: "9b9e861d327a2e191ae98b4b078178537bbac2de"
- $.entries[25].uri: "archiveQuests/Spring2025.json"
+ $.entries[25].uri: "archiveQuests/Halloween2023.json"
- $.entries[26].contentVersion: "b8a21a5e417eb4fb58a3fe3f19e51297b148aed8"
+ $.entries[26].contentVersion: "38269db0144c1dd4eb259b0ca64a33db060bd238"
- $.entries[26].uri: "archiveQuests/Summer2023.json"
+ $.entries[26].uri: "archiveQuests/Halloween2024.json"
- $.entries[27].contentVersion: "76ddf592108f835d0a40fde54f2d32bfd1ec9220"
+ $.entries[27].contentVersion: "81c68ec37f0478e0ba80f5b3d675751fed75de1d"
- $.entries[27].uri: "archiveQuests/Tome01.json"
+ $.entries[27].uri: "archiveQuests/Spring2024.json"
- $.entries[28].contentVersion: "faca8eb7e0ea75ef097e9ba639a8937b6855fd89"
+ $.entries[28].contentVersion: "7eda790a24a924246e1e64e6113745b111c10bbe"
- $.entries[28].uri: "archiveQuests/Tome02.json"
+ $.entries[28].uri: "archiveQuests/Spring2025.json"
- $.entries[29].contentVersion: "a4f7629b334ec029c89e994e71931bb2bdb4e0ac"
+ $.entries[29].contentVersion: "28508f31923ee8b725363eccdad226d0ca38bb62"
- $.entries[29].uri: "archiveQuests/Tome03.json"
+ $.entries[29].uri: "archiveQuests/Summer2023.json"
- $.entries[30].contentVersion: "bbf3b2706c65158c48f7eb2385b161032be044b2"
+ $.entries[30].contentVersion: "d1f37b8492d0fdb432a8ea61c3dbb864626e9456"
- $.entries[30].uri: "archiveQuests/Tome04.json"
+ $.entries[30].uri: "archiveQuests/Tome01.json"
- $.entries[31].contentVersion: "b4542d3a9f74f6793dbe6915a893c8fc098c01c8"
+ $.entries[31].contentVersion: "da208e659614e53ff1e8249284914ca75c47fb09"
- $.entries[31].uri: "archiveQuests/Tome05.json"
+ $.entries[31].uri: "archiveQuests/Tome02.json"
- $.entries[32].contentVersion: "799459d079f1cae39cde25b9d4b8f0358e4e62d4"
+ $.entries[32].contentVersion: "dc24f08d20dd1e4e1f948517118ab644e802e15f"
- $.entries[32].uri: "archiveQuests/Tome06.json"
+ $.entries[32].uri: "archiveQuests/Tome03.json"
- $.entries[33].contentVersion: "6b5ccd71f6eea0fe9a7b07371100e6e7f8c65595"
+ $.entries[33].contentVersion: "34b3ac318ad925cbe2ba7185eab5726ddbdebad8"
- $.entries[33].uri: "archiveQuests/Tome07.json"
+ $.entries[33].uri: "archiveQuests/Tome04.json"
- $.entries[34].contentVersion: "97165ee326eaf03b03498c04cfa83510860f8259"
+ $.entries[34].contentVersion: "1f9e5fa9a0500ed1412cf848b7ff34278507bcfc"
- $.entries[34].uri: "archiveQuests/Tome08.json"
+ $.entries[34].uri: "archiveQuests/Tome05.json"
- $.entries[35].contentVersion: "3b3de3a94550e5b3ff68d30f136ebca9c9ad5597"
+ $.entries[35].contentVersion: "26b38a348f4f4f6b35252d8128155554c3221960"
- $.entries[35].uri: "archiveQuests/Tome09.json"
+ $.entries[35].uri: "archiveQuests/Tome06.json"
- $.entries[36].contentVersion: "1851ba7b118fc49eb5b6d585141db1447f89a543"
+ $.entries[36].contentVersion: "760147c218a998f0b41020b515f1acf11a61cc54"
- $.entries[36].uri: "archiveQuests/Tome10.json"
+ $.entries[36].uri: "archiveQuests/Tome07.json"
- $.entries[37].contentVersion: "b73d2378b0c910d7191f4b9269c046d086a46c4c"
+ $.entries[37].contentVersion: "deb6f139e94690ba00aa382e95178f6101166395"
- $.entries[37].uri: "archiveQuests/Tome11.json"
+ $.entries[37].uri: "archiveQuests/Tome08.json"
- $.entries[38].contentVersion: "64f454e26b505ab9f4877892aaec77c180c6de3f"
+ $.entries[38].contentVersion: "4d4bf56234af45adac32174657a9ae88c5c53604"
- $.entries[38].uri: "archiveQuests/Tome12.json"
+ $.entries[38].uri: "archiveQuests/Tome09.json"
- $.entries[39].contentVersion: "22cecda2a00721fbe3da30e094e5dbf883cf32f7"
+ $.entries[39].contentVersion: "8e740988c71a1b7ade694351704e663935e4034e"
- $.entries[39].uri: "archiveQuests/Tome13.json"
+ $.entries[39].uri: "archiveQuests/Tome10.json"
… 709 more change(s) — see the commit diff for everything
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
+ $.specialEvents[61].eventName
+ $.specialEvents[61].eventType: "MapShowcase"
- $.specialEvents[61].eventId: "ChocolateBoxOmelet"
+ $.specialEvents[61].eventId: "MapShowcase_Omelet_01"
- $.specialEvents[61].mainEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].mainEndTime: "2025-12-05T15:59:42"
- $.specialEvents[61].postEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].postEndTime: "2025-12-05T15:59:42"
- $.specialEvents[61].startTime: "2026-01-13T16:00:00"
+ $.specialEvents[61].startTime: "2025-12-01T16:00:00"
- $.specialEvents[61].useCommonData: false
+ $.specialEvents[61].useCommonData: true
- $.specialEvents[62].eventId: "MapShowcase_Omelet_01"
+ $.specialEvents[62].eventId: "MapShowcase_Omelet_02"
- $.specialEvents[62].eventName.de: "Skiort am Mount Ormond"
+ $.specialEvents[62].eventName.de: "Mine am Ormond-See"
- $.specialEvents[62].eventName.en: "Mount Ormond Resort"
+ $.specialEvents[62].eventName.en: "Ormond Lake Mine"
- $.specialEvents[62].eventName.es: "Complejo del monte Ormond"
+ $.specialEvents[62].eventName.es: "Mina del lago Ormond"
- $.specialEvents[62].eventName["es-MX"]: "Complejo del monte Ormond"
+ $.specialEvents[62].eventName["es-MX"]: "Mina del lago Ormond"
- $.specialEvents[62].eventName.fr: "Station du mont Ormond"
+ $.specialEvents[62].eventName.fr: "Mine du lac d'Ormond"
- $.specialEvents[62].eventName.it: "Resort del Monte Ormond"
+ $.specialEvents[62].eventName.it: "Miniera del lago Ormond"
- $.specialEvents[62].eventName.ja: "オーモンド山のリゾート"
+ $.specialEvents[62].eventName.ja: "オーモンド湖採掘場"
- $.specialEvents[62].eventName.ko: "오르몬드 산 리조트"
+ $.specialEvents[62].eventName.ko: "오르몬드 호수 채굴장"
- $.specialEvents[62].eventName.pl: "Ośrodek Mount Ormond"
+ $.specialEvents[62].eventName.pl: "Kopalnia nad jeziorem Ormond"
- $.specialEvents[62].eventName["pt-BR"]: "Resort do Monte Ormond"
+ $.specialEvents[62].eventName["pt-BR"]: "Mina do Lago de Ormond"
- $.specialEvents[62].eventName.ru: "Курорт «Гора Ормонд»"
+ $.specialEvents[62].eventName.ru: "Шахта у озера Ормонд"
- $.specialEvents[62].eventName.th: "ที่พักตากอากาศเขาออร์มอนด์"
+ $.specialEvents[62].eventName.th: "เหมืองทะเลสาบออร์มอนด์"
- $.specialEvents[62].eventName.tr: "Ormond Dağı Tatil Yeri"
+ $.specialEvents[62].eventName.tr: "Ormond Gölü Madeni"
- $.specialEvents[62].eventName["zh-Hans"]: "奥蒙德山度假村"
+ $.specialEvents[62].eventName["zh-Hans"]: "奥蒙德湖矿场"
- $.specialEvents[62].eventName["zh-Hant"]: "奧蒙德山度假村"
+ $.specialEvents[62].eventName["zh-Hant"]: "奧蒙德湖礦場"
- $.specialEvents[62].mainEndTime: "2025-12-05T15:59:42"
+ $.specialEvents[62].mainEndTime: "2025-12-09T15:59:42"
- $.specialEvents[62].postEndTime: "2025-12-05T15:59:42"
+ $.specialEvents[62].postEndTime: "2025-12-09T15:59:42"
- $.specialEvents[62].startTime: "2025-12-01T16:00:00"
+ $.specialEvents[62].startTime: "2025-12-05T16:00:00"
- $.specialEvents[63]
- $.specialEventsData[18].eventId: "ChocolateBoxOmelet"
+ $.specialEventsData[18].eventId: "ChocolateBoxV1"
+ $.specialEventsData[18].lteData.incentiveBonus: 0.0
- $.specialEventsData[19].eventId: "ChocolateBoxV1"
+ $.specialEventsData[19].eventId: "DreadByDaylightZodiac"
- $.specialEventsData[19].lteData.affectsMMR: true
+ $.specialEventsData[19].lteData.affectsMMR: false
- $.specialEventsData[19].lteData.gameModeQueue: "ChocolateBox"
+ $.specialEventsData[19].lteData.gameModeQueue: "DreadByDaylight"
- $.specialEventsData[19].lteData.gameType: "ChocolateBox"
+ $.specialEventsData[19].lteData.gameType: "DreadByDaylight"
- $.specialEventsData[20].eventId: "DreadByDaylightZodiac"
+ $.specialEventsData[20].eventId: "FireflyV1"
- $.specialEventsData[20].lteData.gameModeQueue: "DreadByDaylight"
+ $.specialEventsData[20].lteData.gameModeQueue: "Firefly"
- $.specialEventsData[20].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[20].lteData.gameType: "Firefly"
- $.specialEventsData[21].lteData
- $.specialEventsData[21].eventId: "FireflyV1"
+ $.specialEventsData[21].eventId: "Halloween2022"
+ $.specialEventsData[21].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[22].eventId: "Halloween2022"
+ $.specialEventsData[22].eventId: "Halloween2023"
+ $.specialEventsData[22].milestoneRewards[0]
+ $.specialEventsData[22].milestoneRewards[1]
+ $.specialEventsData[22].milestoneRewards[2]
- $.specialEventsData[22].ownerRewards[id=Halloween2022Reward]
+ $.specialEventsData[23].lteData
- $.specialEventsData[23].eventId: "Halloween2023"
+ $.specialEventsData[23].eventId: "Halloween2024"
+ $.specialEventsData[23].eventPeriods[id=Halloween2024]
- $.specialEventsData[23].milestoneRewards[0].rewards[id=XR_037]
+ $.specialEventsData[23].milestoneRewards[0].rewards[id=FU_012]
- $.specialEventsData[23].milestoneRewards[1].rewards[id=MT_Head027]
+ $.specialEventsData[23].milestoneRewards[1].rewards[id=FU_BDG_18]
- $.specialEventsData[23].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[23].milestoneRewards[2].pointsCost: 20
- $.specialEventsData[23].milestoneRewards[2].rewards[id=K30_Head011]
+ $.specialEventsData[23].milestoneRewards[2].rewards[id=FU_BNR_12]
- $.specialEventsData[24].eventId: "Halloween2024"
+ $.specialEventsData[24].eventId: "Halloween2025"
- $.specialEventsData[24].eventPeriods[id=Halloween2024]
- $.specialEventsData[24].lteData.incentiveBonus: 50.0
- $.specialEventsData[24].lteData.gameModeQueue: "Halloween2024"
+ $.specialEventsData[24].lteData.gameModeQueue: "Halloween2025"
- $.specialEventsData[24].milestoneRewards[0]
- $.specialEventsData[24].milestoneRewards[1]
- $.specialEventsData[24].milestoneRewards[2]
- $.specialEventsData[25].lteData
- $.specialEventsData[25].eventId: "Halloween2025"
+ $.specialEventsData[25].eventId: "Lunar2022"
+ $.specialEventsData[25].miscRewards[id=killerStaticReward]
+ $.specialEventsData[25].ownerRewards[id=Lunar2022Reward]
+ $.specialEventsData[25].scoreEventRewards[0]
+ $.specialEventsData[25].scoreEventRewards[1]
+ $.specialEventsData[25].scoreEventRewards[2]
+ $.specialEventsData[25].scoreEventRewards[3]
+ $.specialEventsData[25].scoreEventRewards[4]
+ $.specialEventsData[25].scoreEventRewards[5]
+ $.specialEventsData[25].scoreEventRewards[6]
+ $.specialEventsData[25].scoreEventRewards[7]
- $.specialEventsData[26].eventId: "Lunar2022"
+ $.specialEventsData[26].eventId: "Lunar2023"
- $.specialEventsData[26].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 4000
+ $.specialEventsData[26].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 5000
- $.specialEventsData[26].ownerRewards[id=Lunar2022Reward]
+ $.specialEventsData[26].ownerRewards[id=Lunar2023Reward]
- $.specialEventsData[26].scoreEventRewards[2].weight: 20
+ $.specialEventsData[26].scoreEventRewards[2].weight: 15
- $.specialEventsData[26].scoreEventRewards[3].weight: 20
+ $.specialEventsData[26].scoreEventRewards[3].weight: 25
- $.specialEventsData[26].scoreEventRewards[5].weight: 15
+ $.specialEventsData[26].scoreEventRewards[5].weight: 20
- $.specialEventsData[26].scoreEventRewards[6].weight: 8
+ $.specialEventsData[26].scoreEventRewards[6].weight: 10
- $.specialEventsData[26].scoreEventRewards[7].weight: 2
+ $.specialEventsData[26].scoreEventRewards[7].weight: 5
+ $.specialEventsData[27].lteData
- $.specialEventsData[27].eventId: "Lunar2023"
+ $.specialEventsData[27].eventId: "MapShowcaseKetchup"
- $.specialEventsData[27].miscRewards[id=killerStaticReward]
- $.specialEventsData[27].ownerRewards[id=Lunar2023Reward]
- $.specialEventsData[27].scoreEventRewards[0]
- $.specialEventsData[27].scoreEventRewards[1]
- $.specialEventsData[27].scoreEventRewards[2]
- $.specialEventsData[27].scoreEventRewards[3]
- $.specialEventsData[27].scoreEventRewards[4]
- $.specialEventsData[27].scoreEventRewards[5]
- $.specialEventsData[27].scoreEventRewards[6]
- $.specialEventsData[27].scoreEventRewards[7]
- $.specialEventsData[28].eventId: "MapShowcaseKetchup"
+ $.specialEventsData[28].eventId: "MapShowcase_Omelet_01"
- $.specialEventsData[29].eventId: "MapShowcase_Omelet_01"
+ $.specialEventsData[29].eventId: "MapShowcase_Omelet_02"
- $.specialEventsData[30].lteData
- $.specialEventsData[30].eventId: "MapShowcase_Omelet_02"
+ $.specialEventsData[30].eventId: "Spring2024"
+ $.specialEventsData[30].eventTrackerObjectives[id=main]
+ $.specialEventsData[31].lteData
- $.specialEventsData[31].eventId: "Spring2024"
+ $.specialEventsData[31].eventId: "Spring2025"
- $.specialEventsData[31].eventTrackerObjectives[id=main].questEventId: "QuestEvent.SpringEventPlaceZone"
- $.specialEventsData[31].eventTrackerObjectives[id=main].questEventParams: "instigator:me"
+ $.specialEventsData[31].eventTrackerObjectives[id=main].additionalEventIdsWithMilestoneBonus
+ $.specialEventsData[31].eventTrackerObjectives[id=main].questEventConditions
+ $.specialEventsData[31].eventTrackerObjectives[id=main].questEvents
- $.specialEventsData[31].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 10
+ $.specialEventsData[31].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 16
- $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.0
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
- $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 2.0
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
- $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[1].neededProgression: 7000000
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
- $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 3.0
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
- $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[2].neededProgression: 20000000
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
- $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 4.0
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
- $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[3].neededProgression: 35000000
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[4]
+ $.specialEventsData[31].eventTrackerObjectives[id=main].milestones[5]
+ $.specialEventsData[31].milestoneRewards[0]
+ $.specialEventsData[31].milestoneRewards[1]
+ $.specialEventsData[31].milestoneRewards[2]
- $.specialEventsData[32].lteData
- $.specialEventsData[32].eventId: "Spring2025"
+ $.specialEventsData[32].eventId: "Winter2023"
- $.specialEventsData[32].eventTrackerObjectives[id=main]
- $.specialEventsData[32].milestoneRewards[0].rewards[id=IC_001]
+ $.specialEventsData[32].milestoneRewards[0].rewards[id=YE_005]
- $.specialEventsData[32].milestoneRewards[1].pointsCost: 8
+ $.specialEventsData[32].milestoneRewards[1].pointsCost: 6
- $.specialEventsData[32].milestoneRewards[1].rewards[id=IC_BDG_03]
+ $.specialEventsData[32].milestoneRewards[1].rewards[id=YE_BDG_01]
- $.specialEventsData[32].milestoneRewards[2].pointsCost: 15
+ $.specialEventsData[32].milestoneRewards[2].pointsCost: 9
- $.specialEventsData[32].milestoneRewards[2].rewards[id=IC_BNR_03]
+ $.specialEventsData[32].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[32].milestoneRewards[3]
+ $.specialEventsData[32].milestoneRewards[4]
+ $.specialEventsData[33].lteData
- $.specialEventsData[33].eventId: "Winter2023"
+ $.specialEventsData[33].eventId: "Winter2024"
+ $.specialEventsData[33].eventPeriods[id=Winter2024]
- $.specialEventsData[33].milestoneRewards[0].pointsCost: 3
+ $.specialEventsData[33].milestoneRewards[0].pointsCost: 6
… 22 more change(s) — see the commit diff for everything
```

## Could not download

- `images/T_UI_CollectionBanner_TWD_Rick.png (HTTP 404)`
- `images/T_UI_SpecialPack_HolidayHorror_GhostFace.png (HTTP 404)`
- `images/T_UI_SpecialPack_StrangerThings_Collection.png (HTTP 404)`
- `images/T_UI_SpecialPack_TWD_Rick.png (HTTP 404)`
- `images/T_UI_SpecialPack_UglySweaters2025.png (HTTP 404)`
- `images/T_UI_Specialpack_Bonechill2024.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_GenQuest1.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_cosmetic.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_gift.png (HTTP 404)`

