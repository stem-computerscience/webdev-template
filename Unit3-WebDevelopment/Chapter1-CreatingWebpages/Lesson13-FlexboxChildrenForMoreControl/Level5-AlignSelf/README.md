# Level 5: Align-self

**Lesson:** [Lesson 13 — Flexbox Children for More Control](../README.md)
**Type:** Skill Building
**Source:** https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/13/levels/5

## Instructions

The `align-self` property aligns an item in a flex container. It is important to remember that this property overrides the container's `align-items` value.

The second item in the example image has an `align-self` value of `flex-end`.

### Do This

**In the HTML file:**
- Give the second child item inside the "flex-align" parent a class attribute of `"align"`.

**In the CSS file:**
- Add a rule in the CSS file for the second child item using its class attribute as the selector.
- Give the item the `align-self` property.
- Try out the different values:
  - `flex-end`
  - `flex-start`
  - `center`
  - `stretch`
  - `baseline` (you will only see a visual difference with this value if the items have different heights)

*Guided walkthrough available: "Show Me How To Get Started." Don't forget to refer back to your Flexbox Children Cheat Sheet when needed!*

**Files:** `index.html`, `style.css`
