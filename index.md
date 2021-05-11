# The BrainCode Games

## Descripción

BrainCode Games es una **hackaton**, una competición colaborativa cuyo fin último es el desarrollo de una solución a  un problema abierto durante un periodo corto (¡pero muy intenso!) de tiempo. El objetivo de The BrainCode Games es utilizar herramientas de **Inteligencia Artificial** para resolver un problema de **Neurociencia**. Este evento está orientado a estudiantes de grado y de máster, así que no te preocupes si sientes que no tienes conocimientos suficientes. Precisamente, el objetivo final de esta hackaton es enseñar de una manera **didáctica, práctica y divertida** una serie de temas cada vez más demandados (inteligencia artificial, neurociencia y programación), por lo que daremos una serie de **cursillos** previos al evento para prepararte. Recibirás asimismo un **certificado** de asistencia por el número de horas total de participación. Y por supuesto, como competición que es, hay un **premio económico** para los equipos que consigan los mejores resultados.

Si estás interesado/a, inscríbete en este [formulario](https://docs.google.com/forms/d/e/1FAIpQLSdRXJrgS9pzjdWVZeb912Bbw3gX4v5m3-ksiC6zEfrSRlm8cQ/viewform), y síguenos en [Twitter](https://twitter.com/BraincodeGames) e [Instagram](https://www.instagram.com/braincodegames/), donde iremos publicando información referente al evento, y divulgación sobre los temas que trataremos. ¡Ah! Y no te preocupes si no tienes un equipo, te emparejaremos con la persona que más complemente tu formación :grin:

### Información relevante
- Formulario de inscripción: [en este enlace](https://docs.google.com/forms/d/e/1FAIpQLSdRXJrgS9pzjdWVZeb912Bbw3gX4v5m3-ksiC6zEfrSRlm8cQ/viewform)
- Fecha de la hackaton: del 22 al 25 de octubre de 2021
- Fecha de los cursillos: septiembre de 2021
- Será todo online
- Requisitos para inscribirse:
    - Ser estudiante de grado, máster, o recién graduado
    - Participar en equipo
    - Ganas de aprender
- Lenguaje de programación: python
- Premios: hasta 500€ para los equipos con mejores resultados
- Se otorgará un certificado de asistencia por el número de horas de participación

![Image of ripple](https://github.com/TheBrainCodeGames/TheBrainCodeGames.github.io/blob/master/assets/images/descripcion.png)

## Más sobre...

Aquí te explicamos más detalladamente cada uno de los aspectos relacionados con este evento. Si tienes alguna duda, no dudes en escribirnos a braincodegames@gmail.com

### ...el problema abierto

El problema consiste en la detección de ciertos eventos en señales biológicas. Estos eventos, llamados *sharp wave ripples* (o *ripples* para resumir), son unas oscilaciones rápidas como las que se ven señaladas en la imagen. Estos eventos aparecen recurrentemente en nuestros cerebros, y son los encargados de consolidar la memoria. El estudio de los `ripples` nos acerca al entendimiento de los mecanismos que subyacen a la memoria, y muchos laboratorios del mundo centran sus investigaciones alrededor de estos eventos. Se ha demostrado que la interrupción de los `ripples` impide que se generen memorias, y que su prolongación mejore la memoria.

La señal biológica donde se ven los `ripples`, es decir, la representada en la imagen, es conocida como **LFP** (de las siglas *Local Field Potential* en inglés, o potencial de campo). Las neuronas están constantemente cogiendo y soltando iones, y ese flujo eléctrico se traduce en un potencial eléctrico que, sumado a los potenciales eléctricos de las demás neuronas, forman una señal eléctrica lo suficientemente potente como para ser registrada por nuestros aparatos de medición. Por lo tanto, el `LFP` es el potencial eléctrico resultante de la suma de los potenciales eléctricos de todas las neuronas individuales circundantes al electrodo. En la señal de arriba, tenemos 8 electrodos alineados, que miden el `LFP` como en estratos.

La región del cerebro donde suceden los `ripples` se llama **hipocampo**, una zona muy primitiva que se encarga principalmente de la memoria y el procesamiento espacial (es decir, crear un mapa del mundo, la orientación, etc...). En el hipocampo las neuronas están colocadas de tal manera, que esta los potenciales eléctricos individuales se suman de tal manera que no se cancelan entre sí, haciendo que sea muy fácil ver oscilaciones de todo tipo en el `LFP` .

Pues bien, el objetivo de la hackaton es desarrollar un algoritmo utilizando herramientas de inteligencia artificial y *machine learning* para detectar `ripples` en registros de `LFP`. Para ello, os proporcionaremos una base de datos con la señal `LFP` y los tiempos de los `ripples`, etiquetados uno a uno manualmente por una experta. De esta manera podréis utilizar la metodología de aprendizaje supervisado, en el que entrenar un algoritmo para que los detecte. 

Cubriremos todos estos temas más en detalle más adelante.

![Image of ripple](https://github.com/TheBrainCodeGames/TheBrainCodeGames.github.io/blob/master/assets/images/ejemplo_ripple.png)

### ...la hackaton

Una hackathon o hackatón, es un término proviene de las comunidades hacker para referirse a un encuentro de programadores cuyo objetivo es el desarrollo colaborativo de software, pero ahora se utiliza en toda serie de ámbitos. Estos eventos pueden durar entre dos días y una semana. Algunas hackatones tienen propósitos educativos o sociales, aunque en muchos casos el objetivo es crear un software utilizable. En nuestro caso, el propósito es doble :) 

El término integra los conceptos de maratón y hacker, aludiendo a una experiencia colectiva que persigue la meta común de desarrollar aplicaciones de forma colaborativa en un lapso corto.

La hackatón, desde el punto de vista organizativo, supone una dinámica horizontal e intensiva en donde los participantes complementan experiencias y habilidades individuales con el propósito de desarrollar soluciones concretas. De allí que para los especialistas en educación, la hackatón posea ciertas características propias de un dispositivo pedagógico en tanto promueve el trabajo colaborativo entre pares orientado a la resolución de problemas, hace foco sobre el proceso de trabajo como instancia de aprendizaje y favorece la motivación intrínseca de los participantes.

### ...los cursillos

Se impartirán tres charlas-cursillo:

- **Inteligencia Artificial** Se hablará de qué es la Inteligencia Artificial, o *Machine Learning*. Se explicarán diversas formas de atacar diferentes problemas, en función de sus características, centrándonos sobre todo en los algoritmos de aprendizaje supervisado, ya que son los que más se ajustan a nuestro problema. Será impartido por Daniel García-Rincón

- **Neurociencia** Para aquellas personas con perfiles más técnicos, revisaremos los mecanismos que tiene el cerebro para procesar información, empezando desde lo más simple, las neuronas, hasta los circuitos, y cómo estos son capaces de codificar el mundo. Estudiaremos qué son las oscilaciones cerebrales, y cómo las oscilaciones se relacionan con el comportamiento. Será impartido por [Enrique R Sebastian](https://twitter.com/EnrRodSeb)

- **Python** Para aquellas personas con una formación más alejada de la programación, y gente que provenga de otros lenguajes, daremos un cursillo de iniciación a python, poniendo ejemplos desde las sintaxis más habituales hasta pequeños programas donde usemos herramientas de inteligencia artificial que puedan ser aplicables durante la hackaton. Será impartido por [Andrea Navas-Olive](https://twitter.com/acnavasolive)

Tanto los cursillos como el material que subamos a esta web tiene como propósito ofrecer una guía a los/las participantes para estudiar más en profundidad los temas por su cuenta.

### ...qué ganaré con esta experiencia

- Aprenderás temas cada vez más demandados tanto en el mundo de la investigación y la ciencia, como en el mundo empresarial...

- ... y lo harás en un formato que fomenta la ejecución práctica, la colaboración y la diversión

- Trabajarás en un equipo multidisciplinar con el objetivo de resolver un problema en un espacio breve de tiempo

- Y muy posiblemente, un premio, que el dinero nunca viene mal :wink:

## Organización

Este evento está organizado por:

- [Andrea Navas-Olive](https://twitter.com/acnavasolive): Estudiante de Doctorado en Neurociencia Computacional en el [Instituto Cajal - CSIC](http://www.cajal.csic.es/), y profesora en Ingeniería Informática en la [Universidad Autónoma de Madrid (UAM)](https://www.uam.es/uam/inicio)

- [Rodrigo Amaducci](https://twitter.com/AmaducciRodrigo): Estudiante de Doctorado en Neurociencia Computacional y profesor en Ingeniería Informática en la [Universidad Autónoma de Madrid (UAM)](https://www.uam.es/uam/inicio)

- [Enrique R Sebastian](https://twitter.com/EnrRodSeb): Estudiante de Doctorado en Neurociencia Computacional en el [Instituto Cajal - CSIC](http://www.cajal.csic.es/)

-  [Daniel García-Rincón](https://es.linkedin.com/in/darcia-dev): Doctor en Bioquímica, Biología Molecular y Biomedicina por la [Universidad Complutense de Madrid](https://www.ucm.es/), y actualmente Data Scientist en [BBVA Advanced Analytics en Indizen](https://indizen.com/project/bbva-salesforce-marketing-cloud/)

- [Adrián Gollerizo](https://twitter.com/agollerizo): Profesor de Física en [IDEO Escuela](https://www.escuelaideo.edu.es/) y estudiante de Doctorado en Educación en la [Universidad Autónoma de Madrid (UAM)](https://www.uam.es/uam/inicio)

- [Liset M de la Prida](https://twitter.com/acnavasolive): Investigadora Principal del laboratorio [Hippocircuit Lab](http://hippo-circuitlab.es/) en el [Instituto Cajal - CSIC](http://www.cajal.csic.es/)

The BrainCode Games está financiado por la Sociedad Española de Neurociencia (SENC)

<img src="https://github.com/TheBrainCodeGames/TheBrainCodeGames.github.io/blob/master/assets/images/senc_logo_hor.png" alt="Image of SENC" width="600"/>


