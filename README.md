# Greetins, I'm Themadhood Pequot  
**Founder & Developer at Themadhood Codes**  
**Python Engineer | Automation Architect | Systems Designer**

I build tools, engines, and automation systems that solve real problems.  
Through **Themadhood Codes**, I focus on creating scalable software, and custom automation tools for both industrial and creative applications.

My work blends practical engineering with large-system architecture — from industrial machine programming to multi-layer simulation engines.

---

## 🔧 What I Do
- **Python Engineering** – automation, backend systems, APIs, toolchains
- **Learn a pro** – automation, backend systems, APIs, toolchains
- **Industrial / Embedded Coding** – machine logic, troubleshooting, system support  
- **Software Architecture** – modular libraries, error systems, maintainable frameworks  
- **Automation & Integration** – repo syncing, Google Sheets workflows, data pipelines  
- **Game & Simulation Engineering** – worldgen, chunk systems, biomes, entity logic
- **Language Adaptability** – familiar with multiple languages (Python, C, C++, Java, Bash, PLC IEC languages, and more) and able to learn new languages rapidly — often within a day or by reviewing existing codebases.

---

## 🚀 Projects by *Themadhood Codes*

### **Pi Panic — Distributed Alert & Response System**
Pi Panic is a modular monitoring and response framework designed to coordinate multiple Raspberry Pi nodes from a central controller.  
Built for reliability and expansion, it supports local-first control with optional remote dashboards and notification layers.

Pi Panic is designed to provide:
- **Node-Based Architecture**  
  Multiple devices reporting status to a master controller  
- **Event Triggers & Escalation**  
  Panic events, alert routing, and severity-based handling  
- **Local UI + Headless Operation**  
  Operates with or without a display, with optional lightweight GUI control  
- **Recoverable Networking**  
  Resilient connections, automatic reconnect, and retry/backoff logic  
- **Integration-Ready Design**  
  Built to connect into additional sensor modules, dashboards, and automation endpoints  
- **Error Module Integration**  
  Structured diagnostics, context capture, and safe-mode behavior when failures occur  

Pi Panic is engineered as a long-term foundation for property-wide monitoring, automation, and rapid-response workflows.

### **Themadhood Pi Environment — Standardized Pi Dev & Runtime Platform**
Themadhood Pi Environment is a standardized Raspberry Pi software foundation that ensures every device shares the same baseline configuration, dependencies, and development utilities.

It exists to solve one core problem:  
**build once, deploy everywhere** across multiple Pi systems without manual rework.

The environment provides:
- **Repeatable Device Baselines**  
  Consistent folders, configs, permissions, and default tooling  
- **Shared Support Modules**  
  Centralized libraries (including Error Modules) reused across Pi apps  
- **Update-Friendly Structure**  
  Designed so core modules can be updated from a single source rather than reinstalled per-project  
- **Service + App Launch Patterns**  
  Standard start methods for CLI tools, GUIs, and background services  
- **Integration Hooks**  
  Ready to connect with RepoSync, Pi Panic, and other Themadhood Codes systems  

This environment is the backbone that keeps multi-device deployments stable, maintainable, and fast to expand.

### **Pi Setup Scripts — Automated Fresh-Install Provisioning**
Pi Setup Scripts is a collection of automated shell scripts used to provision a new Raspberry Pi from a clean state into a fully working Themadhood Codes environment.
This project was created for when cloning a PI SD is not an option.

These scripts are built for speed, repeatability, and low human error — ideal for scaling multiple devices quickly.

Pi Setup Scripts includes:
- **One-Run Bootstrap Setup**  
  A primary setup script that chains install, copy, and configuration steps  
- **Dependency & Tool Installation**  
  Python tooling, system packages, and required runtime components  
- **Project File Deployment**  
  Copies libraries, modules, templates, and app folders into the correct structure  
- **Standard Settings Configuration**  
  Applies consistent defaults across devices (services, permissions, networking rules as needed)  
- **Future-Proof Expansion**  
  Built to plug in additional setup stages without rewriting the core installer  

The goal is simple: take a fresh Pi and turn it into a ready-to-use development or production node with minimal manual work.


### **RepoSync — Automated Repository Management Framework**
RepoSync is a professional-grade automation tool developed by **Themadhood Codes** to eliminate repetitive manual workflows and standardize code deployment across multiple projects and environments.

Designed to support both standalone applications and large, multi-repo ecosystems like the THEMADHOOD Library, RepoSync automates synchronization using git.

