[HTML codes derive.1.txt](https://github.com/user-attachments/files/17598640/HTML.codes.derive.1.txt)- 👋 Hi, I’m @Davidking00
- 👀 I’m interested in ...[Uploading HTML codes dtutoria

<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>

HTML Headings
HTML headings are defined with the <h1> to <h6> tags.

<h1> defines the most important heading. <h6> defines the least important heading: 

Example
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>

HTML Links
HTML links are defined with the <a> tag:

Example
<a href="https://www.w3schools.com">This is a link</a>


HTML Images
HTML images are defined with the <img> tag.

The source file (src), alternative text (alt), width, and height are provided as attributes:

Example
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">





How to View HTML Source
Have you ever seen a Web page and wondered "Hey! How did they do that?"

View HTML Source Code:
Click CTRL + U in an HTML page, or right-click on the page and select "View Page Source". 
This will open a new tab containing the HTML source code of the page.

Inspect an HTML Element:
Right-click on an element (or a blank area), and choose "Inspect" to see what elements are made up of
 (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles

The HTML element is everything from the start tag to the end tag:

<tagname>Content goes here...</tagname>
Examples of some HTML elements:

<h1>My First Heading</h1>
<p>My first paragraph.</p>
Start tag	Element content	End tag
<h1>	My First Heading	</h1>
<p>	My first paragraph.	</p>
<br>	none	none


Nested HTML Elements
HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

The following example contains four HTML elements (<html>, <body>, <h1> and <p>):

Example
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
Example Explained
The <html> element is the root element and it defines the whole HTML document.

It has a start tag <html> and an end tag </html>.

Then, inside the <html> element there is a <body> element:

<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
The <body> element defines the document's body.

It has a start tag <body> and an end tag </body>.

Then, inside the <body> element there are two other elements: <h1> and <p>:

<h1>My First Heading</h1>
<p>My first paragraph.</p>
The <h1> element defines a heading.

It has a start tag <h1> and an end tag </h1>:

<h1>My First Heading</h1>
The <p> element defines a paragraph.

It has a start tag <p> and an end tag </p>:

<p>My first paragraph.</p>

Never Skip the End Tag
Some HTML elements will display correctly, even if you forget the end tag:

Example
<html>
<body>

<p>This is a paragraph
<p>This is a paragraph

</body>
</html>
However, never rely on this! Unexpected results and errors may occur if you forget the end tag!

Empty HTML Elements
HTML elements with no content are called empty elements.

The <br> tag defines a line break, and is an empty element without a closing tag:

Example
<p>This is a <br> paragraph with a line break.</p>
HTML is Not Case Sensitive
HTML tags are not case sensitive: <P> means the same as <p>.

The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.

At W3Schools we always use lowercase tag names.

Exercise
?
True or False. Empty elements must have a close tag.


True
False

HTML Tag Reference
W3Schools' tag reference contains additional information about these tags and their attributes.

Tag	Description
<html>	Defines the root of an HTML document
<body>	Defines the document's body
<h1> to <h6>	Defines HTML headings
For a complete list of all available HTML tags, visit our HTML Tag Reference.

HTML Attributes
HTML attributes provide additional information about HTML elements.

HTML Attributes
All HTML elements can have attributes
Attributes provide additional information about elements
Attributes are always specified in the start tag
Attributes usually come in name/value pairs like: name="value"
The href Attribute
The <a> tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

Example
<a href="https://www.w3schools.com">Visit W3Schools</a>
You will learn more about links in our HTML Links chapter.

The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

Example
<img src="img_girl.jpg">
There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.

The width and height Attributes
The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

Example
<img src="img_girl.jpg" width="500" height="600">
The alt Attribute
The required alt attribute for the <img> tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

Example
<img src="img_girl.jpg" alt="Girl with a jacket">
Example
See what happens if we try to display an image that does not exist:

<img src="img_typo.jpg" alt="Girl with a jacket">
You will learn more about images in our HTML Images chapter.

ADVERTISEMENT

The style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.

Example
<p style="color:red;">This is a red paragraph.</p>
You will learn more about styles in our HTML Styles chapter.

The lang Attribute
You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:

<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

The following example specifies English as the language and United States as the country:

<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
You can see all the language codes in our HTML Language Code Reference.

The title Attribute
The title attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

Example
<p title="I'm a tooltip">This is a paragraph.</p>
We Suggest: Always Use Lowercase Attributes
The HTML standard does not require lowercase attribute names.

The title attribute (and all other attributes) can be written with uppercase or lowercase like title or TITLE.

However, W3C recommends lowercase attributes in HTML, and demands lowercase attributes for stricter document types like XHTML.

At W3Schools we always use lowercase attribute names.

We Suggest: Always Quote Attribute Values
The HTML standard does not require quotes around attribute values.

However, W3C recommends quotes in HTML, and demands quotes for stricter document types like XHTML.

Good:
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
Bad:
<a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
Sometimes you have to use quotes. This example will not display the title attribute correctly, because it contains a space:

Example
<p title=About W3Schools>
 At W3Schools we always use quotes around attribute values.

Single or Double Quotes?
Double quotes around attribute values are the most common in HTML, but single quotes can also be used.

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

<p title='John "ShotGun" Nelson'>
Or vice versa:

<p title="John 'ShotGun' Nelson">
Chapter Summary
All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element
Exercise
?
Which of the following is a correct syntax for using an HTML attribute?


<img src='img_girl.jpg'>
<img src('img_girl.jpg')>
<img src:'img_girl.jpg')>

                 The HTML Style Attribute
Setting the style of an HTML element, can be done with the style attribute.

The HTML style attribute has the following syntax:

<tagname style="property:value;">

                                   Background Color
The CSS background-color property defines the background color for an HTML element.

Example
Set the background color for a page to powderblue:

<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>

                    Example
Set background color for two different elements:

<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
                          Text Color
The CSS color property defines the text color for an HTML element:
Example
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

                                          Fonts
The CSS font-family property defines the font to be used for an HTML element:
Example
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>

                           Text Size
The CSS font-size property defines the text size for an HTML element:
Example
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
                                          Text Alignment
The CSS text-align property defines the horizontal text alignment for an HTML element:
Example
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>

                                Chapter Summary
Use the style attribute for styling HTML elements
Use background-color for background color
Use color for text colors
Use font-family for text fonts
Use font-size for text sizes
Use text-align for text alignment

                                          HTML Text Formatting
HTML contains several elements for defining text with a special meaning.
Example
This text is bold
This text is italic
This is subscript and superscript
                       HTML Formatting Elements
Formatting elements were designed to display special types of text:

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

       HTML <b> and <strong> Elements
The HTML <b> element defines bold text, without any extra importance.
Example
<b>This text is bold</b>
The HTML <strong> element defines text with strong importance. The content inside is typically displayed in bold.
Example
<strong>This text is important!</strong>

         HTML <i> and <em> Elements
The HTML <i> element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.
Tip: The <i> tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.
Example
<i>This text is italic</i>
The HTML <em> element defines emphasized text. The content inside is typically displayed in italic.
Tip: A screen reader will pronounce the words in <em> with an emphasis, using verbal stress.
Example
<em>This text is emphasized</em>

   HTML <small> Element
The HTML <small> element defines smaller text:
Example
<small>This is some smaller text.</small>

    HTML <mark> Element
The HTML <mark> element defines text that should be marked or highlighted:
Example
<p>Do not forget to buy <mark>milk</mark> today.</p>

    HTML <del> Element
The HTML <del> element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:
Example
<p>My favorite color is <del>blue</del> red.</p>

    HTML <ins> Element
The HTML <ins> element defines a text that has been inserted into a document. Browsers will usually underline inserted text:
Example
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>

     HTML <sub> Element
The HTML <sub> element defines subscript text. Subscript text appears half a character below the 
normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, 
like H2O:
Example
<p>This is <sub>subscripted</sub> text.</p>

     HTML <sup> Element
The HTML <sup> element defines superscript text. Superscript text appears half a character above the normal line,
 and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:
Example
<p>This is <sup>superscripted</sup> text.</p>

                HTML Quotation and Citation Elements
In this chapter we will go through the <blockquote>,<q>, <abbr>, <address>, <cite>, and <bdo> HTML elements.
<!DOCTYPE html>
<html>
<body>
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization,
 WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and
 deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
</body>
</html>
      HTML <q> for Short Quotations
The HTML <q> tag defines a short quotation.
Browsers normally insert quotation marks around the quotation.
Example
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
HTML <abbr> for Abbreviations
The HTML <abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
Marking abbreviations can give useful information to browsers, translation systems and search-engines.
Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element. 
Example
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

               HTML <address> for Contact Information
The HTML <address> tag defines the contact information for the author/owner of a document or an article.
The contact information can be an email address, URL, physical address, phone number, social media handle, etc.
The text in the <address> element usually renders in italic, and browsers will always add a line break before and after the <address> element.
Example
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>

   HTML <cite> for Work Title
The HTML <cite> tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).
Note: A person's name is not the title of a work.
The text in the <cite> element usually renders in italic.
Example
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

         HTML <bdo> for Bi-Directional Override
BDO stands for Bi-Directional Override
The HTML <bdo> tag is used to override the current text direction:
Example
<bdo dir="rtl">This text will be written from right to left</bdo>

HTML Quotation and Citation Elements
Tag	Description
<abbr>	Defines an abbreviation or acronym
<address>	Defines contact information for the author/owner of a document
<bdo>	Defines the text direction
<blockquote>	Defines a section that is quoted from another source
<cite>	Defines the title of a work
<q>	Defines a short inline quotation


                Add Comments
With comments you can place notifications and reminders in your HTML code:
Example
<!-- This is a comment -->
<p>This is a paragraph.</p>
<!-- Remember to add more information here -->

      HTML Colors
HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
Color Names
In HTML, a color can be specified by using a color name:
           background colour
Example
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
             text color
Example
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
                            border color
Example
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
                          color value
Example
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>

                                                   HTML CSS
Chapter Summary
Use the HTML style attribute for inline styling
Use the HTML <style> element to define internal CSS
Use the HTML <link> element to refer to an external CSS file
Use the HTML <head> element to store <style> and <link> elements
Use the CSS color property for text colors
Use the CSS font-family property for text fonts
Use the CSS font-size property for text sizes
Use the CSS border property for borders
Use the CSS padding property for space inside the border
Use the CSS margin property for space outside the border

                    Inline CSS
An inline CSS is used to apply a unique style to a single HTML element.
An inline CSS uses the style attribute of an HTML element.
The following example sets the text color of the <h1> element to blue, and the text color of the <p> element to red:
Example
<h1 style="color:blue;">A Blue Heading</h1>
<p style="color:red;">A red paragraph.</p>  

Internal CSS
An internal CSS is used to define a style for a single HTML page.
An internal CSS is defined in the <head> section of an HTML page, within a <style> element.
The following example sets the text color of ALL the <h1> elements (on that page) to blue, 
and the text color of ALL the <p> elements to red. In addition,
 the page will be displayed with a "powderblue" background color: 
Example
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>
</body>
</html>

                         External CSS
An external style sheet is used to define the style for many HTML pages.
To use an external style sheet, add a link to it in the <head> section of each HTML page:
Example
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
                       NOTE
The external style sheet can be written in any text editor.
 The file must not contain any HTML code, and must be saved with a .css extension.
Here is what the "styles.css" file looks like:
"styles.css":
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
Tip: With an external style sheet, you can change the look of an 
entire web site, by changing one file!

                              CSS Colors, Fonts and Sizes
Here, we will demonstrate some commonly used CSS properties.
 You will learn more about them later.

The CSS color property defines the text color to be used.

The CSS font-family property defines the font to be used.

The CSS font-size property defines the text size to be used.

Example
Use of CSS color, font-family and font-size properties:

<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

                    CSS Border
The CSS border property defines a border around an HTML element.
Tip: You can define a border for nearly all HTML elements.
Example
Use of CSS border property: 
p {
  border: 2px solid powderblue;
}

                             CSS Padding
The CSS padding property defines a padding (space) between the text and the border.
Example
Use of CSS border and padding properties:
p {
  border: 2px solid powderblue;
  padding: 30px;
}

CSS Margin
The CSS margin property defines a margin (space) outside the border.
Example
Use of CSS border and margin properties:
p {
  border: 2px solid powderblue;
  margin: 50px;
}

                   Link to External CSS
External style sheets can be referenced with a full URL or with a path relative to the current web page.
Example1
This example uses a full URL to link to a style sheet:
<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">

Example2
This example links to a style sheet located in the html folder on the current web site: 
<link rel="stylesheet" href="/html/styles.css">

Example3
This example links to a style sheet located in the same folder as the current page:
<link rel="stylesheet" href="styles.css">

You can read more about file paths in the chapter HTML File Paths.


                               Chapter Summary
Use the <a> element to define a link
Use the href attribute to define the link address
Use the target attribute to define where to open the linked document
Use the <img> element (inside <a>) to use an image as a link
Use the mailto: scheme inside the href attribute to create a link that opens the user's email program

                     HTML Links - Syntax
The HTML <a> tag defines a hyperlink. It has the following syntax:
<a href="url">link text</a>
The most important attribute of the <a> element is the href attribute, which indicates the link's destination.
The link text is the part that will be visible to the reader.
Clicking on the link text, will send the reader to the specified URL address.
Example
This example shows how to create a link to W3Schools.com:
<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>

                                        By default, links will appear as follows in all browsers:

An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red
Tip: Links can of course be styled with CSS, to get another look!
HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
Example
Use target="_blank" to open the linked document in a new browser window or tab:

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

                                                              Absolute URLs vs. Relative URLs
Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):

