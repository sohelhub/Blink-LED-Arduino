# Blink-LED-Arduino
A simple Arduino sketch to blink the built-in LED at 1-second intervals. Ideal as a beginner project to test the basic functionality of an Arduino board.

void setup() {
 
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);  
  delay(1000);                      
  digitalWrite(LED_BUILTIN, LOW);   
  delay(1000);                      
}
