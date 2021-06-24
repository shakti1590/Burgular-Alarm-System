# Burgular-Alarm-System
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  digitalWrite(13, HIGH);

  tone(8, 1661, 1000); // play tone 80 (G#6 = 1661 Hz)
  delay(10); // Delay a little bit to improve simulation performance
}
