# Tally (web app)

A personal budget app that runs from your iPhone Home Screen. No Mac, no Xcode, and it never expires.

## One-time setup (about 10 minutes)

1. Go to github.com and create a free account (or sign in).
2. Click **+** at the top right, then **New repository**. Name it `tally`, leave it **Public**, and click **Create repository**.
3. On the new repository page click **uploading an existing file**. Drag in everything inside this folder:
   `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` and the `icons` folder. Click **Commit changes**.
   (If `.nojekyll` is hidden on your computer, skip it. The app works without it.)
4. Open **Settings → Pages**. Under **Branch** choose `main` and `/ (root)`, then **Save**.
5. Wait a minute or two, then refresh that page. It shows your address, like `https://yourname.github.io/tally/`.

## Put it on your iPhone

1. Open that address in **Safari** on your iPhone.
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open Tally from the Home Screen icon and use it from there.

Enter your spending in the Home Screen app, not in the Safari tab. iPhone keeps the two separately, so
anything typed in Safari will not show up in the Home Screen app.

## Good to know

- Your spending is saved only on your phone, inside the Home Screen app. The repository is public, but it
  holds only the app itself, never your data.
- Removing Tally from the Home Screen erases its data. Use **Settings → Backup → Save a backup file**
  now and then, and **Restore from a backup file** to bring it back.
- It works with no signal once it has been opened one time.

## Updating the app later

Upload the new `index.html` to the same repository (**Add file → Upload files**, then **Commit changes**).
The next time you open Tally with a connection it loads the new version. Your data stays.
