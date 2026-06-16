# VocalEyes — AudioToISLConverter

An early-stage project to convert spoken English/Hindi audio into Indian Sign Language (ISL), and to help interpret ISL back into spoken/written form — bridging the communication gap between the deaf and hard-of-hearing community and people who do not know sign language.

## Overview

Indian Sign Language (ISL) is a visual-gestural language used by deaf and hard-of-hearing individuals across India, combining hand movements, facial expressions, and body postures to convey meaning. A large communication barrier exists between ISL users and people who only communicate through spoken language, which makes everyday interactions in education, healthcare, transport, and public services difficult.

VocalEyes aims to reduce that barrier by using speech recognition, natural language processing, and computer vision / animation to:

- Transcribe and interpret English/Hindi audio and convert it into corresponding ISL gestures in (ideally) real time.
- Support the reverse direction — recognizing ISL gestures (e.g. via a mobile camera) and converting them into spoken/written language.

**Who it's for:** the deaf and hard-of-hearing community, and the people who interact with them (teachers, healthcare workers, transport staff, family members). Example use cases include converting railway-platform announcements into ISL, and a mobile app that lets a hearing person understand signs made by a deaf individual.

This repository was started as part of a hackathon problem statement (Problem Statement ID **1715**, Ministry of Social Justice and Empowerment). It currently collects the problem definition, dataset references, and supporting research rather than a running application.

## Tech stack

No application code has been committed yet, so there is no fixed stack. Based on the problem statement and the collected research, the intended building blocks are:

- **Speech recognition (ASR):** to transcribe English/Hindi audio.
- **Natural language processing:** to map transcribed text to ISL grammar/glosses.
- **Computer vision / 3D animation:** to render ISL gestures, and to recognize signs from camera input for the reverse flow.
- **Target platforms:** web and/or mobile application.

The intended dataset and language reference is the **Indian Sign Language Research and Training Centre (ISLRTC)** — https://www.islrtc.nic.in — alongside the academic papers gathered in `Research papers/`.

## Getting started

There is no buildable/runnable code in this repository yet, so there is nothing to install or launch at the moment.

To explore the project's research and planning materials:

```bash
git clone https://github.com/komalboyo/VocalEyes.git
cd VocalEyes
# open the PDFs in "Research papers/" with any PDF viewer
```

When implementation begins, this section should document the install steps, the run command, and any required environment variables (for example, API key names for an ASR/translation service and a model/dataset path). No secrets or credentials should ever be committed — only the variable **names** belong in this README.

## Project structure

```
.
├── README.md          # Problem statement, overview, and references (this file)
└── Research papers/    # Academic papers and dataset references on audio-to-ISL translation
```

The `Research papers/` directory contains background literature on audio/speech-to-ISL conversion, sign-language translation, and related datasets (including the ISLTranslate dataset).

## Status

**Prototype / research stage — not yet functional.**

This repository currently holds the problem statement and a collection of reference papers only. There is no application source code, build configuration, or model in the repo, so nothing runs end-to-end today. It serves as the planning and research foundation for the VocalEyes audio-to-ISL converter.

## References

- **Problem Statement ID:** 1715 — *AI tool / mobile app for Indian Sign Language (ISL) generator from audio-visual content in English/Hindi to ISL content and vice-versa* (Ministry of Social Justice and Empowerment).
- **Dataset / language reference:** ISLRTC — https://www.islrtc.nic.in
- **Related project:** SignPal — https://github.com/soodaryan/SignPal
- **Research papers:** see the `Research papers/` directory.
