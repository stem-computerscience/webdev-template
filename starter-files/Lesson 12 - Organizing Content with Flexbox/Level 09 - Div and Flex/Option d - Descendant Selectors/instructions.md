# Descendant Selectors

*Learn how to style the same type of elements within a container even if they aren't "direct children"!*

# Descendant Selector

If you did the previous challenge level you learned what an HTML "child" is and a "child selector" does. _If you did not do the previous challenge level, consider completing it and then coming back to this level. You can also read the documentation on "CSS Selectors" in the **Help and Tips** dropdown_.

<hr>

The ability to select child elements in a parent is awesome, but what if you want to select **all** the same type of elements within a **parent**, even if it's **not a direct child**?

Easy! We use the **Descendant Selector**!!

::: details [🔎**Click Here For a Visual of the "Parent"/"Child"/"Descendant" Relationship**]

<br>
In this example, the descendant selector will style <b>all</b> the paragraph tags in the main, parent container ... even the one that is not a direct child, but a "descendant."
<div style="width:800px;">
<img src="https://images.code.org/6bad3f9c0f70ee2c9b8d214557fe9444-image-1706819626262.png" style="width: 50%; float:left;">
<img src="https://images.code.org/6c071a78847757a0747519c2d9df1eeb-image-1706893386759.png" style="width: 50%; float: right;">
</div>



:::

<hr style="display: block; clear: left;">

To use a descendant selector, you will format the selector of the rule, like this: 
```
div p {
 font-family: serif;
}
``` 

# Do This

::: details [✔️ **FIRST, EXPAND ME TO SEE HOW THE DESCENDANT SELECTOR WORKS!** ✔️]

**In the HTML file:**

Find the `div` class with the "parent" class attribute in the HTML. 
- Notice how paragraphs 1, 2, and 4 are within the container, while paragraph 3 is a "descendant" of the parent container but not a direct child since it is in its _own_ container, and paragraphs 5 & 6 are not in the container at all.

**In the CSS file:**

Find the rule for the paragraph tags that are children of the parent container in the CSS file.
- The rule looks like this: 
   <img src="https://images.code.org/670d8651173dab087a69ca2603b0ea08-image-1706313408574.png" style="width:250px;">

**In the Preview Window:**

Notice how only **ALL** of the paragraphs in the parent container are getting the yellow background color!

:::

<br>

**YOUR TURN!**

1. Add a rule to the CSS file that uses the descent selector to style **ALL** the images within the container.
2. Give those images the following properties:
   - Width of 100px
   - Yellow border color
   - A  margin of 5px
   
::: details [**EXTRA CHALLENGE**]

Add a rule to the CSS file that uses the **child selector** to style just the first two images in the container.
- Give those two images the following properties:
   - width of 115px
   - Red border color
   - 15px border radius

:::

::: details [Help & Tips]
- [<i class="fa-regular fa-map"></i> Flexbox](https://studio.code.org/courses/csd-2024/guides/flexbox)
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
