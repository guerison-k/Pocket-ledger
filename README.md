# Pocket Ledger: install on iPhone (no Mac needed)

This is an installable web app (PWA). Host it once on HTTPS, open the link in Safari on your iPhone, and add it to your Home Screen. It then opens full screen like a normal app and works offline.

## 1. Put it online (free, 2 minutes)
Pick one:
- **Netlify Drop:** on a computer go to app.netlify.com/drop, sign in, drag the `pocket-ledger` folder onto the page. You get a link like https://something.netlify.app
- **Cloudflare Pages:** Workers & Pages > Create > Pages > Upload assets > upload the folder.
- **GitHub Pages:** push the folder contents to a repo, Settings > Pages > deploy from branch.

It must be an https link. Opening index.html straight from Files will not install.

## 2. Install on iPhone
1. Open the link in **Safari** (not Chrome).
2. Tap the **Share** button (square with arrow).
3. Tap **Add to Home Screen**, then **Add**.
4. Open "Ledger" from your Home Screen.

## Notes
- Entries are saved on the phone only. Deleting the app icon or clearing Safari website data erases them. Use Budget > Export CSV to back up (opens the iOS share sheet, save to Files).
- Use the Home Screen icon every time. Data in Safari and in the installed app is stored separately.
- To update after editing files, upload the folder again, then open the app twice.
