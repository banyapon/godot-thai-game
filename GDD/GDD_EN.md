# Sweet Sugar Stories
## Khanom: Stories of Siam
### Game Design Document (EN)

## High Concept
**Genre:** Point-and-Click Puzzle Adventure + Visual Novel + 2D Side-Scrolling Exploration
**Platform:** PC / Steam

The player explores hand-crafted 2D Thai locations, moves left/right and between authored foreground/background lanes, inspects objects, talks to NPCs, combines clues, solves environmental and recipe puzzles, and completes story quests. Important quests reward collectible **Memory Cards** about desserts, people, places, ingredients, rituals, crafts, and family memories.

## Core Pillars
1. Explore layered side-scrolling scenes.
2. Observe hotspots and environmental storytelling.
3. Talk through Visual Novel scenes.
4. Solve point-and-click puzzles.
5. Complete quests and relationships.
6. Collect Memory Cards and complete cultural story sets.

## Core Loop
Enter location → Explore → Inspect / Talk → Receive clue or quest → Solve puzzle chain → Narrative resolution → Gain Memory Card → Update journal/map/relationship → Unlock next route.

## Navigation
- Left / Right: horizontal movement.
- Up / Down: change authored walk lane / depth.
- Interact: inspect, talk, use, take.
- Inventory: select/combine/use items.
- Journal: quests, clues, recipes, cards, people.

Vertical movement uses **Walk Zones** and **Transition Nodes**, not unrestricted Y movement. This keeps 2D staging readable and animation-friendly.

## Point-and-Click Verbs
LOOK, TALK, TAKE, USE, COMBINE, GIVE, READ, SMELL, TASTE, REMEMBER.
Context-sensitive interaction is preferred over a large verb menu.

## Puzzle Types
- Observation
- Inventory combination
- Recipe sequence
- Symbol / pattern matching
- Environment reconstruction
- Dialogue deduction
- Heat / time / process logic
- Memory reconstruction
- Cultural association
- Multi-scene puzzle chain

Every puzzle defines setup, goal, clues, requirements, wrong-state feedback, hint levels, solution, and narrative consequence. Avoid pixel hunting.

## Visual Novel System
Supports speaker, portrait, expression, dialogue, choices, flag checks, item checks, relationship updates, quest updates, Auto, Skip, and History. Choices may affect tone, clue order, optional lore, relationship, and minor quest variants, but should avoid accidental hard-locks.

## Quest System
Types: Main Story, Character Story, Dessert Story, Community Story, Exploration, Collection.
States: locked, available, active, ready_to_turn_in, completed, failed (rare).
Quest completion may unlock scenes, quests, journal entries, dialogue, items, and Memory Cards.

## Memory Cards
Categories: character, dessert, ingredient, place, craft, festival, belief, family_memory, community_story.
Cards are narrative rewards, not loot boxes. They can form themed sets and unlock concept art, dialogue, recipes, shop decoration, or epilogues.

## Inventory
Item types: clue, ingredient, tool, key_item, gift, document, quest_item.
Items support inspect text, combine rules, use targets, quest ownership, persistent/consumable state.

## Journal
Contains Active Quests, Clues, Map, Characters, Recipes, Memory Cards, and Cultural Notes. Visual direction: handmade family recipe notebook.

## Progression
Narrative-first: quests, trust, locations, recipes, techniques, card sets. Optional meta stats: Insight, Craft Knowledge, Community Trust.

## Vertical Slice
### Chapter 1 — The Missing Recipe Page
Locations: Family Dessert Shop, Morning Market, Riverside House.
1. Search for the missing recipe page.
2. Ask Ya Noi about old handwriting.
3. Find three market clues.
4. Solve a banana-leaf folding puzzle.
5. Reconstruct the recipe sequence.
6. Return to Ya Noi.
7. Unlock Memory Card: **The First Fold**.
Target: 30–45 minutes.
