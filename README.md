<!DOCTYPE html>
<html>
<head>
  <title>Love Test ❤️</title>
  <style>
    body {
      font-family: Arial;
      background: linear-gradient(to right, #ff758c, #ff7eb3);
      text-align: center;
      color: white;
      padding: 40px;
    }
    input, button {
      padding: 10px;
      margin: 10px;
      border-radius: 8px;
      border: none;
      font-size: 16px;
    }
    button {
      background: #fff;
      color: #ff3b6f;
      cursor: pointer;
    }
    .result {
      font-size: 24px;
      margin-top: 20px;
    }
  </style>
</head>

<body>

  <h1>💖 Love Compatibility Test 💖</h1>

  <input type="text" id="name1" placeholder="Your Name"><br>
  <input type="text" id="name2" placeholder="Partner Name"><br>

  <button onclick="calculateLove()">Test Love 💘</button>

  <div class="result" id="result"></div>

  <script>
    function calculateLove() {
      let loveScore = Math.floor(Math.random() * 41) + 60; // 60–100
      document.getElementById("result").innerHTML =
        "❤️ Love Score: " + loveScore + "%<br>" +
        "You both are made for each other 💑";
    }
  </script>

</body>
</html>
