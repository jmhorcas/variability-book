# SPL book

## Dependencies

- **rsvg-convert**: to convert SVG images to PDF (`sudo apt-get install librsvg2-bin`))


## Modelo mental del libro
Se trata de un libro de conceptos, donde:
- cada concepto principal = 1 página (.qmd)
- lectura no lineal (web)
- profundidad controlada (1–2 pantallas / páginas)

Este modelo encaja perfectamente con:

- lectores noveles (consumo progresivo),
- expertos (consulta puntual),
- docencia,
- y referencia académica.


## Tips
- Para exponer el contenido hay que seguir un orden didáctico. 
La solución “de libro de texto” es esta secuencia:
Contexto → Definición → Explicación → Ejemplo → Analogía en software 

- Si un contenido puede titularse como un sintagma nominal claro, es una página.
Si necesita “Sección X.Y”, probablemente es demasiado grande.

- Figura principal → cuerpo del texto; Figura aclaratoria → margen (.aside)

- Cada .qmd: una idea principal, reutilizable, enlazable, fácil de mantener.
