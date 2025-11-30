Cyberpunk Neon Snake2 — Neo Tokyo
---

A modern, neon-themed snake game with a cyberpunk aesthetic. This version enhances customization by allowing players to choose their favorite snake color and improves visual feedback for a more vibrant gaming experience.

🎮 Features
---

Neon Cyberpunk Theme: Dark background with glowing snake segments for a futuristic arcade feel.

Customizable Snake Color: Players can pick their favorite color using the color input.

Dynamic Gift System: Score points to unlock emoji rewards like 🌹, 🌸, ⚡, 🔥, 💧, 🌙, ⭐, ❤️, 💍.

Level System: Every 10 points, the level increases and the snake’s speed gradually rises.

Highscore Tracking: Player highscores are stored in the browser using localStorage.

Responsive Design: Works on both desktop and mobile, with on-screen touchpad controls for mobile devices.

🕹 How to Play
---

Open the game in a modern browser.

Enter your display name in the input field.

Select your preferred snake color.

Use arrow keys or WASD to control the snake on desktop.

On mobile devices, use the on-screen arrows to navigate.

Collect the emoji “food” to score points.

Avoid colliding with the snake’s body; the snake wraps around edges.

Use the Pause, Restart, and Set Color buttons to control the game.

📦 How It Works
---
Game Mechanics:-

Grid-Based Movement: The canvas is divided into cells; the snake occupies one cell per segment.

Snake Growth: Eating the food increases the snake length.

Speed & Level: Base speed starts at 8; speed increases with each level for added challenge.

Gift System: Each score corresponds to an emoji gift displayed in the HUD.

Rendering:-

Canvas & 2D Context: All graphics drawn using HTML5 Canvas.

Glowing Snake Effect: Snake segments have shadows and glow based on hue cycling for a dynamic neon effect.

Food Representation: Food is displayed as a colorful emoji, changing based on the score.

HUD: Shows current score, level, and glowing gift emoji.

Collision Detection:-

Self-Collision: Game ends if the snake collides with itself.

Edge Wrapping: The snake appears on the opposite side if it crosses canvas boundaries.

⚙️ Technical Details
---

Languages Used: HTML, CSS, JavaScript.

No External Libraries: Vanilla JavaScript for full compatibility.

LocalStorage: Saves highscores per player.

Responsive Design: CSS media queries handle mobile layouts and touch controls.

📱 Responsive & Mobile Controls
---

Desktop: Keyboard arrows or WASD.

Mobile: On-screen touchpad for directional control.

UI elements adapt to screen size using CSS.

🔧 How to Run
---

Clone or download the repository.

Open index.html in a modern browser (Chrome, Firefox, Edge).

Enter your name, select a snake color, and start playing immediately.

✨ Future Enhancements
---

Add sound effects for eating food and leveling up.

Add multiple snake skins or neon trails.

Implement online leaderboards using Firebase or Supabase.

Add power-ups or special bonuses for collecting gifts.

Just some things changed.
