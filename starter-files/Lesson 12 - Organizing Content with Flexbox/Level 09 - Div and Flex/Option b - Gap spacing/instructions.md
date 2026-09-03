# Gap spacing

*Learn a new property to control the spacing between rows and columns*

<img src="https://images.code.org/904a09e6a6bdb840557b0e5d800ec9ed-image-1706747985587.png" style="width:300px; float:right;">

# Row & Column "Gap"

The **gap property** explicitly controls the space **between** flex items. It applies that spacing _only between items_ not on the outer edges.

The behavior could be thought of as a _minimum space_. If the space is bigger somehow (if you had `justify-content: space-between;` for example) then the gap will only take effect if that space would end up smaller.

`grid-gap` accepts one or two values:
* A single value sets both `grid-row-gap` and `column-gap` by the same value
   - _See the spacing between the rows and columns of the items in the first, purple container to the right._
* When two values are used, the first sets the `grid-row-gap` and the second sets the `column-gap`
   - _See the different spacing between the rows and columns of the items in the second, teal container to the right._

# Do This

1. Assign the gap property to each container in the CSS to match the spacing of the items in the image to the right.
   - Give the 1st container the `grid-gap` property and define both the row and column spacing to be 50px.
   - Give the 2nd container the `grid-gap` property and define the spacing to be 10px between the rows and 50px between the columns.
   - Give the 3rd container the `grid-gap` property and define the spacing to be 50px between the rows and 10px between the columns.
   - Give the 4th container the `grid-row-gap` property and define the spacing between the rows to be 60px.
   - Give the 5th container the `column-gap` property and define the spacing between the columns to be 60px.
   - Give the 6th container the `grid-gap` property and define the spacing between rows to be 25px and spacing between columns to be 70px.

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
