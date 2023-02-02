Microbiome random forest analysis was done for four separate sets of data…

First 5 PCs of full microbiome for every type (bacteria/fungi), compartment (root/rhizosphere), and treatment (CK,D,LN,LP) [microbiomesPCs]
Combined massila specific ASVs [massilia]
Combined oxalobacteraceae specific ASVs [oxalobacteraceae]
Massila and oxalobacteraceae ASVs (bASV10, bASV111, bASV1751, ASV18, bASV37, bASV49, bASV51, bASV56, bASV7, bASV79, bASV824) [ASVsSUBSET]

For each, the output folder has…

Boruta_objects - Files named “Boruta_X.rds” Boruta (feature selection) identified environmental related “traits” and the associated aspects of environment 

FOAM_predicitons - Files named “FOAMpredictions_X.csv” CIMMYT FOAM predictions for env related “traits”

The code folder has two scripts…

“MaizeMicrobiome_PCsFullMicrobiome.Rmd” is the analysis on PCs of the full microbiome
“MaizeMicrobiome_SelectASVsGenera.Rmd” includes the analysis for massilia, oxalobacteraceae, and their associated ASVs
