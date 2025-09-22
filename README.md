# Docs Proyecto Curso

Micrositio de documentación y notas técnicas versionadas para el proyecto del curso.

## Descripción

Este repositorio contiene la documentación técnica del proyecto, organizada de manera estructurada y bajo control de configuración utilizando Git Flow y versionado semántico (SemVer).

## Estructura del proyecto

```
/
├── README.md
├── CHANGELOG.md
├── RELEASE_NOTES.md
├── docs/
│   ├── README.md
│   └── CONTRIBUTING.md
└── .github/
    └── pull_request_template.md
```

## Cómo contribuir

Para contribuir a este proyecto, sigue estos pasos:

1. **Fork** el repositorio
2. Crea una **rama** para tu feature: `git checkout -b feat/nueva-funcionalidad-#issue`
3. **Commit** tus cambios referenciando el issue: `git commit -m "feat: descripción #issue"`
4. **Push** a tu rama: `git push origin feat/nueva-funcionalidad-#issue`
5. Abre un **Pull Request** usando la plantilla proporcionada

### Convención de commits

- `feat:` para nuevas funcionalidades
- `fix:` para corrección de errores  
- `docs:` para cambios en documentación
- `chore:` para tareas de mantenimiento

Para más detalles, consulta [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md)

## Versiones

| Versión | Fecha      | Descripción | Notas |
|---------|------------|-------------|-------|
| v1.1.0  | 2025-09-21 | Guía de contribución y mejoras en documentación | Agregada guía de contribución |
| v1.0.0  | 2025-09-21 | Línea base inicial del proyecto | Primera versión estable |

## Licencia

Este proyecto es de uso académico para el curso de Gestión de Configuración de Software.