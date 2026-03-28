---
title: Why Decimal Sorting Wins
status: seedling
tags:
  - system-design
  - meta
  - organization
created: 2026-03-28 17:08:26
updated: 2026-03-28 17:13:22
---

# Why Decimal Sorting Wins

Most digital note-takers fall into the **"Folder Shuffle Trap."** They organize by topic (e.g., "Genetics," "Coding"), but as their interests grow, their sidebar becomes a chaotic, shifting mess of a-z sorting. 

To build a system that lasts a decade, we need **Fixed Anchors.**

---

## 🏗️ The System Design: 3-Digit Decimal Sorting
Inspired by the *Johnny.Decimal* system, we use three digits (100, 200, 300) to create a "Neighborhood" for our data.

### 1. Spatial Memory > Alphabetical Luck
When folders are numbered, they never move. `200_Garden` is always in the same physical spot in my sidebar. My brain develops **muscle memory**, allowing me to navigate my library without reading a single word.

### 2. The Accordion Principle (Infinite Scalability)
By jumping from `210_Seedlings` to `220_Incubating`, I leave a "Semantic Gap" of 9 slots. 
* If I need a new category for *Distributed Systems*, I don't re-number the whole vault. 
* I simply slide in `211_Distributed_Systems`.
* The system expands like an accordion without breaking the top-level logic.

### 3. The Identity Firewall
This isn't just about aesthetics; it's about **Security.**
By designating `200_Garden` as the "Public" folder and pointing my web engine (Quartz) strictly there, I create a physical air-gap. My private journals (`300_Vault`) and messy raw thoughts (`100_Capture`) are physically impossible to publish.

---

## 🌿 The "Bottom-Up" Truth
> [!info] The Core Realization
> Organization is a technical debt. If your system requires "Re-orgs" every six months, your system is poorly designed. Decimal sorting is a one-time setup that scales to 10,000+ notes.

---

