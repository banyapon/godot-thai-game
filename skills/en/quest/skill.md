# Skill: Quest System

## Purpose
Track objectives and connect scenes, dialogue, puzzles, inventory, and rewards.

## Quest States
locked, available, active, ready_to_turn_in, completed, failed

## Completion Flow
1. Verify required steps.
2. Mark completed.
3. Apply unlocks.
4. Grant Memory Card(s).
5. Add journal entry.
6. Trigger closing dialogue.
7. Autosave.

## Rules
- Reward card ID must be explicit.
- Completion is idempotent.
- Optional steps do not block completion unless marked required.
