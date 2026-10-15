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

## 🚀 Guía de Uso

1. Coloque los insumos del negocio o proyecto en su directorio de trabajo.
2. Invoque la investigación estratégica en chat con el agente:
   ```bash
   "research fondo naming para una plataforma de analítica de datos en logística"
   ```
3. Siga la secuencia por compuertas hasta la generación del dossier final.

---

## 📜 Licencia

Apache-2.0. Desarrollado por Totopo27.
