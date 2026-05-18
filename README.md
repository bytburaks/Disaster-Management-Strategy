# Emergency Dispatch & Disaster Management Strategy Game

This repository contains an educational real-time strategy (RTS) and management game built using **Unity** and **C#**. Inspired by emergency response operations (like AFAD), the game tasks the player with monitoring a city map, identifying dynamic disaster events, and strategically dispatching specialized rescue teams to mitigate crises and save lives.

## 🚀 Play in Browser
You can play the web-optimized version of the game directly on your browser via GitHub Pages:
👉 **[Click Here to Play the Game](https://bytburaks.github.io/Disaster-Management-Strategy/)**

---

## 🛠️ Tech Stack & Key Features

*   **Game Engine:** Unity (2D/3D Hybrid Navigation)
*   **Language:** C# (Object-Oriented Programming, Event-Driven Architecture)
*   **Genre:** Real-Time Strategy (RTS) / Resource Management / Serious Game
*   **Core Systems:** Dynamic event spawning, resource allocation, and grid/node-based team dispatching.

---

## ⚙️ Technical Highlights (What I Implemented)

### 1. Dynamic Event Spawning & Threat Levels
*   Developed a centralized **Event Manager** that algorithmically spawns random emergency situations across different city sectors (e.g., structural collapses, chemical leaks, or fires).
*   Coded a threat-escalation system where active events increase in severity over time if left unattended, adding a strategic layer of prioritization.

### 2. Fleet & Unit Dispatching Mechanics
*   Implemented a modular unit management system for different emergency teams (e.g., Search & Rescue, Firefighters, Medical Teams).
*   Designed the core selection and dispatch mechanic: Players click on an active event on the city map and deploy appropriate units based on resource availability and proximity.

### 3. Resource & Queue Management
*   Coded a finite resource system tracking available rescue vehicles, team stamina, and city-wide casualty rates using clean UI event binding.
*   Implemented duration-based mission completion logic where units are "locked" to an event location until the crisis meter reaches zero, requiring careful queue planning.

### 4. Interactive City Map UI & Feedback Loops
*   Built an interactive, scalable map UI utilizing Unity's Canvas and Screen-to-World point conversion to handle seamless clicking and unit deployment.
*   Integrated a visual notification/alert ticker system that dynamically updates the player on crisis outcomes and team status changes.

---

## 🎮 Game Loop & Mechanics

1.  **Monitor the City:** Keep an eye on the city overview map for incoming emergency signals.
2.  **Assess the Threat:** Analyze the type of incident (e.g., a fire requires firefighters, a collapsed building requires search & rescue).
3.  **Dispatch Teams:** Click the event zone, select the correct available units from headquarters, and deploy them.
4.  **Manage Resources:** Balance your fleet to handle multiple overlapping incidents simultaneously without letting the city's panic meter overflow.

---
