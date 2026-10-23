# Implementación de la ontología

Esta carpeta contiene la **implementación formal de la ontología de movilidad urbana compartida**, siguiendo la función de `ontology/` en [EDINT Censo de Vehículos](https://github.com/EDINT-Ontologia/edint-ontologia-censo-vehiculos/tree/main/ontology).

## Finalidad
Almacenar el modelo legible por máquinas: clases, jerarquías, propiedades, dominios, rangos y relaciones entre vehículos, agentes, reservas, servicios de movilidad, trayectos, tarifas y pagos.

## Contenido
- Archivos `.ttl`, `.rdf`, `.owl` o `.jsonld` con la definición de la ontología.
- Su versión de trabajo consolidada una vez revisada y validada.

Los **individuos de ejemplo** van a [`../ejemplos/`](../ejemplos/); los **vocabularios SKOS** a [`../skos/`](../skos/); los **diagramas** a [`../diagramas/`](../diagramas/).

## Buenas prácticas
Validar la sintaxis, conservar los espacios de nombres de forma coherente y mantener la correspondencia con los requisitos y el modelo conceptual.

> El archivo `ontologia_movilidad.ttl` se encuentra actualmente en la raíz del repositorio; esta carpeta está preparada para organizar la implementación definitiva.
