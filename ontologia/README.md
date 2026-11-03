# Ontología de movilidad compartida

- [`ontologia_movilidad_compartida_v8.ttl`](ontologia_movilidad_compartida_v8.ttl): versión V8 actual, sin individuos de ejemplo; incluye clases OWL, propiedades y referencias a los vocabularios SKOS.
- [`ontologia_movilidad_compartida.ttl`](ontologia_movilidad_compartida.ttl): versión anterior, conservada por trazabilidad.
- [`../skos/`](../skos/): dos vocabularios propios y cinco externos.
- [`../resources/ontologia_movilidad_compartida_v8_integrada_protege.ttl`](../resources/ontologia_movilidad_compartida_v8_integrada_protege.ttl): copia concatenada de los ocho archivos RDF para inspección en Protégé; no equivale a `owl:imports`.

Comprobaciones realizadas: sintaxis Turtle y correspondencias SKOS / IRIs referenciadas. Pendiente: coherencia lógica con un razonador OWL y contraste de todas las equivalencias externas.
