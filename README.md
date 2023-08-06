# html# Calculadora

Esta es una calculadora simple con operaciones de suma, resta, multiplicación y división. Permite ingresar dos operandos, seleccionar un operador y calcular el resultado.

## Casos de Prueba

A continuación se describen algunos casos de prueba realizados para validar el funcionamiento de la calculadora:

1. **Suma de dos números:**  
   Operandos: 5 y 3  
   Operador: +  
   Resultado esperado: 8  
   Resultado obtenido: 8

2. **Resta de dos números:**  
   Operandos: 10 y 4  
   Operador: -  
   Resultado esperado: 6  
   Resultado obtenido: 6

3. **Multiplicación de dos números:**  
   Operandos: 7 y 2  
   Operador: *  
   Resultado esperado: 14  
   Resultado obtenido: 14

4. **División de dos números:**  
   Operandos: 15 y 3  
   Operador: /  
   Resultado esperado: 5  
   Resultado obtenido: 5

5. **División por cero:**  
   Operandos: 8 y 0  
   Operador: /  
   Resultado esperado: Mensaje de error ("No se puede dividir por cero")  
   Resultado obtenido: Mensaje de error ("No se puede dividir por cero")

6. **Operación con número inválido:**  
   Operandos: 4 y "abc"  
   Operador: +  
   Resultado esperado: Mensaje de error ("Ingresa números válidos en ambos campos")  
   Resultado obtenido: Mensaje de error ("Ingresa números válidos en ambos campos")

7. **Resultado demasiado grande:**  
   Operandos: 1e100 y 2  
   Operador: *  
   Resultado esperado: Mensaje de error ("Resultado fuera de rango")  
   Resultado obtenido: Mensaje de error ("Resultado fuera de rango")

8. **Borrado de campos:**  
   Ingresar operandos y calcular, luego borrar  
   Resultado esperado: Campos de operandos y resultado vacíos  
   Resultado obtenido: Campos de operandos y resultado vacíos

## Observaciones

La calculadora ha sido probada en varios casos para asegurar su funcionamiento correcto. Los resultados obtenidos coincidieron con los resultados esperados en todos los casos de prueba.

