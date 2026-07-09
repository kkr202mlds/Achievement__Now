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


# style.css

#custom-btn {
  display: inline-block;
  padding: 0.4em 1em;
  font-size: 1rem;
  font-family: sans-serif;
  color: buttontext;
  background-color: buttonface;
  border: 1px solid #ccc;
  border-radius: 4px;
  cursor: pointer;
  user-select: none;
  text-align: center;
}

#custom-btn:focus {
  outline: 2px solid Highlight;
  outline-offset: 2px;
}

#custom-btn:active {
  background-color: #ddd;
}


# index.js

const button = document.getElementById("custom-btn");

button.addEventListener("click", () => {
  alert("Button clicked!");
});

button.addEventListener("keydown", (e) => {
  if (e.key === "Enter" || e.key === " ") {
    e.preventDefault(); 
    button.click();
  }
});
```
<img width="155" height="69" alt="Screenshot 2026-07-08 152705" src="https://github.com/user-attachments/assets/79ebe830-8697-4d27-8456-6663d2501d2a" />

<img width="792" height="248" alt="Screenshot 2026-07-09 161355" src="https://github.com/user-attachments/assets/f33b887b-170e-4f3c-9106-59a8da9ca360" />



