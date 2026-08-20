# GANES

Current GANES web build prepared for GitHub Pages.

## Publish with GitHub Pages

1. Create a public GitHub repository (for example `ganes`).
2. Upload everything in this folder to the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then save.

GitHub will publish the site at a `github.io` address.

## Backend

The app continues to use the existing Supabase project for authentication and cloud data.
The Supabase publishable/anon key in a browser app is expected to be public; security must be enforced by RLS and server-side policies.

## Version

GANES V5.32.0 — Full Achievements
