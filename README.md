# Polygonia calbum genome and annotation #

Release 

Associated Publication
in review

reference needed here. Link below needs updating once established

- [link to article](https://academic.oup.com/gbe/article/13/5/evab054/6179806)

***************************************

### Contents ###

+ A. Folders with bioinformatic scripts
+ B. Publication files


***************************************

### A. Folders with bioinformatic scripts  ###

+ `annotation` — scripts for running BRAKER2 for protein, RNAseq and combined annotation

+ `busco_assembly_assessment` - scripts for running our BUSCO assessment of the genome versions.

+ `genome_assembly` - scripts for running our BUSCO assessment of the genome versions.

+ `genome_to_chromosome` - scripts for integrating the genome assembly with the linkage map.

+ `linkage_map` - apg files for each chromosome and PDFs of Marley maps for each linkage group.

+ `synteny` - R scripts for the alignment and visualization of synteny between M. cinxia and P. c-album chromosome assemblies.


***************************************

### B. Publication files ###

The v1 distribution contains the following files in /publication_files:

+ `Pcalbum_chromosome_and_unplaced.naf` — final genome assembly with chromosomes and unplaced scaffolds. This is compressed Pcalbum_chromosome_and_unplaced.fa in Nucleotide Archival Format (NAF). More on NAF, which is much more efficient than PIGZ compression:
- [link to website](https://github.com/KirillKryukov/naf)
- [link to article](https://academic.oup.com/bioinformatics/article/35/19/3826/5364265)

+ `Pcalbum_chromosome_and_unplaced.gff` - annotation for the final assembly, using BRAKER2 with both Arthropod proteins and RNAseq data for annotation training.


