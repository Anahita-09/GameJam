# ✉️ Hope's Message: Platformer Adventure

A multi-level **2D platformer game** built with **p5.js** and **p5.play**, where players race against the clock to collect letters and dodge monsters across unique, themed worlds. Can you collect all the letters in time to reveal Hope's message?

---

## 🎮 How to Play

* Use the **arrow keys** to move the player:

  * ⬅️ Left / ➡️ Right to move horizontally
  * ⬆️ Up to jump
* Your goal is to **collect all 10 letter** in each level before time runs out.
* Avoid falling off platforms and colliding with monsters — or the level restarts!

---

## 🌍 Game Features

* 🏠 **Home screen** with animated title and level selection
* ⏱️ **Time-based challenge**: 20 seconds per level
* 🧗‍♂️ **Platforming physics** and gravity
* ✉️ **Collectible letters** to increase your score
* 👾 **Bouncing monsters** that create obstacles
* 🎨 **Four unique themes**:

  * 🌿 Level 1: Grassland
  * ❄️ Level 2: Ice World
  * 🌋 Level 3: Lava Zone
  * 🏜️ Level 4: Desert

---

## 🧠 Concepts

* Sprite creation and collision using `p5.play`
* Dynamic level loading and platform generation
* Responsive camera following the player
* UI buttons for level selection and reset
* Real-time countdown timer and win/loss conditions
* Adaptive layout for different screen sizes (`windowResized()`)

---

## 📁 Project Structure

```
hope-message-game/
├── script.js             # Main game logic
├── assets/
│   ├── Guy.png           # Player sprite
│   ├── Block.png         # Platform block
│   ├── Letter.png        # Coin/letter
│   ├── monster.png       # Monster enemy
│   ├── Grass.png         # Background for level 1
│   ├── Ice.png           # Background for level 2
│   ├── Lava.png          # Background for level 3
│   ├── Sand.png          # Background for level 4
│   └── Home.png          # Home screen background
├── README.md             # You're here!
```

---

## 🚀 Getting Started

1. Open the code in the [p5.js Web Editor](https://editor.p5js.org/).
2. Add the **p5.play** library via the Settings → Libraries tab.
3. Upload the image assets to the editor under the `assets` folder.
4. Click the ▶ Play button to begin!
5. Start from the Home screen, select a level, and begin collecting letters.

---

## 🏁 Victory Condition

🎉 **You win** when you collect all 10 letters in a level before time runs out.

💀 **You lose/reset** if:

* Time runs out
* You touch a monster
* You fall off the platforms