Example
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>5

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

                       HTML Links - Use an Image as a Link
To use an image as a link, just put the <img> tag inside the <a> tag:
Example
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

                             Link to an Email Address
Use mailto: inside the href attribute to create a link that opens
 the user's email program (to let them send a new email):
Example
<a href="mailto:someone@example.com">Send email</a>

                         Button as a Link
To use an HTML button as a link, you have to add some JavaScript code.
JavaScript allows you to specify what happens at certain events, such as a click of a button:
Example
<button onclick="document.location='default.asp'">HTML Tutorial</button>

                                        Link Titles
The title attribute specifies extra information about an element. 
The information is most often shown as a tooltip text when the mouse moves over the element.
Example
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>

                           More on Absolute URLs and Relative URLs
Example
Use a full URL to link to a web page: 
<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>
Example
Link to a page located in the html folder on the current web site: 
<a href="/html/default.asp">HTML tutorial</a>
Example
Link to a page located in the same folder as the current page: 
<a href="default.asp">HTML tutorial</a>

                                     HTML Links - Different Colors
An HTML link is displayed in a different color depending on whether it has been visited, is unvisited, or is active.
HTML Link Colors
By default, a link will appear like this (in all browsers):
An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red
You can change the link state colors, by using CSS:

Example
Here, an unvisited link will be green with no underline. A visited link will be pink with no underline. An active link will be yellow and underlined. In addition, when mousing over a link (a:hover) it will become red and underlined:

