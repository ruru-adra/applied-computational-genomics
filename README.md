### Applied Computational Genomics Course at UU: Spring 2017
- Faculty: Aaron Quinlan (aquinlan at genetics.utah.edu)
- Teaching assistants: Tom Sasani (tom.sasani@utah.edu), Julie Feusier (jfeusier@genetics.utah.edu) and Jingtao Guo (jingtao.guo@hci.utah.edu)
- Meets Tu and Th from 9:10-10:30 in HSEB 2948; January 10 - April 25
- TA Hours: M and W from 4-5 PM, meet in 2nd floor HSEB lobby, Th from 10:30 to 11:30 AM (right after class)

### Overview
This course will provide a comprehensive introduction to fundamental concepts and experimental approaches in the analysis and interpretation of experimental genomics data. It will be structured as a series of lectures covering key concepts and analytical strategies. A diverse range of biological questions enabled by modern DNA sequencing technologies will be explored including sequence alignment, the identification of genetic variation, structural variation, and ChIP-seq and RNA-seq analysis. Students will learn and apply the fundamental data formats and analysis strategies that underlie computational genomics research. **The primary goal of the course is for students to be grounded in theory and leave the course empowered to conduct independent genomic analyses.**

### Prerequisites
- Online introduction to Linux. Students must complete one of the following online tutorials (or both) before class begins. 
  - [Code academy's Intro to Unix](https://www.codecademy.com/en/courses/learn-the-command-line/lessons/environment/exercises/bash-profile)
  - [Command line bootcamp](http://rik.smith-unna.com/command_line_bootcamp/?id=9xnbkx6eaof)
- Undergraduate or graduate level Molecular Biolog (for future versions of the class)
- An Apple or Linux computer. Or a Windows machine with [Putty](http://www.putty.org/) installed.

### Course lecture slides
- [All slide decks (in Google Drive)](https://drive.google.com/drive/folders/0B5Jmsvw39gJkT0dZOExrR3EwVjg?usp=sharing)
- [Class 1: Course overview and Intro to UNIX](https://docs.google.com/presentation/d/1B8kvetTDwUe-d7hZuV2NufVOMPM7MCxh_MyP-n9yDZo/edit?usp=sharing)
- [Class 2: Intro to UNIX, Part 2](https://docs.google.com/presentation/d/1YSXYqCSHUZGRVr00oTttv_v1u83ccPLpF5_TMtW0iRI/edit?usp=sharing)
- [Class 3: The human genome](https://docs.google.com/presentation/d/1304Ueup_n8_vqKjQZh-AV3dDAOs2gCqNgrm8o25nBHo/edit?usp=sharing)
- [Class 4: Pattern searching in the human genome](https://docs.google.com/presentation/d/1W7bwMLAqCIB9unbv4Kswc8P7cE5ATkMhHYJfwBa64L0/edit?usp=sharing)
- [Class 5: Genetic Variation](https://docs.google.com/presentation/d/1JnBiaGG_eJAb1LGUiNaXP4DX-oZKaxaDVg1KFqYeAfA/edit?usp=sharing)
- [Class 6: DNA sequencing technologies and FASTQ format](https://docs.google.com/presentation/d/1N0DO5rlHdbrnNhyDhib8fpYYhfbtFOPcKw_Bpvv-2lA/edit?usp=sharing)

### Homework
- [Homework 1: Basic Unix analysis](https://gist.github.com/arq5x/c0eb84bce2086fbfbe9184668ef87b31#file-hw1-md)
- [Homework 2: DNA Pattern exploration in a FASTA file] (https://gist.github.com/arq5x/c0eb84bce2086fbfbe9184668ef87b31#file-hw2-md)

### Syllabus
- **Class 1 (Tu Jan 10; Quinlan): Course overview and Intro to UNIX**
    - [Class 1 Slides](https://docs.google.com/presentation/d/1B8kvetTDwUe-d7hZuV2NufVOMPM7MCxh_MyP-n9yDZo/edit?usp=sharing)
    - **Required** Reading Prior to Lecture: 
        - Part 1 of [Unix and Perl Primer for Biologists](http://korflab.ucdavis.edu/Unix_and_Perl/current.pdf)
    - Topics covered
        - Brief history of computational biology
        - Course computing environment
        - Intro. to UNIX: Part 1
            - Logging in
            - The "shell"
            - "Home"
            - Navigation
            - File system
            - Files
            - Basic commands: `ls`, `pwd`, `cd`, `mkdir`, `head`
- **Class 2 (Th Jan 12; Quinlan): Intro to UNIX Part 2**
    - [Class 2 Slides](https://docs.google.com/presentation/d/1YSXYqCSHUZGRVr00oTttv_v1u83ccPLpF5_TMtW0iRI/edit?usp=sharing)
    - **Required** Reading Prior to Lecture: 
        - Part 2 (Advanced UNIX) of [Unix and Perl Primer for Biologists](http://korflab.ucdavis.edu/Unix_and_Perl/current.pdf)
    - Topics covered
        - Intro. to UNIX: Part 2
          - grep
          - cut
          - redirects
    - **Homework 1 assigned. (due by start of class, Jan 17)**
 
- **Class 3 (Tu Jan 17; Quinlan): The human genome**
    - [Class 3 Slides](https://docs.google.com/presentation/d/1304Ueup_n8_vqKjQZh-AV3dDAOs2gCqNgrm8o25nBHo/edit?usp=sharing)
    - **Required** Reading Prior to Lecture: 
        - [Initial sequencing and analysis of the human genome](http://www.nature.com/nature/journal/v409/n6822/full/409860a0.html)
    - Topics covered
      - Karyotype
      - Chromosome structure
      - Centromeres
      - Banding
      - Chromatin
      - How was the genome sequenced?
        - sequencing technology
        - assembly strategy
      - Chromosomes
        - size
        - gene content
        - centromeres
      - Haplotypes
      - Genes and transcripts
      - Repeat content
        - mobile elements
        - simple repeats
      - GC content, banding
      - CpG islands  
- **Class 4 (Th Jan 19; Quinlan): Using UNIX to find patterns in a genome**
    - **Required** Reading Prior to Lecture:    
        - None.     
    - Topics covered
      - The UNIX PATH
      - Environment variables
      - Basic regular expressions with grep
      - sort
      - uniq
    - **Homework 2 (finding biological patterns in FASTA files with UNIX) assigned**
- **Class 5 (Tu Jan 24; Quinlan): Genetic variation: mutations, polymorphisms, and haplotypes**
    - **Required** Reading Prior to Lecture: 
        - [A global reference for human genetic variation](http://www.nature.com/nature/journal/v526/n7571/full/nature15393.html)
    - Topics covered
      - Genetic variation: what, why, etc.
      - Mutation vs. polymorhism
      - De novo mutation
         - Human mutation rates
      - Polymorphism
      - SNPs INDELs
        - abundance
        - frequency
        - examples
        - 1000 Genomes
        - Site frequency spectrum
      - Population stratification
      - Intro to haplotypes and recombination

- **Class 6 (Th Jan 26; Quinlan): Modern DNA sequencing technologies**
    - **Required** Reading Prior to Lecture: 
        - [Coming of age: ten years of next-generation sequencing technologies](http://www.nature.com/nrg/journal/v17/n6/full/nrg.2016.49.html)
    - Topics covered
        - Illumina sequencing
            - Overview of technology
            - Paired-end vs. single-end
        - Pacbio
        - Oxford nanopore
        - Base calling
        - FASTQ format
        - seqtk, fastx toolkit
    - **Homework 3 (working with the FASTQ format) assigned**

- **Class 7 (Tu Jan 31; Quinlan): DNA sequence alignment**
    - **Required** Reading Prior to Lecture: 
        - [Alignment of Next-Generation Sequencing Reads](http://www.annualreviews.org/doi/abs/10.1146/annurev-genom-090413-025358?journalCode=genom)
    - Topics covered
      - Sequence alignment
          - Theory
          - Mapping versus alignment
          - Local versus global alignment
              - Smith waterman
              - Needleman-wunsch
          - Advanced algorithms
          - Alignment for RNA-seq
          - Alignment for SV detection.
          - Tools
              - BWA, etc.

- **Class 8 (Th Feb 2; Quinlan): DNA sequence alignment**
    - The SAM/BAM format
    - Samtools
    - IGV
    - **Homework 4 (creating and working with SAM/BAM files with samtools and IGV) assigned**

- **Class 9 (Tu Feb 7; Quinlan and/or Marth): Detecting genetic variation, part 1**
    - **Required** Reading Prior to Lecture: 
        - [A framework for variation discovery and genotyping using next-generation DNA sequencing data](http://www.nature.com/ng/journal/v43/n5/full/ng.806.html)
    - **Optional** Reading Prior to Lecture: 
        - [A general approach to single-nucleotide polymorphism discovery.](http://www.nature.com/ng/journal/v23/n4/full/ng1299_452.html)
    - Topics covered
      - SNP and INDEL calling
          - Theory
              - Basic concept
              - Sequencing error
              - Bayes theorem and priors
      - Assigning a genotype
      - Common problems and artifacts
          - paralogy
          - low depth
          - high error rate
          - ambiguous alignment
      - Single sample variant detection
- **Class 10 (Th Feb 9; Quinlan): Detecting genetic variation, part 2**
    - **Required** Reading Prior to Lecture: 
        - [The VCF format and VCFtools](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3137218/)
    - Topics covered
        - VCF format
          - Attributes
          - Genotypes
        - Population calling
        - Basic annotations
    - Landscape of human genetic variation
        - Alleles and genotypes
        - Allele frequency spectrum
        - Hardy weinberg equilibrium
        - More on haplotypes and recombination
    - Exploring the format
        - examples
        - IGV
    - Manipulating VCF with bcftools
    - **Homework 5 (variant calling and working with VCF files with bcftools and UNIX) assigned**
- **Class 11 (Tu Feb 14; Quinlan): Annotating of genetic variation**
    - **Required** Reading Prior to Lecture: 
        - [Choice of transcripts and software has a large effect on variant annotation](https://genomemedicine.biomedcentral.com/articles/10.1186/gm543)
    - Topics covered
        - Concepts
          - e.g, synonymous, non-synonymous
          - frameshift
          - stopgain
          - constraint
          - impact of transcript model
    - Tools
        - Polyphen
        - SIFT
        - vcfanno
        - CADD
        - VEP
        - SnpEff
    - **Homework 6 (annotating and profiling VCF files) assigned**
- **Class 12 (Th Feb 16; Quinlan): Exome sequencing in studies of human disease**
    - **Required** Reading Prior to Lecture: 
        - [Exome sequencing as a tool for Mendelian disease gene discovery](http://www.nature.com/nrg/journal/v12/n11/full/nrg3031.html)
    - Topics covered
        - Exome capture
        - Variant detection in families
          - Mendelian inheritance
          - Mendelian violations (de novo mutations, LoH, uniparental disomy)
        - The Exome Aggregation Consortium
        - Mendelian disease analysis
            - Variant annotation
            - Using population allele frequency
    - **Homework 6 (variant prioritization with snpeff, gqt, and bcftools) assigned (due Feb 16)**
- **Class 12 (Th Feb 16; Quinlan): Somatic mutation in cancer and "healthy" tissue**
    - **Required** Reading Prior to Lecture: 
        - [Sensitive detection of somatic point mutations in impure and heterogeneous cancer samples](http://www.nature.com/nbt/journal/v31/n3/full/nbt.2514.html)
    - Topics covered
        - Sources of mutation
        - Mutational landscape
        - Tumor heterogeneity
        - Somatic mutation detetion
            - why is it so hard?
        - Using mutation to track cancer evolution
        - Mosaicism and disease
- **Class 13 (Tu Feb 21; Quinlan): Variation in genome structure**
    - **Required** Reading Prior to Lecture: 
        - [Genome structural variation discovery and genotyping](http://www.nature.com/nrg/journal/v12/n5/full/nrg2958.html)
    - Topics covered
        - The genome is repetitive
        - Segmental duplication
        - SV versus CNV
        - SV Mechanisms
            - NAHR / ectopic recombination
            - NHEJ
            - Replication mechansism
        - SV detection
        - Examples
    - **Homework 7 (visualizing SV and CNV) assigned (due Feb 23)**
- **Class 14 (Th Feb 23; Quinlan): Genome annotation**
    - **Required** Reading Prior to Lecture: 
        - None
    - Topics covered
      - How and why do we annotate a genome?
      - Conservation
      - CpG islands
      - Repeatmasker
      - Chromatin modifications
      - DNA methylations
      - Linkage blocks
  - **Homework 8 (exploring genome annotation files with UNIX) assigned (due Feb 28)**
- **Class 15 (Tu Feb 28; Quinlan): Genome data formats and genome arithmetic**
    - **Required** Reading Prior to Lecture: 
        - None
    - Topics covered
      - The genome as a coordinate system
      - BED format
      - GFF format
      - VCF format
      - Recap BAM format
      - UCSC and Biomart to retrieve genome annotations
      - UCSC and IGV to visualize 
- **Class 16 (Th Mar 2; Quinlan): Applied genome arithmetic with bedtools; part 1**
    - **Required** Reading Prior to Lecture: 
        - [BEDTools: the Swiss‐army tool for genome feature analysis](http://onlinelibrary.wiley.com/doi/10.1002/0471250953.bi1112s47/abstract?userIsAuthenticated=false&deniedAccessCustomisedMessage=)
    - Topics covered
      - The genome as a coordinate system revisited
      - Basic concepts of genome arithmetic
      - Introduction to bedtools
    - **Homework 9 (basic genome arithmetic with bedtools) assigned (due Mar 7)**
- **Class 17 (Tu Mar 7; Quinlan): Applied genome arithmetic with bedtools; part 2**
- **Class 18 (Th Mar 9; Quinlan): Digging deeper into UNIX, part 1**
    - awk
    - sed
    - tr
    - PATH
    - .bashrc
- **Class 19 (Tu Mar 21; Quinlan): ChIP-seq analysis**
    - experimental design
    - protocols
    - examples
- **Class 20 (Th Mar 23; Quinlan): RNA-seq analysis**
    - analyses
    - toolsets
    - Class project assignment
- **Class 21 (Tu Mar 28; Quinlan): Basic probability**
    - Probability with coins and dice
    - Probability with DNA
    - Conditional probabilities
    - Use R for examples
- **Class 22 (Th Mar 30; Quinlan): Statistical tests**
    - Gaussian
      - Z scores
    - Chi-squared
    - Fisher
    - KS test
    - Rank tests
    - Applications
- **Class 23 (Tu Apr 4; Quinlan): How do I know if my observation is significant?**
    - Models
    - Expectation
    - Tests for significance
- **Class 24 (Th Apr 6; Quinlan): Data visualization, part 1**
    - Why
    - Pattern recognition
    - Detect problems
    - Ansombe’s quartet
    - **Introduce class projects**
- **Class 25 (Tu Apr 11; Quinlan): Data visualization, part 2**
    - http://www.nature.com/collections/qghhqm/pointsofsignificance
    - Scatter plots
    - Histograms
    - Box whiskers
- **Class 26 (Th Apr 13; Quinlan): Digging deeper into UNIX, part 2**
    - loops
    - shuffling
    - randomization
    - advanced commands
    - basic scripts and pipelines
- **Class 27 (Tu Apr 18; Quinlan): Advanced topics**
- **Class 28 (Th Apr 20; Quinlan): Group Presentations, part 1**
- **Class 29 (Tu Apr 25; Quinlan): Group Presentations, part 2**
