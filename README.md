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

- **Dispositivo:** DESKTOP-P7P6BN9  
- **Procesador:** AMD Ryzen 7 5800H with Radeon Graphics @ 3.20 GHz  
- **RAM instalada:** 16 GB (15.4 GB utilizable)  
- **Sistema operativo:** Windows 10 - 64 bits (procesador x64)  
- **Almacenamiento disponible:** 1.38 TB  
- **Pantalla:** Sin soporte táctil

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

## ⚙️ Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/Gusva26/SOFTWARE---HOJA-DE-MAIZ.git
cd SOFTWARE---HOJA-DE-MAIZ


python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
pip install -r requirements.txt


streamlit run app.py