<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>

              Link Buttons
A link can also be styled as a button, by using CSS:

This is a link
Example
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>

                              HTML Links - Create Bookmarks

Chapter Summary
Use the id attribute (id="value") to define bookmarks in a page
Use the href attribute (href="#value") to link to the bookmark
HTML links can be used to create bookmarks, so that readers can jump to specific parts of a web page.

        Create a Bookmark in HTML
Bookmarks can be useful if a web page is very long.

To create a bookmark - first create the bookmark, then add a link to it.

When the link is clicked, the page will scroll down or up to the location with the bookmark.

Example
First, use the id attribute to create a bookmark:

<h2 id="C4">Chapter 4</h2>
Then, add a link to the bookmark ("Jump to Chapter 4"), from within the same page:

Example
<a href="#C4">Jump to Chapter 4</a>
You can also add a link to a bookmark on another page:

<a href="html_demo.html#C4">Jump to Chapter 4</a>

HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax
<img src="url" alt="alternatetext">
The src Attribute
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads, it is the browser, at that moment, that gets the image
 from a web server and inserts it into the page. Therefore, 
make sure that the image actually stays in the same spot in relation to the web page,
 otherwise your visitors will get a broken link icon. 
The broken link icon and the alt text are shown if the browser cannot find the image.

