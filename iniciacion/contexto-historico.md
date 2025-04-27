---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Contexto Histórico

Esta actividad guía a los alumnos a elaborar un **Contexto Histórico realista y preciso** ayudándose de herramientas de inteligencia artificial.

<Steps>
<Step>
### **Preparar la información base.**

<Tabs>
<Tab title="Instrucciones">
A partir de los datos que el alumno haya recopilado en su tabla de [Datos Históricos](datos-historicos.md), se construirá un pequeño listado.

* Periodo
* Tecnología
* Medio Ambiente
* Sociedad
* Innovación Clave
</Tab>

<Tab title="Ejemplo">
* **Periodo**:&#x20;
  * Paleolítico inferior (≈ 450 000 a. C.)
* **Tecnología**:&#x20;
  * Industria Achelense (bifaces simétricos de sílex y cuarcita)
  * Uso eventual de martillos de madera.
* **Medio ambiente**:&#x20;
  * Sabana intercalada con galería boscosa
  * Alternancia de estaciones secas/húmedas.
* **Sociedad**:&#x20;
  * Bandas de 20-30 individuos
  * Cooperación básica
  * Cuidado de crías prolongado
  * Comunicación protolingüística (gestos, vocalizaciones).
* **Innovación clave**:&#x20;
  * Control intermitente del fuego en hogueras naturales: noches más largas de actividad, defensa frente a depredadores.
* **Fuente**: Libro de texto, pág. 12.
</Tab>
</Tabs>

</Step>

<Step>
### **Elaborar el prompt para la IA.**

Para elaborar un **Contexto Histórico** de calidad usando Inteligencia Artificial, es fundamental que los alumnos aprendan a formular un **buen prompt**: un mensaje claro y preciso que indique exactamente lo que queremos que la IA escriba.

<Tabs>
<Tab title="Instrucciones">
1. **Presentar el objetivo**:\
   Explicar que se quiere redactar un **párrafo breve** que describa cómo era la vida en una época concreta, basándose **solamente** en los datos que ya tienen.
2. **Dar instrucciones claras**:\
   El mensaje debe pedir explícitamente que:
   * Solo se use la información proporcionada (sin inventar ni añadir datos externos).
   * Se escriba en un formato y estilo determinados.
3. **Especificar formato y estilo**:
   * **Extensión**: Un único párrafo de 90 a 120 palabras.
   * **Tono**: Divulgativo y preciso, escrito en tercera persona.
   * **Inicio**: El párrafo debe empezar con una frase específica como "En el Paleolítico inferior…".
   * **Integración de la información**: No repetir la lista de datos ni citar fuentes; todo debe estar integrado de forma fluida en el texto.
4. **Usar siempre un lenguaje sencillo y directo en el prompt** para evitar interpretaciones erróneas.
</Tab>

<Tab title="Ejemplo">
Redacta un párrafo titulado **"Contexto histórico real"** para una ficha-personaje de Prehistoria.\
Utiliza **solamente** los hechos de la siguiente lista (no añadas información externa):

* Periodo: Paleolítico inferior (≈ 450 000 a. C.)
* Tecnología: Industria Achelense (bifaces simétricos de sílex y cuarcita); uso eventual de martillos de madera.
* Medio ambiente: Sabana intercalada con galería boscosa; alternancia de estaciones secas/húmedas.
* Sociedad: Bandas de 20-30 individuos; cooperación básica, cuidado de crías prolongado; comunicación protolingüística (gestos, vocalizaciones).
* Innovación clave: Control intermitente del fuego en hogueras naturales: noches más largas de actividad, defensa frente a depredadores.

**Formato y estilo**:

* Un único párrafo de 90-120 palabras.
* Tono divulgativo y preciso, tercera persona.
* Empieza con "En el Paleolítico inferior…".
* No repitas la lista ni cites la fuente, integra todo en prosa continua.
</Tab>
</Tabs>
</Step>

<Step>
### Revisión crítica

El objetivo es que los alumnos aprendan a revisar críticamente el contenido generado con IA e identifiquen errores comparando el texto generado con las fuentes originales.

<Tabs>
<Tab title="Instrucciones">
* **Comparar punto por punto con la información original**:
  * Revisar si el texto incluye **todos los datos** proporcionados:
    * Periodo
    * Tecnología
    * Medio ambiente
    * Sociedad
    * Innovación clave
  * Verificar si esos datos se reflejan de manera correcta, usando como referencia los [Datos Históricos](datos-historicos.md) y el libro de texto.
