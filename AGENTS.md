# Configuración de Agentes y Skills del Proyecto: namingSkills

Este repositorio contiene el **Framework Profesional de Ingeniería de Naming**, desarrollado bajo estándares **LLM-first** agnósticos de runtime y la política de redacción anti-IA de **`escribe-humano`**.

## Arquitectura de Skills y Directorios

Las skills están estructuradas bajo el estándar universal `.agents/skills/` con compatibilidad nativa en `.opencode/skills/`:

| Skill | Trigger Principal | Responsabilidad |
| :--- | :--- | :--- |
| `escribe-humano` | `escribe-humano`, `redacción humana`, `narrativa humana` | Aplica reglas estructurales anti-IA de StoryScope para toda la prosa, relatos de marca, justificaciones y dossiers. |
| `naming-research-fondo` | `research fondo naming`, `auditar negocio naming`, `propuesta ohmae naming` | Investiga visión a 5 años, arquetipo de usuario y propuesta de valor estructural bajo el modelo Ohmae. |
| `naming-research-forma` | `research forma naming`, `investigacion lexica naming`, `etimologias naming` | Rastrea etimologías (latín/griego), glosarios técnicos de industria, conceptos clave y jerga/slang urbano. |
| `naming-brief` | `naming brief`, `crear brief naming`, `estructurar brief naming` | Consolida y formaliza el briefing integral de Fondo y Forma antes de la generación. |
| `naming-divergence` | `naming divergence`, `lista larga naming`, `divergencia naming` | Genera la lista larga (*Longlist*) de ~70 nombres sin censura aplicando los 6 motores morfosemánticos. |
| `naming-filter` | `naming filter`, `lista corta naming`, `shortlist naming` | Destila la lista larga a exactamente 10-15 nombres mediante la prueba de aislamiento visual (Ficha A5) y diversidad tipológica. |
| `naming-clearing` | `naming clearing`, `screening marcas naming`, `viabilidad legal naming` | Audita viabilidad registral (46 clases de Niza), test implacable de Google página 1, dominios web y choque lingüístico (online u offline). |
| `naming-pitch` | `naming pitch`, `presentar naming`, `argumentar naming` | Estructura el dossier de entrega final con defensa centrada en el usuario, psicología cognitiva y respaldo de la Longlist completa. |

## Reglas Operativas No Negociables
1. **Redacción Desprovista de Aroma a IA (`escribe-humano`)**: Toda narrativa de marca, justificación etimológica, perfil de usuario en el brief y fichas de defensa en el pitch deben redactarse sin clichés sintácticos de LLM, sin moralejas de cierre, sin fórmulas corporativas edulcoradas y con anclaje concreto, crudo y directo.
2. **Principio Rector de Divergencia**: *"No se busca el nombre definitivo; se generan sistemáticamente nombres en relación a un territorio conceptual"*.
3. **Cero Salto de Fases**: Nunca iniciar la divergencia de nombres sin tener aprobado el `NAMING_BRIEF.md`.
4. **Volumen de Divergencia**: No filtrar hasta alcanzar la cuota métrica de ~70 candidatos.
5. **Defensa por Usuario y Psicología Cognitiva**: Queda prohibido justificar un nombre por gusto subjetivo; toda defensa apela al usuario final, fluidez de procesamiento y simbolismo fonético.
