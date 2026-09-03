# Create Borders

*Create borders around the elements on your page.*

<div class="no-pullthrough" style="float: right; height: 250px; width: 40%; overflow-y: scroll; margin-left: 20px; font-size:14px" markdown="1">

::: details [**What colors can I use in CSS?**]
CSS includes most common color names (red, blue, green, etc.), and many uncommon ones.  You can see a full list of CSS color names at <a href="http://www.w3schools.com/colors/colors_names.asp" target="_new">W3Schools - HTML Color Names</a>.  You can still use colors that are not included in the named list, but you will need to use their RGB values.  You can read more about using colors in CSS at <a href="http://www.w3schools.com/cssref/css_colors_legal.asp" target="_new">W3Schools - CSS Legal Color Values</a>
:::

::: details [**How does the code work?**]
Here is the code that is making the image borders:

```
img {
  border-color: saddlebrown;
  border-width: 4px;
  border-style: solid;
  border-radius: 10px;
}
```

* `img` is the _selector_.  It specifies which elements will have to follow the rules inside the curly braces, in this case, the images.
* `border-color: saddlebrown;`,`border-width: 4px;`,`border-style: solid;`, and `border-radius: 10px;` are the rules that make the border.
:::

::: details [**What does the `border-style` property do?**]
The `border-style` property determines what kind of border (solid, dotted, etc.) the element has.  You can read more about this property at <a href="http://www.w3schools.com/cssref/pr_border-style.asp" target="_new">W3Schools - CSS border-style Property</a>
:::

::: details [**What does the `border-radius` property do?**]
The `border-radius` property determines the radius of the curves at the corners of the element.  A bigger radius makes a bigger, softer curve, and a smaller radius makes a smaller, sharper curve.  A radius of zero makes a regular corner.  You can read more about this property at <a href="http://www.w3schools.com/cssref/css3_pr_border-radius.asp" target="_new">W3Schools - CSS3 border-radius property</a>
:::

::: details [**What does the `float` property do?**]

The `float` property makes an element "float", meaning that the elements that come after it all flow around it.  If the `float` value is `left`, the element will float to the left, and the elements after it will show up on its right.  If the `float` value is `right`, the element will float to the right, and the elements after it will show up on its left.  You can read more about this property at <a href="http://www.w3schools.com/cssref/pr_class_float.asp" target="_new">W3Schools - CSS float Property</a>


:::
</div>

# Borders

* Find the rules in the style sheet that set image borders color and width.
* Change the color and width of your borders.
* Try out some different border styles.
  * Choose from `dotted`, `dashed`, `solid`, and `double`
* Put a border on another type of page element, such as one of the headings or the paragraphs.

::: details [Help & Tips]
- [<i class="fa-regular fa-map"></i> Layout Properties](https://studio.code.org/courses/csd-2024/guides/layout-properties)
- [<i class="fa-solid fa-book"></i> Body Styling](https://studio.code.org/courses/csd-2024/guides/body-styling)
- [<i class="fa-solid fa-book"></i> Images in HTML](https://studio.code.org/courses/csd-2024/guides/images-in-html)
- [<i class="fa-solid fa-book"></i> Creative Commons Search](https://studio.code.org/courses/csd-2024/guides/creative-commons-search)
- [<i class="fa-solid fa-book"></i> Style Sheets](https://studio.code.org/courses/csd-2024/guides/style-sheets)
- [<i class="fa-solid fa-book"></i> Text Properties](https://studio.code.org/courses/csd-2024/guides/text-properties)
- [<i class="fa-solid fa-book"></i> Formatting HTML](https://studio.code.org/courses/csd-2024/guides/formatting-html)
- [<i class="fa-solid fa-book"></i> Lists](https://studio.code.org/courses/csd-2024/guides/lists)
- [<i class="fa-solid fa-book"></i> Headings and Paragraphs](https://studio.code.org/courses/csd-2024/guides/headings-and-paragraphs)
- [<i class="fa-solid fa-book"></i> HTML Tags](https://studio.code.org/courses/csd-2024/guides/html-tags)
- [<i class="fa-solid fa-book"></i> Debugging in HTML](https://studio.code.org/courses/csd-2022/guides/debugging-html)
:::
