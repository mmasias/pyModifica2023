# CLAUDE.md

Este archivo proporciona orientación a Claude Code (claude.ai/code) al trabajar con código en este repositorio.

## Descripción del Proyecto

Este es un repositorio de documentación académica en español para el proyecto "Modifica de Informática 2023", enfocado en el desarrollo curricular para un programa de grado en Ingeniería Informática. El repositorio contiene documentos de planificación y materiales visuales para reorganizar y mejorar la estructura curricular académica.

## Estructura del Repositorio

- `README.md` - Descripción general del proyecto con visualización curricular actual vs. objetivo
- `mallaCurricular.md` - Cuadrícula curricular detallada mostrando cursos organizados por semestre con categorías codificadas por colores y tabla completa de equivalencias
- `ASW.md` - Especificación para la nueva asignatura de Arquitectura de Software (renombrado desde AdSw.md)
- `organizarHilo.md` - Documento de planificación para organizar la secuencia de asignaturas de ingeniería de software
- `unificarMDisLog.md` - Propuesta para unificar las asignaturas de Matemática Discreta y Lógica
- `images/` - Recursos visuales incluyendo diagramas curriculares actuales y propuestos
- `modelosUML/` - Modelos UML y diagramas PlantUML para visualización curricular

## Conceptos Clave

### Sistema de Codificación de Colores Curricular Actual

El sistema de colores ha evolucionado para usar un gradiente verde-amarillo que refleja la progresión conceptual:

- 🟡 **#FFFF99 (Conexión)**: Amarillo claro para asignaturas de integración con el entorno empresarial
- 🟢 **#CDDC39 (Desarrollo)**: Verde-amarillo para asignaturas de desarrollo e implementación de sistemas  
- 🟢 **#A5D6A7 (Construcción)**: Verde claro para metodologías y procesos de construcción de software
- 🟢 **#4CAF50 (Ingeniería)**: Verde fuerte para fundamentos científicos y técnicos

### Filosofía de Organización Curricular

El currículo se organiza alrededor de un hilo de ingeniería de software que progresa a través de:

1. **FPSW** (Fundamentos de Proyectos y Software) - 1º curso, 1º semestre
2. **ISW1** (Ingeniería de Software I) - 2º curso, 2º semestre  
3. **ISW2** (Ingeniería de Software II) - 3º curso, 1º semestre
4. **ASW** (Arquitectura de Software) - 3º curso, 2º semestre

### Abreviaciones de Asignaturas

El repositorio usa abreviaciones estandarizadas de asignaturas. Asignaturas clave de ingeniería de software:

- **FPSW**: Fundamentos de Proyectos y Software (anteriormente iGPySw)
- **ISW1**: Ingeniería de Software I (anteriormente IdSw1)
- **ISW2**: Ingeniería de Software II (anteriormente IdSw2)
- **ASW**: Arquitectura de Software (anteriormente AdSw)

Las equivalencias completas de asignaturas se mantienen en `mallaCurricular.md`.

## Notas de Desarrollo

- Todo el contenido está en español y enfocado al diseño curricular académico
- No hay herramientas de construcción, pruebas o comandos tradicionales de desarrollo de software
- El repositorio usa markdown para documentación y PlantUML para diagramas
- Los diagramas PlantUML usan un esquema de colores en gradiente verde con paquetes estilo marco
- Los materiales visuales se referencian a través de rutas relativas al directorio `images/`
- El proyecto rastrea TODOs académicos y el estado de modificación curricular

## Trabajando con Este Repositorio

Al realizar cambios:

- Mantener consistencia en el idioma español a través de todos los documentos
- Seguir el sistema actual de codificación de colores en gradiente verde-amarillo para visualización curricular
- Usar abreviaciones estandarizadas de asignaturas (FPSW, ISW1, ISW2, ASW, etc.)
- Asegurar que los diagramas visuales en los directorios `images/` y `modelosUML/` permanezcan sincronizados con las descripciones textuales
- Preservar el formato académico y la estructura de los documentos curriculares
- Actualizar tanto las tablas markdown como los diagramas PlantUML al realizar cambios curriculares

## Notas Específicas de PlantUML

- Los paquetes de curso tienen colores de fondo verde graduados por año académico
- Los paquetes de semestre no tienen color de fondo para evitar conflictos visuales
- La progresión de color sigue la jerarquía conceptual desde conexión hasta fundamentos de ingeniería