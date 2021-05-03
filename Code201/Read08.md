# Chapter 15 Layout
**In this chapter we are going to look at how to control where each element sits on a page and how to create attractive page layouts.**
## Key Concepts in PositioningEl ements
1. Building Blocks 
+ CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
2. Containing Elements
- If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. 
## Controll ing the Position of El ements
+ CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
1. Normal flow: 
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
2. Relative Positioning: This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.
3. Ab solute positioning :This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.
![Image](/Images201/qwer4.png)
## [Sorce](https://drive.google.com/file/d/1OuBQfpRFPnLGq8LmJIgrWFRqQTXUegTr/view?usp=sharing)