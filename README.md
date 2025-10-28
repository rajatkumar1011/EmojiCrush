Project: EmojiCrush Console
URL: rajatkumar1.me/EmojiCrush

Project Overview

EmojiCrush Console is a static, single-page web application that reimagines the classic match-3 game as a futuristic, high-tech console. It is designed to be visually "unrealistic" and sleek, prioritizing aesthetics and a unique user experience through a combination of modern web technologies.

The entire application is self-contained in a single HTML file, demonstrating robust front-end development without any backend dependencies.

Key Features

Sleek Glassmorphism UI: The main console panel uses semi-transparent backgrounds, backdrop filters (blur), and glowing borders to create a "glass" effect, making it appear to float over the animated background.

Dynamic Particle Background: Utilizes the tsparticles library to generate a complex, interactive field of moving and connecting particles, giving the page a "live" and futuristic feel.

Generative Audio: Integrates Tone.js to create synth-based sound effects for key game actions (gem swap, match, invalid move). This avoids static audio files and enhances the "console" aesthetic.

Fully Responsive Design: The game grid and all UI elements are fully responsive. The layout uses a combination of Tailwind CSS, clamp(), and vmin units to ensure the game looks and plays perfectly on all devices, from mobile phones to desktops, with no scrollbars.

Robust Game Logic: The core game logic is built in pure JavaScript, handling:

Grid generation with no initial matches.

Player input (gem selection and swapping).

Adjacent-only swap validation.

Match detection (3-in-a-row, horizontal and vertical).

Cascading matches and chain reactions.

"Gravity" physics for gems falling into empty spaces.

Refilling the board with new gems.

Score and move tracking.

Game over state and modal.

High-Tech Theming: The "Orbitron" Google Font is used throughout to maintain a consistent, sci-fi/console theme.

Animated Transitions: All game actions (gem swaps, matches, new gem-fills) are accompanied by smooth CSS animations (@keyframes) for a polished user experience.

Technology Stack

HTML5: Serves as the structural foundation.

Tailwind CSS (CDN): Used for all styling, layout, and responsiveness.

JavaScript (ES6+): Powers all game logic, state management, and DOM manipulation.

tsparticles (CDN): A lightweight library for creating the animated particle background.

Tone.js (CDN): A Web Audio framework used to generate all sound effects in real-time.
