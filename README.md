# Equine_late_greying
Data and code relating to "An intronic copy number variation in Syntaxin 17 determines speed of greying and melanoma incidence in Grey horses"

## PLINK was run using genotypes from horses displaying Grey and LateGrey phenotypes with the following command:

plink --file Grey --pheno Grey.pheno --pheno-name Greying --model --fisher --allow-no-sex --horse --out assoc_model_fisher.out

## Results from this association test (Dominance model) can be found in the files:
LateGrey_vs_grey_PLINK_dominance_gwas.results.chr1-10.txt.gz
LateGrey_vs_grey_PLINK_dominance_gwas.results.chr11-20.txt.gz
LateGrey_vs_grey_PLINK_dominance_gwas.results.chr21-and-above.txt.gz

## The python script WinNuclDivmPileup500kb.py was used to generate nucleotide diversity estimates  alongthe genome from nanopore data of a G2/G2 horse.
