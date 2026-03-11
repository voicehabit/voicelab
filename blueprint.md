# Blueprint

## Overview

This project is an interactive web application designed to guide users through a voice and physical training routine. Inspired by Duolingo, it will provide a fun and engaging experience where users check their voice, perform a plank exercise, and then check their voice again to see the effects of physical exertion.

## Implemented Features

*   Initial project setup with `index.html`, `style.css`, and `main.js`.
*   **Partnership Inquiry Form:** Added a Formspree-powered contact form at the bottom of the main page for partnership inquiries.

## Current Plan

### Create a Duolingo-style Voice and Plank Trainer

1.  **Structure `index.html`:**
    *   Create a main container for the application.
    *   Design three distinct sections for the user journey: Initial Voice Check, Plank Exercise, and Final Voice Check.
    *   Use Web Components (`<voice-check-module>`, `<plank-exercise-module>`) to create reusable UI components.
    *   Add buttons for navigation and to initiate actions.

2.  **Style `style.css`:**
    *   Implement a modern, friendly, and "Duolingo-like" design.
    *   Use a vibrant color palette, clean typography, and playful icons.
    *   Add animations and transitions to make the experience more dynamic.
    *   Ensure the layout is responsive and works well on mobile devices.

3.  **Implement `main.js`:**
    *   Define the custom elements for the voice check and plank modules.
    *   **Voice Check Module:**
        *   Integrate the Web Speech API (`SpeechRecognition`) to capture and transcribe user's voice.
        *   Provide a target phrase for the user to say.
        *   Display the recognized text and provide simple feedback.
    *   **Plank Exercise Module:**
        *   Implement a countdown timer for the plank.
        *   Provide clear visual instructions and a motivating interface.
    *   **Application Flow:**
        *   Manage the state of the application to guide the user through the three stages.
        *   Handle all user interactions through event listeners.
