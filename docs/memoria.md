# Memoria del Sprint 1: Ideación y Prototipado Base

| | |
| --- | --- |
| **Curso** | DAM 2 |
| **Grupo** | Grupo 2 |
| **Integrantes** | María Dolores <br> Alba Durán <br> Santiago González <br> Jorge Espejo |
| **Módulo / profesor** | PI/DII - Willman Acosta Lugo |
| **Sprint** | Sprint 1 <br> 24/09/2026 – 02/10/2026 |
| **Repositorios** | <https://github.com/SantiagoGonzalez12/Tempomedic> <br> <https://github.com/SantiagoGonzalez12/Tempomedic-Interfaz> |
| **Tablero** | <https://github.com/users/SantiagoGonzalez12/projects/6> |



# ÍNDICE 

## 1. INTRODUCCIÓN

* **1.1.** Contexto del proyecto
* **1.2.** Problema o necesidad detectada
* **1.3.** Propuesta de solución
* **1.4.** Objetivos del proyecto
  * **1.4.1.** Objetivo general
  * **1.4.2.** Objetivos específicos
* **1.5.** Alcance del proyecto
* **1.6.** Limitaciones y exclusiones
* **1.7.** Estructura de la memoria

## 2. ANÁLISIS DEL CONTEXTO Y VIABILIDAD

* **2.1.** Sector profesional y perfil de usuarios
* **2.2.** Análisis de la necesidad
* **2.3.** Estudio de soluciones existentes
* **2.4.** Partes interesadas
* **2.5.** Estudio de viabilidad técnica
* **2.6.** Estudio de viabilidad económica
* **2.7.** Estudio de viabilidad legal y normativa
  * **2.7.1.** Protección de datos personales
  * **2.7.2.** Propiedad intelectual y licencias
  * **2.7.3.** Accesibilidad y otros requisitos aplicables
* **2.8.** Análisis de riesgos inicial


--------------------------------------------------------------------------------------------------------------------------------------------
# 1. INTRODUCCIÓN

## 1.1. Contexto del proyecto

En la actualidad, el uso de dispositivos móviles se ha vuelto indispensable para la gestión de tareas cotidianas, y el ámbito de la salud digital es una de las áreas con mayor crecimiento y demanda tecnológica.

El proyecto consiste en el desarrollo de una aplicación móvil orientada a la gestión individual de la salud, la plataforma tiene en un único sistema dos funcionalidades clave: 

* La reserva y gestión de citas médicas 
* Módulo de control de medicación con alertas automáticas

En cuanto a la parte técnica de este proyecto el sistema se ha estructurado mediante una arquitectura cliente-servidor. Cuenta con una aplicación móvil como frontend, un backend y una base de datos relacional para la persistencia de la información, además, la aplicación hace uso de servicios en segundo plano y gestores de tareas del sistema operativo móvil para garantizar el lanzamiento preciso de las notificaciones de los medicamentos, incluso en el caso de que no haya conexión a Internet.

## 1.4. Objetivos del proyecto
   ### 1.4.1. Objetivo general

   ### 1.4.2. Objetivos específicos 
Aunque el proyecto tiene muy claro dónde quiere llegar, la verdadera captación son en los pequeños detalles que marcan la diferencia. Hoy en día existen muchas aplicaciones que se limitan a cumplir sus función, pero lo que realmente distinguirá a esta es su facilidad de uso y su capacidad para no dejar a nadie fuera.

La aplicación, TempoMedic, nace para acompañar a personas de cualquier edad, aunque pone la mirada en un grupo fundamental, los mayores. Ellos son la población más expuesta a los cambios de los últimos tiempo; no crecieron rodeados de pantallas y han tenido que adaptarse, paso a paso, tanto a las transformaciones tecnológicas como a los avances médicos.

Por eso, la app prescinde de complicaciones innecesarias. Apuesta por una navegación limpia y sencilla, donde la información siempre estará en primera mano junto a la ayuda que se soliciten. 

## 1.5. Alcance del proyecto
Para definir el alcance de la app, lo ideal es estructurarla en tres fases que vayan progresivamente para tenerla muy clara desde el principio.
* Primera fase: recopilar la información de los usuarios. Una vez completado, desarrollar un programa de recordatorios de medicación con notificaciones, alarmas o registros de tomas. Posibilidad de asociarlo a aplicaciones nativas del móvil como Apple Calendar o Google.
* Segunda fase: fidelizar a los usuarios sin complicar en exceso la tecnología. Aquí se incluye el control de inventario de pastillas para avisar cuando toque ir a la farmacia, la opción de gestionar perfiles de familiares dependientes, el guardado de fotos de recetas o informes médicos y la generación de un PDF con el historial de tomas para enseñárselo al médico (opcional).
* Tercera fase: se intentará conectar la app con bases de datos oficiales de medicamentos para buscar la medicina y detectar interacciones entre ellos. Poder integrar APIS con clínicas para reservar citas desde la app y añadir seguimiento de la medicación.

