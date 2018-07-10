# hello-world
Arduino: Prints "Hello World!" in Serial monitor every 1500ms through serial connection 9600 Bd.

void setup() {
  // Open serial connection at 9600 Bd.
  Serial.begin(9600);
}
void loop() {
  // Print "Hello World!" in the Serial monitor every 1500ms.
  Serial.println("Hello World!");
  delay(1500);
  Serial.println("Hey world!");
  delay(1500);
}
