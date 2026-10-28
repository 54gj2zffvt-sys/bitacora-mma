# Pendiente: rediseño de la bitácora (esperando sistema de diseño compartido)

Estado: **LISTO PARA CONSTRUIR — esperando aprobación de los bocetos**.
`~/nutriologo-mma/sistema-de-diseno.md` ya existe y está completo (incluye
los tokens de RONDA: --session-striking #0093E7, --session-grappling
#7BA1BB). Bocetos de Hoy/modo entrenamiento/temporizador ya mostrados:
https://claude.ai/artifact/MyhCtoqVR3sFw9e584rV9Q
No tocar el código real de la bitácora hasta que el usuario apruebe esos
bocetos.

## Uso personal (aplica siempre, no es solo visual)
- Sin registro de usuarios, planes de pago, suscripciones, anuncios,
  tutoriales de onboarding ni panel de administración.
- No diseñar para escalar a muchos usuarios.
- Acceso simple: elegir "Martín" o "Mamá" al abrir, con PIN simple si
  hace falta — nada más.
- Prioridad: rápida, fácil, bonita, funciona bien en los dos iPhone.
- Si algo resulta complicado o innecesario para dos personas, avisar y
  proponer versión más simple en vez de construirlo igual.

## Sistema de diseño compartido
Debe verse de la misma familia visual que la app de nutrición de Martín:
misma paleta, tipografía, tarjetas, botones, anillos de progreso, íconos
y animaciones — tomado literalmente de `sistema-de-diseno.md` cuando
exista, no inventado aparte. Si hace falta algo que ese archivo no define
(ej. el temporizador), crearlo siguiendo las mismas reglas y agregarlo
a ese archivo (no a uno aparte).

## Diseño especializado para entrenamiento (inspirado sin copiar marca)
Referencias: Whoop, Apple Fitness, Strong, Hevy, Nike Training Club.

- Anillo de progreso del entrenamiento del día en "Hoy", junto a un
  indicador de recuperación.
- Color fijo por tipo de sesión (striking, grappling/BJJ, fuerza,
  cardio, descanso) — sacado de la misma paleta compartida.
- "Modo entrenamiento": botones grandes, números enormes, temporizadores
  muy visibles — pensado para usarse con una mano y sudando.
- Temporizador de rounds a pantalla completa, colores que cambian entre
  trabajo y descanso.
- Videos de ejercicio integrados en las tarjetas (ya existe la base:
  modal de YouTube por ejercicio).
- Gráficas de récords/progreso con el mismo estilo que los reportes de
  la app de nutrición.
- Tono enérgico y motivador.

## Antes de programar cualquiera de esto
Mostrar bocetos de "Hoy", modo entrenamiento y temporizador de rounds,
confirmar que usan el sistema de diseño compartido, y esperar aprobación
explícita. No construir nada de esto sin ese visto bueno.
