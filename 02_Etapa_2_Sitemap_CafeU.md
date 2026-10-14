# Etapa 2: Sitemap — CaféU

## Descripción de la etapa

En esta etapa se organiza la estructura de pantallas y estados que necesita CaféU para cubrir los requisitos. El sitemap muestra cómo se agrupan; el orden de las acciones y las decisiones se detallará en la etapa siguiente, el user flow.

Un sitemap es una representación visual de la organización de las páginas o áreas de un sistema y sus relaciones estructurales ([Nielsen Norman Group: Information Architecture vs. Sitemaps](https://www.nngroup.com/articles/information-architecture-sitemaps/)).

## Sitemap propuesto

Las flechas del diagrama indican agrupación dentro de la aplicación, no el recorrido paso a paso.

El diagrama está preparado en LaTeX con TikZ. El archivo fuente compilable es [02_Diagrama_Sitemap_CafeU.tex](02_Diagrama_Sitemap_CafeU.tex). Para generar el diagrama en PDF, compílalo con:

```bash
pdflatex 02_Diagrama_Sitemap_CafeU.tex
```

El sitemap organiza la aplicación así:

- **CaféU:** aplicación móvil.
- **Pedido:** área funcional que contiene las pantallas y estados del pedido.
- **Menú:** consulta y selección de productos.
- **Revisión del pedido:** revisión de productos, cantidades y total.
- **Estado del pedido:** agrupa el envío, la recepción exitosa y el error recuperable.

## Pantallas y estados

| Pantalla o estado | Propósito |
|---|---|
| Menú | Consultar productos y precios, y preparar el pedido. |
| Revisión del pedido | Revisar productos, cantidades y total antes de confirmar. |
| Enviando pedido | Indicar que el sistema está procesando la confirmación. |
| Pedido recibido | Confirmar que CaféU recibió la orden. |
| Error de envío | Informar que hubo un problema y permitir recuperarse sin perder el pedido. |

## Relación con los requisitos

- **Menú:** RF-01 y RF-02.
- **Revisión del pedido:** RF-03, RF-04 y RF-05.
- **Enviando pedido:** RF-06.
- **Pedido recibido:** RF-06.
- **Error de envío:** RF-06 y RF-07.

No se incluyen pantallas de pago, inicio de sesión, retiro o preparación porque están fuera del alcance definido en la Etapa 1.

## Referencia

- Nielsen Norman Group. [Information Architecture vs. Sitemaps](https://www.nngroup.com/articles/information-architecture-sitemaps/).



