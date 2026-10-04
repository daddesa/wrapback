<h1 align="center">WrapBack</h1>

<p align="center">
  <a href="https://daddesa.github.io/wrapback/">
    <img src="https://img.shields.io/badge/▶_OPEN_IN_YOUR_BROWSER-1DB954?style=for-the-badge&logoColor=black&labelColor=1DB954" alt="Open WrapBack" width="320">
  </a>
</p>

Spotify Wrapped is great, but it has two big flaws:
1. It only drops once a year and vanishes from the app a few weeks later.
2. If you want to see what you were actually listening to years ago, you have to dig through old camera roll screenshots.

**WrapBack** lets you revisit those moments. Just drop in your official Spotify streaming history, and the app rebuilds your summary card with your top tracks, artists, minutes, and genre, styled around the look and feel of past years.

---

## Available Designs

Instead of using a generic layout, WrapBack takes inspiration from past Wrapped releases. As of now, layouts are available for the following years: **2019**, **2020**, **2021**, **2022**, **2023**, **2024**, **2025**.

---

## How It Works

WrapBack only asks you for two things:

1. **Drop your Spotify JSON files** into the upload area.
2. **Click the year** you want to view (you can also select multiple years together to see your combined stats across an entire era).

Everything else happens under the hood:
* **Accurate listening minutes**: Accounts for Spotify's historical cutoff dates (including the mid-November extension for 2023 instead of the traditional Halloween cutoff).
* **Top Artist photo**: Automatically finds high-res artist artwork and renders it in crisp black-and-white.
* **Smart genre deduction**: Analyzes your top tracks and artists to figure out your dominant genre automatically.
* **1-click export**: Downloads a high-res 9:16 PNG (1080x1920), ready to be shared with your friends.

---

## Privacy

Your listening habits are personal. Because of that, WrapBack:
* **Has no backend or database.**
* **Never asks for your account credentials.**
* **Runs entirely inside your browser:** JSON files are parsed on the fly in memory and never leave your machine.
* **100% Client-Sided!**

---

## How to get your Spotify data

If you don't have your streaming files yet:
1. Log into your Spotify account at [spotify.com/account/privacy](https://www.spotify.com/account/privacy).
2. Scroll down to **"Download your data"**.
3. Select **"Account data"** and **Extended streaming history** and submit the request.
4. Spotify will email you a ZIP file within a few days. Inside you'll find files named `Streaming_History_Audio_*.json`.
5. Drop them into WrapBack and revisit your old Wrapped summaries.

---

## Known issues and what's to come

WrapBack is an independent side project built by a statistics & music enthusiast. Sadly, **I'm not a graphic designer**, so the current card designs are my best-effort recreations. They aren't 100% pixel-perfect replicas *yet*, but they capture the spirit of each year.
To make future versions indistinguishable from the official app, the next steps are:
* **High-Res Background Plates**: Replacing pure CSS tricks with authentic, clean background assets.
* **Exact Typography & Alignment**: Calibrating font kerning, letter-spacing, and millimeter-precise coordinates to match the official layout grid.
* **More Archival Years**: Adding accurate templates for the remaining Wrapped editions.

*If you are a designer or Figma wizard and want to help clean up authentic background templates or vector assets, contributions are more than welcome!*

---

## Legal & Disclaimer 

**WrapBack** is an independent, open-source personal project developed solely for educational, archival, and non-commercial purposes.

* **No Affiliation:** This project is not affiliated, associated, authorized, endorsed by, or in any way officially connected with Spotify AB, Spotify USA Inc., or any of their subsidiaries or affiliates.
* **Trademarks & Copyright:** The names "Spotify" and "Spotify Wrapped", as well as related names, marks, logos, emblems, and aesthetic designs are registered trademarks and intellectual property of Spotify AB. Any use of these terms within this project is intended purely for nominative and descriptive purposes under Fair Use guidelines.
* **Zero Data Collection:** WrapBack does not collect, store, log, or transmit any user data or streaming history. All file reading, statistical processing, and image rendering occur strictly client-side within the user's browser.
* **Notice & Takedown:** If you are a copyright or trademark owner and have concerns regarding any visual assets or references used in this project, please contact the repository owner, and the content will be promptly modified or removed.
