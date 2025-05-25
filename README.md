## PAAD 2025
# Grupo 21 Adopción Digital Sena

## Integrantes:

Martha Catalina Cardenas Ortiz

Jhon Nicolas Garzon Rodriguez

Jinneth Carolina Parada Amaya

## Principales Enlaces

Video Presentación: [PAAD 2025 - Grupo 21 Adopción Digital con fines educativos por departamentos de Colombia - Sena](https://youtu.be/kWAqvUXTq8c)

Tablero: [Dashboard - Adopción digital por departamentos](https://lookerstudio.google.com/reporting/30ea9b0b-af30-4292-8a12-193cff8c6e32/page/p_ixlwkaapsd)

Manual de Usuario: [Manual de usuario.pdf](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/blob/main/Manual%20del%20usuario.pdf)

Repositorio: [Github - G21 Adopción digital por departamentos](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/tree/main)

## Otros Entregables:

Prototipo Fachada: [Visualización en MIRO del prototipo](https://miro.com/app/board/uXjVIGoVpIs=/)  Versión en PDF [Prototipo Fachada.pdf](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/blob/main/MIAD%20-%20PAAD%20-%20PAPER%20PROTOTYPE.pdf)

Tabla de requerimientos: [Tabla de requerimientos.pdf](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/blob/main/Tabla%20de%20requerimientos.pdf)

Reporte técnico: [Reporte técnico de selección e implementación de modelos.pdf](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/blob/main/Grupo%2021%20-%20REPORTE%20TE%CC%81CNICO%20SELECCIO%CC%81N%20E%20IMPLEMENTACIO%CC%81N%20DE%20MODELOS.pdf)

Repositorio de Datos: [Datos](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/tree/main/Data)

Repositorio de Códigos: [Códigos](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/tree/main/Codigos)

## Introducción:

Este proyecto tiene como objetivo primordial maximizar la cobertura educativa virtual que el SENA proporciona en el territorio nacional. Reconocemos que la educación virtual constituye una de las principales herramientas contemporáneas para asegurar que la población adquiera las habilidades técnicas y profesionales adecuadas, fundamentales tanto para su desarrollo individual como para el progreso económico global. En consecuencia, nuestro esfuerzo se centra en la formulación de propuestas que propicien un entorno óptimo para la implementación eficiente de esta modalidad educativa a lo largo del país. Para lograrlo, aspiramos a que el SENA, en su rol de institución modelo en formación técnica y tecnológica, se erija como el principal vehículo para la construcción de un ecosistema educativo cimentado en dos principios esenciales: la alta calidad y la facilidad de acceso remoto.

## Descripción del problema

Consideramos que el mayor obstáculo para la formación virtual del SENA radica en su carencia de una planificación y segmentación territorial efectiva. Si bien los programas técnicos y tecnológicos tienen una amplia cobertura nacional, no existe una oferta diferenciada que se alinee con las necesidades y realidades de cada región. Esto genera una percepción de desinterés por parte de los estudiantes hacia estas opciones formativas.

Adicionalmente, la escasa cultura de formación digital en la población colombiana agrava la situación, frenando la adopción de los programas virtuales y desperdiciando así oportunidades cruciales para el crecimiento intelectual y económico del país.

Para hallar una solución, hemos compilado datos de cobertura educativa regional, información de cobertura virtual del SENA, indicadores de habilidades digitales de MINTIC e información de conectividad privada de Ookla. Mediante la consolidación de estos datos y la aplicación del algoritmo K-medias (el cual detallaremos posteriormente), pretendemos proporcionar la base para el diseño de estrategias que optimicen la oferta educativa virtual del SENA, permitiendo la creación de intervenciones adaptadas a las particularidades de cada región.

## Propuesta de valor y Resultados

Consideramos que la clasificación por clusters de los departamentos del país permite reconocer patrones en comportamientos específicos por región, tales como: (Niveles de interés real en acceso a educación virtual, necesidades de infraestructura o conectividad para desarrollar eficientemente los programas educativos, preferencias tematicas o sectoriales por formaciones académicas especifica, entre otros). 

Estos comportamientos y patrones pueden ser aplicados al diseño de estrategias y programas más focalizados en las necesidades territoriales, mejorando el bienestar de los aprendices y sus niveles de satisfacción al incrementar las tasas de enrolamiento en los cursos, reducir las tasas de deserción y principalmente ofrecerles mejores perspectivas laborales en sus respectivas regiones.

Por otro lado, el SENA lograría convertirse en la institución de educación publica más influyente de país, al ser el principal proveedor de mano de obra calificada en el territorio nacional, lo que a su vez puede derivar en el nacimiento de multiples alianzas con el sector privado para fomentar la formación de aprendices adecuados para el mundo empresarial. 

Para generar una segmentación departamental basada en los índices disponibles, se consideraron dos algoritmos de clustering: K-means: y DBSCAN
La técnica de calibración y optimización del modelo utilizada para encontrar los mejores hiperparámetos es GridSearch y El principal criterio de selección fue la capacidad de cada algoritmo para adaptarse a los datos disponibles y generar agrupaciones relevantes. A partir Silhouette Score validamos la coherencia de los grupos, evaluando la similitud de cada punto con aquellos que pertenecen a su mismo cluster.
El resultado de la experimentación y calibración arrojó un modelo de Kmeans que segmenta la información en 9 agrupaciones  con un Silouette score de 0.16 (zona de aceptación).

## Dashboard - Adopción Digital 

Tablero: [Dashboard - Adopción digital por departamentos](https://lookerstudio.google.com/reporting/30ea9b0b-af30-4292-8a12-193cff8c6e32/page/p_ixlwkaapsd)

Manual de Usuario: [Manual de usuario.pdf](https://github.com/CarolinaParada07/PAAD_G21_AdopcionDigitalSena/blob/main/Manual%20del%20usuario.pdf)


## Características 

- No existe una segmentación territorial basada en el nivel de adopción digital educativa en Colombia, por lo que esta propuesta no solo provee una clusterización territorial, sino que abre la puerta a una investigación más profunda.
- No presenta costos iniciales; sin embargo, puede refinarse para ofrecer más funcionalidades.
- Requiere de una constante recolección y actualización de información para ofrecer una perspectiva y un contexto apropiados para la generación de intervenciones.
- No requiere de una infraestructura complicada o costosa para su uso.










