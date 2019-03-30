## BowTie2
Bowtie, an ultrafast, memory-efficient short read aligner for short DNA sequences (reads) from next-gen sequencers.

## Installation 
[BowTie2](https://sourceforge.net/p/bowtie-bio/files/)

## Usage
**(1)** build index for human genome: ```*bowtie2 -build genome.fasta*```  
[human genome dowloading]
(ftp://ftp.ensembl.org/pub/release-95/fasta/homo_sapiens/dna/)

**(2)** map metagenomic reads to human reference: *bowtie2 -x <bt2-idx> xxx_1.fastq xxx_2.fastq -S xxx.sam*

## Citation
https://sourceforge.net/p/bowtie-bio/wiki/Home/
******************************
## Burrows-Wheeler Aligner - BWA
BWA is a program for aligning sequencing reads against a large reference genome (e.g. human genome). It has two major components, one for read shorter than 150bp and the other for longer reads.

## Installation
[BWA](https://sourceforge.net/projects/bio-bwa/files/)

## Basic Usage
**(1)** build index for human genome: *bwa index genome.fasta -p genome*

**(2)** map metagenomic reads to human reference: *bwa mem -t 4 genome xxx_1.fastq xxx_2.fastq > xxx.mem.sam*

## Citation


