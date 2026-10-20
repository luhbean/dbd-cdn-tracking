# live · 9.2.2_2790686live

| | |
|---|---|
| Build date | 2025-10-06 16:01 UTC |
| CDN version | `9.2.2_2790686live-1759766470` |
| Key | `9.2.2_live` |
| Compared with | [9.2.1_2787180live](../9.2.1_2787180live/CHANGES.md) (2025-10-02 16:45 UTC) |

## Summary

**2** added · **28** modified · **0** removed · 177 unchanged

## New or updated images

<a href="images/T_UI_SpecialPack_Rift3.png"><img src="images/T_UI_SpecialPack_Rift3.png" alt="T_UI_SpecialPack_Rift3.png" width="240"></a>
<a href="images/T_UI_Specialpack_HauntedByDaylight2024.png"><img src="images/T_UI_Specialpack_HauntedByDaylight2024.png" alt="T_UI_Specialpack_HauntedByDaylight2024.png" width="240"></a>

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.analytics.EnableAnalyticErrorIncludesRuleIds: false
- $.analytics.EnableAnalyticFailureBlockIIS: false
+ $.analytics.enableAnalyticErrorIncludesRuleIds: false
+ $.analytics.enableAnalyticFailureBlockIIS: false
+ $.analytics.minCountValuesForRules
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=AV_Head029]
+ $[id=AV_Head029_01]
+ $[id=AV_Head029_02]
+ $[id=AV_Head029_03]
+ $[id=AV_Legs029]
+ $[id=AV_Legs029_01]
+ $[id=AV_Legs029_02]
+ $[id=AV_Legs029_03]
+ $[id=AV_Torso029]
+ $[id=AV_Torso029_01]
+ $[id=AV_Torso029_02]
+ $[id=AV_Torso029_03]
+ $[id=CM_Legs034]
+ $[id=CM_Legs034_01]
+ $[id=CM_Legs034_02]
+ $[id=CM_Legs034_03]
+ $[id=CM_Torso034]
+ $[id=CM_Torso034_01]
+ $[id=CM_Torso034_02]
+ $[id=CM_Torso034_03]
+ $[id=DF_Torso039]
+ $[id=GK_Body026]
+ $[id=GK_Head026]
+ $[id=GK_W026]
+ $[id=HK_Body026]
+ $[id=HK_Body026_01]
+ $[id=HK_Body026_02]
+ $[id=HK_Body026_03]
+ $[id=HK_Head026]
+ $[id=HK_Head026_01]
+ $[id=HK_Head026_02]
+ $[id=HK_Head026_03]
+ $[id=HK_W026]
+ $[id=HK_W026_01]
+ $[id=HK_W026_02]
+ $[id=HK_W026_03]
+ $[id=HS_Head031]
+ $[id=HS_Legs031]
+ $[id=HS_Torso031]
+ $[id=K23_Body029]
+ $[id=K23_Body029_01]
+ $[id=K23_Body029_02]
+ $[id=K23_Body029_03]
+ $[id=K23_Head029]
+ $[id=K23_Head029_01]
+ $[id=K23_Head029_02]
+ $[id=K23_Head029_03]
+ $[id=K23_W028]
+ $[id=K23_W029]
+ $[id=K23_W029_01]
+ $[id=K23_W029_02]
+ $[id=K23_W029_03]
+ $[id=K28_Body020]
+ $[id=K28_Head020]
+ $[id=K28_W020]
+ $[id=K30_Body020]
+ $[id=K30_Body020_01]
+ $[id=K30_Head020]
+ $[id=K30_Head020_01]
+ $[id=K30_W020]
+ $[id=K30_W020_01]
+ $[id=K31_Body018]
+ $[id=K31_Head018]
+ $[id=K31_W018]
+ $[id=K32_Body014]
+ $[id=K32_Body014_01]
+ $[id=K32_Head014]
+ $[id=K32_Head014_01]
+ $[id=K32_W014]
+ $[id=K32_W014_01]
+ $[id=K41_W007]
+ $[id=NA_001]
+ $[id=NA_002]
+ $[id=NA_003]
+ $[id=NA_004]
+ $[id=NA_005]
+ $[id=NA_006]
+ $[id=NA_007]
+ $[id=NA_008]
+ $[id=NA_009]
+ $[id=NA_010]
+ $[id=NA_012]
+ $[id=NA_013]
+ $[id=NA_014]
+ $[id=NA_BDG_01]
+ $[id=NA_BDG_04]
+ $[id=NA_BDG_05]
+ $[id=NA_BDG_06]
+ $[id=NA_BDG_08]
+ $[id=NA_BDG_09]
+ $[id=NA_BDG_10]
+ $[id=NA_BDG_11]
+ $[id=NA_BDG_12]
+ $[id=NA_BDG_13]
+ $[id=NA_BDG_14]
+ $[id=NA_BDG_15]
+ $[id=NA_BDG_16]
+ $[id=NA_BDG_17]
+ $[id=NA_BDG_18]
+ $[id=NA_BDG_19]
+ $[id=NA_BDG_20]
+ $[id=NA_BNR_01]
+ $[id=NA_BNR_03]
+ $[id=NA_BNR_04]
+ $[id=NA_BNR_05]
+ $[id=NA_BNR_06]
+ $[id=NA_BNR_07]
+ $[id=NA_BNR_08]
+ $[id=NA_BNR_09]
+ $[id=NA_BNR_10]
+ $[id=NA_BNR_11]
+ $[id=NA_BNR_12]
+ $[id=NA_BNR_13]
+ $[id=NA_BNR_14]
+ $[id=NA_BNR_15]
+ $[id=NA_BNR_16]
+ $[id=NA_BNR_17]
+ $[id=S23_Head034]
+ $[id=S23_Legs034]
+ $[id=S23_Torso034]
+ $[id=S25_Head031]
+ $[id=S25_Head031_01]
+ $[id=S25_Head031_02]
+ $[id=S25_Head031_03]
+ $[id=S25_Legs031]
+ $[id=S25_Legs031_01]
+ $[id=S25_Legs031_02]
+ $[id=S25_Legs031_03]
+ $[id=S25_Torso031]
+ $[id=S25_Torso031_01]
+ $[id=S25_Torso031_02]
+ $[id=S25_Torso031_03]
+ $[id=S34_Head025]
+ $[id=S34_Head025_01]
+ $[id=S34_Head025_02]
+ $[id=S34_Head025_03]
+ $[id=S34_Legs025]
+ $[id=S34_Legs025_01]
+ $[id=S34_Legs025_02]
+ $[id=S34_Legs025_03]
+ $[id=S34_Torso025]
+ $[id=S34_Torso025_01]
+ $[id=S34_Torso025_02]
+ $[id=S34_Torso025_03]
+ $[id=S35_Head024]
+ $[id=S35_Legs024]
+ $[id=S35_Torso024]
+ $[id=S36_Head024]
+ $[id=S36_Legs024]
+ $[id=S36_Torso024]
+ $[id=S37_Head023]
+ $[id=S37_Head023_01]
+ $[id=S37_Legs023]
+ $[id=S37_Legs023_01]
+ $[id=S37_Torso023]
+ $[id=S37_Torso023_01]
+ $[id=S48_Head008]
+ $[id=S48_Legs008]
+ $[id=S48_Torso008]
+ $[id=S49_Torso007]
+ $[id=SK_W024]
+ $[id=US_Torso031]
+ $[id=AV_outfit_029]
+ $[id=AV_outfit_029_01]
+ $[id=AV_outfit_029_02]
+ $[id=AV_outfit_029_03]
+ $[id=CM_outfit_034]
+ $[id=CM_outfit_034_01]
+ $[id=CM_outfit_034_02]
+ $[id=CM_outfit_034_03]
+ $[id=GK_outfit_026]
+ $[id=HK_outfit_026]
+ $[id=HK_outfit_026_01]
+ $[id=HK_outfit_026_02]
+ $[id=HK_outfit_026_03]
+ $[id=HS_outfit_031]
+ $[id=K23_outfit_029]
+ $[id=K23_outfit_029_01]
+ $[id=K23_outfit_029_02]
+ $[id=K23_outfit_029_03]
+ $[id=K28_outfit_020]
+ $[id=K30_outfit_020]
+ $[id=K30_outfit_020_01]
+ $[id=K31_outfit_018]
+ $[id=K32_outfit_014]
+ $[id=K32_outfit_014_01]
+ $[id=S23_outfit_034]
+ $[id=S25_outfit_031]
+ $[id=S25_outfit_031_01]
+ $[id=S25_outfit_031_02]
+ $[id=S25_outfit_031_03]
+ $[id=S34_outfit_025]
+ $[id=S34_outfit_025_01]
+ $[id=S34_outfit_025_02]
+ $[id=S34_outfit_025_03]
+ $[id=S35_outfit_024]
+ $[id=S36_outfit_024]
+ $[id=S37_outfit_023]
+ $[id=S37_outfit_023_01]
+ $[id=S48_outfit_008]
… 12 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[384].text: "Kapitelquests"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Schließe {0} Kapitelquest(s) ab."
+ $.locText[386].text: "Verdiene {0} schillernde(s) Emblem(e)."
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Spaltpass-Quests – Woche 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Spaltpass-Quests – Woche 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Schließe {0} Prüfung(en) als ein beliebiger Killer ab."
+ $.locText[389].text: "Spaltpass-Quests – Woche 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Spaltpass-Quests – Woche 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Spuk in Dead by Daylight"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Schließe {0} Prüfung(en) als ein beliebiger Überlebender ab."
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Hake {0} Überlebende(n) als {1} fest."
+ $.locText[395].text: "Zerstöre Kürbisse."
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Hake {0} Überlebende(n) als ein beliebiger Killer fest."
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Sammle {0}-mal Leereenergie aus einer Leerekugel."
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Rette {0} Überlebende(n) als {1} sicher vom Haken."
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Rette {0} Überlebende(n) als ein beliebiger Überlebender sicher vom Haken."
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Hake {0} Überlebende(n) in der Leere fest."
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Beschädige {0} Generator(en) als {1}."
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Beschädige {0} Generator(en) als ein beliebiger Killer."
+ $.locText[404].text: "Repariere {0} Generator(en) mit einem Leerekristall."
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Repariere insgesamt {0} Generator(en) als {1}."
+ $.locText[407].text: "Öffne {0} Portal(e)."
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Repariere insgesamt {0} Generator(en) als ein beliebiger Überlebender."
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Kapitel-Abschlussquests"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "KAPITELQUESTS – WOCHE 1"
+ $.locText[410].text: "Sammle {0} Einheiten Leereenergie, indem du Überlebende niederstreckst."
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "KAPITELQUESTS – WOCHE 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[384].text: "Chapter Quests"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Complete {0} Chapter quest(s)"
+ $.locText[386].text: "Earn {0} Iridescent emblem(s)"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Rift Pass Quests - Week 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Rift Pass Quests - Week 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Complete {0} trial(s) as any Killer"
+ $.locText[389].text: "Rift Pass Quests - Week 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Rift Pass Quests - Week 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Haunted by Daylight"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Complete {0} trial(s) as any Survivor"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Hook {0} Survivor(s) as {1}"
+ $.locText[395].text: "Smash pumpkin(s)"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Hook {0} Survivor(s) as any Killer"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Collect Void Energy from a Void Orb {0} time(s)"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Safely unhook {0} Survivor(s) as {1}"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Safely unhook {0} Survivor(s) as any Survivor"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Hook {0} Survivor(s) in the Void"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Damage {0} generator(s) as {1}"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Damage {0} generator(s) as any Killer"
+ $.locText[404].text: "Repair {0} generator(s) with a Void Crystal"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Repair a total of {0} generator(s) as {1}"
+ $.locText[407].text: "Open {0} portal(s)"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Repair a total of {0} generator(s) as any Survivor"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Chapter Completion Quests"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "CHAPTER QUESTS - WEEK 1"
+ $.locText[410].text: "Collect {0} Void Energy from downing Survivors"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "CHAPTER QUESTS - WEEK 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[384].text: "Misiones de capítulo"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Completa {0} misión/misiones de capítulo."
+ $.locText[386].text: "Gana {0} emblema(s) iridiscentes"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Misiones del pase de la Grieta - Semana 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Misiones del pase de la Grieta - Semana 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Como cualquier asesino, completa {0} partida(s)."
+ $.locText[389].text: "Misiones del pase de la Grieta - Semana 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Misiones del pase de la Grieta - Semana 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Haunted By Daylight"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Como cualquier sobreviviente, completa {0} partida(s)."
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Como {1}, cuelga a {0} sobreviviente(s)."
+ $.locText[395].text: "Aplasta calabazas"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Como cualquier asesino, cuelga a {0} sobreviviente(s)."
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Obtén {0} vez/veces energía del Vacío de un orbe del Vacío"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Como {1}, descuelga de forma segura a {0} sobreviviente(s)."
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Como cualquier sobreviviente, descuelga de forma segura a {0} sobreviviente(s)."
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Cuelga a {0} sobreviviente(s) en el Vacío"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Como {1}, daña {0} generador(es)."
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Como cualquier asesino, daña {0} generador(es)."
+ $.locText[404].text: "Repara {0} generador(es) con un cristal del Vacío"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Como {1}, repara un total de {0} generador(es)."
+ $.locText[407].text: "Abre {0} portal(es)"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Como cualquier sobreviviente, repara un total de {0} generador(es)."
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Misiones de finalización de capítulo"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "MISIONES DE CAPÍTULO - SEMANA 1"
+ $.locText[410].text: "Obtén {0} de energía de Vacío al derribar sobrevivientes"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "MISIONES DE CAPÍTULO - SEMANA 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[384].text: "Misiones del capítulo"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Completa {0} misión/misiones de capítulo."
+ $.locText[386].text: "Consigue {0} emblema(s) iridiscente(s)."
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Misiones del pase de la grieta: semana 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Misiones del pase de la grieta: semana 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Completa {0} partida(s) con cualquier asesino."
+ $.locText[389].text: "Misiones del pase de la grieta: semana 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Misiones del pase de la grieta: semana 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Terror hasta el alba"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Completa {0} partida(s) con cualquier superviviente."
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Cuelga a {0} superviviente(s) con {1}."
+ $.locText[395].text: "Aplasta calabaza(s)."
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Cuelga a {0} superviviente(s) con cualquier asesino."
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Recoge energía del vacío con un orbe del vacío {0} vez/veces."
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Desengancha a {0} superviviente(s) de forma segura con {1}."
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Desengancha a {0} superviviente(s) de forma segura con cualquier superviviente."
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Cuelga a {0} superviviente(s) en el Vacío."
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Daña {0} generador(es) con {1}."
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Daña {0} generador(es) con cualquier asesino."
+ $.locText[404].text: "Repara {0} generador(es) con un cristal del vacío."
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Repara un total de {0} generador(es) con {1}."
+ $.locText[407].text: "Abre {0} portal(es)."
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Repara un total de {0} generador(es) con cualquier superviviente."
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Misiones de finalización de capítulo"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "MISIONES DEL CAPÍTULO - SEMANA 1"
+ $.locText[410].text: "Reúne {0} unidades de energía del vacío por derribar supervivientes."
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "MISIONES DEL CAPÍTULO - SEMANA 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[260].text: "Accomplissez {0} épreuve(s) en tant que : {1}."
+ $.locText[260].text: "Accomplir {0} épreuve(s) avec : {1}"
- $.locText[283].text: "Accomplissez {0} épreuve(s) en tant que : {1}."
+ $.locText[283].text: "Accomplir {0} épreuve(s) avec : {1}"
- $.locText[384].text: "Quêtes de chapitre"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Accomplissez {0} quête(s) de chapitre"
+ $.locText[386].text: "Gagner {0} emblème(s) de qualité Irisé"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Quêtes du Passe de la Faille - Semaine 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Quêtes du Passe de la Faille - Semaine 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Avec n’importe quel tueur, terminez {0} épreuve(s)"
+ $.locText[389].text: "Quêtes du Passe de la Faille - Semaine 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Quêtes du Passe de la Faille - Semaine 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Hantise en plein jour"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Avec n’importe quel survivant, terminez {0} épreuve(s)"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Avec {1}, suspendez {0} survivant(s)"
+ $.locText[395].text: "Écrasez des citrouille(s)."
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Avec n’importe quel tueur, suspendez {0} survivant(s)"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Récoltez de l'Énergie du Vide d'un Orbe du Vide {0} fois."
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Avec {1}, décrochez {0} survivant(s) de façon sécurisée"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Avec n’importe quel survivant, décrochez {0} survivant(s) de façon sécurisée"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Suspendez {0} survivant(s) dans le Vide."
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Avec {1}, endommagez {0} générateur(s)"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Avec n’importe quel tueur, endommagez {0} générateur(s)"
+ $.locText[404].text: "Réparez {0} générateur(s) avec un Cristal du Vide."
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Avec {1}, réparez {0} générateur(s) au total"
+ $.locText[407].text: "Ouvrez {0} portail(s)."
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Avec n’importe quel survivant, réparez {0} générateur(s) au total"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Quêtes d’accomplissement de chapitre"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "QUÊTES DU CHAPITRE - SEMAINE 1"
+ $.locText[410].text: "Collectez {0} unités d'Énergie du Vide en abattant des survivants."
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "QUÊTES DU CHAPITRE - SEMAINE 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[384].text: "Missioni del capitolo"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Completa {0} missione/i del capitolo"
+ $.locText[386].text: "Ottieni {0} emblema/i di qualità iridescente"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Missioni pass Spaccatura: settimana 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Missioni pass Spaccatura: settimana 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Completa {0} prova/e con qualunque killer"
+ $.locText[389].text: "Missioni pass Spaccatura: settimana 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Missioni pass Spaccatura: settimana 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Persecuzione aurorale"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Completa {0} prova/e con qualunque sopravvissuto"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Appendi al gancio {0} sopravvissuto/i con {1}"
+ $.locText[395].text: "Spacca zucche"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Appendi al gancio {0} sopravvissuto/i con qualunque killer"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Ottieni energia del Vuoto da una sfera del Vuoto {0} volta/e"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Libera dal gancio {0} sopravvissuto/i con {1}"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Libera dal gancio {0} sopravvissuto/i con qualunque sopravvissuti"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Appendi {0} sopravvissuto/i nel Vuoto"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Danneggia {0} generatore/i con {1}"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Danneggia {0} generatore/i con qualunque killer"
+ $.locText[404].text: "Ripara {0} generatore/i con un Cristallo del Vuoto"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Ripara un totale di {0} generatore/i con {1}"
+ $.locText[407].text: "Apri {0} portale/i"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Ripara un totale di {0} generatore/i con qualunque sopravvissuto"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Missioni di completamento del capitolo"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "MISSIONI CAPITOLO: SETTIMANA 1"
+ $.locText[410].text: "Ottieni {0} energia del Vuoto abbattendo sopravvissuti"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "MISSIONI CAPITOLO: SETTIMANA 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[384].text: "キャプタークエスト"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "チャプタークエストを{0}個完了する"
+ $.locText[386].text: "彩のエンブレムを{0}個獲得する"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "リフトパスクエスト - 第13週"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "リフトパスクエスト - 第14週"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "いずれかの殺人鬼で儀式を{0}回完了する"
+ $.locText[389].text: "リフトパスクエスト - 第15週"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "リフトパスクエスト - 第16週"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "ホーンテッド・バイ・デイライト"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "いずれかの生存者で儀式を{0}回完了する"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "{1}で生存者{0}人をフックに吊るす"
+ $.locText[395].text: "カボチャをたたき割る"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "いずれかの殺人鬼で生存者{0}人をフックに吊るす"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "虚無の玉から虚無エネルギーを{0}回集める"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "{1}で、生存者{0}人を安全にフックから救助する"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "いずれかの生存者で、生存者{0}人を安全にフックから救助する"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "虚無で生存者{0}人をフックに吊るす"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "{1}で発電機を{0}台破壊する"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "いずれかの殺人鬼で発電機を{0}台破壊する"
+ $.locText[404].text: "虚無クリスタルを使って発電機{0}台を修理する"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "{1}で合計{0}台の発電機を修理する"
+ $.locText[407].text: "{0}個のポータルを開ける"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "いずれかの生存者で合計{0}台の発電機を修理する"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "チャプター 完了クエスト"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "チャプタークエスト - 第1週"
+ $.locText[410].text: "生存者をダウンさせて{0}個の虚無エネルギーを集める"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "チャプタークエスト - 第2週"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[384].text: "챕터 퀘스트"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "챕터 퀘스트 {0}개 완료하기"
+ $.locText[386].text: "핏빛 엠블럼 {0}개 획득하기"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "균열 패스 퀘스트 - 13주차"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "균열 패스 퀘스트 - 14주차"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "아무 살인마로 플레이하며 희생제 {0}회 완료하기"
+ $.locText[389].text: "균열 패스 퀘스트 - 15주차"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "균열 패스 퀘스트 - 16주차"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "데이라이트의 출몰"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "아무 생존자로 플레이하며 희생제 {0}회 완료하기"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "{0}(으)로 플레이하며 갈고리에 생존자 {1}명 걸기"
+ $.locText[395].text: "호박 박살 내기"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "아무 살인마로 플레이하며 갈고리에 생존자 {0}명 걸기"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "공허한 구체에서 공허한 에너지 {0}회 수집하기"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "{1}(으)로 플레이하며 생존자 {0}명을 안전하게 갈고리에서 구출하기"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "아무 생존자로 플레이하며 생존자 {0}명을 안전하게 갈고리에서 구출하기"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "공허에서 생존자 {0}명 걸기"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "{1}(으)로 플레이하며 발전기 {0}대 손상시키기"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "아무 살인마로 플레이하며 발전기 {0}대 손상시키기"
+ $.locText[404].text: "공허한 크리스탈로 발전기 {0}대 수리하기"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "{1}(으)로 플레이하며 총 {0}개의 발전기 수리하기"
+ $.locText[407].text: "포털 {0}회 열기"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "아무 생존자로 플레이하며 총 {0}개의 발전기 수리하기"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "챕터 완료 퀘스트"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "균열 패스 퀘스트 - 1주차"
+ $.locText[410].text: "생존자를 빈사 상태에 빠뜨려 공허한 에너지 {0}개 수집하기"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "균열 패스 퀘스트 - 2주차"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[384].text: "Zadania rozdziału"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Ukończ tyle zadań rozdziału: {0}"
+ $.locText[386].text: "Zdobądź tyle opalizujących emblematów: {0}"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Zadania przepustki szczelinowej – tydzień 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Zadania przepustki szczelinowej – tydzień 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Jako dowolny zabójca ukończ tyle prób: {0}"
+ $.locText[389].text: "Zadania przepustki szczelinowej – tydzień 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Zadania Przepustki Szczelinowej – tydzień 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Haunted By Daylight"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Jako dowolny ocalały ukończ tyle prób: {0}"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Jako {1} powieś na haku tylu ocalałych: {0}"
+ $.locText[395].text: "Rozbij dynie"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Jako dowolny zabójca powieś na haku tylu ocalałych: {0}"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Zbierz energię pustki z kuli pustki tyle razy: {0}"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Jako {1} bezpiecznie zdejmij z haka tylu ocalałych: {0}"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Jako dowolny ocalały bezpiecznie zdejmij z haka tylu ocalałych: {0}"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Powieś tylu ocalałych na haku w pustce: {0}"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Jako {1} uszkodź tyle generatorów: {0}"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Jako dowolny zabójca uszkodź tyle generatorów: {0}"
+ $.locText[404].text: "Napraw tyle generatorów za pomocą kryształu pustki: {0}"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Jako {1} napraw łącznie tyle generatorów: {0}"
+ $.locText[407].text: "Otwórz tyle portali: {0}"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Jako dowolny ocalały napraw łącznie tyle generatorów: {0}"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Zadania ukończenia rozdziału"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "ZADANIA ROZDZIAŁU – TYDZIEŃ 1"
+ $.locText[410].text: "Zbierz tyle energii pustki z powalania ocalałych: {0}"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "ZADANIA ROZDZIAŁU – TYDZIEŃ 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[384].text: "Missões do Capítulo"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Complete {0} missão(ões) do Capítulo"
+ $.locText[386].text: "Obtenha {0} emblema(s) de qualidade Iridescente"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Missões do Passe da Fenda - Semana 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Missões do Passe da Fenda - Semana 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Complete {0} partida(s) com qualquer Assassino"
+ $.locText[389].text: "Missões do Passe da Fenda - Semana 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Missões do Passe da Fenda - Semana 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Assombrados até a Aurora"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Complete {0} partida(s) com qualquer Sobrevivente"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Enganche {0} Sobrevivente(s) como {1}"
+ $.locText[395].text: "Destrua abóbora(s)"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Enganche {0} Sobrevivente(s) com qualquer Assassino"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Colete Energia do Vácuo de um Orbe do Vácuo {0} vez(es)"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Desenganche {0} Sobrevivente(s) com segurança como {1}"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Desenganche {0} Sobrevivente(s) com segurança com qualquer Sobrevivente"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Enganche {0} Sobrevivente(s) no Vácuo"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Danifique {0} gerador(es) como {1}"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Danifique {0} gerador(es) com qualquer Assassino"
+ $.locText[404].text: "Repare {0} gerador(es) com um Cristal do Vácuo"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Repare um total de {0} gerador(es) como {1}"
+ $.locText[407].text: "Abra {0} portal(is)"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Repare um total de {0} gerador(es) como qualquer Sobrevivente"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Missões de Conclusão do Capítulo"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "MISSÕES DO CAPÍTULO - SEMANA 1"
+ $.locText[410].text: "Colete {0} de Energia do Vácuo derrubando Sobreviventes"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "MISSÕES DO CAPÍTULO - SEMANA 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[384].text: "Задания главы"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "Выполните задания главы ({0} шт.)"
+ $.locText[386].text: "{0} раз(а) получите золотую эмблему радуги"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Задания билета разрыва (13-я неделя)"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Задания билета разрыва (14-я неделя)"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Завершите матч {0} раз(а), играя за любого убийцу"
+ $.locText[389].text: "Задания билета разрыва (15-я неделя)"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Задания билета разрыва (16-я неделя)"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Haunted by Daylight"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Завершите матч {0} раз(а), играя за любого выжившего"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "Как {1}, повесьте на крюк выживших ({0} чел.)"
+ $.locText[395].text: "Раздавите тыквы"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Повесьте на крюк выживших ({0} чел.), играя за любого убийцу"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "{0} раз(а) заберите пустотную энергию из сферы Пустоты"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "Как {1}, {0} раз(а) снимите выжившего с крюка"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "{0} раз(а) снимите выжившего с крюка, играя за любого выжившего"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "Повесьте выживших ({0} чел.) на крюки в Пустоте"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "Как {1}, повредите генераторы ({0} шт.)"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Повредите генераторы ({0} шт.), играя за любого убийцу"
+ $.locText[404].text: "Почините генератор кристаллом Пустоты {0} раз(а)"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "Как {1}, почините генераторы, в общей сложности {0} шт."
+ $.locText[407].text: "Откройте портал {0} раз(а)"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Почините генераторы, в общей сложности {0} шт., играя за любого выжившего"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Задания завершения главы"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "ЗАДАНИЯ ГЛАВЫ — НЕДЕЛЯ 1"
+ $.locText[410].text: "Накопите {0} ед. пустотной энергии, смертельно ранив выживших"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "ЗАДАНИЯ ГЛАВЫ — НЕДЕЛЯ 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[384].text: "เควสต์ประจำบท"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "พิชิตเควสต์ประจำบท {0} เควสต์"
+ $.locText[386].text: "ได้รับตราสีรุ้ง{0} ชิ้น"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "เควสต์บัตรผ่านรอยแยก - สัปดาห์ที่ 13"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "เควสต์บัตรผ่านรอยแยก - สัปดาห์ที่ 14"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "จบ {0} เกมโดยเล่นเป็นฆาตกรคนใดก็ได้"
+ $.locText[389].text: "เควสต์บัตรผ่านรอยแยก - สัปดาห์ที่ 15"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "เควสต์บัตรผ่านรอยแยก - สัปดาห์ที่ 16"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "ทิวาหลอน"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "จบ {0} เกมโดยเล่นเป็นผู้รอดชีวิตคนใดก็ได้"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "จับผู้รอดชีวิตแขวนบนตะขอ {0} คนโดยเล่นเป็น{1}"
+ $.locText[395].text: "ทุบฟักทอง"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "จับผู้รอดชีวิตแขวนบนตะขอ {0} คนโดยเล่นเป็นฆาตกรคนใดก็ได้"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "เก็บพลังงานความว่างเปล่าจากลูกแก้วว่างเปล่า {0} ครั้ง"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "ปลดผู้รอดชีวิตลงจากตะขออย่างปลอดภัย {0} คนโดยเล่นเป็น{1}"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "ปลดผู้รอดชีวิตลงจากตะขออย่างปลอดภัย {0} คนโดยเล่นเป็นผู้รอดชีวิตคนใดก็ได้"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "จับผู้รอดชีวิตแขวนบนตะขอในความว่างเปล่า {0} คน"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "ทำความเสียหายให้เครื่องปั่นไฟ {0} เครื่องโดยเล่นเป็น{1}"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "ทำความเสียหายให้เครื่องปั่นไฟ {0} เครื่องโดยเล่นเป็นฆาตกรคนใดก็ได้"
+ $.locText[404].text: "ใช้คริสตัลความว่างเปล่าซ่อมแซมเครื่องปั่นไฟ {0} เครื่อง"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "ซ่อมแซมเครื่องปั่นไฟรวม {0} เครื่องโดยเล่นเป็น{1}"
+ $.locText[407].text: "เปิดประตูมิติ {0} บาน"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "ซ่อมแซมเครื่องปั่นไฟรวม {0} เครื่องโดยเล่นเป็นผู้รอดชีวิตคนใดก็ได้"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "การพิชิตเควสต์ประจำบท"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "เควสต์ประจำบท - สัปดาห์ที่ 1"
+ $.locText[410].text: "เก็บพลังงานความว่างเปล่า {0} หน่วยจากการตีผู้รอดชีวิตให้ล้มลง"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "เควสต์ประจำบท - สัปดาห์ที่ 2"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[384].text: "Bölüm Görevleri"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "{0} Bölüm görevi tamamla."
+ $.locText[386].text: "{0} Parıltılı arma kazan."
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "Yarık Bileti Görevleri - 13. Hafta"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "Yarık Bileti Görevleri - 14. Hafta"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "Herhangi bir Katil olarak {0} mücadele tamamla."
+ $.locText[389].text: "Yarık Bileti Görevleri - 15. Hafta"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "Yarık Bileti Görevleri - 16. Hafta"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "Haunted By Daylight"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "Herhangi bir Kurban olarak {0} mücadele tamamla."
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "{1} olarak {0} Kurban'ı kancaya as."
+ $.locText[395].text: "Balkabağı ez"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "Herhangi bir Katil olarak {0} Kurban'ı kancaya as."
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "Bir Hiçlik Küresinden {0} kez Hiçlik Enerjisi topla."
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "{1} olarak {0} Kurban'ı güvenle kancadan kurtar."
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "Herhangi bir Kurban olarak {0} Kurban'ı güvenle kancadan kurtar."
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "{0} Kurban'ı Hiçlik'te kancaya as."
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "{1} olarak {0} jeneratöre hasar ver."
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "Herhangi bir Katil olarak {0} jeneratöre hasar ver."
+ $.locText[404].text: "Hiçlik Kristali kullanarak {0} jeneratör onar."
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "{1} olarak toplam {0} jeneratör tamir et."
+ $.locText[407].text: "{0} geçit aç."
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "Herhangi bir Kurban olarak toplam {0} jeneratör tamir et."
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "Bölüm Tamamlama Görevleri"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "BÖLÜM GÖREVLERİ - 1. HAFTA"
+ $.locText[410].text: "Kurbanları yere düşürerek {0} Hiçlik Enerjisi topla."
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "BÖLÜM GÖREVLERİ - 2. HAFTA"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[384].text: "章节任务"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "完成{0}个章节任务"
+ $.locText[386].text: "获得{0}块荧虹徽章"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "裂隙通行证任务 - 第13周"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "裂隙通行证任务 - 第14周"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "扮演任意杀手，完成{0}场对局"
+ $.locText[389].text: "裂隙通行证任务 - 第15周"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "裂隙通行证任务 - 第16周"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "黎明鬼祟"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "扮演任意逃生者，完成{0}场对局"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "扮演{1}，钩住{0}名逃生者"
+ $.locText[395].text: "砸烂南瓜"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "扮演任意杀手，钩住{0}名逃生者"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "从虚空能量球中收集虚空能量{0}次"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "扮演{1}，安全解救{0}名逃生者"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "扮演任意逃生者，安全解救{0}名逃生者"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "在虚空钩住{0}名逃生者"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "扮演{1}，破坏{0}台发电机"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "扮演任意杀手，破坏{0}台发电机"
+ $.locText[404].text: "使用虚空水晶修理{0}台发电机"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "扮演{1}，累计修理{0}台发电机"
+ $.locText[407].text: "开启{0}个传送门"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "扮演任意逃生者，累计修理{0}台发电机"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "章节完成度任务"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "章节任务 - 第1周"
+ $.locText[410].text: "通过击倒逃生者收集{0}虚空能量"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "章节任务 - 第2周"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[384].text: "章節任務"
+ $.locText[384].text: "@#CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[384].textId: "CHALLENGESET_ChapterQuests_TITLE"
+ $.locText[384].textId: "CHALLENGE_EarnEmblemsIridescent_TITLE"
- $.locText[385].text: "@#CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].text: "@#CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[385].textId: "CHALLENGESET_ChapterQuests_INFO"
+ $.locText[385].textId: "CHALLENGE_EarnEmblemsIridescent_DESC"
- $.locText[386].text: "完成{0}項章節任務"
+ $.locText[386].text: "獲得{0}個白銀虹彩徽章"
- $.locText[386].textId: "CHALLENGE_CompleteChapterQuests_INFO"
+ $.locText[386].textId: "CHALLENGE_EarnEmblemsIridescent_INFO"
- $.locText[387].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].text: "裂縫通行證任務 - 第13週"
- $.locText[387].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_TITLE"
+ $.locText[387].textId: "LIST_BattlePass_TITLE_13"
- $.locText[388].text: "@#CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].text: "裂縫通行證任務 - 第14週"
- $.locText[388].textId: "CHALLENGE_PlayAsKillerOrAnyKiller_DESC"
+ $.locText[388].textId: "LIST_BattlePass_TITLE_14"
- $.locText[389].text: "扮演任一殺手，完成{0}場遊戲"
+ $.locText[389].text: "裂縫通行證任務 - 第15週"
- $.locText[389].textId: "CHALLENGE_PlayAnyKiller_INFO"
+ $.locText[389].textId: "LIST_BattlePass_TITLE_15"
- $.locText[390].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].text: "裂縫通行證任務 - 第16週"
- $.locText[390].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[390].textId: "LIST_BattlePass_TITLE_16"
- $.locText[391].text: "@#CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].text: "黎明鬧鬼"
- $.locText[391].textId: "CHALLENGE_PlayAsSurvivorOrAnySurvivor_DESC"
+ $.locText[391].textId: "CHALLENGESET_Halloween_TITLE"
- $.locText[392].text: "扮演任一倖存者，完成{0}場遊戲"
+ $.locText[392].text: "@#CHALLENGESET_Halloween_INFO"
- $.locText[392].textId: "CHALLENGE_PlayAnySurvivor_INFO"
+ $.locText[392].textId: "CHALLENGESET_Halloween_INFO"
- $.locText[393].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].text: "@#CHALLENGE_SmashPumpkins_TITLE"
- $.locText[393].textId: "CHALLENGE_HookAsKillerOrAnyKiller_TITLE"
+ $.locText[393].textId: "CHALLENGE_SmashPumpkins_TITLE"
- $.locText[394].text: "@#CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].text: "@#CHALLENGE_SmashPumpkins_DESC"
- $.locText[394].textId: "CHALLENGE_HookAsKillerOrAnyKiller_DESC"
+ $.locText[394].textId: "CHALLENGE_SmashPumpkins_DESC"
- $.locText[395].text: "扮演{1}，把{0}個倖存者掛上鉤子"
+ $.locText[395].text: "砸爛南瓜"
- $.locText[395].textId: "CHALLENGE_HookAsKiller_INFO"
+ $.locText[395].textId: "CHALLENGE_CommunitySmashPumpkins_INFO"
- $.locText[396].text: "扮演任一殺手，把{0}個倖存者掛上鉤子"
+ $.locText[396].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[396].textId: "CHALLENGE_HookAsAnyKiller_INFO"
+ $.locText[396].textId: "CHALLENGE_CollectVoidEnergyFromOrb_TITLE"
- $.locText[397].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].text: "@#CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[397].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[397].textId: "CHALLENGE_CollectVoidEnergyFromOrb_DESC"
- $.locText[398].text: "@#CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].text: "從虛空靈球蒐集虛空能量{0}次"
- $.locText[398].textId: "CHALLENGE_UnhookAsSurvivorOrAnySurvivor_DESC"
+ $.locText[398].textId: "CHALLENGE_CollectVoidEnergyFromOrb_INFO"
- $.locText[399].text: "扮演{1}，將{0}名倖存者平安救下鉤子"
+ $.locText[399].text: "@#CHALLENGE_HookInVoidMap_TITLE"
- $.locText[399].textId: "CHALLENGE_UnhookAsSurvivor_INFO"
+ $.locText[399].textId: "CHALLENGE_HookInVoidMap_TITLE"
- $.locText[400].text: "扮演任一倖存者，將{0}名倖存者平安救下鉤子"
+ $.locText[400].text: "@#CHALLENGE_HookInVoidMap_DESC"
- $.locText[400].textId: "CHALLENGE_UnhookAsAnySurvivor_INFO"
+ $.locText[400].textId: "CHALLENGE_HookInVoidMap_DESC"
- $.locText[401].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].text: "在虛空內把{0}個倖存者掛上鉤子"
- $.locText[401].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_TITLE"
+ $.locText[401].textId: "CHALLENGE_HookInVoidMap_INFO"
- $.locText[402].text: "@#CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].text: "@#CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[402].textId: "CHALLENGE_BreakGenAsKillerOrAnyKiller_DESC"
+ $.locText[402].textId: "CHALLENGE_RepairGenWithVoidCrystal_TITLE"
- $.locText[403].text: "扮演{1}，破壞{0}台發電機"
+ $.locText[403].text: "@#CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[403].textId: "CHALLENGE_BreakGenAsKiller_INFO"
+ $.locText[403].textId: "CHALLENGE_RepairGenWithVoidCrystal_DESC"
- $.locText[404].text: "扮演任一殺手，破壞{0}台發電機"
+ $.locText[404].text: "使用虛空水晶修理{0}台發電機"
- $.locText[404].textId: "CHALLENGE_BreakGensAnyKiller_INFO"
+ $.locText[404].textId: "CHALLENGE_RepairGenWithVoidCrystal_INFO"
- $.locText[405].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].text: "@#CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[405].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_TITLE"
+ $.locText[405].textId: "CHALLENGE_OpenVoidPortal_TITLE"
- $.locText[406].text: "@#CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].text: "@#CHALLENGE_OpenVoidPortal_DESC"
- $.locText[406].textId: "CHALLENGE_RepairGenAsSurvivorOrAnySurvivor_DESC"
+ $.locText[406].textId: "CHALLENGE_OpenVoidPortal_DESC"
- $.locText[407].text: "扮演{1}，總共修復{0}台發電機"
+ $.locText[407].text: "打開{0}扇傳送門"
- $.locText[407].textId: "CHALLENGE_RepairGenAsSurvivor_INFO"
+ $.locText[407].textId: "CHALLENGE_OpenVoidPortal_INFO"
- $.locText[408].text: "扮演任一倖存者，總共修復{0}台發電機"
+ $.locText[408].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[408].textId: "CHALLENGE_RepairGenAnySurvivor_INFO"
+ $.locText[408].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_TITLE"
- $.locText[409].text: "章節通關任務"
+ $.locText[409].text: "@#CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[409].textId: "LIST_OverarchingChapterQuests_TITLE"
+ $.locText[409].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_DESC"
- $.locText[410].text: "章節任務 - 第1週"
+ $.locText[410].text: "從被擊倒的倖存者身上收集{0}點虛空能量"
- $.locText[410].textId: "LIST_ChapterQuests_TITLE_1"
+ $.locText[410].textId: "CHALLENGE_CollectVoidEnergyFromSurvivor_INFO"
- $.locText[411].text: "章節任務 - 第2週"
+ $.locText[411].text: "@#CHALLENGE_CraftVoidCrystal_TITLE"
- $.locText[411].textId: "LIST_ChapterQuests_TITLE_2"
+ $.locText[411].textId: "CHALLENGE_CraftVoidCrystal_TITLE"
+ $.locText[412]
+ $.locText[413]
+ $.locText[414]
+ $.locText[415]
+ $.locText[416]
+ $.locText[417]
+ $.locText[418]
+ $.locText[419]
+ $.locText[420]
+ $.locText[421]
+ $.locText[422]
+ $.locText[423]
+ $.locText[424]
+ $.locText[425]
+ $.locText[426]
+ $.locText[427]
+ $.locText[428]
+ $.locText[429]
+ $.locText[430]
+ $.locText[431]
+ $.locText[432]
+ $.locText[433]
+ $.locText[434]
+ $.locText[435]
+ $.locText[436]
+ $.locText[437]
+ $.locText[438]
+ $.locText[439]
+ $.locText[440]
+ $.locText[441]
+ $.locText[442]
+ $.locText[443]
+ $.locText[444]
+ $.locText[445]
+ $.locText[446]
+ $.locText[447]
+ $.locText[448]
+ $.locText[449]
+ $.locText[450]
+ $.locText[451]
+ $.locText[452]
+ $.locText[453]
+ $.locText[454]
+ $.locText[455]
+ $.locText[456]
+ $.locText[457]
+ $.locText[458]
+ $.locText[459]
+ $.locText[460]
```

### [`challengeRewardTrackers.json`](challengeRewardTrackers.json)

[Full line-by-line diff](diffs/challengeRewardTrackers.json.diff)

```diff
+ $.Rift_03
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
+ $.Halloween_2025_Set
+ $.Rift_03_QuestSet
- $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingKiller_Community.maxProgressionPerPlayer: 1000000
+ $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingKiller_Community.maxProgressionPerPlayer: 80000000
- $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingKiller_Community.neededProgression[]: 1000000
+ $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingKiller_Community.neededProgression[]: 80000000
- $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingSurvivor_Community.maxProgressionPerPlayer: 1000000
+ $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingSurvivor_Community.maxProgressionPerPlayer: 80000000
- $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingSurvivor_Community.neededProgression[]: 1000000
+ $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_PlayAnyKillerOrPlayAnySurvivor].objectives.FinishedPlayingSurvivor_Community.neededProgression[]: 80000000
- $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_CompleteModeQuests].objectives.Overarching_Community.maxProgressionPerPlayer: 5000000
+ $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_CompleteModeQuests].objectives.Overarching_Community.maxProgressionPerPlayer: 70000000
- $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_CompleteModeQuests].objectives.Overarching_Community.neededProgression[]: 5000000
+ $.DbdDay_2025_Set.challengeList[0].challenges[id=DbdDay_2025_Set-DbbDay_CommunityQuests-C_CompleteModeQuests].objectives.Overarching_Community.neededProgression[]: 70000000
- $.DbdDay_2025_Set.challengeList[0].endDate: "2025-10-18T15:00:00"
+ $.DbdDay_2025_Set.challengeList[0].endDate: "2025-10-20T15:00:00"
- $.DbdDay_2025_Set.challengeList[1].endDate: "2025-10-18T15:00:00"
+ $.DbdDay_2025_Set.challengeList[1].endDate: "2025-10-20T15:00:00"
- $.DbdDay_2025_Set.challengeList[2].endDate: "2025-10-18T15:00:00"
+ $.DbdDay_2025_Set.challengeList[2].endDate: "2025-10-20T15:00:00"
- $.DbdDay_2025_Set.endDate: "2025-10-18T15:00:00"
+ $.DbdDay_2025_Set.endDate: "2025-10-20T15:00:00"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[30].limitedAvailabilityStartDate: "2025-10-14T15:00:00Z"
+ $.collections[30].visibleBeforeStartDate: false
- $.collections[30].collectionId: "HookedOnYou"
+ $.collections[30].collectionId: "VoidTouched"
- $.collections[30].collectionTitle.de: "Hooked on You"
+ $.collections[30].collectionTitle.de: "Die Leere"
- $.collections[30].collectionTitle.en: "Hooked on You"
+ $.collections[30].collectionTitle.en: "The Void"
- $.collections[30].collectionTitle.es: "Hooked on You"
+ $.collections[30].collectionTitle.es: "El Vacío"
- $.collections[30].collectionTitle["es-MX"]: "Hooked on You"
+ $.collections[30].collectionTitle["es-MX"]: "El Vacío"
- $.collections[30].collectionTitle.fr: "Hooked on You"
+ $.collections[30].collectionTitle.fr: "Le Vide"
- $.collections[30].collectionTitle.it: "Hooked on You"
+ $.collections[30].collectionTitle.it: "Il Vuoto"
- $.collections[30].collectionTitle.ja: "Hooked on You"
+ $.collections[30].collectionTitle.ja: "虚無"
- $.collections[30].collectionTitle.ko: "Hooked on You"
+ $.collections[30].collectionTitle.ko: "보이드"
- $.collections[30].collectionTitle.pl: "Hooked On You"
+ $.collections[30].collectionTitle.pl: "Pustka"
- $.collections[30].collectionTitle["pt-BR"]: "Hooked on You"
+ $.collections[30].collectionTitle["pt-BR"]: "O Vácuo"
- $.collections[30].collectionTitle.ru: "На твоем крючке"
+ $.collections[30].collectionTitle.ru: "Пустота"
- $.collections[30].collectionTitle.th: "Hooked on You"
+ $.collections[30].collectionTitle.th: "ความว่างเปล่า"
- $.collections[30].collectionTitle.tr: "Sana Tutuldum"
+ $.collections[30].collectionTitle.tr: "Hiçlik"
- $.collections[30].collectionTitle["zh-Hans"]: "心醉魂迷"
+ $.collections[30].collectionTitle["zh-Hans"]: "虚空"
- $.collections[30].collectionTitle["zh-Hant"]: "《鉤魂迷戀》"
+ $.collections[30].collectionTitle["zh-Hant"]: "虛空"
- $.collections[30].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_HookedOnYou.T_UI_CollectionBanner_HookedOnYou"
+ $.collections[30].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Fudge/T_UI_CollectionBanner_Void_BC.T_UI_CollectionBanner_Void_BC"
- $.collections[30].items[]: "BE_outfit_017"
- $.collections[30].items[]: "CM_outfit_021"
- $.collections[30].items[]: "DF_outfit_023"
- $.collections[30].items[]: "HK_outfit_017"
- $.collections[30].items[]: "K23_outfit_014"
+ $.collections[30].items[]: "DK_outfit_019"
+ $.collections[30].items[]: "GS_outfit_033"
+ $.collections[30].items[]: "HS_outfit_025"
+ $.collections[30].items[]: "MK_outfit_017"
+ $.collections[30].items[]: "S25_outfit_019"
+ $.collections[30].items[]: "S31_outfit_013"
+ $.collections[30].items[]: "US_outfit_025"
- $.collections[30].sortOrder: "-19"
+ $.collections[30].sortOrder: "-173"
- $.collections[30].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[30].updatedDate: "2024-09-19T19:13:53Z"
+ $.collections[31].limitedAvailabilityEndDate: "2025-11-04T15:00:00Z"
+ $.collections[31].limitedAvailabilityStartDate: "2025-10-14T15:00:00Z"
+ $.collections[31].visibleAfterEndDate: false
+ $.collections[31].visibleBeforeStartDate: false
- $.collections[31].collectionId: "GrimMatsuri"
+ $.collections[31].collectionId: "MidnightGrove"
- $.collections[31].collectionTitle.de: "Düsteres Matsuri-Fest"
+ $.collections[31].collectionTitle.de: "Der Mitternachtshain"
- $.collections[31].collectionTitle.en: "Grim Matsuri"
+ $.collections[31].collectionTitle.en: "The Midnight Grove"
- $.collections[31].collectionTitle.es: "Matsuri tenebrosa"
+ $.collections[31].collectionTitle.es: "Arboleda de medianoche"
- $.collections[31].collectionTitle["es-MX"]: "Matsuri tenebrosa"
+ $.collections[31].collectionTitle["es-MX"]: "El bosque nocturno"
- $.collections[31].collectionTitle.fr: "Matsuri sinistre"
+ $.collections[31].collectionTitle.fr: "Le Bosquet de minuit"
- $.collections[31].collectionTitle.it: "Matsuri funebre"
+ $.collections[31].collectionTitle.it: "Bosco notturno"
- $.collections[31].collectionTitle.ja: "おぞましい祭り"
+ $.collections[31].collectionTitle.ja: "真夜中の森"
- $.collections[31].collectionTitle.ko: "음산한 축제"
+ $.collections[31].collectionTitle.ko: "자정의 숲"
- $.collections[31].collectionTitle.pl: "Ponury Festiwal"
+ $.collections[31].collectionTitle.pl: "Północny gaj"
- $.collections[31].collectionTitle["pt-BR"]: "Festival Japonês Sombrio"
+ $.collections[31].collectionTitle["pt-BR"]: "O Bosque da Meia-Noite"
- $.collections[31].collectionTitle.ru: "Мрачный Мацури"
+ $.collections[31].collectionTitle.ru: "Полуночная роща"
- $.collections[31].collectionTitle.th: "เทศกาลสยอง"
+ $.collections[31].collectionTitle.th: "สวนเที่ยงคืน"
- $.collections[31].collectionTitle.tr: "Kasvetli Festival"
+ $.collections[31].collectionTitle.tr: "Gece Yarısı Korusu"
- $.collections[31].collectionTitle["zh-Hans"]: "冷血祭"
+ $.collections[31].collectionTitle["zh-Hans"]: "午夜林地"
- $.collections[31].collectionTitle["zh-Hant"]: "冷血祭"
+ $.collections[31].collectionTitle["zh-Hant"]: "午夜樹林"
- $.collections[31].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GrimMatsuri.T_UI_CollectionBanner_GrimMatsuri"
+ $.collections[31].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_MidnightGrove_BC.T_UI_CollectionBanner_MidnightGrove_BC"
- $.collections[31].inclusionVersion: "7.7.0 PTB"
+ $.collections[31].inclusionVersion: "8.3.0"
- $.collections[31].items[]: "Bear_outfit_003"
- $.collections[31].items[]: "Claudette_outfit_018"
- $.collections[31].items[]: "GS_outfit_011"
- $.collections[31].items[]: "Jake_outfit_017"
- $.collections[31].items[]: "Meg_outfit_023"
- $.collections[31].items[]: "Nea_outfit_010"
- $.collections[31].items[]: "SwedenSurvivor_outfit_009"
- $.collections[31].items[]: "TN_outfit_010"
+ $.collections[31].items[]: "AV_outfit_010_01"
+ $.collections[31].items[]: "DF_outfit_005_01"
+ $.collections[31].items[]: "DO_outfit_013"
+ $.collections[31].items[]: "FM_outfit_01_06"
+ $.collections[31].items[]: "GK_outfit_02_04"
+ $.collections[31].items[]: "KS_outfit_008_01"
+ $.collections[31].items[]: "S28_outfit_007"
+ $.collections[31].items[]: "TR_outfit_01_04"
+ $.collections[31].items[]: "TW_outfit_007_01"
- $.collections[31].sortOrder: "-2"
+ $.collections[31].sortOrder: "-174"
- $.collections[31].updatedDate: "2024-03-06T20:44:22Z"
+ $.collections[31].updatedDate: "2024-09-19T16:10:17Z"
+ $.collections[32].limitedAvailabilityEndDate: "2025-11-04T15:00:00Z"
+ $.collections[32].limitedAvailabilityStartDate: "2025-10-14T15:00:00Z"
+ $.collections[32].visibleAfterEndDate: false
+ $.collections[32].visibleBeforeStartDate: false
- $.collections[32].collectionId: "AliceInWonderland"
+ $.collections[32].collectionId: "TricksAndTreats"
- $.collections[32].collectionTitle.de: "Alice im Wunderland"
+ $.collections[32].collectionTitle.de: "Süßes und Saures"
- $.collections[32].collectionTitle.en: "Alice in Wonderland"
+ $.collections[32].collectionTitle.en: "Tricks and Treats"
- $.collections[32].collectionTitle.es: "Alicia en el País de las Maravillas"
+ $.collections[32].collectionTitle.es: "Trucos y tratos"
- $.collections[32].collectionTitle["es-MX"]: "Alicia en el País de las Maravillas"
+ $.collections[32].collectionTitle["es-MX"]: "Dulces y travesuras"
- $.collections[32].collectionTitle.fr: "Alice au pays des merveilles"
+ $.collections[32].collectionTitle.fr: "Farces et friandises"
- $.collections[32].collectionTitle.it: "Alice nel paese delle meraviglie"
+ $.collections[32].collectionTitle.it: "Dolcetti e scherzetti"
- $.collections[32].collectionTitle.ja: "不思議の国のアリス"
+ $.collections[32].collectionTitle.ja: "トリックとトリート"
- $.collections[32].collectionTitle.ko: "이상한 나라의 앨리스"
+ $.collections[32].collectionTitle.ko: "장난과 과자"
- $.collections[32].collectionTitle.pl: "Alicja w Krainie Czarów"
+ $.collections[32].collectionTitle.pl: "Cukierki i psikusy"
- $.collections[32].collectionTitle["pt-BR"]: "Alice no País das Maravilhas"
+ $.collections[32].collectionTitle["pt-BR"]: "Gostosuras e Travessuras"
- $.collections[32].collectionTitle.ru: "Алиса в Стране чудес"
+ $.collections[32].collectionTitle.ru: "Гадости и сладости"
- $.collections[32].collectionTitle.th: "อลิซในแดนมหัศจรรย์"
+ $.collections[32].collectionTitle.th: "ทริกส์ออร์ทรีตส์"
- $.collections[32].collectionTitle.tr: "Alice Harikalar Diyarında"
+ $.collections[32].collectionTitle.tr: "Şekerler ve Şakalar"
- $.collections[32].collectionTitle["zh-Hans"]: "爱丽丝梦游仙境收藏"
+ $.collections[32].collectionTitle["zh-Hans"]: "糖果与捣蛋"
- $.collections[32].collectionTitle["zh-Hant"]: "《愛麗絲夢遊仙境》"
+ $.collections[32].collectionTitle["zh-Hant"]: "搗蛋有禮"
- $.collections[32].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AliceInWonderland.T_UI_CollectionBanner_AliceInWonderland"
+ $.collections[32].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Fudge/T_UI_CollectionBanner_TricksAndTreats_BC.T_UI_CollectionBanner_TricksAndTreats_BC"
- $.collections[32].items[]: "AV_outfit_018"
- $.collections[32].items[]: "BE_outfit_020"
- $.collections[32].items[]: "GS_outfit_023"
- $.collections[32].items[]: "K26_outfit_011"
- $.collections[32].items[]: "NK_outfit_023"
+ $.collections[32].items[]: "AV_Torso025"
+ $.collections[32].items[]: "BE_W023"
+ $.collections[32].items[]: "CM_outfit_025"
+ $.collections[32].items[]: "CM_Torso008_01"
+ $.collections[32].items[]: "DF_outfit_022"
+ $.collections[32].items[]: "DK_Torso006_01"
+ $.collections[32].items[]: "DO_W015"
+ $.collections[32].items[]: "FM_outfit_028"
+ $.collections[32].items[]: "FM_Torso01_06"
+ $.collections[32].items[]: "GK_W017"
+ $.collections[32].items[]: "GS_outfit_021"
+ $.collections[32].items[]: "GS_Torso018_01"
+ $.collections[32].items[]: "HK_W023"
+ $.collections[32].items[]: "JP_outfit_021"
+ $.collections[32].items[]: "K21_W019"
+ $.collections[32].items[]: "K22_W009"
+ $.collections[32].items[]: "K23_outfit_025"
+ $.collections[32].items[]: "K26_W016"
+ $.collections[32].items[]: "K28_W012"
+ $.collections[32].items[]: "K30_outfit_011"
+ $.collections[32].items[]: "K30_W015"
+ $.collections[32].items[]: "K32_W011"
+ $.collections[32].items[]: "K35_W009"
+ $.collections[32].items[]: "KK_W030"
+ $.collections[32].items[]: "MK_W012"
+ $.collections[32].items[]: "MS_outfit_018"
+ $.collections[32].items[]: "MS_Torso007_01"
+ $.collections[32].items[]: "MT_outfit_027"
+ $.collections[32].items[]: "MT_Torso031"
+ $.collections[32].items[]: "NK_Torso019_01"
+ $.collections[32].items[]: "S23_Torso009_01"
+ $.collections[32].items[]: "S24_Torso007_01"
+ $.collections[32].items[]: "S25_outfit_027"
+ $.collections[32].items[]: "S25_Torso012_01"
+ $.collections[32].items[]: "S28_outfit_028"
+ $.collections[32].items[]: "S28_Torso008_02"
+ $.collections[32].items[]: "S29_Torso019"
+ $.collections[32].items[]: "S31_Torso008_01"
+ $.collections[32].items[]: "S34_Torso008_01"
+ $.collections[32].items[]: "S35_Torso018"
+ $.collections[32].items[]: "S36_Torso019"
+ $.collections[32].items[]: "S37_Torso017"
+ $.collections[32].items[]: "S41_outfit_012"
+ $.collections[32].items[]: "SwedenSurvivor_Torso010_01"
… 2062 more change(s) — see the commit diff for everything
```

### [`consents/eula/v4/en.json`](consents/eula/v4/en.json)

[Full line-by-line diff](diffs/consents/eula/v4/en.json.diff)

```diff
- $[id=eula].versions[0].content.en: "END USER LICENCE AGREEMENT \n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE …
+ $[id=eula].versions[0].content.en: "END USER LICENCE AGREEMENT \n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE …
```

### [`consents/eula_psn_eu/v5/en.json`](consents/eula_psn_eu/v5/en.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/en.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
+ $[id=eula_psn_eu].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
```

