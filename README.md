# SN4KE Online

An online multiplayer snake game inspired by [SN4KE by Hommer](https://hommer.dk) (2003). Play with up to 4 friends anywhere in the world — directly in the browser, no installs needed.

## How to Play

1. Visit the game URL
2. Enter your name
3. Pick a game mode (Free For All, Team Mode, or ⚡ Power-Ups)
4. **CREATE ROOM** → share the 4-letter code (or the link) with friends
5. Friends open the link or enter the code via **JOIN ROOM**
6. Host clicks **START** → 3-2-1 → GO!

### Controls
- **Arrow Keys** or **WASD** to steer
- **Space** to continue between rounds / rematch
- **Escape** or **P** to pause (host only)
- **Shift** to turbo (Power-Ups mode, if enabled)

## Game Modes

- **Free For All** — last snake alive wins the round
- **Team Mode** — Team A vs Team B, any combination (2v2, 3v1, 1v1, etc.)
- **⚡ Power-Ups** — FFA or Teams with toggleable power-ups:
  - ⚡ Speed Boost — move faster for 4 seconds
  - ⭐ Invincibility — pass through other snakes for 4 seconds
  - 👻 Ghost — pass through your own body for 4 seconds
  - 🔥 Turbo — hold Shift for 2x speed
  - 🧱 Obstacles — random blocks on the grid
  - 🌀 Portals — linked teleport pairs

## Host Settings

- **Speed**: Slow / Normal / Fast / Insane
- **Rounds**: Best of 3, 5, 7, or 10

## Technical Details

- **Zero server costs** — uses WebRTC peer-to-peer via PeerJS
- **Minimal latency** — game data flows directly between browsers
- **TURN fallback** — if direct P2P fails (firewalls), relays through Metered.ca TURN servers
- **Single HTML file** — no build step, no dependencies, no framework

## Deploy Your Own

1. Fork this repo
2. Go to **Settings → Pages → Deploy from main branch**
3. Your game is live at `https://yourusername.github.io/sn4ke/`

---

*Inspired by SN4KE by Hommer (Christian Holmsgaard) at Hommer.dk — NOV 2003*
