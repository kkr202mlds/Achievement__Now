```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <title>Checkout Page</title>
</head>

<body>
  <h1>Checkout</h1>
  <section>
    <h2>Your Cart</h2>
    <img src="https://cdn.freecodecamp.org/curriculum/labs/cube.jpg" alt="multiple colour cube">
  </section>
  <section>
    <h2>Payment Information</h2>
    <form>
        <label for="card-name">Cardholder Name
          <span aria-hidden="true">*</span>
        </label>
        <input id="card-name"
        name="card-name"
        type="text"
        required>

        <label for="card-number">Cardholder Number
          <span aria-hidden="true">*</span>
        </label>
        <input id="card-number"
        name="card-number"
        type="text"
        aria-describedby="card-number-help"
        required>
        <p id="card-number-help">Please enter your 16-digit card number without spaces or dashes.</p>
        
    </form>
  </section>

</body>
</html>
```
<img width="524" height="505" alt="image" src="https://github.com/user-attachments/assets/e2fcb504-9341-46d9-8334-cedd5e1285fb" />
