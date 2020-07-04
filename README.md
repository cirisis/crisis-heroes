# crisis-heroes
#artificial_irrigation


{Arduino codes}

İnt sensorPin =9;
İnt buzzerPin =8;
İnt melumat;
Void setup () {
pinMode (sensorPin, İNPUT);
pinMode (buzzerPin, OUTPUT);
}
void loop ()  {
nelumat=digitalRead (sensorPin);
if (melumat ==true) {
digitalWrite(buzzerPin, HIGH);
delay (100);
digitalWrite(buzzerPin,LOW);
delay (100);
}
else {
digitalWrite(buzzerPin, LOW);
}
}



