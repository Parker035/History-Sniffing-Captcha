<?php
$query = $_POST['fake'];
$D = 'D';
$L = 'L';
$Q = 'Q';
$S = 'S';
$B = 'B';
$I = 'I';
$PAX = 'PAX';
if($query == $PAX){
echo "It is time to choose a major.";
}
else{
	echo "Have you considered, ";
	if(strpos($query,$D)){
	echo "art history ";
	}
	if(strpos($query,$L)){
	echo "chemistry ";
	}
	if(strpos($query,$Q)){
	echo "economics ";
	}
	if(strpos($query,$S)){
	echo "english ";
	}
	if(strpos($query,$B)){
	echo "math ";
	}
	if(strpos($query,$I)){
	echo "physics ";
	}
	echo "?";
}

?>