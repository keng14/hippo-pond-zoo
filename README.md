# 🦛 Hippo Pond Zoo

A 2D browser game. Pick a fruit, then tap a hippo when its mouth is wide open.
Throw while the mouth is closed and you lose a life.

เกมป้อนผลไม้ให้ฮิปโป เลือกผลไม้ แล้วแตะฮิปโปตอนอ้าปากกว้าง ถ้าโยนตอนปากปิดจะเสียหัวใจ

**Play / เล่นเลย:** https://keng14.github.io/hippo-pond-zoo/

## Features

- 4 missions: 2 hippos, 3 hippos, 3 picky hippos (each asks for a specific fruit), and LV MAX with 15 hippos
- Choose mouth speed: Slow, Medium or Fast
- Four fruits: 🍎 🍌 🍉 🍊
- Win and lose effects, stars, and a progress bar
- Thai / English language switch
- Background music and sound effects
- Works on desktop and mobile, no install, no dependencies

## Controls

| Action | Input |
| --- | --- |
| Choose fruit | Tap a fruit, or keys `1` `2` `3` `4` |
| Feed a hippo | Tap the hippo, or keys `Z` `X` `C` (hippo 1, 2, 3) |

## Run locally

Open `index.html` in a browser. Fonts load from Google Fonts, so use an internet connection for the intended look.

## Publish with GitHub Pages

1. Upload `index.html` and `README.md` to the repository root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. The game goes live at `https://<username>.github.io/<repo>/` in a minute or two.

## Tech

Plain HTML, CSS and JavaScript with the Canvas API. All game code is in one file.

## License

MIT. See [LICENSE](LICENSE).
