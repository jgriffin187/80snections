# 📼 '80sNections

**The ultimate 80s music connections game.**

![Neon Teal](https://img.shields.io/badge/vibe-Neon%20Arcade-2de2e6?style=flat-square) ![Games](https://img.shields.io/badge/games-100-c724b1?style=flat-square) ![Daily](https://img.shields.io/badge/play-1%20per%20day-f7d716?style=flat-square)

One puzzle per day. Same game for everyone. Covers the entire 80s music universe — songs, artists, MTV VJs, movies, albums, and more.

### How to Play
- A new puzzle unlocks every day at midnight
- Group the 16 tiles into four categories of four
- **4 mistakes** allowed before game over
- After finishing, a countdown shows time until tomorrow's puzzle
- Your progress is saved locally — no account needed

### What's Covered
- **Artist spotlights** — Michael Jackson, Madonna, Prince, Whitney Houston, Cyndi Lauper, Duran Duran, The Police, U2, Bon Jovi, Def Leppard, and many more
- **Genre categories** — New Wave, Hair Metal, Synth-Pop, British Invasion, 80s Hip-Hop, Power Ballads
- **MTV VJs** — the original five and beyond
- **#1 Hits by year** — 1980 through 1989
- **80s movie soundtracks** — *Top Gun*, *Footloose*, *Dirty Dancing*, *The Breakfast Club*, and more
- **Live Aid performers** (1985)
- **Famous 80s albums**
- **Themed categories** — songs with colors, cities, animals, numbers, girl names, and more
- **Letter-of-the-alphabet categories**

### Sounds
Fully synthesized 8-bit arcade sounds using the Web Audio API — no audio files needed. Every action has its own sound:
- Tile select/deselect — blip sounds
- Correct answer — ascending fanfare
- Wrong answer — descending wah-wah
- One away — teasing wiggle
- Win — full victory jingle
- Lose — sad trombone
- Shuffle — cascading beeps

### Secret Dev Menu
**Triple-tap the '80sNections logo** to open the dev menu:
- **⏭ Skip to Next Game** — advance to tomorrow's puzzle for testing
- **🔄 Reset to Day 1** — wipe progress and start fresh

---

## 🚀 Deployment

Both games are single `.html` files. To deploy on GitHub Pages:

1. Add the HTML file(s) to your repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Rename the file to `index.html` if you want it to load at the root URL

Your game will be live at `https://yourusername.github.io/your-repo-name/`

---

## 🛠 Technical Details

- Pure HTML, CSS, and vanilla JavaScript — zero dependencies
- No build step, no bundler, no npm
- All game data is embedded directly in the file
- Daily puzzle uses `localStorage` to track played state (per device/browser)
- Audio generated entirely with the Web Audio API
- Works on desktop and mobile including iOS Safari

---

## 📁 Files

| File | Game | Size |
|------|------|------|
| `80snections.html` | '80sNections | ~95 KB |

---

*Built with Claude. Inspired by the NYT Connections game.*
