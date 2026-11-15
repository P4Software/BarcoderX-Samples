<p align="center"><img src="brand/barcoderx-horizontal.svg" alt="BarcoderX" width="280"></p>

# Ejemplos de BarcoderX

[English](README.md)

## Qué es este repositorio

Este es el lugar de los programas de ejemplo de BarcoderX, un conjunto de herramientas para desarrolladores, para diseñar, previsualizar e imprimir etiquetas con códigos de barras, en especial en impresoras térmicas. BarcoderX está construido sobre .NET 10. Cada ejemplo es un programa pequeño que muestra una sola cosa y dice con palabras sencillas lo que hizo.

## Cómo están las cosas hoy

BarcoderX está en desarrollo. Todavía no hay nada publicado y no hay ningún paquete que instalar. **Ningún ejemplo de este repositorio se puede ejecutar todavía.**

Lo que existe hoy es la estructura: una carpeta por tema, con un README breve que indica qué mostrará el ejemplo y qué necesitará usted. Todos los temas están marcados como **Planificado**.

Los ejemplos llegan junto con las funciones que muestran. Cuando una función está terminada, su ejemplo se agrega aquí, y solo entonces su estado cambia a **Disponible**. Una carpeta contiene un programa real únicamente cuando su función está terminada. Mientras tanto, contiene solo el README.

## Índice de ejemplos

| Tema | Qué muestra | Estado | Carpeta | Guía |
|---|---|---|---|---|
| Primera etiqueta en código | El camino más corto desde cero hasta una etiqueta terminada, desde un programa de .NET | Planificado | [01-first-label-in-code](01-first-label-in-code/README.es.md) | [Cómo encajan las piezas](https://docs.p4software.cloud/barcoderx-es/how-the-pieces-fit) |
| Salida en PNG y PDF | Una etiqueta guardada como imagen PNG y como archivo PDF | Planificado | [02-png-and-pdf-output](02-png-and-pdf-output/README.es.md) | [Formatos de salida](https://docs.p4software.cloud/barcoderx-es/output-formats) |
| Códigos de barras (lineales, 2D, GS1) | Códigos de barras de cada tipo, con dígitos de control y texto legible | Planificado | [03-barcodes](03-barcodes/README.es.md) | [Códigos de barras](https://docs.p4software.cloud/barcoderx-es/barcodes) |
| Texto y fuentes | Diseño del texto, la fuente incorporada y una fuente que usted carga | Planificado | [04-text-and-fonts](04-text-and-fonts/README.es.md) | [Texto, fuentes e imágenes](https://docs.p4software.cloud/barcoderx-es/text-fonts-and-pictures) |
| Plantillas y vinculación de datos | Una plantilla, muchos registros, una etiqueta por cada uno | Planificado | [05-templates-and-data-binding](05-templates-and-data-binding/README.es.md) | [Plantillas y datos](https://docs.p4software.cloud/barcoderx-es/templates-and-data) |
| Impresión en una impresora ZPL por la red | Una etiqueta enviada desde su programa directamente a una impresora de su red | Planificado | [06-print-to-zpl-over-network](06-print-to-zpl-over-network/README.es.md) | [Impresión](https://docs.p4software.cloud/barcoderx-es/printing) |
| La API web | Crear un trabajo de impresión y leer su estado | Planificado | [07-web-api-print-job](07-web-api-print-job/README.es.md) | [API web](https://docs.p4software.cloud/barcoderx-es/web-api) |
| El editor de etiquetas en React, Angular y Vue | El editor incorporado en una página web de cada framework | Planificado | [08-label-editor](08-label-editor/README.es.md) | [El editor de etiquetas](https://docs.p4software.cloud/barcoderx-es/label-editor) |
| El agente de impresión | El agente instalado cerca de sus impresoras y vinculado con su servidor | Planificado | [09-print-agent](09-print-agent/README.es.md) | [El agente de impresión](https://docs.p4software.cloud/barcoderx-es/print-agent) |
| Licencias y la marca de evaluación | La misma etiqueta con y sin una clave de licencia | Planificado | [10-licensing-and-evaluation-mark](10-licensing-and-evaluation-mark/README.es.md) | [Marca de evaluación y claves de licencia](https://docs.p4software.cloud/barcoderx-es/evaluation-and-licence-keys) |

El conjunto completo de guías está en la [guía de usuario de BarcoderX](https://docs.p4software.cloud/barcoderx-es/overview).

## Qué necesitará

Cuando existan ejemplos, usted necesitará:

- El SDK de .NET 10.
- Windows x64, Linux x64 o Linux arm64.
- La clave de licencia es opcional. Sin ella todo funciona igual, y el resultado lleva la marca de evaluación.

Los ejemplos están escritos en C#. Los ejemplos de la API web, del editor y del agente de impresión necesitan además un servidor de API que usted instala y ejecuta por su cuenta. BarcoderX no aloja nada por usted, así que todos los ejemplos se ejecutan en sus propios equipos.

El README de cada ejemplo indica lo demás que ese ejemplo necesita.

## Cómo ejecutar un ejemplo

Cuando un ejemplo esté Disponible, abra su carpeta, lea su README y ejecútelo. La mayoría de los ejemplos se inician con un solo comando, `dotnet run`, y el README le avisa si alguno necesita algo distinto. El ejemplo muestra lo que hizo, con palabras sencillas, y qué hacer a continuación.

## Informar de un problema

[Abra una incidencia](https://github.com/P4Software/BarcoderX-Samples/issues) (issue). Indique qué carpeta de ejemplo usó, qué sistema operativo utiliza, qué esperaba y qué ocurrió. Nunca pegue una clave de licencia ni una clave de API en una incidencia.

---

*BarcoderX es un producto de P4 Software.*
