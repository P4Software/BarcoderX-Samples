<p align="center"><img src="../brand/barcoderx-horizontal.svg" alt="BarcoderX" width="280"></p>

# The print agent

[Español](README.es.md)

> **Status:** Planned. This folder holds no program yet. It will hold one when the feature is finished. BarcoderX is not released, so nothing here can run today.

## What this sample will show

How to put the print agent on a computer that is on the same network as your printers and connect it to your own server. An administrator creates a one-time pairing code on the server, the code is entered on the agent, and the agent then lists the printers it can reach so that you can register them. The agent only connects out, so it needs no open incoming port. The sample ends by printing one label through the agent and saying in plain words what happened.

## What you will need

- An API server that you installed and run yourself, and an administrator account on it.
- A computer on the same network as your printers: Windows 10, Windows 11 or Windows Server 2019 or later, or Linux on x64 or arm64 with systemd.
- A permitted outbound HTTPS and WebSocket connection from that computer to your server.
- A thermal printer that the computer can reach.
- Nothing can be installed yet, because BarcoderX is not released.

## Learn more

- [The print agent](https://docs.p4software.cloud/barcoderx-en/print-agent)
- [Printing](https://docs.p4software.cloud/barcoderx-en/printing)

---

*BarcoderX is a product of P4 Software.*
