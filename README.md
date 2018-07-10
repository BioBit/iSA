# iSA (in silico Strand Annealing)

Whole genome bisulfite sequencing (WGBS) has been widely used to quantify cytosine DNA methylation frequency in an expanding array of cell and tissue types. Because of the denaturing conditions used, this method ultimately leads to the measurement of methylation frequencies at single cytosines. Hence, the methylation frequency of CpG dyads can only be indirectly inferred by overlaying the methylation frequency of two cytosines measured independently. Furthermore, hemi-methylated CpGs (hemiCpGs), a significant component of the DNA methylome, has not been analyzed in previous WGBS studies. We recently developed in silico Strand Annealing (iSA), a bioinformatics method applicable to WGBS data, to resolve the methylation status of CpG dyads into unmethylated, hemi-methylated, and methylated. The versatility of iSA enables its application downstream of other WGBS-related methods such as nasBS-seq, ChIP-BS-seq, TAB-seq, oxBS-seq, and fCAB-seq. As an example of its tunability, iSA also enables calling the single-molecule non-CpG methylome. Here we provide this interactive shell script to be run from the Unix shell prompt in a terminal window.


Please cite:
1. Xu, C. & Corces, V. G. Nascent DNA methylome mapping reveals inheritance of hemimethylation at CTCF/cohesin sites. Science 359, 1166-1170, doi:10.1126/science.aan5480 (2018)
