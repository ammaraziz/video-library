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
    title: "Session 1: From Wet to Dry - Overview of NGS Technology"
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
          title: Resources on bioinfo file formats
          other:
            - label: Sequence file formats
              link: https://www.algosome.com/articles/bioinformatics-sequence-file-formats.html
            - label: Sequence file formats vcf and gff
              link: https://www.hadriengourle.com/tutorials/file_formats/
      - external: 
          title: Understanding the output of Illumina/ONT
          other:
            - label: Illumina ncl2fastq2 pdf
              link: http://www.bea.ki.se/documents/bcl2fastq.pdf
            - label: ONT
              link: https://stab.st-andrews.ac.uk/wiki/index.php/MinKNOW_folders_and_log_files
      - video: galaxy/intro

  day2:
    title: "Session 2: From Reads to Trees"
    description: |
      Objectives:
        - Theory and practice of assessing the quality of your sequencing data
        - Theory of mapping sequencing reads to a reference genome
        - Phylogenetic theory and practice
        - Hands on experience with Galaxy for Mapping, Variant Calling, Consensus and Phylogenetics
    trainings:
      - video: sequence-analysis/quality-control/slides
      - video: sequence-analysis/mapping/slides
      - video: variant-analysis/sars-cov-2-variant-discovery/tutorial
      - self-study: variant-analysis/non-dip
      - external:
          title: Introduction to Phylogenetics
          video: QasuKryesOQ
          other:
            - label: EMBL Online Course on Phylogenetics
              link: https://www.ebi.ac.uk/training/online/courses/introduction-to-phylogenetics/what-is-phylogenetics/
            - label: How to read a phylogenetic tree by Andrew Rambaut
              link: https://artic.network/how-to-read-a-tree.html
      - self-study: evolution/mtb_phylogeny
  day3:
    title: "Session 3: From Noice to Proficent - What next?
    description: |
        - Resources for future learning
        - Support post-training
        - Galaxy Training Network
        - GCC2023 - Brisbane
        - Q&A
    trainings:
      - self-study: galaxy-interface/workflow-editor
        prefix: "(Optional)"
      - video: galaxy-interface/upload-to-ena
      - video: metagenomics/introduction/slides
      - video: transcriptomics/scrna-intro/slides
      - external:
        title: "Resource: The Carpentries"
          - label: "Carpentries for Genomics"
            link: https://datacarpentry.org/lessons/#genomics-workshop
          - label: "Carpentries for Software R and Python"
            link: https://software-carpentry.org/lessons/
          - label: "The Carpentries Main Site"
            link: https://carpentries.org/workshops-curricula/
---
