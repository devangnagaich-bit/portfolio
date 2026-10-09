# Deskwatch: Study Focus Monitor

**Live app:** https://devangnagaich-bit.github.io/portfolio/deskwatch/  
**Source code:** [deskwatch/index.html](../deskwatch/index.html)

A study session monitor that watches for stillness, tab-switching and app-switching, and turns it into a focus score. It is one self-contained HTML file with no libraries.

## Features

- **Camera stillness watch:** compares small camera frames locally and raises an alert after 25 seconds without movement
- **Tab-switch and window-switch watch:** logs every time you leave the study tab or window
- **Sound alerts:** short synthesized beeps with a different tone for each distraction type, no audio files
- **Session timer** with subject picker (Physics, Chemistry, Mathematics, Biology, English, Computer Science, Other), pause and end
- **Live focus score** and distraction-event count, plus a timestamped distraction log
- **Stats dashboard:** time studied today, day streak, sessions logged, average focus score, a 7-day bar chart and time by subject

## Privacy

Camera video never leaves the page. Motion is measured with a pixel-difference check, and nothing is uploaded or recorded. Session data is stored only in the browser's local storage.

**Tech:** HTML, CSS and vanilla JavaScript (getUserMedia, Web Audio, Page Visibility API, localStorage)
