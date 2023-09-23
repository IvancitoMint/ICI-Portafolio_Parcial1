# Ejercicio 14

## Enunciado del Problema:
> Una empresa desea calcular el sueldo base total de una persona bajo los siguientes rubros: sueldo base, 5% de canasta basica, 3% de prima de antiguedad y deducciones; si el salario base excede los $10,000, el impuest ISR es del 30% y si es menos que eso, sera del 20%.
> Indique cuanto es el total de la nomina a pagar y cuantos son los impuestos que el patron debe pagar al SAT.

## Análisis:
1. > Pregunar la cantidad de empleados y almacenar la respuesta en "np".
2. > Se valida que sea un numero positivo.
3. > Preguntar el salario base del trabajador y la respuesta se le asigna a la variable "sb".
4. > Se valida que sea un numero positivo.
5. > Se realiza "sb>10000" para saber cuanto sera el impuesto aplicado.
6. > Se realiza "sb*0.05" para la canasta basica.
7. > Se realiza "pa=sb*0.03" para la prima de antiguedad.
8. > Se realiza "isr=sb*0.3" para el 30% de ISR.
9. > Se realiza "sb*0.05" para la canasta basica.
10. > Se realiza "pa=sb*0.03" para la prima de antiguedad.
11. > Se realiza "isr=sb*0.2" para el 20% de ISR.
12. > Con "imp=imp+isr" almacenaremos el impuesto que debera pagar el patron.
13. > Calculamos el total de la nomina de cada trabajador usando "tn=(sb-isr)+(cb+pa)".
14. > Imprimimos la nomina total.
15. > Utilizamos "c=c+1" para aumentar el contador de iteraciones.
16. > Validamos si "c<np" para saber cuantas iteraciones han ocurrido.
17. > Imprimimos los impuestos que el patron debe pagar "imp".
    
## Diagrama de Flujo de Datos (DFD):
![Ejercicio 14](https://github.com/IvancitoMint/ICI-Portafolio_Parcial1/assets/145072070/a62cf056-e21c-4965-bef0-e939714f1b41)

## Prueba de Escritorio:
![Ejercicio 14 1 PE](https://github.com/IvancitoMint/ICI-Portafolio_Parcial1/assets/145072070/49bb1def-2968-47c5-9885-1a99c3a4378e)
![Ejercicio 14 2 PE](https://github.com/IvancitoMint/ICI-Portafolio_Parcial1/assets/145072070/48033c58-c907-41c8-8534-bc2b44a3aae6)
![Ejercicio 14 3 PE](https://github.com/IvancitoMint/ICI-Portafolio_Parcial1/assets/145072070/748554fa-66ab-4af4-adc7-64a326aa6eaf)
