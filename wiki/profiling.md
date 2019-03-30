## mOTUs2
#### The mOTUs2 profiler is a computational tool that estimates relative abundance of known and currently unknown micorbial community members using metagenomic shotgun sequencing data.

## Installation
[git clone](https://github.com/motu-tool/mOTUs_v2.git)\
cd mOTUs_v2\
python setup.py\
python test.py\
export PATH=`pwd`:$PATH\

## Simplified Usage  
**(1)** motus profile -f for_sample.fastq -r rev_sample.fastq -s no_pair.fastq -t 6 > taxonomy_profile.txt

**(2)** motus merge -i taxonomy_profile_1.txt, taxonomy_profile_2.txt > all_sample_profiles.txt

## Citation 
Alessio Milanese, Daniel R Mende, Lucas Paoli, Guillem Salazar, Hans-Joachim Ruscheweyh, Miguelangel Cuenca,
Pascal Hingamp, Renato Alves, Paul I Costea, Luis Pedro Coelho, Thomas S B Schmidt, Alexandre Almeida, 
Alex L Mitchell, Robert D Finn, Jaime Huerta-Cepas, Peer Bork, Georg Zeller & Shinichi Sunagawa. Microbial abundance, 
activity and population genomic profiling with mOTUs2; Nature Communications 10, Article number: 1014 (2019).
doi: 10.1038/s41467-019-08844-4

[Referring to github page](https://github.com/motu-tool/mOTUs_v2)
*******************************************************************************
## MetaPhlAn2
#### MetaPhlAn is a computational tool for profiling the composition of microbial communities (Bacteria, Archaea, Eukaryotes and Viruses) from metagenomic shotgun sequencing data (i.e. not 16S) with species-level. With the newly added StrainPhlAn module, it is now possible to perform accurate strain-level microbial profiling.

## Installation
[download from Bitbucket](https://bitbucket.org/biobakery/metaphlan2/get/default.zip)

## Simplified Usage  
**(1)** metaphlan2.py metagenome_1.fastq,metagenome_2.fastq --bowtie2out metagenome.bowtie2.bz2 --nproc 5 --input_type fastq > profiled_metagenome.txt

**(2)** python utils/merge_metaphlan_tables.py metaphlan_output*.txt > output/merged_abundance_table.txt 

## Citation 
MetaPhlAn2 for enhanced metagenomic taxonomic profiling. Duy Tin Truong, Eric A Franzosa, Timothy L Tickle, Matthias Scholz, George Weingart, Edoardo Pasolli, Adrian Tett, Curtis Huttenhower & Nicola Segata. Nature Methods 12, 902-903 (2015)

[Referring to bitbucket page](https://bitbucket.org/biobakery/metaphlan2/overview)




