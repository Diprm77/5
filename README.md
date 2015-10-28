
Tree one,two,three;
float horizon;


void setup(){
  
  size(700,600);
  //horizon(height/3);
  one = new Tree();
}

void draw(){
  trees();
}

void trees(){
  one.show();
}

class Tree {
  
  float x = 100, y = 50, dx = 3, dy = .5;
  int r,g,b;
  float w = 80;
  
  
  
 void show (){
   

   noStroke();
   fill(95,54,13);
   rect(140,80,20,40);
   fill(20,169,50);
   triangle(100,50,150,10,200,50);
   
   triangle(100,50+20,150,10+20,200,50+20);
   
   triangle(100,50+40,150,10+40,200,50+40);
   
   stroke(1);
 }}
