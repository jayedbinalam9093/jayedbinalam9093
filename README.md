<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #0a0a0a 0%, #1a0033 100%);
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      font-family: 'Courier New', monospace;
    }

    .container {
      text-align: center;
    }

    h1 {
      font-size: 5em;
      font-weight: bold;
      color: #ffffff;
      letter-spacing: 8px;
      text-shadow: 0 0 30px rgba(0, 255, 150, 0.6),
                   0 0 60px rgba(100, 200, 255, 0.4);
      margin: 0;
      animation: glow 2s ease-in-out infinite;
    }

    @keyframes glow {
      0%, 100% { text-shadow: 0 0 30px rgba(0, 255, 150, 0.6); }
      50% { text-shadow: 0 0 50px rgba(0, 255, 150, 0.8); }
    }

    .typewriter {
      height: 50px;
      color: #00ff00;
      font-size: 1.5em;
      overflow: hidden;
      border-right: 3px solid #00ff00;
      white-space: nowrap;
      animation: typing 4s steps(50, end), blink 0.75s step-end infinite;
      display: inline-block;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      from, to { border-color: transparent }
      50% { border-color: #00ff00 }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>JAYED</h1>
    <div class="typewriter">First year CSE student | Learning C</div>
  </div>
</body>
</html>
