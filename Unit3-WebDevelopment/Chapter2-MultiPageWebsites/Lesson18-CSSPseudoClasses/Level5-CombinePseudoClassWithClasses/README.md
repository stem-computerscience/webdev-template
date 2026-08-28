# Level 5: Combine Pseudo-class with Classes

**Lesson:** [Lesson 18 — CSS Pseudo-classes](../README.md)
**Type:** Skill Building
**Source:** https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/18/levels/5

## Instructions

What if you have more than one hyperlink and you want to style them differently? Normally when we have several of the same element but we want to style one of them differently we would give that element a class attribute. Good news! We can do the same thing with pseudo-classes!

To do this, we would use our class attribute in our selector, instead of the anchor tag like this:

```css
.special:visited {
  color: purple;
}
```

Let's try it!

### Do This

In the HTML file:
- Give the first hyperlink a "highlight" class attribute.

In the CSS file:
- Add a rule for the "hover" state of the anchor tag using its "highlight" class attribute in the selector.
  - `.highlight:hover`
- Style this state with a different `background-color` and large font size.
- Add any other different styles to each state of your choice.

In the Preview Window:
- Click the "Refresh and Save" button to make sure your styles have been applied.
- Hover over the first link to see your "hover" styling.
- Hover over the second link to confirm it does not have any "hover" styling.

*(Show Me How To Get Started and Help & Tips are available for this level.)*

**Starter files:** index.html, style.css
