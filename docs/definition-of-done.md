# Definition of Done (DoD) - Criterios de Finalización (LastBite)

Una Historia de Usuario o Tarea se considera **Terminada (Done)** en el Sprint solo cuando cumple con la siguiente lista de verificación:

---

## 1. Código y Calidad
- [ ] El código cumple con las convenciones de estilo del lenguaje utilizado (PEP8 en Python, Standard JS, etc.).
- [ ] No existen variables no utilizadas, bloques de código comentado ni credenciales/claves expuestas directamente en el código base (uso de `.env`).
- [ ] El código fue integrado en la rama principal (`develop` o `main`) mediante un Pull Request o Merge revisado.

## 2. Funcionalidad y Pruebas
- [ ] Todos los criterios de aceptación especificados en la Historia de Usuario han sido probados y validados.
- [ ] Se probó el flujo completo manualmente en navegadores de escritorio y dispositivos móviles (o emulador responsivo).
- [ ] El control de errores gestiona situaciones excepcionales (ej. intentar reservar un producto con stock 0).

## 3. Base de Datos y Persistencia
- [ ] Las migraciones o scripts de creación de tablas/colecciones se encuentran actualizados en el repositorio.
- [ ] Los datos de prueba (seeders) están disponibles para probar la app en un entorno limpio.

## 4. Documentación
- [ ] Los endpoints creados o modificados cuentan con un ejemplo de consumo o documentación breve en el `README.md`.
- [ ] Los archivos `.md` del Sprint están sincronizados con la versión final del sistema.

## 5. Despliegue Local / Demostración
- [ ] La aplicación se puede ejecutar en un entorno local siguiendo los pasos detallados del instalador o guía en el `README.md`.
- [ ] La funcionalidad está lista para ser presentada en la sesión de revisión/demostración del Sprint.