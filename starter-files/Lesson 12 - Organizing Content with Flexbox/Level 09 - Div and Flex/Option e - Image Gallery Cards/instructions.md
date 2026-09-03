# Image Gallery Cards

*Learn how to create an image gallery with information underneath each image!*

<img src="https://images.code.org/075a7cf5c1e8fabe115e9f44dda4b274-image-1709228773267.png" style="float: right; width: 200px;">

# Image Gallery Cards

There are many times when we want to create some sort of image gallery with information about each image underneath. This is easier than it sounds when we use `div` containers, Flex and some CSS styles we already know! Let's see how!

# Do This

**In the HTML file:**
1) Add a div with a "gallery" class around ALL content after the main page title.
2) Add a child div with a "ramen-card" class around EACH set of image, h3 tag and paragraph.
   
   :::details [*Click Me To See What This Code Should Look Like*]
   ```
   <div class="ramen-card">
   		<img>
        	<h3> </h3>
     	<p> </p>
   </div>
   ```
   :::
   
3) Add one more child div with a "content" class around EACH set of h3 tag and paragraph.
   
   :::details [*Click Me To See What This Code Should Look Like*]
   ```
   <div class="ramen-card">
   		<img>
        	<div class="content">
        		<h3> </h3>
     			<p> </p>
            </div>
   </div>
   ```
   :::

<br>

**In the CSS file:**
1) Add the following styles to the "gallery" rule set:

   :::details [**Click Me To See The List of "gallery" Class Styles**]
   - Establish flex layout
   - Set the flex content to wrap
   - Define the items to be centered horizontally
   - Set a margin of 20px to keep the cards from getting too close to each other
   :::

<br>

2) Add the following styles to the "ramen-card" rule set:

	:::details [**Click Me To See The List of "ramen-card" Class Styles**]
   - Set the width to 325px
   - Define the border to be solid, 2px wide, and a color of your choice
   - Align the text in the center
   - Set a margin of 10px
   - Establish flex layout for the content within 
   - Set the layout direction to be in a column
   - Align the items to be vertically centered
   :::

<br>

3) Add the following style to the "content" rule set:

	:::details [**Click Me To See The List of "content" Class Styles**]
   - Set the padding to be 10px
   :::
   
<br>

4) Add the following style to apply to all **paragraphs within containers the "ramen-card" class**:

   :::details [**Click Me To See The List of Paragraph Styles**]
   - Set the font size to be 17px
   :::

<br>

5) Add the following styles to the `h3` headings:

   :::details [**Click Me To See The List of `h3` Styles**]
   - Set the bottom margin to be 10px (or less)
   :::

<br>

6) Add the following styles to the images:

   :::details [**Click Me To See The List of Image Styles**]
   - Set the width to be 100%
   :::

<br>

<div>
<img src="https://images.code.org/6a4727a01f98a68d5836dc6cbf02a20c-image-1709229413339.png" style="float: left; width: 150px; margin-right: 10px;">

**Extra Challenge:** Try playing around with the image style ... can you make the image have a border and spaced within the card to look like the image to the left?
</div>
