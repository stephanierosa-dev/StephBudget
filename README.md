# Household Budget Dashboard

A custom, progressive web app (PWA) designed to manage household cash flow, built with HTML, CSS, JavaScript, and Firebase Firestore.

## Core Features
* **Smart Allocator:** Automatically calculates the safest paycheck to pull recurring bills from without dropping below the user-defined safety buffer.
* **True Ledger Math:** Anchors math to a single real-world bank balance and accurately calculates forward.
* **Soft Archiving:** Hides paid bills from the active dashboard to keep the UI lightning-fast while preserving data in the background for accurate pie charts and analytics. 
* **50/30/20 Analyzer:** Automatically tracks monthly spending against Needs, Wants, and Savings goals.
* **Progressive Web App (PWA):** Installable on mobile devices with local caching and custom icon support.

## Tech Stack
* **Frontend:** Vanilla HTML, CSS, JavaScript
* **Backend/Database:** Google Firebase Firestore (V8 Compat)
* **Hosting:** GitHub Pages
* **Charting:** Chart.js

## Deployment Notes
To use this application, a `firebaseConfig` object must be supplied in the `index.html` file to connect to a valid Firestore database. Database rules must allow basic read/write access.
