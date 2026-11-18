# ROADLEDGER — Stage 4 & 5 Deployment Guide

## 1. Connect Google Sheets (Stage 4)
1. Open your **ROADLEDGER Database** Google Sheet.
2. Go to **Extensions → Apps Script**, delete any default code, paste the contents of `Code.gs`, and save.
3. Click **Deploy → New deployment → Web app**:
   - **Execute as:** Me
   - **Who has access:** Anyone
4. Copy the generated **Web App URL** (`https://script.google.com/macros/s/.../exec`).
5. In the ROADLEDGER app, open **Settings → Data Management**, paste your Web App URL, and tap **Save & Sync Now**.

## 2. Host on GitHub Pages & Install on iQOO 15R (Stage 5)
1. Upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` to a GitHub repository.
2. Enable **Settings → Pages → Deploy from branch (`main`)**.
3. Open your GitHub Pages URL in **Chrome on your iQOO 15R**, tap the browser menu (**⋮**), and select **Add to Home screen / Install app**.
