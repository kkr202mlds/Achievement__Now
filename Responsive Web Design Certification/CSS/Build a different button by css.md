```
#index.html

<link rel="stylesheet" href="styles.css" />

<button class="regular-btn">Unstyled Button</button>
<button class="round-btn">Round Button</button>

#styles.css

.round-btn {
  font-size: 1rem;
  font-family: 'Segoe UI', sans-serif;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.2s ease;
  background-color: #2ecc71;
  color: white;
  border-radius: 50px;
  padding: 0.6rem 1.6rem;
}

.round-btn:hover {
  background-color: #27ae60;
  transform: translateY(-2px);
}
```
<img width="302" height="82" alt="image" src="https://github.com/user-attachments/assets/9dc1af94-7bc3-443f-8996-0c22f2c9d99e" />
