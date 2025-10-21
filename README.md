# Clasificación de Noticias con Modelos Transformer (AG News)

Este proyecto desarrolla y evalúa un sistema de clasificación automática de noticias utilizando el conjunto de datos **AG News**.  
Se realiza el ajuste de tres modelos de lenguaje basados en transformadores — **RoBERTa**, **DeBERTa** y **ModernBERT** — con el objetivo de categorizar noticias en cuatro temas: *Mundo*, *Deportes*, *Negocios* y *Ciencia/Tecnología*.  
El propósito es comparar su desempeño y analizar cómo la arquitectura y la comprensión contextual de cada modelo influyen en la precisión de la clasificación.

Como **tarea adicional (Bonus Task)**, se amplía el sistema para clasificar noticias reales de **RPP**, comparando los resultados de los modelos entrenados con las clasificaciones generadas por un **modelo de lenguaje de gran escala (LLM)**.  
Esta comparación permite explorar el grado de coincidencia y las diferencias entre los transformadores ajustados y un LLM al aplicarse a contenido local y de dominio específico.

El proyecto tambien esta conectado con otro repositorio llamdo **news-query_RPP-lab** , que integra recuperación de texto, embeddings y categorización, además, busca **comprender cómo funcionan los modelos de lenguaje, cómo pueden entrenarse o ajustarse (fine-tuning) para tareas específicas y de qué manera se puede mejorar su precisión** al aplicar técnicas de evaluación y comparación entre diferentes arquitecturas.