# Business Intelligence Software – System Design with PlantUML

![VS Code](https://img.shields.io/badge/IDE-VS%20Code-007ACC?logo=visual-studio-code)
![PlantUML](https://img.shields.io/badge/Diagrams-PlantUML-4CAF50?logo=plantuml)
![GitHub Repo](https://img.shields.io/github/stars/vasei-me/business-intelligence-software?style=social)
![License](https://img.shields.io/github/license/vasei-me/business-intelligence-software)

> **A comprehensive Business Intelligence (BI) platform** for **data ingestion, transformation, storage, and visualization**.  
> This repository contains **10 professional UML diagrams** created using **PlantUML** and rendered **live in Visual Studio Code**.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [VS Code + PlantUML Setup](#vs-code--plantuml-setup)
  - [1. Install PlantUML Extension](#1-install-plantuml-extension)
  - [2. Install Graphviz & Java](#2-install-graphviz--java)
  - [3. Configure Settings](#3-configure-settings)
- [How to Use PlantUML](#how-to-use-plantuml)
  - [Live Preview](#live-preview)
  - [Export Diagrams](#export-diagrams)
  - [Auto-Export on Save](#auto-export-on-save)
- [10 UML Diagrams Catalog](#10-uml-diagrams-catalog)
- [Tips & Best Practices](#tips--best-practices)
- [Contributing](#contributing)
- [Security Notes](#security-notes)
- [License](#license)

---

## Project Overview

This project provides a **complete architectural blueprint** of a modern **Business Intelligence system** using **standard UML 2.5 diagrams**.

All diagrams are:
- Written in **PlantUML syntax** (`.puml` files)
- **Editable in real-time**
- **Rendered instantly** in VS Code
- **Version-controlled** with Git

> **Goal**: Deliver **clear, maintainable, and professional documentation** for developers, architects, analysts, and stakeholders.

---

## Prerequisites

| Tool        | Minimum Version | Installation Command |
|-------------|------------------|------------------------|
| **VS Code** | Latest           | [Download](https://code.visualstudio.com/) |
| **Git**     | 2.30+            | `winget install --id Git.Git` |
| **Java**    | 11+ (JRE/JDK)    | Required by PlantUML |
| **Graphviz**| 2.38+            | Required for rendering |

---

## VS Code + PlantUML Setup

### 1. Install PlantUML Extension

1. Open VS Code
2. Press `Ctrl+Shift+X` → **Extensions**
3. Search: `PlantUML`
4. Install: **PlantUML by Jebbs** (most popular)

> Or via terminal:
> ```bash
> code --install-extension jebbs.plantuml
> ```

---

### 2. Install Graphviz & Java

#### Windows (Recommended: Winget or Chocolatey)
```powershell
# Using Winget
winget install Graphviz.Graphviz
winget install Oracle.JDK.17

# Using Chocolatey
choco install graphviz
choco install jdk17