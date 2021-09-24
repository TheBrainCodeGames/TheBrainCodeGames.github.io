---
layout: default
---
[English version](./index_en.html)

# The BrainCode Games

## Descripción

The BrainCode Games es una **hackatón**, una competición colaborativa cuyo fin último es el desarrollo de una solución a  un problema abierto durante un periodo corto de tiempo (¡pero muy intenso!). El objetivo de The BrainCode Games es utilizar herramientas de **Inteligencia Artificial** para resolver un problema de **Neurociencia**. No te preocupes si sientes que no tienes conocimientos suficientes. Precisamente, el objetivo final de esta hackatón es enseñar de una manera **didáctica, práctica y divertida** una serie de temas cada vez más demandados (inteligencia artificial, neurociencia y programación), por lo que organizaremos una serie de **cursillos** previos al evento para prepararte. Recibirás asimismo un **certificado** de asistencia por el número de horas total de participación y formación. Y por supuesto, habrá un **premio económico** para los equipos que consigan los mejores resultados.

### Inscripción (Cerrada)

Si estás interesado/a, inscríbete en este **<a href="https://forms.gle/uK6U2gVmhc9wa3SV9" target="_blank">formulario</a>**, y síguenos en <a href="https://twitter.com/BraincodeGames" target="_blank">Twitter</a> e <a href="https://www.instagram.com/braincodegames/" target="_blank">Instagram</a>, donde iremos publicando información referente al evento, y divulgación sobre los temas que trataremos. ¡Ah! Y no te preocupes si no tienes un equipo, te podremos emparejar con la persona que más complemente tu formación :P

### Información relevante
- Formulario de inscripción: <a href="https://forms.gle/uK6U2gVmhc9wa3SV9" target="_blank">en este enlace</a>.
- Fecha de la hackatón: fin de semana del 22 al 25 de octubre de 2021.
- Se impartirán unos cursillos de formación para la participación. Se grabarán y subirán a la web para que puedas verlos siempre que quieras.
- Tanto la hackatón como las cursillos serán online.
- Se dispondrán de medios online para poder hablar y conocernos durante la hackatón.
- Número de plazas limitadas.
- Se favorecerá la inscripción de estudiantes.
- Lenguaje de programación: Python.
- Premios: hasta 500€ para los equipos con mejores resultados.
- Se otorgará un certificado de asistencia.

![Description](/assets/images/descripcion.png)

## Más sobre...

Aquí te explicamos más detalladamente cada uno de los aspectos relacionados con este evento. Si tienes alguna duda, no dudes en escribirnos a nuestro correo electrónico:
**braincodegames@gmail.com**

### ...el problema abierto

El problema consiste en la detección de ciertos eventos en señales electrofisiológicas (que son registros de la actividad eléctrica del sistema nervioso). Estos eventos, llamados *sharp wave ripples* (o *ripples* para resumir), son unas oscilaciones rápidas como las que se ven señaladas en la imagen. Estos eventos aparecen recurrentemente en una región de nuestros cerebros, llamada hipocampo, y son los encargados de consolidar la memoria. El estudio de los `ripples` nos acerca al entendimiento de los mecanismos que subyacen a la memoria, y muchos laboratorios del mundo centran sus investigaciones alrededor de estos eventos. Se ha demostrado que la interrupción de los `ripples` impide que se generen memorias, y que su prolongación mejore la memoria.

![Image of ripple](/assets/images/ejemplo_ripple.png)

La señal biológica donde se ven los `ripples`, es decir, la representada en la imagen, es conocida como **LFP** (de las siglas *Local Field Potential* en inglés, o potencial de campo). Las neuronas están constantemente cogiendo y soltando iones, y ese flujo eléctrico se traduce en un potencial eléctrico que, sumado a los potenciales eléctricos de las demás neuronas, forman una señal eléctrica que puede ser registrada por nuestros aparatos de medición. Por lo tanto, el `LFP` es una señal que refleja la contribución de la actividad de las neuronas individuales circundantes al electrodo. En la imagen de arriba se muestran 8 electrodos alineados, que miden el `LFP` en diferentes puntos del cerebro.

La región del cerebro donde suceden los `ripples` se llama **hipocampo**, una zona muy primitiva que se encarga principalmente de la memoria y el procesamiento espacial (es decir, crear un mapa del mundo, la orientación, etc...). En el hipocampo las neuronas están colocadas de tal manera, que los potenciales eléctricos individuales se suman de tal manera que no se cancelan entre sí, sino que se potencian, haciendo que sea muy fácil ver oscilaciones en el `LFP`.

Pues bien, el objetivo de la hackatón es desarrollar un algoritmo utilizando herramientas de inteligencia artificial y *machine learning* para detectar `ripples` en registros en una serie temporal como es el `LFP` (sampleado a 1250 Hz). Para ello, os proporcionaremos una base de datos con la señal `LFP` y los tiempos de los `ripples`, etiquetados uno a uno manualmente por nuestra experta. De esta manera podréis utilizar la metodología de aprendizaje supervisado, y entrenar un algoritmo para que los detecte. 

Cubriremos todos estos temas en detalle más adelante.

### ...la hackatón

Una hackathon o hackatón, es un término proviene de las comunidades hacker para referirse a un encuentro de programadores cuyo objetivo es el desarrollo colaborativo de software, pero ahora se utiliza en toda serie de ámbitos. Estos eventos pueden durar entre dos días y una semana. Algunas hackatones tienen propósitos educativos o sociales, aunque en muchos casos el objetivo es crear un software utilizable. En nuestro caso, el propósito es doble, aplicar herramientas de IA a neurociencia, mientras enseñamos la metodología de manera didáctica :) 

