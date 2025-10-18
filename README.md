# benefits-split-section
A lightweight Shopify section that displays 3 benefits above and 3 below a center image on mobile. Fully configurable via Theme Editor—no external deps.
# Shopify Benefits Split Section

A drop-in Shopify section (Liquid + CSS) that renders six product benefits with icons:
- **Desktop/Tablet (unchanged)**: benefits flank a center image in a 3×2 grid.
- **Mobile**: shows **3 benefits above the image** and **3 below** (Javvy-style list).
- Forces benefit headings and section title to **font-weight: 500** for cleaner typography.

> Zero JavaScript. Zero external CSS. Theme-editor friendly.

---

## Demo
- Desktop: 3 benefits left, image center, 3 benefits right.
- Mobile: 1–3 stacked, **image**, 4–6 stacked.
<img width="1163" height="748" alt="Screenshot 2025-10-17 at 8 29 18 PM" src="https://github.com/user-attachments/assets/6e595185-7208-4a31-8e39-e9e024f06f28" />
<img width="348" height="889" alt="Screenshot 2025-10-17 at 8 29 53 PM" src="https://github.com/user-attachments/assets/2e92d522-6ace-49af-a3d0-96bbcd4b2d96" />
<img width="354" height="872" alt="Screenshot 2025-10-17 at 8 30 15 PM" src="https://github.com/user-attachments/assets/c3fbf1bd-0fc6-4853-8606-a76d1c671914" />


---

## Features
- 🔁 Responsive: desktop grid ↔ mobile split list (3 up / image / 3 down)
- 🖼️ Icon bubbles with shadows
- 🧩 Theme Editor controls for texts, icons, colors, sizes, paddings
- ✍️ Typography tuned to **weight 500** for titles/benefit headings
- 🧪 Framework-free, copy-paste installation

---

## Installation

1. **Create a new section**
   - In Shopify Admin → **Online Store → Themes → Edit code**
   - Add file under **/sections**: `ai-product-benefits.liquid`

2. **Paste the section code**
   - Copy the entire Liquid from this repo’s `sections/ai-product-benefits.liquid` and paste it in.

3. **Add the section to a template**
   - In the Theme Editor, add **“Product benefits”** to your Product template (or any page/landing).

4. **Configure**
   - Set the **center image**.
   - Fill **Benefit 1–6** title & description.
   - Upload **Icon 1–6** (optional).
   - Adjust colors, sizes, paddings to taste.

---


---

## `LICENSE` (MIT)

```text
MIT License

Copyright (c) 2025 Humankind Candles

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


