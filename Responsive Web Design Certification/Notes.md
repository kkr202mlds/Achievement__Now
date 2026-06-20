- HTML stands for Hypertext Markup Language, is a markup language for creating web pages. It's the code that defines the structure and content like (paragraphs, headings, links, images, and videos) of a webpage.
```
left angle bracket (<), right angle bracket (>) &  forward slash (/)
<opening tag>content</closing tag>
```
- **Void Element** : Some HTML elements do not have a closing tag. These are known as void elements like img - image element
```
<img />
image element with a src attribute and alt attribute
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch." />
```
- **source attribute** ("src") specifies the URL or file path of an external resource that an element should load and embed into a webpage
- **alternative attribute** ("alt") is used to provide short, descriptive text for the images.
- HTML tag names are case-insensitive like 
```
<H1> as same as <h1> ->  case-insensitive
```
- HTML is made up of elements. The first one you will use is the h1 element.
- An **`<h1>` element** is the main heading of a webpage and you should only use one per page. h2 elements represent subheadings.
- When you need to add a paragraph to a webpage, you can use the p element.
- HTML represents the blocks, concrete, and irons that make up the walls. It's the foundation that makes the building strong. **CSS** represents the interior and exterior design that makes the house look beautiful. **JavaScript** represents the electrical and water system that ensures uninterrupted access to water and electricity.
```
<element attribute="value"></element>
The value can be a string or a number, depending on the attribute.
<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>
```
- **href attribute** (hypertext reference) specifies the URL of a link or external resource and the **target attribute** specifies where to open the link to open in a new browser tab.
- **anchor element** (`<a>` element) is used to create hyperlinks. The text between the opening and closing a tags is the clickable part users select to navigate.
- **`<input>` element** with the type attribute set to checkbox. **Inputs** are used to collect data from users, and the **type attribute** specifies the type of input.
-  **checked attribute** is used to specify that the checkbox should be checked by default.
```
<input type="checkbox" checked />
<input type="text">
<input type="text" disabled>
```
- If the attribute is not present, the checkbox will be unchecked. This is known as a boolean attribute like disabled & checked.
- Role of an attribute in HTML -> Attributes provide additional information and help define the behavior for HTML elements.
```
<link rel="stylesheet" href="./styles.css" />
```
-  **`<link>` element** is used to link to external resources like stylesheets and site icons. **rel attribute** stands for relationship b/w html doc & external res. href - hypertext refrenece
```
<link rel="stylesheet" href="./styles.css" />
stylesheet: Imports an external CSS file to style the webpage
```
- **`<head>` element tag** is used to contain metadata about the document, such as its title, links to stylesheets, and scripts.
- **`<meta>` Metadata element tag** is information about the page that isn't displayed directly on the page.
```
<head>                     
  <meta charset="UTF-8" />  # UTF-8 is the dominant std character encoding system used on web.
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Examples of the link element</title>
  <link rel="stylesheet" href="./styles.css" />
</head>
```
- Playwright Cuba : link element to link to an external Google Font
```
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap"
  rel="stylesheet"
/>
```
- **preconnect value** for the rel attribute tells the browser to create an early connection to the value.
- A favicon, which is short for favorite icon, is a small icon typically displayed in the browser tab next to the site title. A lot of websites will use a favicon to display their brand icon
```
<link rel="icon" href="favicon.ico" />
```
- **HTML boilerplate** is like a ready-made template for your webpages. Think of it as the foundation of a house. A boilerplate includes the basic structure and essential elements every HTML document needs.
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>freeCodeCamp</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
  </body>
</html>
```
- DOCTYPE declaration (Document Type Declaration) is an instruction placed at the very top of a web document to tell the web browser how to interpret and render the page. HTML5 document
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <!--Important metadata goes here-->
  </head>
  <body>
    <!--Headings, paragraphs, images, etc. go inside here-->
  </body>
</html>
```
- language for your page is set in the opening html tag.
```
<html lang="en">
```
- UCS- (Unicode Character Set) Transformation Format 8
- **Character encoding** is the method computers use to store characters as data. Essentially, all text on a web page is a sequence of characters stored as one or more bytes.
- In computing, a byte is a unit of data consisting of 8 bits, or binary digits.
- **`<meta>` elements tag** (metadata) has details about things like character encoding.
- Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.
#### Purpose does a HTML boilerplate serve
- Provides a starting structure for your websites.
- Ensures you are not missing any essential elements.
- Allows you to get started writing the content of your page faster.
- Turn the image <img> into a link by <a> anchor's tags.
```
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
```
- **`<section>` element tag** to separate the cat photos content from the future content.
- section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.
```
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
```
- **`<ul>` element tag** : To create an unordered list of items.
- **`<ol>` element tag** : defines an ordered list, which displays a sequence of items in a specific numerical, alphabetical, or Roman numeral order
- **`<li>` element tag** : is used to create a list item in an ordered <ol >or unordered list.
```
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```
- **`<figure>` element tag** represents self-contained content and will allow you to associate an image with a caption.
- **`<figcaption>` figure caption element tag** is used to add a caption to describe the image.
```
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
```
-  **`<em>` emphasis element tag** : To place emphasis on a specific word or phrase.
-  **`<strong>` element tag** : is used to indicate that some text is of strong importance or urgent.
-  **`<footer>` element tag** : is used to define a footer for a document or section. A footer typically contains information about the author of the document, copyright data, links to terms of use, contact information, and more.
```
<main>
</main>
  <footer>
    <p>Copyright</p> 
  </footer>
</body>
```
- **Div Elements** is used as a container to group other elements. When grouping related content for styling purposes CSS.
```
<div>
  <p>Example paragraph element.</p>
</div>
```
- **section element** has semantic meaning over the **div element** which is not semantic.
- Semantics are the meaning of words or phrases in a language. In HTML, which is a language, elements have their own semantic meaning too.
```
<section>
  <h2>Mammals</h2>
  <p>
    Mammals are warm-blooded animals with fur or hair. Most give birth to live
    young.
  </p>
  <ul>
    <li>Lion</li>
    <li>Elephant</li>
    <li>Dolphin</li>
  </ul>
</section>
```
- **id attribute** adds a unique identifier to an HTML element.
```
<h1 id="title">Movie Review Page</h1>
OR
<div class="card" id="sally-adventure-book">
```
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Review page Example</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <h1 id="title">Movie Review Page</h1>
  </body>
