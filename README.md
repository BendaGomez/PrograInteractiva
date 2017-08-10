# PrograInteractiva proyecto 1
float angle = 0.0;
float offset = 300;
float scalar = 50;
float speed = 0.1;

void setup()
{
  size(600,600);
}

void draw()
{
  float x = offset + cos(angle) * scalar;
  float y = offset + sin(angle) * scalar;
  ellipse(x,y,100,100);
  scalar +=0.1;
  angle += speed;
}
