# SpendWise - Personal Budget Tracker

SpendWise is a fully responsive personal finance application styled from the ground up using advanced modern CSS. This project serves as a comprehensive showcase of UI design, custom typography, form and table structuring, and intentional CSS Box Model architecture.

---

## 🎨 Visual Design & Rubric Alignment

### 1. Intentional Color Palette (25%)
* Built using custom CSS variables (`:root`) to maintain a clean, professional, and consistent scheme across the entire layout:
  * **Primary Slate (`#1e293b`)**: Used for main headings, section headers, and table head backgrounds.
  * **Accent Blue (`#3b82f6`)**: Applied to action buttons, focus rings, and interface elements.
  * **Neutral Slates & Off-Whites**: Used for background surfaces, subtle container borders (`#e2e8f0`), and alternating table row bands.

### 2. Typography & Hierarchy (20%)
* **Font Pairing**: Integrated **Inter** (clean sans-serif) for all high-impact UI elements, buttons, and headings to maintain legibility, paired with **Merriweather** (refined serif) for comfortable, readable body paragraphs.
* **Hierarchy**: Implemented proportional font sizes (`2.5rem` main titles, `1.35rem` section headers) and precise line-height (`1.6`) to prevent visual clutter.

### 3. Table and Form Styling (30%)
* **Form & Inputs**: Form fields feature clean padding (`10px 12px`), rounded borders (`border-radius: 6px`), and smooth glowing focus states. The action button includes a hand cursor and a hover transition.
* **Expense Table**: Built with `border-collapse: collapse`, distinct header blocks, generous cell padding, and automated zebra striping (`tr:nth-child(even)`) backed by subtle row-hover highlights.

### 4. Effective Use of the CSS Box Model (25%)
* Each logical block of the application (Header details, Help accordion, Form, Expense Table, and Video module) is styled as a distinct **visual "card"**.
* Utilizes intentional container padding (`25px`), section margins (`25px`), thin structural borders, and modern rounded corners (`border-radius: 12px`) to separate page content cleanly.

---

## 🚀 How to Run Locally
1. Clone or download this repository.
2. Open the project folder in **Visual Studio Code**.
3. Fire up the **Live Server** extension to launch `index.html` in your web browser.
