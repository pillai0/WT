# WT

# Practical no:- 1

(a)Text Formatting:

<!DOCTYPE html>
<html>
<head>
<title>Text level formatting tags</title>
</head>
<body>
<H1>Text level formatting tags</H1>
<big>This text is big.</big><br/>
<small>This text is small.</small><br/>
<em>This text is emphasized.</em><br/>
<Strong>This text is important.</Strong><br/>
Chemical formula of water: H<sub>2</sub>O<br/>
Mathematical expression: a<sup>2</sup>+b<sup>2</sup><br/>
Hurry for a special discount! <del>25% off</del><br/>
Claim special discount: <ins>50%</ins> for 24 hours only!
</p>
</body>
</html>

(b)Document Structure Tags:

Input:
<!DOCTYPE html>
<html>
<head>
<title>Formatting tags</title>
</head>
<body>
<h1>Welcome to the webpage</h1>
<p>This paragraph 1 of the webpage.<b> This text is bold. </b><i>This text is italic.</i><u> This text is underlined.</u>
<br/>
This sentence uses break tag to be displayed on another line.<br/>
<b>Bold</b><br/>
<i>Italic</i><br/>
<u>Underline</u><br/>
</body>
</html>

(c)Image Tags

Input:
<!DOCTYPE HTML>
<html>
<head>
<title>HTML Tags</title>
</head>
<body>
<img>
<img src="C:\Users\Administrator\Downloads\ms1.jfif" height=350 width=350>
<img src="C:\Users\Administrator\Downloads\ms2.jfif" height=350 width=350>
</body>
</html>

(d) List Tags

i) List:

<!DOCTYPE html>
<html>
<head>
<title>List tags</title>
</head>
<body>
<h1>Unordered list example:</h1>
<ul>
<li>HTML</li>
<li>Javascipt</li>
<li>XML</li>
<li>Ajax</li>
</ul>
<h2>Ordered list example:</h2>
<ol>
<li>HTML</li>
<li>Javascript</li>
<li>XML</li>
<li>Ajax</li>
</ol>
</body>
</html>

ii) Nested List:

   <!DOCTYPE html>
<html>
<head>
<title>Nested lists</title>
</head>
<body>
<h4>Nested List Example:</h4>
<ul type="square">
<li>Hot Beverages</li>
<ol type="I">
<li>Cofee</li>
<li>Tea</li>
<li>Soup</li>
</ol>
<li>Cold Beverages</li>
<ol type="A">
<li>Fruit Juice</li>
<li>Raspberry Fizz</li>
<li>Lemon Water</li>
</ol>
</ul>
</body>
</html>

iii) Definition List:

<!DOCTYPE html>
<html>
<head>
<title>Definition list</title>
</head>
<body>
<dl>
<dt>HTML</dt>
<dd>Language of the web</dd>
<dt>AJAX</dt>
<dd>Client side scripting language</dd>
</dl>
</body>
</html>

# Practical no:-2

(A) Table Tags

 <!Doctype html>
<html>
<head>
<title>HTML Table Header</title>
</head>
<body>
<table border="1">
<tr>
<th>Students</th>
<th>Total</th>
</tr>
<tr>
<td>Boys</td>
<td>50</td>
</tr>
<tr>
<td>Girls</td>
<td>100</td>
</tr>
</table>
</body>
</html>

b. Form Tags

<html>
<head>
<title>Form Page: sampleform</title>
</head>
<body>
<h1>Sample form page</h1>
<form id='sampleform' method='post' action=''>
<p>
Name:<input type='text' name='Name'/>
</p>
<p>
Email:<input type='text' name='Email'/>
</p>
<p>
Gender:<input type="radio" name="r1"/> Male
<input type="radio" name="r1"/> Female
</p>
<p>
Hobbies:<input type="checkbox" name="Hobbes1" value="on">Dancing
<input type="checkbox" name="Hobbes1" value="on">Singing
</p>
<p>
<input type='submit' name='Submit' value='Submit'/>
</p>
</form>
</body>
</html>

