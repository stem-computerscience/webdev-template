# CSD U2L18-L5_2026

# Combine Pseudo-class with Classes

What if you have more than one hyperlink and you want to style them differently? Normally when we have several of the same element but we want to style one of them differently we would give that element a class attribute. Good news! We can do the same thing with pseudo-classes!

To do this, we would use our class attribute in our selector, instead of the anchor tag like this:

```
.special:visited {
  color: purple;
}
```

Let's try it!

# Do This

**In the HTML file:**
1. Give the first hyperlink a "highlight" class attribute.

**In the CSS file:**
1. Add a rule for the "hover" state of the anchor tag using its "highlight" class attribute in the selector.
   - `.highlight:hover`
2. Style this state with a different background-color and large font size.
3. Add any other different styles to each state of your choice.

**In the Preview Window:**
1. Click the "Refresh and Save" button to make sure your styles have been applied.
2. Hover over the first link to see your "hover" styling.
3. Hover over the second link to confirm it does not have any "hover" styling.

<br>

::: details [🔎 **Show Me How To Get Started** 🔍]

<img src="https://images.code.org/e78d1254d55db0e3fc7c07d1d9fddc19-image-1708197128500.gif" style="width:500px">

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
