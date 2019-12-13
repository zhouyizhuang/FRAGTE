# FRAGTE
A completeness-independent method for pre-selection of closely related genomes for species delineation in prokaryotes

# Please Cite
If you use FRAGTE in your publication, please cite: 

# Usage
1. Fragmenting phase for reference/Query 
perl Fragmenting.pl [GenomeInfo file] [output]
[GenomeInfo file] has 8 fields, including:
Assembly_assession\tspecies_taxid\torganism_name\tinfraspecific_name\tassembly_level\tChromosome size\tfile for Chromosome\tfile for Plasmid

Note: file for Chromosome,the file containing sequences in fasta format; file for Plasmid, the file containing sequences in fasta format, if no plasmid, this field is "NA".

2. Determining phase
perl Pairs_byFRAGTE.pl [Ref Fragmenting][Query Fragmenting][output]
[Ref Fragmenting] the output file for reference genome info file from step 1.
[Query Fragmenting] the output file for Query genome info file from step 1.

# Note
All scripts are in Bin directory, and all tested data are in Data directory.

# Support
If you are having issues, please email me via zhouyizhuang3@163.com
