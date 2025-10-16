# Ponderada-Arduino-UNO

Segue link do video do arduino funcionando:
https://youtu.be/gKJVif3j-zc

![Tinkercad](Tinkercad.PNG)

https://www.tinkercad.com/things/g9ComeIuFhz-arduino-caua

![Arduino](Arduino.jpg)

Codigo utilizado:

```
int redPin = 0;
int greenPin = 1;
int bluePin = 2;

void setup() {
  pinMode(11, OUTPUT);
    
  pinMode(10, OUTPUT); 
   
  pinMode(9, OUTPUT); 

  pinMode(8, OUTPUT);

  pinMode(redPin, OUTPUT);
  pinMode(greenPin, OUTPUT);
  pinMode(bluePin, OUTPUT);

}

void loop() {

  digitalWrite(redPin, HIGH);
  delay(300);
   digitalWrite(redPin, LOW);
  delay(300);

digitalWrite(greenPin, HIGH);
   delay(300);
digitalWrite(greenPin, LOW);
   delay(300);

digitalWrite(bluePin, HIGH);
  delay(300);
digitalWrite(bluePin, LOW);

  digitalWrite(redPin, HIGH);
  delay(300);
   digitalWrite(redPin, LOW);
  delay(300);

digitalWrite(greenPin, HIGH);
   delay(300);
digitalWrite(greenPin, LOW);
   delay(300);

digitalWrite(bluePin, HIGH);
  delay(300);
digitalWrite(bluePin, LOW);

  digitalWrite(redPin, HIGH);
  delay(300);
   digitalWrite(redPin, LOW);
  delay(300);

digitalWrite(greenPin, HIGH);
   delay(300);
digitalWrite(greenPin, LOW);
   delay(300);

digitalWrite(bluePin, HIGH);
  delay(300);
digitalWrite(bluePin, LOW);
  

  digitalWrite(11, HIGH);
  delay(300);           
  digitalWrite(11, LOW);  
  delay(300);            

  digitalWrite(10, HIGH);
  delay(300);           
  digitalWrite(10, LOW);  
  delay(300);            

  digitalWrite(9, HIGH);
  delay(300);           
  digitalWrite(9, LOW);  
  delay(300);           

  digitalWrite(8, HIGH); 
  delay(300);           
  digitalWrite(8, LOW); 
  delay(300);           

}

void setColor(int red, int green, int blue) {
  analogWrite(redPin, red);
  analogWrite(greenPin, green);
  analogWrite(bluePin, blue);
}

```
