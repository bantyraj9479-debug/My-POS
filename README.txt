UNIVERSAL POS — PWA DEPLOYMENT PACKAGE

This is a separate new app. Do not upload it over your old POS repository.

FILES TO UPLOAD TO A NEW GITHUB REPOSITORY:
- index.html
- manifest.webmanifest
- sw.js
- icon.svg

MOBILE DEPLOYMENT:
1. Extract this ZIP on your Android phone.
2. In GitHub, create a NEW public repository named universal-pos-app.
3. Upload all four files directly into the repository root (not inside another folder).
4. Open repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for GitHub Pages to publish. Your URL will look like:
   https://YOUR-GITHUB-USERNAME.github.io/universal-pos-app/
8. Open that HTTPS URL in Chrome. Menu (⋮) > Install app / Add to Home screen.

APK NOTE:
This step publishes the installable PWA. It does not create a native APK yet.
Once the live HTTPS URL works, we can use a PWA-to-APK cloud packaging service as the next step.
Data is currently stored in this browser's local storage. Export a JSON backup before clearing browser/app data.
