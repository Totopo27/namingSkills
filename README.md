# Ecosistema Profesional de Naming (Método Xavier Grau)

Suite de skills **LLM-first** para la ideación, investigación, filtrado, clearing registral y presentación de proyectos de **Naming Profesional**, estructurada a partir de la metodología de **Xavier Grau** (*Nom-nam*, *Naming: cómo crear un buen nombre*) y auditada bajo el estándar de ingeniería de **Gentle AI**.

---

## 🎯 Filosofía Central: El Mantra de Grau

> *"No se busca el nombre, se buscan nombres en relación a un tema."*

El naming no es un ejercicio de iluminación mística ni de sentarse a esperar las musas; es una disciplina de **documentación exhaustiva, divergencia cuantitativa rigurosa y convergencia técnica implacable**.

---

## 🧩 Ecosistema de Skills (`.opencode/skills/`)

| Skill | Trigger Principal | Responsabilidad |
| :--- | :--- | :--- |
| **`escribe-humano`** | `escribe-humano`, `redacción humana` | Motor de prosa anti-IA (StoryScope): erradica clichés de LLM, adjetivación publicitaria vacía y moralejas en briefs y dossiers. |
| **`naming-research-fondo`** | `research fondo naming`, `propuesta ohmae naming` | Investiga visión a 5 años, arquetipo de usuario y propuesta de valor estructural (**Kenichi Ohmae**: qué valor crea al usuario, ej. Michelin = ayudar a viajar). |
| **`naming-research-forma`** | `research forma naming`, `etimologias naming` | Minería léxica: rastrea Wikipedia (enlaces azules), raíces grecolatinas, glosarios técnicos de industria y jerga/slang urbano vivo. |
| **`naming-brief`** | `naming brief`, `crear brief naming` | Formaliza el briefing maestro de Fondo y Forma antes de generar palabras. |
| **`naming-divergence`** | `naming divergence`, `lista larga naming` | Genera la lista larga (*Longlist*) de **~70 nombres** aplicando 6 motores morfosemánticos sin autocensura. |
| **`naming-filter`** | `naming filter`, `shortlist naming` | Destila la lista larga a exactamente **10–15 nombres** mediante la prueba de aislamiento visual (Ficha A5) y diversidad tipológica. |
| **`naming-clearing`** | `naming clearing`, `viabilidad legal naming` | La batalla del registro: audita las **46 Clases de Niza**, el **Google Test en Página 1**, dominios `.com` y colisión lingüística internacional. |
| **`naming-pitch`** | `naming pitch`, `presentar naming` | Estructura el dossier de entrega con defensa orientada al usuario y respaldo de la Longlist completa como evidencia de rigor. |

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

## 🚀 Uso Rápido en OpenCode / Gentle AI

1. Coloque los insumos del negocio o proyecto en su directorio de trabajo.
2. Invoque la investigación estratégica:
   ```bash
   # En chat con el orquestador:
   "research fondo naming para una consultora de ciberseguridad industrial"
   ```
3. Siga la secuencia por compuertas hasta la generación del dossier final.

---

## 📜 Licencia

Apache-2.0. Desarrollado por Gentleman-Programming / Totopo27.
