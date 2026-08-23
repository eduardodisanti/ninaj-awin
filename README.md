# Ninaj Awin — The Eye of Fire

> **A historical archive of a 2015 multidisciplinary research and educational project of the Universidad Mayor de San Simón (UMSS), Cochabamba, Bolivia.**

In 2015, when small civilian drones were still relatively novel and today's mature AI, robotics and cloud ecosystems did not yet exist, students and faculty at **UMSS** set out to explore a difficult question:

**Could autonomous aerial systems detect smoke or fire early enough to support wildfire response?**

Ninaj Awin — *The Eye of Fire* — became much more than a computer-vision experiment. It brought together work in artificial intelligence, computer vision, autonomous agents, flight control, electronics, software engineering, communications, web/mobile systems and field operations around a concrete problem: wildfire detection, with **Parque Tunari** as the project's immediate environmental context.

The project operated with **less than US$4,000 in resources** and involved **nearly 100 students and faculty** across different activities and disciplines. Equipment was shared, adapted, repaired and improvised. Teams taught, learned, programmed, assembled hardware, trained classifiers, tested control systems, flew aircraft, worked late, sought local support and took the system outside the laboratory.

The surviving photographs and videos document that progression: early perception experiments using simple flame targets; a live SVM-based test detecting two candles simultaneously; aerial fire detection under changing viewpoints; night stabilization work; a first autonomous flight with a human guard; field work in the dry landscape of Parque Tunari; demonstrations with firefighters; and visits and media coverage as the students' work became visible beyond the project team.

## What this repository is

This repository is a **historical reconstruction and archive**. It preserves the project website, surviving audiovisual evidence, and links to source-code repositories from the period.

The old code is intentionally not rewritten to look modern. Python 2-era code, OpenCV/HOG/SVM experiments, Arduino/OpenPilot integration, Django/MongoDB components, sockets, image services and other period-specific implementation choices are part of the technical record.

Related surviving repositories include:

- [`ninaj-awin`](https://github.com/eduardodisanti/ninaj-awin) — historical umbrella repository and this archive
- [`drone_control`](https://github.com/eduardodisanti/drone_control) — autonomous control, image services and fire/smoke recognition
- [`inteligencia_visual`](https://github.com/eduardodisanti/inteligencia_visual) — computer-vision experiments, preprocessing, training-data generation and classifiers
- [`Control-Openpilot`](https://github.com/eduardodisanti/Control-Openpilot) — Arduino/OpenPilot control experiments
- [`FabricaWeb`](https://github.com/eduardodisanti/FabricaWeb) — Django, MongoDB/MongoEngine, REST, mobile and web infrastructure

## What this repository is not

This repository should **not** be interpreted as a claim that Ninaj Awin was a personal project of the repository owner.

**Ninaj Awin was a project of the Universidad Mayor de San Simón (UMSS).** It existed because students, faculty, collaborators and external participants contributed their time, knowledge and work.

This repository is maintained by **Eduardo Di Santi** as a personal historical archive to preserve surviving material and reconnect a fragmented project record. Ownership of this GitHub repository does not imply ownership of the original university project, nor of every photograph, video, software contribution or other work preserved here.

Where individual authorship or ownership can be reconstructed reliably, it should be attributed explicitly. Some historical attribution remains incomplete and will be improved as contributors and records are recovered.

## Historical scope

The archive distinguishes carefully between:

- what was **actually built and tested** in Bolivia in 2015;
- what was demonstrated experimentally;
- and broader applications for which the architecture was technically relevant.

For example, the project was tested in the context of Parque Tunari. The same engineering problem is relevant to other dry wildland environments, including Mediterranean and European regions, but this archive does **not** claim that Ninaj Awin was deployed operationally in Europe.

Likewise, Ninaj Awin did not become a production wildfire-monitoring service. Its significance lies in the experimental system, the multidisciplinary engineering effort, the educational experience, the surviving technical work and the people who made it happen under severe resource constraints.

## Why preserve it?

A Git repository can preserve code. It does not automatically preserve the story around the code.

This archive exists to remember the students and teachers who learned, taught, argued, soldered, debugged, flew, failed, repaired, returned the next day and eventually made the system work.

The photographs, videos and source code are therefore not decorative additions. Together they are the surviving evidence of the project.

## Project archive

The reconstructed public site is intended to be served through GitHub Pages:

**https://eduardodisanti.github.io/ninaj-awin/**

The archive will continue to evolve as additional photographs, videos, names, dates and contributions are identified.

## Rights, attribution and reuse

This repository is publicly accessible for **historical preservation, viewing, educational reference and citation**.

**Publicly accessible does not mean public domain.**

Unless a specific item explicitly states otherwise, photographs, videos, prose, graphics and archival materials are **all rights reserved**. Rights may be held by UMSS and/or by the respective authors, photographers, students, faculty members, contributors or other rights holders.

Reproduction, redistribution, republication, modification, exhibition, documentary use, dataset use, commercial exploitation or other reuse requires prior permission from the relevant rights holder(s), except where otherwise permitted by applicable law.

Third-party libraries or historical source components may carry their own licenses. Those licenses continue to apply to those components and are not superseded by this archival notice.

See [`LICENSE`](LICENSE) for the repository's full rights notice and [`CITATION.cff`](CITATION.cff) for machine-readable citation metadata.

### Suggested citation

> Universidad Mayor de San Simón (UMSS). (2015). *Ninaj Awin — The Eye of Fire* [multidisciplinary research and educational project]. Cochabamba, Bolivia. Historical archive maintained by Eduardo Di Santi, reconstructed 2026.

If citing a particular software component, photograph, video or contribution for which an individual author is known, please also credit that contributor.

---

**Project:** Universidad Mayor de San Simón (UMSS), Cochabamba, Bolivia · 2015  
**Historical archive:** maintained by Eduardo Di Santi · reconstructed 2026
