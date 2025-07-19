# 📊 Análisis de Evasión de Clientes - TelecomX Parte 2

> Challenge Parte 2 - Programa ONE + Alura LATAM
> Especialización en Ciencia de Datos

## 🎯 Descripción del Proyecto

Este proyecto analiza el comportamiento de evasión de clientes (churn) de la empresa TelecomX utilizando técnicas de análisis exploratorio de datos y visualización. El objetivo principal es identificar patrones y factores que influyen en la cancelación de servicios para desarrollar estrategias de retención efectivas.

**Problema central:** TelecomX presenta una tasa de cancelación del 25.7% (1 de cada 4 clientes se da de baja).

## 📈 Hallazgos Principales

### Perfil de Alto Riesgo

- **Demográfico:** Clientes menores de 65 años, sin pareja, sin dependientes
- **Servicios:** Facturación electrónica, fibra óptica, contratos mensuales
- **Pago:** Método de cheque electrónico (43.8% de cancelación)

### Factores Protectores

- **Contratos largos:** 1-2 años tienen cancelación < 3%
- **Adultos mayores:** 22.9% vs 40.3% en jóvenes
- **Clientes con dependientes:** 14.9% vs 30.3% sin dependientes

## 🛠️ Tecnologías Utilizadas

```python
Python 3.10+
├── Pandas & NumPy          # Análisis de datos
├── Matplotlib & Seaborn    # Visualización estática
├── Plotly                  # Visualización interactiva
└── Google Colab            # Entorno de desarrollo
```

## 📁 Estructura del Repositorio

```python
ChallengeParteII-TelecomX/
├── 📄 Analisis-de-Evasion-de-Cliente...  # Notebook principal
├── 📓 Challenge2_TELECOMX.ipynb         # Análisis completo
├── 📋 README.md                         # Este archivo
└── 📊 Datasets y análisis complementarios
```

## 🚀 Cómo Ejecutar el Proyecto
### Opción 1: Google Colab (Recomendado)

```python
1. Abre Challenge2_TELECOMX.ipynb en Google Colab
2. Ejecuta: Runtime > Run All
3. Los datos se cargan automáticamente desde la API
```

### Opción 2: Entorno Local

```bash
# Instalar dependencias
pip install pandas numpy matplotlib seaborn plotly

# Ejecutar notebook
jupyter notebook Challenge2_TELECOMX.ipynb
```

## 📊 Metodología del Análisis

1. **Exploración inicial** - Distribución de cancelaciones y variables clave
2. **Análisis demográfico** - Edad, estado civil, dependientes
3. **Análisis de servicios** - Tipo de contrato, internet, facturación
4. **Variables numéricas** - Meses de contrato, cargos, patrones temporales
5. **Correlaciones** - Relaciones entre variables predictoras
6. **Insights y recomendaciones** - Estrategias basadas en datos

## 💡 Recomendaciones Estratégicas

### 🎯 Retención Inmediata

- **Promocionar contratos anuales/bianuales** con incentivos
- **Optimizar experiencia de pago** electrónico
- **Programas de bienvenida** para primeros 6 meses

### 📈 Segmentación

- **Campañas personalizadas** para perfil alto riesgo
- **Ofertas familiares** para clientes con dependientes
- **Beneficios exclusivos** por permanencia

## 📋 Requisitos del Sistema

- **Python:** 3.10 o superior
- **Memoria RAM:** 4GB mínimo (para procesamiento de datasets)
- **Conexión:** Internet (para carga de datos desde API)

## 🏆 Resultados del Proyecto

- ✅ Identificación de 4 variables clave predictoras de churn
- ✅ Segmentación de clientes en 3 perfiles de riesgo
- ✅ 10 recomendaciones estratégicas basadas en datos
- ✅ Base sólida para modelos predictivos futuros

## 👨‍💻 Autor
**Alberto Daniel Gutiérrez Ramos**
📧 Participante del Programa ONE + Alura LATAM
🎓 Especialización en Ciencia de Datos
