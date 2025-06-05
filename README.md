# 🛢️ Análisis de Riesgo en la Exploración de Pozos Petroleros

Este proyecto fue desarrollado para **OilyGiant**, una empresa del sector energético que busca invertir estratégicamente en el desarrollo de **200 nuevos pozos petroleros**. Se evaluaron tres regiones candidatas mediante técnicas de predicción y análisis de riesgo, con el objetivo de tomar decisiones informadas que minimicen las pérdidas y maximicen el retorno esperado.

---

## 🎯 Objetivo

- 🧪 Estimar la cantidad de petróleo disponible por pozo en tres regiones distintas.
- 🔍 Seleccionar los pozos con mayor volumen estimado de reservas.
- 💰 Calcular el posible beneficio económico por región.
- ⚖️ Evaluar el **riesgo financiero** mediante simulaciones estadísticas.

---

## 🔍 Metodología

1. **Predicción de Reservas de Petróleo**  
   Se entrena un modelo de regresión para estimar el volumen de petróleo recuperable por pozo en cada región.

2. **Selección de Pozos Óptimos**  
   Se seleccionan los **200 pozos con mayor potencial** de producción para evaluar su rendimiento económico.

3. **Cálculo del Beneficio Potencial**  
   Se calcula el ingreso esperado por pozo, restando el costo de desarrollo a los ingresos estimados.

4. **Evaluación de Riesgos con Bootstrapping**  
   Se generan **miles de escenarios aleatorios** usando remuestreo para analizar la probabilidad de pérdida.

---

## 📊 Resultados

- 📍 **Región 2** fue identificada como la **mejor opción** entre las tres analizadas.
- ❌ Aunque ninguna región genera ganancias en promedio, **Región 2 presenta la menor pérdida estimada**.
- 📉 Las simulaciones muestran que el impacto negativo es **más controlado** en Región 2, haciéndola la más viable desde un enfoque de mitigación de riesgos.

---

## 🛠️ Tecnologías Utilizadas

- Python 🐍  
- Pandas & NumPy 📊  
- Scikit-learn 🤖  
- Matplotlib 📈  
- Bootstrapping (simulación estadística)

---

## ✅ Conclusión

Este análisis permitió a OilyGiant tomar una decisión estratégica basada en datos, priorizando no solo el rendimiento potencial sino también la **exposición al riesgo financiero**. La combinación de técnicas predictivas y simulaciones probabilísticas proporciona una herramienta sólida para la planificación en industrias de alto riesgo como la energética.

---

📫 ¿Te interesa colaborar en más proyectos de ciencia de datos aplicada? ¡Estoy abierto a nuevas oportunidades y desafíos!
