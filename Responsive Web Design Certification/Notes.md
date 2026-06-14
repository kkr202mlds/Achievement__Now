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
- An **h1 element** is the main heading of a webpage and you should only use one per page. h2 elements represent subheadings.
- When you need to add a paragraph to a webpage, you can use the p element.
- HTML represents the blocks, concrete, and irons that make up the walls. It's the foundation that makes the building strong. **CSS** represents the interior and exterior design that makes the house look beautiful. **JavaScript** represents the electrical and water system that ensures uninterrupted access to water and electricity.
```
<element attribute="value"></element>
The value can be a string or a number, depending on the attribute.
<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>
```
- **href attribute** (hypertext reference) specifies the URL of a link or external resource and the **target attribute** specifies where to open the link to open in a new browser tab.
- **anchor element** (a element) is used to create hyperlinks. The text between the opening and closing a tags is the clickable part users select to navigate.
- **input element** with the type attribute set to checkbox. **Inputs** are used to collect data from users, and the **type attribute** specifies the type of input.
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
-  **link element** is used to link to external resources like stylesheets and site icons. **rel attribute** stands for relationship b/w html doc & external res. href - hypertext refrenece
```
<link rel="stylesheet" href="./styles.css" />
stylesheet: Imports an external CSS file to style the webpage
```
```
<head>
  <meta charset="UTF-8" />
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
