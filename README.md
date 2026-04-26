#  Análisis de Datos - Airbnb New York City

##  Fase 1: Comprensión del Problema

###  Contexto

Este proyecto se basa en un dataset de la plataforma Airbnb, que describe la actividad de alojamientos en New York City.

El dataset incluye información relevante como:

* Precio de los alojamientos (`price`)
* Ubicación (`neighbourhood_group`, `neighbourhood`)
* Tipo de habitación (`room_type`)
* Reseñas (`number_of_reviews`, `reviews_per_month`)
* Disponibilidad (`availability_365`)

El objetivo es analizar el comportamiento del mercado de alquileres turísticos y entender los factores que influyen en su dinámica.

Puedes consultar el dataset aquí:  
[Airbnb NYC Dataset](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata?resource=download)

---

###  Problema de Análisis

Identificar los factores que influyen en el precio, la disponibilidad y la demanda de los alojamientos en Nueva York, con el fin de generar insights que permitan mejorar la rentabilidad y competitividad de los anfitriones.

---

###  Preguntas Clave

1. ¿Existen diferencias significativas en el precio según la zona (`neighbourhood_group`)?
2. ¿El tipo de habitación (`room_type`) influye en el precio y la demanda?
3. ¿Existe relación entre el número de reseñas (`number_of_reviews`) y el precio?
4. ¿Qué zonas presentan mayor disponibilidad y menor ocupación?

---

##  Fase 2: Formulación de Hipótesis

###  Hipótesis 1: Precio vs Ubicación

* **H0:** No existen diferencias significativas en el precio entre zonas
* **H1:** Sí existen diferencias significativas en el precio entre zonas

**Variables:**

* Independiente: `neighbourhood_group`
* Dependiente: `price`


###  Hipótesis 2: Reviews vs Precio

* **H0:** No existe relación entre el número de reseñas y el precio
* **H1:** Existe relación entre el número de reseñas y el precio

**Variables:**

* `number_of_reviews`
* `price`

**Test estadístico:** Correlación de Pearson

---

###  Justificación

* El precio es el principal indicador de rentabilidad.
* Las reseñas reflejan la demanda y la confianza de los usuarios.
* La ubicación es un factor determinante en el mercado turístico.

Estas hipótesis permiten validar patrones clave dentro del comportamiento del mercado.

---

