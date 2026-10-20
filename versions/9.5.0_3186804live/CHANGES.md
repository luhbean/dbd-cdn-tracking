# live · 9.5.0_3186804live

| | |
|---|---|
| Build date | 2026-03-17 16:33 UTC |
| CDN version | `9.5.0_3186804live-1773765180` |
| Key | `9.5.0_live` |
| Compared with | [9.5.0_3185911live](../9.5.0_3185911live/CHANGES.md) (2026-03-16 20:58 UTC) |

## Summary

**0** added · **9** modified · **0** removed · 208 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=S52].metaData.defaultCustomization[]: "S52_Torso01_04"
- $[id=S52_Torso01_04].categories[]: "default"
- $[id=S52_Torso01_04].metaData.entitledByDefault: true
+ $[id=S52_Torso01_04].metaData.entitledByDefault: false
- $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.ko: "MiNA Bundle"
+ $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.ko: "미나 번들"
- $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.pl: "MiNA Bundle"
+ $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.pl: "Pakiet MiNA"
- $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.ru: "MiNA Bundle"
+ $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.ru: "Набор «МиНА»"
- $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.tr: "MiNA Bundle"
+ $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle.tr: "MiNA Paketi"
- $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle["zh-Hant"]: "MiNA Bundle"
+ $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle["zh-Hant"]: "米娜組合包"
- $[id=ChapterPack_Quiche].metaData.specialPackTitle.ko: "All-Kill: Comeback Chapter"
+ $[id=ChapterPack_Quiche].metaData.specialPackTitle.ko: "올킬: 컴백 챕터"
- $[id=ChapterPack_Quiche].metaData.specialPackTitle.pl: "All-Kill: Comeback Chapter"
+ $[id=ChapterPack_Quiche].metaData.specialPackTitle.pl: "Rozdział All-Kill: Powrót"
- $[id=ChapterPack_Quiche].metaData.specialPackTitle.ru: "All-Kill: Comeback Chapter"
+ $[id=ChapterPack_Quiche].metaData.specialPackTitle.ru: "Глава All-Kill: Comeback"
- $[id=ChapterPack_Quiche].metaData.specialPackTitle.tr: "All-Kill: Comeback Chapter"
+ $[id=ChapterPack_Quiche].metaData.specialPackTitle.tr: "All-Kill: Comeback Bölümü"
- $[id=ChapterPack_Quiche].metaData.specialPackTitle["zh-Hant"]: "All-Kill: Comeback Chapter"
+ $[id=ChapterPack_Quiche].metaData.specialPackTitle["zh-Hant"]: "趕盡殺絕：回歸章節"
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[462].text: "균열 패스 퀘스트 - 1주차"
+ $.locText[462].text: "챕터 퀘스트 - 파트 1"
- $.locText[463].text: "균열 패스 퀘스트 - 2주차"
+ $.locText[463].text: "챕터 퀘스트 - 파트 2"
- $.locText[565].text: "Chapter Quests - Trickster"
+ $.locText[565].text: "챕터 퀘스트 - 트릭스터"
- $.locText[567].text: "@핏빛 달"
+ $.locText[567].text: "핏빛 달"
- $.locText[571].text: "@ 피의 발전기{0}대 손상시키기"
+ $.locText[571].text: "피의 발전기 {0}대 손상시키기"
- $.locText[574].text: "@ 피의 캔을 보유한 생존자에게 {0}회 부상 입히기"
+ $.locText[574].text: "피의 캔을 보유한 생존자에게 {0}회 부상 입히기"
- $.locText[575].text: "Fill A Blood Generator"
+ $.locText[575].text: "피의 발전기 채우기"
- $.locText[577].text: "Fuel {0} Blood Generator(s)"
+ $.locText[577].text: "피의 발전기 {0}대에 연료 채우기"
- $.locText[580].text: "@ 피의 캔 {0}회 채우기"
+ $.locText[580].text: "피의 캔 {0}회 채우기"
- $.locText[581].text: "@핏빛 달 완료 퀘스트"
+ $.locText[581].text: "핏빛 달 완료 퀘스트"
- $.locText[582].text: "@핏빛 달 마일스톤 퀘스트"
+ $.locText[582].text: "핏빛 달 마일스톤 퀘스트"
- $.locText[583].text: "@핏빛 달 - 파트 1"
+ $.locText[583].text: "핏빛 달 - 파트 1"
- $.locText[584].text: "@핏빛 달 - 파트 2"
+ $.locText[584].text: "핏빛 달 - 파트 2"
- $.locText[585].text: "@핏빛 달 - 파트 3"
+ $.locText[585].text: "핏빛 달 - 파트 3"
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[462].text: "ZADANIA ROZDZIAŁU – TYDZIEŃ 1"
+ $.locText[462].text: "ZADANIA ROZDZIAŁU – CZĘŚĆ 1"
- $.locText[463].text: "ZADANIA ROZDZIAŁU – TYDZIEŃ 2"
+ $.locText[463].text: "ZADANIA ROZDZIAŁU – CZĘŚĆ 2"
- $.locText[565].text: "Chapter Quests - Trickster"
+ $.locText[565].text: "Zadania rozdziału – Magik"
- $.locText[567].text: "@Krwawy księżyc"
+ $.locText[567].text: "Krwawy księżyc"
- $.locText[571].text: "@Uszkodź tyle krwawych generatorów: {0}"
+ $.locText[571].text: "Uszkodź tyle krwawych generatorów: {0}"
- $.locText[574].text: "@Zrań ocalałych niosących pojemnik z krwią tyle razy: {0}"
+ $.locText[574].text: "Zrań ocalałych niosących pojemnik z krwią tyle razy: {0}"
- $.locText[575].text: "Fill A Blood Generator"
+ $.locText[575].text: "Wypełnij krwawy generator"
- $.locText[577].text: "Fuel {0} Blood Generator(s)"
+ $.locText[577].text: "Zasil tyle krwawych generatorów: {0}"
- $.locText[580].text: "@Napełnij pojemnik z krwią tyle razy: {0}"
+ $.locText[580].text: "Napełnij pojemnik z krwią tyle razy: {0}"
- $.locText[581].text: "@Krwawy księżyc – zadania końcowe"
+ $.locText[581].text: "Krwawy księżyc – zadania końcowe"
- $.locText[582].text: "@Krwawy księżyc – zadania etapów"
+ $.locText[582].text: "Krwawy księżyc – zadania etapów"
- $.locText[583].text: "@Krwawy księżyc – część 1"
+ $.locText[583].text: "Krwawy księżyc – część 1"
- $.locText[584].text: "@Krwawy księżyc – część 2"
+ $.locText[584].text: "Krwawy księżyc – część 2"
- $.locText[585].text: "@Krwawy księżyc – część 3"
+ $.locText[585].text: "Krwawy księżyc – część 3"
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[462].text: "ЗАДАНИЯ ГЛАВЫ — НЕДЕЛЯ 1"
+ $.locText[462].text: "ЗАДАНИЯ ГЛАВЫ — ЧАСТЬ 1"
- $.locText[463].text: "ЗАДАНИЯ ГЛАВЫ — НЕДЕЛЯ 2"
+ $.locText[463].text: "ЗАДАНИЯ ГЛАВЫ — ЧАСТЬ 2"
- $.locText[565].text: "Chapter Quests - Trickster"
+ $.locText[565].text: "Задания главы — Трюкач"
- $.locText[567].text: "@Кровавая луна"
+ $.locText[567].text: "Кровавая луна"
- $.locText[571].text: "@Повредите кровавый генератор {0} раз(а)"
+ $.locText[571].text: "Повредите кровавый генератор {0} р."
- $.locText[574].text: "@Нанесите урон выжившему, несущему канистру крови, {0} раз(а)"
+ $.locText[574].text: "Нанесите урон выжившему, несущему канистру крови, {0} р."
- $.locText[575].text: "Fill A Blood Generator"
+ $.locText[575].text: "Заправьте кровавый генератор"
- $.locText[577].text: "Fuel {0} Blood Generator(s)"
+ $.locText[577].text: "Заправьте кровавый генератор {0} р."
- $.locText[580].text: "@Заполните канистру крови {0} раз(а)"
+ $.locText[580].text: "Заполните канистру крови {0} р."
- $.locText[581].text: "@Кровавая луна: задания завершения"
+ $.locText[581].text: "Кровавая луна: задания завершения"
- $.locText[582].text: "@Кровавая луна: задания этапов"
+ $.locText[582].text: "Кровавая луна: задания этапов"
- $.locText[583].text: "@Кровавая луна — часть 1"
+ $.locText[583].text: "Кровавая луна — часть 1"
- $.locText[584].text: "@Кровавая луна — часть 2"
+ $.locText[584].text: "Кровавая луна — часть 2"
- $.locText[585].text: "@Кровавая луна — часть 3"
+ $.locText[585].text: "Кровавая луна — часть 3"
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[462].text: "BÖLÜM GÖREVLERİ - 1. HAFTA"
+ $.locText[462].text: "BÖLÜM GÖREVLERİ - 1. KISIM"
- $.locText[463].text: "BÖLÜM GÖREVLERİ - 2. HAFTA"
+ $.locText[463].text: "BÖLÜM GÖREVLERİ - 2. KISIM"
- $.locText[565].text: "Chapter Quests - Trickster"
+ $.locText[565].text: "Bölüm Görevleri - Dümenci"
- $.locText[567].text: "@Kanlı Ay"
+ $.locText[567].text: "Kanlı Ay"
- $.locText[571].text: "{0} Kan Jeneratörüne @Hasar Ver"
+ $.locText[571].text: "{0} Kan Jeneratörüne hasar ver"
- $.locText[574].text: "Kan kutusu taşıyan kurbanı {0} defa @yarala"
+ $.locText[574].text: "Kan kutusu taşıyan bir Kurbanı {0} defa yarala"
- $.locText[575].text: "Fill A Blood Generator"
+ $.locText[575].text: "Bir Kan Jeneratörü doldur"
- $.locText[577].text: "Fuel {0} Blood Generator(s)"
+ $.locText[577].text: "{0} Kan Jeneratörü doldur"
- $.locText[580].text: "Bir Kan Kutusunu {0} Defa @Doldur"
+ $.locText[580].text: "Bir Kan Kutusunu {0} defa doldur"
- $.locText[581].text: "@Kanlı Ay Tamamlama Görevleri"
+ $.locText[581].text: "Kanlı Ay Tamamlama Görevleri"
- $.locText[582].text: "@Kanlı Ay Kilometre Taşı Görevleri"
+ $.locText[582].text: "Kanlı Ay Kilometre Taşı Görevleri"
- $.locText[583].text: "@Kanlı Ay - 1. Kısım"
+ $.locText[583].text: "Kanlı Ay - 1. Kısım"
- $.locText[584].text: "@Kanlı Ay - 2. Kısım"
+ $.locText[584].text: "Kanlı Ay - 2. Kısım"
- $.locText[585].text: "@Kanlı Ay - 3. Kısım"
+ $.locText[585].text: "Kanlı Ay - 3. Kısım"
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[462].text: "章節任務 - 第1週"
+ $.locText[462].text: "章節任務 - 第1段"
- $.locText[463].text: "章節任務 - 第2週"
+ $.locText[463].text: "章節任務 - 第2段"
- $.locText[565].text: "Chapter Quests - Trickster"
+ $.locText[565].text: "章節任務 - 騙術師"
- $.locText[567].text: "@血月"
+ $.locText[567].text: "血月"
- $.locText[571].text: "@傷害{0}台鮮血發電機"
+ $.locText[571].text: "破壞{0}台鮮血發電機"
- $.locText[574].text: "@傷害攜帶血罐的倖存者{0}次"
+ $.locText[574].text: "傷害攜帶血罐的倖存者{0}次"
- $.locText[575].text: "Fill A Blood Generator"
+ $.locText[575].text: "填滿鮮血發電機"
- $.locText[577].text: "Fuel {0} Blood Generator(s)"
+ $.locText[577].text: "填滿{0}鮮血發電機"
- $.locText[580].text: "@裝滿血罐{0}次"
+ $.locText[580].text: "裝滿血罐{0}次"
- $.locText[581].text: "@血月完成任務"
+ $.locText[581].text: "血月完成任務"
- $.locText[582].text: "@血月里程碑任務"
+ $.locText[582].text: "血月里程碑任務"
- $.locText[583].text: "@血月 - 第1章"
+ $.locText[583].text: "血月 - 第1章"
- $.locText[584].text: "@血月 - 第2章"
+ $.locText[584].text: "血月 - 第2章"
- $.locText[585].text: "@血月 - 第3章"
+ $.locText[585].text: "血月 - 第3章"
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.BloodMoon_Quiche.titleLocalizationText.ko: "@핏빛 달"
+ $.BloodMoon_Quiche.titleLocalizationText.ko: "핏빛 달"
- $.BloodMoon_Quiche.titleLocalizationText.pl: "@Krwawy księżyc"
+ $.BloodMoon_Quiche.titleLocalizationText.pl: "Krwawy księżyc"
- $.BloodMoon_Quiche.titleLocalizationText.ru: "@Кровавая луна"
+ $.BloodMoon_Quiche.titleLocalizationText.ru: "Кровавая луна"
- $.BloodMoon_Quiche.titleLocalizationText.tr: "@Kanlı Ay"
+ $.BloodMoon_Quiche.titleLocalizationText.tr: "Kanlı Ay"
- $.BloodMoon_Quiche.titleLocalizationText["zh-Hant"]: "@血月"
+ $.BloodMoon_Quiche.titleLocalizationText["zh-Hant"]: "血月"
- $.ChapterQuests_Quiche.titleLocalizationText.ko: "Chapter Quests - Trickster"
+ $.ChapterQuests_Quiche.titleLocalizationText.ko: "챕터 퀘스트 - 트릭스터"
- $.ChapterQuests_Quiche.titleLocalizationText.pl: "Chapter Quests - Trickster"
+ $.ChapterQuests_Quiche.titleLocalizationText.pl: "Zadania rozdziału – Magik"
- $.ChapterQuests_Quiche.titleLocalizationText.ru: "Chapter Quests - Trickster"
+ $.ChapterQuests_Quiche.titleLocalizationText.ru: "Задания главы — Трюкач"
- $.ChapterQuests_Quiche.titleLocalizationText.tr: "Chapter Quests - Trickster"
+ $.ChapterQuests_Quiche.titleLocalizationText.tr: "Bölüm Görevleri - Dümenci"
- $.ChapterQuests_Quiche.titleLocalizationText["zh-Hant"]: "Chapter Quests - Trickster"
+ $.ChapterQuests_Quiche.titleLocalizationText["zh-Hant"]: "章節任務 - 騙術師"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[51].collectionTitle.ko: "All-Kill: Comeback"
+ $.collections[51].collectionTitle.ko: "올킬: 컴백"
- $.collections[51].collectionTitle.pl: "All-Kill: Comeback"
+ $.collections[51].collectionTitle.pl: "All-Kill: Powrót"
- $.collections[51].collectionTitle["zh-Hant"]: "All-Kill: Comeback"
+ $.collections[51].collectionTitle["zh-Hant"]: "趕盡殺絕：回歸"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[12].contentVersion: "0e29c1cf52e5fa0769bf12698d25a70f2e2df9f4"
+ $.entries[12].contentVersion: "8d150266e5d944f70a45286e9bc547e4c3827d7a"
- $.entries[86].contentVersion: "993ae18364af9c3a9dafb635d2b179bd1067e0f9"
+ $.entries[86].contentVersion: "64b365024056bdd8e001ab844196304260bdf43d"
- $.entries[183].contentVersion: "3d786cdd0ec936804798056c6a38fa0d44969832"
+ $.entries[183].contentVersion: "55b133fb90b401b8ccf5d63ea1b219f50a25e096"
- $.entries[206].contentVersion: "21ae70418a22ace8547a16dc00245cb11a9c9ec7"
+ $.entries[206].contentVersion: "4d089819d9165cc5ab60a79713c17d15170dd110"
- $.entries[207].contentVersion: "6038d2e61302d1a37a0d0d0b403bd54de6251214"
+ $.entries[207].contentVersion: "79e134e748bae50dd1d660f9a4ea96574c1ee6ec"
- $.entries[209].contentVersion: "d1d1d88c4aad91c1a45d14a00371b9460c2cafb1"
+ $.entries[209].contentVersion: "32a020fc6b71595f2418194cd2fa29660a097f33"
- $.entries[211].contentVersion: "8db936bb9f3fac6694055e057b98555603a04094"
+ $.entries[211].contentVersion: "e64d09a056d1ee07e60e702863ebfd67339f9d52"
- $.entries[213].contentVersion: "7ecc5cce9b73c0b86043845f52db3163c0bf9f2c"
+ $.entries[213].contentVersion: "bc5e997843b4b285fa167bcd41b815ec40e6e39b"
```

