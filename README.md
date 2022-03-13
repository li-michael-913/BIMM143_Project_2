# BIMM143_Project_2

Scientific Question: What differences in the sequences of each segment of the segmented genome and expression of infected cells exist between the H1N1 from the 2009 Swine flu pandemic and non-pandemic H1N1 (specifically the strain A/Puerto Rico/8/1934) that may contribute to differences in severity?

Hypothesis: If there is a difference in gene sequences, then severity related differences will be seen in the NS1 and NS2 sequences with pandemic strains having more closely correlated scores and seasonal strains having closely correlated scores, and if there is a difference in transcription of infected cells, then we should see different levels of expression for immune system related genes with pandemic strains inducing higher levels of expression of those genes.

This project will be looking at the differences between the genes in pandemic strains of H1N1 and H3N2 (pH1N1 and pH3N2) and seasonal strains of H1N1 and H3N2 (sH1N1 and sH3N2). For pH1N1, we will be using sequences from A/California/04/2009 (CA04) and A/USSR/90/1977 (USSR90). For sH1N1, we will be using sequences from A/Alabama/01/2020 (AL90) and A/PR/8/1934 (PR8). For pH3N2, we will be using sequences from A/HK/1-1-MA-12/1968. For sH3N2, we will be using sequences from A/Delaware/05/2020 (DE05).

In addition to looking at the different sequences of segments, this project will also be looking at the differences in host cell responses by looking at RNAseq data of infected cells' transcriptome (comparing between PR8 infected cells and CA01 infected cells; CA01 is also from the 2009 H1N1 pandemic). The cells used in this experiment are A549 immortalized lung epithelial cells.

H1N1 and H3N2 are influenza A viruses (IAV) of the orthomyxoviridae family. It is a segmented dsDNA virus with 8 segments, each coding for a different protein. Although segments generally code for 1 protein each, some can code for different proteins using alternative splicing and alternative start codons. Different strains of IAVs are categorized based on their hemagglutinin and neuraminidase proteins (segments 4 and 6 respectively). Segments 1 to 3 code for RNA polymerase subunits. Segment 5 codes for the nucleoprotein (capsid protein). Segment 7 codes for matrix proteins 1 and 2. Segment 8 codes for nonstructural proteins 1 and 2.

---
## Description of files
All files need to be in the same folder for the R notebook to run properly. The .png files starting with hsa are the output images from the pathway analysis. The legend for the pathway analysis images are in the .JPG file titled "KEGG_pathway_legen.JPG". The .fasta files contain the sequences of the proteins in the following order: PB2, PB1, PA, HA, NP, NA, M1, M2, NS1, NS2. The .xlsx files contain the data from RNAseq. The units of the numerator and denominator used in the log2ratio are RPKM, which are reads per kilobase of transcript per million.
