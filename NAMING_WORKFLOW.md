# FLUJO DE TRABAJO: Ecosistema Profesional de Naming (Método Xavier Grau)

> Basado en la conferencia magistral de **Xavier Grau** (*Nom-nam*, *Naming: cómo crear un buen nombre*) en Diséñala 2024.
> Diseñado bajo la arquitectura **LLM-first** de *Gentle AI* y compuertas medibles (*Decision Gates*).

```
   ┌─────────────────────────────────────────────────────────────────┐
   │                       FASE 0: DOCUMENTACIÓN                     │
   │   [naming-research-fondo]        [naming-research-forma]        │
   │   - Visión 5 años                - Wikipedia (enlaces azules)   │
   │   - Arquetipo de usuario         - Etimologías grecolatinas     │
   │   - Propuesta valor Ohmae        - Glosarios y Slang urbano     │
   └──────────────────────────────┬──────────────────────────────────┘
                                  │
                                  ▼
   ┌─────────────────────────────────────────────────────────────────┐
   │                    FASE 1: BRIEFING MAESTRO                     │
   │                        [naming-brief]                           │
   │     - Formalización de Fondo (Estratégico) y Forma (Léxico)     │
   │     - COMPUERTA 1: Validación binaria del brief con el cliente  │
   └──────────────────────────────┬──────────────────────────────────┘
                                  │
                                  ▼
   ┌─────────────────────────────────────────────────────────────────┐
   │                   FASE 2: DIVERGENCIA TOTAL                     │
   │                     [naming-divergence]                         │
   │   - Mantra: "No buscamos el nombre, buscamos nombres de..."     │
   │   - 6 Motores: Etimología, Glosario, Slang, Scrabble, Cruces,   │
   │     Metáforas/Toponimia                                         │
   │   - COMPUERTA 2: Lista larga de ~70 nombres sin censura         │
   └──────────────────────────────┬──────────────────────────────────┘
                                  │
                                  ▼
   ┌─────────────────────────────────────────────────────────────────┐
   │                FASE 3: FILTRADO Y AISLAMIENTO                   │
   │                       [naming-filter]                           │
   │   - Prueba visual de aislamiento monocrómico (Ficha A5)         │
   │   - Diversidad tipológica balanceada                            │
   │   - COMPUERTA 3: Shortlist destilada de 10 a 15 nombres         │
   └──────────────────────────────┬──────────────────────────────────┘
                                  │
                                  ▼
   ┌─────────────────────────────────────────────────────────────────┐
   │                 FASE 4: CLEARING REGISTRAL                      │
   │                      [naming-clearing]                          │
   │   - Mapeo de Clasificación de Niza (1 a 46)                     │
   │   - Prueba implacable: Google Página 1                          │
   │   - Búsqueda en bases de marcas (INAPI, OEPM, EUIPO, WIPO)      │
   │   - Verificación de dominios web y filtros lingüísticos         │
   │   - COMPUERTA 4: 3 a 5 nombres con semáforo verde o mitigable   │
   └──────────────────────────────┬──────────────────────────────────┘
                                  │
                                  ▼
   ┌─────────────────────────────────────────────────────────────────┐
   │              FASE 5: DOSSIER Y PRESENTACIÓN                     │
   │                       [naming-pitch]                            │
   │   - Argumentación centrada 100% en el usuario final             │
   │   - Desmonte técnico de objeciones subjetivas del cliente       │
   │   - Entrega de La Caja / Dossier con la Longlist como prueba    │
   └─────────────────────────────────────────────────────────────────┘
```

---

## Matriz de Habilidades y Compuertas de Validación (*Gates*)

| Fase | Skill Responsable | Artefacto Generado | Compuerta de Salida (*Gate*) |
| :--- | :--- | :--- | :--- |
| **0. Fondo** | `naming-research-fondo` + `escribe-humano` | `brief_fondo.md` | ¿Se definió la visión a 5 años, el usuario real y la propuesta de valor Ohmae sin adjetivos vacíos ni clichés de IA? |
| **0. Forma** | `naming-research-forma` | `banco_lexico.md` | ¿Se exploraron al menos 4 fuentes (Wikipedia, etimologías, glosarios y slang urbano)? |
| **1. Brief** | `naming-brief` + `escribe-humano` | `NAMING_BRIEF.md` | ¿El cliente validó explícitamente los pilares de Fondo y Forma redactados de forma directa y concreta? |
| **2. Divergencia** | `naming-divergence` | `naming_longlist.md` | ¿Se alcanzaron numéricamente los 70 nombres clasificados en los 6 motores sin autocensura? |
| **3. Filtro** | `naming-filter` | `naming_shortlist.md` | ¿Se redujo la lista a exactamente 10-15 nombres evaluados en aislamiento visual A5 y con tipologías diversas? |
| **4. Clearing** | `naming-clearing` | `naming_clearing_report.md` | ¿Los finalistas superaron el test de Google página 1, la clase de Niza y el filtro lingüístico internacional? |
| **5. Pitch** | `naming-pitch` + `escribe-humano` | `DOSSIER_PRESENTACION_NAMING.md` | ¿Las fichas de defensa están fundamentadas en el usuario, sin tono corporativo artificial ni moralejas, con la Longlist como prueba? |

---

## Directriz de Redacción: Integración con `escribe-humano`

Todo texto explicativo, historia de origen del nombre, descripción del usuario, narrativa de marca y argumentación en el dossier final debe procesarse obligatoriamente bajo las reglas estructurales de **`escribe-humano`**:
- **Cero aroma a IA**: Sin frases como *"en un mundo cada vez más digital"*, *"este nombre encapsula la sinergia"*, *"un viaje transformador"*, ni adjetivos de marketing inflado.
- **Anclaje a hechos y acciones concretas**: Usar términos técnicos, nombres de lugares, contextos físicos y fricciones reales del usuario.
- **Tono directo y sobrio**: El nombre se defiende por su función, su valor registrable y su conexión visceral con el arquetipo, no con poesía publicitaria genérica.
