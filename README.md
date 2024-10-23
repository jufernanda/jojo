# jojo
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Você me ama?</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }

    .container {
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .buttons {
      margin-top: 20px;
    }

    .buttons button {
      font-size: 1.2rem;
      padding: 10px 20px;
      margin: 0 10px;
      background-color: pink;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .buttons button:hover {
      background-color: #ff99cc;
    }

    .result {
      margin-top: 20px;
    }

    .result img {
      max-width: 150px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>você me ama momo?</h1>
    <div class="buttons">
      <button onclick="showHeart()">Sim</button>
      <button onclick="showSadCat()">Não</button>
    </div>
    <div class="result" id="result"></div>
  </div>

  <script>
    function showHeart() {
      document.getElementById('result').innerHTML = '<img src="https://i.pinimg.com/enabled_hi/236x/b5/1c/2d/b51c2d96f6772c321f677b477def77d6.jpg" alt="Coração">';
    }

    function showSadCat() {
      document.getElementById('result').innerHTML = '<img src="https://i.pinimg.com/enabled_hi/236x/46/4c/dd/464cdd1de04dae7d8a74d5feda4d0446.jpg" alt="Gato triste">';
    }
  </script>
</body>
</html>
