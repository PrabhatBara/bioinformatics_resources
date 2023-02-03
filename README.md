# Bioinformatics Resources [![GitHub Super-Linter](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/linter.yml/badge.svg)](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/linter.yml) [![Generate TOC](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/toc.yml/badge.svg)](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/toc.yml)

> Bioinformatics is an interdisciplinary field that develops methods and software tools for understanding biological data. It is a new emerging discipline that combines mathematics, information science, and biology and helps answer biological questions — [ScienceDirect](https://www.sciencedirect.com/science/article/pii/B9780123749840001558)

This reposition contains a curated list of Bioinformatics software, resources, libraries, databases and tutorials that can help you in answering your question. You can use this as a central point of reference. Please feel free to [contribute](CONTRIBUTING.md)!

### Table Of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Package suites](#package-suites)
- [Data Tools](#data-tools)
  - [Downloading](#downloading)
  - [Compressing](#compressing)
- [Data Processing](#data-processing)
  - [Command Line Utilities](#command-line-utilities)
- [Next Generation Sequencing](#next-generation-sequencing)
  - [Workflow Managers](#workflow-managers)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Package suites

Package suites gather software packages and installation tools for specific languages or platforms. We have some for bioinformatics software.

- **[Bioperl](https://github.com/bioperl/bioperl-live)** - International association of users & developers of open source Perl tools for bioinformatics, genomics and life sciences. [ [paper-2002](https://doi.org/10.1101%2Fgr.361602) | [web](https://bioperl.org) ]

- **[Bioconductor](https://github.com/Bioconductor)** - A plethora of tools for analysis and comprehension of high-throughput genomic data, including 1500+ software packages. [ [paper-2004](https://link.springer.com/article/10.1186/gb-2004-5-10-r80) | [web](https://www.bioconductor.org) ]

- **[Biopython](https://github.com/biopython/biopython)** - Freely available tools for biological computing in Python, with included cookbook, packaging and thorough documentation. Part of the [Open Bioinformatics Foundation](http://open-bio.org/). Contains the very useful [Entrez](https://biopython.org/DIST/docs/api/Bio.Entrez-module.html) package for API access to the NCBI databases. [ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19304878) | [web](https://biopython.org) ]

- **[Bioconda](https://github.com/bioconda)** - A channel for the [conda package manager](http://conda.pydata.org/docs/intro.html) specializing in bioinformatics software. Includes a repository with 3000+ ready-to-install (with `conda install`) bioinformatics packages. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29967506) | [web](https://bioconda.github.io) ]

- **[BioJulia](https://github.com/BioJulia)** - Bioinformatics and computational biology infastructure for the Julia programming language. [ [web](https://biojulia.net) ]
- **[Rust-Bio](https://github.com/rust-bio/rust-bio)** - Rust implementations of algorithms and data structures useful for bioinformatics. [ [paper-2016](http://bioinformatics.oxfordjournals.org/content/early/2015/10/06/bioinformatics.btv573.short?rss=1) ]
- **[SeqAn](https://github.com/seqan/seqan3)** - The modern C++ library for sequence analysis.
- **[(Poly)merase](https://github.com/TimothyStiles/poly)** - A Go library and command line utility for engineering organisms.
- **[Biocaml](https://github.com/biocaml/biocaml)** - Biocaml aims to be a high-performance user-friendly library for Bioinformatics.

## Data Tools

### Downloading
- **[GGD](https://github.com/gogetdata/ggd-cli)** - Go Get Data; A command line interface for obtaining genomic data. [ [web](https://gogetdata.github.io) ]
- **[SRA-Explorer](https://github.com/ewels/sra-explorer)** - Easily get SRA download links and other information. [ [web](https://sra-explorer.info) ]

### Compressing
- **[Genozip](https://github.com/divonlan/genozip)** - A compressor of common genomic file formats (BAM, CRAM, FASTQ, VCF etc). [ [web](https://genozip.com/?utm_source=Awesome-Bioinformatics) | [paper-2021](https://www.researchgate.net/publication/349347156_Genozip_-_A_Universal_Extensible_Genomic_Data_Compressor) ]

## Data Processing

### Command Line Utilities

- **[Bioinformatics One Liners](https://github.com/stephenturner/oneliners)** - Git repo of useful single line commands.
- **[BioNode](https://github.com/bionode/bionode)** - Modular and universal bioinformatics, Bionode provides pipeable UNIX command line tools and JavaScript APIs for bioinformatics analysis workflows. [ [web](http://bionode.io) ]
- **[bioSyntax](https://github.com/bioSyntax/bioSyntax)** - Syntax Highlighting for Computational Biology file formats (SAM, VCF, GTF, FASTA, PDB, etc...) in vim/less/gedit/sublime. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/30134911) | [web](http://www.bioSyntax.org) ]
- **[CSVKit](https://github.com/wireservice/csvkit)** - Utilities for working with CSV/Tab-delimited files. [ [web](https://csvkit.readthedocs.io/en/latest) ]
- **[csvtk](https://github.com/shenwei356/csvtk)** - Another cross-platform, efficient, practical and pretty CSV/TSV toolkit. [ [web](https://bioinf.shenwei.me/csvtk) ]
- **[datamash](https://git.savannah.gnu.org/gitweb/?p=datamash.git)** - Data transformations and statistics. [ [web](http://www.gnu.org/software/datamash) ]
- **[easy_qsub](https://github.com/shenwei356/easy_qsub)** - Easily submitting PBS jobs with script template. Multiple input files supported.
- **GNU Parallel** - General parallelizer that runs jobs in parallel on a single multi-core machine. [Here](https://www.biostars.org/p/63816/) are some example scripts using GNU Parallel. [ [web](http://www.gnu.org/software/parallel) ]
- **[grabix](https://github.com/arq5x/grabix)** - A wee tool for random access into BGZF files.
- **[gsort](https://github.com/brentp/gsort)** - Sort genomic files according to a specified order.
- **[tabix](https://github.com/samtools/tabix)** - Table file index. [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21208982) ]
- **[wormtable](https://github.com/wormtable/wormtable)** - Write-once-read-many table for large datasets.
- **[zindex](https://github.com/mattgodbolt/zindex)** - Create an index on a compressed text file.

## Next Generation Sequencing

### Workflow Managers

- **[BigDataScript](https://github.com/pcingola/BigDataScript)** - A cross-system scripting language for working with big data pipelines in computer systems of different sizes and capabilities. [ [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25189778) | [web](https://pcingola.github.io/BigDataScript) ]
- **[Bpipe](https://github.com/ssadedin/bpipe)** - A small language for defining pipeline stages and linking them together to make pipelines. [ [web](http://docs.bpipe.org) ]
- **[Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)** - a specification for describing analysis workflows and tools that are portable and scalable across a variety of software and hardware environments, from workstations to cluster, cloud, and high performance computing (HPC) environments. [ [web](http://www.commonwl.org) ]
- **[Cromwell](https://github.com/broadinstitute/cromwell)** - A Workflow Management System geared towards scientific workflows. [ [web](https://cromwell.readthedocs.io) ]
- **[Galaxy](https://github.com/galaxyproject)** - a popular open-source, web-based platform for data intensive biomedical research. Has several features, from data analysis to workflow management to visualization tools. [ [paper-2018](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6030816) | [web](https://galaxyproject.org) ]
- **[Nextflow](https://github.com/nextflow-io/nextflow) (recommended)** - A fluent DSL modelled around the UNIX pipe concept, that simplifies writing parallel and scalable pipelines in a portable manner. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29412134) | [web](http://nextflow.io) ]
- **[redun](https://github.com/insitro/redun)** - A python-based workflow manager.
- **[Ruffus](https://github.com/cgat-developers/ruffus)** - Computation Pipeline library for python widely used in science and bioinformatics. [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20847218) | [web](http://www.ruffus.org.uk) ]
- **[SciPipe](https://github.com/scipipe/scipipe)** - Workflow library embedded in the Go programming language, focusing on supporting complex workflow constructs, compiling to a single binary, providing powerful file naming and comprehensive audit reports for every output [ [paper-2019](https://pubmed.ncbi.nlm.nih.gov/31029061/) | [web](https://scipipe.org/) ]
- **[SeqWare](https://github.com/SeqWare/seqware)** - Hadoop Oozie-based workflow system focused on genomics data analysis in cloud environments. [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/21210981) | [web](https://seqware.github.io) ]
- **[Snakemake](https://bitbucket.org/snakemake)** - A workflow management system in Python that aims to reduce the complexity of creating workflows by providing a fast and comfortable execution environment. [ [paper-2018](https://pubmed.ncbi.nlm.nih.gov/29788404) | [web](https://snakemake.readthedocs.io) ]
- **[Workflow Descriptor Language](https://github.com/broadinstitute/wdl)** - Workflow standard developed by the Broad. [ [web](https://software.broadinstitute.org/wdl) ]

### Pipelines

- **[Awesome-Pipeline](https://github.com/pditommaso/awesome-pipeline)** - A list of pipeline resources.
- **[Bactopia](https://github.com/bactopia/bactopia/)** - A flexible pipeline, built with Nextflow, for the complete analysis of bacterial genomes. [ [web](https://bactopia.github.io/) ]
- **[Bacannot](https://github.com/fmalmeida/bacannot)** - A generic but comprehensive bacterial annotation pipeline, built with Nextflow, with nice graphical options for investigating results. [ [web](https://bacannot.readthedocs.io/en/latest/?badge=latest) ]
- **[bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen)** - Batteries included genomic analysis pipeline for variant and RNA-Seq analysis, structural variant calling, annotation, and prediction. [ [web](https://bcbio-nextgen.readthedocs.io) ]
- **[R-Peridot](https://github.com/pentalpha/r-peridot)** - Customizable pipeline for differential expression analysis with an intuitive GUI. [ [web](http://www.bioinformatics-brazil.org/r-peridot) ]
- **[ngs-preprocess](https://github.com/fmalmeida/ngs-preprocess)** - A pipeline for preprocessing short and long sequencing reads, built with Nextflow. [ [web](https://ngs-preprocess.readthedocs.io/en/latest/?badge=latest) ]
- **[Awesome Nextflow](https://github.com/nextflow-io/awesome-nextflow)** - A curated list of Nextflow pipelines, tutorials and resources. [[web](https://github.com/nextflow-io/awesome-nextflow)]

## Databases

- **[Pan-UkBioBank GWAS](https://pan.ukbb.broadinstitute.org/)** - Multi-ancestry analysis of 7,228 phenotypes using a generalized mixed model association testing framework, spanning 16,131 genome-wide association studies reporting GWAS summary Statistics. [[web](https://pan.ukbb.broadinstitute.org/)]
- **[FinnGen- BioBank](https://www.finngen.fi/en/access_results)** - FinnGen is a large public-private partnership aiming to collect and analyse genome and health data from 500,000 Finnish biobank participants. Reporting GWAS summary data for Free Access [[web](https://www.finngen.fi/en)]
- **[GEO- Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/)** - GEO is a public functional genomics data repository supporting MIAME-compliant data [[web](https://www.ncbi.nlm.nih.gov/geo/summary/)]. Some repositories hosting consistently processed GEO Data

  -**[DEE2- Digital Expression Explorer](https://dee2.io/)** - Digital Expression Explorer 2 (DEE2) is a repository of uniformly processed RNA-seq data mined from public data obtained from NCBI Sequence Read Archive. [[web](https://dee2.io/)]
  - **[ARCHS4- Massive Mining of Publicly Available RNA-seq Data from Human and Mouse]()** - All RNA-seq and ChIP-seq sample and signature search (ARCHS4) is a resource that provides access to gene and transcript counts uniformly processed from all human and mouse RNA-seq experiments from the Gene Expression Omnibus (GEO) and the Sequence Read Archive (SRA).[[web](https://maayanlab.cloud/archs4/)]
- **[ArrayExpress - Functional Genomics Data](https://www.ebi.ac.uk/biostudies/arrayexpress)** - The functional genomics data collection (ArrayExpress), stores data from high-throughput functional genomics experiments, and provides data for reuse to the research community. [[web](https://www.ebi.ac.uk/biostudies/arrayexpress)]
- **[Expression Atlas](https://www.ebi.ac.uk/gxa/home)** - Expression Atlas is an open science resource that gives users a powerful way to find information about gene and protein expression [[web](https://www.ebi.ac.uk/gxa/home)]
- **[LINCS-Library of Integrated Network-Based Cellular Signatures](https://lincsproject.org/)** - Gene expression profiles that occur when cells(cancer cell lines) are exposed to a variety of perturbing agents Drugs and iRNA. [[web](https://lincsproject.org/)]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
- **[]()** - [[]()]