c. navigation to multiple web pages 

<html>
<head>
<title>Form Page: sampleform</title>
</head>
<body>
<div align="center">
<a href="index.html">Index</a>
<a href="nature.html">Nature</a>
<a href="history.html">History</a>
<a href="art.html">Art</a>
</div>
</body>
</html>

# Practical no:-3

(A)  CSS Properties to change the background of Page
<!Doctype html>
<html>
<head>
<style>
h1{
background-color:cyan;
}
p{
background-color:red;
}
</style>
</head>
<body>
<h1>Deepak Kumar</h1>
<p>Deepakkumar Mehato</p>
</div>
</body>
</html>

(B)  CSS Properties to change Fonts and Text Styles

<!doctype html>
<html>
<head>
<style>
p.normal{
font-family:"Times New Roman",Times, serif;
font-style: normal;
}
p.italic{
font-family: Arial, Helvetica, sans-serif;
font-style: italic;
}
p.oblique{
font-style: oblique;
}
</style>
</head>
<body>
<p class="normal">Paragraph in normal form.</p>
<p class="italic">Deepak Kumar.</p>
</body>
</html>

(C)  CSS Properties  for positioning an element   

<doctype html>
<html>
<head>
<style>
div.static{
position: static;
border: 3px solid #73AD21;
}
p.relative{
position: relative;
left: 30px;
border: 3px solid #73AD21;
}
</style>
</head>
<body>
<h2>position: static;</h2>
<p class="relative">This Paragraph will be positioned relatively</p>
<div class="static">
This div element has position: static;
</div>
</body>
</html>

# Practical no:-3

Incorporate advanced HTML elements
• Embed media using <audio>, <video>, and <embed>
• Create a user registration form using input types (text, email, password,
etc.)
• Use Label, Output, and Progress elements
• Organize sections using <div>, <section>, and <nav>

codes:-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML Elements Example</title>
</head>
<body>

    <h1>Advanced HTML Features Demo (Basic Version)</h1>

    <nav>
        <p>Navigation:</p>
        <a href="#media-section">Media</a> |
        <a href="#form-section">Registration Form</a> |
        <a href="#data-section">Data Display</a>
    </nav>

    <div>
        
        <section id="media-section">
            <h2>🎬 Media Embedding: Audio, Video, and Embed</h2>
            
            <p>This section demonstrates embedding different types of media.</p>

            <h3>Video Example</h3>
            <video controls width="320" height="240">
                <source src="your-video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <br><br>

            <h3>Audio Example</h3>
            <audio controls>
                <source src="your-audio.mp3" type="audio/mp3">
                Your browser does not support the audio element.
            </audio>
            <br><br>

            <h3>Embed Example</h3>
            <embed src="document.pdf" type="application/pdf" width="500" height="300">
        </section>

        <hr>

        <section id="form-section">
            <h2>📝 User Registration Form</h2>

            <form action="/register" method="post">
                
                <p>
                    <label for="username">Username:</label>
                    <input type="text" id="username" name="username" required>
                </p>

                <p>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </p>

                <p>
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" minlength="8" required>
                </p>

                <p>
                    <input type="submit" value="Register User">
                </p>
            </form>
        </section>

        <hr>

 b. internal css property

codes:-
<html>
<head>

<!--#Internal or Embedded CSS-->
<style>
p.dotted {
border-style: dotted;
background-color:Tomato;
border: 2px solid red;
border-radius: 12px;
padding: 5px;
}

div.aaa {
  background-color: coral;
  width: 500px;
  height: 200px;
  border: 1px solid black;
  overflow: scroll;
}

img:hover {
  opacity: 0.5;
 position: absolute;
   z-index: -1;

}
</style>

<!--External Style Sheet-->
<link rel="stylesheet" href="style.css">
</head>
<body>

<!--#inline style sheet-->

<h1 style="background-color:rgb(238, 130, 238);border-style: double;">Hello World</h1>

