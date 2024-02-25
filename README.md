# HTML Interview Questions and Answers

**1.What is HTML?**
- `HTML` stands for Hypertext Markup Language it use to create website. It provides a way to structure content on the web by using tags such as headings, paragraphs, links, images, forms and many more.

**2.What is a meta tag?**
- A meta tag provides metadata about a web page. The page  information is not displayed on the web page. but is used by browsers and search engines to understand and categorize the content of the page such as page description, keywords, author, and viewport settings for responsive design.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> //Special characters to use like ASCII (American Standard Code for Information Interchange) The ASCII code for uppercase 'A' is 65.The ASCII code for lowercase 'a' is 97.The ASCII code for the digit '0' is 48.
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="This is food description">
    <meta name="keyword" content="food, food service, food industry">
    <meta name="robots" content="index, follow">
    <meta name="author" content="Nandakishore">
    <link rel="stylesheet" href="assets/style.css">
    <title>Food4You</title>
</head>
<body>
</body>
</html>
```

**3.Difference between link and anchor tag?**
- `Link tag`  It is used for linking the external resources file.
- `Anchor tag` It is used for linking to navigate one web page to another web page and these links are clickable.

**4.What are the new input types in HTML5?**

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

**5.What are the different types of lists in HTML?**

There are 3 types of list:  
- `Ordered list`  Ordered list It's used when you want to display a list of items and each item is marked with a number.
- `Unordered list` On the other hand an unordered list to displays a list of items and each item is marked with a bullet point.
- `Definition list` are lists having each list item with a title as well as a description.
```
<ol type="I">
        <li>Apple</li>
        <li>Banana</li>
        <li>Carrot</li>
</ol>
<ul type="circle">
        <li>Apple</li>
        <li>Banana</li>
        <li>Carrot</li>
</ul>
```

**6.What is a marquee in HTML?**
- A marquee tag is used to make text or images scroll automatically on a web page.However, it's no longer in modern (HTML5)

**7.What is the difference between HTML and CSS?**
- HTML is used to display the content on a web page, while CSS is used to control the presentation, layout, and design of a web page.

**8.How many ways to write css in HTML?**

There are three ways to write CSS in HTML documents: 
- Inline 
- Internal 
- External

**9.What is doctype in HTML?**

Doctype  stands for Document Type.It is a way to give  “information” to the browser about  html version.
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd" > //Versions: - 4 
<!DOCTYPE html /> //Versions: - 5
```

**10.What is dom in HTML?**
- DOM stands for Document Object Model. When a web page is getting loaded that time the browser creates a dom of the page and it is constructed as a tree of objects. 


**11.What are the various formatting tags in HTML5?**
```
<sup></sup> //Superscript 
<sub></sub> //Subscript
<del></del> //strike line
<strong></strong> //Bold
<em></em> //Italic or emphasized
```

**12.What are the root tags in html?**

There are some root tags. Without including these root tags in HTML we can’t create web pages.
- html <html></html>
- head <head></head>
- body <body></body>

**13.What is the difference between an ID and a class in HTML?**
- An ID is used to identify a unique element on a web page, while a class is used to identify a group of elements.

**14.What is the purpose of the href attribute in the <a> tag?**
- href attribute is used to specify the URL of the hyperlink.It tells the browser where to navigate when the link is clicked.URL(Uniform Resource Locator) 

**15.What is the purpose of the src attribute in the <img> tag?**
- src attribute specifies the source file path.

**16.What are some new tags introduced in HTML5?**

Some new tags in HTML5 include:
- header
- footer
- section
- nav
- article
- main
- aside
- video
- audio

**17.What are the attributes in html?**
- style 
- href 
- src 
- alt 
- class 
- Id
- type
- value
- width
- height

**18.What is the difference between inline, block-level and inline-block elements?**
- Inline elements doesn’t start with a new line and only take up as much width as necessary. 
- Block-level elements always start with a new line and take up the full width.
- inline-block It’s formatted just like the inline element, where it doesn’t start on a new line. but, you can set width and height values.

**19.What is the use of an iframe tag?**
- iframe stands for "inline frame tag." It's used to embed content from another source directly into the current webpage. To integrate external resources like web pages, videos, maps, and more into your own page.
```
    <iframe src="https://www.bing.com/" frameborder="0" width="800"></iframe>
```

**20.What is the difference between HTML and XHTML?**

