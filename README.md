# Summit-Run

🏔️ Summit Run 3D

An endless 3D runner set on a mountain trail. You play a hero from a mountain tribe, and a troop of monkeys chases you. Collect dollar coins, dodge obstacles, and survive as the speed keeps rising.

Play: https://claude.ai/artifact/8STFYkWQPgrRatzJAtE2dZ

Gameplay
Run down a three-lane trail through snowy peaks and pine forest.
Every $ coin is one point.
Speed increases as your dollars grow, and the music tempo speeds up with it.
Hitting an obstacle lets the monkeys close in.
A second hit before they fall back means they catch you and the run ends.
The monkeys slowly drop back if you run cleanly, and your best score is saved on your device.
Controls
Action	Keyboard	Touch / mouse
Move left / right	← → or A / D	Swipe left / right, or ◀ ▶ buttons
Jump	↑, W or Space	Swipe up, tap, or ▲ button
Slide	↓ or S	Swipe down, or ▼ button
Start from menu	Enter	PLAY button
Obstacles
Rocks: jump over them.
Low logs: slide under them.
Boulders: change lanes.
Characters
Name	Style
Kaito	Feather chief
Asha	Braided scout
Bhim	Horned hunter

Pick a character in the menu. You can switch again from the game-over screen with Change Character.

HUD
$ is your coin count.
km/h is your current speed.
♥♥ / ♥♡ is your lives. ♥♡ means one more hit ends the run.
♪ mutes or unmutes music and sound effects.
Tech
Single HTML file with no build step.
3D rendering with three.js r128, loaded from cdnjs.
All music and sound effects are generated in the browser with the Web Audio API, so there are no audio files.
Models, textures, coins and mountains are all built in code from simple shapes.
Troubleshooting
Blank page or “Could not load the 3D engine”: check your internet connection and reload, because the 3D library loads from a CDN.
No sound: browsers only allow audio after you click, so press PLAY. Also check that ♪ isn’t muted.
Slow on an older phone: close other tabs, or ask for lower shadow quality and fewer snow particles.
Error message at the bottom of the screen: copy it and report it so it can be fixed.
Ideas for later

Power-ups (magnet, shield), corner turns like Temple Run, more obstacle types, and a global leaderboard.
