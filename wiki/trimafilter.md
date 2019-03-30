## AfterQC
#### Automatic filtering, triming, error removing and quality control for fastq data.

## Installation
With bioconda conda install afterqc\
latest: [git clone](https://github.com/OpenGene/AfterQC.git) or [download](https://github.com/OpenGene/AfterQC/archive/master.zip)

## Simplified Usage 
Using PyPy to run AfterQC is strongly suggested since it can make AfterQC 3X faster than native Python (CPython).\
To run with pypy, just replace python with pypy in the commands.

**(1)** Prepare your fastq files in a folder, the filenames in the folder should be *R1* and *R2*,\
Otherwise you should specify --read1_flag and --read2_flag

**(2)** ```cd /path/to/fastq/folder```\
```python path/to/AfterQC/after.py```

**(3)** Gzip output\
if the input FastQ files are gzipped, then the output will be also gzipped.\
if the input FastQ files are not gzipped, you can enbale --gzip or -z option.

## Citation
Shifu Chen, Tanxiao Huang, Yanqing Zhou, Yue Han, Mingyan Xu and Jia Gu.AfterQC: automatic filtering, trimming, error removing and quality control for fastq data.BMC Bioinformatics 2017 18(Suppl 3):80 https://doi.org/10.1186/s12859-017-1469-3

[Referring to github page](https://github.com/OpenGene/AfterQC)

