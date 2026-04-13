# 📊 Finanzas: Riesgo Operacional y Modelización Cuantitativa

![Status](https://img.shields.io/badge/Estado-Activo-success)
![Audiencia](https://img.shields.io/badge/Audiencia-Ingeniería_Matemática_(CEU)-blue)
![Industria](https://img.shields.io/badge/Aplicación-Banca_y_Gestión_de_Capital-purple)

Bienvenido al repositorio oficial del submódulo de **Riesgo Operacional**, impartido dentro del programa de Modelación Cuantitativa de Riesgo en el CEU.

La industria financiera pierde miles de millones anualmente por fallos en sistemas, fraudes y errores de ejecución. Este submódulo abandona los enfoques cualitativos tradicionales para abordar el Riesgo Operacional como un problema puramente cuantitativo y actuarial. El objetivo es transformar eventos aislados en **inteligencia de negocio accionable**, calculando con precisión el capital regulatorio necesario mediante el Enfoque de Distribución de Pérdidas (LDA).

---

## 🎯 Arquitectura del Módulo

Este es un *sprint* técnico de **4 horas cronológicas** diseñado para modelar eventos extremos (cola pesada). La estructura didáctica se centra en:

* **Ingeniería de Datos Operacionales:** Estrategias para la recolección, limpieza y homogenización de bases de datos de pérdidas internas y externas.
* **Modelación Actuarial:** Calibración algorítmica de distribuciones de frecuencia y severidad.
* **Simulación a Escala:** Despliegue de motores Monte Carlo para la convolución de distribuciones y cálculo del Valor en Riesgo Operacional (OpVaR).

### 📚 Contenido Público (Material de Clase)

En este nivel de acceso se expone el marco teórico y la arquitectura regulatoria requerida para estructurar el modelo estadístico:

#### TEMA 10: Modelización del Riesgo Operacional
* `10.1` Taxonomía y regulación: Definición y categorización de eventos de pérdida según los comités de Basilea.
* `10.2` Arquitectura de datos: 
    * Protocolos de recopilación de eventos de pérdida interna.
    * Integración de bases de datos externas (consorcios) y escalado de datos.
    * Cuantificación de *expert judgment* a través de análisis de escenarios.
* `10.3` El Enfoque de Distribución de Pérdidas (LDA): 
    * Modelización de la Frecuencia (Procesos de Poisson).
    * Modelización de la Severidad (Ajuste de distribuciones de colas pesadas: Lognormal, Weibull, Teoría de Valores Extremos).
* `10.4` Agregación y Capital: Convolución de distribuciones de frecuencia y severidad mediante Simulación de Monte Carlo para la asignación óptima de capital.

---

## 🔐 Acceso a Entorno de Modelación (Python)

Calibrar distribuciones de cola pesada y ejecutar convoluciones estocásticas requiere *pipelines* de datos robustos, lejos de las limitaciones de las hojas de cálculo convencionales. Para proteger la integridad del código fuente desarrollado, este material reside en un repositorio privado.

El entorno restringido proporciona:
* Scripts de Python (`scipy.stats`, `numpy`) para el ajuste automático de curvas de severidad (*Maximum Likelihood Estimation*).
* Motores de Simulación Monte Carlo vectorizados para la agregación rápida de millones de trayectorias de pérdida.
* Algoritmos para la integración de datos externos y ponderación de escenarios.

📩 **Para Alumnos y Académicos CEU:** Solicite acceso al código enviando su usuario de GitHub a **carr8824@gmail.com** (sujeto a validación de matrícula).

---

## 💼 Consultoría Institucional y Optimización de Capital

Gestionar el riesgo operacional de manera ineficiente inmoviliza capital regulatorio que debería estar generando retornos. Las arquitecturas LDA detalladas en este módulo están diseñadas para escalar a nivel *Enterprise*.

Como profesional cuantitativo (Ph.D., Ingeniero de Machine Learning), ofrezco servicios de consultoría estratégica para:
* Auditoría y automatización técnica de departamentos de Riesgo Operacional.
* Migración de matrices cualitativas (Excel) a modelos estadísticos LDA programados en Python.
* Optimización de capital regulatorio mediante la demostración de modelos internos robustos ante organismos supervisores.

📩 **Contacto Corporativo:** Para modernizar la infraestructura analítica de su institución y reducir la carga de capital por riesgo operacional, contácteme en **carr8824@gmail.com**.