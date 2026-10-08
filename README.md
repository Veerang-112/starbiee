# ⭐ Starbie — PCB Design Learning Project

> A hands-on PCB designing and electronics learning project based on **Starbie by Hack Club**.

## 📌 About

This project was created as part of my **HackLife PCB Designing Week**, where I started learning the fundamentals of PCB design using **KiCad**.

I spent around **5 hours** learning KiCad through GitHub resources, YouTube tutorials, and hands-on trial and error. After learning the basic workflow, I explored the **Starbie** project by Hack Club to understand how a real PCB project is structured and how the different parts of PCB design work together.

Starbie is a **motion-controlled digital pet**, similar to a desktop Tamagotchi. Instead of interacting mainly through buttons, the user can physically move or tilt the board to interact with the pet. The original project combines a microcontroller, display, motion sensor, and environmental sensor into a compact PCB.

## 🎯 Purpose of This Project

The main goal of this project was **learning PCB design**, rather than creating a completely original product.

Through Starbie, I wanted to understand:

* How PCB projects are structured
* How to work with **KiCad**
* How electronic components are represented in schematics
* How schematic designs are converted into PCB layouts
* How components are placed on a PCB
* How electrical connections are routed
* How PCB fabrication files are generated
* How an actual hardware project is organized on GitHub

## 🛠️ Tools & Technologies

* **KiCad** — PCB and schematic design
* **Git & GitHub** — Version control and project management
* **Arduino IDE** — Firmware development
* **XIAO ESP32-C3** — Microcontroller used by the original Starbie design
* **PCB Design & Routing**
* **Electronics & Embedded Systems**

## 📚 What I Learned

### 1. KiCad Basics

I started by learning the KiCad interface and understanding the basic PCB design workflow.

I explored:

**Schematic → Footprints → PCB Layout → Routing → Design Review → Fabrication Files**

### 2. Schematics

I learned how electronic components are represented in a schematic and how their electrical connections are defined before creating the physical PCB layout.

### 3. PCB Layout

I learned how components are positioned on the board and how tracks are routed between them while considering the physical constraints of the PCB.

### 4. Trial & Error

A significant part of my learning came from experimenting with KiCad and fixing mistakes along the way.

Rather than only watching tutorials, I tried different tools and workflows myself to understand what each step actually does.

### 5. Studying an Existing PCB

After learning the basics, I studied the Starbie project to understand how a complete PCB project is organized.

The original repository contains:

* KiCad PCB source files
* Fabrication exports
* PCB renders
* Project documentation
* Arduino firmware
* A browser-based simulator

## ⭐ About Starbie

Starbie is designed as a small desktop digital pet.

The board contains a:

* Microcontroller
* Small display
* Motion sensor
* Environmental sensor
* USB power interface

The project uses physical movement such as **tilting and shaking** as part of the interaction. The original repository describes the default firmware as a two-eye pet with a tilt-controlled menu and a shake reaction.

## 📁 Repository Structure

```text
Starbie/
│
├── PCB/
│   ├── KiCad project files
│   └── PCB/fabrication files
│
├── Renders/
│   └── PCB renders
│
├── Firmware/
│   └── Arduino firmware
│
├── Documentation/
│   └── Learning notes
│
└── README.md
```

## 🧠 My Learning Outcome

This project helped me move from **theoretical understanding to practical PCB design**.

Before starting this project, I had very little experience with PCB designing. By spending approximately **5 hours** learning KiCad and then studying the Starbie project, I gained a basic understanding of how an electronic product moves from an idea and schematic to a physical PCB.

This project also gave me a foundation to start designing **my own PCBs and embedded hardware projects** in the future.

## 🙏 Credits & Reference

This project is based on the **Starbie project created for Hack Club's beginner electronics/PCB learning program**.

Original project:

[SharKingStudios/Starbie on GitHub](https://github.com/SharKingStudios/Starbie?utm_source=chatgpt.com)

The original Starbie repository contains the project design, documentation, PCB files, renders, and firmware.

## 📜 Note

This repository is primarily a **learning and educational project** created to understand PCB design and the KiCad workflow.

All credit for the original Starbie project and its design goes to its respective creators.
