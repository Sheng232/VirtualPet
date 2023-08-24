void setup() {
size(500,500);
}
void draw() {
  int changex = -70;
  int changey = 0;
  fill(235, 150, 216);
  noStroke();
  ellipse(350 + changex, 310,200,100);
  ellipse(250 + changex, 250 + changey,150,70);
  fill(10, 10, 10);
  int x = 30;
  ellipse(180+x,235,10,10);
  ellipse(180-x,235,10,10);
  fill(252, 250, 250);
  ellipse(180,250,80,15);
  fill(8, 8, 8);
  ellipse(180+10,250,5,10);
  ellipse(180-10,250,5,10);
  fill(235,150,216);
  arc(140,240,100,100,PI/2+1.8,PI+1);
  arc(215,235,100,100,2*PI/3+3.4,2*PI);
  stroke(5);
  noFill();
  arc(380,260,100,100,0,PI/2);
  fill(111, 74, 125);
  ellipse(280+40,350,40,15);
  ellipse(280-40,350,40,15);
}
