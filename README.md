# Hypertrophy Tracker — Android-friendly app

A mobile-first web app adapted from `Partner_Hypertrophy_Tracker.xlsx`.

## Features
- Four training sessions with load/reps logging and progression cues (loads in lbs)
- Program week and editable start date
- Daily body-weight entries in lbs and a recent seven-entry average
- Weekly measurements in inches: waist, chest, shoulders, arms, and thighs
- Automatic weekly changes and four-check-in/monthly trend averages for measurements and average body weight
- Sleep, joint pain, resting heart rate, and recovery notes
- Cardio log (Zone 2 / HIIT)
- Weekly volume audit
- Local backup export/import

## Install on Android
This folder is a Progressive Web App (PWA). For an app icon and offline use:
1. Put the contents of this folder on a static HTTPS host (for example, GitHub Pages or another static web host).
2. Open the hosted URL in Chrome on your Android phone.
3. Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.
4. Launch it from the new icon. After the first load, the app can work offline.

## Data and privacy
Logs are saved locally in that browser on that device. There is no account or cloud sync. Export a JSON backup from **More** periodically. Clearing browser storage may erase the data. To move to another device, export the backup and import it there.
