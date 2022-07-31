# `22` Integral

Dado un número integral n, escribe un programa para generar un diccionario que contenga (i, i*i) como un número integral entre 1 y n (ambos incluidos). Luego el programa debiese imprimir el diccionario.
## 📝 Instrucciones:

1. Crea una función llamada `generate_dict`.
2. La función deberá retornar un diccionario con la cantidad de keys que se pasen por parametro (comenzando desde el uno).

## Ejemplo de entrada:

```py
generate_dict(8)
```
## Ejemplo de salida:

```py
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25, 6: 36, 7: 49, 8: 64}
```

## 💡 Pistas:

En el caso de que se le entreguen datos a la pregunta, deben asumirse como entradas de la consola. 
Considera usar dict()
