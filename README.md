# MusicWave 🎵

A modern, responsive music player website built with **HTML, CSS and vanilla JavaScript**. No Node.js, npm or build step is required.

## Features

- Responsive desktop + mobile UI
- Music player with play/pause, next/previous
- Progress bar and volume control
- Shuffle and repeat
- Search songs, artists and albums
- Like/favourite songs with `localStorage`
- Chill Vibes and Workout playlist filters
- Light/dark theme toggle
- Local demo audio files
- Local SVG album artwork
- GitHub Pages ready

## Run locally

Open `index.html` in a browser.

For best results, use a small local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Upload to GitHub Pages

1. Create a new GitHub repository.
2. Upload all files/folders from this project.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`.
6. Save and wait for GitHub Pages to publish.

## Add your own songs

Put MP3/WAV files inside:

`assets/audio/`

Then edit `assets/js/app.js` and add a song object:

```js
{
  id: 7,
  title: "Your Song",
  artist: "Your Artist",
  album: "Your Album",
  cover: "your-cover.svg",
  audio: "your-song.mp3",
  genres: ["Chill Vibes"]
}
```

For a real public website, only upload music you own or have permission/licensing to distribute.

## Project structure

```text
musicwave-github/
├── index.html
├── README.md
└── assets/
    ├── audio/
    ├── covers/
    ├── css/
    │   └── style.css
    └── js/
        └── app.js
```
