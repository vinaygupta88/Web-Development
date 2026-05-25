## Day 1
<h2>Cascading Style Sheet</h2>

- Css stands for Cascading Style Sheet, it is a language that is used to decribe the <b>style</b> of a document.
- Syntax : <b>selector{property:value;}</b>.
- There aare three type of CSS: Inline css,Internal css and External css.
1. Inline css : Inline Css is used directly in HTML tag using style attribute.<br>
    eg: < h1 style="color:red> Text/Content </ h1>
2. Internal css: Internal css is used within the <b>head</b> tag in HTML page.<br>
    eg: inside head tag - < style>selector{property:value;}</ style>
3. External css: External css is type of CSS file which is located in any where . All the css is written is separate document and linking it with HTML . This file is link with HTML file using link tag in head section .<br>
    eg: < link rel="stylesheet" href="style.css">
- Priority: inline >  external > internal 
- If external style is link before style tag in head the style tag css is applied vis-versa
<hr>

<h2>Color Property</h2>
Used to set the color of foreground eg: color:red; color:green;

- Background Color:  used to set the background color of an element. eg: background-color:red;
- RGB is used to select multiple color , in RGB there is three color- red,green,blue. eg: rgb (0,0,0). The range of color is 0-255.
- Hex is also used to gave the color. eg: # f00000, in this 2 character is used for each 00-r, 00-g, 00-b.
---
## Day 2
<h2>Selectors</h2>

1. Universal Selector[*{}]- It apply on all element of html.
2. Element Selector[p{}]- It apply on particular element in whole page it is used.
3. Id Selector[#myid{}]- It apply on particular ID only. Id is unique.
4. Class Seclector[.myclass{}]- It apply on particular Class only. Class may be used for multiple element.

<b>Task 1-</b> a. Create a simple div with an id "box", add some text content inside the div set bacground-color to blue.<br>
b. Create 3 heading with h1,h2,h3. Give them all a class "heading" and set color of "heading" to red.<br>
c. Create a button & set its background color to : green using css style sheet, blue using < style > tag and pink using inline style.
