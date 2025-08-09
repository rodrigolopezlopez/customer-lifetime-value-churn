# Customer Lifetime Value & Churn Analysis

Este proyecto analiza el comportamiento de los conductores de una plataforma de transporte para comprender el **Valor de por Vida del Cliente (LTV)** y la **tasa de abandono (churn)** de los conductores.

---

### **🎯 Key Highlights & Project Overview**

Este análisis se centra en extraer **insights clave** sobre el comportamiento de los conductores. Los hallazgos más importantes incluyen:

* **Driver LTV**: Cada nuevo conductor se estima que genera **$132 USD** en ganancias para la plataforma antes de abandonarla. Este cálculo se basa en un viaje promedio de $13.84, **48 viajes por conductor** y una división de ganancias del 20% para la plataforma.
* **Churn Rate**: Aproximadamente el **16.54%** de los conductores abandonan la plataforma, con una permanencia promedio de **43 días**. Los conductores que se dan de baja suelen mostrar una **tendencia negativa** en su actividad de viajes semanales antes de irse.
* **Driver Engagement**: La mayoría de los conductores son **ocasionales** (menos de 20 viajes/semana) o de **medio tiempo** (20-40 viajes/semana). Existe una fuerte correlación entre una **menor participación** y una **mayor tasa de abandono**, lo que indica una oportunidad significativa para aumentar los viajes generales mejorando la participación de los conductores existentes.

---

### **🛠️ Technical Approach**

#### **Análisis y Metodología**

* **Datos**: Se utilizaron datos de conductores y viajes que incluyen sellos de tiempo (**timestamps**), distancia, duración y "**prime time**".
* **Metodología**: El proceso de análisis incluyó limpieza de datos, **cálculo del LTV**, identificación del **churn** (definido como **28 días de inactividad**) y **segmentación** de los conductores por el promedio de viajes semanales.
* **Herramientas**: El proyecto se implementó utilizando **Python** (con las bibliotecas **Pandas**, **Matplotlib** y **Seaborn**).

---

### **📈 Future Work**

El análisis inicial proporciona una base sólida, pero el trabajo futuro se centrará en las siguientes áreas para obtener una visión más completa:

* **Análisis de Datos a Largo Plazo**: Analizar períodos de datos más largos para obtener **tendencias más precisas** de LTV y churn.
* **Modelos Predictivos**: Desarrollar **modelos predictivos** para anticipar el churn y optimizar los programas de incentivos para los conductores.

---

### **Relevant Graphs**

<div align="center">
  <img src="https://github.com/user-attachments/assets/ca61d661-0f5d-4df1-b74c-95318982d226" alt="Graph 1" width="32%" />
  <img src="https://github.com/user-attachments/assets/3e16266b-8592-4ab5-a89c-9c43fb568f2b" alt="Graph 2" width="32%" />
  <img src="https://github.com/user-attachments/assets/7dfd2452-79c4-49c7-ad6f-06ad8152a9d4" alt="Graph 3" width="32%" />
</div>