HTML and XHTML Both essential languages for creating web pages.The main difference between them syntax and structure.
| HTML  | XHTML |
| ------------- | ------------- |
| HTML is Hypertext Markup Language  | XHTML is Extensible Hypertext Markup Language |
| It is not a case-sensitive language  | It is a case-sensitive language |
| It is An application of SGML  | It is An application of XML |
| It Can function properly without a closing tag | It Can’t function properly without being closed |
| It No hard rule on structures of the elements | It Structure of the elements should be followed |
| It Attributes have quotes as optional |  It Attributes have quotes mandatory |

**21.Different between html4 and html5?**

**1.Doctype Declaration:**
- HTML 4 we have to declare a little lengthy code of doctype. 
- HTML 5 we have to  declare  in short code of doctype <!DOCTYPE html>

**2.Semantic Elements:**
- HTML 4 we need to specify a name for the div element.
- HTML 5 Introduces semantic elements like section, article, nav, header, footer, etc., which provides a more meaningful way to structure content.

**3.Multimedia Support:**
- HTML 4 Relying on third-party plugins like Flash for multimedia content.
- HTML 5 Introduces native support for multimedia with audio and video tags, reducing the need for third-party plugins.

**4.Input Types:**
- HTML4: Limited input types available like text, password, email, number, checkbox, radio, submit, reset, hidden.
- HTML5: Introduces new input types like week, month, time, datetime, datetime-local, color etc.

**22.what is the difference between http and https?**

The main difference between these two terms http and https.

**HTTP** (Hypertext Transfer Protocol):
- HTTP is a protocol used for transferring data over the internet.
- It is not secure because the data transferred between the client and website is not encrypted
- HTTP is fast compared to HTTPS
  
**HTTPS** (Hypertext Transfer Protocol Secure):
- HTTPS is a secure version of HTTP.
- It uses SSL (Secure Sockets Layer) protocols to encrypt the data transmitted between the client and website.
- This encryption helps protect sensitive information like passwords, credit card numbers, and personal details from being intercepted.
- HTTPS It helps to improve search rankings

**23.What are the Inline and Block-level tags?**

| Inline tags  | Block-level tags |
| ------------- | ------------- |
| a  | header |
| strong  | footer |
| em  | section |
| img  | form |
| button  | h1 to h6 |
| input  | hr |
| br  | p |
| label  | ol |
| span  | ul |
| sub  | li |
| sup  | dl |
| textarea  | dt |
| script | dd |
| small  | table |
|   | div | 
|   | nav |
|   | aside |
|   | video |
  
**24.What is the basic structure of an HTML document?**

