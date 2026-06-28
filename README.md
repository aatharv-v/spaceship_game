Space Shooter is a browser-based 2D arcade game built entirely in HTML, CSS, and vanilla JavaScript using the Canvas API — no frameworks or libraries.

Gameplay: You control a spaceship at the bottom of the screen, moving left/right and shooting upward to destroy enemies and bosses that fall from the top. Letting them reach the bottom costs you a life.

Core features:

Regular enemies and periodic bosses (with HP bars)
3 power-up types: ⚡ Rapid Fire, 🛡️ Shield, and ❤️ Extra Life
Score combo multiplier for consecutive kills
Level system — every 100 points increases enemy speed and spawn rate
High score saved in localStorage
Polish & visuals:

Parallax scrolling starfield (3 layers)
Plasma bolt bullets with radial gradient glow
Thruster flame particles on the ship
Explosion particles on enemy/boss death
Orbitron sci-fi font throughout
Animated title screen, pause overlay, and game over screen
Lives displayed as ❤️ icons in the HUD
Audio: Procedurally generated sound effects (shoot, explosion, power-up, level-up) via the Web Audio API, plus looping background music.

Controls: Arrow keys to move, Space to shoot, P to pause, R to restart.
