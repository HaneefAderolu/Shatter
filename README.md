Shatter

A small browser game where you throw glowing balls at walls of glass and watch them explode. I made it because I loved Smash Hit and wanted to see if I could build something in that spirit that runs from a single HTML file, on a phone or a laptop, with nothing to install.

It's not a copy. The core idea is the same (smash the glass, don't crash into it, don't run out of balls), but I added my own things on top: bank shots off the walls, bomb glass, armored glass, bosses and a 20-level story mode.

Play it: 

How to play

Tap or click where you want to throw. That's the whole control scheme.

You start with 25 balls and every throw costs 1.
Crashing into glass you didn't break costs you 10.
Shoot the floating crystals to get 2 balls back.
When you run out of balls, it's over.

Pause with the II button, or press Esc or P on a keyboard.

Modes

Story mode has 20 levels. You win a level by reaching the golden gate at the end with balls left. Levels unlock as you go, and every one has its own twist: thick fog, sliding gates, low gravity, starting with fewer balls, a flood of power-ups, and so on. Levels 5, 10, 15 and 20 end with a boss, and each boss fights differently (a fixed core, a core that moves, and one with a pulsing shield).

Endless mode is just that. Keep going until you lose. Your best score is saved for each difficulty.

Easy, Medium and Hard only change how fast the glass comes at you.

What you'll run into
Double and triple balls: each throw sends out 2 or 3 balls but still only costs 1.
Invincible: you speed up and plough through everything for a few seconds.
Time Warp: slows the world down, which makes bank shots and bosses a lot easier.
Magnet: crystals and power-ups fly straight to you.
Bomb glass: the red tiles with a glowing core. Break one and it takes the glass around it with it.
Armored glass: silver tiles that need two hits.
Combos and ricochets: chain hits for a multiplier, and bounce a ball off a wall before it hits for bonus points.

There's a power-ups screen in the menu that shows what each icon does.

Running it yourself

It's a single HTML file with no dependencies. You can double click index.html, or serve the folder if you want the install and offline features to work:


If you add it to your home screen from a phone, it opens full screen and keeps working without a connection.

How it's built

Plain HTML, CSS and JavaScript drawn onto one canvas. There are no libraries and no game engine. The 3D look is a hand-written perspective projection: everything has an x, y and z position and gets projected onto the 2D screen. All the sounds are generated with the Web Audio API, so there are no audio files either. Progress and settings live in localStorage.


Credits

Inspired by Smash Hit by Mediocre. I'm not affiliated with them, and no code, art or sound from that game is used here.

License

Copyright 2026 H.fa. All rights reserved.

Please don't copy, redistribute or sell this without asking me first.
