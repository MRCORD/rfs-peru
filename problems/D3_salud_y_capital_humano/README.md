# D3: Bienestar Social, Capital Humano y Servicios Vitales 🧬

> **Dominio de Ciencia Política:** Preservación del capital humano, nutrición y neurodesarrollo temprano, cobertura médica integral, acceso a principios activos y educación para la frontera tecnológica.

---

## 🗺️ Mapa de Arquitectura del Dominio 3

```mermaid
graph TD
    D3[DOMINIO 3: Bienestar Social, Salud y Capital Humano] --> C31[Cartera 3.1: Salud Pública y Farmacéutica]
    D3 --> C32[Cartera 3.2: Educación, Ciencia e Innovación]
    D3 --> C33[Cartera 3.3: Inclusión y Asistencia Social]

    C31 --> S311[3.1.1: Epidemiología y Anemia Infantil]
    C31 --> S312[3.1.2: Red Prestacional y Citas Médicas]
    C31 --> S313[3.1.3: Cadena Farmacéutica y DIGEMID]

    C32 --> S321[3.2.1: Educación Básica e Infraestructura]
    C32 --> S322[3.2.2: Educación Superior y SUNEDU]
    C32 --> S323[3.2.3: Ciencia y Tecnología CONCYTEC]

    C33 --> S331[3.3.1: Focalización SISFOH y Subsidios]

    S313 -.->|Punto de Falla Crítica| F1[D3-01: Cártel Farmacéutico 85% & DIGEMID]
    S311 -.->|Punto de Falla Crítica| F2[D3-02: 43.6% Anemia & Daño Cerebral Infantil]
    S312 -.->|Punto de Falla Crítica| F3[D3-03: Citas en EsSalud a 5 Meses & 35% Out-of-Pocket]

    style D3 fill:#1d4ed8,stroke:#1e40af,stroke-width:2px,color:#fff
    style C31 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C32 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C33 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style F1 fill:#1e1b4b,stroke:#3b82f6,stroke-width:2px,color:#bfdbfe
    style F2 fill:#1e1b4b,stroke:#3b82f6,stroke-width:2px,color:#bfdbfe
    style F3 fill:#1e1b4b,stroke:#3b82f6,stroke-width:2px,color:#bfdbfe
```

---

## 📋 Problemas Estructurales Catalogados

| ID | Título del Problema | Severidad | Métrica de Quiebre | TAM LatAm (USD) | Tesis de Startup Principal (RFS) |
|---|---|:---:|---|---|---|
| [**D3-01**](C3.1_salud_publica_y_aseguramiento/S3.1.3_abastecimiento_y_regulacion_farmaceutica/D3-01-cartel-farmacias-d2c.md) | **Cártel Farmacéutico y Desabastecimiento** | `critical` | 85% retail en un grupo; 35% gasto de bolsillo | **$65B** | Farmacia digital D2C de genéricos esenciales directo de laboratorio |
| [**D3-02**](D3-02-anemia-primera-infancia.md) | **Anemia Infantil Crónica (0 a 3 años)** | `critical` | 43.6% anemia infantil; daño neurocognitivo | **$15B** | Tele-seguimiento nutricional por WhatsApp a madres + micronutrientes bioasimilables |
| [**D3-03**](D3-03-colapso-citas-essalud.md) | **Colapso de Citas y Esperas a 6 Meses** | `high` | 5 meses de demora en citas; 60% médicos en Lima | **$35B** | Tele-triaje por agentes de IA clínicos y conexión de especialistas (*HablaDoc*) |

---

## 🏛️ Desglose de Carteras y Subcarteras en este Dominio

* **[Cartera 3.1: Asuntos de Salud y Regulación Farmacéutica](C3.1_salud_publica_y_aseguramiento/README.md)**
  * [*3.1.1. Epidemiología, Nutrición y Primera Infancia*](C3.1_salud_publica_y_aseguramiento/S3.1.1_epidemiologia_nutricion_primera_infancia/README.md) (Anemia infantil, 50% inseguridad alimentaria FAO).
  * [*3.1.2. Red Prestacional y Agendamiento*](C3.1_salud_publica_y_aseguramiento/S3.1.2_red_prestacional_y_agendamiento/README.md) (Citas a 6 meses, fragmentación en 5 subsistemas médicos).
  * [*3.1.3. Regulación y Abastecimiento Farmacéutico*](C3.1_salud_publica_y_aseguramiento/S3.1.3_abastecimiento_y_regulacion_farmaceutica/README.md) (DIGEMID demora 3 años, monopolio minorista del 85%).
* **[Cartera 3.2: Asuntos de Educación, Ciencia e Innovación](C3.2_educacion_ciencia_e_innovacion/README.md)**
  * [*3.2.1. Educación Básica e Infraestructura*](C3.2_educacion_ciencia_e_innovacion/S3.2.1_educacion_basica_e_infraestructura/README.md) (Brecha escolar de S/150B, colegios sin agua ni luz).
  * [*3.2.2. Educación Superior y CTI*](C3.2_educacion_ciencia_e_innovacion/S3.2.2_educacion_superior_universitaria/README.md) (Universidades sin I+D, solo 0.18% del PBI en innovación).
  * [*3.2.3. Juventud Desconectada*](C3.2_educacion_ciencia_e_innovacion/S3.2.3_ciencia_tecnologia_innovacion/README.md) (1.5 millones de jóvenes NININIs).
* **[Cartera 3.3: Asuntos de Inclusión Social y Poblaciones Vulnerables](C3.3_inclusion_social_y_poblaciones_vulnerables/README.md)**
  * [*3.3.1. Focalización y Transferencias*](C3.3_inclusion_social_y_poblaciones_vulnerables/S3.3.1_focalizacion_y_transferencias_sociales/README.md) (Clientelismo y programas sociales sin graduación al empleo).
