PALDOWP launcher (for the iPhone home screen)

1. Put these files on GitHub Pages (free):
   - github.com -> New repository, name it e.g. "paldowp" (Public).
   - "Add file" -> "Upload files" -> drop index.html, apple-touch-icon.png, icon-192.png, icon-512.png -> Commit.
   - Settings -> Pages -> Source: "Deploy from a branch", Branch: main, folder / (root) -> Save.
   - After a minute your page is at https://<your-username>.github.io/paldowp/

2. On your iPhone, open that page in Safari. Paste your PALDOWP link
   (Apps Script -> Deploy -> Manage deployments, the one ending in /exec) and tap "Make my launcher link".
   (Or put the link in index.html at: const APP_URL = '...'; before uploading.)

3. Tap Share -> Add to Home Screen. Remove the old PALDOWP icon, and open the app from the new one.

If it shows a Google sign-in problem inside the app, open the /exec link once in Safari and sign in,
then try the icon again. If it still can't sign in, Safari is blocking Google sign-in inside the launcher;
keep using the old icon (and tell Claude).
