# Diagnóstico de conformidad BOE-A-2026-10594 (Anexo II)

## Grado en Ingeniería Informática — Universidad Europea del Atlántico (modifica 2025)

> **Contexto normativo.** El 15 de mayo de 2026 se publicó en el BOE la Resolución de 31 de marzo de 2026 de la Secretaría General de Universidades (BOE-A-2026-10594), que establece nuevas recomendaciones para memorias de títulos en los ámbitos de la Ingeniería Informática e Ingeniería Técnica Informática. Este acuerdo reemplaza las recomendaciones de 2009 (BOE-A-2009-12977) y abre por primera vez la vía para que el Grado obtenga carácter habilitante para la profesión regulada de Ingeniero Técnico en Informática, siempre que el plan de estudios se ajuste a la estructura del Anexo II.

> **Situación de partida.** La memoria de verificación vigente (identificador 2503218, fecha 04/12/2025) declara explícitamente: *«HABILITA PARA EL EJERCICIO DE PROFESIONES REGULADAS: No»*. La modifica en curso es la oportunidad para invertir ese campo y obtener el reconocimiento habilitante sin añadir ni eliminar asignaturas de fondo, aprovechando que el contenido del plan ya cumple la estructura exigida.

Mención elegida: **Ingeniería del Software**

---

## Cambios incluidos en el modifica

| Cambio | Tipo | Impacto BOE |
|---|---|---|
| Incorporación de ASW (Arquitectura de Software) | Alta (nueva asignatura) | Cubre IS3/RAH14 directamente; refuerza IS1, IS4, IS5, IS6 |
| Eliminación de ING2 (Inglés II) | Baja (supresión) | Elimina 6 ECTS obligatorios sin bloque BOE |
| Posición de ASW: 3S2 (malla) vs. 4S1 (ficha ASW.md) | Pendiente de resolver | Sin impacto en conformidad, sí en prerequisitos |


---

## Resumen crediticio

| Módulo BOE (Anexo II) | ECTS exigidos | ECTS asignados | Estado |
|---|---|---|---|
| Formación básica | 60 | 60 | ✓ Conforme |
| Común a la rama de informática | 60 | 60 | ⚠ 4 lagunas formales menores (ver análisis) |
| Tecnología específica — Ingeniería del Software | 48 | 48 | ✓ Conforme |
| Trabajo Fin de Grado | 12 | 12 | ✓ Conforme |
| Resto (optativas, prácticas, otros obligatorios) | — | 60 | N/A |
| **Total** | **240** | **240** | |

---

## Módulo Formación Básica (60 ECTS) — 10 asignaturas

El BOE 2026 exige materias de: álgebra lineal, cálculo, métodos numéricos, estadística, campos y ondas, circuitos electrónicos, matemática discreta, lógica, algorítmica, uso y programación de computadores, estructura de sistemas informáticos, organización y gestión de empresas.

| Sem | Sigla | Asignatura | ECTS | Materia BOE |
|---|---|---|---|---|
| S1 | FIS | Física | 6 | Fundamentos físicos de la informática |
| S1 | MAT1 | Matemática I | 6 | Fundamentos matemáticos de la informática |
| S1 | PRG1 | Programación I | 6 | Programación |
| S1 | TEO | Tecnología y estructura de ordenadores | 6 | Ingeniería de ordenadores |
| S2 | MAT2 | Matemática II | 6 | Fundamentos matemáticos de la informática |
| S2 | MDISC | Matemática discreta | 6 | Fundamentos matemáticos de la informática |
| S2 | LOG | Lógica | 6 | Fundamentos matemáticos de la informática |
| S2 | PRG2 | Programación II | 6 | Programación |
| S3 | MNUM | Matemática numérica | 6 | Fundamentos matemáticos de la informática |
| S3 | EST | Estadística | 6 | Fundamentos matemáticos de la informática |



---

## Módulo Común a la rama de informática (60 ECTS) — 10 asignaturas

