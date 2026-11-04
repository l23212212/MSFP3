[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=l23212212/MSFP3)

# Práctica 3: Sistema Musculoesquelético

## Información del estudiante

Diego Macias Armenta [23212212]; l23212212@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México / TecNM - Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación *in silico* brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de las analogías electromecánicas (fuerza-voltaje) para describir la dinámica de sistemas fisiológicos, obtener funciones de transferencia mediante el principio de superposición y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Convertir el diagrama mecánico del compartimento musculoesquelético de Khoo a su equivalente eléctrico mediante la analogía de fuerza-voltaje (fuerza $F(t) \rightarrow$ voltaje $V(t)$, velocidad $\dot{x}(t) \rightarrow$ corriente $I(t)$, compliancias $C_p, C_s \rightarrow$ capacitancias, amortiguación $R \rightarrow$ resistencia).
2. Calcular analíticamente la función de transferencia del sistema musculoesquelético aplicando el principio de superposición para evaluar la contribución de la fuerza activa $F_0 = \alpha F(t)$ y la fuerza real $F(t)$.
3. Determinar el error en estado estacionario y analizar la estabilidad en lazo abierto evaluando la variación de parámetros entre un individuo sano (Control, $R = 100\,\Omega$) y un paciente con atrofia muscular (Caso, $R = 10\,\text{k}\Omega$).
4. Construir el diagrama de bloques del sistema en lazo abierto y lazo cerrado dentro de Simulink.
5. Diseñar e implementar un controlador PID en Simulink utilizando el bloque `PID Controller` y la herramienta `Tune` para encontrar las ganancias óptimas ($k_P, k_I, k_D$) que corrijan la respuesta alterada en la atrofia muscular.
6. Simular y comparar la respuesta al impulso en el intervalo $t \in [0, 10]$ segundos mediante herramientas computacionales (Python, Simulink y Multisim) tanto en lazo abierto como en lazo cerrado con el controlador.
7. Diseñar la representación esquemática y biológica del sistema utilizando BioRender.com.

## Descripción detallada del sistema

En esta práctica se aborda el modelado computacional de un compartimento del sistema musculoesquelético basado en el modelo mecánico propuesto por M. C. Khoo (Sección 2, Pág. 26). El modelo describe la relación entre la fuerza desarrollada por el elemento contráctil activo ($F_0 = \alpha F(t)$ con $0 < \alpha < 1$), la resistencia de amortiguación viscosa del tejido ($R$) y las propiedades de almacenamiento elástico del sarcolema ($C_p$, en paralelo) y los tendones musculares ($C_s$, en serie).

Palabras clave: Sistema musculoesquelético; Analogía fuerza-voltaje; Teorema de superposición; Atrofia muscular; Controlador PID; Khoo.

## Lista de archivos incluidos en el repositorio

1. Scripts de MATLAB para inicialización de parámetros, resolución del modelo de EDOs y graficación `plotsignals` [`.m` o `.mlx`].
2. Modelo de Simulink del sistema musculoesquelético y los controladores PID `Practica3.slx` [`.slx`].
3. Archivo de datos extraído de la simulación `signal.xlsx` [`.xlsx`].
4. Imágenes de las simulaciones y comparativas (Hipotónico vs Normotónico vs PID, etc.) [`.pdf` y `.png`].

## Referencias

[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

[2] M. C. Khoo, *Physiological Control Systems: Analysis, Simulation, and Estimation*, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 2, Page 26.

[3] N. S. Nise, *Control Systems Engineering*, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.