* **Detectar información no autorizada**:
  * Comprobar si el texto añade información que **no aparece** en su [Datos Históricos](datos-historicos.md)  ni en el libro.
  * Si detectan añadidos (como inventos, eventos, tecnologías o costumbres no mencionadas en el libro), deben considerarlo un **error**.
* **Identificar errores históricos**:
  * Revisar si el texto incluye **anacronismos** o datos erróneos (por ejemplo, mencionar cerámica en el Paleolítico Inferior).
* **Registrar los errores en una** [**Tabla de Errores**](../tabla-de-errores.md)
</Tab>

<Tab title="Ejemplo">
<table>
<thead>
<tr>
<th width="127.13671875">Tipo de Error</th>
<th>Error Detectado</th>
<th>Fuente Correcta (según libro)</th>
<th>Corrección Propuesta</th>
</tr>
</thead>
<tbody>
<tr>
<td>Anacronismo</td>
<td>Mención de cerámica en el Paleolítico Inferior</td>
<td>La cerámica no existía en el Paleolítico Inferior</td>
<td>Eliminar la referencia a la cerámica.</td>
</tr>
<tr>
<td>Invento añadido</td>
<td>Uso de arcos y flechas</td>
<td>No se documentan arcos en el Paleolítico Inferior</td>
<td>Sustituir por el uso de bifaces de sílex.</td>
</tr>
<tr>
<td>Omisión</td>
<td>No se menciona el control del fuego</td>
<td>El control del fuego es una innovación clave</td>
<td>Añadir una frase que describa el control del fuego.</td>
</tr>
<tr>
<td>Error de contexto</td>
<td>Descripción de vida en aldeas permanentes</td>
<td>La sociedad era nómada en bandas</td>
<td>Corregir describiendo bandas móviles de 20-30 personas.</td>
</tr>
<tr>
<td>Error de tecnología</td>
<td>Uso de herramientas metálicas</td>
<td>No había metalurgia en el Paleolítico Inferior</td>
<td>Cambiar por herramientas de piedra y madera.</td>
</tr>
<tr>
<td>Estilo inadecuado</td>
<td>Texto muy técnico ("sistema protolingüístico emergente")</td>
<td>Tono divulgativo sencillo</td>
<td>Reformular en lenguaje claro ("se comunicaban con gestos y sonidos").</td>
</tr>
<tr>
<td>Error de medio ambiente</td>
<td>Mención de bosques tropicales</td>
<td>Clima: sabana intercalada con galerías boscosas</td>
<td>Ajustar el paisaje descrito al correcto.</td>
</tr>
<tr>
<td>Información externa añadida</td>
<td>Referencia a rituales funerarios organizados</td>
<td>No documentados en ese periodo en el libro</td>
<td>Eliminar mención o aclarar que no hay evidencias.</td>
</tr>
<tr>
<td>Error de innovación clave</td>
<td>Uso de domesticación de animales</td>
<td>No existía aún la domesticación</td>
<td>Eliminar referencia y reforzar actividades de caza y recolección.</td>
</tr>
<tr>
<td>Error de extensión</td>
<td>Párrafo supera las 150 palabras</td>
<td>Extensión pedida: entre 90-120 palabras</td>
<td>Resumir para cumplir el límite.</td>
</tr>
</tbody>
</table>
</Tab>
</Tabs>
</Step>

<Step>
### Re-Prompt

* Si hay pequeños errores, el alumno puede corregir el texto directamente.
* Si hay muchos errores, se recomienda rehacer el prompt ajustándolo mejor.
</Step>
</Steps>

1.  **Revisar el resultado con un Checklist**:\
    Una vez la IA entregue el párrafo, el alumno debe revisarlo usando esta lista de comprobación:

    ✅ ¿Menciona todos los puntos clave (tecnología, medio ambiente, sociedad, innovación)?\
    ✅ ¿Añadió algo que NO estaba en la lista?\
    ➔ Si sí: señalizarlo y rehacer el prompt pidiendo "No añadir información externa".\
    ✅ ¿El tono es divulgativo y claro, no demasiado técnico?\
    ➔ Si no: pedir "hazlo más claro/menos técnico".\
    ✅ ¿Hay anacronismos (herramientas o hechos que no existían aún)?\
    ➔ Si los hay: pedir corrección o anotarlo en una tabla de errores.
2. **Ajustes y correcciones**:
   * Si el texto es correcto, puede ser incorporado directamente a la ficha-personaje.
   * Si el texto tiene errores menores, el alumno puede corregirlos manualmente con tu ayuda.
   * Si hay errores graves, se debe rehacer el prompt con mejores instrucciones.