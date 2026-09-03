# DIIW UT01: Planificación de interfaces gráficas

## Teoría del color aplicada a la web

El color crea identidad, establece jerarquía, comunica estados y dirige la atención. Una paleta debe responder a las necesidades de la interfaz y generar variantes suficientes para fondos, textos, bordes, acciones y mensajes del sistema.

El color nunca debe ser el único medio para comunicar información: hay que acompañarlo con texto, iconos, formas u otros indicadores.

## Colores primarios, secundarios y terciarios

En el modelo tradicional descrito por el material:

* los colores primarios son rojo, amarillo y azul;
* los secundarios se obtienen mezclando dos primarios: naranja, verde y violeta;
* los terciarios se sitúan entre un primario y un secundario en la rueda cromática.

En interfaces digitales los colores se expresan mediante modelos como RGB, HSL o valores hexadecimales. La rueda cromática sigue siendo útil para estudiar sus relaciones.

## Variantes de un color

Partiendo de un color se pueden generar variantes:

* **tono claro (*tint*):** resultado de añadir blanco;
* **tonalidad (*tone*):** resultado de añadir gris;
* **matiz oscuro (*shade*):** resultado de añadir negro.

Estas variantes permiten construir estados y niveles de énfasis sin introducir colores sin relación entre sí.

## Combinaciones cromáticas

### Monocromática

Utiliza un color junto con sus variantes claras, medias y oscuras. Es sencilla y coherente, aunque necesita suficiente contraste para que la interfaz no resulte plana.

### Complementaria

Combina colores opuestos en la rueda cromática. Produce contraste y permite destacar acciones o elementos importantes. Los colores intensos deben dosificarse para evitar fatiga visual.

### Triádica

Selecciona tres colores aproximadamente equidistantes en la rueda. Conviene elegir uno como dominante y reservar los otros para apoyo y acento.

### Tetrádica

Utiliza dos pares de colores complementarios. Ofrece variedad, pero es más difícil de equilibrar. Limitar la saturación o trabajar con variantes de luminosidad ayuda a conservar la coherencia.

## Colores cálidos y fríos

Los colores cálidos recuerdan al sol o al fuego; los fríos, al agua o al hielo. Combinar temperaturas puede crear contraste y profundidad. Estas asociaciones no son universales: el contexto cultural y la identidad del producto también influyen en la interpretación.

## Color y accesibilidad

Una paleta visualmente atractiva no garantiza una interfaz accesible. Es necesario:

* comprobar el contraste entre primer plano y fondo;
* revisar texto normal, texto grande, iconos y controles;
* no diferenciar estados solo mediante el color;
* diseñar estados de foco, error, éxito, advertencia y desactivado;
* probar la paleta con simuladores de distintos tipos de visión del color;
* validar los valores finales con herramientas de contraste.

La antigua paleta de “colores seguros para web”, creada para pantallas de 256 colores, ya no es una restricción habitual en navegadores modernos.

## Construcción de una paleta para interfaces

Una estrategia práctica consiste en:

1. elegir un color base relacionado con la identidad y el propósito;
2. generar variantes ordenadas por luminosidad;
3. asignar funciones semánticas, no nombres puramente visuales;
4. definir colores neutrales para fondos, bordes y texto;
5. añadir colores para estados de información, éxito, advertencia y error;
6. comprobar contraste y legibilidad;
7. probar la paleta en componentes y pantallas reales.

```css
:root {
  --color-primary: #315efb;
  --color-primary-hover: #2448c7;
  --color-text: #1f2937;
  --color-surface: #ffffff;
  --color-border: #d1d5db;
  --color-error: #b42318;
}
```

Nombrar los tokens por su función facilita cambiar la paleta sin reescribir cada componente.

## Recursos

* [Lectura sobre teoría del color aplicada a la web](https://mosaic.uoc.edu/ac/le/es/m2/ud3/index.html)
* [Adobe Color](https://color.adobe.com/es/create/color-wheel)
* [Colour Lovers](https://www.colourlovers.com/)
* [Cohesive Colors](https://javier.xyz/cohesive-colors)
* [0to255](https://0to255.com/)
* [The Art of Color — Google Arts & Culture](https://artsandculture.google.com/pocketgallery/IQUxrMnvNro2DQ)

Observar y analizar trabajos visuales ayuda a educar el criterio: el sentido del color se desarrolla mediante la exposición, la comparación y la práctica consciente.
