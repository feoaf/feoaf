
# Design Update Documentation: FEOAF Website

---

## 🎯 Overview
This document outlines the recent and ongoing design updates made to the **FEOAF** website. The primary goals of these changes are to establish a more cohesive brand identity, ensure all sponsor logos are displayed cleanly, and improve overall website accessibility by meeting proper color contrast standards.

---

## ✨ Key Visual Changes (Before & After)

### 1. Sponsors Logo Contrast Colors
**The Problem:** The varied colors and styles of the sponsor logos were clashing with the FEOAF website background, making the section look cluttered and reducing the visibility of certain logos.
**The Solution:** * Implemented a unified background container for the sponsor grid.
* Adjusted the contrast and applied a standardized visual treatment (e.g., grayscale/monochrome conversion on hover or resting states) so all logos stand out clearly without fighting the main FEOAF color palette.

| Before | After |
| :--- | :--- |
| ![Before Sponsor Logos](path/to/your/before-sponsors.png) | ![After Sponsor Logos](path/to/your/after-sponsors.png) |

### 2. Color Palette Design
**The Problem:** The previous color scheme lacked consistency across different pages, leading to a fragmented user experience.
**The Solution:** * Defined a strict primary, secondary, and accent color palette.
* Standardized button colors, background sections, and typography colors to align with FEOAF's core brand identity. 
* Created a clear visual hierarchy using these new brand colors to guide the user's eye toward key actions.

| Before | After |
| :--- | :--- |
| ![Before Color Palette](path/to/your/before-colors.png) | ![After Color Palette](path/to/your/after-colors.png) |

### 3. General Color Contrast 🚧 *(Ongoing/In Progress)*
**The Problem:** Several text elements and interactive components (like links and buttons) currently do not meet the WCAG (Web Content Accessibility Guidelines) minimum contrast ratios, making them hard to read for visually impaired users or those on low-brightness screens.
**Current Action Items:** * Auditing text-to-background contrast across all pages.
* Darkening light grey text and adjusting button background colors to ensure a minimum contrast ratio of 4.5:1 for normal text.
* *Note: Screenshots will be added once the sitewide audit and CSS adjustments are fully completed.*

| Current State | Target State |
| :--- | :--- |
| ![Current Low Contrast Example](path/to/your/current-contrast.png) | *(Pending final design approval)* |

---

## 🛠️ Technical Handoff Notes for Developers
* **New Color Variables:** Please ensure the root CSS file is updated with the new FEOAF color palette hex codes. 
* **Sponsor Logos:** The new sponsor logo grid utilizes a CSS filter for the contrast adjustment. Let's make sure this behaves nicely across all browsers (Safari, Chrome, Firefox).
* **Accessibility:** For the ongoing contrast updates, we will be rolling out changes to the global text utility classes soon.
