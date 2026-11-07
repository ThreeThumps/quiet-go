# Quiet Go

A relaxed game of Go for your phone, against a computer you can tune to your strength.

Open `index.html` in any browser, or host the folder on any static web host to install it as an app.

## Put it on your iPhone home screen

1. Open **https://threethumps.github.io/quiet-go/** (served by GitHub Pages from `main`).
2. Open the site in **Safari**, tap **Share → Add to Home Screen**, then **Add**.
3. Launch it from the icon. It opens full-screen, with no Safari bars, and works offline after the first visit.

Updates arrive automatically the next time you open it with a connection. Games and settings are stored on the phone, separately from Safari and from any other copy of the game.

## Features

- 9×9, 13×13 and 19×19 boards (any size from 5×5 to 19×19 when loading an SGF)
- Play the computer, or two players on one phone
- **10 strength levels.** Levels 1–5 use a fast rule-based player with fewer blind spots at each level. Levels 6–10 add Monte Carlo tree search, reading more at each level.
- **Fine-tune:** reading depth, loose-move rate and how reliably it spots captures and ataris
- **Personality sliders:** style (territory ↔ centre), fighting spirit (calm ↔ aggressive), big moves (local ↔ open areas) and risk (safe ↔ invading)
- Change strength mid-game. Optional auto-adjust: one level up after a win, one down after a loss.
- Japanese (territory) or Chinese (area) scoring, handicap 2–9, a choice of komi
- Undo, hints, and "Who's ahead?" shading
- End of game: the computer guesses which stones are dead, you tap to fix it, then accept the score
- **SGF:** save (copy, file download or the iPhone share sheet) and load (file or pasted text)
- The game is saved in the browser, so you can close it and pick up later
- Silent by default. The optional click sound is set to mix with an audiobook instead of pausing it.

Everything is in one file, with no build step and no server. The engine runs in a background Web Worker.