| Sem | Sigla | Asignatura | ECTS | RAs activos |
|---|---|---|---|---|
| S3 | EDA1 | Estructuras de datos y algoritmos I | 6 | RAK2, RAH6, RAC5, RAC6 |
| S3 | BD1 | Bases de datos I | 6 | RAH10, RAH11 |
| S4 | EDA2 | Estructuras de datos y algoritmos II | 6 | RAK2, RAH6, RAC5, RAC6 |
| S4 | BD2 | Bases de datos II | 6 | RAH10, RAH11 |
| S4 | SOP | Sistemas operativos | 6 | RAH5, RAH8 |
| S5 | PW1 | Programación web I | 6 | RAH11, RAC2, RAC6, RAC7 |
| S6 | PW2 | Programación web II | 6 | RAH11, RAC2, RAC6, RAC7 |
| S6 | SICR | Seguridad informática y criptografía | 6 | RAH4, RAH5, RAC8 |
| S7 | SDPP | Sistemas distribuidos y prog. en paralelo | 6 | RAH9, RAH12 |
| S7 | INTA | Inteligencia artificial | 6 | RAH13 |

### Cobertura competencial del módulo Común

| Competencia BOE 2026 | RA | Estado | Asignatura(s) |
|---|---|---|---|
| C1: Diseñar/evaluar aplicaciones (fiabilidad, seguridad, calidad) | RAC2 | ✓ | PW1, PW2 |
| C2: Planificar, concebir, dirigir proyectos y sistemas | RAC3 | ✗ laguna | Cubierta en módulo específico: FPSW, ISW2, DSI, PRY |
| C3: Negociación, liderazgo, comunicación | RAC4 | ✗ laguna | Cobertura implícita: PRY, DSI, EEE. Ver estrategia. |
| C4: Pliego de condiciones técnicas | RAH4 | ✓ | SICR |
| C5: Administración y mantenimiento de sistemas | RAH5 | ✓ | SOP, SICR |
| C6: Procedimientos algorítmicos, idoneidad y complejidad | RAC5 | ✓ | EDA1, EDA2 |
| C7: Estructuras de datos | RAH6 | ✓ | EDA1, EDA2 |
| C8: Construir aplicaciones robustas, paradigmas y lenguajes | RAC6 | ✓ | EDA1, EDA2, PW1, PW2 |
| C9: Arquitectura de computadores | RAH7 | ✗ laguna | Cubierta en Formación Básica: TEO. Duplicidad normativa en el propio BOE. |
| C10: Sistemas operativos y aplicaciones sobre sus servicios | RAH8 | ✓ | SOP |
| C11: Sistemas distribuidos, redes, Internet | RAH9 | ✓ | SDPP |
| C12: Bases de datos | RAH10 | ✓ | BD1, BD2 |
| C13: Sistemas de información, almacenamiento, web | RAH11 | ✓ | BD1, BD2, PW1, PW2 |
| C14: Programación paralela, concurrente, distribuida | RAH12 | ✓ | SDPP |
| C15: Sistemas inteligentes | RAH13 | ✓ | INTA |
| C16: Principios, metodologías y ciclos de vida de IS | RAK4 | ✗ laguna | Cubierta en módulo específico: FPSW, ISW2 |
| C17: Interfaces persona-computador, accesibilidad | RAC7 | ✓ | PW1, PW2 |
| C18: Normativa y regulación informática | RAC8 | ✓ | SICR |

---

## Módulo Tecnología Específica — Ingeniería del Software (48 ECTS) — 8 asignaturas

| Sem | Sigla | Asignatura | ECTS | RAs activos |
|---|---|---|---|---|
| S1 | FPSW | Fundamentos de proyectos y software | 6 | RAK4, RAC3, RAC9, RAC10, RAC11, RAC12 |
| S2 | TIC | Tecnologías de la información y comunicación | 6 | RAH5, RAC2, RAC11 |
| S4 | ISW1 | Ingeniería de software I | 6 | RAK2, RAH4, RAH14, RAC2, RAC6, RAC9, RAC11, RAC13 |
| S5 | ISW2 | Ingeniería de software II | 6 | RAK4, RAH5, RAC3, RAC7, RAC10, RAC11, RAC12 |
| S5 | ETI | Ética y legislación informática | 6 | RAK3, RAH4, RAC2, RAC8, RAC13 |
| S6 | ASW | Arquitectura de software *(nueva)* | 6 | RAK2, RAH14, RAC2, RAC6, RAC9, RAC11, RAC12, RAC13 |
| S7 | PRY | Proyectos | 6 | RAH4, RAC3, RAC4, RAC10, RAC11, RAC12 |
| S8 | DSI | Dirección de sistemas de información | 6 | RAH4, RAH14, RAC3, RAC4, RAC10, RAC12, RAC13 |

