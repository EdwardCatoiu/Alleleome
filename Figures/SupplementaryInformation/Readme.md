# SI Figures S1-S9 Legends

The following figures and captions are presented in following manuscript.

## Whole genome sequences from wild-type and laboratory evolved strains define the alleleome and establish its hallmarks.
Edward Alexander Catoiu<sup>1</sup>, Patrick Phaneuf<sup>2</sup>, Jonathan Monk<sup>3</sup>, Bernhard O Palsson<sup>*1,2</sup>
- <sup>1</sup>Department of Bioengineering, University of California, San Diego, La Jolla, CA 92101, USA
- <sup>2</sup>The NNF Center for Biosustainability, The Technical University of Denmark, Lyngby, Denmark
- <sup>3</sup>Avellino Lab, Menlo Park, CA 94025, USA
- *Correspondence to Bernard Palsson, palsson@ucsd.edu



--------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img width="300" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS1-NEW-230126.png">
</p>

#### Fig. S1. Phylogenetic diversity of 2,661 wild-type E. coli strains used to define the ORF alleleome. 
(a) A cladogram of 2,661 sequenced E. coli strains shows that (b) multiple phylogroups from various geographic locations are represented. Phylotyping was done in silico using EzClermont52. Mash distances found with MashTree53 were graphed with Interactive Tree of Life (ITOL)54 to generate the cladogram. (c) The phylogenetic variation in gene content is reflected in (d) the length of amino acid positions each strain shares with the alleleome.  In these positions, (e) the amino acid residues across a given strain’s genome is often identical to the dominant amino acid in the alleleome (μglobal = 0.97). (f) The genome similarity and shared genome length to the alleleome consensus sequence for each of the 2,661 wild-type E. coli strains is shown. The panel A data can be found in Dataset S1. Panels C-F are calculated from Dataset(s) S2, S3 & S4.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img width="500" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS2-WT_allele_qcqa.png">
</p>

#### Fig. S2. Alleles in 4,194 genes from whole genome sequences of 2,661 wild-type E. coli strains define the ORF alleleome. 
(a) The gene portfolio (all the genes in a given strain) varies by strain (Dataset S2). (b) A collection of 729,212 codon alleles (present >5% of strains and with truncations shorter than 20% of the gene length) define the sequence variation in 4,194 genes of the alleleome. (c) An average of 174 codon alleles contribute to the nucleic acid sequence (codon) diversity of one ORF. The genes with the fewest and greatest number of alleles are shown, and their corresponding strain counts from panel A. Genetic code redundancy leads to a loss of sequence variation in the amino acid sequences, resulting in fewer unique amino acid alleles per gene. The data in Panels B-C is found in Dataset S3. 

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img width="400" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS3-all_wt_mutation_types.png">
</p>

#### Fig. S3. The distribution of variants across a conserved and narrow E. coli alleleome.
(a) The conservation of each position in the alleleome is determined by the wild-type occurrence of its dominant amino acid (gray). We find 98% of the alleleome is conserved and 70% of the alleleome is absent any amino acid variation. The amino acid diversity in 2,661 E. coli strains is defined by 503,739 unique amino acid substitutions (cyan) distributed across 393,580 positions. (b) The alleleome is “narrow”– the amino acid diversity in 99% of positions can be described by a dominant amino acid (D) and at most two additional amino acid substitutions (D+1, D+2).  (c) Synonymous mutations account for 85% of the nucleic acid sequence variation in the alleleome; the result of these mutations has no effect on the amino acid sequence. (d)  Multiple types of mutations can occur at the same position in the alleleome. It is important to note that in-frame deletions and insertions in Figure S3c-d are counted as “amino acid substitutions” or “variants” in the wild-type alleleome (Fig. 2, Fig. S3a-b), but these are rarely observed. Insertion variants are found in the rows of Dataset S4 where the consensus codon is a “Gap” (“-“) but there exists additional “NNN” codons in the codon sequence details column. Likewise, deletion variants can be found in rows of Dataset S4 where the consensus codon is an “NNN” codon but there exists a “Gap” variant (“-“) in the consensus sequence details column. Deletions and insertions are not considered for Grantham score analyses (Fig. 3 & 6).

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img width="300" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS4-codon_model_for_mutations.png">
</p>

