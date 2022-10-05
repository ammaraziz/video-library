---
layout: event
id: camtraining
title: "WHOCC Bioinformatics Training"
description: "Cambodia Training"
certbot: false
institutions: [whocc]
instructors:
 - 

date:
  start: 2022-10-10
  end: 2022-10-15

practical:
  - name: Infustracture
    text: "[Galacy Australia Training Server](https://usegalaxy.org.au/join-training/whocc_cambodia)"

setup:
  servers:
    - server: au
      tiaas: whocc_cambodia

program:
  day0:
    title: Please install the following software
    description: |
      - Modern browser Firefox/Chrome/Edge
      - [UGENE](http://ugene.net/download-all.html) 
      - [Notepad++](https://notepad-plus-plus.org/downloads/) or [Sublime](https://www.sublimetext.com/download)
      - [Figtree](https://github.com/rambaut/figtree/releases)
      - [Inkscape](https://inkscape.org/release/inkscape-1.2.1/)
      - MS office or [LibreOffice](https://www.libreoffice.org/)
      - [7zip](https://www.7-zip.org/)
  day1:
    title: "Day 1 - Overview and theory of NGS technologies"
    description: |
      Objectives:
        - Gain an understanding  of sequencing technology (Sanger, Illumina, ONT)
        - Overview of Illumina/ONT output file structure
        - Overview of commonly used file formats (Fasta, Fastq etc)
        - Recommended best practices
    trainings:
      - external:
        title: DNA Sequencing - Definition, Principle, Steps, Types, Uses
        description: test
        other:
          - label: Types of Sequencing
            value: https://thebiologynotes.com/dna-sequencing-principle-steps-types-uses/
          - label: Overview of NGS technology
            value: https://thebiologynotes.com/dna-sequencing-principle-steps-types-uses/
      - tutorial: introduction/galaxy-intro-ngs-data-managment
      - video: galaxy/intro
      - video: sequence-analysis/quality-control/slides
      - video: sequence-analysis/quality-control/tutorial
      - video: sequence-analysis/mapping/slides
      - video: sequence-analysis/mapping/tutorial
  day2:
    title: "Day 2"
    description: "Some description about today's content"
    trainings:
      - video: variant-analysis/sars-cov-2-variant-discovery/tutorial

---
## Course Description
