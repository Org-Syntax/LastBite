# PULL_REQUEST_TEMPLATE.md

## Descripción
<!-- Describe brevemente qué hace este Pull Request y el propósito de los cambios. -->
[Descripción clara de la funcionalidad agregada, error solucionado o ajuste realizado]

## Historia de Usuario / Tarea Relacionada
<!-- Referencia la Historia de Usuario (ej. HU-01, HU-02) o la tarea de la Guía de Aprendizaje. -->
- **HU/Tarea:** [Ej: HU-02 Publicación de Paquete Excedente]

## Tipo de Cambio
<!-- Marca con una [x] las opciones que correspondan a este PR -->
- [ ] ✨ Nueva característica (Feature - ej. nuevo endpoint o vista)
- [ ] 🐛 Corrección de error (Bugfix)
- [ ] ♻️ Refactorización de código (Mejora estructural sin añadir funcionalidad)
- [ ] 📝 Actualización de documentación (Markdown, esquemas BD)
- [ ] 🎨 Ajustes de diseño / UI responsivo

## Lista de Verificación (Definition of Done)
<!-- Revisa que tu PR cumpla con los siguientes puntos antes de solicitar revisión -->
- [ ] Mi código sigue los estándares y nomenclatura del proyecto LastBite.
- [ ] He probado estos cambios localmente y cumplen con los Criterios de Aceptación de la HU.
- [ ] No estoy incluyendo credenciales, tokens, ni archivos no deseados (ej. `.env`, `node_modules`, `__pycache__`).
- [ ] Si hay cambios en la base de datos, he incluido los scripts SQL o de colecciones actualizados.

## Evidencia Visual (Obligatorio para cambios en UI)
<!-- Si este PR modifica la interfaz (Catálogo, Registro, Tarjetas), añade capturas de pantalla. -->
| Vista Móvil | Vista Escritorio |
| --- | --- |
| [Arrastra tu imagen aquí] | [Arrastra tu imagen aquí] |

## Pasos para Probar (Reviewer)
<!-- Instrucciones específicas para que tu compañero o instructor pruebe el código. -->
1. Hacer checkout a esta rama: `git checkout nombre-de-la-rama`
2. [Ej: Ejecutar el script de base de datos para cargar las nuevas categorías]
3. [Ej: Iniciar sesión con el usuario de prueba comercio@lastbite.com]
4. Verificar que [acción específica] funciona correctamente.