THE PLAYGROUND PRESS · ISSUE 004: DEAD AIR

RENDER STATIC SITE DEPLOYMENT
1. Download and extract this ZIP.
2. Create or open your GitHub repository for the magazine.
3. Upload the contents of this folder to the repository root (index.html must be at the root).
4. In Render, choose New > Static Site and connect the GitHub repository.
5. Branch: main
6. Root Directory: leave blank
7. Build Command: leave blank
8. Publish Directory: .
9. Select Create Static Site.

No backend, package manager, environment variables or build command are required.
The site is plain HTML/CSS/JavaScript and runs as a Render Static Site.

PACKAGE CONTENTS
- index.html: interactive issue
- issue-004.pdf: printable companion with the same puzzle set and answer key
- cover.svg: original vector cover illustration
- puzzle-data.json: underlying solution data for verification/reference

QA status: See QA-REPORT.txt for the documented puzzle, browser interaction, responsive-layout, and HTML/PDF parity checks. The local Chromium test suite passed 18/18 checks. Browser/device and live-hosting limitations are listed in the report.
