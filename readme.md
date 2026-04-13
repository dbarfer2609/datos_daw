Práctica RA5 · c+d — Big Data e IA

1) Caso
Sistema: Detección de fraude bancario en BBVA
Contexto: Un banco analiza millones de transacciones diarias para detectar operaciones fraudulentas en tiempo real y proteger a sus clientes.

2) Conceptos
Big Data: Conjunto de datos masivos (como transacciones bancarias) que requieren herramientas avanzadas para su gestión.
Análisis de datos: Proceso de examinar esos datos para encontrar patrones sospechosos o comportamientos anómalos.
Machine Learning: Algoritmos que aprenden de transacciones pasadas para identificar fraudes automáticamente.
Deep Learning: Modelos más avanzados (redes neuronales) capaces de detectar patrones complejos y difíciles de identificar.
IA: Sistema global que utiliza estos modelos para tomar decisiones inteligentes (bloquear o permitir transacciones).

3) Relación
Los clientes generan datos constantemente (pagos, transferencias).
Estos datos se almacenan como Big Data, luego se analizan para encontrar patrones.
Con ese análisis se entrenan modelos de Machine Learning y Deep Learning, que forman parte de la IA del banco, la cual toma decisiones en tiempo real (detectar fraude o no).

4) Pipeline
Datos masivos → Procesamiento → Análisis → Modelo ML/DL → IA → Decisión
- Se registran millones de transacciones
- Se limpian y organizan los datos
- Se analizan patrones de comportamiento
- Se entrena un modelo ML/DL
- La IA evalúa cada nueva transacción
- Se decide si es segura o fraudulenta
  
5) 5V del Big Data
- Volumen: Millones de transacciones diarias
- Velocidad: Procesamiento en tiempo real
- Variedad: Datos de compras, ubicaciones, dispositivos
- Veracidad: Necesidad de datos precisos para evitar errores
- Valor: Prevención de fraude y ahorro económico
  
6) Ejemplo aplicado
- Datos: Importe, ubicación, hora, tipo de compra, historial del cliente
- Análisis: Comparación con patrones normales del usuario
- Modelo: Algoritmo de Machine Learning (detección de anomalías) y redes neuronales
- Decisión: Bloquear la transacción o solicitar verificación al cliente

7) Tabla
| Concepto | Función |
|----------|--------|
| Big Data | Gestionar grandes volúmenes de datos masivos |
| Análisis de datos | Extraer información útil y patrones |
| ML/DL | Aprender de los datos y hacer predicciones |
| IA | Tomar decisiones inteligentes automáticamente |
8) Diagrama
```
Usuario
   ↓
Datos
   ↓
Big Data
   ↓
Procesamiento
   ↓
Análisis
   ↓
ML / DL
   ↓
IA
   ↓
Decisión
```
9) Problemas
Problema 1: Falsos positivos (bloquear compras legítimas)
Solución 1: Mejorar modelos con más datos y ajustar umbrales
Problema 2: Sesgo en los datos (clientes mal clasificados)
Solución 2: Uso de datos diversos y auditorías de los modelos

10) Fuente
Enlace: https://www.bbva.com/es/innovacion/que-es-big-data/.
