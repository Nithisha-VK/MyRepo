# 👋 Hello developer!

This project contains a basic HTML structure to get you started. 


## 🏗 What's next?

Build your project however you like using HTML, CSS and JavaScript. 

Use these four files as your starting point:


- **index.html:** This is the default page for your space, where you write HTML, the standard markup language for creating web pages.
- **styles.css:** Use the CSS file to style your content and change the look of your space with beautiful colors, fonts and much more. 
- **scripts.js:** Use this file to make your website dynamic and interactive with JavaScript. 

> **Note:** The **styles.css** and **scripts.js** files link into the **index.html** file so that they are all connected.


<h1>Hello, World!</h1>


Welcome to _Learn HTML_, the easiest way to learn HTML interactively.

<h2>What is HTML?</h2>




* HTML stands for Hyper Text Markup Language
* HTML is the standard markup language for creating Web pages
* HTML describes the structure of a Web page
* HTML consists of a series of elements
* HTML elements tell the browser how to display the content
* HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

<h2>A Simple HTML Document</h2>



```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```


<h3>Example Explained</h3>




* The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
* The `<html>` element is the root element of an HTML page
* The `<head>` element contains meta information about the HTML page
* The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
* The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
* The `<h1>` element defines a large heading
* The `<p>` element defines a paragraph

<h2>What is an HTML Element?</h2>


An HTML element is defined by a start tag, some content, and an end tag:

`<tagname>Content goes here...</tagname>`

The HTML element is everything from the start tag to the end tag:

`<h1>My First Heading</h1>`

`<p>My first paragraph.</p>`

<h2>Web Browsers</h2>


The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:

<h2>HTML Page Structure</h2>


Below is a visualization of an HTML page structure:

<html>


    <head>


    <title>Page title</title>


    </head>


    <body>


        <h1>This is a heading</h1>


        <p>This is a paragraph.</p>


        <p>This is another paragraph.</p>


    </body>

</html>

Note: The content inside the <body> section (the white area above) will be displayed in a browser. The content inside the <title> element will be shown in the browser's title bar or in the page's tab.

<h2>Let’s Start</h2>


<h2>Step 1: Open Visual Studio Code(PC)</h2>


<h2>Step 2: Write Some HTML</h2>


Write or copy the following HTML code into


```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
```


<h2>Step 3: Save the HTML Page</h2>


Tip: You can use either .htm or .html as file extension. There is no difference, it is up to you.

<h2>Step 4: View the HTML Page in Your Browser</h2>


Open the saved HTML file in your favorite browser (double click on the file, or right-click - and choose "Open with").

<h2>HTML Documents</h2>


All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with `<html>` and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`.

<h2>The <!DOCTYPE> Declaration</h2>


The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The `<!DOCTYPE>` declaration is not case sensitive.

<h2>HTML Headings</h2>


HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading

<h2>HTML Paragraphs</h2>


HTML paragraphs are defined with the `<p>` tag

<h2>HTML Links</h2>


HTML links are defined with the `<a>` tag:


```
<a href="https://www.w3schools.com">This is a link</a>
```


The link's destination is specified in the `href` attribute. 

Attributes are used to provide additional information about HTML elements.

<h2>HTML Images</h2>


HTML images are defined with the `<img>` tag.

The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:

<h2>How to View HTML Source?</h2>


Have you ever seen a Web page and wondered "Hey! How did they do that?"

<h3>View HTML Source Code:</h3>


Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

<h3>Inspect an HTML Element:</h3>


Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

<h2>HTML Elements</h2>


The HTML element is everything from the start tag to the end tag:

<tagname>Content goes here...</tagname>

Note: Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

<h2>Nested HTML Elements</h2>


HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

The following example contains four HTML elements (`<html>`, `<body>`, `<h1>` and `<p>`)

<h2>HTML is Not Case Sensitive</h2>


HTML tags are not case sensitive: `<P>` means the same as `<p>`.

The HTML standard does not require lowercase tags

<h1>HTML Attributes</h1>




* All HTML elements can have attributes
* Attributes provide additional information about elements
* Attributes are always specified in the start tag
* Attributes usually come in name/value pairs like: name="value"
* The `href` attribute of `<a>` specifies the URL of the page the link goes to
* The `src` attribute of `<img>` specifies the path to the image to be displayed
* The `width` and `height` attributes of `<img>` provide size information for images
* The `alt` attribute of `<img>` provides an alternate text for an image
* The `style` attribute is used to add styles to an element, such as color, font, size, and more
* The `lang` attribute of the `<html>` tag declares the language of the Web page
* The `title` attribute defines some extra information about an element

<h2>Exercise</h2>




1. Add an HTML `<title>` tag with the text "Hello, World!"
2. Add a paragraph (`<p>` tag) to the body with the text "Hello, World!"
3. Add an HTML `<h1>` tag with the text "I'm the most important!"
4. Add an HTML `<h2>` tag with the text "I'm less important!"
5. Add an HTML `<h6>` tag with the text "I'm the least important!"
<h1>
    Links</h1>



---


A link ("anchor") is a small span of text that will direct you to a different section in the page, or to a different page. To create a link, you will need to specify where you would like the user to be directed to when the link is clicked by specifying the `href` attribute.

For example:


```
    <a href="https://www.google.com">A link to Google</a>
