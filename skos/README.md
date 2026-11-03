# Vocabularios SKOS

- [`propios/`](propios/): esquemas `mo:EstadoVehiculoScheme` y `mo:TipoPropulsionScheme`, con alineamientos EDINT entre conceptos.
- [`segittur/`](segittur/): PaymentMethod, StationType y VehicleType, con IRIs oficiales.
- [`edint/`](edint/): VehicleState y PropulsionSystemType, con etiquetas mal codificadas corregidas en copias locales, sin cambiar IRIs.

El vocabulario de estados incluye una correspondencia aproximada `closeMatch` (Mantenimiento y UnderRepair); los de propulsión incluyen dos `exactMatch` y dos `narrowMatch`. No se definen equivalencias Active/Ocupado o Inactive/Disponible.

La ontología actual se encuentra en [`../ontologia/ontologia_movilidad_compartida_v8.ttl`](../ontologia/ontologia_movilidad_compartida_v8.ttl). El grafo combinado de trabajo para Protégé está en [`../resources/ontologia_movilidad_compartida_v8_integrada_protege.ttl`](../resources/ontologia_movilidad_compartida_v8_integrada_protege.ttl).
