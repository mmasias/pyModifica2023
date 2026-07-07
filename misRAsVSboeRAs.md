# Mis RA vs RA del BOE-A-2026-10594 (Anexo II)

Contraste entre los 36 resultados de aprendizaje del grado (hoja RdA de `gII2025.xlsx`) y las dos columnas del Anexo II del BOE 2026 (competencias que deben adquirirse y resultados de aprendizaje) para los módulos que aplican: formación básica, común a la rama, mención Ingeniería del Software y TFG.

Veredicto: la correspondencia estructural es uno a uno y el esqueleto es correcto. Los déficits son léxicos, concentrados en 8 RA, y se corrigen con la tabla de redline de abajo sin tocar la matriz asignatura-RA.

Las lagunas de adscripción a módulo (competencia de empresa en la básica, C3 sin RA en el común) son un problema distinto, de mapeo y no de redacción: ver [ModificaVsBOE2026.md](ModificaVsBOE2026.md).

## Correspondencia completa

### Módulo de formación básica

| Competencia BOE (resumen) | Mi RA | Estado |
|---|---|---|
| B1: Resolución de problemas matemáticos: álgebra, cálculo, métodos numéricos, algorítmica numérica, estadística, optimización | RAK1, RAH2 | Conforme |
| B2: Campos y ondas, circuitos eléctricos y electrónicos, semiconductores | RAH1 | Conforme |
| B3: Matemática discreta, lógica, algorítmica y complejidad computacional | RAK1, RAH2 | Ajuste 1: RAK1 no nombra discreta, lógica ni complejidad |
| B4: Uso y programación de computadores, sistemas operativos, bases de datos | RAH3 | Conforme (SO y BD básicos se apoyan en asignaturas del común) |
| B5: Estructura, organización, funcionamiento e interconexión de sistemas informáticos | RAK2 | Conforme |
| B6: Concepto de empresa, marco institucional y jurídico, organización y gestión de empresas | RAC1 | RA existe; laguna de adscripción (EEE en S8, fuera de la básica) |

### Módulo común a la rama de informática

| Competencia BOE | Mi RA | Estado |
|---|---|---|
| C1: Diseñar, desarrollar, seleccionar y evaluar aplicaciones y sistemas (fiabilidad, seguridad, calidad) | RAC2 | Conforme |
| C2: Planificar, concebir, desplegar y dirigir proyectos, servicios y sistemas | RAC3 | Ajuste 3 (transversal ambiental) |
| C3: Negociación, hábitos de trabajo efectivos, liderazgo, comunicación | RAC4 | Ajuste 7; ademas laguna de adscripción en el común |
| C4: Pliego de condiciones técnicas | RAH4 | Conforme |
| C5: Conocimiento, desarrollo, operación, gestión de la configuración, administración y mantenimiento | RAH5 | Ajuste 5: falta operación y gestión de la configuración |
| C6: Procedimientos algorítmicos, idoneidad y complejidad | RAC5 | Conforme |
| C7: Tipos y estructuras de datos | RAH6 | Conforme |
| C8: Construir aplicaciones robustas: paradigmas y lenguajes | RAC6 | Conforme |
| C9: Estructura y arquitectura de computadores | RAH7 | Conforme |
| C10: Sistemas operativos y aplicaciones sobre sus servicios | RAH8 | Conforme |
| C11: Sistemas distribuidos, redes, internet | RAH9 | Conforme |
| C12: Bases de datos, centralizadas y distribuidas | RAH10 | Ajuste 6: falta "centralizadas y distribuidas" |
| C13: Sistemas de información, almacenamiento, web | RAH11 | Conforme |
| C14: Programación paralela, concurrente, distribuida y de tiempo real | RAH12 | Conforme |
| C15: Sistemas inteligentes | RAH13 | Conforme |
| C16: Principios, metodologías y ciclos de vida de la ingeniería de software | RAK4 | Conforme |
| C17: Interfaces persona-computador, accesibilidad y usabilidad | RAC7 | Ajuste 8 (opcional): diseño universal e inclusivo |
| C18: Normativa y regulación informática | RAC8 | Conforme |

### Módulo de tecnología específica: mención Ingeniería del Software

| Competencia BOE | Mi RA | Estado |
|---|---|---|
| IS1: Desarrollar, operar, mantener y evaluar servicios y sistemas software | RAC9 | Ajuste 4: falta operar, mantener y evaluar |
| IS2: Valorar necesidades del cliente y especificar requisitos | RAC10 | Conforme |
| IS3: Soluciones seguras a problemas de integración | RAH14 | Conforme |
| IS4: Identificar y analizar problemas; diseñar, desarrollar, verificar, validar y documentar soluciones | RAC11 | Conforme |
| IS5: Identificar, evaluar y gestionar riesgos | RAC12 | Conforme |
| IS6: Soluciones sostenibles integrando aspectos éticos, sociales, legales y económicos | RAC13 | Ajuste 2: falta sostenibles / ambiental |

### Trabajo Fin de Grado

| Competencia BOE | Mi RA | Estado |
|---|---|---|
| Ejercicio original, presentado y defendido ante tribunal, de naturaleza profesional, que sintetice e integre las competencias adquiridas | RAC15 | Conforme |

