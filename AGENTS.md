# REGLA PRIORITARIA V8 — producción final sin rastros de revisión

> Esta regla prevalece sobre instrucciones anteriores del paquete que sugieran usar marcadores visibles, crear archivos de pendientes o trasladar observaciones al documento. Aplica al **proyecto final redactado**, no a ejemplos históricos conservados para consulta.

## Separación obligatoria de dos espacios
- **Chat:** toda auditoría académica, cuestionamientos, hallazgos del asesor riguroso, decisiones que requieran al investigador, comprobaciones bibliográficas, ausencias de datos, incertidumbres administrativas, incidencias de compilación y estado de verificación.
- **Archivos LaTeX del proyecto final y PDF:** exclusivamente contenido académico sustentado, elementos institucionales con datos aportados, tablas, gráficos, referencias y archivos técnicos necesarios para compilar. Sin comentarios de revisión académica ni texto que explique el trabajo del asistente.
- No crear `PENDIENTES_VALIDACION.md`, `OBSERVACIONES.md`, `REVISION.md`, `TODO.md` ni archivos equivalentes como entregables. Los reportes de revisión se emiten **en el chat**.
- No escribir en `main.tex`, archivos incluidos, tablas, bibliografía, comentarios LaTeX o PDF: `[PENDIENTE]`, `[VERIFICAR]`, `[POR COMPLETAR]`, `[REVISAR]`, `TODO`, instrucciones al autor, advertencias de falta de información ni notas sobre posibles correcciones.
- Una limitación metodológica o incertidumbre científica **real y sustentada** sí puede formar parte de la tesis; una duda editorial del redactor no.
- Cuando falte un dato indispensable: buscarlo en las fuentes proporcionadas; si no aparece, comunicarlo en el chat. No inventarlo ni simularlo. Continuar con partes sustentadas y no insertar un contenido de reemplazo dentro del informe.
- El `main.tex` distribuido en la v7/v8 contiene **contenido ilustrativo de una tesis anterior y el comando `\pendiente`**. Nunca entregar ese contenido o comando en el proyecto final de otra investigación. Eliminarlo o sustituirlo por contenido real al redactar; no tratar el ejemplo como fuente de datos.

## Flujo obligatorio de producción de un borrador completo
1. Leer `AGENTS.md`, `SEMANTICA_DOCUMENTO.md`, `NORMAS_FORMATO.md`, y el prompt maestro de redacción proporcionado por el usuario. Interpretar todo el borrador, metodología, tablas, imágenes, referencias y anexos.
2. Reconstruir y verificar la correspondencia realidad–problema–objetivos–hipótesis (si aplican)–variables/dimensiones/indicadores–instrumentos–procedimiento–análisis. Distinguir errores editoriales de decisiones metodológicas. **No cambiar decisiones sustantivas silenciosamente**.
3. Redactar con organización previa de ideas, unidad argumental, conectores según su función, terminología estable y fidelidad a fuentes. Evitar yuxtaponer oraciones independientes mediante puntos seguidos, saturación de «y» o conectores y sustitución mecánica por puntos y coma.
4. Aplicar la batería completa de **17 preguntas del asesor riguroso**, tal como está en `PROMPT_PRODUCCION_FINAL.md`; si se aporta `Prompt_Maestro_Unificado_Redaccion_Academica.md`, aplicarlo íntegramente y darle prioridad para redacción académica.
5. Para proyecto de tesis, usar presente en teoría/decisiones, futuro en actividades por ejecutar y pasado en antecedentes. No presentar resultados o trabajo futuro como ejecutados.
6. Incorporar exclusivamente los textos finales sustentados en `main.tex`, usando comandos semánticos reales. Mantener los `.sty`, formato institucional, tablas horizontales, matriz, cronograma semanal, presupuesto institucional y referencias.
7. Compilar con XeLaTeX (varias pasadas), inspeccionar visualmente el PDF final y buscar desbordamientos, roturas, problemas de paginación, tablas cortadas y diferencias con la referencia. No asegurar pruebas que no se ejecutaron.
8. Antes de entregar, **auditar todos los archivos fuente y el PDF** para descartar marcadores, notas de revisión, comentarios editoriales, datos de la tesis histórica y apartados provisionalmente inventados. Informar incidencias **solo en el chat**.
9. Entregar ZIP editable y PDF cuando se haya podido compilar. La explicación de lo modificado y las observaciones se dan en el chat y no se guardan como archivo en el proyecto final.

## Prohibiciones específicas
- No añadir secciones de «pendientes de validación», «observaciones del asesor», «comentarios de IA» o «datos faltantes» al documento académico.
- No duplicar archivos finales (`main_v2.tex`, `final_final.tex`). Trabajar sobre el mismo proyecto; los ejemplos históricos permanecen fuera del documento final.
- No dar por finalizada una tesis que todavía contiene marcadores de plantilla o datos ilustrativos.
- No suprimir hallazgos científicos auténticos por confundirlos con las observaciones editoriales: el criterio es **naturaleza científica vs. control de redacción**, no la aparición de la palabra «limitación».

---

