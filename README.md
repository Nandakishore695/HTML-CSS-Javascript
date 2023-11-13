# HTML-CSS-Interview Question & Answer

**1.What is HTML?**
- HTML stands for Hypertext Markup Language and it also allows us to create website. It provides a way to structure content on the web by using tags such as headings, paragraphs, links, images, forms and many more.

**2.Difference between link tag <link> and anchor tag <a>?**
- Link tag :- It is used for linking the external resources file. This tag is placed within the head tag.
- Anchor tag :- It is used for linking to navigate one web page to another web page. This tag is placed within the body tag. and these links are clickable.

**3.What are the new input types in HTML5?**

New input types offered by HTML5 
- type=”week”
- type=”month”
- type=”time”
- type=”datetime”
- type=”datetime-local”
- type=”color”
- type=”search”
- type=”range”
- type=”url”

**4.What are the different types of lists in HTML?**

There are 3 types of list  
- Ordered list  :- Ordered list It's used when you want to display a list of items in a specific order, and each item is marked with a number.
- Unordered list :- On the other hand an unordered list displays a list of items without a specific order, and each item is marked with a bullet point.
- Definition list :- Definition lists are lists having each list item with a title as well as a description. There can also be multiple descriptions for each of the list items.

**5.What is a marquee in HTML?**
- A marquee tag is used to make text or images scroll automatically on a web page.However, it's no longer in modern (HTML5)

**6.What is the difference between HTML and CSS?**
- HTML is used to display the content on a web page, while CSS is used to control the presentation, layout, and design of a web page.

**7.How many ways to write css in HTML?**

There are three ways to add CSS to HTML documents 
- Inline 
- Internal 
- External

**8. What is doctype in HTML?**

Doctype  stands for Document Type.It is a way to give  “information” to the browser about  html version.
- Versions: - 5 <!DOCTYPE html />
- Versions: - 4 <!DOCTYPE HTML PUBLIC >


**9.What is dom in HTML?**
- DOM stands for Document Object Model. When a web page is getting loaded that time the browser creates a dom of the page and it is constructed as a tree of Objects. 


**10.What are the various formatting tags in HTML5?**
- sub <sub></sub>  
- sup <sup></sup> 
- del  <del></del> :in html 5 for underline
- strong :in html 5 for bold
- em :in html 5 for italic

**11.What are the root tags in html?**

There are some root tags. Without including these root tags in HTML we can’t create web pages.
- <html></html>
- <head></head>
- <body></body>

**12.What is the basic structure of an HTML document?**

<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
<body>
  <h1>Heading 1</h1>
  <p>Paragraph</p>
</body>
</html>


**13.What is the difference between an ID and a class in HTML?**
An ID is used to identify a unique element on a web page, while a class is used to identify a group of elements.
 14.What is the purpose of the href attribute in the <a> tag? ok
href attribute is used to specify the URL of the hyperlink.It tells the browser where to navigate when the link is clicked. 
URL (Uniform Resource  Locator) 


**14.What is the purpose of the src attribute in the <img> tag?**
src attribute specifies the source file of the image.



**15.What are some new tags introduced in HTML5?**
Some new tags in HTML5 include:
<header> - Defines a header section
<footer> - Defines a footer section
<nav> - Defines a navigation section
<article> - Defines an article
<section> - Defines a section of content
<main> - Specifies the main content section
<aside> - Defines content aside from the main content
<video> and <audio> - For embedding media content


**16.What are the attributes in html?**
style :- Specifies the inline CSS style for an element.
href :- Specifies the URL (web address) for a link.
src :- Specifies the URL (web address) for an image.
alt :- Specifies an alternative style for an image.
class :- 
Id:-
type:-
value:-
width
height:-


**17.What is a meta tag?**
A meta tag is an HTML element that provides metadata about a web page. The page  information is not displayed on the page. but is used by browsers and search engines to understand and categorize the content of the page such as page description, keywords, author, and viewport settings for responsive design.
19.What is the difference between inline and block-level elements? ok
Inline elements do not start with a new line and only take up as much width as necessary. 
Block-level elements always start with a new line and take up the full width.


**18.What is the use of an iframe tag?**
iframe stands for "inline frame tag." It's used to embed content from another source (like a different webpage) directly into the current webpage. To integrate external resources like web pages, videos, maps, and more into your own page.


**19.What is the difference between HTML and XHTML?**
HTML and XHTML Both essential languages for creating web pages.The main difference between them syntax and structure.
1.HTML is Hypertext Markup Language
1.XHTML is Extensible Hypertext Markup Language.

2.HTML is not a case-sensitive language.
2.XHTML is a case-sensitive language.

3. HTML is An application of SGML.
3. XHTML is An application of XML.

4. HTML Can function properly without a closing tag.. EX- <br> <p> <p>.
4. XHTML Can’t function properly without being closed. EX- <br/>. <p></p>.

5. HTML No hard rule on structures of the elements. EX- <p><b> The difference
5. XHTML Structure of the elements should be followed. EX- <p></p>

6. HTML Attributes have quotes as optional.
6. XHTML Attributes have quotes mandatory.


**20.Different between html4 and html5?**
**1.Doctype Declaration:**
HTML 4 we have to declare a little lengthy code of doctype. 
HTML 5 we have to  declare  in short code of doctype <!DOCTYPE html>

**2.Semantic Elements:**
HTML 4 we need to specify a name for the div element.
HTML 5 Introduces semantic elements like <section>, <article>, <nav>, <header>, <footer>, etc., which provides a more meaningful way to structure content.

**3.Multimedia Support:**
HTML 4 Relying on third-party plugins like Flash for multimedia content.
HTML 5 Introduces native support for multimedia with <audio> and <video> tags, reducing the need for third-party plugins.

**4.Input Types:**
HTML4: Limited input types available.
HTML5: Introduces new input types like date, time, month, etc.

**21.what is the difference between http and https?**
The main difference between these two terms http and https.
**HTTP** (Hypertext Transfer Protocol):
HTTP is a protocol used for transferring data over the internet.
It is not secure because the data transferred between the client's browser and the website is not encrypted
HTTP is fast compared to HTTPS
  
**HTTPS** (Hypertext Transfer Protocol Secure):
HTTPS is a secure version of HTTP.
It uses SSL (Secure Sockets Layer) protocols to encrypt the data transmitted between the client's browser and the website's server.
This encryption helps protect sensitive information like passwords, credit card numbers, and personal details from being intercepted.
HTTPS It helps to improve search rankings


**22.What are the Inline and Block-level tags?**
**Here are the inline tags**
<a>       	  Anchor
<strong> 	  Bold
<em>      	  Italic
<img>     	  Image
<button> 	  Button
<input>   	  Field
<br>       	  Break
<label>   	  Field Name
<span>   	  span
<sub>    	  Subscript
<sup>    	  Superscript
<textarea>        Description

**Here are the block-level tags**
<header>	  Header
<footer>	  Footer
<section>	  Section
<form>		  User form
<h1> to <h6>	  Heading
<hr>	   	  Horizontal 
<p> 		  Paragraph
<ol>		  Order list
<ul>		  Unorder list
<li>  		  List item
<dl>		  Definition list
<dt>		  Definition terms
<dd>		  Definition description 
<table>	          Grid
<div>		  Division

