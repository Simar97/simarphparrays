<?php

class Pokemon

{
  
  //Declare properties
  public $PokemonName;
  public $PokemonTYPE;
  
  //Method to get the perimeter
  public fuction PokemonAttack(){
    return (rand(1,100));
    
    }
    }
    
    $psiDuck = new Pokemon;
    $psiDuck->PokemonName = "PsiDuck";
    $psiDuck->PokemonTYPE = "Psychic Pokemon";
    // Get the object properties values
    echo "Pokemon Name".$psiDuck->PokemonName."\n\r";
    echo "Pokemon Type".$psiDuck->PokemonType."\n\r";
    
    //Call the object methods
    echo "Pokemon Attack Strength:".$psiDuck->PokemonAttack();
    
    ?>
