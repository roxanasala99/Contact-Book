# Contact Book: put it online and install it on your phone

This takes about 10 minutes and costs nothing. Your contacts are **not** uploaded anywhere. Only the app itself goes online. Contacts are saved on your phone.

## 1. Put the app online (GitHub Pages, free)

1. Unzip `contact-book.zip` on your computer. You'll get a folder with `index.html`, `manifest.webmanifest`, `sw.js` and an `icons` folder.
2. Make a free account at github.com.
3. Click **+** (top right), then **New repository**. Name it `contact-book`, choose **Public**, and click **Create repository**.
4. On the next page, click **uploading an existing file**. Drag in **everything inside** the folder, including the `icons` folder. Click **Commit changes**.
5. Go to **Settings**, then **Pages** (in the left menu). Under "Branch", pick **main** and **/ (root)**, then click **Save**.
6. Wait a minute or two, then refresh. The page shows your link, which looks like
   `https://YOUR-USERNAME.github.io/contact-book/`

Public here means people could see the app's code. Your contacts are never in it.

## 2. Install it on your phone

**iPhone:** open the link in **Safari**, tap **Share**, then **Add to Home Screen**, then **Add**.
**Android:** open the link in **Chrome**, tap **⋮**, then **Add to Home screen** or **Install app**.

**Important:** install it first, then add contacts *from the home-screen icon*. On iPhone, the installed app keeps its own storage, separate from Safari.

## 3. Keep a backup

Tap **Backup**, then **Save backup file**, and save it to Files, iCloud Drive or Google Drive, or email it to yourself. To move to a new phone, install the app there and tap **Backup**, then **Restore from backup**. The app tells you when your last backup is more than a month old.

**Export as spreadsheet (CSV)** gives you a file that opens in Excel or Google Sheets.

## Updating the app later

Upload the new `index.html` to the same repository, replacing the old one. Your phone picks up the new version the next time you open the app with internet. Your contacts stay where they are.
