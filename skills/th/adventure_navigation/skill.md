# Skill: Side-Scrolling Adventure Navigation

## เป้าหมาย
ควบคุมการเดิน 2D ซ้าย–ขวา และการกดขึ้น–ลงเพื่อเปลี่ยน Lane ตามจุดที่ออกแบบไว้

## Scene Data
bounds, walk_zones, lanes, transition_nodes, exits, spawn_points, blocked_regions

## กติกา
- ขึ้น/ลงเปลี่ยน Lane ได้เฉพาะ Transition ที่อนุญาต
- ระยะคุย NPC ต้องคำนึงถึง Lane
- Exit ต้องมี destination_scene_id และ destination_spawn_id
- Foreground Occluder ต้องกำหนด Mask/Pass Rule ชัดเจน
