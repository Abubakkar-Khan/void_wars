# 🚀 VOID WARS — Duel of Flagships

**VOID WARS** is a fast-paced browser-based **space strategy skirmish** game.  
Deploy squads of ships, upgrade your flagship, and survive escalating waves of enemy fleets and bosses.  
Built with **vanilla JavaScript + Canvas**, no frameworks required.

---

## 🎮 Gameplay

- Each round, deploy ships from your flagship to attack the enemy.
- Earn **credits** for each victory (and salvage).
- Between battles, spend credits on **upgrades** to enhance your fleet.
- Every **5th round spawns a boss** — don’t let it reach your flagship!

⚔️ The duel ends when either flagship is destroyed.

---

## ✨ Features

- **Five ship types**:
  - 🛩 Fighter — cheap melee swarmers  
  - ⚡ Interceptor — fast anti-bomber hunters  
  - 💣 Bomber — heavy hitters with explosive deathblow  
  - 🤖 Drone — support healers for your fleet  
  - 🚀 Frigate — long-range support cannons  

- **Dynamic flagship battles** with HP, energy, and regen.
- **Upgrades system** with 16 branching enhancements:
  - More damage, HP, regen, armor, squad size, and special effects.
- **Boss fights** every 5 rounds.
- **AI enemy commander** with changing personalities.
- **Juicy effects**: particles, bloom, screen shake, and retro SFX (WebAudio).
- **Pause, retry, and shop system** with scaling upgrade costs.

---

## 🕹 Controls

- **1–5** → Select ship type  
- **Click** → Deploy selected ship  
- **Space** → Deploy selected ship  
- **P** → Pause  
- **⏩ Speed** → Toggle game speed (1× / 1.5× / 2×)  
- **📸** → Take a screenshot  
- **⨉ Max Deploy** → Toggle burst-deploy mode  

---

## ⚡ Upgrades

Spend credits in the **shop** after each round:

| Upgrade             | Effect                                  |
|---------------------|------------------------------------------|
| Weapon Damage       | +10% ship damage                        |
| Hull Plating        | +12% max HP                             |
| Reactor Regen       | +15% energy regen                       |
| Energy Cap          | +2 max energy                           |
| Thrusters           | +10% ship speed                         |
| Armor               | -8% incoming damage                     |
| Ramming Plate       | +25% collision damage                   |
| Projectile Speed    | +15% projectile speed                   |
| Targeting Suite     | +10% weapon range                       |
| Squad Size          | +1 concurrent unit                      |
| Drone Optics        | +15% heal range                         |
| Med Throughput      | +20% heal/sec                           |
| Point-Defense       | Flagship auto-turret                    |
| Captain’s Tactics   | +5% global aura                         |
| Boss Buster         | +20% vs bosses                          |
| Salvage Bonus       | +4 credits per kill                     |

---

## 🧩 Tech Stack

- **HTML5 Canvas** for rendering
- **Vanilla JavaScript** (ES6+)
- **CSS HUD & modals**
- **WebAudio API** for retro SFX

No external dependencies. Just open the `.html` file in your browser.

---

## 📸 Screenshots

*(Add your screenshots here)*

---

## 🚀 Getting Started

1. Clone or download this repo  
2. Open `index.html` in your browser  
3. Start commanding your fleet!

---

## 🛠 Development

The game is a **single self-contained file** (`index.html`).  
You can tweak:

- `BASE` → ship stats  
- `UPG` → upgrade list and scaling  
- AI personalities in `pickPersonality()`  
- Particle/bloom/screen-shake settings in `Settings`

---

## 🏆 Credits

Created with ❤️ for **strategy + arcade fans**.  
Inspired by classic flagship duel concepts, with modern juice.

---
