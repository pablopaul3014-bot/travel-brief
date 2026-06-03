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
