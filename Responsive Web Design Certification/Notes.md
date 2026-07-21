- HTML stands for Hypertext Markup Language, is a markup language for creating web pages. It's the code that defines the structure and content like (paragraphs, headings, links, images, and videos) of a webpage.
```
left angle bracket (<), right angle bracket (>) &  forward slash (/)
<opening tag>content</closing tag>
```
- **Void Element** : Some HTML elements do not have a closing tag. These are known as void elements like img - `image element, input elements`
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
- Semantics are the meaning of words, or phrases, in a language. semantic meaning of a p element, for example, is a paragraph of text.
```
<p>
  Let me tell you about my fantastic holiday in Paris.
  I saw the impressive Eiffel Tower up close!
</p>
```
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
-  **`<footer>` element tag** : is used to define a footer for a document or section in bottom. A footer typically contains information about the author of the document, copyright data, links to terms of use, contact information, and usually contains copyright information
-  
```
<main>
</main>
  <footer>
    <p>Copyright</p> 
  </footer>
</body>
```
#### Non-Semantic elements `<div> <span>`
- **Division Elements`<div>`** is used as a container to group other elements. When grouping related content for styling purposes CSS.
```
<div>
  <p>Example paragraph element.</p>
</div>
```
- **`<span>` element** is a generic inline container used to group phrasing content for styling or scripting purposes
```
<head>
    <title>my web page</title>
    <style type="text/css">
        span {
            color: green;
            font-size: 40px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div>
        <span>GeeksForGeeks</span> <br>
        A computer science portal for geeks
    </div>
</body>
```
- **`<section> & <p>`** has semantic meaning over the **`<div>`** which is not semantic.
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
- **class attribute** value does not need to be unique and can contain spaces and to group elements for styling and behavior.
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

```
<audio
  src="https://cdn.freecodecamp.org/curriculum/js-music-player/can't-stay-down.mp3"
  loop
  controls
></audio>
```
- **muted attribute** : boolean attribute will start the audio in a muted state.
- **source elements** : browser will select the first source that it understands.
```
<audio controls>
  <source src="audio.ogg" type="audio/ogg" />
  <source src="audio.wav" type="audio/wav" />
  <source src="audio.mp3" type="audio/mpeg" />
</audio>
```
- video elements tag
- **autoplay attribute** to the opening video tag so the video plays automatically.
- **width attribute** is being used here to make the video smaller and fit better in the preview window.
```
<video
  src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.mp4"
  loop
  controls
  muted
  width="400"
></video>
```
- **poster attribute** : you wanted to display an image while the video is downloading.
```
<video
  src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.mp4"
  loop
  controls
  muted
  poster="https://peach.blender.org/wp-content/uploads/title_anouncement.jpg?x11217"
  width="400"
></video>
```
- source element inside a video element, just like you did with the audio element, the same video in multiple formats.
```
<video
  controls
  width="400"
  poster="https://peach.blender.org/wp-content/uploads/title_anouncement.jpg?x11217"
>
  <source
    src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.mp4"
    type="video/mp4"
  />
  <source
    src="https://archive.org/download/BigBuckBunny_124/Content/big_buck_bunny_720p_surround.webm"
    type="video/webm"
  />
  Your browser does not support the video tag.
</video>
```
- Common image formats like PNG(**lossless quality**)  and JPG(**loss quality**) are classified as **raster formats**.
- **Scalable Vector Graphic(SVG) no-loss quality** a vector graphic tracks data (store in XML) based on paths and equations to plot points, lines, and curves can be scaled to any size without impacting the quality.
```
<svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="45" stroke="black" stroke-width="4" fill="green" />
  <circle cx="35" cy="40" r="5" fill="black" />
  <circle cx="65" cy="40" r="5" fill="black" />
  <path d="M35 65 Q50 80 65 65" stroke="black" stroke-width="4" fill="transparent" />
</svg>
```
<img width="106" height="108" alt="Screenshot 2026-06-21 171152" src="https://github.com/user-attachments/assets/ea6e45f8-2d2d-4aac-8fd4-f73a5fc93b7c" />

- sites like Pixabay and Unsplash, which offer free-to-use images, Creative Commons 0 license are considered public domain and permissive license, like a Creative Commons license, or the BSD license.
- **svg element tag** is the container for the whole drawing. It sets up the space where all the shapes appear. width and height attributes.
- **viewBox attribute** controls what part of the image is visible inside the SVG
- **circle element tag** is used to make the face and the eyes. One large circle forms the yellow face, and two smaller circles make the eyes.
- **path element tag** is used to draw the smile. It creates a curved line for the mouth.
- update the value for the **fill attribute tag** to any named color like red, green, blue, yellow, etc.
<img width="172" height="63" alt="Screenshot 2026-06-21 171607" src="https://github.com/user-attachments/assets/480e5748-8fd7-46f6-ab94-0235db30b7b4" />

- **replaced element** is an element whose content is determined by an external resource rather than by CSS itself like <img>, <video>, <iframe> & <input type="image">
- The layout or positioning style in a replaced element.
- **<input type="image">**: a graphical submit button for web forms.
```
<img src="example-img-url" alt="Descriptive text goes here">
```
- **Inline Frame <iframe>**: Embed external content, such as videos, maps, or other web pages, directly into a parent webpage.
```
<iframe width="400" height="200" src="https://www.youtube.com/embed/u43gJJrVa1I?si=BoDW_puFsy8OEr_Z" title="Professional Cloud Architect Certification Course – Pass the Exam! (YouTube video)" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
```
```
<iframe
  title="Map of the Royal Observatory, Greenwich, London"
  width="300"
  height="200"
  src="https://www.openstreetmap.org/export/embed.html?bbox=-0.004017949104309083%2C51.47612752641776%2C0.00030577182769775396%2C51.478569861898606&amp;layer=mapnik">
</iframe>
```
```
<input type="image" alt="Descriptive text goes here" src="example-img-url">
```
- **Not Replaced Elements** : input types like text, or email.
- **cascading stylesheets CSS**, is used to add styles to a web page. Common examples of replaced elements include the image, iframe, and video elements.
- **allowfullscreen attribute** allows the user to display the iframe in full screen mode.
- **allow attribute** lets you define what an iframe can or can't do. This is called an allowlist.
- **clipboard-write value** to it allows the embedded page to write items to your clipboard
- **accelerometer** use motion sensors so it can detect things like device tilting and rotation
```
<iframe
  width="400"
  height="400"
  src="https://www.youtube.com/embed/PkZNo7MFNFg?si=-UBVIUNM3csdeiWF"
  title="Learn JavaScript - Full Course for Beginners (YouTube video)"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  referrerpolicy="strict-origin-when-cross-origin"
  allowfullscreen
></iframe>
```
```
<h1>A Map from Openstreetmap.org Embedded with the iframe Element</h1>

<iframe
  width="425"
  height="350"
  src="https://www.openstreetmap.org/export/embed.html?bbox=3.006134033203125%2C6.150112578753815%2C3.6357879638671875%2C6.749850810550778&amp;layer=mapnik"
  title="Map of Lagos area, Nigeria"
  style="border: 1px solid black"
>
</iframe>
<br />
<small>
  <a href="https://www.openstreetmap.org/#map=11/6.4501/3.3210">
    View Larger Map
  </a>
</small>
```
- **srcdoc attribute** location want to embed direct HTML.
- Anchor Target Attribute Types:-
1. _self, which is the default value. This opens the link in the current browsing context. In most cases, this will be the current tab or window.
2.  _blank, which opens the link in a new browsing context. Typically, this will open in a new tab. But some users might configure their browsers to open a new window instead.
3.  _parent, which opens the link in the parent of the current context. For example, if your website has an iframe, a _parent value in that iframe would open in your website's tab/window, not in the embedded frame.
4.  _top, which opens the link in the top-most browsing context - think "the parent of the parent". This is similar to _parent, but the link will always open in the full browser tab/window, even for nested embedded frames.
- four important possible values for this attribute
5.  _unfencedTop, which is currently used for the experimental FencedFrame API. At the time of this lesson, you probably won't have a reason to use this one yet.
- Anchor path(src) types:
1. absolute path is a complete link to a resource. It starts from the root directory, includes every other directory, and finally the filename and extension.
- link to a resource available only on the internet
```
<p>
  Read more on the
  <a
    href="/Users/user/Desktop/fCC/script-code/absolute-vs-relative-paths/pages/about.html"
OR
    href-"file:///Users/user/Desktop/fCC/script-code/absolute-vs-relative-paths/pages/about.html"
    >About Page</a
    >
</p>
```
- if the resource is on the web protocol - which could be http, https, and file and the domain name.
```
<a href="https://design-style-guide.freecodecamp.org/img/fcc_secondary_small.svg">
  View fCC Logo
</a>
```
2. relative path specifies the location of a file relative to the directory of the current file. It does not include the protocol or the domain name
-  to ensure links work without an internet connection
```
<p>
  Read more on the
  <a href="about.html">About Page</a>
</p>
```
- **"/"** slash is known as the "path separator", single dot points to the current directory and two dots point to the parent directory.
- Different Link States
1. **:link** : This state represents a link which the user has not visited, clicked, or interacted with yet.
```
<a href="https://freecodecamp.org" target="_blank">Visit freeCodeCamp</a>

# style.css
a:active {
  color: black;
}
```
<img width="185" height="50" alt="Screenshot 2026-06-24 144137" src="https://github.com/user-attachments/assets/9ed5359d-133c-446e-aa75-f9f93eb61ecd" />