```


To create a link to a different section in the same page, you will need to use a hash sign along with the element ID to where you would like the browser to jump to. For example:


```
    <a href="#faq">Click here to read the Frequently Asked Questions</a>
```


The element ID is denoted using the `id` attribute:


```
    <h3 id="faq">Frequently asked questions</h3>
    <p>The first rule about fight club is that you do not talk about fight club.</p>
```


Let's try it out:


```
    <!DOCTYPE html>
    <html>
        <head>
        </head>
        <body>
            <h1>My First Page</h1>
            <p>This is my first page.</p>
            <a href="#faq">Click here to read the Frequently Asked Questions</a>
            <hr/>
            <h3 id="faq">Frequently asked questions</h3>
            <p>The first rule about fight club is that you do not talk about fight club.</p>
            <p>However, if you do have questions, please e-mail me at foo@bar.com</p>

        </body>
    </html>
```


<h2>
    Exercise</h2>




1. Mark the word `Go to google.` to a `link` to `https://www.google.com` .
2. Mark the word `Go to blue!` to an `anchor` and link it to element `<div id="blue">` , and so does `Back to green!` .
<h1>
    Lists</h1>



---


HTML provides a way to create both an ordered list (with elements counting up, 1, 2, 3...) and an unordered list with bullets instead of numbers. Lists are a good way to formalize a list of items and let the HTML styling do the work for you.

<h3>
    Ordered lists</h3>


Here is an example of how to create an ordered list:


```
    <p>Here is a list of ordered items:</p>
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
```


Ordered lists have a "type" attribute which defines the numbering convention to use.

To count using numbers, use type="1":


```
    <p>Here is a list of ordered items:</p>
    <ol type="1">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
```


To count using uppercase letters, use type="A":


```
    <p>Here is a list of ordered items:</p>
    <ol type="A">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
```


To count using lowercase letters, use type="a":


```
    <p>Here is a list of ordered items:</p>
    <ol type="a">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
```


To count using uppercase roman numerals, use type="I":


```
    <p>Here is a list of ordered items:</p>
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
```


To count using lowercase roman numerals, use type="i":


```
    <p>Here is a list of ordered items:</p>
    <ol type="i">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
```


<h3>
    Unordered lists</h3>


Here is an example of how to create an unordered list:

Here is a list of unordered items:



* First item
* Second item
* Third item

To change the list style attributes, we can use the CSS attribute called `list-style-type`. The available types are:



* disc
* circle
* square
* none

Here is an example of the disc list style type:


```
    <p>Here is a list of unordered items:</p>    
    <ul style="list-style-type: disc">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>
```


Here is an example of the circle list style type:


```
    <p>Here is a list of unordered items:</p>    
    <ul style="list-style-type: circle">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>
```


Here is an example of the square list style type:


```
    <p>Here is a list of unordered items:</p>    
    <ul style="list-style-type: square">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>
```


Here is an example of the none list style type:


```
    <p>Here is a list of unordered items:</p>    
    <ul style="list-style-type: none">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>
```


<h2>
    Exercise</h2>


Use `<ul>` and `<ol>` listing the list(bottom) below the text `My favorite foods/drinks list`.

(Hint: You can insert a list to a list like `<ol>` into `<li>`)


```
    • Foods
        1. Egg
        2. Sushi
    • Drinks
        1. Apple juice
        2. Coffee
```


