Data and scripts to calculate abundance-weighted mean amino acid compositions in fruit fly and biofilm development.

The output files (`CBS+17_mean_aa.csv` and `FOK+20_mean_aa.csv`) are used in [JMDplots](https://github.com/jedick/JMDplots) to make figures for the ["evdevH2O" paper](http://chnosz.net/JMDplots/doc/evdevH2O.html "Redox potential linked to water loss from proteins in evolution and development").

* `CBS+17_abundance.csv`: Processed protein abundance data from Supplemental Table S1 of Casas-Vila et al. (2017). Values in the columns for "imputed.log2.LFQ.intensity" were exponentiated, and means of all 4 replicates at each time point were taken to give the values in this file. Protein IDs were mapped to UniProt IDs in the "Entry" column.

* `CBS+17_aa.csv`: Amino acid compositions obtained from the canonical UniProt sequences for all proteins.

* `CBS+17.R`, `CBS+17_mean_aa.csv`: R script and output for abundance-weighted mean amino acid compositions for proteins at each developmental time point.

* `FOK+20_abundance.csv`: Gene and protein abundance data from Supplementary File S10 of Futo et al. (2020). Values in the sheets named "TAI" and "PAI" were used without modification and stored in the columns starting with "T_" and "P_". Protein IDs were mapped to UniProt IDs in the "Entry" column.

* `FOK+20_aa.csv`: Amino acid compositions obtained from the canonical UniProt sequences for all proteins.

* `FOK+20.R`, `FOK+20_mean_aa.csv`: R script and output for abundance-weighted mean amino acid compositions for proteins at each developmental time point.

## References

Casas-Vilas, N. and Bluhm, A. and Sayols, S. et al. (2017) The developmental proteome of *Drosophila melanogaster*. *Genome Res.* **27**, 1273--1285. <https://doi.org/10.1101/gr.213694.116>

Futo, M. and Opašić, L. and Koska, S. et al. (2020) Embryo-like features in developing *Bacillus subtilis* biofilms. *Mol. Biol. Evol.* **38**, 31--47. <https://doi.org/10.1093/molbev/msaa217>
