<p align="center"><img src="../brand/barcoderx-horizontal.svg" alt="BarcoderX" width="280"></p>

# Impresión en una impresora ZPL por la red

[English](README.md)

> **Estado:** Planificado. Esta carpeta todavía no contiene ningún programa. Lo contendrá cuando la función esté terminada. BarcoderX aún no está publicado, así que hoy nada de lo que hay aquí se puede ejecutar.

## Qué mostrará este ejemplo

Una etiqueta enviada desde su propio programa de .NET directamente a una impresora térmica de su red, mediante una conexión TCP (puerto 9100 de forma predeterminada), en el lenguaje de impresora ZPL. El SDK construye los comandos de impresión y los envía por sí mismo, de modo que no interviene ningún servidor de API ni ningún agente de impresión. El ejemplo primero muestra lo que va a enviar, y solo imprime cuando usted lo indica.

## Qué necesitará

- El SDK de .NET 10.
- Windows x64, Linux x64 o Linux arm64.
- Los paquetes del SDK de BarcoderX, cuando estén publicados. Todavía no se puede instalar nada.
- Una impresora térmica que entienda ZPL y a la que se pueda llegar por su red. Necesita su dirección de red y su resolución en puntos por pulgada.
- Ninguna clave de licencia. Sin ella, la etiqueta impresa lleva la marca de evaluación.

## Más información

- [Impresión](https://docs.p4software.cloud/barcoderx-es/printing)
- [Lenguajes de impresora](https://docs.p4software.cloud/barcoderx-es/printer-languages)

---

*BarcoderX es un producto de P4 Software.*
