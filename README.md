# Abyssal Ascent 🌊🫧

Dive into the dark depths and guide your resilient bubble towards the light in this challenging arcade-style ascent game! Navigate treacherous underwater caverns, avoid dangerous marine life, and collect precious air to survive your journey to the surface.

<div align="left">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/tin2tin/Reach_for_the_Air/master/index.html">PLAY</a><br><br>
</div>

## 🌟 Features

*   **Challenging Ascent Gameplay:** Master the art of attaching and pushing off underwater ceilings.
*   **Progressive Difficulty:** Each level (depth segment) brings new challenges and faster elements.
*   **Resource Management:** Collect air bubbles to survive and increase your score.
*   **Diverse Platforms:** Encounter normal, disappearing, bouncy, conveyor, retracting, and slippery kelp platforms.
*   **Varied Enemies:** Avoid Angler Fish, bouncy Jellyfish, and dangerous Lurkers.
*   **Helpful Power-ups:** Grab shields, speed boosts, extra lives, and sonar pulses.
*   **Atmospheric Experience:** Dynamic backgrounds, ambient bubbles, and particle effects.
*   **Sound & Music:** Immersive audio with a mute option (SFX and background tracks by Mellow Echoes).
*   **Mobile Friendly:** Playable on Android devices with on-screen touch controls.
*   **Persistent High Score:** Your best "Total Air" is saved locally in your browser.
*   **Pause Menu:** Take a break when needed.

## Video

https://github.com/user-attachments/assets/0725d1bd-5866-4546-b90b-eafbdd710614

## 🎮 How to Play

You control a bubble striving to reach the surface from the abyssal depths.

*   **Movement:**
    *   **Arrow Left/Right:** Move along the underside of a platform/ceiling you are attached to.
    *   **Mobile "LEFT" / "RIGHT" Buttons:** Same as arrow keys.
*   **Action:**
    *   **Spacebar / Mobile "PUSH" Button:**
        *   When attached to a ceiling: PUSH off to propel yourself downwards (and thus, upwards in buoyancy).
        *   When in open water: Briefly push nearby jellyfish or attempt a quick push-off from a nearby ceiling if close enough.
*   **Objective:**
    *   Collect glowing **Air Bubbles** (gems) to increase your air supply and score. This also slightly increases your player bubble's size.
    *   Attach to the special **"ASCENT"** platform once all air bubbles in a level are collected to progress to the next, shallower depth.
    *   Reach a depth of 0m to win!
*   **Avoid:**
    *   Hitting Angler Fish or being caught by Lurkers.
    *   Bumping into Jellyfish (they will push you around).
    *   Reaching the top surface of the water (a designated death zone near Y=0) or the deadly ocean floor at the very start.
*   **Other Controls:**
    *   **P / Escape / Mobile "PAUSE" Button:** Pause/Resume the game. The pause menu allows you to resume, restart, mute sounds, or return to the surface/close.

## 🚀 Running Locally

1.  Clone this repository or download the `index.html` file.
2.  **Important:** Ensure you have the audio files:
    *   `audio/Abyssal_Drone.mp3`
    *   `audio/Cycling_Platforms.mp3`
    These should be placed in an `audio` subfolder relative to the `index.html` file.
3.  Open the `index.html` file in a modern web browser (Chrome, Firefox, Edge, Safari).
    *   For best results and to ensure all features (like local storage for high scores and potentially local audio file access without CORS issues) work correctly, it's recommended to serve the files through a local web server. You can use:
        *   VS Code's "Live Server" extension.
        *   Python's built-in HTTP server: `python -m http.server` (Python 3) or `python -m SimpleHTTPServer` (Python 2) in the game's root directory, then navigate to `http://localhost:8000` (or the port it specifies).
        *   Node.js `http-server` package: `npx http-server .`

## 🛠️ Technology Stack

*   **HTML5:** Structure of the game.
*   **CSS3:** Styling for UI elements and layout.
*   **JavaScript (ES6+):** Core game logic.
    *   **Canvas API:** For rendering all game graphics.
    *   **Web Audio API:** For sound effects.
    *   **HTMLMediaElement (`<audio>`):** For background music.

## 📜 License

Distributed under the MIT License. See `LICENSE.md` for more information.


## 🙏 Acknowledgements (Optional)

*   Music and sound design by Tintwotin.


<div align="left">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/tin2tin/Reach_for_the_Air/master/index_sideways.html">PLAY</a><br><br>
</div>
