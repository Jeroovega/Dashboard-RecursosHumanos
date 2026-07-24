# Dashboard de Recursos Humanos | Caso de estudio: LuzuTV & OLGA 🚀

> ⚠️ **Disclaimer:** Este proyecto utiliza información completamente ficticia generada de forma aleatoria con fines exclusivamente educativos. No representa datos reales de LuzuTV, OLGA ni de ninguna otra organización.
## 📌 Acerca del proyecto
Este proyecto consiste en el desarrollo de un dashboard de Recursos Humanos inspirado en la estructura organizacional de dos de los principales canales de streaming de Argentina: **LuzuTV** y **OLGA**.

El objetivo es simular un escenario empresarial real para analizar indicadores de personal, composición del equipo y métricas salariales mediante visualizaciones interactivas.

Toda la información utilizada fue generada de forma ficticia con fines exclusivamente educativos.

### Objetivos 

Este dashboard tiene como objetivo facilitar el análisis del personal mediante indicadores e información visual que permitan comprender la estructura de la organización, la composición del equipo y las métricas salariales, brindando soporte para la toma de decisiones.



### Estructura

```text
Dashboard
│
├── 📊 Panel Principal
├── 👥 Datos Demográficos
└── 💰 Ingresos
```

---

## 📊 Panel Principal

La sección principal proporciona una visión general del área de Recursos Humanos, incluyendo:

- Total de empleados contratados, activos y desvinculados.
- Evolución de contrataciones y bajas a lo largo del tiempo.
- Distribución de empleados por área y puesto.
- Comparación de empleados entre áreas/departamentos.
- Distribución geográfica por provincia y ciudad.

> **Objetivo:** obtener un panorama general del estado de la organización y la distribución de su personal.

---

## 👥 Datos Demográficos

La sección de datos demográficos permite analizar la composición del equipo de trabajo, incluyendo:

- Proporción de género.
- Distribución de empleados por grupos etarios.
- Distribución por nivel educativo.
- Cantidad de empleados en cada grupo etario.
- Cantidad de empleados en cada nivel educativo.
- Relación entre el nivel educativo y la evaluación de desempeño.

> **Objetivo:** comprender la composición demográfica de la empresa, identificar patrones y analizar la diversidad del equipo.

---

## 💰 Ingresos

La sección de ingresos está orientada al análisis de las métricas salariales, incluyendo:

- Comparación de salarios según nivel educativo y género.
- Relación entre la edad y el salario de los empleados por área/departamento.

### Registro de Empleados

El dashboard incluye un listado completo de colaboradores con información detallada para realizar análisis individuales y aplicar filtros dinámicos. La tabla permitirá filtrar los empleados por cualquiera de las columnas disponibles.

| Columna | Ejemplo |
| :--- | :--- |
| ID Empleado | EMP-0001 |
| Nombre | Santiago |
| Apellido | Soria |
| Empresa | LuzuTV |
| Programa | Nadie Dice Nada |
| Área | Producción |
| Puesto | Asistente de Producción |
| Género | Masculino |
| Educación | Universitario en curso |
| Provincia | Buenos Aires |
| Ciudad | La Plata |
| Tipo de contrato | Full Time |
| Salario | $1.650.000 |
| Rendimiento | Bueno |
| Horas extra | No |
| Fecha de ingreso | 2023-10-05 |
| Fecha de baja | - |

> La información presentada corresponde a datos ficticios generados automáticamente y no representa empleados reales.

> **Objetivo:** facilitar el análisis individual de cada empleado e identificar posibles patrones o discrepancias.
---
## 🧪 Generación de datos ficticios

Para la construcción del dashboard se desarrolló un generador de datos sintéticos en Python utilizando la librería **Faker**, junto con estructuras personalizadas para representar una organización de streaming argentina.

El dataset generado contiene información ficticia de **250 empleados distribuidos entre LuzuTV y OLGA**, simulando una estructura organizacional realista de una empresa de medios digitales.

Los datos fueron diseñados teniendo en cuenta:

