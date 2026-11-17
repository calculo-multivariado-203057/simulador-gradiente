# Simulador de gradiente y optimización con multiplicadores de Lagrange

Recurso educativo digital para la **Fase 2** del curso **Cálculo Multivariado (203057)** de la
Universidad Nacional Abierta y a Distancia (UNAD). El estudiante ingresa paso a paso los datos de
su propio problema y el simulador **verifica** sus cálculos: no entrega la respuesta resuelta.

- **Módulo 1 — Gradiente y derivada direccional.** Apoya el ítem III de la actividad 2 del
  Apéndice 1. El estudiante escribe la función y el punto, observa el campo de gradientes y las
  curvas de nivel, y luego contrasta sus derivadas parciales, la magnitud del gradiente y el
  vector unitario con los que calcula el simulador.
- **Módulo 2 — Multiplicadores de Lagrange.** Apoya los ítems I a III de la actividad 4. El
  estudiante escribe la restricción y su valor, obtiene los puntos óptimos y el valor de λ, y
  compara con los que él mismo determinó.

Cada módulo trae un ejemplo resuelto plegado («¿No sabe qué escribir? Vea un ejemplo resuelto»),
que permanece oculto hasta que el estudiante lo abre. El trabajo se conserva en el navegador y
puede trasladarse a otro equipo mediante un código de transferencia, de modo que la fase puede
desarrollarse en varias sesiones y en el orden que el estudiante decida.

En [`ejemplo/`](ejemplo/) se encuentra la hoja de apoyo con el recorrido completo, tecla por
tecla, de un problema de práctica.

## Uso

Abra `index.html` en cualquier navegador moderno. **No requiere instalación, servidor ni conexión
a internet**: las tres bibliotecas que utiliza (mathjs, Plotly y MathJax) y las tipografías están
incluidas en `vendor/`, de manera que el recurso seguirá funcionando aunque esos servicios
cambien de dirección o el estudiante trabaje sin conectividad, condición frecuente en las zonas
rurales del Caribe colombiano en las que se sitúa el curso.

## Publicación en GitHub Pages

1. Cree el repositorio y suba el contenido de esta carpeta a la rama `main`.
2. En **Settings → Pages**, elija *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. En pocos minutos el simulador queda en
   `https://USUARIO-GITHUB.github.io/simulador-gradiente-203057/`
   y la hoja de apoyo en `.../simulador-gradiente-203057/ejemplo/`.

El archivo `.nojekyll` ya está incluido para que GitHub publique los archivos tal como están.

## Autoría y filiación

**Pablo Emilio Gutiérrez Duncan**
Director del curso Cálculo Multivariado (203057)
Escuela de Ciencias Básicas, Tecnología e Ingeniería (ECBTI)
Universidad Nacional Abierta y a Distancia (UNAD) — CCAV Puerto Colombia, Zona Caribe
Barranquilla, Colombia

> Complete el ORCID en `CITATION.cff` antes de publicar la primera versión.

## Cómo citar

Gutiérrez Duncan, P. E. (2026). *Simulador de gradiente y optimización con multiplicadores de
Lagrange* (versión 1.0) [Software]. Universidad Nacional Abierta y a Distancia.
https://github.com/USUARIO-GITHUB/simulador-gradiente-203057

El archivo `CITATION.cff` permite que GitHub genere la cita automáticamente y que Zenodo la lea
si decide asignarle un DOI.

## Licencia

El simulador y la hoja de apoyo se publican bajo **Creative Commons Atribución-NoComercial-
CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)**; véase [`LICENSE`](LICENSE).

Las bibliotecas incluidas en `vendor/` conservan sus propias licencias, que se distribuyen junto
a cada archivo:

| Componente | Versión | Licencia |
|---|---|---|
| mathjs | 12.4.2 | Apache-2.0 |
| Plotly.js | 2.32.0 | MIT |
| MathJax (salida SVG) | 3.2.2 | Apache-2.0 |
| Bitter, Source Sans 3, IBM Plex Mono | — | SIL Open Font License 1.1 |
