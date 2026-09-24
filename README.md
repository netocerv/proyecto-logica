# Proyecto: Validador de Argumentos Lógicos

**Materia:** Lógica y Estructuras Discretas  
**Institución:** ITESO  
**Integrantes:** [Escribe aquí los nombres y números de expediente]  
**Profesor:** [Nombre del profesor]  
**Fecha:** 24 de septiembre de 2026

## Descripción
Este programa determina si un argumento lógico es válido. Permite al usuario ingresar hasta 3 premisas y una conclusión, utilizando las proposiciones primitivas `p`, `q`, `r` y los operadores lógicos `and`, `or`, `not` y `→` (implicación).

Además, incluye una pestaña con las **tablas de verdad** de las proposiciones ingresadas y un botón de **Random** para generar ejemplos automáticos.

## Instrucciones de Uso
1. Abre el archivo `index.html` en tu navegador web.
2. En la pestaña **Validador**, ingresa las premisas y la conclusión.
3. Usa `p`, `q`, `r` para las variables.
4. Usa `and`, `or`, `not` para los operadores.
5. Usa `→` para la implicación (o su equivalente `not A or B`).
6. Usa paréntesis `( )` para agrupar proposiciones compuestas.
7. Presiona el botón **Validar Argumento** para ver el resultado.
8. Presiona el botón **🎲 Random** para generar un ejemplo aleatorio.
9. Cambia a la pestaña **Tablas de Verdad** y presiona **Mostrar Tablas de Verdad** para ver las tablas completas.

## Ejemplos
- **Válido:** P1: `(p → q)`, P2: `p`, C: `q`
- **No Válido:** P1: `(p → q)`, P2: `not p`, C: `q`

## Tecnologías Usadas
- HTML5
- CSS3
- JavaScript

## Créditos y Referencias
- Inspirado en la herramienta [Academia LAP](https://academialap.com/Comprobador_validez_argumentos_online.html).
- Código generado con asistencia de IA (Gemini) para fines educativos.