# Skill — Generador de imágenes de campaña (estilo documental/testimonial) para ChatGPT

**Para qué sirve:** generar o editar imágenes de una serie de campaña de fundraising/dawah a partir de fotos reales del terreno, manteniendo un estilo documental, cálido y testimonial (no corporativo), sin inventar elementos ni alterar rostros.

**Hecha para:** ChatGPT con generación/edición de imágenes (gpt-image). **No genera video.** Si el plan original pedía video con movimiento de cámara (push-in, pan, tilt — estilo Higgsfield), esta skill NO lo reproduce: ChatGPT solo entrega imágenes fijas. Si necesitas video, usa una herramienta de imagen-a-video (Higgsfield, Runway, Kling, etc.) con la imagen que generes aquí como punto de partida.

---

## Cómo usar esta skill en ChatGPT

**Opción A — GPT personalizado:** pega el contenido de este archivo en el campo "Instrucciones" de un GPT personalizado. Así queda disponible cada vez que lo abras.

**Opción B — Proyecto de ChatGPT:** sube este archivo como "archivo de conocimiento" de un Proyecto. Ábrelo cada vez que trabajes en la campaña.

**Opción C — Conversación suelta:** pega este archivo completo como primer mensaje de la conversación, antes de adjuntar ninguna foto.

Luego, para cada pieza:
1. Adjunta la foto real que quieres usar como base (si la tienes). Si no hay foto, dilo y se genera desde cero con la descripción.
2. Pega el prompt correspondiente de la plantilla de abajo, reemplazando los placeholders.
3. Pide el resultado en el formato pedido (por defecto, vertical 4:5 para Instagram).
4. Revisa el resultado contra las reglas de la sección "Qué no debe pasar" antes de aprobarlo.

---

## Reglas de estilo (aplican a TODAS las piezas)

- Tono documental y testimonial: parece una foto real de campo, no una pieza publicitaria genérica.
- Grado de color cálido, luz natural (tarde/dorada cuando la escena original la tenga).
- Si hay una foto de referencia con personas reales: **no alterar rostros, no inventar personas, no agregar ni quitar gente**. Pide edición/mejora de luz y encuadre, no recreación.
- Si la escena tiene elementos de fondo que no corresponden al tema de la pieza (p. ej. señalética, carteles o paneles de otro contexto/confesión que no se quieren mostrar), decide ANTES de generar si se recortan, se difuminan (blur) o se dejan visibles — y dilo explícitamente en el prompt.
- Sin texto superpuesto generado por la IA salvo que lo pidas aparte (el copy del post se maneja por separado, no dentro de la imagen).
- Formato por defecto: vertical 4:5. Ajusta solo si la pieza es para otro canal (historia 9:16, feed cuadrado 1:1).

## Qué no debe pasar

- No inventar cifras, logos, marcas o links dentro de la imagen.
- No usar menores de edad reconocibles sin confirmación explícita de que hay autorización para publicarlos.
- No generar escenas que sugieran proselitismo agresivo o comparación negativa con otras creencias: el tono es informativo y de servicio, nunca de confrontación.
- No reemplazar una foto real por una genérica de banco de imágenes si el objetivo es mostrar evidencia real de la campaña.

---

## Plantilla de prompt reutilizable

```
Edita/genera esta imagen para una pieza de campaña de fundraising/dawah, serie documental.

Escena: [DESCRIBE QUÉ SE VE: lugar, acción, personas — sin inventar lo que no está en la foto]
Encuadre: [close-up / plano medio / plano general]
Luz y color: [cálido tarde dorada / neutro interior / natural exterior]
Fondo: [deja visible / recorta — especifica qué] 
Formato de salida: [vertical 4:5 / 9:16 / 1:1]
Restricciones: preservar rostros reales sin alterar, no agregar texto, no agregar personas u objetos que no estén en la foto original, mantener aspecto documental (no publicitario).
```

## Los 15 prompts de la serie (adaptados a imagen fija, sin movimiento de cámara)

Reemplaza `[FOTO]` por el nombre de tu archivo real al subirlo en ChatGPT.

1. `[FOTO: grupo de equipo antes de salir]` — Plano general del equipo preparándose en el aula, luz cálida de tarde, look documental, vertical 4:5.
2. `[FOTO: folletos en mano]` — Close-up a los folletos en la mano, profundidad de campo poco (fondo desenfocado), luz natural de día, mantener el texto del folleto legible, vertical 4:5.
3. `[FOTO: aula/salón]` — Plano general del salón, corrección de color neutra interior, sin agregar elementos, 4:5.
4. `[FOTO: grupo en mesa, interior]` — Plano medio del grupo, luz cálida interior, preservar la composición original, 4:5.
5. `[FOTO: fila de oración]` — Plano medio-alto siguiendo la fila de oración, tonos cálidos atenuados, vertical 4:5.
6. `[FOTO: grupo en mesa, exterior]` — Plano medio del grupo en la mesa, luz natural exterior, 4:5.
7. `[FOTO: salón de mujeres, momento de enseñanza]` — Plano medio del momento de enseñanza, **decidir antes de generar si se recorta o difumina el fondo**, luz cálida, 4:5.
8. `[FOTO: escena de ángulo bajo]` — Plano de ángulo bajo, luz de última hora del día, 4:5.
9. `[FOTO: interior de bus/transporte]` — Plano medio dentro del vehículo, grado de luz interior, 4:5.
10. `[FOTO: conversación en banca]` — Plano medio de la conversación en la banca, luz dorada de atardecer, 4:5.
11. `[FOTO: voluntario, retrato]` — Plano medio del voluntario, luz interior neutra, 4:5.
12. `[FOTO: escena exterior, atardecer]` — Plano general, grado de color de atardecer, 4:5.
13. `[FOTO: tres personas en plaza]` — Plano general revelando a las tres figuras, luz cálida de plaza, 4:5.
14. `[FOTO: mano y rostro, close-up]` — Close-up con foco en la mano pasando a rostro, luz natural de día, 4:5.
15. `[FOTO: caligrafía/escritura a mano]` — Macro/close-up sobre la escritura a mano, grado de color cálido suave, 4:5.

---

## Nota de confidencialidad

Este archivo es genérico y no contiene fotos reales, links de donación ni datos de personas. Las fotos originales, el link de donación real y los nombres de archivo exactos de cada campaña **no se suben a este repositorio** — se usan solo dentro de la conversación de ChatGPT, de forma local a cada sesión.
