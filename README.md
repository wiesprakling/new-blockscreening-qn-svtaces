# Queue Numbers site

## 1. Publish your Google Sheet
Column A = Name, Column B = Queue number (header row on row 1).
File > Share > Publish to web > choose your sheet tab and **Comma-separated values (.csv)** > Publish. Copy the link.

## 2. Add the link
Open `index.html` and replace `PASTE_YOUR_PUBLISHED_CSV_LINK_HERE` with that link.

## 3. Deploy on GitHub Pages
1. Create a new GitHub repo and upload `index.html`.
2. Settings > Pages > Source: "Deploy from a branch" > Branch `main` / `(root)` > Save.
3. Share the `https://<username>.github.io/<repo>/` link.

Only you can edit the repo and the sheet, so visitors can only view.
Edits to the sheet show on the site within a few minutes (Google caches published sheets briefly).
