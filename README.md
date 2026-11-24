# FitTrack — Fitness & Recovery Tracker

A free, responsive, static website for tracking gym workouts, football sessions, food/protein, water, sleep, weight and recovery.

## Publish with GitHub Pages

1. Sign in to GitHub and create a new **public** repository, for example `fittrack`.
2. Download and unzip `fittrack-website.zip`.
3. Upload `index.html` and this `README.md` to the repository's root (not inside another folder).
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then Save.
7. Wait a minute or two. GitHub will show your website URL, usually:
   `https://YOUR-USERNAME.github.io/fittrack/`

## How to use

- Open the site and choose **Daily log**.
- Enter one record per date and save. Saving the same date again updates that date.
- Use **History & progress** to review your entries and charts.
- Use **Settings & backup** to change targets and download JSON/CSV backups.
- To move your records to another device, download a JSON backup on the old device and restore it on the new one.

## Data storage and Google Forms

This version uses browser local storage. It does not send your entries to a server, and it does not automatically sync between devices or browsers. Export backups regularly.

You can save a Google Forms URL in Settings as a shortcut. A normal Google Form link does not automatically connect or import the website's data. To automatically send entries to Google Forms/Sheets, a separate Apps Script or other integration would need to be configured.

## Personal targets included

- Starting weight: 55.6 kg
- Initial goal weight: 60 kg
- Protein target: 100 g/day (editable)
- Water target: 2.5 L/day (editable)
- Sleep target: 8.5 hours/day (editable)

These are editable starting points, not medical prescriptions. Adjust food, hydration and training based on your needs, climate, activity and professional advice.
