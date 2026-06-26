#  JustIA - MVP de Clasificación Automática de Consultas Jurídicas

##  Descripción

Este proyecto corresponde al desarrollo de un **Producto Mínimo Viable (MVP)** para el caso **JustIA**, un consultorio jurídico virtual que busca apoyar la clasificación automática de consultas jurídicas mediante técnicas de **Procesamiento de Lenguaje Natural (NLP)** y **Machine Learning**.

El sistema recibe una consulta escrita en lenguaje natural y predice automáticamente el área del derecho a la que pertenece.

El objetivo del proyecto es demostrar cómo la Inteligencia Artificial puede apoyar la organización inicial de consultas jurídicas, sin reemplazar el criterio profesional de un abogado.

---

#  Objetivos

- Implementar un modelo de clasificación automática de consultas jurídicas.
- Aplicar técnicas de Procesamiento de Lenguaje Natural (NLP).
- Evaluar el desempeño del modelo utilizando métricas de clasificación.
- Promover el uso responsable y ético de la Inteligencia Artificial en el ámbito jurídico.

---

#  Categorías jurídicas

El modelo clasifica consultas en las siguientes categorías:

- Laboral
- Civil
- Penal
- Familia
- Comercial

---

#  Tecnologías utilizadas

- Python 3.14
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

#  Modelo de Machine Learning

El sistema utiliza dos componentes principales:

## TF-IDF (Term Frequency - Inverse Document Frequency)

Se emplea para transformar las consultas escritas en lenguaje natural en vectores numéricos que puedan ser procesados por el algoritmo de clasificación.

## Logistic Regression

Se utiliza como algoritmo de clasificación supervisada para predecir la categoría jurídica correspondiente a cada consulta.

---

#  Estructura del proyecto

```
justia-mvp/
│
├── justia_clasificador.ipynb
├── README.md
└── requirements.txt
```

---

#  Instalación

## 1. Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/justia-mvp.git
```

Entrar al proyecto

```bash
cd justia-mvp
```

---

## 2. Crear entorno virtual (Opcional)

Windows

```bash
python -m venv .venv
```

Activar

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv .venv
```

```bash
source .venv/bin/activate
```

---

## 3. Instalar dependencias

```bash
pip install pandas numpy scikit-learn matplotlib notebook
```

o utilizando requirements.txt

```bash
pip install -r requirements.txt
```

---

# ▶ Ejecución

Iniciar Jupyter Notebook

```bash
jupyter notebook
```

Abrir

```
justia_clasificador.ipynb
```

Ejecutar todas las celdas en orden.

---

#  Funcionalidades implementadas

- Creación de un dataset jurídico sintético.
- Transformación de texto mediante TF-IDF.
- Entrenamiento del modelo Logistic Regression.
- Evaluación mediante Accuracy.
- Classification Report.
- Matriz de Confusión.
- Gráfico de distribución de categorías.
- Clasificación automática de nuevas consultas.
- Análisis de probabilidades por categoría.
- Función reutilizable para clasificar consultas.
- Consideraciones éticas del sistema.

---

#  Resultados

El modelo obtuvo una precisión del **100%** sobre el conjunto de prueba.

Este resultado corresponde a un conjunto de datos sintético y reducido utilizado únicamente para fines académicos.

---

#  Consideraciones éticas

Este sistema constituye un apoyo para la clasificación inicial de consultas jurídicas.

No reemplaza el análisis, interpretación ni la toma de decisiones de un profesional del derecho.

Toda recomendación generada por el modelo debe ser revisada por un abogado antes de ser utilizada en un contexto real.

---

#  Mejoras futuras

- Incorporar miles de consultas jurídicas reales.
- Implementar modelos basados en Transformers (BERT Legal).
- Integrar una interfaz web mediante Streamlit.
- Exponer el modelo mediante una API REST con FastAPI.
- Incorporar explicación de predicciones mediante SHAP o LIME.
- Integrar autenticación y gestión de usuarios.

---

#  Autor

**David Carrasco**

Especialización en Desarrollo de Software

Proyecto desarrollado para el caso de estudio **JustIA**.