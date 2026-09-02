# Flex Shorthand

*"Flex" your skills and learn how to combine `flex-grow`, `flex-shrink`, and `flex-basis` into shorthand!*

# Flex Property

The "flex" property is the shorthand for `flex-grow`, `flex-shrink` and `flex-basis` combined into one line. When we use it in CSS, it looks like this:

```
div {
  flex: 1 0 auto;
}
```

This example sets the `flex-grow` to 1, the `flex-shrink` to 0, and the `flex-basis` to auto. An easy way to think of this and remember the order is to imagine you are setting the **"max"**, **"min"**, and **"ideal size"**. 

_Check out the previous challenge level or the "Help & Tips" tab to learn about `flex-basis`!_

Let's check out what some commonly used value combinations for the `flex` property will do!

# Do This

**In the CSS file:**

::: details [1. Set the child elements of "flex1" to not grow when there is free space, to shrink when there is not enough space, and their size to be based on their content _(expand me to get more instructions)_]
- **Add the `flex` property to the "flex1" child elements with the following three values:**
   - **Set the first "grow" value to 0.** This will make the items _inflexible_ when there is some free space left in the container. 
   - **Set the second "shrink" value to 1.** This will allow the elements to shrink to their minimum size when there is not enough space in the container. 
   - **Set the third "ideal size" value to "auto".** This will size the items based on their content.
:::

<br>

::: details [2. Set the child elements of "flex2" to grow to absorb any extra space, to shrink when there is not enough space, and their size to be based on their content _(expand me to get more instructions)_]
- **Add the `flex` property to the "flex2" child elements with the following three values:**
   - **Set the first "grow" value to 1.** This will make the items absorb any extra space left in the container. 
   - **Set the second "shrink" value to 1.** This will allow the elements to shrink to their minimum size when there is not enough space in the container. 
   - **Set the third "ideal size" value to "auto".** This will size the items based on their content.
:::

<br>

::: details [3. Set the child elements of "flex3" to not grow when there is free space, to not shrink when there is not enough space, and their size to be based on their content _(expand me to get more instructions)_]
- **Add the `flex` property to the "flex3" child elements with the following three values:**
   - **Set the first "grow" value to 0.** This will make the items _inflexible_ when there is some free space left in the container. 
   - **Set the second "shrink" value to 0.** This will not allow the elements to shrink even in an overflow situation. 
   - **Set the third "ideal size" value to "auto".** This will size the items based on their content.
:::

<br>

4. Resize the Preview Window to see the differences between the three layouts. 
   - Make sure you fully expand the Preview Window as well as shrink the window to be very, very small.


<br>



**Make sure to add this to your <a href="https://docs.google.com/document/d/1lrkMGcPwjKo4g5uyvVfaXpFb7kRUfdtqcsqLRtaDWYM/edit?usp=sharing">Flexbox Children Cheat Sheet</a>!**

::: details [Help & Tips]
- [<i class="fa-regular fa-map"></i> Flex Children](https://studio.code.org/courses/csd-2024/guides/flex-children)
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
