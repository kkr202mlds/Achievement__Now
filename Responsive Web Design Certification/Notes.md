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
<img width="185" height="56" alt="Screenshot 2026-06-24 143525" src="https://github.com/user-attachments/assets/eed46387-a160-4b6f-9548-c5d2448002bd" />

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

