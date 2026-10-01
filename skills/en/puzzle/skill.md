# Skill: Puzzle System

## Purpose
Run deterministic narrative puzzles with clue tracking and escalating hints.

## Required Fields
id, type, setup, goal, required_clues, required_items, solution, hint_levels, success_effects, retry_behavior

## Hint Levels
0 none; 1 restate goal; 2 point to clue; 3 suggest relationship; 4 near-explicit solution.

## Rules
- Puzzle must be solvable with available information.
- Failure should teach something.
- Completion must be idempotent.
