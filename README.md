# CINEMAMARVEL

A personal Marvel watch tracker that runs in your browser. Track movies and series, manage watch progress, record season and episode progress, and keep your catalogue organised.

## Features

- Marvel catalogue organised into dedicated sections and categories.
- Three-state watch tracking: **Plan to Watch**, **Watching**, and **Watched**.
- Dashboard with progress totals, completion percentage, continue-watching list, and viewing statistics.
- Series cards with seasons and episode progress managed inside each series.
- Add custom titles and edit title details.
- Add or replace poster artwork using an image URL or an uploaded image.
- Personal ratings, notes/reviews, and collection details where supported by the app.
- Search and filter titles by watch status.
- Watch activity/history panel.
- Export and import a JSON backup to move your tracker data between browsers/devices.
- Appearance settings and selectable character/universe themes.
- Optional TMDB integration for poster and series metadata lookup.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox, or Safari).
3. The tracker runs client-side; no build step or server is required for normal local use.

## Publish with GitHub Pages

1. Push the repository to GitHub.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then save.
5. Wait for GitHub Pages to publish the site. The public URL will appear in the Pages settings.

## Data storage and backups

The tracker stores its working data in this browser's local storage. Data does not automatically sync between devices or browsers. Use the app's **Settings → Export backup** option regularly. On another device, open the app and use **Import backup** to restore the JSON file. Importing replaces the current local tracker data, so export a backup first if you need to preserve it.

## Optional TMDB setup

The app can use a TMDB API key for poster and series metadata features. Add your own key through the app's settings. **Never commit your API key, access token, or personal backup file to this public repository.** If you add secrets in future development, keep them out of source control.

This product uses the TMDB API but is not endorsed or certified by TMDB.

## Stable backup

`CINEMAMARVEL-stable-backup.html` is a separate copy of the current HTML version included for rollback. Keep this file updated whenever you intentionally replace the stable release.

## License and trademarks

This is an independent fan-made tracking project. Marvel names, characters, logos, and related marks belong to their respective owners. This project is not affiliated with or endorsed by Marvel, Disney, or TMDB. Add an explicit open-source license only after choosing the license terms you want to use.
