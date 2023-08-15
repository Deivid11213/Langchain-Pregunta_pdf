# Langchain-Pregunta_pdf
Esta es una aplicación de Python que le permite cargar un PDF y hacer preguntas al respecto usando lenguaje natural. La aplicación utiliza un LLM para generar una respuesta sobre su PDF. El LLM no responderá preguntas no relacionadas con el documento.

# Como Funciona
La aplicación lee el PDF y divide el texto en fragmentos más pequeños que luego se pueden introducir en un LLM. Utiliza incrustaciones de OpenAI para crear representaciones vectoriales de los fragmentos. Luego, la aplicación encuentra los fragmentos que son semánticamente similares a la pregunta que hizo el usuario y envía esos fragmentos al LLM para generar una respuesta.

La aplicación utiliza Streamlit para crear la GUI y Langchain para gestionar el LLM.

# Instalación

Para instalar el repositorio, clone este repositorio e instale los requisitos:

pip install -r requirements.txt

También deberá agregar su clave API de OpenAI al .envarchivo.

# Uso
streamlit run app.py

# contribuyendo
Este repositorio es solo para fines educativos y no está destinado a recibir más contribuciones. Se supone que debe usarse como material de apoyo para el tutorial de YouTube que muestra cómo construir el proyecto.

