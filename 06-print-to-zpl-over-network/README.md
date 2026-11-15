<p align="center"><img src="../brand/barcoderx-horizontal.svg" alt="BarcoderX" width="280"></p>

# Printing to a ZPL printer over the network

[Español](README.es.md)

> **Status:** Planned. This folder holds no program yet. It will hold one when the feature is finished. BarcoderX is not released, so nothing here can run today.

## What this sample will show

A label sent from your own .NET program straight to a thermal printer on your network, over a TCP connection (port 9100 by default), in the ZPL printer language. The SDK builds the printer commands and sends them itself, so no API server and no print agent are involved. The sample first shows what it is about to send, and prints only when you say so.

## What you will need

- The .NET 10 SDK.
- Windows x64, Linux x64 or Linux arm64.
- The BarcoderX SDK packages, once they are released. Nothing can be installed yet.
- A thermal printer that understands ZPL, reachable on your network. You need its network address and its resolution in dots per inch.
- No license key. Without one, the printed label carries the evaluation mark.

## Learn more

- [Printing](https://docs.p4software.cloud/barcoderx-en/printing)
- [Printer languages](https://docs.p4software.cloud/barcoderx-en/printer-languages)

---

*BarcoderX is a product of P4 Software.*