Example
<img src="img_chania.jpg" alt="Flowers in Chania">

                         The alt Attribute
The required alt attribute provides an alternate text for an image, 
if the user for some reason cannot view it
 (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

Example
<img src="img_chania.jpg" alt="Flowers in Chania">
If a browser cannot find an image, it will display the value of the alt attribute:

Example
<img src="wrongname.gif" alt="Flowers in Chania">
Tip: A screen reader is a software program that reads the HTML code, and allows the user to
 "listen" to the content. Screen readers are useful for people who are visually impaired or learning disabled.


                      Image Size - Width and Height
You can use the style attribute to specify the width and height of an image.
Example
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
Alternatively, you can use the width and height attributes:
Example
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
The width and height attributes always define the width and height of the image in pixels
Note: Always specify the width and height of an image.
 If width and height are not specified, the web page might flicker while the image loads.

                                                 Image Size - Width and Height
You can use the style attribute to specify the width and height of an image.
Example
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
Alternatively, you can use the width and height attributes:
Example
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
The width and height attributes always define the width and height of the image in pixels.
Note:     Always specify the width and height of an image. 
If width and height are not specified, the web page might flicker while the image loads.

                 Images in Another Folder
If you have your images in a sub-folder, you must include the folder name in the src attribute:
Example
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

               Images on Another Server/Website
Some web sites point to an image on another server.
To point to an image on another server, you must specify an absolute (full) URL in the src attribute:
Example
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">
Animated Images
              HTML allows animated GIFs:
Example
<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">

Image as a Link
To use an image as a link, put the <img> tag inside the <a> tag:
Example
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

                            Image Floating
Use the CSS float property to let the image float to the right or to the left of a text:
Example
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>
<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>

                                                  Common Image Formats
Here are the most common image file types, which are supported in all browsers (Chrome, Edge, Firefox, Safari, Opera):

Abbreviation	File Format	File Extension
APNG	Animated Portable Network Graphics	.apng
GIF	Graphics Interchange Format	.gif
ICO	Microsoft Icon	.ico, .cur
JPEG	Joint Photographic Expert Group image	.jpg, .jpeg, .jfif, .pjpeg, .pjp
PNG	Portable Network Graphics	.png
SVG	Scalable Vector Graphics	.svg
Chapter Summary
Use the HTML <img> element to define an image
Use the HTML src attribute to define the URL of the image
Use the HTML alt attribute to define an alternate text for an image, if it cannot be displayed
Use the HTML width and height attributes or the CSS width and height properties to define the size of the image
Use the CSS float property to let the image float to the left or to the right
Note: Loading large images takes time, and can slow down your web page. Use images carefully.

HTML Image Maps
With HTML image maps, you can create clickable areas on an image.

                                       Image Maps
The HTML <map> tag defines an image map. 
An image map is an image with clickable areas. 
The areas are defined with one or more <area> tags.
Try to click on the computer, phone, or the cup of coffee in the image below:
Workplace
Example
Here is the HTML source code for the image map above:
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">
<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>
How Does it Work?
The idea behind an image map is that you should be able to perform different actions
 depending on where in the image you click.
To create an image map you need an image, and some HTML code that describes the clickable areas.

                 Create Image Map
Then, add a <map> element.
The <map> element is used to create an image map, and is linked to the image by using the required name attribute:
<map name="workmap">
The name attribute must have the same value as the <img>'s usemap attribute .
The Areas
Then, add the clickable areas.
A clickable area is defined using an <area> element.
Shape
You must define the shape of the clickable area, and you can choose one of these values:
rect - defines a rectangular region
circle - defines a circular region
poly - defines a polygonal region
default - defines the entire region
You must also define some coordinates to be able to place the clickable area onto the image. 
Shape="rect"
The coordinates for shape="rect" come in pairs, one for the x-axis and one for the y-axis.
So, the coordinates 34,44 is located 34 pixels from the left margin and 44 pixels from the top:
Workplace
The coordinates 270,350 is located 270 pixels from the left margin and 350 pixels from the top:
Workplace
Now we have enough data to create a clickable rectangular area:
Example
<area shape="rect" coords="34, 44, 270, 350" href="computer.htm">
This is the area that becomes clickable and will send the user to the page "computer.htm":
Workplace
Shape="circle"
To add a circle area, first locate the coordinates of the center of the circle:
337,300
Workplace
Then specify the radius of the circle:
44 pixels
Workplace
Now you have enough data to create a clickable circular area:

Example
<area shape="circle" coords="337, 300, 44" href="coffee.htm">
This is the area that becomes clickable and will send the user to the page "coffee.htm":
Workplace
Shape="poly"
The shape="poly" contains several coordinate points, which creates a shape formed with straight lines (a polygon).
This can be used to create any shape.
Like maybe a croissant shape!
How can we make the croissant in the image below become a clickable link?
French Food
We have to find the x and y coordinates for all edges of the croissant:
French Food
The coordinates come in pairs, one for the x-axis and one for the y-axis:
Example
<area shape="poly" coords="140,121,181,116,204,160,204,222,191,270,140,329,85,355,58,352,37,322,40,259,103,161,128,147" href="croissant.htm">
This is the area that becomes clickable and will send the user to the page "croissant.htm":
French Food
Image Map and JavaScript
A clickable area can also trigger a JavaScript function.
Add a click event to the <area> element to execute a JavaScript function:
Example
Here, we use the onclick attribute to execute a JavaScript function when the area is clicked:
<map name="workmap">
  <area shape="circle" coords="337,300,44" href="coffee.htm" onclick="myFunction()">
</map>
<script>
function myFunction() {
  alert("You clicked the coffee cup!");
}
</script>
Chapter Summary
Use the HTML <map> element to define an image map
Use the HTML <area> element to define the clickable areas in the image map
Use the HTML usemap attribute of the <img> element to point to an image map
HTML Image Tags
Tag	Description
<img>	Defines an image
<map>	Defines an image map
<area>	Defines a clickable area inside an image map
<picture>	Defines a container for multiple image resources
For a complete list of all available HTML tags, visit our HTML Tag Reference.

                HTML Background Images
A background image can be specified for almost any HTML element.
Background Image on a HTML element
To add a background image on an HTML element, use the HTML style attribute and the CSS background-image property:
Example
Add a background image on a HTML element:
<p style="background-image: url('img_girl.jpg');">
You can also specify the background image in the <style> element, in the <head> section:
Example
Specify the background image in the <style> element:
<style>
p {
  background-image: url('img_girl.jpg');
}
</style>

                      Background Image on a Page
If you want the entire page to have a background image, 
you must specify the background image on the <body> element:
Example
Add a background image for the entire page:
<style>
body {
  background-image: url('img_girl.jpg');
}
</style>

                                                  Background Repeat
If the background image is smaller than the element, 
the image will repeat itself, horizontally and vertically, 
until it reaches the end of the element:
Example
<style>
body {
  background-image: url('example_img_girl.jpg');
}
</style>
To avoid the background image from repeating itself, set the background-repeat property to no-repeat.
Example
<style>
body {
  background-image: url('example_img_girl.jpg');
  background-repeat: no-repeat;
}
</style>

                            Background Cover
If you want the background image to cover the entire element, you can set the background-size property to cover.
Also, to make sure the entire element is always covered, set the background-attachment property to fixed:
This way, the background image will cover the entire element, with no stretching (the image will keep its original proportions):
Example
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}
</style>
Background Stretch
If you want the background image to stretch to fit the entire element, you can set the background-size property to 100% 100%:

