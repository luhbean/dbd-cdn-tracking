# live · 9.0.2_2607135live

| | |
|---|---|
| Build date | 2025-07-10 12:51 UTC |
| CDN version | `9.0.2_2607135live-1752151867` |
| Key | `9.0.2_live` |
| Compared with | [9.0.2_2541994live](../9.0.2_2541994live/CHANGES.md) (2025-07-07 17:09 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 198 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=FM_Head024].defaultCost[1]
+ $[id=FM_Legs024].defaultCost[1]
+ $[id=FM_Torso024].defaultCost[1]
+ $[id=K31_Body013].defaultCost[1]
+ $[id=K31_Head013].defaultCost[1]
+ $[id=K31_W013].defaultCost[1]
- $[id=Boulet_Brothers_Bundle].metaData.specialPackTitle.fr: "@#Boulet_Brothers_Bundle_Title"
+ $[id=Boulet_Brothers_Bundle].metaData.specialPackTitle.fr: "Lot Boulet Brothers"
- $[id=Boulet_Brothers_Bundle].metaData.specialPackTitle.ja: "@#Boulet_Brothers_Bundle_Title"
+ $[id=Boulet_Brothers_Bundle].metaData.specialPackTitle.ja: "Boulet Brothersバンドル"
- $[id=NewPlayer_Killers].metaData.hiddenIfOwned: false
+ $[id=NewPlayer_Killers].metaData.hiddenIfOwned: true
- $[id=NewPlayer_Survivors].metaData.hiddenIfOwned: false
+ $[id=NewPlayer_Survivors].metaData.hiddenIfOwned: true
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[12].text: "Break {0} generator(s)"
+ $.locText[12].text: "Damage {0} generator(s)"
- $.locText[49].text: "Break {0} pallet(s)"
+ $.locText[49].text: "Destroy {0} pallet(s)"
- $.locText[164].text: "Break {0} generator(s) in a single trial"
+ $.locText[164].text: "Damage {0} generator(s) in a single trial"
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[4].text: "Accrochez {0} survivant(s)"
+ $.locText[4].text: "Accrocher {0} survivant(s)"
- $.locText[12].text: "Endommagez {0} générateur(s)"
+ $.locText[12].text: "Endommager {0} générateur(s)"
- $.locText[49].text: "Détruisez {0} palette(s)"
+ $.locText[49].text: "Détruire {0} palette(s)"
- $.locText[100].text: "Accrochez {0} survivants différents en une seule Épreuve"
+ $.locText[100].text: "Accrocher {0} survivants différents en une seule Épreuve"
- $.locText[111].text: "Aveuglez le tueur quand il transporte un survivant {0} fois"
+ $.locText[111].text: "Aveugler le tueur quand il transporte un survivant {0} fois"
- $.locText[124].text: "Accrochez {0} survivant(s) sur des Crochets flagellateurs"
+ $.locText[124].text: "Accrocher {0} survivant(s) sur des Crochets flagellateurs"
- $.locText[155].text: "Accrochez {0} survivant(s) en une seule épreuve"
+ $.locText[155].text: "Accrocher {0} survivant(s) en une seule épreuve"
- $.locText[164].text: "Endommagez {0} générateur(s) en une seule Épreuve"
+ $.locText[164].text: "Endommager {0} générateur(s) en une seule Épreuve"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[3].contentVersion: "e77153102f1c010d12550751edff542629e8b43a"
+ $.entries[3].contentVersion: "d22da0102e1d56b31a454b6ca58f354309aaca46"
- $.entries[187].contentVersion: "ea27425ec39e20309e29be6b322522f7d3488dbd"
+ $.entries[187].contentVersion: "7e39491eb4718877e626e9c7324630763347fdf9"
- $.entries[191].contentVersion: "dbaf6f0278509766ffcb1c517bf0a1508102b17f"
+ $.entries[191].contentVersion: "574eef35f7a89f8fa472aa99ab377acedbfc2034"
```

## Could not download

- `images/T_UI_CollectionBanner_BouletBrothers.png (HTTP 404)`
- `images/T_UI_SpecialPack_BouletBrothers.png (HTTP 404)`
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

