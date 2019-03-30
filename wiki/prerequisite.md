##  Reads download
* [EBI](https://www.ebi.ac.uk/metagenomics)
* [NCBI](https://www.ncbi.nlm.nih.gov/home/download/)
* [CNGB](https://db.cngb.org/)  

## Environment set up
**Linux** /Windows/Mac OS X\
**Perl/Python** /R for bioinformatics

[Anaconda (python)](https://www.anaconda.com/)\
conda upgrade --all\
conda install package_name\
conda create -n env_name package_names

[Perl](http://www.perl.org/get.html)\
tar zxvf xxx.tar.gz\
mkdir /usr/local/perl\
./configure --help\
./configure -des -Dprefix=/usr/local/perl -Duesthreads -Uversiononly\
make\
make install

## Softwares required
* trimming and filtering fastq reads:  [AfterQC](https://github.com/OpenGene/AfterQC)
* mapping to human genome:  [Bowtie2](https://github.com/BenLangmead/bowtie2) or [Bwa](https://sourceforge.net/projects/bio-bwa/)\
  ***precision: bwa > bowtie2***\
  ***speed :bwa < bowtie2*** 
* profiling: [mOTU2](https://github.com/motu-tool/mOTUs_v2) or [Metaphlan2](https://bitbucket.org/biobakery/metaphlan2/overview)
* phylogenetic analysis: [Phyloshift](https://github.com/gjospin/PhyloSift)



