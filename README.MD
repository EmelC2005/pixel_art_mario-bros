# Pixel Art - Mario Bros 🍄

Este proyecto es una página web que muestra un arte en píxeles (pixel art) de Mario Bros, utilizando únicamente HTML y CSS. El objetivo es rendir homenaje al icónico personaje de Nintendo mediante técnicas modernas de CSS, logrando un resultado visual atractivo y fiel al estilo retro de los videojuegos clásicos.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Técnicas Utilizadas](#técnicas-utilizadas)
- [Colores Utilizados](#colores-utilizados)
- [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
- [Captura de Pantalla](#captura-de-pantalla)
- [Créditos](#créditos)
- [Licencia](#licencia)

---

## Descripción

La página muestra un pixel art de Mario Bros centrado sobre un fondo temático. El arte se genera exclusivamente con CSS, usando la propiedad `box-shadow` para simular los píxeles de diferentes colores y posiciones. No se utilizan imágenes para el personaje, lo que demuestra el poder y la flexibilidad de CSS moderno.

## Estructura del Proyecto

```
index.html
css/
  styles.css
image/
  background.jpg
```

- **index.html**: Archivo principal HTML que contiene la estructura básica de la página.
- **css/styles.css**: Archivo de estilos CSS donde se define el arte en píxeles y el diseño visual.
- **image/background.jpg**: Imagen de fondo utilizada para ambientar la página.

## Técnicas Utilizadas

- **Pixel Art con CSS**: Se utiliza la propiedad `box-shadow` para crear cada "píxel" del personaje Mario, posicionando y coloreando cada sombra para formar la figura completa.
- **Responsive Design**: El fondo se adapta al tamaño de la ventana mediante `background-size: 170vw 170vh` y otras propiedades.
- **Estilizado de Fondo**: El fondo utiliza una imagen fija, centrada y sin repetición para dar contexto visual.
- **Optimización Visual**: Se emplea `image-rendering: pixelated` para mantener la nitidez de los píxeles y `zoom` para ajustar el tamaño general del arte.

## Colores Utilizados

A continuación se listan los principales colores empleados en el pixel art y su significado:

| Color                | Código RGB         | Uso Principal                |
|----------------------|-------------------|------------------------------|
| Rojo                 | rgb(240, 12, 12)  | Gorra y camisa de Mario      |
| Rojo oscuro          | rgb(130, 39, 39)  | Sombras en la gorra/camisa   |
| Marrón oscuro        | rgb(58, 55, 55)   | Bordes y detalles            |
| Piel clara           | rgb(239, 160, 81) | Cara y manos                 |
| Amarillo claro       | rgb(234, 247, 165)| Botones y detalles           |
| Amarillo oscuro      | rgb(232, 166, 61) | Sombras en la piel           |
| Azul oscuro          | rgb(1, 4, 188)    | Pantalón                     |
| Azul claro           | rgb(111, 114, 255)| Sombras y detalles del pantalón|
| Gris claro           | rgb(233, 223, 223)| Sombras y detalles           |
| Gris medio           | rgb(118, 118, 118)| Sombras y detalles           |
| Amarillo intenso     | rgb(227, 234, 8)  | Hebillas y detalles          |
| Marrón claro         | rgb(178, 116, 9)  | Botas y detalles             |

## Cómo Ejecutar el Proyecto

1. **Clona o descarga este repositorio.**
2. Asegúrate de que la estructura de carpetas se mantenga igual.
3. Abre el archivo `index.html` en tu navegador favorito.
4. ¡Disfruta del pixel art de Mario Bros!

## Captura de Pantalla

> _Incluye aquí una captura de pantalla de la página renderizada para mostrar el resultado visual._

## Créditos

- Pixel art diseñado y adaptado por [Tu Nombre].
- Inspirado en el personaje Mario Bros de Nintendo.
- Imagen de fondo: [background.jpg](image/background.jpg).

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

---

¡Gracias por visitar este proyecto! Si te gustó, no dudes en compartirlo o contribuir con mejoras.