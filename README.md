# Gala Thermometer

A live fundraiser thermometer for gala events. Runs entirely in the browser — no server, no internet required.

## How It Works

Open `index.html` in Google Chrome. From the launcher, open two tabs:

- **Control Screen** — enter donor names and amounts, track history
- **Display Screen** — the thermometer shown on the projector

Both tabs stay in sync automatically via the browser's localStorage. No setup required.

## Features

- Real-time animated thermometer that fills as donations are recorded
- Donor name + amount ticker at the bottom of the display
- Preset buttons ($25, $50, $100, $250, $500, $1,000) or enter a custom amount
- Undo last donation
- Confetti celebration when the goal is reached
- Customizable animated gradient background with 5 presets and color pickers
- Export / Import JSON backup of all donation data
- Configurable goal amount and event title
- Reset event clears everything including the display ticker
- Fullscreen button on the display screen
- Works completely offline

## Download & Install

1. Go to the [GitHub repo](https://github.com/dowa-hub/gala-thermometer)
2. Click the green **Code** button → **Download ZIP**
3. Unzip the folder anywhere on your computer
4. Open `index.html` in Google Chrome — no installation needed

## Usage

1. Open `index.html` in Google Chrome
2. Click **Open Control Screen** — use this on your laptop
3. Click **Open Display Tab** — send this to the projector
4. Set your goal and event title in the Goal & Settings section, click Save
5. To record a donation: enter donor name (optional), select a preset or type a custom amount, click **GO**

## Requirements

- Google Chrome (required)
- Both tabs must be open in Chrome on the same machine
- Does not work in private/incognito mode (localStorage is restricted)