### [`consents/eula_psn_na/v5/en.json`](consents/eula_psn_na/v5/en.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/en.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
+ $[id=eula_psn_na].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "2da896be9c99475af3cac1bf5b35e3d2835cf227"
+ $.entries[0].contentVersion: "300916bd34af0919914af1be14cb8e626389ce25"
- $.entries[0].downloadStrategy: "preferRemote"
+ $.entries[0].downloadStrategy: "preferPackaged"
- $.entries[0].enableChecksum: true
+ $.entries[0].enableChecksum: false
- $.entries[0].packagedPath: ""
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_Specialpack_HauntedByDaylight2024.T_UI_Specialpack_HauntedByDaylight2024"
- $.entries[0].schema: "s3ver://"
+ $.entries[0].schema: "s3verbin://"
- $.entries[0].uri: "catalog.json"
+ $.entries[0].uri: "images/T_UI_Specialpack_HauntedByDaylight2024.png"
- $.entries[1].contentVersion: "0445e9b53741e73e096eaa60db9dc0935928c86c"
+ $.entries[1].contentVersion: "a046c3e24e3acdca2fe0edcc58f4560604168fa1"
- $.entries[1].downloadStrategy: "preferRemote"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[1].enableChecksum: true
+ $.entries[1].enableChecksum: false
- $.entries[1].packagedPath: ""
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_Rift3.T_UI_SpecialPack_Rift3"
- $.entries[1].schema: "s3ver://"
+ $.entries[1].schema: "s3verbin://"
- $.entries[1].uri: "bonusPointEventsContent.json"
+ $.entries[1].uri: "images/T_UI_SpecialPack_Rift3.png"
- $.entries[2].contentVersion: "064280961f401d507030a56aa3edb1f7fe58e686"
+ $.entries[2].contentVersion: "58aaeed65d11861f3296bae4c4a6f4e368abae73"
- $.entries[2].uri: "freetoplay/NA/event.json"
+ $.entries[2].uri: "catalog.json"
- $.entries[3].contentVersion: "064280961f401d507030a56aa3edb1f7fe58e686"
+ $.entries[3].contentVersion: "7149f0777c9ee6086e174b85769e2c8c3d6882de"
- $.entries[3].uri: "freetoplay/EU/event.json"
+ $.entries[3].uri: "bonusPointEventsContent.json"
- $.entries[4].contentVersion: "da04b229f98654aa4512586974f07ebc1a9ac6e3"
+ $.entries[4].contentVersion: "3a07314e9a6ed7d2048ce8e2dbcabd30e5389a1f"
- $.entries[4].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[4].uri: "freetoplay/NA/event.json"
- $.entries[5].contentVersion: "56214b6a9ea5453ee0d0dc53d2d6ae258cfc7e2d"
+ $.entries[5].contentVersion: "3a07314e9a6ed7d2048ce8e2dbcabd30e5389a1f"
- $.entries[5].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[5].uri: "freetoplay/EU/event.json"
- $.entries[6].contentVersion: "410d854d3e6f2f53514ceb5293f6461cac851229"
+ $.entries[6].contentVersion: "83968ba4671301731f95658aeb76529345631289"
- $.entries[6].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[6].uri: "archiveQuests/Anniversary2022.json"
- $.entries[7].contentVersion: "23a39d3a2127b3da974e83740c890c974a1ba3c7"
+ $.entries[7].contentVersion: "479aa8ad3ce195fa224157021ed3d1c73c75cfc5"
- $.entries[7].uri: "archiveQuests/CalamariV1.json"
+ $.entries[7].uri: "archiveQuests/Anniversary2023.json"
- $.entries[8].contentVersion: "521594505706afe1bee97d6e817a24bea93746be"
+ $.entries[8].contentVersion: "29476ea173535a27c5f1d874a7bd6b8257c67c5c"
- $.entries[8].uri: "archiveQuests/CalamariV2.json"
+ $.entries[8].uri: "archiveQuests/Anniversary2024.json"
- $.entries[9].contentVersion: "960dcd4b8b314ae81bffd306d1d30d5e7203b6d5"
+ $.entries[9].contentVersion: "6bb68cd7dfda1c9e1d7fa4158bd9f4fc6f3482f1"
- $.entries[9].uri: "archiveQuests/CalamariV3.json"
+ $.entries[9].uri: "archiveQuests/CalamariV1.json"
- $.entries[10].contentVersion: "8e5a21f308b79af1e10e67de3356ec99fd8a2334"
+ $.entries[10].contentVersion: "ba1ebc392c0e2575adb6d1adb59e6dd85305bb8f"
- $.entries[10].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[10].uri: "archiveQuests/CalamariV2.json"
- $.entries[11].contentVersion: "782077a5aa8a290b23149168bf3d03962da69f50"
+ $.entries[11].contentVersion: "e520af59e61c3e63eec79bf683a3d0c77d98881d"
- $.entries[11].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[11].uri: "archiveQuests/CalamariV3.json"
- $.entries[12].contentVersion: "e4fb16835af6347a0f5b46e151f78960f4441a04"
+ $.entries[12].contentVersion: "1635f1bb6b3e782470aa1a1f8afab87a1ed09f92"
- $.entries[12].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[12].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[13].contentVersion: "ca480b5f1d4bf1e51d1d27a49c88f093db3f5df0"
+ $.entries[13].contentVersion: "b79d351a23907b14e40d4895448245e714c382bc"
- $.entries[13].uri: "archiveQuests/FireflyV1.json"
+ $.entries[13].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[14].contentVersion: "3c240b344ff4349391b8b42b968b573ff8d27298"
+ $.entries[14].contentVersion: "e14d802bbfca9bd3a30736f4e102873a4584fd81"
- $.entries[14].uri: "archiveQuests/Halloween2021.json"
+ $.entries[14].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[15].contentVersion: "5247dffd42a2145b907167a48226e957e962cd25"
+ $.entries[15].contentVersion: "532bc7b3ae5f206e49389f222fc53fdd5da8be28"
- $.entries[15].uri: "archiveQuests/Halloween2022.json"
+ $.entries[15].uri: "archiveQuests/FireflyV1.json"
- $.entries[16].contentVersion: "96d08a9965d021b82c5f9c80858be90ac703bc3c"
+ $.entries[16].contentVersion: "854614282a79d10bef966b561adbb49e23fb869c"
- $.entries[16].uri: "archiveQuests/Halloween2023.json"
+ $.entries[16].uri: "archiveQuests/Halloween2021.json"
- $.entries[17].contentVersion: "6ea2b2712abcdda9c672c0a61e2c6c947e8fd1b1"
+ $.entries[17].contentVersion: "722f3a072c5629ba655ec1f4e9156f1e6f906923"
- $.entries[17].uri: "archiveQuests/Halloween2024.json"
+ $.entries[17].uri: "archiveQuests/Halloween2022.json"
- $.entries[18].contentVersion: "51bb2cf7e35e2937f2db1401251bd02d7bc5ad23"
+ $.entries[18].contentVersion: "fab41ec15484d4faa2183a6211de8ff3b202809d"
- $.entries[18].uri: "archiveQuests/Spring2024.json"
+ $.entries[18].uri: "archiveQuests/Halloween2023.json"
- $.entries[19].contentVersion: "276580f6e67ab970b724c7d3ff863a9d363b8b94"
+ $.entries[19].contentVersion: "db3c1d12561ea142cfd67adfe62831e341e2b669"
- $.entries[19].uri: "archiveQuests/Spring2025.json"
+ $.entries[19].uri: "archiveQuests/Halloween2024.json"
- $.entries[20].contentVersion: "a483672fc8c3667d2079e365020b91e8dbcbf796"
+ $.entries[20].contentVersion: "b91d9707fb146abc287600d6712e40527cfa027b"
- $.entries[20].uri: "archiveQuests/Summer2023.json"
+ $.entries[20].uri: "archiveQuests/Spring2024.json"
- $.entries[21].contentVersion: "d9832f5fd1fe3f63ee7ae69df2927755272864dd"
+ $.entries[21].contentVersion: "3cc52f7f21a41a7fa3043a9c1d450431f91d4741"
- $.entries[21].uri: "archiveQuests/Tome01.json"
+ $.entries[21].uri: "archiveQuests/Spring2025.json"
- $.entries[22].contentVersion: "4a03119bce8b9cac64460ded149e976824721a92"
+ $.entries[22].contentVersion: "949009e5f1d895e16940aec0b264968f194103a4"
- $.entries[22].uri: "archiveQuests/Tome02.json"
+ $.entries[22].uri: "archiveQuests/Summer2023.json"
- $.entries[23].contentVersion: "6171f928a73c843f21bb35a88ddd0e0a3f50d83f"
+ $.entries[23].contentVersion: "1442435e95543291dd0164bb4305774a76a0efd5"
- $.entries[23].uri: "archiveQuests/Tome03.json"
+ $.entries[23].uri: "archiveQuests/Tome01.json"
- $.entries[24].contentVersion: "636554b90bd6a84ee657d3423db5a6f437543f69"
+ $.entries[24].contentVersion: "172cafa64c97b98d88413688e053e7009327dbde"
- $.entries[24].uri: "archiveQuests/Tome04.json"
+ $.entries[24].uri: "archiveQuests/Tome02.json"
- $.entries[25].contentVersion: "741b740b5c08793c5dc9659d8dc81a7dd5dcef1b"
+ $.entries[25].contentVersion: "cb095bc3d5ebf03bcb5d42c00d0657e2711b52fd"
- $.entries[25].uri: "archiveQuests/Tome05.json"
+ $.entries[25].uri: "archiveQuests/Tome03.json"
- $.entries[26].contentVersion: "9c46e0366d0c1afc06d209c27608b1ae549dcd8a"
+ $.entries[26].contentVersion: "0f15e94c25385f9a6dc6c267a9ea59b76da1aadd"
- $.entries[26].uri: "archiveQuests/Tome06.json"
+ $.entries[26].uri: "archiveQuests/Tome04.json"
- $.entries[27].contentVersion: "47e39cd05cb2dc9b4b87dc573d8c58ded963e7df"
+ $.entries[27].contentVersion: "bc50b24678bd2733fb221748cedad957e7b1ff9a"
- $.entries[27].uri: "archiveQuests/Tome07.json"
+ $.entries[27].uri: "archiveQuests/Tome05.json"
- $.entries[28].contentVersion: "b5829103eb54a16037b7fb5813e4856c40eedd42"
+ $.entries[28].contentVersion: "ae3fe62e28153792172f0f2914513ae3763e45b4"
- $.entries[28].uri: "archiveQuests/Tome08.json"
+ $.entries[28].uri: "archiveQuests/Tome06.json"
- $.entries[29].contentVersion: "51a02f9c3699cb32e79ebd94db848cc12f870fd0"
+ $.entries[29].contentVersion: "5c47faa387f1708077ebbcbededeafbd9d8b4325"
- $.entries[29].uri: "archiveQuests/Tome09.json"
+ $.entries[29].uri: "archiveQuests/Tome07.json"
- $.entries[30].contentVersion: "a8a68425d3bb647141300c7b2e614b5a8d46f109"
+ $.entries[30].contentVersion: "17b3fa184a69d21911d0ab79de7b782e329b1d20"
- $.entries[30].uri: "archiveQuests/Tome10.json"
+ $.entries[30].uri: "archiveQuests/Tome08.json"
- $.entries[31].contentVersion: "8bd691dd538e26c2b96543cfaa71b96013185a16"
+ $.entries[31].contentVersion: "e8348e9f7000b9fd4b3253c212bbebe7f1adf5eb"
- $.entries[31].uri: "archiveQuests/Tome11.json"
+ $.entries[31].uri: "archiveQuests/Tome09.json"
- $.entries[32].contentVersion: "57406ef086d76f494a63ab37e8131f73612fe92e"
+ $.entries[32].contentVersion: "3bf710d04488232cac02a2f919a22e2ef0f907a2"
- $.entries[32].uri: "archiveQuests/Tome12.json"
+ $.entries[32].uri: "archiveQuests/Tome10.json"
- $.entries[33].contentVersion: "6a23b7d99f22e6db23dd2db83ebfd790ffffa0be"
+ $.entries[33].contentVersion: "d5765956e001ac5993efe50f0cfaf991517a6c80"
- $.entries[33].uri: "archiveQuests/Tome13.json"
+ $.entries[33].uri: "archiveQuests/Tome11.json"
- $.entries[34].contentVersion: "619e1d93064bceb2c0b396c66c404761fd2f3d9f"
+ $.entries[34].contentVersion: "3941bfbce4b183caccf29c9f68d269e9b9695cec"
- $.entries[34].uri: "archiveQuests/Tome14.json"
+ $.entries[34].uri: "archiveQuests/Tome12.json"
- $.entries[35].contentVersion: "345fe33965e75e64caa89062ea6ddce65a6a4009"
+ $.entries[35].contentVersion: "e9131fe81bd0ea41f9040f9d0277401f717387b5"
- $.entries[35].uri: "archiveQuests/Tome15.json"
+ $.entries[35].uri: "archiveQuests/Tome13.json"
- $.entries[36].contentVersion: "944d97177804c6e90d4d65876640f4e88b68b51c"
+ $.entries[36].contentVersion: "7c369d8998d95122f5ca0a8bc3ee766f1f5e761d"
- $.entries[36].uri: "archiveQuests/Tome16.json"
+ $.entries[36].uri: "archiveQuests/Tome14.json"
- $.entries[37].contentVersion: "1e46a472dcd8d8cfef6671b711518cf03884ae6e"
+ $.entries[37].contentVersion: "5c89ea5b72facd17e2b2700b2f405e041fa80801"
- $.entries[37].uri: "archiveQuests/Tome17.json"
+ $.entries[37].uri: "archiveQuests/Tome15.json"
- $.entries[38].contentVersion: "91bd8f9f9779504f67eec3c344fec2134e8ae591"
+ $.entries[38].contentVersion: "9d1be7c9568d86f94a2a57e1372085860b161db0"
- $.entries[38].uri: "archiveQuests/Tome18.json"
+ $.entries[38].uri: "archiveQuests/Tome16.json"
- $.entries[39].contentVersion: "34b4412b05aa223598de56c6d1db250c07b6cf3c"
+ $.entries[39].contentVersion: "e58da61c27abceb60cf632608ec0df50f6fa84f4"
- $.entries[39].uri: "archiveQuests/Tome19.json"
+ $.entries[39].uri: "archiveQuests/Tome17.json"
- $.entries[40].contentVersion: "e44a375aac9fd69e5e3e4043794da0206050781b"
+ $.entries[40].contentVersion: "0a0db7b268a70308b2f901fd3de67438fff1592a"
- $.entries[40].uri: "archiveQuests/Tome20.json"
+ $.entries[40].uri: "archiveQuests/Tome18.json"
- $.entries[41].contentVersion: "25f247333b09ad8a518425b1b1b1e814e7e0c69e"
+ $.entries[41].contentVersion: "cf907fc469274b85e6a27c5fb1b81171adc8f3d6"
- $.entries[41].uri: "archiveQuests/Tome21.json"
+ $.entries[41].uri: "archiveQuests/Tome19.json"
- $.entries[42].contentVersion: "5b31d95db4aee7e85b19c29175c393ed3a696fb2"
+ $.entries[42].contentVersion: "f3afeae4fb4a2b819bde40d4a28e171e3a1e7ca3"
- $.entries[42].uri: "archiveQuests/Tome22.json"
+ $.entries[42].uri: "archiveQuests/Tome20.json"
- $.entries[43].contentVersion: "2389b8871fbde717afc0fd2d2fc32fba295f516e"
+ $.entries[43].contentVersion: "bb0cebcc43e03addaaf175f09bd585c91bb5f5b2"
- $.entries[43].uri: "archiveQuests/Winter2022.json"
+ $.entries[43].uri: "archiveQuests/Tome21.json"
- $.entries[44].contentVersion: "afcb081a5b99eb05616917a79f1fe293268d3d60"
+ $.entries[44].contentVersion: "b315dbb8dd2ecbffd98d05936b49936585c6b540"
- $.entries[44].uri: "archiveQuests/Winter2023.json"
+ $.entries[44].uri: "archiveQuests/Tome22.json"
- $.entries[45].contentVersion: "9ccd71aec8c961b5735de004bdbbb4ad6a8ed415"
+ $.entries[45].contentVersion: "e0c529333192cf0a5bd7dda5cd2270f8744b0653"
- $.entries[45].uri: "archiveQuests/Winter2024.json"
+ $.entries[45].uri: "archiveQuests/Winter2022.json"
… 654 more change(s) — see the commit diff for everything
```

### [`freetoplay/EU/event.json`](freetoplay/EU/event.json)

[Full line-by-line diff](diffs/freetoplay/EU/event.json.diff)

```diff
- $.event.end: "2025-06-23T15:00:00"
+ $.event.end: "2025-11-03T16:00:00"
- $.event.start: "2025-06-19T15:00:00"
+ $.event.start: "2025-10-30T15:00:00"
```

### [`freetoplay/NA/event.json`](freetoplay/NA/event.json)

[Full line-by-line diff](diffs/freetoplay/NA/event.json.diff)

```diff
- $.event.end: "2025-06-23T15:00:00"
+ $.event.end: "2025-11-03T16:00:00"
- $.event.start: "2025-06-19T15:00:00"
+ $.event.start: "2025-10-30T15:00:00"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Maple_W3]
- $.featuredCustomizationRecommendations[id=MapleW3].activeTo: "2025-10-14T15:00:00"
+ $.featuredCustomizationRecommendations[id=MapleW3].activeTo: "2025-10-09T15:00:00"
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[57].mainEndTime: "2025-10-18T15:00:00"
+ $.specialEvents[57].mainEndTime: "2025-10-20T15:00:00"
- $.specialEvents[57].postEndTime: "2025-10-18T15:00:00"
+ $.specialEvents[57].postEndTime: "2025-10-20T15:00:00"
```

