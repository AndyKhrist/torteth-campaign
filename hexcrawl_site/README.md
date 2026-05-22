# The Tavern — D&D 5e Campaign Site

## How to deploy to GitHub Pages

1. Go to github.com and create a free account if you don't have one
2. Click **+ New repository**
3. Name it anything (e.g. `my-campaign`)
4. Set it to **Public** (required for free GitHub Pages)
5. Click **Create repository**
6. Click **uploading an existing file**
7. Drag ALL these files into the upload window at once:
   - index.html
   - player1.html through player6.html
   - dm.html
8. Click **Commit changes**
9. Go to **Settings → Pages**
10. Under "Source" select **Deploy from a branch**
11. Choose **main** branch, **/ (root)** folder → click Save
12. Wait ~60 seconds, then your site is live at:
    `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Renaming players

To rename "Player 1" to your actual character name:
- In GitHub, click on `player1.html`
- Click the pencil (edit) icon
- Press Ctrl+H (find & replace) — replace `Player 1` with the character name
- Commit changes
- Do the same in `index.html` to update the landing page card

## Sharing

- Send each player their specific URL, e.g.:
  `https://yourname.github.io/my-campaign/player1.html`
- Keep `dm.html` URL to yourself
- The index page (`/`) is safe to share with everyone

## Saving character data

Data saves to each player's browser localStorage automatically.
Players should also hit 💾 Save after each session to download a .json backup.
If they switch devices, they use 📥 Import to reload their backup.
