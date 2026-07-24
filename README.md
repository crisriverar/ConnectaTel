# Analysis-ConnectaTel

Este repositorio contiene el análisis realizado para **ConnectaTel**, una empresa de telecomunicaciones con operaciones en México y Colombia.

## 📂 Contenido del repositorio

**Notebook principal**
- `ConnectaTel.ipynb` → contiene la limpieza de datos, análisis exploratorio (EDA), distribuciones, detección de outliers y conclusiones.

**Fuentes de datos**
- `plans.csv` → planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- `users_latam.csv` → información de clientes (edad, ciudad, fecha de registro, plan contratado).
- `usage.csv` → detalle de uso real: llamadas (duración) y mensajes (longitud).

## 🧠 Objetivo del análisis

- Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
- Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
- Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
- Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.

## ▶️ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK_EN_GITHUB)]

O de forma manual:
1. Abre el archivo `.ipynb` en GitHub.
2. Haz clic en **Open in Colab**.

## 📘 Cómo reproducir el análisis

1. Abre `ConnectaTel.ipynb`.
2. Ejecuta las celdas en orden.
3. El notebook carga automáticamente el dataset desde `/data/`.
