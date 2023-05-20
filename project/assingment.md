## project
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
