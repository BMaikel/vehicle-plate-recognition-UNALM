# 🔍 Reconocimiento Automático de Placas Vehiculares - UNALM
<p align="center">
  <img src="https://ozeki.hu/attachments/5857/number-plate-recognition-system.png" alt="Reconocimiento de Placas Vehiculares" style="width:100%;"/>
</p>

Este proyecto fue desarrollado para el curso de **Ciencia de Datos II**, a cargo del profesor **Aldo R. Meza R.**, en la **Universidad Nacional Agraria La Molina (UNALM)**. Implementa un sistema de reconocimiento automático de **números de placas vehiculares** utilizando técnicas de visión por computador y OCR.

## 📌 Descripción

El sistema detecta la placa en imágenes de vehículos y luego extrae el número usando herramientas de reconocimiento óptico de caracteres (OCR). Se implementaron dos versiones del sistema:

### 🔧 Versión 1 - Modelo Local
- **Detección de Placas**: YOLOv11n
- **OCR**:
  - [`PyTesseract`](https://github.com/madmaze/pytesseract)
  - [`EasyOCR`](https://github.com/JaidedAI/EasyOCR)

> ⚠️ Resultados limitados en precisión, especialmente con placas en condiciones desfavorables (ángulos, sombras o resoluciones bajas).

### ☁️ Versión 2 - Precisión Mejorada con Servicios en la Nube
- **Detección**: YOLOv11n
- **OCR Mejorado**: [`Google Cloud Vision API`](https://cloud.google.com/vision)

> ✅ Excelente precisión y robustez en diferentes condiciones de iluminación y calidad de imagen.

---

## 🖼️ Ejemplo de Flujo

1. 📷 Captura de imagen o vdeo del vehículo  
2. 🟥 Detección de la placa (YOLO)  
3. 🔡 Lectura del número de placa (OCR)  
4. 📋 Visualización y almacenamiento del resultado

---

## 🚀 Tecnologías Usadas

- Python 3.13.0  
- YOLOv11n  
- PyTesseract  
- EasyOCR  
- Google Cloud Vision API  
- OpenCV  

---

## 🏫 Universidad

**Universidad Nacional Agraria La Molina (UNALM)**  
Facultad de Economía y Planificación - Departamento de Estadística Informática

---

## 👨‍💻 Autores

- [Michael A. Bañares G.](https://github.com/BMaikel)
- [Jhordy A. Castro Fernandez]()
- [Elvis Herrera Mendoza]()
- [Leonardo ...]

---

## 📚 Citación

Si este proyecto te fue útil, por favor cítalo así:

> Tu Nombre. (2025). *Reconocimiento Automático de Placas Vehiculares - UNALM*. GitHub. https://github.com/BMaikel/vehicle-plate-recognition-UNALM

---

## 🌐 Enlace al Proyecto

🔗 [Repositorio en GitHub](https://github.com/BMaikel/vehicle-plate-recognition-UNALM)
