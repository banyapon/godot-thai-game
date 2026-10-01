# Skill: Side-Scrolling Adventure Navigation

## Purpose
Manage 2D horizontal movement plus authored up/down lane transitions.

## Scene Data
bounds, walk_zones, lanes, transition_nodes, exits, spawn_points, blocked_regions

## Rules
- Up/down changes lane only where transitions are allowed.
- NPC interaction range is lane-aware.
- Every exit defines destination_scene_id and destination_spawn_id.
- Occluders require explicit masking/pass rules.
