function mediana($numeros)
{
    sort($numeros);
    $totalNumeros = count($numeros);
    $med = floor($totalNumeros / 2);

    return ($totalNumeros % 2) === 0 ? ($numeros[$med - 1] + $numeros[$med]) / 2 : $numeros[$med];
}
//Ejecución:
//median([1, 3, 3, 6, 7, 8, 9]);
// 6
//median([1, 2, 3, 6, 7, 9]);
// 4.5
