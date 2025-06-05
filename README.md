# 🔐 Browser Extension Removal Guide

This repository documents the process of reviewing and removing browser extensions to enhance browser **security** and **performance**.

---

## 📋 Overview

The goal was to identify and remove **suspicious or unnecessary Chrome extensions** by following a structured **8-step review process**.

Four extensions were evaluated:

- **Chrome Remote Desktop**
- **McAfee® WebAdvisor**
- **Google Docs Offline**
- **Privacy Badger**

> 🗑️ **Removed:** McAfee® WebAdvisor (suspicious third-party source, excessive permissions)

---

## 🛠️ How Extensions Were Removed

The process followed the steps in [`browser-extensions/extension_review_process.md`](browser-extensions/extension_review_process.md):

### 1. Opened Extension Manager
- Accessed Chrome’s extension page via `chrome://extensions/`.

### 2. Reviewed Installed Extensions
Listed extensions and their purposes:
- **Chrome Remote Desktop** – Remote access (by Google)
- **McAfee® WebAdvisor** – Web security (third-party)
- **Google Docs Offline** – Offline editing (by Google)
- **Privacy Badger** – Privacy protection (by EFF)

### 3. Checked Permissions and Reviews
- Reviewed permissions in each extension’s **Details** panel.
- Verified **Web Store ratings** (if available).

### 4. Identified Suspicious or Unused Extensions
- **McAfee® WebAdvisor** flagged: Broad permissions + third-party source.
- Others were trusted and in active use.

### 5. Removed Suspicious Extension
Removed McAfee® WebAdvisor by:
- Clicking **“Remove”** in `chrome://extensions/`
- Confirming the removal

### 6. Restarted Browser
- Relaunched Chrome
- Noted **slightly improved performance**

### 7. Researched Malicious Extensions
- Summarized risks (e.g., **data theft, CSP bypass**) in [`browser-extensions/research-on-extensions.md`](browser-extensions/reasearch-on-extensions.md)

### 8. Documented Actions
- Logged details in [`browser-extensions/extensions-log.md`](browser-extensions/extension-log.md)

---

## ✅ Results

### 🗑️ Removed:
- **McAfee® WebAdvisor** – Suspicious source, excessive permissions

### ✔️ Retained:
- **Chrome Remote Desktop** – Trusted, actively used
- **Google Docs Offline** – Useful for offline work
- **Privacy Badger** – Privacy protection from a trusted source

### ⚡ Performance:
- Slight improvement in **browsing speed** after removal

---
