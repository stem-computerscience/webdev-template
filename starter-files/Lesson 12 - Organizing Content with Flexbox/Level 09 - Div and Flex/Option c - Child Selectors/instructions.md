# Child Selectors

*Learn how to style an element within a container differently than the rest!*

# Child Selector

The "child selector" selects all elements that are the "children" of a specified element.

::: details [🔎**Click Here For a Visual of the "Parent"/"Child" Relationship**]

<div style="width:800px;">
<img src="https://images.code.org/6bad3f9c0f70ee2c9b8d214557fe9444-image-1706819626262.png" style="width: 50%; float:left;">
<img src="https://images.code.org/76f33c385256c63653553adee40ea82c-image-1706818742325.png" style="width: 50%; float: right;">
</div>



:::

<hr style="display: block; clear: left;">


To style child elements you will use the `>` character in the selector of the rule, like this: 
```
div > p {
 font-family: serif;
}
``` 

# Do This

::: details [✔️ **FIRST, EXPAND ME TO SEE HOW THE CHILD SELECTOR WORKS!** ✔️]

<br>

**In the HTML file:**

Find the `div` class with the "parent" class attribute in the HTML. 
- Notice how paragraphs 1, 2, and 4 are direct children within the container 
- Notice how paragraph 3 is inside the container **but** in its _own_ container. This makes paragraph 3 a "descendant" of the parent container but _not_ a _direct child_.
- Notice how paragraphs 5 & 6 are not in the container at all.

**In the CSS file:**

Find the rule for the paragraph tags that are children of the parent container in the CSS file.
- The rule looks like this: <img src="https://images.code.org/7a3c58d67c23f9c3e29223f30f27bf83-image-1706313834923.png" style="width:250px;">

**In the Preview Window:**

Notice how only the paragraphs that are children of the parent container are getting the yellow background color!

:::

<br>

**YOUR TURN!**

1. Add a rule to the CSS file that uses the child selector to style the images within the container.
2. Give those images the following properties:
   - Width of 75px
   - Solid border style
   - 30px margin

::: details [💪🏽 **Extra Challenge!**]

Can you figure out how to use the child selector to style just the _first two images in the container_?
- Give those two images the following properties:
   - Yellow border color
   - 25px border radius

:::
