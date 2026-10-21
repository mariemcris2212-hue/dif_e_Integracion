Práctica: Métodos Numéricos - Simpson 1/3 Compuesto y Trapecio Compuesto

Instrucciones de Compilación y Ejecución

Opción A: Desde la Terminal (Línea de comandos)
1. Abre la terminal y ubícate en la carpeta raíz del proyecto (donde se encuentra la carpeta `src`).
2. Compila todas las clases ejecutando:
   ```bash
   javac src/dif_e_Integracion/*.java
   Ejecuta el método de Trapecio Compuesto:Bashjava -cp src dif_e_Integracion.MainTrap

Ejecuta el método de Simpson 1/3 Compuesto:Bashjava -cp src dif_e_Integracion.MainSim

Ejemplos de Salida en Consola

Evaluando la función f(x) = x^2 en el intervalo [0.0, 2.0] con una tolerancia de 0.0001:1. 
Salida de Trapecio Compuesto (MainTrap)

--- ITERACIONES (TRAPECIO COMPUESTO) ---
n = 2 | Integral = 3.0

n = 4 | Integral = 2.75 | Error = 0.25

n = 8 | Integral = 2.6875 | Error = 0.0625

n = 16 | Integral = 2.671875 | Error = 0.015625

n = 32 | Integral = 2.66796875 | Error = 0.00390625

n = 64 | Integral = 2.6669921875 | Error = 9.765625E-4

n = 128 | Integral = 2.666748046875 | Error = 2.44140625E-4

n = 256 | Integral = 2.66668701171875 | Error = 6.103515625E-5

Convergencia en 7 iteraciones con n = 256 subintervalos

Resultado final: 2.66668701171875


2. Salida de Simpson 1/3 Compuesto (MainSim)

--- ITERACIONES (SIMPSON 1/3 COMPUESTO) ---

n = 2 | Integral = 2.6666666666666665

n = 4 | Integral = 2.6666666666666665 | Error = 0.0

Convergencia en 1 iteraciones con n = 4 subintervalos

Resultado final: 2.6666666666666665
