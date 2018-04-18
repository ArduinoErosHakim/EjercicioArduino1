# Práctica MarkDown by *Eros* & *Hakim*
___

### Componentes:
- Un led
- Una protoboard o breadboard
- Una placa Arduino R3

### Código fuente
~~~C
// Pin 13 has an LED connected on most Arduino boards.
// give it a name:
int led = 13;

// the setup routine runs once when you press reset:
void setup() {
  // initialize the digital pin as an output.
  pinMode(led, OUTPUT);
}

// the loop routine runs over and over again forever:
void loop() {
  digitalWrite(led, HIGH);  // turn the LED on (HIGH is the voltage level)

  delay(4000);  // se mantendrá encendido 4 segundos

  digitalWrite(led, LOW);   // turn the LED off by making the voltage LOW

  delay(1000);  // se mantendrá apagado 1 segundo
}
~~~

### Imágenes
![Imagen Arduino](D:\DAM\Entornos/de/Desarrollo\Tercera/Evaluación\arduino.jpg "Arduino")

### Funcionalidad
Realiza intervalos de luz sostenida de hasta cuatro segundos para reiniciarse de nuevo tras un segundo inactivo. 