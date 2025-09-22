# Guía de Contribución

Esta guía describe cómo contribuir al proyecto de documentación del curso.

## Flujo de trabajo

### 1. Preparación
- Fork el repositorio principal
- Clona tu fork localmente: `git clone https://github.com/tu-usuario/docs-proyecto-curso.git`
- Configura el remoto upstream: `git remote add upstream https://github.com/usuario-original/docs-proyecto-curso.git`

### 2. Desarrollo
1. **Sincroniza** tu fork con upstream:
   ```bash
   git checkout main
   git pull upstream main
   git push origin main
   ```

2. **Crea un issue** describiendo el cambio propuesto (si no existe)

3. **Crea una rama** desde main:
   ```bash
   git checkout -b feat/nombre-descriptivo-#numero-issue
   ```

4. **Desarrolla** tus cambios siguiendo las convenciones del proyecto

5. **Commit** con mensajes descriptivos:
   ```bash
   git commit -m "feat(docs): agregar sección de instalación #123"
   ```

### 3. Pull Request
1. **Push** tu rama: `git push origin feat/nombre-descriptivo-#numero-issue`
2. **Abre un PR** en GitHub usando la plantilla
3. **Completa** el checklist del PR
4. **Responde** a comentarios de revisión si es necesario

## Convenciones

### Mensajes de Commit
Sigue el formato: `tipo(scope): descripción #issue`

**Tipos:**
- `feat`: nueva funcionalidad
- `fix`: corrección de bug
- `docs`: cambios en documentación
- `style`: formateo, espacios en blanco
- `refactor`: refactorización de código
- `test`: agregar/modificar tests
- `chore`: tareas de mantenimiento

### Nombres de Ramas
- `feat/descripcion-#issue` para nuevas funcionalidades
- `fix/descripcion-#issue` para correcciones
- `docs/descripcion-#issue` para documentación
- `chore/descripcion-#issue` para mantenimiento

### Estructura de Archivos
- Usa Markdown (.md) para documentación
- Mantén líneas de máximo 80 caracteres cuando sea posible
- Usa títulos jerárquicos (##, ###, etc.)
- Incluye tabla de contenidos en documentos largos

## Proceso de Revisión

1. **Revisor asignado** evaluará el PR
2. **Cambios solicitados** deben ser atendidos antes del merge
3. **Merge** se realiza usando "Squash and merge" para mantener historial limpio
4. **Tag de versión** se crea después del merge (por mantenedores)

## Versionado

Este proyecto usa [Semantic Versioning](https://semver.org/):
- **MAJOR.MINOR.PATCH**
- **MAJOR**: cambios incompatibles
- **MINOR**: nueva funcionalidad compatible
- **PATCH**: correcciones compatibles

## Contacto

Para dudas sobre contribuciones, abre un issue con la etiqueta `question`.