Try resizing the browser window, and you will see that the image will stretch, but always cover the entire element.

Example
<style>
body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: 100% 100%;
}
</style>

Exercise
?
What is a correct CSS property for defining background images?
The bg property
The image property
The background-image property
Learn More CSS
From the examples above you have learned that background images can be styled by using
 the CSS background properties.
To learn more about CSS background properties, study our CSS Background Tutorial.

                                 HTML <picture> Element
The HTML <picture> element allows you to display different pictures for different devices or screen sizes.
The HTML <picture> Element
The HTML <picture> element gives web developers more flexibility in specifying image resources.
The <picture> element contains one or more <source> elements, each referring to differentiate 
 images through the srcset attribute. This way the browser can choose the image that best fits 
the current view and/or device.
Each <source> element has a media attribute that defines when the image is the most suitable.
Example
Show different images for different screen sizes:
<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>
Note: Always specify an <img> element as the last child element of the <picture> element. 
The <img> element is used by browsers that do not support the <picture> element, 
or if none of the <source> tags match.

                                            When to use the Picture Element
There are two main purposes for the <picture> element:

        1. Bandwidth
If you have a small screen or device, it is not necessary to load a large image file. 
The browser will use the first <source> element with matching attribute values, 
and ignore any of the following elements.

             2. Format Support
