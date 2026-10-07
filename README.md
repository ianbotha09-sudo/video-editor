# ClipForge Mobile Video Editor

A free, mobile-first browser editor starter designed for Android Chrome.

## Publish free with GitHub Pages
1. Create a public repository named `video-editor` on GitHub.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish. Your address will be:
   `https://ianbotha09-sudo.github.io/video-editor/`

## Current features
- Mobile responsive UI
- Select local video/image files and audio
- Video preview and seeking
- Clip list and reordering/removing source clips
- Trim start/end controls
- Text overlay preview
- Playback speed and volume controls
- 9:16, 16:9, square export canvas
- Experimental WebM export for a selected video clip with text overlay and optional music
- Save/load project settings (media files are not embedded)

## Notes
- No account, subscription, paid API, or backend is required.
- Files are handled locally by the page; the page does not upload your media.
- The export workflow is experimental because browser MediaRecorder/audio behavior varies across Android devices. This is a starter, not a full nonlinear editor: it does not yet stitch several clips into one finished video, and image clips cannot be exported.
- GitHub Pages is free for public repositories. No custom domain is needed.
