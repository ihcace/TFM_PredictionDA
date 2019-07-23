# TFM_PredictionDA
## Trabajo Fin del Máster en Inteligencia Artificial: Predicción de Actividades del Día a Día con Redes LSTM

Autor: Inés Heras Cáceres
Universidad Internacional de la Rioja

El trabajo trata de predecir la siguiente actividad que se realizará a partir de datos de sensores.
Se han desarrollado en Google Colab, por lo que todos los notebooks queran preparados para ejecutarse en este entorno. Se recomienda su ejecución con GPU

### Datos
Todos los datos utilizados y sus descripciones se encuentran comprimidos en Data.7z
Se han utilizado dos conjuntos de datos: data1 y data2. Se dispone la descripción de ambos en los ficheros data1_README y data2_README
Ambos pertenecen al repositorio [CASAS](http://casas.wsu.edu/datasets/).

### Preprocesamiento
Para preprocesar cada uno de ellos, se han desarrollado dos notebooks: DataPrep1.ipynb y DataPrep2.ipynb
Puesto que estos procesos pueden tardar más de una hora, se incluye el resultado de ambos en los ficheros data1_window_next y data2_window_next
Para su ejecución, se deben configurar las variables FILE (datos de entrada en crudo) y WINDOW_FILE (datos de salida con ventana)

### Modelos
En los ficheros DataModel1.ipynb y DataModel2.ipynb, se encuentran los modelos para cada uno de los datasets, donde se entrenan las redes neuronales y se muestran los resultados
Los datos de entrada de los notebooks son los ficheros data1_window_next y data2_window_next respectivamente
Para su ejecución, se debe configurar la variable WINDOW_FILE (datos de entrada con ventana)