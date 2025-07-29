<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elif</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #000000, #2c2c2c);
      font-family: 'Playfair Display', serif;
      color: #fff;
      overflow: hidden;
    }

    h1 {
      text-align: center;
      margin-top: 20vh;
      font-size: 3rem;
      color: #ff6699;
      text-shadow: 2px 2px 5px black;
    }

    .heart {
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      transform: rotate(45deg);
      animation: float 2s ease-out forwards;
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      border-radius: 50%;
    }

    .heart::before {
      top: -10px;
      left: 0;
    }

    .heart::after {
      left: -10px;
      top: 0;
    }

    @keyframes float {
      0% {
        opacity: 1;
        transform: translateY(0) scale(1) rotate(45deg);
      }
      100% {
        opacity: 0;
        transform: translateY(-200px) scale(1.5) rotate(45deg);
      }
    }

    footer {
      position: absolute;
      bottom: 10px;
      width: 100%;
      text-align: center;
      font-size: 0.8rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <h1>Elif</h1>
  <audio autoplay loop>
    <source src="https://example.com/born-to-die.mp3" type="audio/mpeg">
    Tarayıcınız ses öğesini desteklemiyor.
  </audio>
  <footer>Born to Die - Lana Del Rey</footer>

  <script>
    document.body.addEventListener("click", (e) => {
      const heart = document.createElement("div");
      heart.className = "heart";
      heart.style.left = e.clientX + "px";
      heart.style.top = e.clientY + "px";
      document.body.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 2000);
    });
  </script>
</body>
</html>
