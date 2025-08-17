# Contranada-
New Website 08/17/25
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Joseph Lakata | Contranada</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      margin: 0;
      background: #f6f5f3;
      color: #111;
      font-family: sans-serif;
      overflow: hidden;
    }
    .container {
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      position: relative;
    }
    .logo-link {
      text-align: center;
      text-decoration: none;
      color: inherit;
    }
    .logo {
      width: 300px;
      max-width: 80%;
      cursor: pointer;
    }
    .hidden-text {
      margin-top: 16px;
      font-size: 1em;
      opacity: 0;
      animation: fadeInOut 4s ease-in-out infinite;
    }
    @keyframes fadeInOut {
      0%, 100% { opacity: 0; }
      50% { opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="container">
    <a href="home.html" class="logo-link">
      <img src="assets/Untitled-1.png" alt="Two Faces Logo" class="logo" />
      <p class="hidden-text">Don't Assume</p>
    </a>
  </div>
</body>
</html>
