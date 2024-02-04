<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cielo te amo</title>
  <style>
    body {
      background-color: #ffa8d9;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      font-family: 'Arial Black', sans-serif;
    }

    #gif-container {
      text-align: center;
    }

    #message {
      font-size: 24px;
      margin-top: 20px;
    }

    #buttons-container {
      margin-top: 20px;
    }

    .button {
      font-size: 18px;
      padding: 10px 20px;
      margin: 0 10px;
      cursor: pointer;
      border: none;
      border-radius: 5px;
    }

    #yes-button {
      background-color: #89004f;
      color: #fff;
    }

    #yes-button2 {
      background-color: #c33b80;
      color: #fff;
    }
  </style>
</head>
<body>
  <div id="gif-container">
    <img src="sanrio-hello-kitty.gif" width="45%">
  </div>

  <div id="message">
    Cielo, ¿quieres ser mi San Valentín?
  </div>

  <div id="buttons-container">
    <button id="yes-button" class="button">Sí</button>
    <button id="yes-button2" class="button">Sí</button>
  </div>
</body>
</html>
