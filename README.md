# iPod Classic UI (React)

A classic **iPod-style user interface clone** built using **React**, featuring **rotational wheel navigation**, dynamic menus, and music playback.  
The project focuses on **gesture-based interaction**, **state-driven UI rendering**, and a **component-based architecture** inspired by the original Apple iPod.

---

## Live Demo
[View Live iPod Demo](https://ipod-react-six.vercel.app/)

---

## Preview

![iPod UI Preview](preview/Screenshot%20(165).png)

---

## Features

- Rotational wheel navigation with clockwise and anti-clockwise support  
- Dynamic side menu navigation  
  - Coverflow  
  - Music  
  - Games  
  - Settings  
- Nested music menu  
  - All Songs  
  - Artists  
  - Albums  
- Music playback using HTML5 Audio  
- Active menu highlighting  
- State-driven screen rendering  
- Classic iPod look and feel  

---

## React Concepts Used

- Class Components for central state management  
- Functional Components for modular UI  
- useEffect hook for menu highlighting and DOM synchronization  
- Conditional rendering based on application state  
- Props-based component communication  

---

## Gesture & Event Handling

- ZingTouch library used for detecting wheel rotation gestures  
- Gesture-based navigation similar to real iPod behavior  
- Controlled DOM manipulation where required for gesture handling  

---

## Project Architecture

- App  
  - Central controller managing global state and navigation logic  

- Screen  
  - Responsible for rendering the active screen  

- Controls  
  - Handles wheel rotation, menu button, and OK button actions  

- Menu Components  
  - SideMenu  
  - MusicMenu  

- Content Components  
  - Coverflow  
  - Music  
  - AllSongs  
  - Artists  
  - Albums  
  - Games  
  - Settings  

---

## Tech Stack

- React  
- JavaScript (ES6+)  
- ZingTouch  
- HTML5 Audio API  
- CSS  

---

## Run Locally

1. Clone the repository  
   git clone https://github.com/akhilBharti510/ipod-react.git  

2. Navigate to the project directory  
   cd ipod-react  

3. Install dependencies  
   npm install  

4. Start the development server  
   npm start  

---

## Learning Outcomes

- Implemented gesture-based navigation in React  
- Managed complex UI state centrally  
- Combined declarative React patterns with imperative DOM logic  
- Built an interactive, non-form-based UI  

---

## Author

Akhil Bharti  
Frontend Developer  
GitHub: https://github.com/akhilBharti510

---

⭐ If you like this project, feel free to star the repository.
