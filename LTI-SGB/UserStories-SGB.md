## User Story 1: Publicar una Oferta de Empleo

**Como** reclutador, **quiero** poder crear y publicar fácilmente una oferta de empleo en múltiples plataformas, **para** atraer a un amplio abanico de candidatos cualificados y acelerar el proceso de contratación.

**Criterios de Aceptación:**

- Puedo crear una oferta de empleo con información detallada como título, descripción, requisitos, ubicación y departamento.
- Puedo previsualizar la oferta de empleo antes de publicarla.
- Puedo publicar la oferta de empleo en el sitio web de la empresa, portales de empleo y redes sociales con un solo clic.
- Puedo programar la fecha de publicación y cierre de la oferta de empleo.
- Puedo editar la oferta de empleo después de ser publicada.
- Puedo hacer un seguimiento de las plataformas donde se ha publicado la oferta de empleo.

## User Story 2: Evaluar Candidatos Automáticamente

**Como** reclutador, **quiero** que el sistema evalúe automáticamente las habilidades y la experiencia de los candidatos, **para** que pueda identificar rápidamente a los candidatos más adecuados y ahorrar tiempo en la selección inicial.

**Criterios de Aceptación:**

- El sistema analiza los CVs y las cartas de presentación de los candidatos para extraer información relevante como habilidades, experiencia laboral y educación.
- El sistema compara la información extraída con los requisitos de la oferta de empleo.
- El sistema asigna una puntuación a cada candidato en función de su adecuación a la oferta de empleo.
- Puedo ajustar los criterios de evaluación para cada oferta de empleo.
- Puedo revisar la evaluación automática del sistema y realizar cambios si es necesario.
- Puedo filtrar y ordenar a los candidatos en función de su puntuación.

## Backlog de Producto LTI - Sprint 1

| ID  | User Story                                                                                                                                                                                                                        | Prioridad | Puntos de Esfuerzo | Estado | Asignado a           |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------ | ------ | -------------------- |
| 1   | Como reclutador, quiero poder crear y publicar fácilmente una oferta de empleo en múltiples plataformas, para atraer a un amplio abanico de candidatos cualificados y acelerar el proceso de contratación.                        | Alta      | 8                  | To Do  | Equipo de Desarrollo |
| 2   | Como reclutador, quiero que el sistema evalúe automáticamente las habilidades y la experiencia de los candidatos, para que pueda identificar rápidamente a los candidatos más adecuados y ahorrar tiempo en la selección inicial. | Alta      | 13                 | To Do  | Equipo de Desarrollo |

## Backlog de Producto LTI - Sprint 1 - Priorizado por Valor de Negocio

| ID  | User Story                                                                                                                                                                                                                        | Prioridad | Valor de Negocio | Puntos de Esfuerzo | Estado | Asignado a           |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ---------------- | ------------------ | ------ | -------------------- |
| 2   | Como reclutador, quiero que el sistema evalúe automáticamente las habilidades y la experiencia de los candidatos, para que pueda identificar rápidamente a los candidatos más adecuados y ahorrar tiempo en la selección inicial. | Alta      | **Alto**         | 13                 | To Do  | Equipo de Desarrollo |
| 1   | Como reclutador, quiero poder crear y publicar fácilmente una oferta de empleo en múltiples plataformas, para atraer a un amplio abanico de candidatos cualificados y acelerar el proceso de contratación.                        | Alta      | **Medio**        | 8                  | To Do  | Equipo de Desarrollo |

**Cambios con respecto al backlog anterior:**

- Se ha añadido la columna "Valor de Negocio".
- Se ha priorizado la User Story 2 sobre la User Story 1 debido a su mayor valor de negocio.

## Backlog de Producto LTI - Sprint 1 - Priorizado por Coste-Beneficio

| ID  | User Story                                                                                                                                                                                                                        | Prioridad | Valor de Negocio | Puntos de Esfuerzo | Coste-Beneficio | Estado | Asignado a           |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ---------------- | ------------------ | --------------- | ------ | -------------------- |
| 1   | Como reclutador, quiero poder crear y publicar fácilmente una oferta de empleo en múltiples plataformas, para atraer a un amplio abanico de candidatos cualificados y acelerar el proceso de contratación.                        | Alta      | Medio            | 8                  | **Alto**        | To Do  | Equipo de Desarrollo |
| 2   | Como reclutador, quiero que el sistema evalúe automáticamente las habilidades y la experiencia de los candidatos, para que pueda identificar rápidamente a los candidatos más adecuados y ahorrar tiempo en la selección inicial. | Alta      | Alto             | 13                 | **Medio**       | To Do  | Equipo de Desarrollo |

**Cambios con respecto a los backlogs anteriores:**

- Se ha añadido la columna "Coste-Beneficio".
- Se ha priorizado la User Story 1 sobre la User Story 2 debido a su mayor coste-beneficio (menor esfuerzo para un valor de negocio medio).
- En el backlog anterior, la User Story 2 tenía mayor prioridad por su alto valor de negocio, aunque requería un mayor esfuerzo de desarrollo.

## Tickets de Trabajo para la User Story 1: Publicar una Oferta de Empleo

**User Story:** Como reclutador, quiero poder crear y publicar fácilmente una oferta de empleo en múltiples plataformas, para atraer a un amplio abanico de candidatos cualificados y acelerar el proceso de contratación.

**Tickets de Trabajo:**

| ID  | Título                                                     | Descripción                                                                                                                                                                                                       | Prioridad | Puntos de Esfuerzo | Estado | Asignado a             |
| --- | ---------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------ | ------ | ---------------------- |
| 1.1 | Diseñar la interfaz de creación de ofertas de empleo       | Diseñar la interfaz de usuario para que los reclutadores puedan crear nuevas ofertas de empleo, incluyendo campos para la información relevante (título, descripción, requisitos, ubicación, departamento, etc.). | Alta      | 3                  | To Do  | Diseñador UI/UX        |
| 1.2 | Desarrollar la funcionalidad para crear ofertas de empleo  | Implementar la lógica para guardar las ofertas de empleo creadas por los reclutadores en la base de datos.                                                                                                        | Alta      | 5                  | To Do  | Desarrollador Backend  |
| 1.3 | Implementar la previsualización de la oferta de empleo     | Permitir a los reclutadores previsualizar la oferta de empleo antes de publicarla.                                                                                                                                | Media     | 2                  | To Do  | Desarrollador Frontend |
| 1.4 | Integrar con plataformas de publicación de empleo          | Desarrollar la funcionalidad para publicar las ofertas de empleo en diferentes plataformas (sitio web de la empresa, portales de empleo, redes sociales) con un solo clic.                                        | Alta      | 8                  | To Do  | Desarrollador Backend  |
| 1.5 | Programar la publicación y cierre de ofertas de empleo     | Implementar la funcionalidad para que los reclutadores puedan programar la fecha de publicación y cierre de las ofertas de empleo.                                                                                | Media     | 3                  | To Do  | Desarrollador Backend  |
| 1.6 | Desarrollar la funcionalidad para editar ofertas de empleo | Permitir a los reclutadores editar las ofertas de empleo después de su publicación.                                                                                                                               | Media     | 4                  | To Do  | Desarrollador Backend  |
| 1.7 | Implementar el seguimiento de la publicación de ofertas    | Mostrar a los reclutadores un registro de las plataformas donde se ha publicado cada oferta de empleo.                                                                                                            | Baja      | 2                  | To Do  | Desarrollador Frontend |