<h1>
    Images</h1>



---

Images in HTML are inline elements that can be placed within a paragraph. To add an image, use the `<img>` tag along with the `src` attribute to specify the location of the image.


```
    <img src="/static/img/code.jpg">
```


You may use JavaScript to trigger an event when an image finished loading.


```
    <img src="/static/img/code.jpg" onload="alert('image loaded')">
```


Resizing the image can be done using the width and height attributes of an image, or alternatively by using CSS:


```
    <img src="/static/img/code.jpg" width="100">

    <img src="/static/img/code.jpg" style="width: 100px">
```


Having an "alt" attribute set for the image is useful for when an image could not load or when you want to add a tooltip description that will be displayed when hovering on top of an image.


```
    <img src="/static/img/code.jpg" style="width: 100px" alt="A picture of some code">
```


<h3>
    Image Types</h3>


There are three main types of image formats which you should be using.



* Lossless formats - useful for when you need pixel-perfect graphics, for example for logos. The most common format is PNG. PNG also supports alpha transparency, meaning that you can use any background you want and overlay the image on top of that background.
* Lossy formats - useful for displaying rich images. Using a lossless format such as PNG would be an order of magnitude larger if used in such images. The most common format used in this category is JPG.
* Animated formats - useful for showing short animated images. The most common format is GIF, although it is a very old yet widely supported format, with many inherent drawbacks, such as a 256 color limit on each frame, and bad compression.
<h3>
    Using the CSS float attribute with images</h3>



Images can be set to float nearby text so they would blend with the text better. Notice the use of the `clear` CSS attribute - which directs the browser to break the floating effect after the first paragraph.


```
    <img src="/static/img/lab.png" style="float: left;">

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore 
    magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo 
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

    <p style="clear: both">Second paragraph</p>
```


<h2>
    Exercise</h2>




1. Add an image within the body, tag with the image "photo.jpg".
2. Adjust size of img to 100px by 100px
3. Add onload command, onload="alert('')" with the text "task complete"

<h1>HTML Styles</h1>


The HTML `style` attribute is used to add styles to an element, such as color, font, size, and more.

Setting the style of an HTML element, can be done with the `style` attribute.

The HTML `style` attribute has the following syntax:


```
<tagname style="property:value;">
```


The _property_ is a CSS property. The _value_ is a CSS value.

<h2>Background Color</h2>


The CSS `background-color` property defines the background color for an HTML element.


```
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```


<h2>Text Color</h2>


The CSS `color` property defines the text color for an HTML element:


```
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```


<h2>Fonts</h2>


The CSS `font-family` property defines the font to be used for an HTML element:


```
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
```


<h2>Text Size</h2>


The CSS `font-size` property defines the text size for an HTML element:


```
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
```


<h2>Text Alignment</h2>


The CSS `text-align` property defines the horizontal text alignment for an HTML element:


```
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```


<h1>Classes</h1>



---

CSS classes are commonly used to define a set of CSS styles and then apply them on an HTML element using selectors. To define a class within a CSS stylesheet, use the dot selector, as follows:


```
<style>
.nice {
    font-family: sans-serif;
}
</style>
```


Each HTML element can have a set of classes, ordered in a specific order. Each class will potentially add a set of CSS definitions according to the styles that were defined in the page. In this piece of code we have defined a CSS rule that will be applied to every element that contains the "nice" class. This means that once this piece of code has been defined inside the HTML page, the following HTML paragraph will have the style applied to it:


```
<style>
.nice {
    font-family: sans-serif;
}
</style>
<p class="nice">This is a short sentence.</p>

	

## 🎨 Where to find everything

- **HTML:** Learn HTML .  
	[Go to tutorial about HTML](https://www.w3schools.com/html/default.asp)

- **Front-end Development:** Learn Front-end Development .  
	[Go to tutorial about Front-end Development](https://www.w3schools.com/where_to_start.asp)


- **Fonts:** Add your favorite from **Google fonts**.  
	[Go to tutorial about fonts](https://www.w3schools.com/w3css/w3css_fonts_google.asp)

- **Icons:** Add icons with **Fontawesome** and their free library.  
	[Go to tutorial about Fontawesome](https://www.w3schools.com/icons/fontawesome5_intro.asp)










Happy learning!

