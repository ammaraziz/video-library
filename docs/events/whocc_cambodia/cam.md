---
layout: event
id: camtraining
title: "WHOCC Bioinformatics Training"
description: "Cambodia Training"
certbot: false
institutions: [whocc]
instructors: [aaziz]

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
          other:
            - label: 1 Types of Sequencing
              link: https://thebiologynotes.com/dna-sequencing-principle-steps-types-uses/
            - label: 2 Overview of NGS technology
              link: https://thebiologynotes.com/next-generation-sequencing-ngs/
      - video: introduction/galaxy-intro-ngs-data-managment
        prefix: Common data formats
      - external:
          title: Common data formats 2
          other:
            - label: Sequence file formats 1
              link: https://www.algosome.com/articles/bioinformatics-sequence-file-formats.html
            - label: vcf and gff
              link: https://www.hadriengourle.com/tutorials/file_formats/
      - external: 
          title: Understanding the output of Illumina/ONT
          other:
            - label: Illumina ncl2fastq2 [pdf]
              link: https://support.illumina.com/content/dam/illumina-support/documents/documentation/software_documentation/bcl2fastq/bcl2fastq2-v2-20-software-guide-15051736-03.pdf
            - label: ONT
              link: https://stab.st-andrews.ac.uk/wiki/index.php/MinKNOW_folders_and_log_files
      - video: galaxy/intro
      - video: sequence-analysis/quality-control/slides
      - video: sequence-analysis/mapping/slides
  day2:
    title: "Day 2"
    description: "Some description about today's content"
    trainings:
      - video: variant-analysis/sars-cov-2-variant-discovery/tutorial

---
