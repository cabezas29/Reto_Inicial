
# Revisión de Proyecto 

Los puntos que voy a tocar aquí son sobre todo para mejorar y reforzar huecos que tenemos en algunas areas.


> Es más facil escribir código que leerlo.
> -Joel Spolsky (Fundador de Stack Overflow)


# HTML

Para la parte de HTML los puntos que hay que recalcar son sobre todo las buenas practicas.

###  Bueno

- Estructura con sentido 

### Malo

- Utilizamos puros divs, hay más etiquetas para hacer divisiones, debemos tener una mejor estructura semántica
- Hay elementos que se podian identar mejor y no se hizo
- Hay que tener presente para que sirve cada etiqueta, en el caso del texto podiamos utilizar `p` `article` 
- Ningún elemento tiene `id` como esperas identificarlos para futuras implementaciones
- No esta adecuado para ser escalable

Nos hace falta reforzar bastante las etiquetas de HTML y las buenas prácticas.
Te recomiendo checar este repo y esta pagina para las etiquetas:
[https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references](https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references)

[https://www.w3schools.com/TAGS/default.ASP](https://www.w3schools.com/TAGS/default.ASP)

# CSS

Para esta parte lo que hay que tener en cuenta es el escalamiento de un proyecto, la redacción y el uso de las propiedades correctas

### Bueno

- Tenemos una baja especificidad en las reglas
- Le pusimos buenos comentarios a nuestras reglas

### Malo

- El nombre de las clases no tienen sentido
- No tenemos ningún sistema de diseño
- **Utilizamos solamente `px`, eso es muy muy MALO**. Para tamaño de letra se utiliza una diferente medida (em o rem), para tamaño de cosas que tengan que ver con sus padres hay más opciones y para las que tengan que ver con el tamaño de la página hay aún más, hay que ponernos a estudiar eso!
- **No hay consistencia en la organización de tu código**, hay lugares donde dejas espacios y otros donde no
- Para **los colores se deben de poner en hexadecimal** y en minúsculas
- Todo esta en un solo archivo, debemos de poder pensar en como se puede modularizar todo.

Hay que practicar muchísimo, te dejo links donde puedes encontrar lo que te puse:
[https://www.w3schools.com/cssref/css_units.asp](https://www.w3schools.com/cssref/css_units.asp)
[https://css-tricks.com/guides/](https://css-tricks.com/guides/)

# CONCLUSIÓN

En general funciona, pero ese código no es optimo para nada.
No tenemos nada nada de documentación, ni un README, ni comentarios. 
**Debemos de seguir practicando.**
