# Urban Mobility Ontology

Proyecto desarrollado para la asignatura **Ingeniería Ontológica** del Máster en Inteligencia Artificial.

## Descripción

Este repositorio contiene una ontología sobre **movilidad urbana**, centrada en vehículos compartidos y servicios de alquiler de coches.

El objetivo es representar de forma estructurada los principales conceptos y relaciones del dominio utilizando tecnologías de la Web Semántica.

## Tecnologías utilizadas

- **RDF:** representación de recursos y relaciones.
- **RDFS/OWL:** definición de clases y propiedades de la ontología.
- **SKOS:** organización de vocabularios controlados.
- **Turtle (.ttl):** serialización de los datos RDF.
- **SPARQL:** consultas para responder a preguntas de competencia.

## Contenido del proyecto

La ontología modela:

- Vehículos compartidos y sus características.
- Tipos de propulsión y estados de los vehículos mediante SKOS.
- Usuarios, proveedores y servicios de movilidad.
- Reservas, tarifas y pagos.
- Trayectos y puntos de recogida y devolución.

También se reutilizan vocabularios externos, como el de métodos de pago de SEGITTUR.

## Estructura del repositorio

```text
urban-mobility-ontology/
├── README.md
├── ontologia_movilidad.ttl
├── propulsion.ttl
├── estado.ttl
├── consultas/
│   └── consultas.sparql
└── docs/
    └── memoria.pdf
```

## Consultas SPARQL

El proyecto incluye consultas SPARQL para comprobar que la ontología permite responder a diferentes preguntas de competencia, como:

- ¿Qué coches compartidos están disponibles?
- ¿Qué vehículos utilizan propulsión eléctrica?
- ¿Qué coches están en mantenimiento?
- ¿Dónde se recogen y devuelven los vehículos de alquiler?
- ¿Qué distancia y duración tienen los trayectos?

## Contexto académico

**Asignatura:** Ingeniería Ontológica  
**Titulación:** Máster en Inteligencia Artificial  
**Tipo de proyecto:** Práctica académica
