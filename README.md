# iching001
The 64 iChing Hexagrams in a 8 x 8 grid


// Started 21161119 2315
// To draw the following image:
// http://baharna.com/iching/images/Plate2_Fig1_Hexagrams_FuHsi.gif
// https://en.wikipedia.org/wiki/I_Ching#/media/File:Diagram_of_I_Ching_hexagrams_owned_by_Gottfried_Wilhelm_Leibniz,_1701.jpg
// http://www.ichingfortune.com/hexagrams.php



int black  = 0;

int white= 255;

int scale = 20;

float gap = scale;
float x1origin;
float y1origin;

void setup() {
  background(255, 255, 255); 
  size(880, 860);
  smooth(8);
}


void draw() {

  noLoop();
  // 1,1
  x1origin = 200;
  y1origin = 200;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 2,1
  x1origin = 200 + (scale * 3);
  y1origin = 200;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 3,1
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 4,1
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 5,1
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 6,1
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 7,1
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 8,1
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 1,2
  x1origin = 200;
  y1origin = 200 + scale * 3;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 2,2
  x1origin = 200 + (scale * 3);
  y1origin = 200 + scale * 3;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 3,2
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200 + scale * 3;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 4,2
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200 + scale * 3;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 5,2
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200 + scale * 3;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 6,2
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200 + scale * 3;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 7,2
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200 + scale * 3;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 8,2
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200 + scale * 3;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 1,3
  x1origin = 200;
  y1origin = 200 + scale * 6;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 2,3
  x1origin = 200 + (scale * 3);
  y1origin = 200 + scale * 6;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 3,3
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200 + scale * 6;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 4,3
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200 + scale * 6;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 5,3
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200 + scale * 6;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 6,3
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200 + scale * 6;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 7,3
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200 + scale * 6;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 8,3
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200 + scale * 6;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 1,4
  x1origin = 200;
  y1origin = 200 + scale * 9;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 2,4
  x1origin = 200 + (scale * 3);
  y1origin = 200 + scale * 9;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 3,4
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200 + scale * 9;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 4,4
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200 + scale * 9;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 5,4
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200 + scale * 9;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 6,4
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200 + scale * 9;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 7,4
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200 + scale * 9;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);

  // 8,4
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200 + scale * 9;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYin(x1origin, y1origin, scale, 0);


  // 1,5
  x1origin = 200;
  y1origin = 200 + scale * 12;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 2,5
  x1origin = 200 + (scale * 3);
  y1origin = 200 + scale * 12;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 3,5
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200 + scale * 12;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 4,5
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200 + scale * 12;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 5,5
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200 + scale * 12;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 6,5
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200 + scale * 12;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 7,5
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200 + scale * 12;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 8,5
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200 + scale * 12;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 1,6
  x1origin = 200;
  y1origin = 200 + scale * 15;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 2,6
  x1origin = 200 + (scale * 3);
  y1origin = 200 + scale * 15;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 3,6
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200 + scale * 15;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 4,6
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200 + scale * 15;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 5,6
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200 + scale * 15;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 6,6
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200 + scale * 15;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 7,6
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200 + scale * 15;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 8,6
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200 + scale * 15;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYin(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 1,7
  x1origin = 200;
  y1origin = 200 + scale * 18;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 2,7
  x1origin = 200 + (scale * 3);
  y1origin = 200 + scale * 18;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 3,7
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200 + scale * 18;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 4,7
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200 + scale * 18;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 5,7
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200 + scale * 18;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 6,7
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200 + scale * 18;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 7,7
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200 + scale * 18;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 8,7
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200 + scale * 18;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYin(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 1,8
  x1origin = 200;
  y1origin = 200 + scale * 21;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 2,8
  x1origin = 200 + (scale * 3);
  y1origin = 200 + scale * 21;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 3,8
  x1origin = 200 + (scale * 2 + gap * 4);
  y1origin = 200 + scale * 21;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 4,8
  x1origin = 200 + (scale * 3 + gap * 6);
  y1origin = 200 + scale * 21;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYin(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 5,8
  x1origin = 200 + (scale * 4 + gap * 8);
  y1origin = 200 + scale * 21;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 6,8
  x1origin = 200 + (scale * 5 + gap * 10);
  y1origin = 200 + scale * 21  ;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYin(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 7,8
  x1origin = 200 + (scale * 6 + gap * 12);
  y1origin = 200 + scale * 21;
  YoungYin(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // 8,8
  x1origin = 200 + (scale * 7 + gap * 14);
  y1origin = 200 + scale * 21;
  YoungYang(x1origin, y1origin, scale, 5);
  YoungYang(x1origin, y1origin, scale, 4);
  YoungYang(x1origin, y1origin, scale, 3);
  YoungYang(x1origin, y1origin, scale, 2);
  YoungYang(x1origin, y1origin, scale, 1);
  YoungYang(x1origin, y1origin, scale, 0);

  // save("Hexagrams010.png");
  // exit();
}

void YoungYin(float origin_x1, float origin_y1, float scale, float number) {
  // - -
  fill(0);
  float gap = scale * 0.3;
  if (number == 0) {
    float x1 = origin_x1;
    float x2 = origin_x1 + scale;  
    float x4 = origin_x1;
    float x3 = origin_x1 + scale;
    float y1 = origin_y1 - scale * 0.2;
    float y2 = origin_y1 - scale * 0.2;
    float y4 = origin_y1;
    float y3 = origin_y1;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);

    x1 = origin_x1 + scale + gap;
    x2 = origin_x1 + scale + scale + gap;  
    x4 = origin_x1 + scale + gap;
    x3 = origin_x1 + scale + scale + gap;
    y1 = origin_y1 - scale * 0.2;
    y2 = origin_y1 - scale * 0.2;
    y4 = origin_y1;
    y3 = origin_y1;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }


  if (number == 1) {
    fill(0);
    float x1 = origin_x1;
    float x2 = origin_x1 + scale;  
    float x4 = origin_x1;
    float x3 = origin_x1 + scale;
    float y1 = origin_y1 - (scale * 0.2) * 3;
    float y2 = origin_y1 - (scale * 0.2) * 3;
    float y4 = origin_y1 - (scale * 0.2) * 2;
    float y3 = origin_y1 - (scale * 0.2) * 2;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);

    x1 = origin_x1 + scale + gap;
    x2 = origin_x1 + scale + scale + gap;  
    x4 = origin_x1 + scale + gap;
    x3 = origin_x1 + scale + scale + gap;
    y1 = origin_y1 - (scale * 0.2) * 3;
    y2 = origin_y1 - (scale * 0.2) * 3;
    y4 = origin_y1 - (scale * 0.2) * 2;
    y3 = origin_y1 - (scale * 0.2) * 2;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }


  if (number == 2) {
    fill(0);
    float x1 = origin_x1;
    float x2 = origin_x1 + scale;  
    float x4 = origin_x1;
    float x3 = origin_x1 + scale;
    float y1 = origin_y1 - (scale * 0.2) * 5;
    float y2 = origin_y1 - (scale * 0.2) * 5;
    float y4 = origin_y1 - (scale * 0.2) * 4;
    float y3 = origin_y1 - (scale * 0.2) * 4;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);

    x1 = origin_x1 + scale + gap;
    x2 = origin_x1 + scale + scale + gap;  
    x4 = origin_x1 + scale + gap;
    x3 = origin_x1 + scale + scale + gap;
    y1 = origin_y1 - (scale * 0.2) * 5;
    y2 = origin_y1 - (scale * 0.2) * 5;
    y4 = origin_y1 - (scale * 0.2) * 4;
    y3 = origin_y1 - (scale * 0.2) * 4;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }


  if (number == 3) {
    fill(0);
    float x1 = origin_x1;
    float x2 = origin_x1 + scale;  
    float x4 = origin_x1;
    float x3 = origin_x1 + scale;
    float y1 = origin_y1 - (scale * 0.2) * 7;
    float y2 = origin_y1 - (scale * 0.2) * 7;
    float y4 = origin_y1 - (scale * 0.2) * 6;
    float y3 = origin_y1 - (scale * 0.2) * 6;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);

    x1 = origin_x1 + scale + gap;
    x2 = origin_x1 + scale + scale + gap;  
    x4 = origin_x1 + scale + gap;
    x3 = origin_x1 + scale + scale + gap;
    y1 = origin_y1 - (scale * 0.2) * 7;
    y2 = origin_y1 - (scale * 0.2) * 7;
    y4 = origin_y1 - (scale * 0.2) * 6;
    y3 = origin_y1 - (scale * 0.2) * 6;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }



  if (number == 4) {
    fill(0);
    float x1 = origin_x1;
    float x2 = origin_x1 + scale;  
    float x4 = origin_x1;
    float x3 = origin_x1 + scale;
    float y1 = origin_y1 - (scale * 0.2) * 9;
    float y2 = origin_y1 - (scale * 0.2) * 9;
    float y4 = origin_y1 - (scale * 0.2) * 8;
    float y3 = origin_y1 - (scale * 0.2) * 8;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);

    x1 = origin_x1 + scale + gap;
    x2 = origin_x1 + scale + scale + gap;  
    x4 = origin_x1 + scale + gap;
    x3 = origin_x1 + scale + scale + gap;
    y1 = origin_y1 - (scale * 0.2) * 9;
    y2 = origin_y1 - (scale * 0.2) * 9;
    y4 = origin_y1 - (scale * 0.2) * 8;
    y3 = origin_y1 - (scale * 0.2) * 8;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }

  if (number == 5) {
    fill(0);
    float x1 = origin_x1;
    float x2 = origin_x1 + scale;  
    float x4 = origin_x1;
    float x3 = origin_x1 + scale;
    float y1 = origin_y1 - (scale * 0.2) * 11;
    float y2 = origin_y1 - (scale * 0.2) * 11;
    float y4 = origin_y1 - (scale * 0.2) * 10;
    float y3 = origin_y1 - (scale * 0.2) * 10;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);

    x1 = origin_x1 + scale + gap;
    x2 = origin_x1 + scale + scale + gap;  
    x4 = origin_x1 + scale + gap;
    x3 = origin_x1 + scale + scale + gap;
    y1 = origin_y1 - (scale * 0.2) * 11;
    y2 = origin_y1 - (scale * 0.2) * 11;
    y4 = origin_y1 - (scale * 0.2) * 10;
    y3 = origin_y1 - (scale * 0.2) * 10;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }
}


