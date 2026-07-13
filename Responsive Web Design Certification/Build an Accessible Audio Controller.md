```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Accessible Controls</title>
  </head>
  <body>

    <h1>Audio Controls</h1>

    <button type="button">Play</button>

    <div>
      <span id="volume-label">Volume</span>
      <span id="volume-description">Adjust the sound level</span>
      <input type="range" min="0" max="100" value="50"
        aria-labelledby="volume-label volume-description">
    </div>

    <button type="button">Mute</button>    

  </body>
</html>
```

<img width="404" height="190" alt="image" src="https://github.com/user-attachments/assets/c3d1135c-3181-4a96-9646-6a099fe26b71" />

