```
# index.html

<link rel="stylesheet" href="styles.css">

<form>
  <label for="password">Password:</label>
  <input type="password" id="password" aria-describedby="password-help" />
  <p id="password-help">Your password must be at least 8 characters long.</p>
</form>

<script src="index.js"></script>

# style.css

#password-help {
  color: red;
}

# index.js

const passwordEl = document.getElementById("password");
const passwordHelpText = document.getElementById("password-help");

passwordEl.addEventListener("input", (e) => { 
  const userInput = e.target.value;
  passwordHelpText.style.color = userInput.length >= 8 ? "green" : "red";
});
```

<img width="464" height="356" alt="image" src="https://github.com/user-attachments/assets/cd40e033-735d-4953-b846-7dba6e50491c" />

