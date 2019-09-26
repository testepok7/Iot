# Projeto 4 - Utilização do NODEMCU + Botão

### Passo 0 - Preparar o Ambiente Arduino - IDE
Adicionar em preferencias->URL adicionais para gerenciamento de placas : http://arduino.esp8266.com/stable/package_esp8266com_index.json

Link com tutorial para instalar a placa ESP e programas iniciais para a placa
https://www.filipeflop.com/blog/programar-nodemcu-com-ide-arduino/


### Passo 1 - Executar Blink no NODEMCU ESP 
```C++
void setup() {
// Define o pino 2 como saida
pinMode(2, OUTPUT);
}
void loop() {
digitalWrite(2, HIGH); // Acende o Led
delay(3000); // Aguarda 3 segundo
digitalWrite(2, LOW); // Apaga o Led
delay(3000); // Aguarda 3 segundo
}
```
