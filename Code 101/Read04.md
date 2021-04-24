#  Dynamic web pages with JavaScript 
## HOW HTML, CSS,
# JAVASCRIPT FIT TOGETHER
+ Before diving into the JavaScript language, you need to know how it will fit together with the HTML and CSS in your web pages. 
1. Web developers usually talk about three languages that are used to create web pages: HTML, CSS, and JavaScript. 
2. Where possible, aim to keep the three languages in separate files, with the HTML page linking to CSS and JavaScript files. 
Each language forms a separate layer with a different purpose. Each layer, from left to right. builds on the previous one.
![Image](/Images/555.png)
![image](/Images/666.png)
# PROGRESSIVE ENHANCEMENT
* These three layers form the basis of a popular approach to building web pages called progressive enhancement
![image](/Images/777.png)
## CREATING A BASIC JAVASCRIPT 
- JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script. This example adds a greeting into an HTML page. The greeting changes depending on the time of day. 
1. 0 Create a folder to put the example in called cOl, then start up your favorite code editor, and enter the text to the right. A JavaScript file is just a text file (like HTML and CSS files are) but it has a . j s file extension, so save this file with the name add-content . j s
2. Get the CSS and images for this example from the website that accompanies the book: [www.javascriptbook. com ]
3. 9 In your code editor, enter the HTML shown on the left. Save this file with the name add-content.html
3. Open the HTML file in your browser. You should see that the JavaScript has added a greeting (in this case, Good Afternoon!) to the page. (These greetings are coming from the JavaScript file; they are not in the HTML file.) 
5. f) Once you have tried the example in your browser, view the source code for the page. (This option is usually under the View, Tools or Develop menu of the browser.) 
6. The source of the web page does not actually show the new element that has been added into the page; it just shows the link to the JavaScript file. 
7. Finally, try opening the HTML file, removing the src attribute from the opening <script> tag, and adding the new code shown on the left between the opening <script> tag and the closing </script> tag. The s re attribute is no longer needed because the JavaScript is in the HTML page.
8. Open the HTML file in your web browser and the welcome greeting is written into the page. 


[http://www.javascriptbook/](http://www.javascriptbook/) 
## LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE 
+ When you want to use JavaScript with a web page, you use the HTML <script> element to tell the browser it is coming across a script. Its s re attribute tells people where the JavaScript file is stored. 
# How to usr objects and methodes 
![Image](/Images/888.png)
## JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML
+ When the browser comes across a <script> element, it stops to load the script and then checks to see if it needs to do anything. 
![image](/Images/999.png)
# Bacic Javascript Instruction
+ In this chapter, you will start learning to read and write JavaScript. You wil l also learn how to give a web browser instructions you want it to follow.
## STATEMENTS 
+ A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.  
![image](/Images/10.png)
## COMMENTS 
+ You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 
## WHAT IS A VARIABLE? 
 A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables. 
 + A variable is a good name for this concept because the data stored
in a variable can change (or vary) each time a script runs. 
![image](/Images/11.png)
![image](/Images/12.png)
### DATA TYPES 
* JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.  
## USING A VARIABLE TO STORE A NUMBER 
+ Here, three variables are created and values are assigned to them.
-  price holds the price of an
individual tile
- quantity holds the number
of tiles a customer wants
- tota 1 holds the total cost of the tiles 

## USING A VARIABLE TO STORE A STRING 
- For the moment, concentrate on the first four lines of JavaScript. Two variables are declared (username and message), and they are used to hold strings (the user's name and a message for that user). 
-  The code to update t he page (shown in the last four lines) is discussed fully in Chapter 5. This code selects two elements using the values of their id attributes. The text in those elements is updated using the values stored in these variables. 
## USING QUOTES INSIDE A STRING
+ Sometimes you will want to use a double or single quote mark within a string. 
## USING A VARIABLE TO STORE A BOOLEAN
+ A Boolean variable can only have a value of true or fa 1 se, but this data type is very helpful.  
## SHORTHAND FOR CREATING VARIABLES
+ CHANGING THE VALUE OF A VARIABLE
## RULES FOR NAMING VARIABLES 
1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number
2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name. 
3. You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
4. All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases. 
5. Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age. 
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash) 
