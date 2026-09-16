# D5: Recursos Naturales, Energía y Matriz Productiva ⚡

> **Dominio de Ciencia Política:** Soberanía energética, capitalización intergeneracional de la renta extractiva, gestión del estrés hídrico y transición hacia la economía del cómputo.

---

## 🗺️ Mapa de Arquitectura del Dominio 5

```mermaid
graph TD
    D5[DOMINIO 5: Recursos Naturales, Energía y Matriz] --> C51[Cartera 5.1: Minería y Renta Soberana]
    D5 --> C52[Cartera 5.2: Electricidad y Cómputo de IA]
    D5 --> C53[Cartera 5.3: Recursos Hídricos y Riego]
    D5 --> C54[Cartera 5.4: Conservación y Ambiente]

    C51 --> S511[5.1.1: Ventana de 50 Años del Cobre]
    C51 --> S512[5.1.2: Conflictos Sociales Las Bambas]

    C52 --> S521[5.2.1: Energía Solar Sur $65/MWh]
    C52 --> S522[5.2.2: Gas Natural de Camisea]
    C52 --> S523[5.2.3: Data Centers Locales de IA]

    C53 --> S531[5.3.1: Cuencas y Riego por Gravedad]

    C54 --> S541[5.4.1: Deforestación y Pasivos Mineros]

    S523 -.->|Punto de Falla Crítica| F1[D5-01: Energía a $65/MWh vs Cero Data Centers IA]
    S531 -.->|Punto de Falla Crítica| F2[D5-02: Costa con 1.8% Agua Dulce & 60% Pérdida en Riego]

    style D5 fill:#eab308,stroke:#ca8a04,stroke-width:2px,color:#000
    style C51 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C52 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C53 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style C54 fill:#1e293b,stroke:#475569,stroke-width:1px,color:#fff
    style F1 fill:#713f12,stroke:#facc15,stroke-width:2px,color:#fef08a
    style F2 fill:#713f12,stroke:#facc15,stroke-width:2px,color:#fef08a
```

---

## 📋 Problemas Estructurales Catalogados

| ID | Título del Problema | Severidad | Métrica de Quiebre | TAM LatAm (USD) | Tesis de Startup Principal (RFS) |
|---|---|:---:|---|---|---|
| [**D5-01**](D5-01-data-centers-desierto-solar.md) | **Energía Solar Barata ($65/MWh) vs Cero Data Centers** | `high` | 0 data centers IA en Perú; nubes en Virginia | **$18B** | Greenfield AI Data Centers modulares en el desierto solar andino + Nube regional de GPUs |
| [**D5-02**](D5-02-estres-hidrico-costa.md) | **Estrés Hídrico en la Costa y Desperdicio en Riego** | `critical` | 70% población en costa con 1.8% del agua dulce | **$32B** | Riego por goteo solar como servicio (pago por m³) + Micro-desaladoras barriales |

---

## 🏛️ Desglose de Carteras y Subcarteras en este Dominio

* **Cartera 5.1: Asuntos de Minería y Renta Extractiva**
  * *5.1.1. Horizonte de Reservas y Soberanía* (Ventana de 50 años del cobre sin fondo soberano).
  * *5.1.2. Gestión Socioambiental y Conflictos* (Bloqueos del Corredor Minero del Sur).
* **Cartera 5.2: Asuntos de Energía y Cómputo de Escala**
  * *5.2.1. Generación Renovable y Nodos* (Energía solar a $65/MWh sin contratos industriales).
  * *5.2.2. Hidrocarburos y Gas Natural* (Gasoducto del sur paralizado; rescates a Petroperú).
  * *5.2.3. Infraestructura de Cómputo de IA* (Fuga de divisas pagando servidores en Norteamérica).
* **Cartera 5.3: Asuntos Agrarios y Recursos Hídricos**
  * *5.3.1. Eficiencia Hídrica en Cuencas* (60% de agua dulce perdida en riego por inundación).
* **Cartera 5.4: Asuntos Ambientales y Biodiversidad**
  * *5.4.1. Deforestación y Pasivos Mineros* (150,000 ha deforestadas/año; 8,000 pasivos mineros).
