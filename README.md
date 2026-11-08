# Live demo

https://shaheersaeed5125.github.io/cropguard-demo/

# CropGuard — public GitHub Pages demo

This folder contains a **static public preview** for teammates and judges. It has the full interactive signup/plan/greenhouse setup, crop search, simulated sensor pairing, automatic tomato green→yellow→orange→red replay, scouting follow-up, recovery, and history.

## Publish on GitHub Pages (free)
1. Create a **Public** GitHub repository, e.g. `cropguard-demo`.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository **root** (not a nested folder). Commit.
3. Repository **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. Wait for GitHub to publish and use the website URL displayed in Settings → Pages. It typically resembles `https://USERNAME.github.io/cropguard-demo/`.
5. Send the website link to teammates.

## Security and limitations
- **Never upload `.env`, Twilio tokens, credentials, or your private working project ZIP.**
- This public preview **does not send SMS** or access a backend. The SMS panel explicitly says preview-only.
- The separate locally running CropGuard project (`http://localhost:3000`) is the one connected to Twilio trial; keep it on your Mac for the live phone demonstration.
- Signup is simulated; no account or payments are created. Use sample phone numbers, not real contact data.
- Greenhouse readings are simulated, not physical sensors or confirmed disease diagnosis.