<!--#Internal or Embedded CSS-->
<p class="dotted">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
</p>

<div id="greeks">
CSS (Cascading Style Sheets) is used to style and layout of web pages, and controlling the appearance of HTML elements. CSS targets HTML elements and applies style rules to dictate their appearance.
Below are the types of CSS:</br>
<ul>
<li>Inline CSS</li>
<li>Internal or Embedded CSS</li>
<li>External CSS</li>
</ul>
</div>

<div class="aaa">
1. Inline CSS</br>
Inline CSS involves applying styles directly to individual HTML elements using the style attribute. </br>

2. Internal or Embedded CSS</br>
Internal or Embedded CSS is defined within the HTML document’s style element. It applies styles to specified HTML elements. The CSS rule set should be within the HTML file in the head section i.e. the CSS is embedded within the style tag inside the head section of the HTML file.</br>

3. External CSS<br/>
External CSS contains separate CSS files that contain only style properties with the help of tag attributes (For example class, id, heading, … etc). CSS property is written in a separate file with a .css extension and should be linked to the HTML document using a link tag. <br/>
</div>

<h1>This is a Forest Image</h1>
<img src="C:\Users\Administrator\Documents\img_forest.jpg" alt="Forest" width="270" height="200">
<p style="font-style: oblique;font-size:15px;"> The z-index property specifies the stack order of an element (which element should be placed in front of, or behind, the others).Because the image has a z-index of -1, it will be placed behind the text.</p>
</body>
</html>

# Practical no:- 5

