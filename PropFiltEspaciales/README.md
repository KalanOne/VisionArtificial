# 🖼️ Proyecto: Mejora de la Calidad de Imágenes en Escala de Grises

Este proyecto contiene un conjunto de ejercicios prácticos de **procesamiento digital de imágenes**, aplicando técnicas de mejora, filtrado y análisis estadístico sobre cuatro imágenes de prueba:

- `chest_xray.jpg`  
- `cat.jpg`  
- `forest.jpg`  
- `papyrus.png`

Las imágenes deben ubicarse dentro de la carpeta **`Imagenes/`** para que el notebook funcione correctamente.

---

## ⚙️ Contenido del Proyecto

- `mejorar_imagenes.ipynb` → ✅ **ARCHIVO PRINCIPAL Y CORRECTO.**  
  Contiene todo el desarrollo solicitado: conversión a escala de grises, cálculo de valores mínimo/máximo, normalización, filtros de media, mediana, máximo y mínimo, así como la función `SubMatriz` y un reporte final.

- `mejorar_imagenes_optimizado.ipynb` → ⚠️ **NO USAR.**  
  Versión alternativa o de pruebas que **no debe utilizarse** para la entrega o ejecución oficial.

- Carpeta `Imagenes/` → Contiene las imágenes fuente.  
- Carpeta `Salida_Procesada/` → Se genera automáticamente y almacena las imágenes resultantes.

---

## 🧩 Requisitos

Asegúrate de tener instaladas las siguientes librerías antes de ejecutar el notebook:

```bash
pip install -r requirements.txt
````

---

## ▶️ Ejecución

1. Coloca la carpeta `Imagenes` en el mismo directorio del notebook.
2. Abre el archivo **`mejorar_imagenes.ipynb`** en Jupyter Notebook o VS Code.
3. Ejecuta todas las celdas en orden.
4. Los resultados y las imágenes procesadas se guardarán en `Salida_Procesada/`.

---

## 📄 Descripción Breve

El notebook implementa los siguientes pasos:

1. Conversión de imágenes a escala de grises.
2. Obtención de valores mínimo y máximo de intensidad.
3. Normalización del contraste.
4. Aplicación de filtros: media, mediana, máximo y mínimo.
5. Implementación de la función `SubMatriz(img, (x, y), k)`.
6. Generación de un breve reporte con conclusiones y resultados visuales.

---

## ⚠️ IMPORTANTE

### 🚨 **Usar exclusivamente el archivo `mejorar_imagenes.ipynb`.**

El archivo `mejorar_imagenes_optimizado.ipynb` **NO es válido para evaluación** ni contiene las versiones finales del código ni del reporte.
