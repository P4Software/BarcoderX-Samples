<p align="center"><img src="../brand/barcoderx-horizontal.svg" alt="BarcoderX" width="280"></p>

# El agente de impresión

[English](README.md)

> **Estado:** Planificado. Esta carpeta todavía no contiene ningún programa. Lo contendrá cuando la función esté terminada. BarcoderX aún no está publicado, así que hoy nada de lo que hay aquí se puede ejecutar.

## Qué mostrará este ejemplo

Cómo instalar el agente de impresión en un equipo que está en la misma red que sus impresoras y conectarlo con su propio servidor. Un administrador crea un código de vinculación de un solo uso en el servidor, el código se introduce en el agente y el agente enumera las impresoras a las que llega, para que usted las registre. El agente solo se conecta hacia afuera, por lo que no necesita ningún puerto de entrada abierto. El ejemplo termina imprimiendo una etiqueta a través del agente y diciendo con palabras sencillas lo que ocurrió.

## Qué necesitará

- Un servidor de API que usted instaló y ejecuta por su cuenta, y una cuenta de administrador en él.
- Un equipo en la misma red que sus impresoras: Windows 10, Windows 11 o Windows Server 2019 o posterior, o Linux en x64 o arm64 con systemd.
- Una conexión saliente de HTTPS y WebSocket permitida desde ese equipo hasta su servidor.
- Una impresora térmica a la que el equipo pueda llegar.
- Todavía no se puede instalar nada, porque BarcoderX aún no está publicado.

## Más información

- [El agente de impresión](https://docs.p4software.cloud/barcoderx-es/print-agent)
- [Impresión](https://docs.p4software.cloud/barcoderx-es/printing)

---

*BarcoderX es un producto de P4 Software.*