Some browsers or devices may not support all image formats. 
By using the <picture> element, you can add images of all formats, 
and the browser will use the first format it recognizes, and
 ignore any of the following elements.

Example
The browser will use the first image format it recognizes:

<picture>
  <source srcset="img_avatar.png">
  <source srcset="img_girl.jpg">
  <img src="img_beatles.gif" alt="Beatles" style="width:auto;">
</picture>
Note: The browser will use the first <source> element with matching attribute values,
 and ignore any following <source> elements.

HTML Favicon
A favicon is a small image displayed next to the page title in the browser tab.

How To Add a Favicon in HTML
You can use any image you like as your favicon. You can also create your own favicon
 on sites like https://www.favicon.cc.
Tip: A favicon is a small image, so it should be a simple image with high contrast.
A favicon image is displayed to the left of the page title in the browser tab, like this:

Example of favicon
To add a favicon to your website, either save your favicon image to the root directory
 of your webserver, or create a folder in the root directory called images, and save your 
favicon image in this folder. A common name for a favicon image is "favicon.ico".
Next, add a <link> element to your "index.html" file, after the <title> element, like this:
Example
<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
Now, save the "index.html" file and reload it in your browser. Your browser tab should now 
display your favicon image to the left of the page title.

                                         HTML Tables
HTML tables allow web developers to arrange data into rows and columns.

Example
Company	Contact	Country
Alfreds Futterkiste	Maria Anders	Germany
Centro comercial Moctezuma	Francisco Chang	Mexico
Ernst Handel	Roland Mendel	Austria
Island Trading	Helen Bennett	UK
Laughing Bacchus Winecellars	Yoshi Tannamuri	Canada
Magazzini Alimentari Riuniti	Giovanni Rovelli	Italy
Define an HTML Table
A table in HTML consists of table cells inside rows and columns.

Example
A simple HTML table:

<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
Table Cells
Each table cell is defined by a <td> and a </td> tag.

td stands for table data.

Everything between <td> and </td> are the content of the table cell.

Example
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>
Note: A table cell can contain all sorts of HTML elements: text, images, lists, links, other tables, etc.

ADVERTISEMENT

Table Rows
Each table row starts with a <tr> and ends with a </tr> tag.

tr stands for table row.

Example
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
You can have as many rows as you like in a table; just make sure that the number of cells are the same in each row.

Note: There are times when a row can have less or more cells than another. You will learn about that in a later chapter.

Table Headers
Sometimes you want your cells to be table header cells. In those cases use the <th> tag instead of the <td> tag:

th stands for table header.

Example
Let the first row be table header cells:

<table>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
By default, the text in <th> elements are bold and centered, but you can change that with CSS.

Exercise
?
What is the correct tag name for a table-cell in HTML?


<tc>
<td>
<tr>

                                                  HTML Table Tags
Tag	Description
<table>	Defines a table
<th>	Defines a header cell in a table
<tr>	Defines a row in a table
<td>	Defines a cell in a table
<caption>	Defines a table caption
<colgroup>	Specifies a group of one or more columns in a table for formatting
<col>	Specifies column properties for each column within a <colgroup> element
<thead>	Groups the header content in a table
<tbody>	Groups the body content in a table
<tfoot>	Groups the footer content in a table
For a complete list of all available HTML tags, visit our HTML Tag Reference.

                                    HTML Table Borders
HTML tables can have borders of different styles and shapes.

How To Add a Border
To add a border, use the CSS border property on table, th, and td elements: 	 	  	 	  	 	 
Example
table, th, td {
  border: 1px solid black;
}
Collapsed Table Borders
To avoid having double borders like in the example above, 
set the CSS border-collapse property to collapse.
This will make the borders collapse into a single border: 	 	  	 	  	 	 
Example
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
Style Table Borders
If you set a background color of each cell, and give the border a white color
 (the same as the document background),
 you get the impression of an invisible borders 	 	 
Example
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}
th, td {
  background-color: #96D4D4;
}
Round Table Borders
With the border-radius property, the borders get rounded corners:	 	  	 	  	 	 
Example
table, th, td {
  border: 1px solid black;
  border-radius: 10px;
}
Skip the border around the table by leaving out table from the css selector:

 	 	 
 	 	 
 	 	 
Example
th, td {
  border: 1px solid black;
  border-radius: 10px;
}
Dotted Table Borders
With the border-style property, you can set the appearance of the border	 	 
The following values are allowed:
dotted     
dashed     
solid     
double     
groove     
ridge     
inset     
outset     
none     
hidden     
Example
 th, td {
  border-style: dotted;
}
Border Color
With the border-color property, you can set the color of the border. 	 	 
Example
 th, td {
  border-color: #96D4D4;
}

HTML Table Sizes
HTML tables can have different sizes for each column, row or the entire table.

 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
Use the style attribute with the width or height properties to specify the size of a table, row or column.

HTML Table Width
To set the width of a table, add the style attribute to the <table> element:

Example
Set the width of the table to 100%:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
Note: Using a percentage as the size unit for a width means how wide will this element be compared to its parent element, which in this case is the <body> element.

                     HTML Table Column Width
 	 	 
 	 	 
 	 	 
To set the size of a specific column, add the style attribute on a <th> or <td> element:

Example
Set the width of the first column to 70%:

<table style="width:100%">
  <tr>
    <th style="width:70%">Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
ADVERTISEMENT

                     HTML Table Row Height
 	 	 
 	 	 
 	 	 
To set the height of a specific row, add the style attribute on a table row element:

Example
Set the height of the second row to 200 pixels:

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr style="height:200px">
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>

HTML Table Headers
HTML tables can have headers for each column or row, or for many columns/rows.

EMIL	TOBIAS	LINUS
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
8:00	 	 
9:00	 	 
10:00	 	 
11:00	 	 
12:00	 	 
13:00	 	 
MON	TUE	WED	THU	FRI
8:00	 	 	 	 	 
9:00	 	 	 	 	 
10:00	 	 	 	 	 
11:00	 	 	 	 	 
12:00	 	 	 	 	 
DECEMBER
 	 	 
 	 	 
 	 	 
 	 	 
 	 	 
HTML Table Headers
Table headers are defined with th elements. Each th element represents a table cell.

Example
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
Vertical Table Headers
To use the first column as table headers, define the first cell in each row as a <th> element:

Example
<table>
  <tr>
    <th>Firstname</th>
    <td>Jill</td>
    <td>Eve</td>
  </tr>
  <tr>
    <th>Lastname</th>
    <td>Smith</td>
    <td>Jackson</td>
  </tr>
  <tr>
    <th>Age</th>
    <td>94</td>
    <td>50</td>
  </tr>
</table>
ADVERTISEMENT

Align Table Headers
By default, table headers are bold and centered:

Firstname	Lastname	Age
Jill	Smith	50
Eve	Jackson	94
To left-align the table headers, use the CSS text-align property:

Example
th {
  text-align: left;
}
Header for Multiple Columns
You can have a header that spans over two or more columns.

Name	Age
Jill	Smith	50
Eve	Jackson	94
To do this, use the colspan attribute on the <th> element:

Example
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
You will learn more about colspan and rowspan in the Table colspan & rowspan chapter.

Table Caption
You can add a caption that serves as a heading for the entire table.

Monthly savings
Month	Savings
January	$100
February	$50
To add a caption to a table, use the <caption> tag:

Example
<table style="width:100%">
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>
Note: The <caption> tag should be inserted immediately after the <table> tag.

HTML Table Padding & Spacing
HTML tables can adjust the padding inside the cells, and also the space between the cells.

With Padding
hello	hello	hello
hello	hello	hello
hello	hello	hello
With Spacing
hello	hello	hello
hello	hello	hello
hello	hello	hello
HTML Table - Cell Padding
Cell padding is the space between the cell edges and the cell content.

By default the padding is set to 0.

To add padding on table cells, use the CSS padding property:

Example
th, td {
  padding: 15px;
}
To add padding only above the content, use the padding-top property.

