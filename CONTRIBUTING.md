<p align="center"><img src="brand/barcoderx-horizontal.svg" alt="BarcoderX" width="280"></p>

# Contributing to BarcoderX Samples

This page is for the BarcoderX team. It says how a sample gets into this repository and what a finished sample must look like. The repository is public, so everything you add is read by customers.

## How a sample gets here

1. Every feature work package in the product repository ends with a hand-over that includes **sample notes**: the smallest program that shows the feature working. The notes say what the program does, what it needs and what it prints.
2. A sample is added here in the **same wave** in which its feature merges in the product repository. Not earlier: public API names are frozen late, and a sample written against a name that later changes is wrong the day it is published. Not later: a feature without a sample is not finished.
3. Until the feature has merged and its names are final, the topic folder holds only the planned-sample README. Do not write a program that calls BarcoderX before then.
4. The sample is added in a pull request on a branch. Nobody pushes to `main`. The owner merges.

## What a finished sample must do

- **One command.** It builds and runs with one command, written at the top of its README. No switches to learn and no environment variables to set.
- **Plain words.** It prints what it did and what to do next, in plain language. A person who has never seen the product can read the output and know whether it worked. The window never closes before the result can be read.
- **Settings in a file.** Anything the sample needs from the user, such as a printer address, lives in a JSON settings file next to the program. If the file is missing, the sample creates a commented starter file on its first run.
- **Safe by default.** A sample that prints, sends or changes anything starts as a dry run that shows what it would do. A setting that the user changes on purpose makes it really do it.
- **No secrets.** No license key, API key, password or customer data in the code, the settings file, the output, a screenshot or a pull request. A sample reads such values from the user's own settings file, and the starter file holds a clear placeholder.
- **Small.** One sample shows one thing. Put shared helper code in the sample that needs it, not in a library for all samples.
- **Real.** A sample never fakes a result. If a sample needs a server or a printer, its README says so before anything else.

## What each sample folder holds

| File | Content |
|---|---|
| `README.md` | The English README. |
| `README.es.md` | The Spanish README, with the same structure and the same facts. |
| The program | Only once the feature is merged and its names are final. |

A README for an Available sample has these sections, in this order: what the sample shows; what you will need; how to run it (the one command); what it prints and what to expect; learn more (a link to the guide page, in English in `README.md` and in Spanish in `README.es.md`).

## English and Spanish change together

- A change to `README.md` is a change to `README.es.md` in the same pull request, and the other way round. The root README, its Spanish twin and every topic folder follow this rule.
- Every message that a sample prints to the user exists in English and in Spanish.
- Spanish is Panama Spanish. Address the reader as "usted", never "tú".
- Use US English spelling: license, color, center, meter.

## Keeping the index true

- The sample index in `README.md` and `README.es.md` lists every topic with a status: **Planned** or **Available**.
- The status changes from Planned to Available **in the same pull request** that adds the working program. Never before.
- Every link to a guide page is checked: it must return HTTP 200 before it goes in. The page names come from the published guide at https://docs.p4software.cloud/barcoderx-en/overview and its Spanish twin.
- When the first sample is Available, tell the owner so that the Samples page of the product guide is updated too.

## Wording rules

- The brand shown to users is **BarcoderX**. The name of the company appears only in the one small footer line at the end of each README.
- BarcoderX has no hosted service. Customers' developers run everything themselves. BarcoderX keeps only the developer's account, license keys and the versions they may download. Never write a sentence that suggests data goes to BarcoderX.
- No prices, and no promise about editions or plans beyond what the published guide already says.
- Never name a competing label or barcode product.
- Never write "certified" or "compliant".
- Do not write about the future as if it had happened. A feature that is not released is "planned".

## Brand

- Every README starts with the logo from `brand/barcoderx-horizontal.svg`. Use that file as it is. Set a width and leave the height alone, so the proportions never change. Do not recolor, crop or redraw it.
- In a topic folder, the path to the logo is `../brand/barcoderx-horizontal.svg`.
- Light theme only. Do not add a dark variant of anything.

## License

Every sample added here is released under the repository's MIT License (see `LICENSE`).

## Commits and pull requests

- A commit message describes the change and nothing else. The same goes for a pull request description. They carry no co-author trailer and no credit line of any kind.
- Branch names say what the branch does, for example `sample/first-label-in-code`.

---

*BarcoderX is a product of P4 Software.*
