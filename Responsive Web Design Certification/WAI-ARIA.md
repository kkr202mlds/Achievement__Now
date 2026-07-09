```
# index.html

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

# styles.css

body{
  padding: 25px;
}
.title {
	color: #5C6AC4;
}

# script.js

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
# index.html

<link rel="stylesheet" href="styles.css">

<div class="alert" id="exp-warning" role="alert">
  <span class="hidden">Your log in session will expire in 3 minutes.</span>
</div>

# styles.css

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



