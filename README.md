✅ 1. HTML separado en index.html, CSS en archivo externo (+ normalize.css enlazado antes):

✅ 2. Al menos 4 variables de color/tipografía en :root, usadas con var():
Cumplido de sobra. Tienes 8 variables (colores, fuentes, bordes y transiciones) y las usas a lo largo de todo tu CSS con var().

✅ 3. Reset básico con box-sizing: border-box:
Cumplido. Tienes el bloque de *, *::before, *::after limpiando márgenes y aplicando el box-sizing.

✅ 4. Al menos 1 id usado de forma justificada:
Cumplido y muy bien comentado. Usaste #pie-principal para demostrar que gana en especificidad sobre la clase .footer para cambiar el color de fondo. Además, usaste IDs para la navegación con anclas (#inicio, #sobre-mi, etc.).

✅ 5. Al menos clases aplicadas sobre divs auxiliares o elementos repetidos:
Cumplido perfectamente. Utilizaste una excelente convención de nombres (como .tarjeta, .tarjeta__cabecera, .tarjeta__texto) que se repiten en tus 4 artículos.

✅ 6. Flexbox para alinear al menos dos grupos de elementos:
Cumplido. Lo usaste en .nav (para los enlaces), en .servicios__grid (para las tarjetas), en el .footer y en .hero.

✅ 7. Al menos un elemento con :hover + transition:
Cumplido con creces. Tienes :hover y transition en los enlaces de navegación, en los botones, en el botón principal de la portada (.hero__cta) y el efecto de luz en las tarjetas.

✅ 8. Al menos 3 @media query funcional:
Cumplido. Tienes tres bloques de Media Queries perfectos (max-width: 768px, min-width: 480px, y max-width: 480px).

✅ 9. CSS organizado por bloques y comentado:
Cumplido. Tu CSS está impecable, con comentarios grandes y claros separando las secciones (/* === HEADER === */, etc.).
