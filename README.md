# Social Chat Simulator

A browser-based **social chat mockup** for demos, tutorials, and video. It includes a **WhatsApp-style** phone UI (editable chat list, typing simulation, optional auto-replies) and a separate **prompt bar** tab with themes (including an animated Aurora border), stage backdrops for green/blue screen or patterned shots, and adjustable typing speed.

**Live site (GitHub Pages):** after you enable Pages on this repo, visit  
`https://crownemmanuel.github.io/socialchatsimulator/`

## Usage

- Open `index.html` locally in a browser, or use the GitHub Pages URL above once deployed.
- **WhatsApp tab:** Edit chat names (one per line), pick a **chat target**, type the message to **simulate typing** into the composer, and use **Options** for frame size and reply behavior.
- **Prompt field tab:** Pick a theme and backdrop, set typing speed, enter text, then **Simulate**.

### Optional asset

Place an optional `avatar.png` (square image) in the project root if you want a custom image for the Meta AI avatar in the chat list and header. If the file is missing, the browser may show a broken image for that slot; you can ignore it or add your own asset.

## Deploying on GitHub Pages

1. Push this repository to GitHub (`main` branch).
2. In the repo: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`**, folder **`/ (root)`**, then save.

The site will be available at `https://<user>.github.io/<repo>/`.

You can also enable Pages via the GitHub CLI (see project setup scripts or run the API call documented in GitHub’s REST API for “Create a GitHub Pages site”).

## License

MIT — see [LICENSE](LICENSE).

## Contributing

Issues and pull requests are welcome. Keep changes focused and match the existing single-file HTML style unless you are splitting assets deliberately.
