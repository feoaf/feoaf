# 🚧 [DRAFT] FEOAF Design Updates & Work-in-Progress Log

---

## 🎯 Overview
This is a living document tracking the ongoing design improvements for the **FEOAF** website. The current sprint focuses on establishing a cohesive color palette, fixing sponsor logo visibility, and auditing the site for accessibility (color contrast). This document will be updated with final screenshots and developer handoff notes as each phase is completed.

---

## 🛠️ Active Design Sprints

### 1. Color Palette Design & Standardization ⏳ *In Progress*
**The Goal:** The current site lacks a unified color scheme. I am working on defining a strict primary, secondary, and accent color palette to standardize buttons, backgrounds, and typography.
**Current Tasks:**
- [ ] Define core brand hex codes.
- [ ] Map out standard button states (default, hover, active, disabled).
- [ ] Apply the new hierarchy to a sample page layout.

**Draft Implementation:**
![Placeholder: Add screenshot of the drafted color palette here](path/to/draft-colors.png)


### 2. Refining Partner Visibility (Sponsors Logo Contrast) ⏳ *In Progress*
**The Goal:** The sponsor logos currently clash with the site's background due to varied colors and styles. I am exploring ways to isolate them or apply filters so they look clean and uniform.
**Current Tasks:**
- [ ] Test a unified background container for the logo grid.
- [ ] Experiment with CSS filters (e.g., grayscale on resting state, full color on hover) to improve contrast.

**Proposed Solution:**
![Placeholder: Add screenshot of the drafted sponsor logo grid here](path/to/draft-sponsors.png)


### 3. Accessibility Audit (General Color Contrast) 🔍 *Auditing Phase*
**The Goal:** Ensure the website meets WCAG minimum contrast ratios (4.5:1 for normal text). Some light grey text and interactive elements currently fail this standard.
**Current Tasks:**
- [ ] Run a sitewide audit on text-to-background contrast.
- [ ] Document specific elements that need darkening or background adjustments.
- [ ] Finalize the accessible text utility classes.

**Areas Identified for Improvement:**
![Placeholder: Add screenshot of contrast issues being targeted here](path/to/contrast-audit.png)

---

## 📝 Developer Handoff Notes (Draft)
*(Note: These will be finalized once the design phases above are locked in.)*
* **Global Variables:** Will need to update the root CSS file with the final FEOAF hex codes (values TBD).
* **Sponsor Logos:** Will likely require specific CSS filter classes. Code snippets to follow.
* **Text Utility Classes:** Expect a list of updated classes for the global stylesheet to address the contrast fixes.
