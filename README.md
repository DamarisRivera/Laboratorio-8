# Laboratorio-8-3P
# 1. OBJETIVOS 

**Objetivo General:**

* Analizar y comprender experimentalmente el comportamiento de una onda senoidal dentro del simulador virtual, donde se utilizara el osciloscopio para ver como se presenta la onda y analizar las características que se presentan y reconocer como estas afectan la forma de la onda.

**Objetivo Específicos:**

* Elaborar el circuito simplificado en el simulador DCACLAB.

* Identificar los caracteristicas que afectan la onda senoidal.

* Entender la onda y responder las preguntas planteadas.

* Leer los valores que presenta la gráfica y concluir.

# 2. MARCO TEORICO 

![image](https://user-images.githubusercontent.com/105617383/186017479-f412f6b5-c9e9-4283-a0e8-24b6c84eede5.png)

# 3. EXPLICACIÓN DEL PROCEDIMIENTO 

**Material y equipo requerido**

![image](https://user-images.githubusercontent.com/105617383/186023453-9a04e24e-8675-4329-aafe-0a241c048c0e.png)

7.5.1. Implemente el circuito que se presenta en la figura 7.1

![image](https://user-images.githubusercontent.com/105617383/186023577-a636292d-bcce-4a24-8da0-b9529e627fd1.png)

8.5.2.. Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

![image](https://user-images.githubusercontent.com/105617383/186024716-61a9c396-0c76-4aea-9313-e95b8740288b.png)

8.5.3. Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.

![image](https://user-images.githubusercontent.com/105617383/186031368-344c367d-22cb-4cca-b7bb-debbd461ac9e.png)

![image](https://user-images.githubusercontent.com/105617383/186031383-cc9b27c0-b395-464c-abe1-90bce9957295.png)

8.5.4. Responda las siguientes preguntas:

¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

La amplitud pico abarca 2.3 cuadros aproximadamente.
¿En qué valor está posicionada la perilla VOLTS/DIV?

Esta posisionado en el valor de 3v
¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

Un ciclo completo abarca cuatro cuadros.
¿En qué valor está posicionada la perilla TIME/DIV?

Esta posicionado en el valor de 0.1ms.
8.5.5.¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?

Amplitud de voltaje:
Como cada cuadro equivale a 3V y se observa 2 cuadros y un poco mas entonces da un valor aproximado de 6.8 (V)
Periodo:

Un ciclo es de 4 cuadros y esto se va a multiplicar po el valor de la perilla TIME/DIV que es de 0.0001 ms
4(0.0001) = 0.0004 s
T = 0.0004s

8.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

Se va a usar el periodo anteriormente encontrado en la siguiente formula:
fn = 1/T
fn = 1/0.0004
fn: 2500 (Hz)

ω: 2πf
ω: 2π(2500)
ω: 15707,96 (rad/s)

8.5.7. Con el multímetro digital mida el voltaje de salida en RL: 4.833 V

image

8.5.8. Compare el voltaje medido en el punto 8.5.5. y el obtenido en el punto 8.5.7.

No coinciden, esto se debe a que el osciloscopio da el valor del voltaje pico, mientras que el multimetro da un valor eficas es decir Vrms, esto pasa puesto que el multimetro da el 71% del valor del voltjae pico, si se quiere obtener el valor que da el osiloscpoio se debe usar la siguiente formula Vp = Vrms(0.707), reemplazando los valores Vp = 4.833(0.707), nos da Vp = 6.9 V que es el valor que da el osiloscopio.

# 4.RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR


# 5.VIDEO



# 6.CONCLUSIONES

* 

# 7.BIBLIOGRAFÍA

Floyd, Thomas. 2007. Principios de circuitos eléctricos. Octava edición.
