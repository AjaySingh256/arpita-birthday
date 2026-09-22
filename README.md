# Ajay ❤️ Arpita — Birthday Love Story

Premium cinematic React + Vite experience built for mobile-first sharing.

## Run locally
```bash
npm install
npm run dev
```

## Add your photos
Put photos in `public/images/` using these names (or edit `src/data/memories.js`):
- first-memory.jpg
- long-distance-01.jpg
- long-distance-02.jpg
- call-memory.jpg
- lucknow-01.jpg
- lucknow-02.jpg
- first-meeting.jpg
- first-kiss.jpg
- memory-01.jpg
- memory-02.jpg
- memory-03.jpg
- together-01.jpg
- birthday-memory.jpg

Missing images automatically use a placeholder.

## Add your song
Put your MP3 at:
`public/music/our-song.mp3`

The browser requires a user interaction before audio starts; the opening Play button handles this.

## Edit personal text
- `src/data/memories.js` — timeline and memories
- `src/data/messages.js` — letters, birthday message, final letter and poetry
- `src/data/music.js` — song configuration

## Build
```bash
npm run build
```

## Render deployment
1. Create a GitHub repository and push this project.
2. In Render, choose **New → Static Site** and connect the GitHub repo.
3. Build command: `npm install && npm run build`
4. Publish directory: `dist`
5. Deploy.

No server or environment variables are required.