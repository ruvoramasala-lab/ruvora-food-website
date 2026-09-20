# RUVORA Customer Website

Firebase Hosting package for the RUVORA customer website.

## Files
- `index.html` — customer storefront
- `firebase.json` — Firebase Hosting configuration
- `.firebaserc` — Firebase project alias
- `.github/workflows/firebase-hosting.yml` — GitHub Actions live deployment

The website uses the existing `ruvora-food` Firebase project and listens to Firestore products/settings in real time.

Do not commit any Firebase service-account JSON key. Store it only as the GitHub repository secret `FIREBASE_SERVICE_ACCOUNT`.