> **Posición de ASW en la malla.** La malla objetivo del repo la ubica en 3S2 (semestre 6). La ficha `ASW.md` indica "4to curso, 1er semestre" (semestre 7). La cobertura competencial es idéntica en ambos casos; la decisión afecta al prerequisito de ISW2 (3S1) y a la secuencia del hilo FPSW → ISW1 → ISW2 → ASW documentada en `organizarHilo.md`. Se recomienda fijar 3S2 como posición definitiva para mantener el hilo completo dentro del tercer curso.

### Contenido de ASW y su alineación con el BOE 2026

El temario de ASW cubre tres bloques (según `ASW.md`):

- **Patrones**: creacionales, estructurales, comportamiento — cubre diseño detallado de módulos (RAC6, RAC9).
- **Arquitecturas**: principios, estilos, MVC y variantes — cubre diseño arquitectónico explícito (RAH14, RAC11).
- **Metodologías**: RUP (requisitos, análisis, diseño, implementación, pruebas) y Agilismo (XP, refactoring, TDD) — cubre ciclos de vida y verificación (RAK2, RAC12, RAC13).

Esta cobertura resuelve directamente IS3 (RAH14: problemas de integración), que era la competencia más débilmente cubierta en la versión anterior del plan sin ASW.

### Cobertura competencial del módulo específico

| Competencia BOE 2026 | RA | Estado | Asignatura(s) |
|---|---|---|---|
| IS1: Desarrollar/evaluar servicios SW (requisitos, fiabilidad, calidad) | RAC9 | ✓ | FPSW, ISW1, ASW |
| IS2: Valorar necesidades del cliente, especificar requisitos | RAC10 | ✓ | FPSW, ISW2, DSI, PRY |
| IS3: Problemas de integración | RAH14 | ✓ | ISW1, **ASW**, DSI |
| IS4: Identificar problemas, diseñar/documentar soluciones SW | RAC11 | ✓ | FPSW, TIC, ISW1, ISW2, ASW, PRY |
| IS5: Identificar/gestionar riesgos | RAC12 | ✓ | FPSW, ISW2, ASW, DSI, PRY |
| IS6: Soluciones integrando ética, social, legal, económico | RAC13 | ✓ | ISW1, ASW, DSI, ETI |

**Resultado: 6/6 competencias cubiertas. Sin lagunas.**

---

## Asignaturas sin adscripción a módulo BOE (60 ECTS)

| Sem | Sigla | Asignatura | ECTS | Carácter | Observación |
|---|---|---|---|---|---|
| S3 | RED | Redes de ordenadores | 6 | Obligatoria | Contenido solapado con RAH9 (SDPP); no genera laguna |
| S4 | LPR | Lenguajes de programación | 6 | Obligatoria | Complementa RAC6 del bloque Común |
| S5 | ING3 | Inglés III | 6 | Obligatoria | Sin bloque BOE; ver nota |
| S6 | ING4 | Inglés IV | 6 | Obligatoria | Sin bloque BOE; ver nota |
| S8 | EEE | Economía de la empresa y emprendedores | 6 | Obligatoria | Apoya C3/RAC4 del bloque Común |
| S5–S8 | OPT1–4 | Optativas (1 bloque de 4) | 24 | Optativa | No cuentan para la mención |
| S7 | PRCT | Prácticas académicas externas | 6 | Prácticas externas | No exigidas ni prohibidas por el BOE |

> **Nota sobre ING3 e ING4.** Con la eliminación de ING2 que incluye la modifica, quedan 12 ECTS de inglés obligatorio sin hueco en la estructura BOE. No son un impedimento para la verificación, pero su carácter obligatorio puede generar preguntas de ANECA. La opción más limpia a futuro es convertirlos a optativos o integrar la competencia lingüística en los resultados de aprendizaje de asignaturas de proyecto (PRY, DSI).

