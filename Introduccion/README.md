# 🖼️ Conversor a Escala de Grises

Aplicación de escritorio sencilla en **Python** usando **PySide6 (Qt)** y **Pillow (PIL)** que permite:

- Cargar imágenes desde el explorador de archivos.
- Convertirlas a escala de grises.
- Guardar el resultado en formato PNG, JPG o BMP.

---

## 🚀 Requisitos

- Python 3.10 o superior (probado en 3.13).
- Entorno virtual recomendado (`venv`).

---

## ⚙️ Instalación

1. Clonar este repositorio o descargar el proyecto.

```bash
git clone https://github.com/KalanOne/VisionArtificial.git
cd VisionArtificial
cd Introduccion
````

2. Crear y activar un entorno virtual:

   ```bash
   python -m venv .venv
   # En Windows (PowerShell)
   .\.venv\Scripts\activate
   # En Linux/Mac
   source .venv/bin/activate
   ```

3. Instalar dependencias necesarias:

   ```bash
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

4. (Opcional) Registrar el kernel en Jupyter Notebook o JupyterLab:

   ```bash
   python -m ipykernel install --user --name=venv-introduccion --display-name "Python (Introduccion .venv)"
   ```

---

## ▶️ Uso

Ejecuta el notebook principal:

1. Abre **Jupyter Notebook** o **JupyterLab**:

```bash
jupyter lab      # o jupyter notebook
````

2. Navega a la carpeta del proyecto y abre `app.ipynb`.
3. Ejecuta las celdas del notebook siguiendo los pasos de la aplicación.
4. En la celda que crea la ventana:

   * Haz clic en **Abrir** para cargar una imagen.
   * Haz clic en **Convertir a gris** para transformarla.
   * Haz clic en **Guardar** para exportar la imagen convertida.

---

## 📂 Estructura del proyecto

```
.
├── app.ipynb            # Notebook principal con la aplicación
├── README.md            # Este archivo
└── requirements.txt     # Dependencias del proyecto
```


---

📌 Notas importantes para Jupyter:  

- Asegúrate de que el kernel del notebook esté usando el **.venv** correcto donde instalaste `pyside6`, `pillow` e `ipykernel`.  
- Si no aparece tu entorno en el menú de kernels, ejecuta:
```bash
python -m ipykernel install --user --name=venv-introduccion --display-name "Python (Introduccion .venv)"
````

---

## 📦 Generar `requirements.txt`

Para exportar las librerías instaladas en el entorno virtual:

```bash
pip freeze > requirements.txt
```

Para instalar dependencias en otro equipo:

```bash
pip install -r requirements.txt
```

---

## 📝 Notas

* Proyecto académico de **Visión Artificial**.
* Compatible con Windows, Linux y macOS.
* Puedes ejecutar también en Jupyter Notebook, pero se recomienda correrlo desde consola.