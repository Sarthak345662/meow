# Nova Music

Upload this whole folder to a GitHub repo, then **Settings → Pages → Deploy from branch → main / (root)**.
Then open the **Actions** tab → *Build DMG* → *Run workflow* once. It creates `downloads/Nova-Music.dmg` (a single file); after that the Mac button downloads only the DMG.

- `downloads/Nova-Music.apk` – Android app (rebuild it to get the new player/login fixes; the web app `/app` already has them)
- `downloads/Nova-Music-Mac.zip` – source for the Mac app; the Action turns it into the DMG
- `app/` – web version (also installable as PWA)

Accounts are stored on each device/browser (no server), so register and log in on the same device.
Admin: `admin@gmail.com`, first password `admin` — change it.
