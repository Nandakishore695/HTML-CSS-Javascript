# HTML Interview Questions and Answers

**1. What is HTML?**
- `HTML` stands for Hypertext Markup Language it use to create website. It provides a way to structure content on the web by using tags such as headings, paragraphs, links, images, forms and many more.

**2. What is a meta tag?**
- A `meta tag` provides metadata about a web page. The page  information is not displayed on the web page. but is used by browsers and search engines to understand and categorize the content of the page such as page description, keywords, author, and viewport settings for responsive design.
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

**3. Difference between link and anchor tag?**
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

**5. What are the different types of lists in HTML?**

There are 3 types of lists:  
- `Ordered list`  It's used when you want to display a list of items and each item is marked with a number.
- `Unordered list` On the other hand an unordered list displays a list of items and each item is marked with a bullet point.
- `Definition list` each list item with a title and a description.
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

**6. What is a marquee in HTML?**
- A `marquee tag` is used to make text or images scroll automatically on a web page. However, it's no longer in modern (HTML5)

**7. What is the difference between HTML and CSS?**
- HTML is used to display the content on a web page, while CSS is used to control the presentation, layout, and design of a web page.

**8. How many ways to write css in HTML?**

There are three ways to write CSS in HTML documents: 
- Inline 
- Internal 
- External

**9. What is doctype in HTML?**

`Doctype`  stands for Document Type.It is a way to give  “information” to the browser about  html version.
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd" > //Versions: - 4 
<!DOCTYPE html /> //Versions: - 5
```

**10. What is dom in HTML?**
- DOM stands for Document Object Model. When a web page is getting loaded that time the browser creates a dom of the page and it is constructed as a tree of objects. 


**11.What are the various formatting tags in HTML5?**
```
<sup></sup> //Superscript 
<sub></sub> //Subscript
<del></del> //strikethrough
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

**17.Why we use semantic tags?**
- For deveveloper easier to read and understand as well as It help the search engines.

**18.What are the attributes in html?**

Attributes are special words used inside the opening tag to control the element's behaviour
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

**19.What is the difference between inline, block-level and inline-block elements?**
- Inline elements doesn’t start with a new line and only take up as much width as necessary. 
- Block-level elements always start with a new line and take up full width.
- inline-block It’s formatted just like the inline element, where it doesn’t start on a new line. but, you can set width and height values.

**20.What is the use of an iframe tag?**
- iframe stands for "inline frame tag." It's used to embed content from another source directly into the current webpage. To integrate external resources like web pages, videos, maps, and more into your own page.
```
    <iframe src="https://www.bing.com/" frameborder="0" width="800"></iframe>
```

**21.What is the difference between HTML and XHTML?**

HTML and XHTML Both essential languages for creating web pages.The main difference between them syntax and structure.
| HTML  | XHTML |
| ------------- | ------------- |
| HTML is Hypertext Markup Language  | XHTML is Extensible Hypertext Markup Language |
| It is not a case-sensitive language  | It is a case-sensitive language |
| It is An application of SGML  | It is An application of XML |
| It Can function properly without a closing tag | It Can’t function properly without being closed |
| It No hard rule on structures of the elements | It Structure of the elements should be followed |
| It Attributes have quotes as optional |  It Attributes have quotes mandatory |

**22.Different between html4 and html5?**

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

**23.what is the difference between http and https?**

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

**24.What are the Inline and Block-level tags?**

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
  
**25.What is the basic structure of an HTML document?**

