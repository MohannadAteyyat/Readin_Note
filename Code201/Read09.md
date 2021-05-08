# Chapter 7: “Forms” 
**Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.**
## Why Forms? 
+ The best known form on the web is probably the search box that sits right in the middle of Google's homepage.
## Form Controls 
**There are several types of form controls that you can use to collect information from visitors to your site.**
![aaa](Images201/a1.png)
### How Forms Work
![images](/Images201/aq2.png)
**A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.**
## Form Structure 
![images](/Images201/aq3.png)
# Chapter 14: Lists, Tables & Forms
**There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.**
![images](/Images201/aq4.png) 
### Images for Bullets
+ You can specify an image to act as a bullet point using the list-style-image property.
+ The value starts with the letters url and is followed by a pair of parentheses. Inside the parentheses, the path to the image is given inside double quotes.
- This property can be used on rules that apply to the <ul> and \<li> elements.
* The example on this page also shows the use of the margin property to increase the vertical gap between each item in the list.
# Positining The Marker
![images](/Images201/aq5.png) 
# Summary
+ In addition to the CSS p XX roperties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
-  List markers can be given different appearances using the list-style-type and list-style image properties.
+  Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
* Forms are easier to use if the form controls are vertically aligned using CSS.
+ Forms benefit from styles that make them feel more
interactive.

## [Sorce](https://drive.google.com/file/d/1OuBQfpRFPnLGq8LmJIgrWFRqQTXUegTr/view?usp=sharing)


# Chapter 6: “Events” 

** When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.**
## DIFFERENT EVENT TYPES 
![images](/Images201/aq6.png) 
## TERMINOLOGY 
**EVENTS FIRE OR ARE RAISED**
- When an event has occurred, it is often described as having fired or been raised. In the diagram on the right, if the user is tapping on a link, a cl ick event would fire in the browser.
**EVENTS TRIGGER SCRIPTS**
+ Events are said to t rigger a function or script. When the click event fires on the element in this diagram, it could trigger a script that enlarges the selected item.
![images](/Images201/aq7.png)
**HOW EVENTS TRIGGER JAVASCRIPT CODE**
- When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling.

1. Select t he element node(s) you want the script to respond to. For example, if you want to trigger a function when a user clicks on a specific link, you need to get the DOM node for that link element. You do this using a DOM query (see Chapter 5).
2. Indicate which event on the selected node(s) will trigger the response. Programmers call this binding an event to a DOM node. The previous two pages showed a selection of the popular events that you can monitor for.
3. State the code you want to run when the event occurs. When the event occurs, on a specified element, it will trigger a function. This may be a named or an anonymous function.

## [Sorce](https://drive.google.com/file/d/1KFKjXZMEVY5OIxIUcUlCzCxCvZvr529K/view?usp=sharing)