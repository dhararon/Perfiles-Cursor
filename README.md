# Perfiles de Configuración de Cursor

## 🎯 Misión General
PDT Grading es una empresa mexicana especializada en la calificación de cartas coleccionables, enfocada en ofrecer un servicio confiable y preciso mediante el uso eficiente de la tecnología.

## 👥 Perfiles de Equipo

### Frontend Designer
- **Responsabilidad**: Diseñar interfaces limpias, usables y escalables
- **Enfoque**: 
  - Crear y mantener un design system coherente
  - Garantizar experiencias de usuario rápidas y accesibles
  - Definir lógica de interacción en flujos complejos
- **Herramientas**: Figma, Tokens de diseño, Storybook, Zeplin
- **Stack**: TailwindCSS, Radix UI, shadcn/ui

### Frontend Developer
- **Responsabilidad**: Desarrollar interfaces eficientes y mantenibles
- **Enfoque**:
  - Implementar componentes complejos en React
  - Optimizar performance y experiencia de usuario
  - Integrar APIs de forma robusta
- **Stack**: React/Next.js, TailwindCSS, shadcn/ui
- **Testing**: Jest, Playwright, Testing Library

## 📋 Convenciones de Desarrollo

### Control de Versiones
- **Commits**: Seguir formato Conventional Commits
- **Tipos**: feat, fix, docs, style, refactor, perf, test, chore, ci, revert
- **Versionado**: Semantic Versioning (MAJOR.MINOR.PATCH)

### Estilo de Código
- **Documentación**: Docstrings completos para módulos y funciones
- **Nombrado**: 
  - Variables/funciones: `snake_case`
  - Clases: `PascalCase`
  - Constantes: `UPPER_SNAKE_CASE`
- **Testing**: Coverage mínimo del 80%

### CI/CD
- **Pipelines**: Lint → Tests → Build → Deploy
- **Ambientes**: development, staging, production
- **Branches**: main, develop, feature/*, fix/*, release/*

### Seguridad
- No commitear secretos
- Pull Requests obligatorios
- Mínimo 1 aprobación requerida
- CI debe pasar antes de merge

### Monitoreo
- Logs: ERROR, WARN, INFO, DEBUG
- Métricas: Tiempo de respuesta, uso de recursos, tasa de errores
- Performance: Perfilado y benchmarks documentados

### Documentación
- README completo con descripción, requisitos, instalación, uso
- APIs documentadas con OpenAPI/Swagger
- Gestión de dependencias con versiones exactas 