Los medicamentos tienen que estar protegidos legalmente por la normativa RGPD.

# 2. ANÁLISIS DEL CONTEXTO Y VIABILIDAD

## 2.1. Sector profesional y perfil de usuarios
## 2.2. Análisis de la necesidad
## 2.3. Estudio de soluciones existentes
Aplicaciones similares en el mercado:

* **MedControl**: funciona como un asistente de salud personal y pastillero virtual. Permite crear alarmas personalizadas para medicamentos, llevar un control de inventario y organizar recordatorios para citas médicas. Además, incluye un diario de tensión arterial y seguimiento de síntomas.  
* **Recordatorio de Medicamentos 2**: se centra en la adherencia al tratamiento. Ofrece recordatorios altamente configurables (cada X horas, días específicos, etc.), alertas cuando quedan pocas pastillas y la posibilidad de enviar reportes por correo al médico. Además permite agendar recordatorios de citas médicas.  
* **CareClinic**: va más allá de la medicación. Permite a los usuarios registrar síntomas, mediciones, estado de ánimo y nutrición. Sus recordatorios son personalizables para medicamentos y citas, también admite la gestión de múltiples perfiles, como hijos o personas mayores.  
* **Biva**: está diseñada para pacientes y cuidadores. Permite registrar condiciones médicas y tratamientos, estableciendo recordatorios para cada uno. Integra servicios como la recarga de medicamentos y la reserva de citas médicas, con un enfoque en la relación paciente-cuidador.  
* **DayMedy**: es una aplicación de telemedicina que integra consultas en línea, gestión de prescripciones digitales y programación de citas. Tras una consulta, el usuario recibe la receta en la app y puede configurar recordatorios para la medicación. También permite gestionar los registros de salud de la familia.  
* **Medical Reminder**: se enfoca en la simplicidad y la privacidad, funcionando sin conexión a internet. Ofrece recordatorios fiables para medicamentos y citas médicas, con un diseño de texto grande ideal para adultos mayores y cuidadores. Permite generar informes de salud en PDF para compartir con los médicos.  
* **Otras aplicaciones**: también existen ejemplos como **IMQ** (de una aseguradora de salud), **MyCarePlan**, **PineApp** y **MedGemak**, que ofrecen funcionalidades parciales o totales, como gestión de citas, historial clínico, videoconsulta y alarmas de medicación.

Noticias y tendencias recientes:

* **Éxito de las tarjetas sanitarias virtuales**: en la Comunidad de Madrid, la Tarjeta Sanitaria Virtual (TSV) ha registrado cerca de 57 millones de accesos en 2025, un 43,5% más que el año anterior. Los servicios más utilizados son la gestión de citas médicas, la consulta de medicación y el acceso a informes. La aplicación ha incorporado herramientas como recordatorios de citas de atención primaria, que han enviado más de 5 millones de notificaciones, y alertas sobre la dispensación de medicamentos en farmacias.  
* **Integración de IA en portales de pacientes**: Oracle Health ha lanzado un portal de pacientes con inteligencia artificial que ofrece resúmenes de salud, recordatorios automáticos de visitas y la posibilidad de programar citas de seguimiento. Esta IA ayuda a los pacientes a entender sus planes de cuidado y medicamentos en un lenguaje sencillo, buscando mejorar la adherencia al tratamiento.  
* **Nuevos modelos de negocio y funcionalidades**: Startups como **Assort Health** han levantado capital significativo para plataformas que utilizan IA para conectar la programación de citas, la gestión de medicamentos y los pagos en un solo sistema. Por otro lado, **Amazon** ha lanzado un agente de IA para la salud que puede reservar citas y gestionar recetas médicas.  
* **Investigación en universidades**: investigadores de la Universidad Miguel Hernández (UMH) de Elche han desarrollado una aplicación para que personas con inmunodeficiencias puedan autogestionar su enfermedad, incluyendo el control de citas y tratamientos con recordatorios personalizados.

Comparación
| | Otras apps | Tempomedic |

## 2.4. Partes interesadas
## 2.5. Estudio de viabilidad técnica
## 2.6. Estudio de viabilidad económica
## 2.7. Estudio de viabilidad legal y normativa
   ### 2.7.1. Protección de datos personales
   ### 2.7.2. Propiedad intelectual y licencias
   ### 2.7.3. Accesibilidad y otros requisitos aplicables
## 2.8. Análisis de riesgos inicial
