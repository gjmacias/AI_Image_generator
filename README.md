# AI_Image_generator - gjmacias
El generador de imágenes de inteligencia artificial (AI Image Generator) emplea el modelo DALL-E 3 desarrollado por OpenAI. Es un modelo de aprendizaje profundo entrenado para generar imágenes creativas a partir de descripciones textuales, conocido como "Generative Pre-trained Transformer" (GPT).

### Indice
* [¿Que es AI_Image_generator?](#que-es-AI_Image_generator)
* [Que utilizamos?](#que-utilizamos)
* [Como funciona?](#como-funciona)

### ¿Que es AI_Image_generator?
 Utiliza la arquitectura de transformer y está preentrenado para entender y generar imágenes a partir de descripciones textuales.

Prompt de Descripción: La aplicación toma una descripción textual como entrada, proporcionada por el usuario. Esta descripción actúa como un "prompt" que guía al modelo en la generación de imágenes.

Generación de Imágenes: La solicitud y el prompt se envían a la API de OpenAI mediante solicitudes HTTP. DALL-E 3 procesa esta información y devuelve una URL que apunta a la imagen generada.

Descarga y Visualización: La aplicación descarga la imagen generada y la muestra en la interfaz de usuario utilizando Streamlit. También proporciona la opción de descargar la imagen generada.

### Que utilizamos?
En nuestro **AI_Image_generator** tenemos las siguentes librerias externas:

| imports  | Descripción								 	|
|-------|-----------------------------------------------------------------------------------|
| Requests | solicita información o, envia una acción, a un servidor web utilizando el protocolo HTTP		|
| Streamlit | Crea aplicaciones web interactivas para el desarrollo ágil de prototipos y aplicaciones simples.	|

### Como funciona?

**Para compilar el programa seguimos los siguientes pasos:**

Verifica que tienes Python instalado ejecutando el siguiente comando:

	python --version
Si no tienes Python instalado, descárgalo e instálalo desde: https://www.python.org/

Verifica que tienes "pip" instalado ejecutando el siguiente comando:

	pip --version
Si no tienes "pip", instálalo siguiendo las instrucciones en https://pip.pypa.io/en/stable/installation/

Clona el repositorio desde GitHub:

	git clone https://github.com/gjmacias/AI_Image_generator/
	cd AI_Image_generator
Instala las bibliotecas necesarias utilizando "pip":

	pip install -r requirements.txt
Finalmente, ejecuta la aplicación Streamlit:

	streamlit run ImageGenerator.py
Esto abrirá tu navegador web con la aplicación Image Generator en ejecución.

¡Listo! Ahora deberías tener la aplicación funcionando localmente en tu máquina.

# Quizás pueda interesarte!

### - Para ver mi progresion en 42 🌠
[AQUÍ](https://github.com/gjmacias/42BCN)

### - Mis proyectos personales 🧐
[AQUÍ🗒️](https://github.com/gjmacias/autoproyectos)

# Contacto 📥

◦ Email: gmacias-@student.42barcelona.com
