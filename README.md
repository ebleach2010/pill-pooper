# Dose Tracker

A tiny offline checklist for medication doses. One file (`index.html`), no build, no dependencies. Checkmarks are saved in your browser's `localStorage`, so they survive refreshes.

## Put it on your phone

1. Merge this branch into `main` (or whichever branch you want to publish).
2. On GitHub, open the repo → **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. Wait a minute or two. The page shows your URL, usually `https://<your-username>.github.io/pill-pooper/`.
5. Open that URL on your phone.
   - **iPhone (Safari):** Share button → **Add to Home Screen**.
   - **Android (Chrome):** ⋮ menu → **Add to Home screen** / **Install app**.

Open it once with a connection and it keeps working offline after that. You can also just open `index.html` directly from disk.

## Things to know

- Data lives in that one browser on that one device. A different phone or browser starts fresh. Clearing site data wipes your checkmarks.
- Times are your device's local time (the schedule is written for America/Boise).
- "Reset all" at the bottom clears every checkmark, then re-checks the two doses taken before the app existed.