2. **:visited** : which applies when a user has already visited the page being linked to. By default, this turns the link purple.
```
<head>
    <link href="styles.css" rel="stylesheet" />
</head>

<body>
    <a href="https://freecodecamp.org" target="_blank">Visit freeCodeCamp</a>
</body>

# style.css
a:visited {
  color: brown;
}
```
<img width="196" height="50" alt="Screenshot 2026-06-24 143559" src="https://github.com/user-attachments/assets/a3906ac3-116e-42f5-bd0b-4dc5a9731b88" />
<img width="185" height="56" alt="Screenshot 2026-06-24 143525" src="https://github.com/user-attachments/assets/eed46387-a160-4b6f-9548-c5d2448002bd" />

3. **:hover** : This state applies when a user is hovering their cursor over a link.
```
<head>
    <link href="styles.css" rel="stylesheet" />
</head>

<body>
    <a href="https://freecodecamp.org" target="_blank">Visit freeCodeCamp</a>
</body>

# style.css
a:hover {
  color: red;
}
```


4. **:focus** : This state applies when we focus on a link.
```
<head>
    <link href="styles.css" rel="stylesheet" />
</head>

<body>
    <a href="https://freecodecamp.org" target="_blank">Visit freeCodeCamp</a>
</body>

# style.css
a:focus {
  color: green;
}
```
<img width="187" height="53" alt="Screenshot 2026-06-24 144042" src="https://github.com/user-attachments/assets/34216c37-56f3-471d-ac47-738a00777f55" />


5. **:active** : This state applies to links that are being activated by the user.
```
<head>
    <link href="styles.css" rel="stylesheet" />
</head>

<body>
    <a href="https://freecodecamp.org" target="_blank">Visit freeCodeCamp</a>
</body>

# style.css
a:active {
  color: black;
}
```
<img width="183" height="58" alt="Screenshot 2026-06-24 144110" src="https://github.com/user-attachments/assets/8498d76e-5039-4f6a-8809-30041fd2472e" />

### Presentational HTML `<b> <i> <em> <s> <strike> <s> <del> <center> <font> <big> <small> <tt>`
- focuses on the appearance and style of the content. In the early days of HTML, developers would use elements like the center, big, and font elements.
- modern web development you shouldn't use these types of elements, because of their limitations and negative impact on accessibility and maintainability.
#### deprecated element
- **`<font>` element** is a deprecated element used to set the font size and color of the text.
```
<font size="5" color="blue">This text is blue and large.</font>
```
- **`<center>` element** is another deprecated element that is used to center the content horizontally within its container.
```
<center>
  This text is centered.
  <p>HTML is awesome.</p>
</center>

<p>Another example text.</p>
```
- **`<big>` element** is another deprecated presentational HTML element that makes the enclosed text one level bigger than its surrounding text.
```
<p>
  This text has a normal font size.
  <big>This text is larger.</big>
  Some other text.
</p>
```
### Semantic HTML `<strong> <article> <figure> <figcaption> <main> <nav> <section> <footer> <header> <form>`
- It is now the recommended practice. It describes the content of the elements, so it's much easier to read, understand, and maintain.
- **`<nav>` navigation section element** represents a section of a webpage designed specifically to hold major navigation links.
```
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
  </ul>
</nav>
```
- **`<article>` element** represents a self-contained, independent composition within a document, page, or site that is intended to be independently distributable or reusable.
```
<article>
  <h2>Understanding Semantic HTML</h2>
  <p>Semantic tags help search engines and screen readers understand page structure.</p>
</article>
```
- `<article>` Reusable, self-contained units of content.
- `<section>` Theme-based grouping of related content.
- `<div>` Purely a layout container for CSS styling.
- **`<header>` element** is used to represent introductory content like page navigation and other introductory information
- **idiomatic text element `<i>`** was originally used for presentational purposes to display the text in italics.
```
<p>There is a certain <i lang="fr">je ne sais quoi</i> in the air.</p>
```
#### emphasis element
```
<p>
  Never give up on <em>your</em> dreams.
</p>
```
- Use CSS instead of the i or em elements -> When you want to display text in italics for presentational purposes only.
- primary difference between i and em -> There is no difference; they both emphasize text.
i indicates that the text differs from the surrounding content, while em emphasizes important text.
- **bring attention to element `<b>`** is commonly used to highlight keywords in summaries, or product names in reviews.
```
<p>
  We tested several products, including the <b>SuperSound 3000</b> for audio
  quality, the <b>QuickCharge Pro</b> for fast charging, and the
  <b>EcoClean Vacuum</b> for cleaning. The first two performed well, but the
  <b>EcoClean Vacuum</b> did not meet expectations.
</p>
```
- To emphasize the importance of the text, you should use the strong element instead of the b element.
- **3  description lists**
- **description list element `<dl>`** is the container for the entire list. You can see it wraps around all the other elements of the description list in the example.
- **description term element `<dt>`** to specify a term in description list.
- **description details element `<dd>`** for the description, or details associated with that term in description list.
```
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
  <!-- <dt>JS</dt>
  <dd>JavaScript</dd> -->
</dl>
```
-  use cases for description lists include product specifications, frequently asked questions, contact information, and metadata.
-  **block quotation element `<blockquote>`** are used to distinguish quoted text from the surrounding content. This gives the quoted text a format that is easy to identify.
-  **cite attribute** : URL address of quote source.
```
<blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">
  <p>Build your projects. Show them to your friends. Build projects for your friends.</p>
</blockquote>
```
<img width="312" height="78" alt="Screenshot 2026-06-27 144943" src="https://github.com/user-attachments/assets/eddd5db3-eca7-450b-8dd7-5f603b9dc810" />

