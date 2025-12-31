# 🎧 iPod Classic UI – React

A **classic iPod-style UI clone** built using **React**, featuring a **rotational wheel navigation**, dynamic menus, and music playback — inspired by the original Apple iPod experience.

This project focuses on **event-driven UI logic**, **gesture handling**, and **state-based screen navigation**, rather than simple CRUD or form-based interfaces.

---

## 📸 Preview

> _(Add a screenshot of the app UI here)_

```md
![iPod UI Preview](preview/ipod-ui.png)
🚀 Features
🎡 Rotational Wheel Navigation

Clockwise & anti-clockwise wheel rotation

Menu item selection based on rotation direction

📂 Dynamic Menu System

Side Menu (Coverflow, Music, Games, Settings)

Nested Music Menu (All Songs, Artists, Albums)

🎵 Music Playback

Audio playback using HTML5 <audio> element

Song thumbnail and metadata display

🧭 State-Driven Screen Rendering

Centralized state management

Smooth transitions between screens

🖥️ Classic iPod-style UI

Authentic menu layout

Highlighted active menu items

⚛️ React Concepts Used
Class Components

State management using constructor

Event handler methods

Props-based data flow

Functional Components

Modular UI components

Reusable menu and screen components

React Hooks

useEffect() for:

Menu highlighting

DOM synchronization

Conditional Rendering

Screen switching based on application state

🔄 Gesture & Event Handling
ZingTouch Library

Used for detecting rotational gestures on the wheel

Enables real-world iPod-like interaction

DOM Interaction

Controlled usage of querySelector and classList

Necessary for gesture-based UI logic

⚠️ Direct DOM manipulation is intentionally used here due to gesture-based interactions that are not easily handled through standard React synthetic events.

🧩 Project Architecture
App
Central controller managing global state and navigation logic

Screen
Responsible for rendering the active screen

Controls
Handles wheel rotation, menu button, and OK button interactions

Menu Components

SideMenu

MusicMenu

Content Components

Coverflow

Music

AllSongs

Artists

Albums

Games

Settings

🛠️ Tech Stack
React

JavaScript (ES6+)

ZingTouch (Gesture detection)

HTML5 Audio API

CSS

⚙️ Run Locally
Clone the repository

bash
Copy code
git clone https://github.com/akhilBharti510/ipod-react.git
Navigate to the project folder

bash
Copy code
cd ipod-react
Install dependencies

bash
Copy code
npm install
Start the development server

bash
Copy code
npm start
🌐 Live Demo
(Will be added after deployment)

arduino
Copy code
https://ipod-react.vercel.app
📌 Learning Outcomes
Handling complex UI state in React

Gesture-based event management

Mixing declarative React logic with imperative DOM handling

Designing non-form-based interactive UIs

👤 Author
Akhil Bharti
Frontend Developer
GitHub: https://github.com/akhilBharti510

⭐ If you like this project, feel free to star the repository!