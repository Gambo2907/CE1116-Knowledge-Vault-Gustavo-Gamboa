---
Fecha de creación: 2025-08-05 00:00
Fecha de Modificación: 2025-08-05 00:00
tags:
  - "#ingeniería-de-software"
Topic: []
---


## 📚 Idea/Concepto 
 El mecanismo de atención en los Transformers es la autoatención (self attention) y su extensión, la atención multicabezal (multi-head attention). Estos mecanismos permiten al modelo ponderar la importancia de diferentes partes de la secuencia de entrada al generar una salida, calculando vectores de consulta (Query), clave (Key) y valor (Value) para cada elemento, estos vectores son proyecciones lineales aprendidas (a través de matrices de pesos) de los embeddings de entrada. El self-attention se calcula la compatibilidad QK por medio de un producto punto para luego realizar la normalización (Softmax) la cual es una función en la que se obtienen pesos de atención, esto es muy importante porque permite el procesamiento paralelo de secuencia.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redes Neuronales]]
- [[Large Language Models (LLMs)]] 


## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 