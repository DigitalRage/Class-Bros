# Super-Class-Bros

Open the secret UCAS button to launch the game. Choose a fighter, stage, and match mode in the HUD; the game includes Canvas, myUVU, training, and a generated open-world map, Smash-style combat, UI Tag, Adventure quests, local CPUs/dummies, and multiplayer rooms.

## Default controls

- A / D: move left / right
- W / S: aim up / crouch, fast-fall, or drop through a platform
- Space: jump
- Q: shield / dodge
- Shift: fighter class movement
- Left Arrow: light / tilt attack
- Right Arrow: smash attack
- Down Arrow: ranged special
- Up Arrow: recovery special
- Backquote key: enter or leave the game

Open **Settings** to rebind controls. Bindings are saved on this device. Touch controls are shown on mobile and coarse-pointer screens, and gamepads are supported.

## Music

The optional music player is available in **Settings → Music player**. It supports track selection, play/pause, previous/next, seek, volume, mute, shuffle, playlist/track/off loop modes, and an optional top-left mini player. Music can be played on either stage.

Tracks are read from `assets/music/`. The game attempts to discover MP3s from a server directory listing; GitHub Pages does not expose directory listings, so its known tracks use explicit relative paths in `MUSIC_TRACK_PATHS` in `index.html`. When adding a track for GitHub Pages, add its path there as well as the MP3 file. Browsers block playback when the page is opened with `file://`; use GitHub Pages or a local web server.

## Gameplay and multiplayer

- Fighters have distinct movement abilities, specials, shields, dodges, and Smash-style combat.
- Solid surfaces, walls, and slopes have collision; semisolid platforms can be dropped through.
- The myUVU portal stage scrolls vertically to keep the player near the center of the view; manual scrolling is also supported, with a floor at the bottom of the stage.
- Remote player positions and animation states are synchronized, and Tag/Fight modes use separate room channels.
- The HUD includes fighter selection, host stage/mode controls, rooms, player customization, and training dummy reset.
- Choose **Adventure** from the mode picker to explore a hand-drawn fantasy world with five biomes, collect starlight shards, and complete the Wayfinder quest. The generated map spans 25 viewports wide by 8 tall (200 times a normal viewport's area); use **A/D** to explore and **E** near the Wayfinder in Moonbloom Vale to interact. Touch players can use **TALK**.
