


## AdSense


## Settings

Settings lets visitors choose a custom tab title, upload a custom tab icon, or select a supplied YouTube, Google, Google Drive, or Google Classroom icon preset.

## Deploy

Copy everything in this folder into the repository root, then:

```bash
git add -A
```


## AdSense
The AdSense Auto Ads script is installed site-wide for publisher `ca-pub-4294926180211945`, and `ads.txt` is included. Actual ad serving is controlled by Google; Auto ads must be enabled for the site and the site must be approved/ready in AdSense.
# jnoengamess

## Adding games
Drop each game's folder into `play/` (e.g. `play/slope/`). The folder's main page must be named `index.html`.
The folder name must match the `file` name in the `games` list in `site.js` (e.g. `slope.html` -> `play/slope/`).
Games open through `game.html?g=<folder-name>`. The separate `games/` folder is no longer needed.
