# CSS Transforms 
**With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.** 
# Transform Syntax 
**The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.**

![image](Images201/z1.png)
# 2D Transforms 
**Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.**

![image](Images201/z2.png)
# Transform Origin 
+ As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used.

- The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

* Individually the values are treated like that of a background image position, using either a length or keyword value. That said, 0 0 is the same value as top left, and 100% 100% is the same value as bottom right. More specific values can also be set, for example 20px 50px would set the origin to 20 pixels across and 50 pixels down the element.
![image](Images201/z3.png)
# Transitions & Animations 
**One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.**
## Transitions 
+ As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes. 
![image](Images201/z4.png)
### Vendor Prefixes 
+ The code above, as with the rest of the code samples in this lesson, are not vendor prefixed. This is intentionally un-prefixed in the interest of keeping the code snippet small and comprehensible. For the best support across all browsers, use vendor prefixes.

- For reference, the prefixed version of the code above would look like the following.
![image](Images201/z5.png)
## Animations 
+ Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

![image](Images201/z6.png)
![image](Images201/z7.png)
# 8 simple CSS3 transitions that will wow your users 
1. Fade in
+ Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.

2. Change color
+ Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them. Now, we just set the div’s class to “color” and specify the color we want in our CSS:
![image](Images201/z8.png)
3. Grow & Shrink
* To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.
4. Rotate elements
- CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element. Give your div the class “rotate” and add the following to your CSS: 
![image](Images201/z9.png)
5. Square to circle 
6. 3D shadow
7. Swing
8. Inset border

## [Sorce 1](https://learn.shayhowe.com/advanced-html-css/css-transforms/)
## [Sorce 2](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
## [Sorce 3](https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/)
## [Sorce 4](https://codepen.io/retyui/pen/ByoaXV)

