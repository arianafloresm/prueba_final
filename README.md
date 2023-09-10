# Resumen

Este proyecto se centra en el desarrollo y entrenamiento de una Red Neuronal Convolucional (CNN) utilizando la biblioteca TensorFlow y Keras para la clasificación de imágenes. La CNN se entrena para clasificar imágenes en ocho clases diferentes utilizando un conjunto de datos de imágenes de carne.

# Objetivo del Proyecto
El objetivo principal de este proyecto es crear un modelo de aprendizaje automático capaz de clasificar con precisión las imágenes de carne en ocho categorías diferentes. Esto puede ser útil en aplicaciones como la inspección de calidad de productos cárnicos.

# Estructura del Repositorio
El repositorio de este proyecto está organizado de la siguiente manera:

Código Fuente: El código fuente del proyecto se encuentra en archivos Python, incluyendo la definición de la CNN, el entrenamiento del modelo y las funciones para realizar predicciones.

Modelo Pre-entrenado: Se proporciona un modelo pre-entrenado que se puede utilizar para realizar predicciones en imágenes nuevas.

Datos: El conjunto de datos utilizado para el entrenamiento y la validación se encuentra en la carpeta 'CarneDataset'. Se debe descargar y descomprimir antes de ejecutar el código.

Informe: Se incluye un informe de clasificación que muestra el rendimiento del modelo en el conjunto de datos de prueba, incluyendo la matriz de confusión y el informe de clasificación.

# Uso del Modelo Pre-entrenado
Si desea realizar predicciones en nuevas imágenes, puede utilizar el modelo pre-entrenado proporcionado. Simplemente cargue el modelo y sus pesos utilizando el código proporcionado en el archivo y llame a la función predict_class(image_path) para obtener la clasificación de una imagen específica.

# Requisitos de Software
Asegúrese de tener instaladas las siguientes bibliotecas de Python antes de ejecutar el código:

TensorFlow
Keras
Numpy
Matplotlib
Seaborn
Scikit-learn (para evaluar el rendimiento del modelo)
Pasos para Ejecutar el Proyecto
Descargue el conjunto de datos de 'CarneDataset' y colóquelo en la ubicación adecuada.

Ejecute el código Python proporcionado para entrenar el modelo o realizar predicciones en nuevas imágenes.

Consulte el informe de clasificación para evaluar el rendimiento del modelo en el conjunto de datos de prueba.

# Notas Importantes
Descargar las imagenes https://drive.google.com/file/d/1Z5DJ-MVS1TQV1kow9mIFWTec-ZdOLRLF/view?usp=sharing 

Descargar los archivo .*h5 desde el repositorio https://mailinternacionaledu-my.sharepoint.com/:f:/g/personal/arfloresmu_uide_edu_ec/Esm13oAXuARAl-LGWoDdsCABy7u5dH21CY4gh0WK9ixk2A?e=CQD4Wc

Asegúrese de que las rutas de los directorios y archivos en el código coincidan con las ubicaciones de su sistema.

Este proyecto se centra en la clasificación de imágenes de carne en ocho clases específicas. Si desea utilizar el modelo para otro tipo de clasificación, se deben realizar modificaciones en el código y el conjunto de datos.

Si encuentra problemas o errores, consulte la documentación de TensorFlow y Keras, y asegúrese de tener todas las dependencias instaladas correctamente.