</html>

:- style.css
#title {
  color: blue;
}
```
- id attribute values should only contain letters, digits, underscores, and dashes.
- id attribute values should not contain spaces at all.
```
<h1 id="main-heading">Main heading</h1>
```
- **class attribute** value does not need to be unique and can contain spaces.
```
<div class="box"></div>
# type of class
<div class="box red-box"></div>
```
- Multi[le Classes with help of CSS
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Colored boxes example</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="box red-box"></div>
    <div class="box blue-box"></div>
    <div class="box red-box"></div>
    <div class="box blue-box"></div>
  </body>
</html>

:- style.css
.box {
  width: 100px;
  height: 100px;
}

.red-box {
  background-color: red;
}

.blue-box {
  background-color: blue;
}
```
- **HTML entity**, or **Character Reference** is a set of characters used to represent a reserved character in HTML.
- **Named Character References** : start with an ampersand sign (&) and end with a semicolon (;)
```
&lt; as same as <
&gt; as same as >
```
- **Decimal Character References** : starts with an ampersand sign and hash symbol (#), followed by one or more decimal digits, followed by a semicolon.
```
Input              Output
&#60;                <        
&#169;               ©
&#174;               ®
&#17;                
&#x3C;               <
```
- **Hexadecimal Numeric Reference** starts with an ampersand sign, hash symbol, and the letter x.
```
Input              Output
&#x20AC;             €
&#x03A9;             Ω
```
- **script element** is used to embed executable code. 
- **JavaScript** is used to add interactivity to your web pages. JavaScript include interactive games, image sliders, and dynamic forms.
```
<body>
  <script>
    alert("Welcome to freeCodeCamp");
  </script>
</body>
```
<img width="620" height="350" alt="Screenshot 2026-06-18 154312" src="https://github.com/user-attachments/assets/ce9ea2d4-66cb-4d6f-a700-246778d16d95" />

- script element to link to an external JavaScript file:
```
<script src="path-to-javascript-file.js"></script>
```
- **button element** is used to create clickable buttons on a webpage.      Buttons are interactive elements that users can click to perform actions.
```
<button class="btn">Buy Now</button>
```
- **Search Engine Optimization** SEO, is a practice that optimizes web pages so they become more visible and rank higher on search engines. One way to improve your site's SEO, is to provide a short description for the web page using the meta element.
```
<meta
  name="description"
  content="Discover expert tips and techniques for gardening in small spaces, choosing the right plants, and maintaining a thriving garden."
/>
```
- 4 Open Graph(OG) property Tags - to set how your website's content will be seen on different social media platforms.
- 1. title -  title of your web page content share
-  The content attribute is where you will write the title you want displayed for social media sites.
```
<meta content="freeCodeCamp.org" property="og:title" />
```
- 2. type - the type of content used for your web page share
```
<meta property="og:type" content="website" />
```
- 3. image - at least 1200 by 630 px and minimum are 600 by 315 pixel.
```
<meta content="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png" property="og:image"/>
```
- 4. url
```
<meta property="og:url" content="https://www.freecodecamp.org" />
```
- more OG properties that you can set, like description, audio, video and locale.
#### audio and video elements tag allow you to add sound and video content to your HTML documents. The audio element supports popular audio formats like mp3, wav, and ogg. The video element supports mp4, ogg, and webm formats.
```
<audio src="https://cdn.freecodecamp.org/curriculum/js-music-player/cruising-for-a-musing.mp3"></audio>
```
- **control attribute** - (boolean attribute) to see the audio player on the page, then you can add the audio element with the controls attribute.
```
<audio src="https://cdn.freecodecamp.org/curriculum/js-music-player/never-not-favored.mp3" controls></audio>
```
- controls attribute enables users to manage audio playback, including pausing or resuming playback.
- **loop attribute** is a boolean attribute that makes the audio replay continuously.
<img width="320" height="120" alt="Screenshot 2026-06-20 183407" src="https://github.com/user-attachments/assets/626e51ab-77be-4ce4-8805-75580569832d" />

