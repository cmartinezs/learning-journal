# Plan de conciliación — aprendizaje personal y ADÜMÜN

> Decisión: **Learning Journal es una bitácora personal de estudio y progreso, no una aplicación ni un nuevo producto educativo.**

## 1. Propósito y límites

Este repositorio registra qué quiero aprender, qué estudié, qué entendí, mis dudas y evidencia de mi progreso. No implementa motor de competencias, gestores de cápsulas, UX de aprendizaje ni sincronizaciones con otros repositorios.

No usar issues como tareas de estudio, ni sprints, PRs obligatorias, CI/CD, métricas de commits, workflows automáticos ni pipelines de progreso.

## 2. Autoridades existentes (no duplicar)

| Fuente | Qué gobierna | Relación con mi bitácora |
| --- | --- | --- |
| [ADÜMÜN / competency-engine](https://github.com/adumun/competency-engine) | Semántica genérica de competencias, dependencias, evidencia, dominio y progresión | Inspira las preguntas y criterios; no se importa el modelo ni se proclama dominio formal del motor |
| [ADÜMÜN / learning-roadmaps](https://github.com/adumun/learning-roadmaps) | Producto educativo: cápsulas, práctica, evaluación y experiencia del alumno | Referencia metodológica; no se copia software ni contenido de producto |
| [ADÜMÜN / generative-art-learning-roadmap](https://github.com/adumun/generative-art-learning-roadmap) | Currículo y cápsulas de arte generativo, con Learn → Practice → Build y prerrequisitos suaves | Fuente consultable para mis estudios artísticos, sin replicar su currículo |
| [Learning Journal](../README.md) | Apuntes personales, objetivos, preguntas, autoevaluaciones y enlaces a evidencias | Única fuente de verdad de mi progreso personal |
| [Drive de seguimiento](https://drive.google.com/drive/folders/1lvZHqelwNjDQdHaAVoMJytPC0vtyN9Rm) | Material privado, archivos de apoyo o vistas personales complementarias | No mantener aquí un segundo estado manual que contradiga STATUS.md |

Los repositorios ADÜMÜN conservan sus propias autoridades y sus diferentes etapas de implementación. Ninguna integración de software se presupone.

## 3. Modelo liviano de aprendizaje

- **Ruta:** dirección o interés amplio. No equivale a curso ni a compromiso.
- **Objetivo/competencia personal:** capacidad verificable que quiero desarrollar, expresada en lenguaje natural.
- **Cápsula:** una unidad pequeña que puedo recorrer con una pregunta, una explicación, una práctica y una reflexión. Puede proceder de Udemy, libros, papers, repositorios o experiencia.
- **Prerrequisitos:** preguntas orientativas que ayudan a escoger qué repasar, sin bloquear artificialmente el avance. Distinguir imprescindible, útil y complementario en las notas cuando haga falta.
- **Evidencia:** explicación autónoma, ejercicio razonado, caso nuevo, esquema, crítica, análisis o un experimento breve.
- **Autovaloración 0–4:** aproximación personal para orientar el estudio, **no** una decisión certificada del Competency Engine.

No crear un catálogo exhaustivo de cápsulas antes de estudiar. Crear notas únicamente cuando se utilizan.

## 4. Responsabilidades de los soportes

**GitHub / Learning Journal**
- `routes/catalog.md`: intereses y estados orientativos de rutas.
- `STATUS.md`: situación vigente, próxima pregunta y enlaces al trabajo reciente.
- `areas/`: preguntas y diagnósticos por tema.
- `notes/`: notas fechadas cuando existan aprendizajes reales.
- `templates/`: plantillas opcionales, nunca formularios obligatorios.
- `docs/learning-conciliation-plan.md`: este acuerdo.

**Drive**
- archivos privados o complementarios que no convenga publicar;
- materiales propios de apoyo difíciles de mantener en Markdown;
- enlaces a recursos, si su formato aporta algo;
- no duplicar los niveles y estados de `STATUS.md`.

**Udemy Business y otras fuentes**
- proporcionan contenido. No determinan por sí mismas dominio, ruta ni ritmo;
- verificar el acceso de cada curso en la cuenta institucional y respetar propiedad intelectual.

## 5. Conciliación incremental

### Fase 0 — preservar lo existente (hecho)
Identificar y enlazar los tres repositorios de referencia. No tocar su código, sus contratos ni sus estados; mantener el catálogo de rutas personales.

### Fase 1 — contrato editorial y estado único (realizada)
Dejar este plan y un `STATUS.md` legibles; enlazar ambos desde el README. Conservar plantillas y rutas actuales. No migrar a software ni automatizar.

### Fase 2 — primera experiencia de aprendizaje (pendiente)
- Elegir una pregunta pequeña de AI Engineering.
- Realizar diagnóstico desde memoria.
- Seleccionar solo el material preciso de Udemy u otra fuente.
- Escribir una nota con idea, ejemplo, dificultad, evidencia y siguiente pregunta.
- Actualizar `STATUS.md` con resultado real. No inventar aprendizaje completado.

### Fase 3 — revisión de utilidad (tras 2–4 semanas de uso)
Comprobar si las notas ayudan a recordar y explicar, si los prerrequisitos ahorran tiempo y si Drive está aportando valor adicional. Eliminar campos o pasos molestos. Solo después estudiar opciones de integración, **sin compromiso de construirlas**.

## 6. Criterios de éxito

1. Encuentro en menos de dos minutos el estado y la próxima pregunta.
2. Puedo explicar al menos una idea sin consultar el curso.
3. Tengo evidencia breve y honesta de mis cambios de comprensión.
4. Puedo pasar de una ruta a otra sin rehacer apuntes compartidos.
5. El mantenimiento de la bitácora ocupa menos tiempo que estudiar.

**Antipatrones:** duplicación entre Drive/GitHub, medir estudio con indicadores de software, convertir prerequisitos en puertas absolutas, inventar una ontología de competencias, documentar más de lo aprendido.