![image](https://github.com/Nandakishore695/HTML-CSS-Demo-Templete-For-Beginners/assets/104244494/e496b060-fcdb-4467-b549-ee74b1d6bbca)

**25.What is the use of the target attribute in the <link> tag?**
- _blank: It opens the link in a new window.
- _self: It opens in the same window.

**26.What are HTML Entities?**

HTML Entities are special characters used to represent characters that cannot be typed on a keyboard
- &lt; for <(less than)
- &gt; for <(greater than)
- &copy; for <(copyright right)
- &reg; for (Register)
- &trade; for (Trade Mark)
- ![image](https://github.com/Nandakishore695/HTML-CSS-Demo-Templete-For-Beginners/assets/104244494/42cfd9b2-2da2-4caf-a441-a7ae0a9963b2)


**27.What is a manifest file in HTML5?**
- A Manifest file is a simple text file that tells the browser what to cache and what not to cache. In offline and online mode.
  
**There are three sections of a Manifest file:**
- **CACHE** - Files listed here are cached after they are downloaded for the first time.
- **NETWORK** - Files listed here require a connection to the server, and are never cached.
- **FALLBACK** - Files listed here specify fallback pages if a page is inaccessible.

**28.Explain the concept of web storage in HTML5?**

- web applications can store data locally within the client browser. 
- Before HTML5 version, application data had to be stored in cookies.
- Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

**There 2 object :-**
- **LocalStorage-** for multiple sessions with no expired date.
- **sessionStorage-** for single session(data is lost when browser is tab closed).
  
**Example:-**
- windows.localstorage.setItem(key,value);
- value=windows.localstorage.getItem(key);
- windows.localstorage.removeItem(key)
- windows.sessionstorage.setItem(key,value);
- value=windows.sessionstorage.getItem(key);
- windows.sessionstorage.removeItem(key

**29.What is cookies and how it works?**

- A cookie is a small piece of data that a website stores on a user's browser to remember information about the user, such as personalization and tracking user behaviour. Generally, email and password are will not store directly in cookies, instead of that server will create a session ID for session management.

**30.Explain Different between image and figure tag?**

Both tags are used to display image on a webpage, but they have different purposes.

-	An image tag is use to display on a webpage. It is a self-closing tag. Requires the "src" attribute to specify image source. Optional attributes like "alt," "width," and "height" can be included.
-	The figure tag is used to group together an image or a video along with a caption. It Requires a closing tag. It is used to semantically organize the content.

**31.How to add favicon in website?**

-  To add a favicon to a website in between head tag use the link tag inside of link tag we have some attribute **rel** for icon **type** is format **href** for source for image.
```
<link rel="icon" type="image/x-icon" href="/images/favicon.ico">
```
**32.Different between div and span?**

- A div element is used for block-level organize and styling of page, where as a span element is used for inline organize and styling.

**33.How many types of links in html?**

It has 5 types of links:
```
<a href="https://www.example.com">Visit Example Website</a> // External link

<a href="https://www.example.com">
  <img src="image.jpg" alt="Example Image"> //Image link
</a>

<a href="mailto:info@example.com">Send Email</a> //Email link

<a href="#section2">Bookmark Section 2</a> //Bookmark link
<div id="section2">This is Section 2</div>

<a href="tel:+1234567890">Call Us</a> //Phone link
```
**34.What is Bookmark link?**
- A bookmark link is used to navigate to a specific section on the same website.
```
  <body>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      
      <section id="home">
        <h2>Section Home</h2>
        <p>This is home page</p>
      </section>
                                 
       <a href="#home">Home</a>
      <section id="about">
        <h2>Section Home</h2>
        <p>This is home page</p>
      </section>
  <body/>
```
**35.What is the purpose of base tag?**
- The base tag is used for common base url for all relative urls within a document and this tag is placed in head tag.
```
 <!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <link rel="stylesheet" href="styles.css" />
    <base href="https://www.abc.com/" />
  </head>
  <body>
      <a href="page1.html">Home</a>
      <a href="page2.html">About</a>
  </body>
</html>
```
**36.What are table, tr, th, td elemetns and advantesges & desiadvantages?**
- Table is the container for the entire table.
- Tr (table row) is used to define a row in the table.
- Th (table header) is used to represent the column headers names.
- Td (table data) is used to represents the regular cells in a table.
- Table structure is not good for mobile device(not responsive).
```
<table border="1" cellpadding="10" cellspacing="0" width='100%'>
                <thead>
                    <tr>
                        <th colspan="2">S.No</th>
                        <th>Name</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td rowspan="2">1</td>
                        <td>Nandakishore</td>
                        <td>nandakishore695@gmail.com</td>
                        <td>7893797371</td>
                    </tr>
                    <tr>

                        <td>Akshay</td>
                        <td>akshay@gmail.com</td>
                        <td>7893797371</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td colspan="3">Total</td>
                        <td>20</td>
                    </tr>
                </tfoot>
            </table>
```

**37.What is the colspan and rowspan attribute in html?**
- The colspan attribute is used to merge multiple cells in horizontally into a single cell.
- The rowspan attribute is used to merge multiple cells in vertically into a single cell.
- Colspan and rospan attribute is applicable to th and td tag only.
  ![image](https://github.com/Nandakishore695/HTML-CSS-Demo-Templete-For-Beginners/assets/104244494/33bb8a79-9c9b-4095-ba9a-0c1c58d371e6)

# CSS Interview Question and Answer
1.**What is css?**
- CSS stands for Cascading Style Sheets. It is a style sheet language which is used with HTML to design websites.

What are the different version of CSS?
- CSS1
- CSS2
- CSS2.1
- CSS3
- CSS4

**2.List the CSS Frameworks?**
- Bootstrap
- Semantic UI
- Tailwind CSS

**3.What are CSS Selectors?**
```
p {  color:"pink" } //Element
.my-class {  color:"red" } //Class
#my-id { color:"blue" } //ID
ul > li { width:30px } //Child
a:hover { color:"orange" } //Pseudo-Class
```
**4.What are CSS backgroundsl ist properties?**
- background-color
- background-repeat
- background-image
