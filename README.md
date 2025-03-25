# numero-maior-PHP

<?php

echo "digite o primeiro numero:"; 
$num1 = (float) readline();

echo "digite o segundo numero:";
$num2 = (float) readline();

if ($num1 > $num2) {
    echo "o primeiro é maior";


}else if ($num1 < $num2) {
    echo "o segundo é maior";
}else {
    echo "os dois são iguais";
}
