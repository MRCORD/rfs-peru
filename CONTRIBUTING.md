# Guía de Contribución: Request for Startups (RFS: Perú) 🇵🇪🤝

> **Filosofía de Contribución:** Este repositorio no es un foro de quejas ni un muro de lamentos. Es un **laboratorio abierto de investigación y formulación de startups**. Si vas a señalar un problema, debes desglosarlo con datos duros y proponer o posibilitar una tesis de solución tecnológica.

---

## 🎯 Las 3 Vías Principales de Contribución

```
1. [NUEVO PROBLEMA]       ──► Trae un cuello de botella estructural que aún no esté catalogado.
2. [EVIDENCIA / NOTICIA]  ──► Aporta noticias, papers, datos del INEI o enlaces para respaldar problemas existentes.
3. [TESIS DE STARTUP]     ──► Propón una hipótesis de negocio/software para resolver una falla documentada.
```

---

## 1. Reglas para Proponer un Nuevo Problema

Antes de abrir un Issue o enviar un Pull Request para agregar un archivo en `problems/`:

1. **Sin Quejas Ad-Hominem ni Partidistas:**  
   No aceptamos issues como *"los congresistas son unos ladrones"* o *"el alcalde clausura porque es corrupto"*. La ciencia política analiza **fallas de incentivos, de lectura de datos o de diseño institucional**.
2. **Debe Contener al Menos un Dato Numérico Verificable:**  
   Obligatorio incluir métricas (tasa de impunidad, costo logístico, días de espera, porcentaje de pérdida, número de personas afectadas). Cita la fuente oficial (INEI, BCRP, FAO, Banco Mundial, SBS, etc.).
3. **Debe Responder a un Arquetipo Sistémico:**  
   Revisa [`framework/systemic_mechanics_vs_specific_symptoms.md`](framework/systemic_mechanics_vs_specific_symptoms.md) y clasifica la falla en uno de los 6 arquetipos universales.
4. **Formato Frontmatter Obligatorio:**  
   Todo archivo dentro de `problems/` debe iniciar con el bloque YAML estándar:
   ```yaml
   ---
   id: D[1-6]-[01-99]
   domain_id: D1
   domain_name: Nombre del Dominio
   title: Título descriptivo y neutral
   severity: critical | high | medium
   metrics:
     clave_1: valor
     clave_2: valor
   market_scaling:
     tam_peru_usd: "$XX"
     tam_latam_usd: "$XX"
     tam_global_usd: "$XX"
   startup_theses:
     - Tesis 1
     - Tesis 2
   ---
   ```

---

## 2. Cómo Enviar un Pull Request (Paso a Paso)

1. **Haz un Fork** del repositorio a tu cuenta de GitHub.
2. **Crea una rama descriptiva:**
   ```bash
   git checkout -b feature/D3-anemia-tamizaje-seguimiento
   ```
3. **Agrega o edita el archivo en la carpeta correspondiente de `problems/`** (ej. `problems/D3_salud_y_capital_humano/D3-02-anemia-primera-infancia.md`).
4. **Actualiza `index.json`** agregando los metadatos de tu nuevo archivo.
5. **Envía tu Pull Request** asegurándote de completar el checklist del PR Template.

---

## 3. Código de Conducta y Propiedad Intelectual

- Este proyecto utiliza la **Licencia MIT**. Todo el contenido, datos y tesis aportados son de dominio público para fundadores e investigadores.
- No requieres pedir permiso a los autores para usar estas tesis de startup para postular a aceleradoras (YC, Techstars), levantar capital de riesgo o fundar una empresa. **Queremos que las construyas.**

---

*Para dudas o debates conceptuales, utiliza la pestaña de [GitHub Discussions](../../discussions) o abre un Issue.*