RepoSync provides:
- **One-Click Repository Synchronization**  
  Push, pull, merge, update, or replicate entire projects automatically  
- **Cross-Platform Build Support**  
  Includes PyInstaller integration, asset bundling, and executable packaging  
- **Smart Conflict Prevention**  
  Detects mismatched files, missing modules, and outdated dependencies before sync
- **Integrated Error Module Support**  
  Full error logging, <!--upload reporting, -->retry logic, and safe-mode fallback  

RepoSync is designed to scale — from single-file utilities to multi-module frameworks — making it a central tool in the THEMADHOOD development workflow.


### **THEMADHOOD Library**
The THEMADHOOD Library is a multi-language ecosystem engineered by **Themadhood Codes**.  
Each language has its own dedicated library (`_Python`, `_C`, `_CSharp`, `_Bash`, etc.), each containing:

- **Custom error-handling modules**
- **Code templates and scaffolding tools**
- **Reusable logic blocks and problem-solving patterns**
- **Private APIs for internal services** (Google Sheets, Sheets-based databases, metadata stores, automation endpoints)
- **Copy/paste-ready examples** to accelerate development across all projects

This structure allows updates to be made in *one* central repo instead of maintaining duplicated logic across multiple platforms, languages, or environments.

The THEMADHOOD Library acts as the backbone for:
- Application development  
- Engine and simulation systems  
- Automation tools (e.g., RepoSync)  
- Backend utilities 
- Cross-language consistency and rapid prototyping  

### **EVG — Evolutionary Sandbox Board Game & Engine**
EVG began in 2015 as a physical board game where players and mobs evolve, grow, and interact within an open sandbox environment.  
In 2020, development expanded into a full software adaptation, transforming EVG into a modular, programmable game engine built on top of the THEMADHOOD Library.

EVG blends elements of Zombicide-style tactical gameplay with D&D-style character progression, while remaining completely open-ended and evolution-driven.

The EVG engine includes:
- **Player and Mob Evolution Systems**  
  Growth paths, stat progression, skills, and adaptive traits  
- **Dynamic Combat & Interaction Logic**  
  Turn structure, action resolution, modifiers, and reactive events  
- **Item, Class, and Ability Frameworks**  
  Modular systems for equipment, roles, powers, and unique builds  
- **Sandbox Gameplay Architecture**  
  No fixed narrative; players shape the world through actions  
- **Entity Management**  
  Players, mobs, objects, loot, interactables, triggers, and hazards  
- **Simulation Backbone**  
  Event pipelines, turn order, effect stacking, and world updates  

EVG is not a world generator.  
It is a **complete sandbox game system** with its own ruleset, evolution mechanics, and programmable framework — the generator is simply one tool the engine can use.

EVG continues to evolve as a long-term flagship project within the THEMADHOOD ecosystem.


### **Themadhood Codes Error Module Framework**
Every THEMADHOOD Library includes its own custom Error Module — a full diagnostic and recovery framework designed to maintain stability, protect user data, and provide developers with actionable information.

Key Features:
- Error Categorization
- Central Error Dispatcher
- Error Codes & Tags
- Structured Error Objects
- User-Friendly Message Layer
- Automatic Retry System
- Fallback Actions
- Graceful Shutdown Handler
- Real-Time Error Stats
- Error Deduplication
- Context Capture
- Testing Hooks
- Persistent Error Queue
- Developer Notifications
- User Action Suggestions
- Version & Build Tracking
- Automatic Environment Checks

---

## 💼 Professional Background
While operating as **Themadhood Codes**, I bring experience from roles including:

**Programming & Systems Developer – Industrial Automation Manufacturer 6/18-present**  
Developing and refining software used in automated machinery, improving reliability, supporting legacy systems, and helping engineer modern control solutions.

**Independent Developer – MN 4-H 9/24-2/25**  
Lead developer for a custom judging/feedback platform and technical coordinator for major multi-week events, managing infrastructure, devices, software updates, and live operational support.


---

## 🎓 Education
- **B.S. Computer Science** – St. Cloud State University  
- **A.S. & A.A. Computer Science** – Anoka-Ramsey Community College  

---

## 📫 Contact
**Business:** Themadhood Codes  
**Email:** themadhoods.codes@gmail.com  

Thanks for stopping by — explore the projects, find inspiration, or reach out for collaboration.


<!--
**Themadhood/Themadhood** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
