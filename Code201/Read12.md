# EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS 
**Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.**
1. Setting up 

+ The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script: 
2. Drawing a line chart 
- To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page: 
![image](Images201/z11.png)
3. Drawing a pie chart 
![image](Images201/z12.png)
4. Drawing a bar chart 
![image](Images201/z13.png)
5. And finally, we add in the bar chart’s data: 
![image](Images201/z14.png)
# Chart.js docs: 
## Installation
+ You can get the latest version of Chart.js from npm , the GitHub releases , or use a Chart.js CDN . Detailed installation instructions can be found on the installation page.

## Creating a Chart
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single < canvas> node to render the chart.

+ In this example, we create a bar chart for a single dataset and render that in our page. You can see all the ways to use Chart.js in the usage documentation.


## Contributing
+ Before submitting an issue or a pull request to the project, please take a moment to look over the [contributing guidelines](https://www.chartjs.org/docs/latest/developers/contributing.html)first.

- For support using Chart.js, please post questions with the [chartjs tag on Stack Overflow](https://stackoverflow.com/questions/tagged/chart.js?tab=Newest) .

### License
- Chart.js is available under the MIT license .

+ Documentation is copyright © 2014-2021 Chart.js contributors.
[sorce](https://www.chartjs.org/docs/latest/)

# Basic usage of canva
**The < canvas> element**
+ At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the < canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.
**Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the < canvas> attributes, and not using CSS.**
## Fallback content 
+ The < canvas> element differs from an < img> tag in that, like for < video>, < audio>, or < picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

+ Providing fallback content is very straightforward: just insert the alternate content inside the < canvas> element. Browsers that don't support < canvas> will ignore the container and render the fallback content inside it. Browsers that do support < canvas> will ignore the content inside the container, and just render the canvas normally.
## The rendering context 
**The < canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES.**
+ [sorce](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
## Drawing shapes with canvas 
+ Now that we have set up our [canvas environment](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage), we can get into the details of how to draw on the canvas. By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.
## The grid 
![image](Images201/z15.png)
## Drawing rectangles 
![image](Images201/z16.png)
+ [sorce](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes )
## Applying styles and colors 
## [Read The following](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
