# Caso de Uso: Establecer Metas Nutricionales.
## Objetivo
- El nutricionista debe poder establecer y gestionar metas nutricionales personalizadas para cada paciente a través del sistema basado en la nube.

## Actores
- Nutricionista (Usuario Principal)
- Almacenamiento en la Nube

## Flujo Principal de Eventos
- El nutricionista inicia sesión en el software de cálculo nutricional en la nube.
- Selecciona la opción "Establecer Metas Nutricionales" del menú principal.
- Elige un paciente específico para quien quiere establecer metas nutricionales.
- El sistema recupera los datos nutricionales actuales y el historial del paciente desde la nube.
- El nutricionista establece metas nutricionales personalizadas para el paciente, como la ingesta calórica diaria, la distribución de macronutrientes y el peso objetivo.
- El sistema guarda de forma segura las metas recién establecidas en la nube, asociándolas con el paciente seleccionado.

## Flujos Alternativos de Eventos
- Si el nutricionista intenta establecer metas poco realistas, el sistema proporciona una advertencia y sugiere objetivos más alcanzables.
- Si hay un problema al guardar las metas nutricionales, el sistema informa al nutricionista y recomienda reintentar o verificar la conexión a internet.

## Precondiciones
- El nutricionista tiene acceso a una conexión a internet.
- El software de cálculo nutricional está funcionando correctamente.

## Postcondiciones
- El nutricionista establece con éxito metas nutricionales personalizadas para el paciente seleccionado, almacenadas de forma segura en la nube.