And the others sides with the padding-bottom, padding-left, and padding-right properties:
Example
th, td {
  padding-top: 10px;
  padding-bottom: 20px;
  padding-left: 30px;
  padding-right: 40px;
}
HTML Table - Cell Spacing
Cell spacing is the space between each cell.
By default the space is set to 2 pixels.
To change the space between table cells, use the CSS border-spacing property on the table element:
Example
table {
  border-spacing: 30px;
}

                                                HTML Table Colspan & Rowspan
HTML tables can have cells that span over multiple rows and/or columns.
NAME	  	 	  	 	  	 	 	 	 
APRIL	 	  	  	  	 	  	 	 
2022 	 	 
FIESTA	   	 	 
HTML Table - Colspan
To make a cell span over multiple columns, use the colspan attribute:
Example
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>57</td>
  </tr>
</table>
Note: The value of the colspan attribute represents the number of columns to span.

HTML Table - Rowspan
To make a cell span over multiple rows, use the rowspan attribute:

Example
<table>
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
</tr>
</table>
Note: The value of the rowspan attribute represents the number of rows to span.

                                   HTML Table Styling
Use CSS to make your tables look better.

   HTML Table - Zebra Stripes
If you add a background color on every other table row, you will get a nice zebra stripes effect.

1	2	3	4
5	6	7	8
9	10	11	12
13	14	15	16
17	18	19	20
To style every other table row element, use the :nth-child(even) selector like this:

Example
tr:nth-child(even) {
  background-color: #D6EEEE;
}
Note: If you use (odd) instead of (even), the styling will occur on row 1,3,5 etc. instead of 2,4,6 etc.

          HTML Table - Vertical Zebra Stripes
To make vertical zebra stripes, style every other column, instead of every other row.

1	2	3	4
5	6	7	8
9	10	11	12
13	14	15	16
17	18	19	20
Set the :nth-child(even) for table data elements like this:

Example
td:nth-child(even), th:nth-child(even) {
  background-color: #D6EEEE;
}
Note: Put the :nth-child() selector on both th and td elements if you want to have the styling on both headers and regular table cells.
Combine Vertical and Horizontal Zebra Stripes
You can combine the styling from the two examples above and you will have stripes on every other row and every other column.

If you use a transparent color you will get an overlapping effect 	 	   	 	 	 	 	 	 	 	 	 	  
Use an rgba() color to specify the transparency of the color:
Example
tr:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}
th:nth-child(even),td:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}
Horizontal Dividers
First Name	Last Name	Savings
Peter	Griffin	$100
Lois	Griffin	$150
Joe	Swanson	$300
If you specify borders only at the bottom of each table row, you will have a table with horizontal dividers.

Add the border-bottom property to all tr elements to get horizontal dividers:

Example
tr {
  border-bottom: 1px solid #ddd;
}
Hoverable Table
Use the :hover selector on tr to highlight table rows on mouse over:

First Name	Last Name	Savings
Peter	Griffin	$100
Lois	Griffin	$150
Joe	Swanson	$300
Example
tr:hover {background-color: #D6EEEE;}

        HTML Table Colgroup          
The <colgroup> element is used to style specific columns of a table.

HTML Table Colgroup
If you want to style the two first columns of a table, use the <colgroup> and <col> elements.

MON	TUE	WED	THU	FRI	SAT	SUN
1	2	3	4	5	6	7
8	9	10	11	12	13	14
15	16	17	18	19	20	21
22	23	24	25	26	27	28
The <colgroup> element should be used as a container for the column specifications.

Each group is specified with a <col> element.

The span attribute specifies how many columns that get the style.

The style attribute specifies the style to give the columns.

Note: There is a very limited selection of legal CSS properties for colgroups.

Example
<table>
  <colgroup>
    <col span="2" style="background-color: #D6EEEE">
  </colgroup>
  <tr>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
...
Note: The <colgroup> tag must be a child of a <table> element and should be placed before
 any other table elements, like <thead>, <tr>, <td> etc., but after the <caption> element, if present.

Legal CSS Properties
There is only a very limited selection of CSS properties that are allowed to be used in the colgroup:

width property
visibility property
background properties
border properties

All other CSS properties will have no effect on your tables.

Multiple Col Elements
If you want to style more columns with different styles, use more <col> elements inside the <colgroup>:

Example
<table>
  <colgroup>
    <col span="2" style="background-color: #D6EEEE">
    <col span="3" style="background-color: pink">
  </colgroup>
  <tr>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
...
Empty Colgroups
If you want to style columns in the middle of a table, insert a "empty" <col> element (with no styles) for the columns before:

Example
<table>
  <colgroup>
    <col span="3">
    <col span="2" style="background-color: pink">
  </colgroup>
  <tr>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
...
Hide Columns
You can hide columns with the visibility: collapse property:

Example
<table>
  <colgroup>
    <col span="2">
    <col span="3" style="visibility: collapse">
  </colgroup>
  <tr>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
...





erive.1.txt…]()

- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Davidking00/Davidking00 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
