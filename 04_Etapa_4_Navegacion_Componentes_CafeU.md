# Etapa 4: Navegación y componentes — CaféU

## Descripción de la etapa

Esta etapa convierte las pantallas y acciones del user flow en una navegación comprensible y en los controles que el estudiante necesita para completar el pedido. La estructura del sistema y los elementos de navegación se relacionan, pero no son lo mismo: el sitemap organiza pantallas; los componentes permiten llegar a ellas y actuar dentro de ellas ([Nielsen Norman Group: IA and Navigation](https://www.nngroup.com/articles/ia-vs-navigation/)).

## Navegación propuesta

| Desde | Control o acción | Hacia | Comportamiento |
|---|---|---|---|
| Menú | Agregar producto y revisar pedido | Menú actualizado o Revisión | Actualiza el pedido y muestra el acceso a revisión. |
| Menú | Revisar pedido | Revisión del pedido | Abre el resumen con productos, cantidades y total. |
| Revisión | Editar pedido | Menú | Regresa conservando el pedido. |
| Revisión | Confirmar pedido | Enviando pedido | Inicia el envío y comunica que se está procesando. |
| Enviando pedido | Recepción exitosa | Pedido recibido | Muestra la confirmación. |
| Enviando pedido | Error | Error de envío | Informa el problema sin borrar el pedido. |
| Error de envío | Reintentar | Enviando pedido | Vuelve a intentar el envío. |
| Error de envío | Volver a revisar | Revisión del pedido | Permite comprobar o editar antes de otro intento. |

## Componentes por pantalla

| Pantalla | Componentes | Función |
|---|---|---|
| Menú | Encabezado CaféU; indicador o acceso “Ver pedido”; tarjeta de producto; nombre y precio; botón “Agregar”; control de cantidad; barra inferior con total y botón de revisión. | Consultar productos, agregarlos y acceder al resumen. |
| Revisión del pedido | Enlace “← Menú” o acción “Editar pedido”; filas de producto; control de cantidad; opción para quitar; total; botón “Confirmar pedido · $4,25”. | Comprobar y ajustar el pedido antes de enviarlo. |
| Enviando pedido | Mensaje de estado e indicador de procesamiento. | Comunicar que el sistema está atendiendo la confirmación. |
| Pedido recibido | Mensaje explícito de recepción; resumen del pedido; acción “Hacer otro pedido”. | Confirmar que CaféU recibió la orden. |
| Error de envío | Mensaje claro; botón “Reintentar”; acción “Volver a revisar”. | Explicar el error y ofrecer recuperación. |

## Etiquetas principales

Usar etiquetas directas y consistentes:

- **Agregar**
- **Ver pedido**
- **Editar pedido**
- **Confirmar pedido · $4,25**
- **Reintentar**
- **Volver a revisar**
- **Pedido recibido**

En la interfaz final, “← Menú” y “Editar pedido” no deben presentarse como dos acciones distintas si ambas llevan al mismo destino. Se debe escoger una etiqueta principal coherente en las pantallas relacionadas.

## Referencia

- Nielsen Norman Group. [The Difference Between Information Architecture (IA) and Navigation](https://www.nngroup.com/articles/ia-vs-navigation/).

