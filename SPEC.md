# Super Plumber - Game Specification

## 1. Project Overview

**Project Name:** Super Plumber
**Type:** 2D Platformer Game (Mariko-style)
**Core Functionality:** Multi-level platformer with underground levels, quest system, and NPCs
**Target Users:** Casual gamers

## 2. Level Structure

### Level 1 - Overworld (Ground)
- **Length:** Extended horizontal map (longer than screen, scrollable)
- **Goal:** Reach the end and jump into a hatch/pipe to enter underground
- **Elements:** Platforms, enemies (Goombas), coins, blocks

### Level 2 - Underground
- **Length:** Extended horizontal map
- **NPC Encounter:** Meet wizard/warlock at specific point
- **Quest:** Find artifact that destroys all enemies
- **Goal:** Exit through hatch to surface

### Level 3 - Open World
- **Structure:** Multiple locations connected by platforms/bridges
- **NPCs:** Travelers with simple quests at different locations
- **Quest System:**
  - Press Q to view quest list
  - Only one active quest at a time
  - Cannot take multiple quests from different locations
  - View available quests at location before accepting

## 3. Game Mechanics

### Controls
- **Arrow Keys / WASD:** Movement
- **Space / W / Up Arrow:** Jump
- **Q:** Open quest list (Level 3)
- **E:** Interact with NPCs

### Player States
- Normal: 40px height
- Invincible after hit: blink effect

### Enemies
- Goomba: Basic walking enemy
- Stomp to kill, get hit = lose life

## 4. UI Elements
- Score display
- Coins counter
- Lives counter
- Quest list (Level 3)
- NPC interaction prompts

## 5. Visual Style
- Retro pixel art aesthetic
- Color palette: Blue sky (#5c94fc), green ground (#228B22), brown blocks (#CD853F)
- Yellow coins, red player character

## 6. Acceptance Criteria

1. ✅ Level 1: Extended map scrolls, reach end hatch to go underground
2. ✅ Level 2: Underground level with wizard NPC, artifact quest
3. ✅ Level 3: Multiple locations with bridges, travelers with quests
4. ✅ Q key opens quest list in Level 3
5. ✅ Only one quest can be active at a time
6. ✅ Artifact in Level 2 destroys all enemies when collected