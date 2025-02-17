👕 Generación de Imágenes con GANs en Google Colab

📌 Descripción:
Este proyecto ha sido desarrollado en Google Colab con el objetivo de entrenar una GAN (Generative Adversarial Network) para la generación de imágenes de ropa. La imagen anterior representa los resultados obtenidos en la época 10 del entrenamiento, donde el modelo ya empieza a capturar algunos detalles de las prendas.

![image](https://github.com/user-attachments/assets/0f442194-d7d0-4906-a844-4ffe35e71fdb)


🚀 Tecnologías Utilizadas

Google Colab: Plataforma utilizada para entrenar el modelo de manera eficiente en GPU.

TensorFlow / Keras: Framework principal para la implementación de la GAN.

Fashion-MNIST: Conjunto de datos utilizado para el entrenamiento.

Matplotlib: Visualización de las imágenes generadas en cada época.

NumPy y Pandas: Manejo de datos y operaciones matriciales.

📂 Estructura del Proyecto

📁 GAN_Fashion_MNIST
 ├── 📄 GAN_prendas_López_Muñoz_Carlos.ipynb  # Notebook principal
 ├── 📁 datasets/                             # Datos de entrenamiento
 ├── 📁 images/                               # Imágenes generadas en cada época
 └── 📄 README.md                             # Este archivo

🏗️ Arquitectura de la GAN

Este modelo utiliza una Red Generativa Antagónica (GAN) con dos componentes principales:

Generador 🏗️: Red neuronal que toma ruido aleatorio como entrada y genera imágenes similares a las del dataset de Fashion-MNIST.

Discriminador 🧐: Red neuronal que evalúa si una imagen es real (del dataset) o generada por el modelo.

Ambas redes se entrenan en un proceso de competencia, donde el generador intenta engañar al discriminador y este último intenta mejorar en la detección de imágenes falsas.

🔥 Entrenamiento

El modelo fue entrenado con redes neuronales convolucionales en el generador y discriminador. A lo largo de las épocas, la calidad de las imágenes mejoró progresivamente, como se observa en la imagen anterior. Cada vez que se completa una época, las imágenes generadas son guardadas en local en la carpeta images/.

📊 Progreso del Entrenamiento

✅ Época 1: Ruido sin forma reconocible.✅ Época 5: Se empiezan a notar algunas estructuras.✅ Época 9: Las imágenes ya tienen cierta similitud con prendas reales (ver imagen).✅ Época 20+: Generaciones más nítidas y detalladas.

📌 Cómo Ejecutar el Proyecto

Abrir el notebook en Google Colab.

Ejecutar todas las celdas para entrenar la GAN.

Explorar las imágenes generadas en la carpeta images/.

🎯 Conclusión

Este proyecto demuestra el poder de las GANs para generar imágenes de ropa de manera realista. A medida que el entrenamiento avanza, la calidad mejora significativamente. Cada imagen generada se almacena para su análisis y comparación con versiones anteriores. ¡Esperamos seguir explorando más mejoras en el futuro! 🚀

📩 Para más información o sugerencias, ¡contáctame! 😃

⚠️ Notas : 

Recalcar que el modelo esta entrenado con 10 epoca porque mi ordenador no es capaz de entrenar más rápido. 

![image](https://github.com/user-attachments/assets/c367d0cf-93dd-43d8-9837-2ca88e658777)
