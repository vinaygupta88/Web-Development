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

---
## Day 3 
<h2>Text Properties</h2>

1. text-align : It is used to align the text either Left/Right or center. eg: text-align:center;
All the text by default left align.
- this property apply only its parent element only not page.
2. text-decoration: How to use line on text.(underline, overline,line-through).
3. font-weight : It used to dark the text (light or dark). eg:(normal,bold,bolder,lighter). Range- 100 - 900.
4. font-famliy : used to style the text like arial,times new roman, and etc. eg:- font-family:italic;
5. Unit in css- Used to resize the text size.
    a. Absolute: pixels(px)- small and most useable unit.
    b. Relative: these are the units which behave differnt for same value. There are some most used units are-- **%, em, rem**
        i. Percentage(%)- it is often used to define a size as relative to an element's parent object. eg:- width:100%;
        ii. Em(em)- Font size of the parent, in the case of **typographical properties** like font-size. eg:- font-size:2em; (2 times of parent's font size)
        iii. Root Em(rem)- Font size of the root element.
6. text-transform : used to change the formate of text eg;- text-transform: uppercase/ lowercase /capitalize/ none.

<b>Task 2-</b> a. Create a heading on the page with all of its text Capitalized by default.
            b. Set the font family of all the content in the document to "Times New Roman".
            c. Create one div inside the another div. Set id and text "outer" for the first one & "inner" for the second one. Set the outer div text size to 25px & inner div text size to 10px.
--- 
## Day 4

<h2>Box Model</h2>

```
        ----------------------------------------
        |             Margin                    |
        |   ---------------------------------   |
        |   |          Border               |   |
        |   |   ------------------------    |   |
        |   |   |      Padding          |   |   |
        |   |   |     --------------    |   |   |
        |   |   |     |  Content   |    |   |   |
        |   |   |     |            |    |   |   |
        |   |   |     --------------    |   |   |
        |   |   -------------------------   |   |
        |   |                               |   |
        |   ---------------------------------   |
        |                                       |
        -----------------------------------------
```
1. Height: By default, it sets the content area height of element.
2. Width:  By default, it sets the content area width of element.
3. Border: used to set an element's border. it user three property.
    a. border-width: 2px;
    b. border-style:solid/dotted/dashed;
    c. border-color:black;
    ** all three property are merge in single called "shorthand" eg:- border:2px solid black;
    ** border-radius: used to make border in round shape. For circular it must be 50% meanse it design circle(height=width). eg:- border-radius: 50%
4. Padding: It add addition space around content. it has four property-
    a. padding-top:10px
    b. padding-right: 10px
    c. padding-bottom: 10px
    d. padding-left: 10px
    ** shorthand - padding:10px means from all four side, / padding: 10px 0px 5px 10px;
5. Margin: It add addition space around content. it has four property-
    a. margin-top:10px
    b. margin-right: 10px
    c. margin-bottom: 10px
    d. margin-left: 10px
    ** shorthand - margin:10px means from all four side, / margin: 10px 0px 5px 10px;(top right bottom left)
<b>Task 3- </b> a. Create a div with heaight & widthof 100 px, Set its background color to green & the border radius to 50%.
    b. Create the following navbar

    ```  
    amazon.in           Account         My Cart         Contact Us          Search Box    
    ```
---
## Day 5
<h2>Display Property</h2>

- display: inline/block/inliine-block/none
1. inline- Takes only the space required by the element (no margin/padding).
2. block- Takes full space available in width.
3. inline-block- Similar to inline but we can set margin & padding.
4. none- To remove element from document flow.

<h2>Alph channel </h2>
<p>ppacity : eg:- rgba(25,0,0,10,)</p>

<b>Task 4- </b>a. Create a webpage layout with a header. a footer & a content area containg 3 divs. Set the height & width of divs to 100px.(add the previous navbar in the header)
    b. Add Borders to all the divs.
    c. Add a different background color to each div with an opacity of 0.5
    d. Give the content area an appropriate height.

---
## Day 6
<h2>Position Property</h2>
The position CSS property sets **how an elemnt is positioned **in a document.
eg:- position:static/relative/absolute/fixed.

1. static- Default position(Top,right,bottom,left and z-index properties have no effect).
2. relative- element is relative to itself.(Top, right, bottom, nd z-index will work).
3. absolute- positioned relative to its closest positioned ancestor (removed from flow).
4. fixed- positioned relative to browser (removed from flow).
5. sticky- positiooned based on user's scroll position.
6. z-index- it decides the stack level of elements. Overlapping elements with a larger z-index cover those with a smaller one. eg:- z-index: auto/ 1/2/3/.../-1/-2/-3...... 

<h2>Background Image</h2>
This is the CSS property, used to set an image as background. eg:-background-image:url("image path");

- To set the background image so that image can't stuck we have to add extra property called background-size:cover/contain/auto;
1. cover- it cover complete space , no empty space left
2. contain- it fit the image in container but if space is available the image is repeat.

<b>Task 5- </b>Create the following layout using the given html.
    . Give the div a height, width & some background image.
    . Use the appropriate position prperty for the div element to place it at the right end of the page.(The div should not move even on sroll)
    < p>lorem*5</ p>
    < div>Love Nature</ div>
    < p>lorem*5</ p>
    
---
## Day 7
<h2>FlexBox</h2>
It is a one-dimenstional layout method for arranging items in rows or columns.

1. Flexbox Direction: It sets how flex item are placed in the flex container, along which axis and direction. eg:- **flex-direction:row/row-reverse/column/column-reverse;**
2. Flex Properties:-
    a. justify-content: alignment along the main axis. eg:- flex-start/flex-end/centre/space-evenly/space-around/space-between
    b. flex-warp: nowrap/wrap/wrap-reverse
    c. align-items: alignment along the cross axis.
    d. align-content: alignment of space between & around the content along cross -axis
    e. align-self: alignment of individual along the cross axis.
    f. flex-grow: how much a flex item will grow relative to the rest of the flex item if space is available.
    g. flex-shrink: how much a flexitem will shrink relative to the rest of the space is availabe.

<b>Task 6- </b>Create a navbar with 4 options in the form of anchor tags inside list items.Now, use flexbox to place them all spaced equaly in a single line.
        Use flexbox to center one div inside another div.
        Which has higher priority-align-items or align-self

<h2>Meadia Queeries</h2>
Help create a responsive website

```
@media(width/ min-width/ max-width:600px){
    div{
        background-color:red
    }
}

@media(min-width:500px and max-width:800px){
    div{
        font-size:12px;
    }
}
```
## Day 8
<h2>Transitions</h2> 
Transitions enable you todefine the transition between two states of an element.

- tansition-property: property you want to transition(font-size,width, etc)
- transition-duration:2s/4ms .....
- transition-timing-function: ease-in/ease-out/linear/steps....
- transition-delay: 2s/4ms ....
* Transition hai mainly two use property - hover and active 
 **transition: property name | duration | timing-function |delay**

<h2>Css transform</h2>
Used to apply 2D & 3D transformations to an element

1. rotate- transform:rotate(45deg);

```
                ^
                |   /           rotateX:45deg;    
                |  /            rotateY:45deg;
                | /) 45         rotateZ:45deg;
    <----------------------->
                |
                |
                |
                v
    * transition : translate(100); - used to move element it could be in x, y or (x,y)
    * transition: skew() used to sretch and item diagonaly
```

<h2>Animation</h2>
To animate CSS element. It define by using @keyframes. It work only when we use animation property.

```
@keyframe myName{
    from{font-size:20px;}
    to{font-size:40px}
}
>> property:
    animation-name, animation-duration, animation-timing-function, animation-delay, animation-iteration-count, animation-direction
    ** shorthand--- animation: name duration timing-function delay iteration-count direction;
```
<b>Task 7- </b>Create a simple loader using CSS with following step:

- Create a div with circular shape & a thik border from one end(top/bottom/left/right)
- To make it spin create an animation which transform it from 0 deg to 360 deg.
- Add the animation property to thh loader with infinite duration.
---

# Project
<h1>Amazon Webpage clone</h1>

- This is the clone of Amazon website, where only frontend part is design using **html and Css**.<br>
To build this project(Amazon website clone) i used some external website for help like-

1. Icon- https://fontawesome.com/
2. Font- https://cdnjs.com/ (it used for both font and icon)