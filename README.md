# Film-Junky-Union-Review-Classification
Clasificación de Reseñas - Film Junky Union

Descripción del Proyecto
Este proyecto, desarrollado para la comunidad Film Junky Union, implementa un sistema automatizado para clasificar reseñas de películas clásicas en positivas y negativas. Utilizando datos de IMDb, el objetivo principal fue entrenar un modelo de aprendizaje automático que alcance un F1 Score de al menos 0.85 en un conjunto de pruebas.

Estructura del Proyecto
Inicialización
Instalación de bibliotecas necesarias y configuración del entorno para el análisis.

Carga y Exploración de Datos (EDA)

Análisis de un conjunto de datos con más de 47,000 reseñas de IMDb.
Exploración de características clave como el año de lanzamiento, géneros y polaridad de las reseñas.
Normalización de Texto
Procesamiento de las reseñas para eliminar caracteres irrelevantes, uniformizar el formato y preparar los textos para su análisis.

Modelos Implementados

Modelo 0 (Constante): Línea base para evaluar desempeño inicial.
Modelo 1 (TF-IDF + Regresión Logística): Logró un F1 Score de 0.86.
Modelo 3 (TF-IDF Optimizado + Regresión Logística): Rendimiento destacado con F1 Score de 0.88.
Modelo 4 (LightGBM + Embeddings y TF-IDF): Una opción robusta con F1 Score de 0.86.
Modelo 9 (BERT): Explorado como modelo avanzado, con ajustes iniciales limitados por recursos.
Evaluación y Métricas

Comparación de exactitud, F1 Score y ROC AUC entre modelos.
Visualización de matrices de confusión y métricas por clase.
Conclusiones

El Modelo 3 es la solución recomendada por su desempeño consistente.
BERT mostró potencial para futuras iteraciones con más recursos.
Cómo Ejecutar el Proyecto
Clonar el repositorio:

git clone https://github.com/jose-alberto-hurtado/Film-Junky-Union-Review-Classification.git
Instalar las dependencias:

pip install -r requirements.txt
Ejecutar el notebook:

jupyter notebook Clasificación_de_Reseñas_Film_Junky_Union.ipynb
Tecnologías Utilizadas
Python

Bibliotecas: pandas, scikit-learn, spacy, lightgbm, transformers
Modelo avanzado: BERT para clasificación de texto

Recursos
Conjunto de datos: IMDb reseñas públicas.

Google Colab: Utilizado para mitigar limitaciones de recursos locales.

Autores
José Alberto Hurtado

Correo: josealberto1829@gmail.com

LinkedIn: linkedin.com/in/josé-alberto-hurtado-echeverría-77910a319

Si tienes preguntas o sugerencias, no dudes en abrir un issue o contactarme.

