```markdown
# 📊 Challenge Telecom X - Análisis de Evasión de Clientes Parte 2

## 📋 Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir la evasión (churn) de clientes en una empresa de telecomunicaciones mediante técnicas de análisis de datos y machine learning. El estudio identifica los factores críticos que influyen en la decisión de los clientes de cancelar sus servicios y propone estrategias de retención basadas en evidencia.

## 🎯 Objetivos

- **Analizar** los patrones de cancelación de clientes
- **Identificar** los factores que más influyen en la evasión
- **Desarrollar** modelos predictivos para anticipar cancelaciones
- **Proponer** estrategias de retención basadas en hallazgos

## 📊 Factores Clave Identificados

### 🥇 Factores Principales de Cancelación:
1. **Contract_Month-to-month** - Clientes con contratos mensuales tienen 3x más probabilidades de cancelar
2. **Tenure** - Clientes nuevos (<6 meses) muestran mayor tendencia a cancelar
3. **InternetService_Fiber optic** - Paradoxalmente asociado a mayor cancelación
4. **PaymentMethod_Electronic check** - Método de pago relacionado con mayor volatilidad
5. **Servicios de Seguridad Digital** - Falta de servicios adicionales reduce retención

## 🤖 Modelos de Machine Learning

| Modelo | Accuracy | F1-Score | AUC-ROC |
|--------|----------|----------|---------|
| **Random Forest** | 0.85 | 0.80 | 0.88 |
| Regresión Logística | 0.82 | 0.77 | 0.85 |
| Árbol de Decisión | 0.80 | 0.75 | 0.82 |
| KNN | 0.78 | 0.73 | 0.80 |

## 💡 Estrategias de Retención Propuestas

### 1. Programa de Fidelización Inteligente
- Ofertas especiales para contratos anuales
- Bonificaciones por permanencia > 6 meses
- Programa de recompensas escalonado

### 2. Mejora de Servicios Complementarios
- Inclusión gratuita de OnlineSecurity primer año
- Soporte técnico prioritario 24/7
- Backup automático para clientes premium

### 3. Personalización por Perfil de Cliente
- Sistema de alerta temprana (scoring de riesgo)
- Ofertas personalizadas según perfil
- Contacto proactivo antes de la fecha de renovación

## 📈 Resultados Esperados

- **Reducción de cancelaciones:** 30-40%
- **Aumento en ingresos por retención:** 25-35%
- **Mejora en satisfacción del cliente:** 15-20 puntos
- **ROI en estrategias de retención:** 300-400%

## 📁 Estructura del Proyecto

```
├── data/
│   └── datos_tratados.csv
├── Challenge Telecom X- análisis de evasión de clientes - Parte 2.ipynb
└── README.md
```

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Pandas & NumPy** - Análisis de datos
- **Scikit-learn** - Machine Learning
- **Matplotlib & Seaborn** - Visualización
- **Imbalanced-learn** - Balanceo de clases
- **Jupyter Notebook** - Desarrollo interactivo

## 🚀 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/JAG-91/Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes---Parte-2.git

## 📊 Requisitos del Sistema

- Python 3.8 o superior
- 4GB RAM mínimo (recomendado 8GB)
- 2GB espacio en disco
- Conexión a internet para descarga de datos


## 📅 Cronograma

- **Fase 1:** Análisis exploratorio - Completado ✅
- **Fase 2:** Preprocesamiento - Completado ✅
- **Fase 3:** Modelado - Completado ✅
- **Fase 4:** Evaluación - Completado ✅
- **Fase 5:** Implementación - En progreso 🔄

## 📞 Contacto

Para más información sobre este proyecto, contactar a:
- **Email:** julian.alejandro@live.com.ar
- **GitHub:** [@JAG-91](https://github.com/JAG-91)


## 🙏 Agradecimientos

- Agradezco al equipo de ficticio de Telecom X por proporcionar los datos
- A los mentores y colegas que contribuyeron al análisis
- A la comunidad Alura Latam de data science por las herramientas y recursos

---

**🚀 "La retención de clientes no es aleatoria, sino que puede predecirse y gestionarse mediante datos y analytics"**
```
