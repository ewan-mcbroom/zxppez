# zxppez – portfolio

## Put it online with GitHub Pages
1. On GitHub, create a new public repository named exactly `YOUR-USERNAME.github.io` (your GitHub username).
   Note: the site address includes your GitHub username, so use an account that doesn't show your real name.
2. Click "uploading an existing file" and drag in `index.html` and the `assets` folder. Commit.
3. Go to Settings → Pages. Under "Build and deployment", pick "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at https://YOUR-USERNAME.github.io

## Editing
Everything you'd want to change is near the top of the `<script>` in `index.html`, under "EDIT YOUR INFO HERE":
- `SERVERS`: the Experience server list. One line per server: name, role, address (or ""), members and fallback.
  Each server's icon is loaded live from its address (the same icon as the in-game server list, via api.mcsrvstat.us).
  If a server is offline or has no address, the `fallback` icon is shown. Add `icon: "assets/whatever.png"` to force your own image.
- `MORE`: the line under the list about your other positions.
- `SKILLS`: the 9 hotbar slots.
