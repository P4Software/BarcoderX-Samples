<p align="center"><img src="brand/barcoderx-horizontal.svg" alt="BarcoderX" width="280"></p>

# BarcoderX Samples

[Español](README.es.md)

## What this repository is

This is the home of the sample programs for BarcoderX, a toolkit for developers to design, preview and print labels with barcodes, especially on thermal printers. BarcoderX is built on .NET 10. Each sample is a small program that shows one thing and says in plain words what it did.

## Where things stand today

BarcoderX is under development. Nothing is released yet, and there is no package to install. **No sample here can run yet.**

What exists today is the structure: one folder for each topic, with a short README that says what the sample will show and what you will need. Every topic is marked **Planned**.

Samples arrive with the features they show. When a feature is finished, its sample is added here, and only then does its status change to **Available**. A folder holds a real program only when its feature is finished. Until then, it holds only the README.

## Sample index

| Topic | What it shows | Status | Folder | Guide |
|---|---|---|---|---|
| First label in code | The shortest path from nothing to one finished label, from a .NET program | Planned | [01-first-label-in-code](01-first-label-in-code/) | [How the pieces fit](https://docs.p4software.cloud/barcoderx-en/how-the-pieces-fit) |
| PNG and PDF output | One label saved as a PNG picture and as a PDF file | Planned | [02-png-and-pdf-output](02-png-and-pdf-output/) | [Output formats](https://docs.p4software.cloud/barcoderx-en/output-formats) |
| Barcodes (linear, 2D, GS1) | Barcodes of each kind, with check digits and readable text | Planned | [03-barcodes](03-barcodes/) | [Barcodes](https://docs.p4software.cloud/barcoderx-en/barcodes) |
| Text and fonts | Text layout, the built-in font and a font that you upload | Planned | [04-text-and-fonts](04-text-and-fonts/) | [Text, fonts and pictures](https://docs.p4software.cloud/barcoderx-en/text-fonts-and-pictures) |
| Templates and data binding | One template, many records, one label for each | Planned | [05-templates-and-data-binding](05-templates-and-data-binding/) | [Templates and data](https://docs.p4software.cloud/barcoderx-en/templates-and-data) |
| Printing to a ZPL printer over the network | A label sent from your program straight to a printer on your network | Planned | [06-print-to-zpl-over-network](06-print-to-zpl-over-network/) | [Printing](https://docs.p4software.cloud/barcoderx-en/printing) |
| The web API | Create a print job and read its status | Planned | [07-web-api-print-job](07-web-api-print-job/) | [Web API](https://docs.p4software.cloud/barcoderx-en/web-api) |
| The label editor in React, Angular and Vue | The editor embedded in a web page of each framework | Planned | [08-label-editor](08-label-editor/) | [The label editor](https://docs.p4software.cloud/barcoderx-en/label-editor) |
| The print agent | The agent installed near your printers and paired with your server | Planned | [09-print-agent](09-print-agent/) | [The print agent](https://docs.p4software.cloud/barcoderx-en/print-agent) |
| Licensing and the evaluation mark | The same label with and without a license key | Planned | [10-licensing-and-evaluation-mark](10-licensing-and-evaluation-mark/) | [Evaluation mark and license keys](https://docs.p4software.cloud/barcoderx-en/evaluation-and-licence-keys) |

The full set of guides is in the [BarcoderX user guide](https://docs.p4software.cloud/barcoderx-en/overview).

## What you will need

When samples exist, you will need:

- The .NET 10 SDK.
- Windows x64, Linux x64 or Linux arm64.
- A license key is optional. Without one, everything still works, and the output carries the evaluation mark.

The samples are written in C#. Samples for the web API, the editor and the print agent also need an API server that you install and run yourself. BarcoderX hosts nothing for you, so every sample runs on your own computers.

Each sample README lists anything more that its sample needs.

## How to run a sample

Once a sample is Available, open its folder, read its README and run it. Most samples start with one command, `dotnet run`, and the README tells you if a sample needs something different. The sample prints what it did, in plain words, and what to do next.

## Report a problem

[Open an issue](https://github.com/P4Software/BarcoderX-Samples/issues). Please say which sample folder you used, which operating system you run, what you expected and what happened. Never paste a license key or an API key into an issue.

---

*BarcoderX is a product of P4 Software.*
