# Instrucciones

Ahora tienes la oportunidad de crear una calculadora mejor. Tu calculadora puede funcionar como desees, pero debe ser útil como una calculadora.

Primero, vamos a separar nuestra lógica interactiva en la función `main()`, de la siguiente manera:

```
def main():
  print("Hello, learners!")

if __name__=="__main__":
  main()
```

Este es un código boilerplate (plantilla) de Python que solo se ejecutará cuando el programa sea invocado por una persona. Ahora, todo tu código debe estar dentro de una función, ya sea esta función `main()` (donde puedes colocar cosas como declaraciones de entrada) u otra función.

La calificación automática se hará sobre 8 puntos y evaluará la funcionalidad de las siguientes funciones:  
⭐`addmultiplenumbers([num, num, ..])` - Esta función debe existir en tu programa, debe tomar una lista de números como entrada y debe generar la suma de esos números.  
⭐`multiplymultiplenumbers([num, num, ..])` - Esta función debe existir en tu programa, debe tomar una lista de números como entrada y debe generar el resultado de multiplicar cada número con el siguiente.  
⭐`isiteven(num)` - Esta función debe existir en tu programa, debe tomar un solo número como entrada y debe generar un valor booleano:`True`  si el número es un número entero par, `False` en caso contrario.  
⭐`isitaninteger(num)` - Esta función debe existir en tu programa, debe tomar un solo número como entrada y debe generar un valor booleano:`True` si el número es un número entero, `False` en caso contrario.

**Recuerda:** Este proyecto será calificado automáticamente, ¡y las computadoras son muy literales!

**Nota:** ¡Usa las pruebas! No hay nada de malo en ejecutar las pruebas hasta que pasen. ¡No es hacer trampa!

**Nota:** Si te quedas atascado intentando que una función funcione, prueba a trabajar en otra. Puede que descubras que puedes resolver funciones posteriores más rápido que las primeras.