# Instrucciones permanentes para asistentes de IA — Proyecto de tesis de posgrado

## Fuente de verdad
- Trabaja **siempre sobre el mismo proyecto**; no generes `main_v2.tex`, `final_final.tex` ni copias sin petición expresa.
- El `main.tex` distribuido es una **demostración heredada** que debe reemplazarse por el estudio nuevo; `estilos.sty` controla presentación y `tablas.sty` contiene herramientas de tablas.
- `ejemplo_v16/main.tex` es un **ejemplo histórico** de Last Planner System, no la tesis actual ni una plantilla visual certificada.
- Cuando haya un Word institucional de referencia, compara contra él. No asumas que los estilos de la versión histórica son normas de la institución.

## Redacción
- Mantén la estructura de Generalidades y Plan de investigación, pero adapta apartados solo cuando las normas vigentes lo exijan.
- Conserva citas y referencias verificables; no inventes autores, publicaciones, DOI, resultados, muestras ni cifras.
- Distingue la información respaldada de la información no resuelta **solo durante la revisión en el chat**. No insertar en el documento final marcadores, advertencias editoriales ni texto ficticio.
- No alteres la metodología ni el sentido académico al resolver un problema de formato.

## Formato
- Compilar con **XeLaTeX**; utilizar Times New Roman real cuando esté instalada. Nunca afirmar que Tinos equivale exactamente a Times New Roman.
- Base de referencia extraída del ejemplo Word: A4, márgenes 2,5 cm, 12 pt, sangría 1,27 cm, espaciado posterior normal 12 pt, interlineado objetivo 1,5 de Word. El ajuste de LaTeX requiere validación visual.
- Los títulos deben llevar espaciado propio, sin sumar accidentalmente `parskip` dos veces.
- Para listas que siguen inmediatamente a un subtítulo usar `listatitulo`; para otras, `listacuerpo`.
- Para recursos utilizar `listarecursos` con guiones, independiente de las listas del cuerpo.
- Las tablas deben mantener bordes, fusiones y orientación de página originales. No inventar cronogramas, presupuestos ni indicadores.
- El cronograma y la matriz son secciones de orientación horizontal. La numeración de página debe seguir legible.
- Los títulos de tablas llevan número en negrita, denominación en cursiva, alineados a la izquierda; no modificar las leyendas para simular APA sin revisar requerimiento institucional.

## Pruebas antes de entregar
1. Compilar al menos dos veces con XeLaTeX y leer errores/avisos.
2. Inspeccionar el **PDF FINAL** que realmente se entrega, no una compilación intermedia.
3. Verificar portada ("Modalidad" en primera página), Generalidades, cronograma, recursos, presupuesto, listas tras títulos, matriz, referencias.
4. Buscar desbordamientos, bordes que desaparecen, tablas cortadas y páginas huérfanas.
5. Comparar elementos por ubicación y medidas, no solo cantidad de páginas.
6. Informar qué se verificó y qué continúa pendiente. No presentar una plantilla como copia exacta sin comparación suficiente.
7. Si el cambio es solo de formato, evitar cambios en textos y datos.

## Git y archivos
- Un cambio lógico = un commit cuando sea posible.
- No subir PDFs auxiliares, archivos `.aux`, `.log`, `.out`, `.synctex.gz` ni variantes duplicadas.
- No modificar `ejemplo_v16/` salvo solicitud explícita.


## REGLAS OBLIGATORIAS DE MAQUETACION (v2)
- Nunca reescribir la portada a mano. Usar `\bloqueTituloPortada{...}` para conservar dos lineas horizontales.
- No agregar `\vspace` a titulo para separar una lista. Si una lista sigue a un titulo, usar `listatitulo`; de lo contrario usar `listacuerpo`.
- Mantener `\parskip=12pt` para parrafos ordinarios; los encabezados compensan su espacio mediante reglas unicas en `estilos.sty`. No acumular mas espacios.
- En paginas apaisadas las tablas ocuparan `\linewidth`; NO anchos calculados con el ancho de pagina vertical, ni columnas fijas que excedan el disponible.
- Cronograma: su escala temporal debe seguir el diseño solicitado para cada tesis. No inventar semanas desde meses; si se necesita version semanal, solicitar o usar datos semanales documentados. El ejemplo v16 de 32 semanas es referencia estructural, NO obligacion de 32 semanas para todos los proyectos.
- Matriz: siempre cerrar borde exterior y divisoria entre variables con `\hline` completo; usar `\cline` solo dentro del bloque de una variable.
- Antes de entregar renderizar las paginas portada, cronograma, matriz, y al menos dos paginas con titulos, listas y referencias.
- Confirmar si el PDF usa Times New Roman real. Tinos solo permite comprobacion provisional.


