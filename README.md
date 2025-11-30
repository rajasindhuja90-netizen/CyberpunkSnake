Cyberpunk Neon Snake — Neo Tokyo
---
A modern, neon-themed snake game with a cyberpunk aesthetic, inspired by retro arcade classics. Includes dynamic levels, a scoring system, personalized touches, and mobile-friendly controls.


🎮 Features
---

Neon Cyberpunk Theme: Dark, glowing visuals with animated snake segments.

Personalized Gameplay: Enter your name and your crush's name; the first letter of your crush’s name appears as the food.

Level System: Snake speed increases with each level (every 10 points).

Gift System: Collect points to unlock emojis representing gifts (e.g., 🌹, ❤️, 💍).

Highscore Tracking: Saves highscores per player using localStorage.

Responsive Design: Works on desktop and mobile. On-screen touch controls for mobile devices.

Custom Snake Color: Player can choose their favorite snake color.

🕹 How to Play
---

Open the game in a modern browser.

Enter your display name and your crush’s name.

Use arrow keys or WASD to control the snake on desktop.

On mobile, use the on-screen arrows to move.

Collect your crush’s letter (food) to score points and level up.

Avoid colliding with the snake’s body; walls wrap around.

Click Pause to pause/resume the game, Set Snake Color to customize color, or Restart to start over.

📦 How It Works
---

Game Mechanics:-

Grid System: The canvas is divided into cells. Each snake segment occupies one cell.

Snake Movement: Controlled via dir (direction). Updates at each frame according to current speed.

Food & Gifts:-

Food appears randomly on the grid.

Score determines the current “gift” emoji, giving a playful reward.

Speed and Level:-

Base speed starts at 8 frames per second.

Every 10 points, the level increases, and speed gradually rises.

Collision Detection:-

Snake wraps around edges (no wall collision).

Game ends if the snake bites itself.

Rendering:-

Canvas-based Drawing: Uses canvas and 2D context.

Snake segments have a glowing effect.

Food displays the first letter of the crush’s name.

Background grid drawn with subtle lines for a cyberpunk effect.

Controls:-

Keyboard: Arrow keys or WASD

Mobile: On-screen arrows

Buttons: Start, Pause/Resume, Restart, Set Snake Color

🎨 Customization
---


Player can change snake color using the Set Snake Color button.

Highscores are stored per player in the browser.

⚙️ Technical Details
---


HTML5 Canvas for graphics.

Vanilla JavaScript for game logic.

CSS Flexbox & Media Queries for responsive design.

LocalStorage for persisting highscores.

No external libraries required.

📱 Responsive Design
---


Desktop: Use keyboard controls.

Mobile: Touchpad arrows appear for easy control.

All UI elements scale appropriately with screen width.

🔧 How to Run
---


Clone or download the repository.

Open index.html in a modern web browser (Chrome, Edge, Firefox).

Start playing immediately — no installation required.

✨ Future Improvements
---


Add sound effects for eating and leveling up.

Add multiple snake skins or neon trails.

Include online leaderboard using Firebase or Supabase.

Add special bonuses for collecting gifts.
