# Efectos de capa

## Crear efectos de capa

### Mask Generators

Son herramientas que crean máscaras de forma procedural.

1. Se añaden sobre una máscara negra o blanca de una capa.
2. Generan un patrón procedural.
3. Cada generador tiene parámetros ajustables para controlar el resultado.
4. Puedes combinarlos con pintura manual o filtros para refinar la máscara.

### Intelligent mask

Son herramientas que crean máscaras automáticamente en base a la información del modelo y sus mapas.

1. Se añaden sobre una máscara negra o blanca de una capa.
2. El generador analiza los mapas bakeados del modelo y genera un patrón de blanco/negro.
3. Cada generador tiene parámetros ajustables para controlar el resultado.
4. Puedes combinarlos con pintura manual o filtros para refinar la máscara.

### Fill effect

Cuando se añade un Fill Effect sobre una máscara, esta se rellena automáticamente utilizando una textura o patrón como base.

Fill effect permite cargar cualquier recurso disponible en la librería de MatPlus. Pueden utilizarse texturas procedurales, mapas grunge, patrones o incluso mapas pintados previamente.

El usuario puede modificar parámetros como el tamaño, la rotación, la proyección UV, el tiling y el balance de la textura aplicada, adaptando el resultado a las necesidades específicas del material.

Es posible apilar varios Fill Effects dentro de una misma máscara. De esta forma, se pueden combinar diferentes texturas y patrones utilizando los modos de fusión y la opacidad.

### Paint effect

El Paint Effect permite editar una máscara de forma manual con pinceles, ofreciendo control y flexibilidad para refinar o complementar máscaras.

### Mask filter

Los filtros de máscaras permiten ajustar, suavizar o transformar el resultado de una máscara ya creada.

### LinkMask

Un LinkMask se crea en una máscara para referenciar su información en otra capa. 

Los LinkMask solo guardan la información que tienen debajo. Si se hacen cambios a las capas inferiores se debe refrescar el LinkMask.

Ese LinkMask puede ser llamado desde Fill effect.

