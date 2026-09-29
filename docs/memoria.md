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
