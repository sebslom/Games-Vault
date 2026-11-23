<div align="center">

```text
  ____                               __     __          _ _   
 / ___| __ _ _ __ ___   ___  ___     \ \   / /_ _ _   _| | |_ 
| |  _ / _` | '_ ` _ \ / _ \/ __|_____\ \ / / _` | | | | | __|
| |_| | (_| | | | | | |  __/\__ \_____\ V / (_| | |_| | | |_ 
 \____|\__,_|_| |_| |_|\___||___/      \_/ \__,_|\__,_|_|\__|
```

### 🕹️ **INSTANT BROWSER ARCADE · 20 STANDALONE HTML5 GAMES** 🕹️

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Canvas API](https://img.shields.io/badge/Canvas_2D_%26_Raycaster-6842FF?style=for-the-badge&logo=webgl&logoColor=white)](#)
[![Zero Dependencies](https://img.shields.io/badge/Build_Step-None_(Standalone)-10B981?style=for-the-badge)](#)

<br/>

<!-- Clickable SVG Graphic Banner ("CLICK HERE TO PLAY") -->
<!-- Replace YOUR_USERNAME and YOUR_REPO with your actual GitHub Pages URL -->
<a href="https://YOUR_USERNAME.github.io/YOUR_REPO/" target="_blank">
  <img src="https://img.shields.io/badge/%E2%96%B6%EF%B8%8F_CLICK_HERE_TO_PLAY_NOW-6842FF?style=for-the-badge&labelColor=090D16" alt="Click Here to Play Games Vault" height="54" />
</a>

<p>
  <em>No downloads. No installations. Just pure, instant arcade action on Desktop & Mobile!</em>
</p>

</div>

---

## ✨ What is Games Vault?

**Games Vault** is a fast, lightweight, CrazyGames-inspired web arcade portal built with zero external dependencies. Every single title in the collection is engineered as a **self-contained standalone `.html` file** with procedural WebAudio sound effects, responsive mobile touch controls, and instant modal launching.

* 🎨 **Sleek Arcade Hub:** Dark-mode interface with instant live search, tag filtering, and 15+ game genres.
* 🖼️ **Live Previews & Custom Covers:** Supports both custom thumbnail artwork and live-scaled interactive HTML previews directly inside the grid tiles.
* 📱 **Cross-Platform Ready:** Play with Keyboard + Mouse, Gamepads, or built-in on-screen touch controls on phones and tablets.
* ⚡ **Instant GitHub Pages Hosting:** Drop the files into any static host and play immediately.

---

## 🎮 The 20-Game Arcade Lineup

| Icon | Game Title | Genre | Highlights & Features |
| :---: | :--- | :--- | :--- |
| 🗡️ | **Grimglyf: ASCII Action RPG** | `RPG` | Procedural dungeons, 9 classes, Runewords, multi-floor estate building & LAN co-op |
| 🔫 | **Doom II: Brutal Hellgate** | `Shooter` | Textured 3D raycaster, 6 weapons, headshots, Mighty Boot kicks & glory executions |
| 🧛 | **Crimson Horde Survival** | `Survival` | Auto-firing gothic arena roguelike with weapon evolutions & 60s Overlord bosses |
| 🏰 | **Bastion Micro Defense** | `Strategy` | 3 tactical maps, 6 upgradable/evolving turrets, commander powers & Armory doctrines |
| 🌟 | **Star Forge Tycoon** | `Clicker` | Interactive star reactor, alloy smelting, 5-stage Dyson Ring & Supernova prestige |
| 🏎️ | **Cyber Drift Overdrive** | `Racing` | High-speed synthwave traffic dodging & Neon Cell overdrive boosts |
| 🚀 | **Void Star Defender** | `Space` | Wave-based alien squadron shooter with armored elites & laser cannons |
| 🧱 | **BlockGuy (1993 DOS Tribute)** | `Puzzle` | Faithful clone of *Block-Man* (1993)—lift, carry & stack blocks to reach the exit |
| 🟦 | **Tetrix Blox** | `Arcade` | Classic falling block stacker with landing ghost-piece preview & speed levels |
| 💣 | **Cyber Minefield** | `Strategy` | Multi-grid minesweeper (`9x9` to `12x12`) with quick Dig/Flag mobile toggle |
| 🔮 | **Prism Brick Breaker** | `Arcade` | Multi-stage paddle & orb action with reinforced bricks & smooth pointer tracking |
| 🥷 | **Shadow Spire Jumper** | `Platformer` | Endless double-jump parkour runner over abyssal gaps and crimson spikes |
| 🐍 | **Neon Grid Snake** | `Arcade` | Grid arcade snake with golden bonus orbs, high-score saving & D-pad support |
| 🧠 | **Neural Memory Matrix** | `Puzzle` | Dual-mode brain trainer: Pair Decryption Matrix + Sequence Override recall |
| 🏓 | **Plasma Pong 1P / 2P** | `2 Player` | Classic duel vs 3 AI tiers or local 2-player split-touch with power-up orbs |
| 🚁 | **Aether Drone Dash** | `Platformer` | **1 to 4 Players** simultaneous local flight through moving laser pylons |
| 🃏 | **High-Stakes Blackjack 21** | `Board` | 6-deck casino table with Split, Double Down, Insurance & built-in rules guide |
| ❌ | **Tic Tac Toe Arena** | `2 Player` | Play against a tactical AI or challenge a friend locally with win tracking |
| ⚡ | **Reflex Reaction Test** | `Rhythm` | Millisecond reaction speed benchmark with average & personal best tracking |
| 🎯 | **Aim Trainer: Catch the Dot** | `Action` | 30-second precision target clicking challenge with live accuracy % readout |

---

## 🚀 Deploy Your Own Arcade in 60 Seconds

1. **Fork or Clone** this repository to your GitHub account.
2. Ensure `index.html` and all game `.html` files are in the root folder.
3. Navigate to **Settings → Pages** in your GitHub repository.
4. Under **Build and deployment**, select **Deploy from a branch** → choose `main` and `/ (root)`, then click **Save**.
5. Update the *"Click Here to Play"* link at the top of this README with your live GitHub Pages URL!

---

## 🛠️ Adding New Games

Adding a new standalone `.html` game to **Games Vault** takes just one object entry inside `GAMES` in `index.html`:

```javascript
{
  id: 'my-new-game',
  title: 'My Awesome HTML5 Game',
  genre: 'Action',
  badge: 'new', // 'new', 'hot', or 'top'
  tags: ['arcade', 'fast', 'html5'],
  livePreview: true, // Or use `image: 'covers/my-cover.png'`
  url: './my-new-game.html'
}
```

<div align="center">
  <br/>
  <strong>⭐ Star this repository if you enjoy the games! ⭐</strong>
</div>
