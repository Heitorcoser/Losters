# Graph Report - losters  (2026-10-25)

## Corpus Check
- 52 files · ~139,870 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 16 file(s) not represented in the graph (top: (none) 4, .xml 4, .properties 2)

## Summary
- 835 nodes · 1011 edges · 50 communities (37 shown, 13 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 6 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `39857c60`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Battle
- engine.js
- Updater.java
- with
- MasterBattle
- pc/main.js
- sprites.js
- steps
- phase10.js
- phase3.js
- phase5.js
- phase2.js
- phase4.js
- sprites9.js
- phase8.js
- ApkProvider
- phase13.js
- phase9.js
- phase6.js
- build
- phase12.js
- phase14.js
- phase7.js
- sprites2.js
- phase1.js
- phase11.js
- README.md
- sprites5.js
- sprites7.js
- sprites3.js
- js/main.js
- sprites4.js
- sprites6.js
- world.js
- coop.js
- sprites8.js
- quests.js
- CLAUDE.md
- .claude/CLAUDE.md
- audio.js
- NOVIDADES.md
- c2fase3.js
- c2fase2.js
- c2fase1.js
- cap2.js
- sprites10.js
- FinalBattle

## God Nodes (most connected - your core abstractions)
1. `Battle` - 43 edges
2. `MasterBattle` - 23 edges
3. `FinalBattle` - 20 edges
4. `with` - 14 edges
5. `Updater` - 12 edges
6. `MainActivity` - 11 edges
7. `ApkProvider` - 9 edges
8. `TrainBattle` - 8 edges
9. `steps` - 7 edges
10. `build` - 7 edges

## Surprising Connections (you probably didn't know these)
- `MainActivity` --references--> `Updater`  [EXTRACTED]
  android/app/src/main/java/com/heitorcoser/perdido/MainActivity.java → android/app/src/main/java/com/heitorcoser/perdido/Updater.java

## Import Cycles
- None detected.

## Communities (50 total, 13 thin omitted)

### Community 0 - "Battle"
Cohesion: 0.07
Nodes (17): Battle, BATTLE_CLASSES, BOX_FULL, BTN, BULLET_DRAW, DRAGON_EVO, dragonBonus(), DRAGONS (+9 more)

### Community 1 - "engine.js"
Cohesion: 0.05
Nodes (20): Config, ctx, cv, Dialog, Fade, G, Input, ITEMS (+12 more)

### Community 3 - "with"
Cohesion: 0.06
Nodes (40): runs-on, steps, run, jobs, android, lancar, windows, needs (+32 more)

### Community 4 - "MasterBattle"
Cohesion: 0.08
Nodes (16): BLASTER, BLASTER_OPEN, boss9Sprites(), bt9(), drawBlaster(), M9_COLORS, M9_FLAVOR, M9_PHASES (+8 more)

### Community 5 - "pc/main.js"
Cohesion: 0.09
Nodes (21): checkUpdate(), createWindow(), download(), getJSON(), request(), author, description, devDependencies (+13 more)

### Community 6 - "sprites.js"
Cohesion: 0.08
Nodes (27): buildSprites(), buildTiles(), composePlayer(), DUMMY, FANTASMINHA, I_BASE, I_BLINK, I_WALK (+19 more)

### Community 7 - "steps"
Cohesion: 0.07
Nodes (26): concurrency, cancel-in-progress, group, name, url, jobs, publicar, name (+18 more)

### Community 9 - "phase3.js"
Cohesion: 0.11
Nodes (14): BLOCK_START, Cine3, ents(), LAKE_ROCKS, musicAt(), P3, penguinNpc(), Phone (+6 more)

### Community 10 - "phase5.js"
Cohesion: 0.11
Nodes (9): Cine5, ents(), guardEnt(), gummyNpc(), musicAt(), P5, ROLL_SPOT, sprNpc() (+1 more)

### Community 11 - "phase2.js"
Cohesion: 0.13
Nodes (10): ents(), ghostEnt(), lampEnt(), layer(), musicAt(), npcDragon(), P2, STATUE_ORDER (+2 more)

### Community 12 - "phase4.js"
Cohesion: 0.12
Nodes (9): Cine4, DOORS4, ents(), kidNpc(), musicAt(), P4, robotNpc(), TOUR (+1 more)

### Community 13 - "sprites9.js"
Cohesion: 0.12
Nodes (18): buildPartySets(), buildSprites9(), buildTiles9(), CARMIM, CARMIM_PAL, DRESS, KAI, KAI_PAL (+10 more)

### Community 14 - "phase8.js"
Cohesion: 0.12
Nodes (6): Cine8, GEYSER_ROWS, musicAt(), P8, STONES8, update()

### Community 16 - "phase13.js"
Cohesion: 0.12
Nodes (3): musicAt(), P13, update()

### Community 17 - "phase9.js"
Cohesion: 0.13
Nodes (6): DOORS9, dragonEnt9(), ents(), musicAt(), P9, update()

### Community 18 - "phase6.js"
Cohesion: 0.14
Nodes (6): Cine6, critter(), ents(), musicAt(), P6, update()

### Community 19 - "build"
Cohesion: 0.13
Nodes (15): build, appId, directories, files, nsis, productName, win, output (+7 more)

### Community 20 - "phase12.js"
Cohesion: 0.14
Nodes (4): DOORS12, musicAt(), P12, update()

### Community 21 - "phase14.js"
Cohesion: 0.14
Nodes (4): DOORS14, musicAt(), P14, update()

### Community 22 - "phase7.js"
Cohesion: 0.14
Nodes (4): DOORS7, musicAt(), P7, update()

### Community 23 - "sprites2.js"
Cohesion: 0.15
Nodes (14): BRASA_PAL, BRASINHA, buildCityTiles(), buildSprites2(), DRAGON, DRAGON_FLAP, DRAGON_PALS, FIRE_PAL (+6 more)

### Community 24 - "phase1.js"
Cohesion: 0.16
Nodes (4): build(), genMaze(), mazePath(), P1

### Community 26 - "README.md"
Cohesion: 0.17
Nodes (11): ⬇️ Baixar e instalar, 🕹️ Controles, 🛠️ Desenvolvimento, 📖 História — Capítulo 1, 🔴 História — Capítulo 2: Determinação, 👥 Multiplayer cooperativo, 🧑‍🤝‍🧑 Personagens, 🔥 Quanto mais jogadores, mais difícil (+3 more)

### Community 27 - "sprites5.js"
Cohesion: 0.20
Nodes (10): buildIslandTiles(), buildSprites5(), CHOCO, CHOCO_PAL, GUARD_PAL, GUMMY, GUMMY_PALS, MACARON (+2 more)

### Community 28 - "sprites7.js"
Cohesion: 0.22
Nodes (10): buildSprites7(), buildVolcanoTiles(), DRACO, DRACO_PAL, drawDragonAura(), drawRider(), FANT_LAVA, FANT_LAVA_PAL (+2 more)

### Community 29 - "sprites3.js"
Cohesion: 0.22
Nodes (9): buildSnowTiles(), buildSprites3(), CAPUZ_PAL, ENCAPUZADO, NEVE_PAL, NEVOSO, PING_PAL, PINGUIM (+1 more)

### Community 30 - "js/main.js"
Cohesion: 0.22
Nodes (8): Chapter, ConfigMenu, Credits, End, Game, GameOver, Intro, Title

### Community 31 - "sprites4.js"
Cohesion: 0.25
Nodes (8): buildFutureTiles(), buildSprites4(), BULLY_DOWN, KID_PALS, ROBOT, ROBOT_PALS, ROBOT_SAD, ROBOT_WHEEL

### Community 32 - "sprites6.js"
Cohesion: 0.25
Nodes (8): ARANHA, ARANHA_PALS, buildDeepTiles(), buildSprites6(), ESQ_PALS, ESQUELETO, KITSUNE, KITSUNE_PAL

### Community 33 - "world.js"
Cohesion: 0.25
Nodes (3): frameWaiters, MAPS, World

### Community 34 - "coop.js"
Cohesion: 0.33
Nodes (4): Coop, COOP_COLORS, COOP_ICE, CoopUI

### Community 35 - "sprites8.js"
Cohesion: 0.50
Nodes (4): buildArenaTiles(), buildSprites8(), LEAO, LEAO_PAL

### Community 44 - "c2fase3.js"
Cohesion: 0.12
Nodes (6): bf(), Det2, F2_ATK, F2_TALK, R3, update()

### Community 45 - "c2fase2.js"
Cohesion: 0.11
Nodes (4): C2TrainBattle, D2, musicAt(), update()

### Community 46 - "c2fase1.js"
Cohesion: 0.12
Nodes (4): A1, FISH2, Lab2, Voo2

### Community 47 - "cap2.js"
Cohesion: 0.22
Nodes (10): C2, C2_PHASES, C2_WHO, c2lines(), c2say(), c2show(), Card2, ChapterSel (+2 more)

### Community 48 - "sprites10.js"
Cohesion: 0.20
Nodes (10): BOTA, buildSprites10(), CRIANCA, JORGE, JORGE_PAL, MORADOR, MORADOR_PALS, PEIXE (+2 more)

## Knowledge Gaps
- **13 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Updater` connect `Updater.java` to `ApkProvider`?**
  _High betweenness centrality (0.002) - this node is a cross-community bridge._
- **Should `Battle` be split into smaller, more focused modules?**
  _Cohesion score 0.07175141242937853 - nodes in this community are weakly interconnected._
- **Should `engine.js` be split into smaller, more focused modules?**
  _Cohesion score 0.04625346901017576 - nodes in this community are weakly interconnected._
- **Should `Updater.java` be split into smaller, more focused modules?**
  _Cohesion score 0.11397849462365592 - nodes in this community are weakly interconnected._
- **Should `with` be split into smaller, more focused modules?**
  _Cohesion score 0.05975609756097561 - nodes in this community are weakly interconnected._
- **Should `MasterBattle` be split into smaller, more focused modules?**
  _Cohesion score 0.08048780487804878 - nodes in this community are weakly interconnected._
- **Should `pc/main.js` be split into smaller, more focused modules?**
  _Cohesion score 0.08866995073891626 - nodes in this community are weakly interconnected._