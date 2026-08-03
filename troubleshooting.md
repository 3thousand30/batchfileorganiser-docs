---
layout: default
title: Troubleshooting
nav_order: 5
---

# Troubleshooting

---

## "This folder is protected"

BatchFile Organiser intentionally blocks risky Windows locations such as:

- `C:\`
- `Windows`
- `Program Files`
- `ProgramData`
- `AppData`
- `System Volume Information`

These restrictions exist to help prevent accidental changes to Windows, apps, or user profile internals.

Choose a normal working folder instead, such as Downloads, Desktop, Documents, Pictures, or Videos.

---

## The scan found fewer files than I expected

The app scans **top-level files only by default**.

If your files are inside subfolders, enable **Include files in subfolders** before scanning. The nested files will then appear in the scan and be organised under the selected folder according to the chosen mode.

---

## An empty folder was not removed

This is usually intentional. Cleanup removes only subfolders that contained files affected by the current run and are empty after the file changes finish.

An empty folder is kept when:

- It was already empty before the run
- It still contains a file or another non-empty folder
- The cleanup checkbox was not enabled
- A file operation failed or was cancelled

The selected root folder is never removed.

---

## Apply finished with partial success

This means some file operations succeeded and some failed.

Common causes:

- A file was open in another app
- A file was moved, renamed, or deleted after the preview was generated
- A destination path became unavailable or permission-restricted during apply

Close other apps that may be using the files, re-scan the folder, and try again.

---

## Undo is unavailable

Undo is available only after a completed apply operation, and it only affects the **most recent** run.

If you have not applied changes yet, or if there is no saved last operation, there is nothing to undo.

---

## The preview looks different after I changed files manually

If files were added, removed, renamed, or modified after scanning, the original preview may no longer reflect the current folder state.

Run a fresh scan before applying changes if anything in the folder has changed.

---

## The app will not start or crashes on launch

- Ensure you're running Windows 10 or later
- Try reinstalling from the Microsoft Store
- Check whether Windows is pending a restart or update

If the issue continues, [open an issue](https://github.com/3thousand30/batchfileorganiser-docs/issues) with what you were doing and what error you saw.

---

## Still stuck?

Email [hello@3thousand30.com](mailto:hello@3thousand30.com) or [open an issue](https://github.com/3thousand30/batchfileorganiser-docs/issues) on GitHub.
