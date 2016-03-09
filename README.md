## Recon para Ghost

Recon es un tema que usando un poco de lógica invade la manera en que funcionan los temas de ghost para agregarle algunas cosas cool, aunque ghost recomienda no usar la api en producción, saltarnos esa recomendación fue la única manera de lograr la funcionalidad requerida, me refiero a poner en la página principal los trabajos y los miembros del equipo de manera elegante.

## Cómo instalar

Los temas de Ghost viven en `content/themes/`
Después de descargar 'Recon', extraelo y ponlo en `content/themes` junto al tema default 'Casper'.

Para activarlo:

 * Reinicia Ghost. (Por el momento, Ghost no notará que has agregado un nuevo directorio a content/themes, por eso tienes que reiniciarlo.)

 * Entra a tu administrador de Ghost y navega a `/ghost/settings/general/`

 * Selecciona el nombre de tu tema en el menu desplegable 'Theme'

 * Clic 'Save'

 * Visita la portada de tu blog y admira tu nuevo tema.

Si eres nuevo usando Ghost, recomiendo que le des una revisada a las siguientes ligas:
 * La guia de Ghost: http://docs.ghost.org/
 * Cambiando temas: http://docs.ghost.org/themes/
 * Publicando con Ghost: http://docs.ghost.org/usage/writing/

## Instrucciones de uso

Recién instalado no notarás mucha diferencia tal vez, eso es porque necesitas hacer lo siguiente:

 * Lo que quieras que salga sobre la imagen como portada, ya sea un texto o video, lo agregas como un artículo nuevo y le pones la etiqueta `portada`.
 * Lo que quieras que salga debajo de la portada como explicatorio o ambiental si tu quieres, lo agregas como artículo nuevo y le pones la etiqueta `flor`.
 * Agrega cada miembro del equipo como un artículo nuevo y ponle la etiqueta `equipo`.
 * Agrega cada trabajo nuevo del equipo como un artículo nuevo y ponle la etiqueta `producciones`.
 

## Copyright & License

© [QwertyForte](https://qwertyforte.com) Licencia MIT 
Por [@JorgeArtware](https://twitter.com/jorgeartware) para QwertyForte
Originalmente desarrollado para la casa productora [La Flor del Nopal](http://laflordelnopal.com)
Inicialmente basado en "Landscape" de [Diverse Themes](http://diversethemes.com) pero con demasiadas modificaciones.
