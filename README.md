# 🎮 Steam Hype vs. Player Retention Engine

### Analyzing the long-term popularity and player retention of Steam games.

Steam Hype vs. Player Retention Engine is a Django-based analytics application designed to examine how video games retain their player bases after launch.

The platform collects live concurrent player counts, imports historical player data, and analyzes changes in player activity over time.

Rather than looking only at a game's launch popularity, the project focuses on a more interesting question:

**Does a game maintain its player base after the initial launch hype fades?**

---

## 📸 Application Screenshots

### 1. Home Page

Introduces the platform and its purpose.

![Steam Retention Homepage](assets/homepage.png)

### 2. Games Dashboard

Displays tracked games and their player activity, including CS2, Apex Legends, Dota 2, ELDEN RING, GTA V, and PUBG.

![Steam Retention Dashboard](assets/dashboard.png)

### 3. Individual Game Analysis

Displays historical player-count charts and detailed activity information for individual games.

![Steam Retention Game Details](assets/game-details.png)

---

## ✨ Key Features

- **Live Player Tracking:** Collects current concurrent player counts using the Steam Web API.
- **Historical Data Import:** Imports historical player-count data from SteamCharts.
- **Player Snapshots:** Stores collected player counts over time for historical analysis.
- **Historical Peak Analysis:** Compares current activity against a game's historical player peak.
- **Retention Analysis:** Examines current player activity relative to historical peaks.
- **Trend Analysis:** Calculates player-count changes over 7-day and 30-day periods.
- **Game Classification:** Categorizes games according to their activity levels and player trends.
- **Interactive Charts:** Uses Chart.js to visualize historical player activity.
- **Automated Collection:** Supports scheduled player-count collection through Windows Task Scheduler.
- **Game Management:** Supports adding and tracking Steam games using their application IDs.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application logic and data analysis |
| Django | Backend web framework |
| SQLite | Database and player snapshots |
| Chart.js | Historical data visualization |
| Steam Web API | Live concurrent player counts |
| SteamCharts | Historical player-count data |
| HTML & CSS | User interface |
| JavaScript | Interactive frontend functionality |

---

## ⚙️ How It Works

The application follows a data collection and analysis workflow:

1. **Game Registration:** Games are added using their Steam application IDs.
2. **Historical Import:** Historical player-count records are imported.
3. **Live Collection:** Current concurrent player counts are collected from Steam.
4. **Snapshot Storage:** Player counts are stored with timestamps.
5. **Metric Calculation:** The application calculates activity levels and player-count trends.
6. **Visualization:** Results are presented through dashboards and individual game charts.

---

## 🎯 Project Objective

The main objective is to explore the relationship between launch popularity and long-term player retention.

The project aims to distinguish games that maintain sustained player activity from those experiencing significant declines after launch.

It provides a way to examine player activity using historical data rather than relying solely on launch-day popularity.

---

## 🔒 Source Code

This repository is a **public portfolio showcase**.

The complete application source code is maintained in a separate private GitHub repository and is not included here.

The screenshots and descriptions demonstrate the application's functionality and development work.

---

## 📌 Project Status

The application has a working Django backend, historical data import, automated player collection, retention analysis, and interactive game dashboards.

This project is independently developed and is not affiliated with, endorsed by, or sponsored by Valve Corporation or Steam.

