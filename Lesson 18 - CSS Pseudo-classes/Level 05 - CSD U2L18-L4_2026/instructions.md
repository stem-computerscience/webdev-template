# CSD U2L18-L4_2026

# Anchor Pseudo-class Order

It is recommended that if you are going to use all four states for an anchor tag, you create your rule sets in CSS in the following order:
1. link
2. visited
3. hover
4. active

Setting these out of order on your CSS can create unforeseen actions as the cascading style of CSS can have one property overriding another. In short, if there are competing rule sets, styles declared later typically override those declared earlier.

**One way to remember the right order is with the phrase "LOVE, HATE" - LV, HA (Link, Visited, Hover, Active).**

# Do This

**In the CSS file:**
1. Add a rule for each of the states for the `<a>` element in the right order.
   - `a:link`
   - `a:visited`
   - `a:hover`
   - `a:active`
2. Style each state with a different color and font size.
3. Add any other different styles to each state of your choice.

**In the Preview Window:**
1. Click the "Refresh and Save" button to make sure your styles have been applied.
2. Test each state to make sure they work
   - Hover over the link to see your "hover" styling. 
   - _Slowly_ click on the link to see your "active" styling.
   - Click on the link and come back to Web Lab to see if the link changed to your "visited" style. 
   
<br>

::: details [🔎 **Show Me How To Get Started** 🔍]

<img src="https://images.code.org/2f5beba5755add94ceae9df3522428f8-image-1708196980711.gif" style="width:500px">

:::

<br>

::: details [Help & Tips]
- [<i class="fa-regular fa-map"></i> Pseudo Classes](https://studio.code.org/courses/csd-2024/guides/pseudo-classes)
- [<i class="fa-solid fa-book"></i> Hyperlinks](https://studio.code.org/courses/csd-2024/guides/hyperlinks)
- [<i class="fa-solid fa-book"></i> Flex Children](https://studio.code.org/courses/csd-2024/guides/flex-children)
- [<i class="fa-solid fa-book"></i> Flexbox](https://studio.code.org/courses/csd-2024/guides/flexbox)
- [<i class="fa-solid fa-book"></i> HTML Selectors](https://studio.code.org/courses/csd-2024/guides/html-selectors)
- [<i class="fa-solid fa-book"></i> Div Tags](https://studio.code.org/courses/csd-2024/guides/div)
- [<i class="fa-solid fa-book"></i> Classes](https://studio.code.org/courses/csd-2024/guides/classes)
- [<i class="fa-solid fa-book"></i> Layout Properties](https://studio.code.org/courses/csd-2024/guides/layout-properties)
- [<i class="fa-solid fa-book"></i> Body Styling](https://studio.code.org/courses/csd-2024/guides/body-styling)
- [<i class="fa-solid fa-book"></i> Images in HTML](https://studio.code.org/courses/csd-2024/guides/images-in-html)
- [<i class="fa-solid fa-book"></i> Text Properties](https://studio.code.org/courses/csd-2024/guides/text-properties)
- [<i class="fa-solid fa-book"></i> Creative Commons Search](https://studio.code.org/courses/csd-2024/guides/creative-commons-search)
- [<i class="fa-solid fa-book"></i> Style Sheets](https://studio.code.org/courses/csd-2024/guides/style-sheets)
- [<i class="fa-solid fa-book"></i> Formatting HTML](https://studio.code.org/courses/csd-2024/guides/formatting-html)
- [<i class="fa-solid fa-book"></i> Formatting HTML](https://studio.code.org/courses/csd-2024/guides/formatting-html)
- [<i class="fa-solid fa-book"></i> Lists](https://studio.code.org/courses/csd-2024/guides/lists)
- [<i class="fa-solid fa-book"></i> Headings and Paragraphs](https://studio.code.org/courses/csd-2024/guides/headings-and-paragraphs)
- [<i class="fa-solid fa-book"></i> HTML Tags](https://studio.code.org/courses/csd-2024/guides/html-tags)
- [<i class="fa-solid fa-book"></i> Debugging in HTML](https://studio.code.org/courses/csd-2022/guides/debugging-html)
:::
