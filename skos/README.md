# Vocabularios controlados SKOS


## Finalidad
Representar mediante SKOS las categorías utilizadas por la ontología, separando los conceptos controlados de las clases RDF/RDFS.

## Contenido previsto
- `propulsion.ttl`: conceptos de tipos de propulsión de los vehículos.
- `estado.ttl`: conceptos de estado de los vehículos.
- Referencias documentadas a vocabularios externos reutilizados, como el de métodos de pago de SEGITTUR, sin copiar su definición salvo que sea necesario.

## Buenas prácticas
Usar `skos:ConceptScheme`, `skos:Concept`, `skos:prefLabel` y los idiomas definidos en el proyecto (español e inglés). Mantener URI y prefijos coherentes con [`../ontologia/`](../ontologia/) y validar los archivos Turtle.
