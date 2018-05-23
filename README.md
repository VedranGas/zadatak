<?php
 
  class Circle{
  
     function Area($r){
        $A=$r*$r*3.14;
        return $A;
     }

  }

     function Radius($r2) {
        $R=2*$r2*3.14;
        return $R;
     }


  class Triangle{
 
     function Area($b,$h){
            $A=$b*$h/2;
            return $A;
     }
  }

   function Radius($r2) {
        $R=a+b+c;
        return $R;
     }
  ?>


<?php
  $Shape="Circle";
  $a="";
  $b="";

  if($Shape=="Circle"){
     $Circle= new Circle();
     echo "<br/>".$Shape." area: ";
     echo $Circle->Area($a);
  }

if($Shape=="Triangle"){
     $Triangle= new Triangle();
     echo "<br/>".$Shape." area: ";
     echo $Triangle->Area($a,$b);
  }
  ?>
