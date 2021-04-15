*Nota: Actualmente se encuentra en construcción.*

## Tabla de contenidos
1. [Acerca del FAQ](#acerca)  
2. [Disclaimer](#disclaimer)
3. [¿Quiénes somos?](#quienes)
4. [FAQ](#faq)
    1. [¿Qué es la seguridad informática?](#que-es)
    2. [¿Qué es ser hacker?](#hacker)
    3. [¿Qué cosa no es?](#que-no)
    4. [¿Cuáles son las grandes ramas de la seginfo?](#ramas)
    5. [No arranqué de jóven, ¿es tarde para mí?](#arrancar-joven)
    6. [Quiero hackear, pero no se qué estudiar, ni dónde, ¿qué hago?](#que-estudiar)
    7. [Lo que me da la universidad no es lo que quiero, ¿qué hago?](#universidad-quiero)
    8. [¿Creen que es necesario crear una carrera de seguridad informática?](#necesario-carrera)
    9. [¿Qué acercamiento se tiene desde la seguridad con respecto a la educación que se brinda hoy en día?](#educacion)
    10. [¿Son recomendables las certificaciones?](#certificaciones)
    11. [¿Cuál es la mejor manera de aprender?](#manera-aprender)
    12. [¿Que sería lo básico que necesito para la seguridad informática?](#conocimiento-basico)
    13. [¿Qué perfiles se encuentran en el mundo laboral?](#perfiles-laborales)
    14. [¿Por qué hay más foco en lo ofensivo que en lo defensivo?](#foco)
    15. [¿Cómo ven el futuro de la seguridad informática?](#futuro)
    16. [Si recién empiezo, ¿es un desperdicio ir a una conferencia?](#comenzar-conferencia)
    17. [Red Team, Pentesting, ¿son todos lo mismo?](#redteam-pentest)
    18. [Más allá de las ramas, ¿qué cosas se pueden hacer?](#que-mas-ramas)
    19. [¿Hay algún mapa de todos los dominios que abarca la cyberseguridad?](#mindmap)
    
5. [Conclusión](#conclusión)
6. [Recomendaciones generales](#recomendaciones)
7. [Más información](#mas-info)
    1. [Glosario](#glosario)
    2. [Cursos gratuitos](#cursos-gratuitos)
    3. [Guías en español](#guias-es)
    4. [Guías en inglés](#guias-en)
    5. [Lecturas recomendadas](#lecturas)
    6. [Canales de YouTube](#canales-de-yt)
    7. [Podcasts](#podcasts)
    8. [Instituciones que tratan la seguridad](#instituciones-seg)
    9. [Películas & Series](#pelis-series)
    10. [Documentales](#documentales)
8. [Eventos públicos](#eventos)
    1. [Meetups](#meetups)
    2. [Conferencias](#conferencias)
    3. [Infosec Twitter](#infosec-twitter)
9. [Referencias](#referencias)
10. [Proving grounds (mentorship)](#mentorship)
11. [Salida laboral](#salida-laboral)

# Acerca de este FAQ
<a name="acerca"/>

La idea de este documento es combatir un poco la desinformación, remover ambigüedades, despejar dudas, y crear un espacio en el que podamos referenciar a futuro como un lugar de partida para cualquier persona que quiera introducirse en la seguridad informática.

La propuesta no se focaliza en *enseñar habilidades técnicas*, sino en orientar un poco a quienes necesiten una ayuda, se encuentran perdidos ó no saben cómo armarse camino en esta profesión.

# Disclaimer
<a name="disclaimer"/>

Toda la información contenida en este documento, es una recopilación personal abierta, por lo tanto es subjetiva, y no está sujeta a ninguna verdad absoluta.

# ¿Quiénes somos?
<a name="quienes"/>

Amigos, colegas, conocidos; un grupo de personas apasionadas de la seguridad informática, que viven de ello (en su mayoría), y comparten desde la empatía con todos los que están en esta situación de iniciación al aprendizaje o desconcierto, ya que hemos estado allí.

Andrés Riancho, Federico Pacheco, Gustavo M. Sorondo, María Jośe Erquiaga, Martin Gallo, Matías A. Ré Medina, Nicolás Waisman, Sebastián Bortnik, Sebastián García, Sheila Berta, Verónica Valeros.

También agradecemos a Patricio Palladino por su feedback.

# FAQ
<a name="faq"/>

## ¿Qué es la seguridad informática?
<a name="que-es"/>

También conocida como ciberseguridad, está definida de la siguiente manera por ISACA (Information Systems Audit and Control Association):

> Protección de activos de información, a través del tratamiento de amenazas que ponen en riesgo la información que es procesada, almacenada y transportada por los sistemas de información que se encuentran interconectados"

## ¿Qué es ser hacker?
<a name="hacker"/>

Según la RAE, existen dos definiciones:
- Pirata informático
- Persona experta en el manejo de computadoras, que se ocupa de la seguridad de los sistemas y de desarrollar técnicas de mejora.

No reconocemos la primera definición, y seguimos sin entender por qué la segunda fue incorporada sin desplazar a la primera.

Un hacker NO es un pirata informático.

Entendemos por *hacker* a una palabra que no está sólo arraigada a la seguridad informática, sino a la habilidad para poder encontrar funcionalidades en *cosas* que originalmente no fueron destinadas para ese uso, más allá del contexto.

Un ejemplo de *hackers* que utilizan otros tipos de tecnologías, no necesaria y únicamente informática, es la de los perfiles que se dedicaron a estudiar en la psicología el comportamiento humano, la persuasión, y de esa manera obtener información sensible. Esto es más conocido como *ingeniería social* (ver glosario). 

_[Introducir más ejemplos]_

## ¿Qué cosa no es?
<a name="que-no"/>

 * Una profesión estática donde es posible alcanzar un conocimiento pleno
 * La mayoría de las cosas que vemos en las noticias y películas* (si llegaste aquí por las escenas de hacking de distintas peliculas, eso definitivamente no es)
 * Hackear la cuenta de facebook de la pareja de un amigo

(*) Al final del documento hay buenas recomendaciones por si quieren mirar algo que se asemeje un poco más a la realidad ;)

## ¿Cuáles son las grandes ramas de la seginfo?
<a name="ramas"/>

A nivel organizacional, se podría separar en, pero no limitada a:

**Defensiva (Blue team)**
Equipo de personas que defiende una organización de atacantes externos. A diferencia de los equipos que se encargan de asegurar sistemas acorde a estándares o para que cumplan ciertas normativas (ver *compliance* en glosario), estos están en constante vigilia protegiendo a la organización.

Una parte que no está *tan* utilizada, al menos en las pequeñas empresas, o es considerada poco popular.

**Ofensiva (Red team)**
Son en general equipos externos a la organización que testean la seguridad de los sistemas utilizando técnicas similares a las que utilizarían atacantes reales.

Esta rama de la profesión tiene fama de ser más divertida y desafiante que otras, ya que hay que encontrar debilidades en sistemas que, en teoria al menos, han sido configurados y desarrollados para ser seguros.

La mayoría de las consultoras de seguridad informatica realizan este tipo de servicios.

Muchos lo confunden con Vulnerability Assesment o Penetration Testing, que tienen sus diferencias (ver sección xx)


## No arranqué de jóven, ¿es tarde para mí?
<a name="arrancar-joven"/>

No hace falta haber hackeado la NASA a los 12 años para poder dedicarte a la seguridad informática el resto de tu vida, ni tener un background *sólido* para comenzar, ni una edad en particular.

Hay que tener ganas, y saber organizarse con el tiempo. Entendemos que todas las situaciones son distintas, pero hey, nadie los corre, así que a disfrutar que es un proceso hermoso de aprendizaje, y si no lo está siendo para vos, ojalá que este documento te motive un poco :)

## Quiero hackear, pero no se qué estudiar, ni dónde, ¿qué hago?
<a name="que-estudiar"/>

No está tan claro el camino, no te preocupes. No hay un lugar específico a donde ir así como los hay en otro tipo de *carreras laborales* donde está más trazado. Si bien existen carreras que son complementarias, no es el único camino a seguir.

Algunas de las carreras universitarias que pueden ayudarte son las relacionadas con la informática, como ciencias de la computación e ingeniera informática. Aunque en estas carreras veas poco de seguridad informatica, vas a entender como funcionan las computadoras por dentro y eso te da una gran ventaja a la hora de intentar identificar vulnerabilidades o solucionarlas.

Elegí lo que te quede más cómodo, recomendamos hacerlo de una manera progresiva para no frustrarte con cosas complicadas desde un principio, y a partir de que se van ganando más conocimientos también se va entendiendo un poco más el panorama, para ese entonces seguramente encontraste algo que te apasionó, y sino revisitar este artículo de ser necesario para volver a orientarse.

## Lo que me da la universidad no es lo que quiero, ¿qué hago?
<a name="universidad-quiero"/>

Si bien creés que no te dá lo que querés de manera inmediata porque en las prácticas no estás sacudiendo exploits y apoderándote de las máquinas de tus compañeros (nota: no lo hagas sin su consentimiento), las carreras de sistemas tienen un aporte y una formación que es sumamente útil.

Más allá de la universidad, y el título, si aprovechás cada materia, y la pivoteás para el lado de la seguridad, podés aprender un montón, e ir haciendo en paralelo tu propia carrera complementaria con lo que ves ahí. Y, si además conseguís algún titular que te segundee para que en los trabajos prácticos haya la flexibilidad suficiente para poder incoporporar este complemento del que hablamos, muchísimo mejor.

## ¿Creen que es necesario crear una carrera de seguridad informática?
<a name="necesario-carrera"/>

No nos parece indispensable, ya que como hablamos, las maneras de aprender son varias. Sin embargo estaría bueno sí, al menos como puerta de entrada, y para salir un poco de que la seguridad sólo esté en posgrados o maestrías únicamente (*).

Por otro lado, no nos gustaría que en el caso de que exista, se utilice para diferenciar a quienes lo tengan de quienes no, como especie de discriminación, más en un ambiente tan autodidacta como en el que nos encontramos.

(*) Ha habido propuestas pero no han tenido éxito porque en su momento no ha existido el flujo necesario como para que se justifique crear una. Para ello es importante comenzar con optativas, cursos, orientadas a seguridad, empezar a generar más movimiento en el ambiente, hasta que eventualmente termine en algo más extenso que justifique incluirse en un plan académico.

## ¿Qué acercamiento se tiene desde la seguridad con respecto a la educación que se brinda hoy en día?
<a name="educacion"/>

De a poco vamos *ganando terreno*, mediante concientización. Estamos inculcando de a poco que la seguridad es algo que se aplica como parte del proceso de desarrollo de las aplicaciones, sistemas, y no como algo que viene después.

Es algo que eventualmente, con el tiempo, va a llegar.

## ¿Son recomendables las certificaciones?
<a name="certificaciones"/>

Dependiendo del tipo de certificado. No son algo *necesario*, ni un requisito para poder aprender. Algunas empresas los exigen por cuestiones burocráticas o clientes para demandar una compliance[ref] de algún tipo.

Pero una certificación no te enseña, simplemente son distintos mecanismos de verificación para validar lo que uno ya sabe hasta es momento.

Es más fácil hablar de las que nos parecen relevantes, que las que no. Reconocemos que la certificación OSCP es muy interesante, ya que envuelve aplicar en práctica un montón de conocimientos para tomar control de distintas máquinas a través de múltiples técnicas en un plazo de 24hs. A diferencia de otras certificaciones que solamente requieren responder preguntas teóricas multiple choice.

## ¿Cuál es la mejor manera de aprender?
<a name="manera-aprender"/>

Lo importante acá nos parece diferenciar el hecho de aprender algo y eventualmente tener la capacidad para demostrarlo.

Lo que está claro es que uno lo podría hacer en la universidad, estudiando para una certificación, de material de internet o experimentando. ¡La que a vos te sirva!

Es un campo muy versátil y en crecimiento, en el que ningún perfil es incorrecto.

*Sean responsables de sus estudios*, si sienten que la universidad ya no lo es, no gasten energía en culparla, busquen en otro lado. Si sienten que necesitan una estructura porque solos no pueden, vayan a la universidad. Si ambos caminos no sirvieron sigan buscando que eventualmente lo van a encontrar, y quién sabe, tal vez abran las puertas para darle camino a mucha gente que estuvo en su misma situación.

## ¿Que sería lo básico que necesito para la seguridad informática?
<a name="conocimiento-basico"/>

No queremos cerrarnos a decir que hay un básico, porque estaríamos cayendo en una generalización y es sumamente abarcativa. Está claro que mientras más conocimientos poséan mejor van a poder encarar cada situación.

No hay ningún curso mágico de 6 meses que les vaya a dar lo básico para cubrir un todo. Sí existen cursos y diplomaturas que les pueden dar un paneo general para ayudarlos a empezar a definir este camino propio del que tanto hablamos, en el cual te terminarás dando cuenta que para poder hacer ingeniería inversa (reverse engineering) necesitás arrancar como base a programar, entender como funcionan los lenguajes de programación, compiladores, y assembler, por ejemplo.

Hay un montón de material online, de cursos gratuitos en distintas plataformas (ver guías y cursos recomendados) que son útiles como puntos de partida y pueden brindar un lindo insight.

## ¿Qué perfiles se encuentran en el mundo laboral?
<a name="perfiles-laborales"/>

Gente recibida, con posgrados, doctorados, haciendo la universidad, que dejó la universidad, que nunca fué a la universidad y estudió sólo por su cuenta, que no terminó el colegio, y más.

La diversidad, en general, es algo que aporta positivamente en los equipos de trabajo. Mientras más diversidad, más puntos de vista y perspectivas distintas se pueden traer a la mesa. Y digamos que el hacking se trata un poco de eso, de tener la capacidad de poder observar las cosas desde distintos lugares.

En resumen, hay de todo :)


## ¿Por qué hay más foco en lo ofensivo que en lo defensivo?
<a name="foco"/>

Atacar es más divertido que defender, y defender es más difícil que atacar.

Desarrollar una técnica de defensa es muchísimo más complejo porque tiene que funcionar para TODOS los ataques, y atacar sólamente tiene que funcionar contra ESA particular defensa. El nivel de dificultad está dado por esa asimetría.

También hay muchas investigaciones atacando mecanismos de seguridad, pero que no llegaron a ser una charla, posiblemente ya que no lograron finalmente romperlos, y hay una verdad y es que en algunas conferencias es más atractivo mostrar casos en los que sí.

## ¿Cómo ven el futuro de la seguridad informática?
<a name="futuro"/>

Hace años en Argentina muchos clientes venían a nosotros cuando ya les había ocurrido un problema, cero proactividad. Luego de ser auditados otros tenían esa sensación de seguridad que les duraba años, o hasta que volvieran a tener un inconveniente. Con el tiempo fueron contratándonos de maneras más periódicas, al comenzar cada proyecto, e incluso ofrecernos como servicios como parte de los suyos.

Hoy en día, luego de campañas de concientización, en el incremento en los ataques informáticos, y muchas variables más, hemos llegado al punto en el que algunas de esas empresas que mencionábamos, hoy en día tienen equipos de *Blue team* y/o conducen auditorías regularmente.

## Si recién empiezo, ¿es un desperdicio ir a una conferencia?
<a name="comenzar-conferencia"/>

En absoluto. Incluso nosotros con años de experiencia, siempre nos encontramos con muchas charlas de las cuales no entendemos su mayoría, pero porque también esa es la idea, que los disertantes expongan investigaciones interesantes, muchas de ellas super específicas, a las que dedicaron la gran mayor parte de su tiempo, y contra alguien que se dedicó de lleno a un tema en específico no hay punto de comparación.

Recomendamos ir a todas las conferencias que les parezcan interesantes, y disfrutarlas. No frustrarse si no entienden, porque no están diseñadas para que todos entiendan todo.

Algo positivo que tiene en general este ambiente, por lo menos en Argentina, es que la mayoría de nosotros siempre tenemos un momento para charlar con interesados, así que si tienen dudas las pueden despejar en persona con el mismo disertante de la charla.

¡No dejes de ir a meetups! Existen varios meetups en Argentina que estan relacionados con seguridad informática, son reuniones periodicas, con audiencias reducidas y un par de charlas. Te van a servir para aprender de temas nuevos y conocer gente!

El social networking, o dicho de otra manera conocer gente, interactuar, socializar, hacer contactos es sumamente valioso y estos espacios existen para ello.

## Red Team, Pentesting, ¿son todos lo mismo?
<a name="redteam-pentest"/>

Penetration Test, Vulnerability Assessment, y Red Team Assessment no son sinónimos, aunque a veces algunas empresas los utilicen intercambiadamente.

**Penetration testing**, más conocido como pentesting, es básicamente encontrar vulnerbilidades y errores de configuración conocidos, y tratar de explotarlos para obtener la mayor cantidad de accesos posibles en un determinado tiempo.

**Red Team Assessment** es similar al pentesting, sólo que el objetivo no es conseguir más accesos ni vulnerabilidades, sino obtener información sensible de la manera más sigilosa posible, entendiendo cómo la empresa responde a este tipo de situaciones y reacciona ante ellas. Se incluyen técnicas de ingeniería social, seguridad física, hacking de dispositivos electrónicos, biométricos, wireless y más.

**Vulnerability Assesment** se podría interpretar como la actividad que engloba encontrar vulnerabilidades en los sistemas, y asesorar a la empresa en cuestión sobre cómo prevenir futuros ataques que las exploten.

Para todos los casos el equipo de profesionales que trabaja en el proyecto realiza un informe detallado para que la organización contratante pueda resolver los problemas detectados.

## Más allá de las ramas, ¿qué cosas se pueden hacer?
<a name="que-mas-ramas"/>

Se podrían definir muchos perfiles laborales, y la verdad que ninguno está limitado a solamente su área, generalmente para trabajar en cada área necesitás un poco de expertise en las otras. Es decir, si estás analizando una aplicación móvil compleja en Objective C (por decir algún lenguaje), también vas a necesitar entender posiblemente algo de critografía y protocolos de internet para poder hacer un buen trabajo.

Algunas de las categorías, en inglés, son las siguientes:
- Networking: aplicar seguridad en redes, protocolos.
- Application: aplicar seguridad en la capa de aplicación.
- Mobile: hacer análisis de aplicaciones móbiles.
- Malware/Spyware Analysis: analizar comportamientos de malware.
- Risk Audit/Management: análisis de riesgos.
- Forensics: técnicas forenses.
- Penetration Testing: tests de penetración.
- Systems security (user level, kernel, os): aplicación de técnicas de seguridad a nivel sistemas operativos, cloud.
- Crypyography: testear, crear o romper seguridad relacionada a algoritmos criptográficos o sistemas de cifrados.

## Mapa de los dominios de la cyberseguridad
<a name="mindmap"/>

No dejen que este mapa, que es tan sólo una representación de las temáticas, los intimide.

Muchas de estos *dominios* generalmente se ven solapados, otros ya a esta altura los saben o se dan una buena idea si miran con atención, por ejemplo "Desarrollo profesional" y "Análisis de riesgos".

Créditos [Henry Jiang](https://www.linkedin.com/pulse/map-cybersecurity-domains-version-20-henry-jiang-ciso-cissp).
![Mapa dominios cyberseguridad](./Cybersecurity%20Domains%20v2%20Spanish.png)

# Conclusión
<a name="conclusion"/>

Cada uno arma su propio camino, no hay una forma única de hacer esto. Esto es muy nuevo para todo el mundo. Así como nosotros tomamos decisiones en ese momento para ver como podíamos ir mejorando, ustedes deberán hacer lo mismo.

Hay que entender que probablemente uno no venga con una pasión adentro, está bueno utilizar la curiosidad como motor, probando, buscando, experimentando. Es cuestión de

Hackeá tu propio camino al hacking :)

# Recomendaciones generales
<a name="recomendaciones"/>

- Comenzá progresivamente. No te frustres, todos estuvimos ahí, y eso que te está costando ya lo vas a lograr.
- No te compares con otros, no tiene sentido. Solo comparate con quien eras hace un par de meses, si mejoraste entonces vas por buen camino.
- Aprendé idiomas, particularmente inglés ya que en él está el mayor caudal de información del cual aprendimos. Por suerte hay bastante material en español también, pero muchas son traducciones.
- No pongan afuera la responsabilidad de aprender, está en ustedes. Busquen lo que les sirva, y si no sirve, se cambia.
- Conocete a vos mismo, entendé que te sirve, si estudiar en tu casa, asistir a eventos, asistir a educación pública/privada, lo que sea que te sirva está bien.

# Más información
<a name="mas-info"/>

## Glosario
<a name="glosario"/>

Se ha creado un documento a parte para el glosario [aquí](Glosario.md).

## Cursos gratuitos
<a name="cursos-gratuitos"/>

Se encuentran cursos gratuitos en todas las siguientes plataformas, los idiomas pueden variar. En el futuro agregaremos links a los cursos más recomendados.
- Coursera
- edX
- Cybrary
- CodeAcademy
- Udemy
- Stanford
- Cardiff
- MIT OpenCourseware

## Links de gran utilidad en Español
<a name="guias-es"/>

- [Guía de auto-estudio para la escritura de exploits - Fundación Sadosky](https://fundacion-sadosky.github.io/guia-escritura-exploits)
- [Web Security Checklist en español (una "hoja de ruta" ideal para Bug Bounty & Pentesting)](https://github.com/alanbriangh/Magic-CheckList-for-Web-Applications)
- [Artículos en Español subidos a Exploit Database](https://www.exploit-db.com/papers?language=spanish)


## Links de gran utilidad en Inglés
<a name="guias-en"/>

- [Web Security Academy @ PortSwigger](https://portswigger.net/web-security)
- [Which Programming Language Should I Learn First? @ Carlcheo](http://carlcheo.com/startcoding)

## Lecturas recomendadas
<a name="lecturas"/>

Todos los libros o su gran mayoría hasta el momento poseen su traducción (si es que no están ya presentados en español), la razón por la cual están listados en inglés se debe a que son más fáciles de encontrar a la hora de comprarlos.

### Español
- [Introducción a DevOps y DevSecOps](https://devsecops-argentina.org/contenidos/introduccion-a-devops-y-devsecops.pdf)
- [DevSecOps Security testing Automation](https://devsecops-argentina.org/contenidos/devsecops-ast.pdf)
- [KEEP CALMS AND DEV SEC OPS](https://devsecops-argentina.org/contenidos/ebook-devsecops-calms.pdf)
- [Criptografía by Fede Pacheco. RedUSERS](https://www.goodreads.com/book/show/24647630-criptograf-a)
- [Web Hacking by Sheila Berta. RedUSERS](https://www.goodreads.com/book/show/43289029-web-hacking)
- [Qué es la seguridad informática, by Hugo D. Scolnik](https://www.goodreads.com/book/show/27871413-qu-es-la-seguridad-inform-tica)
- [Ethical Hacking: Un Enfoque Metodológico Para Profesionales, by Ezequiel Martin Sallis](https://www.goodreads.com/book/show/10408503-ethical-hacking)
- [Seguridad informática - Hacking Ético: Conocer el ataque para una mejor defensa (3ª edición)](https://books.google.com.ar/books/about/Seguridad_inform%C3%A1tica_Hacking_%C3%89tico.html?id=4X32wbgtNfUC&printsec=frontcover&source=kp_read_button&redir_esc=y#v=onepage&q&f=false)
- [Ethical Hacking 2.0: Implementación de un sistema para la gestión de la seguridad](https://www.goodreads.com/book/show/23705212-ethical-hacking-2-0)

### Destacados
- The Art of Software Security Assessment: Identifying and Preventing Software Vulnerabilities - Mark Dowd

### Entendimiento general

#### Fundamental
- Operating System Concepts Essentials - Abraham Silberschatz, Peter B. Galvin, Greg Gagne
- Computer Networks - Andrew S. Tanenbaum

#### Holístico
- Accelerate: Building and Scaling High-Performing Technology Organizations - Nicole Forsgren, Jez Humble, Gene Kim
- The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win - Gene Kim,  Kevin Behr, George Spafford

#### Concientización
- [Vigilancia Permanente, by Edward Snowden](https://www.goodreads.com/book/show/52043209-vigilancia-permanente)

## Podcasts
<a name="podcasts"/>

- [Secure Podcast](https://open.spotify.com/show/0TZOiNDNsTnfMltIvrCkmY): podcast desestructurado sobre infosec.
- [El Tao Del Hacking](https://open.spotify.com/show/5ZqkzIfpgknpCq6mx1yKG5?si=uqyxLMFuTD2uTYf_iSfgaQ): dedicado a la educación en seguridad de la información.

## Instituciones que tratan la seguridad
<a name="instituciones-seg"/>

- [UTNBA Buenos Aires - Diplomatura en Seguridad de la Información](https://sceu.frba.utn.edu.ar/course/diplomatura-en-seguridad-de-la-informacion/)


## Películas & Series
<a name="pelis-series"/>

- [Hackers (1995)](https://www.imdb.com/title/tt0113243/): Un clásico.
- [The Fifth State (2013)](https://www.imdb.com/title/tt1837703): Película basada en la historia de WikiLeaks.
- [Snowden (2016)](https://www.imdb.com/title/tt3774114/): Película basada en la historia de Snowden.
- [Mr. Robot (2015–2019)](https://www.imdb.com/title/tt4158110/): La serie que históricamente tiene más contenido real del mundo del hacking.

## Documentales
<a name="documentales"/>

- [Documental sobre DEFCON (2012)](https://www.youtube.com/watch?v=3ctQOmjQyYg): Documental sobre la conferencia más antigua y grande del mundo. 
- [We Are Legion: The Story of the Hacktivists (2013)](https://www.imdb.com/title/tt1837703): Documental sobre 4chan, el subforo /b/, el surgimiento de Anonymous y LulzSec.
- [The Pirate Bay: Away From Keyboard (2013)](https://www.imdb.com/title/tt2608732): Documental sobre The Pirate Bay, su historia, sus juicios, y su permanencia.
- [We Steal Secrets: The Story of WikiLeaks (2013)](https://www.imdb.com/title/tt1824254/): La historia de WikiLeaks.
- [Internet's own boy (2014)](https://www.imdb.com/title/tt3268458): Documental sobre Aaron Swartz, y el mal manejo del poder del gobierno para sentar un ejemplo contra el hacktivismo.
- [Citizenfour (2014)](https://www.imdb.com/title/tt4044364/): Documental sobre Edward Snowden, whistleblower de la NSA.
- [Risk (2016)](https://www.imdb.com/title/tt4964772/): La íntima historia de Julián Assagne, fundador de WikiLeaks.
- [The Great Hack (2019)](https://imdb.com/title/tt9358204/?ref_=nv_sr_srsg_0): Documental sobre el escándalo con Cambridge Analytica (Facebook, campaña de Trump).
- [iHuman (2019)](https://www.imdb.com/title/tt11279794/): Documental sobre inteligencia artificial relacionado a la privacidad.

## Canales de YouTube
<a name="canales-de-yt"/>

- [Ekoparty](https://www.youtube.com/channel/UCiVNwNkoMapaeyr9o6XEonA)
- [LiveOverflow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w)
- [Hackear](https://www.youtube.com/channel/UCbA9L1AhdzoTN1FWuQCTn9Q/featured)
- [GynvaelEN](https://www.youtube.com/channel/UCCkVMojdBWS-JtH7TliWkVg)
- [IppSec](https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA)
- [Murmus CTF](https://www.youtube.com/channel/UCUB9vOGEUpw7IKJRoR4PK-A)
- [MalwareAnalysisForHedgehogs](https://www.youtube.com/channel/UCVFXrUwuWxNlm6UNZtBLJ-A)
- [Colin Hardy](https://www.youtube.com/channel/UCND1KVdVt8A580SjdaS4cZg)
- [13Cubed](https://www.youtube.com/channel/UCy8ntxFEudOCRZYT1f7ya9Q)
- [Guided Hacking](https://www.youtube.com/user/L4DL4D2EUROPE)
- [Stephen Chapman](https://www.youtube.com/user/seowhistleblower)
- [PwnFunction](https://www.youtube.com/channel/UCW6MNdOsqv2E9AjQkv9we7A)

# Eventos públicos
<a name="eventos"/>

## Meetups
<a name="meetups"/>

- [TandilSec](https://www.meetup.com/TandilSec/) - [@TandilSec](https://twitter.com/tandilsec) - Tandil, Provincia de Buenos Aires
- [R'lyeh Hacklab](https://rlab.be/) - [@rlyehlab](https://twitter.com/rlyehlab) - Ciudad de Buenos Aires
- [Security Jam](https://twitter.com/securityjam) - Ciudad de Buenos Aires
- [404 Zone](https://404zone.com/) - [@404Zone](https://twitter.com/404Zone) - Ituzaingó, Provincia de Buenos Aires
- [Application Security BA](https://www.meetup.com/app-sec-ba/) - Ciudad de Buenos Aires

## Conferencias
<a name="conferencias"/>

- [Ekoparty security conference](https://ekoparty.org/) - [@ekoparty](https://twitter.com/ekoparty) - Ciudad de Buenos Aires
- [Andsec conference](https://andsec.org/) - [@andseccon](https://twitter.com/andsec) - Ciudad de Buenos Aires
- [ParanaConf](https://www.paranaconf.org/) - [@paranaconf](https://twitter.com/ParanaConf) - Paraná, Entre Ríos
- [PampaSeg](https://www.pampaseg.org/) - [@pampaseg](https://twitter.com/PampaSeg) - Santa Rosa, La Pampa
- [BSidesCordoba](https://bsidescordoba.org/) - [@bsidesar](https://twitter.com/BSidesAR) - Córdoba, Córdoba

## Infosec Twitter
<a name="infosec-twitter"/>

Estas son algunas de las cuentas más activas o útiles que te recomendamos seguir:
- [@BSidesAR](https://twitter.com/BSidesAR)
- [@devsecops_ar](https://twitter.com/devsecops_ar)
- [@DragonJAR](https://twitter.com/DragonJAR)
- [@ekoparty](https://twitter.com/ekoparty)
- [@eltaodelhacking](https://twitter.com/eltaodelhacking)
- [@H4ckThePl4net](https://twitter.com/H4ckThePl4net)
- [@Hackear_ARG](https://twitter.com/Hackear_ARG)
- [@hamping_org](https://twitter.com/hamping_org)
- [@l0ckpickar](https://twitter.com/l0ckpickar)
- [@linuxchixar](https://twitter.com/linuxchixar)
- [@PampaSeg](https://twitter.com/PampaSeg)
- [@ParanaConf](https://twitter.com/ParanaConf)
- [@pibasdeinfosec](https://twitter.com/pibasdeinfosec)
- [@SecurePodcast](https://twitter.com/SecurePodcast)
- [@securityjam](https://twitter.com/securityjam)
- [@tandilsec](https://twitter.com/tandilsec)
 

# Referencias
<a name="referencias"/>

[Penetration Test vs. Red Team Assessment: The Age Old Debate of Pirates vs. Ninjas Continues](https://blog.rapid7.com/2016/06/23/penetration-testing-vs-red-teaming-the-age-old-debate-of-pirates-vs-ninja-continues/)

# Salida laboral
<a name="salida-laboral"/>

- Proving grounds (*work in progress*)
- ekodating (by ekoparty)

# Proving grounds (mentorship)
<a name="mentorship"/>

*Work in progress*


