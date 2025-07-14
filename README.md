# 🌽 SOFTWARE - HOJA DE MAÍZ

Proyecto de aprendizaje automático para la detección y análisis de enfermedades en hojas de maíz mediante redes neuronales y visión por computadora. Entrenado con TensorFlow y desplegado con Streamlit.

---

## 🧠 Tecnologías utilizadas

- **Python**
- **Streamlit** – Para el despliegue web interactivo
- **TensorFlow / Keras** – Para redes neuronales
- **OpenCV** – Procesamiento de imágenes
- **Scikit-learn** – Métricas y modelos auxiliares
- **Matplotlib & Seaborn** – Visualización
- **FPDF** – Generación de reportes PDF

---

## 🖥️ Requisitos del sistema (entorno de desarrollo)

Este software fue desarrollado y probado en el siguiente entorno:

- **Dispositivo:** ASUS TUF GAMING A15  
- **Procesador:** AMD Ryzen 7 5800H “8 núcleos, 16 hilos, 3.2 GHz base / 4.4 GHz turbo”  
- **Tarjeta gráfica:** NVIDIA GeForce RTX 3060 (6GB GDDR6, 1280 CUDA cores)  
- **RAM instalada:** 16 GB DDR4 (3200 MHz) - (15.4 GB utilizable)  
- **Sistema operativo:** Windows 11 Pro - 64 bits (WSL2 para compatibilidad con Docker)
- **Almacenamiento disponible:** SSD NVMe 1TB “lectura: 3500 MB/s, escritura: 3000 MB/s”  
- **Pantalla:** Panel IPS 144hz

> ⚠️ Recomendado: Al menos 8 GB de RAM, GPU con soporte CUDA para entrenamiento acelerado, y entorno Python 3.9+.

---

## 📁 Estructura del proyecto


  ├── data/ # Datos de entrenamiento / prueba
  ├── models/ # Modelos entrenados
  ├── reports/ # Reportes generados en PDF
  ├── app.py # Interfaz principal en Streamlit
  ├── grape_training.ipynb # Notebook de entrenamiento
  ├── Dockerfile # Para ejecución en contenedores
  ├── requirements.txt # Dependencias del proyecto



---

## ⚙️ Descargar y Ejecutar

Ejecute estas líneas:

docker build -t grape-disease-detection .
docker run -p 8501:8501 grape-disease-detection
