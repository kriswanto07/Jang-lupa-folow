<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>REICKSANN | Instagram</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #050505;
      font-family: Arial, sans-serif;
      color: white;
    }

    .profile {
      width: min(88vw, 420px);
      aspect-ratio: 1;
      border-radius: 50%;
      padding: 8px;
      background: conic-gradient(
        #8338ff,
        #e600ff,
        #ff0069,
        #ff5722,
        #ffd600,
        #ff5722,
        #e600ff,
        #8338ff
      );
      box-shadow: 0 0 35px #b000ff55;
    }

    .inside {
      width: 100%;
      height: 100%;
      border-radius: 50%;
      background: radial-gradient(
        circle at 70% 25%, #21102e, #090909 65%
      );
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 20px;
      overflow: hidden;
    }

    .instagram {
      width: 34%;
      aspect-ratio: 1;
      border: 8px solid transparent;
      border-radius: 28%;
      background:
        linear-gradient(#090909, #090909) padding-box,
        linear-gradient(135deg, #8338ff, #e600ff,
        #ff0069, #ff8a00, #ffd600) border-box;
      position: relative;
    }

    .instagram::before {
      content: "";
      position: absolute;
      width: 42%;
      aspect-ratio: 1;
      border: 7px solid #ff168d;
      border-radius: 50%;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

    .instagram::after {
      content: "";
      position: absolute;
      width: 12%;
      aspect-ratio: 1;
      border-radius: 50%;
      background: #ff168d;
      top: 13%;
      right: 13%;
    }

    .name {
      position: relative;
      font-family: "Brush Script MT", cursive;
      font-size: clamp(34px, 10vw, 58px);
      font-style: italic;
      font-weight: bold;
      letter-spacing: -2px;
      text-shadow: 0 0 14px #ff168d44;
    }

    .crown {
      position: absolute;
      font-family: Arial, sans-serif;
      font-size: 28px;
      font-style: normal;
      top: -35px;
      right: 0;
    }

    .underline {
      width: 55%;
      height: 5px;
      margin-top: -12px;
      border-radius: 100%;
      background: linear-gradient(
        90deg, #ff9d00, #ff0069, #8338ff
      );
      transform: rotate(-3deg);
    }

    .tagline {
      font-size: 10px;
      letter-spacing: 4px;
      color: #aaa;
      margin-top: -5px;
    }
  </style>
</head>

<body>
  <main class="profile">
    <div class="inside">

      <div class="instagram"></div>

      <div class="name">
        <span class="crown">♛</span>
        reicksann
      </div>

      <div class="underline"></div>

      <p class="tagline">OFFICIAL PROFILE</p>

    </div>
  </main>
</body>
</html>
