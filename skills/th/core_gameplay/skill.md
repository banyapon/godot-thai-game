# Skill: Core Gameplay Orchestration

## เป้าหมาย
ควบคุม Exploration, Interaction, Dialogue, Puzzle, Quest, Inventory และ Reward ให้ทำงานร่วมกันโดย State ไม่ชนกัน

## State Priority
1. Cutscene/VN Lock
2. Puzzle Lock
3. Interaction
4. Free Exploration

## Input
player_state, scene_state, interaction_event, quest_state, inventory_state

## Output
next_game_state, triggered_system, updated_flags, autosave_request

## กติกา
- ห้ามแจก Quest Reward ซ้ำ
- ห้าม Consume Key Item ถ้าไม่มี Rule ระบุ
- หลีกเลี่ยง Dead End แบบถาวร
- การเปลี่ยนข้อมูลต้องอ้าง Stable ID ไม่ใช้ชื่อแสดงผล
