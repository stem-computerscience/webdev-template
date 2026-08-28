# Level 4: Anchor Pseudo-class Order

**Lesson:** [Lesson 18 — CSS Pseudo-classes](../README.md)
**Type:** Skill Building
**Source:** https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/18/levels/4

## Instructions

It is recommended that if you are going to use all four states for an anchor tag, you create your rule sets in CSS in the following order:

1. link
2. visited
3. hover
4. active

Setting these out of order on your CSS can create unforeseen actions as the cascading style of CSS can have one property overriding another. In short, if there are competing rule sets, styles declared later typically override those declared earlier.

One way to remember the right order is with the phrase "LOVE, HATE" - LV, HA (Link, Visited, Hover, Active).

### Do This

In the CSS file:
- Add a rule for each of the states for the `<a>` element in the right order.
  - `a:link`
  - `a:visited`
  - `a:hover`
  - `a:active`
- Style each state with a different color and font size.
- Add any other different styles to each state of your choice.

In the Preview Window:
- Click the "Refresh and Save" button to make sure your styles have been applied.
- Test each state to make sure they work.
  - Hover over the link to see your "hover" styling.
  - Slowly click on the link to see your "active" styling.
  - Click on the link and come back to Web Lab to see if the link changed to your "visited" style.

*(Show Me How To Get Started and Help & Tips are available for this level.)*

**Starter files:** index.html, style.css
