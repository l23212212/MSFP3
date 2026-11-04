[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=l23212212/MSFP3)

# Práctica 3: Sistema Musculoesquelético

Repositorio académico de la asignatura **Modelado de Sistemas Fisiológicos**, correspondiente al programa de **Ingeniería Biomédica** del Tecnológico Nacional de México / Instituto Tecnológico de Tijuana.

Esta práctica aborda el modelado matemático y la simulación computacional de un sistema musculoesquelético, integrando herramientas de análisis matemático, programación y modelado fisiológico. Se emplean MATLAB y Python para desarrollar y comparar los modelos correspondientes, así como recursos gráficos para representar los elementos y características del sistema estudiado.

El propósito es comprender el comportamiento dinámico del sistema musculoesquelético mediante su representación matemática, analizar los parámetros involucrados y estudiar las respuestas obtenidas a través de las simulaciones computacionales.

---

## Información del estudiante

**Estudiante:** Diego Macias Armenta  
**Número de control:** 23212212  
**Correo institucional:** l23212212@tectijuana.edu.mx  
**Asignatura:** Modelado de Sistemas Fisiológicos  
**Clave:** IBF-1020  
**Programa académico:** Ingeniería Biomédica  
**Institución:** Tecnológico Nacional de México / Instituto Tecnológico de Tijuana  

---

## Contenido

1. Resumen
2. Competencia y objetivos
3. Relación con el temario
4. Introducción al sistema musculoesquelético
5. Modelado matemático
6. Análisis de parámetros
7. Implementación en MATLAB
8. Implementación en Python
9. Análisis y comparación de resultados
10. Recursos gráficos y documentación
11. Estructura del repositorio
12. Requisitos de software
13. Reproducibilidad y entregables
14. Referencias

---

## 1. Resumen

La práctica tiene como finalidad estudiar el comportamiento de un sistema musculoesquelético mediante herramientas de modelado matemático y simulación computacional. Para ello, se utilizan los conocimientos de la asignatura Modelado de Sistemas Fisiológicos, relacionando los principios matemáticos con la representación y el análisis de sistemas biológicos.

El desarrollo contempla el análisis matemático del modelo, la identificación de sus parámetros y la implementación de simulaciones utilizando MATLAB y Python. Ambas herramientas permiten observar el comportamiento del sistema, modificar sus parámetros y analizar las respuestas obtenidas bajo las condiciones establecidas en los casos de estudio.

Asimismo, se incorporan recursos gráficos para complementar la interpretación fisiológica del modelo y facilitar la comprensión de los elementos que conforman el sistema musculoesquelético.

**Palabras clave:** sistema musculoesquelético; modelado fisiológico; análisis matemático; simulación computacional; MATLAB; Python; Ingeniería Biomédica.

---

## 2. Competencia y objetivos

### Competencia a desarrollar

Aplicar herramientas de modelado matemático y simulación computacional para representar y analizar sistemas fisiológicos, relacionando sus parámetros y comportamiento dinámico con los principios fundamentales de la Ingeniería Biomédica.

### Objetivo general

Desarrollar y analizar un modelo matemático de un sistema musculoesquelético mediante herramientas computacionales, utilizando MATLAB y Python para estudiar su comportamiento y evaluar la influencia de los parámetros involucrados en su representación.

### Objetivos específicos

- Identificar los elementos y características fisiológicas del sistema musculoesquelético estudiado.
- Comprender los fundamentos matemáticos empleados para representar el sistema.
- Analizar los parámetros que intervienen en el modelo y su influencia sobre el comportamiento dinámico.
- Implementar el modelo matemático utilizando MATLAB.
- Reproducir el caso de estudio mediante programación en Python.
- Comparar los resultados obtenidos en ambas herramientas computacionales.
- Interpretar las respuestas de las simulaciones desde una perspectiva fisiológica y matemática.
- Documentar los procedimientos, resultados y recursos utilizados durante el desarrollo de la práctica.

---

## 3. Relación con el temario

La práctica integra conocimientos de modelado matemático, análisis de sistemas fisiológicos y herramientas computacionales, permitiendo aplicar los fundamentos de Ingeniería de Control y simulación al estudio del sistema musculoesquelético.

| Área de conocimiento | Aplicación en la práctica |
|---|---|
| Modelado matemático | Representación del comportamiento del sistema musculoesquelético. |
| Análisis matemático | Estudio de las ecuaciones y parámetros del modelo. |
| Sistemas fisiológicos | Interpretación de los elementos y variables biológicas involucradas. |
| MATLAB | Implementación y simulación del modelo matemático. |
| Python | Desarrollo de una implementación computacional alternativa. |
| Análisis de resultados | Comparación e interpretación de las respuestas obtenidas. |

---

## 4. Introducción al sistema musculoesquelético

El sistema musculoesquelético está constituido principalmente por músculos, huesos, articulaciones, tendones y ligamentos. En conjunto, estos elementos permiten el movimiento, proporcionan estabilidad y contribuyen al mantenimiento de la postura corporal.