El término integra los conceptos de maratón y hacker, aludiendo a una experiencia colectiva que persigue la meta común de desarrollar aplicaciones de forma colaborativa en un lapso corto.

La hackatón, desde el punto de vista organizativo, supone una dinámica horizontal e intensiva en donde los participantes complementan experiencias y habilidades individuales con el propósito de desarrollar soluciones concretas. De ahí que para los especialistas en educación, la hackatón posea ciertas características propias de un dispositivo pedagógico en tanto promueve el trabajo colaborativo entre pares orientado a la resolución de problemas, hace hincapié sobre el proceso de trabajo como instancia de aprendizaje y favorece la motivación intrínseca de los participantes.

Las hackatones son, además, un estilo cada vez más frecuente de contratación en el mundo empresarial. 

### ...los cursillos

Se impartirán tres charlas-cursillo:

- **Inteligencia Artificial:** Se hablará de qué es la Inteligencia Artificial, o *Machine Learning*. Se explicarán diversas formas de atacar diferentes problemas, en función de sus características, centrándonos sobre todo en los algoritmos de aprendizaje supervisado, ya que son los que más se ajustan a nuestro problema. Será impartido por <a href="https://es.linkedin.com/in/darcia-dev" target="_blank">Daniel García-Rincón</a>.

- **Neurociencia:** Para aquellas personas con perfiles más técnicos, revisaremos los mecanismos que tiene el cerebro para procesar información, empezando desde lo más simple, las neuronas, hasta los circuitos, y cómo estos son capaces de codificar el mundo. Estudiaremos qué son las oscilaciones cerebrales, y cómo las oscilaciones se relacionan con el comportamiento. Será impartido por <a href="https://twitter.com/EnrRodSeb" target="_blank">Enrique R Sebastian</a>.

- **Python:** Para aquellas personas con una formación más alejada de la programación, y gente que provenga de otros lenguajes, daremos un cursillo de iniciación a python, poniendo ejemplos desde las sintaxis más habituales hasta pequeños programas donde usemos herramientas de inteligencia artificial que puedan ser aplicables durante la hackatón. Será impartido por <a href="https://twitter.com/acnavasolive" target="_blank">Andrea Navas-Olive</a>.

Tanto los cursillos como el material que subamos a esta web tiene como propósito ofrecerte una guía para que puedas estudiar más en profundidad los temas por tu cuenta.

### ...qué ganaré con esta experiencia

- Aprenderás temas cada vez más demandados tanto en el mundo de la investigación y la ciencia, como en el empresarial.

- ... y lo harás en un formato que fomenta la ejecución práctica, la colaboración y la diversión.

- Trabajarás en un equipo multidisciplinar con el objetivo de resolver un problema en un espacio breve de tiempo.

- Y muy posiblemente, un premio, que el dinero nunca viene mal ;) 

## Organización

Este evento está organizado por:

- <a href="https://twitter.com/acnavasolive" target="_blank">Andrea Navas-Olive</a>: Estudiante de Doctorado en Neurociencia Computacional en el <a href="http://www.cajal.csic.es/" target="_blank">Instituto Cajal - CSIC</a>, y profesora en el Grado en Ingeniería Informática de la <a href="https://www.uam.es/uam/inicio" target="_blank">Universidad Autónoma de Madrid (UAM)</a>.

- <a href="https://twitter.com/AmaducciRodrigo" target="_blank">Rodrigo Amaducci</a>: Estudiante de Doctorado en Neurociencia Computacional y profesor del Grado en Ingeniería Informática de la <a href="https://www.uam.es/uam/inicio" target="_blank">Universidad Autónoma de Madrid (UAM)</a>.

- <a href="https://twitter.com/EnrRodSeb" target="_blank">Enrique R Sebastian</a>: Estudiante de Doctorado en Neurociencia Computacional en el <a href="http://www.cajal.csic.es/" target="_blank">Instituto Cajal - CSIC</a>.

- <a href="https://es.linkedin.com/in/darcia-dev" target="_blank">Daniel García-Rincón</a>: Doctor en Bioquímica, Biología Molecular y Biomedicina por la <a href="https://www.ucm.es/" target="_blank">Universidad Complutense de Madrid</a>, y actualmente Data Scientist en BBVA Advanced Analytics en Indizen.

- <a href="https://twitter.com/agollerizo" target="_blank">Adrián Gollerizo</a>: Profesor de Física en <a href="https://www.escuelaideo.edu.es/" target="_blank">IDEO Escuela</a> y estudiante de Doctorado en Educación en la <a href="https://www.uam.es/uam/inicio" target="_blank">Universidad Autónoma de Madrid (UAM)</a>.

- <a href="https://twitter.com/lmprida" target="_blank">Liset M de la Prida</a>: Investigadora Principal del laboratorio <a href="http://hippo-circuitlab.es/" target="_blank">Hippocircuit Lab</a> en el <a href="http://www.cajal.csic.es/" target="_blank">Instituto Cajal - CSIC</a>.

The BrainCode Games está financiado por la Sociedad Española de Neurociencia (SENC) y la Universidad Autónoma de Madrid (UAM).

<img src="/assets/images/senc_logo_hor.png" alt="Image of SENC" width="600"/>

<img src="/assets/images/logo_uam.png" alt="Image of UAM" width="600"/>




