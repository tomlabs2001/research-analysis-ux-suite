# Research Analysis Suite v2026 - UX research analysis tool 2026

> **Research Analysis Suite is a browser-based UX research analysis tool for organizing study evidence, mapping interactions, and exporting findings in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tomlabs2001/research-analysis-ux-suite?style=flat-square)](https://github.com/tomlabs2001/research-analysis-ux-suite)

---

<p align="center">
  <a href="https://tomlabs2001.github.io/research-analysis-ux-suite/">
    <img src="https://img.shields.io/badge/Download-Research%20Analysis%20Suite%20Latest-brightgreen?style=for-the-badge" alt="Download Research Analysis Suite">
  </a>
</p>

> **[Direct Download - Research Analysis Suite v2026](https://tomlabs2001.github.io/research-analysis-ux-suite/)**

---

[Download Latest Build](https://tomlabs2001.github.io/research-analysis-ux-suite/)

---

## Overview

Research Analysis Suite gives UX teams and independent practitioners a web-based workspace for reviewing research assets. It combines several analysis activities, including card sorting, heat map inspection, affinity diagramming, and field guide note capture, so evidence can stay in one flow instead of being split across multiple apps.

Because it is packaged as a single-file web application, the project is straightforward to open, share, and keep with the rest of your study files. That makes it a practical HTML and JavaScript option when you want to convert raw usability testing inputs into organized outputs that can be exported and referenced later.

---

## What it includes

- Card sorting workflows for arranging participant input
- Click-tracking heat map visualization for interaction review
- Structured field guide observations for research notes
- Affinity diagramming to group findings and themes
- User flow transcription with annotations for session mapping
- CSV export for moving data into other tools
- Single-file browser app for simple distribution and launch
- Built for UX research, usability testing, and analysis handoff

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/tomlabs2001/research-analysis-ux-suite.git
2. Open the project folder:
   - `cd tds-research-analysis-suite`
3. Start the app by opening the main HTML file in a browser, or run the folder through any local web server if you want a hosted development setup.

---

## Usage

A typical workflow looks like this:

1. Open the app in a modern browser.
2. Load or enter research material for the study you are reviewing.
3. Use card sorting, affinity diagramming, and user flow transcription to structure observations.
4. Review click-tracking heat maps to inspect interaction patterns.
5. Export results as CSV when you need to share or archive findings.

Example local server option:

- `python3 -m http.server`

Then visit the local address shown in your terminal and open the app from there.

---

## Configuration

This project stays intentionally lightweight as a single-file browser app, so most settings live in the app state and in whatever data you load during a session. If you modify the source, keep the HTML and JavaScript together so the workflow remains portable and easy to distribute.

If you plan to embed the tool in another site or environment, check the script and data handling sections in the HTML file so you can adjust defaults, export behavior, and any study-specific labels.

---

## Requirements

- A modern web browser
- HTML and JavaScript support
- Optional local web server for development or file hosting
- Enough storage for loaded research notes and exported CSV files

---

## FAQ

**How do I get started?**  
Open the app in a browser and begin with the research artifact you want to analyze.

**Can I update the tool manually?**  
Yes. Replace your local copy with the latest repository version or refresh the hosted build when a new release is available.

**Where are settings stored?**  
Configuration is handled within the browser app and the project files you use to run it.

**What should I do if the app does not open correctly?**  
Try a different browser, serve the folder from a local web server, and confirm that the HTML file and associated scripts are present.

**Can I export data?**  
Yes. CSV export is included for moving results into external spreadsheets or analysis pipelines.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