Desde el punto de vista de la Ingeniería Biomédica, este sistema puede estudiarse mediante modelos matemáticos que describen las relaciones entre fuerzas, desplazamientos, velocidades y otras variables relacionadas con el movimiento.

El modelado matemático permite representar determinados fenómenos fisiológicos mediante ecuaciones, facilitando el análisis de su comportamiento bajo diferentes condiciones. A través de las simulaciones computacionales es posible estudiar la influencia de los parámetros del modelo y comprender cómo se modifica su respuesta ante diferentes escenarios.

En esta práctica se emplean herramientas como MATLAB y Python para desarrollar y analizar las representaciones computacionales correspondientes al sistema musculoesquelético.

---

## 5. Modelado matemático

El análisis matemático constituye una parte fundamental de la práctica, ya que permite establecer las relaciones entre las variables y parámetros que describen el sistema estudiado.

Para esta etapa se utiliza el documento **AnálisisMatemáticoPráctica3.pdf**, que contiene el material de referencia para el desarrollo de los procedimientos matemáticos.

Los aspectos que se consideran en esta sección incluyen:

- Identificación de las variables del sistema.
- Definición de los parámetros matemáticos.
- Desarrollo de las expresiones y ecuaciones correspondientes.
- Análisis de las relaciones entre las variables.
- Interpretación de los resultados matemáticos.

Los resultados obtenidos durante esta etapa sirven como fundamento para implementar el modelo en las herramientas computacionales.

---

## 6. Análisis de parámetros

Los parámetros del modelo permiten establecer las condiciones bajo las cuales se estudia el comportamiento del sistema musculoesquelético.

El documento **ParámetrosControladorPráctica3.pdf** contiene información de referencia relacionada con los parámetros empleados en el desarrollo de la práctica.

Su análisis permite identificar los valores utilizados en las simulaciones y comprender su influencia sobre el comportamiento del modelo.

Es importante mantener consistencia entre los parámetros utilizados en MATLAB y Python para que los resultados puedan compararse bajo las mismas condiciones.

---

## 7. Implementación en MATLAB

MATLAB se utiliza como herramienta para desarrollar y ejecutar el modelo matemático correspondiente al sistema musculoesquelético.

El archivo principal de esta implementación es:

**`Macias23212212.mlx`**

Este cuaderno permite organizar el desarrollo de la práctica, ejecutar los procedimientos matemáticos y presentar los resultados obtenidos.

La versión exportada del trabajo se encuentra disponible en:

**`Macias23212212.pdf`**

El documento PDF permite consultar el desarrollo y los resultados sin necesidad de ejecutar directamente el archivo de MATLAB.

### Actividades realizadas

1. Definición de los parámetros y variables del modelo.
2. Implementación de las expresiones matemáticas.
3. Ejecución de los procedimientos de simulación.
4. Obtención de resultados gráficos y numéricos.
5. Análisis del comportamiento del sistema.

---

## 8. Implementación en Python

Python se utiliza como herramienta complementaria para reproducir y analizar el caso de estudio.

El archivo correspondiente es:

**`Practica_3.py`**

Mediante este programa se desarrolla la implementación computacional del modelo, utilizando los parámetros y condiciones establecidos para la práctica.

El documento **Caso_python.pdf** contiene el material de referencia relacionado con esta implementación.

### Actividades realizadas

1. Definición de las variables y parámetros.
2. Implementación del modelo matemático.
3. Ejecución de las simulaciones.
4. Generación de representaciones gráficas.
5. Análisis de los resultados obtenidos.

La implementación en Python permite disponer de una segunda herramienta para verificar y comparar los resultados obtenidos mediante MATLAB.

---

## 9. Análisis y comparación de resultados

La comparación de resultados permite identificar las similitudes y diferencias entre las implementaciones computacionales desarrolladas.

Para esta actividad se consideran los siguientes documentos:

- **Caso_matlab.pdf:** material de referencia para el caso implementado en MATLAB.
- **Caso_python.pdf:** material de referencia para el caso implementado en Python.
- **Macias23212212.pdf:** documentación de la implementación realizada en MATLAB.

Los aspectos principales para la comparación son:

- Correspondencia entre los parámetros utilizados.
- Consistencia de las expresiones matemáticas.
- Comportamiento de las variables simuladas.
- Similitudes y diferencias entre las respuestas gráficas.
- Influencia de los parámetros sobre el comportamiento del modelo.

La interpretación de los resultados debe considerar tanto los fundamentos matemáticos como su significado dentro del contexto fisiológico del sistema musculoesquelético.

---

## 10. Recursos gráficos y documentación

Para complementar el desarrollo de la práctica se incorpora el documento **BiorenderPractica3.pdf**, que contiene recursos gráficos relacionados con la representación del sistema musculoesquelético.

