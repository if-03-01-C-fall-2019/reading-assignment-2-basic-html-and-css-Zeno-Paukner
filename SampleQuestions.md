### IF.03.01 Basic Web Techniques
# Reading Assignment 1: WWW and html

## Html
1. Name the components of html elements properly
<!DOCTYPE html>
<html>
 <head>
 <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
 <title>My Personal Web Technique Site</title>
 </head>
 <body>
 <article>
 <h1>Hello World (Wide Web)</h1>
 <section>
 <h1>Mission</h1>
 <p>
 This course is for me ….
 </p>
 </section>

 <section>
 <h1>Personal Goals</h1>
 <p>
 I want to learn in this course ….
 </p>
 </section>
 </article>
 </body>
</html>

Every html page should
have a head and a body.
The head describes meta
information.
The body contains the
things which appear on
the page.


2. Identify void elements and how they are denoted
<br />
wtf is denoted-

3. Identify attributes
example: width, src, alt, lang, disabled, href, id, style, title
<p title="I'm a tooltip">
<html lang="en-US">
<img src="img_typo.jpg" alt="Girl with a jacket">

4. Write down the correct ``DOCTYPE`` declaration for html 5
<!DOCTYPE html>

4. Write down syntactically correct statements for the following elements
 
 <!DOCTYPE html>
<html>
	<head>
		<link rel="stylesheet" type="text/css" href="mystyle.css" />
		<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
		<title>My Personal Web Technique Site</title>
	</head>
	<body>
		<article>
			<h1>Hello World (Wide Web)</h1>
			<section>
				<h1>Mission</h1>
				<p>
				This course is for me ….
				<a href="https://www.w3schools.com">Visit W3Schools.com!</a>
				</p>
			</section>

			<section>
				<h1>Personal Goals</h1>
				<p>
				I want to learn in this course <br /
				How to not kms
				<img src="Team.jpg" alt="Team" style="width:700px;height:400px;">
				</p>
				<!-- This is a comment -->
			</section>
		</article>
	</body>
</html>


   - Article (``<article>``) 
   - Body (``<body>``)
   - line break (``<br/>``)
   - Headings (``<h1>``, ...)
   - Section with meta-information (``<head>``)
   - Top level element (``<html>``)
   - Image named ``Team.jpg`` (``<img src="Team.jpg">``)
   - Paragraph (``<p>``)
   - Section (``<section>``)
   - Label appearing in the title bar (``<title>``)
   - Link to other pages (``<a>``)
   - Comment
   - Head with title and meta elements

## Css
1. Name the components of a css rule properly

h1 { //h1 == Selector
color: blue; //Decleration; color == property, blue = value
text-align: center;
}

2. Use combinators properly: direct child, descendant, adjacent sibling, sibling

div > p {
  background-color: yellow;
}

div p {
  background-color: yellow;
}

div + p {
  background-color: yellow;
}

div ~ p {
  background-color: yellow;
}

3. Specify colors by color names and in hexadecimal notation

body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}

4. Declarations for color, background color

h1 {
  background-color: green;
}

h1 {
  color: green;
}

5. Pseudo classes for the ``<a>`` element

selector:pseudo-class {
  property:value;
}

/* unvisited link */
a:link {
  color: #FF0000;
}

/* visited link */
a:visited {
  color: #00FF00;
}

/* mouse over link */
a:hover {
  color: #FF00FF;
}

/* selected link */
a:active {
  color: #0000FF;
}

a.highlight:hover {
  color: #ff0000;
}

6. Declaration for background image

body {
  background-image: url("bgdesert.jpg");
}

7. Declaration for text alignment (left, right, center, justify)

h1 {
  text-align: center;
}

h2 {
  text-align: left;
}

h3 {
  text-align: right;
}

justify == alle gleich lang gestrecktWhen the text-align property is set to "justify",
each line is stretched so that every line has equal width, and the left and right 
margins are straight (like in magazines and newspapers):

8. Declaration for text decoration (overline, underline, line-through)

h1 {
  text-decoration: overline;
}

h2 {
  text-decoration: line-through;
}

h3 {
  text-decoration: underline;
}

9. Declaration for text transformation (uppercase, lowercase, capitalize)

p.uppercase {
  text-transform: uppercase;
}

p.lowercase {
  text-transform: lowercase;
}

p.capitalize {
  text-transform: capitalize;
}

9. Identify the difference between serif and sans-serif fonts

Serif fonts have small lines at the ends on some characters
"Sans" means without - these fonts do not have the lines at the ends of characters

10. Declarations for font families

p {
  font-family: "Times New Roman", Times, serif;
}

11. Declarations for font style normal and italic

Example
p.normal {
  font-style: normal;
}

p.italic {
  font-style: italic;
}

p.oblique {
  font-style: oblique;
}

12. Declarations for font sizes

h1 {
  font-size: 40px;
}

h2 {
  font-size: 30px;
}

p {
  font-size: 14px;
}



13. Declarations for font weights

p.normal {
  font-weight: normal;
}

p.thick {
  font-weight: bold;
}