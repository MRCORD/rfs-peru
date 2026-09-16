# D4: Infraestructura Física, Logística y Conectividad 🚚

> **Dominio de Ciencia Política:** Reducción de la fricción del espacio, conectividad territorial, integración multimodal de puertos y movilidad urbana metropolitana.

---

## 🗺️ Mapa de Arquitectura del Dominio 4

```mermaid
graph TD
    D4[DOMINIO 4: Infraestructura Física, Logística y Conectividad] --> C41[Cartera 4.1: Transporte y Logística Multimodal]
    D4 --> C42[Cartera 4.2: Telecomunicaciones y Redes]
    D4 --> C43[Cartera 4.3: Vivienda, Suelo y Saneamiento]
    D4 --> C44[Cartera 4.4: Contrataciones y APP]

    C41 --> S411[4.1.1: Infraestructura Vial Nacional Provías]
    C41 --> S412[4.1.2: Transporte de Carga y Fletes]
    C41 --> S413[4.1.3: Puertos Estratégicos Chancay/Callao]
    C41 --> S414[4.1.4: Movilidad Urbana y Metro ATU]

    C42 --> S421[4.2.1: Red Dorsal Nacional de Fibra]

    C43 --> S431[4.3.1: Suelo Urbano y Déficit Habitacional]
    C43 --> S432[4.3.2: Redes de Agua Potable SEDAPAL]

    C44 --> S441[4.4.1: Obras Paralizadas por Arbitrajes]

    S412 -.->|Punto de Falla Crítica| F1[D4-01: Fletes Ciegos 40% & Merma de Frío 35%]
    S413 -.->|Punto de Falla Crítica| F2[D4-02: Colas de 10h en Patios de Chancay/Callao]

    style D4 fill:#b45309,stroke:#92400e,stroke-width:2px,color:#fff
    style C41 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C42 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C43 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C44 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style F1 fill:#451a03,stroke:#f59e0b,stroke-width:2px,color:#fde68a
    style F2 fill:#451a03,stroke:#f59e0b,stroke-width:2px,color:#fde68a
```

---

## 📋 Problemas Estructurales Catalogados

| ID | Título del Problema | Severidad | Métrica de Quiebre | TAM LatAm (USD) | Tesis de Startup Principal (RFS) |
|---|---|:---:|---|---|---|
| [**D4-01**](D4-01-fletes-ciegos-carreteras.md) | **Fletes Ciegos (40% Vacíos) y Merma Agrícola** | `high` | Sobrecosto logístico del 34%; 40% camiones vacíos | **$140B** | Freight Marketplace andino con matching de retorno + Cadenas de frío modulares |
| [**D4-02**](D4-02-cuello-botella-megapuertos.md) | **Cuello de Botella en Patios de Megapuertos** | `high` | 8-10 horas de espera en Callao y Chancay | **$40B** | Citas portuarias virtuales geocercadas y ventanilla única descentralizada |

---

## 🏛️ Desglose de Carteras y Subcarteras en este Dominio

* **[Cartera 4.1: Asuntos de Transporte Terrestre, Carga y Movilidad](C4.1_transporte_terrestre_carga_movilidad/README.md)**
  * [*4.1.1. Infraestructura Vial Nacional*](C4.1_transporte_terrestre_carga_movilidad/S4.1.1_infraestructura_vial_nacional/README.md) (Red vial >70% sin pavimentar, sobrecosto logístico del 34%).
  * [*4.1.2. Transporte de Carga Interprovincial*](C4.1_transporte_terrestre_carga_movilidad/S4.1.2_transporte_carga_interprovincial/README.md) (Fletes vacíos, merma del 35%).
  * [*4.1.3. Articulación Portuaria y Comercio Exterior*](C4.1_transporte_terrestre_carga_movilidad/S4.1.3_infraestructura_portuaria_comercio_exterior/README.md) (Colas en accesos a Callao y Chancay).
  * [*4.1.4. Movilidad Urbana Metropolitana*](C4.1_transporte_terrestre_carga_movilidad/S4.1.4_movilidad_urbana_metropolitana/README.md) ("Guerra del centavo", 3 a 4 horas quemadas en tráfico).
* **[Cartera 4.2: Asuntos de Telecomunicaciones y Redes](C4.2_telecomunicaciones_y_redes/README.md)**
  * [*4.2.1. Redes Troncales de Fibra Óptica*](C4.2_telecomunicaciones_y_redes/S4.2.1_redes_troncales_fibra_espectro/README.md) (Red Dorsal operando solo al 10% de su capacidad).
* **[Cartera 4.3: Asuntos de Vivienda, Suelo y Saneamiento](C4.3_vivienda_suelo_urbano_saneamiento/README.md)**
  * [*4.3.1. Suelo Urbano y Déficit Habitacional*](C4.3_vivienda_suelo_urbano_saneamiento/S4.3.1_suelo_urbano_politicas_habitacionales/README.md) (Metro cuadrado a $2,800 USD en Lima Top; invasiones).
  * [*4.3.2. Agua Potable y Saneamiento*](C4.3_vivienda_suelo_urbano_saneamiento/S4.3.2_agua_potable_y_saneamiento_basico/README.md) (3.5 millones sin red de agua pagando 6x más a cisterna).
* **[Cartera 4.4: Asuntos de Contrataciones y Obras Estratégicas](C4.4_contrataciones_y_obras_estrategicas/README.md)**
  * [*4.4.1. Asociaciones Público-Privadas*](C4.4_contrataciones_y_obras_estrategicas/S4.4.1_asociaciones_publico_privadas_arbitrajes/README.md) (Brecha de $140B USD con 2,000+ obras en litigio).