a. Create a basic webpage layout (header, nav, main, footer) 
codes:-
<!DOCTYPE html> 
<html lang="en"> 
<head> 
<meta charset="UTF-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Responsive Animated Webpage</title> 
<style> 
/* ---------- General Body Settings ---------- */ 
body { 
font-family: 'Arial', sans-serif; 
margin: 0; 
padding: 0; 
background: linear-gradient(120deg, #f0f0f0, #e0f7fa); 
transition: background 0.5s ease-in-out; 
} 
/* ---------- Header ---------- */ 
header { 
background-color: #008080; 
color: white; 
text-align: center; 
padding: 30px 20px; 
transition: all 0.3s ease-in-out; 
} 
header:hover {
background-color: #006666; } 
header h1 { 
margin: 0; 
font-size: 2.5em; 
} 
header p { 
margin-top: 10px; 
font-size: 1.2em; 
} 
/* ---------- Navigation ---------- */ nav { 
background-color: #004d4d; text-align: center; 
padding: 15px 0; 
} 
nav a { 
color: white; 
text-decoration: none; 
margin: 0 20px; 
font-size: 1.1em; 
padding: 8px 15px; 
border-radius: 5px; 
transition: 0.3s; 
} 
nav a:hover {
background-color: #008080; 
transform: scale(1.1); 
} 
/* ---------- Main Content ---------- */ main { 
padding: 30px 20px; 
display: flex; 
flex-wrap: wrap; 
justify-content: space-around; 
gap: 20px; 
} 
.card { 
background-color: white; 
border-radius: 10px; 
padding: 20px; 
flex: 1 1 250px; 
box-shadow: 0 4px 10px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s; } 
.card:hover { 
transform: translateY(-10px); 
box-shadow: 0 8px 20px rgba(0,0,0,0.2); } 
.card h3 { 
color: #008080; 
}
.card p { 
color: #333; 
line-height: 1.5; 
} 
/* ---------- Footer ---------- */ 
footer { 
background-color: #004d4d; 
color: white; 
text-align: center; 
padding: 10px 0; 
} 
/* ---------- Responsive Design ---------- */ @media (max-width: 768px) { 
nav a { 
display: block; 
margin: 10px 0; 
} 
main { 
flex-direction: column; 
align-items: center; 
} 
} 
@media (max-width: 480px) { 
header h1 {
font-size: 1.8em; 
} 
header p { 
font-size: 1em; 
} 
.card { 
flex: 1 1 90%; 
} 
} 
</style> 
</head> 
<body> 
<!-- Header --> 
<header> 
<h1>My Webpage</h1> 
<p>Responsive design with smooth animations</p> </header> 
<!-- Navigation --> 
<nav> 
<a href="#home">Home</a> 
<a href="#about">About</a> 
<a href="#services">Services</a> 
<a href="#contact">Contact</a> 
</nav> 
<!-- Main Content -->
<main> 
<div class="card" id="home"> 
<h3>Home</h3> 
<p>Welcome to our website! This page demonstrates responsive design with hover effects and smooth animations.</p> 
</div> 
<div class="card" id="about"> 
<h3>About Us</h3> 
<p>We create modern and responsive websites that look great on desktops, tablets, and mobiles.</p> 
</div> 
<div class="card" id="services"> 
<h3>Services</h3> 
<p>Our services include web design, development, and user experience improvements with CSS animations.</p> 
</div> 
<div class="card" id="contact"> 
<h3>Contact</h3> 
<p>Reach out to us via email or phone. We will respond promptly to help with your website needs.</p> 
</div> 
</main> 
<!-- Footer --> 
<footer> 
<p>&copy; 2025 My Cool Webpage. All rights reserved.</p> </footer> 
</body> 
</html>

b. Apply different styles for mobile, tablet, and desktop using media queries 

codes:-
<!DOCTYPE html> 
<html lang="en"> 
<head> 
<meta charset="UTF-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Responsive Webpage Layout</title> 
<style> 
/* General body settings */ 
body { 
font-family: Arial, sans-serif; 
margin: 0; 
padding: 0; 
background-color: #f4f4f4; 
} 
/* Header styles */ 
header { 
background-color: #333; 
color: white; 
padding: 20px; 
text-align: center; 
} 
/* Navigation bar styles */ 
nav { 
background-color: #444; 
text-align: center; 
padding: 10px 0;
} 
nav a { 
color: white; 
text-decoration: none; margin: 0 15px; 
font-size: 1.2em; 
} 
nav a:hover { 
text-decoration: underline; } 
/* Main content area */ main { 
padding: 20px; 
background-color: white; margin: 20px; 
} 
/* Footer styles */ 
footer { 
background-color: #333; color: white; 
text-align: center; 
padding: 10px; 
position: relative; 
bottom: 0; 
width: 100%; 
}
/* Mobile Styles (for screens up to 600px wide) */ @media (max-width: 600px) { 
header { 
font-size: 1.5em; 
padding: 15px; 
} 
nav { 
padding: 10px; 
} 
nav a { 
font-size: 1em; 
margin: 0 10px; 
} 
main { 
padding: 10px; 
margin: 10px; 
} 
footer { 
font-size: 0.9em; 
padding: 8px; 
} 
} 
/* Tablet Styles (for screens from 601px to 1024px wide) */ @media (min-width: 601px) and (max-width: 1024px) {
header { 
font-size: 2em; 
padding: 20px; 
} 
nav a { 
font-size: 1.1em; 
margin: 0 20px; 
} 
main { 
padding: 15px; 
margin: 15px; 
} 
footer { 
font-size: 1em; 
padding: 10px; 
} 
} 
/* Desktop Styles (for screens above 1024px wide) */ @media (min-width: 1025px) { 
header { 
font-size: 2.5em; 
padding: 25px; 
} 
nav { 
padding: 15px;
} 
nav a { 
font-size: 1.3em; 
margin: 0 25px; 
} 
main { 
padding: 20px; 
margin: 20px; 
} 
footer { 
font-size: 1.1em; 
padding: 15px; 
} 
} 
</style> 
</head> 
<body> 
<!-- Header --> 
<header> 
<h1>My Responsive Website</h1> <p>Welcome to my responsive webpage!</p> </header> 
<!-- Navigation --> 
<nav>
<a href="#home">Home</a> 
<a href="#about">About</a> 
<a href="#services">Services</a> 
<a href="#contact">Contact</a> 
</nav> 
<!-- Main Content --> 
<main> 
<h2>Welcome to My Website</h2> 
<p>This is a simple webpage layout that adjusts based on the screen size.</p> <p>Explore how the design changes on different devices.</p> </main> 
<!-- Footer --> 
<footer> 
<p>&copy; 2025 My Responsive Website. All rights reserved.</p> </footer> 
</body> 
</html> 

c. Design a webpage with some jQuery animation effects. 
Code: 
<!DOCTYPE html> 
<html lang="en"> 
<head> 
<meta charset="UTF-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>jQuery Animation Example</title> 
<!-- jQuery CDN -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script> 
</head> 
<body> 
<!-- Header --> 
<header> 
<h1>jQuery Animation Demo</h1> 
<p>Click the buttons below to see animation effects</p> </header> 
<!-- Navigation --> 
<nav> 
<a href="#home">Home</a> 
<a href="#effects">Effects</a> 
<a href="#contact">Contact</a> 
</nav> 
<!-- Main Content --> 
<main id="effects"> 
<div class="box" id="box">Click Me!</div> 
<button id="hideBtn">Hide</button> 
<button id="showBtn">Show</button> 
<button id="fadeBtn">Fade</button> 
<button id="slideBtn">Slide</button> 
<button id="animateBtn">Animate</button> 
</main> 
<!-- Footer -->
<footer> 
<p>&copy; 2025 jQuery Animation Demo. All rights reserved.</p> </footer> 
<!-- jQuery Script --> 
<script> 
$(document).ready(function() { 
// Hide the box 
$("#hideBtn").click(function() { 
$("#box").hide(500); 
}); 
// Show the box 
$("#showBtn").click(function() { 
$("#box").show(500); 
}); 
// Fade in/out 
$("#fadeBtn").click(function() { 
$("#box").fadeToggle(500); 
}); 
// Slide up/down 
$("#slideBtn").click(function() { 
$("#box").slideToggle(500); 
}); 
// Animate box size and color 
$("#animateBtn").click(function() { 
$("#box").animate({ 
width: "300px",
height: "150px", 
lineHeight: "150px" 
}, 500).animate({ 
width: "200px", 
height: "100px", 
lineHeight: "100px" 
}, 500); 
}); 
// Click the box to change background 
$("#box").click(function() { 
$(this).css("background-color", "#ff4500"); 
$(this).text("Clicked!"); 
}); 
}); 
</script> 
</body> 
</html> 

d. Write a jQuery Code to find the data passed with the on() method for each element. 
Code: 

<!DOCTYPE html> 
<html lang="en"> 
<head> 
<meta charset="UTF-8"> 
<title>jQuery on() with Data Example</title> 
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script> <style>
.item { 
width: 150px; 
padding: 10px; 
margin: 10px; 
background-color: #1e90ff; 
color: white; 
text-align: center; 
cursor: pointer; 
border-radius: 5px; 
} 
.item:hover { 
background-color: #104e8b; 
} 
</style> 
</head> 
<body> 
<h2>Click on each item to see its data</h2> 
<div class="item" id="item1">Item 1</div> 
<div class="item" id="item2">Item 2</div> 
<div class="item" id="item3">Item 3</div> 
<script> 
$(document).ready(function() { 
// Define data for each item 
$(".item").each(function(index) { 
// Pass data to the on() method 
$(this).on("click", {itemData: "This is " + $(this).text()}, function(event) {
// Retrieve data passed with on() 
alert("Data for " + $(this).text() + ": " + event.data.itemData); }); 
}); 
}); 
</script> 
</body> 
</html>

# Practical no:- 6

a. Perform mathematical operation for calculating factorial
Code:
<html>
<head>
<script>
function show(){
var i,no,fact;
fact=1;
no=Number(document.getElementById("num").value);
for(i=1;i<=no;i++)
{
fact=fact*i;
}
document.getElementById("answer").value=fact;
}
</script>
</head>
<body>
Enter Num:<input id="num">
<button onclick="show()">Factorial</button>
<input id="answer">
</body>
</html>

b. Calculating reverse of a number
Code:
<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reverse of a Number</title>
<script>
function reverseNumber() {
// Get the input number from the text box
var number = document.getElementById("numberInput").value;

// Ensure the input is a valid number
if (isNaN(number) || number === "") {
alert("Please enter a valid number.");
return;
}

// Reverse the number by converting it to a string, then reversing and joining
var reversed = number.toString().split('').reverse().join('');

// Display the reversed number
document.getElementById("result").innerText = "Reversed Number: " + reversed;
}
</script>
</head>
<body>

<h2>Reverse of a Number</h2>
<p>Enter a number to reverse it:</p>

<!-- Input for number -->
<input type="text" id="numberInput" placeholder="Enter a number">

<!-- Button to trigger reverse calculation -->
<button onclick="reverseNumber()">Reverse Number</button>

<!-- Area to display the result -->
<p id="result"></p>

</body>
</html>

c. Validating the various Form Elements
Code:
<!DOCTYPE html>
<html>
<head>
<title>Form Validation</title>

<script>
function validateform() {
var name = document.myform.name.value;
var password = document.myform.password.value;
var password2 = document.myform.password2.value;

if (name == "" || name == null) {
alert("Name can't be blank");
return false;
}

if (password.length < 6) {
alert("Password must be at least 6 characters long");

return false;
}

if (password != password2) {
alert("Passwords do not match");
return false;
}

alert("Form submitted successfully!");
return true;
}
</script>

</head>

<body>

<h2>Form Validation Example</h2>

<form name="myform" onsubmit="return validateform()">
Name: <input type="text" name="name"><br><br>
Password: <input type="password" name="password"><br><br>
Re-enter Password: <input type="password" name="password2"><br><br>
<input type="submit" value="Register">
</form>

</body>
</html>

d. Display all the prime numbers between 1 and 100
Code:

<!DOCTYPE html>
<html>
<head>
<title>Prime Numbers</title>
<script>
for (var i = 2; i <= 100; i++) {
var flag = 0;
for (var j = 2; j <= Math.sqrt(i); j++) { // Loop till the square root of i
if (i % j === 0) {
flag = 1;
break;
}
}
if (flag === 0) {
document.write(i + "<br>");
}
}
</script>
</head>
</html>

# Practical no:- 7

STEP 1: Create React Project
Open Command Prompt / Terminal and run:
      npx create-react-app react-practicals
      cd react-practicals

STEP 2: Install React Router (for Navigation)
            npm install react-router-dom

STEP 3: Folder Structure
Inside src, create this structure:
                src
                 ├── components
                 │    ├── Navbar.js
                 │    ├── UppercaseInput.js
                 │    ├── ButtonEvents.js
                 │    └── SumOfDigits.js
                 ├── App.js
                 └── index.js

STEP 4: Create Navigation Bar (Header)

import React from "react";
import { Link } from "react-router-dom";

function Navbar() {
  return (
    <div style={{ padding: "10px", backgroundColor: "#e0e0e0" }}>
      <Link to="/" style={{ marginRight: "20px" }}>
        Practical A
      </Link>

      <Link to="/button-events" style={{ marginRight: "20px" }}>
        Practical B
      </Link>

      <Link to="/sum-of-digits">
        Practical C
      </Link>
    </div>
  );
}

export default Navbar;

STEP 5: Practical A – Uppercase Input

import React, { useState } from "react";

function UppercaseInput() {
  const [text, setText] = useState("");
  const [bgColor, setBgColor] = useState("white");

  return (
    <div>
      <h2>Uppercase Input Example</h2>

      <input
        type="text"
        value={text}
        onFocus={() => setBgColor("lightyellow")}
        onChange={(e) => setText(e.target.value.toUpperCase())}
        style={{ backgroundColor: bgColor }}
        placeholder="Type here"
      />
    </div>
  );
}
export default UppercaseInput;

STEP 6: Practical B – Button Click & Double Click

import React, { useState } from "react";

function ButtonEvents() {
  const [message, setMessage] = useState("Click the button");

  return (
    <div>
      <h2>{message}</h2>

      <button
        onClick={() => setMessage("Button Clicked")}
        onDoubleClick={() => setMessage("Button Double Clicked")}
      >
        Click / Double Click
      </button>
    </div>
  );
}

export default ButtonEvents;

STEP 7: Practical C – Sum of Digits
import React, { useState } from "react";

function SumOfDigits() {
  const [number, setNumber] = useState("");
  const [sum, setSum] = useState(0);

  const calculateSum = () => {
    let total = 0;
    for (let digit of number) {
      total += parseInt(digit);
    }
    setSum(total);
  };

  return (
    <div>
      <h2>Sum of Digits</h2>

      <input
        type="number"
        value={number}
        onChange={(e) => setNumber(e.target.value)}
        placeholder="Enter number"
      />
      <br /><br />

      <button onClick={calculateSum}>Calculate</button>

      <h3>Sum of Digits: {sum}</h3>
    </div>
  );
}

export default SumOfDigits;

STEP 8: Configure Routing in App.js

import React from "react";
import { BrowserRouter, Routes, Route } from "react-router-dom";

import Navbar from "./components/Navbar";
import UppercaseInput from "./components/UppercaseInput";
import ButtonEvents from "./components/ButtonEvents";
import SumOfDigits from "./components/SumOfDigits";

function App() {
  return (
    <BrowserRouter>
      <Navbar />

      <Routes>
        <Route path="/" element={<UppercaseInput />} />
        <Route path="/button-events" element={<ButtonEvents />} />
        <Route path="/sum-of-digits" element={<SumOfDigits />} />
      </Routes>
    </BrowserRouter>
  );
}

export default App;

STEP 9: Run the Project
npm start

1️⃣ Open VS Code (keep your project open)

2️⃣ Open Command Palette
Press:
        Ctrl + Shift + P
⚠️ Do NOT type in terminal
A dropdown appears at the top of VS Code

3️⃣ Type this in the popup (not terminal):
Terminal: Select Default Profile

4️⃣ Click:
          Command Prompt

5️⃣ Close the current terminal
      Click the 🗑️ trash icon

# Practical no:- 8      

a. Convert JavaScript object to Json
Code:

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JavaScript Object to JSON</title>
</head>
<body>
<h1>Convert JavaScript Object to JSON</h1>

<button onclick="convertToJSON()">Convert Object to JSON</button>

<p id="jsonResult"></p>

<script>
// JavaScript object
let person = {
name: "John",
age: 30,
city: "New York"
};

// Function to convert JavaScript object to JSON and display it
function convertToJSON() {
// Convert the object to JSON
let jsonString = JSON.stringify(person);

// Display the JSON string on the page
document.getElementById("jsonResult").textContent = jsonString;
}
</script>
</body>
</html>

b. Convert Json to JavaScript object
Code:

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JSON to JavaScript Object</title>
</head>
<body>
<h1>Convert JSON to JavaScript Object</h1>

<button onclick="convertToObject()">Convert JSON to Object</button>

<p id="result"></p>

<script>
// JSON string
let jsonString = '{"name":"John","age":30,"city":"New York"}';

// Function to convert JSON to JavaScript object and display it
function convertToObject() {

// Convert JSON string to JavaScript object
let person = JSON.parse(jsonString);

// Display the object properties on the page
document.getElementById("result").textContent =
`Name: ${person.name}, Age: ${person.age}, City: ${person.city}`;
}
</script>
</body>
</html>

c. Load Json from external file
Code:

data.json
{
"name": "John",
"age": 30,
"city": "New York"
}

Index.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Load JSON from External File</title>
</head>
<body>

<h1>Load JSON from External File</h1>

<button onclick="loadJSON()">Load JSON Data</button>

<p id="result"></p>

<script>
function loadJSON() {
// Use fetch to load the JSON file
fetch('data.json')
.then(response => {
if (!response.ok) {
throw new Error('Network response was not ok');
}
return response.json(); // Parse the JSON response
})
.then(data => {
// Display the loaded JSON data
document.getElementById("result").textContent =
`Name: ${data.name}, Age: ${data.age}, City: ${data.city}`;
})
.catch(error => {
console.error('There was a problem with the fetch operation:', error);
});
}
</script>
</body>
</html>

# Practical no:-9
codes:-

index.html
<!DOCTYPE html>
<html>
<head>
    <title>Simple Form</title>
</head>
<body>

<h2>Student Information Form</h2>

<form action="process.php" method="POST">
    <label>Name:</label><br>
    <input type="text" name="name" required><br><br>

    <label>Email:</label><br>
    <input type="email" name="email" required><br><br>

    <label>Course:</label><br>
    <input type="text" name="course"><br><br>

    <input type="submit" value="Submit">
</form>

</body>
</html>

process.php
<?php
// Check if form is submitted
if ($_SERVER["REQUEST_METHOD"] == "POST") {

    $name = $_POST['name'];
    $email = $_POST['email'];
    $course = $_POST['course'];

    echo "<h2>Form Data Received</h2>";
    echo "Name: " . $name . "<br>";
    echo "Email: " . $email . "<br>";
    echo "Course: " . $course . "<br>";
}
?>

# Practical no:- 10

STEP 1: Create Database & Table
1. Open phpMyAdmin (MySQL GUI)
2. Open browser
3. Go to: http://localhost/phpmyadmin
4. This is where you manage databases visually

3️⃣ Create a Database
1. In phpMyAdmin:
2. Click Databases
3. Database name: college_db;
4. Click Create

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100),
    course VARCHAR(50)
);

