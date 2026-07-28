# Analisis-ConnectaTel

Este repositorio contiene el análisis realizado para **ConnectaTel**, una empresa de telecomunicaciones con operaciones en México y Colombia.

## Contenido del repositorio

**Notebook principal**
- `ConnectaTel.ipynb` → contiene la limpieza de datos, análisis exploratorio (EDA), distribuciones, detección de outliers y conclusiones.

**Fuentes de datos**
- `plans.csv` → planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- `users_latam.csv` → información de clientes (edad, ciudad, fecha de registro, plan contratado).
- `usage.csv` → detalle de uso real: llamadas (duración) y mensajes (longitud).

## Objetivo del análisis

- Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
- Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
- Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
- Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.

## Conclusiones y recomendaciones

El análisis muestra que el segmento de adultos concentra el mayor nivel de uso del servicio, lo que sugiere que este grupo representa uno de los principales clientes potenciales para campañas orientadas a la migración hacia planes premium. Su nivel de actividad indica una mayor dependencia del servicio, lo que aumenta la probabilidad de adopción de planes con mayores beneficios.
Aunque el segmento de adultos mayores representa aproximadamente la mitad del tamaño del grupo de adultos, continúa siendo un segmento relevante. En muchos casos, estos usuarios pueden contar con mayor estabilidad económica, por lo que desarrollar estrategias de fidelización y propuestas de valor orientadas a planes premium podría resultar efectivo para incrementar su contribución al ingreso.

El segmento de uso medio agrupa a los clientes con un consumo regular del servicio, representando el comportamiento típico de la mayoría de los usuarios.
El bajo nivel de uso observado en el segmento joven podría estar influenciado por una limitación en las variables analizadas. En este caso, el análisis se centra en llamadas y mensajes, sin considerar el consumo de datos móviles, que suele ser el principal canal de comunicación en usuarios más jóvenes. Esto podría estar generando una subestimación del nivel real de uso en este grupo.

Si la compañía ofrece servicios de datos móviles, incorporar esta variable al dataset sería clave para comprender con mayor precisión el comportamiento del segmento joven, que probablemente concentra una parte significativa de su actividad en el uso de internet.

Los outliers identificados en el análisis de uso sugieren la existencia de un pequeño grupo de usuarios con consumo significativamente superior al promedio. Este segmento podría representar una oportunidad para diseñar planes diferenciados o categorías premium (por ejemplo, planes VIP) orientados a clientes de alto consumo.
Desde una perspectiva estratégica, puede resultar más rentable incentivar la migración de usuarios actuales hacia planes premium que concentrar esfuerzos exclusivamente en la adquisición de nuevos clientes. Estrategias de upselling y personalización de planes podrían aumentar el ingreso promedio por usuario (ARPU) y mejorar la rentabilidad del servicio.

## Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

https://colab.research.google.com/github/crisriverar/ConnectaTel/blob/main/ConnectaTel.ipynb

O de forma manual:
1. Abre el archivo `.ipynb` en GitHub.
2. Haz clic en **Open in Colab**.

## Cómo reproducir el análisis

1. Abre `ConnectaTel.ipynb`.
2. Ejecuta las celdas en orden.
3. El notebook carga automáticamente el dataset desde `/data/`.
