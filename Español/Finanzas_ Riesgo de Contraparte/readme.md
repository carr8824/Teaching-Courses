# 📊 Finanzas: Riesgo de Crédito de Contraparte y xVA

![Status](https://img.shields.io/badge/Estado-Activo-success)
![Audiencia](https://img.shields.io/badge/Audiencia-Ingeniería_Matemática_(CEU)-blue)
![Industria](https://img.shields.io/badge/Aplicación-Mesas_de_Dinero_y_Derivados_OTC-purple)

Bienvenido al repositorio oficial del módulo especializado en **Riesgo de Contraparte y Ajustes de Valoración (xVA)**, estructurado para el programa de Modelación Cuantitativa de Riesgo en el CEU.

La valoración tradicional de derivados asume contrapartes libres de riesgo, una falacia que penaliza severamente el capital regulatorio. Este submódulo traduce la teoría estocástica en **inteligencia de negocio accionable**, enseñando a cuantificar el costo real de operar en mercados OTC mediante infraestructuras computacionales eficientes.

---

## 🎯 Arquitectura del Módulo

Este es un módulo intensivo enfocado en resolver uno de los 'puntos de dolor' más costosos (en términos de procesamiento y capital) para la banca de inversión moderna. La metodología aborda:

* **Discusión Estructural:** Diferenciación matemática y operativa entre el riesgo de crédito tradicional y la exposición bidireccional estocástica.
* **Laboratorio de Simulación:** Diseño de motores de Monte Carlo para proyectar la Exposición Futura Potencial (PFE) sin comprometer la eficiencia del sistema.
* **Optimización de Pricing:** Integración de los ajustes xVA directamente en el precio de los instrumentos para proteger el P&L institucional.

### 📚 Contenido Público (Material de Clase)

A continuación, se detalla la estructura teórica del módulo. Las diapositivas y el marco conceptual están disponibles en esta sección:

#### TEMA 8: Riesgo de Contraparte y Ajustes de Valoración (xVA)
* `8.1` Riesgo de crédito de un bono (Unidireccional) vs. Riesgo de Crédito de Contraparte (CCR) en carteras de derivados (Bidireccional).
* `8.2` Construcción de perfiles de exposición: 
    * Modelación de la Exposición Actual (CE).
    * Simulación estocástica de la Exposición Futura Potencial (PFE).
* `8.3` El Ajuste de Valoración de Crédito (CVA): 
    * Definición regulatoria y matemática.
    * Arquitectura de cálculo y estrategias de cobertura dinámica.
* `8.4` Más allá del CVA: Introducción a la gestión integral de xVA:
    * Ajuste de Valoración de Deuda (DVA).
    * Ajuste de Valoración de Fondeo (FVA) y su impacto en la liquidez de la mesa de operaciones.

---

## 🔐 Acceso a Motores de Simulación y Código (Python)

El cálculo de xVA a nivel de cartera exige simulaciones anidadas que representan un desafío computacional severo. Por motivos de propiedad intelectual corporativa y protección de la ventaja competitiva de la arquitectura, los *pipelines* de datos se mantienen en un repositorio privado.

El material restringido incluye:
* Scripts optimizados en Python para la simulación de PFE utilizando trayectorias de Monte Carlo.
* Algoritmos de integración numérica para el cálculo de CVA sobre portafolios de *swaps*.
* Casos de estudio interactivos para optimización de colaterales y *netting*.

📩 **Para Alumnos y Académicos CEU:** Solicite acceso al entorno de ejecución enviando un correo a **carr8824@gmail.com** con su validación académica y usuario de GitHub.

---

## 💼 Arquitectura de Riesgos para Instituciones Financieras

Las soluciones expuestas en este repositorio están diseñadas teniendo en cuenta las restricciones de los sistemas bancarios reales. No son modelos teóricos aislados, sino arquitecturas escalables. 

Como profesional híbrido (Ph.D., Ingeniero de Machine Learning y experto en gestión de riesgos cuantitativos), ofrezco consultoría técnica para:
* Reestructuración de motores de cálculo CVA/PFE en Python para reducir tiempos de ejecución.
* Auditoría y validación de modelos internos de riesgo de contraparte frente a normativas de Basilea.
* Implementación de *pipelines* de datos que conectan los modelos estocásticos con las bases de datos de *Middle Office*.

📩 **Contacto Corporativo:** Si su mesa de operaciones enfrenta cuellos de botella en el cálculo de xVA o requiere optimización de capital regulatorio, contácteme directamente en **carr8824@gmail.com** para estructurar una prueba de concepto.