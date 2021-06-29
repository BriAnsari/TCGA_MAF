# TCGA_MAF
Using TCGA MAF files

TCGA is one of the few databases that allows scientists to access genomic data along with other patient level data. However one bottle neck encountered by many is the accessibility to VCF files. One of the most common solutions proposed is to convert MAF files (open access) to VCF files using a perl script or a python script, which can lead to some formatting errors. 

My mentor Dr. Sijung yun recommended a more reproducible, although a bit convoluted way to achieve this. This includes converting the MAF file to an annovar input (avinput) as an intermediate step and then using annovar to get a VCF file. 


