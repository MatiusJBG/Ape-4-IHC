# Etapa 1: Requisitos — CaféU

## Descripción de la etapa

En esta etapa se identifica qué necesita lograr el estudiante y qué debe permitir el sistema. Los requisitos servirán de base para estructurar las pantallas y el recorrido en las siguientes etapas.

## Contexto y usuario

CaféU es una cafetería universitaria ficticia. Durante un descanso breve, un estudiante necesita pedir sin explicar verbalmente su pedido mientras espera en una fila concurrida.

El escenario de referencia es:

- 1 café americano: $1,50.
- 1 sánduche: $2,75.
- Total: $4,25.

El alcance acordado es una interfaz móvil para consultar el menú, preparar el pedido y confirmar si fue recibido.

## Necesidad del usuario

El estudiante necesita elegir y revisar su pedido desde el teléfono, para pedir de manera autónoma y saber si CaféU recibió la orden.

**Historia de usuario**

> Como estudiante universitario con poco tiempo durante mi descanso, necesito elegir y confirmar mi pedido desde el teléfono, para pedir sin explicarlo verbalmente en la fila y saber que fue recibido.

Las historias de usuario expresan quién usa el servicio, qué necesita y con qué propósito ([GOV.UK Service Manual: Writing user stories](https://www.gov.uk/service-manual/agile-delivery/writing-user-stories)).

## Requisitos funcionales

| ID | Requisito |
|---|---|
| RF-01 | El sistema muestra el menú con los nombres y precios de los productos. |
| RF-02 | El estudiante puede agregar productos y cambiar sus cantidades. |
| RF-03 | El estudiante puede revisar productos, cantidades y total antes de confirmar. |
| RF-04 | El estudiante puede editar el pedido; el sistema conserva la selección y actualiza el total. |
| RF-05 | El estudiante puede confirmar el pedido desde la revisión. |
| RF-06 | El sistema informa que está procesando el pedido y muestra si fue recibido o si ocurrió un error. |
| RF-07 | Si ocurre un error, el estudiante puede reintentar o volver a revisar el pedido sin perderlo. |

## Requisitos de interacción

- Usar etiquetas claras: “Agregar”, “Editar pedido”, “Revisar pedido” y “Confirmar pedido”.
- Mantener visibles los productos, cantidades, precios y total durante la revisión.
- Comunicar el estado del pedido después de confirmar.
- Explicar los errores con lenguaje sencillo y ofrecer una acción para recuperarse.
- Diseñar controles táctiles distinguibles y fáciles de activar.

Estos requisitos se relacionan con principios de visibilidad del estado, control del usuario y prevención de errores descritos en las [heurísticas de Nielsen](https://www.nngroup.com/articles/ten-usability-heuristics/).

## Alcance

**Incluye:** consulta del menú, selección y edición de productos, revisión, confirmación, estado de envío, recepción exitosa y error recuperable.

**No incluye:** pago, inicio de sesión, selección de sucursal o retiro, disponibilidad en tiempo real, tiempo de preparación ni notificaciones de pedido listo. El enunciado no solicita estas funciones.

## Supuestos

- El teléfono móvil es el dispositivo de uso para este ejercicio.
- Los precios del escenario son finales y no se agregan cargos.
- “Pedido recibido” confirma la recepción de la orden, no que esté preparada.
- El escenario es ficticio y no incluye investigación directa con estudiantes; las necesidades se derivan del enunciado.

## Referencias

- GOV.UK Service Manual. [Writing user stories](https://www.gov.uk/service-manual/agile-delivery/writing-user-stories).
- Nielsen Norman Group. [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/).
