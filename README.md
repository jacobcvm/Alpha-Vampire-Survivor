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
   - 5% chance to drop at least 1 gold    
2. **Anomaly**
   - 20% chance to drop at least 10 gold
3. **Dead**
   - Moves fast
   - 30% chance to drop at least 50 gold
4. **Flying Demon**
   - Very tanky  
   - Fires ranged fireball attacks
   - retreats slowly when the player is too close  
   - Drops a chest that grants a level-up
   - moves slowly
   - 50% chance to drop at least 250 gold
   - doesn't change his movement when he attacks
5. **Knight Boss**
   - Has his own a health bar
   - Extremely Tanky
   - has rotating ice shards around him
   - moves fast
   - has melee attacks
   - Always Drops at least 1000 gold 
   - makes you level up several times in a row 

#### Enemy Behavior
- All enemies:
  - touching enemies makes the player take damage over time
  - enemy attacks are deadly
  - Become black when hit and are pushed back from the slash attack
  - stop moving to use their attacks when they're in range
  - Spawn outside the screen and move toward the player
  - Spawn more frequently as time passes
  - new spawns give more xp, gold, gain better hp, movement speed and damage every minute.
  - Stronger enemies spawn less often than the weaker ones
  - The player becomes black when hit by any of their attacks
  - Drop XP on death  

### 🔹 Magnet Mechanic
- XP and gold will follow the player when within range until it is collected

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
- (XP drops and gold): duration: 10 s

---

## 🚧 Features To-Do

### ⚙️ Gameplay 
- [ ] Show active boosts in the UI 
- [ ] Show the numbers about each upgrade for example: dmg+10
- [ ] OPTIONAL: Add a stats menu after death to know the performance of each weapon
- [ ] OPTIONAL: Improve visuals of the menus
- [ ] OPTIONAL: Add a mini health bar above the head of the main character that only appears when you're not full health
- [ ] OPTIONAL: Add rarity system for upgrades

### ⚔️ Weapons
- [ ] find a better sprite for the slash attack

### 📋 UI & Menus
- [ ] Add options in the main menu  
- [ ] Add credits in the main menu 
 
---

## 💡 Notes

This is an **early pre-alpha** version of the game. Many features are subject to change as development progresses.

---

