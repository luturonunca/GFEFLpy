# GFEFLpy
Galaxy Formation and Excuse for Learning python..

Título: Formación de Galaxias Espirales con Python
Duración: 6 sesiones (idealmente, una sesión mensual)
Modalidad: Mixta (parte teórica y parte práctica en cada sesión)
Público objetivo:
Estudiantes de master y ultimos semestres de pregrado interesados en astrofísica y simulaciones numéricas.
Personas que deseen aprender a utilizar herramientas digitales en Python (NumPy, SciPy, Matplotlib, entre otras) aplicadas al análisis de datos simulados  y/o a la evolución galáctica.
Objetivos generales:
Introducir conceptos clave de astrofísica aplicados a la evolución y morfología de galaxias.
Desarrollar habilidades en el manejo y análisis de datos simulados utilizando Python y otras herramientas numericas utiles en la investigacion.
Comparar y contrastar los resultados de las simulaciones con observaciones y modelos (en este caso de la teoria de la evolucion de galaxia pero facilmente extrapolables a otras aeras).
Metodología:
Cada sesión se dividirá en dos partes:
Teórica: Se presentarán los fundamentos físicos y conceptos esenciales relacionados con el tema de la sesión.
Práctica: Se trabajará con datos simulados y se aplicarán técnicas de análisis y visualización usando Python, mediante ejercicios y casos prácticos que permitan la comparación con observaciones reales. Especificamente se usarán simulaciones cosmológicas de galáxias espirales que ha sido previamente publicadas por la grupos que usan el codigo RAMSES. 
Estructura Detallada de las Sesiones
1. Introducción
Teoría:
Simulaciones de gas y estrellas:
Métodos y modelos empleados para correr las simulaciones.
Fundamentos de las ecuaciones de la hidrodinámica y la dinámica de N-cuerpos.
Morfología galáctica:
Caracterización y clasificación de galaxias: discos, elípticas, espirales, irregulares.
Práctica:
Python Essentials:
Introducción a las herramientas principales: NumPy y Matplotlib.
Uso de histogramas 2D para generar mapas de galaxias simuladas.
Herramientas específicas:
numpy.histogram2d
matplotlib.pyplot.imshow

2. Stars (Estrellas)
Teoría:
Ciclo de vida de las estrellas en distintos rangos de masa, con especial énfasis en el papel de las supernovas en la evolución galáctica.
Práctica:
Star Formation History (SFH):
Generación y análisis de la historia de formación estelar en las simulaciones.
Componentes del disco:
Segmentación de las diferentes partes del disco estelar utilizando criterios basados en la edad (y potencialmente la velocidad) de las estrellas.
Herramientas específicas:
numpy.histogram
numpy.where
Ejercicios propuestos:
1 SFH
2 young and old stars maps

3. Gas
Teoría:
Complejidad del medio interestelar:
Procesos como radiación, transferencia de calor, campos magnéticos y turbulencia, y su impacto en la eficiencia de formación estelar.
Fases del medio interestelar:
Distinción de las fases observables mediante diferentes técnicas.
Mecanismos de reinyección de energía y vientos galácticos:
Impacto en la regulación del gas galáctico y la formación de nuevas estrellas.
Práctica:
Diagrama de fases:
Visualización del gas galáctico en el plano de temperatura y densidad para identificar y separar sus fases.
Análisis de vientos:
Creación de visualizaciones y perfiles verticales que muestren el gas en fuga y el gas reacondicionado en la galaxia.
Herramientas específicas:
numpy.histogram
numpy.where
matplotlib.pyplot.imshow

4. Dark Matter (Materia Oscura)
Teoría:
Justificación de la materia oscura:
Discusión sobre las observaciones a nivel galáctico que requieren la inclusión de materia oscura para explicar ciertos comportamientos.
Observación y detección:
Regiones galácticas con potencial de generar señales observables y resumen de los experimentos actuales en la búsqueda de materia oscura.
Práctica:
Visualización y ajuste de curvas:
Análisis de curvas de rotación, perfiles de densidad y distribución de velocidad de la materia oscura en el vecindario solar.
Herramientas específicas:
numpy.histogram
numpy.where
Herramientas de ajuste de curvas en Python (por ejemplo, módulos de ajuste de SciPy)

5. Galaxias
Teoría:
Revisión de relaciones observacionales clave en poblaciones galácticas, tales como:
Relación de Kennicutt-Schmidt: Relación entre la densidad de gas y la tasa de formación estelar.
Relación entre la masa estelar y la masa de los halos (Stellar-to-Halo Mass Ratio).
Relación de Tully-Fisher: Conexión entre la luminosidad (o masa) y la velocidad de rotación.
Discusión sobre publicaciones y resultados observacionales relevantes para cada relación.
Práctica:
Comparación con datos observacionales:
Recuperación de datos publicados utilizando herramientas como WebPlotDigitizer.
Análisis comparativo entre los resultados de las simulaciones y las observaciones documentadas.
Herramientas específicas:
WebPlotDigitizer para extraer datos de gráficos publicados.

6. Catch Up (Repaso y Profundización)
Sesión destinada a repasar los contenidos anteriores, resolver dudas y profundizar en temas que requieran mayor discusión o clarificación.
Espacio para retroalimentación y posible extensión de algunos ejercicios prácticos, en función de las necesidades del grupo.

Notas:
Este programa está diseñado para que los participantes no sólo comprendan los fundamentos teóricos de la evolución galáctica, sino también para que adquieran competencia práctica en el manejo de grandes volúmenes de datos simulados, comparándolos con modelos y observaciones reales. El curso se apoya en Python y sus librerías especializadas, incluso introduciremos posibles usos de herramientas IA, permitiendo una experiencia de aprendizaje integral y actualizada, que une la astrofísica y la programación aplicada.