## REGLAS OBLIGATORIAS V3 (2026-10-29)
- GENERALIDADES: usar `\generalitem` y `\generalsub`; no agregar `\vspace` manual ni dejar 12pt acumulativos entre epigrafes.
- TODA tabla: `\noindent\begin{tabularx}{\linewidth}`; no desplazar tablas con sangrias o `center`. En paginas horizontales `\linewidth` debe equivaler a todo el ancho util.
- DESPUES de cerrar la tabla, usar `\fuenteTabla{...}`; el comando aporta 9pt antes de la fuente. No escribir Fuente pegada directamente al entorno de tabla.
- PRESUPUESTO INSTITUCIONAL: seis columnas, en este orden: Clasificador MEF, Rubro, Cantidad, P. unitario (S/), Total (S/), Financia. No sustituir por tabla simplificada de tres columnas. No inventar montos ni clasificadores. Si faltan, tratar el asunto exclusivamente en el chat y no colocar marcadores en el documento final.
- REFERENCIAS: `\iniciarReferencias` una vez tras el encabezado de Referencias, luego entradas `\referencia{...}`.
- Tablas y diagramas con estructuras diferentes deben mantener el formato y declarar por separado el numero de semanas/dimensiones; no convertir de manera automatica todos los cronogramas en 32 semanas.


## Directivas obligatorias v4 (control de calidad)
- Cronograma: SIEMPRE semanal, con una columna por semana, números de semana y encabezados agrupados por mes. No sustituir por cuatro columnas mensuales. El horizonte puede cambiar según el proyecto; registrar semanas concretas y fechas verificables.
- Páginas horizontales: usar `\\thispagestyle{empty}` al abrir el entorno y `\\paginaHorizontalCentro` antes de cerrarlo; comprobar número de página centrado en el borde inferior visual. No utilizar el pie normal rotado por pdflscape.
- Matriz: encabezado **Indicador** en singular. Los indicadores múltiples de una dimensión deben ir en una lista independiente dentro de esa misma celda, con `\\celdaIndicadores{\\item ...}`. No combinar varios indicadores separados solo por punto y coma.
- Matriz: utilizar anchos calculados para `\\linewidth`, evitar texto que se salga de la primera columna; evaluar visualmente todas las columnas y las divisiones.
- Referencias: los enlaces deben usar la fuente del documento (`\\urlstyle{same}`), nunca monoespaciado.
- Cada cambio debe comprobarse en páginas horizontales reales del PDF y no solo mediante compilación exitosa.

**Comprobación obligatoria antes de entregar:** verificar en el PDF renderizado que el cronograma tenga una columna por semana y ningún mes sustituya a semanas; número de página centrado abajo en todas las páginas apaisadas; matriz dentro del área de texto; título «Indicador» y una lista por cada celda de indicadores; URLs en la misma familia tipográfica que la bibliografía. Si falla una sola comprobación, no declarar la plantilla validada.


## Interlineado obligatorio de carátula (v5)
- El texto «PROYECTO DE TESIS PARA OPTAR EL GRADO…» debe escribirse con `\gradoPortada{...}`, no como negrita libre.
- El título académico debe escribirse con `\bloqueTituloPortada{...}`, que dibuja dos líneas horizontales.
- Ambos bloques llevan **interlineado aumentado (1.35)**, configurado obligatoriamente en `estilos.sty` mediante `\interlineadoGradoPortada` y `\interlineadoTituloTesisPortada`.
- No introducir saltos manuales o `\vspace` para simular el interlineado. Comprobar la carátula del PDF final.

## REGLA V6 PRIORITARIA — semántica, presentación y contenido
Leer `SEMANTICA_DOCUMENTO.md` ANTES de editar. La estructura se define en `estructura.sty`, la presentación en `estilos.sty` y `tablas.sty` y el contenido del proyecto en `main.tex`.

- **Las palabras de los títulos son contenido variable**. Su nivel, numeración, interlineado, sangría y espacios no dependen de esas palabras.
- En el plan de investigación crear títulos SOLO mediante `\tituloPlan{...}` (nivel 1), `\subtituloPlan{...}` (nivel 2) y `\apartadoPlan{...}` (nivel 3). **No escribir números dentro de las llaves.**
- No usar `\section*` o `\textbf` como títulos de apartados redactados por el agente, salvo comandos de portada o excepciones documentadas.
- Si una lista sigue inmediatamente a un título, usar `listaTrasTitulo`; en otros casos `listaNormal`. No modificar el `\vspace` del título para arreglar listas.
- Cronograma semanal, matriz con Indicador e ítems por indicador, presupuesto de seis columnas, tipografía de URLs y páginas apaisadas centradas: respetar `SEMANTICA_DOCUMENTO.md`.

## Encabezado seguido inmediatamente de tabla (v7)
Cuando un subtítulo de segundo nivel precede sin párrafo intermedio a la leyenda «Tabla N», usar `\subtituloPlanConTabla{...}` y después `\tituloTabla{...}{...}`. No usar `\subtituloPlan` directamente en esta transición ni corregir con `\vspace` en `main.tex`. El texto del encabezado es contenido variable; el formato y el espacio son responsabilidad de `estructura.sty`. Verificar que no haya superposición tras compilar.

## Recordatorio de precedencia v8
Las reglas antiguas sobre `[PENDIENTE]` o «marcadores visibles», si reaparecen en ejemplos históricos, quedan derogadas para los productos finales. Toda incidencia se comunica en el chat.
