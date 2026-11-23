# Games Vault

A browser-based mini-game hub and standalone HTML5 arcade collection designed for desktop and mobile play, featuring genre filtering, instant search, live HTML previews or custom cover art, and full-viewport modal gameplay[cite: 2, 5].

## Features

- **CrazyGames-Inspired Hub UI:** Responsive dark interface with a collapsible genre sidebar on mobile, live search across titles, genres, and tags, and 16:10 game tiles[cite: 2, 5].
- **Flexible Tile Previews:** Supports custom cover images (`image`) or live scaled HTML previews (`livePreview`), launching each game inside a near-fullscreen modal with a top-right close button (`×` or `ESC`)[cite: 2, 5].
- **Standalone HTML5 Games:** Every game runs as a self-contained `.html` file without build steps required for static hosting[cite: 2, 3, 4, 7, 8, 9, 10, 11, 12, 13, 18, 19, 20, 21, 22, 23, 24, 25, 26].

## Included Games

- **Grimglyf: ASCII Action RPG** (`./grimglyf.html`) — Procedural ASCII action RPG and estate builder[cite: 5].
- **Mini FPS: Doom Raycaster** (`./minifps.html`) — Raycasting 3D shooter with multiple weapons, boot kicks, gore effects, campaign sectors, and endless mode[cite: 5, 26].
- **Neon Grid Snake** (`./snake.html`) — Grid snake with bonus orbs, local best score, and touch controls[cite: 4].
- **Tic Tac Toe Arena** (`./tictactoe.html`) — 1P vs AI and 2-player local modes with score tracking[cite: 3].
- **Reflex Reaction Test** (`./reaction.html`) — Reaction speed tester with average and best time tracking[cite: 8].
- **Aim Trainer: Catch the Dot** (`./catchdot.html`) — Timed accuracy and hit counter trainer[cite: 7].
- **Cyber Drift Overdrive** (`./cyber-drift.html`) — High-speed lane-dodging arcade racer[cite: 11].
- **Void Star Defender** (`./void-defender.html`) — Wave-based space shooter[cite: 10].
- **BlockGuy 4096** (`./blockguy-2048.html`) — 1993 MS-DOS Block-Man inspired block-lifting and stacking puzzle[cite: 13].
- **Tetrix Blox** (`./tetrix-blox.html`) — Block stacker with ghost piece preview and increasing levels[cite: 12].
- **Cyber Minefield** (`./minefield.html`) — Mine sweeper with multiple grid sizes and dig/flag mode toggle[cite: 18].
- **Prism Brick Breaker** (`./brick-breaker.html`) — Multi-stage brick breaker with pointer and keyboard controls[cite: 17].
- **Shadow Spire Jumper** (`./shadow-jumper.html`) — Double-jump endless runner over gaps and spikes[cite: 16].
- **Crimson Horde Survival** (`./crimson-horde.html`) — Top-down arena survival roguelike with auto-weapons, evolutions, and bosses[cite: 19].
- **Neural Memory Matrix** (`./memory-matrix.html`) — Pair-matching matrix with neural scan and sequence recall mode[cite: 22].
- **Plasma Pong 1P / 2P** (`./pong-duel.html`) — 1-player AI and 2-player local pong with power orbs[cite: 21].
- **Aether Drone Dash** (`./flappy-drone.html`) — 1 to 4 player local side-scrolling drone flight game[cite: 20].
- **High-Stakes Blackjack 21** (`./blackjack.html`) — 6-deck blackjack with split, double down, insurance, and in-game rules[cite: 23].
- **Star Forge Tycoon** (`./star-forge.html`) — Star harvesting tycoon with alloy smelting, Dyson ring stages, and supernova prestige[cite: 24].
- **Bastion Micro Defense** (`./bastion-defense.html`) — Tactical tower defense across multiple maps with turret evolutions and commander powers[cite: 25].

## Publishing to GitHub Pages

1. Place `index.html` and all standalone game `.html` files in the root of your GitHub repository (or a chosen branch/folder)[cite: 2, 5].
2. In your repository on GitHub, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, select **Deploy from a branch**, choose your branch (e.g., `main`) and `/ (root)`, then save.
4. Wait for the deployment check to complete, then open `https://<your-username>.github.io/<your-repo-name>/`.
