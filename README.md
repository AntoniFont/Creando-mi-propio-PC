# Descripción
Proyecto veraniego de mi tiempo libre. 

A partir de únicamente puertas lógicas (lo mas básico posible, mas simple sería soldar cables y transistores manualmente) 
diseñar un microprocesador y un ordenador completamente funcional que sea capaz de hacer los mismos cálculos que podría
hacer un ordenador o dispositivo movil común de hoy en día. 

Se podría hacer con lenguajes para construir circuitos tales como VHDL o Verilog, pero hacerlo con un diseño gráfico
es mas visual (y entretenido).

La herramienta que he usado es "Digital" de hneeman https://github.com/hneemann/Digital 

# Características
 - 6.5 kHZ,  es decir 6500 ciclos/operaciones por segundo
 - 128 Bytes de memoria, se pueden añadir mas si es necesario
 - 2166 componentes
 - Bus de 16 bits
 - 14 instrucciones

# ISA
| Instrucción | Codificación       |
|-------------|--------------------|
| ADD         | 00000 XXXXX XXXXXX |
| SUB         | 00001 XXXXX XXXXXX |
| LEFT SHIFT  | 00101 XXXXX XXXXXX |
| RIGHT SHIFT | 00110 XXXXX XXXXXX |
| NOT         | 00100 XXXXX XXXXXX |
| AND         | 00010 XXXXX XXXXXX |
| OR          | 00011 XXXXX XXXXXX |
| JMI         | 10000 XXXXX AAAAAA |
| JMN         | 10001 XXXXX AAAAAA |
| JMZ         | 10010 XXXXX AAAAAA |
| LOAD R0     | 01000 XXXXX AAAAAA |
| LOAD R1     | 01001 XXXXX AAAAAA |
| STORE R2    | 01010 XXXXX AAAAAA |
| JMC         | 10011 XXXXX AAAAAA |

Donde AAAAAA es la dirección de una posición de memoria
# Algunas imágenes
Visión principal
![Imagen Central](https://github.com/AntoniFont/Creando-mi-propio-PC/blob/00ac925d20aaf12ab89b806a4b85592d263f39f2/imagenes/ImagenCentral.PNG)
Visión global
![Imagen Global](https://github.com/AntoniFont/Creando-mi-propio-PC/blob/00ac925d20aaf12ab89b806a4b85592d263f39f2/imagenes/imagenTotal.PNG)
Unidad de Ejecución
![Unidad de ejecucion](https://github.com/AntoniFont/Creando-mi-propio-PC/blob/00ac925d20aaf12ab89b806a4b85592d263f39f2/imagenes/unidadDeEjecucion.PNG)
ALU
![ALU](https://github.com/AntoniFont/Creando-mi-propio-PC/blob/00ac925d20aaf12ab89b806a4b85592d263f39f2/imagenes/ALU.PNG)
Unidad de Control
![Unidad de Control](https://github.com/AntoniFont/Creando-mi-propio-PC/blob/00ac925d20aaf12ab89b806a4b85592d263f39f2/imagenes/unidadControl.PNG)
Memoria
![Memoria](https://github.com/AntoniFont/Creando-mi-propio-PC/blob/00ac925d20aaf12ab89b806a4b85592d263f39f2/imagenes/memoria.PNG)


