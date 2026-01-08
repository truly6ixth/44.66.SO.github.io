<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>💘</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #ffe6eb, #fff1dc);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: "Georgia", serif;
    }

    .card {
      background: white;
      padding: 40px 35px;
      max-width: 420px;
      text-align: center;
      border-radius: 20px;
      box-shadow: 0 20px 45px rgba(0,0,0,0.12);
      animation: fadeIn 1.6s ease;
    }

    h1 {
      margin-top: 0;
      font-size: 26px;
    }

    p {
      font-size: 18px;
      line-height: 1.7;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 15px;
    }

    button {
      border: none;
      padding: 12px 22px;
      font-size: 16px;
      border-radius: 30px;
      cursor: pointer;
      transition: transform 0.2s ease;
    }

    .yes {
      background: #ff5c8a;
      color: white;
    }

    .yes:hover {
      transform: scale(1.05);
    }

    .yes2 {
      background: #ffd6e1;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(15px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Hey my love 💕</h1>
    <p>
      From the moment you came into my life, things have felt lighter,
      warmer, and a little more magical. You make me smile without trying,
      and I’m so grateful for you.
    </p>
    <p>
      So I wanted to ask you properly…
      <br><strong>Will you be my Valentine? 💘</strong>
    </p>

    <div class="buttons">
      <button class="yes" onclick="yes()">Yes 💖</button>
      <button class="yes2" onclick="yes()">Of course 💕</button>
    </div>
  </div>

  <script>
    function yes() {
      document.body.innerHTML = `
        <div style="
          height:100vh;
          display:flex;
          justify-content:center;
          align-items:center;
          background:linear-gradient(135deg,#ffe6eb,#fff1dc);
          font-family:Georgia, serif;
          text-align:center;
        ">
          <div style="
            background:white;
            padding:45px;
            border-radius:20px;
            box-shadow:0 20px 45px rgba(0,0,0,0.12);
            animation: fadeIn 1.5s ease;
          ">
            <h1>Yay!! 💘</h1>
            <p style="font-size:18px; line-height:1.7;">
              You just made me the happiest person.
              <br>I can’t wait to spend Valentine’s Day with you ❤️
            </p>
          </div>
        </div>
      `;
    }
  </script>
</body>
</html>
