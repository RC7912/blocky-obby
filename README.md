# Blocky Obby

A Minecraft-style obby (obstacle course) generator that runs in your browser — with chaotic tweenslop animations, emotes, and online multiplayer.

▶️ **Play it here: https://rc7912.github.io/blocky-obby/**

## Features

- **Endless courses** — every seed makes a different obby. Pick the number of stages and the difficulty (Easy / Normal / Hard).
- **Obstacles** — jumps, thin beams, moving platforms, spinners, slime bounce pads, zigzags, disappearing glass, lava floors and magma strips.
- **Minecraft look** — pixel textures for grass, dirt, sand, snow, stone, bricks, planks, gold, emerald and diamond, plus blocky clouds.
- **Double jump** — press jump again in the air.
- **Skins** — 8 characters, or make your own with custom colors, trails and neon glow.
- **Tweenslop animation** — squash and stretch, flips, bobble head, screen shake and meme popups.
- **Emotes** — dance, wave, dab, floss, sit, cheer, breakdance, laugh, play dead… or explode 💥.
- **Multiplayer** — everyone on the same course plays together, with name tags and chat.
- **Music and sound effects**, with a song that plays when you stand still.

## Controls

| Key | Action |
| --- | --- |
| W A S D | Move |
| Space | Jump (press again in the air to double jump) |
| Mouse (click the game first) | Look around |
| Mouse wheel | Zoom |
| Q / E | Turn the camera |
| 1 – 9 | Emotes |
| X | Explode 💥 |
| T or Enter | Chat |
| R | Respawn at checkpoint |
| M | Music on/off |

On phones: drag the left side of the screen to move, drag the right side to look, and tap **JUMP**.

## Playing with friends

Multiplayer joins everyone who is on the **same course** (same seed, stages and difficulty).

1. Make a course you like.
2. Click **Copy link** and send it to your friends.
3. When they open it, you'll see them in the game and the top right shows how many people are online.

Players connect directly to each other (WebRTC peer-to-peer via [Trystero](https://github.com/dmotz/trystero)); public relays are only used to help players find each other. Don't share personal info in chat — anyone on the same course can see it.

## Running it yourself

It's a single HTML file with no build step. Download the repo and serve the folder with any static web server, for example:

```bash
python3 -m http.server
```

Then open http://localhost:8000.

## Made with

- [three.js](https://threejs.org/) for 3D graphics
- [Trystero](https://github.com/dmotz/trystero) for multiplayer
- Web Audio API for the sound effects and beat
- Fonts: Press Start 2P and VT323 from Google Fonts
