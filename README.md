# Driving Test German

A small web app for learning the German words used in the practical Class B driving test (Fahrerlaubnisprüfung), with English meanings.

It covers all 108 terms from the word list published by the Bundesvereinigung der Fahrlehrerverbände (BVF) in *Fahrschule* 7/2018.

## What you can do

- **Cards**: flashcards styled like German road signs. Words you miss come back sooner.
- **Quiz**: 10 multiple-choice questions, German to English or English to German.
- **Listen**: hear the German like the examiner says it, then pick the meaning. There is a slow speed.
- **Words**: the full list with search and audio for every word.

A word counts as known after three right answers in a row. Progress is saved in your browser.

## Install on your phone

The app is a PWA and works offline after the first visit.

- **Android (Chrome)**: open the site and tap **Install app**, or use the menu and choose **Add to Home screen**.
- **iPhone (Safari)**: tap the Share button and choose **Add to Home Screen**.

## Files

- `index.html`: the whole app
- `manifest.webmanifest`: app name and icons
- `sw.js`: offline support. Change `CACHE` when you update the app so phones get the new version.
- `icons/`: app icons

The word list is a guide, not a complete or legally binding vocabulary.
