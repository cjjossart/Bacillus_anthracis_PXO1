# Bacillus Anthracis Virulence Plasmid PXO1 and Phylogeny of Yamal Anthrax Outbreak 
This project is part of a class project for Genomic Epidemiology of Infectious Diseases at the Yale School of Public Health taught under the Dr. grubaugh and Grubaugh Lab members. This project seeks to explore the origin of the virulent plasmid PXO1 in Bacillus anthracis, which carres the genomic information responsible for the anthrax toxin. This project uses similar data as presented in a current article addressing the same questions and themes as this project (1).

Samples
Samples were collected from National Center for Biotechnology Information. Samples were chosed based off recent research using WGS to assess patterns and origin of an anthrax outbreak on the Yamal peninsula of Russia (1). Raw reads and assembled genomes are accessible through NCBI with use of the corresopnding accession number.

Methods
Raw reads and assembled whole genome sequences were accessed via NCBI databases. Data was processed using usegalaxy.org [https://usegalaxy.org/]. 
Raw reads were assembled using Unicycler. Once assembled all samples were mapped to reference sequence of Bacillus anthracis and its subsequent plasmids (Plasmid PXO1 reference: GenBank: AF065404.1) with the use of minimap2 tool. Samples went from FASTA file to BAM.
BAM files of samples were aligned with the help of NGS tools in UGENE software package and a sequence file was created for Nextstrain page creation.

Nextstrain
Some of our analyses were performed using the nextstrain (augur) pipeline. These results can be visualized using auspice, accessing the link:

https://nextstrain.org/community/cjjossart/Bacillus_anthracis_PXO1

References:
1. Article Source: Insights from Bacillus anthracis strains isolated from permafrost in the tundra zone of Russia 
Timofeev V, Bahtejeva I, Mironova R, Titareva G, Lev I, et al. (2019) Insights from Bacillus anthracis strains isolated from permafrost in the tundra zone of Russia. PLOS ONE 14(5): e0209140. https://doi.org/10.1371/journal.pone.0209140 


Disclaimer. Please note that this data is still based on work in progress and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. 
