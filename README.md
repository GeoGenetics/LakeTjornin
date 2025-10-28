# LakeTjornin

## This repo is the documentation following the Environmental DNA Reveals Reykjavík’s Human and Ecological History preprint

**Please cite** 

Environmental DNA Reveals Reykjavík’s Human and Ecological History 

Kurt H. Kjær, Anthony H. Ruter, Mateu Menendez-Serra, Nicola A. Vogel, Abigail D. Ramsøe, Wesley R. Farnsworth, Marie-Louise Siggaard-Andersen, Zihao Huang, Thorfinn S. Korneliussen, Karina K. Sand, Ana Prohaska, Lasse Vinner, Jesper Stenderup, Martin Sikora, Ólafur Ingólfsson, Bjarni F. Einarsson, Egill Erlendsson, Jesper Petersen, Peter C. Ilsøe, Esther R. Guðmundsdóttir, Arni Einarsson, Jón Eríksson, AEGIS Consortium, Frederikke M. Sønderborg, Ladislav Hamerlik, Scott J. Riddell, Orri Vésteinsson, Lars Wörmer, Katherine Richardson, Nicolaj K. Larsen, Ainara Sistiaga, Christoph Dockter, Morten E. Jørgensen, Robbie Waugh, Miriam Schreiber, Joanne R. Russell, Pete E. Hedley, Micha Bayer, Malcolm Macaulay, Sidsel B. Schmidt, Ronja Wonneberger, Yu Guo, Marina P. Marone, Erwang Chen, Axel Himmelbach, Martin Mascher, Nils Stein, Haoran Dong, Yuanyang Cai, Ruairidh Macleod, Lucas P. P. Braga, Chai Hao Chiu, Astrid K. N. Iversen, Michael K. Borregaard, Guðrún Þ. Larsen, Skafti Brynjolfsson, Árni D. Júlíusson, Ralph Fyfe, Laura Scoble, Max Ramsøe, Richard Durbin, Rasmus Nielsen, Yucheng Wang, Mikkel W. Pedersen, Antonio Fernandez-Guerra, David J. Meltzer, Eske Willerslev
bioRxiv 2025.10.08.681091; doi: https://doi.org/10.1101/2025.10.08.681091

We here document the computational and analytical workflows supporting the preprint: from raw sequence data through bioinformatic processing, statistical analyses, visualisations, and interpretation. The pipeline is designed to be transparent, reproducible, and modular. The analysis consists of a series of different workflows in which the link to the respective commit versions can be found below.

Overall the analysis can be split into:
1. Raw read trimming, QC, deduplication, mapping, taxonomic profiling and DNA damage estimation using Holi **LINK**
2. Taxonomic refinement, DNA Age/Damage models, filtering, and visualization **BUTTERFLY**
3. Haplogroup determination using phylogenetic placement **ZIHAO/YUCHENG**
4. Microbial profiling, DNA damage estimation, taxonomic refinement and filtering, functional profiling... **MATEU**
5. Metagenomic barcode analysis: https://github.com/nicolaavogel/meta_barcode_analysis/tree/fc9b515c635e932777a79414a2b4f56eef78fa02
6. Taxonomic overmatching analysis for Rosaceae and Poaceae taxa: **NICOLA**
