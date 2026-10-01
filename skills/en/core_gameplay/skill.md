# Skill: Core Gameplay Orchestration

## Purpose
Coordinate exploration, interaction, dialogue, puzzle, quest, inventory, and reward states.

## State Priority
1. Cutscene/VN lock
2. Puzzle lock
3. Interaction
4. Free exploration

## Inputs
player_state, scene_state, interaction_event, quest_state, inventory_state

## Outputs
next_game_state, triggered_system, updated_flags, autosave_request

## Rules
- Never grant duplicate quest rewards.
- Never consume a key item without an explicit rule.
- Avoid irreversible progression dead ends.
- Mutations must reference stable IDs, never display names.
