# Como funciona um servo motor?

# O que é um Servomotor e como funciona?

Aqui aprenderemos o que é um servomotor e como controlá-lo usando um Arduino, mais especificamente o Arduino Uno, usando a biblioteca nativa da IDE Arduino Servo.h​​

# O que é um Servomotor e como funciona?

Entre os atuadores temos um motor bem especial. Os servomotores, também chamados de servos, são muito utilizados quando o assunto é robótica. De forma simplificada, um servomotor é um motor na qual podemos controlar sua posição angular através de um sinal PWM.

![alt text](https://i2.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2017/05/img-1-servo.jpg?resize=390%2C223&ssl=1)

- Micro servo motor SG90

Dessa forma, um servomotor é um atuador eletromecânico utilizado para posicionar e manter um objeto em uma determinada posição. Para isso, ele conta com um circuito que verifica o sinal de entrada e compara com a posição atual do eixo.

![alt text](https://i2.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2017/05/img-2-servo.jpg?resize=512%2C342&ssl=1)

Controle via PWM de um servo
Como você pode ver na figura anterior, o ângulo do servomotor é proporcional ao Duty Cycle (tempo que o sinal é positivo) do sinal PWM.

Diferentemente dos motores de corrente continua ou motores de passo que podem girar indefinidamente, o eixo de um servo possui a liberdade de apenas 180º. Existem ainda alguns servos que são adaptados para girar indefinidamente, mas não entraremos nesse mérito aqui.

Servomotores geralmente possuem 3 pinos:


- Alimentação positiva (vermelho) – 5V;
- Terra (Preto ou Marrom) – GND;
- (Amarelo, Laranja ou Branco) – Ligado a um pino digital de entrada e saída;

Segue ​em anexo o esquema do circuito.