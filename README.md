# 🎓 EduPredict: Predictor de Abandono y Éxito Académico

## 📌 Descripción del Proyecto

**EduPredict** es una solución de inteligencia artificial para predecir el abandono estudiantil y evaluar el éxito académico en instituciones educativas. El proyecto utiliza técnicas avanzadas de machine learning para identificar factores de riesgo y patrones que influyen en la permanencia y rendimiento de los estudiantes.

## 🎯 Objetivos

- Predecir la probabilidad de abandono estudiantil
- Identificar factores críticos que impactan el rendimiento académico
- Proporcionar insights para intervenciones tempranas
- Ayudar a las instituciones educativas a mejorar las tasas de retención

## 📊 Conjunto de Datos

### Características del Conjunto de Datos

La base de datos contiene múltiples variables que describen las características de los estudiantes, sus antecedentes, sus actividades académicas, y el contexto económico en el que estudian. El objetivo principal es predecir si un estudiante abandonará sus estudios (Dropout), logrará éxito académico (Success), o permanecerá sin concluir su grado (No Graduation).

A continuación, se detalla cada variable:
#### Datos Demográficos
- **Estado Civil**: Situación marital del estudiante
- **Género**: Identidad de género
- **Edad de Inscripción**: Edad al momento de ingresar
- **Nacionalidad**: País de origen
- **Necesidades Educativas Especiales**: Indicador de requerimientos especiales

#### Antecedentes Académicos
- **Modo de Aplicación**: Forma de ingreso a la institución
- **Calificación Previa**: Nota de ingreso
- **Orden de Aplicación**: Secuencia de solicitud
- **Curso**: Programa académico
- **Asistencia (Diurna/Nocturna)**: Tipo de jornada

#### Contexto Familiar
- **Nivel Educativo de la Madre**: Formación académica materna
- **Nivel Educativo del Padre**: Formación académica paterna
- **Ocupación de la Madre**: Trabajo de la madre
- **Ocupación del Padre**: Trabajo del padre

#### Información Académica Semestral
- **Unidades Curriculares Primer Semestre**:
  - Acreditadas
  - Matriculadas
  - Evaluaciones
  - Aprobadas
  - Calificación
  - Sin evaluaciones

- **Unidades Curriculares Segundo Semestre**:
  - Acreditadas
  - Matriculadas
  - Evaluaciones
  - Aprobadas
  - Calificación
  - Sin evaluaciones

#### Contexto Económico
- **Becario**: Indicador de beca estudiantil
- **Deudor**: Estado de deuda
- **Tasas de Matrícula**: Estado de pagos
- **Tasa de Desempleo**: Contexto económico local
- **Tasa de Inflación**: Indicador económico
- **PIB**: Producto Interno Bruto

### Ejemplo Detallado de un Registro

Tomemos un ejemplo hipotético para entender los datos:

```
Estudiante X:
- Edad: 20 años
- Género: Masculino
- Estado Civil: Soltero
- Modo de Aplicación: Admisión directa
- Curso: Ingeniería de Sistemas
- Calificación de Ingreso: 127.3
- Beca: No
- Primer Semestre:
  * Unidades Matriculadas: 6
  * Unidades Aprobadas: 4
  * Calificación Promedio: 14/20
- Contexto Económico:
  * Tasa Desempleo: 10.8%
  * Inflación: 1.4%
  * PIB: 1.74
- Resultado Predicho: Abandono (Dropout)
```

## 🧠 Metodología

1. **Preprocesamiento de Datos**
2. **Análisis Exploratorio**
3. **Selección de Características**
4. **Entrenamiento de Modelos**
5. **Evaluación y Validación**
6. **Predicción**

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📈 Métricas de Evaluación

- Accuracy
- Precision
- Recall
- F1-Score
- Curva ROC
- Matriz de Confusión

## 🚀 Próximos Pasos

- Implementar modelo de predicción en tiempo real
- Desarrollar dashboard interactivo
- Integrar alertas tempranas
- Mejorar interpretabilidad del modelo

## 📋 Requisitos

- Python 3.8+
- Bibliotecas de análisis de datos
- Entorno Jupyter
- Bibliotecas Principales:
    - pandas: Para la manipulación de datos.
    - numpy: Operaciones matemáticas y estadísticas.
    - scikit-learn: Modelos de aprendizaje automático.
    - matplotlib y seaborn: Visualización de datos.
- Entorno de Trabajo: Jupyter Notebook o cualquier IDE compatible con Python.

## Guía de Instalación
1. Clona este repositorio:
```bash
git clone https://github.com/EliazarNoaLlas/EduPredict.git
```
2. Accede al directorio del proyecto:

```bash
cd predictor-abandono-estudiantil
```
3. Crea un entorno virtual:
```bash
python -m venv venv
```
4. Activa el entorno virtual:
En Windows:

```bash
5. venv\Scripts\activate
```
Instala las dependencias:
```bash
pip install -r requirements.txt
```

## 👥 Contribuidores

Las contribuciones son bienvenidas. Por favor, crea un fork del repositorio, realiza cambios y envía un pull request. Asegúrate de incluir una descripción detallada de tus cambios.

- [Nombres de los Contribuidores]
- [Contacto]
- [Afiliación Institucional]


## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.


---

**Nota**: Este proyecto busca ser una herramienta de apoyo, no un determinante absoluto del éxito académico.

## Contacto

Si tienes preguntas o comentarios, no dudes en contactarme a través de 193003@unsaac.edu.pe






