# Skill: Puzzle System

## เป้าหมาย
ควบคุม Narrative Puzzle ที่ตรวจ State ได้ชัด พร้อมระบบ Hint แบบไล่ระดับ

## Field ที่ต้องมี
id, type, setup, goal, required_clues, required_items, solution, hint_levels, success_effects, retry_behavior

## Hint Level
0 ไม่ช่วย; 1 ย้ำ Goal; 2 ชี้ Clue; 3 บอกความสัมพันธ์; 4 เกือบบอก Solution

## กติกา
- Puzzle ต้องแก้ได้จากข้อมูลที่มีอยู่ก่อนจบ Puzzle
- การลองผิดควรให้ข้อมูลกลับ
- Complete ซ้ำต้องไม่เกิด Reward ซ้ำ
