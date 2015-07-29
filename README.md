# ejmplo
como subir codigo al repositorio
<html>
<head>
<title>
Suma
</title>
</head>
<body>
	<?php
	$num1=$_POST["num1"];
	$num1=$_POST["num2"];
	$suma=$num1+$num2;
	?>
<form method="post" name="suma" action="suma.php">
	Ingrese el numero 1:<input type="text" name="num1"><br>
	Ingrese el numero 2:<input type="text" name="num2"><br>
	<input type="submit" value="Enviar">
	<input type="submit" value="Borrar">
</form>
<p><?php if ($num1&&$num2)
             echo"La suma de los numeros ingresados es:$suma";
             else
         if (!$null&&!$num2)
         	echo"Ingrese los numeros por favor";
    ?></p>
</body>
</html>