---

## Diagnóstico de lagunas y estrategia de justificación

| # | Laguna | Competencia | Gravedad | Causa | Estrategia recomendada |
|---|---|---|---|---|---|
| 1 | C9 | Arquitectura de computadores | Nula | Competencia duplicada en el propio BOE 2026 (aparece en bloque Básico y en Común). Cubierta por TEO (Básica). | Citar la duplicidad normativa en la memoria. Sin acción. |
| 2 | C16 | Principios, metodologías y ciclos de vida de IS | Baja | Es competencia nuclear de IS. Cubierta en el módulo específico por FPSW e ISW2. | Argumentar coherencia disciplinar: las metodologías y ciclos de vida IS se desarrollan con profundidad suficiente en el módulo específico, que es su lugar natural. |
| 3 | C2 | Planificar, concebir, dirigir proyectos | Baja | Cubierta en el módulo específico (FPSW, ISW2, DSI, PRY) y de forma transversal en EEE. | Argumentar cobertura cruzada entre módulos. El BOE 2026 no impide que competencias del Común sean reforzadas en el módulo específico. |
| 4 | C3 | Negociación, liderazgo, comunicación | Media | Ningún RA del bloque Común mapea directamente esta competencia. Cobertura implícita vía trabajo en equipo en PRY y DSI. | **Opción A (recomendada):** añadir un resultado de aprendizaje explícito sobre comunicación y trabajo en equipo a una asignatura del Común, por ejemplo EDA1 o SICR, que ya tienen carácter metodológico. **Opción B:** argumentar transversalidad documentando evidencias en las guías docentes de PRY y DSI. |

---

## Cambios necesarios en la memoria para obtener el carácter habilitante

Los siguientes cambios son estrictamente documentales o de reclasificación. No requieren crear nuevas asignaturas más allá de ASW, que ya está planificada en la modifica.

| Campo de la memoria | Valor actual | Valor propuesto |
|---|---|---|
| Habilita para profesiones reguladas | No | Sí |
| Norma de habilitación | — | Resolución de 31 de marzo de 2026, Secretaría General de Universidades (BOE-A-2026-10594), Anexo II; Orden CIN/352/2009 |
| Listado de menciones | *No existen datos* | Ingeniería del Software (48 ECTS) |
| Asignaturas de la mención IS | — | FPSW, TIC, ISW1, ISW2, ETI, ASW, PRY, DSI |
| Módulo Común a la rama | Sin mención formal | 10 asignaturas declaradas (ver tabla) |

---

## Hilo de Ingeniería del Software en la malla resultante

La modifica consolida un hilo vertical de cuatro asignaturas de construcción (categoría `<<Construccion>>`) que recorre los cuatro cursos:

```
1S1  FPSW   Fundamentos de proyectos y software   → visión global del proceso
2S2  ISW1   Ingeniería de software I               → modelado, análisis, diseño
3S1  ISW2   Ingeniería de software II              → requisitos, pruebas, gestión
3S2  ASW    Arquitectura de software               → patrones, estilos, metodologías
```

Este hilo se corresponde exactamente con las competencias IS1–IS6 del módulo específico del BOE 2026 y constituye el argumento pedagógico central para justificar la mención ante ANECA.

---

## Referencias normativas

- BOE-A-2026-10594. Resolución de 31 de marzo de 2026, Secretaría General de Universidades. Acuerdo del Consejo de Universidades sobre recomendaciones para memorias de títulos en los ámbitos de la Ingeniería Informática e Ingeniería Técnica Informática. *BOE* núm. 118, 15 de mayo de 2026, pp. 67488–67507.
- BOE-A-2009-12977. Orden CIN/352/2009, de 9 de febrero. Requisitos para la verificación de títulos universitarios oficiales que habiliten para el ejercicio de la profesión de Ingeniero Técnico en Informática. *BOE* núm. 44, 20 de febrero de 2009.
- Real Decreto 822/2021, de 28 de septiembre, por el que se establece la organización de las enseñanzas universitarias y el procedimiento de aseguramiento de su calidad.
- Memoria de verificación del Grado en Ingeniería Informática, UNEATLANTICO. Identificador 2503218, fecha 04/12/2025.
