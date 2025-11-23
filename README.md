# 🎴 Mario Picture Poker: Casino Collection

**Platforms:** Windows, macOS, Linux  
**Engine:** Godot 4.x (Vulkan Renderer)

---

## 🌟 Overview

*Mario Picture Poker: Casino Collection* is a modern 3D remake and expansion of the classic Picture Poker minigame. Designed for PC, it combines polished casino environments, cinematic presentation, and expanded replay value, while keeping the charm and fun of the Mario universe.

Players enjoy fast, accessible card gameplay enhanced with visually striking tables, themed casinos, and dramatic dealer reveal sequences.

---

## 🎮 Features

### 🃏 Picture Poker Gameplay
- Faithful recreation of classic Picture Poker rules.  
- Optional advanced rule variants for players seeking extra challenge.  
- Fast-paced, character-driven card play for both casual and experienced players.

### 🏰 Themed Casinos
Each casino offers a unique 3D environment and props reflecting its theme:

| Casino | Theme Highlights |
|--------|----------------|
| Mushroom Kingdom | Bright, colorful, floating question blocks, Piranha Plant centerpiece |
| Bowser Casino | Lava flows, volcanic rocks, glowing magma, erupting mini volcano |
| Peach’s Royal Palace | Gold accents, silk felt, crystal chandeliers |
| Luigi’s Mansion | Fog, ghost lanterns, cobwebs, eerie green glow |
| Star Road | Star shards, galaxy-pattern felt, floating particles |

- Each casino has a dedicated pool of dealers with unique animations.  

---

### 🪑 3D Table Selection
- Tables arranged in a **120° semi-circle** for a mini showroom experience.  
- Camera can rotate to browse tables.  
- Each table animates subtly with lights, particles, and props.  

![Table Showcase Placeholder](images/table-showcase.png)

---

### ❓ Table Confirmation Flow
1. Click a table.  
2. A Mario-style pop-up appears: **“Are You Sure?”** ✅ / ❌  
3. **No**: return to the table showcase.  
4. **Yes**:  
   - UI disappears  
   - Camera dives dramatically into the table  
   - Screen fades to black  
   - Dealer Reveal cinematic loads seamlessly

![Are You Sure Placeholder](images/confirmation-popup.png)

---

### 🎬 Dealer Reveal Cinematic
- Random dealer selected from the casino’s dealer pool.  
- 5–8 second cinematic featuring:  
  - Dramatic lighting, smoke, and particle effects  
  - Dealer emerges from shadow and performs a signature animation  
  - Dealer walks to the table and sits down  
- Countdown appears: **3… 2… 1…**  
- Camera transitions to gameplay view, starting the game immediately

![Dealer Reveal Placeholder](images/dealer-reveal.png)

---

## 🎨 Art Direction
- Stylized 3D models faithful to the Mario universe  
- Expressive dealer animations with personality  
- Themed props and lighting for each casino  
- Fun, colorful UI elements inspired by classic Mario menus

---

## ⚙️ Technical Approach
- **Engine:** Godot 4.x (Vulkan Renderer)  
- **Platforms:** Windows, macOS, Linux  
- Focus on:  
  - Optimized 3D scenes  
  - Smooth camera & cinematic transitions  
  - Modular scene system for easy expansion  
  - Controller and mouse support

---

## 📦 Project Scope

### Phase 1 – Core Gameplay
- Implement Picture Poker rules  
- Build gameplay UI  
- Add the first functional casino

### Phase 2 – Cinematics & Dealers
- Add dealer reveal sequences  
- Implement dealer animations  
- Integrate casino-specific dealer variations

### Phase 3 – Table Selection Experience
- Build the 3D semi-circle table showcase  
- Add table confirmation pop-up and camera transitions

### Phase 4 – Additional Casinos
- Add 3–5 more themed casinos  
- Unique tables, props, and dealer animations

### Phase 5 – Polish & Optimization
- Refine visual effects and lighting  
- Optimize performance  
- Integrate sound design and music

---

## 🔮 Optional Future Features
- Online multiplayer  
- Unlockable dealer characters  
- Collectible card backs  
- Seasonal events or challenges  
- Daily leaderboards or scoreboards

---

## ✅ Summary
*Mario Picture Poker: Casino Collection* brings a beloved minigame into the modern era with cinematic flair, themed environments, and polished, character-driven 3D gameplay. The goal is a fun, replayable experience that’s visually engaging and true to the Mario universe.

---

## 📂 Assets / Mockups
> Images are placeholders; final assets will follow Nintendo's IP guidelines.

- `images/table-showcase.png` – Example 3D table arc layout  
- `images/confirmation-popup.png` – “Are You Sure?” Mario-style UI  
- `images/dealer-reveal.png` – Dealer reveal cinematic concept

- # ⚠️ Asset Notice

This project uses **placeholder assets** for demonstration purposes. No Nintendo or Mario assets are included in this repository.

If you wish to run or build the project with actual assets, you must **replace placeholders with your own original or licensed content**, as Nintendo’s intellectual property is **not included or distributed here**.

All code, scripts, and original assets in this repository are released under the **MIT License** and are free to use and modify.

## ⚖️ Legal Disclaimer

This project is an **unofficial fan project** created for **educational and personal purposes only**. It is **not affiliated with, endorsed by, sponsored by, or in any way officially connected to Nintendo Co., Ltd. or any of its subsidiaries or affiliates**.

All characters, names, locations, and trademarks depicted or referenced in this project are the property of their respective owners. This repository does **not include any Nintendo or Mario assets**; any demonstration uses **placeholder content or original assets created for this project**.

This project is distributed **non-commercially**, with no intent for profit or sale. Nintendo and its affiliates retain all rights to their intellectual property. By using or contributing to this project, you acknowledge that it is a **fan-made work** and agree not to infringe on the rights of Nintendo or any other intellectual property holder.
