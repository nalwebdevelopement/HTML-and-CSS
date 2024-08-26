User the fa- fa- font to style my website

https://github.com/jordanhudgens/digital-literacy-html-css/tree/master/images/backgrounds
used flex box container to make the element to align.
Used grid for the left and right column to align the phone and hours 
(display:gird;
grid-template-column: 1fr; // 1 fr will make the div into column.
grid-gap: 10px;)
used the parent child relationship
(.icon i, .left-column > .contact-hour-wrapper)

custome fonts
go to google - fonts.google.column
check for the avaiable font , shows the versions, combination
copy the standard code and copy it into the index.html

added the image with img src tag

Refactorign the css code
enhace the css code with the parent and chilld element

Implement the CSS Animation Pseduo element for the link wrapper, with 
i changed the letter spacing when the mouse hover

Used seperate folder for style which has common and nav

Building a prallox feature in html  and css 
When we scroll the website, the image will show in the background

background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

 Added the background image for feature-sections with repeat which makes
 the picture repeat.used the pesudo element to show the hover effect with 
 border transparent and also with blue line.  

 Adding the nth child property for each column.
 use case:
 I am having a main div and 3 div inside which has 3 elements
 i need to select all the first element in the all the div the i need to use the index like 1 st , 2nd, 3rd
 this is useful because we dont need to indivually specify with each div
 .features-section >.column-wrapper >.column :nth-child(2):hover
{
    letter-spacing: 1px;;
}
In this example i and selecting all my 2nd element of the div irrecpective of div name or element name

 Adding the box shadow 
  Inset box shadow, uses this property in css try to 
  change the values and see the result
box-shadow: inset 0px -26px 79px -8px rgba(0,0,0,0.58);
box-shadow: inset 0px -26px 0px -8px rgba(0,0,0,0.58);

box-shadow: inset 0px -26px 79px 100px rgba(0,0,0,0.58);
css box shadow generator - google and see can use it in your code

Embedd google map

Open the google maps --> search for the location --> and click on the share 
click on option --> embeed map  --> copy the content and paste it in the html code

Learning summary

 The CSS grid tool is quite similar to the Flexbox but with much more utility 
Fonts are absolutely critical to giving a really nice look and fill to your application 
Images can be used in HTML and inserted into the body of the code 
We can perform refactoring of C SS code for more specific selectors 
Refactoring of a code is all about optimizing the performance of the particular code 
CSS Grid and Flexbox can be combined together to get any type of behaviour on a website 
Animations can be implemented on HTML and CSS 
You can refactor nav ba styles and organize style files in HTML and CSS 
You can build a parallax image feature completely from the scratch into a website 
Text overlays can be added  on Parallex image 
You can add HTML structure and content to different types of elements on the homepage  

