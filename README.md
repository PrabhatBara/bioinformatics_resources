# Bioinformatics Resources [![GitHub Super-Linter](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/linter.yml/badge.svg)](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/linter.yml) [![Generate TOC](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/toc.yml/badge.svg)](https://github.com/PrabhatBara/bioinformatics_resources/actions/workflows/toc.yml)

> Bioinformatics is an interdisciplinary field that develops methods and software tools for understanding biological data. It is a new emerging discipline that combines mathematics, information science, and biology and helps answer biological questions — [ScienceDirect](https://www.sciencedirect.com/science/article/pii/B9780123749840001558)

This repository contains a curated list of Bioinformatics software, resources, libraries, databases and tutorials that can help you in answering your question. You can use this as a central point of reference. Please feel free to [contribute](CONTRIBUTING.md)!

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
  - [Pipelines](#pipelines)
- [Databases](#databases)

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
- **[DEPMAP](https://depmap.org/portal/depmap/)** - Profiles of hundreds of cancer cell line models for genomic information and sensitivity to genetic and small molecule perturbation [[web](https://depmap.org/portal/depmap/)]
- **[CCLE](https://sites.broadinstitute.org/ccle/)** - Large-scale genetic characterization of ~1000 cancer cell lines[[web](https://sites.broadinstitute.org/ccle/)]
- **[TCGA](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga)** - molecularly characterized 20,000 primary cancer and matched normal samples spanning 33 cancer types. [[web](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga)]
- **[COSMIC db](https://cancer.sanger.ac.uk/cosmic)** - Catalogue Of Somatic Mutations In Cancer, is the world's largest and most comprehensive resource for exploring the impact of somatic mutations in human cancer. [[web](https://cancer.sanger.ac.uk/cosmic)]
- **[ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/)** - Public archive of reports of the relationships among human variations and phenotypes, with supporting evidence [[web](https://www.ncbi.nlm.nih.gov/clinvar/)]
- **[dbSNP](https://www.ncbi.nlm.nih.gov/snp/)** - Public-domain archive for a broad collection of simple genetic polymorphisms[[web](https://www.ncbi.nlm.nih.gov/snp/)]
- **[gnomAD](https://gnomad.broadinstitute.org/)** - Aggregated and harmonized exome and genome sequencing data from a wide variety of large-scale sequencing projects[[web](https://gnomad.broadinstitute.org/)]
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

### Sequence Processing

Sequence Processing includes tasks such as demultiplexing raw read data, and trimming low quality bases.

- **[AfterQC](https://github.com/OpenGene/AfterQC)** - Automatic Filtering, Trimming, Error Removing and Quality Control for fastq data. [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28361673) ]
- **[FastQC](https://github.com/s-andrews/FastQC)** - A quality control tool for high throughput sequence data. [ [web](http://www.bioinformatics.babraham.ac.uk/projects/fastqc) ]
- **[Fastqp](https://github.com/mdshw5/fastqp)** - FASTQ and SAM quality control using Python.
- **[Fastx Tookit](https://github.com/agordon/fastx_toolkit)** - FASTQ/A short-reads pre-processing tools: Demultiplexing, trimming, clipping, quality filtering, and masking utilities. [ [web](http://hannonlab.cshl.edu/fastx_toolkit) ]
- **[MultiQC](https://github.com/ewels/MultiQC)** - Aggregate results from bioinformatics analyses across many samples into a single report. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27312411) | [web](http://multiqc.info) ]
- **[SeqFu](https://github.com/telatin/seqfu2)** - Sequence manipulation toolkit for FASTA/FASTQ files written in Nim. [ [paper-2021](https://www.mdpi.com/2306-5354/8/5/59) | [web](https://telatin.github.io/seqfu2/) ]
- **[SeqKit](https://github.com/shenwei356/seqkit)** - A cross-platform and ultrafast toolkit for FASTA/Q file manipulation in Golang. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27706213) | [web](https://bioinf.shenwei.me/seqkit) ]
- **[seqmagick](https://github.com/fhcrc/seqmagick)** - file format conversion in Biopython in a convenient way. [ [web](http://seqmagick.readthedocs.io) ]
- **[Seqtk](https://github.com/lh3/seqtk)** - Toolkit for processing sequences in FASTA/Q formats.
- **[smof](https://github.com/incertae-sedis/smof)** - UNIX-style FASTA manipulation tools.

### Data Analysis

The following items allow for scalable genomic analysis by introducing specialized databases.

- **[Hail](https://github.com/hail-is/hail)** - Scalable genomic analysis.
- **[GLNexus](https://github.com/dnanexus-rnd/GLnexus)** - Scalable gVCF merging and joint variant calling for population sequencing projects. [ [paper-2018](https://www.biorxiv.org/content/10.1101/343970v1.abstract) ]

### Sequence Alignment

#### Pairwise

- **[Bowtie 2](https://github.com/BenLangmead/bowtie2)** - An ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences. [ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22388286) | [web](http://bowtie-bio.sourceforge.net/bowtie2) ]
- **[BWA](https://github.com/lh3/bwa)** - Burrow-Wheeler Aligner for pairwise alignment between DNA sequences.
- **[WFA](https://github.com/smarco/WFA)** - the wavefront alignment algorithm (WFA) which expoit sequence similarity to speed up alignment [ [paper-2020](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaa777/5904262) ]
- **[Parasail](https://github.com/jeffdaily/parasail)** - SIMD C library for global, semi-global, and local pairwise sequence alignments [ [paper-2016](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0930-z) ]
- **[MUMmer](https://github.com/mummer4/mummer)** -  A system for rapidly aligning entire genomes, whether in complete or draft form. [ [paper-1999](http://mummer.sourceforge.net/MUMmer.pdf) | [paper-2002](http://mummer.sourceforge.net/MUMmer2.pdf) | [paper-2004](http://mummer.sourceforge.net/MUMmer3.pdf) | [web](http://mummer.sourceforge.net) ]
- **[DIAMOND](https://github.com/bbuchfink/diamond)** - An ultrafast protein aligner for `blastp` and `blastx` like searches. [ [paper-2021](https://www.nature.com/articles/s41592-021-01101-x) ]
- **[STAR](https://github.com/alexdobin/STAR)** - Aligning high-throughput long and short RNA-seq data to a reference genome using SA algorithm [[paper-2013](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3530905/)]
- **[]()** - [[]()]
- **[]()** - [[]()]


#### Multiple Sequence Alignment

- **[POA](https://github.com/ljdursi/poapy)** - Partial-Order Alignment for fast alignment and consensus of multiple homologous sequences. [ [paper-2002](https://academic.oup.com/bioinformatics/article/18/3/452/236691) ]

#### Clustering

- **[MMseqs2](https://github.com/soedinglab/MMseqs2)** - Ultra-fast, sensitive search and clustering suite for protein and nucleotide sequence sets. [ [paper-2017](https://www.nature.com/articles/nbt.3988) | [paper-2018](https://www.nature.com/articles/s41467-018-04964-5) ]

### Quantification

- **[Cufflinks](https://github.com/cole-trapnell-lab/cufflinks)** - Cufflinks assembles transcripts, estimates their abundances, and tests for differential expression and regulation in RNA-Seq samples. [ [paper-2010](https://www.nature.com/articles/nbt.1621) ]
- **[RSEM](https://github.com/deweylab/RSEM)** - A software package for estimating gene and isoform expression levels from RNA-Seq data. [ [paper-2011](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-323) | [web](http://deweylab.github.io/RSEM/) ]

### Variant Calling

- **[DeepVariant](https://github.com/google/deepvariant)** - Deep learning-based variant caller [ [paper-2018](https://rdcu.be/7Dhl) ]
- **[freebayes](https://github.com/ekg/freebayes)** - Bayesian haplotype-based polymorphism discovery and genotyping. [ [web](http://arxiv.org/abs/1207.3907) ]
- **[GATK](https://github.com/broadgsa/gatk)** - Variant Discovery in High-Throughput Sequencing Data. [ [web](https://software.broadinstitute.org/gatk) ]
- **[Octopus](https://github.com/luntergroup/octopus)** - A polymorphic bayesian genotyping model with wide applicability. [ [paper-2021](https://www.nature.com/articles/s41587-021-00861-3) ]
- **[bcftools](https://github.com/samtools/bcftools)** - samtools/bcftools are a suite of tools for manipulating NGS data and can be used to call variants. [ [paper-2009](https://pubmed.ncbi.nlm.nih.gov/19505943) | [web](http://htslib.org) ]
#### Structural variant callers

- **[Delly](https://github.com/dellytools/delly)** - Structural variant discovery by integrated paired-end and split-read analysis. [ [paper-2012](https://pubmed.ncbi.nlm.nih.gov/22962449) ]
- **[lumpy](https://github.com/arq5x/lumpy-sv)** - lumpy: a general probabilistic framework for structural variant discovery. [ [paper-2014](https://link.springer.com/article/10.1186/gb-2014-15-6-r84) ]
- **[manta](https://github.com/Illumina/manta)** - Structural variant and indel caller for mapped sequencing data. [ [paper-2015](https://pubmed.ncbi.nlm.nih.gov/26647377) ]
- **[gridss](https://github.com/PapenfussLab/gridss)** - GRIDSS: the Genomic Rearrangement IDentification Software Suite. [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29097403) ]
- **[smoove](https://github.com/brentp/smoove)** - structural variant calling and genotyping with existing tools, but,smoothly.

### BAM File Utilities

- **[Bamtools](https://github.com/pezmaster31/bamtools)** - Collection of tools for working with BAM files. [ [paper-2011](https://academic.oup.com/bioinformatics/article/27/12/1691/255399) ]
- **[bam toolbox](https://github.com/AndersenLab/bam-toolbox)** MtDNA:Nuclear Coverage; BAM Toolbox can output the ratio of MtDNA:nuclear coverage, a proxy for mitochondrial content.
- **[mergesam](https://github.com/DarwinAwardWinner/mergesam)** - Automate common SAM & BAM conversions.
- **[mosdepth](https://github.com/brentp/mosdepth)** - fast BAM/CRAM depth calculation for WGS, exome, or targeted sequencing. [ [paper-2017](https://pubmed.ncbi.nlm.nih.gov/29096012/) ]
- **[SAMstat](https://github.com/TimoLassmann/samstat)** - Displaying sequence statistics for next-generation sequencing. [ [paper-2010](https://academic.oup.com/bioinformatics/article/27/1/130/201972) | [web](http://samstat.sourceforge.net) ]
- **[Somalier](https://github.com/brentp/somalier)** - Fast sample-swap and relatedness checks on BAMs/CRAMs/VCFs/GVCFs. [ [paper-2020](https://pubmed.ncbi.nlm.nih.gov/32664994) ]
- **[Telseq](https://github.com/zd1/telseq)** - Telseq is a tool for estimating telomere length from whole genome sequence data. [ [paper-2014](https://academic.oup.com/nar/article/42/9/e75/1249448) ]

### VCF File Utilities

- **[bcftools](https://github.com/samtools/bcftools)** - Set of tools for manipulating VCF files. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/26826718) | [paper-2017](https://pubmed.ncbi.nlm.nih.gov/28205675) | [web](http://samtools.github.io/bcftools) ]
- **[vcfanno](https://github.com/brentp/vcfanno)** - Annotate a VCF with other VCFs/BEDs/tabixed files. [ [paper-2016](https://pubmed.ncbi.nlm.nih.gov/27250555) ]
- **[vcflib](https://github.com/vcflib/vcflib)** - A C++ library for parsing and manipulating VCF files.
- **[vcftools](https://github.com/vcftools/vcftools)** - VCF manipulation and statistics (e.g. linkage disequilibrium, allele frequency, Fst). [ [paper-2011](https://pubmed.ncbi.nlm.nih.gov/21653522) ]

### GFF BED File Utilities

- **[AGAT](https://github.com/NBISweden/AGAT)** - Suite of tools to handle gene annotations in any GTF/GFF format. [ [web](https://agat.readthedocs.io/en/latest/?badge=latest) ]
- **[gffutils](https://github.com/daler/gffutils)** - GFF and GTF file manipulation and interconversion. [ [web](http://daler.github.io/gffutils) ]
- **[BEDOPS](https://bedops.readthedocs.io/en/latest/index.html)** - The fast, highly scalable and easily-parallelizable genome analysis toolkit. [ [paper-2012](https://academic.oup.com/bioinformatics/article/28/14/1919/218826) ]
- **[Bedtools2](https://github.com/arq5x/bedtools2)** - A Swiss Army knife for genome arithmetic. [ [paper-2010](https://pubmed.ncbi.nlm.nih.gov/20110278) | [paper-2014](https://pubmed.ncbi.nlm.nih.gov/25199790) | [web](https://bedtools.readthedocs.io) ]

### Variant Simulation

- **[Bam Surgeon](https://github.com/adamewing/bamsurgeon)** - Tools for adding mutations to existing `.bam` files, used for testing mutation callers. [ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/bamsurgeon) ]
- **[wgsim](https://github.com/lh3/wgsim)** - **Comes with samtools!** - Reads simulator. [ [web](https://popmodels.cancercontrol.cancer.gov/gsr/packages/wgsim) ]

### Variant Prediction/Annotation

- **[SIFT](https://github.com/teamdfir/sift)** - Predicts whether an amino acid substitution affects protein function. [ [paper-2003](https://pubmed.ncbi.nlm.nih.gov/12824425) | [web](http://sift.jcvi.org) ]
- **[SnpEff](https://github.com/pcingola/SnpEff)** - Genetic variant annotation and effect prediction toolbox. [ [paper-2012](https://www.tandfonline.com/doi/full/10.4161/fly.19695) | [web](https://pcingola.github.io/SnpEff) ]
- **[Ensembl VEP](https://anaconda.org/bioconda/ensembl-vep)** - The VEP determines the effect of your variants (SNPs, insertions, deletions, CNVs or structural variants) on genes, transcripts, and protein sequence, as well as regulatory regions. [ [paper-2016](https://doi.org/10.1186/s13059-016-0974-4) | [web](http://www.ensembl.org/info/docs/tools/vep/index.html) ]
