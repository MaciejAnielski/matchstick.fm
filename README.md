# Matchstick FM — static site

Black-and-white pirate-style site for Cloudflare Pages.

## Deploy (Cloudflare Pages)
1. Create a new Pages project.
2. Select your repo or upload this folder.
3. Build settings: **Framework preset: None**, **Build command: (empty)**, **Output dir: /**.
4. Deploy.

### Replace the mock player with your stream
In `index.html`, add your stream URL as a source inside the `<audio>` tag, e.g.
```html
<audio id="audio" controls preload="none">
  <source src="https://your-stream.example/stream.mp3" type="audio/mpeg" />
</audio>
```
