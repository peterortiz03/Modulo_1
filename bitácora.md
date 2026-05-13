# Bitácora de Ingeniería: Seguimiento ISS y Antena de Radio

Esta bitácora es el lugar donde voy a ir subiendo el progreso de los dos proyectos que tenemos para este módulo: el sistema motorizado para seguir a la ISS con una cámara y el diseño de la antena para captar los rebotes de señales de radio. La idea es registrar acá todo el proceso, desde los primeros bocetos del hardware hasta las pruebas finales de recepción de señal. Se registrará en la bitácora el avance que hacemos en cada clase.

### Registro de Actividades

#### Marzo
* 04/03/2026: Iniciamos con el estudio de inductores y construcción de los mismos a la inductacia solicitada según el apellido. Estudiamos las prestaciones del servidor para la instalación de Linux.
* 11/03/2026: Realizamos mediciones de inductores y las registramos en el respositorio de todos los integrantes. Comenzamos a rastrear satelites y creamos las cuentas en Xubuntu en el servidor para cada uno de los integrantes del grupo.
* 18/03/2026: Construimos capacitores caseros y empezamos a usar Gpredict e ISS Detector. Instalamos Gpredict en Linux.
* 25/03/2026: Se definieron los roles de gestion usando SCRUM. Nos dividimos en distintos equipos para distintas tareas, el equipo de fotogradía debía ver tutoriales y aprender a usar la cámara; el equipo de escuchas debía tratar de buscar satélites y escuchar con el SDR y el de informes (del cual participé) debía quedarse en la clase para aprender a redactar informes con la plantilla y usando overleaf. Realizamos un informe sobre metodolgías scrum, agile, etc.

#### Abril
* 01/04/2026: Trabajamos en monitoreo de radiofrecuencia de la repetidora local utilizando SDR, logrando recibir y grabar mensajes. Tambien intentamos montar una VPN para acceder por SSH a la PC del proyecto mediante un servicio de ruteo externo por no disponer de IP publica. Analizamos metadatos EXIF de fotografias para estandarizar futuras capturas astronomicas.
* 08/04/2026: Tuvimos una clase sobre antenas donde, por ejemplo, medimos un dipolo que trajo el prodesor de 92 cm para 163 MHz. Aprendimos el uso y calibracion del NanoVNA, cuidando la impedancia de 50 ohms para proteger el equipo. Tambien comenzamos a modelar antenas en MMANA-GAL.
* 15/04/2026: Estudiamos el batido de ondas con scripts en R y modelamos antenas en MMANA-GAL. Utilizamos el mastil de la facultad como soporte elevado y logramos captar señales de Chile y China. Tambien definimos aspectos mecanicos del sistema de seguimiento satelital con montura ecuatorial y control mediante Arduino.
* 22/04/2026: Realizamos simulaciones comparativas en MMANA-GAL entre varias antenas como Dipolo, Moxon y Yagi. La Moxon se perfilo como una mejor opcion por su tamaño reducido y facilidad de integracion por lo que la elegimos para el prototipo real.
* 29/04/2026: Calculamos las medidas exactas para 145 MHz en una página de internet, y utilizamos los cables que trajo el profesor para cortarlos a las medidas solicitadas. Tambien practicamos soldadura.

#### Mayo
* 06/05/2026: Clase suspendida por viento Zonda. Investigamos diseños constructivos de la antena Moxon con el material de la catedra.
