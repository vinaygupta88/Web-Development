## Day 1

<h2>JavaScript</h2>
JavaScript is programming langauage. We use it to give instructions to the computer.Java is Dynamically type .<br>
Input(code ---> Computer ---> Output)

- console.log : it is used to log(print) a message to the console _console.log("message");_ _Ctrl + l_ is used to clear the console.
To connect the JS file HTML file is required. It's connect through HTMl using tag inside the HTML Body section -
`     *< script src="script.js"></ script>*
    `
<h2>Variable</h2>
Variable are containers for data. eg:- age=24 , name= "Tony Starks" <br>
To define any variable  good practice is to give meaningfull name of variable.

1. Variable Rules:
   - Variable names are case sensitive ; "a" & "A" is different.
   - Only letters, digits, underscore(\_) and $ is allowed. (not even space)
   - Only a letter, underscore(\_) or $ should be 1<sup>st</sup> character.
   - Reserved words cannot be variable names.(https://www.w3schools.com/js/js_reserved.asp)
2. Variable Defining: - var : Variable can be re-declared & updated. A globale scope variable. eg:- _var age = 24_ - let : Variable cannot be re-declared but can be updated. A block scope variable. eg: _let name="Vinay"_ - cont : Variable cannot be re-declared or updated. A block scope Variable. eg: _const PI=3.14_
<h2>DataType</h2>
JavaScript data types define what kind of values a variable can hold and how those values behave in a program. <br>
JavaScript data types are categorized into Primitive and Non-Primitive types:<br>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20250726112918113495/data_types_in_javascript.webp" alt="Datatype"> <br>

3. The **Number** data type in JavaScript includes both integers and floating-point numbers. Special values like Infinity, -Infinity, and NaN represent infinite values and computational errors, respectively. eg:- _let n1 = 2;_
4. A **String** in JavaScript is a series of characters that are surrounded by quotes. There are three types of quotes in JavaScript, eg:- _let s1 = "Hello There";_
5. The **boolean** type has only two values i.e. true and false. eg:- _let b1 = true;_
6. The special **null** value does not belong to any of the default data types. It forms a separate type of its own which contains only the null value. eg:- _let age = null;_
7. A variable that has been declared but not initialized with a value is automatically assigned the **undefined** value. It means the variable exists, but it has no value assigned to it.eg:- _let a;_
8. **Symbols**, introduced in ES6, are unique and immutable primitive values used as identifiers for object properties. eg:- _let s1 = Symbol("Geeks");_<br>A Symbol is Never Equal to Another One
9. **BigInt** is a built-in object that provides a way to represent whole numbers greater than 253. eg:- _let b = BigInt("0b1010101001010101001111111111111111");_
10. JavaScript **objects** are key-value pairs used to store data, created with {} or the new keyword. They are fundamental as nearly everything in JavaScript is an object. eg:-_let gfg = {
    type: "Company",
    location: "Noida"
    }_
11. An **Array** is a special kind of object used to store an ordered collection of values, which can be of any data type. eg:- _let a1 = [1, 2, 3, 4, 5];_
12. A **function** in JavaScript is a block of reusable code designed to perform a specific task when called. eg:- _function greet(name) {
    return "Hello, " + name + "!";
    }_
13. The **Date object** in JavaScript is used to work with dates and times, allowing for date creation, manipulation, and formatting. eg:- _let currentDate = new Date();_
14. A **RegExp (Regular Expression)** in JavaScript is an object used to define search patterns for matching text in strings. eg:- _let result = pattern.test("Hello, world!");_

---

## Day 2

<h2>Comments</h2>
Part of Code which is <b>not executed</b> eg:- // this is comment single line <br>/*This is a multiline comment*/

<h2>Operators</h2>
Operators in JavaScript is used to perform some Operation on Data.<br><img src="https://www.learnsimpli.com/wp-content/uploads/2020/02/3-4.png"  height=200px alt="Type of Operators">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20250730195424838609/privacy_and_surveillance_threats.webp"  height=200px alt="Type of Operators"><img src="https://media.geeksforgeeks.org/wp-content/uploads/20250730195456311273/extortion_and_deception_threats.webp"  height=200px alt="Type of Operators"><img src="https://media.geeksforgeeks.org/wp-content/uploads/20250730195443180320/features_of_sora_3.webp"  height=200px alt="Type of Operators"><br>

<h2>Conditional Satements</h2>
JavaScript conditional statements are used to make decisions in a program based on given conditions. They control the flow of execution by running different code blocks depending on whether a condition is true or false.
<table border="1" cellpadding="10" cellspacing="0" >
    <tr>
        <th>Conditional Statement</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>if statement</td>
        <td>Executes a block of code if a specified condition is true.</td>
    </tr>
    <tr>
        <td>else statement</td>
        <td>Executes a block of code if the same condition of the preceding if statement is false.</td>
    </tr>
    <tr>
        <td>else if statement</td>
        <td>Adds more conditions to the if statement, allowing for multiple alternative conditions to be tested.</td>
    </tr>
    <tr>
        <td>switch statement</td>
        <td>Evaluates an expression, then executes the case statement that matches the expression's value.</td>
    </tr>
    <tr>
        <td>ternary operator</td>
        <td>Provides a concise way to write if-else statements in a single line.</td>
    </tr>
    <tr>
        <td>Nested if else statement</td>
        <td>Allows for multiple conditions to be checked in a hierarchical manner.</td>
    </tr>
</table>
<b>Task 1- </b>Get user to input a number using prompt("Enter a number:"). Check if the number is a multiple of 5 or not.

---

## Day 3

<h2>Loops</h2>
Loops are used to execute a block of code repeatedly until a condition is met or all items in a sequence are processed.<br>

1. **For :** The for loop repeats a block of code a specific number of times. It contains initialization, condition, and increment/decrement in one line.
   _for (initialization; condition; increment/decrement) { // Code to execute}_ <img src="https://media.geeksforgeeks.org/wp-content/uploads/20250925165125538280/Forloop.webp" height= 150px alt="For loop synatx">
2. **while :** The while loop executes as long as the condition is true. It can be thought of as a repeating if statement.<br>
   _while (condition) { // Code to execute }_ <br> <img src="https://media.geeksforgeeks.org/wp-content/uploads/20250925165721953487/While-loop.webp" height= 150px alt="while loop">
3. **do-while :** The do-while loop is similar to while loop except it executes the code block at least once before checking the condition.<br>_do {// Code to execute} while (condition);_<br>
   <img src="https://media.geeksforgeeks.org/wp-content/uploads/20250925165838840320/Do-while-loop.webp" height=150px alt="do-while loop">

<h2>String</h2>
String is a sequence of characters used to represent text.

1. Create String: _let str = "sanga;_
2. String length: _str.length;_
3. String Indices: _str[0],str[1]....._
4. Template Literals: A way to have embedded expressions in strings. eg:-_this is atemplate literal_
5. String Iterpolation : To create strings by doing substitution of placehoders. eg:- _string text ${expression} string text_
6. Escape Characters: it used to change line. eg:- _\n_, _\t_
7. String Methods : These are built in functions to manipulate a string.**It can't change original string, it return copy of string**
   a. str.toUpperCase(): used to convert string text in capital letter.
   b. str.toLowerCase():
   c. str.trim(): Used to remove whitespaces from starting and from ending of string.
   d. str.slice(start,end): retirn part of string.
   e. str1.concat(str2): join str 2 with str1.
   f. str.replace(searchVal, newVal): replace old variable from new one.
   g. str.charAt(idx): to find out which character is at that index.
   <b>Task 2: </b>Prompt the user to enter thair full name , Generate ausername for them based on the input. Start username with @, followed by their full name and ending with the fullname length.

---
