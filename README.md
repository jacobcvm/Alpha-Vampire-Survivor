# 🛡️ Knight Survivor - Pre-Alpha

Welcome to the **Vampire Survivor** pre-alpha!  
This is a top-down survival game featuring melee and ranged combat, leveling up and fighting increasing waves of enemies.

---

## 🎮 Current Features

### 🔹 Movement
- Screen Settings: windowed mode 1920-1080 resolution
- **W, A, S, D** or **Arrow Keys** to move the player
- mouse movement (left,right) makes the character flip_horizontally

### 🔹 Combat
- The player starts with the slash attack and finds more weapons over time when he level's up
- **Melee Weapon**: 
   - Orbiting rocks around the player
   - Slash attack
- **Ranged Weapon**: 
   - Rock projectile follows the mouse position
   - Periodical Explosion that follows the mouse

### 🔹 Enemies
1. **Thief**
2. **Anomaly**
3. **Dead**
   - Moves fast
4. **Flying Demon**
   - Very tanky  
   - Fires ranged fireball attacks  
   - Drops a chest that grants a level-up

#### Enemy Behavior
- All enemies:
  - Become black when hit
  - Move back and forth and attack when they have a collision with the player
  - Spawn outside the screen and move toward the player
  - Spawn more frequently as time passes
  - new spawns gain better hp, movement speed and damage every minute.
  - Stronger enemies spawn less often than the weaker ones
  - The player becomes black when hit by any of their attacks
  - Drop XP on death

- Thief the small brown enemy
   - Slash attacks pushes the small thieves away from the player   

### 🔹 Magnet Mechanic
- XP will follow the player when within range until it is collected

---

## 🧪 User Interface (UI)

During gameplay, the UI displays:
- **Hp bar: HP / Max HP**
- **Xp bar: Level: XP / Max XP**
- **Kills**
- **Elapsed Time**
- **Score**

---

## 🗂️ Menus

### Main Menu
- Start Game
- View Highscore
- Upgrades
- Quit Game

### Upgrades
- 3 possible permanent upgrades (Hp,dmg,move_speed)
- reset upgrades
- Return to main menu

### Highscore
- Delete Highscore
- Return to main menu

### Pause Menu (via `ESC`)
- Resume Game
- Return to Main Menu

---

## 🔼 Leveling System

### Level Up Mechanics
- When **current XP ≥ max XP**, the player levels up
- Choose **1 of 3 random upgrades**

#### 📈 Passive Bonus (each level up)
- `+10` Max HP  
- `+5` Damage

#### 🔧 Upgrades

##### Weapon Upgrades
- Faster rotation  
- Bigger Attacks  
- Larger orbit radius  
- Additional rock
- More damage  
- Faster attack speed  
- More damage  

##### Character Upgrades
- Increased health regeneration  
- Increased max HP  
- Increased movement speed  
- Increased XP pickup range

---

## 🎁 Droppable Items
- **Xp -Blue gem-
- **Gold to buy permanent upgrades -coin-
- **Movement speed boost-> duration: 10s -Green gem-
- **Attack boost-> duration: 20s -Red Gem-
- **Health Potion**: restore 50% of health -Heart-
- **Magnet**: -purple crystal-
- Increases pickup range and movement speed for:
- (XP drops, attack boost and movement speed): duration: 10 s

---

## 🚧 Features To-Do

### ⚙️ Gameplay
- [ ] Limit maximum number of enemies and drops 
- [ ] Show active boosts in the UI 
- [ ] Add rarity system for upgrades
- [ ] Show the numbers about each upgrade for example: dmg+10
- [ ] screen effect when player gets hit

### ⚔️ Weapons
- [ ] Add more weapons?

### 📋 UI & Menus
- [ ] Add options in the main menu  
- [ ] Add credits in the main menu 
 
---

## 💡 Notes

This is an **early pre-alpha** version of the game. Many features are subject to change as development progresses.

---

