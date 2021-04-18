# Introduction to css 
[Image](/Images/j3.png)
+ In this section, we will look at how to make your web pages more attractive, controlling the design of them using CSS.
## Understanding CSS: Thinking Insi de the Box
+ The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
* CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
[Image](/Images/j4.png)
+ In this example, block level elements are shown with red borders, and inline elements have green borders.
+ The <body> element creates the first box, then the <h1>, <h2>, <p>, <i>, and <a> elements each create their own boxes within it.
+ Using CSS, you could add a border around any of the boxes, specify its width and height, or add a background color. You could also control text inside a box — for example, its color, size, and the typeface used.
## CSS Ass ociates Style rules with HT ML elements
[Image](/Images/j5.png)
## CSS Properties Affect How El ements Are Dis played
[Image](/Images/j6.png)
## Usi ng External CSS 
## <link> 
+ The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes:
1. href This specifies the path to the CSS file (which is often placed in a folder called css or styles).
2. type This attribute specifies the type of document being linked to. The value should be text/css.
3. relThis specifies the relationshipbetween the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.
+ An HTML page can use more than one CSS style sheet. To do this it could have a <link> element for every CSS file it uses. For example, some authors use one CSS file to control the presentation (such as fonts and colors) and a second to control the layout.
[Image](/Images/j7.png)
## Usi ng Internal CSS 
[Image](/Images/j8.png)
##v CSS Selectors
[Image](/Images/j9.png)
## Why use External Style Sheets?
1. All of your web pages can share the same style sheet. This is achieved by using the <link> element on each HTML page of your site to link to the same CSS document. This means that the same code does not need to be repeated in every page (which results in less code and smaller HTML pages).
2. Therefore, once the user has downloaded the CSS stylesheet, the rest of the site will load faster. If you want to make a change to how your site appears, you only need to edit the one CSS file and all of your pages will be updated. For example, you can change the style of every <h1> element by altering
3. the one CSS style sheet, rather than changing the CSS rules on every page. The HTML code will be easier to read and edit because it does not have lots of CSS rules in the same document. It is generally considered good practice to have the content of the site separated from the rules that determine how it appears.
# Color 
[Image](/Images/j10.png)
## Foreground Color color
### rgb values
+ These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
### hex codes
+ These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
### color names
+ There are 147 predefined color names that are recognized by browsers. For example: DarkCyan
## background-color
[Image](/Images/j13.png)
## Understanding Color 
+ Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.
[Image](/Images/j14.png)
[Image](/Images/j15.png)
## Contrast 
[Image](/Images/j16.png)
## CSS 3: Opacity opacity, rgba 
[Image](/Images/j17.png)
## CSS 3: HSL Colors 

[Image](/Images/j18.png)
