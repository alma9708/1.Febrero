# 1.Febrero
Encendido y apagado de tres leds.
int AZUL=13;
int VERDE=11;
int ROJO=9;
void setup() {
pinMode(AZUL, OUTPUT);
pinMode(VERDE, OUTPUT);
pinMode(ROJO,OUTPUT);

// put your setup code here, to run once:

}

void loop() {
digitalWrite(AZUL,HIGH);
delay (100);
digitalWrite(AZUL,LOW);
delay (400);

digitalWrite(VERDE,HIGH);
delay (100);
digitalWrite(VERDE,LOW);
delay (400);

digitalWrite(ROJO,HIGH);
delay (100);
digitalWrite(ROJO,LOW);
delay (400);

// put your main code here, to run repeatedly:

}
