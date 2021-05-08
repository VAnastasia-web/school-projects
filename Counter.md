<?php
$counters=$_GET["number"];
$counter=++;
?>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
    <title>Счётчик</title>
<link rel="stylesheet" type="text/css"
      href="Counter.css" />
</head>
<body>
   <h1>Счётчик</h1>
   <form>
   <input id="id_number" value="?=$counter ?>"
          class="number" type="text" />
   <input class="button" type="submit" />

</form>
</body>
</html>

