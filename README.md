[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=4l3xand3r-ia/Proyecto_GD)

# Gemelos Digitales. Proyecto [Torres21212848]

## Autor
Alexander Torres Avila

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l21212848@tectijuana.edu.mx

## Resumen del proyecto
Este proyecto tiene como objetivo estudiar un sistema dinámico no lineal compuesto por tres ecuaciones diferenciales ordinarias de primer orden, que describe la interacción entre tres poblaciones celulares: células patológicas (x), células normales (y) y células efectoras inmunológicas (z). El sistema está basado en un modelo multiplicativo tipo acción de masas, que incorpora crecimiento, interacción cruzada y regulación inmunológica.

El modelo matemático considerado es:

𝑥 = 𝜌1𝑥𝑦𝑧
𝑦 = 𝜌2𝑦−𝜌3𝑥𝑦
𝑧 = 𝜌4𝑧−𝜌5𝑥𝑧

Donde cada ecuación representa una dinámica fundamental:

Las células patológicas se activan mediante la interacción simultánea con células sanas e inmunológicas.

Las células sanas crecen proporcionalmente pero son atacadas por células patológicas.

Las células efectoras tienen crecimiento basal, pero se inhiben frente a poblaciones tumorales.

Mediante simulaciones en MATLAB, se analizan las trayectorias del sistema en el tiempo y se confirma su positividad, garantizando que las soluciones biológicamente válidas permanecen en el dominio positivo. Se observa además una dinámica de estabilización, donde algunas variables convergen hacia cero o uno, representando estados estables o de control biológico.

Este modelo ofrece una representación conceptual de procesos como el crecimiento tumoral, la inmunorregulación y el daño tisular. Además, sirve como base teórica para exploraciones futuras en inmunoterapia computacional y modelos de gemelos digitales aplicados a sistemas celulares.

## Objetivos específicos
1. Formular un sistema de ecuaciones diferenciales que modele interacciones celulares tipo acción de masas entre poblaciones patológicas, sanas e inmunológicas.
2. Verificar la positividad del sistema a partir de condiciones matemáticas y simulaciones numéricas, asegurando interpretaciones válidas en biología.
3. Explorar el comportamiento cualitativo del sistema bajo diferentes condiciones iniciales y valores de parámetros 𝜌1 a 𝜌5​, evaluando su impacto en la estabilidad y evolución temporal.
4. Visualizar trayectorias temporales de las tres poblaciones y comparar su normalización y convergencia para interpretar estados estacionarios o dinámicas cíclicas.
5. Discutir el modelo en el contexto de procesos inmunológicos, como la activación celular, la respuesta a invasores o la intervención terapéutica, mediante experimentación computacional (in silico).

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx
