# Sweet Sugar Stories
## Khanom: Stories of Siam
### Game Design Document (TH)

## High Concept
**แนวเกม:** Point-and-Click Puzzle Adventure + Visual Novel + 2D Side-Scrolling Exploration
**แพลตฟอร์ม:** PC / Steam

ผู้เล่นสำรวจฉาก 2D ที่เล่าอัตลักษณ์ไทยผ่านขนม ผู้คน ความทรงจำ และสถานที่ เดินซ้าย–ขวาและเปลี่ยนระดับขึ้น–ลงระหว่าง Walk Lane ที่ออกแบบไว้ ตรวจสอบวัตถุ คุยกับ NPC เก็บและใช้ไอเทม เชื่อมโยงเบาะแส แก้ Puzzle และทำ Quest เมื่อจบ Quest สำคัญจะได้รับ **Memory Card** เพื่อสะสมเรื่องราวเกี่ยวกับขนม วัตถุดิบ ผู้คน สถานที่ งานฝีมือ ความเชื่อ และความทรงจำของครอบครัว

## Core Pillars
1. Explore — เดินสำรวจฉาก Side-Scrolling หลายระนาบ
2. Observe — ตรวจ Hotspot และ Environmental Storytelling
3. Talk — สนทนาแบบ Visual Novel
4. Solve — แก้ Point-and-Click Puzzle
5. Quest — ทำภารกิจและสร้างความสัมพันธ์
6. Collect Stories — สะสม Memory Card และ Card Set

## Core Loop
เข้าสถานที่ → สำรวจ → ตรวจวัตถุ/คุย → ได้ Clue หรือ Quest → แก้ Puzzle → เกิด Narrative Resolution → ได้ Memory Card → อัปเดต Journal/Map/Relationship → เปิดเส้นทางต่อไป

## Navigation
- ซ้าย / ขวา: เดินแนวนอน
- ขึ้น / ลง: เปลี่ยน Walk Lane / Depth
- Interact: ตรวจ พูด ใช้ เก็บ
- Inventory: เลือก ผสม ใช้ Item
- Journal: Quest, Clue, Recipe, Card, Character

การเดินขึ้น–ลงใช้ **Walk Zone** และ **Transition Node** ไม่ใช่เดินแกน Y ได้อิสระทั้งฉาก เพื่อให้การจัดฉากและ Animation ชัดเจน

## Point-and-Click Verbs
LOOK, TALK, TAKE, USE, COMBINE, GIVE, READ, SMELL, TASTE, REMEMBER
ควรเลือก Action ตามบริบทเพื่อลด UI ที่รก

## Puzzle Types
- Observation
- Inventory Combination
- Recipe Sequence
- Symbol / Pattern Matching
- Environment Reconstruction
- Dialogue Deduction
- Heat / Time / Process Logic
- Memory Reconstruction
- Cultural Association
- Multi-scene Puzzle Chain

ทุก Puzzle ต้องมี Setup, Goal, Clue, Requirement, Feedback ตอนผิด, Hint Level, Solution และ Narrative Consequence โดยไม่พึ่ง Pixel Hunting

## Visual Novel
รองรับ Speaker, Portrait, Expression, Dialogue, Choice, Flag Check, Item Check, Relationship Update, Quest Update, Auto, Skip, History. Choice เปลี่ยนน้ำเสียง ลำดับ Clue Lore Relationship และ Quest Variant เล็กน้อย แต่ไม่ควรทำ Main Story ติด Dead End

## Quest System
ประเภท: Main Story, Character Story, Dessert Story, Community Story, Exploration, Collection
State: locked, available, active, ready_to_turn_in, completed, failed (ใช้ให้น้อย)
เมื่อจบ Quest สามารถปลดล็อก Scene, Quest, Journal, Dialogue, Item และ Memory Card

## Memory Card
หมวด: character, dessert, ingredient, place, craft, festival, belief, family_memory, community_story
การ์ดเป็นรางวัลทางเนื้อเรื่อง ไม่ใช่ Loot Box และสามารถรวมเป็น Set เพื่อปลดล็อก Concept Art, Dialogue, Recipe, ของแต่งร้าน หรือ Epilogue

## Inventory
ประเภท: clue, ingredient, tool, key_item, gift, document, quest_item
รองรับ Inspect Text, Combine Rule, Use Target, Quest Ownership และ Persistent/Consumable

## Journal
รวม Active Quest, Clue, Map, Character, Recipe, Memory Card และ Cultural Note โดยภาพลักษณ์เหมือนสมุดสูตรทำมือของครอบครัว

## Progression
เน้น Narrative Progression: Quest, Trust, Location, Recipe, Technique, Card Set. Meta Stat ที่ใช้ได้: Insight, Craft Knowledge, Community Trust

## Vertical Slice
### Chapter 1 — The Missing Recipe Page / หน้าสูตรที่หายไป
สถานที่: ร้านขนมครอบครัว, ตลาดเช้า, บ้านริมน้ำ
1. ตามหาหน้าสูตรที่หายไป
2. ถามยายน้อยเรื่องลายมือเก่า
3. หาเบาะแส 3 ชิ้นในตลาด
4. แก้ Puzzle การพับใบตอง
5. เรียงขั้นตอนสูตร
6. กลับไปหายายน้อย
7. ปลดล็อก Memory Card: **The First Fold / รอยพับแรก**
เวลาเล่นเป้าหมาย 30–45 นาที
