# 🎾 Padel Tournament Manager

A lightweight and fully client-side web application to create, manage, and track amateur padel tournaments directly in the browser.

No backend, no installation — just open and play.

---

## 🚀 Overview

This app allows you to:

- Create a tournament with 8 players
- Automatically generate balanced random teams
- Assign custom team names
- Enter match results
- Automatically compute standings in real time
- Persist data using browser storage

---

## 🧩 Key Features

### 🎲 Tournament Setup
- Input exactly 8 players
- Randomized team generation (4 teams of 2 players)
- Editable team names before saving

### 🎾 Match System
- Predefined round-robin match schedule
- Simple score input per match
- Automatic validation of played matches only

### 📊 Standings
- Live ranking system
- Points system:
  - Win = 2 points
  - Draw = 1 point
  - Loss = 0 points
- Only completed matches are counted

### 💾 Persistence
- Uses `localStorage`
- Data remains after refresh or browser restart

---

## 📂 Project Structure

```bash
.
├── index.html   # Main dashboard (matches + standings + navigation)
├── draw.html    # Player input + team generation (tournament setup)
└── README.md    # Project documentation