#### Fig. S4. The Grantham score values of observed mutations in the alleleome are lower than predicted by a mathematical “null” model.
(a) The codon table is used to illustrate available paths for a UUU→GGG codon change. The Hamming distance (denoted by the subscripts) reflects the number of sequential point mutations required to reach each intermediate in the mutation pathway. (b) A mathematical ‘null’ model of mutation (random, non-selective) is created to determine the expected distribution of specific UUU→ NNN codon-changes. The probability of achieving a specific codon-change is dependent on the Hamming distance between the initial and final codon, and the fraction of suitable intermediates in the mutation pathway. Given that a mutation is observed, the probability of finding any of the 63 specific UUU→ NNN codon changes is equal to 1. (c) The available codon variants colored by their Hamming distance to the initial codon UUU. We note that UUC (gray) is a synonymous mutation of UUU and is not included in the subsequent model predictions.  (d) For each of the 61 non-terminating codons (in this case UUU), synonymous and terminating codons are removed from the codon table and the codon-specific model finds the expected distribution of all non-synonymous mutations and the resulting Grantham score. For the alleleome, a mutation is counted as any variant that is not the WT dominant codon. (e) The expected mutation rates and Grantham scores are compared to the observed mutations in the alleleome for all non-terminating codons. Observed Grantham scores are lower than expected (green) for most initial codons.  The codon-level information is grouped by the corresponding amino acid residue to generate Figure 3c and Figure 6e-g.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img width="400" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS5_LAB_mutant_QCQA.png">
</p>

#### Fig. S5. QCQA workflow yields 55,987 unique laboratory evolution mutations.
(a) QC/QA filters are applied to private and public mutation data from ALEdb25, as well as the LTEE data26. From left to right: (i) raw data, (ii) experiments in E. coli strains with sequenced reference genomes available, (iii) mutations found in genes (Open Reading Frames, ORFs), (iv) mutations where Blattner numbers (Bnums) can be identified, (v) genome position and amino acid position and residue from reference genome sequence matches the mutation annotation provided, (vi) if the mutation is a deletion, the resulting truncation can be no larger than 20% of the full gene length, (vii) the gene and amino acid position is found in the WT alleleome and (viii) is present in at least 5% (133 of 2,661) of strains, (ix) the mutation is only used once (unique mutations).  This study gathered 45,413 QC/QA’d unique mutations from the public and private ALE mutation data (7,392 and 38,021, respectively), and 10,574 QCQA’d mutations from long term evolution experiments hosted at https://barricklab.org/shiny/LTEE-Ecoli/ (see Dataset S5). (b) The majority of ALE mutations come from experiments involving E. coli MG1655. (c) The mutation dataset includes mutations that result in synonymous and non-synonymous amino acid substitutions, as well as early protein truncations. (d) The most commonly mutated genes in ALEdb and LTEE data. 

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img width="500" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS6-LTEE_mutations_and_WT_occurrence.png">
</p>

#### Fig. S6. The long-term evolution experiment mutations26 explore a novel sequence-space outside that of the E. coli alleleome. 
(a) The wild-type (WT) frequency of amino acids involved in 7,788* unique non-synonymous mutations are (b) rank-ordered by the wild-type frequency of the amino acid in the starting strain (pre-mutation). *In-frame deletions are also counted, but are rarely observed in the LTEE (see Dataset S5B). The amino acid in the starting strain can reflect the WT dominant (black) or a WT variant (cyan) amino acid. The WT frequency of the amino acid substitution is plotted (circles) according to the color scheme in Fig. 4a. An inverse log scale (x-axis) is used to highlight the LTEE mutations that are found in wild-type strains. (c) The WT frequency of the pre-mutation amino acid can classify mutations as “leaving the WT consensus” or “leaving a WT variant”.  The WT frequency of the post-mutation amino acid is used to classify a mutation as “novel”, “rare”, “a WT variant”, or “the WT consensus”. The number and fraction of LTEE mutants represented by each group is shown. (d) The unexplored natural sequence space is represented by WT variants that exist in the same positions as LTEE mutations but that are NOT selected for in the LTEE (gray triangles). (e-h) The analysis in Panels A-D is replicated using the WT frequency of the codons involved in LTEE synonymous mutations. The LTEE mutations and associated WT frequencies are provided in Dataset S5B.

--------------------------------------------------------------------------------------------------------------------------------------------------------------


<p align="center">
  <img width="300" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS7-ks_2samp.png">
</p>

