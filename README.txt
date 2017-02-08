HTML README
By: Bianca Capretta
Date: 2/7/17
Assignment 1: Your Portfolio

1. Identify what aspects of the work have been correctly implemeneted and what 
have not

- index.html has been implemented the way I want as my home page.
- bio.html has been implemented with a description of myself in separate sections.
However, the picture of me isn't being implemented exactly as I'd like right
now. I want it to be smaller and on the right.
- resume.html includes information about myself, my education, job experience,
skills, and activities.

- I have also implemented a few other pages:
	- projects.html: describes my projects in more detail
	- music.html: elaborates on my experience and love for music
	- other.html: includes other things I've spent my time doing 
		(film and non-profit work)

- I am currently having trouble making http://www.cs.tufts.edu/~bcapre01/
direct to my github page

2. Identify anyone with whom you have collaborated or discussed the assignment.
- Max Bernstein helped me test my website locally. By typing
	python -m SimpleHTTPServer I was able to start a small little server and
	test my changes immediately.

3. Say approximately how many hours you have spent completing the assignment.
- Since I created some extra pages, I've probably spent ~30 hours on this
project.

--------------------------------------------------------------------------------

The rest of the README includes helpful links and HTML bits for myself:

I am learning HTML and remote Github commands as I make my website, so this README
is a place to make note of anything new. 
# bkcapretta.github.io

HTML README

I am learning HTML and remote Github commands as I make my website, so this README 
is a place to make note of anything and everything new.

Github
Helping information on how to push and commit
http://stackoverflow.com/questions/17291995/push-existing-project-into-github

Link from Max:
http://rogerdudler.github.io/git-guide/

HTML
To embed images:
<img src=”website”/>

To embed links:
<a href=”website”>Whatever I wanna say about it!</a>

--------------------------------------------------------------------------------

Intro to HTML: Hypertext Markup Language

To make text headings:
<h1>Heading</h1>

- h1 is the largest and h6 is the smallest

To make paragraphs:
<p>Description of company here.</p>

To embed images:
<img src="website"/>

To embed links:
<a href="website">Whatever I wanna say about it!</a>

- href is the attribute name
- the website is the attribute value
- the following words is the link text

To embed videos:
<video width="320" height="240" controls>
  <source src="video-url.mp4" type="video/mp4">
</video>

- width and height: Set the size of the screen that displays the video
- controls: Adds play, pause and volume control
- source src: Sets the URL of the video to play
- type: Specifies different video formats

To embed PDFs:
<embed src="filename.pdf" width="800px" height="2100px"/>

To add (unordered) lists:
<ul>
  <li>A list item</li>
  <li>A second list item</li>
  <li>A third list item</li>
</ul>

- ul tags create the unordered list (the parent)
- li tags contain each list item (the children)

Div elements:
<div class="main">
 ...
</div>

- Div elements divide your page by enclosing other elements. These enclosed 
groups of elements can then be organized, moved and styled independently from
one another

<!DOCTYPE html>: Tells the web browser to expect an HTML document

<html>...</html>: The root of the HTML document and parent of all other HTML 
elements on the webpage

<head>...</head>: Enclose other metadata about the site, such as its title

<title>...</title>: Contains the site's title, which is one way users can 
find your site through a search engine, like Google

<meta charset="utf-8"/>: Tells the web browser which character set to use.
In this case, the character set is "utf-8"

Helpful in creating a "bookmark" so a link will take you exactly a place in a page
http://www.w3schools.com/html/html_links.asp

To insert space between blocks of words: &nbsp

--------------------------------------------------------------------------

Intro to CSS

The HTML link element links a CSS file to an HTML file so that CSS styling
can be applied. Here's an example of the link element:
<link rel="stylesheet" type="text/css" href="main.css"/>

-rel: Specifies the relationship between the current file and the file being
linked to: in this case, the rel attribute is "stylesheet"
-type: Specifies the type of file linked to
-href: Provides the URL of the file being linked to

The diagram to the right shows the anatomy of a CSS rule:
- rule: a list of CSS instructions for how to style a specific HTML element or 
group of HTML elements
- selector: specifies exactly which HTML elements to style (h1 is the selector)
- properties and values: located inside the { } brackets, properties and values 
specify what aspect of the selector to style (color is the property, red is the
value)

h1 {
  color: red;
}

Colors can be represented as a Hexadecimal color (#RRGGBB) or RGB (Red, Green, Blue)
colors

If you want to have two different fonts on the same line (helpful link):
http://www.dynamicdrive.com/forums/showthread.php?47401-2-different-fonts-on-same-line
