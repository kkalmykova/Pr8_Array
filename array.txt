<?php

$rows = 5;
$cols = 10;

$table = '<table border="1">';


for ($tr = 1; $tr<=5; $tr++){
    $table .= '<tr>';
    for ($td = 1; $td<=10; $td++){
        $table .= '<td>'. rand(1, 5) .'</td>';
    }

    $table .= '</tr>';
}

$table .= '</table>';
echo $table; 

?>