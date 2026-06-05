# Robot-Runner 🤖✨

An addictive, fast-paced web-based infinite runner game featuring a sleek robot sprinting through a luminous, retro-futuristic cyberpunk city skyline. Built purely with semantic HTML5, CSS custom properties, and vanilla JavaScript using the Canvas API.

<img width="1920" height="1036" alt="image" src="https://github.com/user-attachments/assets/1c1b64f6-9242-4d4b-9ed1-69ebfd659b9f" />

---

## 🕹️ Live Demo



https://github.com/user-attachments/assets/8114cc6f-f313-4737-a0d2-eb615be9484a


---

## 🚀 Features

*   **Pure Vanilla Stack:** Built completely from scratch with zero external frameworks or dependencies—just raw HTML, CSS, and JS (Canvas API).
*   **Dynamic Speed & Scaling:** The game incrementally speeds up as your distance increases, ramping up the tension and challenge.
*   **Dynamic Backdrop:** Fluid parallax city skyline rendering and sparkling particle effects (dust trail, collision sparks, and twinkling stars).
*   **Fully Responsive & Accessible:** Built with fluid layouts using CSS grid, custom variables, viewport-fit configurations, and custom touch controls optimized for mobile and tablets.
*   **Neon Aesthetics:** High-fidelity visuals incorporating glowing radial gradients, linear backdrop blurs, and organic screen-shake feedback upon collision.

---

## 🎮 How to Play

The objective is simple: run as far as you can through the neon grid while dodging high-voltage obstacles.
Use desktop mode in your android or ios browser.

### Desktop Controls
*   <kbd>Spacebar</kbd> — Start Game / Jump over tall barriers
*   <kbd>B</kbd> — Slide under low gates (Hold to stay low)
*   <kbd>R</kbd> — Quick restart when the system goes offline

### Mobile/Tablet Controls
*   **Tap the Screen / Jump Button** — Start Game / Jump
*   **Hold the Slide Button** — Slide under low gates

---

## 🛠️ Technical Highlights

The codebase showcases clean architectural practices for native browser gameplay:
*   **High-DPI Support:** Explicit device pixel ratio (`window.devicePixelRatio`) scaling applied to the canvas element to prevent blurring on Retina and high-res screens.
*   **Deterministic Game Loop:** Utilizes standard `requestAnimationFrame` paired with time-delta scaling (`dt`) ensuring smooth, frame-rate independent game progression.
*   **Custom Collision System:** Lightweight, optimized Axis-Aligned Bounding Box (AABB) intersection queries customized to match the unique bounding parameters of the robot during animations (standing vs. sliding positions).
*   **Robust Touch Capture:** Integrated with pointer event listeners (`setPointerCapture`) to guarantee responsive slide triggers without touch-delay anomalies on mobile layouts.

---

## 📦 Installation & Local Development

No compilation or build steps are necessary! To run this project locally
