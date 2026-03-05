# challenge-telecom-X 
# Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto tiene como objetivo analizar el fenómeno de **evasión de clientes (Churn)** en la empresa ficticia **Telecom X**.  
A través de técnicas de **ETL (Extracción, Transformación y Carga)** y **Análisis Exploratorio de Datos (EDA)**, se busca identificar patrones que expliquen por qué los clientes cancelan el servicio.

Este análisis fue desarrollado como parte del **Challenge de Data Science del programa ONE (Oracle Next Education) en colaboración con Alura Latam**.

---

# Objetivo del Proyecto

El objetivo principal es:

- Analizar los datos de clientes de Telecom X.
- Identificar patrones relacionados con la **evasión de clientes (Churn)**.
- Preparar los datos para futuros **modelos predictivos de Machine Learning**.
- Proporcionar **insights estratégicos** que ayuden a mejorar la retención de clientes.

---

# Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando las siguientes herramientas:

- **Python**
- **Pandas** → Manipulación y análisis de datos
- **NumPy** → Operaciones numéricas
- **Matplotlib** → Visualización de datos
- **Seaborn** → Gráficos estadísticos
- **Google Colab / Jupyter Notebook**

---

# Estructura del Proyecto

El proyecto sigue las etapas del proceso **ETL + Análisis Exploratorio**:

Dentro del notebook se desarrollan las siguientes etapas:

### 1️⃣ Extracción
- Importación de librerías
- Carga de datos desde una **API en formato JSON**

### 2️⃣ Transformación
- Normalización de estructuras JSON
- Limpieza de datos
- Tratamiento de valores nulos
- Creación de nuevas variables (Cuentas_Diarias)
- Conversión de variables categóricas

### 3️⃣ Análisis Exploratorio de Datos
- Análisis descriptivo
- Visualización de la distribución del churn
- Análisis de churn según variables categóricas
- Análisis de churn según variables numéricas

### 4️⃣ Informe Final
- Interpretación de resultados
- Conclusiones
- Recomendaciones estratégicas

---

# Análisis Realizados

Durante el análisis se exploraron diferentes variables para entender la evasión de clientes, entre ellas:

- Tipo de contrato
- Género
- Método de pago
- Servicio de internet
- Cargo mensual
- Total gastado

Se generaron diferentes visualizaciones para identificar patrones entre los clientes que **cancelan el servicio y los que permanecen**.

---

# Principales Insights

Algunos hallazgos relevantes del análisis:

- Los **clientes con contratos mensuales** presentan una mayor tasa de cancelación.
- Los **cargos mensuales elevados** pueden estar asociados a mayor churn.
- El **tipo de contrato** es uno de los factores más influyentes en la retención de clientes.

Estos resultados pueden ayudar a la empresa a desarrollar **estrategias de fidelización y retención**.
