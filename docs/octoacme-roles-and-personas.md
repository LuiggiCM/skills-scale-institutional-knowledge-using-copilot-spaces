# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Perfiles adicionales recomendados

Para mejorar la claridad, responsabilidad y coordinación entre equipos, se recomiendan los siguientes perfiles adicionales. Añadirlos al documento principal ayuda a asignar responsabilidades explícitas en proyectos transversales.

1) Technical Lead (Líder Técnico)
- Resumen: Responsable de las decisiones de arquitectura y dirección técnica del proyecto.
- Responsabilidades:
  - Diseñar y validar la arquitectura técnica.
  - Revisar y aprobar propuestas técnicas y decisiones de dependencia.
  - Asegurar la calidad técnica y guía de implementación.
- Interacción con roles existentes:
  - Colabora con Developers para soluciones técnicas.
  - Coordina con PM/PdM para priorización técnica y con QA para criterios de pruebas.
  - Escala preguntas a Security cuando aplique.

2) Delivery Manager (Responsable de Entrega)
- Resumen: Enfocado en la coordinación operativa para cumplir hitos y entregas.
- Responsabilidades:
  - Seguimiento de hitos y roadmap de lanzamiento.
  - Gestión de impedimentos operativos y coordinación de despliegues.
  - Supervisión del soporte post-lanzamiento y handover.
- Interacción con roles existentes:
  - Trabaja con PM para plan y riesgos; informa a Product Lead.
  - Coordina con Developers, QA y DevOps para checkpoints de entrega.

3) UX / Research Liaison (Enlace UX/Investigación)
- Resumen: Enlaza la investigación y el diseño con el backlog y criterios de aceptación.
- Responsabilidades:
  - Coordinar pruebas de usabilidad y sintetizar hallazgos.
  - Traducir insights de usuarios en criterios de aceptación y prioridades.
  - Validar decisiones de UX antes de implementación.
- Interacción con roles existentes:
  - Colabora con PdM en priorización y con Developers en implementaciones que preserven la experiencia de usuario.

4) Security Champion (Campeón de Seguridad)
- Resumen: Referente de seguridad dentro del equipo de producto.
- Responsabilidades:
  - Revisar historias y requisitos por riesgos de seguridad.
  - Proponer mitigaciones y coordinar escaneos/patches.
  - Mantener prácticas de seguridad en el pipeline (CI/CD).
- Interacción con roles existentes:
  - Trabaja con Developers, DevOps/CI y el equipo de Seguridad cuando sea necesario.

5) Data / Analytics Owner (Responsable de Datos)
- Resumen: Define y mantiene la instrumentación y métricas del proyecto.
- Responsabilidades:
  - Definir métricas de éxito y requisitos de instrumentación.
  - Validar la calidad de los datos y crear dashboards relevantes.
  - Apoyar análisis post-lanzamiento y experimentación.
- Interacción con roles existentes:
  - Colabora con PdM para métricas de producto y Developers para la instrumentación técnica.

6) Stakeholder Representative (Representante de Stakeholders)
- Resumen: Punto de contacto y validación para áreas afectadas fuera del equipo.
- Responsabilidades:
  - Validar impactos de negocio y requisitos no funcionales.
  - Representar intereses de negocio, soporte o ventas en decisiones clave.
  - Coordinar aprobaciones con Sponsor si aplica.
- Interacción con roles existentes:
  - Participa en revisiones clave y priorización; apoya la comunicación hacia su área.

Cómo mejorará los resultados:
- Claridad en rendición de cuentas y eliminación de ambigüedades en decisiones clave.
- Menos cuellos de botella al saber quién es responsable por seguridad, datos, UX o despliegue.
- Integración temprana de aspectos de calidad (UX, Security, Data) mejora el resultado final.
- Métricas mejor alineadas con decisiones de producto, facilitando iteración basada en evidencia.

Sugerencia de ubicación:
- Añadir esta sección "Perfiles adicionales recomendados" en la parte inferior del documento y enlazarla desde el índice del repo (README o Project One-pager) para visibilidad.
