# Drawer – Your Clothes, Matched

A lightweight, zero-backend digital wardrobe management and outfit-matching web application built for **Application Development and Emerging Technologies** (University of Nueva Caceres).

## Live Demo
- **Working Web App:** [Launch Drawer App](file:///C:/Users/mayna/Downloads/Drawer%20(1).html)

## Features
- **Digital Closet:** Add, categorize (`Tops`, `Bottoms`, `Outerwear`, `Shoes`), color-swatch, and filter garments locally via `localStorage`.
- **Outfit Studio & Color-Harmony Engine:** Computes pairwise compatibility scores (`0–100%`) using hue-angle distance and neutral flags, plus a one-click **Match me** outfit generator.
- **Client-Side Photo Color Scanner:** Uses HTML5 `<canvas>` border subtraction and 512-bin RGB quantization to detect a garment's dominant color directly in the browser.
- **Live Look Preview & Pinterest Bridge:** Layered SVG outfit preview with luminance-adaptive backgrounds and dynamic Pinterest outfit inspiration searches.

## Repository Structure
- `index.html` — Complete Single-Page Application (HTML5, CSS3, Vanilla JS, SVG).
- `/prompts` — SRS-linked AI Vibe Coding prompts used to architect, build, and refine the application.
