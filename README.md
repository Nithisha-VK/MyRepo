# 👋 Hello developer!
This project contains a basic HTML structure to get you started. 


<h1>Hello, World!</h1>



---

Welcome to _Learn HTML_, the easiest way to learn HTML & CSS interactively.

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

## 🏗 What's next?

Build your project however you like using HTML, CSS and JavaScript. 

Use these four files as your starting point:


- **index.html:** This is the default page for your space, where you write HTML, the standard markup language for creating web pages.
- **styles.css:** Use the CSS file to style your content and change the look of your space with beautiful colors, fonts and much more. 
- **scripts.js:** Use this file to make your website dynamic and interactive with JavaScript. 

> **Note:** The **styles.css** and **scripts.js** files link into the **index.html** file so that they are all connected.


## 🎨 Where to find everything

- **HTML:** Learn HTML .  
	[Go to tutorial about fonts](https://www.w3schools.com/html/default.asp)

- **Front-end Development:** Learn Front-end Development .  
	[Go to tutorial about fonts](https://www.w3schools.com/where_to_start.asp)


- **Fonts:** Add your favorite from **Google fonts**.  
	[Go to tutorial about fonts](https://www.w3schools.com/w3css/w3css_fonts_google.asp)

- **Icons:** Add icons with **Fontawesome** and their free library.  
	[Go to tutorial about Fontawesome](https://www.w3schools.com/icons/fontawesome5_intro.asp)










Happy learning!

