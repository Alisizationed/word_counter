# Word Counter

A single-file web app that listens through your microphone and counts how many times you say chosen words. It runs fully in the browser, with no install and no account.

## Features

- **Live counting:** tracks any words or phrases you choose, starting with "express" and "internship".
- **Custom words:** add new words with the input box, remove them with ×, and filter the list.
- **Manual correction:** +/− buttons on every word, for when the speech recognition misses or miscounts.
- **Live feedback:** the tile of the word you just said is highlighted, and tiles are sorted by count with a bar showing each word's share.
- **Recording summary:** when you press Stop, it shows the most popular word of that recording.
- **History:** every finished recording is saved in a side panel with its date, length, and per-word counts.

## How to use

1. Open `express.html` in Chrome or Edge (Firefox doesn't support speech recognition).
2. Click **Start** and allow microphone access.
3. Speak. Click **Stop** to see the summary.

## Notes

- Words and history are saved in the browser's local storage, so they persist between visits.
- Each **Start** begins a new recording with all counts reset to 0.
- Chrome sends the audio to Google's speech service, so it needs an internet connection and isn't fully private.