- **citation element `<cite>`** is an HTML element that you can use to mark up the title of a referenced creative work like a book article, song, film, website, or research paper.
- **`<q>` tag** defines a short, inline quotation vs **`<blockquote>` tag** block quotes for extended quotations from other sources
```
<p>As Quincy Larson said,
  <q cite="https://www.freecodecamp.org/news/learn-to-code-book/">Momentum is everything.</q></p>
```
<img width="350" height="80" alt="Screenshot 2026-06-27 150522" src="https://github.com/user-attachments/assets/2317900f-bd37-4516-8399-3d9bf62f8d05" />

- An acronym is a word formed from the initial letters of a phrase, with each letter representing the first letter of a word in that phrase.
- initialism is formed from the initial letters of a phrase, with each letter representing the first letter of a word in that phrase.
```
<p><abbr title="HyperText Markup Language">HTML</abbr> is the foundation of the web.</p>
```
- **contact `<address>` element** is used to represent contact information for a section on a web page.
- **line break element `<br>`** is used to show the division between the text.
- **href value = tel:+ value** creates a clickable link to initiate a telephone numbers & **href value = mailto link** are used in HTML documents to allow users to open a new email & users often perceive it as spam.
```
<address>
  <h2>Company Name</h2>
  <p>
    1234 Elm Street<br />
    Springfield, IL 62701<br />
    United States
  </p>
  <p>Phone: <a href="tel:+15555555555">+1 (555) 555-5555</a></p>
  <p>Email: <a href="mailto:contact@company.com">contact@company.com</a></p>
</address>
```
- **`<time>` element** is used to represent a specific moment in time. `YYYY-MM-DDTHH:MM:SS`
- **datetime attribute** is used to translate dates and times into a machine-readable format.
- **capital T** in the value is a separator between the date and time.
```
<p>
  The graduation will be on <time datetime="2024-06-15T15:00">June 15</time>
</p>
```
- `&mdash;` is an HTML entity that represents an em dash —.
- **superscript element `<sub>`** is used to display a piece of text as a superscript is a symbol or letter printed above the normal line of text.
```
<p>2<sup>2</sup> (2 squared) is 4.</p>
```
<img width="167" height="48" alt="Screenshot 2026-06-27 161618" src="https://github.com/user-attachments/assets/ec0a8fb5-f554-4624-960f-16f7859fb9f4" />

- **subscript element `<sub>`** uses a subscript which displays a lowered baseline using smaller text.
```
<p>CO<sub>2</sub></p>
```
<img width="50" height="39" alt="Screenshot 2026-06-27 161827" src="https://github.com/user-attachments/assets/caf8ba6a-1969-4b71-b530-3450facdc8b7" />

- **inline `<code>` element** is used to represent short snippets of code inside text.
```
<p>
  To set the text color to blue in CSS, use the following code:
  <code>color: blue;</code>
</p>
```
<img width="368" height="58" alt="Screenshot 2026-06-27 162335" src="https://github.com/user-attachments/assets/ff66c4fc-7da4-437d-8539-071b174cf8b8" />


- **`<pre>` element** you will need to be mindful of spacing.
```
<pre>
  <code>
    body {
      color: red;
    }
  </code>
</pre>
```
<img width="213" height="96" alt="Screenshot 2026-06-27 162342" src="https://github.com/user-attachments/assets/cec182cd-6826-4dcf-9204-a6067252a36c" />

- **unarticulated annotation element `<u>`**` for short, is used to represent inline text that has non-textual annotation applied.
```
<p>
  You can use the unarticulated annotation element to highlight
  <u>inccccort</u> <u>spling</u> <u>issses</u>.
</p>
```
- **strikethrough element `<s>`** for short, should be used to represent when text is no longer accurate or relevant, cancellation of an activity.
```
<p><s>Tomorrow's hike will be meeting at noon.</s></p>
```
- **`<ruby>` element** to show the pronunciation of East Asian characters.
- **`<rp>` ruby fallback parenthesis element** is used as a fallback for browsers lacking support for displaying ruby annotations.
- **`<rt>` ruby text element** is used to indicate text for the ruby annotation.
```
<ruby> 明日 <rp>(</rp><rt>Ashita</rt><rp>)</rp> </ruby>
```
- **`<table>` element** with an id set to quickfacts. Inside it, the table has a **table head element `<thead>`**,  **table header `<th>`** **table body element `<tbody>`**, **table foot element `<tfoot>`**,  **table rows `<tr>`** and **table data `<td>`**.
```
<html>
  <body>
    <table>
      <caption>
        Calculus Final Exam Grades
      </caption>

      <thead>     
        <tr>
          <th>Last Name</th>
          <th>First Name</th>
          <th>Grade</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>Davis</td>
          <td>Alex</td>
          <td>54</td>
        </tr>

        <tr>
          <td>Rodriguez</td>
          <td>Marcus</td>
          <td>88</td>
        </tr>
      </tbody>

      <tfoot>
        <tr>
          <td colspan="2">Average Grade</td>
          <td>78.8</td>
        </tr>
      </tfoot>

    </table>
  </body>
</html>
```
- `<form>` element is used to gather user information, such as names and email addresses.
```
<form action="url-goes-here">
  <!-- input elements go here -->
</form>
```
- **action attribute** specifies where the form data will be sent upon submission.
- **`<input>` element** To collect specific information, like names and email addresses.
- input elements are void elements.
- **type attribute** defines the data type expected from the user.
```
<form action="">
  <input type="text" />
</form>
```
- **`<label>` element** To add a label for the input.
```
<form action="">
  <label>
    Full Name:
    <input type="text" />
  </label>
</form>
```
- **implicit association** between the label and the input field.
- **implicit** to something that is understood or inferred without needing to be explicitly stated or defined with additional attributes or elements.
- **for attribute** for an email address label.
```
<form action="">
  <label for="email"> Email Address: </label>
  <input type="email" id="email" />
</form>
```
- **placeholder attribute** show additional hints to the users about the expected input
```
<form action="">
  <label for="email"> Email Address: </label>
  <input type="email" id="email" placeholder="example@email.com" />
</form>
```
- **`<button>` element** : submitting a form, showing a modal, or toggling a side menu open and closed.
- button element is used to perform a particular action when it is activated.
- **type attribute** which controls the behavior of the button.
- **Show Alert button** to see an alert pop up on the screen.
```
<button type="button">Show Alert</button>
<script src="index.js"></script>
```
- **reset button** will clear out all of their input data
```
<form action="">
  <label for="email">Email address:</label>
  <input type="email" id="email" name="email" />
  <button type="reset">Reset form</button>
  <button type="submit">Submit form</button>
