# Drum Machine
You can access the project in this link
https://drum-7klqfgach-fadli-azhars-projects.vercel.app/
## Description

This project is a drum machine built with **React**, **TypeScript**, and **Vite**. It is a functional replica of the drum machine from [freeCodeCamp](https://drum-machine.freecodecamp.rocks/). It allows users to trigger sounds using clickable buttons or corresponding keyboard keys.

## Features

- **React + TypeScript:** The app is built using **React** for the UI and **TypeScript** for type safety.
- **Vite:** Used for the build and development environment to serve the app with fast reloading.
- **Keyboard Event Handling:** You can trigger sounds by pressing the corresponding keys on your keyboard (`Q`, `W`, `E`, etc.).
- **Drum Pads:** There are 9 clickable drum pads, each triggering a unique sound, displayed in a grid layout.
- **Display Panel:** The name of the sound currently playing is displayed in a display area.
- **Audio Clips:** The app uses various sound clips like "Heater 1", "Clap", "Kick", etc., which can be triggered by both mouse clicks and keyboard presses.
  
## User Stories

1. **Outer Container:** I should be able to see an outer container with an id of `drum-machine` that contains all other elements.
2. **Display:** Within `#drum-machine`, I can see an element with the id `display`.
3. **Drum Pads:** Within `#drum-machine`, I can see 9 clickable drum pad elements, each with a class name of `drum-pad`, a unique id that describes the audio clip it triggers, and inner text corresponding to keys: Q, W, E, A, S, D, Z, X, C.
4. **Audio Elements:** Each `.drum-pad` contains an HTML5 audio element with a `src` attribute pointing to an audio clip, a class name of `clip`, and an id corresponding to its key (Q, W, E, etc.).
5. **Click to Play:** When I click on a `.drum-pad`, the associated audio clip should play.
6. **Keyboard Input:** Pressing the corresponding key (Q, W, E, etc.) should also trigger the associated audio clip.
7. **Display Audio Name:** When a `.drum-pad` is triggered, a string describing the audio clip is displayed in the `#display` element.

## Tools Used

- **React (v18)**: A JavaScript library for building user interfaces.
- **TypeScript**: A superset of JavaScript that adds static typing.
- **Vite**: A build tool and development server.
- **CSS/SASS**: Used for styling the application to give it a clean and functional interface.
- **HTML5 Audio API**: For embedding and controlling sound clips within the application.
- **React Hooks**: To handle the state and behavior of the app, such as audio clip playback and key press handling.

## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/drum-machine.git
