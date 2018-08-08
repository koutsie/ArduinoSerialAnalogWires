# ArduinoSerialAnalogWires
Connect some wires and see stuff happen!
[![ko-fi](https://www.ko-fi.com/img/donate_sm.png)](https://ko-fi.com/R6R3HDMB)
## How to?
Download the project file or copy this code straight to the ide:


```arduino
int analogPin = 0;     // Where to connect the first end of the wire
int val = 0;         // The variable to store if the wire is connected

void setup()
{
  Serial.begin(9600);              // Lets setup the serial
  val = analogRead(analogPin);
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
                    {
  val = analogRead(analogPin); // if we dont get a solid analog input well just call it a day
  if (val > 0) {

          val = analogRead(analogPin);
                Serial.println("\n");
            Serial.println("Please connect the cables :3");
            
            Serial.print("Analog reports: ");
            Serial.print(val);
            Serial.println("!");
            Serial.println("\n");

            
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
          delay(2000);
          
    
}

else if (val = 200) {

          val = analogRead(analogPin); // if we get a 200, wow.
                Serial.println("\n");
            Serial.println("How did you get 200?");
            
            Serial.print("Analog reports: ");
            Serial.print(val);
            Serial.println("!");
            Serial.println("\n");

            
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
          delay(10000);
          
    
}
else if (val = 365) {

          val = analogRead(analogPin); // if we get a 365, wow.
                Serial.println("\n");
            Serial.println("Using some tools huh :3 (or just lucky?)");
            
            Serial.print("Analog reports: ");
            Serial.print(val);
            Serial.println("!");
            Serial.println("\n");

            
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
            delay(111);
            digitalWrite(LED_BUILTIN, HIGH);
            delay(111);
            digitalWrite(LED_BUILTIN, LOW);
          delay(10000);
          
    
}
  else {
    val = analogRead(analogPin); // if we get a solid input well proudly show it
    
    Serial.println("\n"); // Print
    Serial.println("\n"); // a
    Serial.println("\n"); // whole
    Serial.println("\n"); // bunch
    Serial.println("\n"); // of 
    Serial.println("\n"); // newlines
    Serial.println("\n"); // to
    Serial.println("\n"); // get
    Serial.println("\n"); // clearer
    Serial.println("\n"); // output
    Serial.println("\n"); // thats
    Serial.println("\n"); // all
    Serial.println("\n"); // for
    Serial.println("\n"); // tonight
    Serial.println("\n"); // folks
    Serial.println("\n"); // :3
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    
    delay(100); // wait 100ms for fun
    
  Serial.println("Analog reads:");
  Serial.print(val);  // print the analogs value.
  
  delay(3000); // wait 3 seconds before anything else.
  }
}

// This all for a school demo. Maybe.```
