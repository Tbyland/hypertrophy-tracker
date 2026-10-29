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


Version 4: Weight view now calculates average gain/loss per 7 days by comparing averages across two consecutive 7-calendar-day windows anchored to the latest weigh-in date.


## Version 5 additions
- Exercise-by-exercise progress summaries based on actual logged sets, not averages alone.
- Compares total reps and tracked volume with the previous logged performance and shows up to four recent sessions.
- Keeps individual set weights and reps. Dumbbell entries are per dumbbell; barbell and plate-loaded machine entries exclude the empty bar or machine starting resistance.
- Retains Version 4's 7-day body-weight trend and all existing app features.
- Existing local data uses the same storage key. Export a JSON backup before updating as a precaution.
