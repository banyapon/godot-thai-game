# Skill: Quest System

## เป้าหมาย
ติดตาม Objective และเชื่อม Quest กับ Scene, Dialogue, Puzzle, Inventory และ Reward

## Quest State
locked, available, active, ready_to_turn_in, completed, failed

## Flow เมื่อจบ Quest
1. ตรวจ Required Step
2. Mark completed
3. Apply Unlock
4. แจก Memory Card
5. เพิ่ม Journal Entry
6. เรียก Closing Dialogue
7. Autosave

## กติกา
- Reward Card ID ต้องระบุชัด
- Complete ซ้ำต้องไม่แจกซ้ำ
- Optional Step ไม่บล็อก Quest เว้นแต่ marked required
