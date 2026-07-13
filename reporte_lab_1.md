# Reporte Laboratorio 1
+ Ana Laura Tschen 221645
+ Karen Pineda 231132

## Datos de la otra pareja
+ Pablo Méndez
+ Carolina

## Preguntas

### 3.1 Transmisión de Códigos
+ **¿Qué esquema (código) fue más fácil de transmitir y por qué? ¿Qué esquema (código) fue más difícil de transmitir y por qué?**
R: El esquema de codigo más fácil de transmitir fue el Baudot, debido a que ya tenía como sus tiempos definidos. Mientras que el más difícil de transmitir fue el morse, porque dependía mucho de la persona si el tiempo para representar el dash o el punto. Si uno pulsa bastante rápido uno se pierde y se terminan juntando las letras, haciendo que no se pueda interpretar donde termina con exactitud la letra.

+ **¿Qué esquema tuvo menos errores (incluir datos que lo evidencien)?**
R: El morse tuvo menos errores, porque el Baudot es un poco más difícil de captar por los tiempos tan rápidos. 

``` 
Mensaje Original (Utilizando código Morse): Buenas noches

```
Resultado
![alt text](image.png)

![alt text](image-2.png)

### 3.2 Transmision empaquetada
+ **¿Qué dificultades involucra el enviar un mensaje de forma “empaquetada”?**
R: Las dificultades que involucra enviar un mensaje de forma empaquetada son el conocer bien que código se está utilizando y poder comprender bien como se representan las letras. También puede llegar a ser dificil reconocer las pausas. Este método también requiere mayor atención y tiempo para elaborar bien las codificaciones.
![alt text](image-1.png)

![alt text](image-3.png)

### 3.3 Conmutación de Mensajes

+ **¿Qué posibilidades incluye la introducción de un conmutador en el sistema?**
El conmutador puede servir como un regulador o elemento que dirige los mensajes, lo cual puede mejorar la comunicación entre las personas, ya que existe más orden. Pero también podría traer dificultades como saturación si se envian mensajes al mismo tiempo o pérdida de la integridad de los datos ya que podria llegarle un mensaje a la persona equivocada si no se define correctamente un protocolo de comunicación.

+ **¿Qué ventajas/desventajas se tienen al momento de agregar más conmutadores al sistema?**
Si se agregan más conmutadores se podría ampliar la capacidad de comunicación, es decir, poder comunicarse con más clientes a la vez y reducir la carga para el conmutador, sin embargo, el punto clave es la organización o administración que se tenga en el proceso, ya que si no se hace bien podría ocurrir la pérdida de información.

+ **Forma definida para comunicarse**
Para comunicarnos de forma ordenada y evitar confusiones, definimos que cada cliente debía identificarse ante el conmutador indicando si era el emisor o el receptor mediante las iniciales de su nombre. Por ejemplo, si Ana era la emisora, se identificaría como AE (A = inicial del nombre, E = emisor), mientras que el receptor se identificaría con la inicial de su nombre seguida de R. Además, para evitar sobrecargar al conmutador, cada cliente tendría un turno o un tiempo de espera para enviar sus mensajes, permitiendo que el conmutador los procesara y los entregara correctamente antes de recibir nuevos. En dado caso el conmutador no estuviera listo para recibir mensajes, tendría que indicarlo enviando un mensaje a todos los clientes.
