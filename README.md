# 🌳 Supporting information  :dna:

Supporting information ARG Review that includes:

* Method list: Current list of methods/software that used ARGs to infer various evolutionary biology processes (last update October the 6th, 2026).
* Application list: Datatases of past publications that used ARGs updated to March, 2026.

> XX

## Method list

This list is not exhaustive, feel free to contact us (pierre.barry1@outlook.fr) if you spot on a method that is missing from the list or if you want to have yours method listed here !

| Method name | Analyses | Reference | Link |
| :-------------: | :-------------: | :-----------: | :---------: |
| **Quantitative genetic and association studies** |
| eGRM  | Genealogical relatedness and population structure | [Fan et al., 2022](https://www.sciencedirect.com/science/article/pii/S0002929722001124?via%3Dihub) | [https://github.com/Ephraim-usc/egrm](https://github.com/Ephraim-usc/egrm)
| **Quantitative genetic and association studies** |
| ARG-RHE  | Heritability estimation and phenotype association studies | [Zhu et al., 2026](https://www.sciencedirect.com/science/article/pii/S2666979X25003283) | [https://github.com/PalamaraLab/arg-lmm](https://github.com/PalamaraLab/arg-lmm)
| Spectre  | Phantom epistatis inference | [Ignatieva et al., 2026](https://academic.oup.com/genetics/article/232/1/iyaf184/8248594) | [https://github.com/a-ignatieva/spectre](https://github.com/a-ignatieva/spectre)
| Tree-based QTL mapping / local eGRM  | Quantitative-trait locus mapping and phenotype association | [Link et al., 2023 ](https://www.sciencedirect.com/science/article/pii/S0002929723003956?via%3Dihub)| [https://github.com/vivilink/sycamore/](https://github.com/vivilink/sycamore/)
| Edge–Coop polygenic score reconstruction  | Reconstruction of historical polygenic-score trajectories | [Edge & Coop, 2019](https://academic.oup.com/genetics/article/211/1/235/5931145) | [https://github.com/mdedge/rhps_coalescent](https://github.com/mdedge/rhps_coalescent)
| **Population structure** |
| Genealogical nearest neighbour (GNN)  | Population structure, relatedness and local ancestry/introgression inference | Kelleher et al., 2019 | [https://www.nature.com/articles/s41588-019-0483-y](https://www.nature.com/articles/s41588-019-0483-y)
| **Selection** |
| CLUES2  | Infer selection coefficients and infer historic allele frequencies | [Vaughn et al., 2024](https://academic.oup.com/mbe/article/41/8/msae156/7724092) | [https://github.com/avaughn271/CLUES2](https://github.com/avaughn271/CLUES2)
| SIA  | Positive selection inference | [Hejase et al., 2021](https://academic.oup.com/mbe/article/39/1/msab332/6433161) | [https://github.com/CshlSiepelLab/arg-selection](https://github.com/CshlSiepelLab/arg-selection)
| dadaSIA  | Positive selection inference | [Mo et al., 2023](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1011032) | [https://github.com/ziyimo/popgen-dom-adapt](https://github.com/ziyimo/popgen-dom-adapt)
| PALM  | Selection inference of complex traits | [Stern et al., 2021](https://www.sciencedirect.com/science/article/pii/S0002929720304419) | [https://github.com/standard-aaron/palm](https://github.com/standard-aaron/palm)
| RTH (relative TMRCA half-life)  | Detection and characterization of selective sweeps and linked selection | [Rasmussen et al., 2014](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1004342) | 
| **Demographic inference** |
| gLike  | Demographic history inference | [Fan et al., 2025](https://www.nature.com/articles/s41588-025-02129-x) | [https://github.com/Ephraim-usc/glike](https://github.com/Ephraim-usc/glike)
| mrpast  | Demographic history inference | [DeHaas et al., 2025](https://www.biorxiv.org/content/10.1101/2025.10.07.680347v1) | [https://github.com/aprilweilab/mrpast](https://github.com/aprilweilab/mrpast)
| SCAR  | Recombination and migration rate inference | [Guo et al., 2022](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010422) | [https://github.com/sunnyfangfangguo/SCAR_project_repo](https://github.com/sunnyfangfangguo/SCAR_project_repo)
| coaldecoder  | Joint inference of time varying asymetric migration and effective population sizes | [Pope & al., 2023](https://www.pnas.org/doi/10.1073/pnas.2208116120) | [https://github.com/nspope/coaldecoder](https://github.com/nspope/coaldecoder)
| rCCR (relative cross-coalescence rate)  | Population divergence, split-time and gene-flow inference | [Schiffels & Durbin, 2014](https://www.nature.com/articles/ng.3015) | 
| **Spatial ARGs** |
| spacetrees  | Dispersal rate and genetic ancestors location inference | [Osmond & Coop, 2024](https://elifesciences.org/articles/72177) | [https://github.com/osmond-lab/spacetrees](https://github.com/osmond-lab/spacetrees)
| **Admixture and introgression** |
| Twigstats  | f-statistics inference | [Speidel et al., 2025](https://www.nature.com/articles/s41586-024-08275-2) | [https://github.com/leospeidel/twigstats](https://github.com/leospeidel/twigstats)
| Topology weighting / Twisst  | Introgression, incomplete lineage sorting and genomic variation in genealogical topology| [Martin, 2026](https://academic.oup.com/genetics/article/232/1/iyaf181/8248911) | [https://academic.oup.com/genetics/article/232/1/iyaf181/8248911](https://academic.oup.com/genetics/article/232/1/iyaf181/8248911)
| **Genome architecture** |
| TRACE  | Archaic introgression inference | [Zhang et al., 2026](https://www.science.org/doi/10.1126/science.aef8874) | [https://github.com/YulinZhang9806/trace](https://github.com/YulinZhang9806/trace)
| **ARG Correction** |
| TRAMA  | Tandem repeat mutation processes inference | [Fernandez-Luna et al., 2026](https://www.biorxiv.org/content/10.64898/2026.01.21.700917v2) | 
| POLEGON  | Recalibration ARG branch lengths | [Deng et al., 2025](https://www.pnas.org/doi/10.1073/pnas.2504461122) | [https://github.com/YunDeng98/POLEGON](https://github.com/YunDeng98/POLEGON)
