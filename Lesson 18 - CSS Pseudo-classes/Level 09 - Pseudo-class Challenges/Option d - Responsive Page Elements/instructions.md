# Responsive Page Elements

*Learn how to create responsive image cards!*

<img src="https://images.code.org/13aeb64e1e339b1319ea917c801d19d2-image-1709232083439.gif" style="float: right; width: 350px;">

# Transforming Image Cards

Back in Chapter 1, you learned how to create "product cards" - an image gallery with information about each image underneath. With our "hover" pseudo-class, we can make these cards even more visually appealing and responsive to our users by using two new properties: `transform` and `transition`. 

The `transform` property applies 2D or 3D transformation to an element. This property allows you to rotate, scale, and move elements! There are _many_ value options!

The `transition` property specifies the duration and time for `transform` property. The syntax of this property looks like this: `transition: property duration timing;`

_We'll also see how to change our mouse cursor when we hover over an image card using CSS to draw attention to them._

Let's try this out!

# Do This

**In the CSS file:**
1) Add a rule for the "hover" pseudo-class for the "ramen-card" class.
2) Add the `transform` property with the value of `translateY(-15px)`
   - _This will set the card to move up by 15 pixels._
2) Add the `transition` property to the "ramen-card" rule set with a value of `transform 0.3s ease-in-out;`
   - _This will set the type of transition to "transform" (which we just set in step 2), with a 0.3 duration for the transition, and to ease in and out of the transition._
4) Add the `cursor` property with a value of `pointer` to the "ramen-card" rule set.

**BONUS:** Play around with different `transform` values! Here's a list of some to try:
- `translateX(px);` - moves the card left or right depending on if the number px is positive or negative
- `translate(x, y);` - moves the card left/right and up/down depending on if the number for eachc px is positive or negative
- `scale(x, y);` - resizes the card in both directions. For example, `scale(1.5, 1.5);` will have your card get bigger by 1.5 on both axis.
- `scaleX(x);` - resizes the card horizontally
- `scaleY(y);` - resizes the card vertically
- `rotate(deg);` - rotates the card by the number degrees indicated. Note: the value in the parenthesis should be written as follows: `rotate(20deg);`

**HAVE FUN WITH THESE RESPONSIVE TECHNIQUES!**
