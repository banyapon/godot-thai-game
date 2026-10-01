# Skill: Data Validation

## เป้าหมาย
ตรวจสอบ Game Data แบบ JSON ก่อน Runtime

## ตรวจ
Unique ID; Cross Reference; Quest→Puzzle; Quest→Card; Dialogue→Flag; Scene→Exit; Item→Target; Card→Set

## Severity
ERROR = Progression พัง; WARNING = Optional/Localization Issue; INFO = Naming/Style Suggestion

## ID Convention
ใช้ lowercase snake_case เช่น q_main_001, p_recipe_fold_001, card_memory_first_fold, scene_market_morning, npc_ya_noi
