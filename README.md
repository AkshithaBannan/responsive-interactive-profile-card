# Responsive Interactive Profile Card

A modern, client-side interactive profile card application built using semantic HTML5, fluid CSS Flexbox layouts, and advanced state-driven Vanilla JavaScript. This project showcases dynamic DOM manipulation, control flow parsing, and JavaScript closures.

---

## Key Features

*   **Dynamic Data Binding & Control Flow:** Parses user string inputs via a space delimiter mapping (`value.split(" ")`) to dynamically update card properties (Name and Title) on the fly.
*   **State Encapsulation via JavaScript Closures:** Implements an Immediately Invoked Function Expression (IIFE) closure module (`profileViews`) to securely protect and increment internal view counters without polluting the global scope.
*   **Array Randomized Selection:** Utilizes deterministic mathematical array indexes (`Math.random()`) to cycle and render dynamic items seamlessly from a predefined collection of hobbies.
*   **Fully Responsive Flexbox Blueprint:** Builds a clean `display: flex` horizontal matrix that elegantly rearranges itself into a vertical layout using explicit CSS media queries (`@media (max-width: 700px)`) for mobile viewports.
*   **Polished User Interactions:** Integrated with smooth visual hover micro-animations (`transition: 0.3s`) and tactile scaling states across control triggers.

---

## Architecture & File Breakdown

### 1. Structure Skeleton (`index.html`)
Lays down the markup architecture for the card component:
*   **Image Segment (`.profile-img`):** Houses the profile photo asset box.
*   **Content Segment (`.profile-info`):** Holds descriptive identifiers, interactive target buttons (`#hobbyBtn`, `#viewBtn`), and data capturing fields (`#userInput`).

### 2. Functional Engine (`script.js`)
Manages structural data mutations, calculations, and interface updates:
*   **Control Flow Logic:** Checks input lengths to dynamically separate custom strings or fire structural fallback alerts.
*   **Closure System:** Encapsulates the tracking metrics variable (`let count = 0`) inside an isolated reference ecosystem.

### 3. Visual Presentation Matrix (`style.css`)
Establishes colors, layout rules, and responsiveness bounds:
*   **Centering Canvas:** Centers the primary profile card within the screen view utilizing a combination of `flex` property constraints and explicit viewport dimensions (`100vh`).
*   **Breakpoint Controls:** Modifies the flow orientation (`flex-direction: column`) below $700\text{px}$ viewports to match responsive standard guidelines.

---

## How to Run Locally

1. Organize all component source files within a single working directory tree:
   ```text
   ├── index.html
   ├── style.css
   └── script.js
