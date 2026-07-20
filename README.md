# Falldental v1.0.0 - Sovereign Professional-Service Workflow Tool 2026

> **Falldental is a browser-run, single-file workflow tool for professional-service teams in version 1.0.0, bringing together offline case handling, US law research, conflict checks, and audit-friendly record keeping.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathanywpoadams5203/falldental-record-tool?style=flat-square)](https://github.com/nathanywpoadams5203/falldental-record-tool)

---

<p align="center">
  <a href="https://nathanywpoadams5203.github.io/falldental-record-tool/">
    <img src="https://img.shields.io/badge/Download-Falldental%20Latest-brightgreen?style=for-the-badge" alt="Download Falldental">
  </a>
</p>

> **[Direct Download - Falldental v1.0.0](https://nathanywpoadams5203.github.io/falldental-record-tool/)**

---

[Download Latest Build](https://nathanywpoadams5203.github.io/falldental-record-tool/)

---

## What Falldental Does

Falldental is built for professional-service operations that need organized records without a backend stack. The application runs fully in the browser, keeps data in IndexedDB on the local device, and ships as one HTML file that is simple to distribute or host.

It gives teams a place to manage treatments, clients, advisers, and firm records while keeping research and day-to-day workflow steps in the same place. Offline use is supported, local conflict checking is available, and audit-focused tracking helps preserve a clearer activity trail.

---

## Capabilities

- Single-file HTML application that opens directly in the browser
- Offline-first design with IndexedDB as the main persistence layer
- No server requirement and no telemetry route
- Treatment, client, adviser, and firm record management
- Included US law research corpus with strategic weaves for reference work
- Conflict scanning across local records, plus BroadcastChannel sync support
- Hashed audit entries and exportable P3 audit chains
- Advice issuance with sha256 signing and retention support

---

## Getting Started

1. Download or clone the repository to your local machine.
2. Open the main HTML file in a modern browser, or host it as a static file if you prefer.
3. For the quickest start, launch the page and allow the app to initialize its local IndexedDB store.

Example:

    git clone https://github.com/nathanywpoadams5203/falldental-record-tool.git
    cd REPO

Then open the single HTML entry file in your browser.

---

## How to Use It

Falldental is meant for direct, local workflow management.

A common path looks like this:
1. Open the app in the browser.
2. Create or import client, adviser, firm, or treatment records.
3. Run conflict scans against local data before issuing advice or updating records.
4. Use the law research corpus and related reference material while working through a case.
5. Review hashed audit entries or export a P3 audit chain when you need a traceable record.

When more than one browser tab is open, BroadcastChannel sync can help keep local state aligned across sessions.

---

## Settings and Local State

Falldental stores its primary data inside the browser.

Typical settings and state are handled through:
- IndexedDB for local persistence
- Browser storage permissions
- In-app workflow settings for records, research, and audit behavior

If you want to reset the app, clearing site data in the browser removes the local IndexedDB store and any related saved state.

---

## Requirements

- A modern browser with IndexedDB support
- JavaScript enabled
- Enough local storage space for records, research content, and audit history
- Optional: static file hosting if you want to share the single-file build as a web app

---

## FAQ

**Does Falldental need a backend?**  
No. It is intended to run entirely in the browser using local storage.

**Can it be used offline?**  
Yes. The tool is designed for offline use and operates as a single-file application.

**Where is the data stored?**  
Data is kept locally in IndexedDB inside the browser.

**How do updates work?**  
Replace the local file or hosted build with the newer version, then reopen the app. Existing browser data may remain unless you clear site storage.

**What should I do if the app does not load?**  
Check browser compatibility, confirm JavaScript is enabled, and verify that local storage is available for the site.

**How do I manage configuration or reset state?**  
Use the app's settings if available, or clear the browser's site data to remove local records and start fresh.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