</form>
```
- input elements are void elements
```
<input class="start-btn" type="button" value="Start Game" />
<script src="index.js"></script>
```
- **required attribute** specifies that the user needs to fill out that portion of the form before it gets submitted.
<img width="373" height="100" alt="Screenshot 2026-06-29 155245" src="https://github.com/user-attachments/assets/7f8acf57-93c5-411b-acf7-7a6f5261f033" />

<img width="966" height="113" alt="Screenshot 2026-06-29 155434" src="https://github.com/user-attachments/assets/9dbbcf20-70db-4f4a-bac0-aea6dc735ba9" />

- **minlength and maxlength attributes** are used to set the minimum and maximum length in characters for the email input.
- **maxlength attribute** physically stops the user from typing or pasting more than the specified number of characters. e.g. `<input type="text" maxlength="3">`
- **max attribute** defines the maximum allowable value for a field. It does not stop a user from typing more characters, but it will make the form invalid if the value is mathematically too high. e.g. `<input type="number" max="100">`
```
<form action="">
  <label for="email">Email Address (Required field):</label>
  <input
    required
    type="email"
    name="email"
    id="email"
    minlength="4"
    maxlength="64"
  />
  <button type="submit">Submit Form</button>
</form>
```
<img width="381" height="100" alt="Screenshot 2026-06-29 155557" src="https://github.com/user-attachments/assets/1d7aa28c-15d4-434b-bfd9-7013d7ca9062" />

- form controls, like inputs, can be in different stages or conditions like a focused state, readonly state, disabled state or default state.
- **default state** of an email address input is a blank input
- **focused state** : 
<img width="768" height="48" alt="Screenshot 2026-06-30 133319" src="https://github.com/user-attachments/assets/4304f9e3-05c9-4ec4-9ec1-29fcf3249d61" />

- **disabled state** :  input cannot be focused or activated.
<img width="770" height="49" alt="Screenshot 2026-06-30 133434" src="https://github.com/user-attachments/assets/32c590db-e7e1-4d20-921c-9f13dff18eaa" />

- **readonly state** : form control, like an input, is not editable by the user
<img width="764" height="146" alt="Screenshot 2026-06-30 133731" src="https://github.com/user-attachments/assets/5762018a-3b81-4b14-8a68-f92973ce0687" />

- difference between the disabled state and readonly state is that readonly can be focused while the disabled state cannot.
- **accessible websites** : the **World Wide Web(www) Consortium, known as W3C**, developed a set of international standards **Web Content Accessibility Guidelines (WCAG)**  are a set of guidelines for making web content more accessible and easier to use for people with disabilities.
- **https : HyperText Transfer Protocol Secure**.
- **POUR** : four core  principles in mind.
- P stands for **Perceivable**. Users must be able to perceive the information that you are presenting. For example, you can provide alternative text for images, so users who access your website with a screen reader can understand them.
- O stands for **Operable**. Users must be able to interact with the user interface. For example, you can make sure that all functionality is accessible through the keyboard too, not just the mouse.
- U stands for **Understandable**. Users must be able to understand the information. For example, you can avoid complex sentences and use simple language as much as possible.
- R stands for **Robust**. A wide range of browsers and other tools, including assistive technologies, must be able to interpret the content.
- **Screen readers** are assistive technology programs that help blind and visually impaired people use computers and mobile devices. Software programs that read the content of a computer screen out loud
- **text-to-speech** is just one of the features of a screen reader
- notable features of screen readers are navigation aids and web browsing assistance.
- macOS, iPhones and iOS both have **VoiceOver** built-in.
- Windows computers have **Narrator built-in**. NonVisual Desktop Access (NVDA) and Job Access With Speech (JAWS) are also available for Windows computers. NVDA is free and open-source, while JAWS is paid.
- Linux has **Orca** for the desktop environment and **Speakup** for the Linux terminal. Android phones have **TalkBack** built-in and **Ella** is an Gen AI-powered platform.
- Large text and braille keyboards are designed for users with visual disabilities. In Large Text Keyboards, also called Large Print Keyboards, the letters, numbers, and symbols are larger compared to standard keyboards. This design is helpful for people who may find smaller text in the keys difficult to see. Most of them also have enhanced contrast and brightness.
- **large print keyboard** made by the brand MaxiAids has yellow keys with black, big, and bold letters, numbers, and symbols on them. This is helpful for people with low vision.
- black large print keyboard with white print on the keys. This keyboard is also backlit, so users can adjust its brightness to different lighting conditions.
- **Braille** is a tactile reading and writing system. It consists of raised dots arranged in specific patterns to represent letters, numbers, and punctuation feeling these patterns with their fingers.
- Large text and braille keyboards are tools that empower people with visual disabilities.
- A **trackball** is a stationary pointing device that consists of a large, movable ball within a socket. It also includes additional buttons for clicking and performing other functions.
- A **joystick** is a pointing device primarily designed for games and certain industrial applications like machinery control. arthritis and carpal tunnel syndrome. It consists of a lever that pivots up, down, left, and right, and often includes additional buttons for various actions.
- A **touchpad** is a flat, touch-sensitive device built into laptops and some keyboards. It allows users to control the cursor on the screen by sliding their fingers across its surface. arthritis and joint pain.
- **Screen magnifiers** are tools that help people with low vision and other visual impairments better access digital content and the web enlarge the display by more than 200%.
- - software developers need to make their digital products accessible to people with low vision.
- - ZoomText for Windows.
- - ClaroView for both macOS and Windows.
- - iZoom for Windows.
- - Zoomify - Screen Magnifier for macOS.
- - LunarPlus for Windows.
- - Loupe for macOS.
- **Voice recognitio**n software helps people with disabilities interact with computers and other digital devices.
- voice recognition tools let people with disabilities use their voice to pass commands to perform various tasks instead of using traditional input devices like keyboards and mice. This includes writing emails and other documents, surfing the net, and controlling smart home devices.
- People with visual impairments, including those with low-vision or blindness.
- Individuals with mobility impairments, such as limited use of hands and arms or conditions like arthritis and carpal tunnel syndrome.
- Those recovering from hand or arm injuries.
- benefit from voice recognition software : People with low leg movement
- Individuals with cognitive disorders, like memory issues or attention deficit disorders.
- Elderly individuals who might find it easier to use voice commands.
- Voice Control for macOS/iOS.
- Voice Access for Android.
- Windows Speech Recognition for Windows (Voice Access).
- Dragon by Nuance for Windows.
- **Accessibility Auditing Tool** evaluates how accessible your digital content by reporting accessibility issues that can be easily found through automated testing. This content includes websites, web applications, and mobile apps.
- **IBM Equal Access Accessibility Checker** can be used as a Chrome extension, Firefox add-on, or NPM package.
- **Google Lighthouse** is a popular web metric checker you can use directly within Chrome DevTools or online.
- Limitation of using the web version of the tool on **Google Lighthouse** cannot test local websites.
- **WAVE** is another reliable accessibility checker you can use as a Chrome extension or on the web. accessibility report will be generated for you.
- proper heading structure help those using screen readers allows screen readers to navigate and skip to different sections easily.
- headings properly for users who rely on keyboards lets users jump between sections without the need to tab through every link.
- best practices for headings on a web page Using clear and descriptive texts that summarize the following content.
- `<th scope="row|col">`**scope attribute** determines if a header is a row header or a column header. Screen readers may guess this correctly from the table's structure, but it's usually recommended to explicitly indicate the scope to ensure clarity.
```
<table>
  <caption>Our Pets</caption>
  <thead>
    <tr>
      <!-- Now they have scope -->
      <th scope="col">Name</th>
      <th scope="col">Age</th>
      <th scope="col">Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Nora</th>
      <td>5</td>
      <td>Dog</td>
    </tr>
    <tr>
      <th scope="row">Gino</th>
      <td>2</td>
      <td>Cat</td>
    </tr>
  </tbody>
