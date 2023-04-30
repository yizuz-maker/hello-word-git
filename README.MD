# Cabeceras

# Cabecera H1

## Cabecera H2

### Cabecera H3

#### Cabecera H4

##### Cabecera H5

###### Cabecera H6

# Formatos de Enfasis

- formato _italica_ de la primer forma.
- formato _italica_ de la primer forma.

- formato **bold o strong** de la primer forma
- formato **bold o strong** de la segunda forma

- formato ~~tachado~~.
- <u> underline </u>

Se puede usar _italica_, se puede usar **bold** y se puede ~~tachar~~. Pero además, se puede hacer todo _**~~combinado~~**_

# Listas

1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links

- [Esto es un link en markdown](http://www.google.com)
- [Esto es un index](index.html)
- [Esto es una cabecera](#cabeceras)

# Imagenes

![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets

Codigo en JSON

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

Codigo en JavaScript

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
| Maxi   | Burgos   | 34857345  |
| Tomas  | Thompson | 12452678  |

# Citas

Esto es un texto referente a una cita que pondremos debajo:

> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:

> Esto es otra cita

# Lineas divisoras

Esto es un texto que será dividido

---

Dividido por guion.

---

Dividido por asteriscos

---

Dividido por guiones bajos

# Saltos de linea

Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo

Esto es nuestro tercer parrafo
