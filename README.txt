SCHOLARSHIP ELIGIBILITY CHECKER — PWA

FILES
- index.html: app interface and scholarship checking logic
- manifest.webmanifest: installable app settings
- sw.js: offline cache
- icons/: app icons

HOW TO TEST ON YOUR COMPUTER
1. Extract this ZIP.
2. Open the extracted folder.
3. Double-click index.html to preview the checker in a browser.
   Note: installation and offline features require HTTPS hosting (or localhost).

HOW TO PUBLISH FOR FREE WITH GITHUB PAGES
1. Create/sign in to a free account at https://github.com/
2. Create a new public repository, e.g. scholarship-checker.
3. Upload the CONTENTS of this folder (index.html, manifest.webmanifest, sw.js, and icons folder).
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for the published website link shown on the Pages screen.

INSTALL
- Android: open the published HTTPS link in Chrome, then use Install app or
  browser menu > Add to Home screen.
- Windows laptop/desktop: open the link in Chrome or Edge, then click the install
  icon in the address bar (or browser menu > Install this site as an app).
- iPhone/iPad: open the link in Safari > Share > Add to Home Screen.

The app works offline after it has been opened online once and its files have
been cached. Scholarship thresholds currently match the supplied Python code:
grade >= 80, attendance >= 85%, monthly family income <= PHP 20,000.
This app runs the checking locally in the browser; it does not upload student data.
