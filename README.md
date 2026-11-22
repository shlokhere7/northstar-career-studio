# Northstar Career Studio

A browser-based career planning app for searching selected job openings, comparing candidate-provided experience with requirements from employer postings, and preparing editable application drafts.

## Run it

Open `index.html` in a modern browser. On first sign-in, the app opens **My Background** so you can enter and save your own information. No build tools or server are required.

## Publish with GitHub Pages

1. Create a GitHub repository containing the files in this folder.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and the root folder, then save.
4. GitHub will show the published site URL in the Pages settings.

## Data and limitations

- The job cards are a small set of employer-page snapshots, checked on November 22, 2026. They are not a live job feed; open the source listing to confirm it is still accepting applications.
- The opening sign-in screen collects a display name and email for a local browser session. The first sign-in opens **My Background** with those two fields filled in; the rest of the profile starts blank. There is no account verification, password, server-side authentication, or per-user data isolation. Do not enter sensitive information.
- Candidate profiles, assessments, reports, and saved drafts use browser `localStorage`. They are not uploaded to this app's server, but browser storage is not encrypted.
- Temporary candidate assessments are kept in memory. Saving another candidate requires a permission confirmation in the app.
- Generated application materials are editable drafts based on entered candidate facts and the selected posting. Review all details before using them.
- This app is a static front end. It does not provide accounts, server-side storage, or automated job API refresh.

## Included files

- `index.html` — complete app, including styling and browser-side behavior.
- `README.md` — setup and deployment notes.
