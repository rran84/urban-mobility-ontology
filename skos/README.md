# Vocabularios SKOS

Los vocabularios se organizan por procedencia:

- [`propios/`](propios/): `estado_vehiculo.ttl` (Disponible, Ocupado, Mantenimiento) y `tipo_propulsion.ttl` (Electrica, Combustion, Hibrida, Humana). Incluyen alineamientos SKOS con EDINT.
- [`segittur/`](segittur/): `paymentmethod.ttl`, `stationtype.ttl` y `vehicletype.ttl`, vocabularios reutilizados de SEGITTUR, con sus IRIs originales.
- [`edint/`](edint/): `propulsionsystemtype.ttl` y `vehiclestate.ttl`, vocabularios externos de EDINT.

Los conceptos SKOS se mantienen separados de las clases OWL. Las correspondencias `skos:exactMatch`, `skos:closeMatch` y `skos:narrowMatch` se documentan en los vocabularios propios; no implican identidad OWL de las clases.

La [ontología principal](../ontologia/ontologia_movilidad_compartida_v6.ttl) define el modelo. Para abrir todos los grafos juntos en Protégé, puede usarse la [versión integrada](../resources/ontologia_movilidad_compartida_v6_integrada_protege.ttl).
