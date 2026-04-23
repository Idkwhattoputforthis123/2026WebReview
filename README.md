HTML Review 

What does HTML stand for 
Hyper Text Markup Language

What is the diffrence between <head> and <body> ?
<head> --> MetaData - read

<body> -->  This is the content displayed in the browser

Name THREE semantic HTML elements.
<header> </header>
<main> </main>
<footer> </footer>
<nav> </nav>
<article> </article> Any content that stands on its own and be able to understand it
<aside> </aside>
<section> </section>

what attribute does an <a> tag need to create a link 
    href --> <a href="linkoldhoe">

    what is a self closing HTML tag? give an example
<br>
tags that do not have closing tags are called void elements
<img>
<link>
<meta>


What does <DOCTYPE html> do?
sets up document language as a whole that tells the browser that its an HTML file.

Every HTML file has the same Skelleton structure


<DOCTYPE html>
<html lang"en">
<head> 
    <title></title>
    <link>
    <style></style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width", inital-scale="1.0">
    makes the page Responsive
</head>

<body>
<header>
    <nav> Content any Navigation </nav>
</header>
<h1> Largest heading/most important heading. ONLY ONCE per page </h1>

</body>
</html>

PART 2 Core HTMl elements 
<h1> - <h6> each gets smaller as they go

There should only be 1 h tag per page
h2 can be though of as section or sub titles
h3 can be subsections
h5 and h6 can be thought of as fine print

Text Elements
<p> --> paragraph tag
<strong> --> bold/important text 
<em> itialics or emphizied - samantic weight
<br> line break (void element)
<u> underline
<hr> horizontal row ------------------ visual line divider viod element 
<span> inline element, does not create a line break
<mark> highlights text

HTML Lists
nested list
bulleted lists unordered list
num lists      ordred list

li is listed item

<ul>
    <li>Item 1</li>
</ul>

used for items with no ranked order is unordered
used for ranking items is used with ordered list


links and images 

how do i create a link to sll boces.org?? 
step one 
<a href="https://sllboces.org" target="_blank"> SLL BOCES </a>

how do i create a link thats in the same directory that our html file is in
<a href="about.html">lala</a>

what if its in a content folder??
<a href="content/about.html">lala</a>

a link to another section of the page
<a href="#about">lala</a>

<a href="mailto:student@sllboces.org">lala</a>


images 

What are the two reqjuired attributes for the <img> tags?
alt --> accessibility text 
src --> file path to the image 

<img src="images/hero.jpg" alt="ufhurfbeuhfuyrbgurebg">

<img src="images/hero.png" alt="ufhurfbeuhfuyrbgurebg">

What is hot-linking an image?? 
<img src="images/hero.jpg" alt="ufhurfbeuhfuyrbgurebg">


part 3 
what is a samantic HTML Element?
it describes the meaning of the content inside of the element not just the way it looks.
reasons why we use sementic elements
organization
effects the document object model
accsessibility allows screen readers 

layout semantic elements heade, nav, main, section, aside, footer

content semantic elements
figure, figcaption,image with a caption and fig caption is the caption for a figure image 
time a date or time 
address contact address info
mark highlighed text
