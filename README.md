# 🌊 Hanuman Chalisa: Knowledge Ocean - Audio Quest UI

Welcome to the digital companion app for the **Hanuman Chalisa: Knowledge Ocean** children's interactive book! 

This repository hosts the lightweight Single Page Application (SPA) that acts as a gamified "Holographic HUD." When young readers scan the QR codes printed in the physical book, this web app instantly loads the corresponding ancient verse, displays the text in multiple languages, and plays the exact audio segment for them to chant along with.

## ✨ Features

* **Dynamic Audio Routing:** Uses URL parameters (e.g., `?v=23`) to jump instantly to specific timestamps within a single master audio file, eliminating the need to host 40+ separate MP3s.
* **Gamified "Level Select" UI:** Designed specifically for young readers, the interface looks like a sci-fi mission log with chunky, kid-friendly controls.
* **Multilingual Display:** Dynamically renders the original text in both Hindi and Kannada scripts.
* **Frictionless Deployment:** Built with Vanilla HTML/CSS/JS. It requires no backend servers or databases and is hosted entirely for free via GitHub Pages.

## 🚀 Live Demo

You can access the live application here: 
(https://dineshav05.github.io/hanuman-audio-quest/)

/* Try jumping to a specific level: `[(https://dineshav05.github.io/hanuman-audio-quest/?v=9)]` */

## 📁 Repository Structure

```text
/
├── index.html          # The main Single Page Application and UI logic
├── favicon.png         # The browser tab icon
├── audio/
│   └── hanuman_chalisa_full.mp3  # The master audio track 
└── README.md           # Project documentation
