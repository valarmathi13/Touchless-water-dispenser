const int irSensor = 2;        // IR sensor pin
const int valveControl = 3;    // LED or valve pin

void setup() {
  pinMode(irSensor, INPUT);
  pinMode(valveControl, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  int handDetected = digitalRead(irSensor);

  if (handDetected == LOW) { // Hand is detected
    Serial.println("Hand Detected - Blinking LED");

    // Blink LED slowly 3 times
    for (int i = 0; i < 3; i++) {
      digitalWrite(valveControl, HIGH);
      delay(1000);  // LED ON for 1 sec
      digitalWrite(valveControl, LOW);
      delay(1000);  // LED OFF for 1 sec
    }
  }

  delay(200); // Small delay before next check
}
