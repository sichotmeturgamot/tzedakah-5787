# צדקה תשפ״ז

A tzedakah tracker for a 10,000 NIS goal in year 5787.

The wooden box fills from the bottom as donations are added.
At 10,000 NIS the gold reaches the top of the window.

Every change is written to
donations.json
in your GitHub repository, using the same kind of token as the Sichos admin page.

## Upload these files
index.html
manifest.json
sw.js
favicon.svg
donations.json

## Pages
Settings → Pages → Deploy from a branch → main → / (root)

## Token
GitHub profile menu:
Settings → Developer settings → Personal access tokens → Tokens (classic)
Generate new token (classic)
Enable:
repo
Paste the token into the app once. It stays in this browser only.

If the repository is public, the donation list inside
donations.json
is visible to anyone who opens the repo.
You can write initials instead of full names.
