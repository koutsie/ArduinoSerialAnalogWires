# ArduinoSerialAnalogWires
Connect some wires and see stuff happen!
------
[![ko-fi](https://www.ko-fi.com/img/donate_sm.png)](https://ko-fi.com/R6R3HDMB)

## How to?
Download the project file or copy the code straight to your ide!

After starting up the ide, connect your arduino and start the serial monitor.
Now, take a wire and connect it to the *ground* and the other end to *analog in 1*.

Have fun with this extremely simple peace of code ment to be a school demo!
--------
```c++
long randNumber;
int analogPin = 0;     // Where to connect the first end of the wire
int val = 0;         // The variable to store if the wire is connected
int lastval = 0; // this is the last value buffer used later for some nice random number logic :3 



void setup()

{
  Serial.begin(9600);              // Lets setup the serial
  val = analogRead(analogPin);
  pinMode(LED_BUILTIN, OUTPUT);
  randomSeed(analogRead(0));
}



void loop()
                    {
  val = analogRead(analogPin); // if we dont get a solid analog input well just call it a day
  if (val > 0) {

          val = analogRead(analogPin);
            lastval = analogRead(analogPin);
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
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");
    Serial.println("\n");


    
    delay(100); // wait 100ms for fun
    
   digitalWrite(LED_BUILTIN, LOW); // turn on led
   
  Serial.print("Analog reports: ");
  Serial.print(val);  // print the analogs value.
  
  Serial.print("\n"); // newline again
  
  randNumber = random(100, 1000); // lets get a random number for fun
  int a = randNumber;
  int b = lastval;
  int  sum = a + b; // lets sum the two variables and get nice results
  
  Serial.println("Heres your random number:  ");
  Serial.println(sum); // print that number already :3

  
  Serial.print("\n");
  Serial.println("You did it!"); // gongratz <3

  
  delay(100000000); // stop execution since were done here
  }
}




// This all for a school demo. Maybe.
// Yes i know i shoud do this and that and while and loops, stop it.
```
