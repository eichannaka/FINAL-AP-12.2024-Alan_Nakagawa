# FINAL-AP-12.2024-Nakagawa

Proyecto: La aplicación de gestión de flujo de trabajo está diseñada para que los equipos gestionen proyectos, tareas y colaboradores de manera eficiente. Ofrecemos herramientas simples, intuitivas y accesibles en todo momento, enfocándonos en mejorar la productividad, la organización interna y la colaboración entre los miembros del equipo. Nuestro objetivo es facilitar el flujo de trabajo y optimizar el tiempo empleado en las tareas diarias.

Objetivos Generales SMART</br>
Específico: Diseñar y desarrollar una aplicación de gestión de flujo de trabajo que permita a los equipos crear, asignar y monitorear tareas, gestionar proyectos y mejorar la colaboración en el equipo.

Medible: Lograr que al menos el 80% de los usuarios dentro de los equipos adopten la aplicación dentro de los primeros 3 meses posteriores al lanzamiento oficial.

Alcanzable: Implementar las funcionalidades básicas como creación y asignación de tareas, gestión de proyectos y reportes de avance, utilizando tecnologías probadas y accesibles para el equipo de desarrollo.

Relevante: Mejorar la productividad organizacional y la capacidad de coordinación de equipos, respondiendo a la creciente necesidad de herramientas digitales para la gestión eficiente del tiempo y los recursos.

Temporal: Completar el desarrollo de la aplicación con sus funcionalidades principales en un plazo de 6 meses, con iteraciones mensuales para pruebas y ajustes según el feedback de los usuarios.


# Milestones del Proyecto

## Milestone 1: **Relación de Áreas en una Base de Datos Compleja**
- **Descripción:** Diseñar e implementar una base de datos robusta que permita gestionar la relación entre proyectos, colaboradores y tareas. Esto incluirá la capacidad de modificar colaboradores asignados a un proyecto, reconfigurar tareas asociadas y garantizar la trazabilidad de los cambios.
- **Objetivo:** Crear una estructura que soporte las interacciones complejas entre los datos para ofrecer flexibilidad en la gestión de proyectos.
- **Fecha límite:** **1 mes** desde el inicio del proyecto.

**Tareas asociadas:**
1. Diseño del esquema de base de datos relacional para soportar múltiples dependencias entre proyectos, colaboradores y tareas.
2. Implementación de APIs para la modificación dinámica de colaboradores y tareas asociadas a proyectos.
3. Validación de integridad referencial y pruebas de las relaciones en la base de datos.

---

## Milestone 2: **Hashing de Datos Sensibles de los Colaboradores**
- **Descripción:** Proteger la información sensible de los colaboradores mediante técnicas de hashing para datos como contraseñas, y cifrado para otros datos confidenciales.
- **Objetivo:** Garantizar la seguridad de los datos sensibles almacenados en la base de datos cumpliendo con buenas prácticas de seguridad.
- **Fecha límite:** **2 meses** después del inicio del proyecto.

**Tareas asociadas:**
1. Implementar el hashing seguro (ej.: bcrypt) para las contraseñas de los colaboradores.
2. Aplicar cifrado AES-256 para datos confidenciales como números de identificación personal.
3. Realizar auditorías de seguridad para garantizar la implementación adecuada.
4. Documentar el enfoque de seguridad y cómo se integran las técnicas utilizadas en el sistema.


## Riesgos identificados

<table>
  <tr>
    <th>Riesgo</th>
    <th>Probabilidad</th>
    <th>Impacto</th>
    <th>Nivel de riesgo</th>
  </tr>
  <tr>
    <td>Baja adopción por parte de los usuarios</td>
    <td style="background-color: #FFBF00;">Media</td> 
    <td style="background-color: #FF0000; color: white;">Alta</td> 
    <td style="background-color: #FF0000; color: white;">Alta</td> 
  </tr>
  <tr>
    <td>Problemas técnicos durante el despliegue</td>
    <td style="background-color: #FFBF00;">Media</td> 
    <td style="background-color: #FF0000; color: white;">Alta</td> 
    <td style="background-color: #FF0000; color: white;">Alta</td> 
  </tr>
  <tr>
    <td>Cambios en los requisitos del cliente</td>
    <td style="background-color: #FF0000; color: white;">Alta</td> 
    <td style="background-color: #FFBF00;">Media</td> 
    <td style="background-color: #FF0000; color: white;">Alta</td> 
  </tr>
</table>
# Detalles

## Baja adopción por parte de los usuarios
Es fundamental realizar una capacitación adecuada y brindar soporte para asegurar que los empleados comprendan el uso de la herramienta.

## Problemas técnicos durante el despliegue
Invertir en pruebas exhaustivas antes del lanzamiento para minimizar inconvenientes.

## Cambios en los requisitos del cliente
Implementar metodologías ágiles que permitan adaptarse rápidamente a nuevas demandas.


