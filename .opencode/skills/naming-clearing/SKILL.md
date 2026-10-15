---
name: naming-clearing
description: "Trigger: naming clearing, screening marcas naming, viabilidad legal naming. Valida Clases de Niza, screening registral, conflicto Google y dominios."
license: Apache-2.0
metadata:
  author: "Gentleman-Programming"
  version: "1.0"
---

# Skill: naming-clearing

## Activation Contract

Activa cuando la lista corta (`naming_shortlist.md`) esté conformada y se deba auditar su viabilidad legal, registral, técnica y lingüística antes de presentarla al cliente.

## Hard Rules

- **La Batalla del Registro**: Ningún nombre se presenta como opción viable sin haber pasado el triple filtro: Niza, Google y Disponibilidad de Dominios.
- **La Regla de Google Página 1**: Si el nombre arroja en la primera página de Google un competidor directo en el mismo sector y geografía, el nombre se considera **muerto** o de altísimo riesgo.
- **Clasificación Internacional de Niza**: Mapear obligatoriamente la clase (1 a 46) aplicable a la actividad económica.
- **Chequeo Lingüístico Internacional**: Verificar que el nombre no signifique algo ofensivo, escatológico o ridículo en los idiomas de los mercados objetivo (ej. ruso, mandarín, árabe, inglés).
- Toda evaluación en esta skill es un screening preliminar de viabilidad que orienta el dictamen definitivo de abogados especializados en propiedad industrial.

## Decision Gates

| Hallazgo en Screening | Acción Recomendada |
| :--- | :--- |
| Marca idéntica registrada en misma Clase de Niza | Descarte inmediato. |
| Marca parecida fonéticamente en clase conexa | Aplicar técnica de mitigación: añadir calificador corporativo o apodo secundario (ej. caso Grau: añadir *Big Blood* o nombre patronímico para facilitar concesión). |
| Dominio `.com` ocupado pero sin actividad real | Evaluar sufijos o prefijos corporativos aceptables según el brief, o negociar compra si el presupuesto lo amerita. |
| Término polisémico con riesgo en idioma destino | Descarte inmediato si vulnera sensibilidades culturales del target. |

## Execution Steps

1. Identificar la(s) clase(s) de Niza aplicable(s) en función del brief.
2. Ejecutar búsqueda preliminar en bases de datos de propiedad industrial (INAPI para Chile, OEPM para España, EUIPO para Europa, TMview o WIPO para internacional).
3. Ejecutar el **Google Test**: Búsqueda exacta del término combinado con el sector para verificar qué domina la primera página.
4. Auditar disponibilidad de dominios web prioritarios (`.com`, locales de país, etc.).
5. Evaluar colisiones fonéticas o semánticas negativas en lenguas secundarias relevantes.
6. Clasificar cada candidato de la shortlist en un semáforo de riesgo: Verde (Viable), Amarillo (Viable con mitigación/aditamento), Rojo (Inviable).

## Output Contract

Generar `naming_clearing_report.md` con:
- Tabla de dictamen preliminar por candidato: `Nombre`, `Clase Niza`, `Riesgo Registral`, `Riesgo Google Pág 1`, `Estado Dominio Web`, `Semáforo Final`.
- Estrategias de mitigación para nombres en Amarillo.
- Selección final de opciones limpias (entre 3 y 6 nombres aptos para la propuesta al cliente).

## References

- `references/nizza-and-screening.md` — Guía de las 46 clases de Niza y filtros de búsqueda registral.
