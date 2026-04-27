Retro Snake: The Nokia Tribute
A nostalgia-driven recreation of the iconic Nokia Snake game, built with modern JavaScript for the mobile-first web.

 The Inspiration
As a creative developer, I often find myself looking back at the "simpler" era of tech. I missed the tactile, high-stakes feeling of playing Snake on a monochromatic Nokia screen. This project started as a way to bring that 90s aesthetic back to life while ensuring it feels fluid and responsive on modern smartphones.

 Features
Authentic Aesthetic: Hand-picked color palette (#94af13) and monochromatic sprites to mirror the original LCD experience.

Mobile-First Design: Custom on-screen D-pad controls designed for thumb-play, using onpointerdown events for zero-latency input.

Responsive Game Loop: Powered by requestAnimationFrame with a custom throttle to maintain that classic grid-based "snap" movement.

Persistent High Scores: LocalStorage integration to keep your "HI" score safe between sessions.

Retro Splash Screen: A 3-second animated "SNAKE GAME" loading sequence to set the mood.

 Technical Stack
HTML5 Canvas: For high-performance pixel rendering.

CSS3: Utilized for the "blinking" game-over animations and the splash screen loading bar.

Vanilla JavaScript: Zero dependencies. Pure logic for collision detection, snake growth, and food randomization.

 Getting Started
This project is a single-file application, making it incredibly lightweight and easy to deploy.

Clone the repo:

Bash
git clone https://github.com/Ayomide-cmd/snake-game.git
Open index.html in any modern web browser.

(Optional) Deploy to GitHub Pages via Settings > Pages to play on your mobile device.

🎮 How to Play
Desktop: Use the Arrow Keys to steer.

Mobile: Use the on-screen directional buttons.

Goal: Eat the round fruit to grow. If you hit a wall or yourself, it's Game Over!

🧑‍💻 Creative Developer's Note
This project was an exercise in "less is more." By restricting the color palette and using a simple grid, I focused on the core game feel—ensuring the snake turns exactly when the player expects it to. It’s a tribute to the games that made many of us fall in love with technology in the first place.

Built with 💚 and nostalgia by Ayomide.
