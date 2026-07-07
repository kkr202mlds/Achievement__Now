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
- **accessible websites** : the **World Wide Web(www) Consortium, known as W3C**, developed a set of international standards **Web Content Accessibility Guidelines (WCAG)** that you can follow to make your websites more accessible and easier to use for people with disabilities.
- **https : HyperText Transfer Protocol Secure**.
- **POUR** : four core  principles in mind.
- P stands for **Perceivable**. Users must be able to perceive the information that you are presenting. For example, you can provide alternative text for images, so users who access your website with a screen reader can understand them.
- O stands for **Operable**. Users must be able to interact with the user interface. For example, you can make sure that all functionality is accessible through the keyboard too, not just the mouse.
- U stands for **Understandable**. Users must be able to understand the information. For example, you can avoid complex sentences and use simple language as much as possible.
- R stands for **Robust**. A wide range of browsers and other tools, including assistive technologies, must be able to interpret the content.
- **Screen readers** are assistive technology programs that help blind and visually impaired people use computers and mobile devices. **text-to-speech** is just one of the features of a screen reader
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
- Voice recognition software helps people with disabilities interact with computers and other digital devices.
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

