# Diario De Proyecto

## Día 1 - 29 de mayo de 2026

Hoy inicié Travel Brief SEA, una app simple de IA para generar briefs iniciales de viaje al Sudeste Asiático.

Decidí empezar con un MVP chico para evitar construir una app demasiado compleja desde el principio.

## Decisiones

- El proyecto comenzará con 3 países: Tailandia, Vietnam e Indonesia
- No incluirá login en la primera versión
- No incluirá mapas en la primera versión
- Primero usaré resultados simples o mockeados
- Luego agregaré IA real con DeepSeek, Kimi o Dify

## Aprendizaje del día

Un proyecto de IA no necesita empezar siendo complejo. Si el input es claro y la salida es útil, ya puede tener valor.

## Próximo paso
Crear la primera interfaz en Lovable.

## Dia 2 - Prototipo visual

Hoy cree la primera version visual de Travel Brief SEA en Lovable.

El objetivo fue tener una pantalla usable con un formulario para generar un brief de viaje al Sudeste Asiatico.

### Avances

- Cree el proyecto en Lovable.
- Cambie el titulo visible a Travel Brief SEA.
- Traduje la interfaz principal al espanol.
- Agregue campos para pais, duracion, mes, presupuesto y estilo de viajero.
- Genere una primera pantalla de resultado con informacion de prueba.
- Revise que la app se entienda como herramienta y no como landing page.

### Aprendizaje Del Dia

Antes de conectar una IA real, conviene validar que la interfaz sea clara y que el resultado esperado tenga sentido para el usuario.

### Proximo Paso

Disenar y probar el prompt principal que generara los briefs de viaje.



Crear la primera interfaz en Lovable.

## Dia 3 - Prompt principal de IA

Hoy disene y probe el primer prompt principal de IA para Travel Brief SEA.

Use Kimi para probar tres casos:
- Tailandia, 14 dias, julio, presupuesto medio, primera vez.
- Vietnam, 14 dias, marzo, presupuesto bajo, mochilero.
- Indonesia, 21 dias, mayo, presupuesto alto, pareja.

### Avances

- Cree el archivo PROMPTS.md.
- Defini el prompt principal en espanol.
- Agregue reglas para evitar informacion sensible inventada.
- Probe tres casos de viaje con Kimi.
- Detecte que las respuestas son utiles, pero algo extensas para un MVP.
- Cree una version 0.2 mas breve para usar en la app.

### Aprendizaje Del Dia

El prompt no solo debe pedir una respuesta correcta. Tambien debe controlar longitud, estructura, riesgos y utilidad para el usuario.

### Proximo Paso

Elegir si la primera integracion real sera con DeepSeek, Kimi, Dify o respuestas mockeadas.
## Testing inicial

### Test 4 - Validacion de formulario

Resultado:

- La app no permite generar el brief si faltan campos.
- El boton "Generar brief" queda desactivado correctamente.
- No aparece un mensaje especifico indicando que se deben completar todos los campos.
- En la parte baja del formulario aparece la leyenda: "Resultados de prueba, sin IA real todavia."

Evaluacion:

- Funcionalidad aprobada.
- Mejora pendiente de UX: agregar un texto de ayuda cuando el formulario este incompleto.

## Dia 4 - Testing y mejoras de generacion mock

Hoy continue probando Travel Brief SEA como usuario final.

El objetivo fue revisar si el prototipo funciona correctamente antes de conectar una API real de IA.

### Avances

- Probe el formulario con distintos paises, duraciones, meses, presupuestos y estilos de viajero.
- Verifique que el boton "Generar brief" permanece desactivado cuando faltan campos.
- Detecte que la app no muestra un mensaje especifico cuando el formulario esta incompleto.
- Revise que la leyenda "Resultados de prueba, sin IA real todavia" aparece correctamente.
- Decidi mantener la generacion mock antes de conectar una API real.

### Testing realizado

#### Validacion del formulario

Resultado:

- La app no permite generar el brief si faltan campos.
- El boton "Generar brief" queda desactivado correctamente.
- No aparece un mensaje especifico indicando que se deben completar todos los campos.

Evaluacion:

- Funcionalidad aprobada.
- Mejora pendiente de UX: agregar un texto de ayuda cuando el formulario este incompleto.

### Aprendizaje del dia

Antes de conectar una IA real, conviene validar que el flujo principal funcione bien con datos de prueba. Una app de IA necesita buena experiencia de usuario, no solo buenas respuestas del modelo.

### Proximo paso

Agregar una mejora pequena de UX para avisar al usuario que debe completar todos los campos antes de generar el brief.