void YoungYang(float origin_x1, float origin_y1, float scale, float number) {
  // ---

  fill(0);
  float gap = scale * 0.3;
  if (number == 0) {
    float x1 = origin_x1;
    float x2 = origin_x1 + scale * 2 + gap;
    float x4 = origin_x1;
    float x3 = origin_x1 + scale * 2 + gap;
    float y1 = origin_y1 - scale * 0.2;
    float y2 = origin_y1 - scale * 0.2;
    float y4 = origin_y1;
    float y3 = origin_y1;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }

  if (number == 1) {
    float x1 = origin_x1;
    float x2 = origin_x1 + scale * 2 + gap;
    float x4 = origin_x1;
    float x3 = origin_x1 + scale * 2 + gap;
    float y1 = origin_y1 - (scale * 0.2) * 3;
    float y2 = origin_y1 - (scale * 0.2) * 3;
    float y4 = origin_y1 - (scale * 0.2) * 2;
    float y3 = origin_y1 - (scale * 0.2) * 2;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }

  if (number == 2) {
    float x1 = origin_x1;
    float x2 = origin_x1 + scale * 2 + gap;
    float x4 = origin_x1;
    float x3 = origin_x1 + scale * 2 + gap;
    float y1 = origin_y1 - (scale * 0.2) * 5;
    float y2 = origin_y1 - (scale * 0.2) * 5;
    float y4 = origin_y1 - (scale * 0.2) * 4;
    float y3 = origin_y1 - (scale * 0.2) * 4;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }

  if (number == 3) {
    float x1 = origin_x1;
    float x2 = origin_x1 + scale * 2 + gap;
    float x4 = origin_x1;
    float x3 = origin_x1 + scale * 2 + gap;
    float y1 = origin_y1 - (scale * 0.2) * 7;
    float y2 = origin_y1 - (scale * 0.2) * 7;
    float y4 = origin_y1 - (scale * 0.2) * 6;
    float y3 = origin_y1 - (scale * 0.2) * 6;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }

  if (number == 4) {
    float x1 = origin_x1;
    float x2 = origin_x1 + scale * 2 + gap;
    float x4 = origin_x1;
    float x3 = origin_x1 + scale * 2 + gap;
    float y1 = origin_y1 - (scale * 0.2) * 9;
    float y2 = origin_y1 - (scale * 0.2) * 9;
    float y4 = origin_y1 - (scale * 0.2) * 8;
    float y3 = origin_y1 - (scale * 0.2) * 8;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }  

  if (number == 5) {
    float x1 = origin_x1;
    float x2 = origin_x1 + scale * 2 + gap;
    float x4 = origin_x1;
    float x3 = origin_x1 + scale * 2 + gap;
    float y1 = origin_y1 - (scale * 0.2) * 11;
    float y2 = origin_y1 - (scale * 0.2) * 11;
    float y4 = origin_y1 - (scale * 0.2) * 10;
    float y3 = origin_y1 - (scale * 0.2) * 10;
    quad(x1, y1, x2, y2, x3, y3, x4, y4);
  }
  
}
