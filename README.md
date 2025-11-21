# SepidZ Business Intelligence Platform – System Design

<div align="center">

![SepidZ Business Intelligence Platform

<br/>

<a href="https://github.com/vasei-me/business-intelligence-software/raw/main/cover.png">
  <img src="https://github.com/vasei-me/business-intelligence-software/raw/main/cover.png" width="600"/>
</a>

</div>

<br/><br/>

> **A comprehensive Business Intelligence (BI) solution** for the SepidZ restaurant management ecosystem  
> Complete architectural documentation using **PlantUML** – fully editable and live-rendered in VS Code

---

## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Prerequisites](#prerequisites)
- [VS Code + PlantUML Setup](#vs-code--plantuml-setup)
- [How to View & Edit Diagrams](#how-to-view--edit-diagrams)
- [Diagrams Catalog (10 UML + Bonus Diagrams)](#diagrams-catalog)
- [Best Practices & Tips](#best-practices--tips)
- [Contributing](#contributing)
- [Security Notes](#security-notes)
- [License](#license)

---

## Project Overview

This repository contains the **complete system design** of **SepidZ Business Intelligence (BI)** platform, developed as the final project for the Software Engineering course under supervision of **Dr. Hojjat Fazayeli** (Academic Year 1404-1405 / 2025-2026).

The system transforms raw transactional data from SepidZ POS into actionable insights using:

- Kimball dimensional modeling
- CRISP-DM methodology
- Modern ETL pipelines (FastAPI, React, PostgreSQL, Redis, Docker, AWS)

All diagrams are created with **PlantUML** for maximum maintainability and collaboration.

---

## Features

- 4 Core UML diagrams (Sequence, Component, Deployment, Sprint Plan)
- 9 Bonus diagrams for extra credit:
  - 3 Collaboration Diagrams
  - 3 State Machine Diagrams
  - 3 Activity Diagrams
- Live preview in VS Code
- Automatic PNG/SVG export on save
- Fully version-controlled

---

## Prerequisites

| Tool         | Minimum Version | Download / Install Command                         |
| ------------ | --------------- | -------------------------------------------------- |
| VS Code      | Latest          | https://code.visualstudio.com/                     |
| Git          | 2.30+           | `winget install --id Git.Git -e --source winget`   |
| Java JRE/JDK | 11+             | `winget install Oracle.JDK.21` or Adoptium Temurin |
| Graphviz     | 2.38+           | `winget install Graphviz.Graphviz`                 |

---

## VS Code + PlantUML Setup

### 1. Install PlantUML Extension

```bash
code --install-extension jebbs.plantuml
```

2. Recommended Settings (add to settings.json)
   {
   "plantuml.render": "PlantUMLServer",
   "plantuml.server": "https://www.plantuml.com/plantuml",
   "plantuml.exportFormat": "png",
   "plantuml.exportOutDir": "diagrams-export",
   "plantuml.exportSubFolder": false,
   "plantuml.autoExportOnSave": true
   }

3. Optional: Local PlantUML Server (for offline work)
   java -jar plantuml.jar -http 8080
