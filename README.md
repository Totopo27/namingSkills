# Framework Profesional de Ingeniería de Naming

Suite de skills **LLM-first** para la investigación estratégica, divergencia cuantitativa, filtrado morfológico, clearing registral y defensa de proyectos de **Naming Profesional**, diseñada con compatibilidad agnóstica multi-runtime y redacción anti-IA.

---

## 🎯 Principio Rector de Divergencia

> *"No se busca el nombre definitivo de forma aislada; se generan sistemáticamente nombres en relación a un territorio conceptual."*

El naming profesional es una disciplina de **documentación exhaustiva, divergencia cuantitativa rigurosa y convergencia técnica implacable**.

---

## 🧩 Ecosistema de Skills (`.agents/skills/` & `.opencode/skills/`)

| Skill | Trigger Principal | Responsabilidad |
| :--- | :--- | :--- |
| **`escribe-humano`** | `escribe-humano`, `redacción humana` | Motor de prosa anti-IA (StoryScope): erradica clichés de LLM, adjetivación publicitaria vacía y moralejas en briefs y dossiers. |
| **`naming-research-fondo`** | `research fondo naming`, `propuesta ohmae naming` | Investiga visión a 5 años, arquetipo de usuario y propuesta de valor estructural (**Modelo Ohmae**: qué capacidad real crea al usuario). |
| **`naming-research-forma`** | `research forma naming`, `etimologias naming` | Minería léxica agnóstica de runtime: rastrea raíces grecolatinas, glosarios técnicos de industria y jerga/slang urbano vivo. |
| **`naming-brief`** | `naming brief`, `crear brief naming` | Formaliza el briefing maestro de Fondo y Forma antes de generar palabras. |
| **`naming-divergence`** | `naming divergence`, `lista larga naming` | Genera la lista larga (*Longlist*) de **~70 nombres** aplicando 6 motores morfosemánticos sin autocensura. |
| **`naming-filter`** | `naming filter`, `shortlist naming` | Destila la lista larga a exactamente **10–15 nombres** mediante la prueba de aislamiento visual (Ficha A5) y diversidad tipológica. |
| **`naming-clearing`** | `naming clearing`, `viabilidad legal naming` | La batalla del registro: audita las **46 Clases de Niza**, el **Google Test en Página 1**, dominios `.com` y colisión lingüística internacional (con modo online y degradación elegante offline). |
| **`naming-pitch`** | `naming pitch`, `presentar naming` | Estructura el dossier de entrega con defensa orientada al usuario, psicología cognitiva (simbolismo fonético, fluidez de procesamiento) y respaldo de la Longlist completa. |

---

## 🔄 Flujo de Trabajo y Compuertas (*Decision Gates*)

```
[ Research Fondo + Forma ] ──► [ Naming Brief ] ──► [ Divergencia: ~70 Nombres ]
                                                           │
                                                           ▼
[ Dossier Pitch ] ◄── [ Clearing: Niza + Google ] ◄── [ Filtro: 10-15 Fichas A5 ]
```

Consulte [NAMING_WORKFLOW.md](./NAMING_WORKFLOW.md) para la matriz completa de compuertas binarias y transiciones.

---

## 🌐 Compatibilidad Multi-Runtime e Instalación

El repositorio sigue la convención portable universal `.agents/skills/`:

| Runtime | Directorio de Detección | Soporte |
| :--- | :--- | :---: |
| **OpenCode** | `.opencode/skills/` y `.agents/skills/` | Nativo |
| **Claude Code** | `.claude/skills/` o `~/.claude/skills/` | Vía symlink / copia |
| **Pi / Codex / Gemini CLI / Antigravity** | `.agents/skills/` | Nativo |

Para enlazar globalmente en tu máquina personal:
```bash
# Ejemplo para Claude Code o entornos compartidos:
cp -r .agents/skills/* ~/.agents/skills/
```

---

## 🚀 Guía de Uso Rápido e Invocación

El framework ofrece dos modos de interacción según la preferencia del usuario o del equipo:

### Modo A: Flujo Guiado End-to-End (Recomendado)
Para iniciar un proceso completo guiado por compuertas de validación (*Gates*), simplemente escriba en el chat con el agente:

```text
"Quiero iniciar un proyecto de naming para [descripción breve del negocio / producto / servicio]"
```

*Ejemplo:*
> *"Quiero iniciar un proyecto de naming para una plataforma de ciberseguridad industrial dirigida a plantas manufactureras en Latinoamérica."*

**Comportamiento automático del orquestador:**
1. **Fase 0 (Documentación)**: Activa automáticamente `naming-research-fondo` + `naming-research-forma` procesadas con `escribe-humano` para generar `brief_fondo.md` (visión a 5 años, usuario y valor Ohmae) y `banco_lexico.md` (etimologías, glosarios de industria y slang urbano).
2. **Fase 1 (Brief Maestro)**: Consolida `NAMING_BRIEF.md` y solicita confirmación binaria explícita del cliente antes de inventar palabras.
3. **Fase 2 (Divergencia Cuantitativa)**: Activa `naming-divergence` para producir la lista larga estricta de ~70 nombres (`naming_longlist.md`) categorizados en los 6 motores morfosemánticos.
4. **Fase 3 (Filtrado y Fichas A5)**: Activa `naming-filter` para destilar a 10–15 finalistas evaluados en aislamiento monocrómico (`naming_shortlist.md`).
5. **Fase 4 (Clearing Registral)**: Ejecuta `naming-clearing` para auditar Clases de Niza, el Google Test en Página 1, disponibilidad de dominios y screening de colisión panhispánica (`naming_clearing_report.md`).
6. **Fase 5 (Dossier y Pitch)**: Genera `DOSSIER_PRESENTACION_NAMING.md` con argumentación de psicología cognitiva (simbolismo fonético Bouba/Kiki, fluidez de procesamiento), desmonte de objeciones subjetivas y la Longlist como respaldo de rigor.

---

### Modo B: Invocación Modular Quirúrgica (Paso a Paso)
Si desea ejecutar fases aisladas o integrarlas en sus propios workflows, puede invocar directamente cada skill mediante sus triggers reconocidos:

| Paso del Flujo | Trigger Recomendado | Qué ejecuta el Agente | Artefacto Resultante |
| :--- | :--- | :--- | :--- |
| **0. Fondo** | `research fondo naming para [tema]` | Extrae visión a 5 años, arquetipo de usuario y propuesta Ohmae. | `brief_fondo.md` |
| **0. Forma** | `research forma naming para [tema]` | Rastrea etimologías grecolatinas, jerga técnica y slang por ciudad. | `banco_lexico.md` |
| **1. Brief** | `naming brief` o `crear brief naming` | Formaliza el briefing integral y define la arquitectura de marca. | `NAMING_BRIEF.md` |
| **2. Divergencia**| `naming divergence` o `lista larga naming` | Genera la cuota métrica de ~70 nombres sin censura. | `naming_longlist.md` |
| **3. Filtro** | `naming filter` o `shortlist naming` | Reduce a 10–15 nombres en Fichas A5 con tipologías balanceadas. | `naming_shortlist.md` |
| **4. Clearing**| `naming clearing` o `viabilidad legal naming` | Audita Niza, Google pág. 1, dominios y doble sentido en Latam/España. | `naming_clearing_report.md` |
| **5. Pitch** | `naming pitch` o `presentar naming` | Construye el dossier de defensa con psicología cognitiva y anexos. | `DOSSIER_PRESENTACION_NAMING.md` |

---

## 📜 Licencia

Apache-2.0. Desarrollado por Totopo27.
