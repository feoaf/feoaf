# FEOAF Design

*Note: This is just a rough scratchpad for upcoming design changes. Nothing is finalized yet!*

---

## 🎨 1. Color Palette Ideas
**The vibe right now:** The website's colors feel a bit inconsistent across different pages. We need a tighter, more unified look that fits the FEOAF brand.

**Initial Thoughts:**
* Strip it back to a strict primary, secondary, and accent color.
* Make sure all buttons look like they belong to the same family (need standard resting, hover, and active states).
* Maybe establish a clearer background color hierarchy (e.g., solid white for main content, very light grey for secondary sections).

> **Visual Inspiration / Rough Color Swatches:**
> ![Drop a screenshot of a color generator, inspiration site, or rough Figma board here](placeholder.jpg)

---

## 🤝 2. Fixing the Sponsor Logos (Contrast Issues)
**The vibe right now:** The sponsor logos come in all different colors, shapes, and styles. When they sit on the main website background, the section looks super cluttered and some logos get completely lost.

**Ideas to test out:**
* **Idea A:** Put all the logos inside neutral, unified background containers (like identical white cards with subtle borders).
* **Idea B (Maybe the winner?):** Use CSS filters to make them all grayscale/monochrome by default so they blend in, but have them light up in full color when the user hovers over them.
* **Idea C:** Add a dark overlay behind the entire sponsor section to force the logos to pop.

> **Quick Concept / Mockup:**
> ![Drop a quick screenshot of a grayscale test or layout idea here](placeholder.jpg)

---

## 👓 3. General Color Contrast & Accessibility
**The vibe right now:** I suspect a bunch of our text and small interactive elements might be failing basic web accessibility standards (WCAG). Light grey text is probably the biggest culprit here.

**Game Plan:**
* Run a quick contrast audit across the main pages (looking for that 4.5:1 ratio).
* Darken the standard body text.
* Tweak button background colors so the text inside them is actually readable for people with low vision or low-brightness screens.
* Figure out a new standard hex code for "muted text" that doesn't disappear into the background.

> **Examples of Problem Areas to Fix:**
> ![Drop a screenshot of some hard-to-read text on the live site here as a reminder](placeholder.jpg)

---

## 📝 Random Notes for Later (Dev Stuff)
* When I finalize the colors, I need to make sure the devs use CSS root variables instead of hardcoding hex values everywhere.
* Need to look up the exact CSS code for the grayscale hover effect if we go with Idea B for the sponsors.
