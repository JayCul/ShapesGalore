# Shapes Galore Particle Engine 🌌

An interactive, gesture-controlled 3D particle visualization powered by mathematical superformulas and computer vision.

## ✨ Features

-   **100+ Unique Shapes**: Parametric engine generating everything from classic geometry (Spheres, Tetrahedrons) to cosmic objects (Galaxies, Saturn) and abstract "Alien Artifacts".
-   **AI Hand Tracking**: Real-time hand detection using MediaPipe.
-   **Dynamic Interaction**:
    -   **Pinch** your fingers to morph into a new random shape.
    -   **Spread** your hand to make the universe expand/explode.
    -   **Move** your hand to dynamically shift colors and rotate the view.
-   **Smooth Animations**: Powered by GSAP for fluid transitions.

## 🎮 Controls

| Gesture | Action |
| :--- | :--- |
| **Pinch (Index + Thumb)** | Cycle to the next shape |
| **Open Hand Wide** | Expand / Explode particles |
| **Close Hand / Fist** | Contract / Shrink particles |
| **Move Hand Left/Right** | Change Particle Colors |
| **Tilt Hand** | Rotate the 3D Object |

## 🛠️ Tech Stack

-   **[Three.js](https://threejs.org/)**: 3D Rendering Engine.
-   **[MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)**: Computer Vision & Hand Tracking.
-   **[GSAP](https://greensock.com/gsap/)**: High-performance animations.

## 🚀 How to Run

1.  Simply open `index.html` in a modern web browser.
2.  Allow camera access when prompted.
3.  Stand back slightly so your hand is clearly visible.

> **Note**: For best performance, use a local server (e.g., `npx serve .`) to avoid CORS issues with some browser security settings, though it should work standalone in most cases.
