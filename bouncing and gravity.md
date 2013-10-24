Cuchina--CLASS
==============

//Declare

CHI [] NumberCHI = new CHI [10]; 
//CHI is the class- my CHI is the class instance


//Initialize
void setup() {
  size(600, 600);
  smooth();
  noStroke();


  //Initialize
  for( int i = 0; i < 10; i++) { 
    NumberCHI [i] = new CHI (random(0,1000), random(0,200)); 
    // new CHI(400,400)the numbers are the starting point
  }
}

void draw() {
  background(0); 
  //Call Functionality
  for( int i = 0; i < 10; i++) { 
   
    // new CHI(400,400)the numbers are the starting point

  NumberCHI[i].run();
  //you only write one fuction but it has all the others in the class
}
  }
