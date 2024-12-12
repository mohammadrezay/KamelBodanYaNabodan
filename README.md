# KamelBodanYaNabodan
https://quera.org/problemset/282
<?php
$n = (int)readline("Enter a number: ");
$all = 0;
for($i = 1; $i < $n; $i++){
	if($n % $i == 0){
		$all += $i;
	}
}
if($all == $n){
    echo "YES";
}else{
    echo "NO";
}	
