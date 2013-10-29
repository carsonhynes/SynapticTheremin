int rLEDO = 13;
int gLED0 = 12;
int rLED1 = 11;
int gLED1 = 10;
int rLED2 = 9;

int tLED0 = 7;
int tLED1 = 6;
int tLED2 = 5;

void setup()
{
  Serial.begin(9600);
  pinMode(rLEDO, OUTPUT);
  pinMode(gLED0, OUTPUT);
  pinMode(rLED1, OUTPUT);
  pinMode(gLED1, OUTPUT);
  pinMode(rLED2, OUTPUT);
  
  pinMode(tLED0, OUTPUT); //Blue
  pinMode(tLED1, OUTPUT); //Green
  pinMode(tLED2, OUTPUT); //Red
}

void loop()
{
  if (Serial.available() > 0)
  {
    int value[] = {0,0,0,0,0,1,0,1};
    if (value[0] == 0)
    {
      digitalWrite(rLEDO, LOW);
    }
    else
    {
      digitalWrite(rLEDO, HIGH);
    }
    
    if (value[1] == 0)
    {
      digitalWrite(gLED0, LOW);
    }
    else
    {
      digitalWrite(gLED0, HIGH);
    }
    
    if (value[2] == 0)
    {
      digitalWrite(rLED1, LOW);
    }
    else
    {
      digitalWrite(rLED1, HIGH);
    }
    
    if (value[3] == 0)
    {
      digitalWrite(gLED1, LOW);
    }
    else
    {
      digitalWrite(gLED1, HIGH);
    }
    
    if (value[4] == 0)
    {
      digitalWrite(rLED2, LOW);
    }
    else
    {
      digitalWrite(rLED2, HIGH);
    }
    
    if (value[5] == 0)
    {
      digitalWrite(tLED2, LOW);
    }
    else
    {
      digitalWrite(tLED2, HIGH);
    }
    
    if (value[6] == 0)
    {
      digitalWrite(tLED1, LOW);
    }
    else
    {
      digitalWrite(tLED1, HIGH);
    }
    if (value[7] == 0)
    {
      digitalWrite(tLED0, LOW);
    }
    else
    {
      digitalWrite(tLED0, HIGH);
    }
  }
}
