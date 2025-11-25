# LMS Offline JS

Prototipo de plataforma educativa (LMS) pensada para instituciones rurales con problemas de conectividad.  
Funciona 100% en el navegador usando **HTML, Bootstrap y JavaScript**, almacenando la información en `localStorage`, sin necesidad de servidor ni base de datos externa.

## Características principales

- Login con dos roles:
  - **Docente**
  - **Estudiante**
- Panel docente con:
  - Dashboard de resumen (cursos, estudiantes, actividades, respuestas).
  - Gestión de **cursos** (crear, editar, eliminar).
  - Gestión de **actividades** por curso (crear, editar, eliminar).
  - Gestión de **matrículas**:
    - Matricular estudiantes existentes.
    - Crear nuevos usuarios estudiantes.
    - Quitar estudiantes de un curso.
  - Visualización de **todas las respuestas** de los estudiantes por curso y por actividad.
- Panel estudiante:
  - Visualización de los cursos en los que está matriculado.
  - Lista de actividades por curso.
  - Envío y edición de respuestas.
  - Registro de fecha y hora de la última respuesta enviada.
- Botón **“Reiniciar datos”** que borra la “base de datos” local y deja el sistema en modo demo
  (1 docente, 1 estudiante demo, 1 curso demo, 1 actividad demo).

## Tecnologías utilizadas

- HTML5
- CSS3 + [Bootstrap 5](https://getbootstrap.com/)
- JavaScript puro (sin frameworks)
- `localStorage` y `sessionStorage` del navegador

## Estructura del proyecto

El prototipo se distribuye en un único archivo:

```text
lms_offline_js.html
