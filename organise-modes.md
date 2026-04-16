---
layout: default
title: Organise Modes
nav_order: 3
---

# Organise Modes

BatchFile Organiser supports four folder structures. This page shows what each one does and when to use it.

---

## Date source

Whenever a mode includes **Year** or **Month**, the app uses the file's **last modified date**.

Example date:

- `report.pdf` modified in March 2024

---

## Type

Groups files only by category.

Example output:

```text
Images/
Documents/
Videos/
Audio/
Archives/
Code/
Other/
```

Best for:

- Messy folders like Downloads
- General cleanup when you do not care about dates
- Fastest, simplest structure

---

## Year / Type

Adds a year layer before the file category.

Example output:

```text
2024/Images/
2024/Documents/
2023/Videos/
```

Best for:

- Large folders that span multiple years
- Users who want date grouping without too many nested folders

---

## Year / Month

Groups files only by year and month, without a category folder.

Example output:

```text
2024/March/
2024/April/
2023/December/
```

Best for:

- Chronological archives
- Monthly project drop folders
- Users who care more about timeline than file type

---

## Year / Month / Type

Adds the file category inside each month.

Example output:

```text
2024/March/Images/
2024/March/Documents/
2024/April/Videos/
```

Best for:

- Large mixed folders containing many file types across many months
- Users who want the most structured output

---

## File categories

The app sorts files into these categories:

- **Images**
- **Documents**
- **Videos**
- **Audio**
- **Archives**
- **Code**
- **Other**

Anything that does not match a known category is placed in **Other**.

---

## Which mode should I choose?

- Start with **Type** if you want the simplest cleanup
- Use **Year / Type** if you want a clean date split without deep nesting
- Use **Year / Month** if your main goal is timeline-based browsing
- Use **Year / Month / Type** if you want the most detailed structure
