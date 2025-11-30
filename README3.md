# Cyberpunk Neon Snake3 — Neo Tokyo

A modern, cyberpunk-styled snake game with coin collection and a ranking system. This version adds **coin-based scoring**, **highscore ranking**, and **level progression**, making the classic snake game more competitive and engaging.

---

## 🎮 Features

* **Cyberpunk Theme:** Dark neon background and bright snake & food colors for a futuristic arcade look.
* **Coin System:** Score points and multiply by the current level to earn coins.
* **Level Progression:** Every 10 points, the level increases, speeding up the snake.
* **Highscore Ranking:** Top scores are stored in browser `localStorage` and displayed in a leaderboard.
* **Responsive Controls:** Play with **arrow keys** or **WASD** on desktop. Mobile support can be added with touch controls.
* **Restart & Pause:** Pause and resume the game at any time; restart starts a new session.

---

## 🕹 How to Play

1. Open the game in a modern browser.
2. Enter your display name in the input field.
3. Press **Start** to begin the game.
4. Use **arrow keys** or **WASD** to control the snake.
5. Eat the food (pink squares) to increase score.
6. Avoid colliding with the snake’s body; the snake wraps around canvas edges.
7. Coins are calculated as `score × level` and displayed in the HUD.
8. Game over occurs when the snake collides with itself, and the ranking board updates automatically.

---

## 📦 Technical Details

* **Languages Used:** HTML, CSS, JavaScript (Vanilla).
* **Canvas Graphics:** Snake, food, and background are rendered using HTML5 Canvas.
* **Dynamic HUD:** Shows score, level, and coins in real-time.
* **Leaderboard:** Saves top scores in `localStorage` and displays the top 5 players.
* **Responsive Design:** Canvas and UI elements adapt to different screen sizes.

---

## ⚙️ Game Mechanics

* **Grid-Based Movement:** The canvas is divided into cells (`CELL = 20`), and the snake moves one cell at a time.
* **Snake Growth:** Eating food increases the snake length.
* **Speed Increase:** Every 10 points, the level increases and the snake speed gradually rises.
* **Edge Wrapping:** Snake appears on the opposite side if it crosses canvas boundaries.
* **Collision Detection:** Game ends when the snake collides with itself.

---

## 🔧 How to Run

1. Clone or download the repository.
2. Open `index.html` in a modern browser.
3. Enter your name and click **Start** to play.
4. Pause, resume, or restart using the corresponding buttons.

---

## ✨ Future Enhancements

* Add mobile touch controls (on-screen arrows).
* Add colorful neon trails for the snake.
* Add power-ups or special collectibles.
* Add online leaderboard using a backend or Firebase.
* Add sound effects for eating food and leveling up.
