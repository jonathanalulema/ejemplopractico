ejemplopractico
===============

uso de repositorios
<html>
<head>
<title>factorial de un numero</title>
</head>
<body>
<center>
<h1>factorial de un numero</h1>
<?php
$factorial=$_POST[ 'factor' ];
echo "<br>" ."1";
$result=1;
for($ciclo=2;$ciclo<=$factorial;$ciclo++)
{
$result= $result * $ciclo;
echo   " x ". $ciclo;
}
echo  " = ".$result;
?>
</center>
</body>
</html>
