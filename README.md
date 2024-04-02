# readme

<!DOCTYPE html>
<html>
<head>
<title>Hola, soy Luis!</title>
<script>
function typewriter(text) {
  var i = 0;
  var speed = 50;

  var interval = setInterval(function() {
    if (i < text.length) {
      document.getElementById("typewriter").innerHTML += text.charAt(i);
      i++;
    } else {
      clearInterval(interval);
    }
  }, speed);
}

typewriter("Hola, soy Luis!");
</script>
</head>
<body>
<h1 id="typewriter"></h1>
</body>
</html>
