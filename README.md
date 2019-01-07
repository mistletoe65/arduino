# arduino
my travel of arduino
the six led
void setup() {
  // put your setup code here, to run once:
  pinMode(2,OUTPUT);
  pinMode(3,OUTPUT);
  pinMode(4,OUTPUT);
  pinMode(5,OUTPUT);
  pinMode(6,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop() {
  int i;
  int led;
  for(i=2;i<8;i++)
  {
    led=i;
    digitalWrite(led,1);
    delay(20);
    digitalWrite(led,0);
    delay(20);}
}
