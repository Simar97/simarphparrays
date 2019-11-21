 <?php

$userINPUT=17;
for($userINPUT=0; $userINPUT<100; $userINPUT++ )
{
    $pokemonattackstrength=rand(1,100);
   
echo "pokemonstrengthis ". $pokemonattackstrength;
if($userINPUT>$pokemonattackstrength)
{
echo"user input is" .$userINPUT;
echo "POKEMON attackl strength is".$pokemonattackstrength."\n\r";
}
}
 
