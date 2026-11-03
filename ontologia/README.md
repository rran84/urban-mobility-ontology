# Ontología de movilidad compartida

- [`ontologia_movilidad_compartida_v6.ttl`](ontologia_movilidad_compartida_v6.ttl): definición principal V6, con clases OWL, propiedades, jerarquías y restricciones. No contiene individuos de ejemplo.
- [SKOS propios y externos](../skos/): vocabularios de estado, propulsión, medios de pago, estaciones y vehículos.
- [TTL integrado para Protégé](../resources/ontologia_movilidad_compartida_v6_integrada_protege.ttl): copia combinada para revisar el modelo y los siete vocabularios en una sola apertura; no sustituye a una configuración formal de `owl:imports`.
- [Diagrama V6](../diagramas/ontologia_movilidad_compartida_v6.json): fuente editable del diseño.

El archivo `ontologia_movilidad.ttl` de la raíz es una versión anterior. Mantener los datos de ejemplo en `ejemplos/` y validar con un razonador en Protégé antes de dar por comprobada la coherencia OWL.
