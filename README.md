<?php

class rectangle

{
    
    //Declare properties
    
    public $length = 0;
    
    public $width = 0;
    
    //Method to get the perimeter
    
    public function getPerimeter(){
        
        return (2 * ($this->length + $this->width));
        
    }
    
    // method to get the area
    
    public function getArea(){
        
        return($this->length * $this->width);
        
    }
    
    
    
}

$obj = new Rectangle;

//get the object properties values

echo $obj->length;//output: 0
echo $obj->width;//output: 0

//set object properties values

$obj->length = 30;

$obj->width = 20;

//read the object properties values again to show the change

echo $obj->length; // output: 30

echo $obj->width; // output: 20


// call the object methods

echo $obj->getperimeter(); // output: 100

echo $obj->getarea(); // output: 600

?>
