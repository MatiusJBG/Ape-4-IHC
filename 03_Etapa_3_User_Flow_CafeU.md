# Etapa 3: User Flow — CaféU

## Descripción de la etapa

El user flow representa los pasos que sigue el estudiante y las respuestas del sistema para completar una tarea concreta. En CaféU se modelan el recorrido principal de confirmación, la alternativa de edición y la recuperación ante un error. A diferencia del sitemap, el diagrama se centra en acciones, decisiones y transiciones de la persona ([Nielsen Norman Group: User Journeys vs. User Flows](https://www.nngroup.com/articles/user-journeys-vs-user-flows/)).

## Escenario

El estudiante abre el menú, agrega 1 café americano ($1,50) y 1 sánduche ($2,75), revisa que el total sea $4,25 y decide confirmar o editar el pedido.

## Diagrama del flujo

El diagrama está preparado en LaTeX con TikZ: [04_Diagrama_User_Flow_CafeU.tex](04_Diagrama_User_Flow_CafeU.tex).

Para generar el diagrama en PDF:

```bash
pdflatex 04_Diagrama_User_Flow_CafeU.tex
```

## Recorrido representado

1. El estudiante consulta el menú y agrega los productos.
2. Revisa las cantidades y el total de $4,25.
3. Si edita, vuelve al menú con el pedido conservado, ajusta la selección y regresa a revisión.
4. Si confirma, el sistema muestra el estado “Enviando pedido”.
5. Si la recepción es exitosa, se muestra “Pedido recibido”.
6. Si ocurre un error, el pedido se conserva y se puede reintentar o volver a revisar.

## Referencia

- Nielsen Norman Group. [User Journeys vs. User Flows](https://www.nngroup.com/articles/user-journeys-vs-user-flows/).

