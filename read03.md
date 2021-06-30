The Definitive Guide: How To Create Your First Wireframe
What is a wireframe, and why do UX designers use them? (Links to an external site.)
Wireframing is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product. This process focuses on how the designer or client wants the user to process information on a site, based on the user research already performed by the UX design team.

Examples of wireframes (Links to an external site.)
Some people like to draw their wireframes by hand, others feel more comfortable using software like Invision, or Balsamiq to create theirs.

That said, for complete beginners, bear in mind the following when deciding on your wireframe creation process:

Wireframes drawn with paper and a pencil, or at a whiteboard, have the advantage of looking and being very easy to change.
With the help of paper-prototypes, you can test with end users at every stage of ideation and design. Changes at these stages are much easier—and therefore cheaper—than changes deemed necessary after coding is under way.
Switching later to software (after initially hand-drawing your wireframe) allows you to keep track of more detailed decisions.
wireframe

The best tools for wireframing (Links to an external site.)
The examples below all have free trials, so check them out!

UXPin: UXPin has a wide range of functionalities, but one of the best ones is how it facilitates building responsive clickable prototypes directly in your browser.
InVision: InVision allows you to get feedback straight from your team and users through clickable mock-ups of your site design. It’s completely free too!
Wireframe.cc: Wireframe.cc provides you with the technology to create wireframes really quickly within your browser, the online version of pen and paper.
# HTML basics ## So what is HTML? HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on.

for example if we want to print “my cat is very grumpy “, we must use the following opening tag and closing tag in the figure below. img

## Anatomy of an HTML document That wraps up the basics of individual HTML elements, but they aren’t handy on their own. Now we’ll look at how individual elements are combined to form an entire HTML page. lets see the structure of html code in the following figure: html ## images to drag an image in html you must use the following code :

<img src="images/firefox-icon.png" alt="My test image">

Lists (Links to an external site.)
A lot of the web’s content is lists and HTML has special elements for these. Marking up lists always consists of at least 2 elements. The most common list types are ordered and unordered lists:

Unordered lists are for lists where the order of the items doesn’t matter, such as a shopping list. These are wrapped in a <ul> element.
Ordered lists are for lists where the order of the items does matter, such as a recipe. These are wrapped in an <ol> element.
Semantics
In programming, Semantics refers to the meaning of a piece of code — for example “what effect does running that line of JavaScript have?”, or “what purpose or role does that HTML element have” (rather than “what does it look like?”.)

## Semantics in JavaScript In JavaScript, consider a function that takes a string parameter, and returns an <li> element with that string as its textContent. Would you need to look at the code to understand what the function did if it was called build(‘Peach’), or createLiWithContent(‘Peach’)?

## Semantics in CSS In CSS, consider styling a list with li elements representing different types of fruits. Would you know what part of the DOM is being selected with div > ul > li, or .fruits__item?

## Semantics in HTML In HTML, for example, the <h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of “a top level heading on your page.”