# Cabeceras 
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# underlines
Underline 1
------------

Underline 2
===========

# Formatos de emphasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada. 
- Esto es un item de lista desordenada. 
- Esto es un item de lista desordenada. 

# Links
- [Esto es un link](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo github](https://cdn-icons-png.flaticon.com/512/25/25231.png)

# Code Snippets
Código en json
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
Código en javascripts
```javascript
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
| Nombre | Apellido | Documentos |
| ------ | -------- | ---------- |
| Maxi |Burgos | 2354654 |
|Tomas | Thompson | 356897 |

# Citas
Esto es un texto referente a una cita que pondremos debajo.
> Esto es una cita

Las citas deben tener un espacio.

Esto es otro texto que no se relaciona con la cita anterior.
> Esto es otra cita.

# Lineas divisoras
Esto es un texto que será dividido por guiones.

---
Esto es otro texto dividido por asteriscos

***
Esto es otro texto dividido por guiones bajos

___

