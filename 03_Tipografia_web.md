# DIIW UT01: Planificación de interfaces gráficas

## Tipografía para interfaces web

La tipografía influye directamente en la legibilidad, la jerarquía, la personalidad visual y la accesibilidad de una interfaz. Debe formar un sistema coherente y no una colección de estilos aislados.

## Legibilidad

Para facilitar la lectura en pantalla:

* utiliza fuentes claras y optimizadas para pantalla;
* establece un tamaño base suficiente, habitualmente alrededor de `16px` a `18px`;
* emplea un interlineado aproximado de `1.5` a `1.6` en textos largos;
* evita líneas excesivamente largas;
* garantiza un contraste suficiente entre texto y fondo;
* reserva mayúsculas y estilos decorativos para fragmentos breves.

Las cifras son puntos de partida, no reglas absolutas. El tipo de fuente, el dispositivo, la densidad de información y el público pueden exigir ajustes.

## Jerarquía tipográfica

Una escala tipográfica diferencia las funciones del contenido:

* título principal;
* títulos de sección;
* subtítulos;
* cuerpo de texto;
* etiquetas y ayudas;
* texto secundario.

La jerarquía puede construirse variando tamaño, peso, color y espacio. Conviene limitar el número de combinaciones para que cada nivel sea reconocible.

## Fuentes web

Servicios como [Google Fonts](https://fonts.google.com/) proporcionan fuentes preparadas para su uso en web. Al elegirlas hay que considerar:

* disponibilidad de los pesos realmente necesarios;
* compatibilidad con los caracteres del proyecto;
* coste de descarga y efecto sobre el rendimiento;
* alternativas de sistema mientras se carga la fuente;
* legibilidad en diferentes tamaños y pantallas.

No es necesario cargar una familia completa si solo se utilizan dos o tres pesos.

## Unidades y adaptabilidad

Las unidades relativas, como `rem` y `em`, ayudan a respetar las preferencias de tamaño del usuario y a construir escalas flexibles.

```css
html {
  font-size: 100%;
}

body {
  font-family: system-ui, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
}

h1 {
  font-size: 2rem;
  line-height: 1.2;
}
```

## Iconografía como apoyo

Los iconos complementan al texto, pero no deben sustituir etiquetas esenciales cuando su significado pueda ser ambiguo. Algunos catálogos mencionados en el material son:

* [Feather](https://feathericons.com/)
* [Orion Icon Library](https://www.orioniconlibrary.com/)
* [Font Awesome](https://fontawesome.com/)
* [Emojipedia](https://emojipedia.org/)

Para que un icono interactivo sea accesible necesita un nombre comprensible para las tecnologías de asistencia.

## Consistencia

La misma escala, familias, pesos y espaciados deben repetirse en todo el producto. Esta consistencia reduce el esfuerzo cognitivo y permite reconocer la estructura antes de leer cada palabra.
