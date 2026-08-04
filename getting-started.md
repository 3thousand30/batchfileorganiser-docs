---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started

This guide walks you through organising your first folder with Batch File Organiser.

---

## 1. Install the app

Download and install **Batch File Organiser** from the Microsoft Store. Once installed, launch it from the Start menu.

---

## 2. Pick a folder

Use **Browse** to choose a folder, or start with one of the quick links:

- **Desktop**
- **Downloads**
- **Documents**
- **Pictures**
- **Videos**

The app is designed for folders you actually manage yourself. Some Windows system folders are intentionally blocked to avoid risky changes.

---

## 3. Scan the folder

Click **Scan** to analyze the folder.

The scan shows:

- Total files
- Total size
- Category breakdowns such as Images, Documents, Videos, Audio, Archives, Code, and Other
- Exact duplicate groups and recoverable space

By default, the app scans **top-level files only**. Enable **Include files in subfolders** when you want every accessible file below the selected folder included in the scan.

When recursive scanning is enabled, files are organised into destinations under the selected folder according to the mode you choose. For example, if you select `Downloads` and it contains `X\Image\photo.png` and `X\notes.txt`, **Type** mode moves them to `Downloads\Images\photo.png` and `Downloads\Documents\notes.txt`.

---

## 4. Choose how to organise

In the **Configure** step, choose one of the four organise modes:

- **Type**
- **Year / Type**
- **Year / Month**
- **Year / Month / Type**

The app uses each file's **last modified date** when building year and month folders.

If duplicates were found, you can also choose a keep preset such as **Keep Newest** or manually override any group.

---

## 5. Preview everything first

Before anything changes, Batch File Organiser shows a full preview of:

- Which files will move
- Where each file will go
- Which duplicate copies will be removed
- Which empty subfolders will be removed, when cleanup is enabled
- How much space will be recovered

Use this step to sanity-check the result before applying changes.

---

## 6. Apply changes

Click **Apply** to start the operation.

While running:

- A progress indicator shows overall status
- The app reports moves and duplicate removals
- Partial failures are called out instead of being shown as a full success

If **Remove empty subfolders after organising** is enabled, cleanup runs after the file changes complete. Only subfolders that contained files affected by this run and are empty afterward are eligible. The selected folder itself is never removed.

When complete, you can review the summary and, if needed, undo the last operation.

---

## 7. Undo if needed

If the result was not what you expected, click **Undo** on the summary screen.

Undo restores:

- Files that were moved during the last operation
- Duplicate files that were moved aside during the last operation

Undo applies only to the most recent completed run.

---

## Tips

- Start with a copy of a test folder the first time you use the app
- Close other programs that may be using files in the folder while applying changes
- Review duplicate groups carefully before removing extra copies
- Leave empty-folder cleanup disabled if you use empty folders as placeholders
- Re-run the scan after manual file changes so the preview stays accurate
