# TasklyElite – Premium Architectural Portfolio

TasklyElite is a symmetric, minimalist, dark-themed architectural portfolio website developed during my Frontend Development Internship at **DecodeLabs**. This project marks the successful completion of **Project 1: Static Webpage Design** under the internal engineering track.

The primary objective was to move away from generic, cluttered layouts and establish a clean, readable digital foundation that presents information with absolute visual clarity and structural integrity.

---

## 🚀 Key Layout & Responsive Features

* **Symmetric Dark UI:** Designed with a high-end, bold dark aesthetic ("Pure Black & Gray" theme) that eliminates unnecessary visual clutter to prioritize content presentation.
* **Compact Mobile Navigation:** Engineered a clean, horizontal-row layout for mobile screens that hides text links (`.nav-menu { display: none !important; }`) to eliminate text overlapping, keeping only the essential brand identifier and action buttons properly balanced.
* **Edge-Safe Image Responsiveness:** The signature hero section illustration (`#robot`) is strictly optimized to automatically center and scale gracefully on small viewports without overflow or edge clipping (`max-width: 300px; height: auto;`).
* **Layout Alignment:** Utilizing strict Flexbox alignment rules, the container spreads structural elements evenly (`justify-content: space-between;`) ensuring high-end professional symmetry across desktop, tablet, and mobile breakpoints.

---

## 🛠️ Engineering Mindset & Principles

The development process strictly adhered to the rigorous design guidelines and internal auditing standards outlined in the DecodeLabs training track:

1.  **Semantic DOM vs. "Div Soup":** Replaced vague layout blocks with meaningful, machine-readable HTML5 semantic structural tags (`<header>`, `<nav>`, `<main>`, `<footer>`) to optimize browser accessibility and screen performance.
2.  **Information Architecture (IA):** Built the navigation system around clear user findability principles, limiting cognitive load by completely avoiding unstructured "catch-all" data clusters.
3.  **The IPO Model Matrix:** Structured code utilizing the Input-Process-Output framework—taking raw asset files (images/text), passing them through clean CSS box modeling rules, and outputting a pixel-perfect layout render.

---

## 💻 Tech Stack

* **HTML5:** Structural markup emphasizing semantic integrity.
* **CSS3:** Advanced layouts using layout grids, flexboxes, structural media query breakpoints, and custom theme parameters.
* **JavaScript:** Used for streamlining user action items.

---

## 📁 Project Directory Tree

```text
├── index.html          # Entry point containing the Semantic DOM structure
├── css/
│   └── style.css       # Styling logic, layout rules, and media queries
└── images/
    └── robot.png       # Main hero illustration asset