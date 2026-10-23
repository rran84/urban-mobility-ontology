# Requisitos y consultas SPARQL

Esta carpeta se inspira en `requirements/` de [EDINT Censo de Vehículos](https://github.com/EDINT-Ontologia/edint-ontologia-censo-vehiculos/tree/main/requirements), que reúne requisitos, preguntas de competencia y consultas SPARQL para verificarlas.

## Finalidad
Documentar **qué debe representar la ontología, para qué usuarios y usos previstos se desarrolla y qué preguntas debe responder**. Las consultas SPARQL permiten comprobar esas preguntas sobre los datos RDF de ejemplo.

## Contenido previsto
- Documentación de requisitos de dominio, usuarios y usos previstos (`.md`, `.pdf`, `.tex`).
- Listado de preguntas de competencia y correspondencia con clases y propiedades de la ontología.
- Archivos `.sparql` o `.rq` individuales: **cada archivo contiene una sola consulta SPARQL**.

## Organización propuesta
```text
requirements/
├── README.md
├── requisitos.pdf
├── preguntas_competencia.md
├── PC01.sparql
├── PC02.sparql
└── ...
```

Cada consulta debe identificar la pregunta de competencia a la que responde, emplear los prefijos y términos del modelo de [`../ontologia/`](../ontologia/) y ser comprobable con los datos de [`../ejemplos/`](../ejemplos/). Los nombres anteriores son ejemplos de organización, no archivos existentes.

## Buenas prácticas
Mantener trazabilidad entre requisito, pregunta de competencia, consulta SPARQL y elementos de la ontología; actualizar las consultas cuando cambie el modelo.
