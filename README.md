# Scene Studio

A single-file, in-browser video editor. Build scenes from images, video clips and narration, add captions, music and voiceover, then export a video. No build step and no dependencies.

## Run locally

Open `src/index.html` in a browser, or serve the folder:

    npx serve src

## Deploy

Vercel serves the `src` folder (set in `vercel.json`). Push to the connected branch and it redeploys.

## Notes

- Export records the canvas in real time, so a 30 s video takes about 30 s to export. Keep the tab open.
- Uploaded images and videos are not saved across reloads. Text, timing and settings are.
- Uploaded video clips are silent in preview and export.
