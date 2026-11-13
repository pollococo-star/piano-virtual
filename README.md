# Clave — piano virtual

Piano en el navegador, con teclas slim. Se toca con el ratón, el dedo o el teclado de la computadora.

## Qué cambió respecto al HTML original

- Las teclas negras ya no usan posiciones fijas en píxeles: se colocan entre las blancas y siguen alineadas al cambiar el tamaño.
- El sonido se sostiene mientras la tecla está pulsada y se apaga al soltarla. Antes cada nota duraba 1,2 s pasara lo que pasara.
- Hay seis sonidos (piano, Rhodes, órgano, cuerdas, bajo y campana), con un poco de reverberación, en vez de un solo oscilador triangular.
- Se puede tocar con el teclado (fila Z y fila Q), mantener acordes, deslizar el dedo y usar varias pulsaciones a la vez.
- 25 teclas con cambio de octava, o las 49 originales de Do2 a Do6.
- Sustain (botón o barra espaciadora), volumen, metrónomo y una escala de prueba.
- Se quitó Three.js: estaba cargado y no dibujaba nada. El panel de arriba ahora muestra el sonido en vivo.
- El icono de pantalla completa tenía un trazo SVG roto.

No está afiliado a Korg. El aspecto de teclas finas es un homenaje a los controladores slim, no un producto de esa marca.

## Cómo tocar

- Clic, toque o deslizamiento sobre las teclas. Más abajo en la tecla, más fuerte.
- Filas Z y Q del teclado. Espacio sostiene. Flechas cambian de octava (o desplazan el teclado en el modo de 49).
- **Escala** toca una frase corta con el sonido elegido.

## Publicación

GitHub Pages sirve `index.html` desde la rama `main`.
