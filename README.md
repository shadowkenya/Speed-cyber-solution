# Speed Cyber Solution

A modern, secure, and responsive web application for **Speed Cyber Solution**—a full-service digital hub specializing in high-speed printing, document editing, file conversions, image cropping, and comprehensive IT solutions.

## 🚀 Features

* **Modern & Responsive UI:** Clean interface built with semantic HTML5, modern CSS3 (glassmorphism, CSS Grid/Flexbox), and a Dark/Light theme toggle.
* **Interactive Image Cropper & Converter:**
  * Upload local images or use the built-in sample card.
  * Switch between aspect ratio presets (**Original**, **1:1 Passport**, **4:3 ID Card**).
  * Real-time adjustments for brightness, contrast, and high-contrast B&W document scan mode.
  * Client-side export directly to **PNG**, **JPG**, or **WEBP**.
* **Client-Side Document Editor & File Converter:**
  * Import `.txt`, `.md`, `.html`, or `.csv` files directly in the browser.
  * Built-in text utilities (whitespace cleanup, case formatting) with live word and character counters.
  * Instant client-side export to **Microsoft Word (`.doc`)**, **Printable PDF**, **HTML**, or **UTF-8 Text**.
* **Instant Print & IT Quote Calculator:**
  * Live price estimation based on print type, page volume, and finishing add-ons (spiral binding, lamination, express rush).
  * Automatic 15% bulk discount calculation.
  * Direct integration with the service booking modal.
* **Privacy-First Processing:** All file conversions, text edits, and image cropping happen 100% locally in the user's browser without uploading sensitive files to external servers.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure and accessible forms.
* **CSS3:** Custom properties (CSS variables), responsive layouts, and adaptive Dark/Light themes.
* **Vanilla JavaScript (ES6+):** HTML5 Canvas API for image cropping/filtering, FileReader/Blob APIs for client-side document conversion, and dynamic DOM manipulation.

## 📂 Project Structure

```text
speed-cyber-solution/
├── index.html      # Main single-page application (markup, styles, and scripts)
└── README.md       # Project documentation
