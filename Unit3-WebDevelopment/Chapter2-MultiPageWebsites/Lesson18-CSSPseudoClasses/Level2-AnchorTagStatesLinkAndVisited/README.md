# Level 2: Anchor Tag States - "link" & "visited"

**Lesson:** [Lesson 18 — CSS Pseudo-classes](../README.md)
**Type:** Skill Building
**Source:** https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/18/levels/2

## Instructions

An anchor (`<a>`) tag has four states:
- **link:** when the link has not yet been clicked
- **visited:** when the link has been clicked (clicking a link "visits" that linked page, hence the name "visited")
- **hover:** when the mouse is hovered over, but not clicked, the link
- **active:** the moment the mouse is actively clicking down on the link

We style these states using pseudo-classes. In the example below, we specify the anchor element selector, a colon, and the name of the anchor state:

```css
a:hover {
  color: yellow;
}
```

Let's give the first two states a try!

### Do This

In the CSS file:
- Add a rule to style the "link" state of the `<a>` element.
  - The selector of your rule should look like this: `a:link`
  - Add the `color` property with a value of your choice.
  - This will define what your link looks like when it has not been clicked - Add any other properties of your choice.
- Add a rule to style the "visited" state of the `<a>` element.
  - The selector of your rule should look like this: `a:visited`
  - Add the `color` property with a different color than the "link" state.
  - This will define what your link looks like when it has been clicked - Add any other properties of your choice.

In the Preview Window:
- Click on the link. A new tab with "google.com" should open. Come back to Web Lab to see the changes to the look of your link.
- You may need to click the "Refresh and Save" button to see the "visited" style applied to your hyperlink.

*(Show Me How To Get Started and Help & Tips are available for this level.)*

**Starter files:** index.html, style.css