</table>
```
- associate a label's for attribute == the input's id attribute.
- **WAI-ARIA** stands for **Web Accessibility Initiative - Accessible Rich Internet Applications**. It's a specification that enhances accessibility for dynamic content and UI (User Interface) components.
- **WAI-ARIA attributes** : To provide additional semantic information for accessibility.

- ARIA properties provide additional details about elements.
```
<h2 id="header-id">About freeCodeCamp</h2>
<button id="button-id" aria-labelledby="header-id button-id">Learn More</button>
```
#### Roles `<div role=:""></div>` 6 categories of ARIA roles:
- **Document structure roles** : article cell document figure group heading img list row table. standard WAI-ARIA roles used in web development to define how elements and widget are announced by screen readers.
- - **Toolbar**: Groups a collection of common controls (such as buttons or checkboxes) into a compact visual form, allowing screen reader users to understand.
- - **Tooltip**: A contextual popup or text bubble that appears when an element is hovered over or focused.
- - **Feed**: A dynamic, scrollable list of articles or content that updates continuously as the user scrolls, allowing screen readers to browse naturally.
- - **Math**: Used for marking up mathematical expressions and formulas so they are properly read by accessibility tools and browsers.
- - **Presentation / None**: They are useful for purely decorative images or layouts (like tables) that screen readers don't convey semantic meaning.
- - **Note**: Identifies a parenthetic or auxiliary section of content that stands out from the main flow, such as an editorial note, warning, or highlight box.
- **Widget roles** `<div role="searchbox">` define the purpose and functionality of interactive elements, like **scrollbar, searchbox, separator (when focusable), slider, spinbutton, switch, tab, tabpanel, and treeitem**.
- **Landmark roles** `<div role="banner">` are **banner, complementary, contentinfo, form, main, navigation, region, and search**. Each of these roles has a corresponding **semantic HTML equivalent, such as header, footer, aside, form, main, nav, section, and search**. `<aside>` element defines content that is tangentially or indirectly related to the main content. `<search>` element tag is used to specify that here comes a set of elements that is related to search.
- **Live region roles** include: **alert, log, marquee, status, and timer** define elements with content that will change dynamically.
- **Window roles** define sub-windows, like **pop-up modal dialogs**. These roles include **alertdialog and dialog**
- **Abstract roles** are only intended for use by browsers to help organize and streamline a document. They should not be used by developers on websites or web applications like **command, composite, input, landmark, range, roletype, section, sectionhead, select, structure, widget, and window.**

```
# index.html
<link rel="stylesheet" href="styles.css">

<div role="math" aria-label="x squared + y squared = 3">
  x<sup>2</sup> + y<sup>2</sup> = 3
</div>

# style.css
.math-expression {
  font-family: "Times New Roman", serif;
  font-size: 1.2rem;
  background-color: #f4f4f4;
  border-left: 4px solid #007acc;
  padding: 0.75em 1em;
  margin-top: 1em;
  display: inline-block;
}

.math-expression sup {
  font-size: 0.8em;
}
```
<img width="110" height="48" alt="image" src="https://github.com/user-attachments/assets/3890ae81-be22-4ed3-b29c-0c10949ad96f" />

#### Roles of the aria-label and aria-labelledby Attributes
-  **aria-label** attribute is an invisible label for interactive elements. It adds a text label to an element that screen readers can read.
```
<button aria-label="Search">
  <i class="fa-solid fa-magnifying-glass"></i>
</button>
```
- **aria-labelledby** attribute use a reference to text that already exists on the page and does the exact same thing as the aria-label attribute, but not directly.
```
<input type="text" aria-labelledby="search-btn">
<button type="button" id="search-btn">Search</button>
```
#### advantage of aria-labelledby
-  is change the button text to Find, the label for the input will automatically be updated to the new text since it is referencing the button text.
-  aria-labelledby can make it much easier to programmatically create complex invisible labels consisting of multiple sources of text.
- Combining multiple id values into a single aria-labelledby attribute value is also possible.
```
<div>
  <span id="volume-label">Volume</span>
  <span id="volume-details">Adjust the volume level</span>
  <input
    type="range"
    min="0"
    max="100"
    value="30"
    aria-labelledby="volume-label volume-details">
</div>
```
- **aria-hidden attribute** is used to hide elements from people who use assistive technology, such as screen reader users.

<img width="1015" height="249" alt="image" src="https://github.com/user-attachments/assets/5cb46b10-aad1-44b1-a1a1-d71bd25fe301" />

- **aria-describedby attribute** is used to provide additional information about an element to screen reader users by referencing existing content on the page.
<img width="872" height="112" alt="image" src="https://github.com/user-attachments/assets/032a25a9-9fa3-4bb1-af07-e7128f1b6f50" />

- **alt attribute text** is a essential information about the image for users who cannot see it, such as people who use screen readers and assistive technologies.
```
<a href="about.html">
  <img src="arrow-right.png" alt="Go to next page." />
</a>
```

- best practice for **writing link texts**  > Make links visually distinct with underlining and other visual cues.
- **Good Link** > It helps users know where they're headed and what they'll access.
```
<a href="/link-to-topic">
   Learn more about our accessibility efforts
</a>
```

- **Audio and Video Content Accessible**  is not just about visuals but also audio, so the first thing you should consider doing is adding **Captions** provide the text version of spoken words or **Subtitles** are essential for people who don't understand the language you're speaking by screen readers. This helps not only people who are deaf or hard of hearing but also those watching videos in noisy or quiet environments.
- By using the **`<track>` tag** inside the **`<video>` tag** or **`<audio>` tag element**.
```
<video
  width="400"
  height="300"
  controls
  src="https://cdn.freecodecamp.org/curriculum/labs/what-is-the-map-method-and-how-does-it-work.mp4"
>
  <track
    src="captions.vtt"
    kind="captions"
    srclang="en"
    label="English"
  />
</video>

<audio controls src="sample.mp3">
  <track
    src="captions.vtt"
    kind="captions"
    srclang="en"
    label="English"
  />
