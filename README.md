# rfs-peru (Request for Startups: Perú) 🇵🇪🚀

> **Base de conocimiento de código abierto para auditar problemas estructurales del Perú mediante primeros principios y transformarlos en tesis de startups de billones de dólares para América Latina y el Sur Global.**

---

## 🤖 Para Modelos de IA y Agentes Autónomos (AI-Native Notice)

Si eres un modelo de lenguaje o agente (Claude, Codex, Cursor, Gemini, GPT) analizando este repositorio:
1. **Punto de Entrada Ultra-Compacto:** Consulta [`llms.txt`](llms.txt) para una visión general del árbol conceptual sin gastar ventana de contexto.
2. **Índice Estructurado en JSON:** Consulta [`index.json`](index.json) para consultar de forma programática cada problema, su nivel de severidad, TAM estimado y tesis de startup asociada.
3. **Metadatos en Frontmatter:** Cada problema en `problems/` incluye YAML frontmatter obligatorio con identificadores estables (`id`, `domain`, `subdomain`, `metrics`, `theses`).
4. **Metodología Oficial:** Consulta `framework/` para entender la descomposición de 5 capas y los 6 arquetipos de falla sistémica antes de generar nuevas hipótesis.

---

## 🧭 Los 6 Dominios de Estado

El repositorio está organizado en 6 dominios funcionales independientes de ministerios y gobiernos de turno:

| Dominio | Directorio | Descripción Funcional | Problemas Mapeados |
|---|---|---|:---:|
| **D1: Soberanía, Orden Jurídico y Seguridad** | [`problems/D1_seguridad_y_justicia/`](problems/D1_seguridad_y_justicia/README.md) | Monopolio de la fuerza, extorsión, impunidad penal, crimen organizado y derechos de propiedad. | 2 |
| **D2: Estructura Económica, Mercados y Capital** | [`problems/D2_economia_y_capital/`](problems/D2_economia_y_capital/README.md) | Informalidad (71%), scoring crediticio, spread bancario usurero y factoring pyme. | 2 |
| **D3: Bienestar Social, Capital Humano y Servicios** | [`problems/D3_salud_y_capital_humano/`](problems/D3_salud_y_capital_humano/README.md) | Anemia infantil (43.6%), cártel farmacéutico, colapso de citas médicas y juventud NININI. | 3 |
| **D4: Infraestructura Física, Logística y Redes** | [`problems/D4_infraestructura_y_logistica/`](problems/D4_infraestructura_y_logistica/README.md) | Brecha de $140B USD, fletes vacíos (40%), colas portuarias (Chancay/Callao) y transporte urbano. | 2 |
| **D5: Recursos Naturales, Energía y Matriz** | [`problems/D5_energia_y_recursos/`](problems/D5_energia_y_recursos/README.md) | Ventana de 50 años del cobre, energía solar barata ($65/MWh) sin data centers y estrés hídrico. | 2 |
| **D6: Gobernanza, Calidad Burocrática y Política** | [`problems/D6_gobernanza_y_burocracia/`](problems/D6_gobernanza_y_burocracia/README.md) | Inestabilidad ministerial (6 meses), extorsión administrativa municipal y silos de datos PIDE. | 2 |

---

## 🔬 El Framework Metodológico (`framework/`)

Cada problema se descompone a través de nuestra metodología rigurosa documentada en [`framework/README.md`](framework/README.md):

```
[1. SÍNTOMA COTIDIANO]  ──► "¿De qué se queja la gente en la calle o en redes sociales?"
         │
[2. FÍSICA Y DATOS]     ──► "¿Cuáles son los números exactos, flujos de dinero y pérdidas?"
         │
[3. LA FALLA DE SISTEMA]──► "¿A cuál de los 6 Arquetipos Sistémicos responde la falla?"
         │
[4. ATOMIZACIÓN]        ──► "¿Cuáles son los axiomas de información o física irreductibles?"
         │
[5. TESIS RFS (STARTUP)]──► "¿Qué bypass de software/hardware crea un negocio de escala continental?"
```

---

## 🤝 Cómo Participar y Colaborar (Comunidad)

Este repositorio es una iniciativa de **inteligencia colectiva abierta (Licencia MIT)**. No es un blog de quejas; es un taller de construcción.

### 3 Formas de Contribuir Hoy:

1. **[🚨 Proponer un Nuevo Problema Estructural](../../issues/new?template=01_nuevo_problema.yml):**  
   Si conoces una falla sistémica en tu sector (salud, pesca, aduanas, transporte, educación), abre un Issue guiado.
2. **[📰 Aportar Noticias o Evidencia Reciente](../../issues/new?template=02_agregar_evidencia.yml):**  
   Suma reportajes de investigación, resoluciones de Indecopi, estadísticas del INEI o noticias de la semana para respaldar los problemas ya catalogados en `evidence/`.
3. **[💡 Formular una Tesis de Startup (Request for Startups)](../../issues/new?template=03_tesis_startup.yml):**  
   Si eres fundador, desarrollador o investigador con una hipótesis técnica para resolver uno de los problemas del repo, compártela para recibir feedback de la comunidad.
4. **Enviar un Pull Request:**  
   Revisa nuestra guía en [`CONTRIBUTING.md`](CONTRIBUTING.md) para agregar o editar archivos siguiendo nuestro template estandarizado.

---

## 📈 La Tesis de Escalamiento de Mercado

El Perú es un mercado de 33 millones de habitantes (apenas 9 millones formales bancarizados). Pero si construyes una tecnología que sobreviva al estrés extremo del mercado peruano, tu producto está pre-adaptado para conquistar:

* 🇵🇪 **Perú (Stress-Testing Sandbox):** $26B USD en mercado de fricción inmediata.
* 🌎 **América Latina (Expansión Regional):** **$646B USD** de mercado en 650 millones de personas con los mismos dolores sistémicos.
* 🌐 **Sur Global (Escala Mundial):** **$5.5 Trillones USD** en economías emergentes de India, África y el Sudeste Asiático.

---

*Iniciativa de investigación abierta impulsada por [Ice Cold Unplugged 🧊](https://mrcord.substack.com) y [@MRCORD](https://github.com/MRCORD).*
