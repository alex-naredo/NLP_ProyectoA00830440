# Proyecto Final NLP 
Módulo 3: Herramientas para el procesamiento del lenguaje natural.

_Profesor: Juan Arturo Nolazco Flores_

*Alexia Elizabeth Naredo Betancourt A00830440*
Equipo 4


El proyecto se centró en la implementación de una interfaz utilizando Streamlit, una librería de Python para la creación de aplicaciones web interactivas. La interfaz tenía como objetivo principal interactuar con diversas APIs y librerías de Procesamiento del Lenguaje Natural (NLP, por sus siglas en inglés).

Para comenzar, se utilizó la librería speech_recognition para habilitar la funcionalidad de reconocimiento de voz. Esta librería permitió que la interfaz recibiera archivos de voz en formato .wav o .mp3, luego los transcribía a texto utilizando la API de reconocimiento de voz de Google (recognize_google). La transcripción resultante se muestra en la interfaz, lo que permite al usuario ver la versión textual del archivo de voz.

Además, se integraron las API de OpenAI para realizar tareas avanzadas de procesamiento de lenguaje natural. A través de OpenAI, se llevó a cabo la generación de resúmenes a partir del texto transcrito. La función de resumen utiliza el modelo text-davinci-003 para crear un breve resumen de las primeras líneas del texto transcrito. Este resumen se presenta en la interfaz para ofrecer al usuario una visión general del contenido del archivo de voz.

Para la evaluación del sentimiento del texto transcrito, se utilizó la librería transformers para crear un pipeline de análisis de sentimientos pipeline("sentiment-analysis") . Este análisis permitió identificar el sentimiento presente en el texto junto con su puntaje de confianza. Los resultados se muestran en la interfaz para proporcionar una comprensión rápida del tono emocional del texto.

En resumen, el código implementado integró diferentes APIs y librerías, incluyendo speech_recognition para transcripción de voz, y la API de OpenAI para generar resúmenes, analizar sentimientos y, en un intento, traducir el texto transcrito a varios idiomas. Estas integraciones ofrecen una experiencia interactiva y funcional dentro de la interfaz Streamlit.

Personalmente, durante el desarrollo de este proyecto y el curso, reflexioné sobre la complejidad, que a veces ignoramos, del lenguaje humano y cómo hacerle entender a una “computadora” o más bien un sistema no es un reto fácil. El entendimiento de cómo funcionan los modelos de procesamiento de lenguaje no sólo es esencial para proyectos de IA, sino que además resulta muy interesante y crucial en la era actual donde existen modelos comerciales de gran uso como OpenAI. Conocer su funcionamiento y saber cómo utilizar sus APIs es sin duda una competencia fundamental en el campo tecnológico actual.

