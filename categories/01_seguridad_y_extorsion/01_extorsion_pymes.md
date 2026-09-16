# 🚨 Extorsión, Cobro de Cupos e Impunidad Judicial

> **Categoría:** Seguridad, Estado de Derecho y Protección Pyme  
> **Estado:** Documentado  
> **Impacto Económico Estimado:** S/6,000M+ anuales en pérdidas directas e indirectas  

---

## 1. El Síntoma Visible
- La bodega de barrio, el restaurante, el taller mecánico o la pequeña constructora reciben un sobre con una bala, un sticker de extorsión o un mensaje de WhatsApp amenazando a la familia con fotos de la fachada.
- Exigencia de una "cuota" mensual (S/500 a S/5,000) bajo el eufemismo de "seguridad".
- Negocios cierran discretamente, bajan cortinas temprano o trasladan su operación.
- El 99% de pymes asume que denunciar ante la policía empeora la situación (riesgo de colusión o filtración de datos).

---

## 2. Los Datos Duros (Ground Truth)

*Datos extraídos y validados del repositorio Peru 2040 (`article-09-85000-extorsiones.md`):*

- **85,000 denuncias de extorsión** registradas anualmente.
- **Apenas 20 sentencias condenatorias** al año.
- **Tasa de efectividad judicial:** **0.02%** (menos de 1 condena por cada 4,000 denuncias).
- **222,730 crímenes reportados** en períodos de 10 meses.
- **Efectividad de los Estados de Emergencia decretados por el Ejecutivo:** Cero impacto medible en delitos violentos o extorsiones tras más de 6 declaraciones en Lima y Callao.

---

## 3. Por Qué el Sistema Actual no lo Resuelve
1. **La Policía Nacional (PNP) y Fiscalía operan con procesos de papel:** Expedientes físicos que tardan meses en tramitarse, vulnerables a coimas y filtración de identidad del denunciante.
2. **Incentivo de riesgo asimétrico para el extorsionador:** Con 0.02% de probabilidad de cárcel y penas que no se cumplen por hacinamiento penitenciario, extorsionar es un negocio de rentabilidad infinita y riesgo casi nulo.
3. **El Estado exige formalización tributaria (RUC, licencias con dirección pública y nombre del titular en SUNAT),** lo que convierte a la pyme formal en un blanco geolocalizable y rastreable para las bandas criminales, mientras que el informal opera bajo el radar.

---

## 4. Descomposición por Primeros Principios

¿Qué es realmente la extorsión desde el punto de vista de flujos e información?

$$\text{Extorsión} = \text{Asimetría de Información (saber quién eres y dónde operas)} + \text{Monopolio de Coacción Local} - \text{Cero Costo de Cobro}$$

- **Fricción 1: Visibilidad de la víctima.** El negocio físico no puede esconder su punto de venta.
- **Fricción 2: Trazabilidad del cobro.** Los delincuentes cobran vía cuentas prestadas ("mulas"), Yape/Plin de terceros o efectivo en mano.
- **Fricción 3: Descoordinación de las víctimas.** Cada comerciante negocia y sufre solo; no hay inteligencia compartida entre comercios de la misma cuadra o gremio.

---

## 5. Request for Startups (RFS: Tesis de Solución Tech)

### Tesis A: Redes Descentralizadas de Alerta y Telemetría Pyme
- **Qué es:** Hardware IoT de bajo costo (sensores de ruptura, botones de pánico de largo alcance LoRaWAN, cámaras edge con detección de placas y rostros) conectado a una red privada comunitaria (gremio de bodegueros, asociación de galerías comerciales).
- **Moat:** Alertas coordinadas colectivas automáticas que quitan el anonimato al extorsionador antes de que llegue a la puerta y generan evidencia encriptada inalterable fuera del alcance de la comisaría local.

### Tesis B: Blindaje de Identidad y Rieles de Cobro Fantasma para Pymes
- **Qué es:** Infraestructura fintech que permita a pymes y profesionales cobrar digitalmente sin exponer en el comprobante público ni en el app el nombre completo, DNI ni dirección del titular.
- **Moat:** Elimina el vector principal de ingeniería social de los extorsionadores (sacar el nombre del titular de la boleta o del código QR de pago).

### Tesis C: Inteligencia de Cuentas Mula y Detección de Patrones de Coacción
- **Qué es:** Software de análisis transaccional y grafos para neobancos, billeteras y cooperativas que detecte patrones de micro-abonos forzados y cuentas receptoras mulas en tiempo real, bloqueando el riel de salida antes del retiro en cajero.
