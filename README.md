# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Underline 1
-------------

Underline 2
===========

# Formatos de enfasis

- formato letra *italica* de la primer forma.
- formato letra _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la primer forma.
- formato ~~tachado~~, formato normal.
- aquí podemos usar italica *formato italico*, pero tamnien **bold** y ~~tachado~~.

# Listas

1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links

- <a href="http://www.google.com"> Esto es un link HTML</a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imágenes 

![Logo Gitchub](https://3.bp.blogspot.com/-Vknrk6s3U18/Upcf-6kCnDI/AAAAAAAAD2E/04uzk-7-0ak/s1600/git-logo.png)

# Code Snippets
Código en JSON
~~~JSON
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
~~~

Código en JavaScript
~~~JavaScript
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
~~~