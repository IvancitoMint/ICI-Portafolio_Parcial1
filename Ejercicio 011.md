# Ejercicio 11

## Enunciado del Problema:
> Caprura n numeros enteros positivos, obtenga la suma de los cuadrados de los pares y el cubo de los impares,

## Análisis:
1. > Se pregunta cuantos  numeros se ingresaran y se almacena la respuesta en "n".
2. > Se valida que sea positivo.
3. > Se pide un numero y la respuesta se le asigna a la variable "num".
4. > Se valida que sea positivo.
5. > Se realiza la condicional "num%2==0" si es cierta, entonces, continuar en linea 6, si no, pasar a la linea 7 .
6. > Se realiza "p=p+(num*num)", pasar a linea 8.
7. > Se realiza "p=p+(num * num * num)", pasar a linea 7.
8. > Utilizamos "c=c+1" para aumentar en 1 el contador de iteraciones.
9. > .Validamso si todas las iteraciones se han cumplido, avanzar, si no, el ciclo se reptitr desde la linea 3.
10. > Se muetran en pantalla los resultado: "p" e "i".
   
## Diagrama de Flujo de Datos (DFD):
![Ejercicio 11](https://github.com/IvancitoMint/ICI-Portafolio_Parcial1/assets/145072070/b5843c7c-f0c1-4ba2-ba0f-525c0d5541db)

## Prueba de Escritorio:
![Ejercicio 11 PE](https://github.com/IvancitoMint/ICI-Portafolio_Parcial1/assets/145072070/3e4d0e73-7cef-49ab-8cee-f15ae2a6ca58)
