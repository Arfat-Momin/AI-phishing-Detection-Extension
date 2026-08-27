# PhishGuard

PhishGuard is a static phishing-awareness frontend built with plain HTML, Tailwind CSS via CDN, and client-side JavaScript. It includes a polished landing page for phishing education plus a SOC Lab page focused on attack analysis, defense guidance, and training content.

## Overview

This repository is designed as a lightweight front-end project that can be opened directly in a browser. It does not require a build step, package manager, or backend service.

## Features

- Modern, animated landing page for phishing awareness
- Real-time style URL analysis demo
- File analysis demo with drag-and-drop support
- FAQ accordion and feedback modal
- Mobile-friendly navigation
- SOC Lab page with attack education and defensive countermeasures
- Static download link for the included extension archive

## Project Structure

```text
.
├── index.html
├── phish.html
├── PhishGuard.zip
└── README.md
```

## Tech Stack

- HTML5
- CSS3
- Tailwind CSS CDN
- JavaScript
- Google Fonts

## How to Run

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Open `phish.html` to view the SOC Lab page.

If you want to serve the files locally, use any static file server. No dependencies need to be installed.

## Notes

- The URL and file scanning features are demonstration logic implemented on the client side.
- The repository is intended for cybersecurity awareness and educational use.
- Keep `PhishGuard.zip` in the repository if you want the download button in `index.html` to work.

## Git Upload

To upload this project to Git:

1. Initialize the repository if needed.
2. Add the files.
3. Commit with a message such as `Add PhishGuard frontend and README`.
4. Push to your remote repository.

Example:

```bash
git init
git add .
git commit -m "Add PhishGuard frontend and README"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

## Disclaimer

PhishGuard is for defensive awareness, training, and educational demonstration only. It should not be used to facilitate phishing or other harmful activity.
