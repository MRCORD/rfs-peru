# D6: Gobernanza, Calidad Burocrática y Estabilidad Política 🏛️

> **Dominio de Ciencia Política:** Reducción de la fricción administrativa, estabilidad en la alta dirección pública, eliminación de la discrecionalidad fiscalizadora e interoperabilidad digital del Estado.

---

## 🗺️ Mapa de Arquitectura del Dominio 6

```mermaid
graph TD
    D6[DOMINIO 6: Gobernanza, Burocracia y Política] --> C61[Cartera 6.1: Función Pública y Estabilidad]
    D6 --> C62[Cartera 6.2: Simplificación y Competencia]
    D6 --> C63[Cartera 6.3: Gobernanza Digital y Datos]

    C61 --> S611[6.1.1: Carrera Pública y SERVIR]
    C61 --> S612[6.1.2: Descentralización y Gob. Regionales]

    C62 --> S621[6.2.1: Barreras Burocráticas Indecopi]
    C62 --> S622[6.2.2: Inspecciones Municipales ITSE]

    C63 --> S631[6.3.1: Interoperabilidad Plataforma PIDE]
    C63 --> S632[6.3.2: Contrataciones Abiertas SEACE]

    S622 -.->|Punto de Falla Crítica| F1[D6-01: Extorsión Administrativa Municipal en Licencias]
    S631 -.->|Punto de Falla Crítica| F2[D6-02: Silos de Datos Estatales & Tiranía del Papel]

    style D6 fill:#7c3aed,stroke:#6d28d9,stroke-width:2px,color:#fff
    style C61 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C62 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C63 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style F1 fill:#4c1d95,stroke:#a855f7,stroke-width:2px,color:#e9d5ff
    style F2 fill:#4c1d95,stroke:#a855f7,stroke-width:2px,color:#e9d5ff
```

---

## 📋 Problemas Estructurales Catalogados

| ID | Título del Problema | Severidad | Métrica de Quiebre | TAM LatAm (USD) | Tesis de Startup Principal (RFS) |
|---|---|:---:|---|---|---|
| [**D6-01**](D6-01-extorsion-administrativa-municipal.md) | **Discrecionalidad y Extorsión Municipal a Pymes** | `high` | 40% clausuras discrecionales; rotación cada 6 meses | **$25B** | Plataforma de autoevaluación ITSE inmutable en video + Fast-track de licencias |
| [**D6-02**](D6-02-silos-datos-publicos-pide.md) | **Silos de Datos del Estado y Tiranía del Papel** | `medium` | 24 meses para permisos CIRA; rechazo a APIs PIDE | **$14B** | Capa de abstracción GovTech que automatiza trámites vía web scraping y firmas |

---

## 🏛️ Desglose de Carteras y Subcarteras en este Dominio

* **[Cartera 6.1: Asuntos de Función Pública y Estabilidad Institucional](C6.1_funcion_publica_estabilidad_institucional/README.md)**
  * [*6.1.1. Carrera Pública y Rotación*](C6.1_funcion_publica_estabilidad_institucional/S6.1.1_carrera_publica_servicio_civil/README.md) (Ministros con duración menor a 6 meses; foja cero de proyectos).
  * [*6.1.2. Descentralización y Gobiernos Regionales*](C6.1_funcion_publica_estabilidad_institucional/S6.1.2_descentralizacion_gobiernos_regionales/README.md) (Incapacidad de ejecución del canon en regiones).
* **[Cartera 6.2: Asuntos de Simplificación Regulatoria y Competencia](C6.2_simplificacion_regulatoria_competencia/README.md)**
  * [*6.2.1. Eliminación de Barreras Burocráticas*](C6.2_simplificacion_regulatoria_competencia/S6.2.1_barreras_burocraticas_competencia/README.md) (Barreras de entrada para proteger monopolios locales).
  * [*6.2.2. Calidad Regulatoria y Licencias*](C6.2_simplificacion_regulatoria_competencia/S6.2.2_calidad_regulatoria_licencias_itse/README.md) (Clausuras arbitrarias de pymes por inspectores municipales).
* **[Cartera 6.3: Asuntos de Gobernanza Digital y Contrataciones](C6.3_gobernanza_digital_contrataciones/README.md)**
  * [*6.3.1. Interoperabilidad Digital (PIDE)*](C6.3_gobernanza_digital_contrataciones/S6.3.1_interoperabilidad_identidad_digital/README.md) (Entidades cobrando por certificados que ya existen en formato digital).
  * [*6.3.2. Contrataciones del Estado (SEACE)*](C6.3_gobernanza_digital_contrataciones/S6.3.2_contrataciones_abiertas_seace/README.md) (Direccionamiento de términos de referencia y colusión de postores).
