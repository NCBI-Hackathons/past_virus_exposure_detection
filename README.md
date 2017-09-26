# VSENSE: Viral Detection Exposure in Host Genomes

### VSENSE is a solution to determine if viral sequences are non-native to a host genome. The system relies upon the Building Up Domains (BUD) algorithm. BUD takes as input an identified viral contig from a metagenomics dataset and it runs the two ends of the identified contig through MagicBLAST to find overlapping reads. These reads are then used to extend the contig in both directions. This process can continue until non-viral domains are identified on either side of the original viral contig, implying that the original contig was endogenous in the host. This process is depicted below:

![alt text](https://github.com/NCBI-Hackathons/past_virus_exposure_detection/blob/master/BUD.png "Logo Title Text 1")
