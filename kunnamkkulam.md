 # 10 day internship
## day 1
## day 2
## day 3


DAY 3
![NO IMAGE](https://github.com/aswinkichuzzz/kichuzzz/blob/main/Screenshot%20from%202023-05-11%2015-42-55.png)

PROGEAM
```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(7, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(13,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(12,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(8,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(7, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(7,LOW);
  delay(100); // Wait for 1000 millisecond(s)
}

```
## day4

## day5
![AND](https://github.com/aswinkichuzzz/kichuzzz/blob/main/Screenshot%20from%202023-05-15%2014-27-56.png)

const int potpin = 0;

void setup () {
  Serial.begin(9600);
}

void loop() {
  int potValue = analogRead(potValue);
  Serial.println(potValue);
  delay(100);
}

![text](https://github.com/aswinkichuzzz/kichuzzz/blob/main/Screenshot%20from%202023-05-15%2015-15-39.png)

void encender(int a, int b, int c, int d, int e, int f, int g)
{
 

  digitalWrite(2, a);
  digitalWrite(3, b);  
  digitalWrite(4, c);  
  digitalWrite(5, d);  
  digitalWrite(6, e);  
  digitalWrite(7, f);  
  digitalWrite(8, g);  
}

void setup() {

  

  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop() {

  

  encender (0, 0, 0, 0, 0, 0, 1); 
  delay(500);

  encender (1, 0, 0, 1, 1, 1, 1); 
  delay(500);

  encender (0, 0, 1, 0, 0, 1, 0); 
  delay(500);

  encender (0, 0, 0, 0, 1, 1, 0); 
  delay(500);

  encender (1, 0, 0, 1, 1, 0, 0); 
  delay(500);

  encender (0, 1, 0, 0, 1, 0, 0); 
  delay(500);

  encender (0, 1, 0, 0, 0, 0, 0); 
  delay(500);

  encender (0, 0, 0, 1, 1, 1, 1); 
  delay(500);

  encender (0, 0, 0, 0, 0, 0, 0); 
  delay(500);

  encender (0, 0, 0, 1, 1, 0, 0); 
  delay(500);
} 

## day6
![3d]()
