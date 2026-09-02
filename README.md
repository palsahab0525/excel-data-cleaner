# Data Cleaner Website

A free, browser-based tool that cleans messy Excel/CSV files — removes duplicates,
fixes inconsistent dates, standardizes text, and flags rows that need review.
Everything runs client-side (no server, no file ever leaves the browser).

## How to run this in VS Code

1. Open this folder in VS Code (`File → Open Folder`)
2. Right-click `index.html` in the Explorer panel
3. Choose **"Open with Live Server"** (if you have the Live Server extension installed)
   - If you don't have it: go to the Extensions tab (left sidebar), search for
     **"Live Server"** by Ritwick Dey, click Install
4. The site will open automatically in your browser at something like `http://127.0.0.1:5500`

**No Live Server extension?** You can also just double-click `index.html` directly
in File Explorer — it will open in your default browser and work fine. Live Server
is only needed if you want auto-refresh while editing the code.

## How to host this for free (so you have a real link to share)

1. Create a free account at [github.com](https://github.com)
2. Create a new repository (e.g. `data-cleaner-tool`)
3. Upload `index.html` from this folder to that repository
4. Go to the repository's **Settings → Pages**, set the source branch to `main`, and save
5. After a minute or two, your live link will appear (something like
   `https://yourusername.github.io/data-cleaner-tool`)

## Files

- `index.html` — the entire website (HTML, CSS, and JavaScript in one file)