</audio>
```
<img width="324" height="200" alt="image" src="https://github.com/user-attachments/assets/09b046dc-f8b2-4b1f-a645-a403e278c7bd" />

- **kind attribute** is used to tell the track element how it should be used. Valid values for the kind attribute include **captions, subtitles, chapters, and metadata**.
- **srclang attribute** represents the language for the track content.
- **label attribute** is a descriptive title for the text track
- **Transcripts** are useful for deaf people and those hard of hearing. They're also beneficial for people who prefer reading instead of watching or listening. Transcripts also make your content searchable, allowing users to quickly find specific parts of your audio or video
<img width="960" height="272" alt="image" src="https://github.com/user-attachments/assets/3ddae022-e12f-4a0d-9666-1a79b6e388a8" />

- **tabindex attribute** want to adjust which elements are focusable or change their focus order.
```
<element tabindex="number">Element Text</element>
```
- The value of tabindex determines how the element behaves in keyboard navigation:
- tabindex="0" adds the element to the natural tab order.
<img width="894" height="81" alt="image" src="https://github.com/user-attachments/assets/7a59946d-dacc-4378-aa46-666765dd0553" />

- **`tabindex="-1"`** makes an element focusable programmatically. This is useful for managing focus in elements that are not normally focusable, such as headings, containers, dialogs, or error messages:
<img width="871" height="96" alt="image" src="https://github.com/user-attachments/assets/2b6cbdca-536e-4bd2-8633-dfe92c9b09f5" />

-  tabbing will focus the input with **tabindex="1"** first, then 2, then 3, regardless of their order in the HTML.
```
<input tabindex="2">
<input tabindex="1">
<input tabindex="3">
```
- **accesskey** is another attribute you can use to make your web project keyboard accessible. It allows you to define a key that focuses on or activates a particular element.
- **accesskey="s"** assigns the key S to the Save button. On most browsers, pressing ALT + S (on Windows) will activate this button.
- **accesskey="c"** sets the key C to the Cancel button, allowing users to activate it using ALT + C (Windows).
- **accesskey="h"** assigns the key H to the Home link, allowing users to navigate to the homepage using ALT + H (Windows).
<img width="741" height="60" alt="image" src="https://github.com/user-attachments/assets/3da5cbab-d8c9-45d7-9bc9-dc09e56acd6d" />

- keyboard accessible in your apps is to make sure you provide clear **focus indicators**.
- **outline property** is used to define the outline around the element.
```
#index.html
 
<link href="styles.css" rel="stylesheet">
<button>Example button</button>

# styles.css

