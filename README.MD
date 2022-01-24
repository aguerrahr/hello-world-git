# Version del curso
Version Actual: V1.2.2
# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4

##### Cabecera H5

###### Cabecera H6

# Underlines
Underline 1
-----------
Underline 2
===========
# formatos de enfasis
- formato *itálica* de la preimer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- auí podemos usar formato *italico* pero tambien **bold** y ~~el tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es una lista desordenada.
- Esto es una lista desordenada.
- Esto es una lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)
# Imagenes
![Logo GitHub](https://www.fullstackpython.com/img/logos/markdown.png)
# Code Snippets
Código en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código Javascript
```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Andrés | Guerra | 123332 |
| Flores | Duran | 58522 |


# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no esta relacionada con la cita anterior:
> Esto es otra cita.

# Lineas divisoras
Esto es un texto que sera division

------
Esto es otro texto dividido po asteriscos

****

Esto es un texto dividido por guines bajos

___

# Saltos de linea

Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es un tercer parrafo.
- Linea del parrafo
