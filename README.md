Gravitas

### ¿Es viable tu negocio?

Gravitas es una herramienta web diseñada para ayudar a emprendedores, trabajadores independientes y propietarios de pequeños negocios en México a evaluar la viabilidad financiera de sus actividades. Convierte información básica sobre ventas, costos, gastos, inversión y deudas en indicadores financieros, escenarios de riesgo y recomendaciones prácticas.

El objetivo es acercar el análisis financiero a personas que no necesariamente tienen conocimientos de contabilidad o finanzas.

## Características

- **Evaluación de viabilidad:** análisis de la situación financiera del negocio a corto, mediano y largo plazo.

- **Proyecciones financieras:** estimaciones de ingresos, costos, gastos y ganancias para los próximos cinco años.

- **Indicadores de inversión:** cálculo del valor actual neto (VAN), tasa interna de retorno (TIR) y periodo de recuperación de la inversión.

- **Punto de equilibrio:** estimación del volumen de ventas necesario para cubrir los gastos del negocio.

- **Análisis de escenarios:** comparación de proyecciones base, optimistas y pesimistas.

- **Estado de resultados:** resumen mensual de ingresos, costos, gastos, impuestos estimados y ganancia neta.

- **Balance simplificado:** estimación de activos, pasivos y capital del negocio.

- **Recomendaciones personalizadas:** sugerencias para mejorar la rentabilidad, controlar gastos y gestionar riesgos.

- **Informes en PDF:** generación de un documento con los resultados y las recomendaciones.

- **Diseño adaptable:** interfaz compatible con pantallas de escritorio y dispositivos móviles.

## Tecnologías

El proyecto utiliza tecnologías web estándar:

- HTML5 para la estructura.

- CSS3 para el diseño y la adaptación a distintos dispositivos.

- JavaScript para la lógica financiera, los cálculos y la interacción.

- jsPDF para la generación de informes en PDF.

- `localStorage` para conservar las respuestas en el navegador.

La aplicación está implementada en un único archivo HTML, por lo que no requiere instalar un entorno de desarrollo ni configurar un servidor para utilizar sus funciones principales.

## Cómo utilizarlo

1. Descarga o clona este repositorio.

2. Abre el archivo `index.html` en un navegador moderno.

3. Completa las cinco etapas del cuestionario con información aproximada de tu negocio.

4. Consulta los resultados, los indicadores financieros, los escenarios y las recomendaciones.

5. Genera un informe en PDF si deseas conservar o compartir el análisis.

Para generar el PDF, el navegador necesita acceso a la CDN desde la que se carga jsPDF, salvo que la biblioteca se encuentre disponible localmente.

## Privacidad

Las respuestas se almacenan mediante `localStorage` en el navegador del usuario. La aplicación no necesita una cuenta ni un servidor propio para realizar los cálculos.

Los datos pueden permanecer guardados en el navegador después de cerrar la página. Si utilizas un dispositivo compartido, evita introducir información financiera confidencial y elimina los datos locales cuando corresponda.

La carga de dependencias externas puede implicar conexiones a terceros. Por ello, el almacenamiento local no debe interpretarse como una garantía de funcionamiento completamente desconectado ni de privacidad absoluta.

## Metodología financiera

Gravitas utiliza la información proporcionada por el usuario para construir una evaluación financiera simplificada.

Entre los principales cálculos se encuentran:

- Proyección de ingresos y gastos.

- Estimación de ganancias netas.

- Punto de equilibrio operativo.

- Valor actual neto (VAN).

- Tasa interna de retorno (TIR).

- Periodo estimado de recuperación.

- Comparación de escenarios con distintas hipótesis de ventas.

El modelo incorpora supuestos de crecimiento e inflación y utiliza una tasa mínima de rendimiento de referencia basada en la TIIE y la inflación esperada.

Las proyecciones dependen de la calidad de los datos introducidos y de los supuestos incorporados en el código. Los resultados no constituyen una predicción garantizada del desempeño futuro del negocio.

## Fuentes y supuestos de mercado

El código incorpora valores de referencia atribuidos a fuentes como el INEGI, el Banco de México y la Encuesta Citi de Expectativas.

Los valores incluidos en la versión actual corresponden al corte indicado en el código fuente: **22 de octubre de 2026**.

Antes de utilizar los resultados para tomar decisiones financieras, se recomienda verificar las cifras, sus fechas de publicación y las fuentes originales. Las tasas y los supuestos deben actualizarse periódicamente.

## Limitaciones

Gravitas es una herramienta de evaluación preliminar y no sustituye un análisis financiero integral.

- Los resultados dependen de los datos introducidos por el usuario.

- Los escenarios son estimaciones basadas en supuestos simplificados.

- El tratamiento de impuestos no contempla todas las particularidades de cada régimen fiscal.

- El modelo no incorpora explícitamente todos los movimientos de efectivo, las necesidades de capital de trabajo, la reposición de activos ni el valor residual.

- Los resultados no sustituyen la asesoría de un contador ni de un profesional financiero.

**Importante:** la clasificación de viabilidad es una orientación basada en el modelo implementado, no una garantía de éxito o fracaso empresarial.

## Estado del proyecto

Gravitas es un proyecto independiente en desarrollo. Su propósito es facilitar el acceso a herramientas de análisis financiero mediante una interfaz sencilla, comprensible y accesible.

Las mejoras futuras pueden incluir validación más exhaustiva de los cálculos, actualización documentada de los datos de mercado, ampliación del modelo de flujo de caja y mayor personalización de los análisis.

## Licencia

La licencia de distribución y reutilización está pendiente de definir. Consulta al autor antes de asumir que el código puede utilizarse, modificarse o redistribuirse libremente.

---

**Gravitas — Entender los números para decidir mejor.
