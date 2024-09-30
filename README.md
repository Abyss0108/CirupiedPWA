Proyecto de Gestión de Expedientes Clínicos - Cirupied

Descripción del Proyecto

Cirupied es una Aplicación Web Progresiva (PWA) orientada a la gestión eficiente de expedientes clínicos. La aplicación está diseñada para facilitar el acceso y la manipulación de datos clínicos desde dispositivos móviles y de escritorio, permitiendo la interacción con la plataforma tanto en línea como fuera de línea. La aplicación está desarrollada con tecnologías modernas, utilizando React + Vite junto con Service Workers, con el objetivo de ofrecer una experiencia rápida, accesible y confiable para los profesionales del sector salud.

El enfoque principal es mejorar la accesibilidad a los expedientes clínicos, permitiendo su consulta y actualización en cualquier momento, garantizando además la seguridad de los datos y cumpliendo con las normativas de protección de información clínica.

Metodología de Desarrollo

° Metodología Utilizada

Para el desarrollo de Cirupied, se ha seleccionado la metodología Kanban. Esta metodología permite un flujo continuo de trabajo, optimizando la eficiencia y la capacidad de respuesta ante cambios en los requisitos. La flexibilidad de Kanban permite gestionar las tareas de forma dinámica, adaptando el desarrollo a las necesidades emergentes del proyecto.

°Aplicación de la Metodología

El equipo trabaja con sprints de duración variable, entre 1 y 2 semanas. Cada sprint está orientado a entregar funcionalidades clave de forma incremental. El progreso se revisa continuamente, asegurando que cada tarea esté alineada con los objetivos del proyecto.


Gestión de Tareas e Issues

°Herramienta Seleccionada

Se utiliza Trello para la gestión de tareas, donde las actividades están organizadas en listas que contienen las actividades que se realizan en cada etapa de desarrollo.

°Proceso de Gestión de Tareas

El flujo de trabajo en Trello sigue estos pasos:

Creación de la tarjeta: Cada tarea se registra en la lista de tareas pendientes.
Asignación: Se asigna la tarea a un miembro del equipo.
Progreso: La tarea se mueve cmbian de qtiqueta segun el estado en la que se encuentren, por ejemplo No Iniciado, En progreso, Completado o Bloqueado.
Revisión: Tras finalizar la tarea, otro miembro del equipo la revisa.
Cierre: Si la revisión es satisfactoria, la tarea se marcan como "Completado".

°Priorización de Tareas

Las tareas se clasifican por prioridad con etiquetas en Trello:

Alta: Tareas críticas que requieren atención inmediata.
Media: Funcionalidades importantes pero no urgentes.
Baja: Mejoras menores o ajustes.

Control de Versiones

1. Herramienta Seleccionada
   
El control de versiones se realiza con Git, y la plataforma donde se estara colaborando en el repositorio es GitHub.

3. Estrategia de Versionamiento

Se utiliza la estrategia GitFlow, que permite mantener un control organizado del desarrollo:

main: Rama que contiene el código en producción.
develop: Rama donde se integran nuevas funcionalidades antes de pasar a producción.
feature/: Ramas específicas para cada nueva característica.
hotfix/: Ramas para corregir errores críticos en producción.

3. Creación de Ramas

Cada miembro del equipo trabaja en su propia rama, creada desde la rama develop, utilizando el prefijo feature/ (por ejemplo, feature/nueva-funcionalidad). Las correcciones urgentes se gestionan en ramas hotfix/ creadas desde master.

4. Políticas de Merge

Las ramas feature/ se integran en develop mediante pull requests, tras pasar por revisiones de código y pruebas. Solo un usuario designado tiene la autorización para realizar merges en la rama master, asegurando un control de calidad riguroso.

Estrategia de Despliegue

1. Estrategia Seleccionada

Se utiliza un despliegue gradual mediante la técnica de Canary Deployment. Esto permite introducir nuevas funcionalidades de manera progresiva, reduciendo el impacto en caso de fallos.

2. Entornos de Despliegue

Desarrollo: Ramas feature/ en desarrollo.
Staging: Rama develop, para validación y pruebas de integración.
Producción: Rama master, con código estable.

3. Integración Continua

El proyecto utiliza GitHub Actions para automatizar las pruebas y el despliegue en cada commit, asegurando que el código sea probado en cada paso antes de su integración en producción.
