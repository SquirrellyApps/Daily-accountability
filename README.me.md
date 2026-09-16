# Daily Accountability

A small, private, static web app for a daily checklist and an honest end-of-day record. It works on phones and desktops and has no server, login, or tracking.

## MVP included

- Daily recurring task templates plus one-off tasks
- Start and complete timestamps, with elapsed task time
- Completion rate and unfinished tasks shown as **Missed** in the daily report
- Daily notes
- A configurable in-page end-of-day review prompt and a print-friendly report that the browser can save as a PDF
- Browser-local storage: records stay on the device/browser where they were entered

## Run it locally

Open `index.html` in a browser. For the smoothest experience, serve the folder with a basic local web server (for example, VS Code's Live Server extension).

## Deploy with GitHub Pages

1. Create a new GitHub repository, such as `daily-accountability`, and keep it public if using the free GitHub Pages option.
2. Upload these four files to the repository root: `index.html`, `styles.css`, `app.js`, and `README.md`.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**. Select branch **main** and folder **/(root)**, then save.
5. GitHub will show the published URL after a minute or two. Open it on each device you want to use.

### Important privacy and backup note

GitHub only hosts the app files. Your completed tasks and notes are stored in the browser's local storage, so they do **not** sync automatically between devices and can be lost if browser data is cleared. Download/save the end-of-day PDF if you want a lasting record. A future version could add an opt-in export/import backup or private cloud sync.

## End-of-day use

Set **Daily review** to the time you want to be prompted. While the app is open, it will bring up that day's report at that time; opening the app after that time does the same. Click **Finish day & review**, check the numbers and notes, then choose **Print / save PDF**. In the print dialog, select **Save as PDF** (or your printer) and save the file with that date.
