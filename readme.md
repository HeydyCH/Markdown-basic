# SINTAXIS BASICA DE MARKDOWN

Markdown es un lenguaje de marcado de texto plano que te permite añadir estilo, imágenes y enlaces a un simple documento de texto. Puedes usar Markdown para dar formato al texto de tus ideas en Spines.

---
## Titulos
Puede usar un `#` hasta llegar a `######` seis para diferentes tamaños de encabezado.

    # Esto es un titular de tamaño 1
    ## Esto es un titular de tamaño 2
    ### Esto es un titular de tamaño 3
    #### Esto es un titular de tamaño 4
    ##### Esto es un titular de tamaño 5
    ###### Esto es un titular de tamaño 6


# Esto es un titular de tamaño 1
## Esto es un titular de tamaño 2
### Esto es un titular de tamaño 3
#### Esto es un titular de tamaño 4
##### Esto es un titular de tamaño 5
###### Esto es un titular de tamaño 6

---
## Cursiva

    Escribe en _cursiva_ para dar énfasis o *otra forma de cursiva*  .

Escribe en _cursiva_   para dar énfasis o *otra forma de cursiva*  .

---
## Negrita

    Usando **negrita** y _cursiva_ para dar _**énfasis al extremo**_.

Usando **negrita** y _cursiva_ para dar _**énfasis al extremo**_.

---

## Tachado

    Ella ~~nació~~ creció en Peru.

Ella ~~nació~~ creció en Peru.

---

## Enlaces
     Es directo : http://spines.me

Es directo :  http://spines.me

Puedes crear enlaces HTML más complejos con la siguiente sintaxis:

    [The New York Times](http://www.nytimes.com) es un periódico.

[The New York Times](http://www.nytimes.com) es un periódico.

---


## Imágenes

    ![Imagen de ejemplo de One Piece](https://cdn.hipwallpaper.com/i/83/67/ijRFLv.jpg)


![Imagen de ejemplo de One Piece](https://cdn.hipwallpaper.com/i/83/67/ijRFLv.jpg)


Si desea insertar imágenes, así es como lo hace 


---

## Texto Citado

    > Café. La mejor suspensión orgánica que se haya ideado ... Le gané a los Borg con ella. 
    
> Café. La mejor suspensión orgánica que se haya ideado ... Le gané a los Borg con ella.



---

## Bloques de código

    `var example = true`  


`var example = true`

Para un bloque de código más largo, puede sangrar con **4 espacios**: 

    $(function(){
        $('div').html('Hola, mundo');
    });


o ponerlo del sgte modo

    `` `
    $(function(){
        $('div').html('Hola, mundo');
    });
    `` `

`` `
$(function(){
    $('div').html('Hola, mundo');
});
`` `

` `` javascript 
if (isAwesome) { 
  return true 
} 
`` `


---

## Tablas

    | Modelo | Color   | Precio |
    | ------ |---------| ------:|
    | Globe  | Negro   | 99€    |
    | Scala  | Azul    | 199€   |
    | Palais | Granate | 399€   |

| Modelo | Color   | Precio |
| ------ |---------| ------:|
| Globe  | Negro   | 99€    |
| Scala  | Azul    | 199€   |
| Palais | Granate | 399€   |


---
A veces deseamos listas numeradas: 

    1. Una 
    2. Dos 
    3. Tres 


1. Una 
2. Dos 
3. Tres 

A veces se desea viñetas: 

    * Comience una línea con una estrella 
    - Los guiones funcionan igual de bien 
        - pto secundario (se pone 2 espacios antes del * o - )
    - Y si tiene puntos secundarios, ponga dos espacios antes del guión o estrella: 
      - Así 
      - Y esto
 
 * Comience una línea con una estrella 
- Los guiones funcionan igual de bien 
    - pto secundario (se pone 2 espacios antes del * o - )
- Y si tiene puntos secundarios, ponga dos espacios antes del guión o estrella: 
  - Así 
  - Y esto
---
## EXTRAS

Comentario a alguien, puedes prefijar su nombre con el símbolo @: Hey @kneath: ¡ama tu suéter!

**Listas de tareas** : 

    - [x]  Este es un elemento completo 
    - [] Este es un elemento incompleto 

- [x]  Este es un elemento completo 
- [] Este es un elemento incompleto 

**Emojis !!**

:destellos:camello::auge:


---