![image](https://github.com/Nandakishore695/HTML-CSS-Demo-Templete-For-Beginners/assets/104244494/e496b060-fcdb-4467-b549-ee74b1d6bbca)

**26.What is the use of the target attribute in the <link> tag?**
- _blank: It opens the link in a new window.
- _self: It opens in the same window.

**27.What are HTML Entities?**

HTML Entities are special characters used to represent characters that cannot be typed on a keyboard
- &lt; for <(less than)
- &gt; for <(greater than)
- &copy; for <(copyright right)
- &reg; for (Register)
- &trade; for (Trade Mark)
- ![image](https://github.com/Nandakishore695/HTML-CSS-Demo-Templete-For-Beginners/assets/104244494/42cfd9b2-2da2-4caf-a441-a7ae0a9963b2)


**28.What is a manifest file in HTML5?**
- A Manifest file is a simple text file that tells the browser what to cache and what not to cache. In offline and online mode.
  
**There are three sections of a Manifest file:**
- **CACHE** - Files listed here are cached after they are downloaded for the first time.
- **NETWORK** - Files listed here require a connection to the server, and are never cached.
- **FALLBACK** - Files listed here specify fallback pages if a page is inaccessible.

**29.Explain the concept of web storage in HTML5?**

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

**30.What is cookies and how it works?**

- A cookie is a small piece of data created by a web server  on browser to remember information about the user and tracking user behaviour. Generally, email and password are will not store directly in cookies, instead of that server will create a session ID for session management.

**31.Explain Different between image and figure tag?**

Both tags are used to display image on a webpage, but they have different purposes.

-	An image tag is use to display on a webpage. It is a self-closing tag. Requires the "src" attribute to specify image source. Optional attributes like "alt," "width," and "height" can be included.
-	The figure tag is used to group together an image or a video along with a caption. It Requires a closing tag. It is used to semantically organize the content.

**32.How to add favicon in website?**

-  To add a favicon to a website in between head tag use the link tag inside of link tag we have some attribute **rel** for icon **type** is format **href** for source for image.
```
<link rel="icon" type="image/x-icon" href="/images/favicon.ico">
```
**33.Different between div and span?**

- A div element is used for block-level organize and styling of page, where as a span element is used for inline organize and styling.

**34.How many types of links in html?**

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
**35.What is Bookmark link?**
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
**36.What is the purpose of base tag?**
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
**37.What are table, tr, th, td elemetns and advantesges & desiadvantages?**
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

**38.What is the colspan and rowspan attribute in html?**
- The colspan attribute is used to merge multiple cells in horizontally into a single cell.
- The rowspan attribute is used to merge multiple cells in vertically into a single cell.
- Colspan and rospan attribute is applicable to th and td tag only.
  ![image](https://github.com/Nandakishore695/HTML-CSS-Demo-Templete-For-Beginners/assets/104244494/33bb8a79-9c9b-4095-ba9a-0c1c58d371e6)

# CSS Interview Question and Answer

**History of css**
- Cascading Style Sheets. 1996- The first version of CSS was invented.

1.**What is css?**
- CSS stands for Cascading Style Sheets. It is a style sheet language which is used with HTML to design websites.

**2.List the CSS Frameworks?**
- Bootstrap
- Semantic UI
- Tailwind CSS

**3.What are CSS Selectors?**
```
* { background:'pink' } //Universal Selector
p {  color:"pink" } // Type selector
.my-class {  color:"red" } //Class selector
#my-id { color:"blue" } //ID selector
ul > li { width:30px } //Child selector
input[type='text']{} //Attribute selector
a:hover { color:"orange" } //Pseudo-Class selector
```
**4.What are CSS backgrounds list properties?**
- background-color: 'pink'
- background-repeat: 'no-repeat'
- background-image: url("./image.png")
- background-size: 'cover'
- background-position: center; 

**5.What is different between margin and padding?**
- Both are used to define space around outside the border of an element margin and inside the border of an element padding.

**6.What are text properties in css?**
- color: '#333'
- text-transform: 'uppercase'
- text-decoration: 'underline'
- text-align: 'center'
- font-size: '16px'
- font-weight: 'bold'
- font-style: 'italic'
- line-height: '1.5'

**7.What are position properties in CSS?**
- Static
- Fixed
- Absolute
- Relative
- sticky

**8.What is default position property in css?**
- Static position is the default value
  
**9.What are pseudo classes in css?**
- hover
- active
- focus
- checked
  
**9.What is Box model CSS?**

**2.specificity" in CSS?**

What are breakpoints in responsive design?




**4.What different between postion absoult and position relative?**

# Basic Javascript Questions and Answers

**History of Javascript**

- JavaScript was invented by Brendan Eich in 1995. It was originally named Mocha but quickly became known as LiveScript and, later, JavaScript. It interpreted language with single-threaded

**1. What is JavaScript?**  
- JavaScript is a client-side scripting language used to create dynamic features for web applications, making them more user-friendly and engaging. (e.g., clickable buttons, popup menus, etc.)

**2.What is vanilla javascript?**
- Vanilla JavaScript means pure JavaScript code written without external libraries or frameworks.
  
**3. How to write JavaScript code in HTML?**

There are three ways to write javascript code: 

1. Inline code
2. Internal code
3. External file

**4. What does "use strict" mean?**
- Strict mode is introduced in (ES5). Using strict mode is a way to tell the javascript engine to enforce stricter rules during code execution
```
Example: -
x = 9; // Throws ReferenceError: x is not defined
```
   
**5. What are Data Types?**

There are two types of data types in JavaScript:-

| Primitive  | Non-primitive |
| ------------- | ------------- |
| String  | Object |
| Number  | Array |
| Boolean  | RegExp |
| Undefined | Function |
| null |  |
| Symbol | | |
| BigInt | | |

- String:- Represents a series of characters. A string can be represented in either single (' ') or double (" ") quotes,  

**6.Difference between “ == “ and “ === “ operators?**

**Both are comparison operators.**

- `Loose equality` operators is used to compare two values and returns true. If they are equal
- `Strict equality` operators is used to compare two values and same datatypes.

**7.What is the difference between var and let and const?**

- **Var** is as a global-scope. so, we can access  from everywhere (inside and outside functions). and with **var** can be redeclared and reassigned value.
- **Let** is as a block-scope. so **let** can be reassigned the value, but they cannot be redeclared. 
- **Const** is a block-scope, cannot be reassigned or redeclared after initialization.

**8.what is synchronous and asynchronous?**
- Synchronous is single-thread, which means one program will run at a time.
- Asynchronous is multi-thread, which means programs can run in parallel.

**9.What are the string method in javascript and Explain?**

JavaScript provides a variety of string methods that allow you to manipulate and work with strings.

| String Method| String Method |
| ------------- |-|
| length  | repeat() |
| concat()  | replaceAll() |
| toUpperCase() | replace()|
| toLowerCase() | substr()  |
| indexOf() | substring() |
| trim() | split() |
| trimStart() | slice() |
| trimEnd() | charAt() |

  let str = "Hello, World!";
  
  console.log(str.length);  // Outputs 13
  
  console.log(str.concat("2"));  // Outputs 'Hello World2'
  
  console.log(str.toUpperCase());  // Outputs 'HELLO WORLD'
  
  console.log(str.toLowerCase());  // Outputs 'hello world'

  console.log(str.indexOf("World"));  // Outputs 7
  
  console.log(str.trim());  // Outputs 'Hello, World!'
  
  console.log(str.charAt(1));  // Outputs 'e'

  console.log(str.replace("World", "Universe"));  // Outputs 'Hello, Universe!'

  console.log(str.slice(0, 5));  // Outputs 'Hello'

  console.log(str.split(","));  // Outputs ['apple', 'banana', 'orange']

**10.What are the different events in JavaScript?**

There are many different events in JavaScript are:
| Mouse events | Keyboard events | Form events | Window events|
| ------------- | ------------- | ------------- |  ------------- |
| click  | keydown | change | load |
| dbclick  | keyup | focus | unload |
| mouseover  |  | submit | resize|
| mouseout |  | onblur ||


**11.What is Babel, and why is it used in JavaScript development?**

- Babel is a JavaScript compiler. It is used to convert code from a non-JavaScript language into JavaScript like React code.

**12.What is scope in javascript?**

JavaScript has two different types of scope. 

- **Global-scope:** Variables declared outside of any function become global variables. It can be accessed and modified from any function.
- **Block-scope:** Variables declared inside a function. It cannot be accessed or modified outside of the function.

**13.What is the “spread” operator?**
- The spread operator is introuduce in ES6. It is denoted by three dots (...). It is used to concatenate two arrays.
```
const array1 = [1, 2, 3];
const array2 = [...array1, 4, 5, 6];
console.log(array2) //Output: [1, 2, 3, 4, 5, 6]
```

**14.What is the difference between "null" and "undefined" in JavaScript?**
- null and undefined are both special values.
- Null value that represents no value or no object. It is an intentional absence of value. On the other hand,
- Undefined it means that a variable has been declared but has not been assigned a value, it implicitly returns undefined.

**15.Give a the different between comparison between ES5 and ES6?**

| ECMAScript5  | ECMAScript6 |
| ------------- | ------------- |
| ES5 was introduced in 2009  | ES6 was introduced in 2015  |
| ES5 supported by Primitive data types are string, number, Boolean, null, & undefined | ES6 introduced a new primitive data type 'symbol' |
| In ES5 the var keyword is used to declare variables, and it has function-level scope | In ES6, introduced let and const are new ways to define variables. Let has block-level scope, while const is used to declare constants  |
| In ES5, both function and return keywords are used to define a function | An arrow function is a new feature introduced in ES6 by which we don't require the function keyword to define the function  |
| In ES5, there is a use of for loop to iterate over elements | ES6 introduced the concept of for...of loop to perform an iteration over the values of the iterable objects  |

**16.What is function in JavaScript?**
- Basically, a function is a set of statements that performs a specific task and returns a value. Functions can take parameters, which act as inputs. They are defined using the function keyword, followed by a name and a block of statements enclosed in curly braces. Once defined, a function can be invoked by using its name.

**17.What is Callback function?**
- A callback is a function that is passed as an argument to another function, and it's executed after the completion of the main function..
```
function show(sum) {
  alert('i am show function'+sum);
}
function display(num1, num2, myshow) {
  let sum = num1 + num2;
  myshow(sum);
}
display(2, 3, show);
```

**18.What is hoisting?**
- Before the interpreter executes the code in JavaScript is a default behaviour where the function, variable, or class declarations are moved to the top of the scope.
```
console.log(x); // Outputs: undefined
var x = 5;
console.log(x); // Outputs: 5
```
**19.What is closure?**
- A closure is an inner function that can access the outer function variable as well as global variables.
```
const outerFunction = (a) => {
   let b = 10;
   const innerFunction = () => {
      let add = a + b;
      console.log(add);
   }
   return innerFunction;
};
let result = outerFunction (20);
result();
```
**20.Difference in settimeout() and setinterval()?**
- setTimeout() method is used to call a function after a certain period of time.
- setInterval() method is used to call a function repeatedly at a specified interval of time.
- clearInterval() method is used to stop the execution of a function
```
const TimeoutFun = setTimeout(show, 5000);
function show() {
   alert('ok');
}
const element = document.getElementById("demo");
setInterval(function() {element.innerHTML += "Hello"}, 1000);
```
**21.How to convert string to integer in javascript Tutorials?**
- We can convert string to integer number by using "parseInt()" method. 

**22.Why to use "innerHTML" in javascript?**
- For replacing the content in the html elements.

**23.What is the use of push, pop method in javascript?**
- push method is used for adding new items into an array in the last.
- pop method is used for removing items from an array in the last. 

```
var products = ["TV", "Mobile", "Apparel", "Laptops"];
products.push("MyProduct");
console.log(products); // Expected output: Array ["TV", "Mobile", "Apparel", "Laptops", "MyProduct"]
```
```
var products = ["TV", "Mobile", "Apparel", "Laptops"];
products.pop();
console.log(products); // Expected output: Array ["TV", "Mobile", "Apparel"]
```
**24.What is the use of unshift, shift method in javascript?**
- unshift method will inserted item into an array from the beginning.
- shift method will removed item from the beginning.
```
var products = [1, 2, 3];
products.unshift(4, 5);
console.log(products); // Expected output: Array [4, 5, 1, 2, 3]
```
```
var products = [1, 2, 3];
products.shift();
console.log(products); // Expected output: Array [2, 3]
```

**25.What Variable in javascript?**
- Variable is a container for storing data values. It is declared using the var, let, or const keyword. Variables can hold different types of values, such as numbers, strings, or objects

**26.What is isNaN in JavaScript?**
- isNaN() is a function is used to check whether the given value is an illegal number or not. If it returns true, the value is a Not a number. Else returns false. It value is a number.

**27.What is the difference between slice and splice?**

slice() and splice() methods are used widely for array manipulations. 

**Slice() Method:**
- Slice method is used to create a new array from the original array. It takes two arguments the starting index, indicat where to begin the slice, and the ending index is not included in the slice array.

**Splice() Method:**
- Splice method is used to add or remove items from the original array. It takes n number of arguments the starting index, indicat where the modification should begin, and the number of elements to be removed. Additionally, you can include optional arguments to specify new elements to be add.

**28.What is this keyword in JavaScript?**
- This keyword refers to the current windows object. 

**29.What are some of the built-in methods in JavaScript?**

JavaScript provides a variety of built-in methods are:
| String Methods | Array Methods | Number Methods | Math Methods| Date Methods| Function Methods|
| ------------- | ------------- | ------------- |  ------------- |------------- |------------- |
| charAt()  | push() | toFixed() | Math.random() |getDate()|bind()|
| concat()  | pop()   |parseInt()|Math.floor()| getMonth()|apply()|
|toLowerCase()|unshift()| parseFloat()|Math.round()|getFullYear()|call()|
|toUpperCase()|shift()||Math.ceil()|getHours()|
|length()   |slice()|||getMinutes()|
||splice()   |||getSeconds()|

**30.Difference between Client-side JavaScript and Server-side JavaScript?**

**Client-side:**
- Code is executed on the user's web browser like HTML, CSS, and JavaScript.
- Primarily responsible for the user interface and user experience
- It handles form validating, animations
- Code is visible and accessible to users
- Use local storage and cookies

**Server-side:**
- Code is executed on the server such as PHP, Python, Ruby, Java, and Node.js
- Interacts with databases, it is responsible for processing requests, managing user authentication,
- Code is not visible to users

**31.Difference between map and foreach?**

Both are array methods that are used to iterate the elements of the array.
- map() method will return a new array
- forEach() method will not return anything and returns undefined.

**32.What is loop and how many types of loops What is the difference between for... of and for... in javascript?**

Loops are used to repeatedly execute a block of code until a condition true.

**It has 5 types of loops are:**
- for loop
- while loop
- do while loop
- for in loop
- for of loop

**For in loop** is use when you want to go through the properties of an object.
```
var animal = {name: "tiger", leg: 4};
for(let key in animal){
   console.log(key) // Expected output: name, leg
   console.log(key, animal[key]) // Expected output: name tiger, leg 4
}
```
**For of loop** is use when you want to go through each item in a collection.
```
var person = ["Nandakishore", Naveen, Bajrang];
for(let index of person){
   console.log(index) // Expected output: 0, 1, 2
   console.log(index, person[index]) // Expected output: 0 Nandakishore, 1 Naveen, 2 Bajrang
}
```
**33.What is callback hell?**
- Callback hell mean inside a function multiple nested callback

**34.What are Promises?**
- A promise is an object that may produce a single value in the future, either resolved with a value or rejected with a reason (error). Promises are in three states:

**Pending**

**Fulfilled**

**Rejected**
```
var result = new Promise(function(resolve,reject){
	var bool = true;
	If(bool){
	   resolve(“it is true”);
	}
	else{ 
	   reject(“it’s false”);
}
)
console.log(result);
result.then(function(value){ console.log(value);})
      .catch(function(value){ console.log(value);})
```
**35.What are the possible ways to create objects?**
- Object is a collection of elements, in the form of properties and methods
  
**i.Object literal syntax:**
```
var object = {
     name: "Sudheer",
     age: 34
};
```
**ii.Using new keyword with object constructor**
```
var object = new Object();
```
**iii..Using new keyword with a constructor function**
```
function Person(name, age) {
  this.name = name;
  this.age = age;
}

var person1 = new Person("John", 30);
```
**iv.Objec.create() Method**
```
const myPrototype = { x: 10, y: 20 };
const myObject = Object.create(myPrototype); 
```
**v.Classes**

**36.Different between Transpiler and Compiler?**
- A transpiler is a tool that converts source code from one high-level programming language(jsx) to angother high-level programming language(Javaascript)
- A compiler is a tool that converts high-level programming language(java) into a lower-level language(machine code or bytecode)

**37.What is Parameter, Argument and Rest Parameter?**
- A parameter is a variable listed in the function declaration
- An argument is the actual value that is passed into the function when it is invoked
- It is represented by three dots (...) followed by a parameter name. 
```
function add(a, b) {
  // 'a' and 'b' are parameters
  return a + b;
}
let result = add(3, 5); // '3' and '5' are argument

function sum(...numbers) {
  // 'numbers' is a rest parameter
  return numbers.reduce((total, num) => total + num, 0);
}

let result = sum(1, 2, 3, 4, 5);
```
**38.What is template literal in ES6 Version?**
- ES6 introduce later versions of JavaScript, called backticks (``) template literal.
- New way to define strings. Template literals have some advantages over traditional string literals enclosed in single or double quotes.
```
//Traditional way
let name = "John";
let greeting = "Hello, " + name + "!";
let multiLineString = "name: \n Hello\n name "; //for line breaks:'\n'
let stringWithQuotes = "This is a string with single 'quotes' and double \"quotes\".";


//New way
let name = "John";
let greeting = `Hello, ${name}!`;
let multiLineString = `Line 1
Line 2
Line 3`;
let stringWithQuotes = `This is a string with single 'quotes' and double "quotes".`;
```
**39.Different between `IF/ELSE` vs `Switch`?**
- Both If-else and Switch both are use excuite the conditional the main difference between is if-else statement is executed based on the multiple condition like using logical operator. On the other and switch statements execute as per the user decision.
  
**40. What is the use of strict mode?**
- Strict mode is a feature that was introduced in ECMAScript 5 to help developers write and maintainable code by catching common mistakes and preventing the certain error
```
<script>
"use strict";
function myFunction(a,a) { //show error duplicate defined a parameter
     add = a + 10; // add is not defined at myFunction
     console.log(add)
}
myFunction(5,5)
<script>
```
**41. What is the difference between `Arrow function` and `Normal function`?**
- Arrow functions do not have their own this context.
- regular functions have their own this context, 

**42. Explain about loops different between?**

**43. What is bug explain?**
- Bugs are completely normal in software development
- Problem in a computer program. Any unexpected or unintended behavior of a computer program is a software bug.
- A real bug that causes an error in Harvard's computer in the 1940s

**44. What are debugging tools?**
- Debugging tools are essential for web developers to identify and fix issues in their code.
- Console, Debugging, Postman, Redux DevTool

**45. What is the difference between if-else and ternary?**

**46. How do we handle errors in javascript?**

**47. What is event bubbling and capturing?**

**48. Why do we use the word “debugger” in JavaScript?**
- The word “debugger” is used in JavaScript to refer to a tool that can step through JavaScript code line by line. This can help debug JavaScript code, which is the process of finding and fixing errors in JavaScript code. 

**49. Type Coercion in javascript?**
- Implicit type coercion in javascript is the automatic conversion of value from one data type to another. It takes place when the operands of an expression are of different data types.

**45. What is currying in JavaScript?**

**51.Explain call(), apply() and, bind() methods?**

**52. What do you mean by BOM?**

**53. What are classes in javascript?**

**54. Explain Async/Await?**

**55. What is the difference between Single-thread and multi-thread?**

**56. What is the difference between synchronous and asynchronous?**  

