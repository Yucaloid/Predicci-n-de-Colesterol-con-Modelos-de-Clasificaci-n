# Predicción de Colesterol con Modelos de Clasificación

Este proyecto analiza un conjunto de datos con características relevantes para predecir los niveles de colesterol alto. Se evaluaron diversos algoritmos de clasificación para seleccionar el modelo más eficiente en términos de precisión.

## Dataset
El dataset incluye las siguientes características:
- Edad: Edad de la persona.
- Sexo: Género de la persona.
- PS: Presión sistólica.
- Na: Nivel de sodio en la sangre.
- K: Nivel de potasio en la sangre.
- Droga: Medicamentos específicos.
- Colesterol: Nivel de colesterol en la sangre.

## Modelos Utilizados
Los siguientes modelos de clasificación fueron implementados y evaluados:
1. K-Nearest Neighbors (KNN)
2. Regresión Logística
3. Naive Bayes
4. Redes Neuronales
5. Random Forest

## Resultados
El modelo **K-Nearest Neighbors (KNN)** fue el mejor, obteniendo una precisión del 90%. Este modelo ofrece una herramienta precisa para la predicción del colesterol alto y puede ser útil para intervenciones tempranas que mejoren la salud cardiovascular.

## Conclusiones
Este estudio demuestra la importancia de seleccionar el modelo adecuado para la predicción de enfermedades basadas en datos clínicos. El modelo KNN optimizado resultó ser el más efectivo para este caso de uso.

## Instrucciones para Ejecutar el Proyecto
1. Clona este repositorio:
    ```
    git clone https://github.com/usuario/repo_colesterol.git
    ```
2. Instala las dependencias necesarias:
    ```
    pip install -r requirements.txt
    ```
3. Ejecuta el Jupyter Notebook:
    ```
    jupyter notebook TallerClasificacion.ipynb
    ```

## Colaboradores
- Johan Caro
- Sebastian Rodriguez
