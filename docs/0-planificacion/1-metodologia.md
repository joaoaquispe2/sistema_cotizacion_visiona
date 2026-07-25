# Metodología del Proyecto

El presente documento describe la metodología que aplicaré para desarrollar el sistema web orientado a mejorar el proceso de elaboración de cotizaciones de una microempresa. Actualmente, la generación de una cotización puede tomar entre dos y cuatro días; por ello, el proyecto busca digitalizar y optimizar este proceso mediante la implementación de un sistema web, una base de datos y la infraestructura necesaria para su funcionamiento.

La metodología del proyecto será **Predictiva** desde el análisis del negocio hasta el diseño del sistema. Para la fase de desarrollo se buscará utilizar un **SCURM** sencillo que permita un desarrollo de módulos más eficiente y realización de pruebas continuas.

Toda la documentación del proyecto se realizará mediante un repositorio de GitHub utilizando archivos Markdown o de otro formato de ser necesario. De esta manera se buscando mantener el seguimiento del proyecto, el control de cambios, la colaboración y el mantenimiento futuro del sistema.

La metodología que utilizaré se divide en siete fases:

## 1. Estudio del Negocio

En esta primera etapa se busca comprender el funcionamiento general de la empresa y analizar detalladamente el proceso actual de elaboración de cotizaciones. Esta fase permitirá conocer cómo trabaja la organización, quiénes participan en el proceso, qué información utilizan, cuáles son las principales dificultades y qué oportunidades de mejora existen.

### Actividades Principales

- Recopilar información clave de la empresa (misión, visión, organigrama, mapa de procesos)
- Realizar un análisis FODA y análisis de negocios CANVA
- Realizar entrevistas con las partes interesadas para conocer cómo se realiza el proceso de cotización, las dificultades que se tiene y los problemas que genera el proceso actual
- Observar el proceso y recopilar los documentos y herramientas actuales que se utilizan
- Documentar el proceso actual (AS-IS) mediante un diagrama de procesos
- Realizar un análisis causa efecto de los problemas encontrados en el proceso
- Identificar las oportunidades de mejora y plantear las posibles soluciones
- Documentar el proceso propuesto (TO-BE) mediante un diagrama de proceso
- Validar propuesta con la empresa

### Documentos Generados

- Documento de análisis inicial
- Análisis FODA y CANVAS
- Resumen de entrevista de análisis de proceso
- Diagrama de proceso actual y su documentación
- Árbol de problemas del proceso de cotización
- Documento de oportunidades de mejora y propuestas de solución
- Diagrama de proceso propuesto y documentación

## 2. Ingeniería de Requisitos

En esta segunda etapa se busca definir de manera clara y organizada las funciones, características y restricciones que deberá cumplir el sistema. Los requisitos serán obtenidos a partir de las necesidades identificadas durante el estudio del negocio y de la información proporcionada por los futuros usuarios.

### Actividades principales

- Recopilar las necesidades de cada usuario mediante entrevista.
- Identificar a los usuarios y actores del sistema.
- Definir los objetivos y alcance del sistema.
- Identificar los requisitos funcionales.
- Identificar los requisitos no funcionales.
- Elaborar historias de usuario o casos de uso.
- Priorizar los requisitos.
- Validar los requisitos con los usuarios.

### Documentos Generados

- Documentación de stakeholders.
- Resumen de entrevista necesidades de usuarios.
- Documento de objetivos y alcance del sistema.
- Catálogo de requisitos funcionales.
- Catálogo de requisitos no funcionales.
- Diagrama de casos de uso.
- Matriz de trazabilidad de requisitos.

## 3. Diseño del Sistema

Durante esta etapa se definirá la estructura técnica y funcional de la solución antes de iniciar su programación. También, se establece cómo estará organizado el sistema, cómo se almacenará la información, cómo se comunicarán sus componentes y cómo interactuarán los usuarios con la aplicación.

### Actividades principales

- Definir la arquitectura general del sistema.
- Seleccionar las tecnologías de desarrollo.
- Diseñar los módulos del sistema.
- Diseñar la base de datos.
- Diseño de lógica del negocio
- Elaborar prototipos de pantallas.
- Definir los roles y permisos.
- Diseñar la seguridad del sistema.
- Diseño de documentos generados.
- Definir los mecanismos de respaldo y recuperación.
- Diseñar la infraestructura de implementación.
- Revisar el diseño con los usuarios y responsables del proyecto.

### Documentos generados