- Distribución de empleados por áreas según una estructura típica de una productora audiovisual.
- Diferenciación entre roles creativos, técnicos, comerciales y administrativos.
- Salarios aproximados en pesos argentinos para el año 2026 según el tipo de puesto.
- Ubicaciones basadas en provincias y ciudades argentinas.
- Diferentes modalidades de contratación (Tiempo Completo, Medio Tiempo y Freelance).
- Fechas de ingreso comprendidas entre 2020 y 2026.
- Registro de empleados activos y desvinculados.
- Niveles educativos y evaluaciones de desempeño.

El objetivo de esta generación de datos no es representar información real de ninguna organización, sino crear un escenario empresarial ficticio que permita practicar análisis de Recursos Humanos, modelado de datos y construcción de dashboards.

---

## 📋 Estructura del dataset

El archivo `empleados.csv` contiene las siguientes columnas:

| Columna | Descripción | Ejemplo |
| :--- | :--- | :--- |
| `id_empleado` | Identificador único del empleado | EMP-0001 |
| `nombre` | Nombre del colaborador | Santiago |
| `apellido` | Apellido del colaborador | Soria |
| `genero` | Género del empleado | Masculino |
| `empresa` | Organización a la que pertenece | LuzuTV |
| `programa` | Programa asociado o área corporativa | Nadie Dice Nada |
| `area` | Área principal dentro de la organización | Producción |
| `puesto` | Rol desempeñado por el empleado | Productor General |
| `educacion` | Nivel educativo alcanzado | Universitario completo |
| `provincia` | Provincia de residencia | Buenos Aires |
| `ciudad` | Ciudad de residencia | La Plata |
| `tipo_contrato` | Modalidad laboral | Full Time |
| `salario` | Salario mensual estimado en pesos argentinos | $2.500.000 |
| `rendimiento` | Evaluación de desempeño | Muy Bueno |
| `horas_extra` | Indicador de realización de horas extra | Sí |
| `fecha_ingreso` | Fecha de incorporación a la empresa | 2023-10-05 |
| `fecha_nacimiento` | Fecha de nacimiento ficticia | 2002-07-30 |
| `fecha_baja` | Fecha de desvinculación (si corresponde) | 2025-03-10 |

> Todos los registros fueron generados automáticamente y no corresponden a empleados reales.

---
## ☕ Contacto

Si te interesó el proyecto, tenés alguna consulta o sugerencia, o representás a alguna de las organizaciones mencionadas y querés solicitar modificaciones o la eliminación de alguna referencia, no dudes en comunicarte conmigo.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeronimo-vega/)

📩 `jerovegadev@gmail.com`

---
## ⚠️ Descargo de responsabilidad

Este proyecto fue desarrollado con fines exclusivamente educativos, de aprendizaje y demostración técnica dentro de un portfolio personal.

Toda la información presentada en el dashboard (empleados, salarios, edades, evaluaciones de desempeño, ubicaciones y cualquier otro dato de Recursos Humanos) es **completamente ficticia** y fue **generada de manera aleatoria** con el único propósito de construir un caso de uso realista para el análisis de datos y la visualización mediante dashboards.

Cualquier semejanza con personas, organizaciones o situaciones reales es **mera coincidencia** y no representa información auténtica de ninguna empresa.

Las referencias a **LuzuTV** y **OLGA** tienen un carácter exclusivamente ilustrativo y educativo, utilizándose únicamente como inspiración para contextualizar el proyecto. En ningún caso existe la intención de divulgar, representar o inferir información interna, confidencial o privada de dichas organizaciones, ni de afectar su imagen o actividad comercial.

Si algún representante de las marcas mencionadas considera que alguna referencia podría generar confusión o prefiere que se elimine cualquier identificación con su organización, me encuentro completamente a disposición para realizar las modificaciones o remociones que sean necesarias.

Agradezco cualquier observación o sugerencia relacionada con el proyecto y quedo disponible para responder consultas a través de los medios de contacto indicados.