button:focus {
  outline: 2px solid #005fcc;        /*solid blue line*/
}
```
<img width="674" height="106" alt="image" src="https://github.com/user-attachments/assets/c83b137c-70bd-492c-a523-4fddd068f4ea" />

### MotherBoards Elements:-
- Sockets & Memory Slots
  -  CPU Socket: brain of the compute
  -  RAM/DIMM Slots: Random Access Memory modules.
- Expansion Slots
  - PCIe Slots: Peripheral Component Interconnect Express slots allow you to add graphics cards,   sound cards, Wi-Fi modules, or high-speed storag.
  - M.2 Slots for installing high-speed solid-state drives (SSDs).
- Power & Storage Connectors
  - Power Connectors
    - 24-pin connector for the main power supply
    - 4/8-pin connector for the CPU.
  - SATA Ports: Connectors used to attach hard disk drives (HDDs) or SATA SSDs.
  - VRMs (Voltage Regulator Modules): Built-in components that manage and deliver clean, stable power to the CPU.
- Back Panel I/O (Input/Output)
  - USB Ports: Used to connect mice, keyboards, and external drives.
  - Audio Jacks: For speakers, microphones, and headphones.
  - Video Ports: HDMI or DisplayPort for monitors.
  - Ethernet Port: For plugging in a wired internet cable.
- Other Important Built-in Components
  - Chipset: Integrated chips (like the Northbridge/Southbridge) that dictate communication between the CPU, RAM, and other devices.
  - BIOS/UEFI Chip: A small chip containing firmware that initializes your hardware when you boot up the computer.
  - CMOS Battery: A small coin-shaped battery that saves your BIOS settings (like the date/time) when the PC is turned off.
  - Fan Headers: Pins that allow you to plug in and power cooling fans

### Key Component of a Computer
- 1\. **Motherboard** holds all the memory and connectors that are needed to run the computer. It serves as the **main circuit board** for the computer.
- 2\. **CPU: Central Processing Unit** (brain of the computer) is a processor that is responsible for executing instructions and performing calculations.
- CPU processor speed is measured in gigahertz (GHz) and mega-hertz (MHz). Gigahertz is a billion cycles per second and mega-hertz is a million cycles per second. 
- 3\. **Short Term Memory: RAM (Random Access Memory)** is a temporary storage location for the computer's CPU. Anytime the computer needs to access data quickly, it will use RAM.
- The more RAM you have on your computer, the faster it will run and the more programs you can run at the same time. If you are running low on RAM, your computer will run slower and you will notice the difference in performance.
- RAM is volatile memory. This means that it is lost when the computer is turned off. This is why it is important to save your work on your computer.
- 4\. **Hard Disk Drive (HDD)** is a permanent storage location that is used to store data even when the computer is turned off. This is where all your files and software are stored.
- The hard drive is made up of a spinning platter and an arm. The platter is where the data is stored and the arm is used to read and write data to the platter. When you have a faster hard drive, your computer will boot up faster and your programs will run faster.
- 5\. **Solid State Drive (SSD)** is non volatile flash memory and can be used in place of a hard drive. SSDs are faster and smaller than hard drives but hard drives are cheaper and have more storage capacity.
- 6\. **Power Supply Unit (PSU)** is responsible for converting the electricity from the wall outlet into a form that the computer can use. It sends the power from the outlet to the motherboard, CPU, and other components of the computer.
- 7\. **Expansion Cards** are inserted into the motherboard to add additional functionality to the computer. Examples of expansion cards would be the video card, sound card, and network card.
- video card, also known as the Graphics Processing Unit or GPU, is responsible for rendering visuals on the computer screen.
- sound card is responsible for playing sound on the computer speakers.
- network card is responsible for connecting the computer to the internet.
#### 3 different Types of ISP
- 1st tier are the giant conglomerate companies, which have the infrastructure to handle most (if not all) of their network traffic independently.
- 2nd tier are the country-wide providers, which sometimes rent access to tier 1 networks but can stand fairly well on their own.
- 3rd tier are the small companies that primarily focus on providing internet to local markets, and rely on larger ISPs to provide their infrastructure.
- **Different Connections Types of Internet Service Providers**: An Internet Service Provider (ISP) is a company that provides access to the internet. There are different types of connection **ISPs, including dial-up, DSL, cable, fiber-optic, and satellite**.
  - **Fibre optic connections** rely on glass or plastic fibres to transmit data via light, resulting in very high connection speeds and data exchange.
  - **Cable connections** use the same infrastructure as a cable television provider, which often makes them readily available in many regions.
  - **DSL connections** use the infrastructure that landline phone services use.
  - DSL is available in areas is slower option where cable might not be.
  - **Dial-up** also uses the phone lines, but requires exclusive connection to the internet.
  - **Satellite connections** use an array of satellites orbiting the earth to connect various devices across the world.
-  use a combination of letters, numbers and special characters to make it more secure using a strong password, enabling (2FA)two-factor authentication an extra layer of security and requires a second form of verification of authorized user, and using a password manager.
-  developers go for computers with fast processing power to handle resource-intensive tasks.
- **Integrated Development Environment (IDE)**: a tool that helps developers write, test, and debug code in an efficient manner.
- **IDEs like Visual Studio, IntelliJ IDEA, JetBrains, and PyCharm** provide powerful features like code completion, debugging, and integrated terminal support.
- **Code Editor**: a tool that developers use to write and debug code. Visual Studio Code (VS Code), Sublime Text, Atom, Notepad++, and Brackets. is essentially a code editor
- **Git**: a popular version control system that allows developers to track changes in their code and collaborate with others.
- **Cloud-based Hosting Services for repositories** is a storage location for project files and version history. Popular cloud-based hosting services for repositories include **GitHub, GitLab, and Bitbucket**.
- **Package Managers**: tools that help developers simplify the process of adding, updating, and removing libraries and project dependencies. Examples include **npm, pip, yarn, pnpm for javascript and Maven**.
- **Testing Libraries and Frameworks**: Testing is done in software to ensure that the code works as expected. Examples of testing libraries and frameworks include **Jest, PHPUnit, and JUnit**.
- developers test their code to ensure it works as intended by **Testing frameworks**.
- **root directory**: top-level directory in a file system. Directory is another name for a folder.
- **Markdown(.md extension)**: a markup language which is a **lightweight markup language** that is commonly used for documentation and README files.
  - README file is a file that contains information about a project, such as how to install and use it.
- **index.html**: represents the default page that is displayed when a user visits a website.
```
.
├── /assets
│   ├── /images
│   │   ├── logo.png
│   │   ├── banner.jpg
│   │   └── icons.svg
│   ├── /fonts
│   │   ├── custom-font.woff
│   │   └── custom-font.woff2
├── /css
│   ├── main.css
│   ├── about.css
│   └── contact.css
├── index.html
├── about.html
├── contact.html
└── README.md
```
- **Explorer** is the file manager in Windows
- **Finder** is the file manager in macOS.
- HTML, CSS, and JS File Types: **.html file extension** is used for HTML files, **.css** for CSS files, and **.js** for JavaScript files.
- **SideBar** is a vertical panel displayed on the left or right edge of a window screen
-  **TaskBar** is a horizontal bar typically located at the bottom of a Windows computer screen, where you can search for files and folder
- Common Image and Graphic Formats:
  - **JPEG("Joint Photographic Experts Group") and PNG("Portable Network Graphics")** are common image file formats compression scaled losing quality
  - **GIF("Graphics Interchange Format")** is another common image file format that supports animation.
  - **SVG("Scalable Vector Graphics")** is a file format for vector graphics can be scaled as much as needed without losing quality.
- Common Audio and Video Formats:
  - MP3 format is commonly used for audio files.
  - MP4 format is commonly used for video files.
  - MOV format was developed by Apple and is commonly used for video files.
  - WAV, a lossless audio format
- Common Font Formats:
  - **TTF format** is commonly used for TrueType fonts.
  - **WOFF(Web Open Font Format) format** is commonly used for web fonts. The successor to WOFF is WOFF2, which provides better compression.
  - **WebM** a high-quality open-source video format.
- **ZIP**: a file format that is used to compress files and folders.
- **Web browser** is a software application that allows users to access and view websites on the internet.
- **Search Engine** is a tool that allows users to search for information on the internet. Examples include **Google, Bing, and Yahoo**.
- Common web browsers:
  - Google Chrome, Mozilla Firefox, and Microsoft Edge.
- Key features of web browsers include
  - the address bar
  - the rendering engine,
- Browsers also offer bookmarks to save and organize favorite websites, extensions to enhance functionality, and various privacy and security features such as pop-up blockers and private browsing modes.
- Components of websites include
  - the domain name, which is the unique address of the website (like freecodecamp.org)
  - web pages, which are individual documents that make up a website.
- Key aspects of search engines include **web crawlers, also known as spiders or bots**, which are programs that systematically browse the web to discover and index new content.
- **Web browsers** are the tools used to access both websites and search engines.
- **Websites** are the destinations that users visit through browsers or find via search engines.
- **Search engines** help users discover websites by providing organized access to the vast amount of information on the web.
- Common Search Strategies:
  - matched both keywords > query in quotation marks, like "freecodecamp curriculum".
  - match sites that include both of those terms, but not necessarily next to each other as a phrase, each term with a plus symbol like this: +freecodecamp +curriculum.
  - freeCodeCamp's initiatives outside of the curriculum. In this case, you can prefix the term curriculum with a minus symbol like this: +freecodecamp -curriculum.
  - You can use **site:** followed by the URL of a website to search for content on that website.
  ```
  site:freecodecamp.org/news curriculum

  # query would search for Python articles on our news site, excluding articles that might talk about our curriculum.

  site:freecodecamp.org/news +python -curriculum 
  ```
  - You can use **filetype:** followed by a file extension to search for files of that type.
  - You can prefix a search term with a minus sign to exclude results containing that term.
  - You can prefix a search term with a plus sign to include results containing that term.
- risks of gripping the mouse too tightly
  - It can cause hand and wrist issues.
- benefit of using an ergonomic keyboard and mouse
  - They reduce wrist strain by keeping your hands in a more natural position.
- Recommendation for the height of your mouse in relation to your keyboard
  - The mouse should be at the same height as the keyboard.
## Cascading Style Sheets (CSS)
- Cascading Style Sheets (CSS) is a stylesheet language used to apply styles to HTML elements. CSS is used for colors, background images, layouts, and more.
- Primary role of CSS is to separate the content of a web page from its visual presentation. This separation allows web developers to create more flexible and maintainable websites.
- CSS contribute to responsive web design By allowing adjustments to layout and styling based on device screen size.
- you can control the layout, colors, fonts, and overall visual appearance of web pages without altering the HTML structure.
- "cascading" nature of CSS > It allows styles to be inherited and overridden in a hierarchical manner.
- **Basic Anatomy of a CSS Rule**: A CSS rule is made up of two main parts:
  - **a selector and a declaration block**.
  - **A selector** is a pattern used in CSS to identify and target specific HTML elements for styling.
    - **Purpose:** To determine which HTML elements the rule will apply to.
  - **A declaration block** applies a set of styles for a given selector or selectors.
```
selector {
    property: value;
}
```
- **Type of selectors** include
  -  type selectors,
  -  class selectors, and
  -  ID selectors.
- **declaration block** > curly braces provided in the basic syntax
  - applies a set of styles for a given selector, or selectors.
  - Each declaration consists of a property and a value.
    - The property is the CSS identifier that specifies which feature is being styled.
      - An example of a property would be the background-color property.
    - The value would be the specific setting applied to that property.
      - For example, if the property is background-color, a value could be purple, which sets the background color to purple.
- type selector targets all paragraph elements on the page.
```
# index.html

<link rel="stylesheet" href="styles.css">
<h1>Learning about CSS</h1>

<p>Example paragraph element</p>
<p>Another example paragraph element</p>

# styles.css  > Type Selector : Matches HTML tags by their literal name.
p {
  color: blue;
}
```
<img width="284" height="115" alt="image" src="https://github.com/user-attachments/assets/248df72d-81c8-45cb-be30-d8610854e49b" />

- there is a comma followed by a class selector that targets all HTML elements with the class value of subheading. All class selectors must start with a dot .
#### multiple selectors styling:
- All id selectors must start with a hash # symbol and end with comma.
- All class selectors must start with a dot.
```
# index.html

