# Level 4: Order Property

**Lesson:** [Lesson 13 — Flexbox Children for More Control](../README.md)
**Type:** Skill Building
**Source:** https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/13/levels/4

## Instructions

Since Flex is a layout system that arranges items in rows and columns, the position of each item can be specified with the `order` property. The `order` property sets the item order relative to the other items inside the container.

Each item inside the container in the example image has set its own order.

### Do This

**In the HTML file:**
- Give each child item inside the "flex-order" parent a specific class attribute:
  - Give the first item the class attribute `"item-a"`
  - Give the second item the class attribute `"item-b"`
  - Give the third item the class attribute `"item-c"`
  - Give the fourth item the class attribute `"item-d"`

**In the CSS file:**
- Add a rule in the CSS file for each of the child items using their class attribute as the selector.
- Set each item's order using the `order` property:
  - Set the order of `"item-a"` to be `3`
  - Set the order of `"item-b"` to be `2`
  - Set the order of `"item-c"` to be `4`
  - Set the order of `"item-d"` to be `1`

*Guided walkthrough available: "Show Me How To Get Started." Don't forget to refer back to your Flexbox Children Cheat Sheet when needed!*

**Files:** `index.html`, `style.css`