### RA propios sin contraparte BOE

RAH15, RAH16, RAH17 (inglés C1) y RAC14 (prácticas externas) no responden a ninguna exigencia del Anexo II. El acuerdo es de mínimos: los extras son admisibles y no computan en los módulos BOE.

## Redline: ajustes de redacción propuestos

| # | RA | Texto actual | Texto propuesto | Exigencia BOE que lo motiva |
|---|---|---|---|---|
| 1 | RAK1 | Describir los conceptos fundamentales de álgebra lineal, cálculo diferencial e integral, métodos numéricos, algorítmica numérica, estadística y optimización relevantes para la ingeniería. | Describir los conceptos fundamentales de álgebra lineal, cálculo diferencial e integral, métodos numéricos, algorítmica numérica, matemática discreta, lógica, complejidad computacional, estadística y optimización relevantes para la ingeniería. | Básica B3: "matemática discreta, lógica, algorítmica y complejidad computacional"; RA básica: "álgebra, cálculo, análisis, matemática discreta, lógica, estadística" |
| 2 | RAC13 | Diseñar soluciones de software en dominios específicos, integrando métodos de ingeniería del software con consideraciones éticas, sociales, legales y económicas. | Diseñar soluciones de software sostenibles en dominios específicos, integrando métodos de la ingeniería del software con consideraciones éticas, sociales, legales, económicas y ambientales. | IS6: "soluciones sostenibles"; RA de la mención: "limitaciones tecnológicas, legales y de sostenibilidad", "aspectos ambientales" |
| 3 | RAC3 | Gestionar proyectos y sistemas informáticos en diversas áreas, desde su concepción hasta su implementación, considerando su impacto económico y social. | Gestionar proyectos y sistemas informáticos en diversas áreas, desde su concepción hasta su implementación, considerando su impacto económico, social y ambiental. | RA básica y C2: "valorando su impacto económico, social y ambiental" |
| 4 | RAC9 | Desarrollar sistemas software que cumplan requisitos de usuario, fiabilidad, eficiencia y calidad, aplicando principios y prácticas de Ingeniería del Software. | Desarrollar, operar, mantener y evaluar sistemas software que cumplan requisitos de usuario, fiabilidad, eficiencia y calidad, aplicando principios y prácticas de la Ingeniería del Software. | IS1: "desarrollar, operar, mantener y evaluar servicios y sistemas software" |
| 5 | RAH5 | Implementar estrategias de administración y mantenimiento en sistemas, servicios y aplicaciones informáticas. | Implementar estrategias de operación, gestión de la configuración, administración y mantenimiento en sistemas, servicios y aplicaciones informáticas. | C5: "desarrollo, operación, gestión de la configuración, administración y mantenimiento" |
| 6 | RAH10 | Diseñar y utilizar bases de datos, aplicando sus características y funcionalidades en el desarrollo de aplicaciones. | Diseñar y utilizar bases de datos, centralizadas y distribuidas, aplicando sus características y funcionalidades en el desarrollo de aplicaciones. | C12: "bases de datos, centralizadas y distribuidas" |
| 7 | RAC4 | Aplicar habilidades interpersonales y de liderazgo en entornos de desarrollo de software, reconociendo su impacto en la eficacia del proceso. | Aplicar habilidades de negociación, comunicación, liderazgo y trabajo en equipos multidisciplinares en entornos de desarrollo de software, reconociendo su impacto en la eficacia del proceso. | C3: "negociación, hábitos de trabajo efectivos, liderazgo, comunicación"; RA común: "equipos humanos multidisciplinares" |
| 8 | RAC7 (opcional) | Diseñar interfaces de usuario, aplicando principios de accesibilidad y usabilidad en diversos contextos informáticos. | Diseñar interfaces de usuario, aplicando principios de accesibilidad, usabilidad y diseño universal e inclusivo en diversos contextos informáticos. | RA común: "principios de diseño universal e inclusivo" |
| 9 | RAC1 (menor) | Aplicar conceptos de economía, organización y gestión empresarial en el desarrollo y dirección de proyectos informáticos, valorando su viabilidad e impacto económico-social. | Aplicar conceptos de economía, organización y gestión empresarial en el desarrollo y dirección de proyectos informáticos, valorando su viabilidad y su impacto económico, social y ambiental. | RA básica: "impacto económico, social y ambiental" |

## Notas

- El patrón dominante es uno solo: el Anexo II de 2026 añade la dimensión ambiental/sostenibilidad de forma transversal y ninguno de los 36 RA la menciona. Los ajustes 2, 3 y 9 la resuelven en los tres RA donde el BOE la exige.
- El ajuste 7 (RAC4) conviene coordinarlo con la estrategia de la laguna C3: si se añade un RA de comunicación y trabajo en equipo a una asignatura del común, la palabra "multidisciplinares" debe estar en el texto.
- Los ajustes 4 y 7 tienen respaldo de práctica docente ya existente en ISW2 (evaluación y continuación de código propio y ajeno; sesiones de VibeCoding con log de decisiones): la redacción propuesta no promete nada que no se haga ya.
