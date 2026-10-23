# Descripción de la ontología (WIDOCO)

Esta carpeta contiene la **documentación HTML generada automáticamente con WIDOCO** a partir de la implementación RDF/RDFS de la ontología de movilidad urbana compartida, junto con el diagrama obtenido.

## Herramienta

La documentación se genera mediante una llamada al ejecutable Java **`widoco-<version>-jar-with-dependencies.jar`**, descargado de los [releases del repositorio oficial de WIDOCO](https://github.com/dgarijo/Widoco/releases/latest). No es necesario guardar el JAR dentro de este repositorio: basta con documentar cómo se utiliza.

## Generación de la documentación

Ejemplo ejecutado desde la raíz del repositorio, suponiendo que el JAR descargado está disponible en el directorio actual:

```bash
java -jar widoco-<version>-jar-with-dependencies.jar \
  -ontFile ontologia_movilidad.ttl \
  -outFolder descripcion \
  -getOntologyMetadata \
  -lang es \
  -rewriteAll
```

**Sustituir** `<version>` por la versión real del JAR descargado. Si el RDF definitivo se guarda en `ontologia/`, actualizar la ruta de `-ontFile` en consecuencia. Ejecutar `-rewriteAll` con cuidado: reemplaza archivos generados previamente en la carpeta de salida.

## Contenido

- Páginas HTML de documentación generadas por WIDOCO.
- Hojas de estilo, scripts, imágenes y otros recursos auxiliares necesarios para su visualización.
- Diagrama de la ontología obtenido durante el desarrollo o incorporado a la documentación.

La salida puede contener nombres y subcarpetas adicionales según la versión y las opciones de WIDOCO. Mantener la estructura generada para no romper los enlaces internos.

## Relación con otras carpetas

- [`../ontologia/`](../ontologia/): implementación formal de la ontología.
- [`../skos/`](../skos/): vocabularios controlados.
- [`../diagramas/`](../diagramas/): diagramas conceptuales y versiones editables.
- [`../documentacion/`](../documentacion/): memoria y documentación académica.

> Esta carpeta se ha preparado para almacenar el resultado de la ejecución de WIDOCO; la generación no se ha ejecutado desde GitHub ni se ha añadido todavía su salida HTML.
