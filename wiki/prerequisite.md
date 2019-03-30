##  Reads download
* [EBI](https://www.ebi.ac.uk/metagenomics) 
* [NCBI](https://www.ncbi.nlm.nih.gov/home/download/) 
* [CNGB](https://db.cngb.org/)  
if dowloaded reads are of .sra, then we use [fastq-dump](https://github.com/ncbi/sra-tools/wiki/HowTo:-fasterq-dump) to transform reads format to .fastq

## Environment set up
**Linux** /Windows/Mac OS X\
**Perl/Python** /R for bioinformatics

[Anaconda (python)](https://www.anaconda.com/)\
```conda upgrade --all\
conda install package_name\
conda create -n env_name package_names```

[Perl](http://www.perl.org/get.html)\
```tar zxvf xxx.tar.gz\
mkdir /usr/local/perl\
./configure --help\
./configure -des -Dprefix=/usr/local/perl -Duesthreads -Uversiononly\
make\
make install```

## Softwares required
* trimming and filtering fastq reads:  [AfterQC](https://github.com/OpenGene/AfterQC)
* mapping to human genome:  [BowTie2](https://github.com/BenLangmead/bowtie2) or [BWA](https://sourceforge.net/projects/bio-bwa/)\
  ***precision: BWA > BowTie2***\
  ***speed :BWA < BowTie2*** 
* profiling: [mOTUs2](https://github.com/motu-tool/mOTUs_v2) or [MetaPhlAn2](https://bitbucket.org/biobakery/metaphlan2/overview)


