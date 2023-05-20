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
![3d](https://github.com/aswinkichuzzz/kichuzzz/blob/main/Screenshot%20from%202023-05-16%2010-24-12.png)

##DAY7
![7 SEGMENT](https://github.com/aswinkichuzzz/kichuzzz/blob/main/Screenshot%20from%202023-05-18%2011-35-39.png)
const int potPin=A0;

void setup(){
  Serial.begin(9600);
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
}
void loop()
{ 
  int potvalue = analogRead(potPin);
  Serial.println(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,HIGH);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(potvalue);
} 

**day8
![rgb led](https://github.com/aswinkichuzzz/kichuzzz/blob/main/kunnamkkulam.md)

**day-9
![volt meter](https://github.com/aswinkichuzzz/kichuzzz/blob/main/Screenshot%20from%202023-05-20%2011-08-29.png)
program
........
#include "LiquidCrystal.h"
LiquidCrystal lcd(2, 3, 4, 5, 6, 7);
int analogI = 0;
float vout = 0.0 ;
float vin = 0.0;
float R1 = 100000.0; // resistance of R1 (100K) -see text!
float R2 = 10000.0; // resistance of R2 (10K) - see text!
int value = 0;
void setup(){
   pinMode(analogI, INPUT);
   lcd.begin(16, 2);
   lcd.print("DC VOLTMETER");
}
void loop(){
   // read the value at analog input
   value = analogRead(analogI);
   vout = (value * 5.0) / 1024.0; // see text
   vin = vout / (R2/(R1+R2)); 
   if (vin<0.09) {
   vin=0.0;//statement to quash undesired reading !
} 
lcd.setCursor(0, 1);
lcd.print("INPUT V= ");
lcd.print(vin);
delay(500);
}



