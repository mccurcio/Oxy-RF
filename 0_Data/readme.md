Folder /0-Data contains the original and reformated data used in the random-forest calculations. 

| Folder           | Use |
|:-----------------|:----|
| /aa-strings-data | contains full sequences of Oxygen-binding proteins |
| /FASTA-data      | contains unzipped .fasta files |
| /Uniprot-gzip-data | contains zipped .fasta files from UniProt |

NOTE: /FASTA-data can be deleted after it is used.

Original data was ultimately derived from UniProtKB:

https://www.uniprot.org/uniprot/?query=reviewed%3Ayes

http://www.uniprot.org/uniprot/?query=reviewed:no+AND+organism:9606+AND+&format=fasta&random=yes&limit=200
