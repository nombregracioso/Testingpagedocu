# Máscaras

## Crear máscaras

Para crear una máscara tenemos un botón que nos despliega varias opciones:

### White mask

Este boton crea una máscara blanca en la capa seleccionada.

Una máscara blanca significa que todo el efecto de la capa es visible en esa zona.

### Black mask

Este boton crea una máscara negra en la capa seleccionada.

Una máscara negra significa que la capa está completamente oculta en esa zona.

!!! example ""
    Si añades una máscara blanca a una capa, por defecto la capa se aplicará en toda la superficie del modelo.

    A partir de ahí puedes pintar en negro o con grises para ocultar o revelar solo ciertas partes.

### Mask UV

Este botón crea una máscara negra por defecto y asigna blanco únicamente a la isla UV que selecciones.

Cada isla UV se trata como una “zona independiente” a la que puedes aplicar materiales o efectos.

!!! example "Ejemplo de uso típico"
    Si tu modelo es un coche con un solo material pero con varias islas UV (carrocería, ventanas, ruedas), puedes añadir un UV Mask en una capa de pintura roja y decirle que solo afecte a la isla UV de la carrocería, sin tocar las ruedas ni las ventanas.

### Mask mesh island

Este botón crea una máscara que identifica automáticamente cada isla de geometría en el modelo.

Permite aplicar materiales distintos a cada pieza de la geometría dentro de un mismo material, sin necesidad de separarlos ni pintar máscaras manualmente.

### Mask vertex color

Este botón crea una máscara negra por defecto y asigna blanco únicamente al vertex color que selecciones.

### Mask object ID

Este botón crea una máscara negra por defecto y asigna blanco únicamente al object ID que selecciones.

## Flujo de trabajo

Al crear una máscara en la capa se nos activa un boton para poder trabajar con las máscaras.

Las máscaras aparecen cuando tenemos la capa seleccionada y estamos en el modo de trabajo de máscara

Las máscaras se organizan justo debajo de la capa seleccionada y trabajan de una manera similar a las capas. Tambien tienen el mismo orden de prioridad que las máscaras

## Acciones de máscara

### Visibilidad de la máscara

Podemos alternar la visibilidad de la capa con el boton en forma de ojo.

### Nombre de la máscara

Podemos cambiar el nombre de la máscara haciendo doble click sobre el.

### Modo de fusión

Esta es una opcion desplegable que nos muestra todas las opciones de fusión de la máscara seleccionada.

### Eliminar máscara

Podemos eliminar la máscara haciendo click sobre la X.