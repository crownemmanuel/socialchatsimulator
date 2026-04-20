# Social Chat Simulator

A browser-based **social chat mockup** for demos, tutorials, and video. It includes a **WhatsApp-style** phone UI (editable chat list, typing simulation, optional auto-replies) and a separate **prompt bar** tab with themes (including an animated Aurora border), stage backdrops for green/blue screen or patterned shots, and adjustable typing speed.

**Live site (GitHub Pages):**  
[https://crownemmanuel.github.io/socialchatsimulator/](https://crownemmanuel.github.io/socialchatsimulator/)

## Usage

- Open `index.html` locally in a browser, or use the GitHub Pages URL above once deployed.
- **WhatsApp tab:** Edit chat names (one per line), pick a **chat target**, type the message to **simulate typing** into the composer, and use **Options** for frame size and reply behavior.
- **Prompt field tab:** Pick a theme and backdrop, set typing speed, enter text, then **Simulate**.

### Avatar image

The repo includes `avatar.png` for the Meta AI avatar in the chat list and header. Replace it with your own square image if you like.

## Deploying on GitHub Pages

This repo is configured to publish from the **`main`** branch at the **root** (`/`). If you fork or clone:

1. Push to GitHub on `main`.
2. **Settings → Pages → Build and deployment:** branch **`main`**, folder **`/`**.

The site URL is `https://<user>.github.io/<repo>/`. You can also enable or update Pages with:

`gh api repos/<owner>/<repo>/pages -X POST --input -` (JSON body with `build_type: legacy` and `source: { branch, path }`).

## License

MIT — see [LICENSE](LICENSE).

## Contributing

Issues and pull requests are welcome. Keep changes focused and match the existing single-file HTML style unless you are splitting assets deliberately.
