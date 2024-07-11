# Chronos 

# SkinDetect

SkinDetect es un programa el cual sirve para predecir un melanoma benigno o maligno según una imagen. Utiliza una estructura de red neuronal.

## Tabla de contenidos

1. [Nombre](#Nombre)
2. [Descripción](#descripción)
3. [Arquitectura](#Arquitectura)
4. [Proceso](#Proceso)
5. [Funcionalidades](#Funcionalidades)
6. [Estado del proyecto](#EstadoDelProyecto)
7. [Agradecimientos](#Agradecimientos)


* Nombre del proyecto:

SkinDetect

* Descripción:
  
SkinDetect es un sistema de inteligencia artificial diseñado para la categorización y predicción de melanomas malignos y benignos a partir de imágenes de la piel. Utilizando la arquitectura InceptionV3 preentrenada, SkinDetect aplica técnicas de transferencia de conocimiento para ofrecer una herramienta precisa y eficiente en el diagnóstico de cáncer de piel.

El modelo se entrena y valida con un conjunto de datos de más de 10,000 imágenes, proporcionando un análisis detallado y resultados confiables. La interfaz de usuario permite cargar imágenes fácilmente y obtener predicciones rápidas, facilitando su uso tanto para profesionales médicos como para investigadores en el campo de la dermatología.
![image](https://github.com/user-attachments/assets/ec606ef7-1391-4dcc-973f-382058bade1f)

* Arquitectura del proyecto 

Modelo Preentrenado: InceptionV3 con capas congeladas.
Capas Adicionales: GlobalAveragePooling2D, Dense (1024 unidades, ReLU), Dropout (0.1), y una capa de salida sigmoide.
Entrenamiento: 9595 imágenes de entrenamiento y 1000 de validación. Compilación con Adam y pérdida binaria. Entrenado durante 15 épocas.
Interfaz de Usuario
Desarrollada con customtkinter, permite cargar imágenes mediante arrastrar y soltar y obtener predicciones instantáneas sobre la malignidad de los melanomas. La interfaz es intuitiva y facilita la interpretación de resultados.

* Proceso de desarrollo:

-Fuente del dataset: 
-Limpieza de datos (img que lo valide)
-Manejo excepciones/control errores
-¿Qué modelo de Machine Learning están usando?
-Estadísticos (Valores, gráficos, …)
-Métrica(s) de evaluación del modelo

* Funcionalidades extra:

Ejem 1: Implementación de chatbot
- Tecnología/Herramientas usadas (Librería, Framework, …)
- Arquitectura (img)
- Indicar fuente del dataset
- Limpieza de datos (ejem: se usó PLN + img que lo validen)
- Manejo excepciones/control errores
- En caso de usar un modelo de ML indicar ¿Qué modelo de Machine Learning están usando?
- Estadísticos (Valores, gráficos, …)
- Métrica(s) de evaluación del modelo

Ejem 2: Integración del proyecto en una pág web
- Tecnología/Herramientas usadas …
- Arquitectura (img)

Ejem 3: Integración del proyecto en un canal WhatsApp, Discord, Telegram, Correo, …
- Tecnología/Herramientas usadas …
- Arquitectura (img)

Ejem 4: Desarrollo de interfaz gráfica de usuario
- Tecnología/Herramientas usadas …
- Arquitectura (img)

Ejem …: …
- Tecnología/Herramientas usadas …
