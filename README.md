# Dragons-Or-Treasure
# 🐉 Dragons Or Treasure - Java Console Game

A text-based strategy and adventure grid game developed in Java. The player navigates through a 2D coordinate map,
searching for hidden treasures while dodging dangerous dragons, traps, and false exits.
---

## 🎮 Game Overview & Mechanics

The game takes place on a custom 2D grid where coordinates `(X, Y)` represent positions:
* **The Player:** Starts at a randomized safe position and moves using `W` (Up), `A` (Left), `S` (Down), and `D` (Right)[cite: 19].
* **Treasures:** Found at specific coordinates. Accessing a treasure triggers a 4-digit lottery guessing minigame to gain extra loot[cite: 19].
* **Dragons:** Roam specific coordinates. Stepping on a dragon forces the player to pay a bribe using accumulated treasures or risk losing game points[cite: 19].
* **Traps:** Hidden threats that strip away player treasures upon encounter[cite: 19].
* **Exits:**
  * **Escape Route:** Successful exit — Player wins the match![cite: 19]
  * **Cliff Exit:** Tragic end — Game over![cite: 19]
---

## 🛠️ Tech Stack & Concepts

* **Language:** Java (JDK 8+)[cite: 18, 19]
* **Core Concepts Applied:**
  * Modular programming with functions and parameter passing[cite: 19].
  * Control structures (`while`, `for`, `switch-case`)[cite: 18, 19].
  * Random position generators (`Math.random()` & `java.util.Random`)[cite: 19, 20].
  * ASCII art integration for terminal feedback[cite: 19].
---

## 📁 Repository Structure

* `DragonsOrTreasurePart1.java`: Main executable game file containing all logic, grid boundaries, and turn loops[cite: 19].
* **Prototypes & Helper Classes:**
  * `GameInProgram.java`: Testing digit matching and lottery reward calculations[cite: 20].
  * `MakeRondumToDragonY.java`: Validating coordinate generation algorithms[cite: 21].
  * `move_player.java`: Experimental movement validation script[cite: 22].
  * `Trapsl_File.java` & `tryTheProgram.java`: HashSet-based non-overlapping entity spawners[cite: 23, 24].
  * `CreateDiamondShape.java`: Nested loop pattern exercise[cite: 18].
---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Dragons-Or-Treasure.git](https://github.com/YOUR_USERNAME/Dragons-Or-Treasure.git)
