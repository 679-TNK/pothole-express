# Pothole Express

A small 2D arcade game in the browser. You drive a yellow express bus down a three-lane highway and swerve around potholes while the bus keeps getting faster.

**Play it:** `https://your-username.github.io/pothole-express/` ← replace this with your GitHub Pages link

## How to play

- **On a phone:** touch the road and slide your finger left or right. The bus follows your finger.
- **On a computer:** steer with **←** **→** or **A** / **D**.
- Each pothole you hit costs one tyre. You have three, and the run ends when the last one goes.
- Grab the yellow **+** token to fix a tyre. If all three are fine, it gives you bonus distance instead.
- Your score is the distance you drive, in kilometres. Your best run is saved on your device.

| Key | Action |
| --- | --- |
| ← → / A D | Steer |
| P / Esc | Pause or resume |
| M | Sound on or off |

## Features

- A main menu with a How to play screen
- A pause button, so you can stop, restart or quit at any time
- Settings for sound on/off and steering sensitivity (1 = gentle, 5 = twitchy)
- Turn indicators that blink on the bus and on the dashboard when you steer
- Sound effects made in the browser: engine hum, indicator ticks, pothole thuds and a pickup chime
- Difficulty that keeps rising: more potholes, bigger potholes, and rows that leave only one lane open
- Works on phones and computers, and pauses itself if you switch away

## Run it yourself

The whole game is one file, `index.html`. There is nothing to install or build. Open the file in any modern web browser to play.

To publish your own copy on GitHub Pages:

1. Upload `index.html` to a public repository.
2. Go to **Settings → Pages**, set the branch to **main** and the folder to **/(root)**, and click **Save**.
3. After a minute or two, your game's link appears at the top of that page.

## Built with

Plain HTML, CSS and JavaScript, drawn on a `<canvas>`. Sound uses the Web Audio API. The fonts are Bungee and Barlow Condensed from Google Fonts. No libraries or game engines are used.
