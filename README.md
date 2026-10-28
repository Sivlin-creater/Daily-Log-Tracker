# ⏱️ Daily Work & Life Tracker (Offline PWA)

A responsive, single-file personal tracking web application built with vanilla HTML5, CSS3, and JavaScript. Designed for offline use on smartphones and laptops to monitor work hours, daily meal logging, personal expenses, and field notes with photo attachments.

---

## 🌟 Key Features

* **Shift Tracking (Clock In / Clock Out)**: One-tap shift timer logging exact start and end times, complete with automatic duration calculation[cite: 3].
* **Expense & Meal Management**: Categorized tracking for meals, drinks, supplies, and miscellaneous spending with real-time day and month running totals[cite: 3].
* **Interactive Calendar**: Browse historical dates with visual dot badges indicating work shifts or expense activity[cite: 3].
* **Dedicated Work Notes & Photo Log**: Separate tab for freeform job notes, customer orders, project specifications, and local camera image uploads[cite: 3].
* **Online & Offline Translation**: One-tap text translation when connected to Wi-Fi/data, with permanent offline persistence once saved[cite: 3].
* **Multilingual Interface**: Real-time localized interface switching between **English**, **Khmer (ភាសាខ្មែរ)**, and **Chinese (中文)**[cite: 3].
* **Data Privacy & Zero Backend**: 100% client-side storage utilizing browser `localStorage`[cite: 3]. No external databases, tracking, or accounts required.
* **Exports & Backups**:
  * **Excel / CSV**: UTF-8 BOM-encoded `.csv` export compatible with Microsoft Excel[cite: 3].
  * **Print-to-PDF**: Formatted summary table for clean PDF generation via native print dialogs[cite: 3].
  * **JSON Backup & Restore**: Full database snapshot export/import for device migration[cite: 3].

---

## 🚀 Live Demo & Deployment

This application requires no build steps (no Node.js, Webpack, or npm). It runs directly in any modern browser[cite: 3].

### Deploy to GitHub Pages:
1. Fork or clone this repository.
2. In your repository on GitHub, navigate to **Settings** ➔ **Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch` and branch to `main` (folder: `/root`).
4. Access the live URL provided by GitHub Pages (e.g., `https://<username>.github.io/<repo-name>/`).

---

## 📱 Installation on Mobile (Add to Home Screen)

### iOS (Safari):
1. Open the live URL in Safari.
2. Tap the **Share** button (box with upward arrow).
3. Tap **Add to Home Screen**.

### Android (Chrome):
1. Open the live URL in Chrome.
2. Tap the **Three Dots (⋮)** menu in the top right corner.
3. Tap **Add to Home screen** / **Install app**.

Once added, the application opens fullscreen and functions completely offline[cite: 3].

---

## 📂 Project Structure

```text
├── index.html        # Complete single-file application (UI, CSS, JavaScript)
├── manifest.json     # Web App Manifest for mobile fullscreen installation
└── .gitignore        # Git ignore rules

Creator: Sivlin Chhay
