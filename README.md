# Blocky Obby

A Minecraft-style obby (obstacle course) generator that runs in your browser — with chaotic tweenslop animations, emotes, and online multiplayer.

▶️ **Play it here: https://rc7912.github.io/blocky-obby/**

## Features

- **Endless courses** — every seed makes a different obby. Pick the number of stages and the difficulty (Easy / Normal / Hard).
- **Obstacles** — jumps, thin beams, moving platforms, spinners, slime bounce pads, zigzags, disappearing glass, lava floors, magma strips, conveyor belts, slippery ice and sweeping magma pillars.
- **Five worlds** — Overworld, Nether, Frozen Peaks, The End and 🪟 Windows XP (Bliss sky and hills, window and taskbar platforms, Start-button checkpoints), each with its own blocks, sky and floating particles. Pick one or let the seed choose.
- **Power-ups** — ⚡ speed boost, 🦘 super jump (with a triple jump) and 🛡️ a shield that saves you from one lava hit.
- **Coins and a hat shop** — grab 🪙 along the course; they're banked when you finish, plus a finish bonus. Spend them on hats like a crown, top hat, halo or a spinning propeller cap.
- **Best times and ghosts** — your best time per course is saved, and a see-through 👻 ghost replays your best run so you can race yourself.
- **Daily challenge** — one course per day that's the same for everyone, so it's a good place to meet other players.
- **Minecraft look** — pixel textures for grass, dirt, sand, snow, ice, stone, bricks, planks, netherrack, end stone, purpur, obsidian, XP windows, gold, emerald and diamond, plus blocky clouds.
- **Double jump** — press jump again in the air.
- **Skins** — 8 characters, or make your own with custom colors, trails and neon glow.
- **Two art styles** — switch between blocky Roblox-style and a round paper-cutout South Park style in the menu. Your skin colors work with both, and other players see the style you picked.
- **Tweenslop animation** — squash and stretch, flips, bobble head, screen shake and meme popups.
- **Emotes** — dance, wave, dab, floss, sit, cheer, breakdance, laugh, play dead… or explode 💥.
- **Multiplayer** — everyone on the same course plays together, with name tags and chat. Press **🏁 Race** for a countdown race where everyone restarts together and finishers are ranked 🥇🥈🥉.
- **Settings** — volume, music, look sensitivity, field of view, and toggles for shadows, screen shake, meme popups, speed lines and the ghost.
- **Music and sound effects**, all made in code with the Web Audio API. The music plays while you move and goes quiet when you stand still.
- **AFK sleeping** — leave the game alone for 20 seconds and your character lies down on the floor and snores 💤. Press any key to wake up.

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

### Servers

Click **🖥️ Servers** (in the menu or on the title screen) to see every server that has players right now: its name, how many people are on it (up to 25), and its course. Click **Join** to hop in.

To make your own, set up a course in the menu, type a name under **New server** and click **Create & join**. **Copy link** also shares the server, so friends land in the same one. Everyone starts on the **Main** server for their course, and making a new course takes you back to Main.

Want to play solo? Click **🌐 Multiplayer on** in the menu to switch to **📴 Offline mode** — you won't connect to anyone, and the game remembers your choice. Click it again to go back online.

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
