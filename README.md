# TFG Javier Collado

Este repositorio contiene el código fuente y la documentación del Trabajo de Fin de Grado titulado **"Predicción de la posición final de pilotos en carreras de Fórmula 1 mediante técnicas de aprendizaje automático"**. El proyecto se centra en el preprocesamiento, análisis exploratorio y modelado de datos utilizando técnicas de aprendizaje automático.

## Contenido del proyecto

### 1. **Preprocesamiento de datos**
- Limpieza, normalización y preparación del conjunto de datos.
- Creación de diccionarios para describir las variables presentes.

### 2. **Análisis exploratorio**
- Generación de histogramas para cada característica numérica del conjunto de datos.
- Identificación de patrones, valores atípicos y distribuciones no uniformes.
- Los histogramas generados se encuentran en la carpeta `images`.

### 3. **Modelos de aprendizaje automático**
- Implementación de regresores: lineal, Ridge, Lasso, Kernel Ridge y Random Forest.
- Implementación de clasificadores: Random Forest, CNN y MLP.
- Ajuste de hiperparámetros mediante validación cruzada.
- Evaluación de los modelos en conjuntos de datos de prueba.

### 4. **Exportación de resultados**
- Generación de gráficos y métricas de evaluación.
- Exportación de resultados a formato CSV.

## Cómo usar este repositorio

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/j19co/TFG_JavierCollado.git

2. **Instalar las dependencias necesarias:**
   	- Python 3.8 o superior.
	- Bibliotecas: pandas, matplotlib, tensorflow, scikit-learn.

3. **Ejecutar los scripts:**
	- Los histogramas se generan ejecutando el archivo principal del proyecto (TFG_JavierCollado_F1.ipynb).
	- Los resultados se guardan automáticamente en la carpeta images. 

Estructura del repositorio:
TFG_JavierCollado_F1.ipynb: Notebook principal con el desarrollo del proyecto.
images/: Carpeta que contiene los histogramas generados.
F1_DATA/: Conjunto de datos utilizado en el proyecto (si aplica).

Contacto:
Para cualquier consulta, puedes contactar conmigo en j19orellana@gmail.com .
