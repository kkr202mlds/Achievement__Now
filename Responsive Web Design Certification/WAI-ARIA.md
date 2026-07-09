```
# index.html  - HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Custom Button</title>
  <link href="styles.css" rel="stylesheet">
</head>
<body>

  <!-- Added tabindex="0" so the custom button can be keyboard focused -->
  <div id="custom-btn" role="button" tabindex="0">Click Me</div>

  <script src="index.js"></script>
</body>
</html>

# styles.css  -   CSS

body{
  padding: 25px;
}
.title {
	color: #5C6AC4;
}

# script.js  -   JavaScript

function showTime() {
	document.getElementById('currentTime').innerHTML = new Date().toUTCString();
}
showTime();
setInterval(function () {
	showTime();
}, 1000);
```
<img width="285" height="105" alt="Screenshot 2026-07-09 143126" src="https://github.com/user-attachments/assets/6eaf1e7e-3119-443b-91d5-e7a319ee8677" />



```
# index.html   -  HTML

<link rel="stylesheet" href="styles.css">

<div class="alert" id="exp-warning" role="alert">
  <span class="hidden">Your log in session will expire in 3 minutes.</span>
</div>

# styles.css  -  CSS

.alert {
  background-color: #fff3cd;
  border: 1px solid #ffeeba;
  color: #856404;
  padding: 1em;
  margin-top: 1em;
  border-radius: 4px;
  font-weight: bold;
}

.alert span {
  display: inline-block;
}
```
<img width="531" height="118" alt="Screenshot 2026-07-09 142418" src="https://github.com/user-attachments/assets/83522329-8674-4f09-9c84-f055be3c9edb" />


```
# index.html

<link rel="stylesheet" href="styles.css">

<div class="search-container" role="search">
  <label for="searchbox" class="visually-hidden">Search</label>

  <div
    id="searchbox"
    class="searchbox"
    role="searchbox"
    aria-label="Search the site"
    tabindex="0"
    contenteditable="true">
  </div>

  <button type="button" aria-label="Submit search">Search</button>
</div>


# style.css

.search-container {
  display: flex;
  align-items: center;
  gap: 0.5em;
  margin-top: 1em;
}

.searchbox {
  flex: 1;
  padding: 0.5em;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
  min-height: 1.5em;
}

.searchbox:focus {
  border-color: #007acc;
  outline: none;
  box-shadow: 0 0 0 2px rgba(0, 122, 204, 0.3);
}

button {
  padding: 0.5em 1em;
  background-color: #007acc;
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  background-color: #005fa3;
}

/* Hide visually but keep for screen readers */
.visually-hidden {
  position: absolute;
  left: -9999px;
}
```
<img width="533" height="117" alt="Screenshot 2026-07-09 145607" src="https://github.com/user-attachments/assets/918e3890-c47e-480e-bc5b-de24d46c9371" />

```
# index.html

<link rel="stylesheet" href="styles.css">


<div role="banner" class="site-banner">
  <h1>Accessible Web Design</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Articles</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</div>


# style.css

.site-banner {
  background-color: #007acc;
  color: #fff;
  padding: 1em 1.5em;
  border-radius: 4px;
}

.site-banner h1 {
  margin: 0 0 0.5em;
  font-size: 1.5em;
}

.site-banner nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  gap: 1em;
}

.site-banner nav a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
}

.site-banner nav a:hover {
  text-decoration: underline;
}
```
<img width="530" height="126" alt="Screenshot 2026-07-09 150055" src="https://github.com/user-attachments/assets/f9ed2eb2-2726-44c1-9475-69ce1c82385f" />

```
# index.html




```
<img width="528" height="115" alt="image" src="https://github.com/user-attachments/assets/42a2f784-32a1-47f4-98bc-357996cf9c3c" />