<link rel="stylesheet" href="styles.css">

<h1 id="title">Example heading</h1>
<h2 class="subheading">Example subheading</h2>
<p>This paragraph is not affected by the selector.</p>

# styles.css

#title,    \*  ID Selector (#idName): Targets a solitary element with a unique id attribute.  *\
.subheading {   \*  Class Selector (.className): Selects all elements containing a matching class attribute.  *\
  color: navy;
}
```
<img width="297" height="125" alt="image" src="https://github.com/user-attachments/assets/8945a53d-3214-4e85-bc50-c3dfeb81f905" />

- meta name="viewport" Element: This meta element gives the browser instructions on how to control the page's dimensions and scaling on different devices, particularly on mobile phones and tablets.
- Default Browser Styles: Each HTML element will have default browser styles applied to them. This usually includes items like default margins and paddings.
- **Types of CSS:**
  - **Inline, Internal, and External CSS**
    - **Inline CSS:** These styles are written directly within an HTML element using the style attribute. Most of the time you will not be using inline CSS due to separation of concerns.
    - Here is an example of inline CSS:
    ```
    <link rel="stylesheet" href="styles.css">
    <p style="color: red;">This is a red paragraph.</p>
    ```
    - **Internal CSS:** These styles are written within the <style> tags inside the head section of an HTML document. This can be useful for creating short code examples, but usually you will not need to be using internal CSS.
    - **External CSS:** These styles are written in a separate CSS file and linked to the HTML document using the link element in the head section. For most projects, you will use an external CSS file over internal or inline CSS.
- Working With the width and height Properties
- width Property: This property specifies the width of an element. If you do not specify a width, then the default is set to auto. This lets the browser determine the element's width based on its content, parent, and display type.
- min-width Property: This property specifies the minimum width for an element.
- max-width Property: This property specifies the maximum width for an element.
- height Property: This property specifies the height of an element. Similarly, the height is auto by default, which means it will adjust to the content inside.
- min-height Property: This property specifies the minimum height for an element.
- max-height Property: This property specifies the maximum height for an element.
- **Different Types of CSS Combinators**
  - **Descendant Combinator:** This combinator is used to target elements that are descendants of a specified parent element. The following example will target all li items inside ul elements.
  ```
  <link rel="stylesheet" href="styles.css">
  <ul>
      <li>Example item one</li>
      <li>Example item two</li>
      <li>Example item three</li>
  </ul>
  ul li {
      background-color: yellow;
  }
  ```
  - **Child Combinator (>):** This combinator is used to select elements that are direct children of a specified parent element. The following example will target all p elements that are direct children of the container class.
  ```
  <link rel="stylesheet" href="styles.css">
  <div class="container">
    <p>This will get styled.</p>
  
    <div>
      <p>This will not get styled.</p>
    </div>
  </div>
  .container > p {
    background-color: black;
    color: white;
  }
  ```
  - **Next-sibling Combinator (+):** This combinator selects an element that immediately follows a specified sibling element. The following example will select the paragraph element that immediately follows the h2 element.
  ```
  <link rel="stylesheet" href="styles.css">
  <h2>I am a sub heading</h2>
  
  <p>This paragraph element will get a red background.</p>
  h2 + p {
    background-color: red;
  }
  ```
  - **Subsequent-sibling Combinator (~):** This combinator selects all siblings of a specified element that come after it. The following example will style only the second paragraph element because it is the only one that is a sibling of the ul element and shares the same parent.
  ```
  <link rel="stylesheet" href="styles.css">
  <div class="container">
    <p>This will not get styled.</p>
    <ul>
      <li>Example item one</li>
      <li>Example item two</li>
      <li>Example item three</li>
    </ul>
    <p>This will get styled.</p>
  </div>
  <p>This will not get styled.</p>
  ul ~ p {
    background-color: green;
  }
  ```
- **Inline, Block, and Inline-Block Level Elements**
  - **Inline Level Elements:** Inline elements only take up as much width as they need and do not start on a new line. These elements flow within the content, allowing text and other inline elements to appear alongside them. Common inline elements are span, a, and img elements.
  - **Block Level Elements:** Block-level elements start on a new line and take up the full width available to them by default, stretching across the width of their container. Some common block-level elements are div, p, and section elements.
  - **Inline-Block Level Elements:** You can set an element to inline-block by using the display property. These elements behave like inline elements but can have a width and height set like block-level elements.
- **Margin and Padding**
  - **margin Property:** This property is used to apply space outside the element, between the element's border and the surrounding elements.
  - **padding Property:** This property is used to apply space inside the element, between the content and its border.
- **margin Shorthand:** You can specify 1–4 values to set the margin sides. One value applies to all four sides; two values set top and bottom, then right and left; three values set top, horizontal (right and left), then bottom; four values set top, right, bottom, left.
- **padding Shorthand:** You can specify 1–4 values to set the padding sides. One value applies to all four sides; two values set top and bottom, then right and left; three values set top, horizontal (right and left), then bottom; four values set top, right, bottom, left.
- **Types of CSS Specificity**
  - **Inline CSS Specificity:** Inline CSS has the highest specificity because it is applied directly to the element. It overrides any internal or external CSS. The specificity value for inline styles is (1, 0, 0, 0).
  - **Internal CSS Specificity:** Internal CSS is defined within a style element in the head section of the HTML document. It has lower specificity than inline styles. Both internal and external CSS share the same specificity level, which is determined by their selectors, not their location.
  - **External CSS Specificity:** External CSS is linked via a link element in the head section and is written in separate .css files. Like internal CSS, its specificity is determined by the selectors used. When two rules have equal specificity, source order determines the winner: the rule that appears later in the document takes precedence. External CSS provides the best maintainability for larger projects.
- **Types of Selector:**
  - **Universal Selector (*):** A special type of CSS selector that matches any element in the document. It is often used to apply a style to all elements on the page, which can be useful for resetting or normalizing styles across different browsers.The universal selector has the lowest specificity value of any selector. It contributes 0 to all parts of the specificity value (0, 0, 0, 0).
  - **Type Selectors:** These selectors target elements based on their tag name. Type selectors have a relatively low specificity compared to other selectors. The specificity value for a type selector is (0, 0, 0, 1).
  - **Class Selectors:** These selectors are defined by a period (.) followed by the class name. The specificity value for a class selector is (0, 0, 1, 0). This means that class selectors can override type selectors, but they can be overridden by ID selectors and inline styles.
  - **ID Selectors:** ID selectors are defined by a hash symbol (#) followed by the ID name. ID selectors have a very high specificity, higher than type selectors and class selectors, but lower than inline styles. The specificity value for an ID selector is (0, 1, 0, 0).
- !important keyword: Used to give a style rule the highest priority, allowing it to override any other declarations for a property. When used, it forces the browser to apply the specified style, regardless of the specificity of other selectors. You should be cautious when using !important because it can make your CSS harder to maintain and debug.
- Cascade Algorithm: An algorithm used to decide which CSS rules to apply when there are multiple styles targeting the same element. It ensures that the most appropriate styles are used, based on a set of well-defined rules.
- CSS Inheritance: The process by which styles are passed down from parent elements to their children. Inheritance allows you to define styles at a higher level in the document tree and have them apply to multiple elements without explicitly specifying them for each element.
