---
name: naming-research-forma
description: "Trigger: research forma naming, investigacion lexica naming, etimologias naming. Rastrea etimologias, glosarios tecnicos, Wikipedia y slang."
license: Apache-2.0
metadata:
  author: "Gentleman-Programming"
  version: "1.0"
---

# Skill: naming-research-forma

## Activation Contract

Activa cuando se requiera recolectar combustible léxico y lingüístico sobre un tema específico antes o durante la fase de divergencia de naming.

## Hard Rules

- El naming es una actividad de documentación exhaustiva, no de inspiración aislada.
- No juzgar si una palabra sirve como marca final durante la recolección; registrar sin censura.
- Obligatorio explorar un mínimo de 4 fuentes: Wikipedia (enlaces temáticos), etimologías grecolatinas/locales, glosarios gremiales/técnicos, y jerga/slang urbano.
- Extraer raíces morfológicas vivas, sufijos, prefijos y términos de uso interno de la industria.

## Decision Gates

| Tipo de Industria / Producto | Fuentes Primarias de Forma |
| :--- | :--- |
| Técnico, industrial o B2B especializado | Glosarios profesionales y jerga operativa de taller (ej. RAG en call centers). |
| Estilo de vida, noche, ocio, subcultura | Slang urbano local por ciudades (Londres, NY, Madrid, Santiago) y cultura popular. |
| Bienestar, descanso, medicina, ciencia | Etimologías latinas y griegas clásicas (ej. Cauma -> Calma). |
| Identidad arraigada o productos de la tierra (vinos, gastronomía) | Toponimia histórica, mapas catastrales antiguos, términos romanos/locales (ej. La Fou, Corpinat). |

## Execution Steps

1. **Wikipedia Deep-Dive**: Ingresar al artículo madre del sector y explorar sistemáticamente los hipervínculos azules relacionados con conceptos clave.
2. **Minería Etimológica**: Consultar raíces en `etimonline.com`, `etimologias.dechile.net` o RAE para palabras asociadas al núcleo de valor.
3. **Extracción de Glosarios**: Buscar diccionarios gremiales de términos técnicos, jergas profesionales y acrónimos del sector.
4. **Rastreo de Slang y Cultura**: Mapear términos informales, expresiones orales y modismos del target en sus ciudades foco.
5. **Consolidar Territorios**: Agrupar los hallazgos en al menos 6 a 8 clusters conceptuales diferenciados.

## Output Contract

Generar o actualizar `banco_lexico.md` con:
- `Wikipedia_Concepts`: Lista de 15+ términos de contexto.
- `Etymologies_Roots`: 10+ raíces clásicas y latinas con significado original.
- `Industry_Glossary`: 10+ términos técnicos/operativos del gremio.
- `Slang_and_Vernacular`: 10+ términos de jerga urbana o cultura callejera.
- `Conceptual_Territories`: 6 a 8 ejes temáticos listos para divergencia.

## References

- `references/sources-guide.md` — Directorio de fuentes documentales recomendadas para naming.
