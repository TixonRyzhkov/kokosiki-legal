# Kokosiki Legal Website

Static legal website for Kokosiki, suitable for GitHub Pages.

## Files
- `index.html` — main page
- `privacy-policy.html` — privacy policy covering AdMob, Firebase / Google Analytics for Firebase, Firebase Crashlytics, and Google Play Billing
- `terms.html` — terms and conditions, including in-app purchases
- `delete-account.html` — data/deletion information (Kokosiki currently does not require accounts)
- `logo.png` — Kokosiki logo

All CSS is embedded directly in each HTML file. There is no external stylesheet.

## Before publishing
1. Replace every `YOUR_EMAIL@example.com` with the real privacy/support email.
2. Verify that the services and SDKs described here match the final Unity build.
3. Complete Google Play's Data Safety form so that it matches the app's actual SDK configuration and this Privacy Policy.
4. If you add account creation later, update the deletion flow to support deletion of the account and associated data.

## GitHub Pages
Put these files in the root of a GitHub repository and enable GitHub Pages. The Privacy Policy URL will be:
`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY/privacy-policy.html`


Crashlytics note:
- The Privacy Policy now covers Firebase Crashlytics because it is planned for the release build.
- Google Play Data Safety should only declare Crashlytics data collection for a version where Crashlytics is actually enabled.
- If you add custom Crashlytics keys, logs, user IDs, or non-fatal events, review the Privacy Policy and Data Safety disclosures again.
