# gidis-number-game

A number guessing game — **Gidi's Number Game** by Gidi Heritage.

## Play

Open `index.html` in any browser, or serve the folder:

```sh
python3 -m http.server 3000
```

and visit the page. No build step, no dependencies — it's a single HTML file.

## Features

- **Three difficulty levels** — Easy (1–10, 5 tries), Medium (1–50, 7 tries), Hard (1–100, 8 tries)
- **Limited tries per round** — win before your tries run out, or the secret number is revealed
- **Scoring & streaks** — earn points based on tries left and difficulty; consecutive wins multiply your score
- **Best score** saved per difficulty in your browser (localStorage)
- **Warm/cold feedback** — see if each guess gets you closer, plus a narrowing range and guess history
- **Hint** — reveals whether the number is even or odd (halves your round score)
- **Celebrations** — confetti on a win, plus sound effects with a mute toggle
- **Responsive design** — works on phones and desktops, respects reduced-motion settings