Estos recursos permiten visualizar los elementos anatómicos y facilitar la comprensión de los fundamentos fisiológicos involucrados en el modelo.

La documentación de apoyo se complementa con los archivos de análisis matemático, casos de estudio y parámetros del controlador proporcionados en el repositorio.

---

## 11. Estructura del repositorio

La organización actual de los archivos de la práctica es la siguiente:

```text
Practica3/
│
├── AnálisisMatemáticoPráctica3.pdf
│
├── BiorenderPractica3.pdf
│
├── Caso_matlab.pdf
│
├── Caso_python.pdf
│
├── LICENSE
│
├── Macias23212212.mlx
│
├── Macias23212212.pdf
│
├── ParámetrosControladorPráctica3.pdf
│
└── Practica_3.py
```

### Descripción de los archivos

| Archivo | Descripción |
|---|---|
| `AnálisisMatemáticoPráctica3.pdf` | Documento de análisis matemático correspondiente a la práctica. |
| `BiorenderPractica3.pdf` | Material gráfico relacionado con el sistema musculoesquelético. |
| `Caso_matlab.pdf` | Documento de referencia del caso desarrollado en MATLAB. |
| `Caso_python.pdf` | Documento de referencia del caso desarrollado en Python. |
| `LICENSE` | Archivo que especifica las condiciones de uso y distribución del repositorio. |
| `Macias23212212.mlx` | Cuaderno de MATLAB con el desarrollo computacional de la práctica. |
| `Macias23212212.pdf` | Exportación en PDF del cuaderno de MATLAB. |
| `ParámetrosControladorPráctica3.pdf` | Documento de referencia de los parámetros del controlador. |
| `Practica_3.py` | Código fuente de la implementación en Python. |

---

## 12. Requisitos de software

### Software utilizado

- **MATLAB:** desarrollo y ejecución del modelo matemático.
- **Python:** implementación computacional complementaria.
- **Visual Studio Code:** entorno de desarrollo para ejecutar y editar el código Python.
- **Git y GitHub:** administración y documentación del repositorio.
- **BioRender:** elaboración y consulta de recursos gráficos relacionados con el sistema musculoesquelético.

Las bibliotecas necesarias para ejecutar el programa de Python deben corresponder a los módulos importados en el archivo `Practica_3.py`.

---

## 13. Reproducibilidad y entregables

Para reproducir el desarrollo de la práctica se recomienda seguir la siguiente secuencia:

1. Consultar los documentos de referencia incluidos en el repositorio.
2. Revisar el análisis matemático del sistema musculoesquelético.
3. Identificar los parámetros y condiciones establecidos para el modelo.
4. Consultar los casos de referencia de MATLAB y Python.
5. Ejecutar el cuaderno `Macias23212212.mlx` en MATLAB.
6. Ejecutar el programa `Practica_3.py` en Python.
7. Comparar los resultados obtenidos mediante ambas herramientas.
8. Analizar las diferencias y similitudes entre las simulaciones.
9. Consultar los recursos gráficos y documentar las características fisiológicas del sistema.
10. Organizar los archivos y resultados correspondientes en el repositorio.

### Entregables

| Entregable | Archivo o evidencia |
|---|---|
| Análisis matemático | `AnálisisMatemáticoPráctica3.pdf` |
| Representación gráfica | `BiorenderPractica3.pdf` |
| Caso de referencia MATLAB | `Caso_matlab.pdf` |
| Caso de referencia Python | `Caso_python.pdf` |
| Desarrollo en MATLAB | `Macias23212212.mlx` |
| Reporte exportado de MATLAB | `Macias23212212.pdf` |
| Parámetros del controlador | `ParámetrosControladorPráctica3.pdf` |
| Implementación en Python | `Practica_3.py` |
| Licencia del repositorio | `LICENSE` |

---

## 14. Referencias

Los documentos de referencia utilizados para el desarrollo de esta práctica se encuentran disponibles dentro del repositorio:

- Análisis matemático de la Práctica 3.
- Caso de estudio implementado en MATLAB.
- Caso de estudio implementado en Python.
- Parámetros del controlador de la Práctica 3.
- Recursos gráficos de BioRender.

Las referencias bibliográficas específicas de los fundamentos matemáticos y fisiológicos deberán consultarse en los documentos originales de la práctica.

---

## Uso académico

Este repositorio contiene los archivos correspondientes al desarrollo de la **Práctica 3: Sistema Musculoesquelético**, realizada como parte de la asignatura Modelado de Sistemas Fisiológicos del programa de Ingeniería Biomédica.

Su finalidad es documentar el análisis matemático, la implementación computacional y la interpretación de los resultados obtenidos mediante MATLAB y Python, integrando los conocimientos de modelado de sistemas fisiológicos y herramientas de simulación.

**Estudiante:** Diego Macias Armenta  
**Número de control:** 23212212  
**Institución:** Tecnológico Nacional de México / Instituto Tecnológico de Tijuana.
