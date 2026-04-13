# 📊 Finanzas: Riesgo de Crédito y Contraparte

![Status](https://img.shields.io/badge/Estado-Activo-success)
![Audiencia](https://img.shields.io/badge/Audiencia-Ingeniería_Matemática_(CEU)-blue)
![Industria](https://img.shields.io/badge/Aplicación-Banca_Comercial_y_Derivados-purple)

Bienvenido al repositorio oficial del módulo **Riesgo de Crédito y Contraparte**, impartido como parte del curso de Modelación Cuantitativa de Riesgo en el CEU. 

Este material está estructurado para transformar la ingeniería matemática avanzada en **inteligencia de negocio accionable**. El enfoque central es dotar a los analistas de las herramientas cuantitativas necesarias para predecir impagos, modelar el contagio en carteras corporativas y valorar instrumentos de transferencia de riesgo (Derivados), optimizando así el capital regulatorio y económico.

---

## 🎯 Arquitectura del Módulo

El programa consta de **20 horas cronológicas** (4 semanas intensivas), integrando el rigor de la investigación aplicada con las necesidades operativas de la industria financiera. La metodología incluye:

* **Aula Invertida:** Asimilación teórica de modelos estructurales previa a la sesión.
* **Laboratorio Cuantitativo:** Calibración algorítmica de modelos y simulación Monte Carlo.
* **Resolución de Problemas Estructurados:** Análisis de eventos de crédito reales y estructuración de carteras.

### 📚 Contenido Público (Material de Clase)

En este repositorio se encuentran las diapositivas y el marco teórico de las sesiones, organizados por áreas de impacto:

#### MÓDULO II: RIESGO DE CRÉDITO Y CONTRAPARTE

* **TEMA 5: Modelos Estructurales de Riesgo de Crédito**
    * `5.1` El modelo de Merton (1974): El patrimonio como opción *Call* sobre los activos.
    * `5.2` Descomposición del riesgo: Probabilidad de Incumplimiento (PD), Pérdida en Caso de Incumplimiento (LGD) y Exposición al Incumplimiento (EAD).
    * `5.3` La Distancia al Impago (*Distance to Default*): Definición geométrica y cálculo.
    * `5.4` Calibración del modelo estructural y resolución de desafíos computacionales.

* **TEMA 6: Modelización de la Dependencia y Riesgo de Cartera**
    * `6.1` Correlación de incumplimientos: El motor subyacente del riesgo sistémico de cartera.
    * `6.2` Teoría de Cópulas: Vinculación de distribuciones marginales para modelar la dependencia.
    * `6.3` Aplicación práctica: La cópula Gaussiana frente a la cópula *t* de Student.
    * `6.4` El marco CreditMetrics™: 
        * *a.* Modelización estocástica de la migración de *ratings*. 
        * *b.* Simulación de la distribución de pérdidas agregadas. 
        * *c.* Cálculo avanzado del VaR de crédito.

* **TEMA 7: Derivados de Crédito y Transferencia de Riesgo**
    * `7.1` *Credit Default Swaps* (CDS): Mecánica operativa y participantes del mercado.
    * `7.2` Flujos de pago: Modelación de la pata de primas (*premium leg*) y pata de protección (*protection leg*).
    * `7.3` Eventos de crédito (ISDA) y mecanismos de liquidación (física vs. efectivo).
    * `7.4` Valoración cuantitativa de CDS: Cálculo del *par spread* y extracción de la probabilidad de impago implícita en el mercado.

---

## 🔐 Acceso a Material Cuantitativo y Entorno de Ejecución (Python/R)

Para garantizar la integridad del material de evaluación y proteger la propiedad intelectual de los *pipelines* de datos desarrollados, el entorno de ejecución técnica es privado. Este entorno excluye implementaciones "de juguete" y se centra en soluciones escalables. Incluye:

* Scripts de Python para la calibración del Modelo de Merton y simulación de Cópulas.
* Implementación en código del motor de CreditMetrics™.
* *Problem Sets* avanzados, bases de datos de *spreads* corporativos y material de evaluación.

📩 **Para Alumnos y Académicos CEU:** El acceso al repositorio de código fuente se otorga bajo validación. Envíe un correo a **carr8824@gmail.com** indicando su usuario de GitHub.

---

## 💼 Consultoría Institucional y Despliegue Corporativo

El marco analítico de este módulo no es un ejercicio teórico pasivo; es una arquitectura de control de riesgos diseñada para escalar. Los modelos estocásticos aquí presentados pueden integrarse en los sistemas de gestión de instituciones financieras para automatizar procesos y reducir la exposición a pérdidas imprevistas.

Se ofrecen servicios de consultoría especializada (respaldada por experiencia en *Machine Learning* y certificación FRM) para:
* Bancos Comerciales e Instituciones de Préstamo.
* Fondos de Pensiones y Gestoras de Activos.
* Departamentos de Riesgo que buscan migrar de Excel a *pipelines* de datos automatizados en Python/Cloud.

📩 **Contacto Corporativo:** Para auditoría de modelos de crédito, estructuración de *backtesting* o adaptación *in-company* de este currículum, contácteme en **carr8824@gmail.com**.