#include "DigiMouse.h"

void setup() {
  DigiMouse.begin();
  pinMode(1, OUTPUT);
}

void loop() {
  DigiMouse.update();
  digitalWrite(1, HIGH);    // turn LED on
  DigiMouse.move(1,0,0,0);  // Move mouse
  DigiMouse.delay(1000);    // wait a second
  DigiMouse.move(-1,0,0,0); // Move mouse back
  digitalWrite(1, LOW);     // turn LED off
  DigiMouse.delay(60000);   // wait a minute
}
