# Análisis de Riesgo para el Desarrollo de Pozos Petroleros
El objetivo de este proyecto es ayudar a la empresa OilyGiant a seleccionar la mejor región para abrir 200 nuevos pozos de petróleo. Se analizan tres posibles regiones con datos clave sobre la cantidad de petróleo que se podría extraer de cada pozo, y se utilizan diferentes técnicas para evaluar el beneficio y el riesgo de cada opción.

🔍 Metodología utilizada:

Predicción de reservas: Se crea un modelo que estima la cantidad de petróleo que podría haber en los nuevos pozos en cada región.
Selección de pozos con mayor potencial: Después de las predicciones, se identifican los pozos con el mayor volumen de reservas.
Cálculo del beneficio: Se calculan los posibles beneficios de abrir los pozos en cada una de las tres regiones.
Evaluación del riesgo: A través de la técnica de bootstrapping, se analizan distintos escenarios de pérdida para cada región, permitiendo entender los riesgos asociados a la inversión.
📊 Resultados:

La Región 2 fue identificada como la opción más favorable, ya que, aunque no generará ganancias, sus pérdidas son menores comparadas con las otras dos regiones.
A pesar de que las tres regiones tienen riesgos asociados, la Región 2 ofrece el menor impacto negativo, lo que la convierte en la opción más recomendada.
🛠️ Tecnologías utilizadas: Python, Pandas, Scikit-Learn, Matplotlib, Bootstrapping.
