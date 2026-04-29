
## ## 1. Visual Strategy: "Fluid Luxury"
The aesthetic is rooted in **Maximalist Depth** rather than just "glow." It uses a clean, high-contrast base to highlight the vibrant aqua and pink of your logo.

* **Color Palette (Directly from Logo & PRD)**:
    * **Foundation**: Deep Space Black (#000000) for the primary background to create a premium "infinite" canvas.
    * **Core Brand Aqua**: Use the electric blue from the "AQUA" text for interactive borders and progress indicators.
    * **Soft Petal Pink**: Use the pink from the flower motif for secondary highlights and "cleanliness" indicators.
    * **Conversion Accent**: Coral (#FF7E67) for B2C "Add to Cart" and B2B "Request Quote" buttons to ensure high visibility.
* **Typography**:
    * **Headings**: *Playfair Display*. This serif font adds an editorial, high-end feel for brand storytelling.
    * **Body/Data**: *Inter*. A clean sans-serif for the technical details of the Dorron cleaning products and bulk-order tables.

---

## ## 2. Motion Architecture: "The Liquid Experience"
Following the **Bespoke Web Design** research, motion must be used to guide the user's eye through the dual B2C/B2B flows.

### ### A. The "AquaGlow" Entrance (Brand Reveal)
* **SVG Morphing**: The logo's flower should subtly "bloom" (scale and rotate) as the page loads, with the "AQUA" and "GLOW" text using a staggered fade-in to create a cinematic arrival.
* **Hero Reveal**: Use a **GSAP-powered** image reveal where lifestyle shots of the products "wipe" onto the screen from left to right, mimicking the action of a surface being cleaned.

### ### B. Advanced Parallax (Depth & Discovery)
* **2.5D Layering**: As the user scrolls, background "water ripples" and flower petals should move at varying speeds.
* **The "Cleaning Routine" Slider**: Implement a horizontal scroll section where product cards slide into view with a slight "magnetic" elasticity, making the product catalog feel tactile.

### ### C. Interaction Design
* **Glass-morphic Panels**: B2B distributor forms and product detail modals should use translucent panels with a 30px backdrop blur to maintain the premium feel without losing site context.
* **Micro-animations**: Add "liquid ripples" that emanate from the cursor when it hovers over primary CTA buttons.

---

## ## 3. Performance & Quality Guardrails
To ensure the site earns a high **Usability Score**, AI Studio must follow these technical constraints:

* **GPU Mandate**: Strictly animate `transform` (scale, translate, rotate) and `opacity` to maintain a steady 60fps and prevent layout shifts.
* **Responsive Motion**: Automatically reduce animation complexity via the `prefers-reduced-motion` media query for accessibility.
* **Interaction Speed**: Target an **Interaction to Next Paint (INP)** of $\leq 200$ms to ensure immediate feedback during the checkout or inquiry process.

---

## ## 4. Prompt for AI Studio Visual Generation
> *"Cinematic macro photography of the AquaGlow flower and cleaning bottles. The background is deep, reflective black glass. Subtle water ripples and floating pink flower petals create a sense of depth. Lighting is sharp and elegant, highlighting the aqua blue liquid inside the bottles. 8k resolution, premium B2C luxury aesthetic, ultra-sharp focus on product textures."*