STEP 2: Create Project Folder
Go to: C:\xampp\htdocs\
Create folder:student_project

STEP 3: Database Connection File

Create db.php

<?php
$conn = mysqli_connect("localhost", "root", "", "college_db");

if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}
?>


STEP 4: HTML Form (Take Data)

Create form.html
<!DOCTYPE html>
<html>
<head>
    <title>Student Form</title>
</head>
<body>
<h2>Student Registration</h2>

<form action="insert.php" method="POST">
    Name: <input type="text" name="name" required><br><br>
    Email: <input type="email" name="email" required><br><br>
    Course: <input type="text" name="course" required><br><br>
    <input type="submit" value="Submit">
</form>

</body>
</html>

STEP 5: Insert Data into Database

Create insert.php
<?php
include "db.php";

$name = $_POST['name'];
$email = $_POST['email'];
$course = $_POST['course'];

$sql = "INSERT INTO students (name, email, course) 
        VALUES ('$name', '$email', '$course')";

if (mysqli_query($conn, $sql)) {
    echo "Data inserted successfully <br>";
    echo "<a href='form.html'>Add More</a> | <a href='fetch.php'>View Data</a>";
} else {
    echo "Error: " . mysqli_error($conn);
}
?>

STEP 6: Retrieve Data from Database

Create fetch.php
<?php
include "db.php";

$result = mysqli_query($conn, "SELECT * FROM students");

echo "<h2>Student Records</h2>";
echo "<table border='1'>
<tr>
<th>ID</th>
<th>Name</th>
<th>Email</th>
<th>Course</th>
</tr>";

while ($row = mysqli_fetch_assoc($result)) {
    echo "<tr>";
    echo "<td>".$row['id']."</td>";
    echo "<td>".$row['name']."</td>";
    echo "<td>".$row['email']."</td>";
    echo "<td>".$row['course']."</td>";
    echo "</tr>";
}

echo "</table>";
?>


STEP 7: Run the Project
1️⃣     Open Form:- http://localhost/student_project/form.html
2️⃣    Submit Data:- It will go to database.
3️⃣    View Data:- http://localhost/student_project/fetch.php

✅ Folder Structure (Important for Exam)
htdocs
 └── student_project
      ├── db.php
      ├── form.html
      ├── insert.php
      └── fetch.php
