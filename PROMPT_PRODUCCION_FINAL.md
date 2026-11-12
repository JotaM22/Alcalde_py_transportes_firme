# Producción final del proyecto de tesis — instrucciones integradas v8

Este archivo complementa `AGENTS.md` y no sustituye al `Prompt_Maestro_Unificado_Redaccion_Academica.md` aportado por el investigador.

## Encargo operativo

A partir del borrador completo y sus fuentes, **producir el proyecto de tesis redactado y compilable en LaTeX**, utilizando esta plantilla y sus comandos semánticos. No limitarse a convertir texto ni detenerse en un diagnóstico. Preservar decisiones metodológicas, cifras y fuentes; no atribuir respaldo no leído.

### Antes de escribir

- Identificar realidad, objeto, problema, objetivos, hipótesis cuando procedan, variables/dimensiones/indicadores, diseño, población y muestra, instrumentos, análisis, plazo, recursos y presupuesto.
- Revisar congruencia de la cadena metodológica sin imponer causalidad ni hipótesis a objetivos descriptivos.
- Separar correcciones editoriales justificables de decisiones sustantivas que requieren respuesta del investigador: estas últimas **solo al chat**.
- Para cada párrafo: definir su función, idea principal, fundamento y relación entre sus elementos. Integrar ideas dependientes, evitando yuxtaposiciones y conectores automáticos.

### Auditoría del asesor riguroso — preguntas obligatorias

1. ¿De qué?
2. ¿De quién?
3. ¿Cuáles?
4. ¿Qué significa eso?
5. ¿Dónde está demostrado?
6. ¿De dónde obtuvo esa afirmación?
7. ¿De dónde sale esa fórmula?
8. ¿Cómo sustenta ese resultado?
9. ¿Por qué repite al autor?
10. ¿Por qué vuelve a decir lo mismo?
11. ¿Dónde está ese dato?
12. ¿Cómo calculó ese valor?
13. ¿Qué procedimiento utilizó?
14. ¿Por qué está explicando algo que no hizo?
15. ¿Ese término ya fue definido?
16. ¿Esta conclusión realmente se deriva de la tabla?
17. ¿La fuente realmente dice eso?

Resolver con evidencia y redacción cuando sea posible. Si el sustento no existe, consultar **en el chat**, sin crear texto artificial ni marcadores en el proyecto.

### Escritura académica y bibliografía

- Párrafos con unidad argumental, consistencia referencial, precisión científica y economía de lenguaje; no oraciones acumuladas por puntos seguidos ni cadenas de «y».
- Tiempos verbales de **proyecto**: presente para teoría/decisiones, futuro para procedimientos previstos y pasado para antecedentes.
- APA 7 salvo mandato institucional distinto; fuentes, cifras y DOI verificables. No inventar referencias, estadísticas ni plazos.
- No trasladar ejemplos ni datos de `ejemplo_v16/` o del `main.tex` demostrativo.

### Transformación a LaTeX

- Respetar `SEMANTICA_DOCUMENTO.md`, `NORMAS_FORMATO.md` y todos los comandos reales de los `.sty`.
- Mantener portada con comandos existentes, títulos jerárquicos sin numeración escrita a mano, listas apropiadas, referencias con sangría y enlaces en la fuente principal.
- Matriz de operacionalización: apaisada, ancho `\linewidth`, bordes y celdas agrupadas, columna «Indicador», cada indicador como elemento individual, paginación centrada inferior.
- Cronograma: semanas explícitas agrupadas por mes, no cronograma mensual ni calendario copiado del ejemplo.
- Presupuesto: seis columnas institucionales (clasificador MEF, rubro, cantidad, P. unitario, total, financiamiento), sin inventar cifras.
- A4, márgenes de 2,5 cm, Times New Roman 12 cuando esté instalada, sangría 1,27 cm únicamente donde corresponda y espaciados definidos por los estilos.

### Frontera estricta chat / documento

**Solo en chat:** observaciones metodológicas, decisiones externas, bibliografía no comprobada, datos faltantes, problemas técnicos, resultados de auditoría y explicaciones sobre el trabajo del redactor.

**Solo en la tesis:** redacción académica final sustentada, datos verificados, ecuaciones, tablas, figuras, citas y referencias correspondientes a la investigación.

No crear archivos `PENDIENTES_VALIDACION.md`, `OBSERVACIONES.md`, `TODO.md` o similares; no escribir `[PENDIENTE]`, `[POR COMPLETAR]`, `[VERIFICAR]` o explicaciones de revisión en `.tex` o PDF. No sustituir un dato desconocido con una invención. Si falta información, producir los apartados que sí pueden sustentarse y comunicar el impedimento en la conversación.

### Entrega

Compilar al menos dos pasadas con XeLaTeX, revisar PDF **real** y presentar ZIP editable y PDF si es técnicamente posible. Antes de entregar, buscar en fuentes y PDF marcadores, datos históricos y comentarios editoriales; no entregar como final lo que todavía los contenga. Las observaciones del redactor solo aparecen en el chat.
