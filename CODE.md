# BlinkName
The code that blinks my name in morse code using Argon!


// My name in Morse code


int led = D7;        // Assigning the LED as a variable to make it easier and cleaner


void setup() 
{
    
    pinMode(led, OUTPUT);       // Setting up the D6 as an output

}

void loop() {


    // The letter J
    
    digitalWrite(led, HIGH);        
    delay(250);
    digitalWrite(led,LOW);
    delay(250);
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(750);
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(750);
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(1000);
    
    // The letter O
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(750);
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(750);
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(1000);
    
    // The letter N
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(750);
    
    digitalWrite(led, HIGH);        
    delay(250);
    digitalWrite(led,LOW);
    delay(1000);
    
    // The letter A
    
    digitalWrite(led, HIGH);        
    delay(250);
    digitalWrite(led,LOW);
    delay(250);
    
    digitalWrite(led,HIGH);
    delay(750);
    digitalWrite(led,LOW);
    delay(3000);            // Slowly restart the loop
    
    
}


