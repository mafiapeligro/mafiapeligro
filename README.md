<!DOCTYPE html>
<html>
<head>
  <title>Screamer</title>
  <style>
    #screamer {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 48px;
      color: red;
    }
  </style>
  <script>
    function showScreamer() {
      var screamer = document.getElementById('screamer');
      screamer.style.display = 'block';
    }
  </script>
</head>
<body>
  <h1>¡Haz clic en el botón para ver algo sorprendente!</h1>
  <button onclick="showScreamer()">¡Haz clic aquí!</button>
  <div id="screamer">¡AHHHHH!</div>
</body>
</html>
