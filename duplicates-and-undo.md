---
layout: default
title: Duplicates and Undo
nav_order: 4
---

# Duplicates and Undo

BatchFile Organiser can identify exact duplicate files and help you keep only the copy you want.

---

## How duplicate detection works

A duplicate group is a set of two or more files with **identical content**.

The app narrows candidates by file size first, then confirms exact duplicates with **SHA-256 hashing**. If two files land in the same duplicate group, their contents match exactly.

---

## What you can choose

For duplicate groups, you can use one of these presets:

- **Keep Newest**
- **Keep Oldest**
- **Keep Largest**
- **Keep Smallest**

You can also manually override any group and choose the exact file you want to keep.

---

## What the preview shows

Before applying changes, the preview shows:

- Which file from each duplicate group will be kept
- Which copies will be removed
- How much storage space will be recovered

This lets you verify your choices before anything changes on disk.

---

## What happens during apply

When you apply changes:

- Files being organised are moved into their new folders
- Duplicate copies selected for removal are moved aside as part of the undo system

This is important because it means the app can restore them during undo.

---

## How undo works

After a completed run, the summary screen offers **Undo**.

Undo restores:

- Files moved during the last operation
- Duplicate copies that were removed during the last operation

Undo works on the **most recent** operation only.

---

## Tips for safer duplicate review

- Prefer **Keep Newest** when you're cleaning working folders with revisions
- Prefer **Keep Oldest** when you want the earliest original copy
- Use manual override when filenames are similar but context matters
- Review duplicate groups carefully before applying changes in folders with important personal files