#### Fig. S7. Kolmogorov-Smirnov two-sample test shows that distribution of Grantham scores for a majority of mutations is distinct between wild-type and laboratory strains. 
(a) The codon-changes (C1C2) in WT and ALE datasets are grouped by their corresponding original (C1) codon (summarized in Dataset S6). Only non-stop C1 codons and non-terminating codon-changes resulting in non-synonymous amino acid substitutions are analyzed. The distribution of Grantham scores for all WT and ALE mutations is shown in the main text (Fig. 6c).  For each C1-codon, the distribution of Grantham scores observed in WT strains is compared to the observed distribution in ALE mutations using a Kolmogorov-Smirnov two-sample test. The resulting p-values are rank-ordered and plotted for each C1-codon. The distribution of Grantham scores for mutations that originate from the same codon are distinct (p<0.01, reject null-hypothesis Ho) between WT and ALE mutations for all but five codons. (b) The analysis in Panel A is repeated to compare the WT and LTEE codon-changes (also in Dataset S6).  (c) The WT and ALE mutation datasets are grouped by their corresponding original (AA1) amino acid and the analysis in Panel A is repeated for all amino acid substitutions (AA1AA2) originating from the same amino acid (AA1).  Unlike Panel A, the x-axis is ordered by observed average Grantham score for all the mutations originating from the same codon (as in Fig. 6e in the main text). (d) The analysis in Panel C is repeated to compare the WT and LTEE amino acid substitutions (in Fig. 6d). For all amino acids, the observed distributions of the Grantham scores for amino acid substitutions are distinct between WT and laboratory strains (reject null-hypothesis Ho). Mutation metadata for ALE and LTEE strains is presented in Dataset S5. Mutations are grouped by codon-level information in Dataset S6. The values for this statistical analysis are presented in Dataset S7.

--------------------------------------------------------------------------------------------------------------------------------------------------------------
<p align="center">
  <img width="500" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS8-chisquared_codon.png">
</p>

#### Fig. S8. Chi-squared test shows that the observed rates of specific non-synonymous codon-changes in WT and laboratory strains are distinct. 
(a) The codon-changes (C1C2) in WT and ALE are grouped by their corresponding original (C1) codon (grouped in Dataset S6). Only non-stop C1 codons and non-terminating codon-changes resulting in non-synonymous amino acid substitutions are analyzed. (left) The histogram counts the number of C1-codons for which a specific number of C1C2 variants are observed in ALE strains (e.g. non-synonymous mutations originating from an AGG codon result in only one of five C2 variants across all ALE strains).  The total number of C1 codons, total unique C1C2 codon-changes, and total unique mutations across all ALE strains are shown in the legend. (right) The rate of expected occurrence for all C1C2 variants across all ALE strains is calculated using the rate at which the same variant is observed in WT strains. C1C2 variants that are both expected and observed more than 5 times in the ALE strains fit the chi-squared test criteria. C1 codons with at least two C2 variants that meet the test criteria (b) can be analyzed using a chi-squared test. The observed distribution of C2 variants in ALE does not resemble the WT distribution (reject null-hypothesis Ho) for all but one C1 codon. (c-d) Similar results are shown for codon-changes in the LTEE mutations. WT mutations are calculated from Dataset S4. Mutation metadata for ALE and LTEE strains is presented in Dataset S5. Mutations are grouped by codon-level information in Dataset S6. The values for this statistical analysis are presented in Dataset S7.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img width="500" src="https://github.com/EdwardCatoiu/Alleleome/blob/main/Figures/SupplementaryInformation/FigS9-chisquared_aa.png">
</p>

#### Fig. S9. Chi-squared test shows that the observed rates of specific non-synonymous amino acid substitutions in WT and laboratory strains are distinct. 
The analysis in Fig. S9 is repeated at the amino-acid level. (a) Non-synonymous amino acid substitutions (AA1AA2) in WT and ALE strains (Dataset S6) are grouped by their corresponding original (AA1) amino acid. (left) The histogram counts the number of AA1-amino acids for which a specific number of AA1AA2 variants are observed in ALE strains (e.g. non-synonymous mutations originating from a tryptophan (W) amino acid result in only one of five AA2 variants across all ALE strains).  The total number of AA1 amino acids, total unique AA1AA2 amino acid substitutions, and total unique mutations across all ALE strains are shown in the legend. (right) The rate of expected occurrence for all AA1AA2 variants across all ALE strains is calculated by the rate at which the same variant is observed in WT strains. AA1AA2 variants that are both expected and observed more than 5 times in the ALE strains fit the chi-squared test criteria. AA1 amino acids with at least two AA2 variants that meet the test criteria (b) can be analyzed using a chi-squared test. The observed distribution of AA2 variants in ALE does not resemble the WT distribution (reject null-hypothesis Ho) for all amino acids. (c-d) Similar results are shown for amino acid substitutions in the LTEE dataset. WT mutations are calculated from Dataset S4. Mutation metadata for ALE and LTEE strains is presented in Dataset S5. Mutations are grouped by codon-level information in Dataset S6. The values for this statistical analysis are presented in Dataset S7.
 
