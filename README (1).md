# Te-amo-mi-vida
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Para ti 💕</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      background: url('https://i.ibb.co/Jc1NqvG/corazones.jpg') no-repeat center center fixed, 
                  linear-gradient(135deg, #ff9a9e, #fad0c4, #fbc2eb, #a6c1ee);
      background-size: cover;
      animation: gradient 15s ease infinite;
    }
    h1 {
      font-size: 3em;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.5);
      animation: heartbeat 1.5s infinite;
    }
    @keyframes heartbeat {
      0% { transform: scale(1); }
      25% { transform: scale(1.1); }
      50% { transform: scale(1); }
      75% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }
    @keyframes gradient {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }
    audio {
      margin-top: 20px;
      border-radius: 15px;
      box-shadow: 0px 4px 12px rgba(0,0,0,0.4);
    }
  </style>
</head>
<body>
  <div>
    <h1>TE AMO PERLIS 🫶🏻💕</h1>
    <audio controls autoplay loop>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
      Tu navegador no soporta audio.
    </audio>
  </div>
</body>
</html>
