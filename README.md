# Análisis de Datos con IA – Agentes y Automatización en Google Sheets

Este repositorio contiene dos proyectos orientados al análisis de datos con inteligencia artificial, usando agentes configurados en entornos distintos:

---

## 📁 Contenido

### `C1_crearAgente_Lmeza`

Este proyecto muestra la creación de un agente de análisis de datos, denominado `Agente_C1`, cuyo propósito es:

- Sugerir formas de limpiar, transformar y estandarizar un conjunto de datos.
- Realizar un Análisis Exploratorio de Datos (EDA).
- Generar un mapa de calor de correlación para analizar relaciones entre variables.

#### 🧠 Funcionalidades del Agente:
- Corrección y estandarización de columnas específicas (como duración de películas, respuestas en mayúsculas, etc.).
- Eliminación de columnas irrelevantes por solicitud del usuario.
- Visualización de:
  - Distribución de edades (gráfico de histograma).
  - Correlación entre variables numéricas (mapa de calor con Seaborn y Matplotlib).
- Uso de Python y bibliotecas como `pandas`, `matplotlib`, `seaborn`.

#### 📂 Archivos Generados:
- Código en Python embebido.
- Resultados gráficos del análisis.

---

### `C2_ai_analisis_en_sheet`

Este segundo proyecto consiste en la integración de la API de OpenAI dentro de Google Sheets mediante Google Apps Script. Se diseñan funciones para automatizar análisis simples directamente desde la hoja de cálculo.

#### ⚙️ Funcionalidades:
- **`Agente(prompt)`**: Ejecuta un `prompt` de texto contra la API de OpenAI y devuelve la respuesta en la celda.
- **`contarValorEnColumna(columna, valor)`**: Cuenta cuántas veces aparece un valor específico en una columna dada.
- **`contarYAnalizar(columna, valor)`**: Combina el conteo con un análisis generado por la IA para obtener una conclusión textual.

#### 💡 Uso práctico:
- Automatiza insights rápidos sobre datos en Google Sheets sin salir del entorno.
- Ideal para usuarios no técnicos que desean aprovechar el poder de la IA para análisis descriptivo.

---

## 🔧 Requisitos

- Python (para `C1`)
  - `pandas`
  - `matplotlib`
  - `seaborn`
- Cuenta de Google y acceso a Google Apps Script (para `C2`)
- API Key de OpenAI válida (para ambos proyectos si se desea ampliar)

---

### `2daevaluacon`

Este archivo se juntan las evidencias de los proyectos 3, 4 y 5.

- proyecto 3 Uso de la IA en PowerBI
- proyecto 4 Uso de IA en la creación de archivos Multimedia
- proyecto 5 Uso de Ia para front end


## ✍️ Autor

Luis Meza  
Proyectos académicos sobre análisis de datos e inteligencia artificial con enfoque práctico y pedagógico.

