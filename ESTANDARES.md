# Estándares de Reserva Fácil

## Estándares iniciales

- Identificar los cambios de producto con `HU-XX` al inicio del mensaje de commit.
- Mantener una historia lista para tomar cuando tenga objetivo, criterios comprobables, prioridad, estimación y dependencias identificadas.
- Cerrar una historia tras ejecutar los casos aplicables, verificar el flujo en navegador, registrar el resultado y asociar el commit correspondiente.
- Usar fechas en formato ISO para el almacenamiento y fechas de entrada y salida que permitan una nueva entrada el mismo día de una salida.
- Mantener separadas la base de demostración y los datos de aplicación. El repositorio incluye solo nombres ficticios de prueba.
- Registrar movimientos e hitos en la zona horaria de Bogotá y conservar el registro original de los ciclos.

## Límites de trabajo

El ciclo 1 admite hasta dos historias abiertas en paralelo. Las retrospectivas pueden cambiar este límite mediante un registro fechado y el historial del tablero.

## Ajustes después del sprint 1

- CC-01 y M1. Mantener como máximo una historia en En progreso desde el sprint 2.
- CC-01 y M2. Antes de cerrar una historia del sprint 2, guardar la salida de su prueba específica y adjuntarla al commit de la historia.
- Si falla el arranque del navegador del entorno, consignar el bloqueo, verificar por HTTP los recursos y registrar la comprobación visual entre las validaciones pendientes.
