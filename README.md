# Air Juggler Game with TensorFlow.js 🍵

An interactive, gesture-controlled browser game where you juggle virtual objects using real-time hand tracking through your webcam! No mouse, no keyboard—just wave your hands to play. 

This project is my custom implementation based on the Codédex tutorial series by @Goku-kun, featuring a fully personalized user interface theme.

## ✨ Features
* **Mint Matcha UI Theme:** A fresh, arcade-style visual design featuring smooth CSS animations, moving gradients, and glowing arcade borders.
* **AI Hand Tracking:** Powered by Google's MediaPipe Hands model to monitor hand positions directly in the browser.
* **Real-Time Data Processing:** Converts 21 intricate skeletal hand landmarks into a clean, mirrored canvas coordinate system to act as your game paddles.
* **Privacy Focused:** All machine learning calculations run locally on your device; your webcam feed never leaves your computer.

## 🛠️ Built With
* **Core Logic:** JavaScript (ES6+, Promises, Async/Await)
* **Styling:** Custom CSS3 (Flexbox, Keyframe Animations, Backdrop Blurs)
* **Machine Learning Infrastructure:** [TensorFlow.js](https://www.tensorflow.org/js)
* **Computer Vision Model:** [MediaPipe Hands Solution](https://cdn.jsdelivr.net/npm/@mediapipe/hands)

## 🚀 How to Run Locally

Since this project utilizes browser-level hardware APIs (`getUserMedia`), running it requires a local development server:

1. Clone or download this repository to your machine.
2. Open the project folder in **VS Code**.
3. Install the **Live Server** extension in VS Code (if you don't have it already).
4. Right-click on `starter/index.html` and select **"Open with Live Server"**.
5. Allow webcam access when prompted by your browser, hit **Start Game**, and start juggling!

---
*Acknowledgment: Original starter architecture and core game logic concepts by Dharmarajsinh Jethva (@Goku-kun).*