- Documento de arquitectura y tecnologías a utilizar.
- Diagrama de componentes.
- Documentación de los módulos
- Documentación de lógica de negocio
- Modelo entidad-relación.
- Diccionario de datos.
- Prototipos de interfaz.
- Documentación de roles, especificaciones de seguridad y mecanismos de respaldo
- Documento de cotización.
- Diagrama de despliegue.

## 4. Desarrollo

Es la etapa de construicción los componentes del sistema de acuerdo con los requisitos y diseños aprobados. Comprende la programación de la aplicación web, la creación de la base de datos y la configuración de los elementos necesarios para el funcionamiento de la solución.

### Actividades principales

- Definir metodología de desarrollo
- Configurar el entorno de desarrollo.
- Configurar el repositorio de código.
- Implementar la base de datos.
- Desarrollar el sistema de autenticación.
- Programación de usuarios y roles
- Programar los módulos del sistema.
- Implementar las reglas del negocio.
- Crear las interfaces de usuario.
- Desarrollar la generación de cotizaciones.
- Gestionar errores y excepciones.
- Documentar el código.
- Realizar revisiones de código.
- Registrar cambios y avances en GitHub.

### Documentos generados

- Documentación de la metodología.
- Documentación de la base de datos.
- Código fuente.
- Documentación técnica.
- Manual de instalación para desarrollo.
- Registro de versiones.
- Registro de cambios.
- Evidencias de revisión de código.

## 5. Integración y pruebas

En esta etapa se busca verificar que los componentes desarrollados funcionen correctamente de manera individual y conjunta, y comprobar que el sistema cumpla con los requisitos establecidos.

### Actividades principales

- Integrar los módulos del sistema.
- Verificar la comunicación entre la aplicación y la base de datos.
- Ejecutar pruebas unitarias.
- Ejecutar pruebas de integración.
- Ejecutar pruebas funcionales.
- Ejecutar pruebas de interfaz.
- Ejecutar pruebas de seguridad.
- Ejecutar pruebas de rendimiento.
- Ejecutar pruebas de compatibilidad.
- Realizar pruebas con datos representativos.
- Verificar los cálculos de las cotizaciones.
- Validar la generación de documentos.
- Registrar errores e incidencias.
- Corregir los problemas identificados.
- Realizar pruebas de aceptación con los usuarios.

### Documentos generados

- Plan de pruebas.
- Casos de prueba.
- Registro de incidencias.
- Evidencias de pruebas.
- Informe de resultados.
- Matriz de trazabilidad entre requisitos y pruebas.
- Acta de aceptación del sistema.

## 6. Implementación

Es la etapa en la que se pone el sistema en funcionamiento dentro de la empresa y facilitar su adopción por parte de los usuarios; se incluye la  instalación, configuración, migración de información, capacitación y puesta en producción.

### Actividades principales

- Preparar el entorno de producción.
- Configurar el servidor.
- Despliegue de la aplicación en el servidor.
- Configurar la base de datos.
- Configurar usuarios, roles y permisos.
- Importar o registrar información inicial.
- Realizar copias de seguridad.
- Ejecutar pruebas finales en el entorno real.
- Capacitar a los usuarios.
- Entregar manuales.
- Realizar la puesta en funcionamiento.
- Brindar acompañamiento durante el uso inicial.
- Registrar problemas posteriores a la instalación.
- Verificar la continuidad de la operación.

### Documentos generados

- Manual de instalación.
- Manual de usuario.
- Manual de administración.
- Guía de respaldo y recuperación.
- Registro de capacitación.
- Acta de puesta en producción.
- Registro de incidencias de implementación.

## 7. Evaluación y mejora

Se evalúa los resultados obtenidos después de la implementación y determinar si el sistema ha mejorado el proceso de cotizaciones. Esta fase también permite identificar nuevas necesidades, corregir problemas y establecer mejoras para futuras versiones.

### Actividades principales

- Recopilar opiniones de los usuarios.
- Evaluar el nivel de satisfacción.
- Verificar el cumplimiento de los objetivos del proyecto.
- Comparar el proceso anterior con el nuevo proceso.
- Analizar la reducción de actividades manuales.
- Evaluar la calidad de las cotizaciones generadas.
- Revisar errores e incidencias.
- Analizar el uso de las funcionalidades.
- Identificar requisitos nuevos.
- Priorizar mejoras.
- Corregir defectos.
- Actualizar la documentación.
- Crear nuevas versiones del sistema.

### Documentos generados

- Informe de evaluación.
- Encuesta de satisfacción.
- Registro de incidencias.
- Lista de mejoras.
- Solicitudes de cambio.
- Registro de versiones.
- Lecciones aprendidas.
