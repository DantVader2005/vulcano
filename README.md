# vulcano

```
float up =0;  void setup(){   size(700,700);        }  void draw(){   background(128);   stroke(255,66,3);   noFill();       arc(50,200,300,300,PI+HALF_PI,2 * PI);       arc(550,200,300,300,PI,PI+HALF_PI);       line(225,100+up,225,200+up);       line(300,100+up,300,200+up);              up = up-3;      fill(155,120,76);   quad (150,200,450,200,700,700,0,700);}   
```
