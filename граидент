import processing.opengl.*; 
 
 
 void setup(){ 
   size(500, 500, OPENGL); 
   noStroke(); 
 } 
 
 
 void draw(){ 
   background(0); 
    
   fill(155,211,0); 
   rect(0,0,500,500); 

 
   float percentHidden = map(mouseY, 0, 500, 0, 1);   
    
   beginShape(QUADS); 
    fill(0,255); 
    vertex(0,0); 
     vertex(500,0); 
     fill(0,0); 
     vertex(500, 500 * percentHidden); 
     vertex(0, 500 * percentHidden); 
   endShape(); 
 
 
 } 
